# 贡献指南 / Contributing

欢迎提交新的 Jev 用法案例或开源项目。PRs adding new Jev usage cases or open-source projects are welcome.

## 提交什么 / What to add

**案例（Case）**
- 一条真实可访问的来源链接（X / 博客 / 论坛 / 论文等，全网不限）+ 内容截图（放 `images/`，编号顺延，如 `68.png`）+ 作者 @handle + 所属场景（9 大场景之一）+ 一句话摘要。

**开源项目（Project）**
- 项目名 + GitHub 链接 + stars + 语言。

> 评分（`jev_score` / `jev_highlight`）由维护者用 Jev 统一打，无需提交。

## 改四个文件 / Update these 4 files

1. `references/index.json` — 追加一条，字段照抄现有条目（案例 `idx` 顺延）
2. `images/` — 案例的截图
3. `README.md` — 对应场景分组末尾追加，格式照抄现有条目
4. `README_EN.md` — 同步英文条目

## 流程 / Process

1. Fork → 新分支 `feat/<name>` → 改上面 4 个文件 → 开 PR
2. PR 1–2 天内 review

截图版权归原作者，请确认有权转载作索引。
