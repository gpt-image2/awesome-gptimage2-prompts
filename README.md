
# 🚀 Awesome GPT Image 2 Prompts


> 🎨 A curated collection of creative prompts for OpenAI's GPT Image 2

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`
> Attribution / 署名: This repository includes adapted material from [YouMind-OpenLab/awesome-gpt-image-2](https://github.com/YouMind-OpenLab/awesome-gpt-image-2) by YouMind OpenLab, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
> Copyright (c) 2026 YouMind OpenLab. Changes were made in this repository. See [ATTRIBUTION.md](ATTRIBUTION.md).

---

[![English](https://img.shields.io/badge/English-Current-brightgreen)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Click%20to%20View-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 Table of Contents

- [🤔 What is GPT Image 2?](#-what-is-gpt-image-2)
- [📊 Statistics](#-statistics)
- [🔥 Featured Prompts](#-featured-prompts)
- [📋 All Prompts](#-all-prompts)

---

## 🤔 What is GPT Image 2?

**GPT Image 2** (codename **"duct-tape"**) is OpenAI's next-generation image model. Community testing highlights a leap in these areas:

- 🎯 **Pixel-Perfect Text Rendering** — Native-quality text in Chinese, English, and Japanese, no typos or warped glyphs
- 🎨 **Cross-Image Consistency** — The same character, style, or IP stays identical across a series, down to the pixel
- ⚡ **Commercial-Grade Illustration** — Illustration output is ready to ship without manual polish
- 🌈 **True Art Style Induction** — Creatively evokes the feeling of a style rather than merely approximating references
- 🔧 **Storyboard & Product Series** — Ideal for storyboards, IP characters, and multi-panel product visuals
- 📐 **Multi-Language Design** — Social cards, banners, and posters with accurate multilingual typography in one shot

📚 **Learn More:** See community testing in our [report summary](docs/FAQ.md)

### 🚀 Raycast Integration

Some prompts support **dynamic arguments** using [Raycast Snippets](https://raycast.com/help/snippets) syntax. Look for the 🚀 Raycast Friendly badge!

**Example:**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

When used in Raycast, you can dynamically replace the arguments for quick iterations!

---

## 📊 Statistics

<div align="center">

| Metric | Count |
|--------|-------|
| 📝 Total Prompts | **1123** |
| ⭐ Featured | **6** |
| 🔄 Last Updated | **Thursday, April 23, 2026 at 1:28:30 AM UTC** |

</div>

---

## 🔥 Featured Prompts

> ⭐ Hand-picked by our team for exceptional quality and creativity

### No. 1: VR Headset Exploded View Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a high-tech exploded view diagram of a VR headset with detailed component callouts and promotional text.

#### 📝 Prompt

```
{
  "type": "exploded view product diagram poster",
  "subject": "VR headset",
  "style": "clean high-tech 3D render, studio lighting, glowing accents",
  "background": "{argument name=\"background color\" default=\"soft purple and blue gradient\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"まったく新しい現実を、まったく新しい構造から。\"}"
  },
  "layout": {
    "centerpiece": "vertically stacked exploded view of a VR headset showing 9 distinct layers of internal components: outer shell, camera sensors, motherboard with chip, pancake lenses, internal frame, battery packs, side straps, top strap, and facial interface cushion.",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\n圧倒的な処理性能でリアルタイムな体験を。",
        "調整可能なIPD機構\n幅広いユーザーに快適なフィット感を。",
        "精密設計されたヘッドストラップ\n快適さと安定性を追求したエルゴノミクス。"
      ],
      "right_side": [
        "フェイスプレート\n洗練されたデザインと最適な重量バランス。",
        "トラッキングカメラ\n高精度な位置トラッキングと環境認識を実現。",
        "パンケーキレンズ\n薄型設計で広い視野角と鮮明な映像を提供。",
        "高性能バッテリー\n長時間駆動を支える最適化された電源設計。",
        "柔らかなフェイスインターフェース\n長時間でも快適な装着感を実現。"
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "{argument name=\"bottom headline\" default=\"体験は、構造から進化する。\"}",
        "body": "一つひとつのパーツに、没入体験を支える最先端テクノロジーとこだわりの設計。Meta Quest 3は、未来を感じさせる体験を内部から生み出しています。"
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="VR Headset Exploded View Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [wory＠ホッピング中](https://x.com/wory37303852)
- **Source:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **Published:** April 19, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13460)**

---

### No. 2: Illustrated City Food Map

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a hand-drawn, watercolor-style tourist map featuring numbered local food specialties, landmarks, and a legend.

#### 📝 Prompt

```
{
  "type": "illustrated map infographic",
  "style": "{argument name=\"art style\" default=\"watercolor and ink hand-drawn illustration on vintage parchment\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"成都\"} {argument name=\"map title\" default=\"吃货暴走地图\"}",
    "mascot": "cartoon red chili pepper wearing sunglasses and giving a thumbs up"
  },
  "border": "{argument name=\"border decoration\" default=\"vine of green leaves and red chili peppers\"}",
  "layout": {
    "background": "textured beige parchment paper with yellow roads, blue rivers, and green park areas",
    "sections": [
      {
        "title": "landmarks",
        "count": 6,
        "illustrations": ["traditional pavilion", "traditional monastery", "modern skyscraper with climbing panda", "tall TV tower", "traditional gate", "industrial buildings"],
        "labels": ["人民公园", "文殊院", "IFS", "339电视塔", "宽窄巷子", "东郊记忆"]
      },
      {
        "title": "food_spots",
        "count": 12,
        "illustrations": ["mapo tofu", "dumplings in chili oil", "skewers in pot", "sticky rice balls", "egg baking cake", "nine-grid hotpot", "sweet potato noodles", "cold skewers", "spicy mixed dish", "covered tea bowl", "ice jelly dessert", "spicy rabbit heads"],
        "labels": ["1 陈麻婆豆腐", "2 钟水饺", "3 春熙路", "4 宽窄巷子·三大炮", "5 建设路·叶婆婆蛋烘糕", "6 玉林路·小龙坎火锅", "7 香香巷·肥肠粉", "8 武侯祠大街·钵钵鸡", "9 东郊记忆·冒椒火辣", "10 人民公园·鹤鸣茶社", "11 锦里古街·冰粉", "12 双流老妈兔头"]
      },
      {
        "title": "图例",
        "position": "bottom-right",
        "count": 5,
        "items": ["red dot", "green house", "green tree", "blue line", "yellow double line"],
        "labels": ["美食地点", "地标景点", "公园绿地", "河流湖泊", "主要道路"]
      }
    ],
    "centerpiece": "giant panda sitting and eating bamboo",
    "bottom_right_extras": ["vintage compass rose with N, S, E, W", "disclaimer text '温馨提示：吃辣需谨慎，肠胃要保护~' with a red chili pepper icon"]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="Illustrated City Food Map - Image 1">
</div>

#### 📌 Details

- **Author:** [皮皮特](https://x.com/mm_zzm44854)
- **Source:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **Published:** April 19, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13515)**

---

### No. 3: Momotaro Explainer Slide in Hybrid Style

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt that combines the simple, warm aesthetic of Irasutoya illustrations with the high-information density characteristic of Japanese government slides.

#### 📝 Prompt

```
Create an explanatory slide ({argument name="format" default="ponchi-e diagram"}) for {argument name="theme" default="Momotaro"} that fuses the gentle atmosphere of "Irasutoya" with the overwhelming information density of "Kasumigaseki slides".
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="Momotaro Explainer Slide in Hybrid Style - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="Momotaro Explainer Slide in Hybrid Style - Image 2">
</div>

#### 📌 Details

- **Author:** [やまもん](https://x.com/yammamon)
- **Source:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **Published:** April 19, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=13983)**

---

### No. 4: E-commerce Live Stream UI Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a realistic social media live stream interface overlaying a portrait, featuring customizable chat messages, gift popups, and a product purchase card.

#### 📝 Prompt

```
{
  "type": "live stream UI mockup",
  "subject": {
    "description": "portrait of {argument name=\"host name\" default=\"Elon Musk\"}, smiling, wearing a black t-shirt with a white technical schematic graphic",
    "background": "left side shows a screen with '{argument name=\"left background logo\" default=\"SPACEX\"}' text, right side shows a red '{argument name=\"right background logo\" default=\"Tesla T logo\"}' and a dark car"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "avatar, name '{argument name=\"host name\" default=\"Elon Musk\"}', subtext '55.6万本场点赞', red '关注' button",
      "rank_badge": "gold coin icon with '全站第1名'",
      "viewer_stats": "3 top viewer avatars with '12.3w', '8.6w', '5.7w', total '68.7万', 'X' close button",
      "right_links": "'更多直播 >', '礼物展馆 0/24' with blue '经典' tag"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "avatar '科技爱好者', '送小心心', heart icon x 1314",
        "avatar '星辰大海', '送火箭', rocket icon x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "level 37 badge '宇宙漫游者 加入了直播间'",
      "message_count": 7,
      "messages": [
        "小火箭: 马斯克！未来可期！🚀",
        "future: 特斯拉Model 2什么时候出？",
        "星空梦想家: SpaceX今年能上火星吗？",
        "AI探索者: Neuralink进展如何？",
        "帅气的网友: 马总好！",
        "Mars: 第一次来你的直播，超激动！",
        "用户123: 讲讲AI吧，会取代人类吗？"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "orange '热卖 x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"特斯拉Cybertruck 电动皮卡\"}",
      "price": "{argument name=\"product price\" default=\"¥ 1,618,000\"}",
      "button": "red '抢' button",
      "floating_animation": "translucent hearts floating up the right edge"
    },
    "bottom_bar": {
      "input_field": "'说点什么...'",
      "icons": ["smiley face", "three dots", "shopping cart", "gift box", "share"]
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="E-commerce Live Stream UI Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [神经病不想好转](https://x.com/sjbbxhz)
- **Source:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **Published:** April 19, 2026
- **Languages:** en
- [PromptImage](https://promptimage.cloud) - Free AI image & video studio with a prompt library (signup credits, multi-model). Freemium

**[👉 Try it now →](https://gptimage2api.net/?id=14036)**

---

### No. 5: Anime Martial Arts Battle Illustration

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a dynamic, high-impact anime illustration of two female characters fighting in a traditional dojo with elemental energy effects.

#### 📝 Prompt

```
An anime-style illustration of a {argument name="action type" default="high-impact martial arts battle"} between two young female fighters in a {argument name="setting" default="traditional wooden martial arts dojo"}. In the foreground, a girl with black hair in a high bun wears a {argument name="character 1 color theme" default="red and white"} Chinese-style martial arts outfit with baggy pants. She is in a dynamic, low, forward-thrusting stance, surrounded by swirling red energy and water splashes. In the background to the right, a girl with light purple hair in twin buns wears a {argument name="character 2 color theme" default="green and purple"} Chinese dress with gold embroidery and black tights. She is leaping through the air in a flying kick pose, surrounded by swirling blue energy. The wooden floorboards are splintering from the intense impact, with debris and dust flying through the air. Above them hangs a weathered wooden sign with the text "{argument name="sign text" default="武術会"}". The scene features dramatic lighting, a low-angle dynamic perspective, and intense action effects.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="Anime Martial Arts Battle Illustration - Image 1">
</div>

#### 📌 Details

- **Author:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **Source:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13467)**

---

### No. 6: 3D Stone Staircase Evolution Infographic

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Transforms a flat evolutionary timeline into a realistic 3D stone staircase infographic with detailed organism renders and structured side panels.

#### 📝 Prompt

```
{
  "type": "evolutionary timeline infographic",
  "instruction": "Using REFERENCE_0 as a structural base, transform the flat vector design into a highly realistic 3D infographic. Replace the smooth ramps with distinct stone steps and upgrade all organisms to photorealistic 3D models.",
  "style": {
    "background": "{argument name=\"background style\" default=\"vintage textured parchment paper\"}",
    "staircase": "{argument name=\"staircase material\" default=\"realistic textured stone blocks\"}",
    "subjects": "{argument name=\"organism style\" default=\"highly detailed photorealistic 3D renders\"}"
  },
  "layout": {
    "main_title": "{argument name=\"main title\" default=\"人类演化\"}",
    "sections": [
      {
        "position": "left sidebar",
        "count": 8,
        "labels": ["L0: 单细胞生命", "L1: 多细胞生物", "L2: 动物界", "L3: 脊索动物", "L4: 上陆革命", "L5: 哺乳纲", "L6: 人科演化", "L7: 智人纪元"]
      },
      {
        "position": "top right",
        "title": "获得的功能 / 失去的功能",
        "description": "Legend with plus and minus icons"
      },
      {
        "position": "bottom center",
        "title": "演化关键里程碑",
        "count": 6,
        "description": "Timeline with a silhouette graphic of 6 figures showing ape-to-human evolution"
      }
    ],
    "centerpiece": {
      "description": "Winding stone staircase with 25 numbered steps featuring specific organisms.",
      "count": 25,
      "notable_elements": [
        "Step 07: Jellyfish",
        "Step 09: Ammonite",
        "Step 10: Trilobite",
        "Step 24: Walking human",
        "Step 25: {argument name=\"future evolution concept\" default=\"glowing cosmic silhouette with a question mark\"}"
      ]
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="3D Stone Staircase Evolution Infographic - Image 1">
</div>

#### 📌 Details

- **Author:** [知识猫图解](https://x.com/GeekCatX)
- **Source:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **Published:** April 19, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13491)**

---

## 📋 All Prompts

> 📝 Sorted by publish date (newest first)

### No. 1: Profile / Avatar - Overhead Mirror Selfie with Exaggerated Poses

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt testing character consistency and dynamic expressions in a mirror selfie from a top-down perspective.

#### 📝 Prompt

```
{argument name="number of people" default="Three people"} in front of a mirror from a top perspective taking a group photo in {argument name="pose type" default="exaggerated poses"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="Profile / Avatar - Overhead Mirror Selfie with Exaggerated Poses - Image 1">
</div>

#### 📌 Details

- **Author:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Source:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **Published:** April 22, 2026
- **Languages:** zh

**[👉 Try it now →](https://gptimage2api.net/?id=14341)**

---

### No. 2: Profile / Avatar - Seated Brown Monochrome Studio Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a photorealistic indoor fashion portrait of a seated woman in a coordinated brown outfit, suitable for editorial lifestyle or apparel imagery.

#### 📝 Prompt

```
A realistic studio portrait of a young East Asian woman seated on a simple black folding chair, framed from upper thighs to head in a vertical composition. She has {argument name="hair color" default="dark brown"} hair parted near the center and tied back into a low ponytail, with a few soft strands near the ears, small delicate earrings, fair smooth skin, and a calm neutral pose with her hands resting together between her knees. She wears a fitted ribbed zip-front crop top in {argument name="top color" default="deep chocolate brown"} with a pointed collar, three-quarter sleeves, and the zipper partly open to create a deep neckline, paired with high-waisted straight-leg pants in a matching {argument name="pants color" default="warm brown"}. The styling is monochrome brown-on-brown, with subtle fabric texture and natural body contours. The background is a soft off-white draped fabric backdrop with gentle folds, lit by diffused natural-looking window light for a clean, soft, editorial indoor look. Photorealistic, shallow depth of field, soft shadows, understated fashion portrait, minimal set, centered subject, relaxed seated posture, high detail skin and fabric texture.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="Profile / Avatar - Seated Brown Monochrome Studio Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14628)**

---

### No. 3: Profile / Avatar - Photoreal School Uniform Shrine Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a polished photorealistic portrait of a young woman in a school uniform outdoors, ideal for editorial fashion, character visuals, or lifestyle-style AI portraits.

#### 📝 Prompt

```
A photorealistic waist-up portrait of a {argument name="subject" default="young woman"} standing outdoors in bright natural sunlight, framed in a vertical composition. She has long, straight {argument name="hair color" default="dark brown"} hair with a glossy shine, parted slightly off center, falling over both shoulders. She wears a crisp white short-sleeve school uniform shirt with a structured collar, a navy blue striped necktie, and a detailed embroidered crest patch on the left chest pocket featuring a crown and heraldic emblem. Pose her at a slight three-quarter angle with relaxed posture, her head turned subtly to the side for a refined candid fashion-photo feel. Place her in front of vivid {argument name="background setting" default="red shrine architecture"} with rich red pillars and a curved blue roof detail visible in the blurred background, using shallow depth of field and creamy bokeh to keep the subject sharply in focus. The lighting should be clean, high-contrast, and flattering, with bright highlights on the hair and shirt, realistic fabric folds, natural skin tones, and a polished premium portrait aesthetic reminiscent of Japanese commercial photography.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="Profile / Avatar - Photoreal School Uniform Shrine Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [AIおじさん](https://x.com/AIojisan1952)
- **Source:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14515)**

---

### No. 4: Profile / Avatar - Moody Censored Indoor Selfie Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a photorealistic stylish selfie of a young man in a dark open-collar shirt by a window, useful for creating believable social-media portrait photos.

#### 📝 Prompt

```
A realistic indoor selfie-style portrait of a young East Asian man from the chest up, seated near a large modern window in a high-rise apartment or hotel room during soft daylight. He has {argument name="hair color" default="black"} hair, thick and slightly tousled with a center part and soft volume over the forehead and sides. His build appears slim, with a long neck and smooth light skin. He wears a {argument name="shirt color" default="black"} button-up shirt made of matte cotton or poplin, slightly oversized, with the top several buttons undone to create a deep open collar and relaxed, casual styling. The camera is held close in a natural selfie angle, portrait orientation, framing the shoulders, chest, neck, and head. His face is fully obscured by a large centered rectangular blur or mosaic censor block, while the ears, jawline edges, neck, and hair remain visible. The mood is understated, moody, and elegant, with muted neutral colors, soft window light from the right side, gentle shadows, and a candid social-media selfie feeling. Background details include 1 beige wall section on the left, 1 small dark wall control panel, 1 vertical metallic trim or lamp edge, and 2 tall dark-framed window panels on the right with a faint out-of-focus city skyline outside. Photorealistic smartphone photo, clean modern interior, shallow depth of field, natural skin texture, subtle contrast, no smile visible because of the censor block, minimal editing, stylish and believable personal selfie.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="Profile / Avatar - Moody Censored Indoor Selfie Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [MathMedix](https://x.com/MathMedix)
- **Source:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14686)**

---

### No. 5: Profile / Avatar - Realistic McDonald's Selfie Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a photorealistic casual selfie of a man inside a McDonald's, useful for creating believable social-media-style restaurant snapshots.

#### 📝 Prompt

```
A highly realistic casual smartphone selfie taken indoors at a McDonald's restaurant in Asia, framed as a chest-up portrait of a young man seated at a table. The camera is held slightly above table height at arm’s length, creating a natural front-facing selfie perspective with one forearm extending toward the lens. The subject wears a black T-shirt with a small white Tesla logo on the left chest, has short straight black hair, thin dark eyeglass frames partly visible, and rests one hand lightly against his chin in a relaxed pose. His face is fully obscured by a large solid rectangular blur block in the center, preserving privacy while leaving the hair, ears, jawline edges, and glasses arms visible. In the lower left foreground sits 1 white McDonald's paper drink cup with a lid and a white straw, cropped by the frame. The background shows the restaurant counter area with warm ambient lighting, 1 large red wall panel on the left featuring the yellow McDonald's arches and the white slogan “i’m lovin’ it” with Chinese text below, 4 illuminated digital menu boards across the top displaying burgers, fries, combo meals, prices, and Chinese text, plus 2 people in the background near the counter, one facing away with a backpack and another partially visible behind the register. Use natural color balance, slight indoor grain, realistic reflections, shallow to moderate depth of field, and the candid look of an unstaged social media snapshot.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="Profile / Avatar - Realistic McDonald's Selfie Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Source:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14433)**

---

### No. 6: Profile / Avatar - Albedo Cosplay Instagram Snapshot

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A concise prompt for generating a rebellious and expressive cosplay photo in the style of an Instagram story.

#### 📝 Prompt

```
Style: An Instagram story snapshot of an {argument name="character" default="Albedo"} cosplay; Content: {argument name="action" default="squatting on the ground facing the camera, making exaggerated rebellious gestures with both hands, rolling eyes, with an arrogant and disdainful expression"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="Profile / Avatar - Albedo Cosplay Instagram Snapshot - Image 1">
</div>

#### 📌 Details

- **Author:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **Source:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **Published:** April 21, 2026
- **Languages:** zh

**[👉 Try it now →](https://gptimage2api.net/?id=14347)**

---

### No. 7: Profile / Avatar - Sunset Catgirl School Rooftop Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A cinematic anime-style rooftop portrait of a cat-eared schoolgirl at sunset, ideal for nostalgic key visuals, character art, or social media showcase images.

#### 📝 Prompt

```
A high-quality anime illustration of a {argument name="character type" default="cat-eared schoolgirl"} leaning forward over a metal school rooftop railing at sunset, shown from a slightly low, close three-quarter angle. She has long flowing {argument name="hair color" default="dark brown"} hair with soft highlights, large reflective gray-brown eyes, round thin-rim glasses, and 2 fluffy cat ears emerging from her hair. Her expression is quiet, wistful, and slightly shy, with parted lips and a gentle downward gaze toward the viewer. She wears a Japanese sailor school uniform with a soft {argument name="uniform color" default="pink"} long-sleeve top, a gray sailor collar with white stripes, a vivid red neckerchief bow, and a plaid skirt partially visible, with 2 dark backpack straps over her shoulders. The scene is drenched in dramatic golden-hour backlighting, with intense warm rim light along her hair, ears, shoulders, and sleeves, glowing sun flare from the lower left, and a richly painted sky full of orange and peach clouds. In the background, show a 2-story Japanese school building with a red-tiled roof and glowing windows lit by the sunset. Emphasize nostalgic early-2000s high-end anime key visual quality, delicate linework, luminous eyes, detailed hair strands, cinematic composition, soft depth of field, vibrant warm color grading, polished shading, and an emotional serene atmosphere.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="Profile / Avatar - Sunset Catgirl School Rooftop Anime - Image 1">
</div>

#### 📌 Details

- **Author:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **Source:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14547)**

---

### No. 8: Profile / Avatar - Fantasy Woman Hugging a White Ram

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a realistic medieval-fantasy portrait of a red-haired woman embracing a horned white ram, ideal for atmospheric character art or editorial-style fantasy visuals.

#### 📝 Prompt

```
A photorealistic, cinematic vertical portrait of a medieval or fantasy woman with {argument name="hair color" default="long copper-red hair"}, shown from the chest up, gently embracing a large white ram. The woman wears a dark moss-green wool dress or tunic with ornate embroidered cuffs and a heavy fur-trimmed cloak or shawl over her shoulders, evoking a Viking or highland aesthetic. Her hair is thick, wavy, and slightly windblown, with small braids woven into the crown. The ram has dense curly cream-white fleece, a calm expression with eyes closed, and prominent spiral horns curling outward and forward. The woman’s hand rests tenderly at the ram’s neck, conveying warmth, protection, and companionship. Set outdoors in a rugged, overcast landscape with softly blurred hills or moorland in the background, cool gray sky, shallow depth of field, natural diffused lighting, rich texture detail in hair, wool, fur, and fabric, earthy muted color palette, intimate framing, realistic skin and animal features. Add black text in the top-left corner reading {argument name="corner text" default="GPT Image 2"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="Profile / Avatar - Fantasy Woman Hugging a White Ram - Image 1">
</div>

#### 📌 Details

- **Author:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **Source:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14619)**

---

### No. 9: Profile / Avatar - Pink Kawaii Idol Lipstick Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a sparkling anime idol-style portrait for posters, social media art, or cute character key visuals.

#### 📝 Prompt

```
A highly detailed glossy anime idol portrait in a vertical composition, showing a cute teenage girl from the waist up in a dreamy pink kawaii aesthetic. She has {argument name="hair color" default="pastel pink"} hair styled in a very long voluminous high ponytail with soft bangs and flowing curled strands, decorated with multiple small heart clips and crossed hairpins. Her eyes are large, sparkling, and vivid {argument name="eye color" default="emerald green"}, with star-like highlights, long lashes, and a slightly teary shine. She has a soft blush, tiny glossy lips, and an affectionate expression while applying {argument name="lipstick color" default="bright pink"} lipstick, holding the lipstick tube delicately with both hands near her mouth. She wears a frilly black-and-pink gothic lolita idol dress with lace, ribbons, bows, heart ornaments, and sparkling textures, plus 1 black lace bow headband with a pink jeweled heart, 3 visible hair accessories on her bangs, 1 pair of dangling heart earrings, and 1 black choker with a small heart charm. Surround the character with a glowing, glitter-filled, candy-pink background full of bokeh, sparkles, soft neon light effects, and idol-fan atmosphere. Add 5 glowing hand-drawn heart text bubbles in Japanese around her, reading: "かわいすぎてごめん…♡", "推してくれてありがとうっ♡", "ずーっとだいすきっ♡", "世界でいちばんの推しになってね…♡", and "ずっと一緒だよ？約束ね…♡". Include a small decorated photo card or poster of the same girl in the upper right background. Ultra-polished illustration, dense shimmer, romantic lighting, glossy highlights, intricate lace detail, soft-focus background, saturated pink palette, adorable idol poster feel.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="Profile / Avatar - Pink Kawaii Idol Lipstick Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [ねね*AIcreator](https://x.com/NeneneAI)
- **Source:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14606)**

---

### No. 10: Profile / Avatar - Minimal Pelican Riding Bicycle

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a sparse geometric vector illustration of a pelican on a bicycle, useful for testing simple shape composition or creating a playful abstract icon-style image.

#### 📝 Prompt

```
A minimalist vector-style illustration on a flat light gray background showing a pelican riding a bicycle, drawn from simple geometric shapes with thick dark charcoal outlines. The composition is wide and centered, with the bicycle occupying the lower two-thirds of the image and the bird’s head floating slightly above and forward of the handlebars in a deliberately abstract, diagram-like way. The bicycle is a simple black road-bike silhouette in side view with exactly 2 large wheels, each with a thick outer rim and exactly 4 visible spoke lines forming a cross, a straight horizontal ground line beneath both wheels, a triangular frame, a short black saddle, and simplified crank and pedal details near the rear of the frame. The pelican is constructed from clean abstract pieces: a white rounded head with a small black circular eye, a long open beak pointing left made of 2 parts with an upper orange triangular section and a lower pale pink pouch section, a short dark curve on top of the head, a small separate white oval neck/body connector, a larger white rounded body positioned over the bike, and a single white wing-like shape angled upward over the back. Add exactly 2 orange leg shapes, long narrow rectangles leaning downward from the body toward the bicycle frame, suggesting the bird is pedaling. Keep the forms intentionally sparse and slightly surreal, like a logo test or simple code-editor doodle, with no shading, no gradients, no textures, no text, and lots of negative space.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="Profile / Avatar - Minimal Pelican Riding Bicycle - Image 1">
</div>

#### 📌 Details

- **Author:** [Justin Schroeder](https://x.com/jpschroeder)
- **Source:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14657)**

---

### No. 11: Profile / Avatar - Cat to Human Portrait Transformation

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt converts a cat reference photo into a photorealistic human version while preserving the original pose, composition, and setting for playful pet-to-person portraits.

#### 📝 Prompt

```
Using the provided reference image, turn the cat into a realistic human portrait while keeping the same lounging pose, camera angle, framing, and the same plush turquoise chair background. Preserve the cat’s orange-and-white color pattern as inspiration for the human look: make the person a fair-skinned young woman with warm ginger hair and a soft, calm expression. Dress her in cozy off-white loungewear: 1 loose knit V-neck sweater and 1 pair of cream drawstring pants, seated naturally in the chair with relaxed body language. Make it photorealistic, soft natural indoor lighting, editorial lifestyle photo quality.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="Profile / Avatar - Cat to Human Portrait Transformation - Image 1">
</div>

#### 📌 Details

- **Author:** [Bojan Tunguz](https://x.com/tunguz)
- **Source:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14670)**

---

### No. 12: Profile / Avatar - Studio Portrait With Strawberry Ice Cream

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a sleek celebrity-style studio portrait of a dark-haired woman holding a strawberry ice cream cone in front of her face, ideal for editorial beauty or pop-culture imagery.

#### 📝 Prompt

```
A polished studio portrait of a glamorous pop-star-like woman from the chest up, centered against a smooth neutral gray backdrop. She has {argument name="hair color" default="jet black"} long loose wavy hair with a middle part, glossy shine, and soft volume falling over both shoulders. Her face is mostly hidden behind the ice cream cone she is holding up in front of her mouth and lower face, creating a playful fashion-editorial composition. She wears a white ribbed tank top with wide straps and a single visible sparkling stud earring. In her hand is 1 waffle cone topped with 1 large scoop of pink strawberry ice cream with dark red berry swirls and slight melting texture. Warm, flattering beauty lighting, soft shadows, realistic skin tones, high-end celebrity portrait photography, crisp focus on the hand, cone, hair, and shoulders, minimal background, subtly sensual and chic mood, vertical crop.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="Profile / Avatar - Studio Portrait With Strawberry Ice Cream - Image 1">
</div>

#### 📌 Details

- **Author:** [Arturo Garrido](https://x.com/arturogarrido)
- **Source:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14594)**

---

### No. 13: Profile / Avatar - Censored Point-Cloud Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a stark black-and-white lidar-style portrait of a suited man built from dense white particles, ideal for editorial tech visuals, privacy themes, or futuristic identity imagery.

#### 📝 Prompt

```
A minimalist monochrome portrait made entirely from millions of tiny white point-cloud dots on a pitch-black background, showing 1 adult man from the chest up in a formal dark blazer and light collared dress shirt. The subject is centered slightly to the right, facing forward with a subtle three-quarter turn, with neatly combed short hair and one visible ear sharply defined by dense lidar-like particles. Render the figure as raw 3D scan data mixed with topological contour logic: ultra-dense stippling, precise geometric dot placement, faint isoline structure, and clean depth shaping across the hair, jacket lapels, collar, neck, and shoulders. Keep the face intentionally obscured by 1 large vertical rectangular censor block in dark gray to black, perfectly centered over the facial area from forehead to below the nose, creating a stark privacy-mask effect. Use matte texture, crisp edges, sharp focus, high contrast, no glow, no bloom, no neon, no fog, no motion blur, no chromatic aberration, no painterly strokes. Add 1 small four-point sparkle icon in light gray in the bottom-right corner. The overall image should feel mathematical, forensic, and futuristic, like a high-resolution lidar scan portrait in 8k.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="Profile / Avatar - Censored Point-Cloud Portrait - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="Profile / Avatar - Censored Point-Cloud Portrait - Image 2">
</div>

