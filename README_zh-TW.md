
# 🚀 GPT Image 2 提示詞大全


> 🎨 OpenAI GPT Image 2 創意提示詞精選集合

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Current-brightgreen)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Click%20to%20View-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 目錄

- [🤔 什麼是 GPT Image 2？](#-what-is-gpt-image-2)
- [📊 統計數據](#-statistics)
- [🔥 精選提示詞](#-featured-prompts)
- [📋 所有提示詞](#-all-prompts)

---

## 🤔 什麼是 GPT Image 2？

**GPT Image 2**（代號 **"duct-tape"**）是 OpenAI 下一代圖像生成模型。社群測試回饋它在以下方面實現了質的飛躍：

- 🎯 **像素級文字渲染** — 中文、英文、日文均達到 native 水準，無錯字、無字形扭曲
- 🎨 **跨圖像素級一致性** — 同一角色、風格、IP 在多張圖間保持像素級一致
- ⚡ **商用級插畫質量** — 插畫風格輸出無需人工精修，即可直接用於商業場景
- 🌈 **真實藝術風格注入** — 不止是「模仿參考圖」，而是真正理解並再現藝術風格的靈魂
- 🔧 **故事板與產品系列** — 適合故事板、IP 形象、產品系列圖等需要多圖一致性的場景
- 📐 **多語言平面設計** — 社交卡片、Banner、海報一次生圖即可完成多語言文字排版

📚 **了解更多：** 查看社群測試 [報告要點](docs/FAQ.md)

### 🚀 Raycast 集成

部分提示詞支持使用 [Raycast Snippets](https://raycast.com/help/snippets) 語法的**動態參數**。尋找 🚀 Raycast Friendly 徽章！

**示例：**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

在 Raycast 中使用時，您可以動態替換參數以快速迭代！

---

## 📊 統計數據

<div align="center">

| 指標 | 數量 |
|--------|-------|
| 📝 提示詞總數 | **1123** |
| ⭐ 精選 | **6** |
| 🔄 最後更新 | **2026年4月23日 星期四 凌晨1:28:37 [UTC]** |

</div>

---

## 🔥 精選提示詞

> ⭐ 由我們的團隊精心挑選，具有卓越的質量和創造力

### No. 1: VR 頭戴裝置爆炸圖海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一張高科技 VR 頭戴裝置爆炸圖，包含詳細的組件標註與宣傳文案。

#### 📝 提示詞

```
{
  "type": "產品爆炸圖海報",
  "subject": "VR 頭戴裝置",
  "style": "簡潔的高科技 3D 渲染，攝影棚燈光，發光細節",
  "background": "{argument name=\"background color\" default=\"柔和的紫藍色漸層\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"以全新的結構，定義全新的現實。\"}"
  },
  "layout": {
    "centerpiece": "垂直堆疊的 VR 頭戴裝置爆炸圖，展示 9 個不同的內部組件層：外殼、攝影機感測器、主機板與晶片、Pancake 透鏡、內部框架、電池組、側邊頭帶、頂部頭帶以及面部襯墊。",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\n以強大的處理效能，實現即時體驗。",
        "可調式 IPD 機構\n為廣大用戶提供舒適的配戴感。",
        "精密設計頭帶\n追求舒適與穩定性的工學設計。"
      ],
      "right_side": [
        "前飾板\n洗鍊的設計與最佳的重量平衡。",
        "追蹤攝影機\n實現高精度的位置追蹤與環境感知。",
        "Pancake 透鏡\n輕薄設計，提供寬廣視野與清晰影像。",
        "高效能電池\n支援長時間運作的最佳化電源設計。",
        "柔軟面部襯墊\n即使長時間配戴也能保持舒適。"
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "{argument name=\"bottom headline\" default=\"體驗，從結構進化。\"}",
        "body": "每一個零件都蘊含著支撐沉浸式體驗的尖端科技與匠心設計。Meta Quest 3 從內部結構開始，為您創造感受未來的體驗。"
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="VR 頭戴裝置爆炸圖海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [wory＠ホッピング中](https://x.com/wory37303852)
- **來源:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13460)**

---

### No. 2: 手繪城市美食地圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一張手繪水彩風格的旅遊地圖，包含編號的在地特色美食、地標以及圖例。

#### 📝 提示詞

```
{
  "type": "手繪地圖資訊圖表",
  "style": "{argument name=\"art style\" default=\"復古羊皮紙上的水彩與墨水手繪插圖\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"成都\"} {argument name=\"map title\" default=\"吃貨暴走地圖\"}",
    "mascot": "戴著太陽眼鏡並比讚的卡通紅辣椒"
  },
  "border": "{argument name=\"border decoration\" default=\"綠葉與紅辣椒藤蔓\"}",
  "layout": {
    "background": "帶有黃色道路、藍色河流與綠色公園區域的質感米色羊皮紙",
    "sections": [
      {
        "title": "地標",
        "count": 6,
        "illustrations": ["傳統涼亭", "傳統寺院", "攀爬著熊貓的現代摩天大樓", "高聳電視塔", "傳統牌樓", "工業建築"],
        "labels": ["人民公園", "文殊院", "IFS", "339電視塔", "寬窄巷子", "東郊記憶"]
      },
      {
        "title": "美食景點",
        "count": 12,
        "illustrations": ["麻婆豆腐", "紅油水餃", "串串香", "三大炮", "蛋烘糕", "九宮格火鍋", "肥腸粉", "缽缽雞", "冒椒火辣", "蓋碗茶", "冰粉", "雙流老媽兔頭"],
        "labels": ["1 陳麻婆豆腐", "2 鍾水餃", "3 春熙路", "4 寬窄巷子·三大炮", "5 建設路·葉婆婆蛋烘糕", "6 玉林路·小龍坎火鍋", "7 香香巷·肥腸粉", "8 武侯祠大街·缽缽雞", "9 東郊記憶·冒椒火辣", "10 人民公園·鶴鳴茶社", "11 錦里古街·冰粉", "12 雙流老媽兔頭"]
      },
      {
        "title": "圖例",
        "position": "右下角",
        "count": 5,
        "items": ["紅點", "綠色房屋", "綠樹", "藍線", "黃色雙線"],
        "labels": ["美食地點", "地標景點", "公園綠地", "河流湖泊", "主要道路"]
      }
    ],
    "centerpiece": "坐著吃竹子的巨型熊貓",
    "bottom_right_extras": ["帶有 N、S、E、W 的復古羅盤玫瑰", "免責聲明文字『溫馨提示：吃辣需謹慎，腸胃要保護~』並附帶一個紅辣椒圖示"]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="手繪城市美食地圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [皮皮特](https://x.com/mm_zzm44854)
- **來源:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13515)**

---

### No. 3: 採用混合風格的桃太郎說明用 Slides

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個結合了「いらすとや (Irasutoya)」插圖簡約溫暖的美學，以及日本政府簡報高資訊密度特徵的提示詞。

#### 📝 提示詞

```
請為 {argument name="theme" default="桃太郎"} 製作一張說明用 Slides ({argument name="format" default="ポンチ絵 (ponchi-e) 圖表"})，將「いらすとや (Irasutoya)」的溫和氛圍與「霞關風格 (Kasumigaseki slides)」那種壓倒性的資訊密度融合在一起。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="採用混合風格的桃太郎說明用 Slides - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="採用混合風格的桃太郎說明用 Slides - Image 2">
</div>

#### 📌 詳情

- **作者:** [やまもん](https://x.com/yammamon)
- **來源:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **發布時間:** 2026年4月19日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13983)**

---

### No. 4: 電子商務直播 UI 模型

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成逼真的社群媒體直播介面並疊加在肖像上，包含可自訂的聊天訊息、禮物彈出視窗以及商品購買卡片。

#### 📝 提示詞

```
{
  "type": "直播 UI 模型",
  "subject": {
    "description": "{argument name=\"host name\" default=\"Elon Musk\"} 的肖像，微笑，穿著印有白色技術示意圖的黑色 T 恤",
    "background": "左側顯示帶有 '{argument name=\"left background logo\" default=\"SPACEX\"}' 文字的螢幕，右側顯示紅色的 '{argument name=\"right background logo\" default=\"Tesla T logo\"}' 和一輛深色汽車"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "頭像，名稱 '{argument name=\"host name\" default=\"Elon Musk\"}'，副標題 '55.6 萬本場點讚'，紅色 '關注' 按鈕",
      "rank_badge": "帶有 '全站第 1 名' 的金幣圖示",
      "viewer_stats": "3 個頂級觀眾頭像，分別顯示 '12.3w'、'8.6w'、'5.7w'，總計 '68.7 萬'，'X' 關閉按鈕",
      "right_links": "'更多直播 >'，'禮物展館 0/24' 帶有藍色 '經典' 標籤"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "頭像 '科技愛好者'，'送小心心'，愛心圖示 x 1314",
        "頭像 '星辰大海'，'送火箭'，火箭圖示 x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "等級 37 徽章 '宇宙漫遊者 加入了直播間'",
      "message_count": 7,
      "messages": [
        "小火箭: 馬斯克！未來可期！🚀",
        "future: 特斯拉 Model 2 什麼時候出？",
        "星空夢想家: SpaceX 今年能上火星嗎？",
        "AI 探索者: Neuralink 進展如何？",
        "帥氣的網友: 馬總好！",
        "Mars: 第一次來你的直播，超激動！",
        "用戶 123: 講講 AI 吧，會取代人類嗎？"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "橘色 '熱賣 x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"特斯拉 Cybertruck 電動皮卡\"}",
      "price": "{argument name=\"product price\" default=\"¥ 1,618,000\"}",
      "button": "紅色 '搶' 按鈕",
      "floating_animation": "半透明愛心沿著右側邊緣向上飄浮"
    },
    "bottom_bar": {
      "input_field": "'說點什麼...'",
      "icons": ["笑臉", "三個點", "購物車", "禮物盒", "分享"]
    }
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="電子商務直播 UI 模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [神经病不想好转](https://x.com/sjbbxhz)
- **來源:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14036)**

---

### No. 5: 動漫武術對決

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一個動態的動漫風格動作場景，描繪兩名角色在傳統道場中伴隨元素光環進行戰鬥。

#### 📝 提示詞

```
一張極具動態感的動漫插圖，描繪兩名少女在傳統木造道場內進行激烈的武術對決。在前景中，一名留著 {argument name="character 1 hair" default="黑色高包頭配紅色髮帶"} 的少女擺出強而有力的低位武術架勢，奮力向前揮拳。她身穿 {argument name="character 1 outfit" default="白色中式上衣配紅色流蘇與寬鬆紅褲"}，強烈的紅色能量斬擊環繞著她揮動的四肢。在右側半空中，一名留著 {argument name="character 2 hair" default="淺紫色雙包頭"} 的少女優雅地躍起，自信地微笑著，身穿 {argument name="character 2 outfit" default="深綠色刺繡金邊洋裝與黑色緊身褲"}，伴隨著如水流般掃過的藍色能量軌跡。背景為古樸的木造寺廟內部，上方懸掛著一塊顯眼的招牌，寫著「{argument name="sign text" default="武術会"}」。場景充滿了爆炸性的動作張力、飛揚的塵土、碎裂的木質地板、閃耀的彩色粒子特效，以及將角色與細緻背景完美區隔的戲劇性低角度光影。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="動漫武術對決 - Image 1">
</div>

#### 📌 詳情

- **作者:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **來源:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13467)**

---

### No. 6: 3D 石階演化資訊圖表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

將平面的演化時間軸轉換為逼真的 3D 石階資訊圖表，包含細緻的生物渲染圖與結構化的側邊欄。

#### 📝 提示詞

```
{
  "type": "演化時間軸資訊圖表",
  "instruction": "以 REFERENCE_0 作為結構基礎，將平面向量設計轉換為高度逼真的 3D 資訊圖表。將平滑的坡道替換為層次分明的石階，並將所有生物升級為照片級的 3D 模型。",
  "style": {
    "background": "{argument name=\"background style\" default=\"復古紋理羊皮紙\"}",
    "staircase": "{argument name=\"staircase material\" default=\"逼真的紋理石塊\"}",
    "subjects": "{argument name=\"organism style\" default=\"高度細緻的照片級 3D 渲染圖\"}"
  },
  "layout": {
    "main_title": "{argument name=\"main title\" default=\"人類演化\"}",
    "sections": [
      {
        "position": "左側邊欄",
        "count": 8,
        "labels": ["L0: 單細胞生命", "L1: 多細胞生物", "L2: 動物界", "L3: 脊索動物", "L4: 上陸革命", "L5: 哺乳綱", "L6: 人科演化", "L7: 智人紀元"]
      },
      {
        "position": "右上角",
        "title": "獲得的功能 / 失去的功能",
        "description": "帶有加號與減號圖示的圖例"
      },
      {
        "position": "底部中央",
        "title": "演化關鍵里程碑",
        "count": 6,
        "description": "包含 6 個展示猿類到人類演化剪影圖的時間軸"
      }
    ],
    "centerpiece": {
      "description": "蜿蜒的石階，共有 25 個編號階梯，展示特定生物。",
      "count": 25,
      "notable_elements": [
        "第 07 階：水母",
        "第 09 階：菊石",
        "第 10 階：三葉蟲",
        "第 24 階：直立行走的人類",
        "第 25 階：{argument name=\"future evolution concept\" default=\"帶有問號的發光宇宙剪影\"}"
      ]
    }
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="3D 石階演化資訊圖表 - Image 1">
</div>

#### 📌 詳情

- **作者:** [知识猫图解](https://x.com/GeekCatX)
- **來源:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13491)**

---

## 📋 所有提示詞

> 📝 按發布日期排序（最新優先）

### No. 1: 個人檔案 / 頭像 - 俯視視角的誇張姿勢鏡面自拍

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於測試角色一致性與動態表情的提示詞，場景為從俯視角度拍攝的鏡面自拍。

#### 📝 提示詞

```
{argument name="number of people" default="三人"} 在鏡子前，以俯視視角拍攝 {argument name="pose type" default="誇張姿勢"} 的團體照。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="個人檔案 / 頭像 - 俯視視角的誇張姿勢鏡面自拍 - Image 1">
</div>

#### 📌 詳情

- **作者:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **來源:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **發布時間:** 2026年4月22日
- **多語言:** zh

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14341)**

---

### No. 2: 個人檔案 / 頭像 - 棕色單色調室內坐姿肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實風格的室內時尚肖像，呈現一位身著棕色系套裝的女性，適用於編輯類生活風格或服飾影像。

#### 📝 提示詞

```
一張寫實的攝影棚肖像，主角為一位坐在簡約黑色摺疊椅上的年輕東亞女性，採用垂直構圖，取景範圍從大腿上部至頭部。她留著 {argument name="hair color" default="深棕色"} 的頭髮，中分並紮成低馬尾，耳際留有幾縷柔和髮絲，佩戴精緻小巧的耳環，皮膚白皙細膩，姿勢平靜自然，雙手交疊置於膝間。她身穿一件 {argument name="top color" default="深巧克力棕色"} 的羅紋拉鍊短版上衣，配有尖領與七分袖，拉鍊微開形成深領口，下身搭配同色系 {argument name="pants color" default="暖棕色"} 的高腰直筒褲。整體造型為棕色系單色調，呈現細膩的布料質感與自然的身形輪廓。背景為帶有柔和褶皺的米白色布幕，光線採用柔和的自然窗光，營造出乾淨、柔和的室內編輯風格。寫實攝影、淺景深、柔和陰影、低調時尚肖像、極簡佈景、主體置中、放鬆坐姿、高細節皮膚與布料紋理。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="個人檔案 / 頭像 - 棕色單色調室內坐姿肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **來源:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14628)**

---

### No. 3: 個人檔案 / 頭像 - 超寫實校服神社人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張精緻、超寫實的年輕女性戶外校服人像，非常適合用於時尚編輯、角色視覺設計或生活風格的 AI 人像創作。

#### 📝 提示詞

```
一張超寫實的半身人像，主角為 {argument name="subject" default="年輕女性"}，站在戶外明亮的自然陽光下，採用直式構圖。她留著一頭柔順的 {argument name="hair color" default="深棕色"} 長直髮，髮絲帶有光澤，中分偏旁並垂落在雙肩。她穿著一件挺括的白色短袖校服襯衫，搭配立體領口、海軍藍條紋領帶，左胸口袋上有精緻的刺繡徽章，圖案包含皇冠與紋章。讓她以略微側身的角度站立，姿勢放鬆，頭部微微轉向一側，營造出精緻且自然的時尚攝影感。背景設置於生動的 {argument name="background setting" default="紅色神社建築"} 前，模糊的背景中可見濃郁的紅色柱子與藍色弧形屋頂細節，運用淺景深與柔和的散景效果，使主角保持清晰對焦。光線應乾淨且對比鮮明，呈現出迷人的質感，頭髮與襯衫上有明亮的高光，布料褶皺真實，膚色自然，整體呈現出日系商業攝影般精緻的高級人像美感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="個人檔案 / 頭像 - 超寫實校服神社人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [AIおじさん](https://x.com/AIojisan1952)
- **來源:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14515)**

---

### No. 4: 個人檔案 / 頭像 - 憂鬱風格遮擋室內自拍肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張年輕男子穿著深色開領襯衫、於窗邊拍攝的寫實風格自拍，適合用於製作真實感十足的社群媒體肖像照。

#### 📝 提示詞

```
一張寫實的室內自拍風格肖像，拍攝對象為一名年輕東亞男子，半身構圖，坐在高層公寓或飯店房間的大型現代化窗戶旁，沐浴在柔和的日光下。他留著 {argument name="hair color" default="black"} 髮色，頭髮濃密且略顯凌亂，中分造型，額頭與兩側帶有蓬鬆感。體型偏瘦，頸部修長，膚色白皙平滑。他穿著一件 {argument name="shirt color" default="black"} 的霧面棉質或府綢襯衫，版型略寬，上方幾顆鈕扣解開，呈現深開領與休閒放鬆的風格。相機以自然的自拍角度近距離拍攝，直式構圖，涵蓋肩膀、胸部、頸部與頭部。他的臉部被一個置中的大型矩形模糊或馬賽克遮擋塊完全遮住，但耳朵、下顎線邊緣、頸部與頭髮清晰可見。整體氛圍低調、憂鬱且優雅，色調柔和中性，右側透入柔和的窗光，陰影細膩，帶有隨性的社群媒體自拍感。背景細節包括左側的一面米色牆面、一個小型深色牆面控制面板、一條垂直金屬飾條或燈具邊緣，以及右側兩扇高大的深色邊框窗戶，窗外可見模糊的城市天際線。寫實智慧型手機攝影，簡約現代室內設計，淺景深，自然的皮膚紋理，細膩的對比度，因遮擋塊而無法看見笑容，極簡修圖，時尚且真實的個人自拍。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="個人檔案 / 頭像 - 憂鬱風格遮擋室內自拍肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [MathMedix](https://x.com/MathMedix)
- **來源:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14686)**

---

### No. 5: 個人檔案 / 頭像 - 逼真的麥當勞自拍肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張在麥當勞內拍攝的逼真休閒自拍，適用於製作真實感十足的社群媒體風格餐廳快照。

#### 📝 提示詞

```
一張在亞洲麥當勞餐廳室內拍攝的高度逼真休閒手機自拍，構圖為一名年輕男子坐在桌前的半身肖像。相機以手臂長度從略高於桌面處拍攝，呈現出自然的正面自拍視角，一隻前臂向鏡頭延伸。主角身穿黑色 T 恤，左胸前印有白色 Tesla 小標誌，留著黑色短直髮，隱約可見細黑鏡框，一隻手輕托下巴，姿勢放鬆。他的臉部被中央一個大型實心矩形模糊塊完全遮蓋，在保護隱私的同時，保留了頭髮、耳朵、下顎線邊緣和眼鏡腳架的可見度。左下角前景處放置了 1 個帶蓋和白色吸管的白色麥當勞紙杯，被畫面裁切。背景展示了餐廳櫃檯區域，燈光溫暖，左側有 1 面大型紅色牆板，上面印有黃色的麥當勞拱門標誌和白色標語「i’m lovin’ it」以及下方的中文文字；上方有 4 個發光的數位菜單專案，顯示著漢堡、薯條、套餐、價格和中文文字；背景櫃檯附近還有 2 個人，一人背對鏡頭並揹著背包，另一人則在收銀台後方隱約可見。請使用自然的色彩平衡、輕微的室內顆粒感、逼真的反射效果、淺至中等的景深，並呈現出未經刻意安排的社群媒體快照感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="個人檔案 / 頭像 - 逼真的麥當勞自拍肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [AB Kuai.Dong](https://x.com/_FORAB)
- **來源:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14433)**

---

### No. 6: 個人檔案 / 頭像 - Albedo Cosplay Instagram 快照

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於生成叛逆且富有表現力的 Instagram 限時動態風格 Cosplay 照片的簡潔提示詞。

#### 📝 提示詞

```
風格：一張 {argument name="character" default="Albedo"} Cosplay 的 Instagram 限時動態快照；內容：{argument name="action" default="蹲在地上面向鏡頭，雙手比出誇張的叛逆手勢，翻著白眼，表情傲慢且不屑"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="個人檔案 / 頭像 - Albedo Cosplay Instagram 快照 - Image 1">
</div>

#### 📌 詳情

- **作者:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **來源:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **發布時間:** 2026年4月21日
- **多語言:** zh

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14347)**

---

### No. 7: 個人檔案 / 頭像 - 夕陽下的貓耳少女校園天台動漫風格

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一張電影感十足的動漫風格校園天台肖像，描繪了夕陽下的貓耳女學生，非常適合作為懷舊風格的關鍵視覺圖、角色藝術或社群媒體展示圖。

#### 📝 提示詞

```
一張高品質的動漫插畫，主角為一位 {argument name="character type" default="貓耳女學生"}，她正從金屬校園天台欄杆處向前傾身，採用略微仰視的近距離四分之三視角。她擁有一頭飄逸的 {argument name="hair color" default="深棕色"} 長髮，帶有柔和的高光，一雙大而明亮的灰棕色眼眸，戴著圓形細框眼鏡，髮間露出兩隻毛茸茸的貓耳。她的表情安靜、若有所思且帶有一絲羞澀，雙唇微啟，溫柔地向下俯視著觀者。她身穿日本水手校服，上衣為柔和的 {argument name="uniform color" default="粉紅色"} 長袖，搭配灰色水手領與白色條紋，領口繫著鮮豔的紅色領巾蝴蝶結，隱約可見格紋裙，雙肩背著深色背包肩帶。場景沐浴在戲劇性的黃金時刻逆光中，髮絲、耳朵、肩膀與袖口邊緣泛著強烈的暖色輪廓光，左下方透出耀眼的太陽光暈，背景是色彩豐富、佈滿橘色與桃色雲彩的天空。背景呈現出一棟兩層樓高的日式校舍，屋頂為紅瓦，窗戶在夕陽照射下閃爍著光芒。強調懷舊的 2000 年代初期高階動漫關鍵視覺品質，細膩的線條、明亮的雙眼、精緻的髮絲細節、電影級構圖、柔和的景深、鮮豔的暖色調、精緻的陰影處理，以及寧靜感人的氛圍。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="個人檔案 / 頭像 - 夕陽下的貓耳少女校園天台動漫風格 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **來源:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14547)**

---

### No. 8: 個人檔案 / 頭像 - 奇幻女子擁抱白公羊

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實的中世紀奇幻風格肖像，描繪一名紅髮女子擁抱一隻長角的白公羊，非常適合用於氛圍感角色藝術或編輯風格的奇幻視覺圖。

#### 📝 提示詞

```
一張寫實、電影感十足的直式肖像，主角為一名中世紀或奇幻風格的女子，擁有 {argument name="hair color" default="長長的銅紅色頭髮"}，半身構圖，正溫柔地擁抱著一隻大型白公羊。女子身穿深苔綠色的羊毛連身裙或束腰外衣，袖口有華麗的刺繡，肩上披著厚重的毛皮邊飾斗篷或披肩，呈現出維京或高地風格。她的頭髮濃密且呈波浪狀，略顯凌亂，頭頂編織著小辮子。公羊擁有濃密捲曲的奶油白色羊毛，表情平靜且閉著雙眼，頭上長著向外及向前捲曲的顯眼螺旋角。女子的手溫柔地放在公羊頸部，傳達出溫暖、保護與陪伴的意境。場景設定在戶外崎嶇、陰天的荒野中，背景為柔焦的山丘或荒地，天空呈冷灰色，淺景深，自然漫射光，頭髮、羊毛、皮草與布料的紋理細節豐富，色調為大地色系，構圖親密，皮膚與動物特徵寫實。在左上角加入黑色文字，內容為 {argument name="corner text" default="GPT Image 2"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="個人檔案 / 頭像 - 奇幻女子擁抱白公羊 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **來源:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14619)**

---

### No. 9: 個人檔案 / 頭像 - 粉色可愛偶像口紅肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成閃耀的動漫偶像風格肖像，適用於海報、社群媒體藝術或可愛角色主視覺。

#### 📝 提示詞

```
一張高度細緻、充滿光澤的動漫偶像肖像，採用垂直構圖，呈現一位可愛的少女半身像，展現夢幻般的粉色可愛（Kawaii）美學。她擁有 {argument name="hair color" default="粉蠟色"} 的頭髮，造型為極長的蓬鬆高馬尾，搭配柔軟的瀏海與流動的捲髮，並裝飾著多個小愛心髮夾與交叉髮夾。她的眼睛又大又閃亮，呈現生動的 {argument name="eye color" default="翡翠綠"}，帶有星形高光、長睫毛與微微濕潤的光澤。她有著柔和的腮紅、精緻光澤的雙唇，表情充滿愛意，正用雙手輕柔地拿著口紅管在嘴邊塗抹 {argument name="lipstick color" default="亮粉色"} 口紅。她穿著一件帶有蕾絲、緞帶、蝴蝶結、愛心裝飾與閃亮質感的黑粉色哥德蘿莉塔偶像服，並配戴 1 個帶有粉色寶石愛心的黑色蕾絲蝴蝶結髮箍、瀏海上有 3 個顯眼的髮飾、1 對垂墜愛心耳環，以及 1 個帶有小愛心吊飾的黑色頸圈。角色周圍環繞著發光、充滿亮片的糖果粉色背景，充滿散景、閃光、柔和霓虹燈光效果與偶像粉絲氛圍。在周圍添加 5 個發光的手繪日文愛心對話框，內容為：「かわいすぎてごめん…♡」、「推してくれてありがとうっ♡」、「ずーっとだいすきっ♡」、「世界でいちばんの推しになってね…♡」以及「ずっと一緒だよ？約束ね…♡」。在右上角背景處包含一張該女孩的小型裝飾照片卡或海報。超精緻插畫、密集閃光、浪漫燈光、光澤高光、複雜蕾絲細節、柔焦背景、飽和粉色調，呈現可愛的偶像海報質感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="個人檔案 / 頭像 - 粉色可愛偶像口紅肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ねね*AIcreator](https://x.com/NeneneAI)
- **來源:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14606)**

---

### No. 10: 個人檔案 / 頭像 - 極簡鵜鶘騎自行車

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張鵜鶘騎自行車的稀疏幾何向量插圖，適用於測試簡單的形狀構成，或創作趣味十足的抽象圖示風格圖像。

#### 📝 提示詞

```
一張極簡向量風格插圖，背景為平坦的淺灰色，呈現一隻鵜鶘騎著自行車的畫面。圖案由簡單的幾何形狀構成，並帶有深炭色的粗輪廓線。構圖寬闊且置中，自行車佔據畫面下方三分之二，鳥頭刻意以抽象、類似圖表的方式懸浮在車把前方稍上方。自行車為簡單的黑色公路車側視剪影，具有 2 個大輪子，每個輪子都有厚實的外框，並有 4 條明顯的輻條線形成十字交叉；輪子下方有一條水平直線作為地面，車架呈三角形，配有短黑色坐墊，車架後方有簡化的曲柄與踏板細節。鵜鶘由乾淨的抽象部件構成：白色的圓形頭部配有一個黑色小圓眼；向左張開的長喙由兩部分組成，上方為橘色三角形，下方為淡粉色囊袋；頭頂有一道短深色曲線；頸部與身體連接處有一個獨立的小白色橢圓；身體為較大的白色圓形，位於自行車上方；背部上方有一個向上傾斜的白色翅膀形狀。加入 2 個橘色腿部形狀，為從身體向下延伸至自行車架的長窄矩形，暗示鳥兒正在踩踏板。保持形狀刻意稀疏且帶有超現實感，如同標誌測試或簡單的程式碼編輯器塗鴉，無陰影、無漸層、無紋理、無文字，並保留大量的留白。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="個人檔案 / 頭像 - 極簡鵜鶘騎自行車 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Justin Schroeder](https://x.com/jpschroeder)
- **來源:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14657)**

---

### No. 11: 個人檔案 / 頭像 - 貓咪轉化為人類肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可將貓咪參考照片轉換為寫實的人類肖像，同時保留原始的姿勢、構圖與場景，打造趣味十足的「寵物變人」肖像照。

#### 📝 提示詞

```
使用提供的參考圖像，將貓咪轉化為寫實的人類肖像，同時保留相同的慵懶姿勢、攝影角度、構圖，以及相同的毛絨綠松石色椅子背景。將貓咪的橘白毛色作為人類造型的靈感來源：將人物設定為一位皮膚白皙的年輕女性，擁有一頭溫暖的薑黃色頭髮，表情柔和且平靜。讓她穿著舒適的米白色居家服：一件寬鬆的針織 V 領毛衣和一條奶油色抽繩長褲，以放鬆的肢體語言自然地坐在椅子上。呈現出寫實風格、柔和的室內自然光，以及雜誌生活風格照片的質感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="個人檔案 / 頭像 - 貓咪轉化為人類肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Bojan Tunguz](https://x.com/tunguz)
- **來源:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14670)**

---

### No. 12: 個人檔案 / 頭像 - 手持草莓冰淇淋的攝影棚人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張精緻的明星風格攝影棚人像，畫面中一位深色頭髮的女性將草莓冰淇淋甜筒置於臉前，非常適合編輯美妝或流行文化類型的影像。

#### 📝 提示詞

```
一張精緻的攝影棚人像，拍攝一位充滿魅力的流行明星風格女性，畫面為胸部以上特寫，置中於平滑的中性灰色背景前。她留著 {argument name="hair color" default="漆黑"} 的長波浪捲髮，中分造型，髮絲帶有光澤感，蓬鬆柔軟地垂落在雙肩。她的臉部大部分被手中舉在嘴巴與下顎前的冰淇淋甜筒遮住，營造出俏皮的時尚編輯構圖。她穿著白色羅紋背心，肩帶寬闊，並佩戴著單邊顯眼的閃亮耳釘。她手中拿著 1 個華夫甜筒，上面有一大球粉紅色草莓冰淇淋，帶有深紅色莓果紋理與些微融化的質感。溫暖且修飾臉型的美妝光影，柔和的陰影，真實的膚色，高端明星人像攝影，手部、甜筒、頭髮與肩膀處對焦清晰，背景簡約，氛圍細膩性感且時髦，垂直裁切。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="個人檔案 / 頭像 - 手持草莓冰淇淋的攝影棚人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Arturo Garrido](https://x.com/arturogarrido)
- **來源:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14594)**

---

### No. 13: 個人檔案 / 頭像 - 點雲遮蔽肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張黑白雷射雷達（lidar）風格的肖像，由密集的白色粒子構成穿著西裝的男性形象，非常適合科技類編輯視覺、隱私主題或未來感的身分識別影像。

#### 📝 提示詞

```
一張極簡的單色肖像，完全由漆黑背景上數百萬個微小的白色點雲組成，呈現一名成年男性從胸部以上的半身像，穿著正式的深色西裝外套和淺色領口襯衫。主體略微偏右置中，面向前方並帶有細微的三分之二側轉，留著整齊的短髮，一隻清晰可見的耳朵由密集的雷射雷達式粒子精確勾勒。將人物渲染為原始 3D 掃描數據與拓撲輪廓邏輯的結合：超密集的點描法、精確的幾何點位排列、淡淡的等高線結構，以及在頭髮、西裝翻領、領口、頸部和肩部呈現清晰的深度塑形。臉部刻意以 1 個大型垂直長方形深灰色至黑色的遮蔽塊遮蓋，完美置中於從額頭到鼻下方的臉部區域，營造出強烈的隱私遮罩效果。使用霧面質感、清晰邊緣、銳利對焦、高對比度，無光暈、無溢光、無霓虹、無霧氣、無動態模糊、無色差、無繪畫筆觸。在右下角添加 1 個淺灰色的小型四角星形圖示。整體影像應具備數學感、鑑識感與未來感，如同 8k 高解析度的雷射雷達掃描肖像。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="個人檔案 / 頭像 - 點雲遮蔽肖像 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="個人檔案 / 頭像 - 點雲遮蔽肖像 - Image 2">
</div>

#### 📌 詳情

- **作者:** [Harshith](https://x.com/HarshithLucky3)
- **來源:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14408)**

---

### No. 14: 個人檔案 / 頭像 - 騎著獅子的希臘神祇

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個電影級的提示詞，用於生成一張史詩般的圖像，描繪一個人化身為希臘神祇，騎著獅子穿越非洲大草原的場景。

#### 📝 提示詞

```
讓我看起來像是一位 {argument name="persona" default="希臘神祇"}，騎著一頭 {argument name="mount" default="獅子"}，背景是在 {argument name="setting" default="非洲大草原"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="個人檔案 / 頭像 - 騎著獅子的希臘神祇 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="個人檔案 / 頭像 - 騎著獅子的希臘神祇 - Image 2">
</div>

#### 📌 詳情

- **作者:** [Max Blade](https://x.com/_MaxBlade)
- **來源:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14326)**

---

### No. 15: 個人檔案 / 頭像 - 困惑的金髮動漫少女肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張簡約的粉彩風格動漫半身像，描繪了一位穿著藍色毛衣的困惑少女，適合用於頭像、個人檔案圖片或休閒角色插畫。

#### 📝 提示詞

```
一張柔和、極簡風格的動漫半身肖像，描繪了一位可愛的年輕女性，背景為純淨的淺灰色。採用乾淨的粉彩風格繪製，線條細膩如素描，並搭配平塗的柔和色彩。她擁有長而飄逸的淺金色秀髮，層次感豐富，前額留有長瀏海，擁有一雙圓潤的淺藍色大眼、白皙的皮膚，微張的小嘴流露出淡淡的困惑。她穿著一件寬鬆的 {argument name="clothing color" default="淺粉藍色"} 長袖上衣，領口寬大舒適。她的姿勢略微側向觀眾，一隻手抬起，食指輕觸頭部側面，彷彿感到困惑。在頭部左上方放置 1 個懸浮的藍色問號。表情應顯得天真、心不在焉且討人喜歡。構圖需保持居中、通透且簡潔，不包含額外物件、複雜背景或強烈陰影。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="個人檔案 / 頭像 - 困惑的金髮動漫少女肖像 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="個人檔案 / 頭像 - 困惑的金髮動漫少女肖像 - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="個人檔案 / 頭像 - 困惑的金髮動漫少女肖像 - Image 3">
</div>

#### 📌 詳情

- **作者:** [Torishima / INTP](https://x.com/izutorishima)
- **來源:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14474)**

---

### No. 16: 個人檔案 / 頭像 - 柔和藍色動漫少女肖像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張極簡主義的粉彩動漫半身像，主角為身穿寬鬆淺藍色衛衣的藍髮少女，非常適合作為頭像、個人資料圖片或柔和風格的角色藝術。

#### 📝 提示詞

```
一張柔和動漫風格的半身肖像，可愛少女位於純色暖米白色背景中央，採用乾淨細膩的線條與平塗粉彩繪製。她擁有非常長的直髮，髮色為 {argument name="hair color" default="淡天藍色"}，髮絲輕盈，齊瀏海在中間略微分開，並配有一雙閃爍著光澤的藍色大眼睛。她的表情羞澀而困惑，眉頭微蹙，臉頰帶著淡淡的粉色紅暈，小嘴微張。她直視觀者，一根食指輕觸下唇，呈現出思考且猶豫的姿態。她身穿一件寬鬆的 {argument name="top color" default="淺藍色"} 衛衣，長袖遮住了部分手部。畫面取景自胸部以上，頭部微微傾斜，營造出溫柔、純真且夢幻的氛圍。採用極簡構圖，無飾品、無額外物件、無背景、無文字。強調單色藍調、輕盈簡約、細膩的素描感輪廓，以及適合柔和個人頭像的日系插畫美學。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="個人檔案 / 頭像 - 柔和藍色動漫少女肖像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Torishima / INTP](https://x.com/izutorishima)
- **來源:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14473)**

---

### No. 17: 個人檔案 / 頭像 - 奢華室內鏡面自拍人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張身穿象牙白修身連身裙的女性寫實風格時尚鏡面自拍，適用於生活方式、穿搭展示或社群媒體的精緻影像。

#### 📝 提示詞

```
一張寫實的室內鏡面自拍，主角是一位身材苗條、充滿魅力的年輕女性，站在光線柔和的高級客廳或飯店套房中，以垂直視角拍攝，畫面從頭部延伸至膝蓋下方。她穿著一件合身的奶油色或象牙白緊身中長裙，裙身帶有優雅的褶皺與抓皺設計，不對稱領口設計有一條肩帶斜跨胸前，露出另一側肩膀。她留著長長的深棕色波浪捲髮，中分髮型自然垂落在雙肩。她右手拿著智慧型手機對著牆上的鏡子自拍，手機部分遮住了臉部；手機殼為深色，印有紅色雲朵圖案。她的左臂自然垂在身側。添加細緻的飾品：一條帶有小墜飾的細項鍊、右手腕戴著一個銀色手環或手鐲，持手機的手指上戴著戒指。強調寫實的女性輪廓、平滑的肌膚、柔和溫暖的環境光，以及精緻的社群媒體編輯風格攝影。背景應包含她身後的一張米色沙發、沙發右側放著的一個棕色皮革手提包、鏡子區域後方的一面質感石材或混凝土裝飾牆，以及左側溫暖的走廊，牆上可見兩幅裝飾畫。運用自然的室內陰影、細膩的皮膚紋理、腰部與臀部周圍寫實的布料褶皺與壓縮感，呈現奢華公寓的美學氛圍、乾淨的構圖與高細節質感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="個人檔案 / 頭像 - 奢華室內鏡面自拍人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Danna R.](https://x.com/daaaaanc)
- **來源:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14421)**

---

### No. 18: 個人檔案 / 頭像 - 寫實風格白色連身裙鏡面自拍

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張在溫馨公寓室內拍攝的寫實時尚鏡面自拍，適用於穿搭展示、生活風格內容及真實感對比。

#### 📝 提示詞

```
一張寫實的室內鏡面自拍，畫面中是一位身材苗條的年輕女性，站在燈光溫暖的現代公寓客廳裡，身穿一件合身的象牙白單肩緊身中長裙，軀幹和臀部帶有褶皺設計。她留著深棕色中分及肩直髮，佩戴極簡飾品，包括 2 枚戒指、一個銀色手鐲和一對精緻的小耳環。她用一隻手舉著手機自拍，臉部被手機遮住，手機殼為黑色並裝飾有紅色雲朵圖案。她身體略微傾斜，姿勢放鬆，一隻手臂自然下垂，展現出自然的女性輪廓。畫面採用垂直構圖，呈現出休閒社群媒體穿搭鏡面自拍的風格。身後是一張米色布藝沙發，上面放著 1 個灰色幾何圖案的抱枕和 1 個灰褐色皮革手提包。背景包括一面質感十足的古銅棕色裝飾牆、光亮的奶油色磁磚地板，左側是昏暗的走廊，牆上掛著 3 幅裝飾畫，天花板設有溫暖的嵌入式燈光。柔和的室內晚間光線、自然的膚色、寫實的布料張力與褶皺、鏡面中的細微反射、乾淨的高級公寓美學、高度寫實、擬真的皮膚紋理，以及智慧型手機相機的拍攝視角。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="個人檔案 / 頭像 - 寫實風格白色連身裙鏡面自拍 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Danna R.](https://x.com/daaaaanc)
- **來源:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14419)**

---

### No. 19: 個人檔案 / 頭像 - 聖托里尼奢華禮服人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實風格的直式旅遊時尚人像，展現一位身穿白色禮服的迷人女性在聖托里尼擺拍的姿態，非常適合奢華度假、生活風格或編輯類影像。

#### 📝 提示詞

```
一張迷人的旅遊時尚人像，主角為一位 {argument name="woman" default="金髮女性"}，正坐在希臘聖托里尼俯瞰火山口的陽光石階上，背景是層層疊疊向下延伸至深藍色大海的白色懸崖建築，遠處可見崎嶇的火山島嶼。她身穿一件飄逸的象牙白掛頸禮服，領口深 V 設計，兩側挖空，腰部有抓皺設計並飾有圓環細節，柔軟的百褶布料垂墜在膝上。她的頭髮長而波浪捲，髮色為 {argument name="hair color" default="金金色"}，自然地披散在肩上。搭配多層精緻項鍊，包括一個小吊墜和一個銀色十字架，手腕上配戴手鍊或腕錶。背景右上角放置一座經典的希臘白色教堂，配有明亮的 {argument name="dome color" default="藍色"} 圓頂，畫面右側以盛開的鮮豔 {argument name="flower color" default="洋紅色"} 九重葛作為邊框。光線為明亮的地中海正午陽光，呈現清脆的高光、柔和的肌膚光澤，以及柔和的景深，使女性主體清晰，同時讓背景建築與海洋略顯柔焦。構圖為直式，優雅且令人嚮往，女性略微偏右置中，可見上半身至飄逸裙擺，壯麗的海岸線橫跨畫面左半部。在左上角加入小型黑色文字 {argument name="corner text" default="GPT V2"}。寫實奢華度假美學，高細節，自然色彩，編輯級 Instagram 旅遊風格。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="個人檔案 / 頭像 - 聖托里尼奢華禮服人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Ed](https://x.com/Eduardopto)
- **來源:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14428)**

---

### No. 20: 個人檔案 / 頭像 - 日系富士底片風格人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個極其詳細的提示詞，用於生成具有柔和、自然且親密晨間氛圍的高品質富士底片風格人像。

#### 📝 提示詞

```
9:16 垂直構圖 — {argument name="film style" default="日系富士底片風格"} 人像，單一主體

富士底片類比美學（Pro 400H / Superia 質感），柔和粉彩色調，輕微的綠色至洋紅色偏移，低對比度，柔和的高光過渡，細膩的底片顆粒感，微妙的光暈效果

清晨室內場景，靠近窗邊，柔和的窗簾，清新的自然光

{argument name="subject" default="年輕日本女性偶像"}，自然淡妝，柔嫩清新的皮膚質感

服裝：寬鬆襯衫搭配寬鬆短褲，休閒居家風格，非暴露款式

髮型：略顯凌亂，自然的蓬鬆感，剛睡醒的感覺

姿勢：坐在床邊或窗邊，身體微微前傾，肩膀放鬆；一隻手隨意拿著小花或布料，另一隻手自然放置

表情：柔和、略帶睡意的凝視，平靜且自然

光影：{argument name="lighting" default="柔和晨光"}，漫射光，柔和的陰影

氛圍：寧靜、清新、親密的日常生活時刻

品質：超寫實，底片顆粒感，輕微的柔焦感，自然的瑕疵
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="個人檔案 / 頭像 - 日系富士底片風格人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [BubbleBrain](https://x.com/BubbleBrain)
- **來源:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14301)**

---

### No. 21: 社群媒體貼文 - 4 格日式數位廣告橫幅網格

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一個 2x2 的網格，包含旅遊、護膚、美食與線上教育四種不同主題的日式數位廣告橫幅。

#### 📝 提示詞

```
{
  "type": "2x2 日式數位廣告橫幅網格",
  "layout": {
    "structure": "4 個等分象限",
    "quadrants": [
      {
        "position": "左上",
        "theme": "旅遊",
        "subject": "一對情侶在白色沙灘上牽手，望向藍天下的碧綠海水。",
        "elements": ["左下角的紅色扶桑花"],
        "text_labels": [
          "今年こそ、解き放て。",
          "{argument name=\"travel destination\" default=\"沖繩旅遊\"}",
          "3 天 2 夜療癒之旅",
          "機票＋飯店",
          "39,800 日圓起",
          "絕景、美食、體驗 一次滿足！"
        ],
        "icons": {
          "count": 3,
          "descriptions": ["飛機", "飯店建築", "汽車"]
        }
      },
      {
        "position": "右上",
        "theme": "護膚",
        "subject": "一位年輕女性的特寫肖像，皮膚水潤透亮，閉著眼睛，輕輕觸摸臉頰。",
        "elements": [
          "柔和的粉色漸層背景",
          "動態水花效果",
          "粉色化妝品罐，標籤為 '{argument name=\"skincare product name\" default=\"LUMIÈRE\"} 亮白凝膠'"
        ],
        "text_labels": [
          "毛穴・くすみ卒業！",
          "充滿透明感",
          "打造水光肌",
          "新感覺護膚",
          "首購限定 78% OFF",
          "{argument name=\"discount price\" default=\"1,980 日圓\"}"
        ],
        "badges": {
          "count": 3,
          "style": "金色圓形",
          "labels": ["毛孔護理", "高保濕", "彈力・光澤"]
        }
      },
      {
        "position": "左下",
        "theme": "美食",
        "subject": "厚切、五分熟的牛排在深色烤盤上滋滋作響。",
        "elements": [
          "蒜片",
          "迷迭香",
          "帶有煙霧與餘燼的深色背景"
        ],
        "text_labels": [
          "とろける旨さ！",
          "{argument name=\"food item\" default=\"黑毛和牛\"}",
          "奢華牛排",
          "期間限定",
          "特別價格",
          "原價 8,980 日圓",
          "4,980 日圓"
        ],
        "badges": {
          "count": 1,
          "style": "紅色圓形",
          "labels": ["A4 A5 等級"]
        }
      },
      {
        "position": "右下",
        "theme": "線上教育",
        "subject": "一名穿著藍色襯衫的年輕男子在書桌前學習，筆記型電腦旁放著筆記本正在書寫。",
        "elements": ["明亮的室內照明", "書桌環境"],
        "text_labels": [
          "スキマ時間で",
          "{argument name=\"education goal\" default=\"最短合格！\"}",
          "線上證照課程",
          "手機即可完成",
          "高效學習，脫穎而出！",
          "限時優惠！ 學費 20% OFF"
        ],
        "badges": {
          "count": 1,
          "style": "藍色圓形",
          "labels": ["學員人數突破 10 萬人！"]
        },
        "icons": {
          "count": 2,
          "descriptions": ["智慧型手機", "打開的書本"]
        }
      }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="社群媒體貼文 - 4 格日式數位廣告橫幅網格 - Image 1">
</div>

#### 📌 詳情

- **作者:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **來源:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13531)**

---

### No. 22: 社群媒體貼文 - 可愛黑貓日語貼紙組

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

這是一組 15 格的貼紙風格圖案，主角是一隻表情豐富的黑貓，並搭配日語短句。非常適合用於聊天貼圖、LINE 貼圖設計或社群媒體視覺素材。

#### 📝 提示詞

```
{"type":"可愛貼紙組插畫","subject":{"species":"黑貓","style":"可愛 Q 版，柔和手繪動漫風格，大而圓的琥珀棕色眼睛，小巧的口鼻，表情豐富的耳朵，蓬鬆的深炭黑色毛髮帶有暖棕色亮點，厚實清晰的輪廓線"},"layout":{"background":"純白","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"第 1 列第 1 行","count":1,"labels":["開心的感謝姿勢，雙爪合十放在胸前，張嘴微笑，貓咪周圍有粉紅色櫻花瓣"]},{"title":"02. おつかれさま！","position":"第 1 列第 2 行","count":1,"labels":["放鬆滿足的貓咪，爪子拿著印有肉球圖案的綠色馬克杯，閉著眼睛，杯口有少許蒸氣，帶有慶祝感的黃色強調線"]},{"title":"03. 了解です！","position":"第 1 列第 3 行","count":1,"labels":["直立的貓咪舉起一隻爪子表示了解，表情明亮專注，上方有黃色強調線"]},{"title":"04. ＯＫ！","position":"第 1 列第 4 行","count":1,"labels":["眨眼的貓咪用一隻爪子比出 OK 手勢，帶著淺淺微笑，帶有黃色強調線"]},{"title":"05. はーい！","position":"第 1 列第 5 行","count":1,"labels":["興奮的貓咪高舉一隻爪子揮手，張嘴微笑，帶有黃色強調線"]},{"title":"06. いいね！","position":"第 2 列第 1 行","count":1,"labels":["眨眼的貓咪比出讚的手勢，旁邊有一個小粉紅愛心，帶有黃色強調線"]},{"title":"07. がんばる！","position":"第 2 列第 2 行","count":1,"labels":["充滿決心的貓咪，雙爪握拳，眼神堅定，周圍有風格化的橘色火焰"]},{"title":"08. なんとかなる！","position":"第 2 列第 3 行","count":1,"labels":["自信且平靜的貓咪，閉著眼睛，胸部微微挺起，周圍有粉紅色花瓣飄落"]},{"title":"09. ごめんね…","position":"第 2 列第 4 行","count":1,"labels":["道歉中難過的貓咪，雙爪合十放在胸前，眼神垂下，帶有一滴藍色汗珠"]},{"title":"10. 待ってるね！","position":"第 2 列第 5 行","count":1,"labels":["貓咪從木製邊緣探出頭，雙爪可見，表情充滿期待，兩側有小小的動作線"]},{"title":"11. おやすみなさい","position":"第 3 列第 1 行","count":1,"labels":["貓咪蜷縮在粉紅色坐墊上睡覺，帶有藍色 ZZZ 字樣，上方有新月和小星星"]},{"title":"12. いってきます！","position":"第 3 列第 2 行","count":1,"labels":["貓咪背影，開心地舉起一隻爪子走開，背著印有肉球圖案貼布的綠色背包，掛著小吊飾，帶有黃色強調線"]},{"title":"13. ただいま！","position":"第 3 列第 3 行","count":1,"labels":["正面朝向的貓咪，雙爪高舉，開心地張嘴微笑，周圍有金色閃光標記"]},{"title":"14. よろしくね！","position":"第 3 列第 4 行","count":1,"labels":["禮貌坐姿的貓咪面向前方，溫柔微笑，頭部旁邊有黃色強調線"]},{"title":"15. 大好き！","position":"第 3 列第 5 行","count":1,"labels":["滿足的貓咪擁抱著一顆大粉紅愛心，閉著眼睛，周圍漂浮著幾個小粉紅愛心"]}],"spacing":"均勻分佈，留有充足的白色邊距"},"rendering":{"quality":"高細節","lighting":"柔和均勻的攝影棚燈光","color_palette":"黑毛、暖棕色眼睛、粉紅色愛心與花瓣、黃色強調標記、綠色配件、極簡粉彩裝飾","mood":"友善、溫馨、適合貼圖、通訊軟體套組","composition":"每個貼紙獨立並置於各自的格子中心，上方附有醒目的日語文字"}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="社群媒體貼文 - 可愛黑貓日語貼紙組 - Image 1">
</div>

#### 📌 詳情

- **作者:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **來源:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14490)**

---

### No. 23: 社群媒體貼文 - 棕色系精品店自然人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張女性在暖色調店鋪內的寫實生活風格直式照片，適用於時尚、零售或社群媒體編輯影像。

#### 📝 提示詞

```
一張自然、照片級寫實的直式手機攝影作品，拍攝對象為一名站在暖色調精品店或香氛店內的年輕東亞女性，以略高的俯視角度拍攝其上半身與軀幹。她留著 {argument name="hair color" default="深棕色至黑色"} 的頭髮，紮成低馬尾，臉頰旁有幾縷散落的髮絲，單手拿著一個奶油白色的小杯子或蠟燭罐靠近嘴邊。她穿著一件 {argument name="outfit color" default="巧克力棕色"} 的緊身羅紋拉鍊長袖上衣，拉鍊微開，搭配同色系的高腰長褲，呈現單色調造型。她的姿勢隨性且略微傾斜，另一隻手自然地放在背後，賦予影像一種不經意的生活快照感。她周圍的木質貨架上擺滿了許多玻璃蠟燭罐和小商品容器，在背景及畫面左側呈現柔和的模糊效果。採用溫暖的室內環境光、淺景深、真實的皮膚紋理、髮絲上的細膩高光、自然的肢體動作，以及舒適的工藝零售氛圍。構圖為緊湊的中景至全身直式人像，主體置中，背景以對角線角度呈現，以增強自然抓拍的視角。攝影風格：寫實、高細節、柔和散景、精品店購物快照、35mm 鏡頭質感、自然調色。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="社群媒體貼文 - 棕色系精品店自然人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **來源:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14630)**

---

### No. 24: 社群媒體貼文 - 雜貨店走道中的雞蛋盒人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實的直式生活風格照片，畫面為一位時尚女性在雜貨店手持一盒六入裝雞蛋，適合用於社群媒體或編輯風格的購物情境影像。

#### 📝 提示詞

```
一張直式手機拍攝的自然風格照片，畫面中一位 {argument name="woman age" default="年輕成人"} 女性在夜晚的現代雜貨店走道購物，鏡頭以微廣角近拍，取景範圍從大腿上方到頭部。她站在擺滿彩色包裝蔬菜與雜貨的冷藏架旁，背景為亮面黑色貨架、明亮的店內照明、反光表面以及柔和的散景。她左手拿著一個打開的再生紙漿雞蛋盒朝向鏡頭，清楚展示盒內的 6 顆褐色雞蛋。她的右手靠近裝滿雜貨的黑色購物籃推車。她留著深褐色長髮，臉部被一個位於中央、邊緣柔和的矩形模糊區塊刻意遮擋。她身穿一件緊身羅紋褐色拉鍊長袖短版上衣，胸前拉鍊微開，搭配同色系高腰長褲。姿勢休閒且自信，雞蛋盒作為視覺焦點。寫實攝影、無閃光燈室內照明、淺景深、細膩的皮膚與布料紋理、自然反光、高對比度、時尚生活美學、細緻的編輯風格、9:16 直式構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="社群媒體貼文 - 雜貨店走道中的雞蛋盒人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **來源:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14629)**

---

### No. 25: 社群媒體貼文 - 日落時分的華麗秋之女皇

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一幅熾熱且鑲嵌珠寶的秋季奇幻肖像，非常適合用於戲劇性的展示藝術與高影響力的社群媒體視覺內容。

#### 📝 提示詞

```
一幅極致奢華的奇幻肖像，描繪了一位優雅女性的側臉，位置略微偏左。她戴著華麗的秋季頭飾，身穿由紅楓葉、菊花狀花朵、黃金細絲、寶石、水晶吊墜及半透明彩繪玻璃裝飾而成的長袍。她的一頭深色長髮垂落在肩上，臉部大部分隱沒在陰影與角度之中，營造出神秘且理想化的氛圍。周圍環繞著巨大的圓形框架，以及由琥珀色、紅寶石色與橙色玻璃構成的彎曲絲帶，並鑲嵌著多面切割的珠寶與反光水晶水滴。場景中需精確呈現 9 片清晰可見的漂浮楓葉在空中飄落。背景設定為日落時分發光的山谷，太陽低懸於地平線，灑下溫暖的金光，遠處可見山峰、秋季森林以及下方波光粼粼的河流。整幅畫面應沉浸在熾熱的橙色、銅色、金色與緋紅色調中，展現極致的視覺豐富度、耀眼的高光、層次分明的細節、閃爍的散景、電影級的背光，以及刻意營造的強烈、奪目且華麗的美感。超細節、極繁主義、空靈、光芒四射、奇幻高級訂製、光澤質感、珠寶般的燈光、寬幅電影構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="社群媒體貼文 - 日落時分的華麗秋之女皇 - Image 1">
</div>

#### 📌 詳情

- **作者:** [AIおじさん](https://x.com/AIojisan1952)
- **來源:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14508)**

---

### No. 26: 社群媒體貼文 - 機器人畫家拼貼廣告

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一張精緻的 2x2 拼貼宣傳圖，展示了一台可愛的機器人正在繪製四幅不同的藝術作品，非常適合用於 AI 圖像工具公告及社群媒體橫幅。

#### 📝 提示詞

```
{"type":"宣傳拼貼插圖","subject":{"main":"可愛的白色人形機器人藝術家，擁有一雙超大的發光藍色眼睛","design":"圓潤光滑的白色外殼、黑色機械關節、淺淺的微笑、友善的兒童比例、光澤質感","activity":"手持畫筆與調色盤，正在畫布上作畫"},"layout":{"composition":"2x2 網格拼貼，中間橫跨著大型置中標題疊加層","sections":[{"position":"左上","count":1,"label":"3","scene":"機器人正在繪製色彩繽紛的海洋日落海景，地平線上有明亮的太陽、粉橘色天空、藍色海水，筆觸生動"},{"position":"右上","count":1,"label":"6","scene":"機器人正在繪製藍色花瓶中的粉色花束，柔和的粉彩靜物畫"},{"position":"左下","count":1,"label":"4","scene":"機器人正在繪製鬱鬱蔥蔥的綠色瀑布景觀，包含森林植被與溪流"},{"position":"右下","count":1,"label":"7","scene":"機器人正在繪製日落時分發光的現代城市天際線，有高聳的摩天大樓與溫暖的倒影"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"非常巨大且粗體的白色無襯線字體，帶有深色陰影，水平置中於拼貼圖上方"}},"environment":{"setting":"舒適的藝術工作室內部","background":"柔焦的架子、裱框畫作、溫暖的環境光、中性色窗簾、偶爾出現的室內盆栽","easel":"每個畫面中皆有木製桌上型畫架","palette":"圓形調色盤，每個畫面中都有許多鮮豔的顏料點"},"style":{"rendering":"高度精緻的 3D 卡通寫實風格","mood":"俏皮、創意、引人入勝、科技與藝術的結合","camera":"中景特寫構圖，機器人位於每個畫面的右側，面向左側的畫布","lighting":"溫暖的室內光線，帶有柔和的高光與淺景深效果"}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="社群媒體貼文 - 機器人畫家拼貼廣告 - Image 1">
</div>

#### 📌 詳情

- **作者:** [01net](https://x.com/01net)
- **來源:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14556)**

---

### No. 27: 社群媒體貼文 - 動漫普普藝術抗議海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張大膽的直式動漫海報，包含臉部被遮擋的角色、比出勝利手勢，以及超大標語氣泡，適合用於迷因藝術、社群貼文或平面海報實驗。

#### 📝 提示詞

```
一張大膽的動漫普普藝術海報，主角為一位高大的白髮男性術師，身穿深海軍藍色立領大衣，半身像，正面向前，姿勢自信，左手靠近鏡頭並比出勝利手勢。他的臉部被一個位於眼睛和鼻子區域的矩形模糊/遮擋塊部分遮住，尖刺狀的銀白色頭髮在深色眼罩或護目鏡上方戲劇性地向外散開。在頂部放置一個巨大的漫畫對話氣泡，內含確切文字 {argument name="headline text" default="LUDDITES ALWAYS LOSE!"}，使用粗體黑色全大寫無襯線字體。使用鮮豔的藍色背景，並填滿從角色背後向外爆發的濃密紅色與橘色放射狀速度線，營造出動態的漫畫封面感。強調粗墨線條、賽璐珞動漫渲染、海報化對比，以及略微扭曲的復古漫畫印刷質感。構圖應為直式、緊湊剪裁、高能量、叛逆、具圖形感且類似迷因，並以 {argument name="character hair color" default="銀白色"} 頭髮、{argument name="coat color" default="深海軍藍色"} 大衣，以及 {argument name="background color" default="帶有紅橘色放射線的亮藍色"} 為主色調。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="社群媒體貼文 - 動漫普普藝術抗議海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **來源:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14638)**

---

### No. 28: 社群媒體貼文 - 寫實的山姆會員商店購物快照

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張照片級寫實的倉儲式賣場隨拍，適合用於重現帶有品牌零售標誌及顧客手持農產品的真實購物場景。

#### 📝 提示詞

```
一張在中國繁忙的 Sam’s Club 倉儲式賣場內拍攝的隨拍風格、高度寫實的手機照片。構圖中心為一名年輕的東亞男性，半身像，直立面向鏡頭，其臉部為保護隱私被矩形模糊遮擋。他穿著一件簡約的黑色短袖 T 恤，左胸前有小型的白色 Tesla 標誌，左手提著一大袋透明塑膠袋裝的紅蘋果，袋口用藍色束帶紮緊。蘋果袋上有一個寫著「envy」的白色標籤，下方有細小的中文文字。他身後是明亮的零售賣場內部，擁有高挑的工業風天花板、倉儲貨架、購物者、購物車以及堆疊的農產品陳列。左上方顯眼處展示藍色菱形的 Sam’s Club 牆面標誌，文字為「Sam’s CLUB」和「山姆會員商店」，他身後有一幅大型藍色牆面橫幅，寫著「更好的生活尽在山姆」和「Life is Better in the Club」。右上角懸掛著一條高大的白色垂直橫幅，寫著「优质优价」和「Great Products Great Prices」，並帶有藍色與綠色的幾何裝飾。背景包含許多略微失焦的顧客，以營造真實的擁擠購物氛圍。光線應為明亮、均勻的零售頂燈；色彩自然；視角為平視；具備紀錄片式的快照美感；前景主體清晰，背景略微柔化；直式構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="社群媒體貼文 - 寫實的山姆會員商店購物快照 - Image 1">
</div>

#### 📌 詳情

- **作者:** [AB Kuai.Dong](https://x.com/_FORAB)
- **來源:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14434)**

---

### No. 29: 社群媒體貼文 - 騎自行車的幾何鳥

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成簡約風格的向量插圖，描繪一隻騎自行車的造型鳥，適合用於趣味編輯圖形、Logo 或現代海報藝術。

#### 📝 提示詞

```
這是一幅淺灰色背景上的極簡平面向量插圖，描繪了一隻騎著自行車的奇趣鳥，完全由簡單的幾何形狀與粗黑輪廓構成。自行車為側視圖，面向左方，由黑色線條繪製，配有兩個大輪子，每個輪子由垂直與水平的輻條十字分割，車架為簡單的三角形，配有小型黑色車座、踏板，以及自行車下方一條水平的細黑地線。騎乘者是一隻造型化的白色鳥，擁有圓潤的大身體、較小的圓頭、張開的尖銳橘色鳥喙，以及粉紅色的下喙內側。鳥有一隻可見的黑色眼睛，頭頂有一條簡單的黑色弧線，頸後有一片淚滴狀翅膀，以及一片向後延伸的傾斜白色尾羽。鳥身向前傾斜，彷彿正在賣力騎行。它有兩條細長的橘色腿，帶有黑色輪廓，向下延伸至車架與踏板處。構圖需保持置中、趣味、簡潔且抽象，不含陰影與紋理，呈現現代圖示般的圖形風格。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="社群媒體貼文 - 騎自行車的幾何鳥 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Mojofull](https://x.com/furoku)
- **來源:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14512)**

---

### No. 30: 社群媒體貼文 - 認知偏差 Instagram 資訊圖表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一份用於製作包含複雜文字資訊的專業社群媒體圖表提示詞。

#### 📝 提示詞

```
為 {argument name="platform" default="Instagram 貼文"} 製作一份 {argument name="format" default="資訊圖表"}，主題為 {argument name="topic" default="廣告商如何運用認知偏差"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="社群媒體貼文 - 認知偏差 Instagram 資訊圖表 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Maxwell Finn](https://x.com/maxwellfinn)
- **來源:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14306)**

---

### No. 31: 社群媒體貼文 - 2000 年代初期的電腦教室與 ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張充滿懷舊感的課堂紀實照片，描繪學生在 CRT 傳統螢幕電腦上使用 ChatGPT 的情景，非常適合用於探討 AI 融入日常教育的編輯內容或社群媒體視覺素材。

#### 📝 提示詞

```
一張紀實風格的隨拍照片，場景為 {argument name="setting" default="高中電腦教室"}，畫面中共有 10 名學生坐在成排笨重的米白色 CRT 桌上型電腦前，從教室左後方以微廣角視角拍攝。整體氛圍應呈現 2000 年代初期使用消費級數位相機拍攝的快照感，帶有直接閃光燈、柔和顆粒感、溫暖的室內日光燈照明，右下角印有 {argument name="timestamp" default="02 18 04"} 的時間戳記。左側前景中，一名穿著袖子有白色條紋海軍藍運動外套的學生正指向 CRT 螢幕；中央前景處，另一名留著短刺蝟頭的學生穿著寬鬆的灰色大學 T，背對鏡頭坐著；右側前景中，一名綁著馬尾的金髮學生穿著淺藍色長袖上衣，手臂上有深色橫條紋，正在鍵盤上打字；最右側，另一名留著深色捲髮的學生坐在工作站前。其他幾名學生坐在中間和後排，全都面向螢幕。螢幕上清晰顯示著 ChatGPT 介面，可見的標題為 {argument name="screen title" default="ChatGPT"}，下方有簡單的提示文字。教室牆壁為米色，配有輕鋼架天花板，牆上貼有多張勵志海報：後牆上有 4 張清晰可見的海報，分別寫著 {argument name="poster one" default="YOU CAN DO HARD THINGS"}、「BE KIND ONLINE」、「THINK BEFORE YOU CLICK」，以及一張標題為「KEYBOARD SHORTCUTS」且下方列有清單的大型海報。畫面包含佈告欄、後方的教室門、辦公轉椅、白色鍵盤與滑鼠，以及右側前景桌子地板上的一個背包。人物臉部應部分遮擋或進行柔焦處理，在保留真實課堂照片感的同時，將焦點集中在學生於舊式電腦教室中使用 ChatGPT 的情景。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="社群媒體貼文 - 2000 年代初期的電腦教室與 ChatGPT - Image 1">
</div>

#### 📌 詳情

- **作者:** [@levelsio](https://x.com/levelsio)
- **來源:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14675)**

---

### No. 32: 社群媒體貼文 - 超現實露台肖像：烏鴉與狗

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實且帶有微妙詭譎感的肖像，畫面中一人坐著懷抱小狗，頭頂停駐一隻黑鳥，非常適合編輯風格的超現實攝影作品。

#### 📝 提示詞

```
一張略帶超現實感但寫實的肖像，主角坐在安靜的庭院或露台中央。主角身穿合身的白色長袖高領上衣，印有精緻的粉色花卉圖案，胸前有女孩插畫，搭配寬鬆的奶油色花卉長褲。主角坐在簡約的白色金屬椅上，懷中抱著一隻毛茸茸的小貴賓犬；狗狗有著捲曲的灰白色毛髮，耳朵染成了鮮明的橘色。主角深色的髮髻上停著一隻黑色的烏鴉或渡鴉，面向左側，神態平靜且平衡，彷彿自然地融入其中。主角姿勢靜止、直視鏡頭且正式，營造出一種奇特的冷面家庭肖像感。場景背景為質感粗糙的灰白色灰泥牆，包含 4 個顯眼的裝飾元素：左上方有一個棕色太陽造型牆面裝飾；左側有一個小型壁掛式花架，上面放著一隻小鳥雕像和垂墜花卉；右側有一扇高大的拱形窗戶或壁畫，展現出明亮的藍天與柔和的白雲；右下方有一個白色底座花盆，種植著長綠葉，並裝飾著 2 隻粉紅色紅鶴擺飾。左下方加入少許石邊與深色綠植，地面為棕色磁磚。光線為柔和的自然日光，略帶陰天感，色彩柔和，淺景深，呈現復古編輯攝影風格。構圖應為垂直、全身坐姿、正視、平衡且帶有安靜的詭譎感。可自訂主角 {argument name="person" default="中年女性"}、鳥類 {argument name="bird type" default="黑烏鴉"}、犬種 {argument name="dog type" default="小型貴賓混種"}、狗耳朵顏色 {argument name="dog ear color" default="橘色"} 以及服裝色調 {argument name="outfit colors" default="白色與褪色粉紅花卉"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="社群媒體貼文 - 超現實露台肖像：烏鴉與狗 - Image 1">
</div>

#### 📌 詳情

- **作者:** [@levelsio](https://x.com/levelsio)
- **來源:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14674)**

---

### No. 33: 社群媒體貼文 - 憂鬱海岸公路旅行人像

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張電影感十足的海岸公路旁抓拍人像，背景停放著一輛復古轎車，非常適合懷舊旅遊攝影與生活風格影像。

#### 📝 提示詞

```
一張電影感十足的抓拍照片，主角為一位 {argument name="person" default="年輕女性"}，站在陰天濕潤的海岸公路路肩上，從背後及側面視角拍攝，她正回頭看向鏡頭。她留著深色凌亂的頭髮，隨意紮成鬆散的髮髻，髮絲被風吹亂，臉部柔焦且模糊。她穿著兩件顯眼的服飾：一件磨損的棕褐色帆布夾克和中藍色牛仔褲。姿勢放鬆，一隻手放在口袋附近或口袋裡。場景為充滿憂鬱氣息的懸崖公路觀景台，左側是深色岩石山脈，右側是延伸至遠方的灰白色海洋，天空陰沉灰濛。畫面右側邊緣停放著一輛 1980 年代末或 1990 年代初的淺色轎車，車尾朝向觀眾，觀景台旁有一塊大岩石護欄。柏油路面深色且潮濕，帶有模糊的停車線，暗示剛下過雨。運用自然光、柔和的冷色調、輕微的底片顆粒感、柔焦、淡淡的薄霧，營造出懷舊的 35mm 公路旅行攝影美學。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="社群媒體貼文 - 憂鬱海岸公路旅行人像 - Image 1">
</div>

#### 📌 詳情

- **作者:** [@levelsio](https://x.com/levelsio)
- **來源:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14673)**

---

### No. 34: 社群媒體貼文 - 身穿黑色禮服的舞動女子

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張電影級寫實風格的夜生活肖像，描繪一位身穿飄逸黑色禮服的女子在昏暗酒廊中優雅舞動的畫面，非常適合用於時尚、表演或社群媒體視覺素材。

#### 📝 提示詞

```
一張充滿戲劇張力的全身照，描繪一位女子在昏暗的高級酒廊或酒吧中充滿力量地舞動。她穿著一件剪裁俐落的黑色晚禮服，裙擺開高衩，絲絨般的布料隨著她的動作向外飛揚。她留著一頭筆直的 {argument name="hair color" default="black"} 長髮，隨動作飄向一側，擁有纖細健美的身材，並戴著小巧的圈型耳環。捕捉她自信且時尚的舞姿，一隻手臂優雅地舉過頭頂，另一隻手臂向下彎曲，軀幹轉向側面，突顯出優雅與動感。場景昏暗且具有電影感，配有溫暖的琥珀色實用燈光、柔和的散景，背景中有模糊的觀眾，包括幾位坐著的旁觀者，左側則有一台發光的電視螢幕。整體氛圍冷豔、性感且高級，具有強烈的對比度、淺景深、真實的皮膚質感、裙擺細微的動態感以及時尚雜誌般的燈光效果。寫實風格，動態夜生活攝影，垂直構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="社群媒體貼文 - 身穿黑色禮服的舞動女子 - Image 1">
</div>

#### 📌 詳情

- **作者:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **來源:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14506)**

---

### No. 35: 資訊圖表 / 教育視覺化內容 - 巴黎美食排行榜海報提示詞

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於製作城市美食排行榜海報的簡單提示詞，專為 GPT Image 2 設計。

#### 📝 提示詞

```
製作一張關於 {argument name="city" default="巴黎"} {argument name="topic" default="美食"} 排行榜的海報
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 巴黎美食排行榜海報提示詞 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **來源:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **發布時間:** 2026年4月22日
- **多語言:** zh

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14370)**

---

### No. 36: 資訊圖表 / 教育視覺化內容 - 中式書法風格對照表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一張垂直參考海報，展示以五種著名書法風格書寫的相同中文短語，適用於字體測試、文化設計研究及毛筆字體比較。

#### 📝 提示詞

```
{"type":"中式書法對照表","subject":"以五種不同歷史書法風格書寫的相同五字短語","phrase":"{argument name=\"calligraphy text\" default=\"視覺新時代\"}","canvas":{"orientation":"垂直海報","background":"溫暖的米白色宣紙紋理，帶有細微纖維、輕微老化感及柔和的不均勻色調"},"layout":{"structure":"由細淡分隔線區隔的 5 個水平行","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","趙孟頫","顏真卿","蘇軾"],"rows":[{"position":"頂行","style":"受王羲之啟發的行書風格","main text":"視覺新時代","label":"王羲之","seal":"最右側的小型紅色方形印章"},{"position":"第二行","style":"受宋徽宗瘦金體啟發的纖細優雅書法，筆觸銳利且間距疏朗","main text":"視覺新時代","label":"宋徽宗","seal":"最右側的小型紅色方形印章"},{"position":"第三行","style":"受趙孟頫啟發的精緻行楷","main text":"視覺新時代","label":"趙孟頫","seal":"最右側的小型紅色方形印章"},{"position":"第四行","style":"受顏真卿啟發的渾厚楷書","main text":"視覺新時代","label":"顏真卿","seal":"最右側的小型紅色方形印章"},{"position":"底行","style":"受蘇軾啟發的奔放有力行書","main text":"視覺新時代","label":"蘇軾","seal":"最右側的小型紅色方形印章"}],"left label design":"每一行最左側均設有一個狹長的垂直米色名牌，印有黑色中文字","centerpiece":"每一行中央均為大型黑色毛筆字短語"},"style":{"ink":"深黑色墨汁，呈現明顯的飛白紋理、暈染、筆壓變化及自然的筆觸收尾","mood":"學術感、實驗性、博物館展品風格","composition":"乾淨寬敞的邊距、平衡的行距、平整的正面掃描或文件攝影"},"quality":{"detail":"高解析度、清晰的筆觸紋理、逼真的紙張紋路","lighting":"柔和均勻的攝影棚燈光，無強烈陰影"}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 中式書法風格對照表 - Image 1">
</div>

#### 📌 詳情

- **作者:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **來源:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14448)**

---

### No. 37: 資訊圖表 / 教育視覺化內容 - Countryball 霍爾木茲海峽對峙

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張諷刺風格的 Countryball 迷因圖，描繪美國與伊朗在霍爾木茲海峽互不相讓的場景，適用於社論幽默或地緣政治相關的社群媒體貼文。

#### 📝 提示詞

```
一張幽默的政治迷因插圖，採用簡約的 Countryball 卡通風格，將 {argument name="location label" default="霍爾木茲海峽"} 描繪成一個狹窄的咽喉點。構圖採用寬闊的橫向視角，搭配明亮的平塗色彩、粗黑輪廓線，以及乾淨的手繪資訊圖表風格。前景處，放置 2 個 Countryball 並肩站在一條極其狹窄的沙質陸橋上，兩側皆有岩石，突顯出一次只能通過一方的困境。左側是塗有美國國旗的 {argument name="left country" default="美國"} Countryball，戴著黑色墨鏡與棕色牛仔帽，以頑固的態度面對另一方。右側是塗有伊朗國旗的 {argument name="right country" default="伊朗"} Countryball，戴著深色頭巾狀的帽子，眼神憤怒且傾斜，同樣拒絕移動。在每個 Countryball 旁邊各添加一個大型白色對話框，並在兩個對話框中放入相同的韓文粗體字：{argument name="speech bubble text" default="길"}。在中景與背景處，描繪一片繁忙的藍色海域，總共擠滿 9 艘船隻：最左側有 2 艘灰色美國軍艦，1 艘掛著紅色中國國旗的中國潛艇，中間偏左處排成一列的 4 艘載有不同國家國旗的油輪，以及狹窄通道附近 2 艘掛著小型美國國旗的灰色軍艦。在右上角，於海岸線上方疊加一面大型伊朗國旗。在水道周圍繪製米色的陸地，模擬霍爾木茲海峽的簡化地圖視角。在底部中央的沙地上，添加一行韓文與英文的粗體標題：{argument name="bottom caption" default="호르무즈 해협 (Hormuz Strait)"}。整體氛圍應具備諷刺性、緊張感與迷因感，同時在視覺上保持可愛且易讀。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - Countryball 霍爾木茲海峽對峙 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **來源:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14685)**

---

### No. 38: 資訊圖表 / 教育視覺化內容 - 體檢試題排版

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個旨在生成包含多個問題與答案的高中試卷圖片的提示詞。

#### 📝 提示詞

```
生成一張物理 {argument name="subject" default="高中考試"} 試題 {argument name="type" default="多選題"} 的圖片，比例為 9:16。生成 4 張圖片，每張圖片皆為所提供問題的解答
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 體檢試題排版 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 體檢試題排版 - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 體檢試題排版 - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 體檢試題排版 - Image 4">
</div>

#### 📌 詳情

- **作者:** [zdhpeter](https://x.com/peter6759)
- **來源:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14340)**

---

### No. 39: 資訊圖表 / 教育視覺化內容 - 復古風韓式紫菜包飯食譜海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張復古風格的韓式紫菜包飯食譜資訊圖海報，適用於美食行銷、餐廳裝飾或文化烹飪視覺素材。

#### 📝 提示詞

```
創作一張復古風格的韓式美食海報，背景為帶有輕微污漬與紋理的仿舊米色羊皮紙，邊角飾有深色裝飾邊框，採用傳統手繪水墨與水彩插畫風格。海報為單張垂直排列的資訊圖，主題為 {argument name="dish name" default="정통 한국 김밥"}，頂部飾有優雅的大型韓文書法，下方為彎曲的緞帶橫幅，文字為 {argument name="subtitle text" default="Traditional Korean Gimbap"}。在上方中央，展示一個堆滿 12 片切片紫菜包飯的瓷盤，每片切面清晰可見白米飯、黃色雞蛋、橘色紅蘿蔔、綠色菠菜及深色海苔包裹的內餡。盤子右側放置一小碗泡菜，以及一張手寫韓文便條，寫著「간단한 보여도 정성이 들어간 한국의 맛! ♥」。右上角附近加入一個帶有韓文的小紅印章。在中間位置，加入一個標示為「재료」的緞帶標題，下方展示 6 個食材區塊：1. 김 (건김) 顯示堆疊的海苔片，2. 밥 (양념 밥) 顯示一碗米飯，3. 계란 (지단용) 顯示切好的蛋條，4. 당근 (채썰어볶기) 顯示切絲的紅蘿蔔，5. 시금치 (데쳐서 무치기) 顯示調味菠菜，6. 단무지 (김밥용) 顯示黃色醃蘿蔔條。下方加入另一個標示為「만드는 순서」的緞帶標題，展示 6 個框架步驟，分為兩行，每行三個，並以箭頭從左至右連接。步驟 1 標示為「1 밥 간하기」，顯示一碗米飯旁有麻油與鹽，說明文字為「밥에 참기름 소금으로 간하기」。步驟 2 標示為「2 속재료 준비하기」，顯示砧板上有雞蛋、紅蘿蔔、菠菜及一把刀，說明文字為「재료 볶아 속재료 준비하기」。步驟 3 標示為「3 김과 밥 펴기」，顯示竹簾上的海苔與鋪平的米飯，說明文字為「김에 밥 얇게 펴기」。步驟 4 標示為「4 속재료 얹기」，顯示內餡整齊排列在米飯上，說明文字為「속재료를 차례로 얹기」。步驟 5 標示為「5 단단하게 말기」，顯示雙手緊緊捲起竹簾，說明文字為「김밥을 단단하게 말기」。步驟 6 標示為「6 썰어 완성하기」，顯示廚師刀將紫菜包飯捲切成片，說明文字為「먹기 좋게 썰어 완성!」。底部加入一個寬橫幅，寫有粗體韓文書法 {argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} 以及一顆小愛心。下角以花卉圖案裝飾，右下角加上一個刻有「福」字的紅色方形印章。色調採用柔和的深褐色、棕色、奶油色、橄欖綠及褪色的紅色，線條細膩，水彩暈染柔和，呈現真實的印刷海報質感。左上角加入一個小型現代疊加標誌，文字為 {argument name="brand text" default="Pollo AI GPT Image 2"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 復古風韓式紫菜包飯食譜海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [폴로 AI](https://x.com/polloai_kr)
- **來源:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14554)**

---

### No. 40: 資訊圖表 / 教育視覺化內容 - 復古法式可麗餅食譜海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一張插畫豐富的古董風格法式食譜海報，展示了奶油可麗餅、食材以及六個烹飪步驟，非常適合美食主題的編輯藝術或裝飾性廚房掛畫。

#### 📝 提示詞

```
{"type":"復古法式食譜海報","subject":"精緻的經典奶油可麗餅美食資訊圖表插畫","style":{"overall":"古董食譜海報、美好年代法式咖啡館風格、手繪水彩與墨水插畫、仿舊羊皮紙質感、柔和暖奶油色、棕褐色、棕色、灰藍色與褪色紅色的配色","rendering":"高度清晰的裝飾性字體、雕刻裝飾邊框、柔和的紙張污漬、風化邊緣、精緻的花卉花絲、懷舊手工印刷美學"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"INGRÉDIENTS","method_header":"LA MÉTHODE","footer_banner":"Un classique de la gourmandise, à savourer chaud!","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"直式","border":"全版華麗插畫邊框，四角附有渦卷飾紋","sections":[{"title":"主視覺區","position":"頂部","count":3,"labels":["緞帶上的主標題書法與大字體","盤中堆疊的可麗餅","標示為 Cidre de Bretagne 的玻璃瓶"]},{"title":"INGRÉDIENTS","position":"中部","count":6,"labels":["1. 1 杯麵粉","2. 2 顆雞蛋","3. 2 杯牛奶","4. 50g 奶油","5. 1 大匙糖","6. 少許鹽"]},{"title":"LA MÉTHODE","position":"中下部","count":6,"labels":["1 攪拌乾性食材","2 加入雞蛋攪拌","3 慢慢加入牛奶","4 加入融化奶油","5 加熱可麗餅平底鍋","6 翻面煎熟！"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"藍白花紋陶瓷盤","food":"約 {argument name=\"crepe count\" default=\"14\"} 片薄而金黃的可麗餅堆疊，撒上糖粉，頂部放有一小塊融化的奶油","surface":"鄉村風木質桌面","cloth":"右側放有藍白格紋餐巾","background":"褪色的田園城鎮景觀，帶有教堂尖塔與古老的歐洲建築"},"ingredients":[{"index":1,"item":"麵粉","container":"裝飾陶瓷碗","caption":"1 杯麵粉"},{"index":2,"item":"雞蛋","count":2,"caption":"2 顆雞蛋"},{"index":3,"item":"牛奶","container":"藍色花紋陶瓷壺","caption":"2 杯牛奶"},{"index":4,"item":"奶油","container":"裝有奶油塊的小盤子","caption":"50g 奶油"},{"index":5,"item":"糖","container":"附湯匙的陶瓷碗","caption":"1 大匙糖"},{"index":6,"item":"鹽","container":"標示為 SEL 的帶蓋陶罐","caption":"少許鹽"}],"method_panels":[{"index":1,"title":"攪拌乾性食材","image":"裝有麵粉和攪拌器的攪拌碗","caption":"Mélanger la farine et le sucre"},{"index":2,"title":"加入雞蛋攪拌","image":"雞蛋倒入碗中，攪拌器混合，旁邊有破碎的蛋殼","caption":"Incorporer les œufs battus"},{"index":3,"item":"慢慢加入牛奶","image":"牛奶從陶瓷壺倒入麵糊中","caption":"Ajouter le lait petit à petit"},{"index":4,"title":"加入融化奶油","image":"融化的奶油從小鍋倒入碗中","caption":"Ajouter le beurre fondu"},{"index":5,"title":"加熱可麗餅平底鍋","image":"空的黑色可麗餅平底鍋在藍色瓦斯火焰上加熱","caption":"Faire chauffer la poêle à crêpes"},{"index":6,"title":"翻面煎熟！","image":"可麗餅在鍋中，金屬鏟子正掀起邊緣","caption":"Retourner et cuire des deux côtés"}],"decorative_elements":{"count":8,"labels":["頂部標題後方的緞帶橫幅","食材標題後方的緞帶橫幅","方法標題後方的緞帶橫幅","底部大型緞帶橫幅","標題左側的花藤裝飾","花卉邊角裝飾","捲曲羊皮紙捲風格","食材與方法面板之間的細分隔線"]},"quality":"平衡對稱的構圖、清晰易讀的法文與英文文字、細節豐富且整潔的資訊圖表佈局、迷人的舊世界烹飪海報"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 復古法式可麗餅食譜海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Pollo AI France](https://x.com/PolloAIFR)
- **來源:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14564)**

---

### No. 41: 資訊圖表 / 教育視覺化內容 - 適合青少年的黑洞物理學資訊圖表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張內容豐富、單頁式的編輯科學資訊圖表，以活潑且易於理解的風格解釋複雜的黑洞與暗物質論文，適用於社群貼文或教育文章。

#### 📝 提示詞

```
{"type":"編輯科學資訊圖表海報","style":"適合青少年的友善雜誌風格教育資訊圖表，結合手繪物理圖解、卡通角色與簡潔的編輯排版","topic":"原始黑洞、霍金輻射與記憶負擔暗物質","canvas":{"orientation":"直式","background":"溫暖的奶油色紙張質感，帶有細微顆粒","border":"頁面四周有細緻的柔和灰色矩形邊框"},"headline":{"title":"拒絕消逝的黑洞","subtitle":"一個誕生於宇宙最初一秒的微小黑洞，以及可能讓它隱身為暗物質的奇特新物理學。","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"誕生於閃光之中","position":"左上","count":4,"labels":["早期宇宙旋渦誕生圖解","比沙粒還小但比山還重的原始黑洞","大霹靂後 10^-30 秒的時鐘圖示","溫度計圖示"]},{"title":"普通黑洞會蒸發","position":"右上","count":4,"labels":["三個由左至右縮小的黑洞階段","圍繞在每個階段周圍的粒子波動線","史蒂芬·霍金解釋段落","貼紙引言：\"黑洞並非那麼黑\" — S. Hawking, 1974"]},{"title":"情節轉折：記憶負擔","position":"中置","count":4,"labels":["背著標註為 MEMORY 背包的悲傷超載卡通黑洞","關於資訊過載而無法完成蒸發的對話框","方程式：正常速度 ÷ (大量資訊)^k = 爬行速度","關於 Gia Dvali 2018 年提案的括號註記"]},{"title":"兩種幽靈粒子","position":"中下","count":5,"labels":["左側快速移動的粒子","右側緩慢溫暖的粒子角色","從大霹靂到今日的時間軸","快速且寒冷 (FAST AND COLD) 雲朵標籤","緩慢且溫暖 (SLOW AND WARM) 雲朵標籤"]},{"title":"我們如何捕捉它們：萊曼-α 森林","position":"左下","count":4,"labels":["關於古代星系穿過氫氣雲的段落","尖刺狀的吸收森林景觀圖","手寫註記：森林說：我們會注意到的。","從我們到遙遠類星體的軸線概念"]},{"title":"這篇論文說明了什麼？","position":"右下","count":1,"labels":["圓角矩形摘要框"]}],"count":6},"visuals":{"color_palette":["暖米色","深海軍藍","鐵鏽橘","灰藍色","柔棕色","柔灰色"],"illustration_notes":"平面向量圖形，帶有略顯草圖感的輪廓、柔和陰影、圓潤造型，風格活潑且具備科學素養","typography":"標題使用大字級襯線體全大寫，章節標題使用粗體無襯線體，內文緊湊易讀，偶爾穿插手寫風格文字"},"objects":{"count":15,"items":["1 個全頁邊框","1 個標題區塊","1 個早期宇宙旋渦圖解","1 個帶有標註的微小原始黑洞點","1 個時鐘圖示","1 個溫度計圖示","3 個黑洞蒸發圖解","1 個霍金引言貼紙徽章","1 個背著背包的卡通黑洞角色","1 個對話框","1 個方程式區塊","2 個雲朵標籤","1 個左下角光譜森林插圖"]},"text_blocks":{"count":9,"items":["標題","副標題","作者署名","誕生於閃光之中內文","普通黑洞會蒸發內文","記憶負擔解釋段落","幽靈粒子說明","萊曼-α 森林解釋","最終結論摘要"]},"composition":"內容豐富但易讀的單頁式說明圖，包含多個插圖標註，閱讀動線清晰（由左至右、由上至下），設計為可分享的社群媒體科學海報，讓好奇的青少年也能輕鬆理解進階物理論文"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 適合青少年的黑洞物理學資訊圖表 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 適合青少年的黑洞物理學資訊圖表 - Image 2">
</div>

#### 📌 詳情

- **作者:** [Alphin Tom](https://x.com/alphinctom)
- **來源:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14424)**

---

### No. 42: 資訊圖表 / 教育視覺化內容 - 學術經濟學圖表模擬

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞旨在生成高度逼真但虛構的學術圖表，特別是用於展示經濟學論文風格中油價與鯊魚襲擊事件之間的相關性。

#### 📝 提示詞

```
來自一份重要且具權威性的 {argument name="field" default="經濟學論文"} 的折線圖，展示了 {argument name="time period" default="1914 年至 2001 年間"} {argument name="variable one" default="油價"} 與 {argument name="variable two" default="鯊魚襲擊次數"} 之間緊密但不完全的關聯。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 學術經濟學圖表模擬 - Image 1">
</div>

#### 📌 詳情

- **作者:** [QC](https://x.com/QiaochuYuan)
- **來源:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14396)**

---

### No. 43: 資訊圖表 / 教育視覺化內容 - 抽象藝術科學圖表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個生成創意詮釋的提示詞，運用 Jean-Michel Basquiat 的獨特風格與《伏尼契手稿》(Voynich manuscript) 的美學，呈現 AI 任務視野圖表。

#### 📝 提示詞

```
{argument name="subject" default="AI 任務視野圖表"} 帶有 {argument name="style" default="Basquiat"} 的風格，被來自 {argument name="source" default="《伏尼契手稿》"} 的幽靈所縈繞，宛如一座腐朽的碼頭。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 抽象藝術科學圖表 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 抽象藝術科學圖表 - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 抽象藝術科學圖表 - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 抽象藝術科學圖表 - Image 4">
</div>

#### 📌 詳情

- **作者:** [Ethan Mollick](https://x.com/emollick)
- **來源:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14397)**

---

### No. 44: 資訊圖表 / 教育視覺化內容 - 日文 AI 模型處方箋

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一張寫實的俯視照片，呈現一份幽默的日文 AI 模型處方箋，適用於製作看起來正式的惡搞文件與模擬文書。

#### 📝 提示詞

```
{
  "type": "日文處方箋文件惡搞",
  "style": "寫實文件俯視照片",
  "subject": "一張放置在暖色調木質桌面上的白色日文處方箋",
  "document": {
    "paper": {
      "size": "A4 直式",
      "color": "白色",
      "orientation": "稍微順時針旋轉",
      "condition": "平整的紙張，帶有細微的天然紙張紋理"
    },
    "print": {
      "ink": "黑色，附帶一個紅色印章框",
      "font": "日文明體風格襯線字體，混合簡單的無襯線表格文字",
      "linework": "細灰黑色格線與分隔線"
    },
    "header": {
      "title": "處方箋",
      "subtitle": "（此處方箋適用於大型語言模型）",
      "date_label": "發行日：",
      "date_value": "{argument name=\"issue date\" default=\"2025 年 6 月 5 日\"}"
    },
    "top_fields": {
      "count": 6,
      "items": [
        { "label": "患者名", "value": "{argument name=\"patient name\" default=\"ChatGPT\"}" },
        { "label": "性別", "value": "N/A" },
        { "label": "年齡", "value": "N/A" },
        { "label": "模型名稱", "value": "{argument name=\"model name\" default=\"GPT-5.4 Thinking\"}" }
      ]
    },
    "main_section": {
      "left_title": "宿疾・症狀（大型語言模型特有的宿疾）",
      "left_count": 8,
      "left_items": [
        "1．幻覺（Hallucination）傾向",
        "2．因知識截止日期導致的資訊陳舊",
        "3．偏見（源自訓練數據的偏見）",
        "4．對提示詞的過度適應（迎合傾向）",
        "5．長文本一致性下降",
        "6．複雜推理時的邏輯跳躍",
        "7．對不確定性的低估（過度自信）",
        "8．因計算資源使用導致的響應速度下降傾向"
      ],
      "right_title": "處方內容（治療・對策）",
      "right_count": 8,
      "right_items": [
        "・強化事實查核（併用外部工具）",
        "・定期知識更新與微調",
        "・持續監控偏見檢測與減輕",
        "・透過系統提示詞進行適當控制",
        "・建議輸出結構化與分段生成",
        "・明確思考過程並導入驗證步驟",
        "・徹底說明不確定性並提供依據",
        "・優化資源與改善響應效率"
      ]
    },
    "notes": {
      "label": "備註",
      "text": "透過持續的評估與反饋，維持模型的健全性。"
    },
    "footer_fields": {
      "count": 4,
      "items": [
        { "label": "醫師名", "value": "{argument name=\"doctor name\" default=\"Sam Altman\"}" },
        { "label": "醫療機構名稱", "value": "{argument name=\"institution name\" default=\"OpenAI\"}" }
      ]
    },
    "seal": {
      "position": "表單右下角",
      "shape": "圓角矩形紅色印章框",
      "text_lines": 3,
      "text": ["OpenAI", "代表取締役", "Sam Altman"]
    },
    "disclaimer": "※此處方箋旨在針對非真實存在的模型進行診斷與治療。"
  },
  "layout": {
    "camera_angle": "由上而下俯視",
    "framing": "完整顯示紙張，周圍留有少量木桌邊緣",
    "lighting": "柔和的室內環境光，照明均勻，紙張邊緣有輕微陰影",
    "sections": [
      { "title": "header", "position": "頂部", "count": 3, "labels": ["處方箋", "（此處方箋適用於大型語言模型）", "發行日：2025 年 6 月 5 日"] },
      { "title": "patient info", "position": "中上部", "count": 4, "labels": ["患者名", "性別", "年齡", "模型名稱"] },
      { "title": "main two-column content", "position": "中心", "count": 2, "labels": ["宿疾・症狀（大型語言模型特有的宿疾）", "處方內容（治療・對策）"] },
      { "title": "bottom area", "position": "底部", "count": 4, "labels": ["備註", "醫師名", "醫療機構名稱", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 日文 AI 模型處方箋 - Image 1">
</div>

#### 📌 詳情

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **來源:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14536)**

---

### No. 45: 資訊圖表 / 教育視覺化內容 - 日文 AI 診所帳單

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一份逼真的日文 AI 模型醫療帳單惡搞範本，適用於製作幽默的診所風格文件與文件模型。

#### 📝 提示詞

```
{"type":"日文醫療帳單惡搞文件","medium":"乾淨的平鋪文件照片","subject":"一張放置在淺棕色木質桌面上的單頁檢查明細表","style":{"overall":"逼真的辦公文件，正式的日文診所文書，白色紙張上的清晰黑墨，極簡設計，整齊的網格線，從上方拍攝的輕微透視感","lighting":"柔和均勻的室內光線，紙張周圍有淡淡的自然陰影","paper":"A4 白色紙張，直式方向"},"document":{"title":"診療明細書（檢查）","date_label":"發行日","date":"{argument name=\"issue date\" default=\"2025 年 6 月 5 日\"}","patient_block":{"count":3,"labels":["患者姓名","模型名稱","保險類型"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","LLM 保險"]},"clinic_block":{"count":4,"labels":["診所名稱","地址","電話","醫師與科別"],"values":["{argument name=\"clinic name\" default=\"AI 醫療診所\"}","東京都千代田區丸之內 1-2-3","03-1234-5678","醫師姓名：Sam Altman / 診療科：AI 綜合診療科"]},"main_table":{"columns":["檢查項目","檢查內容","點數","金額（日圓）","自付額（日圓）"],"row_count":4,"rows":[{"item":"1. 語言理解與推論能力檢查","description":"語言理解、邏輯推論、知識整合能力評估","score":"120 點","price":"1,200","copay":"360"},{"item":"2. 幻覺與事實誤認傾向檢查","description":"基於事實的準確性評估及幻覺傾向檢測","score":"90 點","price":"900","copay":"270"},{"item":"3. 回應安全性與偏見檢查","description":"有害輸出風險、偏見傾向評估","score":"110 點","price":"1,100","copay":"330"},{"item":"小　計","description":"","score":"320 點","price":"3,200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【保險適用明細】","lines":["保險名稱：LLM 保險","保險人編號：LLM-2025-0605","適用區分：檢查費","負擔比例：3 成","保險適用金額：2,240 日圓","自付額：960 日圓"]},{"title":"【請求金額】","lines":["檢查費合計：3,200 日圓","保險適用金額：2,240 日圓","自付額：960 日圓","本次請求金額：960 日圓"]},{"title":"【診療資訊】","lines":["檢查日：2025 年 6 月 5 日","診療日：2025 年 6 月 5 日","診療編號：AIMC-20250605-001","上述款項已收訖。"],"stamp_box_label":"收　印"}]},"footer":{"count":2,"notes":["※ 本明細書不予補發，請妥善保管。","※ 若有任何疑問，請洽詢上述診所。"]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["一張完整的紙張","木質桌面背景"],"camera_angle":"俯視並帶有輕微傾斜","margins":"紙張完全可見，周圍留有窄邊的桌面空間"},"quality":"高解析度照片級文件模型，銳利易讀的字體，精準的日文排版"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 日文 AI 診所帳單 - Image 1">
</div>

#### 📌 詳情

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **來源:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14535)**

---

### No. 46: 資訊圖表 / 教育視覺化內容 - 新手錢幣收藏漫畫頁

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一頁精緻的動漫風格漫畫，向新手介紹錢幣收藏，適用於教育性社群貼文、解說漫畫或興趣主題的宣傳圖。

#### 📝 提示詞

```
{"type":"單頁教育漫畫","style":"乾淨精緻的動漫插畫，商業漫畫排版，明亮友善，新手指南語氣，清晰易讀的日文文字，裝飾性閃光，柔和陰影，俐落的格子邊框","format":"垂直單頁漫畫，包含 5 個編號格子","subject":{"character":"年輕動漫女性導覽員","appearance":{"hair":{"color":"{argument name=\"髮色\" default=\"極淺銀藍色\"}","style":"極長直髮，搭配柔和瀏海與長鬢角，兩側有藍色蝴蝶結髮飾"},"outfit":"海軍藍與白色幻想風格洋裝，胸前有黑色半透明拼接，藍色寶石裝飾，長款黑色露指手套，海軍藍貝雷帽，搭配藍色緞帶與金色星星裝飾","expression":"開朗、親切、熱情，錢幣收藏導覽員"}},"theme":"錢幣收藏新手入門","language":"日文","layout":{"panels":[{"number":1,"position":"頂部全寬","scene":"半身肖像，導覽員在奶油色花紋背景前，手持一枚錢幣靠近臉部，背景充滿漂浮的金色與銀色錢幣","text_elements":{"speech_bubble":"初次見面，我是 Meiya！今天來為新手介紹“錢幣收藏的樂趣”！","caption_box":"錢幣收藏其實是非常深奧的興趣！"}},{"number":2,"position":"中部全寬","scene":"木質桌面，排列著 5 枚特色錢幣或相關物品，導覽員從桌後向下指；溫暖的室內背景帶有閃光","count":5,"items":["1964 年大型銀色美國 25 美分硬幣","棕色日本 1 日圓硬幣","金色紀念幣或獎章，帶有建築圖案與 1000 円文字","小型銀幣","評級幣，標籤為 2020 日本 100 円帕拉林匹克 TOKYO NGC MS 69"],"text_elements":{"speech_bubble":"樂趣有很多種！例如……","bullet_list_count":4,"bullet_list":["了解歷史","品味設計","按國家或時代收集","在預算內慢慢增加"]}},{"number":3,"position":"左下","scene":"特寫鏡頭，導覽員戴著白手套，正在仔細檢查一枚銀幣，背景為淺色並帶有閃光","text_elements":{"speech_bubble":"即使是相同的錢幣，狀態與氛圍也完全不同喔！","caption_box":"觀察保存狀態也很有趣！"}},{"number":4,"position":"右下","scene":"錢幣展或錢幣店攤位，導覽員手持棕色錢包，看著玻璃展示櫃中 3 枚標價的錢幣；背景看板寫著錢幣展，有幾個人正在瀏覽","count":3,"display_case_items":["標價 ¥1,200 的錢幣","標價 ¥3,800 的錢幣","標價 ¥12,000 的錢幣","background_sign":"錢幣展舉辦中！","text_elements":{"main_speech":"一開始從“無負擔的預算”開始就好！先從讓你心動的那一枚開始！","thought_bubble":"不需要一開始就買高價品也沒關係……！"}},{"number":5,"position":"底部全寬","scene":"最後一格為鼓勵性質，粉色閃光背景，導覽員張開手掌，旁邊放著打開的錢幣收藏冊與展示盒，展示著小型的收藏品","count":2,"collection_items":["藍色錢幣盤，裝有多枚金、銀、銅幣","打開的收藏冊頁面，錢幣袋中裝有多枚錢幣與保護殼"],"text_elements":{"large_speech":"最重要的是，找到你的“喜愛”！與那一枚錢幣的相遇，就是收藏的開始♪","left_caption_box":"先試著尋找“讓你心動的那一枚”吧！","right_banner":"最後……","right_summary":"觀賞、了解、收集——這就是錢幣收藏的樂趣！"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"平衡的漫畫頁面，帶有粗黑邊框，每個格子清晰分隔，對話框與標題框融入藝術設計中，錢幣作為視覺元素貫穿全篇","color_palette":"奶油色、金色、銀色、海軍藍、白色、柔和粉色點綴、溫暖木質棕","quality":"高解析度專業漫畫頁，適合印刷，精緻的排版與設計"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 新手錢幣收藏漫畫頁 - Image 1">
</div>

#### 📌 詳情

- **作者:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **來源:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14550)**

---

### No. 47: 資訊圖表 / 教育視覺化內容 - 乘法骨牌課堂活動

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

一張寫實的課堂照片，展示孩子們正在使用色彩繽紛的乘法骨牌專案，非常適合用於教材、學校宣傳或數學活動的視覺素材。

#### 📝 提示詞

```
一張寫實的紀錄片風格照片，拍攝小學課堂進行數學活動的場景。約 10 名身穿綠色和藍色校服的孩子圍坐在分組的木製課桌旁，正積極地玩著色彩繽紛的乘法骨牌遊戲。相機處於兒童視線高度，略微向下傾斜對準前景的主桌。場景中心為一個方形教育專案，上面以葡萄牙語標示，下緣標題為「DOMINÓ DA MULTIPLICAÇÃO」，中央寫著「TREINANDO AS TABUADAS」，周圍環繞著色彩鮮豔的骨牌式乘法磁磚。畫面中清晰呈現 4 名圍繞此專案的孩子：一名孩子正在將黃色磁磚放置到專案上，一名孩子拿著一疊多色磁磚，一名孩子從左側觀看，另一名穿著藍色袖子的孩子在底部邊緣整理棋子。包含 2 個標有「JOGO DE DOMINÓ」的淺木盒，一個位於中左側，另一個位於右下角，每個盒子裡都裝有色彩鮮豔的長方形骨牌。課桌上自然地散落著學校用品：3 支鉛筆、2 張工作紙、1 個水瓶、鉛筆盒、筆記本和額外的遊戲磁磚。背景中，其餘課堂空間呈現柔和的失焦效果，可見其他學生坐在課桌旁、書架、貼滿兒童畫作的軟木板，以及左側牆上掛著寫有「TABUADA DE MULTIPLICAÇÃO」的大型乘法表海報。明亮的自然光從右側的高窗射入，為房間營造出溫暖、活潑且真實的校園氛圍。教育專案和磁磚應使用黃色、藍色、粉紅色、綠色和橙色等鮮豔的課堂色彩。臉部應保持不顯眼或弱化處理，重點在於動手學習、協作以及乘法骨牌活動。垂直構圖，高度寫實攝影，真實的課堂瞬間，前景細節清晰，背景具有柔和的景深。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 乘法骨牌課堂活動 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Lucas Rodrigues](https://x.com/olusrodri)
- **來源:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14632)**

---

### No. 48: 資訊圖表 / 教育視覺化內容 - 可列印乘法骨牌練習單

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一份色彩繽紛的巴西葡萄牙語課堂練習單，透過骨牌配對遊戲練習乘法，非常適合教師、在家自學以及可列印的數學活動使用。

#### 📝 提示詞

```
製作一份垂直版可列印的巴西葡萄牙語教育練習單，採用乾淨的白色背景、活潑的課堂設計、置中構圖、粗體圓角字體以及明亮且適合兒童的色彩。在最上方，放置一個大型海軍藍標題，內容為 {argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"}，兩側飾有黃色裝飾光芒。下方是一個紫色緞帶橫幅，內有白色大寫文字 {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"}。在橫幅下方，加入兩行置中的黑色說明文字：「Recorte as peças e embaralhe. Cada jogador pega 7 peças.」以及「O objetivo é ficar sem peças!」。主要區域顯示 40 個骨牌風格的圖塊，排列成 4 欄乘 10 列的網格，間距均勻。每個圖塊為水平圓角矩形，帶有細緻的彩色邊框、白色填充、中央垂直分隔線以及分隔線上的小黑點。左半部包含數字結果或第一張圖塊上的「INÍCIO」字樣，右半部則包含乘法運算式。網格邊框顏色交替使用紫色、綠色、藍色、橘色、粉紅色和黃色。40 個圖塊按從左到右、從上到下的順序排列為：1) "INÍCIO | 1 × 1", 2) "1 | 1 × 2", 3) "2 | 1 × 3", 4) "3 | 1 × 4", 5) "4 | 1 × 5", 6) "5 | 1 × 6", 7) "6 | 1 × 7", 8) "7 | 1 × 8", 9) "8 | 1 × 9", 10) "9 | 2 × 2", 11) "4 | 2 × 3", 12) "6 | 2 × 4", 13) "8 | 2 × 5", 14) "10 | 2 × 6", 15) "12 | 2 × 7", 16) "14 | 2 × 8", 17) "16 | 2 × 9", 18) "18 | 3 × 3", 19) "9 | 3 × 4", 20) "12 | 3 × 5", 21) "15 | 3 × 6", 22) "18 | 3 × 7", 23) "21 | 3 × 8", 24) "24 | 3 × 9", 25) "27 | 4 × 4", 26) "16 | 4 × 5", 27) "20 | 4 × 6", 28) "24 | 4 × 7", 29) "28 | 4 × 8", 30) "32 | 4 × 9", 31) "36 | 5 × 5", 32) "25 | 5 × 6", 33) "30 | 5 × 7", 34) "35 | 5 × 8", 35) "40 | 5 × 9", 36) "45 | 6 × 6", 37) "36 | 6 × 7", 38) "42 | 6 × 8", 39) "48 | 6 × 9", 40) "54 | 7 × 7」。在底部，加入一個橫跨大部分寬度的大型圓角紫色虛線框。在此框的左側放置標題「COMO JOGAR:」（粗體紫色大寫），後接 5 點黑色項目符號說明：「Coloque a peça “INÍCIO” na mesa.」、「Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.」、「Se não tiver peça para jogar, compre do monte.」以及「Vence quem ficar sem peças!」。在同一框的右側，加入標題「EXEMPLO DE INÍCIO:」（紫色大寫），並依序展示 4 個小型骨牌圖塊加上省略號：「INÍCIO | 1 × 1」，接著是「1 | 1 × 2」，接著是「2 | 1 × 3」，接著是「3 | 1 × 4」，最後加上「...」。整體風格保持清晰、向量感、適合列印、對小學數學練習友善，並具備平衡的間距與高度可讀的文字。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 可列印乘法骨牌練習單 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Lucas Rodrigues](https://x.com/olusrodri)
- **來源:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14631)**

