# L4ST-afk · Agent Skill 工具集

> 东瓯旧事，形器之间；不信口头之诺，唯认落盘铁证。
> *From Dong'ou wind and craft to deterministic agent harnesses — no self-reported success, only verifiable artifacts.*

一套围绕 **AI Agent 工程化、确定性交付与东方介质美学** 构建的模块化工具集。每座工具取典浙南风物或古籍意象，配一张专属绘画介质的封面题铭；底层全部遵循同一套冷酷纪律：**先量后改、离线硬闸、零黑盒运行、隔离舱界与退出码验真**。

---

## 已开源

| 题名 | 学名 / 仓库 | 典故与介质 | 定位与职责 | 状态 |
| :--- | :--- | :--- | :--- | :--- |
| **禅院塔・籁** | [*Zojuta Lite*](https://github.com/L4ST-afk/zojuta-lite) | 江心屿东塔 · 水墨古榕 | **判据层快照**：17 卷 98 条「我这次算不算违规」的可机判问题 | 已开源 · Apache-2.0 |
| **浮龟** | [*Vudgio*](https://github.com/L4ST-afk/vudgio) | 罗浮龟象 · 鳞格棱石 | **界面设计总承包**：定方向 → 出对比 → 写界面 → 配图 → 动效 → 盲审交付 | 已开源 · Public |
| **罗蛇** | [*Rassarpa*](https://github.com/L4ST-afk/rassarpa) | 罗浮蛇象 · 蜿蜒有节 | **中西文混排规则与引擎**：四分空隙、标点挤压与字体回退红线 | 已开源 · Public |
| **蝶花半梦** | [*Viola Somnians*](https://github.com/L4ST-afk/somnians) | 蝶栖花上 · 撕纸拼贴水彩 | **存量记忆库去重与安全归并**：同义候选逐对复判、单事务软删、按批回滚留痕 | 已开源 · Public |
| **来雪亭** | [*Lesciotia*](https://github.com/L4ST-afk/lesciotia) | 江心屿来雪亭 · 新版画雪景 | **双出口演示引擎**：同源输出自包含 HTML 与原生可编辑 PPTX，全离线 | 已开源 · Public |
| **对鸟** | [*Deducere*](https://github.com/L4ST-afk/deducere) | 乐清《对鸟》· 錾金四鸟铭牌 | **证据链根因定位**：四问三账、先红后绿硬闸、29 条判据 | 已开源 · MIT |

---

## 禅院塔・籁 · Zojuta Lite

<img src="assets/zojuta-lite.jpg" alt="禅院塔・籁 — 水墨青砖七层空心古塔，塔巅古榕如冠" width="640">

**一套可以拿来审自己工程的判据。不给你答案，给你该问的问题。**

[github.com/L4ST-afk/zojuta-lite](https://github.com/L4ST-afk/zojuta-lite) · Apache-2.0

- **是什么**：判据层快照，2026-11-24，17 卷 98 条。每条都能回答一个问题——「我这次算不算违规」。
- **怎么用**：不要从头读。带着手上正在做的事去找卷——刚写完闸门去 `02b`，在对账去 `01b`，在验收交付去 `06`。
- **边界**：主库未开源。运行层（闸门实现、自检脚本、目录治理、发布流程）不在本仓。
- **介质**：江心屿东塔。唐咸通十年建，檐廊被拆而塔身中空，巅上一榕不借寸土、根垂塔腹，反以榕荫为冠。

## 浮龟 · Vudgio

<img src="assets/vudgio.jpg" alt="浮龟 Vudgio — 罗浮龟象，鳞格棱石" width="640">

**AI agent 的界面设计技能：定方向 → 出界面 → 收图复核 → 交付。**

[github.com/L4ST-afk/vudgio](https://github.com/L4ST-afk/vudgio)

- **是什么**：端到端界面设计技能。不是给一套组件库，是给一条从「要什么感觉」走到「交付件能过盲审」的工序。
- **怎么用**：先定方向与对比稿，再写界面、配图、动效，最后收图复核。references 按需加载。
- **硬闸**：对比度、字形推进宽度、令牌生成、引用鉴权、CI 覆盖，全部离线可跑。
- **介质**：罗浮龟象，鳞格棱石。龟背十三格，一格一判据。

## 罗蛇 · Rassarpa

<img src="assets/rassarpa.jpg" alt="罗蛇 Rassarpa — 罗浮蛇象，蜿蜒有节" width="640">

**中西文混排判据与执行：四分空、标点挤压、避头尾。**

[github.com/L4ST-afk/rassarpa](https://github.com/L4ST-afk/rassarpa)

- **是什么**：中文与西文／数字混排的规则集与执行工具。把「看着别扭」拆成能量出来的数。
- **怎么用**：查判据卷定规则，用 `tools/` 下的脚本量实际读数（含 `text-autospace` 实测）。
- **硬闸**：A1–A4、C1 门禁全绿；字距、挤压、断行逐项可复算。
- **介质**：罗浮蛇象，蜿蜒有节。蛇行有节，节即间隙。

## 蝶花半梦 · Viola Somnians

<img src="assets/somnians.jpg" alt="蝶花半梦 — 蝶栖花上，撕纸拼贴水彩" width="640">

**agent 记忆去重：扫近似、逐对裁、单事务软删、按批回滚。**

[github.com/L4ST-afk/somnians](https://github.com/L4ST-afk/somnians)

- **是什么**：存量记忆库的「夜间去重」。扫出同义候选、跨席位复判、人签字后软删落库。
- **怎么用**：`somnians` CLI，Python 包，`pip install` 或源码直跑。批次可回滚，原碎片不动。
- **硬闸**：单事务落库、`merge_map`／`change_log`／`events` 三表串批号、按批一行 SQL 回滚。
- **边界**：机制是手动触发，同步 timer 与采纳率台账未建。
- **介质**：蝶栖花上，撕纸拼贴水彩。借《仲夏夜之梦》花汁的「驴头」与「解药」两义，不借它的字段设计。

## 来雪亭 · Lesciotia

<img src="assets/lesciotia.jpg" alt="来雪亭 Lesciotia — 江心屿来雪亭，新版画雪景" width="640">

**一份 spec 出两个出口：单文件 HTML 演示与可编辑原生 PPTX。**

[github.com/L4ST-afk/lesciotia](https://github.com/L4ST-afk/lesciotia)

- **是什么**：双出口演示引擎。同一份内容源，一边出零依赖自包含 HTML，一边出能在 PowerPoint 里真改的原生 PPTX。
- **怎么用**：按 spec 写内容，跑生成器出两个出口。全离线，不联网。
- **规模**：17 族梁架、9 瓦作、5 整册。
- **介质**：江心屿来雪亭，新版画雪景。亭有梁架瓦作，一册一构。

## 对鸟 · Deducere

<img src="assets/deducere.jpg" alt="对鸟 Deducere — 墨绿毡布上四枚分离錾金鸟铭牌，四鸟相向，眼宝为祖母绿、白钻、红宝石、蓝宝石，间杂贸易彩珠" width="640">

**证据链根因定位：四问三账，先红后绿才对得起「修好了」。**

[github.com/L4ST-afk/deducere](https://github.com/L4ST-afk/deducere) · MIT

- **是什么**：排障与故障归因技能。四个可反复进入的问（辨征／循链／验真／净痕）＋三本互不替代的账（过程／结果／证据），把「瞎猜乱改」与「真正修好」拆开。
- **怎么用**：先用一条命令把这个 bug 钉成红，再列可证伪假设、单一探针定位，最后源头修＋清探针＋防再犯。29 条判据（J1–J29）单一载体在 `references/判据表.md`。
- **硬闸**：`verify_red_green.py` 先红后绿同一条命令、`check_clean.py` 净痕；24 组单测＋离线自检，零第三方依赖。
- **介质**：乐清民歌《对鸟》一问一答，四鸟对四宝——青翠配祖母绿、白鸽配白钻、雉鸡配红宝石、长尾巴丁配蓝宝石；封面取莫切錾金鸟牌与贸易彩珠的排布。

---

## 共同工程底线（Shared Invariants）

所有仓库在脱敏整理并出列开源前，必须全部通过以下四条硬标准：

- **零外部黑盒依赖**：核心自检（`selftest.py`）与离线门禁全部在本地标准库下闭环跑通，不联网、不读环境变量、不留外部凭据。
- **确定性度量为先**：能用字形推进宽度、退出码、日期算术和 AST/Diff 扫描量出来的指标，绝不交给大语言模型「看一眼觉得还行」。
- **可独立装卸**：每个目录均符合标准 Agent Skill 规范（`SKILL.md` + 按需加载 `references/` + 确定性 `scripts/`），互不强耦合，即插即用。
- **文图同源考据**：每部作品的中文名、拉丁/音韵学名、封面题铭与架构隐喻一一咬合，拒绝空洞概念拼凑。

---

*其余各部仍在历史提交清洗与离线测试回归中，达标后陆续公开。*
