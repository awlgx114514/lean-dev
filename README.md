# lean-dev

`lean-dev` 是用于持续软件开发任务的 Codex Skill，强调根据证据定位问题、限定修改范围、运行相关验证，并交付可检查的结果。

## 文件

- `SKILL.md`：任务分级、调查、实现、验证和交付要求。
- `agents/openai.yaml`：Skill 在 Codex 中显示的名称和默认提示。

## 安装

将本目录放到 `$CODEX_HOME/skills/lean-dev`，然后在 Codex 请求中调用 `$lean-dev`。