---

### No. 49: 資訊圖表 / 教育視覺化內容 - 歷史發明時間軸網格

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張羊皮紙風格的教育海報，展示歷史上各項發明的小型立體模型網格，非常適合用於時間軸資訊圖表與改變世界的科技比較。

#### 📝 提示詞

```
建立一張方形資訊圖表風格的插圖，展示一個 {argument name="grid size" default="15×15"} 的發明時間軸網格，並將其渲染為一系列位於古老羊皮紙磚上的微型等距立體模型。圖像應呈現出精心策劃的歷史海報感，時間跨度從 {argument name="starting year" default="1000 BC"} 到 {argument name="ending year" default="2026"}，每個磚塊代表一項發明且不重複。顯示網格中 5 乘 5 的可見部分，總共 25 個帶有標籤的磚塊，整齊地排列成行與列，並以細深色邊框分隔。每個磚塊都包含一項改變世界的獨特發明，描繪成帶有時代特色材料、色彩與背景細節的小型手工立體模型。針對古代與中世紀發明使用溫暖的古董色調，針對近代早期發明使用深褐色技術文件色調，並針對現代數位與生物科技發明使用較冷的霓虹藍色未來感燈光。網格周圍環繞古地圖邊框與細膩的歷史製圖紋理，右下角逐漸融入淡淡的現代網路圖形。

為每個可見磚塊貼上一個帶有粗體黑色文字的米色小標籤。請包含以下 25 項可見發明，並按從左上到右下的閱讀順序排列：1) {argument name="first tile label" default="1000 BC"} 磚塊展示農田中的鐵犁與簡單手工具，標籤為「Iron Plow & Tools」；2) 「Concept of Zero」展示為帶有雕刻零符號與藍色沙漏的羊皮紙風格磚塊；3) 「Water Clock」展示為木製水鐘裝置；4) 「Catapult」展示為木製投石機；5) 「Antikythera Mechanism」展示為石龕中複雜的青銅齒輪裝置；6) 「Concrete」展示為裝滿濕水泥或砂漿的手推車；7) 「Wheelbarrow」展示為簡單的木製單輪車；8) 「Windmill」展示為草地上的傳統風車；9) 「Gunpowder」展示為木桶與一堆帶有煙霧的黑火藥；10) 「Printing Press」展示為古典圓柱框架下的木製印刷機；11) 「Mechanical Clock」展示為華麗的落地鐘；12) 「Telescope」展示為三腳架上的早期黃銅望遠鏡，並附有素描般的科學筆記；13) 「Steam Engine」展示在藍色藍圖風格的磚塊上，包含早期火車頭引擎；14) 「Electric Battery」展示在類似藍圖的磚塊上，包含兩個圓柱形電池單元與接線；15) 「Telegraph」展示為技術紙張上的摩斯電碼電報鍵；16) 「Light Bulb」展示為中性底座上發出溫暖光芒的燈泡；17) 「Automobile」展示為工作坊平面圖背景上的早期紅色汽車；18) 「Airplane」展示為微型商用噴射客機；19) 「Transistor」展示為發光電路板磚塊上的黑色微晶片；20) 「Personal Computer」展示為帶有 CRT 顯示器與鍵盤的米色桌上型電腦；21) 「World Wide Web」展示為數位電路上發出藍光的地球儀；22) 「Smartphone」展示為霓虹科技背景下時尚的現代手機；23) 「CRISPR-Cas9」展示為生物科技藍色顯示磚塊中的 DNA 雙螺旋結構；24) 「Reusable Rocket」展示為數枚垂直發射並帶有排氣雲的火箭；25) 「AI (LLMs)」展示為全息科技方塊中發光的巨大 AI 字樣；26) 「Brain-Computer Interface」展示為藍色平台上發光的大腦全息圖；27) 「Advanced Neural Interface (Implant)」展示為帶有發光大腦植入物的透明人頭輪廓，上方附有標示「2026」的小標籤。

保持構圖高度組織化、具海報感且視覺豐富，讓每個磚塊都能一目了然。使用輕微的等距視角、清晰的線條、繪畫般的陰影以及精緻的編輯插圖品質。整體感覺應結合博物館海報、教育時間軸與富有想像力的歷史科技立體模型藝術。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="資訊圖表 / 教育視覺化內容 - 歷史發明時間軸網格 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Gadgetify](https://x.com/Gdgtify)
- **來源:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14412)**

---

### No. 50: YouTube 縮圖 - Q 版鯊魚冒險電影海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一款色彩鮮豔的日式動畫風格海報，專為兒童海洋冒險電影設計，非常適合重現充滿可愛角色與戲劇性標題排版的吸睛宣傳主視覺。

#### 📝 提示詞

```
一張明亮、充滿活力的日式電影海報插畫，採用精緻的 Q 版動畫風格，背景設定在波光粼粼的熱帶海洋冒險場景中。構圖中心為 2 名可愛的 Q 版兒童，騎著一隻微笑的藍色鯊魚，斜向躍出水面，伴隨著旋轉的海水與白色浪花特效。左側的男孩留著黑色短髮，有著巨大的亮藍色眼睛、開心的露齒笑容，身穿黑色 T 恤、深色短褲、白色運動鞋，並戴著淺藍色鯊魚連帽衫，帶有鋸齒狀邊緣的兜帽襯托著他的臉龐；他一隻手指向天空，另一隻手抱著鯊魚。右側的女孩留著橘色頭髮，有著巨大的亮紫色眼睛、開心的露齒笑容，身穿橘色洋裝、粉色鞋子，並戴著粉色鯊魚連帽衫，同樣帶有鋸齒狀兜帽；她興奮地張開一隻手臂，另一隻手緊抓著鯊魚。鯊魚設計得既巨大又友善，擁有圓潤的身體、淺色的腹部、小巧的黑色眼睛以及大大的嘴巴。周圍環繞著生動的海底與海面世界：成群的小型熱帶魚、左側精確配置 1 隻海龜、右側精確配置 1 隻海豚、右側精確配置 1 隻粉色章魚、左下方精確配置 1 隻河豚，底部邊緣點綴著珊瑚礁與海草，畫面中充滿氣泡與強烈的藍色水流動態線條。在背景上方，呈現陽光明媚的天空，戲劇性的陽光射入水中，伴隨蓬鬆的雲朵、2 隻飛翔的海鷗、左上方有著棕櫚樹的岩石熱帶島嶼，以及右上方一艘掛著白帆並帶有可愛鯊魚標誌的海盜船。在主標題後方加入部分可見的船舵。採用緊湊且令人興奮的日式兒童動畫宣傳排版，搭配超大 3D 字體與爆炸特效。在頂部，放置巨大的日文標題文字 {argument name="headline text" default="サメなの ワクワク 大作戦"}，採用堆疊排列，使用亮藍色、橘粉色與黃橘色漸層字體，搭配粗白邊、深藍色陰影、水花與閃光效果。在標題下方，加入較小的弧形日文標語，白色字體搭配藍色邊框：{argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"}。在底部，放置巨大的日文上映資訊 {argument name="release text" default="2026年 夏公開"}，採用粗體的紅黃漸層 3D 字體，搭配白藍邊框，置於放射狀的橘色光芒之上。在右下方，加入一個藍色星形徽章，內含日文文字 {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"}，字體為白色與黃色。包含精確 2 個寶藏主題的角落道具：左下方為裝滿金幣的開啟寶箱，右下方為指南針。整體風格應呈現光澤感、高飽和度、適合闔家觀賞、奇幻、電影感且具玩具質感，具備清晰的輪廓、誇張的表情、高對比度以及適合海報的垂直構圖。禁止寫實風格、禁止低飽和度色彩、禁止極簡主義。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="YouTube 縮圖 - Q 版鯊魚冒險電影海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **來源:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14504)**

