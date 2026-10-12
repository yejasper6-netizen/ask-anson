# Ask Anson 来源与适配说明

核对日期：2026-10-13（Asia/Shanghai）。

- 用户提供的抖音短链接：https://v.douyin.com/lV6KqogprrM/
- 重定向后原帖：https://www.douyin.com/note/7676403117654641926
- 作者：数字生命卡兹克。抖音页面显示发布时间 2026-08-21 16:44:44，说明明确列出十二条提示词和五类场景。该页面的图像区域未加载，本次未验证图片总数或逐张图片内容。
- 作者公开的 X 文章：https://x.com/Khazix0918/status/2090726395035156964
- 文章标题：《都Agent时代了，我还是想分享给你这12个我最常用的Prompt。》X 元数据发布时间为 2026-08-21 09:03:11 UTC。通过 x-post-archiver 的 FxTwitter 读取路径获得 Article 正文；正文包含十二个独立 markdown 提示词块，已核对全部方法。文章内三张插图与抖音图卡数量不是同一件事。
- 社区整理参考：https://github.com/hskelp9527-pixel/twelve-prompts 。用于发现原文和交叉核对方法名称，未安装或执行该仓库的代码。
- Ask Matt 入口只作调用方式参考。本 Skill 内部可按用户要求选择参考方法并执行，无需再让用户逐个调用方法。

## 对照清单

| 场景 | 作者原文方法 | 本 Skill 文件 |
| --- | --- | --- |
| 问清问题 | 苏格拉底式提问 | 01-socratic-questioning.md |
| 学习 | 双层解释法 | 02-dual-layer-explain.md |
| 学习 | 反向拆解 | 03-reverse-teardown.md |
| 学习 | 横纵分析法 | 04-cross-axis-research.md |
| 学习 | 事实核查 | 05-fact-check.md |
| 解决问题 | 专家会诊 | 06-expert-panel.md |
| 解决问题 | 第一性原理 | 07-first-principles.md |
| 解决问题 | 跨领域借解 | 08-cross-domain-borrow.md |
| 决策 | 双向钢人论证 | 09-steelman-both-sides.md |
| 决策 | 用最小实验替代空想 | 10-minimum-experiment.md |
| 认识自己 | 挖掘隐藏天赋 | 11-hidden-talent.md |
| 认识自己 | 人生设计术 | 12-life-design.md |

## 执行适配

首批十二种方法的场景整理参考卡兹克文章，不主张其经典思想由本项目或文章作者首次发明。参考文件是重新编写的操作指令，保留方法目标和重要互动节奏，没有逐字复制全部原文。调整包括：取消固定长篇幅，输入由已有上下文补齐，选法后直接开始，真实事实核查提供出处，专家会诊明确为模型内多视角，访谈支持提前总结。

新增六个入口补充数量估算、计划风险、系统瓶颈、多准则比较、情境辨识和事后学习。入口按任务阶段与主要阻碍选法，明确相近方法的分界；具体执行指令及这些路由设计由本项目独立编写。名称 Ask Anson 是项目品牌，不表示经典方法的发明归属。

用户主动调用 Skill 后，内部自动按需选法。`allow_implicit_invocation: false` 防止普通聊天隐式启动该套方法。

## 新增方法的公开来源

以下来源在 2026-10-13 由本次研究团队打开核对。机构提供具体方法说明不意味着它是所有相关思想的唯一原创者。

| 编号 | 新入口 | 一手来源与核对范围 |
| --- | --- | --- |
| 13 | 失败预演 | Gary Klein 的 [作者介绍](https://www.gary-klein.com/premortem)、其官网链接的 [ShadowBox 步骤说明](https://www.shadowboxtraining.com/services/pre-mortem/)。HBR [Performing a Project Premortem](https://hbr.org/2007/09/performing-a-project-premortem) 仅读取公开摘要与开头，不声称读到全文。 |
| 14 | 约束理论 | Theory of Constraints Institute [Five Focusing Steps](https://www.tocinstitute.org/five-focusing-steps.html)，并参照 TOCICO 的 [Goldratt 演讲介绍](https://learningcenter.tocico.org/courses/what-s-is-different-about-toc)。 |
| 15 | 费米估算 | Sanjoy Mahajan，MIT OpenCourseWare，The Art of Approximation in Science and Engineering，Spring 2008。已读取 [Tree Representations](https://ocw.mit.edu/courses/6-055j-the-art-of-approximation-in-science-and-engineering-spring-2008/resources/feb08a/) 和 [Oil Imports](https://ocw.mit.edu/courses/6-055j-the-art-of-approximation-in-science-and-engineering-spring-2008/resources/feb08b/) 的课程 PDF。 |
| 16 | 多准则权衡 | NASA Systems Engineering Handbook [6.8 Decision Analysis](https://www.nasa.gov/reference/6-8-decision-analysis/) 和 [4.4 Design Solution Definition](https://www.nasa.gov/reference/4-4-design-solution-definition/)。 |
| 17 | Cynefin 情境辨识 | Dave Snowden [Cynefin St David's 2021](https://thecynefin.co/cynefin-st-davids-day-2021-1-of-3/) 及官方知识库 [Cynefin Domains](https://cynefin.io/wiki/Cynefin_Domains)。此入口是决策支持框架的适配，不称作固定五步方法。 |
| 18 | 行动后复盘 | 美国陆军 Training Management Directorate，2025-02-20，[TC 7-0.1 官方介绍](https://www.army.mil/article/283214/)；Center for Army Lessons Learned，[Home-Station Training Handbook，Jul 2025](https://api.army.mil/e2/c/downloads/2025/07/25/5ffd4949/no-25-761-home-station-training-handbook-jul-25.pdf)。TC 官方直链抓取超时，不声称已读其全文。 |

## 新入口与原有方法的关系

- 13 对已选计划生成候选失败路径，09 用于比较两个方向；预设失败不意味着预测失败。
- 14 找限制相依流程整体产出的约束，07 重审基本假设；局部耗时长不直接证明系统瓶颈。
- 15 必须形成带单位和假设的数量级，05 核查现有陈述；估算不等于事实。
- 16 处理多个选项、硬门槛与多项准则，09 展开两个方向的最强论点；评分不能覆盖硬门槛。
- 17 判断何种响应方式适合当前情境，10 验证一个可明确表述的关键假设；复杂情境允许多种探查。
- 18 对照真实行动前后的记录，03 从已有成品学习结构；写完复盘不证明改进已经实现。

## 访问边界

按用户要求尝试豆包网页，重载后进入 `/security/doubao-region-ban?source=1`，未能在豆包提交链接或取得回答。未更改代理或网络设置。通过抖音原帖文字与作者 X 正文完成方法核对，不声称豆包成功读图，也不声称完成抖音图卡的逐张 OCR。
