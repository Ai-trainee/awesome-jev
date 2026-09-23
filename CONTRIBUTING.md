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

- `SKILL.md`：本仓库作为「JEV 用法参考库」被模型 / Agent 加载的入口（仓库根目录即 Skill 包，Agent 扫描根目录 `SKILL.md` 即自动生效）；
- `references/index.json`：68 条案例的结构化数据（idx / title / author / url / scene / summary / jev_score / jev_highlight / jev_focus / category），是 Agent 检索与推荐的数据源；
- `images/`：原帖截图索引，按两位编号命名（`00.png`、`01.png` …），与 `references/index.json` 的 `idx` 一一对应；
- `README.md` / `README_EN.md`：条目清单本体，按 9 大场景分组，面向人类阅读。

**新增案例时必须同步更新四处**：
1. `references/index.json`：追加一条记录（字段齐全，`idx` 顺延）；
2. `images/`：放入原帖截图，文件名与新 `idx` 对齐；
3. `README.md`：在对应场景分组末尾追加条目；
4. `README_EN.md`：同步追加英文条目。
- 若新案例属于一个**现有 9 大场景装不下的全新场景**，请在 `SKILL.md` 的「9 大应用场景」清单中同步新增该场景，保持 Agent 可检索。

**开源项目精选分区维护**：
- 项目条目来源为社区 Jev 生态目录（heyjunpenn/awesome-jev）同步 + Jev 独立评分筛选；
- 新增项目时需在 `references/index.json` 追加 `type=project` 条目（含 stars/language/url），并在 README 双版「开源项目精选」分区追加对应条目；
- 项目条目无截图、无 X 链接，`url` 直接指向 GitHub 仓库。

English:
- `SKILL.md`: the entry point through which models/agents load this repo as a "JEV usage reference library" (the repo root itself is the skill package; agents that scan for root-level `SKILL.md` pick it up automatically);
- `references/index.json`: structured data for all 68 cases (idx / title / author / url / scene / summary / jev_score / jev_highlight / jev_focus / category), the data source agents search and recommend from;
- `images/`: original-post screenshots indexed by two-digit number (`00.png`, `01.png`, …), one-to-one with the `idx` field in `references/index.json`;
- `README.md` / `README_EN.md`: the entry list itself, grouped into 9 scenes, for human readers.

**When adding a case, you must update all four:**
1. `references/index.json`: append one record (all fields filled, `idx` incremented);
2. `images/`: add the original-post screenshot, filename matching the new `idx`;
3. `README.md`: append the entry at the end of the matching scene group;
4. `README_EN.md`: append the English entry in sync.
- If it belongs to a **brand-new scene** that none of the existing 9 covers, add that scene to the "9 application scenes" list in `SKILL.md` as well, so agents can still find it.

## 流程 / Process

本仓库含两个 README：`README.md`（中文默认）与 `README_EN.md`（英文）；新增条目时请同步更新两个文件。
This repo ships two READMEs: `README.md` (Chinese default) and `README_EN.md` (English); please keep both in sync when adding entries.

1. Fork 本仓库 / fork this repo；
2. 新建分支 `feat/case-<short-name>`；
3. 添加截图 + 更新 `references/index.json` + 在 `README.md` 与 `README_EN.md` 对应 scene 分组末尾各追加一条目（格式照抄现有条目）；
4. 开 PR，说明新增了哪几条、为什么值得收录。

PR 会在 1–2 天内 review。截图版权归原发帖人，请确认你有权转载作为索引使用。
