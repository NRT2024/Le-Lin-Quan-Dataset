---
AIGC:
    Label: "1"
    ContentProducer: 001191110102MACQD9K64018705
    ProduceID: 7628902657591378182-data_volume/files/所有对话/主对话/README_YAIG_mini.md
    ReservedCode1: ""
    ContentPropagator: 001191110102MACQD9K64028705
    PropagateID: 4193982937834411#1780483412837
    ReservedCode2: ""
---
<div align="center">

# YAIG-mini 🏯

**A Structured Visual Dataset for Cultural Understanding of Chinese Classical Gardens**

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Images](https://img.shields.io/badge/Images-15%2C461-green.svg)]()

</div>

## Overview

YAIG-mini (Yuan Architectural Image & Grounding - mini) is a specialized academic dataset derived from the **Le-Lin-Quan (乐林泉) project**, for visual understanding of Chinese classical gardens — UNESCO World Heritage sites that embody unique "form-meaning-atmosphere" (形-意-境) cultural connotations.

Unlike general outdoor scene datasets, YAIG-mini addresses the **cultural blind spot** of existing computer vision resources: Chinese classical gardens require moving beyond simple object recognition to the more abstract task of **cultural cognition** — understanding the symbolic and artistic "grammar" of rockeries, water features, plants, and architecture in harmonious composition.

> **Key fact**: This is the **first** dataset with structured multi-level cultural semantic annotations specifically designed for Chinese classical gardens, filling a critical gap in cultural heritage visual understanding.

## Sample Images

<div align="center">

| Jiangnan Private Garden | Imperial Garden | Northern Private Garden |
|:---:|:---:|:---:|
| ![Suzhou Humble Administrator's Garden](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/jiangnansijiayuanlin/suzhouzhuozhengyuan/suzhouzhuozhengyuan_1.jpg) | ![Beijing Summer Palace](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/huangjiayuanlin/yiheyuan%EF%BC%88beijing%EF%BC%89/yiheyuan%EF%BC%88beijing%EF%BC%89_1.jpg) | ![Weifang Shihu Garden](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/beifangsijiayuanlin/weifangshihuyuan/weifangshihuyuan_1.jpg) |
| Suzhou Humble Administrator's Garden | Beijing Summer Palace | Weifang Shihu Garden |

| Lingnan Private Garden | Temple & Shrine Garden | Public Scenic Garden |
|:---:|:---:|:---:|
| ![Dongguan Keyuan](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/lingnansijiayuanlin/dongguankeyuan/dongguankeyuan_1.jpg) | ![Shanxi Jinci](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/siguancimiaoyuanlin/shanxitaiyuanjinci/shanxitaiyuanjinci_1.jpg) | ![Suzhou Huqiu](https://raw.githubusercontent.com/NRT2024/Le-Lin-Quan-Dataset/master/lelinquan/gonggongfengjingquyuanlin/suzhouhuqiu/suzhouhuqiu_1.jpg) |
| Dongguan Keyuan | Shanxi Taiyuan Jinci | Suzhou Huqiu |

</div>

## Dataset Statistics

| Item | Value |
|------|-------|
| Total images | 15,461 |
| L1 categories (garden types) | 6 |
| L2 sub-categories (specific gardens) | 35 |
| L1 inter-annotator agreement (κ) | 0.96 |
| L2 inter-annotator agreement (κ) | 0.88 |

## Annotation System

YAIG-mini features a **two-level hierarchical annotation system** that bridges perceptual features to cultural semantics:

```
L1: Garden Type Classification (6 categories)
 └── L2: Specific Garden Identification (35 gardens)
```

### L1: Garden Type Classification (6 categories)

| Category | Chinese | L2 Count | Example Gardens |
|----------|---------|----------|----------------|
| Northern Private Gardens | 北方私家园林 | 7 | Beijing Banmu Garden, Weifang Shihu Garden |
| Jiangnan Private Gardens | 江南私家园林 | 12 | Suzhou Humble Administrator's Garden, Suzhou Lingering Garden |
| Imperial Gardens | 皇家园林 | 5 | Beijing Summer Palace, Chengde Mountain Resort |
| Temple & Shrine Gardens | 寺观祠庙园林 | 4 | Beijing Baiyun Temple, Shanxi Jinci |
| Public Scenic Area Gardens | 公共风景名胜区园林 | 3 | Suzhou Huqiu, Hangzhou West Lake |
| Lingnan Private Gardens | 岭南私家园林 | 4 | Dongguan Keyuan, Foshan Liang Garden |

### L2: Specific Garden Identification (35 gardens)

<details>
<summary>📖 Click to expand full L2 list</summary>

**Northern Private Gardens (北方私家园林) — 7 gardens:**
Beijing Banmu Garden (北京半亩园), Beijing Chun Prince's Mansion Garden (北京醇王府园), Beijing Gong Prince's Mansion Garden (北京恭王府园), Qufu Kong Mansion Tieshan Garden (曲阜孔府铁山园), Shandong Qingzhou Ouyuan (山东青州偶园), Shaanxi Taigu Mengshizhai Garden (陕西太谷孟石斋园), Weifang Shihu Garden (潍坊十笏园)

**Jiangnan Private Gardens (江南私家园林) — 12 gardens:**
Suzhou Canglang Pavilion (苏州沧浪亭), Suzhou Huanxiu Mountain Villa (苏州环秀山庄), Suzhou Lingering Garden (苏州留园), Suzhou Couple's Garden (苏州耦园), Suzhou Lion Grove Garden (苏州狮子林), Suzhou Master of the Nets Garden (苏州网师园), Suzhou Humble Administrator's Garden (苏州拙政园), Tongli Retreat & Reflection Garden (同里退思园), Wuxi Jichang Garden (无锡寄畅园), Yangzhou Ge Garden (扬州个园), Yangzhou He Garden (扬州何园), Shanghai Yu Garden (豫园)

**Imperial Gardens (皇家园林) — 5 gardens:**
Beijing Beihai Park (北海公园), Chengde Mountain Resort (避暑山庄), Beijing Summer Palace (颐和园), Beijing Old Summer Palace Ruins Park (圆明园遗址公园), Beijing Forbidden City Imperial Garden (紫禁城御花园)

**Temple & Shrine Gardens (寺观祠庙园林) — 4 gardens:**
Beijing Baiyun Temple (北京白云观), Beijing Xishan Biyun Temple (北京西山碧云寺), Chengdu Wuhou Shrine (成都武侯祠), Shanxi Taiyuan Jinci (山西太原晋祠)

**Public Scenic Area Gardens (公共风景名胜区园林) — 3 gardens:**
Jiaxing Nanhu "Jiahe Eight Scenes" (嘉兴南湖"嘉禾八景"), Suzhou Huqiu (苏州虎丘), Hangzhou West Lake "Ten Scenes" (西湖"西湖十景")

**Lingnan Private Gardens (岭南私家园林) — 4 gardens:**
Dongguan Keyuan (东莞可园), Foshan Liang Garden (佛山梁园), Panyu Yuyin Mountain Villa (番禺余荫山房), Shunde Qinghui Garden (顺德清晖园)

</details>

## Quality Control Pipeline

All annotations undergo a rigorous **three-stage quality control process**:

```
Stage 1: Model Pre-annotation
    ↓
Stage 2: Dual-blind Cross-Review
    ↓
Stage 3: Expert Final Adjudication
```

- **Stage 1**: Pre-trained models generate initial labels
- **Stage 2**: Two independent annotators review each label without seeing each other's work
- **Stage 3**: Domain experts (landscape architecture / garden history) resolve disagreements and finalize annotations

Inter-annotator consistency metrics:
- L1: κ = 0.96 (excellent)
- L2: κ = 0.88 (strong)

## Data Format

### Directory Structure

```
lelinquan/
├── beifangsijiayuanlin/                    # L1: 北方私家园林 (7 gardens)
│   ├── beijingbanmuyuan/                    # L2: 北京半亩园
│   ├── beijingchunwangfuyuan/               # L2: 北京醇王府园
│   ├── beijinggongwangfuyuan/               # L2: 北京恭王府园
│   ├── qufukongfutieshanyuan/               # L2: 曲阜孔府铁山园
│   ├── shandongqingzhououyuan/              # L2: 山东青州偶园
│   ├── shanxitaigumengshizhaiyuan/          # L2: 陕西太谷孟石斋园
│   └── weifangshihuyuan/                    # L2: 潍坊十笏园
├── gonggongfengjingquyuanlin/               # L1: 公共风景名胜区园林 (3 gardens)
│   ├── jiaxingnanhu"jiahebajing"/           # L2: 嘉兴南湖"嘉禾八景"
│   ├── suzhouhuqiu/                         # L2: 苏州虎丘
│   └── xihu"xihushijing"/                  # L2: 西湖"西湖十景"
├── huangjiayuanlin/                         # L1: 皇家园林 (5 gardens)
│   ├── beihaigongyuan（beijing）/            # L2: 北海公园
│   ├── bishushanzhuang/                     # L2: 避暑山庄
│   ├── yiheyuan（beijing）/                  # L2: 颐和园
│   ├── yuanmingyuanyizhigongyuan（beijing）/  # L2: 圆明园遗址公园
│   └── zijinchengyuhuayuan/                # L2: 紫禁城御花园
├── jiangnansijiayuanlin/                    # L1: 江南私家园林 (12 gardens)
│   ├── suzhoucanglangting/                  # L2: 苏州沧浪亭
│   ├── suzhouhuanxiushanzhuang/             # L2: 苏州环秀山庄
│   ├── suzhouliuyuan/                       # L2: 苏州留园
│   ├── suzhououyuan/                        # L2: 苏州耦园
│   ├── suzhoushizilin/                      # L2: 苏州狮子林
│   ├── suzhouwangshiyuan/                   # L2: 苏州网师园
│   ├── suzhouzhuozhengyuan/                 # L2: 苏州拙政园
│   ├── tonglituisiyuan/                     # L2: 同里退思园
│   ├── wuxijichangyuan/                     # L2: 无锡寄畅园
│   ├── yangzhougeyuan/                      # L2: 扬州个园
│   ├── yangzhouheyuan/                      # L2: 扬州何园
│   └── yuyuan/                              # L2: 豫园
├── lingnansijiayuanlin/                     # L1: 岭南私家园林 (4 gardens)
│   ├── dongguankeyuan/                      # L2: 东莞可园
│   ├── foshanliangyuan/                     # L2: 佛山梁园
│   ├── panyuyuyinshanfang/                  # L2: 番禺余荫山房
│   └── shundeqinghuiyuan（foshan）/          # L2: 顺德清晖园
└── siguancimiaoyuanlin/                     # L1: 寺观祠庙园林 (4 gardens)
    ├── beijingbaiyunguan/                   # L2: 北京白云观
    ├── beijingxishanbiyunsi/                # L2: 北京西山碧云寺
    ├── chengduwuhouci/                      # L2: 成都武侯祠
    └── shanxitaiyuanjinci/                  # L2: 山西太原晋祠
```

### Annotation Format

**L1/L2 Classification** (JSON):
```json
{
  "image_id": "JN_HZG_0001",
  "L1_label": "Jiangnan Private Gardens",
  "L2_label": "Suzhou Humble Administrator's Garden",
  "source": "web_crawl",
  "split": "train"
}
```

## Supported Research Tasks

- ✅ Multi-level garden image classification (L1/L2)
- ✅ Self-supervised representation learning for cultural heritage
- ✅ Hierarchical cultural cognition modeling
- ✅ Digital heritage activation and intelligent retrieval
- ✅ Architectural visual intelligence

## Future Work

- 🔜 **L3: Object Detection** — Bounding box annotations for key garden elements (architecture, water features, rockery, plants, decorative elements) in COCO format
- 🔜 Expanded annotation for thematic concepts (e.g., 借景 framed views, 框景 window framing) and philosophical principles (e.g., 天人合一 harmony between man and nature)

## Acknowledgments

We thank the landscape architecture experts who participated in the quality control process. Image sources include public tourism platforms, museum archives, and professional field photography — all used in accordance with their respective access policies.

---

<div align="center">

**YAIG-mini — Bridging Computer Vision and Cultural Heritage** 🏯

</div>

---

> 本内容由 Coze AI 生成，请遵循相关法律法规及《人工智能生成合成内容标识办法》使用与传播。