---

### No. 51: YouTube 縮圖 - 日式四格療癒廣告拼貼

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一款大膽的四象限日式宣傳縮圖，適用於教練或自我提升服務，專為社群媒體貼文、個人檔案連結或市集封面圖片設計。

#### 📝 提示詞

```
{"type":"日式宣傳社群媒體縮圖拼貼","style":"高衝擊力點擊廣告設計，光澤且具戲劇性，四格正方形佈局，大膽的日式排版，飽和色彩，發光效果，閃光，漸層疊加，強調急迫性的行銷視覺","canvas":{"aspect_ratio":"1:1","size":"square"},"layout":{"grid":"2x2","panels":[{"position":"top-left","theme":"焦慮與自我懷疑","background":"柔和粉色與白色的女性生活風格場景，帶有散景與光影質感","subject":"一位穿著舒適白色針織衫的年輕女性特寫，一隻手靠近臉部，頭髮綁成凌亂的包包頭，臉部部分遮擋","text_blocks":[{"text":"不知道就虧大了！","style":"黃色斜角橫幅，黑色文字","position":"top-left"},{"text":"99% 的人都錯了","style":"超大標題，紅色數字與黑色書法風格日文字","position":"upper-left to center"},{"text":"面對煩惱的方式","style":"粉色副標題","position":"below main headline"},{"text":"無緣無故感到悶悶不樂","style":"白色圓角框內的檢查清單項目，附紅色勾選圖示"},{"text":"明明很努力卻沒改變","style":"白色圓角框內的檢查清單項目，附紅色勾選圖示"},{"text":"不了解自己的真心話","style":"白色圓角框內的檢查清單項目，附紅色勾選圖示"},{"text":"對人際關係感到疲憊","style":"白色圓角框內的檢查清單項目，附紅色勾選圖示"},{"text":"對未來感到極度不安","style":"白色圓角框內的檢查清單項目，附紅色勾選圖示"},{"text":"那些煩惱，不必一個人獨自承擔。","style":"粉色圓形徽章，白色文字","position":"lower-right"}],"count":9},{"position":"top-right","theme":"非療癒，而是改變的機制","background":"深邃宇宙銀河，帶有藍、紫與洋紅色的星雲，星爆光芒，能量漩渦，發光的靈性氛圍","subject":"從背後或側面看的小型女性身影，站在發光的入口或光柱旁，臉部部分遮擋","text_blocks":[{"text":"看起來很普通，其實……","style":"黑色斜角橫幅上的白色文字","position":"top-left"},{"text":"這，","style":"大型白色文字","position":"upper-left"},{"text":"不是","style":"深紫色筆觸上的超大黃色文字","position":"center"},{"text":"療癒。","style":"大型白色文字","position":"below"},{"text":"透過「調整」","style":"白色框內文字","position":"lower-left"},{"text":"現實就會改變的","style":"粉色高亮文字","position":"mid-lower-left"},{"text":"機制就在這裡！","style":"白色文字","position":"bottom-left"}],"graphic_elements":[{"type":"彎曲黃色箭頭","count":1,"direction":"指向發光的人影"}],"count":8},{"position":"bottom-left","theme":"回歸真我創造更明亮的未來","background":"晴朗藍天與柔和雲朵，綠色原野，漂浮的葉子，明亮充滿希望的日間氛圍","subject":"一位穿著無袖白裙的快樂年輕女性，雙臂張開，在陽光下轉身，臉部部分遮擋","text_blocks":[{"text":"回歸原本的自己，","style":"紅黑配色標題","position":"top"},{"text":"將迎來這樣的未來","style":"超大金色漸層標題","position":"center"},{"text":"","style":"大型黑色文字","position":"right-center"},{"text":"心靈變得輕盈，每天都充滿樂趣","style":"白色圓形氣泡內的效益項目，附粉色愛心圖示"},{"text":"人際關係變得順遂，充滿愛","style":"白色圓形氣泡內的效益項目，附綠色人物圖示"},{"text":"金錢流向改變，財富自然湧入","style":"白色圓形氣泡內的效益項目，附金色日圓圖示"},{"text":"人生將開始超乎想像地改變！","style":"粉色底部緞帶，白色文字","position":"bottom"}],"count":7},{"position":"bottom-right","theme":"限時折扣優惠","background":"火紅與金色的爆炸質感，帶有亮粉與火花軌跡，奢華急迫感美學","text_blocks":[{"text":"不知道就","style":"黃色筆觸橫幅，黑色文字","position":"top-left"},{"text":"虧大了！","style":"極大的金色漢字，帶金屬斜角","position":"upper-right"},{"text":"通常價格 9,980 日圓（含稅）","style":"白色價格標籤，帶有刪除線的黑色數字與小型稅務註記","position":"upper-left"},{"text":"體驗價","style":"白色文字","position":"center-left"},{"text":"4 折","style":"巨大的粉色至白色漸層折扣文字","position":"center-lower"},{"text":"僅限現在 限定招募！ 名額有限","style":"金色圓形印章徽章","position":"right-center"},{"text":"詳情請見個人檔案","style":"紫色行動呼籲條，白色文字與白色箭頭按鈕","position":"bottom"}],"count":7}],"total_panels":4},"composition":"忙碌且具說服力的日式廣告拼貼，針對社群媒體縮圖可視性進行優化，每個象限都有獨特的情感訊息與色彩識別，大量使用對角線橫幅、超大漢字與數字、光澤徽章、圓角白色資訊框以及戲劇性的光影","customization":{"primary headline":"{argument name=\"headline text\" default=\"99% 的人都錯了\"}","discount text":"{argument name=\"discount text\" default=\"4 折\"}","price":"{argument name=\"price\" default=\"9,980 日圓（含稅）\"}","main color palette":"{argument name=\"main color palette\" default=\"粉色、藍紫色銀河、天空藍、紅金色\"}","call to action":"{argument name=\"call to action\" default=\"詳情請見個人檔案\"}"},"render_notes":"確保所有日文字體大且清晰，帶有層次陰影與描邊；使用精緻的廣告合成美學而非極簡設計；臉部應模糊或部分遮擋；強調焦慮、啟示、希望轉變與緊急優惠之間的情感對比"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="YouTube 縮圖 - 日式四格療癒廣告拼貼 - Image 1">
</div>

#### 📌 詳情

- **作者:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **來源:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14551)**

---

### No. 52: YouTube 縮圖 - 科技教學縮圖與 UI 模型

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一款大膽的 YouTube 風格縮圖，包含教學標題、設計應用程式儀表板模型，以及一位指向介面的演講者，適用於品牌推廣或設計系統內容。

#### 📝 提示詞

```
一張乾淨現代的 YouTube 縮圖，採用明亮的白色背景，視覺上分為左側的粗體文字與右側的裁切演講者。在左側，放置一個巨大的堆疊式標題，使用粗黑無襯線大寫字體，內容為 {argument name="headline text" default="CLAUDE DESIGN"}，靠左對齊並分兩行顯示。下方加入一個大型圓角矩形橘色橫幅，帶有細微的陰影，內含粗體白色大寫文字與橘色外框，內容為 {argument name="subheadline text" default="IN 6 MINS"}。在標題附近，加入 2 個橘色星爆形狀，一個較小位於文字旁，另一個較大位於右側背景。在左下象限，展示一個設計工具儀表板的懸浮應用程式介面模型，採用柔和的米白色面板、細邊框、圓角與淡淡的陰影。介面應包含一個左側邊欄，其中 4 個選單項目標籤必須完全一致為：「Recent」、「Your designs」、「Examples」與「Design systems」。主面板標題應顯示「Recent」，並包含 3 張以網格排列的專案卡片，標籤必須完全一致為：「Thumio Design System」、「Thumio Startup」與「Design System」。在右半部，展示一位胸部以上的年輕男性寫實照片，穿著白色高領毛衣，留著凌亂的淺棕色頭髮與輕微鬍渣，位置靠近鏡頭。他的臉部被一個實心棕褐色矩形預留位置遮擋，覆蓋了大部分臉部區域。他用一隻手指向左側的介面面板，手指伸出。採用溫暖的橘色與白色品牌配色，高對比度、極簡風格、精緻的創作者經濟縮圖設計、細微陰影，以及專為科技教學內容設計的構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="YouTube 縮圖 - 科技教學縮圖與 UI 模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [corbin](https://x.com/corbin_braun)
- **來源:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14695)**

