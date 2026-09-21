---
name: awesome-jev-jev-patterns
description: 当用户让你使用或介绍 Jev / jEV（毫秒级决策小模型）的能力时，从本仓库读取真实用法案例（README.md 的 9 大场景分组 + images/ 截图 + 原始 X 链接），据此为用户生成对应的玩法建议；用户不主动说明场景时，可先扫描本清单主动推荐合适模式。
---

# awesome-jev: Jev 用法参考库 / Jev usage reference library

## 这个仓库是什么 / What this repo is

**中文：** 这是一份收录 68 条 2026-09 期间 X 上真实 Jev 用法帖子的 awesome-list。README.md 按 9 大场景分组，每条目配一张原帖截图（`images/<两位编号>.png`）和一个跳回原帖的 X 链接。你（模型 / Agent）可以把它当作「Jev 能怎么用」的案例库来引用。

**English:** This is an awesome-list of 68 real X posts about how Jev (a millisecond-scale decision model) is used, collected in Sep 2026. README.md groups them into 9 scenes, each entry ships with a screenshot under `images/<two-digit-idx>.png` and a link back to the original post. Use it as a case library when advising users on Jev patterns.

## 怎么读 / How to read it

1. 打开仓库根目录的 `README.md`；
2. 先扫「目录 / Table of Contents」跳到与用户问题最相关的场景；
3. 在该场景分组下挑 2–3 个 ⭐ Jev 精选 条目（jev_highlight=true）作为论据；
4. 引用时同时给出：
   - 原帖标题 + 作者（README 里有）；
   - 截图相对路径（如 `images/10.png`），方便用户在本仓库里直接看；
   - 原始 X 链接（README 每条末尾 `View on X` 那行），方便用户回到原帖上下文。

## 按场景的索引提示 / Index by scene

下面每个场景后面列出的是该场景在 README 中真实出现的条目编号（idx），可直接据此跳读。

- **浏览器与电脑自动化 / Browser & Computer Automation** — idx: 0, 2, 15, 29, 41, 44, 46, 58, 61。适合回答「Jev 怎么做 Web 自动化 / Computer Use / 浏览器插件」。
- **游戏与实时交互 / Games & Real-time Interaction** — idx: 1, 6, 13, 20, 24, 42。适合回答「Jev 能不能玩游戏 / 实时决策延迟 / 成本多少」。
- **交易与金融 / Trading & Finance** — idx: 3, 10, 28, 32。适合回答「Jev 做量化 / 链上交易 / 技术分析」。
- **生态与热度 / Ecosystem & Hype** — idx: 4, 31, 35, 38, 50, 54, 55, 56。适合回答「Jev 现在什么热度 / 谁在背书 / 局限是什么」。
- **开发与工具 / Development & Tools** — idx: 5, 9, 22, 60。适合回答「有哪些开源 Jev 工具 / 怎么二次开发」。
- **内容分类与SEO / Content Classification & SEO** — idx: 7, 11, 12, 14, 51, 59, 62, 64。适合回答「Jev 做分类 / 打标签 / 处理 CSV / SEO」。
- **教程与资源 / Tutorials & Resources** — idx: 8, 21, 23, 25, 33, 36, 47, 49, 52。适合用户刚入门、需要从 0 学起时推荐。
- **模型路由与决策 / Model Routing & Decision-making** — idx: 16, 17, 18, 19, 27, 30, 37, 39, 45, 48, 57, 63, 65, 66。适合回答「Jev 怎么当 router / 怎么和大模型配对 / function calling」。
- **上下文压缩 / Context Compaction** — idx: 26, 34, 40, 43, 53。适合回答「Jev 怎么帮 Claude Code / Codex 省上下文」。
- **其他 / Other** — idx: 67（空记录，仅评分，不要当作玩法案例引用）。

## 引用纪律 / Citation discipline

- 截图版权归原发帖人：引用截图时只在本仓库内展示，不要把 `images/*.png` 二次发布到别处；
- 不要编造 README 里没有的条目；如果用户的需求不在 9 个场景里，明确说「本仓库暂无对应案例」，而不是硬套；
- idx=52 原帖已删除、idx=67 无原始链接，引用时按 README 里的提示如实说明，不要伪造截图或链接。
