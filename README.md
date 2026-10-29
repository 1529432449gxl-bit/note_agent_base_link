# note_agent_base_link

把 B站 / 抖音 / YouTube / 小红书 视频链接整理成 Markdown 课堂笔记的 Codex / Agent skill。

## 内容

- `note-agent-base-link/SKILL.md`：主流程（抓取 → ASR 兜底 → 截图 → v4 笔记 → 校验）
- `note-agent-base-link/scripts/`：各平台抓取、转写、术语校正、导航深链、质量门禁
- `note-agent-base-link/references/`：笔记模板、ASR 词表、截图锚点
- `note-agent-base-link/tests/`：单元测试

## 使用

把 `note-agent-base-link` 目录装到 Agent 的 skills 路径（例如 Codex 的 `~/.codex/skills/`），按 `SKILL.md` 执行。

配置示例见 `note-agent-base-link/config.example.json`。**不要提交**真实的 `config.json`、cookies 或登录态。

## 许可

见 `note-agent-base-link/LICENSE`；`scripts/abogus.py` 等第三方代码许可见仓库内说明。
