# awesome-jev
[中文版 →](README.md)

![持续更新中](https://img.shields.io/badge/status-continuously%20updated-brightgreen) ![帖子](https://img.shields.io/badge/posts-68-blue) ![Jev精选](https://img.shields.io/badge/Jev%20highlights-50-orange) ![License](https://img.shields.io/badge/license-MIT-green)

**The comprehensive JEV playbook · continuously updated** — real-world Jev usage curated from X, blogs, forums, papers, and more (not limited to X).

📊 68 posts · 9 application scenes · 50 Jev highlights

## What is Jev?

Jev is a lightweight, millisecond-scale execution model, often paired with a large model in a "big-model reasoning + small-model execution" Agent architecture: the LLM plans and reasons, while Jev handles high-frequency, cheap, deterministic decisions and actions. This repository collects real-world usage cases of Jev from the community.

## Why this list

Many people don't know what Jev can actually do. These 68 real cases show typical playbooks across browser automation, gaming, trading, model routing and more. When a user does not specify a scene, this list can be used to proactively suggest the right pattern. The screenshots here are used as an index only; copyright belongs to the original authors.

## Contents

- [Browser & Computer Automation](#浏览器与电脑自动化)
- [Gaming & Real-time Interaction](#游戏与实时交互)
- [Trading & Finance](#交易与金融)
- [Ecosystem & Hype](#生态与热度)
- [Development & Tools](#开发与工具)
- [Content Categorization & SEO](#内容分类与SEO)
- [Tutorials & Resources](#教程与资源)
- [Model Routing & Decision-Making](#模型路由与决策)
- [Context Compression](#上下文压缩)
- [Other](#其他)

## Browser & Computer Automation

- **Breaking: Browser Use + Jev = 超快速浏览器代理！7秒完成成本仅$0.0039，开源** — Gregor Zunic (gregpr07) · Jev score 84 · 成本与性能 · ⭐ Jev highlight
  ![](images/00.png)
  [🔗 View on X](https://x.com/gregpr07/status/2100411066966749359)

- **Jev + Computer use = 比任何LLM快100倍，眨个眼就错过** — sav (savboj) · Jev score 56 · 成本与性能 · ⭐ Jev highlight
  ![](images/02.png)
  [🔗 View on X](https://x.com/savboj/status/2100545295201288678)

- **agent-browser + Jev 玩 Wiki Race：浏览器自动化合理用例（182赞）** — joogie (princecaarlo) · Jev score 48 · 工具与产品
  ![](images/15.png)
  [🔗 View on X](https://x.com/princecaarlo/status/2100313645116952701)

- **Jev 做 Chrome 扩展：实时检测 YouTube 赞助片段并跳过，每视频$0.005（453赞）** — Tony Dinh (tdinh_me) · Jev score 77 · 工具与产品 · ⭐ Jev highlight
  ![](images/29.png)
  [🔗 View on X](https://x.com/tdinh_me/status/2100793777103466615)

- **Browser Use 接 JEV 速度吓人：网页操作本质是离散多选题，不需要 AI 写诗（1190赞）** — 梭哈.AI (SUOHA_AI) · Jev score 80 · 架构与方法 · ⭐ Jev highlight
  ![](images/41.png)
  [🔗 View on X](https://x.com/SUOHA_AI/status/2100628846240264348)

- **Web Agent 航空券搜索 7 秒完成，成本仅 $0.0039：从慢且贵到快且便宜（28赞）** — KANA｜東京AI映像 (KanaWorks_AI) · Jev score 43 · 成本与性能
  ![](images/44.png)
  [🔗 View on X](https://x.com/KanaWorks_AI/status/2100783766193246394)

- **有人用 Jev 做了自动驾驶原型：一小时内完成完整驾驶决策循环（43赞）** — Mikadzyki (Mikadzyki_NFT) · Jev score 58 · 工具与产品 · ⭐ Jev highlight
  ![](images/46.png)
  [🔗 View on X](https://x.com/Mikadzyki_NFT/status/2100950578113232992)

- **SAM 3.1 × Jev：完全自立型 ComputerUse、高速人脸认证（914赞）** — StudioYebisu (studio_yebisu) · Jev score 80 · 架构与方法 · ⭐ Jev highlight
  ![](images/58.png)
  [🔗 View on X](https://x.com/studio_yebisu/status/2101003307200430126)

- **Jev 语音操控电脑比键鼠还快：Alan Daitch 实测（102赞）** — @AlanDaitch · Jev score 57 · 成本与性能 · ⭐ Jev highlight
  ![](images/61.png)
  [🔗 View on X](https://x.com/AlanDaitch/status/2101090570110169547)

## Gaming & Real-time Interaction

- **Jev + Astra 玩吃豆人：Astra 制定策略，Jev 毫秒级执行，大模型+小模型协作架构** — Dan McAteer (daniel_mac8) · Jev score 61 · 架构与方法 · ⭐ Jev highlight
  ![](images/01.png)
  [🔗 View on X](https://x.com/daniel_mac8/status/2100335929273524541)

- **Jev V13 vs Fable 5.1 vs GPT-6 Astra 下棋：Jev 不是LLM，只做决策（2098赞）** — AI/ML API (aimlapi) · Jev score 86 · 架构与方法 · ⭐ Jev highlight
  ![](images/06.png)
  [🔗 View on X](https://x.com/aimlapi/status/2100372930282573876)

- **陈成让 Jev 玩贪吃蛇：200个请求 $0.02，1美元能走一万步（246赞）** — 陈成 (chenchengpro) · Jev score 47 · 成本与性能
  ![](images/13.png)
  [🔗 View on X](https://x.com/chenchengpro/status/2100516953496670430)

- **Jev 玩宝可梦：$1.21 花掉 8000+ 决策，已拿第一个道馆徽章** — Boyd (0xBOYD) · Jev score 72 · 成本与性能 · ⭐ Jev highlight
  ![](images/20.png)
  [🔗 View on X](https://x.com/0xBOYD/status/2100539883836018697)

- **Jev 玩马里奥：单次决策延迟229ms，1-1都没过，实时性不够（56赞）** — 陈成 (chenchengpro) · Jev score 42 · 成本与性能
  ![](images/24.png)
  [🔗 View on X](https://x.com/chenchengpro/status/2100552073150665056)

- **Jev 打杀戮尖塔2：行动思考只需 0.7 秒，超人类游戏速度（977赞）** — paulwei (coolish) · Jev score 64 · 成本与性能 · ⭐ Jev highlight
  ![](images/42.png)
  [🔗 View on X](https://x.com/coolish/status/2100570517954838897)

## Trading & Finance

- **JEV 被做成纯 AI 原生链上自动交易系统，代码前端全开源（14小时亏300%但架构惊艳）** — 梭哈.AI (SUOHA_AI) · Jev score 78 · 工具与产品 · ⭐ Jev highlight
  ![](images/03.png)
  [🔗 View on X](https://x.com/SUOHA_AI/status/2100619720772694036)

- **用 Jev 造交易机器人：每300ms区块判断买卖，执行真实交易（4392赞）** — Jarrod Watts (jarrodwatts) · Jev score 89 · 工具与产品 · ⭐ Jev highlight
  ![](images/10.png)
  [🔗 View on X](https://x.com/jarrodwatts/status/2100356151468585346)

- **用 Jev 自动化技术分析：加密和股票市场预测（417赞）** — Brendan Playford (BrendanPlayford) · Jev score 61 · 架构与方法 · ⭐ Jev highlight
  ![](images/28.png)
  [🔗 View on X](https://x.com/BrendanPlayford/status/2100485748533440990)

- **Jev 交易实测：像人类一样 ATH 买入恐慌卖出，'AGI 确认'（198赞）** — Rafal Wilinski (rafalwilinski) · Jev score 38 · 生态与热度
  ![](images/32.png)
  [🔗 View on X](https://x.com/rafalwilinski/status/2100516118586642476)

## Ecosystem & Hype

- **JEV 电车难题：牺牲人类救机器人，263赞热议 AI 伦理** — Max Rovensky (MaxRovensky) · Jev score 38 · 生态与热度
  ![](images/04.png)
  [🔗 View on X](https://x.com/MaxRovensky/status/2100706874173575199)

- **硅谷十年前就预言了 Jev（3901赞爆款）** — Justin Schroeder (jpschroeder) · Jev score 44 · 生态与热度
  ![](images/31.png)
  [🔗 View on X](https://x.com/jpschroeder/status/2100230381588951209)

- **We don't deserve Jev：100毫秒回答任何问题基本免费，Astra/Fable 让我们不知感恩（131赞）** — Rob Hallam (robj3d3) · Jev score 26 · 成本与性能
  ![](images/35.png)
  [🔗 View on X](https://x.com/robj3d3/status/2100876506549645608)

- **Jev 的局限分析：零样本概率分布不适用于市场语境，生年收入估算也偏差大（83赞）** — 抹茶もなか (GianMattya) · Jev score 57 · 架构与方法
  ![](images/38.png)
  [🔗 View on X](https://x.com/GianMattya/status/2100878864855748668)

- **Vercel CEO：Jev Generative UI 已经在外部实现了（1928赞）** — Guillermo Rauch (rauchg) · Jev score 59 · 工具与产品 · ⭐ Jev highlight
  ![](images/50.png)
  [🔗 View on X](https://x.com/rauchg/status/2101032024635249069)

- **Vercel CEO：Jev 采用数据令人震惊——每个人都在采用（243赞）** — Guillermo Rauch (rauchg) · Jev score 58 · 生态与热度 · ⭐ Jev highlight
  ![](images/54.png)
  [🔗 View on X](https://x.com/rauchg/status/2101079472732848510)

- **Jev 现在感觉像 ChatGPT 时刻（12赞）** — Maz (0xmaz_) · Jev score 9 · 生态与热度
  ![](images/55.png)
  [🔗 View on X](https://x.com/0xmaz_/status/2101030854269231389)

- **睡一觉起来 Jev 系 GitHub 仓库暴增（340赞）** — StudioYebisu (studio_yebisu) · Jev score 66 · 生态与热度 · ⭐ Jev highlight
  ![](images/56.png)
  [🔗 View on X](https://x.com/studio_yebisu/status/2101065176069886152)

## Development & Tools

- **OpenJev 开源：JEV 模型 GitHub 开源实现，全网围观（1466赞）** — 𝑺𝒉𝒊𝒃𝒂 (4ba_ba_baba) · Jev score 55 · 工具与产品 · ⭐ Jev highlight
  ![](images/05.png)
  [🔗 View on X](https://x.com/4ba_ba_baba/status/2100476048957931642)

- **用 Jev 从零搭了个 LLM：每个字符 29 个是/否问题（873赞）** — vogel (ryanvogel) · Jev score 77 · 架构与方法 · ⭐ Jev highlight
  ![](images/09.png)
  [🔗 View on X](https://x.com/ryanvogel/status/2100218045549412499)

- **Jev 即时 AI 建议：每次编辑单元格20+智能检查，无需LLM（174赞）** — Chris Nicholas (ctnicholasdev) · Jev score 66 · 架构与方法 · ⭐ Jev highlight
  ![](images/22.png)
  [🔗 View on X](https://x.com/ctnicholasdev/status/2100611346203353110)

- **开源 jev-job-hunter：给 Jev 一个官网，它自动找招聘页打分（75赞）** — @hqmank · Jev score 51 · 工具与产品 · ⭐ Jev highlight
  ![](images/60.png)
  [🔗 View on X](https://x.com/hqmank/status/2100938653979508826)

## Content Categorization & SEO

- **Jev + Grok Bot + X API：从1000条帖子里选出最有价值的AI Agent建议** — Dan McAteer (daniel_mac8) · Jev score 66 · 架构与方法 · ⭐ Jev highlight
  ![](images/07.png)
  [🔗 View on X](https://x.com/daniel_mac8/status/2100620339097026633)

- **DuckDB 扩展：Jev 给任意 CSV/Parquet 打标签，1千行约10秒（1347赞）** — Hamilton Ulmer (hamiltonulmer) · Jev score 74 · 工具与产品 · ⭐ Jev highlight
  ![](images/11.png)
  [🔗 View on X](https://x.com/hamiltonulmer/status/2100370557405667768)

- **fx auto 安全分类器用 Jev 替代 GPT-5.6 Luna：快5-18倍更准（608赞）** — Pranit (fazxes) · Jev score 78 · 成本与性能 · ⭐ Jev highlight
  ![](images/12.png)
  [🔗 View on X](https://x.com/fazxes/status/2100300097695232164)

- **Jev 语义查询 cookbook：从海量信息中智能提取信号（506赞）** — Nathan LeClaire (dotpem) · Jev score 43 · 架构与方法
  ![](images/14.png)
  [🔗 View on X](https://x.com/dotpem/status/2100389272004198844)

- **Jev 热度非常高：人民日报新闻分类实测（43赞）** — 李不凯正在研究 (libukai) · Jev score 47 · 生态与热度
  ![](images/51.png)
  [🔗 View on X](https://x.com/libukai/status/2100984923926728920)

- **Jev vs DeepSeek 实测：28 秒狂刷 428 条新闻为 15 个品牌匹配热点（564赞）** — 梭哈.AI (SUOHA_AI) · Jev score 75 · 内容与营销 · ⭐ Jev highlight
  ![](images/59.png)
  [🔗 View on X](https://x.com/SUOHA_AI/status/2101000339948282090)

- **Jev 把 SEO/GEO 修复成本砍 90%：原来 /单，现在几乎免费** — @irabukht · Jev score 80 · 内容与营销 · ⭐ Jev highlight
  ![](images/62.png)
  [🔗 View on X](https://x.com/irabukht/status/2101090579127951694)

- **把竞争对手广告库喂给 Jev：19 秒分类 1891 个广告** — @liambraus · Jev score 74 · 内容与营销 · ⭐ Jev highlight
  ![](images/64.png)
  [🔗 View on X](https://x.com/liambraus/status/2100954699255947277)

## Tutorials & Resources

- **Matija Sosic 45秒视频讲清 Jev 核心：想法美得简单（7799赞）** — Matija Sosic (MatijaSosic) · Jev score 82 · 架构与方法 · ⭐ Jev highlight
  ![](images/08.png)
  [🔗 View on X](https://x.com/MatijaSosic/status/2100190746389135772)

- **Jev 深度教程：它是什么、怎么用（716赞）** — Flavio Copes (flaviocopes) · Jev score 75 · 生态与热度 · ⭐ Jev highlight
  ![](images/21.png)
  [🔗 View on X](https://x.com/flaviocopes/status/2100695543995347188)

- **Jev 模型实用指南：Codex 写 waitlist 申请通过，Jev 做分类器，整理10个仓库** — 飞翔的企鹅x (BystAnd3rs) · Jev score 72 · 工具与产品 · ⭐ Jev highlight
  ![](images/23.png)
  [🔗 View on X](https://x.com/BystAnd3rs/status/2100769446457647532)

- **Jev 学习资源聚合中心上线：官方+社区+可运行项目一站式** — YouWare (YouWareAI) · Jev score 43 · 工具与产品
  ![](images/25.png)
  [🔗 View on X](https://x.com/YouWareAI/status/2100655600803966986)

- **Jev 的 9 个使用场景（System 1 模型）：reranking/工具剪枝/模型路由/查询路由（117赞）** — Amit Shekhar (amitiitbhu) · Jev score 69 · 架构与方法 · ⭐ Jev highlight
  ![](images/33.png)
  [🔗 View on X](https://x.com/amitiitbhu/status/2100839449576030414)

- **Jev 45秒视频解析：不止 game/trade，速度+文本理解+排序衍生无限（105赞）** — Jason Zhu (GoSailGlobal) · Jev score 52 · 架构与方法 · ⭐ Jev highlight
  ![](images/36.png)
  [🔗 View on X](https://x.com/GoSailGlobal/status/2100620755155181835)

- **刚拿到 Jev 权限：分享让 Codex 和 Claude 找工作流决策点的 prompt（80赞）** — Avid (Av1dlive) · Jev score 68 · 架构与方法 · ⭐ Jev highlight
  ![](images/47.png)
  [🔗 View on X](https://x.com/Av1dlive/status/2100974220759196026)

- **Jev 来了：最清楚的解释，它是什么，解锁什么新业务（462赞）** — GREG ISENBERG (gregisenberg) · Jev score 86 · 工具与产品 · ⭐ Jev highlight
  ![](images/49.png)
  [🔗 View on X](https://x.com/gregisenberg/status/2101018750916948237)

- **LangChain CEO：Jev 不是生成文本，是做简单受限输出——构建 harness 时非常有用** — Harrison Chase (hwchase17) · Jev score 69 · 架构与方法 · ⭐ Jev highlight
  > ⚠️ Screenshot unavailable: original tweet deleted or restricted.
  [🔗 View on X](https://x.com/hwchase17/status/2100773130041950579)

## Model Routing & Decision-Making

- **创始人回复'私有评测+校准置信度'：去吧自动化！（116赞）** — Diogo Almeida (CompleteSkeptic) · Jev score 41 · 生态与热度
  ![](images/16.png)
  [🔗 View on X](https://x.com/CompleteSkeptic/status/2100655158992719907)

- **Jev 做 UPSC 公务员考试：GS-1 考卷 72.7%（超过1-2%考生）** — YDSE (NeutronPrawn) · Jev score 59 · 工具与产品
  ![](images/17.png)
  [🔗 View on X](https://x.com/NeutronPrawn/status/2100670087128846603)

- **把 Agent 工具调用推理换成 Jev：成本大幅节省，效果接近 Fable/Astra/Opus（1212赞）** — Vini Lana (oviniciuslana) · Jev score 92 · 成本与性能 · ⭐ Jev highlight
  ![](images/18.png)
  [🔗 View on X](https://x.com/oviniciuslana/status/2100457622407168509)

- **Jev 判断特化 AI 实测：输入$0.042/1M tokens，输出无限免费（852赞）** — あきらパパ (akira_papa_IT) · Jev score 72 · 成本与性能 · ⭐ Jev highlight
  ![](images/19.png)
  [🔗 View on X](https://x.com/akira_papa_IT/status/2100590065357639971)

- **Jev 作为模型路由器：用 Claude/Codex + Vercel eve 单提示词构建（166赞）** — Agent Native (agentnative_) · Jev score 67 · 架构与方法 · ⭐ Jev highlight
  ![](images/27.png)
  [🔗 View on X](https://x.com/agentnative_/status/2100624941326500122)

- **Jev 让 agents 快10倍便宜10倍：模型路由+computer use+自动优化的3个用法（486赞）** — david fant (da_fant) · Jev score 75 · 成本与性能 · ⭐ Jev highlight
  ![](images/30.png)
  [🔗 View on X](https://x.com/da_fant/status/2100659471257366766)

- **Jev 的 function calling 不需要按 Enter：理解意图提前执行（276赞）** — Yoshiki Miura (miiura) · Jev score 83 · 工具与产品 · ⭐ Jev highlight
  ![](images/37.png)
  [🔗 View on X](https://x.com/miiura/status/2100615772053877164)

- **Jev 会抢走 LLM 的'脏活'：OpenRouter 已上 beta，不生成文本只判断（24赞）** — sleepy.md (sleepy0x13) · Jev score 59 · 工具与产品
  ![](images/39.png)
  [🔗 View on X](https://x.com/sleepy0x13/status/2100753996684403175)

- **新 Jev 模型：检查 AI 工作并在软件内决策，$0.042/百万输入 token（116赞）** — Shann³ (shannholmberg) · Jev score 76 · 成本与性能 · ⭐ Jev highlight
  ![](images/45.png)
  [🔗 View on X](https://x.com/shannholmberg/status/2100979911825789393)

- **Jev 太火了：给 Claude Code 和 Codex 加 AI 裁判，OpenRouter 体验（61赞）** — 知识猫AI实验室 (GeekCatX) · Jev score 68 · 生态与热度 · ⭐ Jev highlight
  ![](images/48.png)
  [🔗 View on X](https://x.com/GeekCatX/status/2100956459580395585)

- **OpenRouter 官方解释 Jev：决策模型，比 LLM 便宜 10 倍快 10 倍（610赞）** — OpenRouter (OpenRouter) · Jev score 86 · 成本与性能 · ⭐ Jev highlight
  ![](images/57.png)
  [🔗 View on X](https://x.com/OpenRouter/status/2101061688338575739)

- **Jev 实战：跳过聊天直接输出带置信度的结构化决策，快 193 倍便宜 445 倍** — @KKaWSB · Jev score 86 · 成本与性能 · ⭐ Jev highlight
  ![](images/63.png)
  [🔗 View on X](https://x.com/KKaWSB/status/2101043826714661033)

- **Jev 在 Vercel AI Gateway 免费到 9/25，适合测分类/评分/路由** — @HtWavever · Jev score 56 · 工具与产品 · ⭐ Jev highlight
  ![](images/65.png)
  [🔗 View on X](https://x.com/HtWavever/status/2101168084652622062)

- **Jev 用法：主 agent 自动搜 benchmark，按 pass rate/成本/时长路由模型** — @goon_nguyen · Jev score 66 · 架构与方法 · ⭐ Jev highlight
  ![](images/66.png)
  [🔗 View on X](https://x.com/goon_nguyen/status/2101168725458354331)

## Context Compression

- **Jev 配套 Claude Code 插件 fast-jev-compaction：清理工具历史不摘要上下文（244赞）** — 松丸 彗吾 (k_matsumaru) · Jev score 64 · 工具与产品 · ⭐ Jev highlight
  ![](images/26.png)
  [🔗 View on X](https://x.com/k_matsumaru/status/2100767258415157493)

- **Jev 最佳用例是记忆：并行决定 recall/store/merge/remove/relevance（435赞）** — Ant (anthdm) · Jev score 70 · 架构与方法 · ⭐ Jev highlight
  ![](images/34.png)
  [🔗 View on X](https://x.com/anthdm/status/2100489448576131433)

- **JEV 联合创始人亲自转发：Claude Code 上下文卡顿插件开源（1560赞）** — 梭哈.AI (SUOHA_AI) · Jev score 83 · 工具与产品 · ⭐ Jev highlight
  ![](images/40.png)
  [🔗 View on X](https://x.com/SUOHA_AI/status/2100780634734002230)

- **Jev 让 Claude Code/Codex 上下文用量减少 50%：代理问 Jev 哪些历史还需要（121赞）** — Pedro Nauck (pedronauck) · Jev score 70 · 成本与性能 · ⭐ Jev highlight
  ![](images/43.png)
  [🔗 View on X](https://x.com/pedronauck/status/2100744500876320868)

- **被 Claude Fable 5.1 限制困扰的人：用 Jev 大幅改善（198赞）** — Claude code研究ラボ (claudecode84) · Jev score 46 · 工具与产品
  ![](images/53.png)
  [🔗 View on X](https://x.com/claudecode84/status/2100810733076590784)

## Other

- **(untitled record)** — Jev score 0 · 工具与产品
  > ⚠️ Untitled record / no original link provided; score only.

## Data notes

Sources: the author's X bookmarks plus an independent Jev scoring model, current as of 2026-09. Screenshots are copyrighted by their original posters; this repo uses them only as an index and for learning. Licensed under MIT.

## Missing screenshots

- idx=52: original tweet deleted or restricted, so no screenshot is available;
- idx=67: no original link or title provided; only the score record is kept.