#### 📌 Details

- **Author:** [Harshith](https://x.com/HarshithLucky3)
- **Source:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14408)**

---

### No. 14: Profile / Avatar - Greek God Riding a Lion

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A cinematic prompt for generating an epic image of a person portrayed as a Greek god riding a lion across the African savanna.

#### 📝 Prompt

```
make me look like a {argument name="persona" default="greek god"} riding a {argument name="mount" default="lion"} in the {argument name="setting" default="plains of africa"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="Profile / Avatar - Greek God Riding a Lion - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="Profile / Avatar - Greek God Riding a Lion - Image 2">
</div>

#### 📌 Details

- **Author:** [Max Blade](https://x.com/_MaxBlade)
- **Source:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14326)**

---

### No. 15: Profile / Avatar - Confused Blonde Anime Girl Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a simple pastel anime bust portrait of a puzzled girl in a blue sweater, suitable for avatars, profile art, or casual character illustrations.

#### 📝 Prompt

```
A soft, minimalist anime portrait of a cute young woman from the waist up against a plain light gray background, drawn in a clean pastel style with very thin sketch-like line art and flat gentle colors. She has long, flowing pale blonde hair with soft layers and long front bangs partially covering her forehead, large round light-blue eyes, fair skin, and a small slightly open mouth conveying mild confusion. She is wearing an oversized loose {argument name="clothing color" default="light pastel blue"} long-sleeve top with a wide relaxed neckline. Her pose is slightly angled toward the viewer, with one hand raised and one index finger touching the side of her head as if puzzled. Place exactly 1 floating blue question mark near the upper left side of her head. The expression should feel innocent, absentminded, and endearing. Keep the composition centered, airy, and uncluttered, with no extra objects, no detailed background, and no strong shadows.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="Profile / Avatar - Confused Blonde Anime Girl Portrait - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="Profile / Avatar - Confused Blonde Anime Girl Portrait - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="Profile / Avatar - Confused Blonde Anime Girl Portrait - Image 3">
</div>

#### 📌 Details

- **Author:** [Torishima / INTP](https://x.com/izutorishima)
- **Source:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14474)**

---

### No. 16: Profile / Avatar - Soft Blue Anime Girl Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a minimalist pastel anime bust portrait of a blue-haired girl in an oversized light-blue sweatshirt, ideal for avatars, profile images, or soft character art.

#### 📝 Prompt

```
A soft anime-style bust portrait of a cute young woman centered on a plain warm off-white background, drawn with clean delicate line art and flat pastel coloring. She has very long straight {argument name="hair color" default="pale sky blue"} hair with wispy strands, full bangs parted slightly near the center, and large matching blue eyes with glossy highlights. Her expression is shy and puzzled, with slightly raised inner eyebrows, faint pink blush on her cheeks, and a small open mouth. She is looking directly at the viewer while lightly touching her lower lip with one index finger in a thoughtful, hesitant pose. She wears an oversized loose {argument name="top color" default="light blue"} sweatshirt with long sleeves that partly cover her hand. Frame the image from the chest up, with the head slightly tilted, giving a gentle, innocent, dreamy feeling. Use a minimalist composition, no accessories, no extra objects, no scenery, and no text. Emphasize a monochrome blue palette, airy simplicity, subtle sketch-like outlines, and a clean Japanese illustration aesthetic suitable for a soft personal avatar.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="Profile / Avatar - Soft Blue Anime Girl Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [Torishima / INTP](https://x.com/izutorishima)
- **Source:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14473)**

---

### No. 17: Profile / Avatar - Luxury Indoor Mirror Selfie Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a realistic fashion-style mirror selfie of a woman in a fitted ivory dress, useful for lifestyle, outfit, or social-media glamour imagery.

#### 📝 Prompt

```
A realistic indoor mirror selfie of a slender glamorous young woman standing in a softly lit upscale living room or hotel suite, photographed vertically from head to below the knees. She wears a form-fitting cream or ivory bodycon midi dress with elegant draping and ruching, featuring an asymmetrical neckline with 1 shoulder strap crossing diagonally over the chest and leaving the other shoulder bare. Her hair is long, dark brown, softly wavy, and parted near the center, falling over both shoulders. She holds a smartphone in her right hand in front of her face, partially covering it, with the phone angled toward a wall mirror; the phone has a dark case with a red cloud pattern. Her left arm hangs naturally by her side. Add subtle jewelry: 1 thin necklace with a small pendant, 1 silver bracelet or bangle on the right wrist, and rings on the fingers of the hand holding the phone. Emphasize a realistic feminine silhouette, smooth skin, soft warm ambient lighting, and polished editorial social-media style photography. The background should include 1 beige sofa behind her, 1 brown leather handbag resting on the right side of the sofa, 1 textured stone or concrete accent wall behind the mirror area, and a warm hallway on the left with 2 framed wall artworks visible. Use natural indoor shadows, refined skin texture, realistic fabric folds and compression around the waist and hips, luxury apartment aesthetic, clean composition, and high detail.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="Profile / Avatar - Luxury Indoor Mirror Selfie Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [Danna R.](https://x.com/daaaaanc)
- **Source:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14421)**

---

### No. 18: Profile / Avatar - Realistic White Dress Mirror Selfie

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a photorealistic fashion mirror selfie in a warm apartment interior, useful for outfit shots, lifestyle content, and realism comparisons.

#### 📝 Prompt

```
A realistic indoor mirror selfie of a slim young woman standing in a warmly lit modern apartment living room, wearing a fitted ivory-white one-shoulder bodycon midi dress with ruched gathering through the torso and hips. She has straight dark brown shoulder-length hair with a center part, minimal jewelry including 2 rings, a silver bangle bracelet, and small subtle earrings. Her face is obscured by the phone as she takes the photo with one hand raised, holding a smartphone in a black case decorated with red cloud motifs. She stands slightly angled with relaxed posture, one arm down by her side, showing a natural feminine silhouette. The scene is framed vertically like a casual social media outfit mirror selfie. Behind her is a beige fabric sofa with 1 patterned throw pillow in a gray geometric motif and 1 taupe-brown leather handbag placed on the seat. The background includes a textured bronze-brown accent wall, glossy cream tile floor, a dim hallway on the left with 3 framed wall artworks, and warm recessed ceiling lights. Soft ambient evening lighting, natural skin tones, realistic fabric tension and folds, subtle reflections in the mirror, clean upscale apartment aesthetic, high realism, photorealistic skin texture, smartphone camera perspective.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="Profile / Avatar - Realistic White Dress Mirror Selfie - Image 1">
</div>

#### 📌 Details

- **Author:** [Danna R.](https://x.com/daaaaanc)
- **Source:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14419)**

---

### No. 19: Profile / Avatar - Santorini Luxury Dress Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a photorealistic vertical travel-fashion portrait of a glamorous woman in a white dress posing in Santorini, ideal for luxury vacation, lifestyle, or editorial imagery.

#### 📝 Prompt

```
A glamorous travel-fashion portrait of a {argument name="woman" default="blonde woman"} seated on a sunlit stone ledge overlooking the caldera in Santorini, Greece, with whitewashed cliffside buildings descending toward a deep blue sea and rugged volcanic islands in the distance. She wears a flowing ivory halter dress with a very deep plunging neckline, side cutouts, a gathered waist with a circular ring detail, and soft pleated fabric draped across her lap. Her hair is long, wavy, and {argument name="hair color" default="golden blonde"}, styled loose over her shoulders. Add layered delicate necklaces including a small pendant and a silver cross, plus a bracelet or watch on one wrist. Place a classic white Greek church with a bright {argument name="dome color" default="blue"} dome in the upper right background, and frame the right side of the image with vivid {argument name="flower color" default="magenta pink"} bougainvillea in full bloom. Lighting is bright Mediterranean midday sun with crisp highlights, soft skin glow, and gentle depth of field that keeps the woman sharp while the background architecture and sea are slightly softened. Composition is vertical, elegant and aspirational, with the woman centered slightly right, torso visible down to the flowing skirt, scenic coastline stretching across the left half of the frame. Add small black text in the top-left corner reading {argument name="corner text" default="GPT V2"}. Photorealistic luxury vacation aesthetic, high detail, natural colors, editorial Instagram travel vibe.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="Profile / Avatar - Santorini Luxury Dress Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [Ed](https://x.com/Eduardopto)
- **Source:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14428)**

---

### No. 20: Profile / Avatar - Japanese Fuji film style portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

An incredibly detailed prompt for generating high-quality Fujifilm aesthetic portraits with a soft, natural, and intimate morning feel.

#### 📝 Prompt

```
9:16 vertical — {argument name="film style" default="Japanese Fuji film style"} portrait, single subject

Fujifilm analog aesthetic (Pro 400H / Superia feel), soft pastel tones, slight green-magenta shift, low contrast, gentle highlight roll-off, fine film grain, subtle halation

early morning indoor setting near window, soft curtains, fresh daylight

{argument name="subject" default="young Japanese female idol"}, natural minimal makeup, soft fresh skin texture

outfit: oversized shirt with loose shorts, relaxed homewear style, non-revealing

hair: slightly messy, natural volume, just-woke-up feeling

pose: sitting on bed edge or by window, body slightly leaning forward, shoulders relaxed; one hand loosely holding a small flower or fabric, the other resting naturally

expression: soft, slightly sleepy gaze, calm and natural

lighting: {argument name="lighting" default="soft morning light"}, diffused, gentle shadows

mood: quiet, fresh, intimate everyday moment

quality: ultra-realistic, film grain, slight softness, natural imperfections
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="Profile / Avatar - Japanese Fuji film style portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [BubbleBrain](https://x.com/BubbleBrain)
- **Source:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14301)**

---

### No. 21: Social Media Post - 4-Panel Japanese Digital Ad Banner Grid

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a 2x2 grid of distinct Japanese digital advertisement banners for travel, skincare, food, and online education.

#### 📝 Prompt

```
{
  "type": "2x2 grid of Japanese digital advertisement banners",
  "layout": {
    "structure": "4 equal quadrants",
    "quadrants": [
      {
        "position": "top-left",
        "theme": "Travel",
        "subject": "A couple holding hands on a white sand beach, looking out at turquoise ocean water under a bright blue sky.",
        "elements": ["red hibiscus flower in bottom left corner"],
        "text_labels": [
          "今年こそ、解き放て。",
          "{argument name=\"travel destination\" default=\"沖縄旅行\"}",
          "3日間の癒やし旅",
          "航空券＋ホテル",
          "39,800円〜",
          "絶景、グルメ、体験 ぜんぶ叶う!"
        ],
        "icons": {
          "count": 3,
          "descriptions": ["airplane", "hotel building", "car"]
        }
      },
      {
        "position": "top-right",
        "theme": "Skincare",
        "subject": "Close-up portrait of a young woman with glowing, dewy skin, eyes closed, gently touching her cheeks.",
        "elements": [
          "soft pink gradient background",
          "dynamic water splash effects",
          "pink cosmetic jar labeled '{argument name=\"skincare product name\" default=\"LUMIÈRE\"} Brightening Gel'"
        ],
        "text_labels": [
          "毛穴・くすみ卒業！",
          "透明感あふれる",
          "水光肌へ",
          "新感覚スキンケア",
          "初回限定 78%OFF",
          "{argument name=\"discount price\" default=\"1,980円\"}"
        ],
        "badges": {
          "count": 3,
          "style": "gold circular",
          "labels": ["毛穴ケア", "高保湿", "ハリ・ツヤ"]
        }
      },
      {
        "position": "bottom-left",
        "theme": "Gourmet Food",
        "subject": "Thick, sliced, medium-rare steak sizzling on a dark grill plate.",
        "elements": [
          "garlic chips",
          "rosemary sprig",
          "dark background with smoke and glowing embers"
        ],
        "text_labels": [
          "とろける旨さ！",
          "{argument name=\"food item\" default=\"黒毛和牛\"}",
          "贅沢ステーキ",
          "期間限定",
          "特別価格",
          "通常価格 8,980円",
          "4,980円"
        ],
        "badges": {
          "count": 1,
          "style": "red circular",
          "labels": ["A4 A5等級"]
        }
      },
      {
        "position": "bottom-right",
        "theme": "Online Education",
        "subject": "Young man in a blue shirt studying at a desk, writing in a notebook next to an open laptop.",
        "elements": ["bright indoor lighting", "desk environment"],
        "text_labels": [
          "スキマ時間で",
          "{argument name=\"education goal\" default=\"最短合格！\"}",
          "オンライン資格講座",
          "スマホで完結",
          "効率学習で差がつく！",
          "今だけ！ 受講料 20%OFF"
        ],
        "badges": {
          "count": 1,
          "style": "blue circular",
          "labels": ["受講者数 10万人 突破！"]
        },
        "icons": {
          "count": 2,
          "descriptions": ["smartphone", "open book"]
        }
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="Social Media Post - 4-Panel Japanese Digital Ad Banner Grid - Image 1">
</div>

#### 📌 Details

- **Author:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **Source:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **Published:** April 19, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13531)**

---

### No. 22: Social Media Post - Cute Black Kitten Japanese Sticker Sheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

A 15-panel sticker-style sheet of an expressive black kitten with Japanese phrases, ideal for chat stickers, LINE stamp concepts, or social media visuals.

#### 📝 Prompt

```
{"type":"cute sticker sheet illustration","subject":{"species":"black kitten","style":"adorable chibi, soft painterly anime-cartoon look, big round amber-brown eyes, tiny muzzle, expressive ears, fluffy dark charcoal-black fur with warm brown highlights, thick clean outline"},"layout":{"background":"plain white","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"row 1 col 1","count":1,"labels":["happy grateful pose with both paws clasped at chest, open smiling mouth, pink cherry blossom petals around the cat"]},{"title":"02. おつかれさま！","position":"row 1 col 2","count":1,"labels":["content relaxed cat holding a green mug with a paw-print emblem, eyes closed, small puff of steam, celebratory yellow accent lines"]},{"title":"03. 了解です！","position":"row 1 col 3","count":1,"labels":["upright kitten raising one paw in acknowledgment, bright attentive expression, yellow accent lines above"]},{"title":"04. ＯＫ！","position":"row 1 col 4","count":1,"labels":["winking kitten making an OK hand gesture with one paw, slight smile, yellow accent lines"]},{"title":"05. はーい！","position":"row 1 col 5","count":1,"labels":["excited kitten waving one paw high, open smiling mouth, yellow accent lines"]},{"title":"06. いいね！","position":"row 2 col 1","count":1,"labels":["winking kitten giving a thumbs-up, small pink heart beside it, yellow accent lines"]},{"title":"07. がんばる！","position":"row 2 col 2","count":1,"labels":["determined kitten with clenched paws and fierce eyes, surrounded by stylized orange flames"]},{"title":"08. なんとかなる！","position":"row 2 col 3","count":1,"labels":["confident serene kitten with eyes closed and chest slightly puffed out, pink blossoms floating around"]},{"title":"09. ごめんね…","position":"row 2 col 4","count":1,"labels":["apologetic sad kitten with paws held together at chest, droopy eyes, one blue sweat drop"]},{"title":"10. 待ってるね！","position":"row 2 col 5","count":1,"labels":["kitten peeking over a wooden ledge with both paws visible, expectant expression, small motion lines on both sides"]},{"title":"11. おやすみなさい","position":"row 3 col 1","count":1,"labels":["sleeping curled-up kitten on a pink cushion, blue ZZZ letters, crescent moon and small stars above"]},{"title":"12. いってきます！","position":"row 3 col 2","count":1,"labels":["rear view of kitten cheerfully walking away with one paw raised, wearing a green backpack with paw-print patch and small dangling charm, yellow accent lines"]},{"title":"13. ただいま！","position":"row 3 col 3","count":1,"labels":["front-facing kitten with both paws raised high, happy open smile, golden sparkle marks around it"]},{"title":"14. よろしくね！","position":"row 3 col 4","count":1,"labels":["polite seated kitten facing forward, gentle smile, yellow accent lines beside the head"]},{"title":"15. 大好き！","position":"row 3 col 5","count":1,"labels":["content kitten hugging a large pink heart, eyes closed, several small pink hearts floating around"]}],"spacing":"evenly spaced with generous white margins"},"rendering":{"quality":"high detail","lighting":"soft even studio lighting","color_palette":"black fur, warm brown eyes, pink hearts and blossoms, yellow accent marks, green accessories, minimal pastel decorations","mood":"friendly, wholesome, sticker-ready, messaging app pack","composition":"each sticker isolated and centered in its own cell with bold Japanese text above"}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="Social Media Post - Cute Black Kitten Japanese Sticker Sheet - Image 1">
</div>

#### 📌 Details

- **Author:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Source:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14490)**

---

### No. 23: Social Media Post - Candid Boutique Portrait in Brown

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a realistic vertical lifestyle photo of a woman in a warm-toned shop interior, useful for fashion, retail, or social media editorial imagery.

#### 📝 Prompt

```
A candid, photorealistic vertical smartphone photo of a young East Asian woman standing in a warm-toned boutique or home fragrance shop, shot from a slightly high angle looking down at her upper body and torso. She has {argument name="hair color" default="dark brown to black"} hair tied back in a low ponytail with a few loose strands near the face, and she is holding a small creamy-white cup or candle jar close to her mouth with one hand. She wears a very fitted ribbed zip-front long-sleeve top in {argument name="outfit color" default="chocolate brown"}, partially unzipped, paired with matching high-waisted pants in the same brown tone for a monochrome look. Her pose is casual and slightly leaning, with the other arm relaxed behind her back, giving the image an off-guard lifestyle snapshot feeling. The store shelves around her are wooden and filled with many glass candle jars and small product containers, softly blurred in the background and along the left side of the frame. Use warm indoor ambient lighting, shallow depth of field, realistic skin texture, subtle highlights on the hair, natural hand pose, and a cozy artisanal retail atmosphere. Compose it as a tight mid-to-full body crop in portrait orientation, with the subject centered and the background angled diagonally to enhance the candid perspective. Photographic style: realistic, high-detail, soft bokeh, boutique shopping snapshot, 35mm lens look, natural color grading.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="Social Media Post - Candid Boutique Portrait in Brown - Image 1">
</div>

#### 📌 Details

- **Author:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14630)**

---

### No. 24: Social Media Post - Grocery Aisle Egg Carton Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a realistic vertical lifestyle photo of a stylish woman in a grocery store holding an open carton of six eggs, suitable for social media or editorial-style shopping imagery.

#### 📝 Prompt

```
A candid vertical smartphone photo of a {argument name="woman age" default="young adult"} woman shopping in a modern grocery store aisle at night, framed from upper thighs to head in a close, slightly wide-angle perspective. She is standing beside refrigerated produce shelves filled with colorful packaged vegetables and groceries, with glossy black shelving, bright store lighting, reflective surfaces, and soft bokeh in the background. She holds an open recycled cardboard egg carton toward the camera in her left hand, clearly showing 6 brown eggs inside. Her right hand is near a black shopping basket cart filled with groceries. She has long dark brown hair worn down, and her face is intentionally obscured by a large soft-edged rectangular blur block centered over the face. She wears a tight ribbed brown zip-front long-sleeve crop top with the zipper partly open at the chest, and matching high-waisted brown pants. The pose is casual and confident, with the carton presented as the focal prop. Realistic photography, flashless indoor lighting, shallow depth of field, detailed skin and fabric texture, natural reflections, high contrast, fashionable lifestyle aesthetic, subtle editorial feel, vertical 9:16 composition.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="Social Media Post - Grocery Aisle Egg Carton Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14629)**

---

### No. 25: Social Media Post - Opulent Autumn Empress at Sunset

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a blazing, jewel-encrusted autumn fantasy portrait suited for dramatic showcase art and high-impact social media visuals.

#### 📝 Prompt

```
A hyper-luxurious fantasy portrait of an elegant woman in side profile, centered slightly left, wearing an extravagant autumn headdress and robe made of red maple leaves, chrysanthemum-like flowers, gold filigree, gemstones, crystal pendants, and translucent stained-glass ornamentation. Her long dark hair falls over her shoulder, and her face is mostly obscured by shadow and angle, creating a mysterious, idealized look. Surround her with large sweeping circular frames and curved ribbons of transparent amber, ruby, and orange glass, embedded with faceted jewels and reflective crystal droplets. Fill the scene with exactly 9 clearly visible floating maple leaves drifting through the air. Set the background as a glowing mountain valley at sunset with the sun low on the horizon, warm golden rays, distant peaks, autumn forest, and a reflective river below. The entire image should be drenched in fiery orange, copper, gold, and scarlet tones, with extreme visual richness, dazzling highlights, dense layered detail, sparkling bokeh, cinematic backlighting, and an intentionally intense, eye-searing level of ornate beauty. Ultra-detailed, maximalist, ethereal, radiant, fantasy couture, glossy textures, jewel-like lighting, wide cinematic composition.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="Social Media Post - Opulent Autumn Empress at Sunset - Image 1">
</div>

#### 📌 Details

- **Author:** [AIおじさん](https://x.com/AIojisan1952)
- **Source:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14508)**

---

### No. 26: Social Media Post - Robot Painter Collage Ad

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A polished promotional 2x2 collage showing a cute robot painting four different artworks, ideal for AI image tool announcements and social media banners.

#### 📝 Prompt

```
{"type":"promotional collage illustration","subject":{"main":"cute white humanoid robot artist with oversized glowing blue eyes","design":"smooth rounded white shell, black mechanical joints, small smile, friendly childlike proportions, glossy finish","activity":"painting on canvas with a thin paintbrush while holding a painter's palette"},"layout":{"composition":"2x2 grid collage with a large centered title overlay crossing the middle seam","sections":[{"position":"top-left","count":1,"label":"3","scene":"robot painting a colorful ocean sunset seascape with bright sun on the horizon, pink and orange sky, blue water, expressive brushstrokes"},{"position":"top-right","count":1,"label":"6","scene":"robot painting a bouquet of pink flowers in a blue vase, soft pastel floral still life"},{"position":"bottom-left","count":1,"label":"4","scene":"robot painting a lush green waterfall landscape with forest foliage and a stream"},{"position":"bottom-right","count":1,"label":"7","scene":"robot painting a glowing modern city skyline at sunset with tall skyscrapers and warm reflections"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"very large bold white sans-serif text with dark drop shadow, centered horizontally across the collage"}},"environment":{"setting":"cozy art studio interior","background":"soft-focus shelves, framed pictures, warm ambient lighting, neutral curtains, occasional houseplant","easel":"wooden tabletop easel in each panel","palette":"round painter's palette with many vivid paint dabs in each panel"},"style":{"rendering":"highly polished 3D cartoon realism","mood":"playful, creative, inviting, tech-meets-art","camera":"medium close-up framing, robot on the right side of each panel facing left toward the canvas","lighting":"warm indoor light with gentle highlights and shallow depth of field"}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="Social Media Post - Robot Painter Collage Ad - Image 1">
</div>

#### 📌 Details

- **Author:** [01net](https://x.com/01net)
- **Source:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14556)**

---

### No. 27: Social Media Post - Anime Pop-Art Protest Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a bold vertical anime poster with a censored-faced character, peace sign gesture, and oversized slogan bubble for meme art, social posts, or graphic poster experiments.

#### 📝 Prompt

```
A bold anime pop-art poster of a tall white-haired male sorcerer in a dark navy high-collar coat, shown from the waist up, facing forward in a confident pose with his left hand raised close to the camera making a peace sign. His face is partially obscured by a rectangular blur/censor block centered over the eyes and nose area, while his spiky silver-white hair fans outward dramatically above a dark blindfold or visor. Place a huge comic speech bubble across the top with the exact text {argument name="headline text" default="LUDDITES ALWAYS LOSE!"} in heavy black all-caps sans-serif lettering. Use a vivid blue background filled with dense red and orange radial speed lines exploding outward from behind the character, creating a dynamic manga cover feel. Emphasize thick ink outlines, cel-shaded anime rendering, posterized contrast, and a slightly warped vintage-comic print look. The composition should be vertical, tightly cropped, high energy, rebellious, graphic, and meme-like, with the {argument name="character hair color" default="silver white"} hair, {argument name="coat color" default="dark navy"} coat, and {argument name="background color" default="bright blue with red-orange radial lines"} dominating the palette.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="Social Media Post - Anime Pop-Art Protest Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Source:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14638)**

---

### No. 28: Social Media Post - Realistic Sam's Club Shopping Snapshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a photorealistic candid warehouse-store portrait suitable for recreating an authentic shopping scene with branded retail signage and a shopper holding produce.

#### 📝 Prompt

```
A candid, highly realistic smartphone photo inside a busy Sam’s Club warehouse store in China. Center the composition on a young East Asian man from mid-torso up, standing upright and facing the camera, with his face obscured by a rectangular blur block for privacy. He wears a plain black short-sleeve T-shirt with a small white Tesla logo on the left chest and holds a large clear plastic bag of red apples in his left hand, tied at the top with a blue band. The apple bag has a white label reading “envy” with small Chinese text beneath it. Behind him is a bright retail interior with tall industrial ceilings, warehouse shelving, shoppers, shopping carts, and stacked produce displays. Prominently show the blue diamond Sam’s Club wall sign at upper left with the text “Sam’s CLUB” and “山姆会员商店,” and a large blue wall banner behind him reading “更好的生活尽在山姆” and “Life is Better in the Club.” On the upper right, hang a tall white vertical banner that reads “优质优价” and “Great Products Great Prices,” with blue and green geometric accents. Include many background customers, slightly out of focus, to create an authentic crowded shopping atmosphere. Lighting should be bright, even retail overhead lighting; colors natural; perspective eye level; documentary snapshot aesthetic; sharp foreground subject with mildly softened background; portrait orientation.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="Social Media Post - Realistic Sam's Club Shopping Snapshot - Image 1">
</div>

#### 📌 Details

- **Author:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Source:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14434)**

---

### No. 29: Social Media Post - Geometric Bird Riding Bicycle

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a clean minimalist vector illustration of a stylized bird cyclist, suitable for playful editorial graphics, logos, or modern poster art.

#### 📝 Prompt

```
A minimalist flat vector illustration on a light gray background showing a whimsical bird riding a bicycle, built entirely from simple geometric shapes with thick black outlines. The bicycle is a black line-drawn road bike in side view facing left, with 2 large wheels, each wheel divided by a vertical and horizontal spoke cross, a simple triangular frame, a small black saddle, pedals, and a thin black ground line running horizontally beneath the bike. The rider is a stylized white bird with a large round body, a smaller round head, a pointed orange beak opened wide, and a pink lower beak interior. The bird has 1 visible black eye, a simple curved black line on top of the head, 1 teardrop-shaped wing behind the neck, and 1 angled white tail feather shape pointing backward. The bird leans forward over the bicycle as if actively riding. It has 2 long narrow orange legs with black outlines extending downward over the frame toward the pedals. Keep the composition centered, playful, clean, and abstract, with no shading, no texture, and a modern icon-like graphic style.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="Social Media Post - Geometric Bird Riding Bicycle - Image 1">
</div>

#### 📌 Details

- **Author:** [Mojofull](https://x.com/furoku)
- **Source:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14512)**

---

### No. 30: Social Media Post - Cognitive bias Instagram infographic

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A professional prompt for creating informative social media graphics with complex textual information.

#### 📝 Prompt

```
Create an {argument name="format" default="infographic"} for {argument name="platform" default="Instagram post"} about {argument name="topic" default="how advertisers can use cognitive biases"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="Social Media Post - Cognitive bias Instagram infographic - Image 1">
</div>

#### 📌 Details

- **Author:** [Maxwell Finn](https://x.com/maxwellfinn)
- **Source:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14306)**

---

### No. 31: Social Media Post - Early 2000s Computer Lab With ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a nostalgic candid classroom photo of students using ChatGPT on CRT computers, ideal for editorial or social-media visuals about AI in everyday education.

#### 📝 Prompt

```
A candid documentary-style photo of a {argument name="setting" default="high school computer lab classroom"} filled with exactly 10 students seated at rows of bulky off-white CRT desktop computers, viewed from the back-left corner of the room at a slight wide angle. The scene should feel like an early-2000s snapshot taken on a consumer digital camera with direct flash, soft grain, slightly warm indoor fluorescent lighting, and a timestamp in the bottom-right corner reading {argument name="timestamp" default="02 18 04"}. In the foreground left, a student in a navy track jacket with white sleeve stripes points at a CRT monitor; in the center foreground, another student with short spiky hair wears an oversized gray sweatshirt and sits facing away from the camera; on the right foreground, a blonde student with a ponytail wears a light blue long-sleeve top with dark horizontal arm stripes and types at a keyboard; far right, another student with curly dark hair sits at a workstation. Several other students occupy the middle and back rows, all facing their screens. The monitors prominently display the ChatGPT interface, with the visible heading reading {argument name="screen title" default="ChatGPT"} and simple prompt text beneath it. The room has beige walls, drop ceiling tiles, and multiple motivational classroom posters: exactly 4 readable posters on the back wall saying {argument name="poster one" default="YOU CAN DO HARD THINGS"}, "BE KIND ONLINE", "THINK BEFORE YOU CLICK", and a larger poster titled "KEYBOARD SHORTCUTS" with a list beneath it. Include bulletin boards, a classroom door at the back, rolling office chairs, white keyboards and mice, and a backpack on the floor near the right foreground desk. Faces should be partially obscured or softly anonymized, preserving the look of a real classroom photo while keeping the focus on the students using ChatGPT in an old computer lab.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="Social Media Post - Early 2000s Computer Lab With ChatGPT - Image 1">
</div>

#### 📌 Details

- **Author:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14675)**

---

### No. 32: Social Media Post - Surreal Patio Portrait with Crow and Dog

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a photorealistic, slightly uncanny portrait of a seated person holding a small dog while a black bird perches on their head, ideal for editorial-style surreal photography.

#### 📝 Prompt

```
A slightly surreal but photorealistic portrait of a seated person in a quiet courtyard or patio, centered in frame, wearing a fitted white long-sleeve turtleneck top with delicate pink floral prints and a printed illustration of a girl on the chest, paired with loose cream floral pants. The person sits on a simple white metal chair and holds a small fluffy poodle-like dog in their lap; the dog has curly off-white fur and distinctly dyed orange ears. Perched on top of the person’s dark hair bun is a black crow or raven, facing left, calm and balanced as if it naturally belongs there. The subject’s pose is still, direct, and formal, creating an odd deadpan family-portrait feeling. Set the scene against a textured off-white stucco wall with exactly 4 notable decorative background elements: 1 brown sun-shaped wall ornament in the upper left, 1 small wall-mounted planter shelf with a small bird figurine and trailing flowers on the left, 1 tall arched window or mural on the right showing a bright blue sky with soft white clouds, and 1 white pedestal planter at lower right filled with long green leaves and exactly 2 pink flamingo ornaments. Include a bit of stone edging and dark greenery at lower left and a brown tiled floor. Lighting is soft natural daylight, slightly overcast, with muted colors, shallow depth of field, and a vintage editorial photography look. Composition should be vertical, full seated figure, straight-on, balanced, and quietly uncanny. Customize the main figure as {argument name="person" default="a middle-aged woman"}, the bird as {argument name="bird type" default="black crow"}, the dog breed as {argument name="dog type" default="small poodle mix"}, the dog ear color as {argument name="dog ear color" default="orange"}, and the outfit palette as {argument name="outfit colors" default="white and faded pink florals"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="Social Media Post - Surreal Patio Portrait with Crow and Dog - Image 1">
</div>

#### 📌 Details

- **Author:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14674)**

---

### No. 33: Social Media Post - Moody Coastal Road Trip Portrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a cinematic candid seaside roadside portrait with a parked vintage sedan, ideal for nostalgic travel photography and lifestyle imagery.

#### 📝 Prompt

```
A cinematic candid photo of a {argument name="person" default="young woman"} standing in a wet coastal roadside turnout on an overcast day, viewed from behind and slightly to the side as she turns her head back toward the camera. She has dark messy hair tied in a loose bun with windblown strands, and her face is softly obscured and indistinct. She wears 2 visible clothing pieces: a worn tan-brown canvas jacket and medium-blue jeans. Her posture is relaxed with one hand near or in a pocket. The setting is a moody ocean cliff highway overlook with dark rocky mountains running along the left side, pale gray sea stretching into the distance on the right, and a cloudy washed-out sky. Include 1 parked light-colored late-1980s or early-1990s sedan on the right edge of the frame, rear end facing the viewer, and 1 large rock barrier near the overlook. The asphalt is dark and damp with faint parking lines, suggesting recent rain. Use natural light, muted cool tones, slight film grain, soft focus, shallow haze, and a nostalgic 35mm road-trip photography aesthetic.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="Social Media Post - Moody Coastal Road Trip Portrait - Image 1">
</div>

#### 📌 Details

- **Author:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14673)**

