# Arm China(安谋科技)风险专题

> 整理于 2026-07-14。本文聚焦 Arm 与 Arm China 的关系及四层风险,附原始资料便于核实。
> 一手来源:同目录 `年报_20F/FY2026_20-F_2026-03-31.htm`(下称"20-F");二手来源见文末链接。
> 本文为公开信息整理,非投资建议。

---

## 一、Arm China 是什么:一个"顶着 Arm 品牌、独立经营的代理式合资公司"

- **不是普通海外子公司,而是不并表的独立合资实体。** Arm 早年控股并并表 Arm China,后经重组剥离股权,现**不再控制、不再并表**。
- **股权结构(20-F 披露):** 约 **48%** 由 Acetone Limited 持有(软银控制,Arm 在 Acetone 中仅 **10% 无投票权**);约 **35%** 由 HOPU(厚朴)间接持有;约 **17%** 由其他中方持有。
  → Arm 对 Arm China 的**间接经济权益仅约 5%,且无投票权**。
- **收入按"净额法"确认:** Arm 不计入中国区整笔收入,只确认 Arm China 对外转授权所得中**分给 Arm 的那一部分**——即 Arm China 自己**留一道价差**。这正是"代理/分销商"而非"子公司"的会计特征。
- **它是 PRC 市场的主要授权通道:** 20-F 称预计 Arm China 将"在可预见的未来继续提供我们进入 PRC 市场 IP 收入的主要渠道"。标准 IP 它可自行转授权、自主定价;**非标准技术/架构授权须经 Arm 同意**(Arm 保留高端否决权)。

### 收入敞口(逐年下降)

| 口径 | FY26 | FY25 | FY24 |
|---|---|---|---|
| Arm China 占总收入 | **16%** | 17% | 21% |
| PRC(中国)占总收入 | 18% | 19% | 22% |

---

## 二、四层风险 + 具体案例

### 第 1 层｜控制权风险 —— 案例:Allen Wu 公章夺权(2020–2022)

- Allen Wu(吴雄昂)时任 Arm China CEO 兼董事长。**导火索:利益冲突**——2019 年 Arm 发现他私设投资基金 **Alphatecture**,从与 Arm China 有业务往来的公司募资约 **1 亿美元**,投向能"从 Arm 拿到更便宜授权"的中国初创,本应导流给官方的 Hopu-Arm 基金。
- **2020 年 6 月** 董事会压倒性投票罢免;但 Wu **手握公司公章("chop")+ 身为登记的法定代表人**,拒不交权,把 Arm China 当独立王国运营。
- **2022 年 4 月 29 日** 软银主导二次罢免,任命刘仁辰、陈恂(Eric Chen)为联席CEO,称已获中国董事会与监管当局背书;Wu 仍拒绝交接。
- **2022 下半年** Arm 最终夺回董事会/运营控制权,扫清 IPO 障碍 →**2023 年 9 月 Arm 上市**。
- **至今(FY26 20-F):** Wu 及其关联实体自 2022 年 4 月起在中国法院**仍有多起诉讼**未了结。

**为什么一枚公章能压过董事会决议(中国公司治理要点):**
1. 在中国,**盖了公章的文件即视为公司正式意思表示,对外一律有效,不问内部是否授权**;董事会决议不盖章对外等于白纸。
2. Wu 同时是**工商登记的法定代表人**——变更登记程序上又常需现任法代配合或用到公章,形成死循环。
3. 公安将此类**定性为内部民事纠纷,不强制驱离在任CEO**;走诉讼又慢,故"物理占有 = 事实控制",能拖两年。
4. Arm 最终不是靠强制力,而是靠**夺回"工商登记 + 有效新公章"**(大概率重刻新章、声明旧章作废、变更法代登记)才翻盘。

> **投资启示:** 中国资产"法律所有权 ≠ 实际控制权";要单独审"控制权落地机制"(章在谁手里、法代是谁、能否快速合法替换、账户谁签字)。这也是中国合资/中概股普遍存在"治理折价"的根源。

### 第 2 层｜数据真实性风险 —— 案例:对 Arm China 计提坏账

- 20-F 披露:Arm 对 Arm China 应收款的**预期信用损失准备**,FY26 为 **$28.3M**、FY25 为 **$16.0M**(**一年几乎翻倍**,信号本身值得注意);并披露**与 Arm China 的合同纠纷**、2023 年 12 月**终止一项与 Arm China 的软件工程服务协议**(收回自营)。
- Allen Wu 时期(2020–2022)Arm 作为母公司**无法获取/审计 Arm China 的真实账目**。
- **机理:** 中国区版税**按 Arm China 自报的转授权收入的百分比**确认。Arm 自述"像依赖其他版税客户一样,依赖 Arm China 提供可靠、及时的信息"。**收多少靠对方报数,且对方还得真能付**——计提坏账即该风险已转化为实际损失的证据。

