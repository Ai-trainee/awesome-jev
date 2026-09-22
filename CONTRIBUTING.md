# 贡献指南 / Contributing

欢迎补充新的 Jev 用法案例！/ PRs adding new Jev usage cases are welcome.

## 提交要求 / What to include

中文：
- 必须提供一条**真实可访问**的 X（Twitter）帖子链接；
- 必须附一张原帖截图，放到 `images/` 目录，文件名按现有编号顺延（`68.png`、`69.png` …）；
- 在 PR 说明里注明：原帖作者（@handle）、所属场景（建议从 README 已有 9 大场景中选择）、一句话中文摘要；
- 不要修改已有条目的 title / author / url / jev_score，评分由维护者统一处理。

English:
- You must include a **real, publicly accessible** X (Twitter) post URL;
- Attach one screenshot of the original post under `images/`, named with the next free two-digit index (`68.png`, `69.png`, …);
- In the PR description, list: original author (@handle), which of the 9 existing scenes it belongs to, and a one-line English/Chinese summary;
- Do not edit existing entries' title / author / url / jev_score — scoring is done by maintainers.

## 仓库结构 / Repository structure

- `README.md` / `README_EN.md`：条目清单本体，按 9 大场景分组；
- `images/`：原帖截图索引，按两位编号命名（`00.png`、`01.png` …）；
- `skill/`：本仓库作为「JEV 用法参考库」被模型 / Agent 加载的入口。`skill/SKILL.md` 定义了 Agent 如何读取本仓库、按 9 大场景索引定位案例，并引用 `images/` 截图与原始 X 链接为用户生成玩法建议。

**新增案例时**：
- 若只是在**已有 9 大场景**下追加条目，请把新条目的编号（idx）补进 `skill/SKILL.md` 中「按场景的索引提示 / Index by scene」对应场景的 idx 列表；
- 若新案例属于一个**现有 9 大场景装不下的全新场景**，请在追加 README 条目的同时，在 `skill/SKILL.md` 的索引一节新增该场景及其条目编号，保持 Agent 可检索到。

English:
- `README.md` / `README_EN.md`: the entry list itself, grouped into 9 scenes;
- `images/`: original-post screenshots indexed by two-digit number (`00.png`, `01.png`, …);
- `skill/`: the entry point through which models/agents load this repo as a "JEV usage reference library". `skill/SKILL.md` defines how an agent reads the repo, locates cases by the 9-scene index, and references the `images/` screenshots and original X links to suggest usage patterns.

**When adding a case:**
- If it only extends one of the **existing 9 scenes**, append the new entry's idx to that scene's list in the "Index by scene" section of `skill/SKILL.md`;
- If it belongs to a **brand-new scene** that none of the existing 9 covers, add that scene together with its entry idx to `skill/SKILL.md` at the same time, so agents can still find it.

## 流程 / Process

本仓库含两个 README：`README.md`（中文默认）与 `README_EN.md`（英文）；新增条目时请同步更新两个文件。
This repo ships two READMEs: `README.md` (Chinese default) and `README_EN.md` (English); please keep both in sync when adding entries.

1. Fork 本仓库 / fork this repo；
2. 新建分支 `feat/case-<short-name>`；
3. 添加截图 + 在 `README.md` 对应 scene 分组末尾追加一条目（格式照抄现有条目）；
4. 开 PR，说明新增了哪几条、为什么值得收录。

PR 会在 1–2 天内 review。截图版权归原发帖人，请确认你有权转载作为索引使用。