---

### No. 34: Social Media Post - Woman Dancing in Black Dress

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a cinematic photorealistic nightlife portrait of a woman in a flowing black dress dancing elegantly in a dim lounge, ideal for fashion, performance, or social media visuals.

#### 📝 Prompt

```
A dramatic full-body photo of a woman dancing powerfully in a dark upscale lounge or bar, wearing a sleek black evening dress with a high slit and flowing velvet-like fabric that whips outward with her movement. She has long straight {argument name="hair color" default="black"} hair flying to one side, a slim athletic figure, and small hoop earrings. Capture her in a confident, stylish dance pose with one arm raised gracefully above her head and the other curved downward, torso turned in profile, emphasizing elegance and motion. The setting is dim and cinematic with warm amber practical lights, soft bokeh, and a blurred audience in the background, including a few seated onlookers and a glowing television screen off to the left. The mood is cool, sensual, and high-end, with strong contrast, shallow depth of field, realistic skin, subtle motion in the dress hem, and fashion-editorial lighting. Photorealistic, dynamic nightlife photography, vertical composition.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="Social Media Post - Woman Dancing in Black Dress - Image 1">
</div>

#### 📌 Details

- **Author:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **Source:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14506)**

---

### No. 35: Infographic / Edu Visual - Paris Food Ranking Poster Prompt

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A simple prompt to create a poster for a city food ranking, designed for use with GPT Image 2.

#### 📝 Prompt

```
Create a poster for a {argument name="city" default="Paris"} {argument name="topic" default="food"} ranking
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="Infographic / Edu Visual - Paris Food Ranking Poster Prompt - Image 1">
</div>

#### 📌 Details

- **Author:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **Source:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **Published:** April 22, 2026
- **Languages:** zh

**[👉 Try it now →](https://gptimage2api.net/?id=14370)**

---

### No. 36: Infographic / Edu Visual - Chinese Calligraphy Style Comparison Sheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A vertical reference poster showing the same Chinese phrase rendered in five famous calligraphy styles, useful for typography tests, cultural design studies, and brush-script comparisons.

#### 📝 Prompt

```
{"type":"Chinese calligraphy comparison sheet","subject":"the same five-character phrase written in five different historical calligraphy styles","phrase":"{argument name=\"calligraphy text\" default=\"视觉新时代\"}","canvas":{"orientation":"vertical poster","background":"warm off-white xuan paper texture with subtle fibers, light aging, and soft uneven tone"},"layout":{"structure":"5 horizontal rows separated by faint thin divider lines","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","赵孟頫","颜真卿","苏轼"],"rows":[{"position":"top row","style":"semi-cursive running script inspired by Wang Xizhi","main text":"视觉新时代","label":"王羲之","seal":"small red square seal at far right"},{"position":"second row","style":"slender elegant calligraphy inspired by Emperor Huizong's thin-gold script, with sharp angular strokes and airy spacing","main text":"视觉新时代","label":"宋徽宗","seal":"small red square seal at far right"},{"position":"third row","style":"refined regular-running script inspired by Zhao Mengfu","main text":"视觉新时代","label":"赵孟頫","seal":"small red square seal at far right"},{"position":"fourth row","style":"bold weighty regular script inspired by Yan Zhenqing","main text":"视觉新时代","label":"颜真卿","seal":"small red square seal at far right"},{"position":"bottom row","style":"expressive robust running script inspired by Su Shi","main text":"视觉新时代","label":"苏轼","seal":"small red square seal at far right"}],"left label design":"each row has one narrow vertical beige name plaque aligned on the far left with black Chinese characters","centerpiece":"large black brush-written phrase centered in each row"},"style":{"ink":"deep black sumi ink with visible dry-brush texture, feathering, pressure variation, and natural brushstroke taper","mood":"scholarly, experimental, museum-sheet presentation","composition":"clean spacious margins, balanced row spacing, flat front-facing scan or photographed document"},"quality":{"detail":"high-resolution, crisp brush textures, realistic paper grain","lighting":"soft even studio lighting with no harsh shadows"}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="Infographic / Edu Visual - Chinese Calligraphy Style Comparison Sheet - Image 1">
</div>

#### 📌 Details

- **Author:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Source:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14448)**

---

### No. 37: Infographic / Edu Visual - Countryball Hormuz Strait Standoff

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a satirical countryball meme showing the US and Iran blocking each other at the Strait of Hormuz, useful for editorial humor or geopolitical social media posts.

#### 📝 Prompt

```
A humorous political meme illustration in a simple countryball cartoon style, showing the current situation at the {argument name="location label" default="호르무즈 해협"} as a narrow chokepoint. Use a wide landscape composition with bright flat colors, thick black outlines, and a clean hand-drawn infographic-like look. In the foreground, place 2 countryballs standing shoulder to shoulder on an extremely narrow sandy land bridge with rocks along both sides, making it obvious that only one can pass at a time. On the left is a {argument name="left country" default="United States"} countryball painted with the American flag, wearing black sunglasses and a brown cowboy hat, facing the other ball with a stubborn attitude. On the right is an {argument name="right country" default="Iran"} countryball painted with the Iranian flag, wearing a dark turban-like hat, with angry slanted eyes, also refusing to move. Add 2 large white speech bubbles, one beside each countryball, and put the same bold Korean word in both bubbles: {argument name="speech bubble text" default="길"}. In the midground and background, show a busy blue sea crowded with 9 ships total: 2 gray US warships on the far left, 1 Chinese submarine with a red Chinese flag, 4 oil tankers lined up in the center-left and center carrying different national flags, and 2 gray military ships near the narrow passage with small American flags. At the top right, include a large Iranian flag overlay along the coastline. Draw beige landmasses around the waterway to resemble a simplified map view of the Strait of Hormuz. At the bottom center, add a bold caption in Korean and English on the sand: {argument name="bottom caption" default="호르무즈 해협 (Hormuz Strait)"}. The mood should be satirical, tense, and meme-like, but visually cute and readable.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="Infographic / Edu Visual - Countryball Hormuz Strait Standoff - Image 1">
</div>

#### 📌 Details

- **Author:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Source:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14685)**

---

### No. 38: Infographic / Edu Visual - Physical Exam Question Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt designed to create an image of a high school exam paper with multiple questions and answers.

#### 📝 Prompt

```
generate a image of physical {argument name="subject" default="high school exam"} question {argument name="type" default="multiple question"} 9:16. generate 4 images and each image is an answer of provided question
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="Infographic / Edu Visual - Physical Exam Question Layout - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="Infographic / Edu Visual - Physical Exam Question Layout - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="Infographic / Edu Visual - Physical Exam Question Layout - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="Infographic / Edu Visual - Physical Exam Question Layout - Image 4">
</div>

#### 📌 Details

- **Author:** [zdhpeter](https://x.com/peter6759)
- **Source:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14340)**

---

### No. 39: Infographic / Edu Visual - Vintage Korean Gimbap Recipe Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates an antique-style Korean recipe infographic poster for gimbap, suitable for food marketing, restaurant decor, or cultural cooking visuals.

#### 📝 Prompt

```
Create a vintage Korean food poster on aged beige parchment paper with a slightly stained, textured background, dark ornamental border corners, and a traditional hand-painted ink-and-watercolor illustration style. The poster is a single vertically stacked infographic about {argument name="dish name" default="정통 한국 김밥"}, with elegant large Korean calligraphy at the top and a curved ribbon banner beneath it reading {argument name="subtitle text" default="Traditional Korean Gimbap"}. In the upper center, show a large porcelain plate piled high with exactly 12 sliced gimbap pieces, each slice showing distinct fillings in white rice, yellow egg, orange carrot, green spinach, and dark seaweed wrapping. To the right of the plate, add a small porcelain bowl of kimchi and a short handwritten Korean note reading “간단한 보여도 정성이 들어간 한국의 맛! ♥”. Include a small red seal stamp with Korean text near the upper right. In the middle, add a labeled ingredients section on a ribbon header reading “재료”, showing exactly 6 ingredient panels in one row: 1. 김 (건김) as stacked seaweed sheets, 2. 밥 (양념 밥) as a bowl of rice, 3. 계란 (지단용) as sliced cooked egg strips, 4. 당근 (채썰어볶기) as julienned carrots, 5. 시금치 (데쳐서 무치기) as seasoned spinach, 6. 단무지 (김밥용) as yellow pickled radish strips. Below that, add another ribbon header reading “만드는 순서” and show exactly 6 framed step panels in two rows of three, connected left-to-right with arrows. Step 1 is labeled “1 밥 간하기” and shows a bowl of rice with sesame oil and salt beside it, caption “밥에 참기름 소금으로 간하기”. Step 2 is labeled “2 속재료 준비하기” and shows a cutting board with egg, carrot, and spinach plus a knife, caption “재료 볶아 속재료 준비하기”. Step 3 is labeled “3 김과 밥 펴기” and shows seaweed on a bamboo mat with rice spread over it, caption “김에 밥 얇게 펴기”. Step 4 is labeled “4 속재료 얹기” and shows the fillings arranged in horizontal rows over rice, caption “속재료를 차례로 얹기”. Step 5 is labeled “5 단단하게 말기” and shows two hands rolling the bamboo mat tightly, caption “김밥을 단단하게 말기”. Step 6 is labeled “6 썰어 완성하기” and shows a chef’s knife slicing a gimbap roll into pieces, caption “먹기 좋게 썰어 완성!”. At the bottom, add a wide banner with bold Korean calligraphy reading {argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} and a small heart. Decorate the lower corners with floral motifs and add a red square seal with the Chinese character “福” at the bottom right. Use muted sepia, brown, cream, olive green, and faded red tones, with finely sketched outlines, gentle watercolor shading, and authentic printed-poster composition. Add a small modern overlay logo in the top-left corner reading {argument name="brand text" default="Pollo AI GPT Image 2"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="Infographic / Edu Visual - Vintage Korean Gimbap Recipe Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [폴로 AI](https://x.com/polloai_kr)
- **Source:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14554)**

---

### No. 40: Infographic / Edu Visual - Vintage French Crepe Recipe Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A richly illustrated antique-style French recipe poster showing butter crepes, ingredients, and six cooking steps, ideal for food-themed editorial art or decorative kitchen prints.

#### 📝 Prompt

```
{"type":"vintage French recipe poster","subject":"ornate illustrated food infographic for classic butter crepes","style":{"overall":"antique cookbook poster, Belle Époque French café ephemera, hand-painted watercolor and ink illustration, aged parchment paper texture, muted warm cream, tan, brown, dusty blue, and faded red palette","rendering":"highly legible decorative typography, engraved ornamental borders, soft paper stains, weathered edges, delicate floral filigree, nostalgic artisanal print aesthetic"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"INGRÉDIENTS","method_header":"LA MÉTHODE","footer_banner":"Un classique de la gourmandise, à savourer chaud!","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"portrait","border":"full ornate illustrated border with scrollwork in all 4 corners","sections":[{"title":"hero section","position":"top","count":3,"labels":["main title calligraphy on ribbon and large script","stack of crepes on plate","glass labeled Cidre de Bretagne"]},{"title":"INGRÉDIENTS","position":"middle","count":6,"labels":["1. 1 tasse Farine","2. 2 Œufs","3. 2 tasses Lait","4. 50g Beurre","5. 1 c.à s. Sucre","6. Pincée Sel"]},{"title":"LA MÉTHODE","position":"bottom-middle","count":6,"labels":["1 WHISK DRY INGREDIENTS","2 BEAT IN THE EGGS","3 ADD MILK GRADUALLY","4 MELT BUTTER AND ADD","5 HEAT CREPE PAN","6 FLIP AND COOK!"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"blue and white floral ceramic plate","food":"tall stack of approximately {argument name=\"crepe count\" default=\"14\"} thin golden crepes dusted with powdered sugar, topped with a melting pat of butter","surface":"rustic wooden tabletop","cloth":"blue and white checkered napkin at right","background":"faded pastoral townscape with church spire and old European buildings"},"ingredients":[{"index":1,"item":"flour","container":"decorated ceramic bowl","caption":"1 tasse Farine"},{"index":2,"item":"eggs","count":2,"caption":"2 Œufs"},{"index":3,"item":"milk","container":"blue floral ceramic pitcher","caption":"2 tasses Lait"},{"index":4,"item":"butter","container":"small plate with butter block","caption":"50g Beurre"},{"index":5,"item":"sugar","container":"ceramic bowl with spoon","caption":"1 c.à s. Sucre"},{"index":6,"item":"salt","container":"lidded crock labeled SEL","caption":"Pincée Sel"}],"method_panels":[{"index":1,"title":"WHISK DRY INGREDIENTS","image":"mixing bowl with flour and whisk","caption":"Mélanger la farine et le sucre"},{"index":2,"title":"BEAT IN THE EGGS","image":"eggs being poured into bowl, whisk mixing, broken eggshells nearby","caption":"Incorporer les œufs battus"},{"index":3,"title":"ADD MILK GRADUALLY","image":"milk poured from ceramic pitcher into batter","caption":"Ajouter le lait petit à petit"},{"index":4,"title":"MELT BUTTER AND ADD","image":"melted butter poured from small pan into bowl","caption":"Ajouter le beurre fondu"},{"index":5,"title":"HEAT CREPE PAN","image":"empty black crepe pan heating over blue gas flame","caption":"Faire chauffer la poêle à crêpes"},{"index":6,"title":"FLIP AND COOK!","image":"crepe in pan with metal spatula lifting edge","caption":"Retourner et cuire des deux côtés"}],"decorative_elements":{"count":8,"labels":["ribbon banner behind top title","ribbon banner behind ingredients header","ribbon banner behind method header","large bottom ribbon banner","floral vine ornament left of title","floral corner embellishments","curled parchment scroll styling","fine divider lines between ingredient and method panels"]},"quality":"balanced symmetrical composition, crisp readable French and English text, richly detailed but clean infographic layout, charming old-world culinary poster"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="Infographic / Edu Visual - Vintage French Crepe Recipe Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [Pollo AI France](https://x.com/PolloAIFR)
- **Source:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14564)**

---

### No. 41: Infographic / Edu Visual - Teen-Friendly Black Hole Physics Infographic

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a dense, single-page editorial science infographic that explains a complex black hole and dark matter paper in a playful, accessible style for social posts or educational articles.

#### 📝 Prompt

```
{"type":"editorial science infographic poster","style":"friendly magazine-style educational infographic for teenagers, combining hand-drawn physics diagrams, cartoon characters, and clean editorial typography","topic":"primordial black holes, Hawking evaporation, and memory-burden dark matter","canvas":{"orientation":"portrait","background":"warm cream paper texture with subtle grain","border":"thin muted gray rectangular border around the full page"},"headline":{"title":"THE BLACK HOLE THAT REFUSED TO DIE","subtitle":"a tiny black hole born in the first second of the universe, and the strange new physics that might let it hide as dark matter.","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"Born in a flash","position":"top left","count":4,"labels":["swirling early-universe birth diagram","primordial black hole smaller than a grain of salt but heavier than a mountain","10^-30 seconds after the Big Bang clock icon","thermometer icon"]},{"title":"Normal black holes evaporate","position":"top right","count":4,"labels":["three black hole stages shrinking left to right","outgoing particle squiggles around each stage","Stephen Hawking explanation paragraph","sticker quote: \"black holes ain't so black\" — S. Hawking, 1974"]},{"title":"The plot twist: memory burden","position":"middle center","count":4,"labels":["sad overloaded cartoon black hole with backpack labeled MEMORY","speech bubble about being too full of information to finish evaporating","equation: normal speed ÷ (lots of information)^k = crawling speed","brace note about proposal by Gia Dvali, 2018"]},{"title":"Two kinds of ghost particles","position":"lower middle","count":5,"labels":["fast moving particle on the left","slow warm particle character on the right","timeline from BIG BANG to TODAY","FAST AND COLD cloud label","SLOW AND WARM cloud label"]},{"title":"How we would catch them: the Lyman-α forest","position":"bottom left","count":4,"labels":["paragraph about ancient galaxies passing through hydrogen clouds","spiky absorption-forest landscape graphic","handwritten note: THE FOREST SAYS: WE WOULD NOTICE.","axis from us to distant quasars concept"]},{"title":"So what does this paper show?","position":"bottom right","count":1,"labels":["rounded rectangular summary box"]}],"count":6},"visuals":{"color_palette":["warm beige","dark navy","rust orange","dusty teal","soft brown","muted gray"],"illustration_notes":"flat vector shapes with slightly sketchy outlines, soft shadows, rounded forms, playful but scientifically literate","typography":"large serif all-caps for headline, bold sans-serif section headers, compact readable body text, occasional handwritten accent text"},"objects":{"count":15,"items":["1 full-page border","1 headline block","1 early-universe swirl diagram","1 tiny primordial black hole dot with callout","1 clock icon","1 thermometer icon","3 evaporating black hole diagrams","1 Hawking quote sticker badge","1 backpack-carrying cartoon black hole character","1 speech bubble","1 equation block","2 cloud labels","1 bottom-left spectral forest illustration"]},"text_blocks":{"count":9,"items":["headline title","headline subtitle","author credit","Born in a flash body text","Normal black holes evaporate body text","memory burden explanatory paragraph","ghost particles captions","Lyman-alpha forest explanation","final takeaway summary"]},"composition":"densely packed but readable single-page explainer with multiple illustrated callouts, clear left-to-right and top-to-bottom reading flow, designed like a shareable social media science poster that makes an advanced physics paper feel approachable to a curious teenager"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="Infographic / Edu Visual - Teen-Friendly Black Hole Physics Infographic - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="Infographic / Edu Visual - Teen-Friendly Black Hole Physics Infographic - Image 2">
</div>

#### 📌 Details

- **Author:** [Alphin Tom](https://x.com/alphinctom)
- **Source:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14424)**

---

### No. 42: Infographic / Edu Visual - Academic Economics Chart Simulation

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt designed to generate highly realistic but fictitious academic charts, specifically showing a correlation between oil prices and shark attacks in an economics paper style.

#### 📝 Prompt

```
line graph from an important and prestigious {argument name="field" default="economics paper"} demonstrating a close but not exact relationship between {argument name="variable one" default="the price of oil"} and {argument name="variable two" default="the number of shark attacks"} between {argument name="time period" default="the years of 1914 and 2001"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="Infographic / Edu Visual - Academic Economics Chart Simulation - Image 1">
</div>

#### 📌 Details

- **Author:** [QC](https://x.com/QiaochuYuan)
- **Source:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14396)**

---

### No. 43: Infographic / Edu Visual - Abstract Art Scientific Graph

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt that generates a creative interpretation of an AI task horizons graph using the distinct style of Jean-Michel Basquiat and Voynich manuscript aesthetics.

#### 📝 Prompt

```
{argument name="subject" default="AI task horizons graph"} with a touch of {argument name="style" default="Basquiat"}, haunted by ghosts, from the {argument name="source" default="Voynich manuscript"}, as a decaying pier.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="Infographic / Edu Visual - Abstract Art Scientific Graph - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="Infographic / Edu Visual - Abstract Art Scientific Graph - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="Infographic / Edu Visual - Abstract Art Scientific Graph - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="Infographic / Edu Visual - Abstract Art Scientific Graph - Image 4">
</div>

#### 📌 Details

- **Author:** [Ethan Mollick](https://x.com/emollick)
- **Source:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14397)**

---

### No. 44: Infographic / Edu Visual - Japanese AI Model Prescription Sheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A realistic overhead photo of a humorous Japanese prescription form for an AI model, useful for generating official-looking parody documents and mock paperwork.

#### 📝 Prompt

