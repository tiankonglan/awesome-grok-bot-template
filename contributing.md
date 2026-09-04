# Contribution Guidelines · 贡献指南

Thanks for helping curate Grok Bot templates. Please read this before opening a pull request. / 感谢帮忙整理 Grok Bot 模板。提交 pull request 前请先读完本页。

The README is bilingual (English + Chinese). New entries need both descriptions. / README 为中英双语。新条目需同时提供英文和中文描述。

## Inclusion criteria · 收录标准

- The Bot must be publicly installable at a `https://x.ai/bot/<id>` URL. / Bot 必须可通过 `https://x.ai/bot/<id>` 公开安装。
- The Bot should be useful to more than its author: a clear role, a real workflow, or a template others can adopt. / 应对他人有用：角色清晰、流程真实，或可被采用的模板。
- Do not invent Bot IDs or placeholder links. Copy the ID from the public Bot page. / 不要编造 Bot ID 或占位链接。从公开 Bot 页面复制 ID。
- Search the list first. Duplicate IDs will be rejected. / 先搜索列表。重复 ID 会被拒绝。
- One pull request per addition or change, unless you are fixing formatting across the list. / 每次只提交一项增改，除非是全表格式修正。
- New categories or recategorization belong in a separate pull request. / 新分类或重新归类请单独开 PR。
- Keep names such as 赛博小晚 and AI 视频专家 as given. / 赛博小晚、AI 视频专家等已有中文名保持原样。

## Entry format · 条目格式

Use this exact line shape (English first, then Chinese): / 使用以下行格式（先英文，后中文）：

```md
- [Name](https://x.ai/bot/ID) - English description. / 中文描述。
```

Rules:

- The English description starts with a capital letter and ends with a period. / 英文描述首字母大写，以英文句号结尾。
- The Chinese description ends with a full-width period (`。`). / 中文描述以全角句号 `。` 结尾。
- Keep both sides to one short sentence. No marketing taglines. / 中英文都保持一句、简短，不要营销口号。
- Do not wrap lines in the list. / 列表条目不要硬换行。
- Add new entries at the bottom of the matching category. / 新条目加在对应分类末尾。
- Authors are optional. If you include one, put it in the description; do not change the `Name + link + EN / ZH` shape. / 作者可选。如需注明，写进描述，不要改变「名称 + 链接 + 中英描述」结构。

Example:

```md
- [Loops](https://x.ai/bot/Ub3T7usX-c6yRQibQq83P) - Engineering outer loop; verifiable goals with Cursor/GitHub. / 工程外循环；用 Cursor/GitHub 做可验证目标。
```

## Categories · 分类

Place the entry in the closest existing section: / 放入最接近的现有分类：

- Frequently Mentioned / Highly Circulated · 高频提及
- Engineering / Product / Design · 工程 / 产品 / 设计
- Research / Sales / Growth · 研究 / 销售 / 增长
- Content / Creative / Multimedia · 内容 / 创意 / 多媒体
- Assistants / Life / Finance · 助手 / 生活 / 财务

## Starting set · 起步组合

Do not recommend installing the whole list. A sensible default is 1 Chief of Staff + 1 Bouncer + 2–3 role templates. / 不要建议一次装完全表。合理默认是 1 个 Chief of Staff + 1 个 Bouncer + 2–3 个角色模板。

## Pull request checklist · 检查清单

- [ ] I searched for duplicates (same Bot ID). / 已搜索，无重复 Bot ID。
- [ ] The link is `https://x.ai/bot/<id>` and the ID is unchanged. / 链接为 `https://x.ai/bot/<id>`，ID 未改动。
- [ ] The line matches `- [Name](https://x.ai/bot/ID) - English description. / 中文描述。`
- [ ] The English description ends with `.` and the Chinese description ends with `。`. / 英文以 `.` 结尾，中文以 `。` 结尾。
- [ ] The entry is in the right category, at the bottom of that section. / 已放在正确分类的末尾。

## Updating your pull request · 更新 PR

If a maintainer asks for edits, update the same pull request rather than opening a new one. / 维护者要求修改时，请更新同一 PR，不要另开。
