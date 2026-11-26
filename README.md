# Skills

Reusable Codex skills.  
可复用的 Codex Skill 集合。

## English Expression Coach / 英语表达教练

Turn Chinese thoughts and imperfect English attempts into natural, reusable expressions for everyday and workplace communication. The skill preserves the original attempt, explains key corrections, and builds a structured learning record.

将中文想法和不够自然的英文表达改写为清晰、地道、可复用的表达；保留原始答案，解释关键修改，并沉淀为结构化学习笔记。

### Capabilities / 能力

- **Natural correction / 自然改写** — Recommend natural English first, then explain the key changes.  
  先给出自然表达，再解释关键修改。
- **Context-aware / 场景适配** — Offer suitable everyday, conversational, or workplace versions.  
  根据日常、口语或职场场景提供合适版本。
- **Learning record / 学习记录** — Keep the Chinese intent, first attempt, revisions, and next-time focus.  
  记录中文意图、首次表达、修订历史和下次练习重点。
- **Visual notebook / 可视化笔记** — Generate a responsive static page with before/after comparisons and correction categories.  
  生成响应式静态页面，展示前后对比和错误类别。
- **Optional review reminder / 可选复习提醒** — Create a recurring review task in the user's own timezone when requested.  
  需要时按用户所在时区创建周期复习提醒。

The skill uses portable workspace-relative paths and contains no personal learning records, screenshots, reminders, or machine-specific settings.

该 Skill 使用可移植的工作区相对路径，不包含个人学习记录、截图、提醒或特定电脑配置。

## Installation / 安装

Copy `english-expression-coach/` into your Codex skills directory:  
将 `english-expression-coach/` 复制到 Codex Skills 目录：

```text
$CODEX_HOME/skills/
```

If `CODEX_HOME` is unset, use `~/.codex/skills/`.  
如果未设置 `CODEX_HOME`，通常使用 `~/.codex/skills/`。

## Usage / 使用

```text
$english-expression-coach
```

Provide the intended Chinese meaning and your English attempt. The skill will correct the expression, explain the important changes, and update the learning notebook when requested.

提供中文意图和你的英文表达。Skill 会完成纠错、解释关键修改，并在需要时更新学习笔记。
