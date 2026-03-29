# Skill Generator

一个用于生成 **Anthropic-compatible Skills** 的工具。

## 功能

根据输入的能力描述，自动生成符合 Anthropic 规范的标准 `SKILL.md` 文件，包括：

- YAML frontmatter 元数据
- 使用指导和示例
- 清晰的职责边界定义

## 使用方式

在 Claude Code 中使用 `/skill` 命令调用，或向 AI 描述你想要创建的 Skill 能力。

## 相关资源

- [Anthropic Skills 文档](https://docs.anthropic.com/en/docs/claude-code/skills)
- 查看 [SKILL.md](./SKILL.md) 了解本项目的定义规范