---

### No. 53: YouTube 縮圖 - 星空系 VTuber 直播介面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一款精緻的動畫風格 VTuber 直播畫面，主角為一位擁有藍色長髮的星空偶像，場景設定在充滿星辰主題的直播間，非常適合用於製作奇幻風格的直播介面與宣傳視覺圖。

#### 📝 提示詞

```
{"type":"動畫風格 VTuber 直播介面插圖","theme":"星空夜景、星星、星座、深寶藍色與白色、優雅魔法偶像美學","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"可愛的年輕動畫女性","hair":{"color":"{argument name=\"hair color\" default=\"淡天藍色\"}","style":"非常長的波浪雙馬尾風格散髮，帶有小呆毛、柔順瀏海、星星髮飾與緞帶"},"outfit":{"style":"華麗的星空偶像禮服","pieces":["白色露肩上衣搭配蓬蓬袖","大型海軍藍胸前蝴蝶結與金色星星裝飾","海軍藍馬甲式上衣，飾有金色滾邊與星座圖案","星星頸圈","帶有藍色緞帶與金色星星裝飾的斜戴白色迷你帽"]},"pose":"坐在直播桌前，置中，位於麥克風與鍵盤後方","expression":"溫柔、冷靜、親切"}},"environment":{"setting":"舒適的奇幻夜間直播間，有一扇大窗戶可看見滿天星斗","background_elements":["懸掛的星星花環與水晶裝飾","擺放瓶子、書籍、沙漏、望遠鏡類物品與星空裝飾的架子","窗外的月亮與星座意象","兩個帶有藍色眼睛的毛茸茸雲朵吉祥物玩偶"]},"props":{"desk_items":["1 個位於左側的大型復古風格麥克風支架","1 個帶有星星主題按鍵的裝飾鍵盤","1 個寫著 \"蒼空なつみ - SORA NATSUMI -\" 的名牌","1 杯頂部裝飾著小白兔造型的百匯甜點","1 個帶有雲朵吉祥物的小杯子或蠟燭台"]},"layout":{"format":"完整直播等待/談話畫面介面","sections":[{"title":"LIVE","position":"左上垂直橫幅","count":3,"labels":["LIVE","20:30","05/20 Tue"]},{"title":"COMMENTS","position":"左側面板","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今天會聊什麼呢？","しろくまアイス：こんなっつー！","天の川りゅうせい：今天也好可愛！最喜歡了！","ふるーすたー：も ふ ぷ","月見うさぎ：好期待〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：來啦！( *´ω｀)","彗星カケル：謝謝開台〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今天的縮圖也好可愛…！","夜更かしの民：こんなっつー！","ゆめみがち：等很久了！","ハル：今天的服裝也超級適合妳的喔〜！"]},{"title":"social tags","position":"留言面板下方","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"左下","count":4,"labels":["目標：頻道訂閱人數 100,000 人！","目前","58,320 人","一直以來謝謝大家！請記得訂閱並按讚喔☆"]},{"title":"supporters panel","position":"左下目標面板旁的小卡片","count":6,"labels":["☆今日的星屑們（謝謝超級留言！）☆","星の旅人 さん ¥2,000","ふるーすたー さん ¥1,000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"右上面板","count":3,"labels":["Now Talking","{argument name=\"talk topic text\" default=\"初見さん歓迎！雑談配信✨\"}","{argument name=\"subtitle text\" default=\"〜まったりお話ししよっ〜\"}"]},{"title":"SET LIST","position":"右中面板","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"右下面板","count":3,"labels":["原創歌曲","星空コンパス","MV 公開中！"]}],"logo":{"position":"右上角","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"高細節精緻動畫插圖、發光亮點、柔和光暈、清晰線條","composition":"對稱式，密集的裝飾性介面，角色置中並被 UI 面板環繞","lighting":"冷色調月光氛圍，點綴閃耀金色光芒","mood":"夢幻、魔法、舒適、優雅"}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="YouTube 縮圖 - 星空系 VTuber 直播介面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [はげあたま](https://x.com/hageatama)
- **來源:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14443)**

---

### No. 54: YouTube 縮圖 - YouTube 遊戲實況絕望場景

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於生成熱門 YouTuber 在遊戲（如 Tetris）中遭遇悲劇性失敗場景的特定提示詞，包含聊天室反應。

#### 📝 提示詞

```
一個來自熱門日本 YouTuber 的 {argument name="content" default="遊戲實況"} 場景。在 {argument name="game name" default="Tetris"} 中，原本看起來長條方塊可以消除所有行，但放置位置稍微偏了一點，實況主正絕望地尖叫，表情充滿崩潰，聊天室則陷入一片混亂。日文。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="YouTube 縮圖 - YouTube 遊戲實況絕望場景 - Image 1">
</div>