### 第 3 层｜IP 保护/竞争风险 —— 案例:Arm China 自研"周易"NPU 等自主 IP 线

- Arm China(安谋科技)**顶着 Arm 品牌,发展一整套不受 Arm 总部控制的"中国自主 IP"**:代表作 **"周易(Zhouyi)"NPU**(AI 加速器,0.25 TOPS ~ 数百 TOPS,已用于安防/汽车/IoT),另有"山海"(安全)、"玲珑"(视频)、"星辰"(CPU)等自研产品线;并在**将周易 NPU 驱动上游合并进 Linux 内核**、构建开源生态。
- **双重隐患:**
  1. **控制外的 IP 混同**:一个 Arm 管不住的实体,在 Arm 品牌/生态内发展自有 IP,总部难监控其如何保护(或使用)Arm 的技术与数据。
  2. **孵化未来竞争者**:自主 IP 的战略意图,是让中国客户在被断供时也能"去 Arm 化"——等于 Arm 的中国渠道同时在做备胎/竞品。

### 第 4 层｜地缘政治风险 —— 案例:华为断供(2019)+ Neoverse V 禁授中国(2022–)

**案例 A｜华为/海思(2019):** 美国将华为列入实体清单后,Arm 一度**内部通知暂停与华为的合作**(理由:设计含"美国原产技术");后认定 **Armv8/v9 属英国原产**才恢复该部分供应。一纸清单即可瞬间冻结一个客户的授权关系。

**案例 B｜高端 Neoverse V 无法授权中国(2022 至今):** Arm 认定其最高性能的 **Neoverse V 系列**因性能过高、被视为"美国原产",受**美/英出口管制 + 瓦森纳协定**约束,**不能授权给中国实体**(阿里 T-Head/平头哥无法获得,只能改用其他 Armv9 核)。这是 Arm **首次因管制无法把最尖端设计卖给中国**;到 2026 年该限制仍在。
- **转折:** 新推的 **AGI CPU 是"成品芯片"而非"IP"**,适用不同出口规则(按性能阈值),**反而可卖给中国**(管理层称预计中国需求与其他地区一样强)。"卖 IP 被卡、卖成品能过"也是 Arm 转向自研成品芯片的动因之一。

---

## 三、Arm 如何缓释

- **不并表 + 净额收租:** 与其守着一个"决议管不动"的子公司,不如退成"净额确认收入 + ~5% 无投票权"的关系,把治理雷**隔离在墙外**,降级为"收入依赖 + 已披露风险"。
- **保留高端否决权:** 非标准技术/架构授权须经 Arm 同意,低端量走渠道、高端卡在手里。
- **敞口稀释:** 增长越来越靠数据中心/AI 等非中国高价值市场,Arm China 占比 21%→17%→**16%**。

---

## 四、一句话总结

Arm China 是 Allen Wu 夺权失控后重组的产物:一个顶着 Arm 品牌、独家代理中国市场、但母公司管不住的独立合资公司。四层风险都有实例——**控制权(Allen Wu 公章)、数据(~$28M 坏账)、IP(周易自研线)、地缘(华为 + Neoverse V)**,且相互咬合:控制不住、看不透,才有自主 IP 的空间,而地缘断供又给"去 Arm 化"备胎提供了理由。缓释靠"不并表 + 收入稀释",但残留的诉讼与依赖至今未消。

---

# 附:原始资料(便于核实)

## A. 一手来源 —— FY2026 20-F 年报(本地文件)
文件:`年报_20F/FY2026_20-F_2026-03-31.htm`。关键披露原文摘录(可在文件内搜索定位):

