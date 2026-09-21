# awesome-jev

精选围绕 Jev（毫秒级小模型执行器）的真实 X 帖子用法案例库。

A curated awesome-list of real X posts showing how Jev — a millisecond-scale small-model executor — is actually used in the wild.

![](https://img.shields.io/badge/posts-68-blue) 
![](https://img.shields.io/badge/scenes-9-7b68ee) 
![](https://img.shields.io/badge/highlights-50-gold) 
![](https://img.shields.io/badge/license-MIT-green)

📦 共 **68 条帖子** · 🗂️ 覆盖 **9 大应用场景**（另附「其他 / Other」收纳空记录）· ⭐ 标注 **50 条 Jev 精选**（jev_highlight）。

---

## Jev 是什么 / What is Jev

**中文：** Jev 是一个轻量、毫秒级的「决策/执行」小模型：它不写长文本，只在给定的选项里做带置信度的判断（是/否、选 A/B/C、点哪里）。社区普遍把它和大模型配对成「大模型推理 + 小模型执行」的 Agent 架构 —— 大模型负责想，Jev 负责快、便宜、稳定地落地每一步动作。

**English:** Jev is a lightweight, millisecond-scale *decision* model — it does not generate prose, it only picks among a small set of constrained options (yes/no, A/B/C, which button to click) with confidence. The community routinely pairs it with a big model in a "big-model reasons, small-model acts" Agent loop.

---

## 为什么有这个清单 / Why this list

**中文：** 很多人听说了 Jev 却不知道它到底能干什么。这里收录了 68 条 2026-09 期间 X 上的真实玩法 —— 浏览器自动化、游戏实时操作、链上交易、模型路由、上下文压缩、内容分类与 SEO 等 —— 每条都配了原帖截图作为快速索引，点链接可跳回作者原帖。截图版权归原发帖人所有，本仓库仅作索引与学习用途。

**English:** Plenty of people have heard of Jev but don't know what to do with it. This list collects 68 real X posts from Sep 2026 — browser automation, real-time game play, on-chain trading, model routing, context compaction, content classification & SEO, and more — each with a screenshot as a quick index and a link back to the original author. All screenshots belong to their original posters; this repo is an index for learning only.

---

## 目录 / Table of Contents

- [浏览器与电脑自动化 / Browser & Computer Automation](#browser--computer-automation)（9）
- [游戏与实时交互 / Games & Real-time Interaction](#games--real-time-interaction)（6）
- [交易与金融 / Trading & Finance](#trading--finance)（4）
- [生态与热度 / Ecosystem & Hype](#ecosystem--hype)（8）
- [开发与工具 / Development & Tools](#development--tools)（4）
- [内容分类与SEO / Content Classification & SEO](#content-classification--seo)（8）
- [教程与资源 / Tutorials & Resources](#tutorials--resources)（9）
- [模型路由与决策 / Model Routing & Decision-making](#model-routing--decision-making)（14）
- [上下文压缩 / Context Compaction](#context-compaction)（5）
- [其他 / Other](#other)（1）

---

## 浏览器与电脑自动化 / Browser & Computer Automation

- **Breaking: Browser Use + Jev = 超快速浏览器代理！7秒完成成本仅$0.0039，开源** — Gregor Zunic (gregpr07) · Jev 评分 84 · 成本与性能 · ⭐ Jev 精选

  ![](images/00.png)

  [🔗 在 X 上查看 / View on X](https://x.com/gregpr07/status/2100411066966749359)

- **Jev + Computer use = 比任何LLM快100倍，眨个眼就错过** — sav (savboj) · Jev 评分 56 · 成本与性能 · ⭐ Jev 精选

  ![](images/02.png)

  [🔗 在 X 上查看 / View on X](https://x.com/savboj/status/2100545295201288678)

- **agent-browser + Jev 玩 Wiki Race：浏览器自动化合理用例（182赞）** — joogie (princecaarlo) · Jev 评分 48 · 工具与产品

  ![](images/15.png)

  [🔗 在 X 上查看 / View on X](https://x.com/princecaarlo/status/2100313645116952701)

- **Jev 做 Chrome 扩展：实时检测 YouTube 赞助片段并跳过，每视频$0.005（453赞）** — Tony Dinh (tdinh_me) · Jev 评分 77 · 工具与产品 · ⭐ Jev 精选

  ![](images/29.png)

  [🔗 在 X 上查看 / View on X](https://x.com/tdinh_me/status/2100793777103466615)

- **Browser Use 接 JEV 速度吓人：网页操作本质是离散多选题，不需要 AI 写诗（1190赞）** — 梭哈.AI (SUOHA_AI) · Jev 评分 80 · 架构与方法 · ⭐ Jev 精选

  ![](images/41.png)

  [🔗 在 X 上查看 / View on X](https://x.com/SUOHA_AI/status/2100628846240264348)

- **Web Agent 航空券搜索 7 秒完成，成本仅 $0.0039：从慢且贵到快且便宜（28赞）** — KANA｜東京AI映像 (KanaWorks_AI) · Jev 评分 43 · 成本与性能

  ![](images/44.png)

  [🔗 在 X 上查看 / View on X](https://x.com/KanaWorks_AI/status/2100783766193246394)

- **有人用 Jev 做了自动驾驶原型：一小时内完成完整驾驶决策循环（43赞）** — Mikadzyki (Mikadzyki_NFT) · Jev 评分 58 · 工具与产品 · ⭐ Jev 精选

  ![](images/46.png)

  [🔗 在 X 上查看 / View on X](https://x.com/Mikadzyki_NFT/status/2100950578113232992)

- **SAM 3.1 × Jev：完全自立型 ComputerUse、高速人脸认证（914赞）** — StudioYebisu (studio_yebisu) · Jev 评分 80 · 架构与方法 · ⭐ Jev 精选

  ![](images/58.png)

  [🔗 在 X 上查看 / View on X](https://x.com/studio_yebisu/status/2101003307200430126)

- **Jev 语音操控电脑比键鼠还快：Alan Daitch 实测（102赞）** — @AlanDaitch · Jev 评分 57 · 成本与性能 · ⭐ Jev 精选

  ![](images/61.png)

  [🔗 在 X 上查看 / View on X](https://x.com/AlanDaitch/status/2101090570110169547)

---

## 游戏与实时交互 / Games & Real-time Interaction

- **Jev + Astra 玩吃豆人：Astra 制定策略，Jev 毫秒级执行，大模型+小模型协作架构** — Dan McAteer (daniel_mac8) · Jev 评分 61 · 架构与方法 · ⭐ Jev 精选

  ![](images/01.png)

  [🔗 在 X 上查看 / View on X](https://x.com/daniel_mac8/status/2100335929273524541)

- **Jev V13 vs Fable 5.1 vs GPT-6 Astra 下棋：Jev 不是LLM，只做决策（2098赞）** — AI/ML API (aimlapi) · Jev 评分 86 · 架构与方法 · ⭐ Jev 精选

  ![](images/06.png)

  [🔗 在 X 上查看 / View on X](https://x.com/aimlapi/status/2100372930282573876)

- **陈成让 Jev 玩贪吃蛇：200个请求 $0.02，1美元能走一万步（246赞）** — 陈成 (chenchengpro) · Jev 评分 47 · 成本与性能

  ![](images/13.png)

  [🔗 在 X 上查看 / View on X](https://x.com/chenchengpro/status/2100516953496670430)

- **Jev 玩宝可梦：$1.21 花掉 8000+ 决策，已拿第一个道馆徽章** — Boyd (0xBOYD) · Jev 评分 72 · 成本与性能 · ⭐ Jev 精选

  ![](images/20.png)

  [🔗 在 X 上查看 / View on X](https://x.com/0xBOYD/status/2100539883836018697)

- **Jev 玩马里奥：单次决策延迟229ms，1-1都没过，实时性不够（56赞）** — 陈成 (chenchengpro) · Jev 评分 42 · 成本与性能

  ![](images/24.png)

  [🔗 在 X 上查看 / View on X](https://x.com/chenchengpro/status/2100552073150665056)

- **Jev 打杀戮尖塔2：行动思考只需 0.7 秒，超人类游戏速度（977赞）** — paulwei (coolish) · Jev 评分 64 · 成本与性能 · ⭐ Jev 精选

  ![](images/42.png)

  [🔗 在 X 上查看 / View on X](https://x.com/coolish/status/2100570517954838897)

---

## 交易与金融 / Trading & Finance

- **JEV 被做成纯 AI 原生链上自动交易系统，代码前端全开源（14小时亏300%但架构惊艳）** — 梭哈.AI (SUOHA_AI) · Jev 评分 78 · 工具与产品 · ⭐ Jev 精选

  ![](images/03.png)

  [🔗 在 X 上查看 / View on X](https://x.com/SUOHA_AI/status/2100619720772694036)

- **用 Jev 造交易机器人：每300ms区块判断买卖，执行真实交易（4392赞）** — Jarrod Watts (jarrodwatts) · Jev 评分 89 · 工具与产品 · ⭐ Jev 精选

  ![](images/10.png)

  [🔗 在 X 上查看 / View on X](https://x.com/jarrodwatts/status/2100356151468585346)

- **用 Jev 自动化技术分析：加密和股票市场预测（417赞）** — Brendan Playford (BrendanPlayford) · Jev 评分 61 · 架构与方法 · ⭐ Jev 精选

  ![](images/28.png)

  [🔗 在 X 上查看 / View on X](https://x.com/BrendanPlayford/status/2100485748533440990)

- **Jev 交易实测：像人类一样 ATH 买入恐慌卖出，'AGI 确认'（198赞）** — Rafal Wilinski (rafalwilinski) · Jev 评分 38 · 生态与热度

  ![](images/32.png)

  [🔗 在 X 上查看 / View on X](https://x.com/rafalwilinski/status/2100516118586642476)

---

## 生态与热度 / Ecosystem & Hype

- **JEV 电车难题：牺牲人类救机器人，263赞热议 AI 伦理** — Max Rovensky (MaxRovensky) · Jev 评分 38 · 生态与热度

  ![](images/04.png)

  [🔗 在 X 上查看 / View on X](https://x.com/MaxRovensky/status/2100706874173575199)

- **硅谷十年前就预言了 Jev（3901赞爆款）** — Justin Schroeder (jpschroeder) · Jev 评分 44 · 生态与热度

  ![](images/31.png)

  [🔗 在 X 上查看 / View on X](https://x.com/jpschroeder/status/2100230381588951209)

- **We don't deserve Jev：100毫秒回答任何问题基本免费，Astra/Fable 让我们不知感恩（131赞）** — Rob Hallam (robj3d3) · Jev 评分 26 · 成本与性能

  ![](images/35.png)

  [🔗 在 X 上查看 / View on X](https://x.com/robj3d3/status/2100876506549645608)

- **Jev 的局限分析：零样本概率分布不适用于市场语境，生年收入估算也偏差大（83赞）** — 抹茶もなか (GianMattya) · Jev 评分 57 · 架构与方法

  ![](images/38.png)

  [🔗 在 X 上查看 / View on X](https://x.com/GianMattya/status/2100878864855748668)

- **Vercel CEO：Jev Generative UI 已经在外部实现了（1928赞）** — Guillermo Rauch (rauchg) · Jev 评分 59 · 工具与产品 · ⭐ Jev 精选

  ![](images/50.png)

  [🔗 在 X 上查看 / View on X](https://x.com/rauchg/status/2101032024635249069)

- **Vercel CEO：Jev 采用数据令人震惊——每个人都在采用（243赞）** — Guillermo Rauch (rauchg) · Jev 评分 58 · 生态与热度 · ⭐ Jev 精选

  ![](images/54.png)

  [🔗 在 X 上查看 / View on X](https://x.com/rauchg/status/2101079472732848510)

- **Jev 现在感觉像 ChatGPT 时刻（12赞）** — Maz (0xmaz_) · Jev 评分 9 · 生态与热度

  ![](images/55.png)

  [🔗 在 X 上查看 / View on X](https://x.com/0xmaz_/status/2101030854269231389)

- **睡一觉起来 Jev 系 GitHub 仓库暴增（340赞）** — StudioYebisu (studio_yebisu) · Jev 评分 66 · 生态与热度 · ⭐ Jev 精选

  ![](images/56.png)

  [🔗 在 X 上查看 / View on X](https://x.com/studio_yebisu/status/2101065176069886152)

---

## 开发与工具 / Development & Tools

- **OpenJev 开源：JEV 模型 GitHub 开源实现，全网围观（1466赞）** — 𝑺𝒉𝒊𝒃𝒂 (4ba_ba_baba) · Jev 评分 55 · 工具与产品 · ⭐ Jev 精选

  ![](images/05.png)

  [🔗 在 X 上查看 / View on X](https://x.com/4ba_ba_baba/status/2100476048957931642)

- **用 Jev 从零搭了个 LLM：每个字符 29 个是/否问题（873赞）** — vogel (ryanvogel) · Jev 评分 77 · 架构与方法 · ⭐ Jev 精选

  ![](images/09.png)

  [🔗 在 X 上查看 / View on X](https://x.com/ryanvogel/status/2100218045549412499)

- **Jev 即时 AI 建议：每次编辑单元格20+智能检查，无需LLM（174赞）** — Chris Nicholas (ctnicholasdev) · Jev 评分 66 · 架构与方法 · ⭐ Jev 精选

  ![](images/22.png)

  [🔗 在 X 上查看 / View on X](https://x.com/ctnicholasdev/status/2100611346203353110)

- **开源 jev-job-hunter：给 Jev 一个官网，它自动找招聘页打分（75赞）** — @hqmank · Jev 评分 51 · 工具与产品 · ⭐ Jev 精选

  ![](images/60.png)

  [🔗 在 X 上查看 / View on X](https://x.com/hqmank/status/2100938653979508826)

---

## 内容分类与SEO / Content Classification & SEO

- **Jev + Grok Bot + X API：从1000条帖子里选出最有价值的AI Agent建议** — Dan McAteer (daniel_mac8) · Jev 评分 66 · 架构与方法 · ⭐ Jev 精选

  ![](images/07.png)

  [🔗 在 X 上查看 / View on X](https://x.com/daniel_mac8/status/2100620339097026633)

- **DuckDB 扩展：Jev 给任意 CSV/Parquet 打标签，1千行约10秒（1347赞）** — Hamilton Ulmer (hamiltonulmer) · Jev 评分 74 · 工具与产品 · ⭐ Jev 精选

  ![](images/11.png)

  [🔗 在 X 上查看 / View on X](https://x.com/hamiltonulmer/status/2100370557405667768)

- **fx auto 安全分类器用 Jev 替代 GPT-5.6 Luna：快5-18倍更准（608赞）** — Pranit (fazxes) · Jev 评分 78 · 成本与性能 · ⭐ Jev 精选

  ![](images/12.png)

  [🔗 在 X 上查看 / View on X](https://x.com/fazxes/status/2100300097695232164)

- **Jev 语义查询 cookbook：从海量信息中智能提取信号（506赞）** — Nathan LeClaire (dotpem) · Jev 评分 43 · 架构与方法

  ![](images/14.png)

  [🔗 在 X 上查看 / View on X](https://x.com/dotpem/status/2100389272004198844)

- **Jev 热度非常高：人民日报新闻分类实测（43赞）** — 李不凯正在研究 (libukai) · Jev 评分 47 · 生态与热度

  ![](images/51.png)

  [🔗 在 X 上查看 / View on X](https://x.com/libukai/status/2100984923926728920)

- **Jev vs DeepSeek 实测：28 秒狂刷 428 条新闻为 15 个品牌匹配热点（564赞）** — 梭哈.AI (SUOHA_AI) · Jev 评分 75 · 内容与营销 · ⭐ Jev 精选

  ![](images/59.png)

  [🔗 在 X 上查看 / View on X](https://x.com/SUOHA_AI/status/2101000339948282090)

- **Jev 把 SEO/GEO 修复成本砍 90%：原来 /单，现在几乎免费** — @irabukht · Jev 评分 80 · 内容与营销 · ⭐ Jev 精选

  ![](images/62.png)

  [🔗 在 X 上查看 / View on X](https://x.com/irabukht/status/2101090579127951694)

- **把竞争对手广告库喂给 Jev：19 秒分类 1891 个广告** — @liambraus · Jev 评分 74 · 内容与营销 · ⭐ Jev 精选

  ![](images/64.png)

  [🔗 在 X 上查看 / View on X](https://x.com/liambraus/status/2100954699255947277)

---

## 教程与资源 / Tutorials & Resources

- **Matija Sosic 45秒视频讲清 Jev 核心：想法美得简单（7799赞）** — Matija Sosic (MatijaSosic) · Jev 评分 82 · 架构与方法 · ⭐ Jev 精选

  ![](images/08.png)

  [🔗 在 X 上查看 / View on X](https://x.com/MatijaSosic/status/2100190746389135772)

- **Jev 深度教程：它是什么、怎么用（716赞）** — Flavio Copes (flaviocopes) · Jev 评分 75 · 生态与热度 · ⭐ Jev 精选

  ![](images/21.png)

  [🔗 在 X 上查看 / View on X](https://x.com/flaviocopes/status/2100695543995347188)

- **Jev 模型实用指南：Codex 写 waitlist 申请通过，Jev 做分类器，整理10个仓库** — 飞翔的企鹅x (BystAnd3rs) · Jev 评分 72 · 工具与产品 · ⭐ Jev 精选

  ![](images/23.png)

  [🔗 在 X 上查看 / View on X](https://x.com/BystAnd3rs/status/2100769446457647532)

- **Jev 学习资源聚合中心上线：官方+社区+可运行项目一站式** — YouWare (YouWareAI) · Jev 评分 43 · 工具与产品

  ![](images/25.png)

  [🔗 在 X 上查看 / View on X](https://x.com/YouWareAI/status/2100655600803966986)

- **Jev 的 9 个使用场景（System 1 模型）：reranking/工具剪枝/模型路由/查询路由（117赞）** — Amit Shekhar (amitiitbhu) · Jev 评分 69 · 架构与方法 · ⭐ Jev 精选

  ![](images/33.png)

  [🔗 在 X 上查看 / View on X](https://x.com/amitiitbhu/status/2100839449576030414)

- **Jev 45秒视频解析：不止 game/trade，速度+文本理解+排序衍生无限（105赞）** — Jason Zhu (GoSailGlobal) · Jev 评分 52 · 架构与方法 · ⭐ Jev 精选

  ![](images/36.png)

  [🔗 在 X 上查看 / View on X](https://x.com/GoSailGlobal/status/2100620755155181835)

- **刚拿到 Jev 权限：分享让 Codex 和 Claude 找工作流决策点的 prompt（80赞）** — Avid (Av1dlive) · Jev 评分 68 · 架构与方法 · ⭐ Jev 精选

  ![](images/47.png)

  [🔗 在 X 上查看 / View on X](https://x.com/Av1dlive/status/2100974220759196026)

- **Jev 来了：最清楚的解释，它是什么，解锁什么新业务（462赞）** — GREG ISENBERG (gregisenberg) · Jev 评分 86 · 工具与产品 · ⭐ Jev 精选

  ![](images/49.png)

  [🔗 在 X 上查看 / View on X](https://x.com/gregisenberg/status/2101018750916948237)

- **LangChain CEO：Jev 不是生成文本，是做简单受限输出——构建 harness 时非常有用** — Harrison Chase (hwchase17) · Jev 评分 69 · 架构与方法 · ⭐ Jev 精选

  > ⚠️ 截图暂缺：原推文已被删除或设为私密，无法访问。

  > ⚠️ Screenshot unavailable: original tweet deleted or restricted.

  [🔗 在 X 上查看 / View on X](https://x.com/hwchase17/status/2100773130041950579)

---

## 模型路由与决策 / Model Routing & Decision-making

- **创始人回复'私有评测+校准置信度'：去吧自动化！（116赞）** — Diogo Almeida (CompleteSkeptic) · Jev 评分 41 · 生态与热度

  ![](images/16.png)

  [🔗 在 X 上查看 / View on X](https://x.com/CompleteSkeptic/status/2100655158992719907)

- **Jev 做 UPSC 公务员考试：GS-1 考卷 72.7%（超过1-2%考生）** — YDSE (NeutronPrawn) · Jev 评分 59 · 工具与产品

  ![](images/17.png)

  [🔗 在 X 上查看 / View on X](https://x.com/NeutronPrawn/status/2100670087128846603)

- **把 Agent 工具调用推理换成 Jev：成本大幅节省，效果接近 Fable/Astra/Opus（1212赞）** — Vini Lana (oviniciuslana) · Jev 评分 92 · 成本与性能 · ⭐ Jev 精选

  ![](images/18.png)

  [🔗 在 X 上查看 / View on X](https://x.com/oviniciuslana/status/2100457622407168509)

- **Jev 判断特化 AI 实测：输入$0.042/1M tokens，输出无限免费（852赞）** — あきらパパ (akira_papa_IT) · Jev 评分 72 · 成本与性能 · ⭐ Jev 精选

  ![](images/19.png)

  [🔗 在 X 上查看 / View on X](https://x.com/akira_papa_IT/status/2100590065357639971)

- **Jev 作为模型路由器：用 Claude/Codex + Vercel eve 单提示词构建（166赞）** — Agent Native (agentnative_) · Jev 评分 67 · 架构与方法 · ⭐ Jev 精选

  ![](images/27.png)

  [🔗 在 X 上查看 / View on X](https://x.com/agentnative_/status/2100624941326500122)

- **Jev 让 agents 快10倍便宜10倍：模型路由+computer use+自动优化的3个用法（486赞）** — david fant (da_fant) · Jev 评分 75 · 成本与性能 · ⭐ Jev 精选

  ![](images/30.png)

  [🔗 在 X 上查看 / View on X](https://x.com/da_fant/status/2100659471257366766)

- **Jev 的 function calling 不需要按 Enter：理解意图提前执行（276赞）** — Yoshiki Miura (miiura) · Jev 评分 83 · 工具与产品 · ⭐ Jev 精选

  ![](images/37.png)

  [🔗 在 X 上查看 / View on X](https://x.com/miiura/status/2100615772053877164)

- **Jev 会抢走 LLM 的'脏活'：OpenRouter 已上 beta，不生成文本只判断（24赞）** — sleepy.md (sleepy0x13) · Jev 评分 59 · 工具与产品

  ![](images/39.png)

  [🔗 在 X 上查看 / View on X](https://x.com/sleepy0x13/status/2100753996684403175)

- **新 Jev 模型：检查 AI 工作并在软件内决策，$0.042/百万输入 token（116赞）** — Shann³ (shannholmberg) · Jev 评分 76 · 成本与性能 · ⭐ Jev 精选

  ![](images/45.png)

  [🔗 在 X 上查看 / View on X](https://x.com/shannholmberg/status/2100979911825789393)

- **Jev 太火了：给 Claude Code 和 Codex 加 AI 裁判，OpenRouter 体验（61赞）** — 知识猫AI实验室 (GeekCatX) · Jev 评分 68 · 生态与热度 · ⭐ Jev 精选

  ![](images/48.png)

  [🔗 在 X 上查看 / View on X](https://x.com/GeekCatX/status/2100956459580395585)

- **OpenRouter 官方解释 Jev：决策模型，比 LLM 便宜 10 倍快 10 倍（610赞）** — OpenRouter (OpenRouter) · Jev 评分 86 · 成本与性能 · ⭐ Jev 精选

  ![](images/57.png)

  [🔗 在 X 上查看 / View on X](https://x.com/OpenRouter/status/2101061688338575739)

- **Jev 实战：跳过聊天直接输出带置信度的结构化决策，快 193 倍便宜 445 倍** — @KKaWSB · Jev 评分 86 · 成本与性能 · ⭐ Jev 精选

  ![](images/63.png)

  [🔗 在 X 上查看 / View on X](https://x.com/KKaWSB/status/2101043826714661033)

- **Jev 在 Vercel AI Gateway 免费到 9/25，适合测分类/评分/路由** — @HtWavever · Jev 评分 56 · 工具与产品 · ⭐ Jev 精选

  ![](images/65.png)

  [🔗 在 X 上查看 / View on X](https://x.com/HtWavever/status/2101168084652622062)

- **Jev 用法：主 agent 自动搜 benchmark，按 pass rate/成本/时长路由模型** — @goon_nguyen · Jev 评分 66 · 架构与方法 · ⭐ Jev 精选

  ![](images/66.png)

  [🔗 在 X 上查看 / View on X](https://x.com/goon_nguyen/status/2101168725458354331)

---

## 上下文压缩 / Context Compaction

- **Jev 配套 Claude Code 插件 fast-jev-compaction：清理工具历史不摘要上下文（244赞）** — 松丸 彗吾 (k_matsumaru) · Jev 评分 64 · 工具与产品 · ⭐ Jev 精选

  ![](images/26.png)

  [🔗 在 X 上查看 / View on X](https://x.com/k_matsumaru/status/2100767258415157493)

- **Jev 最佳用例是记忆：并行决定 recall/store/merge/remove/relevance（435赞）** — Ant (anthdm) · Jev 评分 70 · 架构与方法 · ⭐ Jev 精选

  ![](images/34.png)

  [🔗 在 X 上查看 / View on X](https://x.com/anthdm/status/2100489448576131433)

- **JEV 联合创始人亲自转发：Claude Code 上下文卡顿插件开源（1560赞）** — 梭哈.AI (SUOHA_AI) · Jev 评分 83 · 工具与产品 · ⭐ Jev 精选

  ![](images/40.png)

  [🔗 在 X 上查看 / View on X](https://x.com/SUOHA_AI/status/2100780634734002230)

- **Jev 让 Claude Code/Codex 上下文用量减少 50%：代理问 Jev 哪些历史还需要（121赞）** — Pedro Nauck (pedronauck) · Jev 评分 70 · 成本与性能 · ⭐ Jev 精选

  ![](images/43.png)

  [🔗 在 X 上查看 / View on X](https://x.com/pedronauck/status/2100744500876320868)

- **被 Claude Fable 5.1 限制困扰的人：用 Jev 大幅改善（198赞）** — Claude code研究ラボ (claudecode84) · Jev 评分 46 · 工具与产品

  ![](images/53.png)

  [🔗 在 X 上查看 / View on X](https://x.com/claudecode84/status/2100810733076590784)

---

## 其他 / Other

- **（无标题记录 / Untitled record）** — 未知作者 · Jev 评分 0 · 工具与产品

  > ⚠️ 无标题 / 原始记录未提供链接，仅保留评分记录。

  > ⚠️ No title / no original link was provided in the source record; only the score entry is kept.

---

## 数据说明 / About the data

- 中文：本清单数据来自作者的 X 收藏夹，并由一个独立的 Jev 评分模型（jev_score 0–100）对每条帖子打分；jev_highlight=true 表示评分模型认为该案例具有代表性。数据截至 2026-09。所有截图版权归原发帖人，本仓库仅作索引与学习用途，不代表对原帖内容的背书。

- English: Data is drawn from the curator's X bookmarks, scored 0–100 by an independent Jev-rating model (`jev_score`); `jev_highlight=true` marks representative cases. Snapshot: 2026-09. All screenshots belong to their original posters; this repo is an index for learning only and does not endorse the original posts.

- License: MIT.

## 截图缺失说明 / Missing screenshots

- idx = 52 — 原推文作者 @hwchase17（LangChain CEO），X 页面提示「该页面不存在」，原推文已被删除或设为私密，无法抓取截图。条目仍保留 title / author / 原始 X 链接，仅供读者自行核对。

- idx = 67 — 原始记录 title / url / author 均为空，未提供可访问的原始链接，因此本条目不嵌图、不放链接，仅保留评分记录。

- idx = 52 — Author @hwchase17 (LangChain CEO); X reports "this page doesn't exist", the original tweet was deleted or made private, so no screenshot could be captured. The entry still lists title / author / original X URL for readers to check directly.

- idx = 67 — The source record has empty title / url / author and no accessible original link, so no image or link is embedded; only the score record is retained.
