<div align="center">

# Hi, I'm Liqi <img align="absmiddle" src="./assets/icons/sparkles.svg" width="26" height="26" alt="">

**简体中文** · [English](./README.en.md)

**無限進步！** 把复杂问题，变成可以验证的下一步。

<img align="absmiddle" src="./assets/icons/map-pin.svg" width="20" height="20" alt=""> Shanghai · <img align="absmiddle" src="./assets/tech/java-badge.svg" width="22" height="22" alt=""> Java · <img align="absmiddle" src="./assets/tech/go-badge.svg" width="22" height="22" alt=""> Go · <img align="absmiddle" src="./assets/tech/python-badge.svg" width="22" height="22" alt=""> Python

<img align="absmiddle" src="./assets/icons/compass.svg" width="20" height="20" alt=""> **[个人网站 →](https://liqi-liu-portfolio.wintrybow32.chatgpt.site/)** · [开源贡献](https://github.com/pulls?q=is%3Apr+author%3Aliu-657667)

</div>

---

### <img align="absmiddle" src="./assets/icons/compass.svg" width="20" height="20" alt=""> 我在做什么

我关注 Java / Go、模块化应用与云原生，也在把 AI 工作流和浏览器自动化做成实际工具。公开贡献涉及 Kubernetes 模块控制器、Go 命令行体验，以及 Spring AI / MCP 示例与可观测性。

我喜欢从具体问题出发：复现、拆解、做出一个能验证的小版本，再继续改进。

### <img align="absmiddle" src="./assets/icons/rocket.svg" width="20" height="20" alt=""> 我的项目

#### <img align="absmiddle" src="./assets/icons/app-window.svg" width="18" height="18" alt=""> [MacSoul](https://github.com/liu-657667/macsoul)

**一个有点嘴欠的 macOS 开发者伴侣。** 把系统状态、网络线索、本地开发环境和 Codex 配额集中到原生主窗口与菜单栏，再让一个小灵魂用简短反馈表达值得关注的状态。

当前公开预发布：**[v0.1.1-beta.1 · 下载与安装 →](https://github.com/liu-657667/macsoul/releases/tag/v0.1.1-beta.1)** · macOS 13+ · Universal DMG / ZIP

这一版改进了 Codex 连接协议兼容、登录时启动、公网 IP 查询回退和字体布局。主要借助 AI 编程迭代，SwiftUI 仍在学习中。Beta 未提供 Developer ID 签名或 Apple 公证；安装说明与验证范围见发布页。

#### <img align="absmiddle" src="./assets/icons/scan-search.svg" width="18" height="18" alt=""> [modao-prototype-inspector](https://github.com/liu-657667/modao-prototype-inspector)

**从一个墨刀分享链接，到结构化视觉证据。** 一个 Python / Codex skill：扫描页面树，采集页面截图和切换证据，生成会话清单，方便后续查看与分析原型。

当前支持 macOS + Chrome，导航范围为页面树。[查看用法 →](https://github.com/liu-657667/modao-prototype-inspector#readme)

### <img align="absmiddle" src="./assets/icons/git-pull-request.svg" width="20" height="20" alt=""> 开源协作

以下是我提交并已合并的部分工作；链接可直接查看具体改动。

| 项目 | 我参与的改进 |
| :--- | :--- |
| [OpenClaw](https://github.com/openclaw/openclaw) | 修复 `/think extra high` 思考级别别名解析，并补充回归测试 [#197085](https://github.com/openclaw/openclaw/pull/197085)。 |
| [SOFAStack / SOFA Serverless](https://github.com/sofastack/sofa-serverless) | Go / Kubernetes 模块控制器：模块部署行为 [#118](https://github.com/sofastack/sofa-serverless/pull/118)、Pod 模块实例统计 [#208](https://github.com/sofastack/sofa-serverless/pull/208)、分组发布幂等处理 [#406](https://github.com/sofastack/sofa-serverless/pull/406)，以及 CI 与测试改进。上游仓库已归档。 |
| [Koupleless / arkctl](https://github.com/koupleless/arkctl) | Go CLI 的错误提示 [#1](https://github.com/koupleless/arkctl/pull/1) 与默认帮助输出 [#6](https://github.com/koupleless/arkctl/pull/6)；另向 [Koupleless](https://github.com/koupleless/koupleless/pull/61) 提交了 CI 修复。 |
| [Spring AI Summary](https://github.com/java-ai-tech/spring-ai-summary) | Java / Spring AI：调用可观测性 [#28](https://github.com/java-ai-tech/spring-ai-summary/pull/28)、Nacos MCP 客户端与服务端示例 [#32](https://github.com/java-ai-tech/spring-ai-summary/pull/32)、评估器—优化器工作流 [#34](https://github.com/java-ai-tech/spring-ai-summary/pull/34)。 |

我也通过复现步骤、日志与源码线索提交问题报告：

- **OpenClaw**：钉钉引用文件消息引发的消息幂等冲突 [#177078](https://github.com/openclaw/openclaw/issues/177078)。
- **DingTalk OpenClaw Connector**：Windows 加载与运行时初始化问题 [#662](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector/issues/662)、群聊重复回复 [#669](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector/issues/669)。

[全部 PR →](https://github.com/pulls?q=is%3Apr+author%3Aliu-657667) · [问题报告 →](https://github.com/issues?q=is%3Aissue+author%3Aliu-657667)

### <img align="absmiddle" src="./assets/icons/layers.svg" width="20" height="20" alt=""> 技术方向

| 方向 | 公开项目与贡献中的实践 |
| :--- | :--- |
| **Java / Spring** | Spring AI、MCP、调用可观测性与工作流示例 |
| **Go / Kubernetes** | 模块控制器、应用部署与调度、命令行工具 |
| **Python / 自动化** | 浏览器自动化、原型检查与结构化证据采集 |

> 先把问题看清楚，再写一个可以验证的小版本；每次都比上次前进一点点。

---

<div align="center">

**欢迎交流开发工具、AI 工作流与开源项目。**

[个人网站](https://liqi-liu-portfolio.wintrybow32.chatgpt.site/) · [浏览仓库](https://github.com/liu-657667?tab=repositories) · [English](./README.en.md)

</div>