- **收入集中度:** "our top five customers (including Arm China and SoftBank Group) collectively accounted for approximately **57%, 56% and 54%** of our total revenue for the fiscal years ended March 31, 2026, 2025 and 2024, respectively, and our largest customer individually, **Arm China, accounted for approximately 16%, 17% and 21%**…"
- **无其他单一客户超 10%:** "No other customer represented 10% or more of total revenue for the fiscal years ended March 31, 2026, 2025 and 2024."
- **高通:** "…Qualcomm, which is currently a major customer of ours and accounted for **9%** of our total revenue for the fiscal year ended March 31, 2026."
- **中国区收入:** "revenues from the PRC accounted for approximately **18%, 19% and 22%**…"; "revenues attributable to our relationship with Arm China were approximately **16%, 17% and 21%**…"
- **股权结构:** "approximately **48%** … owned by Acetone Limited, which is controlled by SoftBank Group and in which we own a **10% non-voting interest**, approximately **35%** … by HOPU …, approximately **17%** … by other Chinese parties."
- **坏账准备:** "the Company's allowance for current expected credit losses related to Arm China was **$ 28.3 million and $ 16.0 million**"(分别为 FY26、FY25)。
- **依赖自报数据:** "…similar to our other royalty customers, we are dependent on **Arm China providing us with reliable and timely** financial information."
- **不受其控制:** "Neither we nor SoftBank Group control the operations of Arm China, which operates independently of us."
- **Allen Wu 诉讼:** "since April 2022, **Allen Wu**, the former Chief Executive Officer of Arm China … have initiated several lawsuits in the courts of the PRC…"
- **服务协议终止:** "In December 2023, we terminated an agreement with Arm China for certain software engineering-related services, which have been brought in-house."
- 完整 SEC 链接:https://www.sec.gov/Archives/edgar/data/1973239/000197323926000097/arm-20260331.htm

## B. 二手来源 —— 按风险层分类

**控制权 / Allen Wu 夺权:**
- Arm China regain control, dismissing Allen Wu (TechNode, 2022-04-29):https://technode.com/2022/04/29/arm-china-regain-control-of-china-entity-dismissing-allen-wu/
- Ousted Arm China CEO refuses to go, again (DataCenterDynamics):https://www.datacenterdynamics.com/en/news/ousted-arm-china-ceo-refuses-to-go-after-being-fired-again/
- ARM Fired Arm China's CEO But He Won't Go — a breakdown (Asianometry):https://www.asianometry.com/p/arm-fired-arm-chinas-ceo-but-he-wont
- Arm sacks China boss over secret Cayman Islands activity (TechRadar):https://www.techradar.com/news/arm-sacks-china-boss-over-secret-cayman-islands-activity-but-he-wont-leave
- Can Arm fend off Allen Wu's autonomy moves? (TechNode, 2021):https://technode.com/2021/09/22/silicon-can-arm-fend-off-allen-wus-latest-autonomy-moves/
- Arm China CEO refuses to go despite SoftBank taking control (The Register):https://www.theregister.com/2022/05/05/arm_china_ceo_stays/

**IP / 竞争 —— Arm China 自研 IP(周易 NPU 等):**
- Arm China Develops NPU Accelerator (Zhouyi) Targeting Domestic CPUs (TechPowerUp):https://www.techpowerup.com/321033/arm-china-develops-npu-accelerator-for-ai-targeting-domestic-cpus
- Arm China Upstreaming Zhouyi NPU Driver Into Linux Kernel (Phoronix):https://www.phoronix.com/news/Arm-China-Zhouyi-NPU-Linux-RFC
- 安谋科技 Arm-China GitHub(周易 model zoo / parser):https://github.com/Arm-China

**地缘政治 —— 华为 & Neoverse V 出口管制:**
- China's access to Arm advanced designs limited by export controls (Tom's Hardware):https://www.tomshardware.com/news/china-access-to-arm-advanced-chip-designes-limited-by-export-controls
- Arm declines to license Neoverse V series to Alibaba (eeNews Europe):https://www.eenewseurope.com/en/arm-declines-to-license-neoverse-v-series-to-alibaba/
- Arm won't sell latest chip designs in China due to US/UK export controls (Engadget):https://www.engadget.com/arm-latest-chip-designs-china-us-uk-export-controls-100235667.html
- Export Controls Block Neoverse V Chip Sale To China (National Law Review):https://natlawreview.com/article/chip-manufacturer-arm-won-t-sell-its-latest-designs-china-due-to-export-controls
- Arm to sell its new AGI CPU in China (Tom's Hardware, 2026):https://www.tomshardware.com/pc-components/cpus/arm-to-sell-its-new-agi-cpu-in-china-we-would-expect-the-demand-for-this-product-to-be-just-as-strong-in-china-as-it-is-in-the-rest-of-the-world
- US Entity List background on Huawei/HiSilicon (PIIE):https://www.piie.com/research/piie-charts/us-trying-use-export-controls-restrict-huaweis-access-semiconductors

*注:二手报道的具体措辞/数字以一手 20-F 与各公司官方公告为准;文中 $28M 坏账等数字来自 20-F,建议核实时以本地 20-F 文件内搜索为准。*
