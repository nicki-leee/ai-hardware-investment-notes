---
type: industry-note
sector: 存储
tags: [AI投资, HBM, 存储, Micron, SK-hynix, Samsung, NVIDIA]
updated: 2026-06-25
---

# HBM需求端与订单格局

## 一句话结论
HBM 需求端仍在快速上升，订单增量来自 NVIDIA GPU 平台，也来自 Google、AWS、Broadcom/Marvell 等 ASIC 生态和云厂商自研芯片。供应端最可能发生的不是“Micron 订单越来越多、SK hynix 订单越来越少”，而是 Micron 份额上升、SK hynix 从极高份额回落一点，但绝对出货仍增长。

## 谁的订单在上升

### 1. Micron
Micron 的边际变化最明显。

已看到的信号：
- Micron 已开始量产/出货面向 NVIDIA Vera Rubin 的 HBM4 36GB 12H。
- Micron 披露其 2026 HBM 供应已经完成价格和数量谈判。
- Micron 数据中心收入占比显著提升，HBM、DDR、数据中心 SSD 共同拉动。

怎么理解：
- Micron 过去在 HBM 份额上落后于 SK hynix，现在正在从低基数快速追赶。
- 订单“增速”可能很高，但不代表立刻取代 SK hynix。
- 对 Micron 来说，核心是 HBM 认证、良率、产能扩张和客户长期协议。

### 2. SK hynix
SK hynix 仍是当前 HBM 龙头，尤其在 HBM3E 和早期 HBM4 供应上优势明显。

已看到的信号：
- 多家机构估计 SK hynix 仍占 HBM 市场最高份额。
- SK hynix 自身材料引用外部机构观点，认为其 HBM3E 领导地位会延续到 HBM4。
- HBM3E 在 2026 仍是 AI 服务器和数据中心主流产品，HBM4 逐步放量。

怎么理解：
- SK hynix 的风险不是“没订单”，而是高份额被 Micron 和 Samsung 稀释。
- 如果行业总需求高速增长，即便份额从 60% 降到 50%，绝对收入仍可能增长。
- 真正要警惕的是良率、价格、客户份额和下一代产品节奏被追上。

### 3. Samsung
Samsung 是潜在修复项。

已看到的信号：
- Samsung 在 HBM 高端认证上曾落后，但仍是全球 DRAM 大厂。
- 一旦 HBM4 或 HBM4E 认证取得突破，订单弹性可能很大。

怎么理解：
- Samsung 更像“份额修复期权”。
- 如果认证顺利，可能同时挤压 SK hynix 和 Micron 的份额。
- 但短期仍要看认证、良率和客户实际导入。

## 需求端来自哪里

```text
云厂商 CapEx
  -> NVIDIA GPU / AMD GPU / 自研 ASIC
  -> 每颗加速器需要 HBM
  -> HBM 供应商：SK hynix、Micron、Samsung
```

主要需求来源：
- NVIDIA：最大、最关键的 HBM 需求牵引者。
- AMD：Instinct GPU 放量也需要 HBM。
- Google、AWS、Meta、Microsoft 等云厂商：既买 NVIDIA，也做自研 ASIC。
- Broadcom、Marvell 等 ASIC/互连公司：受益于云厂商定制芯片，间接拉动 HBM。

## 会不会出现 Micron 越来越多、SK hynix 越来越少

### 更可能的情况
Micron 订单增加，SK hynix 份额下降但绝对订单不一定下降。

原因：
1. HBM 总需求还在扩张。
2. NVIDIA 和云厂商不希望单一供应商卡脖子。
3. Micron 从低基数追赶，边际增速自然更高。
4. SK hynix 仍有先发优势、客户绑定和量产经验。

### 什么时候 SK hynix 订单会真的下降
需要同时出现几类信号：
- HBM 总需求开始放缓。
- Micron 或 Samsung 在性能、功耗、良率、价格上明显优于 SK hynix。
- NVIDIA 或大客户的新平台分配明显转向 Micron/Samsung。
- SK hynix 扩产、良率或产品迭代出问题。

单看“Micron 拿到更多订单”，不能直接推出“SK hynix 订单下降”。

## 美国因素会不会让 NVIDIA 转向 Micron

美国因素会让 Micron 获得战略加分，但很难单独决定 HBM 采购。

可能起作用的地方：
- 美国 CHIPS Act 和本土制造支持。
- 数据中心供应链安全和地缘政治考量。
- NVIDIA 作为美国公司，天然愿意提高美国供应商占比，降低供应链风险。

但约束也很硬：
- HBM 必须和 GPU/ASIC、封装、基板、散热、电源设计一起验证。
- 性能、功耗、良率、交付能力比国别更直接。
- SK hynix 是韩国公司，韩国是美国半导体盟友，不是需要被替代的“不可信供应商”。
- HBM 极度短缺时，NVIDIA 更需要多供应商，而不是主动放弃成熟供应商。

所以更合理的判断是：
- NVIDIA 会提高 Micron 的战略地位。
- NVIDIA 会推动 Micron、SK hynix、Samsung 多源化。
- 但不会因为 Micron 是美国公司，就在技术和供给没有优势时强行替换 SK hynix。

## 投资跟踪指标

### Micron
- HBM4/HBM4E 出货节奏。
- 2026/2027 HBM 供应是否继续 sold out。
- 数据中心收入占比。
- HBM 毛利率。
- 与 NVIDIA、云厂商的长期协议。

### SK hynix
- HBM3E 份额是否维持。
- HBM4 客户分配。
- 与 TSMC 先进封装合作。
- 良率和交付节奏。
- HBM 与普通 DRAM 之间的产能分配。

### Samsung
- NVIDIA/AMD/ASIC 客户认证进度。
- HBM4 或 HBM4E 是否成功放量。
- Memory 业务利润率修复。
- Foundry 与 HBM base die/封装协同。

## 当前结论
HBM 的订单上升不是单一公司故事，而是 AI 算力平台从 GPU 扩展到 ASIC 后带来的结构性需求。Micron 的边际变化最大，SK hynix 的存量地位最强，Samsung 是潜在修复项。

投资上不要只问“谁赢谁输”，更要拆成三层：
1. HBM 总需求是否继续上修。
2. 三家供应商的份额如何变化。
3. 份额变化能否转化成收入、毛利率和现金流。