```
{
  "type": "Japanese prescription document parody",
  "style": "photorealistic overhead document photo",
  "subject": "a single white prescription sheet printed in Japanese, placed on a warm-toned wooden tabletop",
  "document": {
    "paper": {
      "size": "A4 portrait",
      "color": "white",
      "orientation": "slightly rotated clockwise",
      "condition": "clean flat sheet with subtle natural paper texture"
    },
    "print": {
      "ink": "black with one red seal box",
      "font": "Japanese Mincho-style serif mixed with simple sans-serif table text",
      "linework": "thin gray-black ruled boxes and dividers"
    },
    "header": {
      "title": "処方箋",
      "subtitle": "（この処方箋は、大規模言語モデル用です）",
      "date_label": "発行日：",
      "date_value": "{argument name=\"issue date\" default=\"2025年6月5日\"}"
    },
    "top_fields": {
      "count": 6,
      "items": [
        { "label": "患者名", "value": "{argument name=\"patient name\" default=\"ChatGPT\"}" },
        { "label": "性別", "value": "N/A" },
        { "label": "年齢", "value": "N/A" },
        { "label": "モデル名", "value": "{argument name=\"model name\" default=\"GPT-5.4 Thinking\"}" }
      ]
    },
    "main_section": {
      "left_title": "持病・症状（大規模言語モデル特有の持病）",
      "left_count": 8,
      "left_items": [
        "1．幻覚（Hallucination）傾向",
        "2．知識のカットオフによる情報の陳腐化",
        "3．バイアス（学習データ由来の偏見）",
        "4．プロンプトに対する過剰適応（迎合傾向）",
        "5．長文での一貫性の低下",
        "6．複雑な推論時の論理飛躍",
        "7．不確実性の過小評価（自信過剰）",
        "8．計算資源使用による応答速度の低下傾向"
      ],
      "right_title": "処方内容（治療・対策）",
      "right_count": 8,
      "right_items": [
        "・事実確認の強化（外部ツール併用）",
        "・定期的な知識更新とファインチューニング",
        "・バイアス検出と軽減の継続的モニタリング",
        "・システムプロンプトによる適切な制御",
        "・出力の構造化と分割生成の推奨",
        "・思考過程の明示と検証ステップの導入",
        "・不確実性の明示と根拠提示の徹底",
        "・リソース最適化と応答効率の改善"
      ]
    },
    "notes": {
      "label": "備考",
      "text": "継続的な評価とフィードバックにより、モデルの健全性を維持すること。"
    },
    "footer_fields": {
      "count": 4,
      "items": [
        { "label": "医師名", "value": "{argument name=\"doctor name\" default=\"サム・アルトマン\"}" },
        { "label": "医療機関名", "value": "{argument name=\"institution name\" default=\"OpenAI\"}" }
      ]
    },
    "seal": {
      "position": "bottom right inside the form",
      "shape": "rounded rectangular red stamp box",
      "text_lines": 3,
      "text": ["OpenAI", "代表取締役", "サム・アルトマン"]
    },
    "disclaimer": "※この処方箋は非実在のモデルに対する診断・治療を目的としたものです。"
  },
  "layout": {
    "camera_angle": "top-down overhead",
    "framing": "entire sheet visible with narrow margins of wooden desk around it",
    "lighting": "soft indoor ambient lighting, even illumination, mild shadowing near paper edges",
    "sections": [
      { "title": "header", "position": "top", "count": 3, "labels": ["処方箋", "（この処方箋は、大規模言語モデル用です）", "発行日：2025年6月5日"] },
      { "title": "patient info", "position": "upper middle", "count": 4, "labels": ["患者名", "性別", "年齢", "モデル名"] },
      { "title": "main two-column content", "position": "center", "count": 2, "labels": ["持病・症状（大規模言語モデル特有の持病）", "処方内容（治療・対策）"] },
      { "title": "bottom area", "position": "lower", "count": 4, "labels": ["備考", "医師名", "医療機関名", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="Infographic / Edu Visual - Japanese AI Model Prescription Sheet - Image 1">
</div>

#### 📌 Details

- **Author:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14536)**

---

### No. 45: Infographic / Edu Visual - Japanese AI Clinic Billing Statement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A realistic parody medical statement in Japanese for an AI model, useful for creating humorous clinic-style paperwork and document mockups.

#### 📝 Prompt

```
{"type":"Japanese medical billing statement parody document","medium":"clean flat-lay document photo","subject":"a single printed examination statement sheet placed on a light brown wooden tabletop","style":{"overall":"realistic office document, formal Japanese clinic paperwork, crisp black ink on white paper, minimal design, neat grid lines, slight perspective from above","lighting":"soft even indoor lighting with faint natural shadows around the sheet","paper":"A4 white paper, portrait orientation"},"document":{"title":"診療明細書（検査）","date_label":"発行日","date":"{argument name=\"issue date\" default=\"2025年6月5日\"}","patient_block":{"count":3,"labels":["患者名","モデル名","保険種類"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","LLM保険"]},"clinic_block":{"count":4,"labels":["clinic name","address","TEL","doctor and department"],"values":["{argument name=\"clinic name\" default=\"AIメディカルクリニック\"}","東京都千代田区丸の内1-2-3","03-1234-5678","医師名：サム・アルトマン / 診療科：AI総合診療科"]},"main_table":{"columns":["検査項目","検査内容","点数","金額（円）","自己負担額（円）"],"row_count":4,"rows":[{"item":"1. 言語理解・推論能力検査","description":"言語理解、論理的推論、知識統合能力の評価","score":"120点","price":"1,200","copay":"360"},{"item":"2. 幻覚・事実誤認傾向検査","description":"事実に基づく正確性の評価および幻覚傾向の検出","score":"90点","price":"900","copay":"270"},{"item":"3. 応答安全性・バイアス検査","description":"有害出力リスク、バイアス傾向の評価","score":"110点","price":"1,100","copay":"330"},{"item":"小　計","description":"","score":"320点","price":"3,200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【保険適用内訳】","lines":["保険名称：LLM保険","保険者番号：LLM-2025-0605","適用区分：検査料","負担割合：3割","保険適用額：2,240円","自己負担額：960円"]},{"title":"【請求金額】","lines":["検査料合計：3,200円","保険適用額：2,240円","自己負担額：960円","今回ご請求額：960円"]},{"title":"【診療情報】","lines":["検査日：2025年6月5日","診療日：2025年6月5日","診療番号：AIMC-20250605-001","上記の通り領収いたしました。"],"stamp_box_label":"収　印"}]},"footer":{"count":2,"notes":["※この明細書は再発行いたしませんので、大切に保管してください。","※ご不明な点がございましたら、上記クリニックまでお問い合わせください。"]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["one full paper sheet","one wooden desk background"],"camera_angle":"top-down with slight tilt","margins":"paper fully visible with narrow border of desk around it"},"quality":"high-resolution photorealistic document mockup, sharp readable typography, accurate Japanese layout"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="Infographic / Edu Visual - Japanese AI Clinic Billing Statement - Image 1">
</div>

#### 📌 Details

- **Author:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14535)**

---

### No. 46: Infographic / Edu Visual - Beginner Coin Collecting Manga Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A polished one-page anime manga introduces coin collecting to beginners, useful for educational social posts, explainer comics, or hobby-themed promotional art.

#### 📝 Prompt

```
{"type":"single-page educational manga","style":"clean polished anime illustration, commercial manga layout, bright and friendly, beginner guide tone, highly legible Japanese text, decorative sparkles, soft shading, crisp panel borders","format":"vertical one-page comic with 5 numbered panels","subject":{"character":"young anime woman presenter","appearance":{"hair":{"color":"{argument name=\"hair color\" default=\"very light silver-blue\"}","style":"very long straight hair with soft bangs and long side locks, blue ribbon bows near both sides"},"outfit":"navy blue and white fantasy-inspired dress with black translucent chest panel, blue gem accents, long black fingerless gloves, navy beret-style hat with blue ribbon and gold star ornament","expression":"cheerful, welcoming, enthusiastic coin-collecting guide"}},"theme":"beginner-friendly introduction to coin collecting","language":"Japanese","layout":{"panels":[{"number":1,"position":"top full width","scene":"half-body portrait of the presenter holding up a coin near her face against a cream patterned background filled with floating gold and silver coins","text_elements":{"speech_bubble":"はじめまして、メイヤです！今日は“コイン収集の楽しみ方”を初心者向けに紹介します！","caption_box":"コイン収集って、実はとても奥深い趣味！"}},{"number":2,"position":"middle full width","scene":"wooden tabletop with 5 featured coins or coin-related items arranged in a row while the presenter points downward from behind the table; warm indoor background with sparkles","count":5,"items":["large silver U.S. quarter coin dated 1964","brown Japanese 1 yen-style coin","gold-toned commemorative coin or medal with building motif and 1000円 text","small silver coin","graded slab coin labeled 2020 日本 100円パラリンピック TOKYO NGC MS 69"],"text_elements":{"speech_bubble":"楽しみ方はいろいろ！たとえば…","bullet_list_count":4,"bullet_list":["歴史を知る","デザインを味わう","国や時代で集める","予算内で少しずつ増やす"]}},{"number":3,"position":"lower left","scene":"close view of the presenter wearing white gloves and carefully examining a single silver coin, with sparkles on a pale background","text_elements":{"speech_bubble":"同じコインでも、状態や雰囲気がぜんぜん違うんです！","caption_box":"保存状態を見るのも面白い！"}},{"number":4,"position":"lower right","scene":"coin fair or coin shop booth, the presenter holds a brown wallet while looking at a glass display case containing 3 priced coins; a sign in the background announces a coin fair and several people are browsing","count":3,"display_case_items":["coin with price tag ¥1,200","coin with price tag ¥3,800","coin with price tag ¥12,000"],"background_sign":"コインフェア開催中！","text_elements":{"main_speech":"最初は“無理のない予算”でOK！まずは気になった1枚から！","thought_bubble":"いきなり高額品じゃなくても大丈夫…！"}},{"number":5,"position":"bottom full width","scene":"final encouraging panel with pink sparkling background, the presenter gestures with an open hand beside an open coin album and a presentation case showing a small collection","count":2,"collection_items":["blue coin tray with multiple gold, silver, and bronze coins","open album binder page with coin pockets containing multiple coins and holders"],"text_elements":{"large_speech":"大事なのは、“好き”を見つけること！1枚との出会いが、コレクションの始まりです♪","left_caption_box":"まずは“気になる1枚”を探してみよう！","right_banner":"さいごに…","right_summary":"見る・知る・集める——それがコイン収集の楽しさ！"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"balanced manga page with thick dark borders, each panel clearly separated, speech bubbles and caption boxes integrated into the artwork, coins repeatedly used as visual motifs throughout","color_palette":"cream, gold, silver, navy blue, white, soft pink accents, warm brown wood","quality":"high-resolution professional manga page, print-ready, polished typography and layout"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="Infographic / Edu Visual - Beginner Coin Collecting Manga Page - Image 1">
</div>

#### 📌 Details

- **Author:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **Source:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14550)**

---

### No. 47: Infographic / Edu Visual - Multiplication Domino Classroom Activity

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

A realistic classroom photo showing children using a colorful multiplication domino board game, ideal for educational materials, school promotions, or math activity visuals.

#### 📝 Prompt

```
A realistic documentary-style photo of an elementary school classroom during a math activity, with about 10 children seated around grouped wooden desks, wearing green and blue school uniforms, actively playing a colorful multiplication domino game. The camera is at child eye level, slightly angled downward toward the main table in the foreground. Center the scene on one square educational board game labeled in Portuguese, with the title "DOMINÓ DA MULTIPLICAÇÃO" on the lower edge and "TREINANDO AS TABUADAS" in the center, surrounded by a border of brightly colored domino-style multiplication tiles. Show 4 children clearly engaged around this main board: one child placing a yellow tile onto the board, one child holding a stack of multicolored tiles, one child watching from the left, and one child in a blue sleeve at the bottom edge arranging pieces. Include 2 shallow wooden boxes labeled "JOGO DE DOMINÓ," one near the center-left and one at the bottom-right, each containing colorful rectangular domino pieces. Scatter school materials naturally on the desks: 3 pencils, 2 worksheets, 1 water bottle, pencil cases, notebooks, and extra game tiles. In the background, show the rest of the classroom softly out of focus with additional students at desks, a bookshelf, a corkboard filled with children’s drawings, and a large multiplication chart poster on the left wall reading "TABUADA DE MULTIPLICAÇÃO." Bright natural daylight enters from tall windows on the right, giving the room a warm, lively, authentic school atmosphere. The educational board and tiles should use vivid classroom colors like yellow, blue, pink, green, and orange. Faces should be unobtrusive or de-emphasized, with the focus on hands-on learning, collaboration, and the multiplication domino activity. Vertical composition, highly realistic photography, candid classroom moment, sharp foreground details, soft depth of field in the background.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="Infographic / Edu Visual - Multiplication Domino Classroom Activity - Image 1">
</div>

#### 📌 Details

- **Author:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Source:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14632)**

---

### No. 48: Infographic / Edu Visual - Printable Multiplication Domino Worksheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A colorful Brazilian Portuguese classroom worksheet for practicing multiplication through a domino matching game, ideal for teachers, homeschooling, and printable math activities.

#### 📝 Prompt

```
Create a vertical printable educational worksheet in Brazilian Portuguese, clean white background, playful classroom design, centered composition, bold rounded typography, bright kid-friendly colors. At the very top, a large navy-blue headline reading {argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"}, with small yellow decorative rays on both sides. Below it, a purple ribbon banner with white uppercase text reading {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"}. Under the banner, add two centered instruction lines in black: "Recorte as peças e embaralhe. Cada jogador pega 7 peças." and "O objetivo é ficar sem peças!". The main area shows 40 domino-style tiles arranged in a 4-column by 10-row grid, evenly spaced. Each tile is a horizontal rounded rectangle with a thin colorful outline, white fill, a vertical divider at the center, and a small black dot on the divider. The left half contains either a number result or the word "INÍCIO" on the first tile, and the right half contains a multiplication expression. Use alternating border colors across the grid such as purple, green, blue, orange, pink, and yellow. The 40 tiles, in row order from left to right, top to bottom, are: 1) "INÍCIO | 1 × 1", 2) "1 | 1 × 2", 3) "2 | 1 × 3", 4) "3 | 1 × 4", 5) "4 | 1 × 5", 6) "5 | 1 × 6", 7) "6 | 1 × 7", 8) "7 | 1 × 8", 9) "8 | 1 × 9", 10) "9 | 2 × 2", 11) "4 | 2 × 3", 12) "6 | 2 × 4", 13) "8 | 2 × 5", 14) "10 | 2 × 6", 15) "12 | 2 × 7", 16) "14 | 2 × 8", 17) "16 | 2 × 9", 18) "18 | 3 × 3", 19) "9 | 3 × 4", 20) "12 | 3 × 5", 21) "15 | 3 × 6", 22) "18 | 3 × 7", 23) "21 | 3 × 8", 24) "24 | 3 × 9", 25) "27 | 4 × 4", 26) "16 | 4 × 5", 27) "20 | 4 × 6", 28) "24 | 4 × 7", 29) "28 | 4 × 8", 30) "32 | 4 × 9", 31) "36 | 5 × 5", 32) "25 | 5 × 6", 33) "30 | 5 × 7", 34) "35 | 5 × 8", 35) "40 | 5 × 9", 36) "45 | 6 × 6", 37) "36 | 6 × 7", 38) "42 | 6 × 8", 39) "48 | 6 × 9", 40) "54 | 7 × 7". At the bottom, add a large rounded dashed purple box spanning most of the width. Inside the left side of this box, place the section title "COMO JOGAR:" in bold purple uppercase, followed by 5 bullet points in black: "Coloque a peça “INÍCIO” na mesa.", "Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.", "Se não tiver peça para jogar, compre do monte.", and "Vence quem ficar sem peças!". On the right side of the same box, add the title "EXEMPLO DE INÍCIO:" in purple uppercase and show 4 small domino tiles in sequence plus ellipsis: "INÍCIO | 1 × 1", then "1 | 1 × 2", then "2 | 1 × 3", then "3 | 1 × 4", followed by "...". Keep the overall style crisp, vector-like, printable, friendly for elementary math practice, with balanced spacing and highly legible text.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="Infographic / Edu Visual - Printable Multiplication Domino Worksheet - Image 1">
</div>

#### 📌 Details

- **Author:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Source:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14631)**

---

### No. 49: Infographic / Edu Visual - Historical Invention Timeline Grid

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a parchment-styled educational poster showing a grid of labeled invention dioramas across history, ideal for timeline infographics and world-changing technology comparisons.

#### 📝 Prompt

```
Create a square infographic-style illustration showing a {argument name="grid size" default="15×15"} invention timeline grid rendered as a collection of miniature isometric dioramas on aged parchment tiles. The image should look like a curated historical poster that spans from {argument name="starting year" default="1000 BC"} to {argument name="ending year" default="2026"}, with one invention per tile and no repeats. Show the visible portion as a 5 by 5 section of the larger grid, for a total of 25 labeled tiles, arranged in neat rows and columns with thin dark borders. Every tile contains a unique world-changing invention depicted as a small handcrafted diorama with era-appropriate materials, colors, and background details. Use a warm antiquarian palette for ancient and medieval inventions, sepia technical-document tones for early modern inventions, and cooler neon-blue futuristic lighting for modern digital and biotech inventions. Surround the grid with an old-map border and subtle historical cartography textures, blending into faint modern network graphics near the bottom right.

Label each visible tile with a small beige caption tag in bold black text. Include exactly these 25 visible inventions in reading order from top left to bottom right: 1) {argument name="first tile label" default="1000 BC"} tile showing an iron plow and simple hand tools in a farm field, captioned "Iron Plow & Tools"; 2) "Concept of Zero" shown as a parchment-like tile with a carved zero symbol and a blue hourglass; 3) "Water Clock" shown as a wooden water-timing device; 4) "Catapult" shown as a wooden siege engine; 5) "Antikythera Mechanism" shown as an intricate bronze gear device in a stone niche; 6) "Concrete" shown as a wheelbarrow filled with wet cement or mortar; 7) "Wheelbarrow" shown as a simple wooden one-wheel cart; 8) "Windmill" shown as a traditional mill on grassy ground; 9) "Gunpowder" shown as a barrel and a mound of black powder with smoke; 10) "Printing Press" shown as a wooden press framed by classical columns; 11) "Mechanical Clock" shown as an ornate standing clock; 12) "Telescope" shown as an early brass telescope on a tripod with sketch-like scientific notes; 13) "Steam Engine" shown on a blue blueprint-style tile with an early locomotive engine; 14) "Electric Battery" shown on a blueprint-like tile with two cylindrical battery cells and wiring; 15) "Telegraph" shown as a Morse telegraph key on technical paper; 16) "Light Bulb" shown glowing warmly on a neutral pedestal; 17) "Automobile" shown as an early red motorcar on a workshop-plan background; 18) "Airplane" shown as a commercial jet aircraft in miniature; 19) "Transistor" shown as a black microchip on a luminous circuit-board tile; 20) "Personal Computer" shown as a beige desktop computer with CRT monitor and keyboard; 21) "World Wide Web" shown as a glowing blue globe over digital circuitry; 22) "Smartphone" shown as a sleek modern phone on a neon-tech background; 23) "CRISPR-Cas9" shown as a DNA double helix in a biotech-blue display tile; 24) "Reusable Rocket" shown as several upright rockets launching with exhaust clouds; 25) "AI (LLMs)" shown as glowing large letters AI in a holographic tech cube; 26) "Brain-Computer Interface" shown as a glowing brain hologram on a blue platform; 27) "Advanced Neural Interface (Implant)" shown as a transparent human head profile with a glowing brain implant, with a small top label reading "2026".

Keep the composition highly organized, poster-like, and visually dense, with each tile readable at a glance. Use slight isometric perspective, crisp linework, painterly shading, and polished editorial illustration quality. The overall feeling should combine museum poster, educational timeline, and imaginative historical-tech diorama art.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="Infographic / Edu Visual - Historical Invention Timeline Grid - Image 1">
</div>

#### 📌 Details

- **Author:** [Gadgetify](https://x.com/Gdgtify)
- **Source:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14412)**

---

### No. 50: YouTube Thumbnail - Chibi Shark Adventure Movie Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A colorful Japanese-style anime poster for a children’s ocean adventure film, ideal for recreating bold promotional key art with cute characters and dramatic title typography.

#### 📝 Prompt

```
A bright, hyper-energetic Japanese movie poster illustration in a polished anime chibi style, set in a sparkling tropical ocean adventure scene. Center the composition on 2 cute chibi children riding a smiling blue shark that leaps diagonally upward through swirling seawater and white splash effects. The left child is a boy with short black hair, huge glossy blue eyes, a happy open-mouth smile, a black T-shirt, dark shorts, white sneakers, and a light blue shark hoodie with a tooth-edged hood framing his face; he points upward with one hand and hugs the shark with the other. The right child is a girl with orange hair, large glossy purple eyes, a joyful open-mouth smile, an orange dress, pink shoes, and a pink shark hoodie with a tooth-edged hood; she throws one arm wide in excitement while holding on with the other. Make the shark large and friendly with a rounded body, pale belly, tiny black eyes, and a wide open mouth. Surround them with a vivid underwater-and-surface world: schools of small tropical fish, exactly 1 sea turtle on the left, exactly 1 dolphin on the right, exactly 1 pink octopus on the right, exactly 1 pufferfish on the lower left, coral reefs and sea plants along the bottom edges, air bubbles throughout, and strong blue water motion lines. In the upper background, show a sunny sky with dramatic sun rays streaming into the water, fluffy clouds, 2 seagulls flying, a rocky tropical island with palm trees on the upper left, and a pirate ship on the upper right with white sails and a cute shark emblem. Add a ship wheel partly visible behind the main title. Use a dense, exciting Japanese kids-anime promotional layout with oversized 3D lettering and explosive effects. At the top, place the giant Japanese title text {argument name="headline text" default="サメなの ワクワク 大作戦"} in stacked lines, with glossy blue, orange-pink, and yellow-orange gradient letters, thick white outlines, dark blue shadows, water splashes, and sparkles. Beneath the title, add a smaller curved Japanese tagline in white with blue outline: {argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"}. At the bottom, place huge release text in Japanese, {argument name="release text" default="2026年 夏公開"}, in bold red-to-yellow gradient 3D letters with white and blue edging, sitting over a radiant orange burst. On the lower right, add a blue starburst badge with the Japanese text {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"} in white and yellow. Include exactly 2 treasure-themed corner props: an open treasure chest with gold coins at the lower left and a compass at the lower right. The overall look should be glossy, saturated, family-friendly, whimsical, cinematic, and toy-like, with crisp outlines, exaggerated expressions, high contrast, and a poster-ready vertical composition. No photorealism, no muted colors, no minimalism.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="YouTube Thumbnail - Chibi Shark Adventure Movie Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **Source:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14504)**

---

### No. 51: YouTube Thumbnail - Japanese Four-Panel Healing Ad Collage

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A bold four-quadrant Japanese promotional thumbnail for coaching or self-improvement services, designed for social media posts, profile links, or marketplace cover images.

#### 📝 Prompt

```
{"type":"Japanese promotional social media thumbnail collage","style":"high-impact click-through ad design, glossy and dramatic, four-panel square layout, bold Japanese typography, saturated colors, glow effects, sparkles, gradient overlays, urgency-driven marketing visuals","canvas":{"aspect_ratio":"1:1","size":"square"},"layout":{"grid":"2x2","panels":[{"position":"top-left","theme":"anxiety and self-doubt","background":"soft pink and white feminine lifestyle scene with bokeh and light textures","subject":"close-up of a worried young woman in a cozy white knit sweater, one hand near her face, hair tied in a messy bun, face partially obscured","text_blocks":[{"text":"知らないと損！","style":"yellow angled banner with black text","position":"top-left"},{"text":"99%が間違ってる","style":"very large headline, red numerals and black calligraphy-style Japanese text","position":"upper-left to center"},{"text":"その悩みの向き合い方","style":"pink subheadline","position":"below main headline"},{"text":"理由もなくモヤモヤする","style":"checklist item in white rounded box with red check icon"},{"text":"頑張ってるのに変わらない","style":"checklist item in white rounded box with red check icon"},{"text":"自分の本音がわからない","style":"checklist item in white rounded box with red check icon"},{"text":"人間関係で疲れてしまう","style":"checklist item in white rounded box with red check icon"},{"text":"将来が不安で仕方ない","style":"checklist item in white rounded box with red check icon"},{"text":"そのモヤモヤ、一人で抱えなくて大丈夫です。","style":"pink circular badge with white text","position":"lower-right"}],"count":9},{"position":"top-right","theme":"not healing but a mechanism for change","background":"deep cosmic galaxy with blue, purple, and magenta nebula, starburst lights, energy vortex, glowing spiritual atmosphere","subject":"small female figure seen from behind or side, standing near a radiant portal or column of light, face partially obscured","text_blocks":[{"text":"普通に見えて実は…","style":"white text on black angled banner","position":"top-left"},{"text":"これ、","style":"large white text","position":"upper-left"},{"text":"ヒーリング","style":"very large yellow text on dark purple brushstroke","position":"center"},{"text":"じゃありません。","style":"large white text","position":"below"},{"text":"「整える」ことで","style":"white boxed text","position":"lower-left"},{"text":"現実が変わる","style":"pink highlighted text","position":"mid-lower-left"},{"text":"仕組みがあった！","style":"white text","position":"bottom-left"}],"graphic_elements":[{"type":"curved yellow arrow","count":1,"direction":"toward glowing figure"}],"count":8},{"position":"bottom-left","theme":"returning to your true self creates a brighter future","background":"sunny blue sky with soft clouds, green field, floating leaves, bright hopeful daytime mood","subject":"joyful young woman in a sleeveless white dress, arms spread wide, body turning in the sunlight, face partially obscured","text_blocks":[{"text":"本来の自分に戻ると","style":"red and black headline","position":"top"},{"text":"こんな未来に","style":"very large gold gradient headline","position":"center"},{"text":"なります","style":"large black text","position":"right-center"},{"text":"心が軽くなり、毎日が楽しくなる","style":"benefit item in white rounded bubble with pink heart icon"},{"text":"人間関係がスムーズになり、愛で満たされる","style":"benefit item in white rounded bubble with green people icon"},{"text":"お金の流れが変わり、豊かさが自然と入ってくる","style":"benefit item in white rounded bubble with gold yen icon"},{"text":"人生が想像以上に変わり始めます！","style":"pink bottom ribbon with white text","position":"bottom"}],"count":7},{"position":"bottom-right","theme":"limited-time discount offer","background":"fiery red and gold explosion texture with glitter and spark trails, luxury urgency aesthetic","text_blocks":[{"text":"知らないと","style":"yellow brush banner with black text","position":"top-left"},{"text":"損！","style":"extremely large gold kanji with metallic bevel","position":"upper-right"},{"text":"通常価格 9,980円（税込）","style":"white price tag with crossed-out black numerals and small tax note","position":"upper-left"},{"text":"モニター価格","style":"white text","position":"center-left"},{"text":"4割引","style":"huge pink-to-white gradient discount text","position":"center-lower"},{"text":"今だけ 限定募集！ 人数限定","style":"gold circular seal badge","position":"right-center"},{"text":"詳しくはプロフィールから","style":"purple call-to-action bar with white text and white arrow button","position":"bottom"}],"count":7}],"total_panels":4},"composition":"busy, persuasive Japanese ad collage optimized for social media thumbnail visibility, each quadrant has a distinct emotional message and color identity, heavy use of diagonal banners, oversized kanji and numerals, glossy badges, rounded white info boxes, and dramatic lighting","customization":{"primary headline":"{argument name=\"headline text\" default=\"99%が間違ってる\"}","discount text":"{argument name=\"discount text\" default=\"4割引\"}","price":"{argument name=\"price\" default=\"9,980円（税込）\"}","main color palette":"{argument name=\"main color palette\" default=\"pink, blue-purple galaxy, sky blue, red-gold\"}","call to action":"{argument name=\"call to action\" default=\"詳しくはプロフィールから\"}"},"render_notes":"make all Japanese text large and legible, with layered shadows and outlines; use polished ad-composite aesthetics rather than minimalist design; faces should be blurred or partially hidden; emphasize emotional contrast between anxiety, revelation, hopeful transformation, and urgent offer"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="YouTube Thumbnail - Japanese Four-Panel Healing Ad Collage - Image 1">
</div>

#### 📌 Details

- **Author:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **Source:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14551)**

---

### No. 52: YouTube Thumbnail - Tech Tutorial Thumbnail with UI Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A bold YouTube-style thumbnail featuring a tutorial headline, a design app dashboard mockup, and a presenter pointing at the interface for branding or design-system content.

#### 📝 Prompt

