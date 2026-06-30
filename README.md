# codex-custom-instructions
这是一套用于 Codex / AI 编码助手的自定义指令总结，主要参考和整理了网上一些较成熟的 AI coding workflow 思路，并结合我自己的使用体验进行了归纳。

整体风格偏向 Karpathy-style：先理解问题，再进行最小化实现；少做假设，少写不必要的抽象；尽量通过测试、运行结果或明确的成功标准来验证修改是否正确。

这套准则的目标不是让 AI 写更多代码，而是让 AI 在编码任务中更加谨慎、可控、可验证，减少常见的 LLM 编码问题，例如：

- 未确认需求就直接实现
- 过度设计和过度抽象
- 修改无关代码
- 擅自重构已有逻辑
- 没有测试或验证就声称完成
- 隐藏不确定性或错误假设

适合用于 Codex、ChatGPT、Claude Code、Cursor、GitHub Copilot Chat 等 AI 编码工具的自定义指令。
