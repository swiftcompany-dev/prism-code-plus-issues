# Prism Code Plus - Issue Tracker

**Languages:** [🇺🇸 English](README.md) | [🇰🇷 한국어](README.ko.md) | [🇯🇵 日本語](README.ja.md) | [🇨🇳 中文](README.zh.md)

欢迎来到**Prism Code Plus**的公开问题跟踪器!

此仓库专门用于Prism Code Plus的错误报告、功能请求和社区讨论 - 这是一个用于Visual Studio Code的自主AI编码代理。

## 🤖 关于Prism Code Plus

Prism Code Plus是一个功能强大的VS Code扩展，将自主AI编码功能直接带入您的IDE。它支持多个AI提供商，包括:

- 🧠 **Anthropic Claude** (Sonnet 4.5, Opus 4, Haiku)
- 🔮 **Google Gemini** (2.5 Pro, 2.5 Flash)
- 💬 **OpenAI GPT** (GPT-4o, o1, o3-mini)
- 🌐 **OpenRouter** (访问200多个模型)
- 🦙 **本地模型** 通过Ollama
- ...以及更多!

### 主要功能

✨ **自主编码** - 在您的批准下创建、编辑文件并运行命令
🌍 **浏览器集成** - 抓取网页内容并研究文档
🔧 **MCP支持** - 使用模型上下文协议服务器进行扩展
⚡ **自带密钥** - 使用您自己的API密钥或我们的托管服务
🎯 **多模型支持** - 在提供商之间无缝切换
📝 **任务管理** - 内置任务跟踪和历史记录

## 📝 如何提交问题

### 选择正确的模板

我们提供**4种语言**的问题模板：英语、韩语(한국어)、日语(日本語)和中文。

创建问题时，选择与您的**问题类型**和**首选语言**都匹配的模板:

#### 问题类型

- 🐛 **错误报告** - 错误、崩溃、意外行为
- ✨ **功能请求** - 新功能或改进
- 📖 **文档** - 文档错误或改进
- ⚡ **性能** - 响应缓慢、资源使用率高
- 🎨 **UI/UX** - 界面或可用性改进

### 快速开始

1. 转到[Issues](../../issues)
2. 点击**New Issue**
3. 选择您的模板 (例如："🐛 错误报告 (中文)")
4. 填写详细信息
5. 提交!

## 📋 编写好的问题

### 对于错误报告

✅ **应该:**
- 使用错误报告模板
- 包含Prism Code Plus版本
- 指定使用的AI提供商和模型
- 提供清晰的重现步骤
- 包含相关错误消息或截图

❌ **不应该:**
- 发布敏感信息 (API密钥、凭据)
- 无正当理由跳过模板
- 报告仅在低性能模型上发生的问题

### 对于功能请求

✅ **应该:**
- 首先搜索类似请求
- 解释使用案例和好处
- 具体说明期望的行为
- 考虑实施复杂性

❌ **不应该:**
- 请求违反AI提供商条款的功能
- 重复现有请求

## 🎯 我们在这里跟踪什么

### ✅ 我们接受

- 🐛 错误报告
- ✨ 功能请求
- 📖 文档改进
- ⚡ 性能问题
- 🎨 UI/UX改进
- 🔌 MCP集成想法
- 💡 一般反馈

### ❌ 我们不接受

- 💻 拉取请求 (私有仓库)
- 🔐 安全漏洞 (私下报告 - 见下文)
- 🆘 一般支持问题 (使用[Discord](https://discord.gg/Pr9SuQJzkG))
- 📧 个人API密钥问题 (联系支持)

## 🔒 安全问题

**不要在这里发布安全漏洞!**

如果您发现安全问题，请通过以下方式私下报告:
- **Discord**: 向版主发送私信
- **Email**: security@prismcode.plus (如果可用)
- **GitHub Security Advisory** (如果启用)

## ❓ 常见问题

### 一般问题

**Q: Prism Code Plus是开源的吗?**
A: 不，Prism Code Plus是专有项目。此仓库仅是问题和社区反馈的公开跟踪器。

**Q: 我应该使用哪个AI模型进行测试?**
A: 错误报告应该能够使用**Claude Sonnet 4.5**或同等模型重现。Prism使用复杂的提示，可能在低性能模型上无法正常工作。

**Q: 我可以贡献代码吗?**
A: 由于Prism Code Plus在私有仓库中开发，我们不接受直接的代码贡献。但是，您可以通过问题报告、功能建议和文档改进来贡献。

### 关于问题

**Q: 我提交了问题但没有得到回复**
A: 问题根据影响和资源确定优先级。重要问题可以通过标签和反应(👍)获得优先级。对于紧急问题，请在[Discord](https://discord.gg/Pr9SuQJzkG)上联系我们。

**Q: 我不确定这是否是错误**
A: 如果不确定，请先在[GitHub Discussions](../../discussions)中发帖。社区或团队可以帮助确定是否是错误，并在需要时将其转换为问题。

**Q: 我发布了重复的问题**
A: 没问题! 团队会用`duplicate`标签标记它，并引导您到原始问题。请在原始问题上添加👍反应以表示您的关注。

## 💬 社区

- 💭 **GitHub Discussions**: [加入讨论](../../discussions)
- 🎮 **Discord**: [discord.gg/prism-code](https://discord.gg/Pr9SuQJzkG)
- 🌐 **网站**: [prismcode.plus](https://prismcode.plus)

## 📊 问题标签

我们使用标签来跟踪问题状态:

- 🏷️ **bug** - 已确认的错误
- 🏷️ **enhancement** - 功能请求
- 🏷️ **documentation** - 文档改进
- 🏷️ **performance** - 性能问题
- 🏷️ **ui/ux** - UI/UX改进
- 🏷️ **good first issue** - 适合新手的简单问题
- 🏷️ **help wanted** - 需要社区意见
- 🏷️ **wontfix** - 不会实施
- 🏷️ **duplicate** - 已经报告
- 🏷️ **investigating** - 调查中
- 🏷️ **in progress** - 进行中
- 🏷️ **needs more info** - 需要更多信息

## 🙏 谢谢!

您的反馈有助于让Prism Code Plus对每个人都更好。我们会阅读每个问题，并感谢您对社区的贡献!

**Built with ❤️ by the Prism Code Plus Team**

---

**注意:** 这只是公开问题跟踪器。Prism Code Plus的主要代码库是专有的。
如需支持，请访问我们的[Discord](https://discord.gg/prism-code)或[文档](https://prismcode.plus/docs)。
