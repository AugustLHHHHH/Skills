# Skills

A collection of reusable Codex skills.

## Available skills

### English Expression Coach

[English Expression Coach](english-expression-coach/SKILL.md) turns everyday and workplace Chinese-to-English attempts into clear, idiomatic expressions while preserving the user's original wording in a durable learning notebook.

It can:

- Lead with a natural English correction instead of a long grammar lecture.
- Preserve the Chinese intent and the user's first English attempt.
- Maintain a Markdown correction notebook with continuous entry numbering.
- Generate a responsive, self-contained visual notebook with before/after comparisons, correction categories, and revision history.
- Optionally support a recurring review reminder in the user's own timezone.

The skill uses portable relative paths and does not include personal learning records, screenshots, local reminders, or machine-specific paths.

## Installation

Copy the skill folder into your Codex skills directory:

```text
$CODEX_HOME/skills/english-expression-coach/
```

If `CODEX_HOME` is not set, the default is usually:

```text
~/.codex/skills/english-expression-coach/
```

The folder should contain:

```text
english-expression-coach/
└── SKILL.md
```

## Usage

Invoke the skill explicitly:

```text
$english-expression-coach
```

Then provide the intended Chinese meaning and your English attempt. The skill guides Codex through the correction, notebook update, and visual page generation workflow.

## Repository scope

This repository should contain reusable skill instructions and sanitized examples only. Keep personal notebooks, private screenshots, credentials, and local configuration outside the public repository.