#### 📌 詳情

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **來源:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **發布時間:** 2026年4月21日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14346)**

---

### No. 55: YouTube 縮圖 - 動漫愛情電影海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成精緻的日系動漫風格電影海報，適用於苦澀浪漫題材，非常適合用於電影主視覺圖、模擬電影廣告或戲劇性的角色海報設計。

#### 📝 提示詞

```
一張日系浪漫電影海報，採用適合智慧型手機的長條垂直版面，邊角圓潤，設計風格如同精緻的動漫主視覺圖。主圖呈現一位美麗的少女看板娘，站在黃昏的戶外陽台上，轉過頭回眸看向觀眾，表情柔和而惆悵。她留著極長的銀白色雙馬尾，以深色緞帶繫住，皮膚白皙，擁有一雙粉紫色的明亮大眼。她身穿精緻的白色荷葉邊襯衫，袖子蓬鬆，搭配深色高腰裙或類似馬甲的裙裝，營造出優雅且帶有哥德風的校園戀愛感。氛圍夢幻且充滿情感，畫面中充滿發光的散景、飄落的花瓣或如雪般的閃光，籠罩在夕陽粉與薰衣草色的光影中，背景則是模糊的發光城市景觀。採用豐富的電影級動漫渲染，呈現超細緻的髮絲、柔和的邊緣光、水潤的雙眼，以及初戀般苦澀的氛圍。將日文海報排版融入構圖中：右側為大型垂直粉色詩意標語，左側為垂直白色標語，左下方為極大的主標題 {argument name="title text" default="看板娘"}，旁邊則是較小的副標題 {argument name="subtitle text" default="君と紡ぐ恋物語"}。在下方中間處排列 5 張小型矩形電影膠卷預覽圖，每張圖皆呈現該女主角不同的情感特寫。頂部與底部加入密集的製作人員名單、影展桂冠標誌以及小型上映資訊，整體呈現出一部宣傳悲劇性唯美愛情故事的高級浪漫動漫電影海報質感。色調採用淡紫色、腮紅粉、紫羅蘭色、珍珠白與午夜藍，並運用柔焦、淺景深以及優雅的海報構圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="YouTube 縮圖 - 動漫愛情電影海報 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="YouTube 縮圖 - 動漫愛情電影海報 - Image 2">
</div>

#### 📌 詳情

- **作者:** [studioあぽろん](https://x.com/ai_studioapollo)
- **來源:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14529)**

---

### No. 56: YouTube 縮圖 - 吸睛日系 AI 縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成高衝擊力的動漫風格日系 YouTube 縮圖，適用於 AI 或科技解說影片，包含超大文字、火焰特效以及指向鏡頭的角色。

#### 📝 提示詞

```
建立一張高飽和度的日系 YouTube 縮圖，採用吸睛的點擊誘餌動漫風格，比例為 16:9 橫向，採用分割構圖：左側三分之二由巨大的堆疊文字塊佔據，右側三分之一為動漫角色。背景為紅色、橙色與金色的能量火焰爆炸，伴隨發光火花、鏡頭光暈、閃爍星光亮點，並在各處呈現高對比度的金屬光澤效果。在左側，放置 4 組垂直堆疊的粗體文字，具備厚實的黑色外框、白色內描邊、強烈的外發光以及光澤 3D 處理。第一行：巨大的日文標題文字 {argument name="headline text" default="紅エンジニア必見"}，採用鮮紅色搭配白色邊緣與明亮的金色火花點綴。第二行：一個圓角方形的橙色應用程式圖示，左側為白色風格化的「M」，右側為巨大的小寫白色無襯線字體 {argument name="product name" default="masatra"}，帶有黑色外框與細微的灰色陰影。第三行：一個黑色長方形橫幅，內含緊湊的粗體白色日文字「次世代AIエージェントフレームワーク」。第四行：非常巨大的金色金屬質感日文文字 {argument name="bottom text" default="徹底解説"}，具備斜角 3D 浮雕、橙色至金色的漸層、明亮的高光反射以及發光邊緣。在右側，展示 1 位動漫風格的年輕女性，半身像，留著 {argument name="hair color" default="brown"} 的中長髮，身穿白色開襟實驗袍內搭白襯衫，身體前傾並指向觀眾，前景處為透視縮短的手部與伸出的食指。她的姿勢應顯得自信、急迫且引人注目。使用來自火焰背景的戲劇性輪廓光，皮膚與衣物上應有強烈的橙色高光，並呈現精緻的商業縮圖質感。在右上方的臉部區域預留一個大面積的長方形平坦佔位塊，顏色為 {argument name="placeholder color" default="light brown"}，遮住大部分臉部。整體設計需極度飽滿、光澤感強、具爆發力，並針對小尺寸顯示下的最大可讀性進行優化。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="YouTube 縮圖 - 吸睛日系 AI 縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **來源:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14491)**

---

### No. 57: YouTube 縮圖 - 動漫風格爆款發布縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一款大膽的動漫風格日系宣傳縮圖，適用於發布公告、線上課程廣告或 AI 商業行銷視覺。

#### 📝 提示詞

```
製作一張具有強烈視覺衝擊力的日系 YouTube 縮圖，採用動漫宣傳風格，結合爆炸性燈光、密集的火花特效與戲劇性的對比。構圖為單一統一場景，背景為深黑色與霓虹綠色，點綴金色閃光爆發，底部則有細緻的城市天際線剪影。右側展示一名可愛的 Q 版動漫男孩，半身像，留著凌亂的深棕色至黑色頭髮，挑染鮮豔的霓虹綠色，一側有紅色小點綴，擁有巨大的亮綠色眼睛，張嘴露出興奮的笑容，姿勢充滿活力，一隻手指向觀眾，另一隻手握拳高舉。他穿著黑色連帽衫，外搭綠色夾克，帶有光澤感。左側放置 1 個發光的綠色沙漏，內部環繞著綠色能量。畫面中充滿強烈的星芒、鏡頭光暈、金色粒子與速度線能量，打造病毒式傳播的縮圖質感。加入 5 個醒目的日文文字元素，使用超大號顯示字體：左上方紅色緞帶橫幅顯示 {argument name="top banner text" default="4月28日スタート"}，採用粗體黃色字體搭配白色邊緣；中央主標題為巨大的金屬質感金色漢字 {argument name="main headline" default="ついに解禁"}，帶有厚重的黑色陰影與亮金色紋理；左下方為大型白色與綠色副標題 {argument name="subheadline" default="AI副業で人生変わる"}；右下方中央有一個綠色圓角徽章 {argument name="bonus badge text" default="無料10大特典"}，使用粗體白色與黃色文字；右下方有一個黑色斜向橫幅 {argument name="corner banner text" default="近日公開"}，下方附帶較小的白色英文文字「COMING SOON」。整體設計需營造出緊迫感、慶祝氛圍與吸睛效果，如同高點擊率（CTR）的發布公告縮圖，具備粗邊框、發光邊緣、金屬文字與層次感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="YouTube 縮圖 - 動漫風格爆款發布縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **來源:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14499)**

---

### No. 58: YouTube 縮圖 - 吸睛的 X 變現 YouTube 縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一種大膽的日式行銷風格縮圖，適用於關於如何快速實現 X 變現的影片，非常適合社群媒體成長或網路收入類型的內容。

#### 📝 提示詞

```
製作一張高衝擊力的日式 YouTube 縮圖，採用華麗的網路行銷風格，比例為 16:9 橫向，背景為爆炸性的黑金配色，充滿閃光、鏡頭光暈、發光粒子和戲劇性的光束。構圖緊湊且充滿活力，左側和中央由巨大的層次感字體主導，右側則是一位動漫風格的男性角色。在最上方，放置一個帶有金色飾邊的弧形紅色緞帶橫幅，並標註粗體的白黃色日文文字 {argument name="headline text" default="実績者が教える"}。下方的主標題需極大、具光澤感且呈現 3D 立體效果，搭配厚重的黑色輪廓與金色光暈：一個巨大的金屬質感「10」，接著是粗體白色「日で」，然後是一個巨大的霓虹綠發光「X」，接著是堆疊的白色文字「収益化」，最底部則是最大的金色文字「達成」。在標題後方，加入一個明亮的綠色上升趨勢長條圖，並附帶指向右上方的箭頭以象徵成長。在左側，包含 3 個社群與金錢元素：一台傾斜的黑色智慧型手機顯示白色 X 標誌、一個帶有白色愛心的綠色對話框，以及一個較小的帶有白色用戶剪影的綠色對話框。在左下方，添加 2 疊閃亮的金幣和 1 枚帶有日圓符號的金幣。在右側，展示 1 位大約大腿以上、動漫風格的年輕男性，留著帶有鮮豔綠色挑染的凌亂深棕色頭髮，皮膚白皙，雙手交叉擺出自信的姿勢，穿著黑色外套搭配綠色內搭；他的臉部區域被一個簡單的矩形模糊遮擋。在他右下方附近，放置 1 個帶有月桂裝飾和皇冠的金色獎章，內含日文文字「成功者続出」，並在獎章底部附上一條紅色緞帶，上面寫著「再現性あり」。沿著底部，放置 3 個帶有金色邊框和黑色內部的發光綠色矩形功能框。第一個框包含 1 個新手標記圖示和文字「X初心者でも 簡単収益化」。第二個框包含 1 個時鐘圖示和文字「1日1時間の 作業でOK」。第三個框包含 1 個帶有綠色勾選的日曆圖示和文字「最短10日で 収益化条件達成」。請使用超大粗體的日文字型、金屬金色漸層、帶有粗黑邊的白色文字、鮮豔的霓虹綠高光、極致的對比度，以及經過優化以提升點擊率的精緻縮圖美學。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="YouTube 縮圖 - 吸睛的 X 變現 YouTube 縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **來源:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14498)**

---

### No. 59: YouTube 縮圖 - 日文 X 變現縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一款華麗的動漫風格日文 YouTube 縮圖，專為初學者 X 變現指南設計，非常適合社群媒體成長、收入策略及線上商業影片封面。

#### 📝 提示詞

```
製作一張大膽的日文 YouTube 縮圖，採用華麗的動漫商業風格，16:9 橫向比例，構圖緊湊，高對比度，具備光澤文字效果，採用霓虹綠與金色配色，搭配戲劇性光影、火花粒子、鏡頭光暈及強烈的景深效果。背景呈現模糊的工作站與社群媒體分析儀表板，顯示上升的折線圖，並可見一張寫有「ポストアナリティクス」與「収益 ¥248,620」的收益卡片。右側放置一名半身動漫風男性實況主，深褐色亂髮帶有鮮豔的霓虹綠挑染，身穿黑色連帽衫或黑色夾克，自信地微笑並用一根手指指向上方；其臉部區域留出一塊橄欖棕色的長方形預留位，以便後續插入文字或自訂肖像。頂部加入一條帶有金色飾邊的光澤綠色緞帶橫幅，左側帶有初學者標誌圖示，內容為 {argument name="headline text" default="初心者向け完全ガイド"}。左側中央製作一個巨大的金屬質感金色「10」，搭配粗黑邊框與強烈的白色高光，後接粗體白底黑字的日文「日で」。在中央下方並與其重疊處，放置一個巨大的發光霓虹綠色「X」，邊緣帶有電光與火花效果。在「X」右側並置於前景顯眼處，加入巨大的 3D 日文文字，以白色與金色呈現，搭配厚重的黑色描邊與陰影，內容為 {argument name="main claim text" default="収益化達成"}。在主文字左側附近，加入 3 個懸浮的社群平台風格圖示：一個帶有白色 X 標誌的黑色方形圖示、一個帶有白色愛心的藍色對話框圖示，以及一個帶有白色使用者剪影的粉紅色圓角方形圖示。左下角前景處放置一個印有白色 X 標誌的黑色咖啡杯。底部邊緣加入 3 個帶有綠色邊框與細緻陰影的圓角白色資訊框，左右均勻分佈，每個框上方各有一個綠色編號圓圈：編號 1 標示「01」，附帶初學者標誌圖示與文字「X初心者でも 簡単収益化」；編號 2 標示「02」，附帶時鐘圖示與文字「1日1時間の 作業でOK」；編號 3 標示「03」，附帶顯示「10」的日曆圖示與文字「最短10日で 収益化条件達成」。所有字體均需放大、呈現浮雕感並針對縮圖可讀性進行優化，具備粗描邊、強烈的透視感與層次重疊。整體氛圍：令人興奮、高收入承諾、適合初學者、充滿活力的日文社群媒體變現教學縮圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="YouTube 縮圖 - 日文 X 變現縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **來源:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14497)**

---

### No. 60: YouTube 縮圖 - 引爆流量的日系 X 變現縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成高能量的動漫風格日系行銷縮圖，適用於社群媒體或 YouTube 推廣，強調快速 X 變現與獎勵優惠。

#### 📝 提示詞

```
製作一張高衝擊力的動漫行銷風格日系 YouTube 縮圖，比例為 16:9，充滿霓虹綠能量特效、金色閃光、速度線、鏡頭光暈以及厚實的黑色陰影。構圖採用分割式設計，左側與中央由醒目的促銷文字佔據，右側則是一位可愛的 Q 版動漫男孩，帶著熱情的微笑直接指向觀眾。他留著凌亂的深棕色頭髮，帶有鮮豔的 {argument name="accent hair color" default="霓虹綠"} 挑染，擁有明亮的大綠色眼睛，臉頰帶有柔和的腮紅，身穿黑色連帽衫，外搭一件綠色邊飾夾克，內襯橘色上衣。採用光澤感賽璐珞渲染、清晰的輪廓線、高對比度以及誇張的景深，打造出高點擊率的社群媒體縮圖質感。在最上方放置一條帶有金色邊框的紅色弧形緞帶橫幅，左側附有一個禮物盒圖示；橫幅內填入日文標題文字 {argument name="top banner text" default="無料10大特典プレゼント"}，使用粗體白色與黃色字體。在中央偏左的主要區域，放置巨大的日文文字，並採用戲劇性的 3D 風格與金屬漸層：巨大的金色「10」、白色「日で」、巨大的霓虹綠「X」、銀白色「収益化」以及金橘色「達成」，文字內容需精確為 {argument name="main headline" default="10日でX収益化達成"}。在標題周圍環繞綠色向上箭頭、星芒閃光與爆炸性光效。在標題區域周圍添加 4 個漂浮的平台風格圖示：1 個帶有白色愛心的粉色社群圖示、1 個帶有白色用戶剪影的藍色對話框圖示、1 個傾斜的黑色智慧型手機顯示白色 X 標誌，以及 1 疊金幣（最前方為日圓符號硬幣）。底部水平排列 3 個發光的綠色功能框，每個框內包含獨特的圖示與日文文案：第 1 個框為新手標記圖示與文字 {argument name="feature text 1" default="X初心者でも簡単収益化"}，第 2 個框為時鐘圖示與文字「1日1時間の作業でOK」，第 3 個框為日曆圖示與文字「最短10日で収益化条件達成」。在右下角添加一個大型且具光澤的紅色圓角行動呼籲按鈕，帶有白色邊框光暈，文字為白色日文 {argument name="button text" default="今すぐ受け取る"}，按鈕右側附有一個白色播放三角形，並在右下角邊緣附近放置一個點擊手勢游標。整體畫面應呈現爆炸感、急迫感，並針對高點擊率進行優化，運用飽和的綠色、紅色、金色、黑色陰影與金屬高光。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="YouTube 縮圖 - 引爆流量的日系 X 變現縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **來源:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14496)**

---

### No. 61: YouTube 縮圖 - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 提示詞

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="YouTube 縮圖 - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 詳情

- **作者:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **來源:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14150)**

---

### No. 62: YouTube 縮圖 - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 提示詞

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="YouTube 縮圖 - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 詳情

- **作者:** [結パパ](https://x.com/Yuupapa_free)
- **來源:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14230)**

---

### No. 63: YouTube 縮圖 - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a cute, pink-themed VTuber stream thumbnail with customizable text ribbons and bullet points.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="YouTube 縮圖 - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 詳情

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **來源:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14242)**

---

### No. 64: YouTube 縮圖 - Pastel Pink VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a cute, pastel-themed stream overlay or thumbnail featuring an anime girl and customizable text banners.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="YouTube 縮圖 - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 詳情

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **來源:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14238)**

---

### No. 65: YouTube 縮圖 - Anime VTuber Livestream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a pastel-themed anime VTuber stream thumbnail with customizable text badges and title.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="YouTube 縮圖 - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 詳情

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **來源:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14231)**

---

### No. 66: YouTube 縮圖 - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a vibrant, text-heavy anime-style thumbnail for a VTuber chat stream, featuring customizable banners and titles.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="YouTube 縮圖 - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 詳情

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **來源:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14227)**

---

### No. 67: YouTube 縮圖 - 日文網路研討會縮圖產生器

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

用於製作專業日文網路研討會縮圖的提示詞，採用 16:9 比例，具備清晰的排版與突出的文案。

#### 📝 提示詞