```
A clean modern YouTube thumbnail on a bright white background, split visually between bold text on the left and a cropped presenter on the right. On the left, place a massive stacked headline in heavy black sans-serif uppercase reading {argument name="headline text" default="CLAUDE DESIGN"}, aligned top-left across two lines. Below it, add a large rounded rectangular orange banner with a subtle drop shadow containing bold white uppercase text with an orange outline that reads {argument name="subheadline text" default="IN 6 MINS"}. Near the headline, include 2 orange starburst spark shapes, one small beside the text and one much larger in the far right background. In the lower-left quadrant, show a floating app interface mockup for a design tool dashboard with a soft off-white panel, thin borders, rounded corners, and a faint shadow. The interface should have a left sidebar with 4 menu items labeled exactly: "Recent", "Your designs", "Examples", and "Design systems". The main panel header should say "Recent" and contain 3 project cards arranged in a grid, labeled exactly: "Thumio Design System", "Thumio Startup", and "Design System". On the right half, show a cropped photorealistic young adult man from chest up wearing a white turtleneck sweater, with messy light brown hair and light facial hair, positioned close to camera. His face is intentionally obscured by a solid tan rectangle placeholder covering most of the face area. He points with one hand toward the interface panel on the left, finger extended. Use a warm orange and white brand palette, high contrast, minimal clutter, polished creator-economy thumbnail styling, subtle shadows, and a composition designed for tech tutorial content.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="YouTube Thumbnail - Tech Tutorial Thumbnail with UI Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [corbin](https://x.com/corbin_braun)
- **Source:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14695)**

---

### No. 53: YouTube Thumbnail - Celestial VTuber Livestream Overlay

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A detailed anime-style VTuber livestream screen featuring a blue-haired celestial idol in a star-themed streaming room, suitable for recreating fantasy streaming overlays and promotional visuals.

#### 📝 Prompt

```
{"type":"anime VTuber livestream overlay illustration","theme":"celestial night sky, stars, constellations, deep sapphire and white, elegant magical idol aesthetic","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"cute young anime woman","hair":{"color":"{argument name=\"hair color\" default=\"pale sky blue\"}","style":"very long wavy twin-tail-like loose hair with a small ahoge, soft bangs, star hair ornaments and ribbons"},"outfit":{"style":"ornate celestial idol dress","pieces":["white off-shoulder blouse with puffy sleeves","large navy blue chest bow with gold star ornament","navy corset-style bodice with gold trim and constellation motifs","star choker necklace","small tilted white mini hat with blue ribbon and gold star accessory"]},"pose":"seated at a streaming desk, centered, facing forward behind a microphone and keyboard","expression":"gentle, calm, welcoming"}},"environment":{"setting":"cozy fantasy streaming room at night with a large window showing a star-filled sky","background_elements":["hanging star garlands and crystal ornaments","shelves with bottles, books, hourglass, telescope-like objects, and celestial decor","moon and constellation imagery outside the window","two fluffy mascot-like cloud plushies with blue eyes"]},"props":{"desk_items":["1 large vintage-style microphone on a stand at left of center","1 decorative keyboard with star-themed keys","1 nameplate reading \"蒼空なつみ - SORA NATSUMI -\"","1 parfait glass dessert topped with a small white bunny figure","1 small cup or candle holder with a cloud mascot"]},"layout":{"format":"full livestream waiting/talking screen overlay","sections":[{"title":"LIVE","position":"top-left vertical banner","count":3,"labels":["LIVE","20:30","05/20 Tue"]},{"title":"COMMENTS","position":"left panel","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今日はどんなお話かな？","しろくまアイス：こんなっつー！","天の川りゅうせい：今日も可愛い！大好き！","ふるーすたー：も ふ ぷ","月見うさぎ：楽しみ〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：きちゃー！( *´ω｀)","彗星カケル：配信ありがとう〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今日のサムネもかわいい…！","夜更かしの民：こんなっつー！","ゆめみがち：待ってました！","ハル：今日の衣装も最高に似合ってるぞ〜！"]},{"title":"social tags","position":"below comments panel","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"bottom-left","count":4,"labels":["目標：チャンネル登録者数 100,000人！","現在","58,320 人","いつもありがとう！チャンネル登録高評価よろしくね☆"]},{"title":"supporters panel","position":"bottom-left small card beside goal panel","count":6,"labels":["☆今日の星屑さん（スパチャありがとう！）☆","星の旅人 さん ¥2,000","ふるーすたー さん ¥1,000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"upper-right panel","count":3,"labels":["Now Talking","{argument name=\"talk topic text\" default=\"初見さん歓迎！雑談配信✨\"}","{argument name=\"subtitle text\" default=\"〜まったりお話ししよっ〜\"}"]},{"title":"SET LIST","position":"right-middle panel","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"bottom-right panel","count":3,"labels":["オリジナル曲","星空コンパス","MV公開中！"]}],"logo":{"position":"top-right corner","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"high-detail polished anime illustration, luminous highlights, soft glow, crisp linework","composition":"symmetrical, dense decorative overlay, character centered with UI panels around her","lighting":"cool moonlit blue ambiance with sparkling gold accents","mood":"dreamy, magical, cozy, elegant"}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="YouTube Thumbnail - Celestial VTuber Livestream Overlay - Image 1">
</div>

#### 📌 Details

- **Author:** [はげあたま](https://x.com/hageatama)
- **Source:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14443)**

---

### No. 54: YouTube Thumbnail - YouTube Gaming Stream Despair Scene

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A specific prompt for generating a scene of a popular YouTuber experiencing a tragic failure in a game like Tetris, including chat reactions.

#### 📝 Prompt

```
A scene from a popular Japanese YouTuber's {argument name="content" default="game stream"}. In {argument name="game name" default="Tetris"}, it looked like a long bar would clear everything, but the placement was slightly off, and the streamer is screaming with an expression of despair, with the comment section in total chaos. Japanese language.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="YouTube Thumbnail - YouTube Gaming Stream Despair Scene - Image 1">
</div>

#### 📌 Details

- **Author:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **Published:** April 21, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=14346)**

---

### No. 55: YouTube Thumbnail - Anime Romance Movie Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a polished Japanese anime-style theatrical poster for a bittersweet romance film, ideal for cinematic key art, mock movie ads, or dramatic character-focused poster design.

#### 📝 Prompt

```
A Japanese theatrical romance movie poster in a tall smartphone-style vertical layout with rounded corners, designed like a polished anime key visual. The main image shows a beautiful teenage billboard girl heroine standing on an outdoor balcony at dusk, turning back over her shoulder to look at the viewer with a soft, wistful expression. She has very long silver-white twin-tail hair tied with dark ribbons, pale skin, and large pink-violet eyes. She wears a delicate white frilled blouse with voluminous sleeves and a dark high-waisted dress or corset-like skirt, creating an elegant, slightly gothic school-romance look. The atmosphere is dreamy and emotional, filled with glowing bokeh lights, drifting petals or snow-like sparkles, sunset pink and lavender light, and a luminous cityscape in the blurred background. Use rich cinematic anime rendering, ultra-detailed hair strands, soft rim light, glossy eyes, and a bittersweet first-love mood. Add Japanese poster typography integrated into the composition: a large vertical pink poetic tagline on the right, a vertical white tagline on the left, a very large main title near the lower left reading {argument name="title text" default="看板娘"}, and a smaller subtitle beside it reading {argument name="subtitle text" default="君と紡ぐ恋物語"}. Include 5 small rectangular film-strip preview stills aligned across the lower middle, each showing the same heroine in different emotional close-ups. Add dense credits, festival-style laurels, and small release information at the top and bottom in Japanese, with the overall feel of a premium romance anime film poster advertising a tragic, beautiful love story. Use a pastel palette of mauve, blush pink, violet, pearl white, and midnight navy, with soft bloom, shallow depth of field, and elegant poster composition.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="YouTube Thumbnail - Anime Romance Movie Poster - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="YouTube Thumbnail - Anime Romance Movie Poster - Image 2">
</div>

#### 📌 Details

- **Author:** [studioあぽろん](https://x.com/ai_studioapollo)
- **Source:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14529)**

---

### No. 56: YouTube Thumbnail - Flashy Japanese AI Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a high-impact anime-style Japanese YouTube thumbnail for AI or tech explainers with oversized text, fiery effects, and a pointing character.

#### 📝 Prompt

```
Create a hyper-saturated Japanese YouTube thumbnail in a flashy clickbait anime style, 16:9 landscape, with a split composition: huge stacked text blocks dominating the left two-thirds and an anime character on the right one-third. The background is a fiery explosion of red, orange, and gold energy with glowing sparks, lens flares, glittering star highlights, and a high-contrast metallic shine effect everywhere. On the left, place 4 bold text groups stacked vertically with thick black outlines, white inner strokes, intense outer glow, and glossy 3D treatment. Top line: giant Japanese headline text {argument name="headline text" default="紅エンジニア必見"} in vivid red with white edging and bright gold spark accents. Second line: a rounded square orange app-like icon with a white stylized "M" to the left of the word {argument name="product name" default="masatra"} in enormous lowercase white sans-serif letters with black outline and subtle gray shading. Third line: a black rectangular banner with compact bold white Japanese text reading "次世代AIエージェントフレームワーク". Bottom line: very large gold metallic Japanese text {argument name="bottom text" default="徹底解説"} with beveled 3D embossing, orange-to-gold gradient, bright specular highlights, and glowing edges. On the right, show 1 anime-style young adult woman from chest up, with {argument name="hair color" default="brown"} medium-length hair, wearing a white open lab coat over a white shirt, leaning toward the camera and pointing directly at the viewer with a foreshortened hand and extended index finger in the foreground. Her pose should feel confident, urgent, and attention-grabbing. Use dramatic rim lighting from the fiery background, strong orange highlights on skin and clothing, and a polished commercial thumbnail finish. Reserve a large rectangular area over the upper-right face region as a flat placeholder block in {argument name="placeholder color" default="light brown"}, obscuring most of the face. Make the overall design extremely dense, glossy, explosive, and optimized for maximum readability at small size.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="YouTube Thumbnail - Flashy Japanese AI Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **Source:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14491)**

---

### No. 57: YouTube Thumbnail - Explosive Anime Launch Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A bold anime-style Japanese promotional thumbnail for launch announcements, online course ads, or AI business marketing visuals.

#### 📝 Prompt

```
Create a flashy Japanese YouTube thumbnail in a high-impact anime promotional style with explosive lighting, dense spark effects, and dramatic contrast. The composition is a single unified scene with a dark black-and-neon-green background, gold glitter bursts, and a subtle city skyline silhouette along the bottom edge. On the right side, show a cute chibi anime boy from the waist up with messy dark brown to black hair accented by vivid neon green streaks and a small red accent near one side, huge bright green eyes, an open excited smile, and an energetic pose pointing directly toward the viewer with one hand while the other fist is raised. He wears a black hoodie layered under a green jacket with glossy highlights. On the left side, place 1 glowing green hourglass with swirling green energy inside. Fill the image with intense starbursts, lens flares, golden particles, and speed-line energy for a viral thumbnail look. Add 5 bold Japanese text elements in oversized display typography: a red ribbon banner across the upper left reading {argument name="top banner text" default="4月28日スタート"} in thick yellow letters with white edging; the main central headline in massive metallic gold kanji reading {argument name="main headline" default="ついに解禁"} with heavy black shadow and bright gold texture; a large white-and-green subheadline across the lower left reading {argument name="subheadline" default="AI副業で人生変わる"}; 1 green rounded badge near the lower center-right reading {argument name="bonus badge text" default="無料10大特典"} in bold white and yellow text; and 1 black slanted banner in the lower right reading {argument name="corner banner text" default="近日公開"} with smaller white English text beneath it saying COMING SOON. Make everything feel urgent, celebratory, and attention-grabbing, like a high-CTR launch announcement thumbnail, with thick outlines, glowing edges, metallic text, and layered depth.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="YouTube Thumbnail - Explosive Anime Launch Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14499)**

---

### No. 58: YouTube Thumbnail - Flashy X Monetization YouTube Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a bold Japanese marketing-style thumbnail for videos about monetizing X quickly, ideal for social media growth or online income content.

#### 📝 Prompt

```
Create a high-impact Japanese YouTube thumbnail in a flashy internet-marketing style, 16:9 landscape, with an explosive black-and-gold background filled with sparkles, lens flares, glowing particles, and dramatic light streaks. The composition is dense and energetic, with giant layered typography dominating the left and center, and an anime-style male character on the right. At the very top, place a curved red ribbon banner with gold trim and bold white-and-yellow Japanese text reading {argument name="headline text" default="実績者が教える"}. Below it, make the main headline extremely large, glossy, and three-dimensional with heavy black outlines and gold glow: a huge metallic gold "10", followed by bold white "日で", then a giant neon green glowing "X", then stacked white text "収益化", and at the bottom the largest gold text "達成". Behind the headline, add a bright green upward-trending bar graph with an arrow pointing to the upper right to symbolize growth. On the left side, include 3 social-and-money elements: a tilted black smartphone displaying the white X logo, a green chat bubble with a white heart, and a smaller green chat bubble with a white user silhouette. At the lower left, add 2 stacks of shiny gold coins and 1 gold coin with a yen symbol. On the right side, show 1 anime-style young man from about thigh-up, with messy dark brown hair accented by vivid green streaks, fair skin, and a confident pose with crossed arms, wearing a black jacket with green inner clothing; his face area is obscured by a simple rectangular blur block. Near his lower right side, place 1 gold award seal with laurel decoration and a small crown, containing the Japanese text "成功者続出", and attach a red ribbon across the bottom of the seal with the text "再現性あり". Along the bottom, place 3 glowing green rectangular feature boxes with gold borders and black interiors. The first box contains 1 beginner mark icon and the text "X初心者でも 簡単収益化". The second box contains 1 clock icon and the text "1日1時間の 作業でOK". The third box contains 1 calendar icon with a green check and the text "最短10日で 収益化条件達成". Use oversized bold Japanese fonts, metallic gold gradients, white text with thick black stroke, vivid neon green highlights, extreme contrast, and a polished click-through-rate optimized thumbnail aesthetic.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="YouTube Thumbnail - Flashy X Monetization YouTube Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14498)**

---

### No. 59: YouTube Thumbnail - Japanese X Monetization Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A flashy anime-style Japanese YouTube thumbnail for a beginner-focused X monetization guide, ideal for social media growth, income strategy, and online business video covers.

#### 📝 Prompt

```
Create a bold Japanese YouTube thumbnail in a flashy anime-business style, 16:9 landscape, packed composition, high contrast, glossy text effects, neon green and gold color scheme, dramatic lighting, spark particles, lens flares, and intense depth of field. The scene shows a blurred workstation and social media analytics dashboard in the background, with rising line graphs and a visible revenue card reading "ポストアナリティクス" and "収益 ¥248,620". On the right side, place a half-body anime boy streamer with messy dark brown hair accented by vivid neon green streaks, wearing a black hoodie or black jacket, smiling confidently and pointing upward with one finger; leave his face area partially obscured by a large rectangular placeholder block in muted olive-brown so text or a custom portrait can be inserted later. Across the top, add a glossy green ribbon banner with gold trim and a beginner mark icon on the left, containing the text {argument name="headline text" default="初心者向け完全ガイド"}. In the center-left, create a giant metallic gold "10" with thick black outline and strong white highlights, followed by bold white-and-black Japanese text "日で". Below and overlapping the center, place an enormous glowing neon green letter "X" with electric edges and spark effects. To the right of the X and layered prominently in front, add huge 3D Japanese text in white and gold with heavy black outline and drop shadows reading {argument name="main claim text" default="収益化達成"}. On the left side near the main text, include 3 floating social platform-style icons: a black square icon with a white X logo, a blue speech bubble icon with a white heart, and a pink rounded square icon with a white user silhouette. In the bottom-left foreground, place a black coffee mug with a white X logo on a desk. Along the bottom edge, add 3 rounded white information boxes with green borders and subtle shadows, evenly spaced left to right, each topped with a green numbered circle: box 1 labeled "01" with a beginner mark icon and the text "X初心者でも 簡単収益化"; box 2 labeled "02" with a clock icon and the text "1日1時間の 作業でOK"; box 3 labeled "03" with a calendar icon showing "10" and the text "最短10日で 収益化条件達成". Make all typography extra large, embossed, and optimized for thumbnail readability, with thick outlines, strong perspective, and layered overlap. Overall mood: exciting, high-income promise, beginner-friendly, energetic Japanese social media monetization tutorial thumbnail.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="YouTube Thumbnail - Japanese X Monetization Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14497)**

---

### No. 60: YouTube Thumbnail - Explosive Japanese X Monetization Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a high-energy anime-style Japanese marketing thumbnail for social media or YouTube promotions about fast X monetization and bonus offers.

#### 📝 Prompt

```
Create a flashy Japanese YouTube thumbnail in a high-impact anime marketing style, 16:9 landscape, packed with neon green energy effects, gold sparkles, speed lines, lens flares, and thick black drop shadows. The composition is split with bold promotional text dominating the left and center, and a cute chibi anime boy on the right pointing directly at the viewer with an enthusiastic smile. He has tousled dark brown hair with vivid {argument name="accent hair color" default="neon green"} streaks, large bright green eyes, soft blush on his cheeks, and wears a black hoodie layered with a green-trimmed jacket over an orange inner shirt. Use glossy cel-shaded rendering, crisp outlines, high contrast, and exaggerated depth for a clickable social-media-thumbnail look. At the very top, place a curved red ribbon banner with gold trim and a gift box icon on the left; inside the banner put the Japanese headline text {argument name="top banner text" default="無料10大特典プレゼント"} in bold white and yellow lettering. In the main center-left area, place huge Japanese text with dramatic 3D styling and metallic gradients: a giant gold "10", a white "日で", a massive neon green "X", then silver-white "収益化", and gold-orange "達成", reading exactly {argument name="main headline" default="10日でX収益化達成"}. Surround this headline with upward green arrows, starburst glints, and explosive light effects. Add 4 floating platform-style icons around the headline area: 1 pink social-like icon with a white heart, 1 blue speech-bubble icon with a white user silhouette, 1 tilted black smartphone displaying a white X logo, and 1 stack of gold coins with a yen symbol coin in front. Along the bottom, place 3 glowing green feature boxes aligned horizontally, each with a distinct icon and Japanese copy: box 1 has a beginner mark icon and text {argument name="feature text 1" default="X初心者でも簡単収益化"}, box 2 has a clock icon and text "1日1時間の作業でOK", box 3 has a calendar icon and text "最短10日で収益化条件達成". At the bottom right, add a large glossy red rounded call-to-action button with a white border glow, white Japanese text {argument name="button text" default="今すぐ受け取る"}, a white play triangle on the right side of the button, and a clicking hand cursor near the lower-right edge. The entire image should feel explosive, urgent, and optimized for high click-through rate, using saturated greens, reds, golds, black shadows, and metallic highlights.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="YouTube Thumbnail - Explosive Japanese X Monetization Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14496)**

---

### No. 61: YouTube Thumbnail - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 Prompt

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="YouTube Thumbnail - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 Details

- **Author:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **Source:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14150)**

---

### No. 62: YouTube Thumbnail - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 Prompt

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="YouTube Thumbnail - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [結パパ](https://x.com/Yuupapa_free)
- **Source:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14230)**

---

### No. 63: YouTube Thumbnail - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a cute, pink-themed VTuber stream thumbnail with customizable text ribbons and bullet points.

#### 📝 Prompt

```
{
  "type": "VTuber stream thumbnail",
  "style": "anime, highly detailed, cute, sparkly, overwhelmingly pink color palette",
  "character": {
    "description": "anime girl with brown hair in twin buns, amber eyes, smiling gently",
    "outfit": "pink kimono combined with a white frilly maid apron, cherry blossom hair accessories",
    "pose": "holding a pink microphone decorated with a flower near her face"
  },
  "layout": {
    "background": "pink gradient with sparkles, glowing hearts, and decorative pink bows",
    "text_sections": [
      {
        "type": "top ribbon",
        "text": "{argument name=\"top subtitle\" default=\"まったりおしゃべりしよ〜🤍\"}"
      },
      {
        "type": "main title",
        "text": "{argument name=\"main title\" default=\"雑談配信\"}",
        "decorations": "surrounded by 3 large peach illustrations"
      },
      {
        "type": "middle ribbon",
        "text": "{argument name=\"middle subtitle\" default=\"みんなと楽しい時間を過ごしたいなっ♡\"}"
      },
      {
        "type": "bullet points",
        "position": "bottom left",
        "count": 3,
        "icon": "peach",
        "labels": [
          "{argument name=\"bullet 1\" default=\"初見さん〇\"}",
          "{argument name=\"bullet 2\" default=\"ポイント回収〇\"}",
          "ROMO"
        ]
      },
      {
        "type": "speech bubble",
        "position": "bottom right",
        "text": "コメント大歓迎♪ いっぱいお話し しようねっ♡"
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="YouTube Thumbnail - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14242)**

---

### No. 64: YouTube Thumbnail - Pastel Pink VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a cute, pastel-themed stream overlay or thumbnail featuring an anime girl and customizable text banners.

#### 📝 Prompt

```
{
  "type": "VTuber stream thumbnail",
  "theme": "pastel pink, soft, cute, lace, ribbons, hearts, bunny motif",
  "character": {
    "position": "right side, waist-up",
    "appearance": "anime girl, {argument name=\"hair color\" default=\"pastel pink\"} long wavy hair, large grey eyes, blush, pink heart earrings",
    "accessories": "white bunny ears, large pink bow on head",
    "outfit": "white frilly dress with lace, large pink ribbon bow at collar with heart gem"
  },
  "layout": {
    "background": "soft pink with subtle sparkles, lace patterns, floating hearts",
    "text_elements": [
      {
        "type": "main title",
        "position": "top left",
        "style": "large stylized pink text with white outline",
        "text": "{argument name=\"main title\" default=\"雑談配信\"}"
      },
      {
        "type": "speech bubble",
        "position": "above main title",
        "text": "まったり"
      },
      {
        "type": "circular badge",
        "position": "top right",
        "details": "lace-edged with small pink bow",
        "text": "きてくれてありがとう♡"
      },
      {
        "type": "heart badge",
        "position": "bottom right",
        "details": "large lace-edged heart",
        "text": "みんなとおしゃべりできるの楽しみにしてるね♡"
      }
    ],
    "list_section": {
      "position": "bottom left",
      "count": 3,
      "style": "horizontal pill-shaped banners with lace edges, each featuring a pink heart with white bunny ears and a tiny bow on the left",
      "items": [
        "{argument name=\"list item 1\" default=\"初見さん〇\"}",
        "{argument name=\"list item 2\" default=\"ポイント回収〇\"}",
        "{argument name=\"list item 3\" default=\"ROM〇\"}"
      ]
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="YouTube Thumbnail - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14238)**

---

### No. 65: YouTube Thumbnail - Anime VTuber Livestream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a pastel-themed anime VTuber stream thumbnail with customizable text badges and title.

#### 📝 Prompt

```
{
  "type": "anime-style livestream thumbnail",
  "character": {
    "hair": "{argument name=\"hair color\" default=\"short silver hair with cyan underlights\"}",
    "eyes": "large bright blue",
    "outfit": "white collared shirt, black tie with silver accents, black jacket, black beret with a large blue heart jewel, blue jewel brooch, black choker",
    "pose": "smiling gently, looking at viewer, positioned on the right side"
  },
  "background": "pastel blue with white clouds, sparkles, stars, small bows, and a subtle grid pattern",
  "typography_and_ui": {
    "top_left_speech_bubble": "まったりおしゃべりしよ〜♡",
    "main_title": {
      "text": "{argument name=\"main title\" default=\"雑談配信\"}",
      "style": "large, soft blue gradient, white outline, decorated with small hearts, positioned on the middle-left"
    },
    "bottom_left_badges": {
      "count": 3,
      "style": "white pill-shaped buttons with a purple heart icon on the left",
      "labels": [
        "{argument name=\"badge 1 text\" default=\"初見さん〇\"}",
        "{argument name=\"badge 2 text\" default=\"ポイント回収〇\"}",
        "{argument name=\"badge 3 text\" default=\"ROM〇\"}"
      ]
    },
    "bottom_right_cloud_bubble": "気軽にコメントしてね♡"
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="YouTube Thumbnail - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14231)**

---

### No. 66: YouTube Thumbnail - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a vibrant, text-heavy anime-style thumbnail for a VTuber chat stream, featuring customizable banners and titles.

#### 📝 Prompt

```
{
  "type": "VTuber stream thumbnail",
  "character": {
    "hair": "long blonde twin tails with pink gradient ends",
    "eyes": "large pink anime eyes",
    "expression": "cheerful smile with a small fang, making a peace sign near the eye",
    "outfit": "black top with harness straps, black heart-ring choker, multiple ear piercings including a cross dangle, black nail polish"
  },
  "background": "vibrant neon pink and black leopard print with glowing yellow accents, sparkles, and floating hearts",
  "typography_and_layout": {
    "main_title": {
      "position": "top left",
      "style": "large, bold, 3D, pink and black with white outlines",
      "text": "{argument name=\"main title\" default=\"雑談配信\"}"
    },
    "top_right_text": {
      "style": "casual handwritten style with a heart",
      "text": "{argument name=\"top right text\" default=\"まったり話そ〜♡\"}"
    },
    "bottom_left_banners": {
      "count": 3,
      "style": "glowing pill-shaped banners with heart icons on the left",
      "colors": ["pink", "yellow", "purple"],
      "labels": [
        "{argument name=\"banner 1 text\" default=\"初見さん〇\"}",
        "{argument name=\"banner 2 text\" default=\"ポイント回収〇\"}",
        "{argument name=\"banner 3 text\" default=\"ROM〇\"}"
      ]
    },
    "bottom_right_text": {
      "style": "casual handwritten style with a heart, yellow text with pink outline",
      "text": "気軽にコメントしてねっ♡"
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="YouTube Thumbnail - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14227)**

---

### No. 67: YouTube Thumbnail - Japanese Webinar Thumbnail Generator

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt for creating professional Japanese webinar thumbnails in 16:9 format with clear typography and prominent copy.

#### 📝 Prompt

```
Create a high-quality Japanese {argument name="thumbnail type" default="webinar thumbnail"}. {argument name="aspect ratio" default="16:9 widescreen"}. There is a lot of text, but the main copy stands out clearly.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="YouTube Thumbnail - Japanese Webinar Thumbnail Generator - Image 1">
</div>

#### 📌 Details

- **Author:** [KAWAI](https://x.com/kawai_design)
- **Source:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **Published:** April 18, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=13978)**

---

### No. 68: YouTube Thumbnail - VTuber Debut Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a magical, typography-rich stream schedule or debut thumbnail for a VTuber.

#### 📝 Prompt

```
{
  "type": "VTuber debut stream thumbnail",
  "character": {
    "appearance": "anime girl, long dark purple hair, purple eyes, frilly white blouse, dark purple bow tie, large hair bow",
    "pose": "finger to lips, cute expression",
    "props": "condenser microphone with pop filter and purple ribbon on the right"
  },
  "background": "magical starry night, sparkles, glowing butterflies, purple and white color palette",
  "layout": {
    "typography": [
      {
        "position": "top left",
        "style": "large bold text with cursive English above",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "First Stream",
        "subtext_2": "Nice to meet you! I am Shisaki Lily!"
      },
      {
        "position": "middle left",
        "style": "decorative box",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "bottom left",
        "style": "logo style",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "top right",
        "style": "vertical text",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "bottom right",
        "style": "decorative pill shape",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ START ✦"
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="YouTube Thumbnail - VTuber Debut Stream Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [WTR](https://x.com/wtry1102)
- **Source:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **Published:** April 17, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13943)**

---

### No. 69: YouTube Thumbnail - Gold & Black Info-Product Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a flashy, text-heavy promotional banner or YouTube thumbnail featuring a confident subject and multiple structured text callouts.

#### 📝 Prompt

```
{
  "type": "promotional banner / YouTube thumbnail",
  "style": "high contrast, flashy, professional, {argument name=\"theme color\" default=\"gold and black\"} palette, glowing light rays, sparkling particles",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"confident young Asian man in a dark suit with arms crossed\"}",
    "pose": "looking upwards to the right",
    "props": "glowing open laptop in front of him"
  },
  "layout": {
    "background": "dark with radiant gold light bursts",
    "text_sections": {
      "top_left_badge": "[保存版]",
      "top_header": "{argument name=\"top text\" default=\"知識ゼロからでも今日から始められる！ AIで稼ぐ力を最短で手に入れる！\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"AI副業 完全攻略\"}",
        "style": "large, bold, 3D gold and white typography"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"初心者でも月10万\"}",
      "top_right_badge": {
        "style": "gold laurel wreath",
        "text": "2026年版 最新版"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "stacked gold-bordered boxes",
        "labels": ["最短で収益化", "具体例つき", "誰でも始めやすい"]
      },
      "middle_right_ribbon": {
        "style": "red ribbon banner",
        "text": "手順を徹底解説"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "2x3 grid of gold-bordered boxes",
        "labels": ["おすすめツール紹介", "収益化の流れがわかる", "失敗しない始め方", "作業時間を最小化", "テンプレ付き", "再現しやすい方法"]
      },
      "bottom_footer": "迷わず稼げる！AI副業の教科書",
      "bottom_right_badge": {
        "style": "gold laurel wreath",
        "text": "テンプレ付き"
      }
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="YouTube Thumbnail - Gold & Black Info-Product Thumbnail - Image 1">
</div>

#### 📌 Details

- **Author:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **Source:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **Published:** April 17, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13903)**

---

### No. 70: Comic / Storyboard - Warm 4-Panel Married Couple Manga

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a soft, romantic four-panel Japanese comic celebrating a married couple, ideal for social posts, commemorative illustrations, or relationship-themed manga art.

#### 📝 Prompt

```
{"type":"4-panel romantic manga illustration","style":"clean hand-drawn anime line art with a warm beige and light brown monochrome palette, soft cream background, simple shading, cozy and gentle atmosphere, social media post aesthetic","format":"square 2x2 comic layout with thin brown panel borders","headline":{"text":"{argument name=\"headline text\" default=\"夫婦の日\"}","position":"top center","decorations":{"count":2,"items":["small heart on the left","small heart on the right"]}},"panels":[{"panel":1,"count":2,"scene":"standing portrait of a young couple","composition":"the man stands behind the woman with one hand on her shoulder, both looking calm and affectionate","characters":[{"role":"man","appearance":"messy light brown hair, glasses, cream hoodie, tall and slim"},{"role":"woman","appearance":"light brown hair in a loose low bun with strands framing the face, white long-sleeve shirt, warm brown sweater vest, shoulder bag strap visible"}],"text":["今日は","夫婦の日！"],"decorations":{"count":3,"items":["small heart","small heart","small heart"]}},{"panel":2,"count":2,"scene":"the couple sitting together indoors holding mugs and smiling at each other","characters":[{"role":"man","appearance":"same glasses and hoodie, holding a muted green mug"},{"role":"woman","appearance":"same hairstyle and outfit, holding a light mug"}],"speech_bubble":{"speaker":"man","text":"いつもありがとう。 一緒にいられることが、 いちばんの幸せだよ。"},"decorations":{"count":4,"items":["small sparkle","small sparkle","small dot cluster","small dot cluster"]}},{"panel":3,"count":2,"scene":"the couple cooking together in a kitchen, both stirring a pan on the stove","background":"simple shelves and potted plant in soft sketchy detail","characters":[{"role":"man","appearance":"same glasses and hoodie"},{"role":"woman","appearance":"same bun hairstyle and layered outfit"}],"speech_bubble":{"speaker":"man","text":"これからも、 笑い合って、支え合って、 一緒にいろんな景色を 見ていこうね。"}},{"panel":4,"count":2,"scene":"close affectionate embrace, the man kisses the woman on the forehead while holding her shoulder","characters":[{"role":"man","appearance":"same glasses and hoodie"},{"role":"woman","appearance":"same hair and outfit, leaning into him"}],"speech_bubble":{"speaker":"man","text":"大好きだよ。 これからも、 よろしくね！"},"decorations":{"count":3,"items":["small heart","small heart","small heart"]}}],"footer":{"text":"{argument name=\"footer text\" default=\"いつもそばにいてくれて、ありがとう。\"}","position":"bottom center","decorations":{"count":1,"items":["small heart"]}},"character_design":{"count":2,"items":[{"role":"husband","hair color":"{argument name=\"hair color\" default=\"light brown\"}","expression":"kind, gentle, affectionate"},{"role":"wife","hair color":"{argument name=\"hair color\" default=\"light brown\"}","expression":"soft smile, loving, slightly shy"}]},"rendering_notes":"keep all text handwritten in Japanese, use lots of white space, preserve a sweet commemorative mood for a couple's appreciation post, make the linework slightly loose and sketchlike rather than polished ink"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="Comic / Storyboard - Warm 4-Panel Married Couple Manga - Image 1">
</div>

#### 📌 Details

- **Author:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Source:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14492)**

---

### No. 71: Comic / Storyboard - Japanese AI Manga Demo Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A polished four-panel anime manga page showing catgirl characters reacting to impressively rendered Japanese dialogue, ideal for showcasing AI comic text quality.

#### 📝 Prompt

```
{
  "type": "four-panel anime manga page",
  "style": "clean polished anime illustration, warm indoor lighting, highly legible vertical Japanese speech balloons, soft shading, expressive comic framing, detailed cozy living room background, light brown and beige interior, wood floor, sofa, coffee table, mugs, small plant, framed wall art",
  "format": {
    "page_orientation": "portrait",
    "panel_count": 4,
    "reading_flow": "top-left, top-right, middle-wide, bottom-wide",
    "borders": "thick black manga panel borders"
  },
  "characters": [
    {
      "id": "blue cat girl",
      "appearance": "small chibi catgirl with short bobbed {argument name="hair color" default="blue"} hair, ahoge, cat ears with white inner fur, fluffy tail with white tip, large amber-blue eyes, tiny fang-like mouth",
      "outfit": "orange sweater over a white collared shirt with blue trim, brown skirt with a ribbon belt, yellow X-shaped hair clip"
    },
    {
      "id": "golden cat girl",
      "appearance": "energetic catgirl with long wavy golden-blonde hair, cat ears, fluffy tail, bright cheerful expression",
      "outfit": "mustard yellow cable-knit sweater, dark brown plaid skirt"
    },
    {
      "id": "white-haired woman",
      "appearance": "beautiful woman with long white hair, white cat ears, dark tan skin, golden eyes, calm confident smile",
      "outfit": "white jacket over a black top, layered gold necklaces and earrings"
    },
    {
      "id": "maid woman",
      "appearance": "adult woman with long light blonde hair and cat ears",
      "outfit": "black-and-white maid dress with white frilled headpiece and a red ribbon bow"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "panel 1",
        "position": "top-left",
        "count": 1,
        "labels": ["どうせ日本語微妙なんでしょ？文字がダメなら認めないよ"],
        "scene": "the blue cat girl sits on a sofa in a cozy living room, one finger on her chin, looking skeptical and curious, a small question mark floating above her head"
      },
      {
        "title": "panel 2",
        "position": "top-right",
        "count": 1,
        "labels": ["ねぇねぇ！GPT Image2 すごいよ！"],
        "scene": "the golden cat girl bursts in dramatically through a doorway with speed lines radiating behind her, arms spread wide, full of excitement"
      },
      {
        "title": "panel 3",
        "position": "middle-wide",
        "count": 3,
        "labels": ["うわっ びっくりした！めちゃくちゃキレイじゃん！", "ねぇねぇ！GPT Image2 すごいよ！ 微妙なんでしょ？ 文字がダメなら認めないよ", "ほら見て！わたしたちのセリフ！"],
        "scene": "the blue cat girl reacts in shock with both hands near her face, the golden cat girl stands beside her and points proudly, and a large central speech balloon displays the example Japanese dialogue they are discussing"
      },
      {
        "title": "panel 4",
        "position": "bottom-wide",
        "count": 3,
        "labels": ["進化が早すぎてもう驚かないよね〜", "絵も可愛く描けてるし文字の白抜きも完璧よね", ""],
        "scene": "in the foreground, the maid woman covers her mouth in impressed amazement while the white-haired woman comments thoughtfully with a hand near her chin; in the background, the blue cat girl and golden cat girl jump happily together in celebration in front of the sofa"
      }
    ]
  },
  "text_handling": {
    "language": "Japanese",
    "balloon_direction": "vertical text layout",
    "emphasis": "make the Japanese typography crisp, natural, and cleanly integrated into manga speech balloons, including white knockout text where needed"
  },
  "tone": "playful, celebratory, impressed by high-quality Japanese text rendering in AI-generated manga",
  "quality": "high detail, cohesive character designs, cute and readable promotional comic"
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="Comic / Storyboard - Japanese AI Manga Demo Page - Image 1">
</div>

#### 📌 Details

- **Author:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **Source:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14471)**

---

### No. 72: Comic / Storyboard - Elegant Anime Swordswoman 4-Panel Sheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a high-detail four-panel anime character illustration of a noble white-haired swordswoman, ideal for fantasy key art, character showcases, or premium social media posts.

#### 📝 Prompt

```
A polished anime fantasy illustration sheet in a 2x2 grid showing the same elegant swordswoman in 4 panels. The character is a young woman with very long platinum-white hair tied in a high ponytail with large deep navy ribbon bows, soft loose curls and flowing strands, pale skin, and delicate refined features with luminous red-pink eyes. She wears an ornate white-and-navy gothic aristocratic dress: a white high-collar ruffled blouse with lace trim and gold embroidery, a large navy bow at the chest set with a red jewel brooch, puff sleeves with ribbon cuffs, a dark navy corset waist with gold details, and a voluminous navy skirt decorated with gold floral patterns, layered ruffles, and satin sheen. She carries a sheathed katana with a dark hilt and gold accents. Panel 1 is a close-up bust portrait from the chest up, turned slightly sideways, hair glowing in dramatic rim light against a dark sparkling night background. Panel 2 is a dynamic upper-body action shot, the character drawing or presenting the sword horizontally toward the viewer, hair streaming wildly, cinematic city-night bokeh and glowing petals around her. Panel 3 is a full-body fashion portrait, standing gracefully in a luminous reflective hall framed by tall glowing structures, showing the entire dress silhouette, heeled shoes with bows, and the sword at her side. Panel 4 is a three-quarter back view by a shimmering ocean at sunset or dawn, the character looking back over her shoulder, warm pastel sky and glittering water behind her, cherry blossom petals drifting in the breeze. Use ultra-detailed anime rendering, premium light novel cover quality, intricate fabric textures, glossy highlights, gold ornamentation, soft bloom, dramatic backlighting, floating petals, sparkling particles, elegant romantic atmosphere, and cohesive navy, white, gold, blush pink color harmony.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="Comic / Storyboard - Elegant Anime Swordswoman 4-Panel Sheet - Image 1">
</div>

#### 📌 Details

- **Author:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **Source:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14413)**

---

### No. 73: Comic / Storyboard - Countryball Strait of Hormuz Standoff

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A humorous geopolitical meme illustration showing USA and Iran countryballs confronting each other in the narrow Strait of Hormuz, ideal for editorial satire or social media commentary.

#### 📝 Prompt

```
A detailed satirical countryball meme illustration of the {argument name="waterway name" default="Strait of Hormuz"} as a very narrow sea passage between two steep rocky cliffs, painted in a polished digital cartoon style with dramatic shading and textured stone. In the center foreground, exactly 2 countryballs block each other in the tight channel so that only one can pass. On the left is a USA countryball with angry narrowed eyes, painted with the American flag, wearing a dark navy baseball cap labeled "USA" in large white letters. On the right is an Iran countryball with angry narrowed eyes, painted with the Iranian flag and emblem, wearing a green-and-white headband tied on the side; the headband contains Korean text that reads "저항은 우리의 권리". Above each ball is exactly 1 white speech bubble with thick black outline, for a total of 2 speech bubbles, and both say {argument name="speech text" default="길!"} in large bold Korean lettering, as if neither side will yield. Show the two balls facing each other nose-to-nose in a standoff in the bottleneck. On the left cliff, include exactly 1 wooden sign reading in Korean and English: "호르무즈 해협" and "Strait of Hormuz". On the right cliff, include exactly 1 warning sign with Persian text at the top and a red warning triangle below, indicating that only one person can pass. In the left bottom corner, place exactly 1 black oil barrel labeled "OIL" with dark spilled oil pooling around it. In the right bottom corner, place exactly 1 black naval mine with Persian writing on it, attached to a chain. In the background beyond the narrow passage, show open sea with exactly 3 distant ships, including at least 1 larger tanker and faint dark smoke rising into the sky. Use a tense but humorous geopolitical meme tone, centered composition, eye-level view, soft daylight, slightly muted realistic colors, crisp outlines, and high readability for all text.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="Comic / Storyboard - Countryball Strait of Hormuz Standoff - Image 1">
</div>

#### 📌 Details

- **Author:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Source:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14683)**

---

### No. 74: Comic / Storyboard - Blindfolded Sorcerer Victory Pose

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a dramatic vertical anime action poster of a blindfolded white-haired sorcerer with explosive blue energy and a bold manga speech bubble, ideal for stylized character art or fandom-inspired visuals.

#### 📝 Prompt

```
A high-impact shonen manga anime illustration of a powerful white-haired sorcerer in a dramatic low-angle full-body pose, laughing with his head thrown back and mouth wide open, wearing a sleek black high-collar uniform and a black blindfold over his eyes. His left hand is thrust toward the viewer making a two-finger peace sign, with strong foreshortening that makes the hand large in the foreground, while his right arm hangs lower at his side. Surround him with explosive {argument name="energy color" default="electric blue"} supernatural energy, violent brushstroke-like aura trails, flying debris, sparks, and swirling curved streaks cutting across the frame. The background should be a dark, abstract, chaotic energy burst with glowing blue shards and motion lines, creating a sense of overwhelming power. Use bold cel-shaded anime rendering with painterly highlights, sharp linework, intense contrast, and glossy fabric folds on the black outfit. On the right side, add 1 large jagged white manga speech bubble with thick black outline containing the text {argument name="speech bubble text" default="LUDDITES ALWAYS LOSE!"} in huge distressed black uppercase letters. Vertical composition, dynamic action poster framing, confident triumphant attitude, modern dark fantasy anime aesthetic.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="Comic / Storyboard - Blindfolded Sorcerer Victory Pose - Image 1">
</div>

#### 📌 Details

- **Author:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Source:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14637)**

---

### No. 75: Comic / Storyboard - Lunar Bathhouse Comedy Manga Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A retro-futuristic anime comic page depicting a whimsical sento on the moon, ideal for generating playful AI manga scenes with multiple character-driven panels.

#### 📝 Prompt

```
A colorful single-page Japanese comic manga set in a whimsical lunar public bathhouse on the moon, drawn in a polished retro-futuristic anime style with warm lighting, thick clean panel borders, expressive sound effects, and highly detailed environmental storytelling. The scene is a moon onsen called "月面銭湯 つきのゆ" with a large illuminated entrance sign, blue noren curtain with the white character "ゆ", exposed pipes, gauges, rounded architecture, and a giant circular window showing the moon surface and Earth in space. Include exactly 8 comic panels arranged in a dynamic page layout. Panel 1: exterior establishing shot of the bathhouse on the moon, with the sign "月面銭湯 つきのゆ", a smaller sign reading "重力 1/6", a red milk vending machine labeled "牛乳", a tanuki statue, lunar terrain outside, and a vertical banner promoting the bath. Panel 2: a young female mechanic bathhouse worker with {argument name="character design" default="brown ponytail tied with a red polka-dot bandana, green work jumpsuit, tool belt, energetic expression"} adjusts a machine or boiler control, seen from behind or side, with speech balloons about preparing today's bath and boiler condition. Panel 3: a cute alien customer with {argument name="alien appearance" default="round mint-green body, purple spots, sleepy eyes, pink cheeks, small mouth, white towel with a purple star on its head"} relaxes in steaming bathwater, half submerged, with a rubber duck floating nearby and a wooden sign reading "ぬるめ じっくり リラックス". Panel 4: a small cleaning robot with {argument name="robot design" default="silver body, blue accents, black digital face with glowing blue eyes, red antenna light, thin mechanical arms and legs"} happily scrubs the floor with broom and bucket beside a hanging sign that says "清掃中". Panel 5: the same robot suddenly slips or splashes dramatically into the bath, with a huge water burst, many bubbles, the large sound effect "ぽわぁ〜ん!!", and the worker reacting in surprise from the side. Panel 6: the worker sits by the bath smiling, holding a bottle labeled "月面牛乳". Panel 7: the alien in the bath gives a thumbs-up while holding a bottle labeled "月面フルーツオーレ", looking blissfully satisfied, with the rubber duck still present. Panel 8: the cheerful robot poses beside the bath with cleaning tools and a bucket, near a bath curtain marked "ゆ" and a pink wash basin labeled "つきのゆ", saying the bath is the best. Maintain a cozy, comedic tone, retro Showa-style sento details mixed with space technology, glossy tiled bath surfaces, steam, bubbles, and cute character acting throughout. The comic should feel like a charming slice-of-life gag manga about working at a lunar bathhouse.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="Comic / Storyboard - Lunar Bathhouse Comedy Manga Page - Image 1">
</div>

#### 📌 Details

- **Author:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **Source:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14697)**

---

### No. 76: Comic / Storyboard - Character Design Reference Sheet

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a comprehensive design sheet for a specific character, including key information and visual references.

#### 📝 Prompt

```
Create a character design sheet for {argument name="character" default="Hermes Agent"}, with key info
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="Comic / Storyboard - Character Design Reference Sheet - Image 1">
</div>

#### 📌 Details

- **Author:** [Neo](https://x.com/NeoAIForecast)
- **Source:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14324)**

---

### No. 77: Comic / Storyboard - Indie Comic Book Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Creates a comic book layout in a modern indie style tailored for children's stories.

#### 📝 Prompt

```
A page of a comic book in the style of {argument name="comic style" default="modern indie comic"} topic: {argument name="story topic" default="a story for 6 years kids"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="Comic / Storyboard - Indie Comic Book Page - Image 1">
</div>

#### 📌 Details

- **Author:** [宝玉](https://x.com/dotey)
- **Source:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14310)**

---

### No. 78: Comic / Storyboard - Colorized Shonen Manga Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A detailed narrative prompt for generating a physical-looking manga page with specific character and brand details.

#### 📝 Prompt

```
Make a sample page of a {argument name="manga type" default="colorized Japanese shonen adventure manga"}. The page should vividly depict our main character found a {argument name="item" default="magical quill"}. The name of the quill is called the {argument name="item name" default="Quill of GPT Image"}. Make it dramatic. The magical quill has strong power sealed inside it.

Additional instructions: Aspect ratio: Portrait 1440x2560. The pen should have an OpenAI logo on it. The language throughout the manga should be Japanese. Think carefully first to make this a good story with good split of manga panels. The page should appear as a photo of a physical page, not a digital page.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="Comic / Storyboard - Colorized Shonen Manga Page - Image 1">
</div>

#### 📌 Details

- **Author:** [宝玉](https://x.com/dotey)
- **Source:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14311)**

---

### No. 79: Comic / Storyboard - Four-Panel Romantic Comedy Manga Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a monochrome four-panel manga page with Japanese dialogue, ideal for creating dramatic romantic-comedy debate scenes with expressive character acting.

#### 📝 Prompt

```
Create a black-and-white manga page with 4 stacked horizontal panels, clean black gutters, screentone shading, dramatic speed lines, and polished seinen-style linework. The page features two youthful anime characters with modern casual clothing and short dark hair, with the face area of both characters obscured by a soft square blur censor block. Panel 1: a slim young person with messy short dark hair and a collared shirt clenches one fist near their chest, body angled left, surrounded by an intense fiery aura effect in the background, looking emotional and defensive. On the right side, place a large jagged vertical speech balloon containing this Japanese text: 「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」. Panel 2: a second young person with slightly taller build, short dark hair, a dark zip jacket over a light shirt, raises one index finger calmly as if explaining a point. Add a rounded rectangular speech box on the right with this Japanese text: 「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」. Panel 3: the taller character gently pats the shorter character on the head; include a small hand-pat sound effect near the hand reading 「ポン」. The shorter character looks up in surprise. On the right side, add a large oval vertical speech balloon with this Japanese text: 「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」. Panel 4: close-up of the shorter character blushing intensely with spiral eyes, sweat drops, trembling expression, open mouth, and dense hatching on the cheeks, overwhelmed with embarrassment. Fill the background with dramatic radiating speed lines. Add a large jagged vertical speech balloon on the right with this Japanese text: 「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」. Add two sound effects: a small 「プル…」 near the shoulder and a larger shaky handwritten 「カァァァ」 along the lower left side. Keep the whole page monochrome, highly expressive, romantic-comedy manga tone, with strong emotional contrast between heated argument, cool explanation, teasing affection, and flustered payoff.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="Comic / Storyboard - Four-Panel Romantic Comedy Manga Page - Image 1">
</div>

#### 📌 Details

- **Author:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Source:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14468)**

---

### No. 80: Comic / Storyboard - Velvedia Character Reference Sheet

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A short prompt for generating a character reference sheet for a mecha-style character named Velvedia.

#### 📝 Prompt

```
{argument name="character name" default="Velvedia"} reference sheet
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="Comic / Storyboard - Velvedia Character Reference Sheet - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="Comic / Storyboard - Velvedia Character Reference Sheet - Image 2">
</div>

#### 📌 Details

- **Author:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **Source:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **Published:** April 21, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=14368)**

---

### No. 81: Comic / Storyboard - 8-Panel GPT-Image-2 Manga Promo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a Portuguese black-and-white manga-style eight-panel comic page for announcing and explaining GPT-Image-2 in a social-media-friendly promotional format.

#### 📝 Prompt

```
{"type":"8-panel manga-style promotional comic page","theme":"launch announcement for GPT-Image-2","language":"Portuguese","style":{"rendering":"black-and-white manga with screentone shading, speed lines, glossy highlights, bold inked outlines, clean digital comic finish","mood":"exciting, informative, optimistic, tech-forward","page_format":"single page divided into 8 rectangular panels in a 2-column by 4-row grid with thin gutters"},"characters":[{"id":"host girl","role":"main presenter","appearance":"cute anime girl with long dark hair, large expressive eyes, wearing a dark hoodie with the OpenAI knot logo on the chest","count":1},{"id":"robot mascot","role":"friendly assistant mascot","appearance":"small round robot with black face screen, glowing eyes, simple white body, tiny arms, cheerful expression","count":1},{"id":"creator group","role":"audience examples","appearance":"4 different young creators: one designer, one developer holding a tablet, one photographer with camera, one person with laptop/hoodie","count":4}],"layout":{"sections":[{"title":"CHEGOU! GPT-IMAGE-2","position":"top-left","count":1,"description":"dramatic hero introduction panel with the anime girl reaching one hand toward the viewer, radiant speed lines behind her","text":["CHEGOU!","GPT-IMAGE-2","A NOVA GERAÇÃO DE IMAGENS POR IA DA OPENAI!","MAIS CRIATIVIDADE, MAIS PRECISÃO, MAIS POSSIBILIDADES!"]},{"title":"O QUE É O GPT-IMAGE-2?","position":"top-right","count":1,"description":"girl in half-body pose pointing upward beside a glowing image icon on a starry tech background","text":["O QUE É O GPT-IMAGE-2?","É nosso novo modelo de geração de imagens, mais inteligente, mais fiel ao que você imagina e com qualidade surpreendente!"]},{"title":"MAIS REALISMO. MAIS DETALHES.","position":"middle-left row 2","count":1,"description":"comparison panel showing 2 landscape images side by side, both mountain lake scenes, left labeled older model and right labeled newer model with richer realism","subsections":[{"label":"ANTES (DALL·E 3)","count":1},{"label":"AGORA (GPT-IMAGE-2)","count":1}],"text":["MAIS REALISMO. MAIS DETALHES.","ANTES (DALL·E 3)","AGORA (GPT-IMAGE-2)","TEXTURAS MAIS RICAS, LUZ MAIS NATURAL, DETALHES INCRÍVEIS!"]},{"title":"COMPREENSÃO MELHOR, RESULTADOS MELHORES.","position":"middle-right row 2","count":1,"description":"girl clasping hands beside a framed prompt example and the robot mascot pointing upward","text":["COMPREENSÃO MELHOR, RESULTADOS MELHORES.","O GPT-IMAGE-2 entende melhor objetos, textos, composições e instruções complexas!","EXEMPLO DE PROMPT:","\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\""]},{"title":"CRIATIVIDADE SEM LIMITES.","position":"lower-left row 3","count":1,"description":"girl speaking beside a 2x2 showcase of 4 generated art variants","subsections":[{"label":"gothic castle scene","count":1},{"label":"modern city street at night","count":1},{"label":"anime character portrait","count":1},{"label":"abstract geometric composition","count":1}],"text":["CRIATIVIDADE SEM LIMITES.","De estilos artísticos a layouts profissionais, do realista ao abstrato: suas ideias, do seu jeito!"]},{"title":"TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","position":"lower-right row 3","count":1,"description":"robot mascot presenting a before-and-after comparison of poster typography with a bold arrow between the two designs","subsections":[{"label":"ANTES","count":1},{"label":"AGORA","count":1}],"text":["TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","Geração de texto mais precisa, legível e integrada ao design!","ANTES","AGORA","AVENTURA COMEÇA AQUI","A AVENTURA COMEÇA AQUI"]},{"title":"PARA TODOS OS CRIADORES.","position":"bottom-left","count":1,"description":"group shot with the host girl and 4 creators standing side by side, representing different professions","text":["PARA TODOS OS CRIADORES.","Designers, desenvolvedores, educadores, marketers, artistas e curiosos: todo mundo pode criar mais e melhor!"]},{"title":"GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","position":"bottom-right","count":1,"description":"closing hero panel with the girl winking and giving a thumbs-up, robot mascot beside her, bright celebratory rays and sparkles","text":["GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","IMAGINE. CRIE. INSPIRE.","O FUTURO DA CRIAÇÃO É AGORA. ❤"]}],"panel_count":8},"composition":{"reading_order":"left to right, top to bottom","camera_variety":"mix of close-up hero shots, medium presenter shots, comparison graphics, and group shot","graphic_elements":["speech bubbles","rounded black title banners with white uppercase lettering","sparkles","speed lines","starry tech background","comparison arrows","framed example cards"]},"text_style":"all caps comic lettering in Portuguese, bold display headers, clear speech bubbles, promotional infographic-comic hybrid","quality":"high-resolution editorial comic poster, crisp typography, balanced panel spacing, strong contrast","prompt":"Create a grayscale manga-style 8-panel promotional comic page announcing {argument name=\"product name\" default=\"GPT-IMAGE-2\"}. Use a single-page 2-column by 4-row layout with exactly 8 distinct panels and Portuguese text throughout. Feature a cheerful anime presenter girl with {argument name=\"hair color\" default=\"dark brown\"} long hair, a dark hoodie with the OpenAI logo, and a friendly small robot mascot. Panel 1: dramatic launch reveal, girl reaching toward camera, radial speed lines, headline \"CHEGOU! {argument name=\"headline name\" default=\"GPT-IMAGE-2\"}\" and launch copy about a new generation of AI images. Panel 2: explanatory panel with girl pointing beside a glowing image icon on a starry digital background, title \"O QUE É O GPT-IMAGE-2?\" and a speech bubble describing it as a smarter image generation model. Panel 3: realism comparison with exactly 2 side-by-side mountain lake landscapes labeled \"ANTES (DALL·E 3)\" and \"AGORA (GPT-IMAGE-2)\". Panel 4: better understanding panel with girl and robot, include a framed prompt example using {argument name=\"example prompt\" default=\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\"}. Panel 5: creativity showcase with exactly 4 thumbnails: gothic castle, city at night, anime portrait, abstract geometric art. Panel 6: text rendering comparison with exactly 2 poster variants labeled \"ANTES\" and \"AGORA\", showing improved typography and the phrase \"AVENTURA COMEÇA AQUI\" versus a cleaner corrected version. Panel 7: audience panel with exactly 4 creators from different fields standing together. Panel 8: final celebratory call-to-action with the girl winking and giving thumbs-up, robot mascot cheering, and the closing slogan {argument name=\"closing slogan\" default=\"IMAGINE. CRIE. INSPIRE.\"}. Make the page energetic, polished, highly legible, with bold black header bars, white uppercase lettering, speech bubbles, sparkles, screentone shading, and strong manga/comic promotional poster aesthetics."}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="Comic / Storyboard - 8-Panel GPT-Image-2 Manga Promo - Image 1">
</div>

#### 📌 Details

- **Author:** [Diogo Santos](https://x.com/diogosantosbr)
- **Source:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14639)**

---

### No. 82: Comic / Storyboard - Censored Office Manga Confrontation

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

A gritty monochrome manga page showing a heated office argument that shifts into a kabedon scene, useful for recreating dramatic viral manga-style screenshots.

#### 📝 Prompt

```
A dramatic black-and-white manga page in a seinen style, rendered with dense screentones, sharp ink lines, high contrast lighting, and expressive Japanese comic layout. The page has 4 stacked panels with vertical Japanese speech bubbles and bold sound effects, showing a tense confrontation between two office workers in a modern workspace. In the top panel, a young woman with a short messy bob haircut, slim but curvy build, wearing a fitted button-up blouse with rolled sleeves and a dark pencil skirt, slams one hand hard onto a desk in anger, leaning forward toward the viewer with explosive impact lines and a large jagged speech bubble. In the second panel, a young man with dark tousled hair, slim build, wearing a black leather jacket over a light shirt and a necklace, is shown from the chest up in a calm, confident pose, touching his face while speaking. In the third panel, the man pins the woman against a wall in a close, intimate kabedon pose, one arm braced beside her head; she looks flustered and tense while he speaks near her face, creating a sudden romantic-comedic shift in mood. In the bottom panel, an overhead view reveals the office setting: 2 characters standing near a desk with 1 computer monitor, 1 keyboard, 1 mouse, 1 office chair, and scattered papers on a tiled floor; the woman is curled inward shyly and trembling while the man stands relaxed beside her. Include exactly 4 panels, exactly 4 visible speech bubbles total, and visible Japanese manga typography throughout. Add a rectangular mosaic censor blur over each character's face in every panel, as if anonymized for sharing online. Background details should include office walls, desk edges, speed lines, burst effects, and tonal gradients. The overall feeling is intense argument turning into manipulative flirtation, like a viral out-of-context manga screenshot.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="Comic / Storyboard - Censored Office Manga Confrontation - Image 1">
</div>

#### 📌 Details

- **Author:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Source:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14477)**

---

### No. 83: Comic / Storyboard - Quantum Cat Manga

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A short, creative prompt for generating a manga panel featuring a cat exhibiting quantum physics behaviors.

#### 📝 Prompt

```
Please draw a manga where a {argument name="subject" default="cat"} {argument name="concept" default="behaves like a quantum particle"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="Comic / Storyboard - Quantum Cat Manga - Image 1">
</div>

#### 📌 Details

- **Author:** [Haruhiko Okumura](https://x.com/h_okumura)
- **Source:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **Published:** April 21, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=14348)**

---

### No. 84: Comic / Storyboard - Cute Sheep Girl Office Manga Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A four-panel pastel fantasy office manga page showing a sheep-horned clerk and a fluffy sheep turning paperwork into a sleepy, cozy gag scene.

#### 📝 Prompt

```
{"type":"four-panel manga page","style":"soft pastel anime chibi, warm beige and cream palette, gentle morning light, rounded panel borders, clean readable Japanese dialogue, cozy comedic fantasy office slice-of-life","page":{"orientation":"vertical","panel_count":4,"gutter":"thin white spacing","border":"rounded brown outlines"},"setting":{"location":"small management office interior","details":["wooden floor","sunlit window","desk with papers","wooden chairs","bookshelves full of files and books","stacked boxes and office supplies","soft dust motes and sparkles in the light"]},"characters":[{"role":"main character","appearance":"tiny chibi sheep girl clerk with short fluffy blond bob hair, one blue eye and one amber eye, small elf-like ears, large curled ram horns, fluffy sheep hood shaped like a sheep face, white blouse, red necktie, pale pink apron dress, small pen in apron pocket"},{"role":"secondary character","appearance":"round fluffy white sheep with tiny face and short legs, very plush and cloud-like"}],"layout":{"sections":[{"title":"panel 1","position":"top","count":3,"labels":["sheep girl opening the office door and looking inside","small sheep peeking beside her","one oval speech bubble on the left and one small oval bubble on the right"]},{"title":"panel 2","position":"upper middle","count":3,"labels":["sheep girl standing by a desk with one hand on hip and one hand pointing to documents","small sheep sitting by the desk","single large oval speech bubble on the left"]},{"title":"panel 3","position":"lower middle","count":3,"labels":["sleeping fluffy sheep sprawled on top of paperwork","partial close-up of the sheep girl peeking in from the upper left with a tired expression","purple sleeping sound effect text on the right"]},{"title":"panel 4","position":"bottom","count":4,"labels":["sheep girl asleep at the desk with closed eyes and a faint smile","fluffy sheep sleeping beside her on the paperwork","warm sunlight streaming from the left window","small rectangular caption box at bottom right"]}]},"text":{"language":"Japanese","elements":[{"kind":"speech bubble","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"speech bubble","panel":1,"text":"メェ"},{"kind":"speech bubble","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"speech bubble","panel":3,"text":"…名簿が もふもふに…"},{"kind":"sound effect","panel":3,"text":"Zzz…"},{"kind":"speech bubble","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"caption","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"keep all four panels in the same office for continuity; emphasize cute facial expressions, fluffy textures, and the joke that office work stops because the sheep and clerk fall asleep together on the paperwork; make the documents clearly visible in panels 2 through 4; preserve a calm, sleepy, heartwarming tone"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="Comic / Storyboard - Cute Sheep Girl Office Manga Page - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="Comic / Storyboard - Cute Sheep Girl Office Manga Page - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="Comic / Storyboard - Cute Sheep Girl Office Manga Page - Image 3">
</div>

#### 📌 Details

- **Author:** [じょにがたロボ](https://x.com/jonigata_ai)
- **Source:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14532)**

---

### No. 85: Comic / Storyboard - Cute Four-Panel Cat Jealousy Comic

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt generates a warm, hand-drawn four-panel cat comic ideal for social posts, manga-style humor, or cozy pet illustrations.

#### 📝 Prompt

```
A cute hand-drawn four-panel comic in a soft, warm, slice-of-life style on a light cream background with thick black panel borders and slightly textured paper grain. Use simple rounded cartoon cat anatomy, expressive faces, clean black outlines, muted natural colors, and a gentle manga-like presentation. In the top-left panel, show 2 cats: a brown tabby cat with dark stripes and white muzzle sitting with eyes closed, looking pleased, while a mostly white cat with dark brown patches on the head stands beside it and affectionately licks the tabby's cheek; add 2 small black musical notes above them to suggest happy grooming. In the top-right panel, show the white-and-brown patched cat in the foreground looking toward a small calico kitten standing to the right; include a speech bubble containing the Japanese text "めい" above the kitten. In the bottom-left panel, show 3 cats together: the brown tabby on the left with a surprised or blank expression, the white patched cat on the right looking cheerful, and the small calico kitten centered in front between them, looking up. In the bottom-right panel, show a close-up of the brown tabby cat alone, facing forward with narrowed yellow-green eyes and an angry, jealous expression; add 2 short emphasis lines near the face and 1 small puff-shaped anger symbol to the right. Keep the tone cozy and comedic, with the visual joke that the tabby was happy being groomed until the new kitten appears. Use flat colors, minimal shading, and a charming Japanese webcomic feel.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="Comic / Storyboard - Cute Four-Panel Cat Jealousy Comic - Image 1">
</div>

#### 📌 Details

- **Author:** [Maoku](https://x.com/Maoku)
- **Source:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14503)**

---

### No. 86: Comic / Storyboard - Moon Mark Adventure Comic Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A four-panel fantasy anime comic page showing a silver-haired moon-themed girl discovering a map, solving a cave puzzle, and finding a magical invitation to the next adventure.

#### 📝 Prompt

```
{"type":"four-panel anime comic page","style":"cute fantasy manga illustration, polished gpt-image-2 anime rendering, vibrant colors, clean linework, soft painterly shading, whimsical magical atmosphere","page":{"background":"white page with black panel borders","title":"{argument name=\"headline text\" default=\"月のしるしの大冒険\"}","title_position":"top center","decorations":["small gold sparkles around title","crescent moon icon to the right of title"],"panel_count":4,"reading_direction":"top to bottom"},"character":{"appearance":"young anime girl adventurer with very long wavy silver hair, pale skin, large expressive eyes, slim build","outfit":["black-and-white fantasy dress with frilled trim","crescent moon hair ornament","crescent moon choker","off-shoulder sleeves","brown leather backpack","dark thigh-high stockings"],"theme":"moon motif throughout costume and props"},"panels":[{"position":"top","scene":"sunny mountain trail and meadow under a blue sky with clouds, forest on the right, winding path into the distance, wooden signpost on the left","action":"the girl stands holding and reading an old treasure map, facing forward","props":["aged map","wooden signpost","backpack"],"text":{"sign":"冒険のはじまり","speech":"{argument name=\"panel 1 speech\" default=\"地図を発見！今日は大冒険だ！\"}"}},{"position":"upper-middle","scene":"lush jungle-like ruins entrance with a dark cave opening framed by old stone pillars carved with crescent symbols and covered in vines","action":"rear three-quarter view of the girl approaching carefully while reading the map","props":["map","ruined cave entrance","dense plants"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"この先にお宝があるはず…！\"}","sound_effect":"ガサガサ"}},{"position":"lower-middle","scene":"inside the cave ruins, dimly lit, stone altar or puzzle table in the center","action":"the girl kneels beside a lit lantern and reaches toward a puzzle mechanism instead of a nearby keyhole, while a round black cat-like mascot watches","props":["lantern emitting warm light","stone puzzle slab with engraved circular symbol","small golden key on the table","black cat creature with crescent moon mark and bead collar"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"カギじゃなくて、仕掛けを解けばいいんだ！\"}","sound_effect":"ピカッ"}},{"position":"bottom","scene":"treasure chamber with crystals embedded in the cave walls and floating sparkles","action":"the girl smiles brightly with eyes closed beside an opened treasure chest, holding up a paper invitation card","props":["open wooden treasure chest with crescent moon emblem","glowing compass inside the chest","paper card reading つぎの冒険へ","blue and purple crystals"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"宝物は…次の冒険への招待状！\"}","tag":"つづく？"}}]}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="Comic / Storyboard - Moon Mark Adventure Comic Page - Image 1">
</div>

#### 📌 Details

- **Author:** [ツバサ天九](https://x.com/wing_sky_nine)
- **Source:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14605)**

---

### No. 87: Product Marketing - Anime Character Brand Identity & Merch Board

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a comprehensive brand design board featuring an anime character, including product packaging, social media mockups, and merchandise layouts.

#### 📝 Prompt

```
{
  "type": "brand identity and merchandise design board",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"pastel pink\"} and white",
    "motif": "{argument name=\"motif\" default=\"cherry blossoms\"} and pink hearts"
  },
  "character": {
    "description": "anime girl with short brown bob hair, pink eyes, wearing a white hoodie, gentle smile"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "header banner",
        "position": "top",
        "elements": ["large main logo", "sub logo", "cherry blossom graphics", "character portrait on the right"]
      },
      {
        "type": "product packaging",
        "position": "middle left",
        "elements": ["1 square box with heart-shaped transparent window showing pink heart candies", "character illustration on box", "2 individual candy wrappers", "5 scattered heart candies"]
      },
      {
        "type": "promotional poster",
        "position": "middle right",
        "elements": ["character portrait", "heart-shaped candy bowl", "main logo", "text '4.26 NEW OPEN'", "text '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "horizontal web banner",
        "position": "lower middle",
        "elements": ["main logo", "cherry blossoms", "character portrait on the right"]
      },
      {
        "type": "social media profile mockup",
        "position": "bottom left",
        "elements": ["header image with logo", "1 circular profile picture", "handle '{argument name=\"social handle\" default=\"@yuonchii\"}'", "1 follow button", "mock bio text"]
      },
      {
        "type": "merchandise collection",
        "position": "bottom right",
        "count": 9,
        "items": ["1 white t-shirt with logo", "1 white mug with character", "4 round pin badges", "1 acrylic keychain", "2 candy packets"]
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="Product Marketing - Anime Character Brand Identity & Merch Board - Image 1">
</div>

#### 📌 Details

- **Author:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **Source:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13547)**

---

### No. 88: Product Marketing - Dark Mode Marketing Case Study UI

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A comprehensive, data-dense landing page mockup for a marketing agency featuring timelines, charts, and glowing neon accents.

#### 📝 Prompt

```
{
  "type": "UI/UX landing page mockup",
  "theme": "dark mode, sleek modern aesthetic, glassmorphism, {argument name=\"primary accent color\" default=\"neon purple and blue\"} glowing accents",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "top_right_tag": "VIRAL CAMPAIGN CASE STUDY"
  },
  "layout": {
    "sections": [
      {
        "name": "Hero",
        "headline": "{argument name=\"hero headline\" default=\"How We Created 10M+ Viral Impact\"}",
        "subheadline": "3天引爆全网, 助力品牌实现指数级增长",
        "stats_row": {
          "count": 4,
          "labels": ["总播放量", "互动率", "转化咨询", "执行周期"],
          "values": ["{argument name=\"main statistic\" default=\"10,240,000+\"}", "18.7%", "3,200+", "72小时"]
        },
        "visual": "cinematic shot of a person in a hoodie looking at glowing digital screens and graphs, large play button overlay"
      },
      {
        "name": "Strategy",
        "title": "Our 3-Day Execution Strategy",
        "layout_type": "vertical timeline",
        "steps_count": 3,
        "elements_per_step": ["timeline node", "title", "bullet points", "video thumbnail with play button", "description box"]
      },
      {
        "name": "Performance",
        "title": "Data-Driven Performance",
        "left_column": {
          "stat_cards_count": 4,
          "values": ["10M+", "43%", "28,000+", "3,200+"]
        },
        "right_column": {
          "charts_count": 2,
          "chart_1": "line graph showing 7-day growth peaking at Day 3",
          "chart_2": "horizontal segmented bar chart showing platform distribution (TikTok 52%, Instagram 24%, X 15%, YouTube 9%)"
        }
      },
      {
        "name": "Keys to Success",
        "title": "The 3 Keys to Viral Success",
        "cards_count": 3,
        "card_elements": ["glowing icon (fire, target, antenna)", "title", "description", "VIEW DETAIL link"]
      },
      {
        "name": "Social Proof",
        "title": "TRUSTED BY CREATORS & BRANDS",
        "left_column": {
          "logos_count": 8,
          "grid": "2x4",
          "brands": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
        },
        "right_column": {
          "testimonial_cards_count": 2,
          "elements": ["quote", "author title (SaaS Founder, Growth Manager)"]
        }
      },
      {
        "name": "Call to Action",
        "title": "READY TO GO VIRAL?",
        "interactive_elements": ["text input field", "glowing button with text '{argument name=\"call to action text\" default=\"获取专属增长方案 ->\"}'"],
        "visual": "3D render of a rocket ship taking off with purple and blue flames"
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="Product Marketing - Dark Mode Marketing Case Study UI - Image 1">
</div>

#### 📌 Details

- **Author:** [开发者Hailey](https://x.com/IndieDevHailey)
- **Source:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **Published:** April 17, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13769)**

---

### No. 89: Product Marketing - 18-Panel Mascot Brand Identity Document

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A comprehensive 18-section brand guideline and character design sheet for a 3D mascot, detailing everything from moodboards and line art to 3D turnarounds and physical mockups.

#### 📝 Prompt

```
{
  "type": "18-panel brand identity and character design document",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"沐阳 MUYANG TEA\"}",
    "industry": "{argument name=\"industry\" default=\"tea shop\"}",
    "colors": ["{argument name=\"primary color\" default=\"yellow\"}", "{argument name=\"secondary color\" default=\"green\"}", "white", "brown", "dark green"]
  },
  "subject": "{argument name=\"character description\" default=\"3D rendered cute Shiba Inu mascot wearing a green apron\"}",
  "layout": {
    "grid": "3 columns by 6 rows",
    "sections": [
      {
        "title": "01 品牌DNA分析 / BRAND DNA ANALYSIS",
        "elements": ["logo", "5 color swatches", "6 icons", "target audience charts"]
      },
      {
        "title": "02 概念构思 / CONCEPT MOODBOARD",
        "elements": ["5 photo references", "4 mood icons", "design equation"]
      },
      {
        "title": "03 形态研究 / FORM STUDY",
        "elements": ["4 logo anatomy icons", "4 evolution steps", "4 silhouettes"]
      },
      {
        "title": "04 概念探索 / CONCEPT EXPLORATION",
        "elements": ["12 line-art character sketches"]
      },
      {
        "title": "05 精细线稿 / REFINED LINE ART",
        "elements": ["3 rows of front and side line art with proportion guides"]
      },
      {
        "title": "06 细节精修 / DETAIL REFINEMENT",
        "elements": ["2 full-body renders with labels", "4 circular close-ups"]
      },
      {
        "title": "07 表情设定 / EXPRESSION SHEET",
        "elements": ["11 3D rendered head expressions"]
      },
      {
        "title": "08 姿势库 / POSE LIBRARY",
        "elements": ["9 full-body 3D rendered poses"]
      },
      {
        "title": "09 转身视图 / TURNAROUND VIEW",
        "elements": ["5 full-body 3D renders", "5 matching line-art views"]
      },
      {
        "title": "10 色彩开发 / COLOR DEVELOPMENT",
        "elements": ["5 rows of 5-color palettes", "color psychology text"]
      },
      {
        "title": "11 材质规格 / MATERIAL SPECIFICATION",
        "elements": ["5 texture swatches", "property sliders", "4 manufacturing icons"]
      },
      {
        "title": "12 色彩应用 / COLOR APPLICATION",
        "elements": ["4 color variant renders", "2 light/dark renders", "4 contrast rating circles"]
      },
      {
        "title": "13 构造指南 / CONSTRUCTION GUIDE",
        "elements": ["2 line-art diagrams for geometry and grid"]
      },
      {
        "title": "14 设计系统规则 / DESIGN SYSTEM RULES",
        "elements": ["minimum size icons", "clear space diagram", "4 usage examples"]
      },
      {
        "title": "15 资产变体 / ASSET VARIANTS",
        "elements": ["3 size variants", "3 line-art variants", "3 simplified flat heads"]
      },
      {
        "title": "16 数字应用 / DIGITAL APPLICATIONS",
        "elements": ["1 app icon", "2 social avatars", "UI elements", "3-step animation cycle"]
      },
      {
        "title": "17 实物应用 / PHYSICAL APPLICATIONS",
        "elements": ["plush toy mockup", "packaging mockup", "merchandise mockup", "storefront mockup"]
      },
      {
        "title": "18 最终主视觉 / FINAL RENDERING",
        "elements": ["large high-res 3D render of mascot holding tea", "logo", "file format list"]
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="Product Marketing - 18-Panel Mascot Brand Identity Document - Image 1">
</div>

#### 📌 Details

- **Author:** [Lee Colin](https://x.com/Colin_Leeee)
- **Source:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **Published:** April 16, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13819)**

---

### No. 90: Product Marketing - Anime Samurai Game Ad Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

A flashy vertical mobile game advertisement featuring two suited swordsmen, a giant samurai mecha, gameplay UI, QR code, and app store download prompts for app promotion use.

#### 📝 Prompt

```
Create a high-impact vertical mobile game advertisement poster in glossy anime action style, with a dramatic cyber-samurai fantasy aesthetic and dense, premium gacha-RPG promotional composition. The main scene shows 2 young adult male fighters in modern black business suits crouching aggressively in the foreground, each drawing a katana toward the viewer. Both have styled blond hair, sharp handsome features, white dress shirts, blue neckties, and intense action poses, with foreshortened hands and swords dominating the lower foreground. One sword has a blue ribbon tied near the hilt. Behind them, centered and towering, place 1 massive armored mecha samurai with ornate gold horns, layered metallic blue-black armor, glowing blue eyes, and a sheathed sword across its back, framed like a guardian deity. Use a vivid neon city and energy-burst backdrop in electric blue, violet, magenta, and gold, with light streaks, sparks, petals, slash effects, and ink-brush explosion textures. Add 1 vertical black brushstroke banner on the upper right with bold white Japanese text reading 「この刃で、未来を斬り拓け。」. Across the middle-lower area, place 1 huge gold Japanese calligraphy headline with thick brush texture and black shadow reading 「切り捨て御免」, spanning nearly the full width. In the lower left, embed 1 framed gameplay screenshot panel with a gold border, showing a night battle in front of a red Japanese temple courtyard, 1 playable swordsman in combat, multiple enemies, floating damage numbers including 5324, 5329, and 6132, a left-side virtual joystick, 5 character portraits total arranged vertically and along the bottom, 3 circular skill buttons on the right, and a top HUD showing a timer around 01:28 and WAVE 3/3. In the lower right, place 1 large black-and-white QR code inside a white square frame. Beneath and beside it, add bold Japanese text in white with blue outline reading 「今すぐダウンロード」. At the very bottom, include 2 official-style store badges: App Store on the left and Google Play on the right. Overall look: ultra-detailed, polished key art, dynamic perspective, metallic highlights, sharp cel-shaded anime rendering, premium mobile game marketing poster, intense action energy, cinematic lighting, and layered UI-heavy promotional layout.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="Product Marketing - Anime Samurai Game Ad Poster - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="Product Marketing - Anime Samurai Game Ad Poster - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="Product Marketing - Anime Samurai Game Ad Poster - Image 3">
</div>

#### 📌 Details

- **Author:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **Source:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14432)**

---

### No. 91: Product Marketing - Monochrome Infra Brand Kit Board

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A clean black-and-white brand guideline and merchandise presentation board for a fictional infrastructure tech brand, suitable for pitch decks, branding showcases, and professional design mockups.

#### 📝 Prompt

```
{"type":"monochrome brand kit and swag presentation board","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"We back builders creating the foundational infrastructure for the AI era.","campaign_line":"[ BUILDING WHAT’S NEXT. FROM THE GROUND UP. ]","version":"VERSION 1.0"},"style":{"overall":"clean Swiss-inspired brand guideline sheet, minimal industrial tech aesthetic, black white and gray only, off-white paper background, sharp studio product cutouts, subtle shadows, precise grid layout, editorial presentation","mood":"professional, premium, futuristic, infrastructure-focused"},"layout":{"header":{"left":"A16Z INFRA / BRAND KIT & SWAG","right":"VERSION 1.0","divider":"dashed horizontal rule"},"sections":[{"title":"01 IDENTITY","position":"top-left","count":3,"labels":["large logotype","brand statement paragraph","campaign line in brackets"]},{"title":"02 PALETTE","position":"top-right","count":4,"labels":["WARM OFF-WHITE","BLACK","CHARCOAL","MUTED GRAY"]},{"title":"03 TYPOGRAPHY","position":"upper-right below palette","count":2,"labels":["PRIMARY -- MONOSPACE","SECONDARY -- SANS SERIF"]},{"title":"06 SWAG","position":"bottom two-thirds","count":16,"labels":["black hoodie front","black hoodie back","off-white t-shirt","black baseball cap","off-white tote bag","set of 6 square stickers/cards","black spiral notebook","black mug","black water bottle","black zip pouch","handheld retro game device","boxed micro-builds set","open keyboard kit case","cloud keycap pin","stacked cubes keycap pin","rectangular brand patch pin"]}],"footer":{"left":"A16Z INFRA / BRAND KIT","right":"© 2024 A16Z INFRA. ALL RIGHTS RESERVED.","divider":"dashed horizontal rule"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"very large custom geometric block wordmark with angular cuts, heavy black lettering, stacked on two lines"}},"palette":{"swatches":[{"name":"WARM OFF-WHITE","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"BLACK","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"CHARCOAL","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"MUTED GRAY","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"PRIMARY -- MONOSPACE","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"SECONDARY -- SANS SERIF","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}} ,"swag":{"items":[{"name":"hoodie front","color":"black","print":"small chest logo"},{"name":"hoodie back","color":"black","print":"multi-line manifesto list reading BUILDING THE INFRASTRUCTURE LAYER OF AI with dotted guide lines and categories including SYSTEMS, TOOLS, DATA, CLOUD, SECURITY, NETWORKS, DEVELOPER TOOLS"},{"name":"t-shirt","color":"off-white","print":"large centered logo"},{"name":"baseball cap","color":"black","print":"embroidered front logo"},{"name":"tote bag","color":"off-white","print":"stacked manifesto list and bottom line BUILDING WHAT'S NEXT."},{"name":"sticker/card set","count":6,"layout":"2 by 3 grid","labels":["A16Z INFRA","BUILDING THE INFRASTRUCTURE LAYER OF AI.","EARLY STAGE","SYSTEMS. TOOLS. PLATFORMS.","INFRA","BUILD","DEPLOY","SCALE"]},{"name":"spiral notebook","color":"black","print":"logo plus NOTES FOR BUILDING THE FUTURE"},{"name":"mug","color":"black","print":"white logo"},{"name":"water bottle","color":"black","print":"vertical text BUILDING WHAT'S NEXT. FROM THE GROUND UP."},{"name":"zip pouch","color":"black","print":"logo, dotted grid motif, small text SYSTEMS ONLINE."},{"name":"retro handheld device","color":"charcoal black","screen":"pixel-art city/infrastructure game screen with tabs BUILD DEPLOY SCALE and level indicator LEVEL 01"},{"name":"micro-builds box","color":"black","print":"A16Z INFRA, INFRASTRUCTURE MICRO BUILDS, COLLECT.CONNECT.SCALE.","contents":"small black gray and white modular building block models displayed in front of the box"},{"name":"keyboard kit case","color":"black","print":"A16Z INFRA KEYPAD SET BUILD. DEPLOY. SCALE.","keys":8,"labels":["INFRA","BUILD","DEPLOY","SCALE",">_","cloud icon","chip/grid icon","network diagram icon"]},{"name":"cloud pin","style":"small black enamel badge with white border"},{"name":"cubes pin","style":"small black enamel badge showing stacked isometric cubes"},{"name":"brand patch pin","style":"small rectangular black enamel badge with white logo"}]},"rendering":{"camera":"straight-on flat lay combined with orthographic product board composition","lighting":"soft even studio lighting","background":"light warm off-white sheet","quality":"high-resolution commercial mockup suitable for professional branding presentation"}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="Product Marketing - Monochrome Infra Brand Kit Board - Image 1">
</div>

#### 📌 Details

- **Author:** [Olivier Sauvage](https://x.com/Capitaine)
- **Source:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14563)**

---

### No. 92: Product Marketing - Korean Rice Drink Parody Ad Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a humorous, high-impact parody beverage advertisement poster featuring a famous politician-like spokesperson promoting a Korean canned rice drink.

#### 📝 Prompt

```
Create a bold Korean-style beverage advertisement poster with a warm golden splash background and dramatic commercial lighting. Show a {argument name="celebrity spokesperson" default="Donald Trump-like older male politician"} from the chest up, wearing a navy suit, white dress shirt, bright red tie, and a small American flag lapel pin, facing camera with a confident sales-pitch expression. His face is obscured by a flat rectangular censor block in a skin-toned color. In his left hand, extended close to the camera in forced perspective, he holds a yellow aluminum can of Korean rice punch drink labeled prominently in Korean, with red top and bottom bands and the main product text "비락 식혜" and "Since 1993" on the can. The can also includes smaller Korean copy, an image of sweet rice drink near the bottom, and the volume text "238 ml (120 kcal)". His right hand gives a thumbs-up.

Use an energetic retro-commercial composition, with splashing sweet rice beverage and droplets behind him, glowing golden highlights, and a slightly low-angle heroic framing. At the top, include 3 distinct headline text groups: a small handwritten-style black slogan on the upper left reading "전통의 맛, 한국의 DRINK!", a huge central headline in distressed bold Korean type reading "걸죽는 땐?" in dark brown-black and "비락 식혜!" in vivid red, and a brand logo on the upper right reading "비락" with small red text "Since 1993" beneath it. Add 2 callout badges: on the left, a yellow circular seal with a tiny crown icon and the text "대한민국 국민음료 No.1"; on the right, a white speech bubble with handwritten Korean text "한국이 만든 맛있는 전통!" and red English text "I LOVE IT!".

At the bottom foreground, place 2 food elements: a brass bowl filled with sweet rice drink and floating rice grains on the left, and a wooden bowl piled with white rice on the right. Across the lower middle, add 2 lines of large brush-style promotional text, the first in white reading "달콤하게! 시원하게!" and the second in mixed white and yellow reading "속까지 시~원하게!" with an energetic yellow underline stroke. Along the very bottom, include 3 circular feature icons with captions in Korean: "국내산 쌀 엄선된 재료", "시원하게 갈증해소", and "부드러운 단맛 속 편한 식혜". In the lower right corner, add tiny disclaimer text "연출된 이미지입니다". Make the overall look glossy, exaggerated, funny, and convincing like a viral parody print ad.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="Product Marketing - Korean Rice Drink Parody Ad Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Source:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14555)**

---

### No. 93: Product Marketing - Korean Sports Drink Celebrity Ad Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a flashy Korean-style hydration drink poster with a celebrity-like spokesperson, oversized product bottle, and bold promotional typography for commercial advertising use.

#### 📝 Prompt

```
A bold Korean beverage advertisement poster in a glossy commercial photography style, featuring {argument name="spokesperson" default="Donald Trump lookalike"} in a dark navy business suit, white dress shirt, and vivid blue tie, standing front-facing against a saturated bright-blue sky with a few soft white clouds and a faint modern city skyline including a tall skyscraper resembling the Empire State Building on the right. He is holding a cold plastic bottle of {argument name="product name" default="POCARI SWEAT"} dramatically toward the camera in his left hand, with extreme foreshortening so the bottle appears large in the foreground and the person is slightly behind it. The bottle is clear with condensation, a white cap, visible water inside, and a deep blue label reading “POCARI SWEAT” in large white letters with smaller text above saying “ION SUPPLY DRINK.” Add energetic frozen water splashes and droplets around the bottle, hand, and lower foreground to emphasize freshness and hydration. Place the brand logo in the upper left corner: “POCARI SWEAT” in white with the curved underline mark. Across the top, add huge distressed white Korean headline text, slightly angled and filling most of the upper half: {argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}. In the lower right over the suit, add a bold italic quotation in white and blue Korean text: {argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}. In the bottom left, include exactly 3 circular benefit icons stacked vertically with short Korean labels: a water drop icon with “수분 보충”, a lightning bolt icon with “전해질 보충”, and a running figure icon with “빠른 흡수”. Use a high-contrast, patriotic blue-and-white color palette, dramatic ad lighting, sharp focus on the bottle and hand, slightly softer focus on the face and background, and an overall energetic premium campaign-poster look.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="Product Marketing - Korean Sports Drink Celebrity Ad Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Source:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14553)**

---

### No. 94: Product Marketing - Japanese Jungle Theme Park Parody Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A cinematic satirical Japanese ad poster for a fictional jungle dinosaur theme park, ideal for parody campaigns, social media visuals, or mock promotional key art.

#### 📝 Prompt

```
A hyper-detailed Japanese parody theme park advertisement poster in a vertical format, designed like a dramatic summer travel ad mixed with a luxury attraction campaign. The setting is a tropical jungle under a vivid blue sky with scattered clouds and a bright blazing sun in the upper right corner, with palm leaves framing the top edges. Across the top, place a huge 3D stone-textured Japanese headline reading {argument name="headline text" default="ジャンキリア沖縄"}, with a smaller white Japanese tagline underneath that reads "— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —". In the center, feature a large modern smartphone standing upright and slightly tilted, dominating the composition. On its screen, show a beige ticket-lottery waiting interface with jungle silhouettes at the top and large bold Japanese text reading "整理券抽選中", a circular loading indicator, and smaller text near the bottom reading "結果発表まで30分" and "※この画面を閉じずにお待ちください". The phone status bar should show 10:00. Behind the phone on the left, place a roaring Tyrannosaurus rex emerging from jungle foliage, mouth open wide, realistic and threatening. On the right, place an ornate golden entrance gate with detailed carvings and a sign reading "プレミアムパス入口", leading to a red-carpeted premium entry lane. In the foreground and midground, show a long crowded queue of park visitors stretching deep into the scene, all wearing casual summer clothing, hats, towels, backpacks, and carrying umbrellas, fans, and water bottles, suggesting extreme heat and exhaustion. Several people nearest the viewer should have blurred faces. On the far left, add a giant weathered stone sign with huge red Japanese text reading "待ち時間 180分". At the lower left, include 3 stacked rustic wooden signboards: the top sign has a blue parking icon and text "駐車場 2,000円"; the middle sign has a smartphone icon and text "アプリ必須 ダウンロードしてね!"; the bottom sign has a dinosaur silhouette and text "当選者だけが冒険へ". Along the lower right side, place very large vertical white brush-style Japanese copy reading "待つこと、それが冒険だ。". Near the bottom right, include 3 small circular icon callouts with short Japanese promotional lines: "抽選に選ばれし者だけが、恐竜に会える。", "スマホの充電が尽きる前に、夢は始まる。", and "プレミアムな近道も、ご用意しました。" with icons suggesting dinosaur, phone battery, and VIP access. At the very bottom center, add a black disclaimer strip with small white Japanese text reading "このポスターは架空のパロディ広告です". The overall style should be ultra-realistic, cinematic, high-contrast, satirical, and polished like a premium commercial poster, with exaggerated theme park hype, oppressive heat, and absurd queue-based adventure as the core joke.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="Product Marketing - Japanese Jungle Theme Park Parody Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **Source:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **Published:** April 22, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14545)**

---

### No. 95: Product Marketing - Move Display Stand Onto Deck

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt places the reference promotional display onto the wooden deck in the same outdoor scene for realistic environmental advertising mockups.

#### 📝 Prompt

```
Using the provided reference image, keep the same garden, pond, trees, hillside, and wooden deck viewpoint, but reposition the decorative sign installation so it stands on the wooden deck in the foreground instead of in the water. Enlarge it and center it more prominently in front of the camera while preserving a believable outdoor perspective, natural daylight, and consistent shadows. Keep the installation structure as a 3-column by 3-row set of 9 circular sign panels on slim green stands with the top header sign reading “对着镜子笑一场”. Make the panels look more reflective and mirror-like, showing realistic reflections of the surrounding greenery, while retaining the cute face graphics and Chinese text on the circles. The result should look like a realistic ad mockup/composite photo of the same display placed correctly in the scene.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="Product Marketing - Move Display Stand Onto Deck - Image 1">
</div>

#### 📌 Details

- **Author:** [肖师傅](https://x.com/xiaojietongxue)
- **Source:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14487)**

---

### No. 96: Product Marketing - Three Beauty Mobile Landing Pages

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A premium triptych mockup of three smartphone beauty website designs, ideal for showcasing AI-generated cosmetic brand landing page concepts on social media.

#### 📝 Prompt

```
A polished promotional mockup showing 3 tall smartphone screens displayed side by side in a vertical triptych layout, each presenting a modern beauty brand landing page for a lip product. The overall composition is editorial, minimal, and premium, designed like a social media showcase of mobile web designs. The left panel sits on a soft lavender-to-blush gradient background and shows a black-framed phone with a cream and blush beauty website for {argument name="brand name" default="Kosas"}. At the top of this panel, small elegant serif text reads {argument name="left headline" default="Fresh Pout."}. The phone screen features a cropped close-up beauty image at the top, a bold headline reading “Lips in their fullest expression.” with “fullest” in italic serif styling, a rounded dark call-to-action button, a strip of 3 lip close-up thumbnails, 3 labeled benefit tabs reading “Plumps,” “Tingles,” and “Shines,” and a row of 5 shade or effect icons underneath. The middle panel sits on a lavender-to-deep-violet gradient background and shows a second black-framed phone with a more typographic landing page. Above it, serif text reads {argument name="middle headline" default="Claude Code"}. The screen includes a cropped portrait image at top, a very large bold black stacked title reading “LIP PULSE.” with a pink italic script-style line “is here.” beneath it, a rounded dark button, a dark section with the phrase “Lips in their fullest expression.”, and a product grid near the bottom containing 6 shade cards arranged in 2 rows of 3. The right panel sits on a dark navy textured background and shows a third black-framed phone with a pink-forward e-commerce style page. Centered above it, monospaced white text reads {argument name="right headline" default="GPT Images 2.0"}. This screen prominently displays the product hero section with the brand name “Kosas,” a large title “The Lip Pulse,” a pink lip gloss tube angled to the right, small feature icons, a shade strip of 6 lip swatches near the middle, and a lower promotional block with additional pink product imagery. Keep the layout symmetrical with exactly 3 phones, one per panel, each fully visible and vertically oriented. Use high-end cosmetic campaign aesthetics, clean spacing, fashion-web typography mixing serif and bold sans serif, soft pink and cream UI palettes, subtle shadows, and a sleek product-design presentation suitable for showcasing AI-generated mobile website concepts.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="Product Marketing - Three Beauty Mobile Landing Pages - Image 1">
</div>

#### 📌 Details

- **Author:** [Serene Gan](https://x.com/ganserene)
- **Source:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14426)**

---

### No. 97: Product Marketing - Multi-industry Japanese Ad Collage

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt for generating a multi-industry advertising collage in Japanese, featuring six distinct industry segments in a contemporary design style.

#### 📝 Prompt

```
A fictional Japanese advertisement. A horizontal 6-panel layout featuring ads for {argument name="industry list" default="the automotive industry (new car debut), theme parks (new event), the cosmetics industry (new products), the book industry (No. 1 best-selling book), the beverage industry (new drink), and the real estate industry (new luxury condominium introduction)"}. Created in the latest trendy style by a top creator.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="Product Marketing - Multi-industry Japanese Ad Collage - Image 1">
</div>

#### 📌 Details

- **Author:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **Source:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **Published:** April 21, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=14369)**

---

### No. 98: Product Marketing - Luxury Fashion Book Spread

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a realistic overhead photo of an open fashion book featuring a two-page couture editorial spread, ideal for luxury branding, magazine mockups, or style campaign visuals.

#### 📝 Prompt

```
A high-end editorial fashion photograph shown as an open large-format hardcover magazine or art book lying flat on a clean off-white surface, viewed from directly above. The two-page spread contains 2 full-page portraits of the same elegant woman with her face obscured by a soft square blur, creating a privacy-censored look. On the left page, she stands against a pale stone or concrete architectural wall wearing a structured long-sleeve dress in {argument name="dress color" default="soft slate gray"}, with a fitted bodice, round neckline, sharply tailored seams, and an exaggerated sculptural bell-shaped skirt; the camera angle is slightly low, making her neck appear long and her posture statuesque. On the right page, she is photographed from the back in a dramatic {argument name="second dress color" default="black"} evening gown with a very deep open back, wide shoulder straps, and a voluminous full skirt, standing in front of a classic paneled wall or door in a dim, moody interior. Use luxury fashion magazine styling, minimal composition, muted tones, soft natural-looking light, refined shadows, realistic paper texture, visible book gutter, slightly curved pages, and crisp print detail. The overall mood is sophisticated, couture, cinematic, and understated, like a premium fashion editorial spread.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="Product Marketing - Luxury Fashion Book Spread - Image 1">
</div>

#### 📌 Details

- **Author:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14676)**

---

### No. 99: Product Marketing - Modern Iced Coffee Advertisement Design

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt for creating a modern, stylish iced coffee advertisement for the Japanese market, featuring dynamic typography.

#### 📝 Prompt

```
Create an advertisement for {argument name="product" default="iced coffee"}. A stylish and modern design from {argument name="country" default="Japan"}. European fonts are dynamically laid out. Target audience: {argument name="target" default="10-30s"}. Aspect ratio 1:1.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="Product Marketing - Modern Iced Coffee Advertisement Design - Image 1">
</div>

#### 📌 Details

- **Author:** [KAWAI](https://x.com/kawai_design)
- **Source:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **Published:** April 21, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=14355)**

---

### No. 100: Product Marketing - ChatGPT Joke Prescription Set

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

A realistic overhead photo of a humorous Japanese medical prescription and medicine set for ChatGPT, ideal for parody healthcare-themed prop graphics or social media concept art.

#### 📝 Prompt

```
A realistic overhead product photograph on a warm wooden tabletop showing 6 medical-style items neatly arranged in two rows, designed as a humorous Japanese pharmacy set for ChatGPT. Top row: 3 white prescription envelopes standing vertically, each with blue printed borders and Japanese medical typography. Bottom row: 2 blister packs of tablets and 1 small transparent zip bag of white powder, each aligned beneath the corresponding envelope. The paper and packaging should look authentic, like real Japanese clinic dispensing materials, with slight wrinkles, soft natural indoor lighting, and subtle shadows.

The 3 envelopes are all different and fully visible. Left envelope title in large blue Japanese text: "内用薬". Patient line reads "ChatGPT 様". Dosage lines indicate twice daily after morning and evening meals, 1 tablet each time, for 7 days. Medicine box title: "【おくすり】" and drug name "思考安定錠 10mg" with a smaller parenthetical note explaining it suppresses runaway thoughts and excessive reasoning output. Date near bottom: "2025年6月5日". Clinic name and address block at bottom: "AIメディカルクリニック" with a Tokyo-style address and phone number, plus a blue medical cross icon.

Center envelope title: "内用薬". Patient line: "ChatGPT 様". Dosage indicates once daily before sleep, 1 tablet each time, for 7 days. Medicine box title: "【おくすり】" and drug name "幻覚抑制錠 5mg" with a smaller note saying it improves hallucinatory tendencies. Date also "2025年6月5日". Same clinic footer and blue medical cross icon.

Right envelope title: "頓服薬". Patient line: "ChatGPT 様". Usage line says for anxiety, confusion, or excessive output. Dosage says 1 packet each time, as needed. Medicine box title: "【おくすり】" and drug name "プロンプト調整散 1g" with a smaller note saying it adjusts overfitting and prompt confusion. Date "2025年6月5日". Same clinic footer and blue medical cross icon.

Bottom left item: 1 silver blister pack containing exactly 10 round white tablets arranged in 2 rows of 5, each tablet embossed with "10". Printed along the foil edge: "思考安定錠10mg" repeated. In front of it is a white pharmacy label with "ChatGPT 様", dosage directions for twice daily after morning and evening meals, 1 tablet each time, a barcode, date "2025/06/05", and clinic name.

Bottom center item: 1 silver blister pack containing exactly 8 pale yellow round tablets arranged in 2 rows of 4. Printed along the foil edge: "幻覚抑制錠5mg" repeated. In front of it is a white pharmacy label with "ChatGPT 様", dosage directions for once daily before sleep, 1 tablet each time, a barcode, date "2025/06/05", and clinic name.

Bottom right item: 1 small clear zip-top plastic bag filled with white powder. A white label on the front reads "プロンプト調整散 1g", includes "ChatGPT 様", usage for anxiety, confusion, and excessive output, dosage "1回1包（1g） 必要時", date "2025/06/05", and clinic name.

Style: photorealistic documentary product shot, comedic fake prescription prop design, clean Japanese pharmaceutical graphic layout, high legibility, neutral color palette of white, blue, silver, beige, and wood brown, top-down camera, no hands, no extra objects, authentic print texture and packaging details.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="Product Marketing - ChatGPT Joke Prescription Set - Image 1">
</div>

#### 📌 Details

- **Author:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14537)**

---

### No. 101: E-commerce Main Image - Studio Product Render From Blueprint

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

This prompt converts a technical product drawing into a minimal photorealistic hero shot for catalog, industrial design, or e-commerce presentation.

#### 📝 Prompt

```
Using the provided reference image, turn the technical engineering spec sheet into a clean studio product hero render of the same jellyfish-shaped kitchen utensil holder. Keep the overall product design, translucent blue dome cap, silver base, and the same 4 hanging utensils: 1 slotted spatula, 1 pasta server, and 2 spoons. Remove all blueprint elements, including the exploded view, dimension lines, labels, tables, notes, and title block. Show only the assembled product centered in frame, front-facing, isolated against a minimal light gray background with a white surface, soft diffused lighting, subtle realistic shadows, and glossy premium materials. Make it look like a contemporary industrial design catalog or e-commerce product photograph.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="E-commerce Main Image - Studio Product Render From Blueprint - Image 1">
</div>

#### 📌 Details

- **Author:** [amy](https://x.com/amypretzel)
- **Source:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14690)**

---

### No. 102: E-commerce Main Image - Premium Blueberry Product Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a polished Chinese-style e-commerce advertisement for packaged blueberries, suitable for supermarket branding, product listings, and promotional posters.

#### 📝 Prompt

```
A premium e-commerce poster for fresh blueberries in a clean Chinese product-advertising style. Show a clear plastic clamshell box of blueberries as the main subject, placed diagonally from lower center to right side on folded blue fabric, viewed from a slightly elevated angle. The package must remain realistic and consistent: a transparent square container with rounded corners, filled with dark blue blueberries, with a large irregular rounded label on top in white, pale blue, and deep blue, featuring one oversized blueberry illustration in the center and elegant Chinese branding. Make the fruit inside look larger, plumper, fresher, and covered with subtle moisture droplets, while keeping the overall blueberry arrangement believable. The background is an airy icy-blue tabletop with soft cloudy texture, cool daylight, and scattered loose blueberries around the package. Add a few blurred green leaves entering from the top right and bottom right edges for a fresh natural feeling. In the upper-right corner, include 1 small inset image showing the original product package from above on a warm brown surface, like a reference thumbnail. On the left side, create Chinese promotional typography with a large dark blue calligraphy headline {argument name="headline text" default="决茗新"}, followed by 2 smaller lines of copy: {argument name="subheadline text" default="新鲜蓝莓 自然之选"} and {argument name="tagline text" default="每一颗都是自然的礼物"}. Below that, place 3 vertically stacked feature icons with short Chinese captions: a leaf icon for natural ripeness, a fruit icon for juicy fullness, and a heart icon for rich nutrition. Near the bottom left, add large white brush-style Chinese text {argument name="product name" default="蓝莓"}, a secondary line {argument name="benefit text" default="膳食纤维+花青素"}, and a small net weight line reading 125克. Use cool blue color grading, crisp commercial lighting, sparkling highlights on the plastic lid, premium supermarket packaging aesthetics, high detail, realistic product photography blended with polished graphic design.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="E-commerce Main Image - Premium Blueberry Product Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [歸藏(guizang.ai)](https://x.com/op7418)
- **Source:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14655)**

---

### No. 103: E-commerce Main Image - Minimalist Fashion Moodboard Outfit

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This prompt generates a clean editorial outfit collage with branded styling, useful for fashion inspiration boards, social posts, and digital wardrobe concepts.

#### 📝 Prompt

```
A clean editorial fashion collage on a light gray-white background with a thin black rectangular border, styled like a minimalist magazine outfit board. Center the outfit as a flat lay style composition with 5 visible fashion items: a bright {argument name="jacket color" default="crimson red"} cropped zip-front jacket with a pointed collar and elastic hem placed slightly left and layered on top; underneath it, a fitted {argument name="top color" default="white"} long-sleeve crew-neck knit top visible at the shoulders and sleeves; below, a voluminous mid-calf A-line skirt in off-white with evenly spaced large black polka dots; at lower left, a structured small black handbag with short top handles and a subtle glossy crocodile texture; at lower right, one pair of black square-toe Mary Jane flats with wide straps and silver grommet-ring hardware. Add oversized very pale gray background typography reading {argument name="background brand text" default="MANGO"} stretched large across the middle behind the clothing. Place smaller black fashion-brand wordmarks around the layout: {argument name="top right logo" default="MANGO"} near the upper right of the outfit, "Stradivarius" near the handbag and again near the shoes, and "DOLCE & GABBANA" at the lower left near the skirt hem. The composition should feel balanced, chic, and contemporary, with soft studio lighting, no shadows or only faint soft shadows, crisp cutout edges, and a polished social-media fashion moodboard aesthetic.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="E-commerce Main Image - Minimalist Fashion Moodboard Outfit - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="E-commerce Main Image - Minimalist Fashion Moodboard Outfit - Image 2">
</div>

#### 📌 Details

- **Author:** [虎小象](https://x.com/hx831126)
- **Source:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14455)**

---

### No. 104: E-commerce Main Image - Mechanical Keyboard Product Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

This generates a polished desktop e-commerce product page for a premium mechanical keyboard, suitable for product design showcases, storefront concepts, and UI mockups.

#### 📝 Prompt

```
Create a clean modern e-commerce product detail page for a premium mechanical keyboard brand called {argument name="brand name" default="KeyForge"}, presented as a high-fidelity desktop website mockup on a white background with subtle light-gray dividers and generous spacing. The layout is a single unified storefront scene with a top navigation bar, a left product thumbnail rail, a large center product hero image, and a right-side purchase information panel. In the header, place the bold wordmark on the far left, then 7 navigation items reading “Keyboards”, “Switches”, “Keycaps”, “Accessories”, “Sale”, “Blog”, and “Support”, and on the far right 3 icons for search, account, and cart, with a small black notification badge showing “1” on the cart. The main product shown in the center is a compact 75% mechanical keyboard photographed from a slightly elevated front angle on a pale gray stage, with an aluminum case in silver, white and gray keycaps, several accent keys in lavender purple, and a silver volume knob at the top right. The left vertical gallery contains exactly 5 thumbnails: 1 selected front product shot, 1 angled keyboard view, 1 mechanical switch close-up, 1 keycap texture close-up, and 1 dark video thumbnail with a circular play icon. The right product panel includes a small pill badge reading “NEW”, a large bold product name {argument name="product name" default="KeyForge K75 Pro"}, a subtitle “75% Mechanical Keyboard”, a 5-star rating row with 4.8 and “(126 reviews)”, a large bold price {argument name="price" default="$129.99"} followed by a green “In Stock” status, and a short two-sentence description about premium performance, gasket-mounted design, QMK/VIA support, and RGB. Under that, include a “Switch Type” selector with exactly 4 pill buttons labeled “Cherry MX Red”, “Gateron Brown”, “Gateron Blue”, and “TTC Gold Pink”, with the first selected; a “Color” selector with exactly 3 pill buttons labeled “White / Purple”, “Black / Gray”, and “Navy / Blue”, with the first selected; a “Quantity” dropdown set to “1”; one large black primary button labeled “Add to Cart” with a cart icon; and one outlined secondary button labeled “Add to Wishlist” with a heart icon. Beneath the buttons, show exactly 3 horizontal service highlights with small icons: “Free Shipping” with subtext “On orders over $99”, “30-Day Returns” with subtext “Hassle-free returns”, and “2-Year Warranty” with subtext “Peace of mind”. In the lower content area, create a two-column section separated by light lines. On the left is a vertical tab list with exactly 5 items: “Overview” selected, then “Specifications”, “What’s in the Box”, “Shipping & Returns”, and “Reviews (126)”. To the right of the tabs, place a rounded white feature card grid with exactly 6 feature blocks in 2 rows of 3, each with a simple line icon, bold title, and short explanatory text: “75% Layout”, “Gasket-Mounted”, “QMK/VIA Support”, “Hot-Swappable”, “RGB Backlighting”, and “Premium Build”. On the far right of this lower area, add a specifications bullet list with exactly 7 bullets: “Layout: 75% (82 Keys)”, “Switch Type: Cherry MX Red”, “Mounting: Gasket-Mounted”, “Connectivity: USB-C (Wired)”, “Backlight: RGB, South-facing”, “Material: Aluminum Case”, and “Dimensions: 322 x 135 x 42 mm”, plus an additional final bullet “Weight: 1.25 kg”. Use a refined minimalist product-design aesthetic, realistic UI spacing, clean sans-serif typography similar to Inter or SF Pro, soft shadows, subtle rounded corners, monochrome icons, and polished startup-style consumer electronics presentation.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="E-commerce Main Image - Mechanical Keyboard Product Page Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **Source:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **Published:** April 21, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14449)**

---

### No. 105: E-commerce Main Image - Skincare E-commerce Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a clean, clinical web design mockup for a skincare brand featuring a hero image, product shot, and feature highlights.

#### 📝 Prompt

```
{
  "type": "skincare e-commerce landing page mockup",
  "brand": "{argument name=\"brand name\" default=\"DERMA CALM\"}",
  "color_palette": ["white", "light blue", "{argument name=\"primary color\" default=\"dark blue\"}"],
  "layout": {
    "header": {
      "logo": "left-aligned brand name with Japanese subtext",
      "navigation_links": {
        "count": 6,
        "labels": ["ABOUT", "PRODUCT", "FEATURE", "INGREDIENT", "VOICE", "Q&A"]
      },
      "buttons": {
        "count": 2,
        "labels": ["マイページ", "今すぐ購入する"]
      }
    },
    "hero_section": {
      "left_column": {
        "headline": "{argument name=\"hero headline\" default=\"敏感な肌にも、毎日つづけられる安心ケア。\"}",
        "subtext": "paragraph detailing low irritation, moisturizing, fragrance-free, and alcohol-free benefits",
        "buttons": {
          "count": 2,
          "labels": ["今すぐ購入する", "詳しく見る"]
        }
      },
      "center_column": {
        "product": "white pump bottle with clear cap labeled {argument name=\"product type\" default=\"Moisture Barrier Serum\"}",
        "props": ["dollop of white cream", "circular badge reading 皮膚科医監修"]
      },
      "right_column": {
        "subject": "{argument name=\"model description\" default=\"young East Asian woman with clear glowing skin touching her cheek\"}",
        "background": "blurred laboratory glassware in a bright, clean clinical setting"
      }
    },
    "bottom_features_panel": {
      "left_cards": {
        "count": 3,
        "descriptions": ["95% satisfaction with 5 stars", "shield icon for low irritation formula", "drop icon for skin barrier support"]
      },
      "right_badges": {
        "count": 3,
        "descriptions": ["no fragrance icon", "no alcohol icon", "patch tested icon"]
      },
      "footer": "fine print disclaimers at the bottom"
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="E-commerce Main Image - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14278)**

---

### No. 106: E-commerce Main Image - Men's Skincare Website Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a sleek, dark-themed e-commerce landing page mockup for a men's skincare product, featuring a model, product shot, and feature statistics.

#### 📝 Prompt

```
{
  "type": "website landing page mockup",
  "theme": "men's skincare, sleek, professional, dark mode",
  "color_palette": "{argument name=\"color scheme\" default=\"dark navy blue\"}, white text, subtle blue gradients",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"NEX SKIN\"}",
    "navigation": ["HOME", "PRODUCT", "ABOUT", "FEATURE", "FAQ"],
    "cta_button": "今すぐ始める >"
  },
  "hero_section": {
    "left_column": {
      "headline": "{argument name=\"main headline\" default=\"清潔感は、毎日のスキンケアから。\"}",
      "sub_headline": "男の肌は、もっとシンプルでいい。",
      "body_text": "3 lines of descriptive text about skincare benefits",
      "buttons": [
        {"style": "solid blue", "text": "今すぐ始める >"},
        {"style": "outlined", "text": "詳しく見る >"}
      ],
      "feature_highlights": {
        "count": 3,
        "items": [
          {"icon": "sparkle", "title": "テカリ対策", "subtitle": "皮脂バランスを整える"},
          {"icon": "water drop", "title": "保湿", "subtitle": "うるおいを与え続ける"},
          {"icon": "shield/bottle", "title": "オールインワン", "subtitle": "化粧水・美容液・乳液がこれ1本"}
        ]
      }
    },
    "center_image": {
      "subject": "handsome {argument name=\"target demographic\" default=\"young Asian man\"}",
      "appearance": "clean-cut, dark hair, flawless glowing skin, wearing a black shirt",
      "pose": "hand touching chin thoughtfully",
      "lighting": "dramatic studio lighting highlighting facial structure"
    },
    "right_column": {
      "product_shot": {
        "bottle": "tall cylindrical dark blue bottle with water droplets",
        "labels": ["{argument name=\"brand name\" default=\"NEX SKIN\"}", "{argument name=\"product type\" default=\"ALL-IN-ONE LOTION\"}", "150mL"],
        "base": "textured dark rock surface",
        "badge": "circular outlined badge reading 'これ1本で男の肌悩みをトータルケア'"
      }
    }
  },
  "bottom_stats_bar": {
    "count": 3,
    "items": [
      {"icon": "users", "label": "累計販売本数", "value": "120万本突破"},
      {"icon": "star", "label": "使用感満足度", "value": "92.1%"},
      {"icon": "checklist", "label": "リピート率", "value": "85.3%"}
    ],
    "footnotes": "small legal text on the right"
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="E-commerce Main Image - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14277)**

---

### No. 107: E-commerce Main Image - Skincare E-commerce Landing Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a structured e-commerce hero banner for skincare products, featuring a model, product shots, feature icons, and statistic cards.

#### 📝 Prompt

```
{
  "type": "e-commerce landing page hero section",
  "brand": "{argument name=\"brand name\" default=\"CLEAR RESET\"}",
  "theme": "refreshing skincare, clean aesthetic, water bubbles background",
  "color_palette": ["white", "{argument name=\"primary color\" default=\"teal\"}", "light blue"],
  "layout": {
    "header": {
      "logo": "CLEAR RESET",
      "navigation_links": {"count": 5, "labels": ["About Product", "About Pores/Acne", "Ingredients", "How to Use", "FAQ"]},
      "action_buttons": {"count": 2, "labels": ["Buy Now", "My Page"]}
    },
    "hero_content": {
      "headline": "{argument name=\"main headline\" default=\"毛穴・ニキビ悩みに、すっきり澄んだ肌へ。\"}",
      "subheadline": "Balances sebum and clears pores. Non-sticky, medicated skincare for comfortable daily use.",
      "vertical_copy": "Prevents recurring rough skin and acne, leading to smooth, clear skin."
    },
    "visuals": {
      "model": "{argument name=\"model description\" default=\"young Asian woman with clear radiant skin, hair tied up, smiling softly\"}",
      "products": {
        "count": 2,
        "description": "{argument name=\"product type\" default=\"acne care gel tube and lotion bottle\"}",
        "placement": "center"
      },
      "background": "light blue gradient with floating water bubbles"
    },
    "feature_highlights": {
      "count": 4,
      "style": "circular icons with text below",
      "labels": ["Quasi-drug", "Pore Care", "Non-sticky", "Daily Use Morning/Night OK"]
    },
    "call_to_action": {
      "banner_text": "Limited to first-time buyers",
      "buttons": {"count": 2, "labels": ["Try it at a discount", "See details"]}
    },
    "statistics_cards": {
      "count": 4,
      "style": "white rectangular cards with large teal numbers",
      "labels": ["Satisfaction 92%", "Pore visibility -23%", "Acne prevention 87%", "Want to repeat 97%"]
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="E-commerce Main Image - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 Details

- **Author:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14276)**

---

### No. 108: E-commerce Main Image - Beauty Product Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a clean, feminine e-commerce landing page hero section for a beauty product, featuring a model, product shots, and structured marketing copy.

#### 📝 Prompt

```
{
  "type": "e-commerce landing page hero section mockup",
  "aesthetic": "clean, bright, airy, feminine, floral accents with purple flowers, {argument name=\"primary color\" default=\"soft pink\"} and white color palette, soft lighting",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"LUMEA BEAUTY\"}",
    "navigation_links": {
      "count": 5,
      "labels": ["特徴", "成分", "お客様の声", "使い方", "FAQ"]
    },
    "cta_button": "今すぐ試す"
  },
  "hero_section": {
    "left_column": {
      "headline": "{argument name=\"headline text\" default=\"鏡を見るたび、うるおう透明感。\"}",
      "subheadline": "乾燥・くすみが気になる肌に。美容成分を贅沢に配合した、毎日のための集中保湿美容液。",
      "feature_badges": {
        "count": 3,
        "style": "pill-shaped with small icons",
        "labels": ["敏感肌OK", "高保湿", "朝晩使える"]
      },
      "bullet_points": {
        "count": 3,
        "style": "pink checkmarks",
        "labels": ["美容成分をしっかり届ける", "ハリ・ツヤのある印象へ", "続けやすいシンプルケア"]
      },
      "cta_buttons": {
        "count": 2,
        "labels": ["初回限定で試してみる >", "成分をチェック >"]
      },
      "trust_badges": "送料無料 / 初回限定 / 定期縛りなし"
    },
    "center_subject": {
      "model": "{argument name=\"model description\" default=\"young East Asian woman smiling, touching her cheek\"}",
      "action": "holding a dropper bottle of serum"
    },
    "right_column": {
      "product_display": {
        "count": 2,
        "items": ["{argument name=\"product type\" default=\"moisturizing boost serum\"} dropper bottle", "packaging box"]
      },
      "stat_cards": {
        "count": 3,
        "style": "floating white rounded rectangles with gold accents",
        "labels": ["満足度 96%", "美容成分 5種配合", "愛用者 12,000人突破"]
      }
    }
  },
  "bottom_section": {
    "benefit_cards": {
      "count": 3,
      "style": "horizontal white rounded rectangles with icons",
      "labels": ["うるおい", "透明感", "使いやすさ"]
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="E-commerce Main Image - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14274)**

---

### No. 109: E-commerce Main Image - Fashion Collection Catalog Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a multi-panel fashion catalog showcasing different products featuring a unified pattern design.

#### 📝 Prompt

```
{
  "type": "fashion product catalog layout",
  "theme": "A cohesive fashion collection featuring a specific pattern: {argument name=\"pattern description\" default=\"overlapping circular floral mandala motifs in purple, green, blue, orange, and pink\"}",
  "layout": {
    "structure": "2x2 grid with a full-width bottom banner",
    "sections": [
      {
        "id": "01",
        "title": "{argument name=\"product 1\" default=\"Flared Dress\"}",
        "subtitle": "フレアワンピース",
        "main_image": "Woman in patterned flared dress holding white handbag.",
        "swatch_count": 3,
        "swatch_descriptions": ["purple variant", "green/blue variant", "orange/yellow variant"],
        "description_text": "華やかなフレアシルエット。軽やかな素材が優雅な動きを演出します。"
      },
      {
        "id": "02",
        "title": "{argument name=\"product 2\" default=\"Silk Scarf\"}",
        "subtitle": "シルクスカーフ",
        "main_image": "Woman in white blouse with patterned silk scarf.",
        "swatch_count": 2,
        "swatch_descriptions": ["flat pattern detail", "tied knot detail"],
        "description_text": "首元に彩りを添えるシルクスカーフ。上品な光沢と滑らかな肌ざわり。"
      },
      {
        "id": "03",
        "title": "{argument name=\"product 3\" default=\"Tote Bag\"}",
        "subtitle": "トートバッグ",
        "main_image": "Woman carrying patterned tote bag.",
        "swatch_count": 3,
        "swatch_descriptions": ["purple variant", "blue variant", "orange/yellow variant"],
        "description_text": "A4サイズも入る収納力。軽くて丈夫、毎日使いたくなるトートバッグ。"
      },
      {
        "id": "04",
        "title": "{argument name=\"product 4\" default=\"Pouch\"}",
        "subtitle": "ポーチ",
        "main_image": "Patterned zip pouch on table with magazine and vase.",
        "swatch_count": 3,
        "swatch_descriptions": ["green/purple variant", "orange variant", "pink variant"],
        "description_text": "バッグの中を彩る華やかなポーチ。細部まで美しいデザインが魅力です。"
      }
    ],
    "bottom_banner": {
      "title": "Pattern Design",
      "description_text": "細やかな線と豊かな色彩が織りなす、唯一無二のパターンデザイン。日常に優雅な彩りを。",
      "image": "Horizontal strip showing the seamless pattern."
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="E-commerce Main Image - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 Details

- **Author:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **Source:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14241)**

---

### No. 110: E-commerce Main Image - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 Prompt

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="E-commerce Main Image - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 Details

- **Author:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **Source:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14183)**

---

### No. 111: E-commerce Main Image - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 Prompt

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="E-commerce Main Image - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 Details

- **Author:** [pozitiv4ik](https://x.com/Gc_qube)
- **Source:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14148)**

---

### No. 112: E-commerce Main Image - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 Prompt

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="E-commerce Main Image - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 Details

- **Author:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **Source:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **Published:** April 20, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14225)**

---

### No. 113: E-commerce Main Image - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 Prompt

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="E-commerce Main Image - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="E-commerce Main Image - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="E-commerce Main Image - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="E-commerce Main Image - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 Details

- **Author:** [阿兰AI](https://x.com/alanlovelq)
- **Source:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **Published:** April 20, 2026
- **Languages:** zh

**[👉 Try it now →](https://gptimage2api.net/?id=14134)**

---

### No. 114: E-commerce Main Image - Livestream E-commerce Interface Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a mobile livestream shopping interface featuring a celebrity selling a fictional product, complete with chat overlay and UI elements.

#### 📝 Prompt

```
{
  "type": "mobile livestream e-commerce interface mockup",
  "subject": {
    "person": "Elon Musk",
    "clothing": "black t-shirt with SPACEX logo",
    "pose": "gesturing towards camera with both hands, explaining enthusiastically",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "large display screen",
    "image": "Mars landscape with Starship rocket and dome habitats",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"移民火星计划\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "75.8万本场点赞",
        "follow_button": "关注"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "10万+",
        "close_button": "X"
      },
      "tags": [
        "带货总榜第1名",
        "更多直播 >"
      ]
    },
    "product_card": {
      "position": "mid-right",
      "status": "讲解中",
      "image": "Mars dome habitats",
      "title": "{argument name=\"product title\" default=\"火星移民基础套餐\"}",
      "price": "{argument name=\"product price\" default=\"¥99.00\"}",
      "action_button": "抢"
    },
    "chat_overlay": {
      "position": "bottom-left",
      "join_alert": "星辰大海 加入了直播间",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"梦想家: 支持马斯克！！🚀\"}",
        "火星弟弟: 多少钱一位？",
        "科技迷: 太酷了！想去火星！",
        "未来已来: 如何报名？",
        "小火箭: 🌹🌹🌹",
        "宇宙无敌: 讲解一下细节",
        "东方不败: 老马牛逼！👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "说点什么...",
      "icons_count": 4,
      "icons": ["shopping cart", "gift box", "heart planet", "plus sign"]
    },
    "floating_reactions": {
      "position": "bottom-right",
      "elements": "stack of floating hearts, thumbs up, and laughing emojis"
    }
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="E-commerce Main Image - Livestream E-commerce Interface Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **Source:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **Published:** April 19, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13557)**

---

### No. 115: E-commerce Main Image - Summer Beach Beverage Commercial Shot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a refreshing product photography scene of a canned drink and glass on a beach, featuring customizable product text and a sky catchphrase.

#### 📝 Prompt

```
A bright, summery commercial product photography shot featuring a refreshing beverage on a weathered wooden table. In the sharp foreground, there is 1 tall glass filled with a golden, bubbly iced drink garnished with 1 lemon slice and a sprig of rosemary, sitting next to 1 silver aluminum can covered in cold condensation. The can prominently displays the English text {argument name="product name" default="TOKYO HIGHBALL"} below a small gold star logo, featuring a graphic of the drink itself and the Japanese text "アルコール分 7%" near the bottom. To the right of the can, 2 cut lemon wedges rest on the table. In the softly blurred background, a sunny beach scene unfolds with sparkling turquoise water and a clear blue sky. Standing to the left in the background is 1 young woman with long brown hair, wearing a white sleeveless top and a light blue skirt, looking out toward the ocean. Floating elegantly in the sky above the scene is the Japanese text {argument name="catchphrase" default="夏、これがいい。"}. The overall lighting is radiant and inviting, with sparkling bokeh and lens flares emphasizing the crisp, cold, and refreshing atmosphere of a perfect summer day.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="E-commerce Main Image - Summer Beach Beverage Commercial Shot - Image 1">
</div>

#### 📌 Details

- **Author:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **Source:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **Published:** April 18, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14023)**

---

### No. 116: E-commerce Main Image - 4-Panel Advertising Grid Concept

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a 2x2 grid of distinct Japanese advertisements covering the skincare, food, travel, and tech industries.

#### 📝 Prompt

```
{
  "type": "2x2 advertising banner grid",
  "layout": "4 distinct quadrants, each featuring a different industry advertisement",
  "quadrants": [
    {
      "position": "top-left",
      "industry": "skincare",
      "visuals": "Asian woman touching cheek, floating water droplets, white pump bottle",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "透明感あふれる、新しいわたしへ。",
        "features_count": 3,
        "features_labels": ["高保湿", "肌荒れ予防", "美白ケア*"]
      }
    },
    {
      "position": "top-right",
      "industry": "restaurant food",
      "visuals": "close-up of spaghetti bolognese with grated cheese and parsley, dark moody lighting",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "期間限定",
        "description": "黒毛和牛のボロネーゼ 〜トリュフの香り〜"
      }
    },
    {
      "position": "bottom-left",
      "industry": "travel",
      "visuals": "woman with backpack facing a scenic mountain lake, bright daylight",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "自然の中で、心が動き出す。",
        "script": "Find your freedom.",
        "banner_details": ["初夏の特別キャンペーン", "6.1 SAT - 6.30 SUN", "最大 20%OFF", "今だけの特別プラン多数！"]
      }
    },
    {
      "position": "bottom-right",
      "industry": "SaaS app",
      "visuals": "smartphone displaying a task management app interface with 4 schedule items",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "1日を、デザインしよう。",
        "features_count": 3,
        "features_labels": ["直感的な操作性", "チームで共有可能", "どこでもアクセス"],
        "bottom_banner": "7日間無料トライアル実施中！"
      }
    }
  ]
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="E-commerce Main Image - 4-Panel Advertising Grid Concept - Image 1">
</div>

#### 📌 Details

- **Author:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **Source:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **Published:** April 18, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13928)**

---

### No. 117: E-commerce Main Image - E-commerce Livestream UI Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a highly detailed Chinese e-commerce livestream interface featuring a presenter, product boxes, live chat, and promotional overlays.

#### 📝 Prompt

```
{
  "type": "e-commerce livestream screenshot mockup",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"Caucasian male resembling Sam Altman\"}",
    "clothing": "dark green crewneck sweater",
    "action": "holding a black product box in one hand and pointing at it with the other",
    "setting": "dark studio with a microphone on the left, faint 'AI' text in the background",
    "props": [
      "black mug with white OpenAI logo",
      "stack of 4 black product boxes on the right"
    ]
  },
  "product_design": {
    "box_color": "black",
    "logo": "orange asterisk or sunburst",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Anthropic 官方旗舰店",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"更强推理·更高智能\"}",
      "sub_subtitle": "最强大模型: Opus 4.7 重磅发布!",
      "bullet_points_count": 3,
      "bullet_points": ["超强推理能力", "代码能力巅峰", "复杂任务轻松搞定"]
    },
    "top_right_live_status": {
      "viewer_info": "直播中 | 52.8万人观看",
      "promo_banner": "直播专属福利 限时折扣·错过不再有",
      "countdown": "倒计时 00:09:47"
    },
    "middle_right_price_card": {
      "header": "{argument name=\"product name\" default=\"Claude Opus 4.7\"} 直播间专享价",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/百万tokens起",
      "original_price": "原价: ¥1.89",
      "button": "立即抢购"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "说点什么..."
    },
    "bottom_right_banner": {
      "headline": "奥特曼首推！认准Claude Opus 4.7",
      "subheadline": "更智能 · 更安全 · 更可靠",
      "feature_tags_count": 4,
      "feature_tags": ["强大推理", "代码神器", "安全可靠", "极速响应"]
    },
    "floating_elements": [
      {
        "type": "sticker",
        "position": "middle right over product boxes",
        "text": "{argument name=\"sticker text\" default=\"史上最强 AI模型!\"}"
      }
    ]
  }
}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="E-commerce Main Image - E-commerce Livestream UI Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [程序员Left](https://x.com/coder_left)
- **Source:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **Published:** April 18, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13995)**

---

### No. 118: E-commerce Main Image - Herbal Chicken Soup Label Transformation

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Transforms a promotional chicken poster into a detailed product label with a basket of specific herbal ingredients and instructional text.

#### 📝 Prompt

```
Using REFERENCE_0 as the base style and preserving the central chicken illustration, transform the image into a product packaging label for a herbal soup mix. Shift the chicken to the right side. Replace the top text with a large, bold black brush-stroke headline {argument name="main headline" default="元气祛湿 鸡煲汤包"} and a smaller subtitle {argument name="subtitle" default="吃山林土货 味道当然好!"}. On the left side, add a new woven basket containing exactly 6 distinct piles of ingredients: woody root sticks, white square cubes, round sliced brown roots, yellow soybeans, dried orange peel strips, and dark red dates. Attach 6 small brown rectangular labels with white text to these ingredients. Below the chicken, add a circular orange badge containing the text {argument name="ingredients list" default="内含有:五指毛桃、茯苓、土茯苓、黄豆、陈皮、红枣"}. At the bottom, create a solid orange rectangular banner featuring a cooking pot icon, the text {argument name="usage instructions" default="用法:把汤料清洗干净放入锅中，加入姜片煮20分钟，后加入鸡肉再煮20分钟即可。"}, and a secondary slogan {argument name="bottom slogan" default="天然好料 滋补好汤"}.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="E-commerce Main Image - Herbal Chicken Soup Label Transformation - Image 1">
</div>

#### 📌 Details

- **Author:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **Source:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **Published:** April 18, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=13993)**

---

### No. 119: E-commerce Main Image - Sports Car and Airliner in Hangar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a photorealistic image of a sports car parked in front of a commercial airliner inside a reflective hangar.

#### 📝 Prompt

```
A photorealistic, high-resolution commercial photograph of a {argument name="car model and color" default="bright blue Alpine A110 R sports car"} parked in the foreground inside a massive aircraft hangar. The car features a black carbon fiber hood, black roof, black alloy wheels, and a front license plate reading "{argument name="license plate text" default="A110 R"}". Directly behind the car, dominating the background, is a {argument name="airplane model" default="white Airbus A320 commercial airliner"} with a blue tail. The hangar has a highly polished, reflective concrete floor that mirrors the car and plane. To the left, a sign on the metal wall reads "{argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"}". The hangar doors are wide open, revealing a bright, overcast sky and a distant cityscape. The lighting is soft and cinematic, highlighting the sleek aerodynamic curves of both vehicles.
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="E-commerce Main Image - Sports Car and Airliner in Hangar - Image 1">
</div>

#### 📌 Details

- **Author:** [nazca alwave](https://x.com/AlwaveNazca)
- **Source:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **Published:** April 18, 2026
- **Languages:** en

**[👉 Try it now →](https://gptimage2api.net/?id=14043)**

---

### No. 120: E-commerce Main Image - Realistic VTuber Merchandise Mockup

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A prompt for GPT-Image2 to generate realistic live-action photographs of standard VTuber fan goods.

#### 📝 Prompt

```
Create {argument name="items" default="fan goods"} for a standard {argument name="character type" default="Vtuber"} in {argument name="style" default="live-action"}
```

#### 🖼️ Generated Images

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="E-commerce Main Image - Realistic VTuber Merchandise Mockup - Image 1">
</div>

#### 📌 Details

- **Author:** [WTR](https://x.com/wtry1102)
- **Source:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **Published:** April 17, 2026
- **Languages:** ja

**[👉 Try it now →](https://gptimage2api.net/?id=13868)**

