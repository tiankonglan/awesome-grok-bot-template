# Contribution Guidelines

Thanks for helping curate Grok Bot templates. Please read this before opening a pull request.

The list lives in two files: English [`README.md`](README.md) and Chinese [`README.zh-CN.md`](README.zh-CN.md). Add the same Bot to both. Each file is a single language — do not put English and Chinese on the same bullet.

## Inclusion criteria

- The Bot must be publicly installable at a `https://x.ai/bot/<id>` URL.
- The Bot should be useful to more than its author: a clear role, a real workflow, or a template others can adopt.
- Do not invent Bot IDs or placeholder links. Copy the ID from the public Bot page.
- Search the list first. Duplicate IDs will be rejected.
- One pull request per addition or change, unless you are fixing formatting across the list.
- New categories or recategorization belong in a separate pull request.
- Keep names such as 赛博小晚 and AI 视频专家 as given.

## Entry format

Use this exact line shape in **each** README (one language per file):

```md
- [Name](https://x.ai/bot/ID) - Description.
```

Rules:

- English descriptions start with a capital letter and end with a period (`.`).
- Chinese descriptions end with a full-width period (`。`).
- Keep each description to one short sentence. No marketing taglines.
- Do not wrap lines in the list.
- Add new entries at the bottom of the matching category in both files.
- Authors are optional. If you include one, put it in the description; do not change the `Name + link + description` shape.

Examples:

```md
- [Loops](https://x.ai/bot/Ub3T7usX-c6yRQibQq83P) - Engineering outer loop; verifiable goals with Cursor/GitHub.
```

```md
- [Loops](https://x.ai/bot/Ub3T7usX-c6yRQibQq83P) - 工程外循环；用 Cursor/GitHub 做可验证目标。
```

## Categories

Place the entry in the closest existing section:

| English | 中文 |
| --- | --- |
| Frequently Mentioned / Highly Circulated | 高频提及 |
| Engineering / Product / Design | 工程 / 产品 / 设计 |
| Research / Sales / Growth | 研究 / 销售 / 增长 |
| Content / Creative / Multimedia | 内容 / 创意 / 多媒体 |
| Assistants / Life / Finance | 助手 / 生活 / 财务 |

## Starting set

Do not recommend installing the whole list. A sensible default is 1 Chief of Staff + 1 Bouncer + 2–3 role templates.

## Pull request checklist

- [ ] I searched for duplicates (same Bot ID).
- [ ] The link is `https://x.ai/bot/<id>` and the ID is unchanged.
- [ ] I added the Bot to both `README.md` and `README.zh-CN.md`.
- [ ] Each line matches `- [Name](https://x.ai/bot/ID) - Description.`
- [ ] English ends with `.` and Chinese ends with `。`.
- [ ] The entry is in the right category, at the bottom of that section.

## Updating your pull request

If a maintainer asks for edits, update the same pull request rather than opening a new one.