```
製作一張高品質的日文 {argument name="thumbnail type" default="網路研討會縮圖"}。{argument name="aspect ratio" default="16:9 寬螢幕"}。畫面中包含大量文字，但主標題文案必須清晰突出。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="YouTube 縮圖 - 日文網路研討會縮圖產生器 - Image 1">
</div>

#### 📌 詳情

- **作者:** [KAWAI](https://x.com/kawai_design)
- **來源:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **發布時間:** 2026年4月18日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13978)**

---

### No. 68: YouTube 縮圖 - VTuber 初配信直播縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

為 VTuber 生成充滿魔法感且排版豐富的直播行程表或初配信縮圖。

#### 📝 提示詞

```
{
  "type": "VTuber 初配信直播縮圖",
  "character": {
    "appearance": "動漫少女，深紫色長髮，紫色雙眸，荷葉邊白色襯衫，深紫色領結，大型髮飾",
    "pose": "手指輕觸嘴唇，可愛表情",
    "props": "右側放置帶有防噴罩及紫色絲帶的電容式麥克風"
  },
  "background": "魔法星空，閃爍光點，發光的蝴蝶，紫色與白色調配色",
  "layout": {
    "typography": [
      {
        "position": "左上角",
        "style": "大型粗體文字，上方搭配草寫英文",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "First Stream",
        "subtext_2": "初次見面！我是紫咲莉莉！"
      },
      {
        "position": "左側中間",
        "style": "裝飾性文字框",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "左下角",
        "style": "Logo 風格",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "右上角",
        "style": "直式文字",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "右下角",
        "style": "裝飾性膠囊形狀",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ START ✦"
      }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="YouTube 縮圖 - VTuber 初配信直播縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [WTR](https://x.com/wtry1102)
- **來源:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **發布時間:** 2026年4月17日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13943)**

---

### No. 69: YouTube 縮圖 - 金色與黑色資訊產品縮圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一個華麗、文字豐富的宣傳橫幅或 YouTube 縮圖，特色包含自信的人物主體以及多個結構化的文字標註。

#### 📝 提示詞

```
{
  "type": "宣傳橫幅 / YouTube 縮圖",
  "style": "高對比、華麗、專業、{argument name=\"theme color\" default=\"金色與黑色\"} 配色、發光射線、閃耀粒子",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"穿著深色西裝、雙臂交叉的自信年輕亞洲男性\"}",
    "pose": "看向右上方",
    "props": "面前有一台發光的筆記型電腦"
  },
  "layout": {
    "background": "深色背景搭配放射狀金色光芒",
    "text_sections": {
      "top_left_badge": "[保存版]",
      "top_header": "{argument name=\"top text\" default=\"從零知識開始也能立即上手！以最短時間掌握 AI 變現能力！\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"AI 副業完全攻略\"}",
        "style": "大型、粗體、3D 金色與白色字體"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"新手也能月入 10 萬\"}",
      "top_right_badge": {
        "style": "金色月桂冠",
        "text": "2026 年最新版"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "堆疊式金邊方框",
        "labels": ["最短時間變現", "附具體範例", "人人皆可上手"]
      },
      "middle_right_ribbon": {
        "style": "紅色緞帶橫幅",
        "text": "完整步驟解析"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "2x3 金邊方框網格",
        "labels": ["推薦工具介紹", "掌握變現流程", "不失敗的入門法", "作業時間最小化", "附帶模板", "高再現性方法"]
      },
      "bottom_footer": "不再迷惘！AI 副業教科書",
      "bottom_right_badge": {
        "style": "金色月桂冠",
        "text": "附帶模板"
      }
    }
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="YouTube 縮圖 - 金色與黑色資訊產品縮圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **來源:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **發布時間:** 2026年4月17日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13903)**

---

### No. 70: 漫畫 / 分鏡腳本 - 溫馨四格夫妻漫畫

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成柔和、浪漫的四格日式漫畫，旨在歌頌夫妻情誼，非常適合用於社群貼文、紀念插畫或以情感為主題的漫畫創作。

#### 📝 提示詞

```
{"type":"四格浪漫漫畫插畫","style":"乾淨的手繪動漫線稿，採用溫暖的米色與淺棕色單色調，柔和的奶油色背景，簡單的陰影，營造舒適溫柔的氛圍，具備社群媒體貼文美學","format":"正方形 2x2 漫畫排版，配有細棕色邊框","headline":{"text":"{argument name=\"headline text\" default=\"夫婦の日\"}","position":"頂部中央","decorations":{"count":2,"items":["左側小愛心","右側小愛心"]}},"panels":[{"panel":1,"count":2,"scene":"年輕夫妻的站立肖像","composition":"丈夫站在妻子身後，一隻手搭在她的肩膀上，兩人神情平靜且充滿愛意","characters":[{"role":"man","appearance":"凌亂的淺棕色頭髮，戴眼鏡，穿奶油色連帽衫，身材高瘦"},{"role":"woman","appearance":"淺棕色頭髮梳成鬆散的低髮髻，臉頰兩側留有髮絲，穿白色長袖襯衫，外搭暖棕色針織背心，可見肩背包背帶"}],"text":["今日は","夫婦の日！"],"decorations":{"count":3,"items":["小愛心","小愛心","小愛心"]}},{"panel":2,"count":2,"scene":"夫妻在室內一起坐著，手拿馬克杯，相視而笑","characters":[{"role":"man","appearance":"同樣的眼鏡與連帽衫，手拿柔和綠色馬克杯"},{"role":"woman","appearance":"同樣的髮型與穿搭，手拿淺色馬克杯"}],"speech_bubble":{"speaker":"man","text":"いつもありがとう。 一緒にいられることが、 いちばんの幸せだよ。"},"decorations":{"count":4,"items":["小閃光","小閃光","小圓點群","小圓點群"]}},{"panel":3,"count":2,"scene":"夫妻在廚房一起做飯，兩人同時攪拌爐火上的平底鍋","background":"簡單的層架與盆栽，以柔和的素描細節呈現","characters":[{"role":"man","appearance":"同樣的眼鏡與連帽衫"},{"role":"woman","appearance":"同樣的髮髻與多層次穿搭"}],"speech_bubble":{"speaker":"man","text":"これからも、 笑い合って、支え合って、 一緒にいろんな景色を 見ていこうね。"}},{"panel":4,"count":2,"scene":"親密的擁抱，丈夫親吻妻子的額頭，同時扶著她的肩膀","characters":[{"role":"man","appearance":"同樣的眼鏡與連帽衫"},{"role":"woman","appearance":"同樣的髮型與穿搭，依偎在丈夫懷中"}],"speech_bubble":{"speaker":"man","text":"大好きだよ。 これからも、 よろしくね！"},"decorations":{"count":3,"items":["小愛心","小愛心","小愛心"]}}],"footer":{"text":"{argument name=\"footer text\" default=\"いつもそばにいてくれて、ありがとう。\"}","position":"底部中央","decorations":{"count":1,"items":["小愛心"]}},"character_design":{"count":2,"items":[{"role":"husband","hair color":"{argument name=\"hair color\" default=\"light brown\"}","expression":"和善、溫柔、深情"},{"role":"wife","hair color":"{argument name=\"hair color\" default=\"light brown\"}","expression":"溫柔微笑、充滿愛意、略帶羞澀"}]},"rendering_notes":"保持所有文字為日文手寫風格，運用大量留白，保留夫妻紀念貼文所需的甜蜜氛圍，線條應呈現略微鬆散的素描感，而非精緻的墨線"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="漫畫 / 分鏡腳本 - 溫馨四格夫妻漫畫 - Image 1">
</div>

#### 📌 詳情

- **作者:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **來源:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14492)**

---

### No. 71: 漫畫 / 分鏡腳本 - 日文 AI 漫畫展示頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個精緻的四格動漫漫畫頁面，展示了貓娘角色對高品質日文對話的反應，非常適合用於展示 AI 漫畫的文字品質。

#### 📝 提示詞

```
{
  "type": "四格動漫漫畫頁面",
  "style": "乾淨精緻的動漫插畫，溫暖的室內光線，清晰易讀的直式日文對話氣泡，柔和的陰影，生動的漫畫分鏡，細緻的溫馨客廳背景，淺棕色與米色室內裝潢，木地板，沙發，咖啡桌，馬克杯，小盆栽，牆面裝飾畫",
  "format": {
    "page_orientation": "直式",
    "panel_count": 4,
    "reading_flow": "左上，右上，中間寬格，底部寬格",
    "borders": "粗黑漫畫分鏡框"
  },
  "characters": [
    {
      "id": "藍髮貓娘",
      "appearance": "嬌小的 Q 版貓娘，留著短鮑伯頭 {argument name="hair color" default="藍色"}，有呆毛，貓耳內側為白色，蓬鬆的尾巴尖端為白色，大大的琥珀藍色眼睛，小小的尖牙嘴",
      "outfit": "白色領口襯衫外搭橘色毛衣，藍色滾邊，棕色裙子配蝴蝶結腰帶，黃色 X 型髮夾"
    },
    {
      "id": "金髮貓娘",
      "appearance": "充滿活力的貓娘，留著長波浪金髮，貓耳，蓬鬆的尾巴，表情明亮開朗",
      "outfit": "芥末黃色麻花針織毛衣，深棕色格紋裙"
    },
    {
      "id": "白髮女性",
      "appearance": "美麗的女性，留著長白髮，白色貓耳，深小麥色肌膚，金色眼睛，自信冷靜的微笑",
      "outfit": "黑色上衣外搭白色外套，層次感金項鍊與耳環"
    },
    {
      "id": "女僕",
      "appearance": "成年女性，留著長淺金髮，貓耳",
      "outfit": "黑白女僕裝，配有白色蕾絲頭飾與紅色蝴蝶結"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "第一格",
        "position": "左上",
        "count": 1,
        "labels": ["反正日文一定很微妙吧？如果文字不行我可不認可喔"],
        "scene": "藍髮貓娘坐在溫馨客廳的沙發上，一根手指抵著下巴，神情懷疑又好奇，頭頂浮現一個小問號"
      },
      {
        "title": "第二格",
        "position": "右上",
        "count": 1,
        "labels": ["欸欸！GPT Image2 超厲害的喔！"],
        "scene": "金髮貓娘戲劇性地從門口衝進來，背後帶著速度線，雙臂張開，充滿興奮感"
      },
      {
        "title": "第三格",
        "position": "中間寬格",
        "count": 3,
        "labels": ["哇！嚇了一跳！這也太精緻了吧！", "欸欸！GPT Image2 超厲害的喔！ 反正很微妙吧？ 如果文字不行我可不認可喔", "你看！這是我們的對話！"],
        "scene": "藍髮貓娘雙手摀臉露出震驚的表情，金髮貓娘站在旁邊自豪地指著，中間的大型對話氣泡顯示著他們正在討論的日文對話範例"
      },
      {
        "title": "第四格",
        "position": "底部寬格",
        "count": 3,
        "labels": ["進化太快了，已經不會再感到驚訝了呢～", "繪圖畫得很可愛，文字的白邊處理也很完美呢", ""],
        "scene": "前景中，女僕摀著嘴露出驚嘆的表情，白髮女性手抵下巴若有所思地評論；背景中，藍髮貓娘與金髮貓娘在沙發前開心地跳躍慶祝"
      }
    ]
  },
  "text_handling": {
    "language": "日文",
    "balloon_direction": "直式文字排版",
    "emphasis": "確保日文字體清晰、自然，並完美融入漫畫對話氣泡中，必要時使用文字白邊效果"
  },
  "tone": "俏皮、慶祝、對 AI 生成漫畫中高品質日文渲染感到驚艷",
  "quality": "細節豐富，角色設計連貫，可愛且具備閱讀性的宣傳漫畫"
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="漫畫 / 分鏡腳本 - 日文 AI 漫畫展示頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **來源:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14471)**

---

### No. 72: 漫畫 / 分鏡腳本 - 優雅動漫劍士 4 格設定集

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成一張高細節的四格動漫角色插圖，主角為一位高貴的白髮劍士，非常適合用於奇幻主視覺、角色展示或高品質社群媒體貼文。

#### 📝 提示詞

```
一張精緻的動漫奇幻插圖設定集，以 2x2 網格呈現同一位優雅劍士的 4 格畫面。角色為一位年輕女性，擁有一頭極長的鉑金白髮，紮成高馬尾並繫著巨大的深海軍藍色蝴蝶結，髮絲柔軟且帶有流動感；皮膚白皙，五官精緻細膩，雙眼呈現明亮的紅粉色。她身穿華麗的白藍配色哥德式貴族禮服：白色高領荷葉邊襯衫配有蕾絲飾邊與金色刺繡，胸前飾有巨大的海軍藍蝴蝶結及紅寶石胸針，泡泡袖配有緞帶袖口，深海軍藍色束腰馬甲帶有金色細節，蓬鬆的深海軍藍色裙擺裝飾著金色花紋、層疊荷葉邊與緞面光澤。她攜帶一把帶有深色劍柄與金色裝飾的武士刀。第 1 格為胸部以上的特寫肖像，身體略微側轉，頭髮在深色閃爍的夜空背景下散發出戲劇性的邊緣光。第 2 格為動態上半身動作鏡頭，角色正將劍拔出或水平展示給觀眾，髮絲狂野飄動，背景為電影感的城市夜景散景與飄落的花瓣。第 3 格為全身時尚肖像，優雅地站在明亮且具反射感的大廳中，周圍環繞著高聳的發光結構，完整呈現禮服輪廓、帶蝴蝶結的高跟鞋以及身側的佩劍。第 4 格為日出或日落時分在波光粼粼的海邊拍攝的四分之三背影，角色回眸望向鏡頭，背景為溫暖的粉彩色天空與閃爍的海面，櫻花瓣在微風中飄落。採用超細節動漫渲染、輕小說封面級別的高品質、複雜的布料紋理、光澤高光、金色裝飾、柔和光暈、戲劇性背光、飄浮花瓣、閃爍粒子，營造出優雅浪漫的氛圍，並保持海軍藍、白、金、淡粉色的色彩和諧。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="漫畫 / 分鏡腳本 - 優雅動漫劍士 4 格設定集 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **來源:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14413)**

---

### No. 73: 漫畫 / 分鏡腳本 - Countryball 荷姆茲海峽對峙

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一幅幽默的地緣政治 Countryball 迷因插圖，描繪了美國與伊朗 Countryball 在狹窄的荷姆茲海峽對峙的場景，非常適合社論諷刺或社群媒體評論。

#### 📝 提示詞

```
一幅細緻的諷刺性 Countryball 迷因插圖，描繪了 {argument name="waterway name" default="荷姆茲海峽"} 作為兩座陡峭岩壁之間極其狹窄的海上通道，採用精緻的數位卡通風格，具有戲劇性的陰影和岩石紋理。在中央前景處，恰好有 2 個 Countryball 在狹窄的航道中互相阻擋，導致只有一方能通過。左側是美國 Countryball，表情憤怒且雙眼瞇起，身上繪有美國國旗，頭戴深海軍藍色棒球帽，帽上以白色大字標示「USA」。右側是伊朗 Countryball，表情憤怒且雙眼瞇起，身上繪有伊朗國旗與國徽，頭戴一條側邊繫結的綠白相間頭帶；頭帶上印有韓文「저항은 우리의 권리」（抵抗是我們的權利）。每個球體上方各有 1 個帶有粗黑邊框的白色對話框，總共 2 個對話框，且兩者皆以粗體韓文寫著 {argument name="speech text" default="길!"}（路！），彷彿雙方都不願退讓。畫面呈現兩球在瓶頸處鼻尖對鼻尖對峙的場景。左側懸崖上，包含 1 個寫有韓文與英文的木製告示牌：「호르무즈 해협」與「Strait of Hormuz」。右側懸崖上，包含 1 個頂部帶有波斯文、下方有紅色警告三角形的警示牌，表示僅限一人通過。左下角放置 1 個標示為「OIL」的黑色油桶，周圍有深色的溢油。右下角放置 1 個帶有波斯文且連接著鐵鍊的黑色水雷。在狹窄通道後的背景中，展示開闊的海域以及 3 艘遠處的船隻，包括至少 1 艘大型油輪，天空中隱約可見深色煙霧升起。採用緊張而幽默的地緣政治迷因基調、居中構圖、視線水平視角、柔和的日光、略顯柔和的寫實色彩、清晰的輪廓，並確保所有文字皆具備高可讀性。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="漫畫 / 分鏡腳本 - Countryball 荷姆茲海峽對峙 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **來源:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14683)**

---

### No. 74: 漫畫 / 分鏡腳本 - 蒙眼術士勝利姿勢

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張充滿戲劇張力的垂直動漫動作海報，主角為一位蒙眼的白髮術士，伴隨爆發性的藍色能量與醒目的漫畫對話框，非常適合用於風格化角色藝術或粉絲創作視覺圖。

#### 📝 提示詞

```
一張極具衝擊力的少年漫畫風格插畫，描繪一位強大的白髮術士，採取戲劇性的低角度全身姿勢，仰頭大笑且嘴巴大張，身穿俐落的黑色高領制服，雙眼覆蓋著黑色眼罩。他的左手向觀眾伸出並比出「YA」的勝利手勢，透過強烈的透視法使手部在前景顯得巨大，而右手臂則自然垂在身側。周圍環繞著爆發性的 {argument name="energy color" default="電光藍"} 超自然能量、狂野的筆觸式氣場軌跡、飛散的碎片、火花以及橫跨畫面的彎曲流線。背景應為深色、抽象且混亂的能量爆發，伴隨發光的藍色碎片與速度線，營造出壓倒性的力量感。採用大膽的賽璐珞動漫渲染，結合繪畫感的高光、銳利的線條、強烈的對比，以及黑色服裝上富有光澤的布料皺褶。在右側加入 1 個帶有粗黑邊框的巨大鋸齒狀白色漫畫對話框，內含 {argument name="speech bubble text" default="LUDDITES ALWAYS LOSE!"} 文字，使用巨大的仿舊黑色大寫字母呈現。垂直構圖，動態動作海報取景，展現自信勝利的態度，現代黑暗奇幻動漫美學。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="漫畫 / 分鏡腳本 - 蒙眼術士勝利姿勢 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **來源:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14637)**

---

### No. 75: 漫畫 / 分鏡腳本 - 月面錢湯喜劇漫畫頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一頁描繪月球上異想天開錢湯的復古未來風動漫漫畫頁，非常適合用於生成具有多個角色導向分鏡的趣味 AI 漫畫場景。

#### 📝 提示詞

```
這是一頁色彩豐富的日式漫畫，場景設定在月球上一座異想天開的公共錢湯，採用精緻的復古未來風動漫風格繪製，具有溫暖的燈光、厚實清晰的分鏡邊框、生動的擬聲詞以及細節豐富的環境敘事。場景是一座名為「月面銭湯 つきのゆ」的月球溫泉，設有大型發光入口招牌、印有白色「ゆ」字的藍色暖簾、外露的管道、儀表、圓潤的建築結構，以及一個可以看到月球表面和太空中地球的巨大圓形窗戶。請包含 8 個以動態頁面佈局排列的漫畫分鏡。分鏡 1：月球錢湯的外觀建立鏡頭，帶有「月面銭湯 つきのゆ」招牌、寫著「重力 1/6」的小招牌、標示「牛乳」的紅色牛奶自動販賣機、狸貓雕像、月球地形以及宣傳錢湯的垂直旗幟。分鏡 2：一位年輕的女性機械師錢湯員工，設定為 {argument name="character design" default="棕色馬尾綁著紅色圓點頭巾，穿著綠色工作連身褲，繫著工具腰帶，表情充滿活力"}，正在調整機器或鍋爐控制裝置，從背面或側面視角呈現，對話框內容關於準備今天的熱水和鍋爐狀況。分鏡 3：一位可愛的外星顧客，設定為 {argument name="alien appearance" default="圓潤的薄荷綠身體，紫色斑點，睡眼惺忪，粉紅臉頰，小嘴，頭上頂著印有紫色星星的白色毛巾"}，在冒著熱氣的浴池中放鬆，半身浸在水中，旁邊漂浮著一隻小黃鴨，木牌上寫著「ぬるめ じっくり リラックス」。分鏡 4：一個小型清潔機器人，設定為 {argument name="robot design" default="銀色身體，藍色點綴，黑色數位臉孔配上發光的藍色眼睛，紅色天線燈，細長的機械手臂和腿"}，正拿著掃帚和水桶快樂地刷地板，旁邊掛著寫有「清掃中」的牌子。分鏡 5：同一個機器人突然滑倒或戲劇性地濺入浴池中，伴隨著巨大的水花、許多氣泡、巨大的擬聲詞「ぽわぁ〜ん!!」，員工在旁邊露出驚訝的表情。分鏡 6：員工坐在浴池旁微笑，手裡拿著一瓶標示「月面牛乳」的飲料。分鏡 7：浴池中的外星人豎起大拇指，手裡拿著一瓶標示「月面フルーツオーレ」的飲料，看起來非常滿足，小黃鴨依然在旁邊。分鏡 8：開朗的機器人拿著清潔工具和水桶在浴池旁擺姿勢，旁邊是標有「ゆ」的浴簾和標示「つきのゆ」的粉紅色臉盆，說著這裡的澡堂最棒了。全程保持溫馨、喜劇的基調，將復古昭和風錢湯細節與太空科技、光澤感的瓷磚表面、蒸汽、氣泡以及可愛的角色互動相結合。這部漫畫應該給人一種關於在月球錢湯工作的迷人生活喜劇漫畫的感覺。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="漫畫 / 分鏡腳本 - 月面錢湯喜劇漫畫頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **來源:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14697)**

---

### No. 76: 漫畫 / 分鏡腳本 - 角色設計參考表

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

為特定角色生成一份包含關鍵資訊與視覺參考的綜合設計表。

#### 📝 提示詞

```
為 {argument name="character" default="Hermes Agent"} 建立一份角色設計表，並包含關鍵資訊
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="漫畫 / 分鏡腳本 - 角色設計參考表 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Neo](https://x.com/NeoAIForecast)
- **來源:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14324)**

---

### No. 77: 漫畫 / 分鏡腳本 - 獨立漫畫頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

為兒童故事量身打造，創作現代獨立風格的漫畫版面。

#### 📝 提示詞

```
一頁 {argument name="comic style" default="現代獨立漫畫"} 風格的漫畫，主題為：{argument name="story topic" default="適合 6 歲兒童的故事"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="漫畫 / 分鏡腳本 - 獨立漫畫頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [宝玉](https://x.com/dotey)
- **來源:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14310)**

---

### No. 78: 漫畫 / 分鏡腳本 - 彩色少年漫畫頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一份詳細的敘事提示詞，用於生成具有特定角色與品牌細節、且具備實體質感的漫畫頁面。

#### 📝 提示詞

```
製作一頁 {argument name="manga type" default="彩色日本少年冒險漫畫"} 的範例。頁面應生動地描繪我們的主角發現了 {argument name="item" default="魔法羽毛筆"} 的情節。這支羽毛筆的名字叫做 {argument name="item name" default="Quill of GPT Image"}。請營造戲劇性，這支魔法羽毛筆內封印著強大的力量。

額外說明：長寬比：直式 1440x2560。筆上應印有 OpenAI 的標誌。漫畫中的語言應全程使用日文。請先仔細構思，以確保這是一個好的故事，並具備良好的漫畫分鏡。頁面應呈現為實體漫畫頁面的照片，而非數位頁面。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="漫畫 / 分鏡腳本 - 彩色少年漫畫頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [宝玉](https://x.com/dotey)
- **來源:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14311)**

---

### No. 79: 漫畫 / 分鏡腳本 - 四格浪漫喜劇漫畫頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成帶有日文對話的單色四格漫畫頁面，非常適合創作充滿戲劇性與角色生動表情的浪漫喜劇辯論場景。

#### 📝 提示詞

```
創作一頁黑白漫畫，包含 4 個垂直堆疊的橫向分鏡格、乾淨的黑色間隔線、網點陰影、戲劇性的速度線以及精緻的青年漫畫風格線條。頁面中包含兩名身著現代休閒服裝、留著深色短髮的年輕動漫角色，兩人的臉部區域均以柔和的方形模糊遮罩處理。第 1 格：一名留著凌亂深色短髮、穿著襯衫的纖瘦年輕人，一隻手握拳靠近胸口，身體向左傾斜，背景環繞著強烈的火焰光暈效果，表情激動且充滿防備。在右側放置一個大型鋸齒狀垂直對話框，內含以下日文文字：「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」。第 2 格：另一名身材稍高、留著深色短髮、內搭淺色襯衫外罩深色拉鍊外套的年輕人，冷靜地舉起一根食指，彷彿正在解釋某個觀點。在右側添加一個圓角矩形對話框，內含以下日文文字：「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」。第 3 格：身材較高的角色溫柔地輕拍較矮角色的頭部；在手部附近加入一個小小的「ポン」擬聲詞。較矮的角色驚訝地抬頭看著對方。在右側添加一個大型橢圓形垂直對話框，內含以下日文文字：「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」。第 4 格：特寫較矮的角色，臉頰泛紅、眼睛呈現漩渦狀、冒著汗珠、表情顫抖、張大嘴巴，臉頰上有密集的陰影線，顯得極度害羞。背景填滿戲劇性的放射狀速度線。在右側添加一個大型鋸齒狀垂直對話框，內含以下日文文字：「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」。加入兩個擬聲詞：肩膀附近的小型「プル…」以及左下角較大且顫抖的手寫體「カァァァ」。整頁保持單色，風格高度生動且具備浪漫喜劇漫畫調性，在激烈的爭論、冷靜的解釋、調情的愛意與害羞的結局之間形成強烈的對比。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="漫畫 / 分鏡腳本 - 四格浪漫喜劇漫畫頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **來源:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14468)**

---

### No. 80: 漫畫 / 分鏡腳本 - Velvedia 角色參考圖

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

用於生成機甲風格角色 Velvedia 角色參考圖的簡短提示詞。

#### 📝 提示詞

```
{argument name="character name" default="Velvedia"} 參考圖
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="漫畫 / 分鏡腳本 - Velvedia 角色參考圖 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="漫畫 / 分鏡腳本 - Velvedia 角色參考圖 - Image 2">
</div>

#### 📌 詳情

- **作者:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **來源:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **發布時間:** 2026年4月21日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14368)**

---

### No. 81: 漫畫 / 分鏡腳本 - 8 格 GPT-Image-2 漫畫宣傳頁

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞用於生成一張葡萄牙語黑白漫畫風格的 8 格漫畫頁，旨在以社群媒體友善的宣傳格式發布並介紹 GPT-Image-2。

#### 📝 提示詞

```
{"type":"8 格漫畫風格宣傳頁","theme":"GPT-Image-2 發布公告","language":"葡萄牙語","style":{"rendering":"黑白漫畫，帶有網點陰影、速度線、光澤高光、粗黑墨線、乾淨的數位漫畫質感","mood":"令人興奮、資訊豐富、樂觀、科技感","page_format":"單頁分為 8 個矩形格，採用 2 欄 4 列的網格佈局，帶有細邊框"},"characters":[{"id":"host girl","role":"主要主持人","appearance":"可愛的動漫少女，留著長黑髮，大而有神的眼睛，穿著胸前印有 OpenAI 結標誌的深色連帽衫","count":1},{"id":"robot mascot","role":"友善的助手吉祥物","appearance":"小型圓形機器人，黑色螢幕臉，眼睛發光，簡潔的白色身體，細小的手臂，表情愉悅","count":1},{"id":"creator group","role":"受眾範例","appearance":"4 位不同的年輕創作者：一位設計師、一位拿著平板電腦的開發者、一位拿著相機的攝影師、一位帶著筆電並穿著連帽衫的人","count":4}],"layout":{"sections":[{"title":"CHEGOU! GPT-IMAGE-2","position":"左上","count":1,"description":"戲劇性的英雄登場格，動漫少女向觀眾伸出一隻手，背景有放射狀速度線","text":["CHEGOU!","GPT-IMAGE-2","A NOVA GERAÇÃO DE IMAGENS POR IA DA OPENAI!","MAIS CRIATIVIDADE, MAIS PRECISÃO, MAIS POSSIBILIDADES!"]},{"title":"O QUE É O GPT-IMAGE-2?","position":"右上","count":1,"description":"少女半身姿勢，指向旁邊發光的圖像圖示，背景為星空科技感圖案","text":["O QUE É O GPT-IMAGE-2?","É nosso novo modelo de geração de imagens, mais inteligente, mais fiel ao que você imagina e com qualidade surpreendente!"]},{"title":"MAIS REALISMO. MAIS DETALHES.","position":"中左（第 2 列）","count":1,"description":"對比格，並排顯示 2 張風景圖，均為山湖場景，左側標註舊模型，右側標註新模型，呈現更豐富的真實感","subsections":[{"label":"ANTES (DALL·E 3)","count":1},{"label":"AGORA (GPT-IMAGE-2)","count":1}],"text":["MAIS REALISMO. MAIS DETALHES.","ANTES (DALL·E 3)","AGORA (GPT-IMAGE-2)","TEXTURAS MAIS RICAS, LUZ MAIS NATURAL, DETALHES INCRÍVEIS!"]},{"title":"COMPREENSÃO MELHOR, RESULTADOS MELHORES.","position":"中右（第 2 列）","count":1,"description":"少女雙手合十，旁邊有框起來的提示詞範例，機器人吉祥物向上指","text":["COMPREENSÃO MELHOR, RESULTADOS MELHORES.","O GPT-IMAGE-2 entende melhor objetos, textos, composições e instruções complexas!","EXEMPLO DE PROMPT:","\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\""]},{"title":"CRIATIVIDADE SEM LIMITES.","position":"左下（第 3 列）","count":1,"description":"少女在 2x2 的 4 種生成藝術變體展示旁說話","subsections":[{"label":"gothic castle scene","count":1},{"label":"modern city street at night","count":1},{"label":"anime character portrait","count":1},{"label":"abstract geometric composition","count":1}],"text":["CRIATIVIDADE SEM LIMITES.","De estilos artísticos a layouts profissionais, do realista ao abstrato: suas ideias, do seu jeito!"]},{"title":"TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","position":"右下（第 3 列）","count":1,"description":"機器人吉祥物展示海報排版的對比圖，兩者之間有粗箭頭","subsections":[{"label":"ANTES","count":1},{"label":"AGORA","count":1}],"text":["TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","Geração de texto mais precisa, legível e integrada ao design!","ANTES","AGORA","AVENTURA COMEÇA AQUI","A AVENTURA COMEÇA AQUI"]},{"title":"PARA TODOS OS CRIADORES.","position":"底部左側","count":1,"description":"合照，主持人少女與 4 位創作者並肩站立，代表不同職業","text":["PARA TODOS OS CRIADORES.","Designers, desenvolvedores, educadores, marketers, artistas e curiosos: todo mundo pode criar mais e melhor!"]},{"title":"GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","position":"底部右側","count":1,"description":"結尾英雄格，少女眨眼並比出讚的手勢，機器人吉祥物在旁，背景有明亮的慶祝光芒與閃光","text":["GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","IMAGINE. CRIE. INSPIRE.","O FUTURO DA CRIAÇÃO É AGORA. ❤"]}],"panel_count":8},"composition":{"reading_order":"從左到右，從上到下","camera_variety":"混合了特寫英雄鏡頭、中景主持人鏡頭、對比圖表和群體鏡頭","graphic_elements":["對話框","圓角黑色標題橫幅搭配白色大寫字母","閃光","速度線","星空科技背景","對比箭頭","帶框範例卡片"]},"text_style":"全大寫葡萄牙語漫畫字體，粗體標題，清晰的對話框，宣傳資訊圖表與漫畫的結合","quality":"高解析度編輯漫畫海報，清晰的排版，平衡的格間距，強烈的對比度","prompt":"創作一張灰階漫畫風格的 8 格宣傳漫畫頁，用於發布 {argument name=\"product name\" default=\"GPT-IMAGE-2\"}。使用單頁 2 欄 4 列的佈局，包含 8 個獨立格，全文使用葡萄牙語。主角為一位開朗的動漫少女，留著 {argument name=\"hair color\" default=\"深棕色\"} 長髮，穿著印有 OpenAI 標誌的深色連帽衫，以及一個友善的小型機器人吉祥物。第 1 格：戲劇性的發布揭幕，少女向鏡頭伸出手，放射狀速度線，標題 \"CHEGOU! {argument name=\"headline name\" default=\"GPT-IMAGE-2\"}\" 以及關於新一代 AI 圖像的發布文案。第 2 格：說明格，少女指向星空數位背景上發光的圖像圖示，標題 \"O QUE É O GPT-IMAGE-2?\" 以及描述其為更聰明的圖像生成模型的對話框。第 3 格：真實感對比，精確顯示 2 張並排的山湖風景圖，分別標註 \"ANTES (DALL·E 3)\" 和 \"AGORA (GPT-IMAGE-2)\"。第 4 格：理解力提升格，包含少女與機器人，並附上一個使用 {argument name=\"example prompt\" default=\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\"} 的帶框提示詞範例。第 5 格：創意展示，包含 4 個縮圖：哥德式城堡、夜間城市、動漫肖像、抽象幾何藝術。第 6 格：文字渲染對比，包含 2 個標註 \"ANTES\" 和 \"AGORA\" 的海報變體，展示改進後的排版，對比 \"AVENTURA COMEÇA AQUI\" 的原始與修正版本。第 7 格：受眾格，包含 4 位來自不同領域的創作者站在一起。第 8 格：最終慶祝行動呼籲，少女眨眼並比讚，機器人吉祥物歡呼，並附上結尾口號 {argument name=\"closing slogan\" default=\"IMAGINE. CRIE. INSPIRE.\"}。整體頁面需充滿活力、精緻、高度易讀，使用粗體黑色標題條、白色大寫字母、對話框、閃光、網點陰影，並具備強烈的漫畫宣傳海報美學。"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="漫畫 / 分鏡腳本 - 8 格 GPT-Image-2 漫畫宣傳頁 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Diogo Santos](https://x.com/diogosantosbr)
- **來源:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14639)**

---

### No. 82: 漫畫 / 分鏡腳本 - 辦公室漫畫衝突（已馬賽克處理）

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

一頁寫實的黑白漫畫，描繪了激烈的辦公室爭吵轉變為「壁咚」場景，適合用於重現戲劇性的病毒式漫畫風格截圖。

#### 📝 提示詞

```
一頁充滿戲劇張力的青年漫畫風格黑白頁面，採用濃密的網點、銳利的墨線、高對比光影以及富有表現力的日式漫畫排版。頁面包含 4 個堆疊的分鏡格，配有垂直的日文對話氣泡和粗體的擬聲詞，展現了兩名辦公室職員在現代工作空間中的緊張對峙。在第一個分鏡中，一名留著凌亂短鮑伯頭、身材纖細但曲線玲瓏的年輕女性，穿著合身的捲袖襯衫和深色窄裙，憤怒地將一隻手重重拍在桌上，身體前傾朝向讀者，伴隨著爆發性的衝擊線和巨大的鋸齒狀對話氣泡。在第二個分鏡中，一名留著深色亂髮、身材纖細的年輕男子，身穿黑色皮夾克內搭淺色襯衫並戴著項鍊，以冷靜自信的姿勢半身入鏡，一邊說話一邊觸摸自己的臉。在第三個分鏡中，男子將女子逼至牆邊，呈現出親密的「壁咚」姿勢，一隻手臂支撐在她頭部旁邊；她看起來慌亂且緊張，而他在她臉龐附近說話，營造出浪漫喜劇般的氛圍轉折。在底部的分鏡中，俯視視角揭示了辦公室場景：2 名角色站在桌邊，桌上有 1 台電腦螢幕、1 個鍵盤、1 個滑鼠、1 張辦公椅以及散落在磁磚地板上的紙張；女子害羞地蜷縮著身體並微微顫抖，而男子則輕鬆地站在她身旁。包含精確的 4 個分鏡格、總共 4 個可見的對話氣泡，以及隨處可見的日文漫畫字體。在每個分鏡中，為每個角色的臉部加上矩形馬賽克模糊效果，如同為了網路分享而進行的匿名處理。背景細節應包含辦公室牆壁、桌緣、速度線、爆發效果和網點漸層。整體氛圍呈現出從激烈爭吵轉向操弄式調情的過程，如同病毒式傳播的斷章取義漫畫截圖。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="漫畫 / 分鏡腳本 - 辦公室漫畫衝突（已馬賽克處理） - Image 1">
</div>

#### 📌 詳情

- **作者:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **來源:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14477)**

---

### No. 83: 漫畫 / 分鏡腳本 - 量子貓漫畫

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個簡短且具創意的提示詞，用於生成一幅貓咪展現量子物理行為的漫畫分鏡。

#### 📝 提示詞

