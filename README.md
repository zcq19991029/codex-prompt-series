# Prompt 系列

面向 Codex、Claude Code 和其他代码智能体的可复用项目协作 Prompt。

这个仓库不保存某个具体项目的代码，而是保存可以复制到新聊天窗口使用的工作模板。每个 Prompt 都尽量说明适用场景、输入信息、执行顺序、文档要求和验收标准。

## 目录

| 目录 | 内容 |
|---|---|
| `prompts/` | 可直接复制使用的 Prompt |
| `examples/` | 使用示例和填好的参考案例 |
| `templates/` | README、项目交接和贡献模板 |
| `CHANGELOG.md` | 版本和内容变更记录 |

## 当前 Prompt

- [新建大型项目初始化](prompts/new-large-project.md)：为全新大型项目建立目录、README、项目交接和可选 Skill 架构。
- [长期项目文档重建](prompts/project-documentation-refresh.md)：从实际代码、配置和历史资料中恢复完整 README 与当前交接状态。

## 使用方式

1. 打开目标项目或准备创建项目的聊天窗口。
2. 复制对应 Prompt。
3. 填写项目名称、目标和路径等占位信息。
4. 让智能体先分析和建立文档，再开始实现代码。

Prompt 是工作模板，不替代项目自身的 `AGENTS.md`、`README.md` 或测试结果。使用时仍应核对实际文件。

## 添加新 Prompt

新增 Prompt 时：

- 使用小写英文文件名和清楚的短横线命名，例如 `release-checklist.md`。
- 在文件开头写明用途、适用场景和不适用场景。
- 使用占位符表示需要用户填写的信息。
- 写清楚输出物、验证方式和失败时如何报告。
- 在本 README 的“当前 Prompt”表中登记。
- 在 `CHANGELOG.md` 记录变更。

## 许可

MIT License