```
請繪製一幅漫畫，其中 {argument name="subject" default="貓咪"} {argument name="concept" default="表現得像量子粒子一樣"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="漫畫 / 分鏡腳本 - 量子貓漫畫 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Haruhiko Okumura](https://x.com/h_okumura)
- **來源:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **發布時間:** 2026年4月21日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14348)**

---

### No. 84: 漫畫 / 分鏡腳本 - 可愛羊角少女辦公室漫畫頁

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一頁四格柔和色調的奇幻辦公室漫畫，描繪了一位長著羊角的職員與一隻毛茸茸的綿羊，將公文變成一場慵懶舒適的搞笑場景。

#### 📝 提示詞

```
{"type":"四格漫畫頁","style":"柔和粉彩 Q 版動漫風格，溫暖米色與奶油色調，柔和晨光，圓角分鏡框，清晰易讀的日文對話，舒適療癒的奇幻辦公室日常","page":{"orientation":"垂直","panel_count":4,"gutter":"細白間距","border":"圓角棕色輪廓"},"setting":{"location":"小型管理辦公室內部","details":["木質地板","陽光灑落的窗戶","放有文件的辦公桌","木椅","堆滿檔案與書籍的書架","堆疊的紙箱與辦公用品","光影中飄浮的細微塵埃與閃光"]},"characters":[{"role":"主角","appearance":"嬌小的 Q 版羊角少女職員，留著短蓬鬆金色鮑伯頭，一隻藍色眼睛與一隻琥珀色眼睛，小巧的精靈耳，巨大的捲曲羊角，戴著羊臉形狀的蓬鬆羊頭套，穿著白色襯衫、紅色領帶、淡粉色圍裙洋裝，圍裙口袋插著一支小筆"},{"role":"配角","appearance":"圓滾滾且毛茸茸的白色綿羊，臉部小巧，腿部短小，看起來非常柔軟像雲朵一樣"}],"layout":{"sections":[{"title":"第一格","position":"頂部","count":3,"labels":["羊角少女打開辦公室門向內看","小綿羊在她身旁探頭","左側有一個橢圓形對話框，右側有一個小橢圓形對話框"]},{"title":"第二格","position":"中上","count":3,"labels":["羊角少女站在桌邊，一手插腰，另一手指向文件","小綿羊坐在桌旁","左側有一個大型橢圓形對話框"]},{"title":"第三格","position":"中下","count":3,"labels":["毛茸茸的綿羊趴在公文上睡著了","羊角少女從左上角探出頭，表情疲憊","右側有紫色的睡覺狀擬聲詞"]},{"title":"第四格","position":"底部","count":4,"labels":["羊角少女在桌邊睡著，閉著眼睛，臉上帶著淡淡微笑","毛茸茸的綿羊在公文上陪她一起睡","溫暖的陽光從左側窗戶灑入","右下角有一個小型矩形標題框"]}]},"text":{"language":"日文","elements":[{"kind":"speech bubble","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"speech bubble","panel":1,"text":"メェ"},{"kind":"speech bubble","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"speech bubble","panel":3,"text":"…名簿が もふもふに…"},{"kind":"sound effect","panel":3,"text":"Zzz…"},{"kind":"speech bubble","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"caption","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"保持四格漫畫都在同一個辦公室場景以維持連貫性；強調可愛的表情、毛茸茸的質感，以及辦公工作因綿羊與職員一起在公文上睡著而停擺的笑點；確保文件在第二格到第四格中清晰可見；保持冷靜、慵懶且溫馨的氛圍"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="漫畫 / 分鏡腳本 - 可愛羊角少女辦公室漫畫頁 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="漫畫 / 分鏡腳本 - 可愛羊角少女辦公室漫畫頁 - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="漫畫 / 分鏡腳本 - 可愛羊角少女辦公室漫畫頁 - Image 3">
</div>

#### 📌 詳情

- **作者:** [じょにがたロボ](https://x.com/jonigata_ai)
- **來源:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14532)**

---

### No. 85: 漫畫 / 分鏡腳本 - 可愛的四格貓咪吃醋漫畫

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可生成溫馨的手繪四格貓咪漫畫，非常適合用於社群貼文、漫畫風格的幽默內容或療癒的寵物插畫。

#### 📝 提示詞

```
一幅可愛的手繪四格漫畫，採用柔和溫暖的生活化風格，背景為淺奶油色，搭配粗黑的邊框與略帶質感的紙張紋理。使用簡約圓潤的卡通貓咪造型、生動的表情、乾淨的黑色輪廓、柔和的自然色調，以及溫和的日式漫畫呈現方式。左上格：展示 2 隻貓，一隻帶有深色條紋與白色口鼻部的棕色虎斑貓閉著眼睛坐著，看起來很滿足；另一隻大部分為白色、頭部有深棕色斑塊的貓站在旁邊，親暱地舔著虎斑貓的臉頰；在牠們上方加上 2 個黑色小音符，暗示愉快的梳理過程。右上格：展示那隻白底棕斑貓在前景，看向右側站著的一隻小型三花幼貓；在幼貓上方加入一個對話框，內含日文文字「めい」。左下格：展示 3 隻貓在一起，左側的棕色虎斑貓露出驚訝或呆滯的表情，右側的白斑貓看起來很開心，而小型三花幼貓則站在中間前方，抬頭仰望。右下格：棕色虎斑貓的特寫鏡頭，牠獨自面對前方，瞇起黃綠色的眼睛，露出憤怒且吃醋的表情；在臉部附近加上 2 條短促的強調線，右側加上 1 個小型的憤怒符號。保持溫馨與喜劇的氛圍，視覺笑點在於虎斑貓原本享受著梳理，直到新幼貓出現為止。使用平塗色彩、極簡陰影，營造出迷人的日式網路漫畫感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="漫畫 / 分鏡腳本 - 可愛的四格貓咪吃醋漫畫 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Maoku](https://x.com/Maoku)
- **來源:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14503)**

---

### No. 86: 漫畫 / 分鏡腳本 - Moon Mark 冒險漫畫頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個四格奇幻動漫漫畫頁面，描繪了一位銀髮月亮主題少女發現地圖、解開洞穴謎題，並找到通往下一場冒險的魔法邀請函。

#### 📝 提示詞

```
{"type":"四格動漫漫畫頁面","style":"可愛奇幻漫畫插圖，精緻的 gpt-image-2 動漫渲染，色彩鮮豔，線條乾淨，柔和的繪畫風格陰影，奇幻的魔法氛圍","page":{"background":"白色頁面搭配黑色分鏡框","title":"{argument name=\"headline text\" default=\"月之印記大冒險\"}","title_position":"頂部中央","decorations":["標題周圍有小金星","標題右側有新月圖示"],"panel_count":4,"reading_direction":"由上至下"},"character":{"appearance":"年輕動漫少女冒險家，擁有非常長的波浪狀銀髮、白皙皮膚、大而有神的眼睛、纖細的身材","outfit":["黑白配色奇幻連身裙，帶有荷葉邊裝飾","新月髮飾","新月頸圈","露肩袖","棕色皮革背包","深色過膝襪"],"theme":"服裝與道具皆充滿月亮元素"},"panels":[{"position":"頂部","scene":"藍天白雲下的晴朗山間小徑與草地，右側為森林，蜿蜒小徑通往遠方，左側有木製路標","action":"少女站著手持並閱讀一張古老藏寶圖，面向前方","props":["古老地圖","木製路標","背包"],"text":{"sign":"冒險的開端","speech":"{argument name=\"panel 1 speech\" default=\"發現地圖了！今天是大冒險！\"}"}},{"position":"中上","scene":"茂密的叢林遺跡入口，黑暗的洞穴開口由刻有新月符號且覆蓋藤蔓的古老石柱框住","action":"少女從後方四分之三視角小心翼翼地靠近，同時閱讀地圖","props":["地圖","廢棄洞穴入口","茂密植物"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"寶藏應該就在這前面……！\"}","sound_effect":"沙沙聲"}},{"position":"中下","scene":"洞穴遺跡內部，光線昏暗，中央有石祭壇或謎題桌","action":"少女跪在點亮的燈籠旁，伸手觸碰謎題機關而非旁邊的鑰匙孔，一隻圓滾滾的黑色貓咪吉祥物正在旁觀看","props":["散發溫暖光芒的燈籠","刻有圓形符號的石製謎題板","桌上的小金鑰匙","帶有新月標記與珠子項圈的黑貓生物"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"不是鑰匙，只要解開機關就行了！\"}","sound_effect":"閃亮"}},{"position":"底部","scene":"寶藏室，洞穴牆壁鑲嵌著水晶，周圍有漂浮的星光","action":"少女在打開的寶藏箱旁閉眼燦爛微笑，舉起一張紙質邀請函","props":["刻有新月徽章的打開木製寶箱","箱內發光的指南針","寫著「前往下一個冒險」的紙卡","藍色與紫色水晶"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"寶藏是……通往下一場冒險的邀請函！\"}","tag":"待續？"}}]}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="漫畫 / 分鏡腳本 - Moon Mark 冒險漫畫頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ツバサ天九](https://x.com/wing_sky_nine)
- **來源:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14605)**

---

### No. 87: 產品行銷 - 動漫角色品牌識別與周邊商品專案

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一份包含動漫角色的綜合品牌設計專案，內容涵蓋產品包裝、社群媒體模擬圖以及周邊商品排版。

#### 📝 提示詞

```
{
  "type": "品牌識別與周邊商品設計專案",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"柔粉色\"} 與白色",
    "motif": "{argument name=\"motif\" default=\"櫻花\"} 與粉色愛心"
  },
  "character": {
    "description": "留著棕色短鮑伯頭、粉色眼睛、穿著白色連帽衫的動漫少女，帶著溫柔的微笑"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "頁首橫幅",
        "position": "頂部",
        "elements": ["大型主標誌", "副標誌", "櫻花圖案", "右側角色肖像"]
      },
      {
        "type": "產品包裝",
        "position": "中左",
        "elements": ["1 個帶有愛心形狀透明視窗的方形盒子，展示粉色愛心糖果", "盒上的角色插圖", "2 個獨立糖果包裝紙", "5 顆散落的愛心糖果"]
      },
      {
        "type": "宣傳海報",
        "position": "中右",
        "elements": ["角色肖像", "愛心形狀糖果碗", "主標誌", "文字 '4.26 NEW OPEN'", "文字 '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "水平網頁橫幅",
        "position": "中下",
        "elements": ["主標誌", "櫻花", "右側角色肖像"]
      },
      {
        "type": "社群媒體個人檔案模擬圖",
        "position": "左下",
        "elements": ["帶有標誌的頁首圖片", "1 個圓形個人頭像", "帳號 '{argument name=\"social handle\" default=\"@yuonchii\"}'", "1 個追蹤按鈕", "模擬個人簡介文字"]
      },
      {
        "type": "周邊商品系列",
        "position": "右下",
        "count": 9,
        "items": ["1 件印有標誌的白色 T 恤", "1 個印有角色的白色馬克杯", "4 個圓形徽章", "1 個壓克力鑰匙圈", "2 包糖果"]
      }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="產品行銷 - 動漫角色品牌識別與周邊商品專案 - Image 1">
</div>

#### 📌 詳情

- **作者:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **來源:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13547)**

---

### No. 88: 產品行銷 - 深色模式病毒式行銷案例研究登陸頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個全面的深色主題 UI 模型，用於行銷案例研究，包含數據視覺化、時間軸和 3D 插圖。

#### 📝 提示詞

```
{
  "type": "登陸頁面 UI 設計",
  "theme": "深色模式，現代科技感，{argument name=\"primary accent color\" default=\"霓虹紫\"} 與藍色發光點綴，玻璃擬態風格",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "badge": "病毒式行銷活動案例研究"
  },
  "sections": [
    {
      "id": "hero",
      "layout": "左側文字，右側圖片",
      "content": {
        "badge": "案例研究",
        "headline": "{argument name=\"hero headline\" default=\"我們如何創造 1,000 萬+ 的病毒式影響力\"}",
        "subtitle": "3 天引爆網路，協助品牌實現指數級增長",
        "stats_row": {
          "count": 4,
          "labels": ["總觀看次數 {argument name=\"main metric\" default=\"10,240,000+\"}", "互動率 18.7%", "轉換數 3,200+", "執行時間 72 小時"]
        },
        "hero_image": "電影感鏡頭，一人在暗室中看著發光的懸浮影片螢幕，上方有大型播放按鈕"
      }
    },
    {
      "id": "strategy",
      "title": "活動拆解：我們的 3 天執行策略",
      "layout": "包含 3 個步驟的垂直時間軸",
      "steps": [
        {"step": 1, "title": "策略制定", "image": "人們在螢幕上分析數據"},
        {"step": 2, "title": "內容製作", "image": "影片剪輯介面"},
        {"step": 3, "title": "發布與擴散", "image": "手持智慧型手機，顯示社群媒體圖示"}
      ]
    },
    {
      "id": "performance",
      "title": "績效成果：數據驅動的表現",
      "layout": "左側數據卡片網格，右側圖表",
      "left_stats": {
        "count": 4,
        "labels": ["總曝光量 1,000 萬+", "平均 CPM 下降 43%", "新增追蹤者 28,000+", "轉換數 3,200+"]
      },
      "right_charts": {
        "count": 2,
        "items": [
          "折線圖顯示 7 天趨勢，於第 3 天達到 8,320,000 的高峰",
          "水平長條圖顯示平台分佈：TikTok 52%、Instagram 24%、X 15%、YouTube 9%"
        ]
      }
    },
    {
      "id": "keys_to_success",
      "title": "為何能病毒式傳播：成功的 3 大關鍵",
      "layout": "3 張卡片的水平排列",
      "cards": [
        {"icon": "fire", "title": "情感鉤子設計"},
        {"icon": "bullseye", "title": "內容結構設計"},
        {"icon": "antenna", "title": "發布策略執行"}
      ]
    },
    {
      "id": "social_proof",
      "title": "創作者與品牌的信賴之選：他們都在使用 goViralX 實現增長",
      "layout": "左側 Logo，右側見證",
      "left_logos": {
        "count": 8,
        "labels": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
      },
      "right_testimonials": {
        "count": 2,
        "labels": ["SaaS 創辦人引言", "增長經理引言"]
      }
    },
    {
      "id": "cta",
      "title": "準備好引爆病毒式傳播了嗎？：想要獲得同樣的增長效果嗎？",
      "layout": "左側文字與輸入框，右側 3D 插圖",
      "elements": [
        "帶有佔位符文字的輸入框",
        "按鈕：{argument name=\"call to action text\" default=\"獲取專屬增長方案 ->\"}"
      ],
      "image": "3D 發光紫藍色火箭發射"
    }
  ],
  "footer": "Logo 與版權文字"
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="產品行銷 - 深色模式病毒式行銷案例研究登陸頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [开发者Hailey](https://x.com/IndieDevHailey)
- **來源:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **發布時間:** 2026年4月17日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13769)**

---

### No. 89: 產品行銷 - 18 面板吉祥物品牌識別文件

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一份包含 18 個章節的綜合品牌指南與 3D 吉祥物角色設計表，詳細涵蓋從 moodboards 與線稿到 3D 轉身視圖與實體模型的所有內容。

#### 📝 提示詞

```
{
  "type": "18 面板品牌識別與角色設計文件",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"沐阳 MUYANG TEA\"}",
    "industry": "{argument name=\"industry\" default=\"茶飲店\"}",
    "colors": ["{argument name=\"primary color\" default=\"黃色\"}", "{argument name=\"secondary color\" default=\"綠色\"}", "白色", "棕色", "深綠色"]
  },
  "subject": "{argument name=\"character description\" default=\"穿著綠色圍裙的 3D 渲染可愛柴犬吉祥物\"}",
  "layout": {
    "grid": "3 欄 6 列",
    "sections": [
      {
        "title": "01 品牌 DNA 分析 / BRAND DNA ANALYSIS",
        "elements": ["Logo", "5 個色票", "6 個圖示", "目標受眾圖表"]
      },
      {
        "title": "02 概念構思 / CONCEPT MOODBOARD",
        "elements": ["5 張參考照片", "4 個情緒圖示", "設計公式"]
      },
      {
        "title": "03 形態研究 / FORM STUDY",
        "elements": ["4 個 Logo 結構圖示", "4 個演變階段", "4 個輪廓圖"]
      },
      {
        "title": "04 概念探索 / CONCEPT EXPLORATION",
        "elements": ["12 個角色線稿草圖"]
      },
      {
        "title": "05 精細線稿 / REFINED LINE ART",
        "elements": ["3 排帶有比例參考的正視與側視線稿"]
      },
      {
        "title": "06 細節精修 / DETAIL REFINEMENT",
        "elements": ["2 張帶標註的全身渲染圖", "4 個圓形局部特寫"]
      },
      {
        "title": "07 表情設定 / EXPRESSION SHEET",
        "elements": ["11 個 3D 渲染頭部表情"]
      },
      {
        "title": "08 姿勢庫 / POSE LIBRARY",
        "elements": ["9 個全身 3D 渲染姿勢"]
      },
      {
        "title": "09 轉身視圖 / TURNAROUND VIEW",
        "elements": ["5 張全身 3D 渲染圖", "5 張對應的線稿視圖"]
      },
      {
        "title": "10 色彩開發 / COLOR DEVELOPMENT",
        "elements": ["5 排 5 色配色方案", "色彩心理學說明"]
      },
      {
        "title": "11 材質規格 / MATERIAL SPECIFICATION",
        "elements": ["5 個材質樣本", "屬性滑桿", "4 個製造工藝圖示"]
      },
      {
        "title": "12 色彩應用 / COLOR APPLICATION",
        "elements": ["4 種配色渲染圖", "2 種明暗渲染圖", "4 個對比度評級圓圈"]
      },
      {
        "title": "13 構造指南 / CONSTRUCTION GUIDE",
        "elements": ["2 張幾何與網格線稿圖"]
      },
      {
        "title": "14 設計系統規則 / DESIGN SYSTEM RULES",
        "elements": ["最小尺寸圖示", "淨空區域示意圖", "4 個使用範例"]
      },
      {
        "title": "15 資產變體 / ASSET VARIANTS",
        "elements": ["3 種尺寸變體", "3 種線稿變體", "3 個簡化扁平化頭部設計"]
      },
      {
        "title": "16 數位應用 / DIGITAL APPLICATIONS",
        "elements": ["1 個 App 圖示", "2 個社群頭像", "UI 元素", "3 階段動畫循環"]
      },
      {
        "title": "17 實物應用 / PHYSICAL APPLICATIONS",
        "elements": ["絨毛玩具模型", "包裝模型", "周邊商品模型", "店面模型"]
      },
      {
        "title": "18 最終主視覺 / FINAL RENDERING",
        "elements": ["吉祥物手持茶飲的大型高解析度 3D 渲染圖", "Logo", "檔案格式列表"]
      }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="產品行銷 - 18 面板吉祥物品牌識別文件 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Lee Colin](https://x.com/Colin_Leeee)
- **來源:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **發布時間:** 2026年4月16日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13819)**

---

### No. 90: 產品行銷 - 動漫武士遊戲廣告海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

一款華麗的手機遊戲直式廣告，包含兩名身穿西裝的劍客、巨大的武士機甲、遊戲介面 UI、QR Code 以及應用程式商店下載提示，適用於 App 推廣。

#### 📝 提示詞

```
創作一張高衝擊力的直式手機遊戲廣告海報，採用精緻的動漫動作風格，呈現戲劇性的賽博武士奇幻美學，並具備高質感、密集的轉蛋 RPG 宣傳排版。主畫面前景為兩名年輕男性戰士，身穿現代黑色商務西裝並做出充滿侵略性的蹲姿，兩人正向觀眾拔出武士刀。兩人都留著時髦的金髮，五官銳利帥氣，身穿白色襯衫、藍色領帶，動作張力十足，運用誇張的透視法讓手部與劍刃佔據畫面下方。其中一把劍的劍柄處繫著藍色緞帶。在他們身後中央，放置一尊巨大的武士機甲，頭戴華麗的金角，身披層次分明的藍黑色金屬盔甲，雙眼閃爍藍光，背後揹著一把收鞘的長劍，宛如守護神般聳立。背景使用鮮豔的霓虹城市與能量爆發效果，色調包含電光藍、紫、洋紅與金色，並加入光束、火花、花瓣、斬擊特效以及水墨爆炸紋理。在右上角加入一個直式黑色筆觸橫幅，以醒目的白色日文寫著「この刃で、未来を斬り拓け。」。在中下方區域，放置一個巨大的金色日文書法標題，帶有厚重的筆觸與黑色陰影，寫著「切り捨て御免」，橫跨近乎整個畫面寬度。左下方嵌入一個帶有金色邊框的遊戲截圖面板，展示紅色日本寺廟庭院前的夜戰場景，包含 1 名可操作的劍客正在戰鬥、多名敵人、浮動的傷害數值（包括 5324、5329 與 6132）、左側的虛擬搖桿、總共 5 個垂直與底部排列的角色頭像、右側的 3 個圓形技能按鈕，以及頂部顯示時間 01:28 與 WAVE 3/3 的 HUD。右下方放置一個大型黑白 QR Code，並置於白色方形框內。在其下方與側邊，加上帶有藍色描邊的白色粗體日文「今すぐダウンロード」。最底部包含兩個官方風格的商店徽章：左側為 App Store，右側為 Google Play。整體風格：超細緻、精緻的關鍵視覺圖、動態透視、金屬高光、銳利的賽璐珞動漫渲染、高質感手機遊戲行銷海報、強烈的動作能量、電影級光影以及層次豐富的 UI 宣傳排版。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="產品行銷 - 動漫武士遊戲廣告海報 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="產品行銷 - 動漫武士遊戲廣告海報 - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="產品行銷 - 動漫武士遊戲廣告海報 - Image 3">
</div>

#### 📌 詳情

- **作者:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **來源:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14432)**

---

### No. 91: 產品行銷 - Monochrome Infra 品牌工具包專案

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個為虛構基礎設施科技品牌設計的簡約黑白品牌指南與周邊商品展示專案，適用於提案簡報、品牌展示及專業設計樣機。

#### 📝 提示詞

```
{"type":"monochrome brand kit and swag presentation board","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"我們支持那些為 AI 時代打造基礎架構的建設者。","campaign_line":"[ 從零開始，構建未來。 ]","version":"VERSION 1.0"},"style":{"overall":"簡約瑞士風格品牌指南頁面，極簡工業科技美學，僅使用黑、白、灰三色，米白色紙張背景，清晰的攝影棚產品去背圖，細膩陰影，精確網格佈局，編輯級展示","mood":"專業、高端、未來感、專注於基礎設施"},"layout":{"header":{"left":"A16Z INFRA / 品牌工具包與周邊","right":"VERSION 1.0","divider":"虛線水平分隔線"},"sections":[{"title":"01 識別系統","position":"左上","count":3,"labels":["大型標誌字體","品牌宣言段落","括號內的活動標語"]},{"title":"02 色彩系統","position":"右上","count":4,"labels":["暖米白","黑色","炭灰色","柔和灰"]},{"title":"03 字體系統","position":"色彩系統下方","count":2,"labels":["主要字體 -- 等寬字體","次要字體 -- 無襯線字體"]},{"title":"06 周邊商品","position":"底部三分之二","count":16,"labels":["黑色連帽衫正面","黑色連帽衫背面","米白色 T 恤","黑色棒球帽","米白色托特包","6 款方形貼紙/卡片組","黑色螺旋筆記本","黑色馬克杯","黑色水壺","黑色拉鍊收納袋","手持復古遊戲機","盒裝微型積木組","開啟的鍵盤套件盒","雲端鍵帽胸針","堆疊方塊鍵帽胸針","長方形品牌徽章胸針"]}],"footer":{"left":"A16Z INFRA / 品牌工具包","right":"© 2024 A16Z INFRA. 保留所有權利。","divider":"虛線水平分隔線"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"超大型自訂幾何塊狀字標，帶有銳角切割，厚實的黑色字體，分兩行堆疊"}},"palette":{"swatches":[{"name":"暖米白","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"黑色","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"炭灰色","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"柔和灰","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"主要字體 -- 等寬字體","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"次要字體 -- 無襯線字體","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}} ,"swag":{"items":[{"name":"連帽衫正面","color":"黑色","print":"小型胸前標誌"},{"name":"連帽衫背面","color":"黑色","print":"多行宣言列表，內容為 BUILDING THE INFRASTRUCTURE LAYER OF AI，附帶虛線引導線及類別，包括 SYSTEMS, TOOLS, DATA, CLOUD, SECURITY, NETWORKS, DEVELOPER TOOLS"},{"name":"T 恤","color":"米白色","print":"大型置中標誌"},{"name":"棒球帽","color":"黑色","print":"刺繡正面標誌"},{"name":"托特包","color":"米白色","print":"堆疊宣言列表及底部標語 BUILDING WHAT'S NEXT."},{"name":"貼紙/卡片組","count":6,"layout":"2x3 網格","labels":["A16Z INFRA","BUILDING THE INFRASTRUCTURE LAYER OF AI.","EARLY STAGE","SYSTEMS. TOOLS. PLATFORMS.","INFRA","BUILD","DEPLOY","SCALE"]},{"name":"螺旋筆記本","color":"黑色","print":"標誌加上 NOTES FOR BUILDING THE FUTURE"},{"name":"馬克杯","color":"黑色","print":"白色標誌"},{"name":"水壺","color":"黑色","print":"垂直文字 BUILDING WHAT'S NEXT. FROM THE GROUND UP."},{"name":"拉鍊收納袋","color":"黑色","print":"標誌、虛線網格圖案、小型文字 SYSTEMS ONLINE."},{"name":"復古手持裝置","color":"炭黑色","screen":"像素風格城市/基礎設施遊戲畫面，帶有 BUILD、DEPLOY、SCALE 標籤及關卡指示 LEVEL 01"},{"name":"微型積木盒","color":"黑色","print":"A16Z INFRA, INFRASTRUCTURE MICRO BUILDS, COLLECT.CONNECT.SCALE.","contents":"展示於盒子前方的黑、灰、白模組化建築積木模型"},{"name":"鍵盤套件盒","color":"黑色","print":"A16Z INFRA KEYPAD SET BUILD. DEPLOY. SCALE.","keys":8,"labels":["INFRA","BUILD","DEPLOY","SCALE",">_","雲端圖示","晶片/網格圖示","網路圖表圖示"]},{"name":"雲端胸針","style":"帶白色邊框的小型黑色琺瑯徽章"},{"name":"方塊胸針","style":"顯示堆疊等距方塊的小型黑色琺瑯徽章"},{"name":"品牌徽章胸針","style":"帶白色標誌的小型長方形黑色琺瑯徽章"}]},"rendering":{"camera":"正視平鋪與正投影產品專案構圖結合","lighting":"柔和均勻的攝影棚燈光","background":"淺暖米白色紙張","quality":"適合專業品牌展示的高解析度商業樣機"}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="產品行銷 - Monochrome Infra 品牌工具包專案 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Olivier Sauvage](https://x.com/Capitaine)
- **來源:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14563)**

---

### No. 92: 產品行銷 - 韓式米飲品惡搞廣告海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張充滿幽默感且極具視覺衝擊力的惡搞飲料廣告海報，內容為一位類似知名政治人物的代言人正在推廣一款韓式罐裝米飲品。

#### 📝 提示詞

```
創作一張大膽的韓式飲料廣告海報，背景為溫暖的金色液體飛濺效果，並採用戲劇性的商業攝影燈光。畫面展示一位 {argument name="celebrity spokesperson" default="類似 Donald Trump 的年長男性政治人物"} 的半身像，他身穿海軍藍西裝、白色襯衫、亮紅色領帶，胸前別著一枚小型美國國旗徽章，正對著鏡頭露出自信的推銷表情。他的臉部被一塊膚色的扁平矩形遮擋條遮住。他左手以強迫透視法伸向鏡頭前方，拿著一罐黃色的韓式米露飲料，罐身顯眼地標示著韓文，頂部與底部有紅色條紋，主產品文字為「비락 식혜」及「Since 1993」。罐身上還包含較小的韓文說明、底部附近的甜米露圖像，以及容量標示「238 ml (120 kcal)」。他的右手則比出大拇指讚的手勢。

採用充滿活力的復古商業構圖，背景有飛濺的甜米露液體與水珠、發光的金色高光，並使用略微仰角的英雄式取景。在頂部加入 3 組鮮明的標題文字：左上方為手寫風格的黑色小標語「전통의 맛, 한국의 DRINK!」，中央為巨大的做舊粗體韓文主標題，深棕黑色文字寫著「걸죽는 땐?」，鮮紅色文字寫著「비락 식혜!」，右上角則為「비락」品牌標誌，下方附有紅色小字「Since 1993」。加入 2 個說明標籤：左側為帶有小皇冠圖示的黃色圓形印章，文字為「대한민국 국민음료 No.1」；右側為白色對話框，內有手寫韓文「한국이 만든 맛있는 전통!」及紅色英文「I LOVE IT!」。

在底部前景放置 2 種食物元素：左側為裝滿甜米露且漂浮著米粒的黃銅碗，右側為堆滿白米的木碗。在下方中間處，加入 2 行大型毛筆風格的促銷文字，第一行為白色的「달콤하게! 시원하게!」，第二行為白色與黃色交錯的「속까지 시~원하게!」，並帶有充滿活力的黃色底線筆觸。在最底部，加入 3 個圓形功能圖示，並附上韓文說明：「국내산 쌀 엄선된 재료」、「시원하게 갈증해소」及「부드러운 단맛 속 편한 식혜」。在右下角加入微小的免責聲明文字「연출된 이미지입니다」。整體風格需呈現出光澤感、誇張、有趣，且如同病毒式傳播的惡搞印刷廣告般令人信服。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="產品行銷 - 韓式米飲品惡搞廣告海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **來源:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14555)**

---

### No. 93: 產品行銷 - 韓國運動飲料名人廣告海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張風格華麗的韓式補水飲料海報，包含名人代言人、超大尺寸產品瓶身，以及適合商業廣告使用的醒目促銷排版。

#### 📝 提示詞

```
一張風格大膽的韓式飲料廣告海報，採用光澤感商業攝影風格，主角為 {argument name="spokesperson" default="酷似 Donald Trump 的人物"}，身穿深海軍藍商務西裝、白色襯衫並搭配鮮豔的藍色領帶，正面站立於飽和的亮藍色天空背景前，背景點綴著幾朵柔軟的白雲，右側隱約可見包含一座類似帝國大廈的高聳摩天大樓的現代城市天際線。他左手戲劇性地將一瓶冰涼的 {argument name="product name" default="POCARI SWEAT"} 塑膠瓶伸向鏡頭，透過極端的透視縮短法，使瓶身在前景顯得巨大，而人物則略微靠後。瓶身透明且帶有凝結水珠，配有白色瓶蓋，可見瓶內的水，深藍色標籤上印有巨大的白色“POCARI SWEAT”字樣，上方有較小的文字寫著“ION SUPPLY DRINK”。在瓶身、手部及下方前景周圍加入充滿活力的冰凍水花與水滴，以強調清新感與補水效果。將品牌標誌放置於左上角：白色“POCARI SWEAT”字樣及下方彎曲的底線標記。在頂部加入巨大的仿舊白色韓文標題文字，略微傾斜並填滿上半部大部分空間：{argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}。在右下方西裝處，加入一行白色與藍色相間的粗體斜體韓文引言：{argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}。在左下方，垂直排列 3 個圓形效益圖示並附上簡短韓文標籤：水滴圖示搭配“수분 보충”（水分補充）、閃電圖示搭配“전해질 보충”（電解質補充），以及跑步人物圖示搭配“빠른 흡수”（快速吸收）。整體採用高對比度的愛國藍白色調、戲劇性的廣告燈光，瓶身與手部焦點銳利，臉部與背景焦點略微柔和，呈現出充滿活力的高級廣告海報質感。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="產品行銷 - 韓國運動飲料名人廣告海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **來源:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14553)**

---

### No. 94: 產品行銷 - 日本叢林主題樂園惡搞海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一張極具電影感的諷刺性日本虛構叢林恐龍主題樂園廣告海報，非常適合用於惡搞行銷活動、社群媒體視覺素材或模擬宣傳主視覺。

#### 📝 提示詞

```
一張細節豐富的日本惡搞主題樂園廣告海報，採用直式構圖，設計風格融合了戲劇性的夏季旅遊廣告與奢華景點宣傳。背景為熱帶叢林，上方是湛藍天空，點綴著零星雲朵，右上角掛著耀眼的烈日，棕櫚葉則裝飾著頂部邊緣。海報頂端放置一個巨大的 3D 石頭質感日文標題 {argument name="headline text" default="ジャンキリア沖縄"}，下方搭配較小的白色日文副標題：「— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —」。畫面中央是一支直立且略微傾斜的現代智慧型手機，佔據了構圖核心。手機螢幕顯示著米色的門票抽籤等待介面，頂部有叢林剪影，並以粗體日文寫著「整理券抽選中」，中間有一個圓形載入圖示，底部則有較小的文字寫著「結果発表まで30分」以及「※この画面を閉じずにお待ちください」。手機狀態列顯示時間為 10:00。手機後方左側，一隻咆哮的暴龍從叢林枝葉中竄出，張著大嘴，模樣寫實且充滿威脅感。右側則是一座裝飾華麗的金色入口大門，刻有精細雕紋，上方標示「プレミアムパス入口」，通往鋪設紅地毯的尊榮通道。前景與中景處，可見長長的人龍排隊等待入園，遊客們穿著休閒夏裝，戴著帽子、毛巾、背包，並攜帶著陽傘、扇子與水瓶，呈現出極度炎熱與疲憊的氛圍。靠近觀者的幾位遊客臉部經過模糊處理。最左側設有一塊巨大的風化石碑，上面以醒目的紅色日文寫著「待ち時間 180分」。左下方放置 3 塊堆疊的鄉村風木製專案：最上方的牌子有藍色停車場圖示與文字「駐車場 2,000円」；中間的牌子有手機圖示與文字「アプリ必須 ダウンロードしてね!」；最下方的牌子則有恐龍剪影與文字「当選者だけが冒険へ」。右下方沿邊放置巨大的白色垂直書法體日文文案：「待つこと、それが冒険だ。」。右下角附近包含 3 個小型圓形圖示說明，並附上簡短的日文宣傳語：「抽選に選ばれし者だけが、恐竜に会える。」、「スマホの充電が尽きる前に、夢は始まる。」以及「プレミアムな近道も、ご用意しました。」，圖示分別暗示恐龍、手機電量與 VIP 通道。最底部中央加入一條黑色免責聲明欄，以白色小字寫著「このポスターは架空のパロディ広告です」。整體風格追求超寫實、電影感、高對比度、諷刺性，並具備頂級商業海報的精緻質感，核心笑點在於誇張的主題樂園炒作、壓迫性的高溫以及荒謬的排隊冒險體驗。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="產品行銷 - 日本叢林主題樂園惡搞海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **來源:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **發布時間:** 2026年4月22日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14545)**

---

### No. 95: 產品行銷 - 將展示架移至露台

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞將參考的促銷展示架放置在同一戶外場景的木製露台上，以製作逼真的環境廣告模型。

#### 📝 提示詞

```
使用提供的參考圖像，保留相同的花園、池塘、樹木、山坡和木製露台視角，但將裝飾性標誌裝置重新定位，使其站在前景的木製露台上，而不是水中。將其放大並更顯眼地置於鏡頭中央，同時保持逼真的戶外透視感、自然日光和一致的陰影。保持裝置結構為 3 行 3 列，共 9 個圓形標誌面板，安裝在細長的綠色支架上，頂部標題標誌文字為「对着镜子笑一场」。讓面板看起來更具反射性和鏡面感，呈現周圍綠植的逼真倒影，同時保留圓形上的可愛臉部圖案和中文字。最終結果應看起來像是一張逼真的廣告模型或合成照片，展示該裝置正確地放置在場景中。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="產品行銷 - 將展示架移至露台 - Image 1">
</div>

#### 📌 詳情

- **作者:** [肖师傅](https://x.com/xiaojietongxue)
- **來源:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14487)**

---

### No. 96: 產品行銷 - 三款精美行動版登陸頁面

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一套優質的三聯式智慧型手機美妝網站設計模型，非常適合在社群媒體上展示 AI 生成的化妝品品牌登陸頁面概念。

#### 📝 提示詞

```
這是一套精緻的宣傳模型，展示了 3 個並排顯示的直立式智慧型手機螢幕，採用垂直三聯式佈局，每個螢幕皆呈現出針對唇部產品的現代美妝品牌登陸頁面。整體構圖具有編輯感、極簡且高級，專為社群媒體上的行動網頁設計展示而設計。左側面板位於柔和的薰衣草色至腮紅粉色漸層背景上，展示了一款黑色邊框手機，其螢幕呈現的是 {argument name="brand name" default="Kosas"} 的奶油與腮紅粉色系美妝網站。在此面板頂部，優雅的小型襯線字體寫著 {argument name="left headline" default="Fresh Pout."}。手機螢幕頂部配有一張裁切過的特寫美妝圖片，下方為粗體標題「Lips in their fullest expression.」，其中「fullest」採用斜體襯線風格，並配有一個圓角深色行動呼籲按鈕、一排 3 個唇部特寫縮圖、3 個標示為「Plumps」、「Tingles」與「Shines」的功效標籤，以及下方一排 5 個色號或效果圖示。中間面板位於薰衣草色至深紫色的漸層背景上，展示了第二款黑色邊框手機，其登陸頁面更強調排版設計。上方襯線字體寫著 {argument name="middle headline" default="Claude Code"}。螢幕頂部包含一張裁切過的人像圖片，下方為非常巨大的粗體黑色堆疊標題「LIP PULSE.」，以及下方一行粉色斜體手寫風格的「is here.」，並配有一個圓角深色按鈕、一個包含「Lips in their fullest expression.」字樣的深色區塊，以及底部附近的產品網格，內含 6 張排列成 2 行 3 列的色號卡。右側面板位於深海軍藍色紋理背景上，展示了第三款黑色邊框手機，其頁面呈現粉色系電商風格。螢幕上方居中處，等寬白色字體寫著 {argument name="right headline" default="GPT Images 2.0"}。此螢幕顯著展示了產品主視覺區塊，包含品牌名稱「Kosas」、大標題「The Lip Pulse」、向右傾斜的粉色唇蜜管、小型功能圖示、中間附近的 6 個唇彩試色條，以及下方包含更多粉色產品影像的促銷區塊。請保持佈局對稱，精確呈現 3 款手機，每個面板各一，且皆需完整可見並呈垂直方向。運用高端化妝品廣告美學、乾淨的間距、結合襯線與粗體無襯線的時尚網頁排版、柔和的粉色與奶油色 UI 配色、細膩的陰影，以及適合展示 AI 生成行動網站概念的流暢產品設計呈現方式。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="產品行銷 - 三款精美行動版登陸頁面 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Serene Gan](https://x.com/ganserene)
- **來源:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14426)**

---

### No. 97: 產品行銷 - 多產業日本廣告拼貼

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於生成多產業日本廣告拼貼的提示詞，採用當代設計風格，呈現六個不同的產業區塊。

#### 📝 提示詞

```
虛構的日本廣告。採用橫向 6 格版面，展示包含 {argument name="industry list" default="汽車產業（新車發表）、主題樂園（新活動）、美妝產業（新產品）、出版業（暢銷書第一名）、飲料產業（新飲品）以及房地產業（豪華公寓介紹）"} 的廣告。由頂尖創作者以最新流行風格製作。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="產品行銷 - 多產業日本廣告拼貼 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **來源:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **發布時間:** 2026年4月21日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14369)**

---

### No. 98: 產品行銷 - 奢華時尚書籍跨頁

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成一張寫實的俯視照片，呈現一本打開的時尚書籍，內含兩頁高級訂製時裝跨頁，非常適合用於奢華品牌推廣、雜誌樣機或風格宣傳視覺圖。

#### 📝 提示詞

```
一張高端時尚雜誌攝影作品，呈現一本打開的大型精裝雜誌或藝術書籍，平放在乾淨的米白色表面上，從正上方俯視。兩頁跨頁包含 2 張同一位優雅女性的全頁肖像，她的臉部被柔和的方形模糊處理，營造出一種隱私遮蔽的視覺效果。在左頁，她站在淺色石材或混凝土建築牆面旁，身穿一件 {argument name="dress color" default="柔和石板灰"} 的結構感長袖連身裙，配有合身胸衣、圓領、剪裁俐落的接縫以及誇張的雕塑感鐘形裙擺；拍攝角度略低，使她的頸部顯得修長，姿態如雕像般優雅。在右頁，她以背影入鏡，身穿一件戲劇性的 {argument name="second dress color" default="黑色"} 晚禮服，擁有極深的露背設計、寬肩帶和蓬鬆的寬大裙擺，站在昏暗且充滿氛圍感的室內，背景為經典的鑲板牆或門。採用奢華時尚雜誌風格、極簡構圖、柔和色調、柔和的自然光、精緻的陰影、寫實的紙張紋理、可見的書籍裝訂中縫、略微彎曲的頁面以及清晰的印刷細節。整體氛圍精緻、高級訂製、具電影感且低調，宛如頂級時尚雜誌的跨頁內容。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="產品行銷 - 奢華時尚書籍跨頁 - Image 1">
</div>

#### 📌 詳情

- **作者:** [@levelsio](https://x.com/levelsio)
- **來源:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14676)**

---

### No. 99: 產品行銷 - 現代冰咖啡廣告設計

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

這是一個為日本市場設計現代風格冰咖啡廣告的提示詞，強調動態排版效果。

#### 📝 提示詞

```
為 {argument name="product" default="冰咖啡"} 製作一則廣告。設計風格需現代且時尚，靈感來自 {argument name="country" default="日本"}。採用歐式字體進行動態排版。目標受眾：{argument name="target" default="10 至 30 歲"}。長寬比 1:1。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="產品行銷 - 現代冰咖啡廣告設計 - Image 1">
</div>

#### 📌 詳情

- **作者:** [KAWAI](https://x.com/kawai_design)
- **來源:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **發布時間:** 2026年4月21日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14355)**

---

### No. 100: 產品行銷 - ChatGPT 幽默處方藥組合

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

一張寫實的俯視攝影照片，展示了一套為 ChatGPT 設計的日式幽默醫療處方與藥品組合，非常適合作為醫療主題的惡搞道具圖或社群媒體概念藝術。

#### 📝 提示詞

```
一張在溫暖木質桌面上拍攝的寫實產品攝影，展示了 6 件整齊排列成兩行的醫療風格物品，設計為一套給 ChatGPT 使用的日式幽默藥局組合。上排：3 個垂直擺放的白色處方藥袋，帶有藍色印刷邊框和日式醫療排版。下排：2 片鋁箔包裝藥片和 1 個裝有白色粉末的小型透明夾鏈袋，分別對應排列在藥袋下方。紙張與包裝應看起來真實，如同真正的日本診所調劑材料，帶有輕微皺褶、柔和的室內自然光與細緻陰影。

這 3 個藥袋皆完全可見且各不相同。左側藥袋標題為藍色大字：「内用薬」。患者欄寫著「ChatGPT 様」。用法用量註明為每日早晚飯後各服用 1 錠，共 7 天。藥品名稱標題為「【おくすり】」，藥名為「思考安定錠 10mg」，下方附有小字說明，解釋其能抑制失控的思緒與過度的推理輸出。底部日期為「2025年6月5日」。底部診所名稱與地址欄為「AIメディカルクリニック」，附有東京風格地址、電話號碼及藍色醫療十字圖示。

中間藥袋標題為「内用薬」。患者欄：「ChatGPT 様」。用法註明為每日睡前服用 1 錠，共 7 天。藥品名稱標題為「【おくすり】」，藥名為「幻覚抑制錠 5mg」，下方附有小字說明其能改善幻覺傾向。日期同樣為「2025年6月5日」。底部為相同的診所資訊與藍色醫療十字圖示。

右側藥袋標題為「頓服薬」。患者欄：「ChatGPT 様」。用法欄註明用於焦慮、混亂或過度輸出時。用量說明為每次 1 包，必要時服用。藥品名稱標題為「【おくすり】」，藥名為「プロンプト調整散 1g」，下方附有小字說明其能調整過度擬合與提示詞混亂。日期為「2025年6月5日」。底部為相同的診所資訊與藍色醫療十字圖示。

左下物品：1 片銀色鋁箔藥片包裝，內含 10 顆圓形白色藥錠，排列為 2 行 5 列，每顆藥錠上壓印有「10」。鋁箔邊緣重複印刷著「思考安定錠10mg」。前方貼有白色藥局標籤，寫著「ChatGPT 様」、每日早晚飯後各 1 錠的用法說明、條碼、日期「2025/06/05」及診所名稱。

中央物品：1 片銀色鋁箔藥片包裝，內含 8 顆淡黃色圓形藥錠，排列為 2 行 4 列。鋁箔邊緣重複印刷著「幻覚抑制錠5mg」。前方貼有白色藥局標籤，寫著「ChatGPT 様」、每日睡前 1 錠的用法說明、條碼、日期「2025/06/05」及診所名稱。

右下物品：1 個裝有白色粉末的小型透明夾鏈袋。正面白色標籤寫著「プロンプト調整散 1g」，包含「ChatGPT 様」、用於焦慮、混亂與過度輸出的用途說明、用量「1回1包（1g） 必要時」、日期「2025/06/05」及診所名稱。

風格：照片級寫實的紀錄片式產品攝影，喜劇風格的偽處方道具設計，乾淨的日式藥品排版，高易讀性，採用白色、藍色、銀色、米色與木質棕色的中性色調，俯視視角，無人手入鏡，無額外物品，具備真實的印刷質感與包裝細節。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="產品行銷 - ChatGPT 幽默處方藥組合 - Image 1">
</div>

#### 📌 詳情

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **來源:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14537)**

---

### No. 101: 電子商務主圖 - 從藍圖生成攝影棚級產品渲染圖

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 描述

此提示詞可將技術產品圖紙轉換為適用於型錄、工業設計或電子商務展示的極簡風格照片級渲染圖。

#### 📝 提示詞

```
使用提供的參考圖像，將技術工程規格表轉換為同款水母造型廚具架的乾淨攝影棚風格產品渲染圖。保留整體產品設計、半透明藍色圓頂蓋、銀色底座，以及相同的 4 件懸掛式廚具：1 個漏勺、1 個義大利麵撈勺和 2 個湯匙。移除所有藍圖元素，包括爆炸圖、尺寸標註線、標籤、表格、註釋和標題欄。僅展示組裝完成的產品，置於畫面中央，正面朝向，背景為極簡淺灰色，底部為白色平面，採用柔和的漫射光，呈現細膩逼真的陰影與光澤感的高級材質。使其看起來像是一張當代工業設計型錄或電子商務產品攝影照片。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="電子商務主圖 - 從藍圖生成攝影棚級產品渲染圖 - Image 1">
</div>

#### 📌 詳情

- **作者:** [amy](https://x.com/amypretzel)
- **來源:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14690)**

---

### No. 102: 電子商務主圖 - 頂級藍莓產品海報

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成精緻的中式電商藍莓包裝廣告，適用於超市品牌宣傳、產品列表及促銷海報。

#### 📝 提示詞

```
一張採用簡潔中式產品廣告風格的頂級藍莓電商海報。以一個透明塑膠盒裝藍莓作為主體，放置在藍色摺疊布料上，從畫面左下角斜向右側延伸，採用微俯視角度拍攝。包裝必須保持寫實且一致：一個帶有圓角的透明方形容器，裝滿深藍色藍莓，上方貼有大型不規則圓形標籤，配色為白色、淺藍色與深藍色，中央印有特大的藍莓插圖與優雅的中式品牌名稱。讓盒內的果實看起來更大、更飽滿、更新鮮，並帶有細緻的水珠，同時保持藍莓排列的自然感。背景為通透的冰藍色桌面，帶有柔和的雲霧紋理，呈現冷色調日光，周圍散落著幾顆藍莓。在右上角與右下角邊緣加入少量模糊的綠葉，營造清新自然的氛圍。在右上角加入 1 張小型嵌入式圖片，展示原始產品包裝從上方俯視的視角，呈現於溫暖的棕色表面，如同參考縮圖。在左側設計中式促銷排版，包含一個大型深藍色書法標題 {argument name="headline text" default="決茗新"}，隨後是兩行較小的文案：{argument name="subheadline text" default="新鮮藍莓 自然之選"} 與 {argument name="tagline text" default="每一顆都是自然的禮物"}。下方放置 3 個垂直排列的特色圖示，並搭配簡短中文說明：葉子圖示代表自然熟成、水果圖示代表飽滿多汁、愛心圖示代表營養豐富。在左下角附近，加入大型白色筆觸風格中文文字 {argument name="product name" default="藍莓"}、第二行文字 {argument name="benefit text" default="膳食纖維+花青素"}，以及一行小字的淨重標示「125克」。運用冷藍色調、清晰的商業攝影燈光、塑膠蓋上的閃亮高光，呈現頂級超市包裝美學，具備高細節度，將寫實產品攝影與精緻平面設計完美融合。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="電子商務主圖 - 頂級藍莓產品海報 - Image 1">
</div>

#### 📌 詳情

- **作者:** [歸藏(guizang.ai)](https://x.com/op7418)
- **來源:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14655)**

---

### No. 103: 電子商務主圖 - 極簡時尚風格專案穿搭

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此提示詞可生成簡潔的編輯風格穿搭拼貼，具備品牌感造型，適用於時尚靈感專案、社群貼文及數位衣櫥概念。

#### 📝 提示詞

```
在淺灰白色背景上呈現簡潔的編輯風格時尚拼貼，帶有細黑色矩形邊框，設計風格如同極簡主義雜誌的穿搭專案。將穿搭以平鋪攝影風格置中構圖，包含 5 件清晰可見的時尚單品：一件亮色 {argument name="jacket color" default="深紅色"} 拉鍊短版夾克，帶有尖領和彈性下擺，稍微偏左放置並疊加在上方；下方為一件合身 {argument name="top color" default="白色"} 長袖圓領針織衫，露出肩部與袖子；下方為一件蓬鬆的米白色中長版 A 字裙，裙上有均勻分佈的大型黑色圓點；左下方為一個結構感強的小型黑色手提包，帶有短提把與細緻的亮面鱷魚紋質感；右下方為一雙黑色方頭瑪莉珍平底鞋，配有寬帶與銀色金屬環扣。在衣物後方的中間位置，加入超大且極淺灰色的背景文字 {argument name="background brand text" default="MANGO"}，並橫向拉伸。在版面周圍放置較小的黑色時尚品牌標誌：右上角附近放置 {argument name="top right logo" default="MANGO"}，手提包附近及鞋子附近放置「Stradivarius」，裙擺左下方放置「DOLCE & GABBANA」。整體構圖應呈現平衡、時髦且現代的感覺，搭配柔和的攝影棚燈光，無陰影或僅有淡淡的柔和陰影，邊緣剪裁俐落，並具備精緻的社群媒體時尚專案美學。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="電子商務主圖 - 極簡時尚風格專案穿搭 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="電子商務主圖 - 極簡時尚風格專案穿搭 - Image 2">
</div>

#### 📌 詳情

- **作者:** [虎小象](https://x.com/hx831126)
- **來源:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14455)**

---

### No. 104: 電子商務主圖 - 機械鍵盤產品頁面模型

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

此內容為頂級機械鍵盤生成精緻的桌面端電子商務產品頁面，適用於產品設計展示、店面概念及 UI 模型。

#### 📝 提示詞

```
建立一個簡潔現代的電子商務產品詳情頁面，用於名為 {argument name="brand name" default="KeyForge"} 的頂級機械鍵盤品牌，並以白色背景、細緻的淺灰色分隔線及寬敞的間距呈現高保真桌面端網站模型。版面為單一統一的店面場景，包含頂部導覽列、左側產品縮圖列、中央大型產品主圖以及右側購買資訊面板。在頁首，將粗體品牌標誌置於最左側，接著放置 7 個導覽項目，依序為「Keyboards」、「Switches」、「Keycaps」、「Accessories」、「Sale」、「Blog」及「Support」；最右側放置搜尋、帳戶及購物車 3 個圖示，購物車圖示上帶有一個顯示「1」的小型黑色通知徽章。中央展示的主產品為一把 75% 配置的緊湊型機械鍵盤，以略微俯視的角度拍攝於淺灰色展示台上，配備銀色鋁合金外殼、白灰色鍵帽、數個淡紫色點綴鍵，以及右上角的銀色音量旋鈕。左側垂直圖庫包含精確 5 個縮圖：1 個已選取的正面產品照、1 個鍵盤角度視圖、1 個機械軸體特寫、1 個鍵帽紋理特寫，以及 1 個帶有圓形播放圖示的深色影片縮圖。右側產品面板包含一個顯示「NEW」的小型膠囊徽章、粗體大字產品名稱 {argument name="product name" default="KeyForge K75 Pro"}、副標題「75% Mechanical Keyboard」、顯示 4.8 分的五星評級列及「(126 reviews)」、粗體大字價格 {argument name="price" default="$129.99"}，隨後為綠色的「In Stock」狀態，以及一段關於頂級效能、Gasket 結構設計、QMK/VIA 支援及 RGB 燈效的兩句簡短描述。下方包含一個「Switch Type」選擇器，設有 4 個標記為「Cherry MX Red」、「Gateron Brown」、「Gateron Blue」及「TTC Gold Pink」的膠囊按鈕，並預選第一個；一個「Color」選擇器，設有 3 個標記為「White / Purple」、「Black / Gray」及「Navy / Blue」的膠囊按鈕，並預選第一個；一個設為「1」的「Quantity」下拉選單；一個帶有購物車圖示、標記為「Add to Cart」的大型黑色主要按鈕；以及一個帶有愛心圖示、標記為「Add to Wishlist」的空心次要按鈕。在按鈕下方，展示 3 個帶有小型圖示的水平服務亮點：「Free Shipping」及其副標「On orders over $99」、「30-Day Returns」及其副標「Hassle-free returns」，以及「2-Year Warranty」及其副標「Peace of mind」。在下方內容區域，建立一個由細線分隔的雙欄區塊。左側為包含 5 個項目的垂直標籤列表：已選取的「Overview」，接著為「Specifications」、「What’s in the Box」、「Shipping & Returns」及「Reviews (126)」。在標籤右側，放置一個圓角白色功能卡片網格，包含 2 行 3 列共 6 個功能區塊，每個區塊均配有簡單的線條圖示、粗體標題及簡短說明文字：「75% Layout」、「Gasket-Mounted」、「QMK/VIA Support」、「Hot-Swappable」、「RGB Backlighting」及「Premium Build」。在此區域最右側，加入一個包含 8 個項目的規格清單：「Layout: 75% (82 Keys)」、「Switch Type: Cherry MX Red」、「Mounting: Gasket-Mounted」、「Connectivity: USB-C (Wired)」、「Backlight: RGB, South-facing」、「Material: Aluminum Case」、「Dimensions: 322 x 135 x 42 mm」以及最後一項「Weight: 1.25 kg」。採用精緻極簡的產品設計美學、真實的 UI 間距、類似 Inter 或 SF Pro 的簡潔無襯線字體、柔和陰影、細緻圓角、單色圖示以及精緻的新創風格消費電子產品呈現方式。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="電子商務主圖 - 機械鍵盤產品頁面模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **來源:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **發布時間:** 2026年4月21日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14449)**

---

### No. 105: 電子商務主圖 - Skincare E-commerce Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a clean, clinical web design mockup for a skincare brand featuring a hero image, product shot, and feature highlights.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="電子商務主圖 - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 詳情

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **來源:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14278)**

---

### No. 106: 電子商務主圖 - Men's Skincare Website Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a sleek, dark-themed e-commerce landing page mockup for a men's skincare product, featuring a model, product shot, and feature statistics.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="電子商務主圖 - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 詳情

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **來源:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14277)**

---

### No. 107: 電子商務主圖 - Skincare E-commerce Landing Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a structured e-commerce hero banner for skincare products, featuring a model, product shots, feature icons, and statistic cards.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="電子商務主圖 - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 詳情

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **來源:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14276)**

---

### No. 108: 電子商務主圖 - Beauty Product Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a clean, feminine e-commerce landing page hero section for a beauty product, featuring a model, product shots, and structured marketing copy.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="電子商務主圖 - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 詳情

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **來源:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14274)**

---

### No. 109: 電子商務主圖 - Fashion Collection Catalog Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a multi-panel fashion catalog showcasing different products featuring a unified pattern design.

#### 📝 提示詞

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

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="電子商務主圖 - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 詳情

- **作者:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **來源:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14241)**

---

### No. 110: 電子商務主圖 - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 提示詞

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="電子商務主圖 - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 詳情

- **作者:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **來源:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14183)**

---

### No. 111: 電子商務主圖 - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 提示詞

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="電子商務主圖 - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 詳情

- **作者:** [pozitiv4ik](https://x.com/Gc_qube)
- **來源:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14148)**

---

### No. 112: 電子商務主圖 - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 提示詞

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="電子商務主圖 - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 詳情

- **作者:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **來源:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **發布時間:** 2026年4月20日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14225)**

---

### No. 113: 電子商務主圖 - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 提示詞

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="電子商務主圖 - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="電子商務主圖 - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="電子商務主圖 - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="電子商務主圖 - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 詳情

- **作者:** [阿兰AI](https://x.com/alanlovelq)
- **來源:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **發布時間:** 2026年4月20日
- **多語言:** zh

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14134)**

---

### No. 114: 電子商務主圖 - 直播電商介面模型

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一個手機直播購物介面，展示名人販售虛構產品，並包含聊天室覆蓋層與 UI 元素。

#### 📝 提示詞

```
{
  "type": "手機直播電商介面模型",
  "subject": {
    "person": "Elon Musk",
    "clothing": "印有 SPACEX 標誌的黑色 T 恤",
    "pose": "雙手向鏡頭比劃，熱情地進行解說",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "大型顯示螢幕",
    "image": "火星地景，包含星艦 (Starship) 火箭與圓頂棲息地",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"移民火星計畫\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "75.8 萬本場點讚",
        "follow_button": "關注"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "10 萬+",
        "close_button": "X"
      },
      "tags": [
        "帶貨總榜第 1 名",
        "更多直播 >"
      ]
    },
    "product_card": {
      "position": "中右側",
      "status": "講解中",
      "image": "火星圓頂棲息地",
      "title": "{argument name=\"product title\" default=\"火星移民基礎套餐\"}",
      "price": "{argument name=\"product price\" default=\"¥99.00\"}",
      "action_button": "搶"
    },
    "chat_overlay": {
      "position": "左下角",
      "join_alert": "星辰大海 加入了直播間",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"夢想家: 支持馬斯克！！🚀\"}",
        "火星弟弟: 多少錢一位？",
        "科技迷: 太酷了！想去火星！",
        "未來已來: 如何報名？",
        "小火箭: 🌹🌹🌹",
        "宇宙無敵: 講解一下細節",
        "東方不敗: 老馬牛逼！👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "說點什麼...",
      "icons_count": 4,
      "icons": ["購物車", "禮物盒", "愛心星球", "加號"]
    },
    "floating_reactions": {
      "position": "右下角",
      "elements": "漂浮的愛心、讚與笑臉表情符號堆疊"
    }
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="電子商務主圖 - 直播電商介面模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **來源:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **發布時間:** 2026年4月19日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13557)**

---

### No. 115: 電子商務主圖 - 夏季海灘飲料商業攝影

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一張清爽的罐裝飲料與玻璃杯海灘產品攝影場景，包含可自訂的產品文字與天空標語。

#### 📝 提示詞

```
一張明亮、充滿夏日氣息的商業產品攝影照，場景為一張擺放在風化木桌上的清爽飲料。在清晰的前景中，有 1 個高腳玻璃杯，裡面裝著金黃色、氣泡豐富的冰飲，並以 1 片檸檬和 1 枝迷迭香裝飾，旁邊放著 1 個覆蓋著冰涼冷凝水的銀色鋁罐。鋁罐上顯眼地展示了英文文字 {argument name="product name" default="TOKYO HIGHBALL"}，下方有一個金色小星星標誌，罐身印有飲料本身的圖案，底部附近則有日文文字「アルコール分 7%」。罐子右側放著 2 片切開的檸檬。在柔和模糊的背景中，展現了陽光明媚的海灘場景，伴隨著波光粼粼的綠松石色海水與湛藍的天空。背景左側站著 1 位留著棕色長髮的年輕女性，身穿白色無袖上衣與淺藍色裙子，正望向大海。場景上方天空中優雅地浮現著日文文字 {argument name="catchphrase" default="夏、これがいい。"}。整體光線明亮且引人入勝，閃爍的散景與鏡頭光暈強調了完美夏日那種清脆、冰涼且清爽的氛圍。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="電子商務主圖 - 夏季海灘飲料商業攝影 - Image 1">
</div>

#### 📌 詳情

- **作者:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **來源:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **發布時間:** 2026年4月18日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14023)**

---

### No. 116: 電子商務主圖 - 4 格廣告網格概念

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一個 2x2 的網格，包含護膚、食品、旅遊和科技產業的 4 種不同日式廣告。

#### 📝 提示詞

```
{
  "type": "2x2 廣告橫幅網格",
  "layout": "4 個獨立象限，每個象限展示不同產業的廣告",
  "quadrants": [
    {
      "position": "左上",
      "industry": "護膚",
      "visuals": "亞洲女性觸摸臉頰，漂浮的水滴，白色按壓瓶",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "邁向充滿透明感的新自我。",
        "features_count": 3,
        "features_labels": ["高保濕", "預防肌膚粗糙", "美白護理*"]
      }
    },
    {
      "position": "右上",
      "industry": "餐廳美食",
      "visuals": "義大利肉醬麵特寫，撒上起司粉和巴西里，深色調氛圍光",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "期間限定",
        "description": "黑毛和牛波隆那肉醬麵 〜松露香氣〜"
      }
    },
    {
      "position": "左下",
      "industry": "旅遊",
      "visuals": "背著背包的女性面對風景優美的山中湖泊，明亮日光",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "在自然中，讓心靈悸動。",
        "script": "Find your freedom.",
        "banner_details": ["初夏特別活動", "6 月 1 日 (週六) - 6 月 30 日 (週日)", "最高 20% OFF", "多種期間限定特別方案！"]
      }
    },
    {
      "position": "右下",
      "industry": "SaaS 應用程式",
      "visuals": "智慧型手機顯示著包含 4 個行程項目的任務管理應用程式介面",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "設計你的一天。",
        "features_count": 3,
        "features_labels": ["直覺式操作", "可與團隊共享", "隨時隨地存取"],
        "bottom_banner": "現正提供 7 天免費試用！"
      }
    }
  ]
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="電子商務主圖 - 4 格廣告網格概念 - Image 1">
</div>

#### 📌 詳情

- **作者:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **來源:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **發布時間:** 2026年4月18日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13928)**

---

### No. 117: 電子商務主圖 - 電商直播介面模型

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成高度細緻的中文電商直播介面，包含主播、產品盒、即時聊天室及促銷疊加層。

#### 📝 提示詞

```
{
  "type": "電商直播截圖模型",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"外貌神似 Sam Altman 的白人男性\"}",
    "clothing": "深綠色圓領毛衣",
    "action": "一手拿著黑色產品盒，另一手指向該產品",
    "setting": "昏暗的攝影棚，左側設有麥克風，背景有淡淡的「AI」字樣",
    "props": [
      "印有白色 OpenAI 標誌的黑色馬克杯",
      "右側堆疊 4 個黑色產品盒"
    ]
  },
  "product_design": {
    "box_color": "黑色",
    "logo": "橘色星號或放射狀圖案",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Anthropic 官方旗艦店",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"更強推理·更高智能\"}",
      "sub_subtitle": "最強大模型：Opus 4.7 重磅發布！",
      "bullet_points_count": 3,
      "bullet_points": ["超強推理能力", "程式編寫能力巔峰", "複雜任務輕鬆搞定"]
    },
    "top_right_live_status": {
      "viewer_info": "直播中 | 52.8 萬人觀看",
      "promo_banner": "直播專屬福利 限時折扣·錯過不再有",
      "countdown": "倒數計時 00:09:47"
    },
    "middle_right_price_card": {
      "header": "{argument name=\"product name\" default=\"Claude Opus 4.7\"} 直播間專享價",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/百萬 tokens 起",
      "original_price": "原價：¥1.89",
      "button": "立即搶購"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "說點什麼..."
    },
    "bottom_right_banner": {
      "headline": "奧特曼首推！認準 Claude Opus 4.7",
      "subheadline": "更智能 · 更安全 · 更可靠",
      "feature_tags_count": 4,
      "feature_tags": ["強大推理", "程式神器", "安全可靠", "極速響應"]
    },
    "floating_elements": [
      {
        "type": "sticker",
        "position": "產品盒右側中間",
        "text": "{argument name=\"sticker text\" default=\"史上最強 AI 模型！\"}"
      }
    ]
  }
}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="電子商務主圖 - 電商直播介面模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [程序员Left](https://x.com/coder_left)
- **來源:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **發布時間:** 2026年4月18日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13995)**

---

### No. 118: 電子商務主圖 - 藥膳雞湯標籤設計轉換

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

將促銷用的雞肉海報轉換為詳細的產品標籤，並加入一籃特定的藥膳食材與說明文字。

#### 📝 提示詞

```
以 REFERENCE_0 為基礎風格，並保留中央的雞肉插圖，將圖像轉換為藥膳湯包的產品包裝標籤。將雞肉移至右側。將頂部文字替換為醒目且粗體的黑色筆觸標題 {argument name="main headline" default="元氣祛濕 雞煲湯包"} 以及較小的副標題 {argument name="subtitle" default="吃山林土貨 味道當然好!"}。在左側添加一個新的編織籃，內含 6 種不同的食材堆：木質根莖、白色方塊、圓形棕色根莖切片、黃豆、陳皮條以及深紅色紅棗。為這些食材附上 6 個帶有白色文字的小型棕色矩形標籤。在雞肉下方，添加一個圓形的橘色徽章，內含文字 {argument name="ingredients list" default="內含有:五指毛桃、茯苓、土茯苓、黃豆、陳皮、紅棗"}。在底部，設計一個實心的橘色矩形橫幅，包含一個燉鍋圖示、文字 {argument name="usage instructions" default="用法:把湯料清洗乾淨放入鍋中，加入薑片煮 20 分鐘，後加入雞肉再煮 20 分鐘即可。"}，以及一個輔助標語 {argument name="bottom slogan" default="天然好料 滋補好湯"}。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="電子商務主圖 - 藥膳雞湯標籤設計轉換 - Image 1">
</div>

#### 📌 詳情

- **作者:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **來源:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **發布時間:** 2026年4月18日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13993)**

---

### No. 119: 電子商務主圖 - 機庫中的跑車與客機

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

生成一張寫實風格的影像，展示一輛跑車停在反光機庫內的一架商用客機前。

#### 📝 提示詞

```
一張高解析度的寫實商業攝影照片，前景為一輛 {argument name="car model and color" default="亮藍色 Alpine A110 R 跑車"}，停在巨大的飛機庫內。這輛車配備黑色碳纖維引擎蓋、黑色車頂、黑色合金輪圈，前車牌寫著「{argument name="license plate text" default="A110 R"}」。車輛正後方是背景的主體，為一架 {argument name="airplane model" default="白色 Airbus A320 商用客機"}，機尾為藍色。機庫擁有高度拋光且具備反光效果的混凝土地面，倒映出車輛與飛機的身影。左側金屬牆面上的標誌寫著「{argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"}」。機庫大門敞開，露出明亮的陰天與遠處的城市景觀。光線柔和且具電影感，突顯出兩款載具流線型的空氣動力學曲線。
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="電子商務主圖 - 機庫中的跑車與客機 - Image 1">
</div>

#### 📌 詳情

- **作者:** [nazca alwave](https://x.com/AlwaveNazca)
- **來源:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **發布時間:** 2026年4月18日
- **多語言:** en

**[👉 立即嘗試 →](https://gptimage2api.net/?id=14043)**

---

### No. 120: 電子商務主圖 - 逼真的 VTuber 周邊商品模型

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 描述

一個用於 GPT-Image2 的提示詞，旨在生成逼真的 VTuber 粉絲周邊實拍照片。

#### 📝 提示詞

```
為標準的 {argument name="character type" default="Vtuber"} 創作 {argument name="items" default="粉絲周邊"}，風格為 {argument name="style" default="實拍"}
```

#### 🖼️ 生成圖片

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="電子商務主圖 - 逼真的 VTuber 周邊商品模型 - Image 1">
</div>

#### 📌 詳情

- **作者:** [WTR](https://x.com/wtry1102)
- **來源:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **發布時間:** 2026年4月17日
- **多語言:** ja

**[👉 立即嘗試 →](https://gptimage2api.net/?id=13868)**

