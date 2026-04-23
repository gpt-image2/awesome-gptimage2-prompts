
# 🚀 GPT Image 2 プロンプト集


> 🎨 OpenAI GPT Image 2 のクリエイティブなプロンプトコレクション

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Current-brightgreen)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 目次

- [🤔 GPT Image 2 とは？](#-what-is-gpt-image-2)
- [📊 統計](#-statistics)
- [🔥 おすすめプロンプト](#-featured-prompts)
- [📋 すべてのプロンプト](#-all-prompts)

---

## 🤔 GPT Image 2 とは？

**GPT Image 2**（コードネーム **"duct-tape"**）は OpenAI の次世代画像生成モデルです。コミュニティのテストにより、以下の点で大きな進化が確認されています：

- 🎯 **ピクセル精度のテキストレンダリング** — 中国語・英語・日本語すべてネイティブ品質、誤字や字形の歪みなし
- 🎨 **画像間のピクセル一貫性** — 同じキャラクター・スタイル・IP が複数画像間で完全に一致
- ⚡ **商用レベルのイラスト品質** — 手直し不要で商業利用可能なイラスト出力
- 🌈 **真のアートスタイル表現** — 参照画像の模倣ではなく、スタイルの本質を理解して再現
- 🔧 **ストーリーボード・製品シリーズ対応** — ストーリーボード、IP キャラ、製品シリーズ画像など一貫性が必要なシーンに最適
- 📐 **多言語グラフィックデザイン** — SNS カード・バナー・ポスターを多言語タイポグラフィで一発生成

📚 **詳細：** コミュニティテストの [レポート要点](docs/FAQ.md) を参照

### 🚀 Raycast 統合

一部のプロンプトは [Raycast Snippets](https://raycast.com/help/snippets) 構文を使用した**動的引数**をサポートしています。🚀 Raycast Friendly バッジを探してください！

**例：**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

Raycast で使用すると、引数を動的に置き換えて迅速に反復できます！

---

## 📊 統計

<div align="center">

| 指標 | 数 |
|--------|-------|
| 📝 プロンプト総数 | **1123** |
| ⭐ おすすめ | **6** |
| 🔄 最終更新 | **2026年4月23日木曜日 1:28:40 UTC** |

</div>

---

## 🔥 おすすめプロンプト

> ⭐ 優れた品質と創造性のためにチームが厳選

### No. 1: VR ヘッドセット 分解図ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

VR ヘッドセットのハイテクな分解図を、詳細なパーツ説明とプロモーションテキスト付きで生成します。

#### 📝 プロンプト

```
{
  "type": "製品分解図ポスター",
  "subject": "VR ヘッドセット",
  "style": "クリーンなハイテク 3D レンダリング、スタジオ照明、光るアクセント",
  "background": "{argument name=\"background color\" default=\"ソフトなパープルとブルーのグラデーション\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"まったく新しい現実を、まったく新しい構造から。\"}"
  },
  "layout": {
    "centerpiece": "VR ヘッドセットの垂直分解図。外殻、カメラセンサー、チップ搭載マザーボード、パンケーキレンズ、内部フレーム、バッテリーパック、サイドストラップ、トップストラップ、フェイスインターフェースクッションという 9 つの主要パーツを表示。",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\n圧倒的な処理性能でリアルタイムな体験を。",
        "調整可能な IPD 機構\n幅広いユーザーに快適なフィット感を。",
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
        "body": "一つひとつのパーツに、没入体験を支える最先端テクノロジーとこだわりの設計。Meta Quest 3 は、未来を感じさせる体験を内部から生み出しています。"
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="VR ヘッドセット 分解図ポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [wory＠ホッピング中](https://x.com/wory37303852)
- **ソース:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13460)**

---

### No. 2: 街歩きグルメマップ（イラスト版）

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

手描き水彩画風の観光マップを生成します。番号付きの地元グルメ、ランドマーク、凡例が含まれます。

#### 📝 プロンプト

```
{
  "type": "イラストマップ・インフォグラフィック",
  "style": "{argument name=\"art style\" default=\"ヴィンテージ風の羊皮紙に描かれた水彩とインクの手描きイラスト\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"成都\"} {argument name=\"map title\" default=\"グルメ食べ歩きマップ\"}",
    "mascot": "サングラスをかけて親指を立てている、漫画風の赤い唐辛子のキャラクター"
  },
  "border": "{argument name=\"border decoration\" default=\"緑の葉と赤い唐辛子のつるの装飾\"}",
  "layout": {
    "background": "テクスチャ感のあるベージュの羊皮紙。黄色い道路、青い川、緑の公園エリアが描かれている",
    "sections": [
      {
        "title": "ランドマーク",
        "count": 6,
        "illustrations": ["伝統的な東屋", "伝統的な寺院", "パンダが登る近代的な超高層ビル", "高いテレビ塔", "伝統的な門", "工業施設"],
        "labels": ["人民公園", "文殊院", "IFS", "339テレビ塔", "寛窄巷子", "東郊記憶"]
      },
      {
        "title": "グルメスポット",
        "count": 12,
        "illustrations": ["麻婆豆腐", "水餃子（ラー油入り）", "串鍋", "三大炮（もち米菓子）", "蛋烘糕（卵焼きケーキ）", "九宮格火鍋", "酸辣粉", "鉢鉢鶏（冷製串料理）", "冒菜（スパイシー煮込み）", "蓋碗茶", "氷粉（ゼリーデザート）", "麻辣兎頭"],
        "labels": ["1 陳麻婆豆腐", "2 鐘水餃", "3 春熙路", "4 寛窄巷子・三大炮", "5 建設路・葉婆婆蛋烘糕", "6 玉林路・小龍坎火鍋", "7 香香巷・肥腸粉", "8 武侯祠大街・鉢鉢鶏", "9 東郊記憶・冒椒火辣", "10 人民公園・鶴鳴茶社", "11 錦里古街・氷粉", "12 双流老媽兎頭"]
      },
      {
        "title": "凡例",
        "position": "bottom-right",
        "count": 5,
        "items": ["赤い点", "緑の家", "緑の木", "青い線", "黄色い二重線"],
        "labels": ["グルメスポット", "ランドマーク", "公園・緑地", "河川・湖", "主要道路"]
      }
    ],
    "centerpiece": "竹を食べている巨大なパンダ",
    "bottom_right_extras": ["N, S, E, W が記されたヴィンテージ風のコンパスローズ", "免責事項テキスト：『温馨提示：辛いものの食べ過ぎには注意し、胃腸を大切に～』と赤い唐辛子のアイコン"]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="街歩きグルメマップ（イラスト版） - Image 1">
</div>

#### 📌 詳細

- **作者:** [皮皮特](https://x.com/mm_zzm44854)
- **ソース:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13515)**

---

### No. 3: ハイブリッドスタイルで作成する桃太郎の解説用 Slides

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

いらすとやのシンプルで温かみのある美学と、日本の官公庁資料特有の高密度な情報量を融合させるためのプロンプトです。

#### 📝 プロンプト

```
「いらすとや」の柔らかな雰囲気と、「霞が関資料」の圧倒的な情報密度を融合させた、{argument name="theme" default="桃太郎"} の解説用 Slides（{argument name="format" default="ポンチ絵"}）を作成してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="ハイブリッドスタイルで作成する桃太郎の解説用 Slides - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="ハイブリッドスタイルで作成する桃太郎の解説用 Slides - Image 2">
</div>

#### 📌 詳細

- **作者:** [やまもん](https://x.com/yammamon)
- **ソース:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **公開日:** 2026年4月19日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13983)**

---

### No. 4: E-commerce ライブ配信 UI モックアップ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

人物写真に重ねるリアルなソーシャルメディアのライブ配信インターフェースを生成します。カスタマイズ可能なチャットメッセージ、ギフトのポップアップ、商品購入カードを備えています。

#### 📝 プロンプト

```
{
  "type": "ライブ配信 UI モックアップ",
  "subject": {
    "description": "{argument name=\"host name\" default=\"イーロン・マスク\"} のポートレート、笑顔、白い技術図解グラフィックが描かれた黒い T シャツを着用",
    "background": "左側には '{argument name=\"left background logo\" default=\"SPACEX\"}' のテキストが表示されたスクリーン、右側には赤い '{argument name=\"right background logo\" default=\"Tesla T ロゴ\"}' とダークカラーの車"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "アバター、名前 '{argument name=\"host name\" default=\"イーロン・マスク\"}'、サブテキスト '55.6万本場点赞'、赤い 'フォロー' ボタン",
      "rank_badge": "金色のコインアイコンと '全站第1名'",
      "viewer_stats": "上位 3 名の視聴者アバターと '12.3w'、'8.6w'、'5.7w'、合計 '68.7万'、'X' 閉じるボタン",
      "right_links": "'更多直播 >'、'礼物展馆 0/24'（青い '经典' タグ付き）"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "アバター '科技爱好者'、'送小心心'、ハートアイコン x 1314",
        "アバター '星辰大海'、'送火箭'、ロケットアイコン x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "レベル 37 バッジ '宇宙漫游者 加入了直播间'",
      "message_count": 7,
      "messages": [
        "小火箭: マスク！未来に期待！🚀",
        "future: テスラ Model 2 はいつ発売されますか？",
        "星空梦想家: SpaceX は今年火星に行けますか？",
        "AI探索者: Neuralink の進捗はどうですか？",
        "帅气的网友: マスクさん、こんにちは！",
        "Mars: 初めてのライブ配信参加です、超ワクワク！",
        "用户123: AI について話してください、人間を置き換えるのでしょうか？"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "オレンジ色の '热卖 x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"テスラ Cybertruck 電動ピックアップトラック\"}",
      "price": "{argument name=\"product price\" default=\"¥ 1,618,000\"}",
      "button": "赤い '購入' ボタン",
      "floating_animation": "右端を浮遊する半透明のハート"
    },
    "bottom_bar": {
      "input_field": "'何かコメントする...'",
      "icons": ["スマイリーフェイス", "3 点リーダー", "ショッピングカート", "ギフトボックス", "シェア"]
    }
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="E-commerce ライブ配信 UI モックアップ - Image 1">
</div>

#### 📌 詳細

- **作者:** [神经病不想好转](https://x.com/sjbbxhz)
- **ソース:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14036)**

---

### No. 5: アニメ風格闘アクション

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

伝統的な道場で、エレメンタルオーラを纏った 2 人のキャラクターが戦う、躍動感あふれるアニメ風アクションシーンを生成します。

#### 📝 プロンプト

```
伝統的な木造道場で繰り広げられる、激しい格闘戦を描いた躍動感あふれるアニメ風イラスト。手前では、{argument name="character 1 hair" default="赤いリボンで高い位置にお団子にまとめた黒髪"}の少女が、力強いローアングルから拳を突き出す構えをとっています。彼女は{argument name="character 1 outfit" default="赤いタッセルが付いた白いチャイナ風トップスとゆったりとした赤いパンツ"}を着用しており、突き出した四肢の周りには激しい赤いエネルギーの斬撃が渦巻いています。右側の空中では、{argument name="character 2 hair" default="ツインテールのお団子にした薄紫色の髪"}の少女が、{argument name="character 2 outfit" default="金色の刺繍が施されたダークグリーンのドレスと黒いタイツ"}を身にまとい、自信に満ちた笑みを浮かべて優雅に跳躍しており、その周囲には水のような青いエネルギーの軌跡が広がっています。背景には、中央に「{argument name="sign text" default="武術会"}」と書かれた看板が掲げられた素朴な木造寺院の内部が描かれています。舞い上がる砂埃、砕け散る床板、輝くカラフルなパーティクルエフェクト、そしてキャラクターを背景から際立たせるドラマチックなローアングル照明が、シーンに爆発的なアクションの臨場感を与えています。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="アニメ風格闘アクション - Image 1">
</div>

#### 📌 詳細

- **作者:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **ソース:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13467)**

---

### No. 6: 3D 石造階段の進化インフォグラフィック

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

平坦な進化のタイムラインを、詳細な生物のレンダリングと構造化されたサイドパネルを備えた、写実的な 3D 石造階段のインフォグラフィックに変換します。

#### 📝 プロンプト

```
{
  "type": "進化のタイムラインインフォグラフィック",
  "instruction": "REFERENCE_0 を構造のベースとして使用し、フラットなベクターデザインを非常にリアルな 3D インフォグラフィックに変換してください。滑らかなスロープを個別の石の階段に置き換え、すべての生物をフォトリアルな 3D モデルにアップグレードしてください。",
  "style": {
    "background": "{argument name=\"background style\" default=\"ヴィンテージ風のテクスチャ付き羊皮紙\"}",
    "staircase": "{argument name=\"staircase material\" default=\"リアルな質感の石ブロック\"}",
    "subjects": "{argument name=\"organism style\" default=\"非常に詳細なフォトリアル 3D レンダリング\"}"
  },
  "layout": {
    "main_title": "{argument name=\"main title\" default=\"人類の進化\"}",
    "sections": [
      {
        "position": "左サイドバー",
        "count": 8,
        "labels": ["L0: 単細胞生命", "L1: 多細胞生物", "L2: 動物界", "L3: 脊索動物", "L4: 上陸革命", "L5: 哺乳綱", "L6: ヒト科の進化", "L7: ホモ・サピエンスの時代"]
      },
      {
        "position": "右上",
        "title": "獲得した機能 / 失った機能",
        "description": "プラスとマイナスのアイコンが付いた凡例"
      },
      {
        "position": "中央下部",
        "title": "進化の重要なマイルストーン",
        "count": 6,
        "description": "類人猿から人間への進化を示す 6 つのシルエットグラフィックを用いたタイムライン"
      }
    ],
    "centerpiece": {
      "description": "特定の生物を配置した 25 段の番号付き螺旋石階段。",
      "count": 25,
      "notable_elements": [
        "ステップ 07: クラゲ",
        "ステップ 09: アンモナイト",
        "ステップ 10: 三葉虫",
        "ステップ 24: 歩行する人間",
        "ステップ 25: {argument name=\"future evolution concept\" default=\"クエスチョンマークが付いた輝く宇宙的なシルエット\"}"
      ]
    }
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="3D 石造階段の進化インフォグラフィック - Image 1">
</div>

#### 📌 詳細

- **作者:** [知识猫图解](https://x.com/GeekCatX)
- **ソース:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13491)**

---

## 📋 すべてのプロンプト

> 📝 公開日でソート（新しい順）

### No. 1: プロフィール / アバター - オーバーヘッド・ミラー・セルフィーと大げさなポーズ

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

俯瞰（トップダウン）視点からのミラー・セルフィーにおいて、キャラクターの一貫性とダイナミックな表情をテストするためのプロンプトです。

#### 📝 プロンプト

```
{argument name="number of people" default="3 人"} が鏡の前でトップアングルから {argument name="pose type" default="大げさなポーズ"} で集合写真を撮影している様子。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="プロフィール / アバター - オーバーヘッド・ミラー・セルフィーと大げさなポーズ - Image 1">
</div>

#### 📌 詳細

- **作者:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **ソース:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **公開日:** 2026年4月22日
- **言語:** zh

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14341)**

---

### No. 2: プロフィール / アバター - ブラウンのモノトーンで統一したスタジオでの座り姿のポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ブラウンのコーディネートに身を包んだ女性の座り姿を写した、フォトリアルな屋内ファッションポートレートを生成します。エディトリアルライフスタイルやアパレル関連のイメージ画像に最適です。

#### 📝 プロンプト

```
シンプルな黒い折りたたみ椅子に座った、東アジア系の若い女性のフォトリアルなスタジオポートレート。太ももから頭までを捉えた縦構図です。{argument name="hair color" default="ダークブラウン"} の髪はセンター分けに近い位置で分けられ、低い位置でポニーテールにまとめられています。耳元には数本の柔らかな後れ毛があり、小さな繊細なイヤリングを着用。肌はきめ細やかで、両手を膝の間に置いた穏やかでニュートラルなポーズをとっています。服装は、{argument name="top color" default="深いチョコレートブラウン"} のリブ編みジップフロントクロップトップで、ポインテッドカラーと七分袖が特徴です。ジッパーを少し開けて深いネックラインを作り、ボトムスには同系色の {argument name="pants color" default="温かみのあるブラウン"} のハイウエストストレートパンツを合わせています。スタイリングはブラウンで統一したモノトーンで、生地の繊細な質感と自然な体のラインを表現。背景は柔らかなひだのあるオフホワイトの布地で、窓からの自然な拡散光が、清潔感のある柔らかなエディトリアル風の屋内ルックを演出しています。フォトリアル、浅い被写界深度、柔らかな影、控えめなファッションポートレート、ミニマルなセット、中央に配置された被写体、リラックスした座り姿勢、肌と生地の質感まで高精細に再現。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="プロフィール / アバター - ブラウンのモノトーンで統一したスタジオでの座り姿のポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **ソース:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14628)**

---

### No. 3: プロフィール / アバター - フォトリアルな制服姿の神社ポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、屋外で制服を着た若い女性の洗練されたフォトリアルなポートレートを生成します。ファッション誌の編集、キャラクタービジュアル、ライフスタイル系の AI ポートレートに最適です。

#### 📝 プロンプト

```
明るい自然光の下、屋外に立つ {argument name="subject" default="若い女性"} を捉えた、縦構図のフォトリアルなバストアップポートレート。髪は艶やかな光沢のある {argument name="hair color" default="ダークブラウン"} のストレートロングヘアで、センターから少しずらした分け目から両肩に自然に流れている。清潔感のある白い半袖の制服シャツを着用し、襟はしっかりとした作りで、ネイビーブルーのストライプ柄のネクタイを締めている。左胸のポケットには、王冠と紋章がデザインされた精巧な刺繍ワッペンがあしらわれている。ポーズは少し斜め 45 度の角度でリラックスさせ、顔をわずかに横に向けることで、洗練された自然なファッションフォトのような雰囲気を演出する。背景には鮮やかな {argument name="background setting" default="赤い神社の建築物"} を配置し、豊かな赤い柱と湾曲した青い屋根のディテールをぼかして描写する。被写界深度を浅くし、クリーミーなボケ味を加えることで、被写体にピントを鋭く合わせる。ライティングはクリーンでコントラストが高く、被写体を美しく引き立てるものとする。髪やシャツに明るいハイライトを入れ、布地のリアルなシワや自然な肌のトーンを表現し、日本の商業写真のような洗練されたプレミアムなポートレートの美学を追求する。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="プロフィール / アバター - フォトリアルな制服姿の神社ポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [AIおじさん](https://x.com/AIojisan1952)
- **ソース:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14515)**

---

### No. 4: プロフィール / アバター - ムードのあるモザイク加工済み室内自撮りポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、窓辺で開襟シャツを着た若い男性のフォトリアルでスタイリッシュな自撮り写真を生成します。SNS 用のリアルなポートレート作成に最適です。

#### 📝 プロンプト

```
高層マンションやホテルの部屋にある大きなモダンな窓の近くに座る、若い東アジア人男性の胸から上のリアルな室内自撮り風ポートレート。柔らかい自然光が差し込んでいる。髪は {argument name="hair color" default="黒"} で、厚みがあり少し無造作なセンターパート。前髪とサイドに柔らかなボリュームがある。体型は細身で、首が長く、肌は滑らかで明るい。マットなコットンまたはポプリン素材の {argument name="shirt color" default="黒"} のボタンアップシャツを着用。少しオーバーサイズで、上のボタンをいくつか開けて深いオープンカラーを作り、リラックスしたカジュアルなスタイルにしている。カメラは自然な自撮りアングルで近くから構え、縦向きで肩、胸、首、頭部をフレーミングしている。顔は中央に配置された大きな長方形のぼかしやモザイクの検閲ブロックで完全に隠されているが、耳、顎のライン、首、髪は見えている。ムードは控えめで、情緒的かつエレガント。落ち着いたニュートラルカラーで、右側からの柔らかな窓の光と優しい影が、SNS の自撮り写真のような自然な雰囲気を醸し出している。背景には、左側にベージュの壁が 1 面、小さな暗い壁面コントロールパネルが 1 つ、垂直の金属製トリムまたはランプの縁が 1 つ、右側に暗いフレームの背の高い窓パネルが 2 枚あり、外にはピントの合っていないかすかな街のスカイラインが見える。フォトリアルなスマートフォン写真、清潔感のあるモダンなインテリア、浅い被写界深度、自然な肌の質感、繊細なコントラスト、検閲ブロックのため笑顔は見えない、最小限の編集、スタイリッシュで説得力のある個人の自撮り写真。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="プロフィール / アバター - ムードのあるモザイク加工済み室内自撮りポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [MathMedix](https://x.com/MathMedix)
- **ソース:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14686)**

---

### No. 5: プロフィール / アバター - マクドナルドでのリアルな自撮りポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、マクドナルド店内で撮影された男性のフォトリアルなカジュアル自撮り画像を生成します。SNS風の自然なレストランのスナップショットを作成するのに最適です。

#### 📝 プロンプト

```
アジアのマクドナルド店内で撮影された、非常にリアルなスマートフォンのカジュアル自撮り画像。テーブルに座る若い男性の胸から上のポートレート構図。カメラはテーブルの高さより少し上で腕を伸ばした位置にあり、片方の前腕がレンズに向かって伸びる、自然な正面からの自撮り視点を再現。被写体は左胸に小さな白い Tesla ロゴが入った黒い T シャツを着用し、短くストレートな黒髪で、細いダークフレームの眼鏡が一部見えている。リラックスしたポーズで片手を軽く顎に添えている。顔の中央は大きな長方形のぼかしで完全に隠されており、プライバシーを保護しつつ、髪、耳、顎のライン、眼鏡のテンプルは見える状態。左手前の前景には、蓋と白いストローが付いたマクドナルドの白い紙コップが 1 つ、フレームに収まっている。背景にはレストランのカウンターエリアが写り、温かみのある照明が灯っている。左側には、黄色いマクドナルドのアーチと白いスローガン「i’m lovin’ it」、その下に中国語が書かれた大きな赤い壁パネルが 1 枚。上部にはハンバーガー、フライドポテト、コンボメニュー、価格、中国語が表示された 4 枚のデジタルメニューボード。カウンター付近には 2 名の人物がおり、1 人はバックパックを背負って背を向け、もう 1 人はレジの後ろに一部見えている。自然なカラーバランス、わずかな屋内ノイズ、リアルな反射、浅めから中程度の被写界深度を使用し、演出されていない SNS スナップショットのような自然な雰囲気に仕上げる。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="プロフィール / アバター - マクドナルドでのリアルな自撮りポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [AB Kuai.Dong](https://x.com/_FORAB)
- **ソース:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14433)**

---

### No. 6: プロフィール / アバター - アルベドのコスプレ Instagram スナップショット

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Instagram ストーリー風の、反抗的で表情豊かなコスプレ写真を生成するための簡潔なプロンプトです。

#### 📝 プロンプト

```
スタイル: {argument name="character" default="アルベド"} のコスプレをした Instagram ストーリー風のスナップショット。コンテンツ: {argument name="action" default="カメラに向かって地面にしゃがみ込み、両手で大げさな反抗のポーズをとり、目をそらしながら、傲慢で軽蔑したような表情を浮かべている"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="プロフィール / アバター - アルベドのコスプレ Instagram スナップショット - Image 1">
</div>

#### 📌 詳細

- **作者:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **ソース:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **公開日:** 2026年4月21日
- **言語:** zh

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14347)**

---

### No. 7: プロフィール / アバター - 夕暮れの屋上と猫耳女子高生のアニメ風イラスト

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

夕暮れの学校の屋上で佇む猫耳女子高生を、シネマティックなアニメ調で描いたポートレート。ノスタルジックなキービジュアルやキャラクターアート、SNS用の画像に最適です。

#### 📝 プロンプト

```
夕暮れ時、学校の屋上の金属製フェンスに寄りかかる {argument name="character type" default="猫耳の女子高生"} を、少し下からのクローズアップ・スリークォーターアングルで捉えた高品質なアニメイラスト。彼女は、柔らかなハイライトが入った長い {argument name="hair color" default="ダークブラウン"} の髪をなびかせ、大きく輝くグレーブラウンの瞳と、丸い細縁のメガネをかけており、髪の間からはふわふわの猫耳が 2 つ覗いています。表情は静かで物憂げ、少し恥じらいを含んでおり、唇をわずかに開いて、優しくこちらを見下ろしています。服装は日本のセーラー服で、柔らかな {argument name="uniform color" default="ピンク"} の長袖トップスに、白いラインが入ったグレーのセーラー襟、鮮やかな赤色のスカーフリボンを合わせ、チェック柄のスカートが少し見えています。肩には黒いリュックのストラップが 2 本かかっています。シーン全体がドラマチックなゴールデンアワーの逆光に包まれ、髪や耳、肩、袖には温かみのある強いリムライトが当たり、左下からは太陽のフレアが差し込み、空はオレンジやピーチ色の雲で豊かに彩られています。背景には、夕日に照らされて窓が輝く赤瓦屋根の 2 階建て校舎を描写。2000 年代初頭のハイエンドなアニメキービジュアルのようなノスタルジックな質感を強調し、繊細な線画、輝く瞳、緻密な髪の毛の描写、シネマティックな構図、柔らかな被写界深度、鮮やかな暖色系のカラーグレーディング、洗練された陰影、そして静寂でエモーショナルな雰囲気を表現してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="プロフィール / アバター - 夕暮れの屋上と猫耳女子高生のアニメ風イラスト - Image 1">
</div>

#### 📌 詳細

- **作者:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **ソース:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14547)**

---

### No. 8: プロフィール / アバター - 白い羊を抱くファンタジーの女性

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、角のある白い羊を抱きしめる赤毛の女性の、写実的で中世ファンタジー風のポートレートを生成します。雰囲気のあるキャラクターアートや、エディトリアルスタイルのファンタジービジュアルに最適です。

#### 📝 プロンプト

```
中世またはファンタジーの世界観を持つ女性の、フォトリアルで映画のような縦型ポートレート。{argument name="hair color" default="長い赤銅色の髪"}の女性が、胸から上のアングルで大きな白い羊を優しく抱きしめている。女性は、装飾的な刺繍が施された袖口のダークモスグリーンのウールドレス（またはチュニック）を着用し、肩には毛皮で縁取られた厚手のマントやショールを羽織っており、バイキングやハイランド地方のような美学を想起させる。髪は太くウェーブがかかっており、少し風になびき、頭頂部には小さな三つ編みが編み込まれている。羊は密度が高くカールしたクリームホワイトの毛並みで、目を閉じた穏やかな表情をしており、外側と前方にカールした特徴的な螺旋状の角を持つ。女性の手は羊の首に優しく添えられ、温もり、保護、そして絆を表現している。背景には、霧がかった丘や荒野が柔らかくぼやけた、荒々しく曇った屋外の風景が広がり、冷たい灰色の空、浅い被写界深度、自然な拡散光が特徴。髪、羊毛、毛皮、布地の豊かな質感、落ち着いたアースカラーのパレット、親密なフレーミング、リアルな肌や動物の描写。左上隅に {argument name="corner text" default="GPT Image 2"} と書かれた黒いテキストを追加。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="プロフィール / アバター - 白い羊を抱くファンタジーの女性 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **ソース:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14619)**

---

### No. 9: プロフィール / アバター - ピンクでかわいいアイドル風リップスティックのポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ポスターや SNS 用のアート、キュートなキャラクターのキービジュアルに最適な、キラキラしたアニメアイドル風のポートレートを生成します。

#### 📝 プロンプト

```
縦構図で描かれた、非常に詳細で光沢感のあるアニメアイドル風のポートレート。夢のようなピンクでかわいい（Kawaii）世界観の中に、キュートな 10 代の少女をバストアップで表現しています。髪は {argument name="hair color" default="パステルピンク"} で、ボリュームのある非常に長いハイポニーテールに、柔らかな前髪と流れるようなカールがかかっており、小さなハートのクリップやクロスしたヘアピンで飾られています。瞳は大きくキラキラと輝く鮮やかな {argument name="eye color" default="エメラルドグリーン"} で、星のようなハイライト、長いまつ毛、少し潤んだような輝きを放っています。頬は柔らかく紅潮し、小さな唇は艶やかです。{argument name="lipstick color" default="ブライトピンク"} のリップを塗る愛らしい表情で、両手で丁寧にリップスティックを持っています。衣装はフリル、レース、リボン、ボウ、ハートのオーナメント、きらめく質感をあしらった黒とピンクのゴシックロリータ風アイドルドレス。頭にはピンクの宝石付きハートがあしらわれた黒いレースのリボンカチューシャ、前髪には 3 つのヘアアクセサリー、耳には揺れるハートのイヤリング、首元には小さなハートのチャームが付いた黒いチョーカーを着用しています。キャラクターの周囲は、ボケ味やスパークル、柔らかなネオンライトのエフェクト、アイドルファンの雰囲気に満ちた、輝くキャンディピンクの背景で包み込んでください。彼女の周囲に、手書き風の光るハートの吹き出しを 5 つ追加し、それぞれ「かわいすぎてごめん…♡」、「推してくれてありがとうっ♡」、「ずーっとだいすきっ♡」、「世界でいちばんの推しになってね…♡」、「ずっと一緒だよ？約束ね…♡」という日本語のテキストを入れてください。右上の背景には、同じ少女が描かれた小さな装飾付きのフォトカードまたはポスターを配置します。超高精細なイラスト、密度の高いきらめき、ロマンチックなライティング、光沢のあるハイライト、複雑なレースのディテール、ソフトフォーカスな背景、鮮やかなピンクのパレットで、愛らしいアイドルポスターのような仕上がりにしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="プロフィール / アバター - ピンクでかわいいアイドル風リップスティックのポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [ねね*AIcreator](https://x.com/NeneneAI)
- **ソース:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14606)**

---

### No. 10: プロフィール / アバター - 自転車に乗るペリカンのミニマルなイラスト

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、自転車に乗るペリカンの幾何学的なベクターイラストを生成します。シンプルな形状構成のテストや、遊び心のある抽象的なアイコン風画像の作成に最適です。

#### 📝 プロンプト

```
フラットなライトグレーの背景に、自転車に乗るペリカンを描いたミニマルなベクターイラスト。太いダークチャコールの輪郭線を持つシンプルな幾何学図形で構成されています。構図はワイドで中央に配置され、自転車が画像の下部 3 分の 2 を占め、鳥の頭部はハンドルバーの前方やや上に浮いているような、意図的に抽象的で図解のようなスタイルです。自転車は真横から見たシンプルな黒いロードバイクのシルエットで、2 つの大きな車輪（それぞれ太い外枠と十字を形成する 4 本のスポーク）、両輪の下に引かれた水平な地面の線、三角形のフレーム、短い黒いサドル、フレーム後部付近の簡略化されたクランクとペダルで構成されています。ペリカンはクリーンな抽象パーツで構築されています。白い丸みを帯びた頭部、小さな黒い円形の目、左を向いた長い開いたくちばし（上部のオレンジ色の三角形パーツと下部の淡いピンク色の袋状パーツの 2 つで構成）、頭頂部の短い黒い曲線、小さな独立した白い首と胴体の接続部、自転車の上に配置された大きな白い丸みを帯びた胴体、そして背中に向かって上向きに角度がついた白い翼のような形状。ペダルを漕いでいる様子を表現するため、胴体から自転車のフレームに向かって斜め下に伸びる、細長い長方形のオレンジ色の脚パーツを 2 つ追加してください。ロゴのテストやコードエディタの落書きのような、意図的に要素を削ぎ落とした少しシュールな雰囲気を維持し、陰影、グラデーション、テクスチャ、テキストは一切含めず、ネガティブスペースを多く確保してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="プロフィール / アバター - 自転車に乗るペリカンのミニマルなイラスト - Image 1">
</div>

#### 📌 詳細

- **作者:** [Justin Schroeder](https://x.com/jpschroeder)
- **ソース:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14657)**

---

### No. 11: プロフィール / アバター - 猫から人間へのポートレート変換

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、猫の参照写真を、元のポーズ、構図、背景を維持したまま、遊び心のある人間バージョンのフォトリアルなポートレートに変換します。

#### 📝 プロンプト

```
提供された参照画像を使用して、猫をリアルな人間のポートレートに変換してください。その際、猫がくつろいでいるポーズ、カメラアングル、フレーミング、そしてターコイズブルーの豪華な椅子の背景をそのまま維持してください。猫のオレンジと白の毛色をインスピレーションとして取り入れ、色白の若い女性で、温かみのあるジンジャーヘア、穏やかで落ち着いた表情の人物に仕上げてください。服装は、着心地の良いオフホワイトのラウンジウェア（ゆったりとしたニットの V ネックセーター 1 枚と、クリーム色のドローストリングパンツ 1 枚）を着用させ、椅子にリラックスした自然な姿勢で座らせてください。フォトリアルな質感、柔らかな自然光、エディトリアルなライフスタイル写真のクオリティで作成してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="プロフィール / アバター - 猫から人間へのポートレート変換 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Bojan Tunguz](https://x.com/tunguz)
- **ソース:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14670)**

---

### No. 12: プロフィール / アバター - ストロベリーアイスクリームを持つスタジオポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ストロベリーアイスクリームを顔の前に持つ黒髪の女性の、洗練されたセレブ風スタジオポートレートを生成します。エディトリアルビューティーやポップカルチャー系の画像に最適です。

#### 📝 プロンプト

```
滑らかでニュートラルなグレーの背景を背に、胸から上を捉えた、グラマラスなポップスターのような女性の洗練されたスタジオポートレート。{argument name="hair color" default="漆黒"} の長く緩やかなウェーブヘアはセンターパートで、艶やかな光沢と柔らかなボリュームが両肩に落ちている。彼女の顔は、口元から下を覆うように掲げたアイスクリームコーンによって大部分が隠れており、遊び心のあるファッションエディトリアルの構図を作り出している。白いリブ編みのタンクトップを着用し、片耳には輝くスタッドピアスが見える。手には、ダークレッドのベリーソースが混ざり、少し溶けかかった質感の大きなピンクのストロベリーアイスクリームが乗ったワッフルコーンを 1 つ持っている。温かみのある魅力的なビューティーライティング、柔らかな影、リアルな肌の質感、ハイエンドなセレブポートレート写真、手・コーン・髪・肩に合わせた鮮明なフォーカス、ミニマルな背景、さりげなく官能的でシックなムード、縦長クロップ。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="プロフィール / アバター - ストロベリーアイスクリームを持つスタジオポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Arturo Garrido](https://x.com/arturogarrido)
- **ソース:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14594)**

---

### No. 13: プロフィール / アバター - 検閲された点群ポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、高密度の白い粒子で構成された、スーツ姿の男性の鮮明なモノクロのライダー（LiDAR）風ポートレートを生成します。テック系の編集ビジュアル、プライバシーをテーマにしたコンテンツ、または未来的なアイデンティティを表現するイメージに最適です。

#### 📝 プロンプト

```
真っ黒な背景に数百万個の小さな白い点群で構成された、ミニマルなモノクロポートレート。フォーマルなダークブレザーと明るい色の襟付きシャツを着用した成人男性の胸から上を表現。被写体はやや右寄りに配置され、正面を向きつつわずかに横を向いており、きれいに整えられた短髪と、高密度のライダー風粒子によってシャープに定義された片耳が特徴。被写体を、トポロジカルな等高線ロジックと融合した生の 3D スキャンデータとしてレンダリングすること。超高密度の点描、正確な幾何学的ドット配置、かすかな等高線構造、そして髪、ジャケットのラペル、襟、首、肩にわたるクリーンな深度造形を施すこと。顔面は、額から鼻の下にかけて中央に配置された 1 つの大きな垂直の長方形の検閲ブロック（ダークグレーから黒）によって意図的に隠し、鮮明なプライバシーマスク効果を生み出すこと。マットな質感、鮮明なエッジ、シャープなフォーカス、高コントラストを維持し、発光、ブルーム、ネオン、霧、モーションブラー、色収差、絵画的な筆致は一切排除すること。右下隅に 1 つの小さな 4 点スパークルアイコンをライトグレーで追加すること。全体として、8k 解像度の高精細なライダー（LiDAR）スキャンポートレートのような、数学的でフォレンジック（科学捜査的）、かつ未来的な雰囲気に仕上げること。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="プロフィール / アバター - 検閲された点群ポートレート - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="プロフィール / アバター - 検閲された点群ポートレート - Image 2">
</div>

#### 📌 詳細

- **作者:** [Harshith](https://x.com/HarshithLucky3)
- **ソース:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14408)**

---

### No. 14: プロフィール / アバター - ライオンに乗るギリシャ神話の神

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

アフリカのサバンナを舞台に、ライオンに乗るギリシャ神話の神のような姿を壮大に描くためのシネマティックなプロンプトです。

#### 📝 プロンプト

```
{argument name="persona" default="ギリシャ神話の神"} に扮して、{argument name="setting" default="アフリカの平原"} で {argument name="mount" default="ライオン"} に乗っている姿を生成してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="プロフィール / アバター - ライオンに乗るギリシャ神話の神 - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="プロフィール / アバター - ライオンに乗るギリシャ神話の神 - Image 2">
</div>

#### 📌 詳細

- **作者:** [Max Blade](https://x.com/_MaxBlade)
- **ソース:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14326)**

---

### No. 15: プロフィール / アバター - 困惑した表情のブロンドのアニメ風少女のポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、青いセーターを着て困惑した表情を浮かべる少女の、パステル調のシンプルなアニメ風バストアップ画像を作成します。アバターやプロフィール画像、カジュアルなキャラクターイラストに最適です。

#### 📝 プロンプト

```
淡いグレーの無地背景を背にした、若い女性の柔らかくミニマルなアニメ風バストアップポートレート。非常に細いスケッチ風の線画と、フラットで優しい色使いのクリーンなパステルスタイルで描かれています。長く流れるような淡いブロンドヘアは柔らかなレイヤーが入っており、長い前髪が額を部分的に覆っています。大きく丸いライトブルーの瞳、色白の肌、そして軽く開いた小さな口元が、わずかな困惑を表現しています。ゆったりとしたオーバーサイズの {argument name="clothing color" default="淡いパステルブルー"} の長袖トップスを着用し、ネックラインは広めに開いています。体は少し視聴者の方を向き、片手を上げて人差し指で頭の横に触れる、困ったようなポーズをとっています。頭の左上付近に、青いクエスチョンマークを 1 つ浮かべてください。無邪気でぼんやりとした、愛らしい表情に仕上げます。構図は中央に配置し、余計なオブジェクトや詳細な背景、強い影は入れず、すっきりと風通しの良い雰囲気を保ってください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="プロフィール / アバター - 困惑した表情のブロンドのアニメ風少女のポートレート - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="プロフィール / アバター - 困惑した表情のブロンドのアニメ風少女のポートレート - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="プロフィール / アバター - 困惑した表情のブロンドのアニメ風少女のポートレート - Image 3">
</div>

#### 📌 詳細

- **作者:** [Torishima / INTP](https://x.com/izutorishima)
- **ソース:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14474)**

---

### No. 16: プロフィール / アバター - ソフトブルーのアニメ風少女のポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、オーバーサイズのライトブルーのトレーナーを着た青髪の少女の、ミニマルなパステル調アニメ風バストアップ画像を作成します。アバターやプロフィール画像、柔らかい雰囲気のキャラクターアートに最適です。

#### 📝 プロンプト

```
温かみのあるオフホワイトの無地背景を中央に配置した、キュートな若い女性のソフトなアニメ風バストアップポートレート。繊細でクリーンな線画とフラットなパステルカラーで描かれています。非常に長いストレートの {argument name="hair color" default="ペールスカイブルー"} の髪は毛先が細く、中央で少し分かれたフルバングスで、瞳も髪色に合わせた大きなブルーで、艶やかなハイライトが入っています。表情は恥ずかしそうで戸惑っており、眉の内側を少し上げ、頬には淡いピンクのチークをさし、小さく口を開けています。考え込んでいるような、ためらいがちなポーズで人差し指を軽く下唇に当て、真っ直ぐにこちらを見つめています。オーバーサイズでゆったりとした {argument name="top color" default="ライトブルー"} のトレーナーを着用しており、長い袖が手の一部を覆っています。胸から上をフレーミングし、頭を少し傾けることで、優しく無垢で夢見心地な雰囲気を演出してください。ミニマルな構図にし、アクセサリーや余計なオブジェクト、風景、テキストは一切入れないでください。モノクロームのブルーパレット、空気のようなシンプルさ、スケッチ風の繊細な輪郭線を強調し、ソフトな個人用アバターに適したクリーンな日本のアニメイラストの美学を表現してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="プロフィール / アバター - ソフトブルーのアニメ風少女のポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Torishima / INTP](https://x.com/izutorishima)
- **ソース:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14473)**

---

### No. 17: プロフィール / アバター - 高級感のある室内ミラーセルフィーのポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、アイボリーのタイトなドレスを着用した女性のリアルなファッション風ミラーセルフィーを生成します。ライフスタイル、コーディネート、SNS 向けの華やかな画像に最適です。

#### 📝 プロンプト

```
柔らかな光が差し込む高級感のあるリビングルームまたはホテルのスイートルームで、頭から膝下までを縦構図で捉えた、スレンダーで魅力的な若い女性のリアルな室内ミラーセルフィー。エレガントなドレープとシャーリングが施された、体にフィットするクリーム色またはアイボリーのボディコンミディドレスを着用。片方の肩にストラップが斜めにかかり、もう片方の肩が露出したアシンメトリーなネックラインが特徴。髪はダークブラウンのロングヘアで、緩やかなウェーブがかかっており、センター付近で分けて両肩に流している。右手でスマートフォンを持ち、顔の前にかざして一部を隠しながら、壁の鏡に向けて撮影している。スマートフォンには赤い雲柄のダークカラーのケースを装着。左腕は自然に体の横に下ろしている。控えめなジュエリーを追加：小さなペンダント付きの細いネックレス 1 本、右手にシルバーのブレスレットまたはバングル 1 つ、スマホを持つ手の指に指輪。リアルな女性らしいシルエット、滑らかな肌、柔らかな温かみのある環境光、洗練されたエディトリアルな SNS スタイルの写真を強調すること。背景には、背後にベージュのソファ 1 脚、ソファの右側にブラウンのレザーハンドバッグ 1 つ、鏡のエリアの背後に質感のある石またはコンクリートのアクセントウォール、左側に 2 つの額入りアートが飾られた温かみのある廊下を含めること。自然な室内の影、洗練された肌の質感、ウエストやヒップ周りのリアルな生地の折り目や圧迫感、高級アパートメントの美学、クリーンな構図、そして高精細なディテールを表現すること。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="プロフィール / アバター - 高級感のある室内ミラーセルフィーのポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Danna R.](https://x.com/daaaaanc)
- **ソース:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14421)**

---

### No. 18: プロフィール / アバター - リアルな白いドレスの鏡越しセルフィー

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、温かみのあるアパートの室内で撮影された、フォトリアルなファッション系の鏡越しセルフィーを生成します。コーディネートの撮影やライフスタイルコンテンツ、リアリズムの検証などに最適です。

#### 📝 プロンプト

```
温かみのある照明のモダンなアパートのリビングで、鏡越しに自撮りをするスリムな若い女性のリアルな室内写真。彼女は、胴体から腰にかけてシャーリングが施された、体にフィットするアイボリーホワイトのワンショルダー・ボディコン・ミディドレスを着用している。髪は肩までの長さのストレートなダークブラウンで、センター分け。ジュエリーは控えめで、指輪 2 つ、シルバーのバングル、小さなピアスを身につけている。片手でスマートフォンを持ち、顔はスマホで隠れている。スマホケースは黒地で、赤い雲のモチーフが描かれている。少し斜めに立ち、片腕を自然に下ろしたリラックスしたポーズで、女性らしい自然なシルエットを表現。構図はカジュアルな SNS の鏡越しセルフィーのような縦長のアングル。背後にはベージュのファブリックソファがあり、グレーの幾何学模様のクッション 1 つと、トープブラウンのレザーハンドバッグが置かれている。背景にはテクスチャー感のあるブロンズブラウンのアクセントウォール、光沢のあるクリーム色のタイル床、左側には 3 つの額縁が飾られた薄暗い廊下、そして天井には温かみのある埋め込み式照明が見える。柔らかな夕方のアンビエントライト、自然な肌の色味、リアルな生地の張りやシワ、鏡への繊細な映り込み、洗練された高級アパートの雰囲気、高いリアリズム、フォトリアルな肌の質感、スマートフォンカメラの視点。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="プロフィール / アバター - リアルな白いドレスの鏡越しセルフィー - Image 1">
</div>

#### 📌 詳細

- **作者:** [Danna R.](https://x.com/daaaaanc)
- **ソース:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14419)**

---

### No. 19: プロフィール / アバター - サントリーニ島でのラグジュアリーなドレスポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、サントリーニ島で白いドレスを纏いポーズをとる魅力的な女性の、フォトリアルな縦型トラベルファッションポートレートを生成します。ラグジュアリーなバケーション、ライフスタイル、またはエディトリアルなイメージに最適です。

#### 📝 プロンプト

```
ギリシャ・サントリーニ島のカルデラを見下ろす陽光あふれる石の縁に座る、{argument name="woman" default="ブロンドの女性"}の魅力的なトラベルファッションポートレート。背景には、深い青い海と険しい火山島に向かって立ち並ぶ白い崖の建物が広がっています。彼女は、深いプランジングネックライン、サイドのカットアウト、円形リングのディテールが施されたギャザーウエスト、そして膝の上に優雅にドレープされた柔らかなプリーツ生地が特徴の、流れるようなアイボリーのホルタードレスを着用しています。髪は長くウェーブがかかっており、{argument name="hair color" default="ゴールデンブロンド"}で、肩にゆったりと流れるようなスタイルです。小さなペンダントとシルバーの十字架を含む繊細なレイヤードネックレス、そして手首にはブレスレットまたは時計を加えてください。背景の右上には、鮮やかな{argument name="dome color" default="青"}のドームを持つ典型的な白いギリシャ正教会を配置し、画像の右側には満開の鮮やかな{argument name="flower color" default="マゼンタピンク"}のブーゲンビリアをあしらってください。照明は地中海の明るい真昼の太陽で、鮮明なハイライト、柔らかな肌の輝き、そして女性をシャープに保ちつつ背景の建築物や海をわずかにソフトにする穏やかな被写界深度を表現します。構図は縦型で、エレガントかつ憧れを抱かせるものとし、女性をやや右寄りに配置。胴体から流れるようなスカートまでが見えるようにし、左半分には風光明媚な海岸線を広げてください。左上隅には、{argument name="corner text" default="GPT V2"}と書かれた小さな黒いテキストを追加してください。フォトリアルなラグジュアリーバケーションの美学、高精細、自然な色合い、Instagram のエディトリアルな旅行の雰囲気。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="プロフィール / アバター - サントリーニ島でのラグジュアリーなドレスポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Ed](https://x.com/Eduardopto)
- **ソース:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14428)**

---

### No. 20: プロフィール / アバター - 日本の富士フイルム風ポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

柔らかくナチュラルで親密な朝の雰囲気を持つ、高品質な富士フイルム風ポートレートを生成するための非常に詳細なプロンプトです。

#### 📝 プロンプト

```
9:16 縦長 — {argument name="film style" default="日本の富士フイルム風"} ポートレート、被写体 1 名

富士フイルムのアナログな質感（Pro 400H / Superia の雰囲気）、柔らかなパステル調、わずかな緑からマゼンタへの色味のシフト、低コントラスト、穏やかなハイライトのロールオフ、繊細なフィルム粒子、微かなハレーション

早朝の室内、窓辺、柔らかなカーテン、爽やかな自然光

{argument name="subject" default="日本の若い女性アイドル"}、ナチュラルでミニマルなメイク、柔らかく瑞々しい肌の質感

服装：オーバーサイズのシャツにゆったりとしたショートパンツ、リラックスしたホームウェアスタイル、露出控えめ

髪型：少し無造作で自然なボリューム感、寝起きの雰囲気

ポーズ：ベッドの端や窓辺に座り、体を少し前に傾け、肩の力を抜いた姿勢。片手で小さな花や布を軽く持ち、もう片方の手は自然に置いている

表情：柔らかく、少し眠たげな眼差し、穏やかで自然な表情

ライティング：{argument name="lighting" default="柔らかな朝の光"}、拡散された優しい影

ムード：静寂、爽やか、親密な日常のひととき

品質：超リアル、フィルム粒子、わずかな柔らかさ、自然な不完全さ
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="プロフィール / アバター - 日本の富士フイルム風ポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [BubbleBrain](https://x.com/BubbleBrain)
- **ソース:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14301)**

---

### No. 21: ソーシャルメディア投稿 - 4 分割 日本語デジタル広告バナーグリッド

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

旅行、スキンケア、グルメ、オンライン教育の 4 つのテーマで、それぞれ異なる日本語デジタル広告バナーを 2x2 のグリッド形式で生成します。

#### 📝 プロンプト

```
{
  "type": "2x2 グリッド形式の日本語デジタル広告バナー",
  "layout": {
    "structure": "4 等分された四半面",
    "quadrants": [
      {
        "position": "左上",
        "theme": "旅行",
        "subject": "白い砂浜で手をつなぎ、青く澄んだ海を眺めるカップル。空は明るい青色。",
        "elements": ["左下に赤いハイビスカスの花"],
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
          "descriptions": ["飛行機", "ホテル", "レンタカー"]
        }
      },
      {
        "position": "右上",
        "theme": "スキンケア",
        "subject": "ツヤのある潤った肌をした若い女性のアップ。目を閉じ、優しく頬に触れている。",
        "elements": [
          "柔らかなピンクのグラデーション背景",
          "躍動感のある水しぶきの演出",
          "'{argument name=\"skincare product name\" default=\"LUMIÈRE\"} Brightening Gel' とラベルが貼られたピンクの化粧品容器"
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
          "style": "ゴールドの円形",
          "labels": ["毛穴ケア", "高保湿", "ハリ・ツヤ"]
        }
      },
      {
        "position": "左下",
        "theme": "グルメ",
        "subject": "黒いグリルプレートの上で焼かれている、厚切りのミディアムレアステーキ。",
        "elements": [
          "ガーリックチップ",
          "ローズマリーの枝",
          "煙と光る炭火が漂うダークな背景"
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
          "style": "赤の円形",
          "labels": ["A4 A5等級"]
        }
      },
      {
        "position": "右下",
        "theme": "オンライン教育",
        "subject": "青いシャツを着た若い男性がデスクで勉強中。開いたノートパソコンの横でノートに書き込んでいる。",
        "elements": ["明るい室内照明", "デスク環境"],
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
          "style": "青の円形",
          "labels": ["受講者数 10万人 突破！"]
        },
        "icons": {
          "count": 2,
          "descriptions": ["スマートフォン", "開いた本"]
        }
      }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="ソーシャルメディア投稿 - 4 分割 日本語デジタル広告バナーグリッド - Image 1">
</div>

#### 📌 詳細

- **作者:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **ソース:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13531)**

---

### No. 22: ソーシャルメディア投稿 - かわいい黒猫の日本語ステッカーシート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

表情豊かな黒猫と日本語のフレーズを組み合わせた、15 パネルのステッカーシート。チャット用ステッカー、LINE スタンプのコンセプト、SNS 用のビジュアルに最適です。

#### 📝 プロンプト

```
{"type":"かわいいステッカーシートのイラスト","subject":{"species":"黒猫","style":"愛らしいちびキャラ、柔らかい水彩風アニメ・カートン調、大きな丸い琥珀色の瞳、小さな口元、表情豊かな耳、ふわふわのダークチャコールブラックの毛並みに温かみのあるブラウンのハイライト、太くきれいな輪郭線"},"layout":{"background":"無地の白","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"1 行目 1 列目","count":1,"labels":["両手を胸の前で合わせた感謝のポーズ、口を開けて笑顔、猫の周りに桜の花びら"]},{"title":"02. おつかれさま！","position":"1 行目 2 列目","count":1,"labels":["肉球マークの緑色のマグカップを持ったリラックスした猫、目を閉じている、小さな湯気、お祝いの黄色いアクセントライン"]},{"title":"03. 了解です！","position":"1 行目 3 列目","count":1,"labels":["了解の意を込めて片手を挙げた直立した子猫、明るく注意深い表情、頭上に黄色いアクセントライン"]},{"title":"04. ＯＫ！","position":"1 行目 4 列目","count":1,"labels":["片手で OK サインを作ってウィンクする子猫、少し微笑んでいる、黄色いアクセントライン"]},{"title":"05. はーい！","position":"1 行目 5 列目","count":1,"labels":["元気に片手を高く振る子猫、口を開けて笑顔、黄色いアクセントライン"]},{"title":"06. いいね！","position":"2 行目 1 列目","count":1,"labels":["親指を立ててウィンクする子猫、横に小さなピンクのハート、黄色いアクセントライン"]},{"title":"07. がんばる！","position":"2 行目 2 列目","count":1,"labels":["拳を握りしめ、気合の入った目をした子猫、スタイリッシュなオレンジ色の炎に囲まれている"]},{"title":"08. なんとかなる！","position":"2 行目 3 列目","count":1,"labels":["自信に満ちた穏やかな表情の子猫、目を閉じて胸を少し張っている、周りにピンクの花が舞っている"]},{"title":"09. ごめんね…","position":"2 行目 4 列目","count":1,"labels":["胸の前で手を合わせ、申し訳なさそうにしている悲しい子猫、垂れ目、青い汗のしずく"]},{"title":"10. 待ってるね！","position":"2 行目 5 列目","count":1,"labels":["木の縁から両手を出して覗き込んでいる子猫、期待に満ちた表情、両側に小さな動きの線"]},{"title":"11. おやすみなさい","position":"3 行目 1 列目","count":1,"labels":["ピンクのクッションの上で丸まって眠る子猫、青い ZZZ の文字、頭上に三日月と小さな星"]},{"title":"12. いってきます！","position":"3 行目 2 列目","count":1,"labels":["肉球パッチと小さなチャームが付いた緑のリュックを背負い、片手を挙げて元気に歩き去る後ろ姿、黄色いアクセントライン"]},{"title":"13. ただいま！","position":"3 行目 3 列目","count":1,"labels":["両手を高く上げた正面向きの子猫、幸せそうな満面の笑み、周りに金色のキラキラマーク"]},{"title":"14. よろしくね！","position":"3 行目 4 列目","count":1,"labels":["正座して丁寧にお辞儀をする子猫、優しい微笑み、頭の横に黄色いアクセントライン"]},{"title":"15. 大好き！","position":"3 行目 5 列目","count":1,"labels":["大きなピンクのハートを抱きしめて満足そうな子猫、目を閉じている、周りに浮かぶ小さなピンクのハート"]}],"spacing":"十分な余白をとった均等配置"},"rendering":{"quality":"高精細","lighting":"柔らかく均一なスタジオ照明","color_palette":"黒い毛並み、温かみのある茶色の瞳、ピンクのハートと花、黄色いアクセントマーク、緑のアクセサリー、ミニマルなパステルカラーの装飾","mood":"フレンドリー、健康的、ステッカー向け、メッセージアプリ用パック","composition":"各ステッカーは独立してセルの中央に配置され、上部に太字の日本語テキストを記載"}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="ソーシャルメディア投稿 - かわいい黒猫の日本語ステッカーシート - Image 1">
</div>

#### 📌 詳細

- **作者:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **ソース:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14490)**

---

### No. 23: ソーシャルメディア投稿 - ブラウンを基調としたブティックでの自然なポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、温かみのある色調のショップ内での女性のリアルな縦型ライフスタイル写真を生成します。ファッション、小売、SNS のエディトリアル画像に最適です。

#### 📝 プロンプト

```
温かみのある色調のブティックやホームフレグランスショップに立つ、若い東アジア人女性の自然で写実的な縦型のスマートフォン風写真。少し高い位置から上半身と胴体を捉えたアングルです。彼女は {argument name="hair color" default="ダークブラウンからブラック"} の髪を低い位置でポニーテールにまとめ、顔周りに数本の毛束を遊ばせており、片手でクリームホワイトの小さなカップやキャンドルジャーを口元に近づけています。服装は {argument name="outfit color" default="チョコレートブラウン"} の体にフィットしたリブ素材のジップアップ長袖トップス（ジッパーは少し開いた状態）に、同色のハイウエストパンツを合わせたモノトーンコーデです。ポーズは少し寄りかかったカジュアルなもので、もう片方の腕は背後に自然に回しており、オフショットのようなライフスタイル感を出しています。周囲の木製棚にはガラス製のキャンドルジャーや小さな商品容器が並び、背景やフレーム左側は柔らかくぼかされています。温かみのある室内照明、浅い被写界深度、リアルな肌の質感、髪の繊細なハイライト、自然な手のポーズ、そして居心地の良い職人気質な小売店の雰囲気を表現してください。被写体を中央に配置し、背景を斜めに傾けることで自然な視点を強調した、タイトなミドルからフルボディのポートレート構図にしてください。写真スタイル：写実的、高精細、ソフトなボケ味、ブティックでのスナップショット、35mm レンズ風、自然なカラーグレーディング。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="ソーシャルメディア投稿 - ブラウンを基調としたブティックでの自然なポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **ソース:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14630)**

---

### No. 24: ソーシャルメディア投稿 - スーパーの卵パックを持つ女性のポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、スーパーマーケットで卵の6個入りパックを持つスタイリッシュな女性の、リアルな縦型ライフスタイル写真を生成します。SNSやエディトリアルスタイルのショッピング画像に最適です。

#### 📝 プロンプト

```
夜のモダンなスーパーマーケットの通路で買い物をする {argument name="woman age" default="若い成人"} 女性を捉えた、スマートフォン撮影風の自然な縦型写真。太ももから頭までを収めた、やや広角のクローズアップ構図。色鮮やかなパッケージの野菜や食料品が並ぶ冷蔵棚の横に立ち、光沢のある黒い棚、明るい店内照明、反射する表面、背景の柔らかなボケ味が特徴。左手には開いた再生紙製の卵パックを持ち、中に6個の茶色い卵がはっきりと見えるようにカメラに向けている。右手は食料品が入った黒いショッピングカートの近くにある。長くダークブラウンの髪を下ろしており、顔は中央に配置された大きなソフトエッジの長方形のぼかしで意図的に隠されている。胸元までジッパーを開けたタイトなリブ編みの茶色の長袖クロップトップと、お揃いのハイウエストの茶色のパンツを着用。ポーズはカジュアルで自信に満ちており、卵パックが焦点となる小道具として提示されている。リアルな写真、フラッシュなしの屋内照明、浅い被写界深度、肌や生地の緻密な質感、自然な反射、高コントラスト、ファッショナブルなライフスタイル美学、洗練されたエディトリアルな雰囲気、縦型 9:16 の構図。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="ソーシャルメディア投稿 - スーパーの卵パックを持つ女性のポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **ソース:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14629)**

---

### No. 25: ソーシャルメディア投稿 - 夕日に映える豪華絢爛な秋の女帝

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、ドラマチックな展示用アートやインパクトの強い SNS 用ビジュアルに最適な、宝石をちりばめた鮮烈な秋のファンタジーポートレートを生成します。

#### 📝 プロンプト

```
エレガントな女性の横顔を捉えた超豪華なファンタジーポートレート。少し左寄りに配置された彼女は、紅葉、菊のような花々、金のフィリグリー、宝石、クリスタルのペンダント、半透明のステンドグラス装飾で彩られた豪華な秋のヘッドドレスとローブを身にまとっています。長く暗い髪が肩に流れ落ち、顔の大部分は影と角度によって隠されており、神秘的で理想化された雰囲気を醸し出しています。彼女の周囲を、琥珀色、ルビー色、オレンジ色の透明なガラスでできた大きな円形のフレームと曲線を描くリボンが囲み、そこにはカットされた宝石や反射するクリスタルの雫が埋め込まれています。画面内には、はっきりと視認できる 9 枚の浮遊する紅葉を配置してください。背景は夕日に照らされた山の谷間とし、地平線近くに沈む太陽、温かみのある黄金の光線、遠くの山々、秋の森、そして眼下に流れる反射する川を描写します。全体を燃えるようなオレンジ、銅色、ゴールド、スカーレットの色調で満たし、極めて高い視覚的豊かさ、眩いハイライト、緻密なレイヤーのディテール、きらめくボケ味、映画のようなバックライト、そして意図的に強調された、目がくらむほどの華麗な美しさを表現してください。超高精細、マキシマリスト、幻想的、光り輝く、ファンタジー・クチュール、光沢のある質感、宝石のようなライティング、ワイドな映画的構図。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="ソーシャルメディア投稿 - 夕日に映える豪華絢爛な秋の女帝 - Image 1">
</div>

#### 📌 詳細

- **作者:** [AIおじさん](https://x.com/AIojisan1952)
- **ソース:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14508)**

---

### No. 26: ソーシャルメディア投稿 - ロボット画家のコラージュ広告

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

かわいいロボットが 4 つの異なるアート作品を描いている、洗練された 2x2 のプロモーション用コラージュ画像。AI 画像生成ツールの発表やソーシャルメディアのバナーに最適です。

#### 📝 プロンプト

```
{"type":"プロモーション用コラージュイラスト","subject":{"main":"大きな青い光る目を持つ、かわいい白い人型ロボットのアーティスト","design":"滑らかで丸みを帯びた白い外殻、黒い機械的な関節、小さな笑顔、親しみやすい子供のようなプロポーション、光沢のある仕上げ","activity":"絵筆を持ち、パレットを手にキャンバスに絵を描いている"},"layout":{"composition":"2x2 グリッドのコラージュ、中央の継ぎ目をまたぐように大きなタイトルをオーバーレイ","sections":[{"position":"左上","count":1,"label":"3","scene":"ロボットが水平線に輝く太陽、ピンクとオレンジの空、青い海を描いたカラフルな夕日の海景画を描いている、表現力豊かな筆致"},{"position":"右上","count":1,"label":"6","scene":"ロボットが青い花瓶に生けられたピンクの花束を描いている、柔らかなパステル調の静物画"},{"position":"左下","count":1,"label":"4","scene":"ロボットが緑豊かな滝の風景、森の木々と小川を描いている"},{"position":"右下","count":1,"label":"7","scene":"ロボットが夕暮れ時の輝く現代都市のスカイライン、高い摩天楼と温かい反射を描いている"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"非常に大きく太い白のサンセリフ体、暗いドロップシャドウ付き、コラージュの中央に水平配置"}},"environment":{"setting":"居心地の良いアートスタジオの室内","background":"ソフトフォーカスの棚、額縁に入った絵、温かみのある環境光、ニュートラルなカーテン、時折見える観葉植物","easel":"各パネルに木製の卓上イーゼル","palette":"各パネルに鮮やかな絵の具がいくつも乗った丸いパレット"},"style":{"rendering":"非常に洗練された 3D カートゥーンリアリズム","mood":"遊び心があり、創造的で、魅力的、テクノロジーとアートの融合","camera":"ミディアムクローズアップのフレーミング、各パネルの右側にロボットを配置し、左側のキャンバスに向かっている","lighting":"温かみのある室内光、柔らかなハイライトと浅い被写界深度"}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="ソーシャルメディア投稿 - ロボット画家のコラージュ広告 - Image 1">
</div>

#### 📌 詳細

- **作者:** [01net](https://x.com/01net)
- **ソース:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14556)**

---

### No. 27: ソーシャルメディア投稿 - アニメ風ポップアート・プロテストポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、顔が隠されたキャラクター、ピースサイン、巨大なスローガン吹き出しが特徴の、大胆な縦型アニメポスターを生成します。ミームアートや SNS 投稿、グラフィックポスターの制作に最適です。

#### 📝 プロンプト

```
ダークネイビーのハイカラーコートを纏った、白髪の男性呪術師を描いた大胆なアニメ風ポップアートポスター。腰から上の構図で、自信に満ちた表情で正面を向き、カメラに近い左手でピースサインを作っている。目と鼻のあたりには長方形のぼかし（検閲ブロック）がかかっており、その上には黒い目隠しやバイザーから突き出るように、トゲのある銀白色の髪がドラマチックに広がっている。上部には巨大なコミック風の吹き出しを配置し、{argument name="headline text" default="LUDDITES ALWAYS LOSE!"} というテキストを、太い黒のサンセリフ体（すべて大文字）で記載する。背景には鮮やかなブルーを使用し、キャラクターの背後から放射状に広がる高密度の赤とオレンジのスピード線を描くことで、ダイナミックな漫画の表紙のような雰囲気を演出する。太いインクの輪郭線、セルシェーディングによるアニメ調のレンダリング、ポスタリゼーションによるコントラスト、そしてわずかに歪んだヴィンテージコミックの印刷風の質感を強調する。構図は縦型でタイトなクロップとし、ハイエネルギーで反抗的、かつグラフィックでミームのような仕上がりにする。{argument name="character hair color" default="silver white"} の髪、{argument name="coat color" default="dark navy"} のコート、{argument name="background color" default="bright blue with red-orange radial lines"} の背景色がパレット全体を支配するように構成する。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="ソーシャルメディア投稿 - アニメ風ポップアート・プロテストポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **ソース:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14638)**

---

### No. 28: ソーシャルメディア投稿 - リアルな Sam's Club でのショッピングスナップショット

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、ブランドの小売看板や農産物を持つ買い物客など、本格的なショッピングシーンを再現するのに適した、写真のようにリアルな倉庫型店舗のポートレートを生成します。

#### 📝 プロンプト

```
中国の混雑した Sam's Club 倉庫型店舗内での、非常にリアルなスマートフォンのスナップショット写真。構図の中心には、上半身が写った若い東アジア系の男性を配置。彼は直立してカメラを向いており、プライバシー保護のため顔は長方形のぼかしで隠されている。彼は左胸に小さな白い Tesla ロゴが入った無地の黒い半袖 T シャツを着用し、左手には青いバンドで結ばれた赤いリンゴの大きな透明なビニール袋を持っている。リンゴの袋には「envy」と書かれた白いラベルがあり、その下に小さな中国語のテキストが添えられている。彼の背後には、高い天井、倉庫の棚、買い物客、ショッピングカート、積み上げられた農産物のディスプレイがある明るい小売店のインテリアが広がる。左上には「Sam’s CLUB」および「山姆会员商店」と書かれた青いダイヤモンド型の Sam's Club の壁面看板を、彼の背後には「更好的生活尽在山姆」および「Life is Better in the Club」と書かれた大きな青い壁面バナーをはっきりと写す。右上には、「优质优价」および「Great Products Great Prices」と書かれた青と緑の幾何学模様のアクセントがある背の高い白い縦型バナーを吊るす。背景には、本格的で混雑したショッピングの雰囲気を出すために、少しピントを外した多くの買い物客を含める。照明は明るく均一な小売店のオーバーヘッドライト、自然な色合い、視点はアイレベル、ドキュメンタリー風のスナップショットの美学、前景の被写体はシャープで背景はわずかにソフトにぼかす。縦向きのポートレート。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="ソーシャルメディア投稿 - リアルな Sam's Club でのショッピングスナップショット - Image 1">
</div>

#### 📌 詳細

- **作者:** [AB Kuai.Dong](https://x.com/_FORAB)
- **ソース:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14434)**

---

### No. 29: ソーシャルメディア投稿 - 自転車に乗る幾何学的な鳥

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、スタイリッシュな自転車に乗る鳥のクリーンでミニマルなベクターイラストを生成します。遊び心のあるエディトリアルグラフィック、ロゴ、モダンなポスターアートなどに最適です。

#### 📝 プロンプト

```
ライトグレーの背景に、遊び心のある鳥が自転車に乗っている様子を描いた、ミニマルなフラットベクターイラストです。全体がシンプルな幾何学図形と太い黒の輪郭線で構成されています。自転車は左を向いた黒い線画のロードバイクで、2 つの大きな車輪にはそれぞれ縦横のスポークが交差しており、シンプルな三角形のフレーム、小さな黒いサドル、ペダル、そして自転車の下には水平に伸びる細い黒い地面の線が描かれています。ライダーはデフォルメされた白い鳥で、大きな丸い体、一回り小さな丸い頭、大きく開いた尖ったオレンジ色のくちばし、そしてピンク色のくちばしの内側が特徴です。鳥には 1 つの黒い目、頭頂部にシンプルな曲線、首の後ろに 1 つの涙型の翼、そして後ろに向かって伸びる 1 つの角度のついた白い尾羽があります。鳥はまるで実際に漕いでいるかのように、自転車の上で前傾姿勢をとっています。2 本の細長いオレンジ色の脚は黒い輪郭線で描かれ、フレームの上からペダルに向かって伸びています。構図は中央に配置し、影やテクスチャのない、モダンなアイコンのようなグラフィックスタイルで、遊び心のあるクリーンで抽象的なデザインに仕上げてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="ソーシャルメディア投稿 - 自転車に乗る幾何学的な鳥 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Mojofull](https://x.com/furoku)
- **ソース:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14512)**

---

### No. 30: ソーシャルメディア投稿 - 認知バイアスに関する Instagram インフォグラフィック

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

複雑なテキスト情報を含む、情報量の多いソーシャルメディア用グラフィックを作成するためのプロフェッショナルなプロンプトです。

#### 📝 プロンプト

```
{argument name="topic" default="広告主が認知バイアスを活用する方法"} に関する {argument name="platform" default="Instagram 投稿"} 用の {argument name="format" default="インフォグラフィック"} を作成してください
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="ソーシャルメディア投稿 - 認知バイアスに関する Instagram インフォグラフィック - Image 1">
</div>

#### 📌 詳細

- **作者:** [Maxwell Finn](https://x.com/maxwellfinn)
- **ソース:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14306)**

---

### No. 31: ソーシャルメディア投稿 - 2000 年代初頭のコンピュータ室と ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、CRT モニターのコンピュータで ChatGPT を使用する学生たちのノスタルジックなスナップショットを生成します。日常的な教育現場における AI をテーマにしたエディトリアルやソーシャルメディア用のビジュアルに最適です。

#### 📝 プロンプト

```
2000 年代初頭のデジタルカメラで撮影されたような、ドキュメンタリータッチのスナップショット写真。{argument name="setting" default="高校のコンピュータ室"} には 10 人の学生が座っており、かさばるオフホワイトの CRT デスクトップコンピュータが並んでいます。部屋の左後方からわずかに広角で捉えた構図です。直接フラッシュ、柔らかな粒子感、温かみのある室内の蛍光灯、そして右下に {argument name="timestamp" default="02 18 04"} とタイムスタンプが入った、当時の雰囲気を再現した画像。左手前には、袖に白いストライプが入ったネイビーのトラックジャケットを着た学生が CRT モニターを指差しており、中央手前には、短く尖った髪型でオーバーサイズのグレーのスウェットを着た学生が背を向けて座っています。右側手前には、ポニーテールでライトブルーの長袖トップス（腕に濃い水平ストライプ入り）を着た金髪の学生がキーボードを打っており、右端にはカールしたダークヘアの学生がワークステーションに座っています。中列や後列にも他の学生たちが座り、全員が画面に向かっています。モニターには ChatGPT のインターフェースがはっきりと表示されており、見出しには {argument name="screen title" default="ChatGPT"}、その下にシンプルなプロンプトテキストが書かれています。部屋の壁はベージュで、天井にはドロップシーリングタイルがあり、壁にはモチベーションを高めるポスターが貼られています。奥の壁には {argument name="poster one" default="YOU CAN DO HARD THINGS"}、「BE KIND ONLINE」、「THINK BEFORE YOU CLICK」、そして「KEYBOARD SHORTCUTS」というタイトルの大きなポスター（下にリストあり）の計 4 枚が読み取れる状態で配置されています。掲示板、奥の教室のドア、回転式のオフィスチェア、白いキーボードとマウス、右側のデスク近くの床にはバックパックを配置してください。顔は部分的に隠すか、ぼかして匿名性を保ちつつ、古いコンピュータ室で ChatGPT を使用する学生たちのリアルな教室の雰囲気を表現してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="ソーシャルメディア投稿 - 2000 年代初頭のコンピュータ室と ChatGPT - Image 1">
</div>

#### 📌 詳細

- **作者:** [@levelsio](https://x.com/levelsio)
- **ソース:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14675)**

---

### No. 32: ソーシャルメディア投稿 - カラスと犬を伴うパティオでのシュールなポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、座っている人物が小型犬を抱え、頭の上に黒い鳥が止まっている、フォトリアルで少し奇妙なポートレートを生成します。エディトリアルスタイルのシュールな写真撮影に最適です。

#### 📝 プロンプト

```
静かな中庭やパティオに座る人物の、少しシュールでありながらフォトリアルなポートレート。フレームの中央に配置され、繊細なピンクの花柄と胸元に少女のイラストがプリントされた、体にフィットする白い長袖のタートルネックトップスを着用し、ゆったりとしたクリーム色の花柄パンツを合わせています。人物はシンプルな白い金属製の椅子に座り、膝の上にはふわふわしたプードルのような小型犬を抱えています。犬はオフホワイトの巻き毛で、耳がオレンジ色に染められています。人物のダークカラーのお団子ヘアの上には、左を向いた黒いカラスまたはワタリガラスが止まっており、まるでそこが定位置であるかのように落ち着いてバランスをとっています。被写体のポーズは静止しており、まっすぐでフォーマルなため、奇妙で無表情な家族写真のような雰囲気を醸し出しています。背景は質感のあるオフホワイトのスタッコ壁で、以下の 4 つの目立つ装飾要素を配置してください：左上に茶色の太陽の形をした壁飾り 1 つ、左側に小さな鳥の置物と垂れ下がる花が飾られた小さな壁掛けプランターシェルフ 1 つ、右側に明るい青空と柔らかな白い雲が描かれた背の高いアーチ型の窓または壁画 1 つ、右下に長い緑の葉と 2 つのフラミンゴの置物が飾られた白い台座付きプランター 1 つ。左下に石の縁取りと暗い緑の植物を少し加え、床は茶色のタイル敷きにします。照明は柔らかな自然光で、少し曇ったような落ち着いた色調、浅い被写界深度、ヴィンテージのエディトリアル写真のようなルックに仕上げてください。構図は縦位置で、座った全身像を正面から捉え、バランスのとれた静かで奇妙な雰囲気にします。メインの人物を {argument name="person" default="中年の女性"}、鳥を {argument name="bird type" default="黒いカラス"}、犬種を {argument name="dog type" default="小型のプードルミックス"}、犬の耳の色を {argument name="dog ear color" default="オレンジ"}、衣装の配色を {argument name="outfit colors" default="白と色あせたピンクの花柄"} にカスタマイズしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="ソーシャルメディア投稿 - カラスと犬を伴うパティオでのシュールなポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [@levelsio](https://x.com/levelsio)
- **ソース:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14674)**

---

### No. 33: ソーシャルメディア投稿 - ムード漂う海岸沿いのロードトリップ・ポートレート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ヴィンテージセダンが駐車された海岸沿いのシネマティックなポートレートを生成します。ノスタルジックな旅行写真やライフスタイルイメージに最適です。

#### 📝 プロンプト

```
曇りの日の海岸沿いの濡れた路肩に立つ {argument name="person" default="若い女性"} を捉えた、シネマティックなスナップ写真。後ろ姿から少し横に回り込んだアングルで、彼女がカメラの方を振り返っている様子。無造作にまとめられたダークヘアのお団子からは風になびく後れ毛が見え、表情は柔らかくぼかされている。着用アイテムは、着古したタンブラウンのキャンバスジャケットとミディアムブルーのジーンズ。片手をポケットに入れたり近くに添えたりしたリラックスした姿勢。背景はムードのある断崖絶壁のハイウェイで、左側には暗い岩山、右側には遠くまで広がる淡い灰色の海、そして曇り空が広がる。フレームの右端には、1980年代後半から1990年代初頭のライトカラーのセダンがリアをこちらに向けて駐車されており、近くには大きな岩のバリケードがある。アスファルトは雨上がりを思わせる暗く湿った質感で、かすかな駐車ラインが見える。自然光を活かし、落ち着いた寒色系のトーン、わずかなフィルム粒子、ソフトフォーカス、薄い霧を加え、ノスタルジックな 35mm フィルムのロードトリップ写真のような美学を表現する。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="ソーシャルメディア投稿 - ムード漂う海岸沿いのロードトリップ・ポートレート - Image 1">
</div>

#### 📌 詳細

- **作者:** [@levelsio](https://x.com/levelsio)
- **ソース:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14673)**

---

### No. 34: ソーシャルメディア投稿 - 黒いドレスで踊る女性

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、薄暗いラウンジで優雅に踊る、流れるような黒いドレスをまとった女性の映画のようなフォトリアルなナイトライフポートレートを生成します。ファッション、パフォーマンス、SNS 用のビジュアルに最適です。

#### 📝 プロンプト

```
高級感のある薄暗いラウンジやバーで、力強く踊る女性のドラマチックな全身写真。ハイスリットが入った洗練された黒のイブニングドレスを着用し、動きに合わせてベルベットのような生地が外側に大きく広がっている。長くストレートな {argument name="hair color" default="black"} の髪が片側に流れており、スリムで引き締まった体型に小さなフープピアスを身につけている。片腕を頭上に優雅に上げ、もう片方を下に曲げた、自信に満ちたスタイリッシュなダンスポーズを捉える。胴体は横向きで、エレガンスと躍動感を強調。背景は映画のように薄暗く、温かみのあるアンバー色の照明、柔らかなボケ味、そして座っている観客や左側の光るテレビ画面がぼやけて映り込んでいる。クールで官能的、かつ高級感のある雰囲気。強いコントラスト、浅い被写界深度、リアルな肌の質感、ドレスの裾の繊細な動き、ファッション誌のようなライティング。フォトリアル、ダイナミックなナイトライフ写真、縦構図。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="ソーシャルメディア投稿 - 黒いドレスで踊る女性 - Image 1">
</div>

#### 📌 詳細

- **作者:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **ソース:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14506)**

---

### No. 35: インフォグラフィック / 教育ビジュアル - パリのグルメランキングポスター用プロンプト

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

GPT Image 2 で使用するために設計された、都市のグルメランキングポスターを作成するためのシンプルなプロンプトです。

#### 📝 プロンプト

```
{argument name="city" default="パリ"} の {argument name="topic" default="グルメ"} ランキングポスターを作成してください
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - パリのグルメランキングポスター用プロンプト - Image 1">
</div>

#### 📌 詳細

- **作者:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **ソース:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **公開日:** 2026年4月22日
- **言語:** zh

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14370)**

---

### No. 36: インフォグラフィック / 教育ビジュアル - 中国書体比較シート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

5 つの著名な書体で同じ中国語のフレーズを表現した縦型のリファレンスポスター。タイポグラフィのテスト、文化デザインの研究、筆文字の比較に最適です。

#### 📝 プロンプト

```
{"type":"中国書体比較シート","subject":"5 つの歴史的な書体で書かれた同一の 5 文字のフレーズ","phrase":"{argument name=\"calligraphy text\" default=\"视觉新时代\"}","canvas":{"orientation":"縦型ポスター","background":"繊維の質感が残る温かみのあるオフホワイトの宣紙、わずかな経年変化と柔らかな色ムラ"},"layout":{"structure":"薄い区切り線で分けられた 5 つの水平行","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","趙孟頫","顔真卿","蘇軾"],"rows":[{"position":"1 行目","style":"王羲之にインスパイアされた行書","main text":"视觉新时代","label":"王羲之","seal":"右端に小さな赤い正方形の印"},{"position":"2 行目","style":"宋徽宗の痩金体にインスパイアされた、鋭い角と軽やかな間隔を持つ優雅な書体","main text":"视觉新时代","label":"宋徽宗","seal":"右端に小さな赤い正方形の印"},{"position":"3 行目","style":"趙孟頫にインスパイアされた洗練された楷行書","main text":"视觉新时代","label":"趙孟頫","seal":"右端に小さな赤い正方形の印"},{"position":"4 行目","style":"顔真卿にインスパイアされた力強く重厚な楷書","main text":"视觉新时代","label":"顔真卿","seal":"右端に小さな赤い正方形の印"},{"position":"5 行目","style":"蘇軾にインスパイアされた表現力豊かで力強い行書","main text":"视觉新时代","label":"蘇軾","seal":"右端に小さな赤い正方形の印"}],"left label design":"各行の左端に、黒い漢字が記された細長いベージュ色の名札を配置","centerpiece":"各行の中央に配置された大きな黒い筆文字"},"style":{"ink":"かすれや筆の運び、筆圧の変化、自然な筆致が感じられる深みのある墨色","mood":"学術的、実験的、博物館の展示資料のような雰囲気","composition":"余白を活かしたクリーンな構成、バランスの取れた行間、正面からのスキャンまたは撮影画像"},"quality":{"detail":"高解像度、鮮明な筆の質感、リアルな紙の粒子","lighting":"影のない柔らかく均一なスタジオ照明"}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 中国書体比較シート - Image 1">
</div>

#### 📌 詳細

- **作者:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **ソース:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14448)**

---

### No. 37: インフォグラフィック / 教育ビジュアル - カントリーボール：ホルムズ海峡の対峙

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ホルムズ海峡で互いに道を塞ぐアメリカとイランを描いた風刺的なカントリーボールミームを生成します。時事ネタのユーモアや地政学的なSNS投稿に最適です。

#### 📝 プロンプト

```
シンプルなカントリーボールのカートゥーンスタイルで描かれた、ユーモアあふれる政治風刺ミームのイラスト。{argument name="location label" default="ホルムズ海峡"} の狭いチョークポイント（要衝）における現状を表現してください。明るいフラットカラー、太い黒の輪郭線、手描き風のインフォグラフィックのような清潔感のあるワイドなランドスケープ構図を使用します。前景には、両側に岩がある非常に狭い砂の陸橋の上に、肩を並べて立つ 2 つのカントリーボールを配置し、一度に一人しか通れない状況を強調してください。左側には、アメリカの国旗が描かれ、黒いサングラスと茶色のカウボーイハットをかぶり、頑固な態度で相手と向き合う {argument name="left country" default="アメリカ"} のカントリーボールを配置します。右側には、イランの国旗が描かれ、暗いターバンのような帽子をかぶり、怒ったような吊り目で道を譲ろうとしない {argument name="right country" default="イラン"} のカントリーボールを配置します。それぞれの横に大きな白い吹き出しを 2 つ追加し、両方の吹き出しに同じ太字の韓国語を入れます：{argument name="speech bubble text" default="길"}。中景と背景には、合計 9 隻の船で混雑する青い海を描きます。左端に 2 隻の灰色の米軍艦、赤い中国国旗を掲げた 1 隻の中国潜水艦、中央左から中央にかけて異なる国旗を掲げた 4 隻の石油タンカー、そして狭い通路の近くに小さなアメリカ国旗を掲げた 2 隻の灰色の軍艦を配置してください。右上には、海岸線に沿って大きなイラン国旗を重ねます。水路の周囲には、ホルムズ海峡の簡略化された地図のように見えるベージュ色の陸地を描きます。中央下部の砂の上には、韓国語と英語で太字のキャプションを追加します：{argument name="bottom caption" default="호르무즈 해협 (Hormuz Strait)"}。全体的に風刺的で緊張感のあるミームのような雰囲気にしつつ、視覚的には可愛らしく読みやすい仕上がりにしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - カントリーボール：ホルムズ海峡の対峙 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **ソース:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14685)**

---

### No. 38: インフォグラフィック / 教育ビジュアル - 身体検査問題のレイアウト

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

複数の問題と解答が記載された高校の試験用紙の画像を生成するためのプロンプトです。

#### 📝 プロンプト

```
generate a image of physical {argument name="subject" default="high school exam"} question {argument name="type" default="multiple question"} 9:16. generate 4 images and each image is an answer of provided question
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 身体検査問題のレイアウト - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 身体検査問題のレイアウト - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 身体検査問題のレイアウト - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 身体検査問題のレイアウト - Image 4">
</div>

#### 📌 詳細

- **作者:** [zdhpeter](https://x.com/peter6759)
- **ソース:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14340)**

---

### No. 39: インフォグラフィック / 教育ビジュアル - ヴィンテージ風韓国海苔巻き（キンパ）レシピポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、食品マーケティング、レストランの装飾、または料理文化のビジュアルに適した、アンティーク調の韓国海苔巻き（キンパ）レシピのインフォグラフィックポスターを生成します。

#### 📝 プロンプト

```
古びたベージュの羊皮紙風の紙に、わずかにシミや質感のある背景、暗い装飾的な縁取り、伝統的な手描きの墨絵と水彩画風のスタイルで、ヴィンテージの韓国料理ポスターを作成してください。このポスターは、{argument name="dish name" default="정통 한국 김밥"} に関する縦長のインフォグラフィックで、上部にはエレガントで大きな韓国語の書道、その下には {argument name="subtitle text" default="Traditional Korean Gimbap"} と書かれた曲線状のリボンバナーを配置します。中央上部には、大きな磁器の皿にきれいに積み上げられた 12 切れのキンパを描いてください。各断面には、白いご飯、黄色い卵、オレンジ色の人参、緑のほうれん草、黒い海苔という具材がはっきりと見えるようにします。皿の右側には、小さな磁器に入ったキムチと、「간단한 보여도 정성이 들어간 한국의 맛! ♥」と書かれた短い手書き風の韓国語のメモを添えてください。右上付近には、韓国語が刻印された小さな赤い印鑑風のスタンプを押します。中央には、「재료」と書かれたリボンヘッダーの下に、6 つの具材パネルを 1 列に並べたセクションを設けます。1. 김 (건김) は積み重ねた海苔、2. 밥 (양념 밥) はご飯茶碗、3. 계란 (지단용) はスライスした卵焼き、4. 당근 (채썰어볶기) は千切り人参、5. 시금치 (데쳐서 무치기) は味付けほうれん草、6. 단무지 (김밥용) は黄色いタクアンの細切り。その下には「만드는 순서」というリボンヘッダーを配置し、左から右へ矢印で繋がれた 6 つのステップパネルを 2 行 3 列で表示します。ステップ 1 は「1 밥 간하기」とし、ごま油と塩を添えたご飯のボウルを描き、キャプションに「밥에 참기름 소금으로 간하기」と入れます。ステップ 2 は「2 속재료 준비하기」とし、卵、人参、ほうれん草が乗ったまな板と包丁を描き、キャプションに「재료 볶아 속재료 준비하기」と入れます。ステップ 3 は「3 김과 밥 펴기」とし、巻きすの上に海苔を置き、ご飯を広げている様子を描き、キャプションに「김에 밥 얇게 펴기」と入れます。ステップ 4 は「4 속재료 얹기」とし、ご飯の上に具材を横一列に並べた様子を描き、キャプションに「속재료를 차례로 얹기」と入れます。ステップ 5 は「5 단단하게 말기」とし、両手で巻きすをしっかりと巻いている様子を描き、キャプションに「김밥을 단단하게 말기」と入れます。ステップ 6 は「6 썰어 완성하기」とし、包丁でキンパを切り分けている様子を描き、キャプションに「먹기 좋게 썰어 완성!」と入れます。一番下には、{argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} と力強い韓国語の書道で書かれた幅広のバナーと小さなハートを配置します。下部の隅には花のモチーフをあしらい、右下には「福」という漢字が刻まれた赤い正方形の印鑑を押してください。セピア、ブラウン、クリーム、オリーブグリーン、色あせた赤などの落ち着いた色調を使用し、繊細なスケッチの輪郭、柔らかな水彩の陰影、そして本物の印刷ポスターのような構成に仕上げてください。左上隅には、{argument name="brand text" default="Pollo AI GPT Image 2"} と書かれた小さなモダンなオーバーレイロゴを追加してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - ヴィンテージ風韓国海苔巻き（キンパ）レシピポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [폴로 AI](https://x.com/polloai_kr)
- **ソース:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14554)**

---

### No. 40: インフォグラフィック / 教育ビジュアル - ヴィンテージ風フランス風クレープのレシピポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

バタークレープ、材料、6つの調理工程が描かれた、豊かなイラストのアンティーク調フランス風レシピポスター。食をテーマにしたエディトリアルアートやキッチンの装飾用プリントに最適です。

#### 📝 プロンプト

```
{"type":"ヴィンテージ風フランス風レシピポスター","subject":"クラシックなバタークレープのための装飾的なイラスト入りフードインフォグラフィック","style":{"overall":"アンティークな料理本ポスター、ベル・エポック時代のフランスのカフェの紙もの、手描きの水彩とインクのイラスト、古びた羊皮紙の質感、落ち着いた温かみのあるクリーム色、タン、ブラウン、ダスティブルー、色あせた赤のパレット","rendering":"非常に読みやすい装飾的なタイポグラフィ、彫刻風の装飾枠、紙の柔らかなシミ、風化したエッジ、繊細な花のフィリグリー、ノスタルジックな職人風プリントの美学"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"材料","method_header":"作り方","footer_banner":"Un classique de la gourmandise, à savourer chaud!","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"縦長","border":"四隅にスクロールワークをあしらった、全面装飾イラスト枠","sections":[{"title":"ヒーローセクション","position":"上部","count":3,"labels":["リボンと大きなスクリプト体で書かれたメインタイトル","皿に盛られたクレープの山","Cidre de Bretagne とラベルされたグラス"]},{"title":"材料","position":"中央","count":6,"labels":["1. 小麦粉 1 カップ","2. 卵 2 個","3. 牛乳 2 カップ","4. バター 50g","5. 砂糖 大さじ 1","6. 塩 少々"]},{"title":"作り方","position":"下部中央","count":6,"labels":["1 乾いた材料を泡立て器で混ぜる","2 卵を加えて混ぜる","3 牛乳を少しずつ加える","4 溶かしバターを加えて混ぜる","5 クレープパンを熱する","6 裏返して焼く！"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"青と白の花柄の陶磁器の皿","food":"粉砂糖をまぶし、溶けたバターをのせた、約 {argument name=\"crepe count\" default=\"14\"} 枚の薄い黄金色のクレープの山","surface":"素朴な木製のテーブルトップ","cloth":"右側に置かれた青と白のチェック柄のナプキン","background":"教会の尖塔と古いヨーロッパの建物が並ぶ、色あせた牧歌的な街並み"},"ingredients":[{"index":1,"item":"小麦粉","container":"装飾された陶磁器のボウル","caption":"小麦粉 1 カップ"},{"index":2,"item":"卵","count":2,"caption":"卵 2 個"},{"index":3,"item":"牛乳","container":"青い花柄の陶磁器のピッチャー","caption":"牛乳 2 カップ"},{"index":4,"item":"バター","container":"バターブロックをのせた小皿","caption":"バター 50g"},{"index":5,"item":"砂糖","container":"スプーン付きの陶磁器のボウル","caption":"砂糖 大さじ 1"},{"index":6,"item":"塩","container":"SEL とラベルされた蓋付きの壺","caption":"塩 少々"}],"method_panels":[{"index":1,"title":"乾いた材料を混ぜる","image":"小麦粉と泡立て器が入ったミキシングボウル","caption":"小麦粉と砂糖を混ぜる"},{"index":2,"item":"卵を加えて混ぜる","image":"ボウルに卵を入れ、泡立て器で混ぜている様子、近くに割れた卵の殻","caption":"溶き卵を加える"},{"index":3,"item":"牛乳を少しずつ加える","image":"陶磁器のピッチャーから生地に牛乳を注いでいる様子","caption":"牛乳を少しずつ加える"},{"index":4,"item":"溶かしバターを加えて混ぜる","image":"小さなフライパンからボウルに溶かしバターを注いでいる様子","caption":"溶かしバターを加える"},{"index":5,"item":"クレープパンを熱する","image":"青いガス火の上で熱せられている空の黒いクレープパン","caption":"クレープパンを熱する"},{"index":6,"item":"裏返して焼く！","image":"金属製のスパチュラで端を持ち上げているフライパンの中のクレープ","caption":"両面を裏返して焼く"}],"decorative_elements":{"count":8,"labels":["上部タイトルの後ろのリボンバナー","材料ヘッダーの後ろのリボンバナー","作り方ヘッダーの後ろのリボンバナー","大きな下部リボンバナー","タイトルの左側の花のつるの装飾","花のコーナー装飾","丸まった羊皮紙のスクロールスタイル","材料パネルと作り方パネルの間の細い仕切り線"]},"quality":"バランスの取れた左右対称の構図、くっきりと読みやすいフランス語と英語のテキスト、詳細でありながらすっきりとしたインフォグラフィックレイアウト、魅力的な古き良き時代の料理ポスター"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - ヴィンテージ風フランス風クレープのレシピポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [Pollo AI France](https://x.com/PolloAIFR)
- **ソース:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14564)**

---

### No. 41: インフォグラフィック / 教育ビジュアル - 10 代向けブラックホール物理学インフォグラフィック

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、複雑なブラックホールとダークマターに関する論文を、SNS 投稿や教育記事向けに遊び心のある親しみやすいスタイルで解説する、情報密度の高い 1 ページの編集用科学インフォグラフィックを生成します。

#### 📝 プロンプト

```
{"type":"編集用科学インフォグラフィックポスター","style":"10 代向けの親しみやすい雑誌風教育インフォグラフィック。手書き風の物理学図解、キャラクター、すっきりとした編集用タイポグラフィを組み合わせる","topic":"原始ブラックホール、ホーキング放射、記憶負荷（memory-burden）ダークマター","canvas":{"orientation":"縦長","background":"温かみのあるクリーム色の紙の質感、微細な粒子感","border":"ページ全体を囲む細い落ち着いたグレーの長方形の枠"},"headline":{"title":"消えることを拒んだブラックホール","subtitle":"宇宙誕生の最初の 1 秒に生まれた小さなブラックホールと、それがダークマターとして隠れているかもしれないという奇妙な新物理学。","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"閃光の中の誕生","position":"左上","count":4,"labels":["渦巻く初期宇宙の誕生図","砂粒より小さく山より重い原始ブラックホール","ビッグバンから 10^-30 秒後の時計アイコン","温度計アイコン"]},{"title":"通常のブラックホールは蒸発する","position":"右上","count":4,"labels":["左から右へ縮小していく 3 段階のブラックホール","各段階の周囲に描かれた粒子放出の波線","スティーヴン・ホーキングの解説文","ステッカー風引用句：\"ブラックホールはそれほど黒くない\" — S. Hawking, 1974"]},{"title":"物語の転換点：記憶負荷（memory burden）","position":"中央","count":4,"labels":["『MEMORY』と書かれたバックパックを背負った、困り顔のブラックホールのキャラクター","情報が詰まりすぎて蒸発しきれない様子を語る吹き出し","数式：通常の速度 ÷ (膨大な情報量)^k = 非常に遅い速度","Gia Dvali による 2018 年の提案に関する注釈"]},{"title":"2 種類の幽霊粒子","position":"中央下","count":5,"labels":["左側の高速移動する粒子","右側のゆっくりとした温かい粒子キャラクター","ビッグバンから現在までのタイムライン","『速くて冷たい』クラウドラベル","『遅くて温かい』クラウドラベル"]},{"title":"どうやって見つけるのか：ライマンαの森","position":"左下","count":4,"labels":["水素雲を通過する古代銀河に関する解説文","ギザギザした吸収線の森のグラフィック","手書きのメモ：『森が語る：私たちは気づくはずだ。』","地球から遠方のクエーサーまでの軸のコンセプト"]},{"title":"この論文が示すこととは？","position":"右下","count":1,"labels":["角の丸い長方形の要約ボックス"]}],"count":6},"visuals":{"color_palette":["ウォームベージュ","ダークネイビー","ラストオレンジ","ダスティティール","ソフトブラウン","落ち着いたグレー"],"illustration_notes":"少しラフな輪郭線を持つフラットなベクター形状、柔らかな影、丸みを帯びたフォルム。遊び心がありつつも科学的に正確","typography":"見出しには大きなセリフ体のオールキャップス、セクションヘッダーには太字のサンセリフ体、本文はコンパクトで読みやすく、アクセントとして手書き風テキストを使用"},"objects":{"count":15,"items":["1 ページ全体の枠","1 見出しブロック","1 初期宇宙の渦巻き図","1 小さな原始ブラックホールの点と引き出し線","1 時計アイコン","1 温度計アイコン","3 蒸発するブラックホールの図","1 ホーキングの引用ステッカー","1 バックパックを背負ったブラックホールのキャラクター","1 吹き出し","1 数式ブロック","2 クラウドラベル","1 左下のスペクトル森林イラスト"]},"text_blocks":{"count":9,"items":["見出しタイトル","見出しサブタイトル","著者クレジット","『閃光の中の誕生』本文","『通常のブラックホールは蒸発する』本文","『記憶負荷』解説文","『幽霊粒子』キャプション","『ライマンαの森』解説","最終的な要約"]},"composition":"情報が凝縮されていながらも読みやすい 1 ページの解説ポスター。複数のイラスト付き引き出し線があり、左から右、上から下への明確な視線の流れ。高度な物理学の論文を好奇心旺盛な 10 代にも親しみやすく感じさせる、シェア可能な科学ポスターとしてデザイン"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 10 代向けブラックホール物理学インフォグラフィック - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 10 代向けブラックホール物理学インフォグラフィック - Image 2">
</div>

#### 📌 詳細

- **作者:** [Alphin Tom](https://x.com/alphinctom)
- **ソース:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14424)**

---

### No. 42: インフォグラフィック / 教育ビジュアル - 学術経済学チャートシミュレーション

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

経済学論文のスタイルで、原油価格とサメの襲撃件数の相関関係を示すような、非常にリアルかつ架空の学術チャートを生成するためのプロンプトです。

#### 📝 プロンプト

```
権威ある {argument name="field" default="経済学論文"} からの折れ線グラフ。{argument name="time period" default="1914 年から 2001 年"} の間における {argument name="variable one" default="原油価格"} と {argument name="variable two" default="サメの襲撃件数"} の間の、完全ではないものの密接な関係性を示すもの。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 学術経済学チャートシミュレーション - Image 1">
</div>

#### 📌 詳細

- **作者:** [QC](https://x.com/QiaochuYuan)
- **ソース:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14396)**

---

### No. 43: インフォグラフィック / 教育ビジュアル - 抽象芸術的な科学グラフ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Jean-Michel Basquiat の独特なスタイルとヴォイニッチ手稿の美学を融合させ、AI タスクの展望グラフを独創的に解釈したプロンプトです。

#### 📝 プロンプト

```
{argument name="subject" default="AI タスクの展望グラフ"} に {argument name="style" default="Basquiat"} のタッチを加え、幽霊が取り憑いたような、{argument name="source" default="ヴォイニッチ手稿"} 由来の、朽ち果てた桟橋のような表現。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 抽象芸術的な科学グラフ - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 抽象芸術的な科学グラフ - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 抽象芸術的な科学グラフ - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 抽象芸術的な科学グラフ - Image 4">
</div>

#### 📌 詳細

- **作者:** [Ethan Mollick](https://x.com/emollick)
- **ソース:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14397)**

---

### No. 44: インフォグラフィック / 教育ビジュアル - 日本語 AI モデル用処方箋シート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

AI モデル向けのユーモラスな日本語処方箋を模した、リアルな俯瞰写真です。公式風のパロディ書類やモックアップ資料の作成に最適です。

#### 📝 プロンプト

```
{
  "type": "日本語処方箋パロディ書類",
  "style": "写真のようにリアルな書類の俯瞰写真",
  "subject": "温かみのある木製テーブルの上に置かれた、日本語で印刷された白い処方箋シート 1 枚",
  "document": {
    "paper": {
      "size": "A4 縦",
      "color": "白",
      "orientation": "時計回りにわずかに回転",
      "condition": "自然な紙の質感がかすかに残る、平らで清潔なシート"
    },
    "print": {
      "ink": "黒、赤の印影ボックス 1 つ",
      "font": "日本語の明朝体とシンプルなゴシック体の表テキストの組み合わせ",
      "linework": "細い灰黒色の罫線と区切り線"
    },
    "header": {
      "title": "処方箋",
      "subtitle": "（この処方箋は、大規模言語モデル用です）",
      "date_label": "発行日：",
      "date_value": "{argument name=\"issue date\" default=\"2025 年 6 月 5 日\"}"
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
      "position": "用紙右下",
      "shape": "角丸長方形の赤い印影ボックス",
      "text_lines": 3,
      "text": ["OpenAI", "代表取締役", "サム・アルトマン"]
    },
    "disclaimer": "※この処方箋は非実在のモデルに対する診断・治療を目的としたものです。"
  },
  "layout": {
    "camera_angle": "真上からの俯瞰",
    "framing": "用紙全体が見え、周囲に木製デスクの余白がわずかにある",
    "lighting": "柔らかな室内環境光、均一な照明、用紙の端にわずかな影",
    "sections": [
      { "title": "header", "position": "上部", "count": 3, "labels": ["処方箋", "（この処方箋は、大規模言語モデル用です）", "発行日：2025 年 6 月 5 日"] },
      { "title": "patient info", "position": "中上部", "count": 4, "labels": ["患者名", "性別", "年齢", "モデル名"] },
      { "title": "main two-column content", "position": "中央", "count": 2, "labels": ["持病・症状（大規模言語モデル特有の持病）", "処方内容（治療・対策）"] },
      { "title": "bottom area", "position": "下部", "count": 4, "labels": ["備考", "医師名", "医療機関名", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 日本語 AI モデル用処方箋シート - Image 1">
</div>

#### 📌 詳細

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **ソース:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14536)**

---

### No. 45: インフォグラフィック / 教育ビジュアル - 日本語版 AI 診療明細書

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

AI モデル向けに作成された、リアルな日本語の医療明細書パロディです。ユーモアのあるクリニック風の書類やドキュメントのモックアップ作成に最適です。

#### 📝 プロンプト

```
{"type":"日本語版医療明細書パロディドキュメント","medium":"クリーンなフラットレイの書類写真","subject":"薄茶色の木製テーブルの上に置かれた 1 枚の印刷済み検査明細書","style":{"overall":"リアルなオフィス書類、フォーマルな日本のクリニックの書類、白い紙に鮮明な黒インク、ミニマルなデザイン、整った罫線、上部からのわずかなパース","lighting":"柔らかな均一の室内照明、シートの周囲にわずかな自然な影","paper":"A4 白紙、縦向き"},"document":{"title":"診療明細書（検査）","date_label":"発行日","date":"{argument name=\"issue date\" default=\"2025 年 6 月 5 日\"}","patient_block":{"count":3,"labels":["患者名","モデル名","保険種類"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","LLM 保険"]},"clinic_block":{"count":4,"labels":["クリニック名","住所","TEL","医師・診療科"],"values":["{argument name=\"clinic name\" default=\"AI メディカルクリニック\"}","東京都千代田区丸の内 1-2-3","03-1234-5678","医師名：サム・アルトマン / 診療科：AI 総合診療科"]},"main_table":{"columns":["検査項目","検査内容","点数","金額（円）","自己負担額（円）"],"row_count":4,"rows":[{"item":"1. 言語理解・推論能力検査","description":"言語理解、論理的推論、知識統合能力の評価","score":"120 点","price":"1,200","copay":"360"},{"item":"2. 幻覚・事実誤認傾向検査","description":"事実に基づく正確性の評価および幻覚傾向の検出","score":"90 点","price":"900","copay":"270"},{"item":"3. 応答安全性・バイアス検査","description":"有害出力リスク、バイアス傾向の評価","score":"110 点","price":"1,100","copay":"330"},{"item":"小　計","description":"","score":"320 点","price":"3,200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【保険適用内訳】","lines":["保険名称：LLM 保険","保険者番号：LLM-2025-0605","適用区分：検査料","負担割合：3 割","保険適用額：2,240 円","自己負担額：960 円"]},{"title":"【請求金額】","lines":["検査料合計：3,200 円","保険適用額：2,240 円","自己負担額：960 円","今回ご請求額：960 円"]},{"title":"【診療情報】","lines":["検査日：2025 年 6 月 5 日","診療日：2025 年 6 月 5 日","診療番号：AIMC-20250605-001","上記の通り領収いたしました。"],"stamp_box_label":"収　印"}]},"footer":{"count":2,"notes":["※この明細書は再発行いたしませんので、大切に保管してください。","※ご不明な点がございましたら、上記クリニックまでお問い合わせください。"]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["1 枚の用紙","木製デスクの背景"],"camera_angle":"トップダウン、わずかな傾斜あり","margins":"用紙全体が視認可能で、周囲にデスクの縁がわずかに見える"},"quality":"高解像度のフォトリアルなドキュメントモックアップ、鮮明で読みやすいタイポグラフィ、正確な日本語レイアウト"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 日本語版 AI 診療明細書 - Image 1">
</div>

#### 📌 詳細

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **ソース:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14535)**

---

### No. 46: インフォグラフィック / 教育ビジュアル - 初心者向けコイン収集マンガページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

初心者の方へ向けたコイン収集の入門マンガ（1ページ構成）。教育的なSNS投稿や解説マンガ、趣味をテーマにしたプロモーション素材として最適です。

#### 📝 プロンプト

```
{"type":"1 ページ完結型教育マンガ","style":"クリーンで洗練されたアニメ調イラスト、商業マンガレイアウト、明るく親しみやすい雰囲気、初心者ガイドらしいトーン、視認性の高い日本語テキスト、装飾的なキラキラ効果、柔らかな陰影、くっきりとしたパネル枠","format":"縦型 1 ページマンガ（5 つの番号付きパネル）","subject":{"character":"アニメ調の若い女性プレゼンター","appearance":{"hair":{"color":"{argument name=\"hair color\" default=\"非常に明るいシルバーブルー\"}","style":"柔らかな前髪と長いサイドの髪を持つ非常に長いストレートヘア、両サイドに青いリボン付き"},"outfit":"ネイビーと白のファンタジー風ドレス、黒の半透明な胸元パネル、青い宝石のアクセント、黒の長い指なし手袋、青いリボンと金の星の飾りがついたネイビーのベレー帽","expression":"陽気で親しみやすく、熱心なコイン収集ガイド"}},"theme":"初心者向けのコイン収集入門","language":"日本語","layout":{"panels":[{"number":1,"position":"上部全幅","scene":"クリーム色の背景に浮かぶ金貨と銀貨を背景に、コインを顔の近くに掲げるプレゼンターのバストアップ","text_elements":{"speech_bubble":"はじめまして、メイヤです！今日は“コイン収集の楽しみ方”を初心者向けに紹介します！","caption_box":"コイン収集って、実はとても奥深い趣味！"}},{"number":2,"position":"中央全幅","scene":"木製のテーブルの上に 5 枚のコインや関連アイテムが並び、その背後からプレゼンターが指をさしている様子。温かみのある室内背景とキラキラしたエフェクト","count":5,"items":["1964 年発行の大きな銀色の米国クォーターコイン","茶色の日本の 1 円硬貨風","建物が描かれた金色の記念コインまたはメダル（1000 円の文字入り）","小さな銀貨","2020 年 日本 100 円パラリンピック TOKYO NGC MS 69 とラベルされた鑑定済みコイン"],"text_elements":{"speech_bubble":"楽しみ方はいろいろ！たとえば…","bullet_list_count":4,"bullet_list":["歴史を知る","デザインを味わう","国や時代で集める","予算内で少しずつ増やす"]}},{"number":3,"position":"左下","scene":"白い手袋をはめて、1 枚の銀貨を慎重に観察するプレゼンターのクローズアップ。淡い背景にキラキラしたエフェクト","text_elements":{"speech_bubble":"同じコインでも、状態や雰囲気がぜんぜん違うんです！","caption_box":"保存状態を見るのも面白い！"}},{"number":4,"position":"右下","scene":"コインフェアやコインショップのブース。プレゼンターが茶色の財布を持ち、価格のついた 3 枚のコインが入ったガラスケースを覗いている。背景にはコインフェアの看板があり、人々が閲覧している様子","count":3,"display_case_items":["1,200 円のタグ付きコイン","3,800 円のタグ付きコイン","12,000 円のタグ付きコイン"],"background_sign":"コインフェア開催中！","text_elements":{"main_speech":"最初は“無理のない予算”でOK！まずは気になった 1 枚から！","thought_bubble":"いきなり高額品じゃなくても大丈夫…！"}},{"number":5,"position":"下部全幅","scene":"ピンクのキラキラした背景で、プレゼンターがコインアルバムとコレクションケースを指し示している、励ましの最終パネル","count":2,"collection_items":["金貨、銀貨、銅貨が複数入った青いコイントレイ","コインポケットとホルダーに複数のコインが入った開いたアルバムバインダー"],"text_elements":{"large_speech":"大事なのは、“好き”を見つけること！1 枚との出会いが、コレクションの始まりです♪","left_caption_box":"まずは“気になる 1 枚”を探してみよう！","right_banner":"さいごに…","right_summary":"見る・知る・集める——それがコイン収集の楽しさ！"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"太い黒枠でバランスよく配置されたマンガページ。各パネルは明確に区切られ、吹き出しやキャプションボックスはアートワークに統合されている。コインが視覚的なモチーフとして全体に繰り返し使用されている","color_palette":"クリーム、ゴールド、シルバー、ネイビー、ホワイト、柔らかなピンクのアクセント、温かみのある木目調","quality":"高解像度のプロ仕様マンガページ、印刷対応、洗練されたタイポグラフィとレイアウト"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 初心者向けコイン収集マンガページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **ソース:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14550)**

---

### No. 47: インフォグラフィック / 教育ビジュアル - 掛け算ドミノの教室アクティビティ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

カラフルな掛け算ドミノボードゲームで遊ぶ子供たちのリアルな教室風景。教材、学校のプロモーション、算数アクティビティのビジュアルに最適です。

#### 📝 プロンプト

```
算数の授業中の小学校の教室を捉えた、ドキュメンタリースタイルのリアルな写真。緑と青の制服を着た 10 人ほどの子供たちが木製の机を囲んで座り、カラフルな掛け算ドミノゲームに熱中している様子。カメラは子供の目線の高さにあり、手前のメインテーブルに向かってわずかに見下ろすアングル。画面中央には、ポルトガル語で「DOMINÓ DA MULTIPLICAÇÃO（掛け算ドミノ）」と下部に、「TREINANDO AS TABUADAS（九九の練習）」と中央に記された正方形の教育用ボードゲームを配置。その周囲を色鮮やかなドミノ風の掛け算タイルが囲んでいる。このメインボードを囲んで夢中になっている 4 人の子供たちを鮮明に描写する。1 人は黄色いタイルをボードに置き、1 人は色とりどりのタイルの束を持ち、1 人は左側から見守り、もう 1 人は手前で袖が青い服を着てピースを並べている。中央左と右下に「JOGO DE DOMINÓ」とラベルが貼られた浅い木箱を 2 つ配置し、それぞれの中にカラフルな長方形のドミノピースを入れる。机の上には鉛筆 3 本、ワークシート 2 枚、水筒 1 本、筆箱、ノート、予備のゲームタイルを自然に散らす。背景には、他の生徒たちが座る机、本棚、子供たちの絵が貼られたコルクボード、左側の壁には「TABUADA DE MULTIPLICAÇÃO（掛け算九九表）」と書かれた大きなポスターを、ピントをぼかして配置する。右側の高い窓から明るい自然光が差し込み、温かみのある活気に満ちた本物の学校の雰囲気を演出する。教育用ボードとタイルには、黄色、青、ピンク、緑、オレンジといった鮮やかな教室カラーを使用する。顔は目立たせないようにし、ハンズオン学習、協力、掛け算ドミノのアクティビティに焦点を当てる。縦構図、非常にリアルな写真、教室での何気ない瞬間、手前の鮮明なディテール、背景の柔らかな被写界深度。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 掛け算ドミノの教室アクティビティ - Image 1">
</div>

#### 📌 詳細

- **作者:** [Lucas Rodrigues](https://x.com/olusrodri)
- **ソース:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14632)**

---

### No. 48: インフォグラフィック / 教育ビジュアル - 印刷用掛け算ドミノワークシート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

掛け算の練習をドミノ合わせゲームで行うための、ブラジルポルトガル語のカラフルな教室用ワークシートです。教師、ホームスクーリング、印刷可能な算数アクティビティに最適です。

#### 📝 プロンプト

```
ブラジルポルトガル語で作成された、縦型の印刷用教育ワークシートです。清潔感のある白い背景、遊び心のある教室向けデザイン、中央揃えの構成、太めの丸みを帯びたフォント、子供向けの明るい色使いで作成してください。最上部には、{argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"} と書かれた大きなネイビーブルーの見出しを配置し、その両側に小さな黄色の装飾的な光のラインを添えてください。その下に、白い大文字で {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"} と書かれた紫色のリボンバナーを配置します。バナーの下には、黒字で2行の指示文を中央揃えで追加してください：「Recorte as peças e embaralhe. Cada jogador pega 7 peças.」および「O objetivo é ficar sem peças!」。メインエリアには、4列×10行のグリッド状に等間隔で配置された40枚のドミノ風タイルを表示します。各タイルは、細いカラフルな枠線、白い塗りつぶし、中央の垂直仕切り、仕切り上の小さな黒い点を持つ、水平方向の角丸長方形です。左半分には数値の結果、または最初のタイルには「INÍCIO」という単語を入れ、右半分には掛け算の式を入れます。グリッド全体で紫、緑、青、オレンジ、ピンク、黄色といった枠線の色を交互に使用してください。40枚のタイルは、左から右、上から下への順で以下の通りです：1) 「INÍCIO | 1 × 1」、2) 「1 | 1 × 2」、3) 「2 | 1 × 3」、4) 「3 | 1 × 4」、5) 「4 | 1 × 5」、6) 「5 | 1 × 6」、7) 「6 | 1 × 7」、8) 「7 | 1 × 8」、9) 「8 | 1 × 9」、10) 「9 | 2 × 2」、11) 「4 | 2 × 3」、12) 「6 | 2 × 4」、13) 「8 | 2 × 5」、14) 「10 | 2 × 6」、15) 「12 | 2 × 7」、16) 「14 | 2 × 8」、17) 「16 | 2 × 9」、18) 「18 | 3 × 3」、19) 「9 | 3 × 4」、20) 「12 | 3 × 5」、21) 「15 | 3 × 6」、22) 「18 | 3 × 7」、23) 「21 | 3 × 8」、24) 「24 | 3 × 9」、25) 「27 | 4 × 4」、26) 「16 | 4 × 5」、27) 「20 | 4 × 6」、28) 「24 | 4 × 7」、29) 「28 | 4 × 8」、30) 「32 | 4 × 9」、31) 「36 | 5 × 5」、32) 「25 | 5 × 6」、33) 「30 | 5 × 7」、34) 「35 | 5 × 8」、35) 「40 | 5 × 9」、36) 「45 | 6 × 6」、37) 「36 | 6 × 7」、38) 「42 | 6 × 8」、39) 「48 | 6 × 9」、40) 「54 | 7 × 7」。下部には、幅の大部分を占める大きな角丸の紫色の破線ボックスを追加します。このボックスの左側には、太字の紫の大文字で「COMO JOGAR:」というセクションタイトルを配置し、その後に黒字で4つの箇条書きを続けます：「Coloque a peça “INÍCIO” na mesa.」、「Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.」、「Se não tiver peça para jogar, compre do monte.」、「Vence quem ficar sem peças!」。同じボックスの右側には、紫の大文字で「EXEMPLO DE INÍCIO:」というタイトルを追加し、4枚の小さなドミノタイルを順に並べ、最後に省略記号を表示します：「INÍCIO | 1 × 1」、次に「1 | 1 × 2」、次に「2 | 1 × 3」、次に「3 | 1 × 4」、続いて「...」。全体的に、小学校の算数の練習に適した、鮮明でベクター風の印刷可能なスタイルを維持し、バランスの取れた間隔と非常に読みやすいテキストを心がけてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 印刷用掛け算ドミノワークシート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Lucas Rodrigues](https://x.com/olusrodri)
- **ソース:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14631)**

---

### No. 49: インフォグラフィック / 教育ビジュアル - 歴史的発明年表グリッド

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、歴史上の発明をジオラマ風のグリッドで表現した、羊皮紙スタイルの教育用ポスターを生成します。タイムラインのインフォグラフィックや、世界を変えた技術の比較に最適です。

#### 📝 プロンプト

```
{argument name="grid size" default="15×15"} の発明年表グリッドを、古びた羊皮紙のタイル上にミニチュアのアイソメトリック・ジオラマとして描いた、正方形のインフォグラフィック風イラストを作成してください。画像は {argument name="starting year" default="1000 BC"} から {argument name="ending year" default="2026"} までを網羅した、厳選された歴史ポスターのように見えるものとし、各タイルには重複なく1つの発明を描いてください。全体の一部である 5×5 のセクションを可視化し、合計 25 個のラベル付きタイルを、細い暗い境界線で整然と配置してください。すべてのタイルには、時代に合わせた素材、色、背景のディテールで手作りされた小さなジオラマとして、世界を変えた独自の発明が描かれています。古代や中世の発明には温かみのあるアンティークなパレットを、近代の発明にはセピア調の技術文書のような色調を、現代のデジタル技術やバイオテクノロジーの発明にはクールなネオンブルーの照明を使用してください。グリッドの周囲は古い地図の枠で囲み、微妙な歴史的地図の質感を加え、右下付近でかすかな現代のネットワークグラフィックへと溶け込ませてください。

各タイルには、太字の黒いテキストで書かれたベージュの小さなキャプションタグを付けてください。左上から右下への読み順で、以下の 25 個の発明を必ず含めてください：1) {argument name="first tile label" default="1000 BC"} タイル：農地に鉄製の鋤と単純な手工具（キャプション「Iron Plow & Tools」）；2) 「Concept of Zero」：彫り込まれたゼロのシンボルと青い砂時計が描かれた羊皮紙風タイル；3) 「Water Clock」：木製の水時計装置；4) 「Catapult」：木製の攻城兵器；5) 「Antikythera Mechanism」：石のニッチに収められた精巧な青銅の歯車装置；6) 「Concrete」：湿ったセメントやモルタルで満たされた手押し車；7) 「Wheelbarrow」：単純な木製の一輪車；8) 「Windmill」：草地に立つ伝統的な風車；9) 「Gunpowder」：樽と煙を伴う黒色火薬の山；10) 「Printing Press」：古典的な柱に囲まれた木製の印刷機；11) 「Mechanical Clock」：装飾が施された置き時計；12) 「Telescope」：三脚に乗った初期の真鍮製望遠鏡とスケッチ風の科学メモ；13) 「Steam Engine」：初期の蒸気機関車が描かれた青い設計図風タイル；14) 「Electric Battery」：2本の円筒形電池と配線が描かれた設計図風タイル；15) 「Telegraph」：技術文書の上に置かれたモールス信号の電信キー；16) 「Light Bulb」：中立的な台座の上で温かく光る電球；17) 「Automobile」：ワークショップの設計図を背景にした初期の赤い自動車；18) 「Airplane」：ミニチュアの民間ジェット旅客機；19) 「Transistor」：光る回路基板タイル上の黒いマイクロチップ；20) 「Personal Computer」：CRTモニターとキーボードを備えたベージュのデスクトップPC；21) 「World Wide Web」：デジタル回路の上で光る青い地球儀；22) 「Smartphone」：ネオンテックな背景に置かれた洗練された現代のスマートフォン；23) 「CRISPR-Cas9」：バイオテックブルーのディスプレイタイル上のDNA二重らせん；24) 「Reusable Rocket」：排気煙を上げて打ち上がる数基の垂直ロケット；25) 「AI (LLMs)」：ホログラフィックな技術キューブの中で光る大きな「AI」の文字；26) 「Brain-Computer Interface」：青いプラットフォーム上で光る脳のホログラム；27) 「Advanced Neural Interface (Implant)」：脳インプラントが光る透明な人間の頭部プロファイル（上部に「2026」の小さなラベル付き）。

構成は非常に整理されたポスター風で視覚的に密度が高く、各タイルが一目で読み取れるようにしてください。わずかなアイソメトリック視点、鮮明な線画、絵画的な陰影、洗練された編集イラストの品質を使用してください。全体的な雰囲気は、博物館のポスター、教育的な年表、そして想像力豊かな歴史技術ジオラマアートを融合させたものにしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="インフォグラフィック / 教育ビジュアル - 歴史的発明年表グリッド - Image 1">
</div>

#### 📌 詳細

- **作者:** [Gadgetify](https://x.com/Gdgtify)
- **ソース:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14412)**

---

### No. 50: YouTube サムネイル - ちびサメ・アドベンチャー 映画ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

子供向けの海洋冒険映画をイメージした、カラフルな日本のアニメ風ポスター。キュートなキャラクターと迫力あるタイトルタイポグラフィで、印象的なプロモーション用キービジュアルを再現するのに最適です。

#### 📝 プロンプト

```
洗練されたアニメ調のちびキャラスタイルで描かれた、明るくエネルギッシュな日本映画のポスターイラスト。きらめく熱帯の海を舞台にした冒険シーン。構図の中心には、笑顔の青いサメに乗って、渦巻く海水と白い水しぶきの中を斜め上へと飛び跳ねる、2 人のキュートなちびっ子を配置。左側の子供は、黒い短髪で大きな潤んだ青い瞳、口を大きく開けて笑う表情。黒い T シャツにダークカラーのショートパンツ、白いスニーカーを着用し、顔を縁取る歯のついたフード付きのライトブルーのサメパーカーを着ている。片手で上を指差し、もう片方の手でサメを抱きしめている。右側の子供は、オレンジ色の髪で大きな潤んだ紫の瞳、口を大きく開けて楽しそうに笑う表情。オレンジ色のワンピースにピンクの靴を履き、歯のついたフード付きのピンクのサメパーカーを着ている。片腕を大きく広げて興奮を表現し、もう片方の手でサメにつかまっている。サメは丸みを帯びた体、白い腹、小さな黒い目、大きく開いた口を持つ、大きくフレンドリーな姿で描く。周囲には鮮やかな海中と水面の世界を表現：小さな熱帯魚の群れ、左側にウミガメ 1 匹、右側にイルカ 1 頭、右側にピンクのタコ 1 匹、左下にフグ 1 匹、下端に沿ってサンゴ礁と海草、全体に気泡、そして力強い青い水の動きのラインを描く。背景の上部には、水中にドラマチックな光が差し込む晴れた空、ふわふわした雲、飛んでいる 2 羽の海鳥、左上にヤシの木が生えた岩だらけの熱帯の島、右上に白い帆とキュートなサメのエンブレムがついた海賊船を描く。メインタイトルの背後に、舵輪の一部が見えるように配置する。密度が高くエキサイティングな日本の子供向けアニメの宣伝レイアウトを採用し、巨大な 3D 文字と爆発的なエフェクトを使用する。上部には、巨大な日本語タイトル {argument name="headline text" default="サメなの ワクワク 大作戦"} を重ねて配置。光沢のある青、オレンジピンク、黄オレンジのグラデーション文字に、太い白の縁取り、濃い青の影、水しぶき、きらめきを加える。タイトルの下には、青い縁取りの白い小さな曲線状のキャッチコピー {argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"} を追加する。下部には、巨大な公開日テキスト {argument name="release text" default="2026年 夏公開"} を配置。赤から黄色へのグラデーションの太い 3D 文字に白と青の縁取りを施し、放射状のオレンジ色のバーストの上に配置する。右下には、青いスターバースト型のバッジを追加し、その中に日本語で {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"} と白と黄色の文字で記載する。宝物をテーマにしたコーナー用小物を 2 つ配置：左下に金貨が入った開いた宝箱、右下にコンパスを置く。全体的に光沢があり、彩度が高く、家族向けで、幻想的かつ映画のような、おもちゃのような仕上がりにする。くっきりとした輪郭線、誇張された表情、高いコントラスト、ポスターに適した縦長の構図にする。フォトリアリズム、落ち着いた色調、ミニマリズムは避ける。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="YouTube サムネイル - ちびサメ・アドベンチャー 映画ポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **ソース:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14504)**

---

### No. 51: YouTube サムネイル - 日本語の 4 分割ヒーリング広告コラージュ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

コーチングや自己啓発サービス向けの、インパクトのある 4 分割日本語プロモーション用サムネイル。SNS 投稿、プロフィールリンク、マーケットプレイスのカバー画像に最適です。

#### 📝 プロンプト

```
{"type":"日本語プロモーション用 SNS サムネイルコラージュ","style":"高インパクトなクリック率重視の広告デザイン、光沢感とドラマチックな演出、4 分割のスクエアレイアウト、力強い日本語タイポグラフィ、彩度の高いカラー、発光エフェクト、キラキラ感、グラデーションオーバーレイ、緊急性を煽るマーケティングビジュアル","canvas":{"aspect_ratio":"1:1","size":"square"},"layout":{"grid":"2x2","panels":[{"position":"top-left","theme":"不安と自己不信","background":"ボケ味と光のテクスチャを活かした、柔らかいピンクと白のフェミニンなライフスタイルシーン","subject":"居心地の良い白いニットセーターを着た悩める若い女性のクローズアップ、片手を顔に添え、無造作なお団子ヘア、顔は部分的に隠れている","text_blocks":[{"text":"知らないと損！","style":"黒文字の黄色い斜めバナー","position":"top-left"},{"text":"99%が間違ってる","style":"非常に大きな見出し、赤い数字と黒い書道風の日本語テキスト","position":"upper-left to center"},{"text":"その悩みの向き合い方","style":"ピンクのサブ見出し","position":"below main headline"},{"text":"理由もなくモヤモヤする","style":"赤いチェックアイコン付きの白い丸角ボックス内のチェックリスト項目"},{"text":"頑張ってるのに変わらない","style":"赤いチェックアイコン付きの白い丸角ボックス内のチェックリスト項目"},{"text":"自分の本音がわからない","style":"赤いチェックアイコン付きの白い丸角ボックス内のチェックリスト項目"},{"text":"人間関係で疲れてしまう","style":"赤いチェックアイコン付きの白い丸角ボックス内のチェックリスト項目"},{"text":"将来が不安で仕方ない","style":"赤いチェックアイコン付きの白い丸角ボックス内のチェックリスト項目"},{"text":"そのモヤモヤ、一人で抱えなくて大丈夫です。","style":"白文字のピンクの円形バッジ","position":"lower-right"}],"count":9},{"position":"top-right","theme":"ヒーリングではなく変化のメカニズム","background":"青、紫、マゼンタの星雲が広がる深い宇宙、スターバーストの光、エネルギーの渦、輝くスピリチュアルな雰囲気","subject":"輝くポータルや光の柱の近くに立つ、後ろ姿または横顔の小さな女性、顔は部分的に隠れている","text_blocks":[{"text":"普通に見えて実は…","style":"黒い斜めバナー上の白文字","position":"top-left"},{"text":"これ、","style":"大きな白文字","position":"upper-left"},{"text":"ヒーリング","style":"暗い紫のブラシストローク上の非常に大きな黄色い文字","position":"center"},{"text":"じゃありません。","style":"大きな白文字","position":"below"},{"text":"「整える」ことで","style":"白枠のテキスト","position":"lower-left"},{"text":"現実が変わる","style":"ピンクのハイライトテキスト","position":"mid-lower-left"},{"text":"仕組みがあった！","style":"白文字","position":"bottom-left"}],"graphic_elements":[{"type":"曲がった黄色い矢印","count":1,"direction":"輝く人物に向かって"}],"count":8},{"position":"bottom-left","theme":"本来の自分に戻ることで明るい未来を創造する","background":"柔らかい雲が浮かぶ晴れた青空、緑の野原、舞い散る葉、明るく希望に満ちた昼間のムード","subject":"ノースリーブの白いドレスを着た喜びにあふれる若い女性、両腕を広げ、日差しの中で回転している、顔は部分的に隠れている","text_blocks":[{"text":"本来の自分に戻ると","style":"赤と黒の見出し","position":"top"},{"text":"こんな未来に","style":"非常に大きなゴールドグラデーションの見出し","position":"center"},{"text":"なります","style":"大きな黒文字","position":"right-center"},{"text":"心が軽くなり、毎日が楽しくなる","style":"ピンクのハートアイコン付きの白い丸角バブル内のメリット項目"},{"text":"人間関係がスムーズになり、愛で満たされる","style":"緑の人物アイコン付きの白い丸角バブル内のメリット項目"},{"text":"お金の流れが変わり、豊かさが自然と入ってくる","style":"ゴールドの円アイコン付きの白い丸角バブル内のメリット項目"},{"text":"人生が想像以上に変わり始めます！","style":"白文字のピンクの下部リボン","position":"bottom"}],"count":7},{"position":"bottom-right","theme":"期間限定の割引オファー","background":"グリッターと火花が散る、燃えるような赤と金の爆発テクスチャ、高級感と緊急性を演出","text_blocks":[{"text":"知らないと","style":"黒文字の黄色いブラシバナー","position":"top-left"},{"text":"損！","style":"メタリックな面取りが施された極めて大きなゴールドの漢字","position":"upper-right"},{"text":"通常価格 9,980円（税込）","style":"取り消し線付きの黒い数字と小さな税表記がある白い値札","position":"upper-left"},{"text":"モニター価格","style":"白文字","position":"center-left"},{"text":"4割引","style":"巨大なピンクから白へのグラデーション割引テキスト","position":"center-lower"},{"text":"今だけ 限定募集！ 人数限定","style":"ゴールドの円形シールバッジ","position":"right-center"},{"text":"詳しくはプロフィールから","style":"白文字と白い矢印ボタンが付いた紫の CTA バー","position":"bottom"}],"count":7}],"total_panels":4},"composition":"SNS サムネイルの視認性を最適化した、情報量が多く説得力のある日本語広告コラージュ。各象限に明確な感情メッセージとカラーアイデンティティを持たせ、斜めのバナー、特大の漢字と数字、光沢のあるバッジ、丸角の白い情報ボックス、ドラマチックなライティングを多用","customization":{"primary headline":"{argument name=\"headline text\" default=\"99%が間違ってる\"}","discount text":"{argument name=\"discount text\" default=\"4割引\"}","price":"{argument name=\"price\" default=\"9,980円（税込）\"}","main color palette":"{argument name=\"main color palette\" default=\"ピンク、青紫の銀河、空色、赤金\"}","call to action":"{argument name=\"call to action\" default=\"詳しくはプロフィールから\"}"},"render_notes":"すべての日本語テキストを大きく読みやすくし、レイヤー状の影と輪郭を付けること。ミニマルなデザインではなく、洗練された広告合成の美学を使用すること。顔はぼかすか部分的に隠すこと。不安、気づき、希望に満ちた変容、緊急のオファーという感情の対比を強調すること"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="YouTube サムネイル - 日本語の 4 分割ヒーリング広告コラージュ - Image 1">
</div>

#### 📌 詳細

- **作者:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **ソース:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14551)**

---

### No. 52: YouTube サムネイル - テック系チュートリアル用サムネイル（UIモックアップ付き）

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

チュートリアルの見出し、デザインアプリのダッシュボードモックアップ、そしてインターフェースを指差すプレゼンターを配置した、インパクトのあるYouTube風サムネイル。ブランディングやデザインシステム関連のコンテンツに最適です。

#### 📝 プロンプト

```
明るい白背景に、左側の太字テキストと右側のプレゼンターの切り抜きを視覚的に分けた、クリーンでモダンなYouTubeサムネイル。左側には、太い黒のサンセリフ体大文字で「{argument name="headline text" default="CLAUDE DESIGN"}」という巨大なスタック型見出しを左上に配置。その下に、オレンジ色の縁取りと太字の白大文字テキストを配した、ドロップシャドウ付きの大きな角丸長方形オレンジバナーを配置し、「{argument name="subheadline text" default="IN 6 MINS"}」と記載。見出しの近くには、オレンジ色のスターバースト（星型）を2つ配置（テキスト横に小さいもの、右端の背景に非常に大きいもの）。左下の領域には、デザインツールダッシュボードのフローティングアプリインターフェースモックアップを表示。淡いオフホワイトのパネル、細い枠線、角丸、かすかな影を適用。インターフェースの左サイドバーには、「Recent」、「Your designs」、「Examples」、「Design systems」という4つのメニュー項目を正確に配置。メインパネルのヘッダーには「Recent」と記載し、その下に「Thumio Design System」、「Thumio Startup」、「Design System」とラベル付けされた3つのプロジェクトカードをグリッド状に配置。右半分には、白いタートルネックのセーターを着た、胸から上の若い男性のフォトリアルな切り抜き画像を配置。髪は明るい茶色の無造作ヘアで、軽く髭を生やし、カメラに近い位置に配置。顔の大部分は、無地のタンカラーの長方形プレースホルダーで意図的に隠す。男性は片手で左側のインターフェースパネルを指差す。温かみのあるオレンジと白のブランドカラーを使用し、高コントラストで無駄を省いた、洗練されたクリエイターエコノミー向けのサムネイルスタイル。繊細な影を使い、テック系チュートリアルコンテンツに最適な構図で作成。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="YouTube サムネイル - テック系チュートリアル用サムネイル（UIモックアップ付き） - Image 1">
</div>

#### 📌 詳細

- **作者:** [corbin](https://x.com/corbin_braun)
- **ソース:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14695)**

---

### No. 53: YouTube サムネイル - Celestial VTuber ライブ配信オーバーレイ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

星をテーマにした配信部屋で、青髪の天体アイドルが佇む、アニメスタイルの詳細な VTuber ライブ配信画面。ファンタジーな配信オーバーレイやプロモーション用ビジュアルの作成に最適です。

#### 📝 プロンプト

```
{"type":"アニメ調 VTuber ライブ配信オーバーレイイラスト","theme":"天体の夜空、星、星座、深いサファイアブルーと白、エレガントで魔法のようなアイドル美学","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"キュートな若いアニメ風の女性","hair":{"color":"{argument name=\"hair color\" default=\"淡い空色\"}","style":"アホ毛が少しある、非常に長いウェーブのかかったツインテール風のルーズヘア、柔らかな前髪、星のヘアアクセサリーとリボン"},"outfit":{"style":"華やかな天体アイドルドレス","pieces":["オフショルダーの白いブラウス（パフスリーブ）","大きなネイビーブルーの胸元リボン（ゴールドの星の飾り付き）","ゴールドの縁取りと星座モチーフがあしらわれたネイビーのコルセット風ボディス","星のチョーカー","青いリボンとゴールドの星のアクセサリーが付いた、斜めにかぶる小さな白いミニハット"]},"pose":"配信デスクに座り、マイクとキーボードの後ろで正面を向いている","expression":"穏やかで落ち着いた、歓迎するような表情"}},"environment":{"setting":"星空が広がる大きな窓がある、夜の居心地の良いファンタジーな配信部屋","background_elements":["吊るされた星のガーランドとクリスタルの飾り","ボトル、本、砂時計、望遠鏡のようなオブジェクト、天体装飾が置かれた棚","窓の外に見える月と星座のイメージ","青い目をした2つのふわふわしたマスコットのような雲のぬいぐるみ"]},"props":{"desk_items":["中央左に置かれたヴィンテージ風の大きなマイクスタンド","星をテーマにしたキーボード","\"蒼空なつみ - SORA NATSUMI -\" と書かれたネームプレート","小さな白いウサギのフィギュアが乗ったパフェ","雲のマスコットが付いた小さなカップまたはキャンドルホルダー"]},"layout":{"format":"フルライブ配信待機・雑談画面オーバーレイ","sections":[{"title":"LIVE","position":"左上の縦型バナー","count":3,"labels":["LIVE","20:30","5月20日（火）"]},{"title":"COMMENTS","position":"左パネル","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今日はどんなお話かな？","しろくまアイス：こんなっつー！","天の川りゅうせい：今日も可愛い！大好き！","ふるーすたー：も ふ ぷ","月見うさぎ：楽しみ〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：きちゃー！( *´ω｀)","彗星カケル：配信ありがとう〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今日のサムネもかわいい…！","夜更かしの民：こんなっつー！","ゆめみがち：待ってました！","ハル：今日の衣装も最高に似合ってるぞ〜！"]},{"title":"social tags","position":"コメントパネルの下","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"左下","count":4,"labels":["目標：チャンネル登録者数 100,000人！","現在","58,320 人","いつもありがとう！チャンネル登録高評価よろしくね☆"]},{"title":"supporters panel","position":"目標パネル横の左下の小さなカード","count":6,"labels":["☆今日の星屑さん（スパチャありがとう！）☆","星の旅人 さん ¥2,000","ふるーすたー さん ¥1,000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"右上パネル","count":3,"labels":["Now Talking","{argument name=\"talk topic text\" default=\"初見さん歓迎！雑談配信✨\"}","{argument name=\"subtitle text\" default=\"〜まったりお話ししよっ〜\"}"]},{"title":"SET LIST","position":"右中央パネル","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"右下パネル","count":3,"labels":["オリジナル曲","星空コンパス","MV公開中！"]}],"logo":{"position":"右上隅","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"高精細で洗練されたアニメイラスト、輝くハイライト、柔らかな光、鮮明な線画","composition":"左右対称、密度のある装飾的なオーバーレイ、キャラクターを中心に配置し、周囲にUIパネルを配置","lighting":"月明かりのクールなブルーの雰囲気と、輝くゴールドのアクセント","mood":"夢見心地、魔法のよう、居心地が良い、エレガント"}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="YouTube サムネイル - Celestial VTuber ライブ配信オーバーレイ - Image 1">
</div>

#### 📌 詳細

- **作者:** [はげあたま](https://x.com/hageatama)
- **ソース:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14443)**

---

### No. 54: YouTube サムネイル - YouTube ゲーム実況の絶望シーン

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

人気 YouTuber がテトリスのようなゲームで悲劇的な失敗をしてしまうシーンを生成するためのプロンプト。チャット欄の反応も含む。

#### 📝 プロンプト

```
人気日本人 YouTuber による {argument name="content" default="ゲーム実況"} の一場面。{argument name="game name" default="テトリス"} で、長い棒がすべてを消してくれるかと思いきや、配置がわずかにずれてしまい、ストリーマーが絶望の表情で叫んでいる様子。コメント欄は阿鼻叫喚の渦に包まれている。日本語。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="YouTube サムネイル - YouTube ゲーム実況の絶望シーン - Image 1">
</div>

#### 📌 詳細

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **ソース:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **公開日:** 2026年4月21日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14346)**

---

### No. 55: YouTube サムネイル - アニメ風恋愛映画ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ほろ苦い恋愛映画の洗練された日本のアニメ風劇場用ポスターを生成します。映画のキービジュアル、架空の映画広告、ドラマチックなキャラクター重視のポスターデザインに最適です。

#### 📝 プロンプト

```
洗練されたアニメのキービジュアルのようにデザインされた、角が丸いスマートフォン風の縦長レイアウトの日本のアニメ風恋愛映画ポスター。メイン画像には、夕暮れ時の屋外バルコニーに立つ美しい看板娘のヒロインが描かれており、肩越しに振り返り、柔らかく物憂げな表情でこちらを見つめている。彼女はダークリボンで結ばれた非常に長い銀白色のツインテール、青白い肌、そして大きなピンクバイオレットの瞳をしている。ボリュームのある袖の繊細な白いフリルブラウスと、ダークなハイウエストのドレスまたはコルセット風のスカートを着用しており、エレガントで少しゴシックな学園恋愛風のルックを演出している。雰囲気は夢のようで感情的であり、輝くボケ味の光、舞い散る花びらや雪のような煌めき、夕焼けのピンクとラベンダー色の光、そしてぼかされた背景の輝く街並みで満たされている。リッチな映画風アニメレンダリング、超詳細な髪の毛の質感、柔らかなリムライト、艶やかな瞳、そして初恋のほろ苦いムードを使用すること。構成に統合された日本語のポスタータイポグラフィを追加する：右側に大きな縦書きのピンクの詩的なキャッチコピー、左側に縦書きの白いキャッチコピー、左下付近に非常に大きなメインタイトル「{argument name="title text" default="看板娘"}」、その横に小さなサブタイトル「{argument name="subtitle text" default="君と紡ぐ恋物語"}」を配置する。下部中央には、同じヒロインの異なる感情的なクローズアップを映した5つの小さな長方形のフィルムストリップ風プレビュー画像を並べる。上部と下部には、日本語で密集したクレジット、映画祭の月桂冠、小さな公開情報を追加し、悲劇的で美しいラブストーリーを宣伝するプレミアムな恋愛アニメ映画ポスターのような全体的な雰囲気を持たせる。モーヴ、ブラッシュピンク、バイオレット、パールホワイト、ミッドナイトネイビーのパステルカラーパレットを使用し、ソフトなブルーム効果、浅い被写界深度、エレガントなポスター構成で仕上げる。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="YouTube サムネイル - アニメ風恋愛映画ポスター - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="YouTube サムネイル - アニメ風恋愛映画ポスター - Image 2">
</div>

#### 📌 詳細

- **作者:** [studioあぽろん](https://x.com/ai_studioapollo)
- **ソース:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14529)**

---

### No. 56: YouTube サムネイル - 目を引く日本語 AI サムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、AI やテック系の解説動画向けに、巨大な文字、炎のエフェクト、指差しポーズのキャラクターを組み合わせた、インパクト抜群のアニメ風日本語 YouTube サムネイルを生成します。

#### 📝 プロンプト

```
鮮やかでクリックしたくなるようなアニメスタイルの YouTube サムネイルを 16:9 の横長サイズで作成してください。構成は左側 3 分の 2 を巨大なテキストブロックが占め、右側 3 分の 1 にアニメキャラクターを配置する分割構図にします。背景は赤、オレンジ、ゴールドのエネルギーが爆発するような炎の演出で、光り輝く火花、レンズフレア、キラキラした星のハイライト、そして全体に高コントラストなメタリックの輝きを加えます。左側には、太い黒枠、白いインナーストローク、強烈なアウターグロー、光沢のある 3D 加工を施した 4 つの太字テキストグループを垂直に積み重ねてください。1 行目：鮮やかな赤色に白い縁取りと明るいゴールドの火花をあしらった巨大な日本語見出し {argument name="headline text" default="紅エンジニア必見"}。2 行目：左側に白いスタイリッシュな「M」が描かれた丸みを帯びたオレンジ色の正方形アイコンを配置し、その右に巨大な小文字の白いサンセリフ体で {argument name="product name" default="masatra"} と記載（黒い縁取りと淡いグレーの影付き）。3 行目：コンパクトで太い白文字の日本語で「次世代AIエージェントフレームワーク」と書かれた黒い長方形のバナー。4 行目：ベベル加工された 3D エンボス、オレンジからゴールドへのグラデーション、明るい鏡面ハイライト、光るエッジを備えた非常に大きな金色のメタリック日本語テキスト {argument name="bottom text" default="徹底解説"}。右側には、胸から上を写したアニメスタイルの若い女性を配置します。髪は {argument name="hair color" default="brown"} のミディアムヘアで、白いシャツの上に白い白衣を羽織り、カメラに向かって身を乗り出し、手前で人差し指を突き出して視聴者を指差しているポーズをとらせてください。自信に満ちた、緊急性を感じさせる目を引くポーズにします。背景の炎からくるドラマチックなリムライト、肌や服に強いオレンジのハイライトを入れ、商業用サムネイルのような洗練された仕上がりにしてください。右上部の顔の領域には、{argument name="placeholder color" default="light brown"} のフラットな長方形のプレースホルダーブロックを配置し、顔の大部分を隠してください。全体的に非常に密度が高く、光沢があり、爆発的で、小さなサイズでも最大限の視認性を発揮するように最適化してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="YouTube サムネイル - 目を引く日本語 AI サムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **ソース:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14491)**

---

### No. 57: YouTube サムネイル - 爆発的アニメ風ローンチサムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

ローンチ告知、オンライン講座の広告、AI ビジネスマーケティングのビジュアルに最適な、インパクトのあるアニメ風の日本語プロモーション用サムネイル。

#### 📝 プロンプト

```
爆発的なライティング、高密度な火花のエフェクト、ドラマチックなコントラストを効かせた、インパクト抜群のアニメプロモーション風の YouTube サムネイルを作成してください。構図は、黒とネオンカラーのグリーンを基調とした背景に、ゴールドのグリッターが弾け、下部には街のシルエットがうっすらと浮かぶ統一感のあるシーンにします。右側には、ダークブラウンから黒の無造作ヘアに鮮やかなネオングリーンのメッシュと赤いアクセントを入れ、大きな緑色の瞳で、口を大きく開けて興奮気味に笑う可愛いちびキャラの少年を腰から上で配置します。彼は片手を視聴者に向けて指差し、もう片方の手は拳を突き上げるエネルギッシュなポーズで、黒いパーカーの上に光沢のある緑色のジャケットを羽織っています。左側には、渦巻く緑のエネルギーを内包した光る砂時計を 1 つ配置してください。画像全体に強烈なスターバースト、レンズフレア、金色の粒子、スピードラインのエネルギーを散りばめ、バイラルなサムネイルに仕上げます。5 つの太字の日本語テキスト要素を巨大なディスプレイ書体で追加してください。左上に {argument name="top banner text" default="4月28日スタート"} と書かれた赤いリボンバナー（黄色い太文字、白縁取り）、中央に {argument name="main headline" default="ついに解禁"} と書かれた巨大なメタリックゴールドの漢字（重厚な黒い影と明るいゴールドの質感）、左下に {argument name="subheadline" default="AI副業で人生変わる"} と書かれた大きな白と緑のサブヘッドライン、中央下寄りに {argument name="bonus badge text" default="無料10大特典"} と書かれた緑の丸型バッジ（白と黄色の太文字）、そして右下に {argument name="corner banner text" default="近日公開"} と書かれた黒い斜めのバナー（その下に小さく白い英語で COMING SOON と記載）を配置します。太いアウトライン、光るエッジ、メタリックな質感、そしてレイヤーによる奥行きを駆使し、クリック率の高いローンチ告知サムネイルのように、緊急性と祝祭感、そして目を引くデザインに仕上げてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="YouTube サムネイル - 爆発的アニメ風ローンチサムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **ソース:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14499)**

---

### No. 58: YouTube サムネイル - X 収益化 YouTube サムネイル（インパクト重視）

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

X での収益化をテーマにした、日本のマーケティング動画でよく見られるインパクト抜群のサムネイルを生成するプロンプトです。SNS 運用や副業系コンテンツに最適です。

#### 📝 プロンプト

```
日本のインターネットマーケティング風のインパクトが強い YouTube サムネイルを作成してください。16:9 の横長サイズで、黒と金を基調とした背景には、火花、レンズフレア、光の粒子、ドラマチックな光の筋が飛び交う爆発的なデザインにします。構成は密度が高くエネルギッシュで、左側から中央にかけて巨大なレイヤー状のタイポグラフィを配置し、右側にはアニメ調の男性キャラクターを配置します。最上部には、金色の縁取りが施された赤いリボンのバナーを配置し、その中に白と黄色の太字で「{argument name="headline text" default="実績者が教える"}」という日本語を入れます。その下に、非常に大きく光沢のある立体的なメイン見出しを配置します。黒い太い縁取りと金色の輝きを加え、巨大なメタリックゴールドの「10」、その後に太い白文字で「日で」、さらに巨大なネオンカラーの緑色に光る「X」、その下に白文字で「収益化」、一番下に最大サイズの金文字で「達成」と重ねます。見出しの背後には、成長を象徴する右肩上がりの明るい緑色の棒グラフと矢印を追加します。左側には、SNS と収益を連想させる 3 つの要素を配置します。白い X ロゴが表示された傾いた黒いスマートフォン、白いハートが描かれた緑色の吹き出し、白いユーザーシルエットが描かれた小さな緑色の吹き出しです。左下には、輝く金貨の山 2 つと、円マークが刻印された金貨 1 枚を追加します。右側には、太ももから上のアニメ調の青年を配置します。髪はダークブラウンの無造作ヘアに鮮やかな緑のメッシュを入れ、肌は色白、自信に満ちた腕組みポーズで、緑のインナーに黒いジャケットを着用しています。顔はシンプルな長方形のぼかしで隠してください。右下の近くには、月桂樹の装飾と小さな王冠があしらわれた金色の認定シールを配置し、中に「成功者続出」という日本語を入れ、シールの下部には「再現性あり」と書かれた赤いリボンを添えます。下部には、金色の縁取りと黒い背景を持つ、光る緑色の長方形の機能ボックスを 3 つ配置します。1 つ目のボックスには初心者マークのアイコンと「X 初心者でも 簡単収益化」というテキスト、2 つ目のボックスには時計のアイコンと「1 日 1 時間の 作業で OK」というテキスト、3 つ目のボックスには緑のチェックが入ったカレンダーアイコンと「最短 10 日で 収益化条件達成」というテキストを入れます。特大の太い日本語フォント、メタリックゴールドのグラデーション、太い黒縁の白文字、鮮やかなネオンカラーの緑のハイライトを使用し、極端なコントラストとクリック率を最適化した洗練されたサムネイルの美学を追求してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="YouTube サムネイル - X 収益化 YouTube サムネイル（インパクト重視） - Image 1">
</div>

#### 📌 詳細

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **ソース:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14498)**

---

### No. 59: YouTube サムネイル - 日本語版 X 収益化サムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

初心者向けの X 収益化ガイドをテーマにした、目を引くアニメ調の日本語 YouTube サムネイル。SNS 運用、収益化戦略、オンラインビジネス系の動画カバーに最適です。

#### 📝 プロンプト

```
大胆で目を引くアニメ・ビジネススタイルの日本語 YouTube サムネイルを作成してください。16:9 の横長サイズ、情報量の多い構成、高コントラスト、光沢のあるテキストエフェクト、ネオングリーンとゴールドの配色、ドラマチックな照明、火花の粒子、レンズフレア、そして強い被写界深度を特徴とします。背景にはぼかしたワークステーションと SNS の分析ダッシュボードを配置し、上昇する折れ線グラフと「ポストアナリティクス」および「収益 ¥248,620」と書かれた収益カードを表示します。右側には、ダークブラウンの髪に鮮やかなネオングリーンのメッシュが入った、黒いパーカーまたはジャケット姿のアニメ風の男性ストリーマーを配置します。自信に満ちた笑顔で人差し指を上に向けたポーズをとらせ、顔の部分はテキストやカスタムポートレートを後から挿入できるよう、くすんだオリーブブラウンの大きな長方形のプレースホルダーで一部隠してください。上部には、左側に初心者マークのアイコンをあしらった、ゴールドの縁取りがある光沢のある緑色のリボンバナーを配置し、その中に {argument name="headline text" default="初心者向け完全ガイド"} というテキストを入れます。中央左には、太い黒の縁取りと強い白のハイライトが入った巨大なメタリックゴールドの「10」を配置し、その後に太い白黒の日本語テキストで「日で」と続けます。中央の下には、電気を帯びたエッジと火花のエフェクトをまとった、巨大で輝くネオングリーンの「X」を配置します。X の右側、手前には、太い黒の縁取りとドロップシャドウを施した、白とゴールドの巨大な 3D 日本語テキスト {argument name="main claim text" default="収益化達成"} を目立つように重ねます。メインテキストの左側付近には、3 つの浮遊するソーシャルプラットフォーム風アイコン（白い X ロゴが入った黒い正方形アイコン、白いハートが入った青い吹き出しアイコン、白いユーザーシルエットが入ったピンクの角丸四角アイコン）を配置します。左下の前景には、X ロゴが入った黒いコーヒーマグをデスクの上に置きます。下端には、緑色の枠線と控えめな影が付いた 3 つの角丸の白い情報ボックスを、左から右へ均等に配置します。各ボックスの上部には緑色の番号付き円を添え、ボックス 1 には「01」と初心者マークアイコン、「X 初心者でも 簡単収益化」というテキストを、ボックス 2 には「02」と時計アイコン、「1日1時間の 作業でOK」というテキストを、ボックス 3 には「03」と「10」と書かれたカレンダーアイコン、「最短10日で 収益化条件達成」というテキストを記載します。すべてのタイポグラフィは非常に大きく、エンボス加工を施し、太い縁取り、強い遠近感、レイヤーの重なりを活用して、サムネイルとしての視認性を最適化してください。全体的な雰囲気は、ワクワク感、高収益の期待感、初心者向け、エネルギッシュな日本語 SNS 収益化チュートリアルのサムネイルを目指してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="YouTube サムネイル - 日本語版 X 収益化サムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **ソース:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14497)**

---

### No. 60: YouTube サムネイル - 爆発的なクリック率を誇る日本語版 X 収益化サムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、X の迅速な収益化や特典オファーに関する、高エネルギーなアニメスタイルの日本語マーケティング用サムネイルを生成します。

#### 📝 プロンプト

```
インパクトの強いアニメマーケティングスタイルの、派手な日本語 YouTube サムネイルを作成してください。16:9 の横長サイズで、ネオングリーンのエネルギーエフェクト、金の輝き、スピード線、レンズフレア、そして太い黒のドロップシャドウを詰め込んでください。構図は、左側と中央を占める大胆なプロモーションテキストと、右側で満面の笑みを浮かべて視聴者を指差す可愛いちびキャラのアニメ少年に分割します。少年は、鮮やかな {argument name="accent hair color" default="ネオングリーン"} のメッシュが入ったダークブラウンのボサボサ髪で、大きな明るい緑の瞳、頬には柔らかな赤らみがあり、オレンジのインナーの上に緑の縁取りがあるジャケットと黒のパーカーを重ね着しています。クリックしたくなるようなソーシャルメディア用サムネイルにするため、光沢のあるセルシェーディングレンダリング、鮮明な輪郭線、高いコントラスト、そして誇張された奥行きを使用してください。最上部には、左側にギフトボックスのアイコンが付いた金縁の赤いリボンバナーを配置し、バナー内に {argument name="top banner text" default="無料10大特典プレゼント"} という日本語のヘッドラインを太字の白と黄色の文字で入れてください。中央左のメインエリアには、ドラマチックな 3D スタイルとメタリックなグラデーションを施した巨大な日本語テキストを配置します。巨大な金の「10」、白の「日で」、巨大なネオングリーンの「X」、銀白色の「収益化」、金オレンジの「達成」という文字で、正確に {argument name="main headline" default="10日でX収益化達成"} と読めるようにしてください。この見出しの周囲を、上向きの緑の矢印、星型のきらめき、爆発的な光のエフェクトで囲みます。見出しエリアの周囲に 4 つのフローティングプラットフォーム風アイコンを追加してください：白いハートが付いたピンクのソーシャルアイコン 1 つ、白いユーザーシルエットが付いた青い吹き出しアイコン 1 つ、白い X ロゴが表示された傾いた黒いスマートフォン 1 つ、そして前に円マークのコインがある金貨の山 1 つです。下部には、それぞれ異なるアイコンと日本語のコピーが入った 3 つの光る緑の機能ボックスを水平に並べます。ボックス 1 には初心者マークのアイコンと {argument name="feature text 1" default="X初心者でも簡単収益化"} というテキスト、ボックス 2 には時計のアイコンと「1日1時間の作業でOK」というテキスト、ボックス 3 にはカレンダーのアイコンと「最短10日で収益化条件達成」というテキストを入れます。右下には、白い縁取りが光る大きな光沢のある赤い丸みを帯びた CTA ボタンを追加し、白い日本語テキスト {argument name="button text" default="今すぐ受け取る"} と、ボタンの右側に白い再生三角形、右下端の近くにクリックする手のカーソルを配置してください。画像全体が爆発的で緊急性を感じさせ、高いクリック率を実現できるよう、彩度の高い緑、赤、金、黒の影、メタリックなハイライトを使用してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="YouTube サムネイル - 爆発的なクリック率を誇る日本語版 X 収益化サムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **ソース:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14496)**

---

### No. 61: YouTube サムネイル - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 プロンプト

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="YouTube サムネイル - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 詳細

- **作者:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **ソース:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14150)**

---

### No. 62: YouTube サムネイル - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 プロンプト

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="YouTube サムネイル - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 詳細

- **作者:** [結パパ](https://x.com/Yuupapa_free)
- **ソース:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14230)**

---

### No. 63: YouTube サムネイル - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a cute, pink-themed VTuber stream thumbnail with customizable text ribbons and bullet points.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="YouTube サムネイル - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 詳細

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **ソース:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14242)**

---

### No. 64: YouTube サムネイル - Pastel Pink VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a cute, pastel-themed stream overlay or thumbnail featuring an anime girl and customizable text banners.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="YouTube サムネイル - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 詳細

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **ソース:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14238)**

---

### No. 65: YouTube サムネイル - Anime VTuber Livestream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a pastel-themed anime VTuber stream thumbnail with customizable text badges and title.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="YouTube サムネイル - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 詳細

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **ソース:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14231)**

---

### No. 66: YouTube サムネイル - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a vibrant, text-heavy anime-style thumbnail for a VTuber chat stream, featuring customizable banners and titles.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="YouTube サムネイル - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 詳細

- **作者:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **ソース:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14227)**

---

### No. 67: YouTube サムネイル - 日本語ウェビナー用サムネイル生成ツール

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

視認性の高いタイポグラフィと強調されたコピーを用いた、16:9 形式のプロフェッショナルな日本語ウェビナー用サムネイルを作成するためのプロンプトです。

#### 📝 プロンプト

```
高品質な日本語の {argument name="thumbnail type" default="ウェビナー用サムネイル"} を作成してください。 {argument name="aspect ratio" default="16:9 ワイドスクリーン"}。テキスト量は多いですが、メインのコピーがはっきりと目立つようにしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="YouTube サムネイル - 日本語ウェビナー用サムネイル生成ツール - Image 1">
</div>

#### 📌 詳細

- **作者:** [KAWAI](https://x.com/kawai_design)
- **ソース:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **公開日:** 2026年4月18日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13978)**

---

### No. 68: YouTube サムネイル - VTuber 初配信サムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

VTuber の初配信やスケジュール告知用の、魔法のようなタイポグラフィを活かしたサムネイルを生成します。

#### 📝 プロンプト

```
{
  "type": "VTuber 初配信サムネイル",
  "character": {
    "appearance": "アニメ調の女の子、長いダークパープルの髪、紫の瞳、フリル付きの白いブラウス、ダークパープルの蝶ネクタイ、大きなヘアリボン",
    "pose": "口元に指を添えた、キュートな表情",
    "props": "右側に紫のリボンが付いたポップガード付きコンデンサーマイク"
  },
  "background": "魔法のような星空、キラキラした光、光り輝く蝶、紫と白のカラーパレット",
  "layout": {
    "typography": [
      {
        "position": "左上",
        "style": "大きく太いテキスト、上部に筆記体の英語",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "First Stream",
        "subtext_2": "はじめまして！ 紫咲リリーです！"
      },
      {
        "position": "左中央",
        "style": "装飾ボックス",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "左下",
        "style": "ロゴスタイル",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "右上",
        "style": "縦書きテキスト",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "右下",
        "style": "装飾的なピル型",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ START ✦"
      }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="YouTube サムネイル - VTuber 初配信サムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [WTR](https://x.com/wtry1102)
- **ソース:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **公開日:** 2026年4月17日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13943)**

---

### No. 69: YouTube サムネイル - ゴールド＆ブラックのインフォプロダクト用サムネイル

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

自信に満ちた人物と、構造化された複数のテキスト要素を配置した、派手で情報量の多いプロモーション用バナーや YouTube サムネイルを生成します。

#### 📝 プロンプト

```
{
  "type": "プロモーション用バナー / YouTube サムネイル",
  "style": "高コントラスト、派手、プロフェッショナル、{argument name=\"theme color\" default=\"ゴールド＆ブラック\"} パレット、光り輝く光線、きらめくパーティクル",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"ダークスーツを着て腕を組んだ、自信に満ちたアジア系の若者\"}",
    "pose": "右上を見上げている",
    "props": "目の前で光る開いたノートパソコン"
  },
  "layout": {
    "background": "放射状のゴールドの光が広がるダークな背景",
    "text_sections": {
      "top_left_badge": "[保存版]",
      "top_header": "{argument name=\"top text\" default=\"知識ゼロからでも今日から始められる！ AIで稼ぐ力を最短で手に入れる！\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"AI副業 完全攻略\"}",
        "style": "大型、太字、3D ゴールド＆ホワイトのタイポグラフィ"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"初心者でも月10万\"}",
      "top_right_badge": {
        "style": "ゴールドの月桂冠",
        "text": "2026 年版 最新版"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "積み重ねられたゴールド枠のボックス",
        "labels": ["最短で収益化", "具体例つき", "誰でも始めやすい"]
      },
      "middle_right_ribbon": {
        "style": "赤いリボンバナー",
        "text": "手順を徹底解説"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "2x3 グリッドのゴールド枠ボックス",
        "labels": ["おすすめツール紹介", "収益化の流れがわかる", "失敗しない始め方", "作業時間を最小化", "テンプレ付き", "再現しやすい方法"]
      },
      "bottom_footer": "迷わず稼げる！ AI 副業の教科書",
      "bottom_right_badge": {
        "style": "ゴールドの月桂冠",
        "text": "テンプレ付き"
      }
    }
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="YouTube サムネイル - ゴールド＆ブラックのインフォプロダクト用サムネイル - Image 1">
</div>

#### 📌 詳細

- **作者:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **ソース:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **公開日:** 2026年4月17日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13903)**

---

### No. 70: コミック / ストーリーボード - ほっこり温かい 4 コマ夫婦漫画

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

夫婦の絆をテーマにした、柔らかくロマンチックな 4 コマ漫画を生成するプロンプトです。SNS 投稿や記念イラスト、カップル向けの漫画制作に最適です。

#### 📝 プロンプト

```
{"type":"4 コマのロマンチックな漫画イラスト","style":"温かみのあるベージュとライトブラウンのモノクロパレット、清潔感のある手描き風アニメ線画、柔らかなクリーム色の背景、シンプルな陰影、居心地の良い優しい雰囲気、SNS 投稿向けのデザイン","format":"薄い茶色の枠線で区切られた 2x2 の正方形コミックレイアウト","headline":{"text":"{argument name=\"headline text\" default=\"夫婦の日\"}","position":"top center","decorations":{"count":2,"items":["左側に小さなハート","右側に小さなハート"]}},"panels":[{"panel":1,"count":2,"scene":"若い夫婦の立ち姿","composition":"男性が女性の後ろに立ち、片手を肩に置いている。二人とも穏やかで愛情に満ちた表情","characters":[{"role":"man","appearance":"無造作なライトブラウンの髪、メガネ、クリーム色のパーカー、長身でスリム"},{"role":"woman","appearance":"ライトブラウンの髪を低めのルーズなお団子にまとめ、顔周りに後れ毛、白い長袖シャツ、温かみのあるブラウンのニットベスト、ショルダーバッグのストラップが見える"}],"text":["今日は","夫婦の日！"],"decorations":{"count":3,"items":["小さなハート","小さなハート","小さなハート"]}},{"panel":2,"count":2,"scene":"室内でマグカップを手に持ち、微笑み合う二人","characters":[{"role":"man","appearance":"同じメガネとパーカー、くすんだグリーンのマグカップを持っている"},{"role":"woman","appearance":"同じ髪型と服装、明るい色のマグカップを持っている"}],"speech_bubble":{"speaker":"man","text":"いつもありがとう。 一緒にいられることが、 いちばんの幸せだよ。"},"decorations":{"count":4,"items":["小さなキラキラ","小さなキラキラ","小さなドットの集まり","小さなドットの集まり"]}},{"panel":3,"count":2,"scene":"キッチンで一緒に料理をし、コンロの上のフライパンをかき混ぜている二人","background":"シンプルな棚と鉢植えを柔らかなスケッチ風のディテールで描く","characters":[{"role":"man","appearance":"同じメガネとパーカー"},{"role":"woman","appearance":"同じお団子ヘアと重ね着スタイル"}],"speech_bubble":{"speaker":"man","text":"これからも、 笑い合って、支え合って、 一緒にいろんな景色を 見ていこうね。"}},{"panel":4,"count":2,"scene":"親密な抱擁、男性が女性の肩を抱きながら額にキスをしている","characters":[{"role":"man","appearance":"同じメガネとパーカー"},{"role":"woman","appearance":"同じ髪型と服装、男性に寄り添っている"}],"speech_bubble":{"speaker":"man","text":"大好きだよ。 これからも、 よろしくね！"},"decorations":{"count":3,"items":["小さなハート","小さなハート","小さなハート"]}},{"footer":{"text":"{argument name=\"footer text\" default=\"いつもそばにいてくれて、ありがとう。\"}","position":"bottom center","decorations":{"count":1,"items":["小さなハート"]}},"character_design":{"count":2,"items":[{"role":"husband","hair color":"{argument name=\"hair color\" default=\"ライトブラウン\"}","expression":"親切、穏やか、愛情深い"},{"role":"wife","hair color":"{argument name=\"hair color\" default=\"ライトブラウン\"}","expression":"優しい笑顔、愛情深い、少し照れ屋"}]},"rendering_notes":"すべてのテキストは日本語の手書き風にし、余白を十分に持たせること。夫婦の感謝を伝える投稿にふさわしい、甘く記念的なムードを維持する。線画は磨き上げられたインク調ではなく、少しラフなスケッチ風に仕上げる"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="コミック / ストーリーボード - ほっこり温かい 4 コマ夫婦漫画 - Image 1">
</div>

#### 📌 詳細

- **作者:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **ソース:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14492)**

---

### No. 71: コミック / ストーリーボード - 日本語 AI マンガデモページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

AI によるマンガのテキスト品質をアピールするのに最適な、印象的な日本語のセリフが描かれた猫耳キャラクターの 4 コママンガページです。

#### 📝 プロンプト

```
{
  "type": "4 コマアニメマンガページ",
  "style": "洗練されたきれいなアニメイラスト、温かみのある室内の照明、非常に読みやすい縦書きの日本語吹き出し、柔らかな陰影、表情豊かなマンガのコマ割り、詳細で居心地の良いリビングルームの背景、ライトブラウンとベージュのインテリア、木製の床、ソファ、コーヒーテーブル、マグカップ、小さな観葉植物、壁に飾られたアート",
  "format": {
    "page_orientation": "縦長",
    "panel_count": 4,
    "reading_flow": "左上、右上、中段ワイド、下段ワイド",
    "borders": "太い黒枠のマンガコマ",
  },
  "characters": [
    {
      "id": "青い猫耳少女",
      "appearance": "短いボブカットの {argument name="hair color" default="青い"} 髪をした小さなちびキャラの猫耳少女、アホ毛、白い毛が混じった猫耳、白い毛先のふわふわした尻尾、大きな琥珀色の瞳、小さな牙のような口",
      "outfit": "白い襟付きシャツの上にオレンジ色のセーター、青い縁取り、リボンベルト付きの茶色のスカート、黄色い X 字型のヘアクリップ"
    },
    {
      "id": "金色の猫耳少女",
      "appearance": "長くウェーブのかかった金髪の元気な猫耳少女、猫耳、ふわふわした尻尾、明るく陽気な表情",
      "outfit": "マスタードイエローのケーブルニットセーター、ダークブラウンのチェック柄スカート"
    },
    {
      "id": "白髪の女性",
      "appearance": "長い白髪の美しい女性、白い猫耳、小麦色の肌、金色の瞳、穏やかで自信に満ちた笑顔",
      "outfit": "黒いトップスの上に白いジャケット、重ね付けしたゴールドのネックレスとイヤリング"
    },
    {
      "id": "メイドの女性",
      "appearance": "長いライトブロンドの髪を持つ大人の女性、猫耳",
      "outfit": "白いフリルのヘッドドレスと赤いリボンが付いた黒と白のメイド服"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "1 コマ目",
        "position": "左上",
        "count": 1,
        "labels": ["どうせ日本語微妙なんでしょ？文字がダメなら認めないよ"],
        "scene": "居心地の良いリビングのソファに座り、顎に指を当てて、疑わしげで好奇心旺盛な表情をしている青い猫耳少女。頭上に小さなクエスチョンマークが浮かんでいる"
      },
      {
        "title": "2 コマ目",
        "position": "右上",
        "count": 1,
        "labels": ["ねぇねぇ！GPT Image2 すごいよ！"],
        "scene": "背後にスピード線を描きながら、ドアから劇的に飛び込んでくる金色の猫耳少女。両手を広げ、興奮に満ちた様子"
      },
      {
        "title": "3 コマ目",
        "position": "中段ワイド",
        "count": 3,
        "labels": ["うわっ びっくりした！めちゃくちゃキレイじゃん！", "ねぇねぇ！GPT Image2 すごいよ！ 微妙なんでしょ？ 文字がダメなら認めないよ", "ほら見て！わたしたちのセリフ！"],
        "scene": "両手を顔の近くに添えて驚く青い猫耳少女と、その横で誇らしげに指をさす金色の猫耳少女。中央の大きな吹き出しには、議論している日本語のセリフ例が表示されている"
      },
      {
        "title": "4 コマ目",
        "position": "下段ワイド",
        "count": 3,
        "labels": ["進化が早すぎてもう驚かないよね〜", "絵も可愛く描けてるし文字の白抜きも完璧よね", ""],
        "scene": "手前では、メイドの女性が感銘を受けて口元を覆い、白髪の女性が顎に手を当てて思慮深くコメントしている。背景では、ソファの前で青い猫耳少女と金色の猫耳少女が嬉しそうに飛び跳ねて喜んでいる"
      }
    ]
  },
  "text_handling": {
    "language": "日本語",
    "balloon_direction": "縦書きレイアウト",
    "emphasis": "日本語のタイポグラフィを鮮明かつ自然にし、マンガの吹き出しにきれいに統合すること。必要に応じて白抜き文字を使用する"
  },
  "tone": "遊び心があり、お祝いムードで、AI 生成マンガにおける高品質な日本語テキストのレンダリングに感銘を受けている様子",
  "quality": "高精細、一貫性のあるキャラクターデザイン、キュートで読みやすいプロモーション用マンガ"
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="コミック / ストーリーボード - 日本語 AI マンガデモページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **ソース:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14471)**

---

### No. 72: コミック / ストーリーボード - 優雅なアニメ風女剣士の 4 コマシート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、高貴な白髪の女剣士を描いた高精細な 4 コマ構成のアニメ風キャラクターイラストを生成します。ファンタジーのキービジュアルやキャラクター紹介、プレミアムな SNS 投稿に最適です。

#### 📝 プロンプト

```
2x2 のグリッドで構成された、洗練されたアニメ風ファンタジーイラストシート。同一の優雅な女剣士を 4 つのパネルで表現しています。キャラクターは、大きな濃紺のリボンを結んだ高いポニーテールの非常に長いプラチナホワイトの髪を持つ若い女性。柔らかく緩やかなカールと流れるような毛束、透き通るような肌、そして輝く赤ピンクの瞳を持つ、繊細で洗練された容姿です。彼女は装飾的な白と紺のゴシック調貴族ドレスを纏っています。レースの縁取りと金刺繍が施された白いハイカラーのフリルブラウス、赤い宝石のブローチが付いた胸元の大きな紺色のリボン、リボンカフス付きのパフスリーブ、金色のディテールが施されたダークネイビーのコルセットウエスト、そして金色の花柄や重なり合うフリル、サテンの光沢で飾られたボリュームのある紺色のスカートが特徴です。ダークな柄と金色のアクセントが施された鞘入りの刀を携えています。パネル 1 は胸から上のクローズアップ・バストアップで、少し横を向き、暗く輝く夜の背景にドラマチックなリムライトで髪が輝いています。パネル 2 はダイナミックな上半身のアクションショットで、キャラクターが刀を抜くか、あるいは視聴者に向けて水平に構えており、髪が激しくなびき、映画のような夜の街のボケ味と輝く花びらが周囲を舞っています。パネル 3 は全身のファッションポートレートで、高く輝く建造物に囲まれた光り輝くホールに優雅に立ち、ドレスのシルエット全体、リボン付きのヒール、腰に差した刀を見せています。パネル 4 は夕暮れや夜明けのきらめく海辺での 3/4 バックショットで、キャラクターが肩越しに振り返り、背後には温かみのあるパステルの空と輝く水面、そして風に舞う桜の花びらが描かれています。超高精細なアニメレンダリング、プレミアムなライトノベルの表紙品質、複雑な生地の質感、光沢のあるハイライト、金色の装飾、柔らかなブルーム効果、ドラマチックな逆光、舞い散る花びら、輝く粒子、優雅でロマンチックな雰囲気、そしてネイビー、ホワイト、ゴールド、ブラッシュピンクの調和のとれた配色を使用してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="コミック / ストーリーボード - 優雅なアニメ風女剣士の 4 コマシート - Image 1">
</div>

#### 📌 詳細

- **作者:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **ソース:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14413)**

---

### No. 73: コミック / ストーリーボード - カントリーボール：ホルムズ海峡の対峙

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

ホルムズ海峡の狭い海域で対峙するアメリカとイランのカントリーボールを描いた、ユーモアあふれる地政学的ミームイラスト。社説の風刺やソーシャルメディアでのコメントに最適です。

#### 📝 プロンプト

```
デジタルカートゥーンスタイルで丁寧に描かれた、風刺的なカントリーボールミームのイラスト。{argument name="waterway name" default="ホルムズ海峡"} を、険しい岩壁に挟まれた非常に狭い海峡として表現し、ドラマチックな陰影と岩の質感を強調しています。中央手前では、2 つのカントリーボールが狭い水路を塞ぎ、どちらか一方しか通れない状況になっています。左側には、怒りで目を細めたアメリカのカントリーボールが配置され、星条旗模様で「USA」と白文字で書かれた濃紺の野球帽を被っています。右側には、怒りで目を細めたイランのカントリーボールが配置され、イラン国旗と国章が描かれ、横で結んだ緑と白のヘッドバンドを着用しています。ヘッドバンドには「저항은 우리의 권리（抵抗は我々の権利）」という韓国語が書かれています。それぞれのボールの上には、太い黒枠の白い吹き出しが 1 つずつ（計 2 つ）あり、どちらも「{argument name="speech text" default="길!"}（道！）」という大きな太字の韓国語が書かれており、両者が一歩も譲らない様子を表しています。ボトルネックで鼻と鼻を突き合わせて対峙する 2 つのボールを描写してください。左側の崖には、「호르무즈 해협」および「Strait of Hormuz」と書かれた木製の看板を 1 つ設置してください。右側の崖には、上部にペルシャ語が書かれ、その下に赤い警告三角形が描かれた、通行制限を示す警告看板を 1 つ設置してください。左下隅には「OIL」と書かれた黒いオイルドラム缶を 1 つ配置し、その周囲に黒い油が漏れ出している様子を描いてください。右下隅には、鎖につながれたペルシャ語が書かれた黒い機雷を 1 つ配置してください。狭い海峡の向こう側の背景には、少なくとも 1 隻の大型タンカーを含む 3 隻の遠くの船を描き、空にはかすかな黒煙を立ち昇らせてください。緊張感がありつつもユーモアのある地政学的ミームのトーンで、中央構図、アイレベルの視点、柔らかな昼光、わずかに彩度を抑えたリアルな色使い、鮮明な輪郭線を用い、すべてのテキストを読みやすく仕上げてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="コミック / ストーリーボード - カントリーボール：ホルムズ海峡の対峙 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **ソース:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14683)**

---

### No. 74: コミック / ストーリーボード - 目隠しをした呪術師の勝利ポーズ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトでは、目隠しをした白髪の呪術師が爆発的な青いエネルギーを放つ、ドラマチックな縦型アニメ風アクションポスターを生成します。大胆な漫画風の吹き出し付きで、スタイリッシュなキャラクターアートやファンアートの制作に最適です。

#### 📝 プロンプト

```
強力な白髪の呪術師が、頭を後ろに反らせて口を大きく開けて笑っている、ドラマチックなローアングル全身ポーズのインパクトのある少年漫画風アニメイラスト。洗練された黒のハイカラーの制服を身にまとい、目には黒い目隠しをしている。左手は視聴者に向かって突き出され、2 本指のピースサインを作っており、強い遠近法によって手前にある手が大きく強調されている。右手は体の横に低く垂らされている。周囲には {argument name="energy color" default="エレクトリックブルー"} の爆発的な超常エネルギー、激しい筆致のようなオーラの軌跡、飛び散る破片、火花、そしてフレームを横切る渦巻く曲線が描かれている。背景は、輝く青い破片とスピード線が交差する暗く抽象的で混沌としたエネルギーの爆発とし、圧倒的な力を表現する。大胆なセルシェーディングのアニメレンダリングに、絵画的なハイライト、シャープな線画、強烈なコントラスト、そして黒い衣装の光沢のある布のひだを組み合わせる。右側には、太い黒枠で囲まれた大きなギザギザの白い漫画風吹き出しを追加し、その中に {argument name="speech bubble text" default="LUDDITES ALWAYS LOSE!"} という巨大なダメージ加工の施された黒い大文字のテキストを配置する。縦型構図、ダイナミックなアクションポスターのフレーミング、自信に満ちた勝利の態度、モダンなダークファンタジーアニメの美学。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="コミック / ストーリーボード - 目隠しをした呪術師の勝利ポーズ - Image 1">
</div>

#### 📌 詳細

- **作者:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **ソース:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14637)**

---

### No. 75: コミック / ストーリーボード - 月面銭湯コメディ漫画ページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

月面にある風変わりな銭湯を描いたレトロフューチャーなアニメ調の漫画ページ。キャラクター主導の複数のコマで、遊び心あふれる AI 漫画シーンを生成するのに最適です。

#### 📝 プロンプト

```
月面の風変わりな公衆浴場を舞台にした、カラフルな 1 ページの日本漫画。洗練されたレトロフューチャーなアニメスタイルで描かれ、温かみのある照明、太くきれいなコマ枠、表情豊かな擬音、そして細部まで描き込まれた環境ストーリーテリングが特徴です。舞台は「月面銭湯 つきのゆ」という名の月面温泉で、大きな電飾看板、白く「ゆ」と書かれた青い暖簾、むき出しの配管や計器、丸みを帯びた建築デザイン、そして月面と宇宙に浮かぶ地球が見える巨大な円窓が描かれています。ダイナミックなページレイアウトで構成された 8 コマの漫画を作成してください。1 コマ目：月面銭湯の全景。「月面銭湯 つきのゆ」の看板、「重力 1/6」と書かれた小さな看板、赤い「牛乳」の自動販売機、タヌキの置物、月面の地形、そして銭湯を宣伝する縦長の垂れ幕。2 コマ目：{argument name="character design" default="赤い水玉模様のバンダナでポニーテールにまとめた茶髪、緑色の作業用ジャンプスーツ、工具ベルトを身につけ、元気な表情の"} 若い女性の銭湯整備士が、機械やボイラーの調整をしている様子を後ろや横から見た構図。今日の風呂の準備やボイラーの状態について話す吹き出しを配置。3 コマ目：{argument name="alien appearance" default="丸いミントグリーンの体に紫の斑点、眠そうな目、ピンクの頬、小さな口、頭に紫の星が描かれた白いタオルを乗せた"} かわいい宇宙人の客が、湯気立つお湯に半分浸かってリラックスしている様子。近くにはアヒルのおもちゃが浮かび、「ぬるめ じっくり リラックス」と書かれた木の看板がある。4 コマ目：{argument name="robot design" default="銀色の体に青いアクセント、光る青い目の黒いデジタルフェイス、赤いアンテナライト、細い機械の腕と足を持つ"} 小さな掃除ロボットが、「清掃中」と書かれた看板の横で、ほうきとバケツを使って楽しそうに床を掃除している。5 コマ目：そのロボットが突然滑って浴槽に派手に飛び込み、大きな水しぶきとたくさんの泡が上がる様子。「ぽわぁ〜ん!!」という大きな擬音とともに、横で整備士が驚いている。6 コマ目：「月面牛乳」と書かれた瓶を持って微笑む整備士。7 コマ目：風呂に入った宇宙人が「月面フルーツオーレ」と書かれた瓶を持ち、至福の表情でサムズアップしている。アヒルのおもちゃも健在。8 コマ目：掃除道具とバケツを持って風呂の横でポーズをとる陽気なロボット。「ゆ」と書かれた暖簾と「つきのゆ」と書かれたピンクの洗面器のそばで、お風呂が最高だと言っている。昭和レトロな銭湯のディテールと宇宙テクノロジー、光沢のあるタイル、湯気、泡、そしてキャラクターの愛らしい演技を維持し、月面銭湯で働く日常を描いた、チャーミングなギャグ漫画のような雰囲気を目指してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="コミック / ストーリーボード - 月面銭湯コメディ漫画ページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **ソース:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14697)**

---

### No. 76: コミック / ストーリーボード - キャラクターデザイン参照シート

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

特定のキャラクターに関する主要情報やビジュアルリファレンスを含む、包括的なデザインシートを生成します。

#### 📝 プロンプト

```
{argument name="character" default="Hermes Agent"} のキャラクターデザインシートを、主要情報とともに作成してください
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="コミック / ストーリーボード - キャラクターデザイン参照シート - Image 1">
</div>

#### 📌 詳細

- **作者:** [Neo](https://x.com/NeoAIForecast)
- **ソース:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14324)**

---

### No. 77: コミック / ストーリーボード - インディーコミックブックページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

子供向けのストーリーに合わせた、モダンなインディースタイルのコミックブックレイアウトを作成します。

#### 📝 プロンプト

```
{argument name="comic style" default="モダンなインディーコミック"} スタイルのコミックブックのページ。トピック：{argument name="story topic" default="6 歳児向けのストーリー"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="コミック / ストーリーボード - インディーコミックブックページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [宝玉](https://x.com/dotey)
- **ソース:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14310)**

---

### No. 78: コミック / ストーリーボード - カラー少年漫画のページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

特定のキャラクターやブランドの詳細を含む、物理的な漫画のページを生成するための詳細なナラティブプロンプトです。

#### 📝 プロンプト

```
{argument name="manga type" default="カラーの日本の少年冒険漫画"} のサンプルページを作成してください。ページには、主人公が {argument name="item" default="魔法の羽ペン"} を見つける様子を鮮明に描いてください。その羽ペンの名前は {argument name="item name" default="Quill of GPT Image"} です。ドラマチックに仕上げてください。その魔法の羽ペンには、強力な力が封印されています。

追加の指示: アスペクト比: 縦長 1440x2560。ペンには OpenAI のロゴを入れてください。漫画内の言語はすべて日本語にしてください。優れたストーリーと適切なコマ割りを実現するために、まずは慎重に構成を考えてください。ページはデジタル画像ではなく、物理的な漫画のページを撮影した写真のように見えるようにしてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="コミック / ストーリーボード - カラー少年漫画のページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [宝玉](https://x.com/dotey)
- **ソース:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14311)**

---

### No. 79: コミック / ストーリーボード - 4 コマ漫画風ラブコメページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、日本語のセリフが入ったモノクロの 4 コマ漫画ページを生成します。表情豊かなキャラクターによる、ドラマチックでコミカルなラブコメディの議論シーンを作成するのに最適です。

#### 📝 プロンプト

```
縦に 4 つ並んだコマ、すっきりとした黒い枠線、スクリーントーンによる陰影、ドラマチックな集中線、洗練された青年漫画風の線画で構成されたモノクロの漫画ページを作成してください。ページには、現代的なカジュアルな服装で短い黒髪の若いアニメキャラクターが 2 人登場しますが、両者の顔部分は柔らかい四角いぼかし（モザイク）で隠されています。1 コマ目：乱れた短い黒髪で襟付きシャツを着た細身の若者が、胸元で片方の拳を握りしめ、体を左に向けています。背景には激しい炎のエフェクトが描かれ、感情的で防御的な様子です。右側に大きなギザギザの吹き出しを配置し、以下の日本語テキストを入れてください：「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」。2 コマ目：少し背の高いもう一人の若者が、暗い色のジップジャケットに明るい色のシャツを着て、何かを説明するように人差し指を 1 本立てて冷静に振る舞っています。右側に角丸の四角い吹き出しを配置し、以下の日本語テキストを入れてください：「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」。3 コマ目：背の高いキャラクターが短いキャラクターの頭を優しく撫でています。手元に「ポン」という小さな擬音語を添えてください。短いキャラクターは驚いて見上げています。右側に大きな楕円形の吹き出しを配置し、以下の日本語テキストを入れてください：「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」。4 コマ目：短いキャラクターが顔を真っ赤にして、目が渦巻きになり、汗をかき、震えながら口を開けているアップの表情。頬には濃いハッチングが施され、恥ずかしさで圧倒されています。背景をドラマチックな集中線で埋め尽くしてください。右側に大きなギザギザの吹き出しを配置し、以下の日本語テキストを入れてください：「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」。2 つの擬音語を追加してください：肩の近くに小さな「プル…」、左下側に大きく震える手書き風の「カァァァ」。ページ全体をモノクロで統一し、激しい議論、冷静な解説、からかうような愛情、そして赤面する結末という、強烈な感情のコントラストを持つラブコメ漫画のトーンを維持してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="コミック / ストーリーボード - 4 コマ漫画風ラブコメページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **ソース:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14468)**

---

### No. 80: コミック / ストーリーボード - Velvedia キャラクターリファレンスシート

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

メカスタイルキャラクター「Velvedia」のキャラクターリファレンスシートを生成するための短いプロンプトです。

#### 📝 プロンプト

```
{argument name="character name" default="Velvedia"} reference sheet
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="コミック / ストーリーボード - Velvedia キャラクターリファレンスシート - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="コミック / ストーリーボード - Velvedia キャラクターリファレンスシート - Image 2">
</div>

#### 📌 詳細

- **作者:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **ソース:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **公開日:** 2026年4月21日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14368)**

---

### No. 81: コミック / ストーリーボード - 8 コマ GPT-Image-2 マンガ風プロモーション

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、GPT-Image-2 を発表・解説するための、SNS 向けの 8 コマのモノクロマンガ風コミックページを生成します。

#### 📝 プロンプト

```
{"type":"8 コママンガ風プロモーションコミックページ","theme":"GPT-Image-2 のローンチ告知","language":"ポルトガル語","style":{"rendering":"スクリーントーン、集中線、光沢のあるハイライト、太いインクの輪郭線、デジタルコミック仕上げのモノクロマンガ","mood":"エキサイティング、有益、楽観的、テクノロジー志向","page_format":"2 列 × 4 行のグリッドに分割された 8 コマ構成、細い枠線"},"characters":[{"id":"host girl","role":"メインプレゼンター","appearance":"長い黒髪で表情豊かな大きな目を持つかわいいアニメ少女、胸元に OpenAI のノットロゴが入ったダークパーカーを着用","count":1},{"id":"robot mascot","role":"フレンドリーなアシスタントマスコット","appearance":"黒い顔のスクリーンと光る目を持つ小さな丸いロボット、シンプルな白いボディ、小さな腕、陽気な表情","count":1},{"id":"creator group","role":"視聴者の例","appearance":"4 人の異なる若手クリエイター：デザイナー 1 名、タブレットを持つ開発者 1 名、カメラを持つ写真家 1 名、ノート PC とパーカー姿の人物 1 名","count":4}],"layout":{"sections":[{"title":"CHEGOU! GPT-IMAGE-2","position":"左上","count":1,"description":"アニメ少女が視聴者に向かって手を伸ばすドラマチックなヒーロー紹介コマ、背後に放射状の集中線","text":["CHEGOU!","GPT-IMAGE-2","A NOVA GERAÇÃO DE IMAGENS POR IA DA OPENAI!","MAIS CRIATIVIDADE, MAIS PRECISÃO, MAIS POSSIBILIDADES!"]},{"title":"O QUE É O GPT-IMAGE-2?","position":"右上","count":1,"description":"星空のようなテクノロジー背景の中、光る画像アイコンの横で上を指差す少女の半身ポーズ","text":["O QUE É O GPT-IMAGE-2?","É nosso novo modelo de geração de imagens, mais inteligente, mais fiel ao que você imagina e com qualidade surpreendente!"]},{"title":"MAIS REALISMO. MAIS DETALHES.","position":"中段左","count":1,"description":"山と湖の風景を左右に並べた比較コマ。左は旧モデル、右はよりリアルな新モデルとラベル付け","subsections":[{"label":"ANTES (DALL·E 3)","count":1},{"label":"AGORA (GPT-IMAGE-2)","count":1}],"text":["MAIS REALISMO. MAIS DETALHES.","ANTES (DALL·E 3)","AGORA (GPT-IMAGE-2)","TEXTURAS MAIS RICAS, LUZ MAIS NATURAL, DETALHES INCRÍVEIS!"]},{"title":"COMPREENSÃO MELHOR, RESULTADOS MELHORES.","position":"中段右","count":1,"description":"フレームに入ったプロンプト例の横で手を合わせる少女と、上を指差すロボットマスコット","text":["COMPREENSÃO MELHOR, RESULTADOS MELHORES.","O GPT-IMAGE-2 entende melhor objetos, textos, composições e instruções complexas!","EXEMPLO DE PROMPT:","\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\""]},{"title":"CRIATIVIDADE SEM LIMITES.","position":"下段左","count":1,"description":"生成された 4 つのアートバリエーションの 2x2 ショーケースの横で話す少女","subsections":[{"label":"gothic castle scene","count":1},{"label":"modern city street at night","count":1},{"label":"anime character portrait","count":1},{"label":"abstract geometric composition","count":1}],"text":["CRIATIVIDADE SEM LIMITES.","De estilos artísticos a layouts profissionais, do realista ao abstrato: suas ideias, do seu jeito!"]},{"title":"TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","position":"下段右","count":1,"description":"ポスターのタイポグラフィのビフォーアフターを比較し、2 つのデザインの間に太い矢印を配置するロボットマスコット","subsections":[{"label":"ANTES","count":1},{"label":"AGORA","count":1}],"text":["TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","Geração de texto mais precisa, legível e integrada ao design!","ANTES","AGORA","AVENTURA COMEÇA AQUI","A AVENTURA COMEÇA AQUI"]},{"title":"PARA TODOS OS CRIADORES.","position":"左下","count":1,"description":"ホストの少女と 4 人のクリエイターが並んで立つグループショット、異なる職業を表現","text":["PARA TODOS OS CRIADORES.","Designers, desenvolvedores, educadores, marketers, artistas e curiosos: todo mundo pode criar mais e melhor!"]},{"title":"GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","position":"右下","count":1,"description":"少女がウィンクして親指を立てる締めくくりのヒーローコマ、横にはロボットマスコット、明るい祝福の光とキラキラ","text":["GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","IMAGINE. CRIE. INSPIRE.","O FUTURO DA CRIAÇÃO É AGORA. ❤"]}],"panel_count":8},"composition":{"reading_order":"左から右、上から下へ","camera_variety":"ヒーローショットのクローズアップ、プレゼンターのミディアムショット、比較グラフィック、グループショットの組み合わせ","graphic_elements":["吹き出し","白い大文字の文字が入った丸い黒いタイトルバナー","キラキラ","集中線","星空のようなテクノロジー背景","比較矢印","フレーム付きの例示カード"]},"text_style":"ポルトガル語による全大文字のコミックレタリング、太字のディスプレイヘッダー、明確な吹き出し、プロモーション用インフォグラフィックとコミックのハイブリッド","quality":"高解像度の編集用コミックポスター、鮮明なタイポグラフィ、バランスの取れたコマ間隔、強いコントラスト","prompt":"GPT-IMAGE-2 を発表するグレースケールのマンガ風 8 コマプロモーションコミックページを作成してください。1 ページ 2 列 × 4 行のレイアウトで、正確に 8 つの異なるコマを使用し、全編ポルトガル語のテキストを配置してください。{argument name=\"hair color\" default=\"ダークブラウン\"}の長い髪、OpenAI ロゴ入りのダークパーカーを着た陽気なアニメプレゼンターの少女と、フレンドリーな小型ロボットマスコットを登場させてください。1 コマ目：ドラマチックなローンチ発表、カメラに向かって手を伸ばす少女、放射状の集中線、見出し \"CHEGOU! GPT-IMAGE-2\" と AI 画像の新世代に関するローンチコピー。2 コマ目：星空のようなデジタル背景で光る画像アイコンの横で指差す少女、タイトル \"O QUE É O GPT-IMAGE-2?\" と、より賢い画像生成モデルであることを説明する吹き出し。3 コマ目：山と湖の風景を左右に並べたリアルさの比較、\"ANTES (DALL·E 3)\" と \"AGORA (GPT-IMAGE-2)\" とラベル付け。4 コマ目：少女とロボットによる理解力向上パネル、\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\" というプロンプト例をフレームに入れて配置。5 コマ目：ゴシック城、夜の街、アニメのポートレート、抽象的な幾何学アートの 4 つのサムネイルによる創造性のショーケース。6 コマ目：\"ANTES\" と \"AGORA\" とラベル付けされたポスターのバリエーションによるテキストレンダリングの比較、\"AVENTURA COMEÇA AQUI\" というフレーズの改善されたタイポグラフィを表示。7 コマ目：異なる分野の 4 人のクリエイターが並ぶ視聴者パネル。8 コマ目：少女がウィンクして親指を立て、ロボットが応援する最終的な祝福のコールトゥアクション、締めくくりのスローガン \"IMAGINE. CRIE. INSPIRE.\"。エネルギッシュで洗練され、非常に読みやすく、太い黒のヘッダーバー、白い大文字、吹き出し、キラキラ、スクリーントーン、そして力強いマンガ/コミックのプロモーションポスターの美学を取り入れてください。"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="コミック / ストーリーボード - 8 コマ GPT-Image-2 マンガ風プロモーション - Image 1">
</div>

#### 📌 詳細

- **作者:** [Diogo Santos](https://x.com/diogosantosbr)
- **ソース:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14639)**

---

### No. 82: コミック / ストーリーボード - 検閲済みオフィス漫画の対立シーン

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

オフィスでの激しい口論から壁ドンへと展開する、シリアスなモノクロ漫画ページ。ドラマチックでバイラルな漫画風スクリーンショットの再現に最適です。

#### 📝 プロンプト

```
青年漫画スタイルのドラマチックなモノクロページ。密度の高いスクリーントーン、鋭いペン入れ、強いコントラストのライティング、そして表現力豊かな日本の漫画レイアウトで描かれています。現代的なオフィスを舞台に、2 人の会社員の緊張感あふれる対立を描いた 4 段構成のパネルで、縦書きの日本語吹き出しと力強い効果音が配置されています。1 段目では、ショートボブの髪型で、スリムながらも曲線的な体型の若い女性が、袖をまくったフィット感のあるブラウスとタイトスカートを着用し、怒りに任せてデスクを激しく叩いています。彼女は視聴者に向かって身を乗り出し、爆発的な集中線と大きなギザギザの吹き出しが描かれています。2 段目では、黒髪を無造作に流したスリムな青年が、ライトシャツの上に黒のレザージャケットとネックレスを身につけ、落ち着いた自信たっぷりのポーズで顔に手を当てながら話しています。3 段目では、男性が女性を壁際に追い詰め、片手を彼女の頭の横について壁ドンをする親密なポーズをとっています。女性は動揺して緊張した様子を見せ、男性が彼女の顔の近くで話しかけることで、ロマンチックかつコメディタッチな急展開を見せています。4 段目では、オフィス全体を俯瞰した構図で、デスク 1 台、PC モニター 1 台、キーボード 1 台、マウス 1 台、オフィスチェア 1 脚、そして床に散らばった書類が描かれています。女性は恥ずかしそうに身を縮めて震えており、男性はリラックスした様子で彼女の隣に立っています。パネルは合計 4 つ、吹き出しも合計 4 つ配置し、全体に日本語の漫画タイポグラフィを組み込んでください。オンラインでの共有を想定し、各パネルのキャラクターの顔にはモザイク処理を施してください。背景にはオフィスの壁、デスクの端、集中線、バースト効果、トーンのグラデーションを含めます。全体として、激しい口論が駆け引きのある誘惑へと変わる、バイラルな漫画の切り抜きのような雰囲気を演出してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="コミック / ストーリーボード - 検閲済みオフィス漫画の対立シーン - Image 1">
</div>

#### 📌 詳細

- **作者:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **ソース:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14477)**

---

### No. 83: コミック / ストーリーボード - 量子猫マンガ

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

量子力学的な振る舞いをする猫をテーマにした、マンガのコマを生成するための短くクリエイティブなプロンプトです。

#### 📝 プロンプト

```
{argument name="subject" default="猫"} が {argument name="concept" default="量子粒子のように振る舞う"} マンガを描いてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="コミック / ストーリーボード - 量子猫マンガ - Image 1">
</div>

#### 📌 詳細

- **作者:** [Haruhiko Okumura](https://x.com/h_okumura)
- **ソース:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **公開日:** 2026年4月21日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14348)**

---

### No. 84: コミック / ストーリーボード - 羊の女の子の可愛いオフィス漫画ページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

羊の角が生えた事務員とふわふわの羊が、書類仕事を眠くて心地よいギャグシーンに変えてしまう、パステルカラーのファンタジーオフィス4コマ漫画。

#### 📝 プロンプト

```
{"type":"4コマ漫画ページ","style":"ソフトパステル調のアニメちびキャラ、温かみのあるベージュとクリーム色のパレット、柔らかな朝の光、角の丸いコマ枠、読みやすい日本語のセリフ、心地よいコメディファンタジーの日常系オフィス","page":{"orientation":"縦長","panel_count":4,"gutter":"細い白の余白","border":"茶色の丸みを帯びた枠線"},"setting":{"location":"小さな管理事務所の室内","details":["木の床","日の当たる窓","書類の置かれたデスク","木製の椅子","ファイルや本でいっぱいの本棚","積み上げられた箱や事務用品","光の中に舞う柔らかな埃とキラキラしたエフェクト"]},"characters":[{"role":"メインキャラクター","appearance":"短いふわふわの金髪ボブヘア、オッドアイ（青と琥珀色）、小さなエルフのような耳、大きな巻き角、羊の顔の形をしたふわふわのフード、白いブラウス、赤いネクタイ、淡いピンクのエプロンドレス、エプロンのポケットに小さなペンを差した、ちびキャラの羊の女の子"},{"role":"サブキャラクター","appearance":"小さな顔と短い足を持つ、雲のようにぬいぐるみ感のある丸くてふわふわした白い羊"}],"layout":{"sections":[{"title":"1コマ目","position":"上段","count":3,"labels":["事務所のドアを開けて中を覗き込む羊の女の子","その横から顔を出す小さな羊","左に楕円形の吹き出し1つ、右に小さな楕円形の吹き出し1つ"]},{"title":"2コマ目","position":"中段上","count":3,"labels":["デスクの横に立ち、片手を腰に当てて書類を指差す羊の女の子","デスクの横に座る小さな羊","左に大きな楕円形の吹き出し1つ"]},{"title":"3コマ目","position":"中段下","count":3,"labels":["書類の上に広がって眠るふわふわの羊","左上から疲れた表情で覗き込む羊の女の子のアップ","右側に紫色の眠そうな擬音テキスト"]},{"title":"4コマ目","position":"下段","count":4,"labels":["デスクで目を閉じて微かに微笑みながら眠る羊の女の子","書類の上で一緒に眠るふわふわの羊","左の窓から差し込む温かい日差し","右下に小さな長方形のモノローグ枠"]}]},"text":{"language":"日本語","elements":[{"kind":"speech bubble","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"speech bubble","panel":1,"text":"メェ"},{"kind":"speech bubble","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"speech bubble","panel":3,"text":"…名簿が もふもふに…"},{"kind":"sound effect","panel":3,"text":"Zzz…"},{"kind":"speech bubble","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"caption","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"一貫性を保つため、4コマすべて同じオフィス内で構成してください。可愛い表情やふわふわの質感、そして羊と事務員が書類の上で一緒に眠ってしまい仕事が止まってしまうというギャグを強調してください。2コマ目から4コマ目にかけて書類がはっきりと見えるようにし、穏やかで眠気を誘うような心温まるトーンを維持してください。"}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="コミック / ストーリーボード - 羊の女の子の可愛いオフィス漫画ページ - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="コミック / ストーリーボード - 羊の女の子の可愛いオフィス漫画ページ - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="コミック / ストーリーボード - 羊の女の子の可愛いオフィス漫画ページ - Image 3">
</div>

#### 📌 詳細

- **作者:** [じょにがたロボ](https://x.com/jonigata_ai)
- **ソース:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14532)**

---

### No. 85: コミック / ストーリーボード - 猫の嫉妬を描いたかわいい 4 コマ漫画

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、SNS 投稿やマンガ風のユーモア、心温まるペットのイラストに最適な、手描き風の温かみのある猫の 4 コマ漫画を生成します。

#### 📝 プロンプト

```
淡いクリーム色の背景に、太い黒枠とわずかにテクスチャ感のある紙の質感を加えた、柔らかく温かみのある日常系スタイルの手描き風 4 コマ漫画。丸みを帯びたシンプルな猫のキャラクター、表情豊かな顔立ち、すっきりとした黒の輪郭線、落ち着いた自然な色合い、そして優しいマンガ風の表現を用いてください。左上のコマには 2 匹の猫を描きます。1 匹はダークブラウンの縞模様と白い口元を持つ茶トラ猫で、目を閉じて満足そうに座っています。もう 1 匹は頭にダークブラウンの斑点がある白猫で、隣に立って茶トラ猫の頬を愛情を込めて舐めています。幸せな毛づくろいの様子を表すために、2 匹の上に小さな黒い音符を 2 つ追加してください。右上のコマには、手前に白と茶の斑点模様の猫を描き、右側に立っている小さな三毛の子猫の方を向かせます。子猫の上に「めい」という日本語のテキストが入った吹き出しを追加してください。左下のコマには 3 匹の猫を一緒に描きます。左側に驚いたような、あるいは無表情な茶トラ猫、右側に陽気な様子の斑点模様の白猫、そして中央手前に見上げるような小さな三毛の子猫を配置してください。右下のコマには、茶トラ猫のアップを描きます。正面を向き、黄緑色の目を細めて怒ったような嫉妬の表情を浮かべています。顔の近くに短い強調線を 2 本、右側に小さな怒りマークを 1 つ追加してください。茶トラ猫が毛づくろいされて幸せだったところに新しい子猫が現れるという視覚的なジョークを交え、全体的に居心地が良くコミカルなトーンを維持してください。フラットな色使いと最小限の影付けで、魅力的な日本の Web マンガのような雰囲気を出してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="コミック / ストーリーボード - 猫の嫉妬を描いたかわいい 4 コマ漫画 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Maoku](https://x.com/Maoku)
- **ソース:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14503)**

---

### No. 86: コミック / ストーリーボード - Moon Mark 冒険コミックページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

銀髪の月をモチーフにした少女が、地図を見つけ、洞窟のパズルを解き、次の冒険への魔法の招待状を手に入れる様子を描いた 4 コマファンタジーアニメコミックページ。

#### 📝 プロンプト

```
{"type":"4 コマアニメコミックページ","style":"キュートなファンタジー漫画イラスト、洗練された gpt-image-2 アニメレンダリング、鮮やかな色彩、クリーンな線画、柔らかな絵画風の陰影、幻想的で魔法のような雰囲気","page":{"background":"黒い枠線付きの白いページ","title":"{argument name=\"headline text\" default=\"月のしるしの大冒険\"}","title_position":"上部中央","decorations":["タイトルの周りに小さな金の輝き","タイトルの右側に三日月のアイコン"],"panel_count":4,"reading_direction":"上から下"},"character":{"appearance":"非常に長いウェーブのかかった銀髪、色白の肌、大きく表情豊かな瞳、スリムな体型の若いアニメ風の冒険者の少女","outfit":["フリル付きの白黒ファンタジードレス","三日月の髪飾り","三日月のチョーカー","オフショルダーの袖","茶色のレザーリュック","ダークカラーのニーハイソックス"],"theme":"衣装や小道具全体に月をモチーフにしたデザイン"},"panels":[{"position":"上段","scene":"青空と雲が広がる晴れた山の小道と草原、右側に森、遠くに続く曲がりくねった道、左側に木製の道標","action":"少女が古い宝の地図を手に持ち、前を向いて読んでいる","props":["古びた地図","木製の道標","リュック"],"text":{"sign":"冒険のはじまり","speech":"{argument name=\"panel 1 speech\" default=\"地図を発見！今日は大冒険だ！\"}"}},{"position":"中段上","scene":"三日月のシンボルが刻まれ、ツタに覆われた古い石柱に囲まれた、暗い洞窟の入り口がある緑豊かな遺跡","action":"地図を読みながら慎重に近づく少女の後ろ姿（斜め後ろからのアングル）","props":["地図","遺跡の洞窟の入り口","生い茂る植物"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"この先にお宝があるはず…！\"}","sound_effect":"ガサガサ"}},{"position":"中段下","scene":"薄暗い洞窟の遺跡内部、中央に石の祭壇またはパズル台","action":"少女がランタンのそばで膝をつき、近くの鍵穴ではなくパズルの仕掛けに手を伸ばしている。丸い黒猫のようなマスコットが見守っている","props":["温かい光を放つランタン","円形のシンボルが刻まれた石のパズル板","テーブルの上の小さな金の鍵","三日月のマークとビーズの首輪をつけた黒猫の生き物"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"カギじゃなくて、仕掛けを解けばいいんだ！\"}","sound_effect":"ピカッ"}},{"position":"下段","scene":"洞窟の壁にクリスタルが埋め込まれ、キラキラと輝きが漂う宝物庫","action":"開いた宝箱の横で、少女が目を閉じて明るく微笑み、招待状のカードを掲げている","props":["三日月のエンブレムが付いた開いた木製の宝箱","箱の中の光るコンパス","『つぎの冒険へ』と書かれた紙のカード","青と紫のクリスタル"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"宝物は…次の冒険への招待状！\"}","tag":"つづく？"}}]}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="コミック / ストーリーボード - Moon Mark 冒険コミックページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [ツバサ天九](https://x.com/wing_sky_nine)
- **ソース:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14605)**

---

### No. 87: プロダクトマーケティング - アニメキャラクターのブランドアイデンティティ＆グッズデザインボード

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

アニメキャラクターをフィーチャーした包括的なブランドデザインボードを生成します。製品パッケージ、SNS モックアップ、グッズのレイアウトなどが含まれます。

#### 📝 プロンプト

```
{
  "type": "ブランドアイデンティティおよびグッズデザインボード",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"パステルピンク\"} とホワイト",
    "motif": "{argument name=\"motif\" default=\"桜\"} とピンクのハート"
  },
  "character": {
    "description": "茶色のボブヘア、ピンクの瞳、白いパーカーを着用した、優しい笑顔のアニメ風の女の子"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "ヘッダーバナー",
        "position": "上部",
        "elements": ["大きなメインロゴ", "サブロゴ", "桜のグラフィック", "右側にキャラクターのポートレート"]
      },
      {
        "type": "製品パッケージ",
        "position": "中段左",
        "elements": ["ピンクのハート型キャンディが見えるハート型の透明窓付きの正方形ボックス 1 個", "ボックスにキャラクターのイラスト", "個包装のキャンディ 2 個", "散らばったハート型キャンディ 5 個"]
      },
      {
        "type": "プロモーションポスター",
        "position": "中段右",
        "elements": ["キャラクターのポートレート", "ハート型のキャンディボウル", "メインロゴ", "テキスト '4.26 NEW OPEN'", "テキスト '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "横長ウェブバナー",
        "position": "中段下",
        "elements": ["メインロゴ", "桜", "右側にキャラクターのポートレート"]
      },
      {
        "type": "SNS プロフィールモックアップ",
        "position": "下段左",
        "elements": ["ロゴ入りヘッダー画像", "円形プロフィール画像 1 個", "ハンドル名 '{argument name=\"social handle\" default=\"@yuonchii\"}'", "フォローボタン 1 個", "プロフィール文のモックアップ"]
      },
      {
        "type": "グッズコレクション",
        "position": "下段右",
        "count": 9,
        "items": ["ロゴ入りホワイト T シャツ 1 枚", "キャラクター入りホワイトマグカップ 1 個", "丸型缶バッジ 4 個", "アクリルキーホルダー 1 個", "キャンディパック 2 個"]
      }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="プロダクトマーケティング - アニメキャラクターのブランドアイデンティティ＆グッズデザインボード - Image 1">
</div>

#### 📌 詳細

- **作者:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **ソース:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13547)**

---

### No. 88: プロダクトマーケティング - ダークモード採用のバイラルマーケティング事例紹介ランディングページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

データ可視化、タイムライン、3Dイラストを盛り込んだ、ダークテーマのマーケティング事例紹介用UIモックアップ。

#### 📝 プロンプト

```
{
  "type": "ランディングページ UI デザイン",
  "theme": "ダークモード、モダンテック、{argument name=\"primary accent color\" default=\"ネオンパープル\"} とブルーの光るアクセント、グラスモーフィズム",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "badge": "バイラルキャンペーン事例紹介"
  },
  "sections": [
    {
      "id": "hero",
      "layout": "左側にテキスト、右側に画像を配置した分割レイアウト",
      "content": {
        "badge": "事例紹介",
        "headline": "{argument name=\"hero headline\" default=\"1,000 万回以上のバイラルインパクトを生み出した手法\"}",
        "subtitle": "ネットワークを 3 日間で活性化し、ブランドの指数関数的な成長を支援",
        "stats_row": {
          "count": 4,
          "labels": ["総再生数 {argument name=\"main metric\" default=\"1,024 万回以上\"}", "エンゲージメント率 18.7%", "コンバージョン数 3,200 件以上", "実行期間 72 時間"]
        },
        "hero_image": "暗い部屋で光るフローティングビデオスクリーンを見つめる人物のシネマティックなショット、大きな再生ボタンのオーバーレイ"
      }
    },
    {
      "id": "strategy",
      "title": "キャンペーンの全貌：3 日間の実行戦略",
      "layout": "3 ステップの垂直タイムライン",
      "steps": [
        {"step": 1, "title": "戦略策定", "image": "画面上のデータを分析する人々"},
        {"step": 2, "title": "コンテンツ制作", "image": "動画編集インターフェース"},
        {"step": 3, "title": "配信と拡散", "image": "SNS アイコンが表示されたスマートフォンを持つ手"}
      ]
    },
    {
      "id": "performance",
      "title": "成果：データドリブンなパフォーマンス",
      "layout": "左側に統計カードのグリッド、右側にチャートを配置",
      "left_stats": {
        "count": 4,
        "labels": ["総露出数 1,000 万回以上", "平均 CPM 43% 低減", "新規フォロワー 28,000 人以上", "コンバージョン数 3,200 件以上"]
      },
      "right_charts": {
        "count": 2,
        "items": [
          "3 日目に 832 万回でピークに達する 7 日間のトレンドを示す折れ線グラフ",
          "プラットフォーム別の内訳を示す横棒グラフ：TikTok 52%、Instagram 24%、X 15%、YouTube 9%"
        ]
      }
    },
    {
      "id": "keys_to_success",
      "title": "バイラル化の理由：成功のための 3 つの鍵",
      "layout": "3 枚のカードを横並びに配置",
      "cards": [
        {"icon": "fire", "title": "感情を揺さぶるフックのデザイン"},
        {"icon": "bullseye", "title": "コンテンツ構造の設計"},
        {"icon": "antenna", "title": "配信戦略の実行"}
      ]
    },
    {
      "id": "social_proof",
      "title": "クリエイターやブランドから信頼されています：多くの企業が goViralX で成長を実現",
      "layout": "左側にロゴ、右側に導入事例を配置した分割レイアウト",
      "left_logos": {
        "count": 8,
        "labels": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
      },
      "right_testimonials": {
        "count": 2,
        "labels": ["SaaS 創業者からのコメント", "グロースマネージャーからのコメント"]
      }
    },
    {
      "id": "cta",
      "title": "バイラル化の準備はできていますか？：同じ成長効果を得たいですか？",
      "layout": "左側にテキストと入力フォーム、右側に 3D イラストを配置",
      "elements": [
        "プレースホルダーテキスト付きの入力フィールド",
        "ボタン：{argument name=\"call to action text\" default=\"専用の成長プランを獲得 ->\"}"
      ],
      "image": "紫と青に光る 3D ロケットの発射シーン"
    }
  ],
  "footer": "ロゴと著作権表示"
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="プロダクトマーケティング - ダークモード採用のバイラルマーケティング事例紹介ランディングページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [开发者Hailey](https://x.com/IndieDevHailey)
- **ソース:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **公開日:** 2026年4月17日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13769)**

---

### No. 89: プロダクトマーケティング - 18 パネル構成 マスコットブランドアイデンティティドキュメント

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

3D マスコットのブランドガイドラインおよびキャラクターデザインシート（全 18 セクション）。ムードボードや線画から、3D ターンアラウンド、実物モックアップまでを網羅しています。

#### 📝 プロンプト

```
{
  "type": "18 パネル構成 ブランドアイデンティティおよびキャラクターデザインドキュメント",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"沐阳 MUYANG TEA\"}",
    "industry": "{argument name=\"industry\" default=\"ティーショップ\"}",
    "colors": ["{argument name=\"primary color\" default=\"イエロー\"}", "{argument name=\"secondary color\" default=\"グリーン\"}", "ホワイト", "ブラウン", "ダークグリーン"]
  },
  "subject": "{argument name=\"character description\" default=\"緑のエプロンを着用した 3D レンダリングの可愛い柴犬マスコット\"}",
  "layout": {
    "grid": "3 列 × 6 行",
    "sections": [
      {
        "title": "01 ブランド DNA 分析 / BRAND DNA ANALYSIS",
        "elements": ["ロゴ", "5 色のスウォッチ", "6 つのアイコン", "ターゲットオーディエンスチャート"]
      },
      {
        "title": "02 コンセプトムードボード / CONCEPT MOODBOARD",
        "elements": ["5 つの参考写真", "4 つのムードアイコン", "デザイン方程式"]
      },
      {
        "title": "03 形態研究 / FORM STUDY",
        "elements": ["4 つのロゴ解剖アイコン", "4 つの進化ステップ", "4 つのシルエット"]
      },
      {
        "title": "04 コンセプト探索 / CONCEPT EXPLORATION",
        "elements": ["12 のキャラクター線画スケッチ"]
      },
      {
        "title": "05 精密線画 / REFINED LINE ART",
        "elements": ["プロポーションガイド付き正面および側面の線画 3 行"]
      },
      {
        "title": "06 詳細精査 / DETAIL REFINEMENT",
        "elements": ["ラベル付き全身レンダリング 2 点", "円形クローズアップ 4 点"]
      },
      {
        "title": "07 表情設定 / EXPRESSION SHEET",
        "elements": ["3D レンダリングされた頭部の表情 11 点"]
      },
      {
        "title": "08 ポーズライブラリ / POSE LIBRARY",
        "elements": ["全身 3D レンダリングポーズ 9 点"]
      },
      {
        "title": "09 ターンアラウンドビュー / TURNAROUND VIEW",
        "elements": ["全身 3D レンダリング 5 点", "対応する線画ビュー 5 点"]
      },
      {
        "title": "10 色彩開発 / COLOR DEVELOPMENT",
        "elements": ["5 色パレット 5 行", "色彩心理テキスト"]
      },
      {
        "title": "11 素材仕様 / MATERIAL SPECIFICATION",
        "elements": ["5 つのテクスチャスウォッチ", "プロパティスライダー", "4 つの製造アイコン"]
      },
      {
        "title": "12 色彩適用 / COLOR APPLICATION",
        "elements": ["カラーバリエーションレンダリング 4 点", "明暗レンダリング 2 点", "コントラスト評価円 4 点"]
      },
      {
        "title": "13 構造ガイド / CONSTRUCTION GUIDE",
        "elements": ["ジオメトリおよびグリッド用線画図 2 点"]
      },
      {
        "title": "14 デザインシステムルール / DESIGN SYSTEM RULES",
        "elements": ["最小サイズアイコン", "クリアスペース図", "使用例 4 点"]
      },
      {
        "title": "15 アセットバリエーション / ASSET VARIANTS",
        "elements": ["サイズバリエーション 3 点", "線画バリエーション 3 点", "簡略化されたフラットな頭部 3 点"]
      },
      {
        "title": "16 デジタルアプリケーション / DIGITAL APPLICATIONS",
        "elements": ["アプリ用アイコン 1 点", "SNS 用アバター 2 点", "UI 要素", "3 ステップのアニメーションサイクル"]
      },
      {
        "title": "17 実物アプリケーション / PHYSICAL APPLICATIONS",
        "elements": ["ぬいぐるみモックアップ", "パッケージモックアップ", "グッズモックアップ", "店舗外観モックアップ"]
      },
      {
        "title": "18 最終メインビジュアル / FINAL RENDERING",
        "elements": ["お茶を持ったマスコットの高解像度 3D レンダリング", "ロゴ", "ファイル形式リスト"]
      }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="プロダクトマーケティング - 18 パネル構成 マスコットブランドアイデンティティドキュメント - Image 1">
</div>

#### 📌 詳細

- **作者:** [Lee Colin](https://x.com/Colin_Leeee)
- **ソース:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **公開日:** 2026年4月16日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13819)**

---

### No. 90: プロダクトマーケティング - アニメ風侍ゲーム広告ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

スーツ姿の剣士 2 名、巨大な侍メカ、ゲームプレイ UI、QR コード、アプリストアへのダウンロード誘導など、アプリプロモーション用の派手な縦型モバイルゲーム広告。

#### 📝 プロンプト

```
光沢のあるアニメアクションスタイルで、ドラマチックなサイバー侍ファンタジーの美学と、高密度でプレミアムなガチャ RPG プロモーション構成を特徴とする、インパクトの強い縦型モバイルゲーム広告ポスターを作成してください。メインシーンでは、現代的な黒のビジネススーツを着た 2 名の若い男性ファイターが前景で攻撃的にしゃがみ込み、それぞれが視聴者に向かって刀を抜いています。2 名ともスタイリッシュな金髪で、鋭くハンサムな顔立ち、白いドレスシャツ、青いネクタイを着用し、激しいアクションポーズをとっており、遠近法で強調された手と刀が前景下部を占めています。片方の刀の柄の近くには青いリボンが結ばれています。彼らの背後、中央には、豪華な金の角、層状のメタリックな青黒い鎧、光る青い目、背中に納刀された剣を持ち、守護神のように配置された巨大な装甲メカ侍を配置してください。鮮やかなネオン街と、エレクトリックブルー、バイオレット、マゼンタ、ゴールドのエネルギーバーストを背景に使用し、光の筋、火花、花びら、斬撃エフェクト、墨絵の爆発テクスチャを加えてください。右上に、太い白の日本語テキストで「この刃で、未来を斬り拓け。」と書かれた縦型の黒い筆文字バナーを 1 つ追加してください。中下部には、太い筆の質感と黒い影を持つ巨大な金の日本語カリグラフィーの見出しで「切り捨て御免」と書き、ほぼ全幅にわたって配置してください。左下には、金の枠で囲まれたゲームプレイのスクリーンショットパネルを 1 つ埋め込み、赤い日本庭園の前での夜の戦闘、戦闘中のプレイアブルな剣士 1 名、複数の敵、5324、5329、6132 を含む浮遊するダメージ数値、左側の仮想ジョイスティック、垂直および下部に配置された合計 5 名のキャラクターポートレート、右側の 3 つの円形スキルボタン、上部の HUD に 01:28 頃のタイマーと WAVE 3/3 を表示してください。右下には、白い正方形の枠内に大きな白黒の QR コードを 1 つ配置してください。その下と横に、青い縁取りの白い太字で「今すぐダウンロード」という日本語テキストを追加してください。最下部には、左側に App Store、右側に Google Play という公式スタイルのストアバッジを 2 つ含めてください。全体的な外観：超高精細、洗練されたキーアート、ダイナミックな遠近法、メタリックなハイライト、シャープなセルシェーディングのアニメレンダリング、プレミアムなモバイルゲームマーケティングポスター、激しいアクションエネルギー、映画のようなライティング、レイヤー化された UI 重視のプロモーションレイアウト。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="プロダクトマーケティング - アニメ風侍ゲーム広告ポスター - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="プロダクトマーケティング - アニメ風侍ゲーム広告ポスター - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="プロダクトマーケティング - アニメ風侍ゲーム広告ポスター - Image 3">
</div>

#### 📌 詳細

- **作者:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **ソース:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14432)**

---

### No. 91: プロダクトマーケティング - モノクローム Infra ブランドキットボード

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

架空のインフラテックブランド向けの、洗練された白黒のブランドガイドラインおよびグッズプレゼンテーションボード。ピッチデッキ、ブランディングのショーケース、プロフェッショナルなデザインモックアップに最適です。

#### 📝 プロンプト

```
{"type":"モノクロームブランドキットおよびグッズプレゼンテーションボード","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"私たちは、AI 時代の基盤となるインフラを構築するビルダーを支援します。","campaign_line":"[ 次の時代を築く。ゼロから。 ]","version":"バージョン 1.0"},"style":{"overall":"スイスデザインに着想を得たクリーンなブランドガイドラインシート、ミニマルなインダストリアルテックの美学、黒・白・グレーのみを使用、オフホワイトの紙の背景、シャープなスタジオ製品の切り抜き、繊細な影、精密なグリッドレイアウト、編集デザイン風のプレゼンテーション","mood":"プロフェッショナル、プレミアム、未来的、インフラストラクチャ重視"},"layout":{"header":{"left":"A16Z INFRA / ブランドキット & グッズ","right":"バージョン 1.0","divider":"破線の水平線"},"sections":[{"title":"01 アイデンティティ","position":"左上","count":3,"labels":["大型ロゴタイプ","ブランドステートメント","ブラケット付きキャンペーンライン"]},{"title":"02 パレット","position":"右上","count":4,"labels":["ウォームオフホワイト","ブラック","チャコール","ミュートグレー"]},{"title":"03 タイポグラフィ","position":"パレット右下","count":2,"labels":["プライマリ -- 等幅フォント","セカンダリ -- サンセリフ"]},{"title":"06 グッズ","position":"下部 2/3","count":16,"labels":["黒パーカー（前面）","黒パーカー（背面）","オフホワイト T シャツ","黒ベースボールキャップ","オフホワイトトートバッグ","正方形ステッカー/カード 6 枚セット","黒スパイラルノート","黒マグカップ","黒ウォーターボトル","黒ジップポーチ","携帯型レトロゲーム機","マイクロビルドボックスセット","キーボードキットケース（開）","クラウドキーキャップピン","スタックキューブキーキャップピン","長方形ブランドパッチピン"]}],"footer":{"left":"A16Z INFRA / ブランドキット","right":"© 2024 A16Z INFRA. ALL RIGHTS RESERVED.","divider":"破線の水平線"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"角をカットした非常に大きなカスタム幾何学的ブロックワードマーク、太い黒のレタリング、2 行積み"}},"palette":{"swatches":[{"name":"ウォームオフホワイト","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"ブラック","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"チャコール","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"ミュートグレー","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"プライマリ -- 等幅フォント","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"セカンダリ -- サンセリフ","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}} ,"swag":{"items":[{"name":"パーカー前面","color":"ブラック","print":"胸元に小さなロゴ"},{"name":"パーカー背面","color":"ブラック","print":"BUILDING THE INFRASTRUCTURE LAYER OF AI と記された複数行のマニフェストリスト、点線のガイドライン付き。カテゴリ：SYSTEMS, TOOLS, DATA, CLOUD, SECURITY, NETWORKS, DEVELOPER TOOLS"},{"name":"T シャツ","color":"オフホワイト","print":"中央に大きなロゴ"},{"name":"ベースボールキャップ","color":"ブラック","print":"前面に刺繍ロゴ"},{"name":"トートバッグ","color":"オフホワイト","print":"積み重ねられたマニフェストリストと下部に BUILDING WHAT'S NEXT. の文字"},{"name":"ステッカー/カードセット","count":6,"layout":"2 x 3 グリッド","labels":["A16Z INFRA","BUILDING THE INFRASTRUCTURE LAYER OF AI.","EARLY STAGE","SYSTEMS. TOOLS. PLATFORMS.","INFRA","BUILD","DEPLOY","SCALE"]},{"name":"スパイラルノート","color":"ブラック","print":"ロゴと NOTES FOR BUILDING THE FUTURE"},{"name":"マグカップ","color":"ブラック","print":"白ロゴ"},{"name":"ウォーターボトル","color":"ブラック","print":"縦書きの BUILDING WHAT'S NEXT. FROM THE GROUND UP."},{"name":"ジップポーチ","color":"ブラック","print":"ロゴ、ドットグリッドモチーフ、小さな文字で SYSTEMS ONLINE."},{"name":"レトロ携帯ゲーム機","color":"チャコールブラック","screen":"BUILD, DEPLOY, SCALE タブとレベルインジケーター LEVEL 01 を備えたピクセルアートの都市/インフラゲーム画面"},{"name":"マイクロビルドボックス","color":"ブラック","print":"A16Z INFRA, INFRASTRUCTURE MICRO BUILDS, COLLECT.CONNECT.SCALE.","contents":"ボックスの前に展示された黒・グレー・白の小さなモジュール式ビルディングブロックモデル"},{"name":"キーボードキットケース","color":"ブラック","print":"A16Z INFRA KEYPAD SET BUILD. DEPLOY. SCALE.","keys":8,"labels":["INFRA","BUILD","DEPLOY","SCALE",">_","クラウドアイコン","チップ/グリッドアイコン","ネットワーク図アイコン"]},{"name":"クラウドピン","style":"白枠付きの小さな黒いエナメルバッジ"},{"name":"キューブピン","style":"積み重ねられたアイソメトリックキューブを描いた小さな黒いエナメルバッジ"},{"name":"ブランドパッチピン","style":"白ロゴ入りの小さな長方形の黒いエナメルバッジ"}]},"rendering":{"camera":"正面からのフラットレイと正射影製品ボード構成の組み合わせ","lighting":"柔らかく均一なスタジオ照明","background":"明るいウォームオフホワイトのシート","quality":"プロのブランディングプレゼンテーションに適した高解像度商用モックアップ"}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="プロダクトマーケティング - モノクローム Infra ブランドキットボード - Image 1">
</div>

#### 📌 詳細

- **作者:** [Olivier Sauvage](https://x.com/Capitaine)
- **ソース:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14563)**

---

### No. 92: プロダクトマーケティング - 韓国の米飲料パロディ広告ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、有名な政治家風のスポークスパーソンが韓国の缶入り米飲料を宣伝する、ユーモラスでインパクトのあるパロディ飲料広告ポスターを生成します。

#### 📝 プロンプト

```
温かみのある黄金色のスプラッシュを背景に、ドラマチックなコマーシャルライティングを施した、大胆な韓国スタイルの飲料広告ポスターを作成してください。{argument name="celebrity spokesperson" default="ドナルド・トランプのような年配の男性政治家"} を胸から上で描写し、ネイビーのスーツ、白いドレスシャツ、鮮やかな赤のネクタイを着用し、小さなアメリカ国旗のラペルピンを付け、自信に満ちたセールスピッチの表情でカメラを見つめている様子を描いてください。彼の顔は、肌色の平らな長方形の検閲ブロックで隠されています。カメラの近くに強制遠近法で突き出した左手には、韓国の米飲料（シッケ）の黄色いアルミ缶を持たせてください。缶には赤の上下の帯があり、メインの製品テキストとして「비락 식혜」および「Since 1993」が目立つように記載されています。缶には他にも小さな韓国語のコピー、下部付近に甘い米飲料の画像、および容量を示す「238 ml (120 kcal)」というテキストを含めてください。右手はサムズアップをしています。

エネルギッシュなレトロコマーシャルの構図を使用し、彼の背後には甘い米飲料が飛び散る様子と水滴、輝く黄金のハイライトを加え、少しローアングルからの英雄的なフレーミングにしてください。上部には、3 つの明確な見出しテキストグループを含めてください。左上に手書き風の小さな黒いスローガン「전통의 맛, 한국의 DRINK!」、中央にダークブラウンから黒のダメージ加工された太い韓国語の巨大な見出し「걸죽는 땐?」と鮮やかな赤の「비락 식혜!」、右上に「비락」というブランドロゴと、その下に小さな赤い文字で「Since 1993」を配置します。2 つの吹き出しバッジを追加してください。左側には小さな王冠アイコンが付いた黄色の円形シールで「대한민국 국민음료 No.1」、右側には手書きの韓国語「한국이 만든 맛있는 전통!」と赤い英語の「I LOVE IT!」が書かれた白い吹き出しを配置します。

下部の前景には 2 つの食品要素を配置してください。左側には甘い米飲料と浮いた米粒が入った真鍮のボウル、右側には白米が盛られた木製のボウルを置きます。中央下部には、2 行の大きな筆文字スタイルのプロモーションテキストを追加してください。1 行目は白で「달콤하게! 시원하게!」、2 行目は白と黄色を混ぜて「속까지 시~원하게!」とし、エネルギッシュな黄色のアンダーラインを引きます。最下部には、韓国語のキャプション付きの 3 つの円形アイコンを含めてください：「국내산 쌀 엄선된 재료」、「시원하게 갈증해소」、「부드러운 단맛 속 편한 식혜」。右下隅には、小さな免責事項テキスト「연출된 이미지입니다」を追加してください。全体的に光沢があり、誇張された、面白く、バイラルなパロディ印刷広告のように説得力のある外観に仕上げてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="プロダクトマーケティング - 韓国の米飲料パロディ広告ポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **ソース:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14555)**

---

### No. 93: プロダクトマーケティング - 韓国のスポーツドリンクのセレブリティ広告ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、セレブリティ風のスポークスパーソン、巨大な製品ボトル、そして商業広告用の大胆なプロモーションタイポグラフィを特徴とする、派手な韓国スタイルの水分補給ドリンクのポスターを生成します。

#### 📝 プロンプト

```
光沢のある商業写真スタイルの大胆な韓国飲料広告ポスター。{argument name="spokesperson" default="ドナルド・トランプ似の人物"}がダークネイビーのビジネススーツ、白いドレスシャツ、鮮やかなブルーのネクタイを着用し、正面を向いて立っている。背景は彩度の高い明るい青空で、柔らかい白い雲がいくつか浮かび、右側にはエンパイア・ステート・ビルに似た高層ビルを含む現代的な都市のスカイラインがうっすらと見える。彼は左手に{argument name="product name" default="POCARI SWEAT"}の冷えたペットボトルをカメラに向かってドラマチックに掲げており、極端な遠近法によってボトルが手前で大きく見えるように配置されている。ボトルは結露した透明なプラスチック製で、白いキャップが付き、中の水が見える。深い青色のラベルには「POCARI SWEAT」と大きな白い文字で書かれ、その上に「ION SUPPLY DRINK」という小さな文字がある。ボトル、手、および前景の下部に、エネルギーあふれる凍ったような水しぶきと水滴を加え、新鮮さと水分補給を強調する。左上隅にブランドロゴを配置する：白い文字で「POCARI SWEAT」、その下に曲線の下線マーク。上部には、巨大でかすれた質感の韓国語のヘッドラインテキストを配置し、少し傾けて上半分を埋め尽くすようにする：{argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}。右下のスーツの上には、白と青の韓国語で太字のイタリック体の引用文を追加する：{argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}。左下には、短い韓国語のラベルが付いた3つの円形ベネフィットアイコンを垂直に配置する：水滴アイコンには「수분 보충」、稲妻アイコンには「전해질 보충」、走る人物のアイコンには「빠른 흡수」。コントラストの高い愛国的な青と白のカラーパレットを使用し、ドラマチックな広告照明を当て、ボトルと手にシャープな焦点を合わせ、顔と背景は少し柔らかい焦点にすることで、全体的にエネルギッシュでプレミアムなキャンペーンポスターのような外観に仕上げる。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="プロダクトマーケティング - 韓国のスポーツドリンクのセレブリティ広告ポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **ソース:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14553)**

---

### No. 94: プロダクトマーケティング - 日本のジャングル・テーマパーク風パロディポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

架空のジャングル恐竜テーマパークを題材にした、映画のような風刺的日本風広告ポスター。パロディキャンペーンや SNS 用のビジュアル、架空のプロモーション用キーアートに最適です。

#### 📝 プロンプト

```
超高精細な日本風パロディ・テーマパーク広告ポスター（縦型）。ドラマチックな夏の旅行広告と高級アトラクションのキャンペーンを融合させたデザイン。背景は鮮やかな青空と点在する雲、右上に輝く太陽が描かれた熱帯のジャングルで、上部にはヤシの葉がフレームのようにあしらわれている。上部には、石の質感を再現した巨大な 3D 日本語見出し「{argument name="headline text" default="ジャンキリア沖縄"}」を配置し、その下に「— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —」という白い日本語のタグラインを添える。中央には、少し傾いた状態で直立する大型の最新スマートフォンを配置し、構図の主役とする。画面には、上部にジャングルのシルエット、中央に大きく太い日本語で「整理券抽選中」と書かれたベージュ色のチケット抽選待ちインターフェースを表示。円形のローディングアイコンを添え、下部には「結果発表まで30分」「※この画面を閉じずにお待ちください」という小さな文字を配置。ステータスバーの時刻は 10:00 とする。スマホの左背後には、ジャングルの茂みから現れ、口を大きく開いて咆哮するリアルで威圧的なティラノサウルスを配置。右側には、精巧な彫刻が施された黄金の入場ゲートを設置し、「プレミアムパス入口」という看板を掲げ、レッドカーペットが敷かれたプレミアム専用レーンへと繋げる。手前から中景にかけては、夏服に帽子、タオル、バックパックを身につけ、日傘や扇風機、水筒を手にした大勢の来場者が長い行列を作っており、猛暑と疲労感を演出する。手前の数人の顔はぼかす。左端には、巨大な風化した石の看板を立て、赤文字で「待ち時間 180分」と大きく記す。左下には、3 段重ねの素朴な木製看板を配置。上段は青い駐車アイコンと「駐車場 2,000円」、中段はスマホアイコンと「アプリ必須 ダウンロードしてね！」、下段は恐竜のシルエットと「当選者だけが冒険へ」という文字を記載。右下には、非常に大きな縦書きの白い筆文字で「待つこと、それが冒険だ。」とコピーを入れる。右下付近には、3 つの小さな円形アイコンを配置し、それぞれ「抽選に選ばれし者だけが、恐竜に会える。」、「スマホの充電が尽きる前に、夢は始まる。」、「プレミアムな近道も、ご用意しました。」という短いプロモーション文を、恐竜、スマホのバッテリー、VIP アクセスを連想させるアイコンと共に添える。最下部中央には、黒い免責事項の帯を配置し、小さな白い文字で「このポスターは架空のパロディ広告です」と記載。全体として、超リアルで映画のような高コントラストなスタイルに仕上げ、テーマパークの過剰な盛り上がり、うだるような暑さ、そして行列待ちという不条理な冒険をユーモラスに表現した、高級感のある商業ポスター風のデザイン。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="プロダクトマーケティング - 日本のジャングル・テーマパーク風パロディポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **ソース:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **公開日:** 2026年4月22日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14545)**

---

### No. 95: プロダクトマーケティング - ディスプレイスタンドをウッドデッキ上に配置

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、参照用の販促ディスプレイを同じ屋外シーンのウッドデッキ上に配置し、リアルな環境広告モックアップを作成するためのものです。

#### 📝 プロンプト

```
提供された参照画像を使用し、庭、池、木々、丘、ウッドデッキの視点はそのまま維持しつつ、装飾看板の設置場所を水上から手前のウッドデッキ上に変更してください。看板を拡大し、カメラの正面により目立つように配置してください。その際、自然な屋外の遠近感、自然光、一貫した影を維持してください。設置構造は、細い緑色のスタンドに支えられた 3 列 × 3 行の計 9 枚の円形看板パネルで構成し、上部のヘッダー看板には「对着镜子笑一场」と記載してください。パネルはより反射率を高めて鏡のようにし、周囲の緑をリアルに映し出しつつ、円形パネル上のキュートな顔のグラフィックと中国語のテキストは保持してください。最終的な結果は、同じディスプレイがシーン内に適切に配置された、リアルな広告モックアップや合成写真のように見える必要があります。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="プロダクトマーケティング - ディスプレイスタンドをウッドデッキ上に配置 - Image 1">
</div>

#### 📌 詳細

- **作者:** [肖师傅](https://x.com/xiaojietongxue)
- **ソース:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14487)**

---

### No. 96: プロダクトマーケティング - ビューティー系モバイルランディングページ 3 選

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

AI で生成したコスメブランドのランディングページコンセプトを SNS で紹介するのに最適な、スマートフォン向けビューティーサイトデザインのプレミアムな 3 面モックアップです。

#### 📝 プロンプト

```
3 台のスマートフォン画面を縦型の 3 面レイアウトで並べた、洗練されたプロモーション用モックアップです。各画面には、リップ製品のモダンなビューティーブランドのランディングページが表示されています。全体的な構成は、モバイルウェブデザインの SNS 投稿を意識した、ミニマルでプレミアムなエディトリアルスタイルです。左側のパネルはソフトなラベンダーからブラッシュへのグラデーション背景で、黒いフレームのスマートフォンに {argument name="brand name" default="Kosas"} のクリーム＆ブラッシュカラーのビューティーサイトが表示されています。パネル上部には、エレガントなセリフ体の小さなテキストで {argument name="left headline" default="Fresh Pout."} と記載されています。スマートフォンの画面上部にはトリミングされたビューティーイメージのクローズアップ、中央には「Lips in their fullest expression.」（「fullest」はイタリックのセリフ体）という大胆な見出し、丸みを帯びたダークカラーの CTA ボタン、リップのクローズアップサムネイル 3 枚、「Plumps」、「Tingles」、「Shines」とラベル付けされた 3 つのベネフィットタブ、そして下部には 5 つのシェードや効果を示すアイコンが並んでいます。中央のパネルはラベンダーからディープバイオレットへのグラデーション背景で、タイポグラフィを強調した 2 台目のスマートフォンが表示されています。その上部にはセリフ体のテキストで {argument name="middle headline" default="Claude Code"} と記載されています。画面上部にはトリミングされたポートレート画像、中央には「LIP PULSE.」という非常に大きく大胆な黒いスタックタイトルと、その下に「is here.」というピンクのイタリック体スクリプトが配置されています。さらに、丸みを帯びたダークボタン、ダークカラーのセクションに「Lips in their fullest expression.」というフレーズ、そして下部には 3 枚× 2 列で構成された 6 つのシェードカードの製品グリッドがあります。右側のパネルはダークネイビーのテクスチャ背景で、ピンクを基調とした 3 台目の EC サイト風スマートフォンが表示されています。中央上部には、等幅フォントの白いテキストで {argument name="right headline" default="GPT Images 2.0"} と記載されています。画面にはブランド名「Kosas」を冠したヒーローセクション、大きなタイトル「The Lip Pulse」、右向きに配置されたピンクのリップグロスのチューブ、小さな特徴アイコン、中央付近に 6 つのリップスウォッチが並ぶシェードストリップ、そして下部にはピンクの製品画像を用いたプロモーションブロックが配置されています。レイアウトは 3 台のスマートフォンを各パネルに 1 台ずつ、すべてが見えるように垂直に配置し、左右対称を維持してください。ハイエンドなコスメキャンペーンの美学、クリーンな余白、セリフ体と大胆なサンセリフ体を組み合わせたファッションウェブ向けのタイポグラフィ、ソフトピンクとクリーム色の UI パレット、繊細な影、そして AI 生成のモバイルウェブサイトコンセプトを披露するのにふさわしい、洗練された製品デザインのプレゼンテーションを心がけてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="プロダクトマーケティング - ビューティー系モバイルランディングページ 3 選 - Image 1">
</div>

#### 📌 詳細

- **作者:** [Serene Gan](https://x.com/ganserene)
- **ソース:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14426)**

---

### No. 97: プロダクトマーケティング - マルチ業界向け日本語広告コラージュ

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

現代的なデザインスタイルで 6 つの異なる業界セグメントを特徴とする、日本語のマルチ業界広告コラージュを生成するためのプロンプト。

#### 📝 プロンプト

```
架空の日本語広告。{argument name="industry list" default="自動車業界（新型車発表）、テーマパーク（新イベント）、化粧品業界（新製品）、出版業界（ベストセラー第 1 位）、飲料業界（新ドリンク）、不動産業界（高級マンション紹介）"} の広告をフィーチャーした 6 分割の横長レイアウト。トップクリエイターによる最新のトレンドスタイルで作成。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="プロダクトマーケティング - マルチ業界向け日本語広告コラージュ - Image 1">
</div>

#### 📌 詳細

- **作者:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **ソース:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **公開日:** 2026年4月21日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14369)**

---

### No. 98: プロダクトマーケティング - ラグジュアリーファッション誌の見開きページ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、高級感のあるブランディング、雑誌のモックアップ、スタイルキャンペーンのビジュアルに最適な、クチュールエディトリアルの見開きページが掲載されたファッションブックのリアルな俯瞰写真を生成します。

#### 📝 プロンプト

```
クリーンなオフホワイトの表面に平らに置かれた、大型のハードカバー雑誌またはアートブックを開いた状態のハイエンドなファッションエディトリアル写真。真上からのアングル。見開き 2 ページには、同じエレガントな女性のポートレートが 2 枚掲載されており、プライバシーに配慮して顔は柔らかい四角いぼかしで隠されています。左側のページでは、{argument name="dress color" default="ソフトスレートグレー"} の構築的な長袖ドレスを着用し、淡い石材またはコンクリートの建築壁の前に立っています。体にフィットしたボディス、ラウンドネックライン、シャープな仕立ての縫い目、誇張された彫刻的なベル型のスカートが特徴です。カメラアングルはわずかに低く、首を長く見せ、彫像のような姿勢を強調しています。右側のページでは、非常に深いオープンバック、幅広のショルダーストラップ、ボリュームのあるフルスカートを備えた {argument name="second dress color" default="ブラック"} のドラマチックなイブニングガウンを着用し、薄暗くムードのある室内のクラシックなパネル壁またはドアの前に立っている後ろ姿が撮影されています。ラグジュアリーファッション誌のスタイリング、ミニマルな構図、落ち着いた色調、柔らかく自然な光、洗練された影、リアルな紙の質感、見える本の綴じ目、わずかに湾曲したページ、鮮明な印刷ディテールを使用してください。全体的な雰囲気は、プレミアムなファッションエディトリアルのような、洗練されたクチュール感のある、映画的で控えめなスタイルです。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="プロダクトマーケティング - ラグジュアリーファッション誌の見開きページ - Image 1">
</div>

#### 📌 詳細

- **作者:** [@levelsio](https://x.com/levelsio)
- **ソース:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14676)**

---

### No. 99: プロダクトマーケティング - モダンなアイスコーヒーの広告デザイン

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

ダイナミックなタイポグラフィを取り入れた、日本市場向けのモダンでスタイリッシュなアイスコーヒー広告を作成するためのプロンプトです。

#### 📝 プロンプト

```
{argument name="product" default="アイスコーヒー"} の広告を作成してください。{argument name="country" default="日本"} らしいスタイリッシュでモダンなデザイン。欧文フォントをダイナミックに配置してください。ターゲット層：{argument name="target" default="10 代〜30 代"}。アスペクト比 1:1。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="プロダクトマーケティング - モダンなアイスコーヒーの広告デザイン - Image 1">
</div>

#### 📌 詳細

- **作者:** [KAWAI](https://x.com/kawai_design)
- **ソース:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **公開日:** 2026年4月21日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14355)**

---

### No. 100: プロダクトマーケティング - ChatGPT 用 処方箋ジョークセット

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

ChatGPT をテーマにした、ユーモアあふれる日本の処方箋と薬のセットを写したリアルな俯瞰写真です。ヘルスケアをテーマにしたパロディ用の小道具や、SNS 向けのコンセプトアートに最適です。

#### 📝 プロンプト

```
温かみのある木製のテーブルの上に、6 つの医療用アイテムが 2 列に整然と並べられた、リアルな製品写真です。ChatGPT 用のユーモアあふれる日本の薬局セットとしてデザインされています。上段：青い枠線と日本の医療用タイポグラフィが印刷された、垂直に立てられた 3 つの白い処方箋袋。下段：対応する袋の下に配置された、2 つの錠剤用ブリスターパックと 1 つの白い粉末が入った小さな透明なジップ袋。紙やパッケージは、本物の日本のクリニックで処方されるもののように、わずかなシワや柔らかな自然光、繊細な影を伴い、本格的な質感で表現してください。

3 つの袋はすべて異なり、全体がはっきりと見えます。左の袋のタイトルは大きな青い日本語で「内用薬」。患者名には「ChatGPT 様」。用法は「1 日 2 回 朝食後・夕食後 1 回 1 錠 7 日分」と記載。薬の名称は「【おくすり】」および「思考安定錠 10mg」。小さな注釈として、思考の暴走や過剰な推論出力を抑制する旨を記載。下部付近の日付は「2025 年 6 月 5 日」。最下部のクリニック名と住所欄には「AI メディカルクリニック」、東京風の住所と電話番号、青い医療用十字アイコンを配置。

中央の袋のタイトルは「内用薬」。患者名：「ChatGPT 様」。用法は「1 日 1 回 就寝前 1 回 1 錠 7 日分」と記載。薬の名称は「【おくすり】」および「幻覚抑制錠 5mg」。小さな注釈として、幻覚傾向を改善する旨を記載。日付は同じく「2025 年 6 月 5 日」。クリニックのフッターと青い医療用十字アイコンも同様。

右の袋のタイトルは「頓服薬」。患者名：「ChatGPT 様」。使用法には、不安、混乱、または過剰な出力時に使用する旨を記載。用法は「1 回 1 包 必要時」と記載。薬の名称は「【おくすり】」および「プロンプト調整散 1g」。小さな注釈として、過学習やプロンプトの混乱を調整する旨を記載。日付は「2025 年 6 月 5 日」。クリニックのフッターと青い医療用十字アイコンも同様。

左下のアイテム：5 錠 × 2 列で計 10 錠の丸い白い錠剤が入った銀色のブリスターパック。各錠剤には「10」の刻印。アルミの縁には「思考安定錠 10mg」の文字が繰り返し印刷されています。その手前には「ChatGPT 様」、用法（1 日 2 回 朝食後・夕食後 1 回 1 錠）、バーコード、日付「2025/06/05」、クリニック名が記載された白い薬局ラベルを配置。

中央下のアイテム：4 錠 × 2 列で計 8 錠の淡い黄色の丸い錠剤が入った銀色のブリスターパック。アルミの縁には「幻覚抑制錠 5mg」の文字が繰り返し印刷されています。その手前には「ChatGPT 様」、用法（1 日 1 回 就寝前 1 回 1 錠）、バーコード、日付「2025/06/05」、クリニック名が記載された白い薬局ラベルを配置。

右下のアイテム：白い粉末が入った小さな透明なジップ袋。表面の白いラベルには「プロンプト調整散 1g」、「ChatGPT 様」、使用法（不安、混乱、過剰な出力時）、用法（1 回 1 包（1g） 必要時）、日付「2025/06/05」、クリニック名を記載。

スタイル：フォトリアルなドキュメンタリー風製品ショット、コメディ調の架空の処方箋小道具デザイン、清潔感のある日本の医薬品グラフィックレイアウト、高い視認性、白・青・銀・ベージュ・木目のニュートラルなカラーパレット、真上からのカメラアングル、手や余計なオブジェクトは含めない、本物のような印刷の質感とパッケージの詳細。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="プロダクトマーケティング - ChatGPT 用 処方箋ジョークセット - Image 1">
</div>

#### 📌 詳細

- **作者:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **ソース:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14537)**

---

### No. 101: E コマースのメイン画像 - 設計図からスタジオ品質の製品レンダリングを作成

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 説明

このプロンプトは、技術的な製品図面を、カタログ、工業デザイン、または E コマース向けのミニマルでフォトリアルなヒーローショットに変換します。

#### 📝 プロンプト

```
提供された参照画像を使用して、技術的なエンジニアリング仕様書を、同じクラゲ型のキッチンツールホルダーのクリーンなスタジオ製品ヒーローレンダリングに変換してください。製品全体のデザイン、半透明の青いドームキャップ、シルバーのベース、そして 4 つの吊り下げ式ツール（スロット付きスパチュラ 1 つ、パスタサーバー 1 つ、スプーン 2 つ）を維持してください。分解図、寸法線、ラベル、表、注釈、タイトルブロックなど、設計図の要素はすべて削除してください。組み立てられた製品のみをフレーム中央に配置し、正面を向け、白の表面を持つミニマルなライトグレーの背景に分離してください。柔らかな拡散光、繊細でリアルな影、そして光沢のある高級感のある素材感で表現してください。現代的な工業デザインのカタログや E コマースの製品写真のように仕上げてください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="E コマースのメイン画像 - 設計図からスタジオ品質の製品レンダリングを作成 - Image 1">
</div>

#### 📌 詳細

- **作者:** [amy](https://x.com/amypretzel)
- **ソース:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14690)**

---

### No. 102: E コマースのメイン画像 - プレミアムブルーベリー製品ポスター

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、スーパーマーケットのブランディング、商品リスト、販促ポスターに適した、洗練された中国風のブルーベリーパッケージ用 E コマース広告を生成します。

#### 📝 プロンプト

```
クリーンな中国の製品広告スタイルで、新鮮なブルーベリーを表現したプレミアム E コマースポスター。メインの被写体として、透明なプラスチック製のクラムシェル容器に入ったブルーベリーを配置。折りたたまれた青い布の上に、画面中央下から右側にかけて斜めに配置し、少し高い位置から見下ろすアングルで撮影する。パッケージは、角が丸い透明な正方形の容器で、中にはダークブルーのブルーベリーが詰まっている。上部には白、ペールブルー、ディープブルーを基調とした大きな不規則な円形のラベルが貼られ、中央に特大のブルーベリーのイラストとエレガントな中国語のブランド名が記載されている。中の果実はより大きく、ふっくらと新鮮に見せ、かすかな水滴をまとわせつつ、ブルーベリーの配置は自然でリアルな状態を保つ。背景は空気感のあるアイスブルーのテーブルトップで、柔らかな雲のようなテクスチャとクールな自然光を表現し、パッケージの周囲にはブルーベリーを散らす。右上と右下の端からぼかした緑の葉を少し入れ、フレッシュで自然な雰囲気を演出する。右上隅には、温かみのある茶色の表面に置かれた元の製品パッケージを真上から見た小さなインセット画像を 1 つ配置する。左側には、中国語の販促タイポグラフィを作成する。大きなダークブルーのカリグラフィーによる見出し {argument name="headline text" default="决茗新"} を配置し、その後に 2 行のコピーを続ける：{argument name="subheadline text" default="新鲜蓝莓 自然之选"} および {argument name="tagline text" default="每一颗都是自然的礼物"}。その下に、短い中国語のキャプションが付いた 3 つの機能アイコンを縦に並べる：自然な熟度を示す葉のアイコン、ジューシーな充実感を示す果実のアイコン、豊富な栄養を示すハートのアイコン。左下付近に、大きな白い筆文字風の中国語テキスト {argument name="product name" default="蓝莓"}、2 行目のサブテキスト {argument name="benefit text" default="膳食纤维+花青素"}、および「125克」と書かれた小さな正味重量のラインを追加する。クールなブルーの色調、鮮明なコマーシャルライティング、プラスチックの蓋に輝くハイライト、プレミアムなスーパーマーケットのパッケージ美学、高精細、そして洗練されたグラフィックデザインと融合したリアルな製品写真を使用する。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="E コマースのメイン画像 - プレミアムブルーベリー製品ポスター - Image 1">
</div>

#### 📌 詳細

- **作者:** [歸藏(guizang.ai)](https://x.com/op7418)
- **ソース:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14655)**

---

### No. 103: E コマースのメイン画像 - ミニマリスト・ファッション・ムードボード・アウトフィット

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

このプロンプトは、ブランド感のあるスタイリングで洗練されたエディトリアル風のコーディネートコラージュを生成します。ファッションのインスピレーションボードやSNS投稿、デジタルワードローブのコンセプト作成に最適です。

#### 📝 プロンプト

```
ライトグレーからホワイトの背景に、細い黒の長方形の枠線をあしらった、ミニマリストな雑誌風のファッションコラージュ。中央にフラットレイ（平置き）スタイルで5つのファッションアイテムを配置。左側に少し重ねて配置された、明るい {argument name="jacket color" default="クリムゾンレッド"} のクロップド丈ジップフロントジャケット（ポインテッドカラー、ゴム裾）。その下に、肩と袖が見えるフィット感のある {argument name="top color" default="ホワイト"} の長袖クルーネックニット。下部には、オフホワイト地に等間隔で大きな黒のドットが配置された、ボリューム感のあるミモレ丈のAラインスカート。左下には、短いトップハンドルと控えめな光沢のあるクロコダイル調の質感が特徴の、構築的な小さな黒のハンドバッグ。右下には、幅広のストラップとシルバーのハトメリング金具が付いた、黒のスクエアトゥ・メリージェーンフラットシューズ。背景の中央には、服の後ろに大きく引き伸ばされた、非常に淡いグレーの大きなタイポグラフィで {argument name="background brand text" default="MANGO"} と記載。レイアウトの周囲には、小さな黒いファッションブランドのロゴを配置：右上に {argument name="top right logo" default="MANGO"} 、ハンドバッグ付近とシューズ付近に「Stradivarius」、スカートの裾に近い左下に「DOLCE & GABBANA」。全体的にバランスが取れたシックで現代的な構成で、柔らかなスタジオ照明を使用。影はなし、またはわずかにソフトな影のみとし、切り抜きエッジは鮮明に。洗練されたSNS向けファッションムードボードの美学を表現してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="E コマースのメイン画像 - ミニマリスト・ファッション・ムードボード・アウトフィット - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="E コマースのメイン画像 - ミニマリスト・ファッション・ムードボード・アウトフィット - Image 2">
</div>

#### 📌 詳細

- **作者:** [虎小象](https://x.com/hx831126)
- **ソース:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14455)**

---

### No. 104: E コマースのメイン画像 - メカニカルキーボード製品ページモックアップ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

プレミアムメカニカルキーボード向けの洗練されたデスクトップ用Eコマース製品ページを生成します。製品デザインのショーケース、ストアフロントのコンセプト、UIモックアップに最適です。

#### 📝 プロンプト

```
{argument name="brand name" default="KeyForge"} というプレミアムメカニカルキーボードブランド向けに、クリーンでモダンなEコマース製品詳細ページを作成してください。背景は白、淡いグレーの区切り線と十分な余白を設けた、高精細なデスクトップウェブサイトのモックアップとして提示します。レイアウトは、上部のナビゲーションバー、左側の製品サムネイルレール、中央の大きな製品ヒーロー画像、右側の購入情報パネルで構成される統一されたストアフロントシーンです。ヘッダーの左端に太字のワードマークを配置し、その横に「Keyboards」、「Switches」、「Keycaps」、「Accessories」、「Sale」、「Blog」、「Support」と書かれた 7 つのナビゲーション項目を並べます。右端には検索、アカウント、カートの 3 つのアイコンを配置し、カートには「1」と書かれた小さな黒い通知バッジを表示します。中央に表示されるメイン製品は、淡いグレーのステージ上で少し高い位置から撮影されたコンパクトな 75% メカニカルキーボードで、シルバーのアルミニウムケース、白とグレーのキーキャップ、ラベンダーパープルのアクセントキー、右上にシルバーのボリュームノブを備えています。左側の垂直ギャラリーには、選択された正面の製品ショット 1 枚、キーボードの斜めからのビュー 1 枚、メカニカルスイッチのクローズアップ 1 枚、キーキャップの質感のクローズアップ 1 枚、円形の再生アイコンが付いた暗いビデオサムネイル 1 枚の、計 5 枚のサムネイルを配置します。右側の製品パネルには、「NEW」と書かれた小さなピル型バッジ、「{argument name="product name" default="KeyForge K75 Pro"}」という太字の大きな製品名、「75% Mechanical Keyboard」というサブタイトル、4.8 の評価と「(126 reviews)」が表示された 5 つ星評価の行、太字で大きく表示された「{argument name="price" default="$129.99"}」という価格とそれに続く緑色の「In Stock」ステータス、そしてプレミアムなパフォーマンス、ガスケットマウント設計、QMK/VIA サポート、RGB について説明する短い 2 文の紹介文を含めます。その下に、「Cherry MX Red」、「Gateron Brown」、「Gateron Blue」、「TTC Gold Pink」とラベル付けされた 4 つのピル型ボタンを持つ「Switch Type」セレクター（最初を選択状態に）、同じく「White / Purple」、「Black / Gray」、「Navy / Blue」とラベル付けされた 3 つのピル型ボタンを持つ「Color」セレクター（最初を選択状態に）、「1」に設定された「Quantity」ドロップダウン、カートアイコン付きの「Add to Cart」と書かれた大きな黒いプライマリボタン、ハートアイコン付きの「Add to Wishlist」と書かれたアウトライン形式のセカンダリボタンを配置します。ボタンの下には、小さなアイコン付きの 3 つのサービスハイライトを表示します。「Free Shipping」（サブテキスト：「On orders over $99」）、「30-Day Returns」（サブテキスト：「Hassle-free returns」）、「2-Year Warranty」（サブテキスト：「Peace of mind」）。下部のコンテンツエリアには、細い線で区切られた 2 カラムのセクションを作成します。左側には「Overview」（選択状態）、「Specifications」、「What’s in the Box」、「Shipping & Returns」、「Reviews (126)」の計 5 つの項目からなる垂直タブリストを配置します。タブの右側には、2 行 3 列の計 6 つの機能ブロックで構成される角丸の白い機能カードグリッドを配置し、それぞれにシンプルなラインアイコン、太字のタイトル、短い説明文（「75% Layout」、「Gasket-Mounted」、「QMK/VIA Support」、「Hot-Swappable」、「RGB Backlighting」、「Premium Build」）を記載します。この下部エリアの右端には、7 つの箇条書きからなる仕様リストを追加します。「Layout: 75% (82 Keys)」、「Switch Type: Cherry MX Red」、「Mounting: Gasket-Mounted」、「Connectivity: USB-C (Wired)」、「Backlight: RGB, South-facing」、「Material: Aluminum Case」、「Dimensions: 322 x 135 x 42 mm」、および最後の項目として「Weight: 1.25 kg」。洗練されたミニマリストの製品デザイン美学、リアルな UI の余白、Inter や SF Pro に似たクリーンなサンセリフ体、柔らかな影、繊細な角丸、モノクロアイコン、そして洗練されたスタートアップスタイルの家電製品プレゼンテーションを使用してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="E コマースのメイン画像 - メカニカルキーボード製品ページモックアップ - Image 1">
</div>

#### 📌 詳細

- **作者:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **ソース:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **公開日:** 2026年4月21日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14449)**

---

### No. 105: E コマースのメイン画像 - Skincare E-commerce Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a clean, clinical web design mockup for a skincare brand featuring a hero image, product shot, and feature highlights.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="E コマースのメイン画像 - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 詳細

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **ソース:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14278)**

---

### No. 106: E コマースのメイン画像 - Men's Skincare Website Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a sleek, dark-themed e-commerce landing page mockup for a men's skincare product, featuring a model, product shot, and feature statistics.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="E コマースのメイン画像 - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 詳細

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **ソース:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14277)**

---

### No. 107: E コマースのメイン画像 - Skincare E-commerce Landing Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a structured e-commerce hero banner for skincare products, featuring a model, product shots, feature icons, and statistic cards.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="E コマースのメイン画像 - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 詳細

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **ソース:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14276)**

---

### No. 108: E コマースのメイン画像 - Beauty Product Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a clean, feminine e-commerce landing page hero section for a beauty product, featuring a model, product shots, and structured marketing copy.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="E コマースのメイン画像 - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 詳細

- **作者:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **ソース:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14274)**

---

### No. 109: E コマースのメイン画像 - Fashion Collection Catalog Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a multi-panel fashion catalog showcasing different products featuring a unified pattern design.

#### 📝 プロンプト

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

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="E コマースのメイン画像 - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 詳細

- **作者:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **ソース:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14241)**

---

### No. 110: E コマースのメイン画像 - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 プロンプト

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="E コマースのメイン画像 - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 詳細

- **作者:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **ソース:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14183)**

---

### No. 111: E コマースのメイン画像 - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 プロンプト

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="E コマースのメイン画像 - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 詳細

- **作者:** [pozitiv4ik](https://x.com/Gc_qube)
- **ソース:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14148)**

---

### No. 112: E コマースのメイン画像 - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 プロンプト

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="E コマースのメイン画像 - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 詳細

- **作者:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **ソース:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **公開日:** 2026年4月20日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14225)**

---

### No. 113: E コマースのメイン画像 - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 プロンプト

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="E コマースのメイン画像 - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="E コマースのメイン画像 - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="E コマースのメイン画像 - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="E コマースのメイン画像 - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 詳細

- **作者:** [阿兰AI](https://x.com/alanlovelq)
- **ソース:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **公開日:** 2026年4月20日
- **言語:** zh

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14134)**

---

### No. 114: E コマースのメイン画像 - ライブ配信コマースのインターフェースモックアップ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

有名人が架空の商品を販売しているモバイルライブショッピングのインターフェースを生成します。チャットオーバーレイや UI 要素も完備しています。

#### 📝 プロンプト

```
{
  "type": "モバイルライブ配信コマースのインターフェースモックアップ",
  "subject": {
    "person": "Elon Musk",
    "clothing": "SPACEX ロゴ入りの黒い T シャツ",
    "pose": "両手でカメラを指し示し、熱心に説明している様子",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "大型ディスプレイ画面",
    "image": "火星の風景、Starship ロケット、ドーム型居住施設",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"火星移住計画\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "75.8 万いいね",
        "follow_button": "フォロー"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "10 万+",
        "close_button": "X"
      },
      "tags": [
        "販売ランキング 1 位",
        "他の配信を見る >"
      ]
    },
    "product_card": {
      "position": "中央右",
      "status": "解説中",
      "image": "火星のドーム型居住施設",
      "title": "{argument name=\"product title\" default=\"火星移住基本セット\"}",
      "price": "{argument name=\"product price\" default=\"¥99.00\"}",
      "action_button": "購入"
    },
    "chat_overlay": {
      "position": "左下",
      "join_alert": "星辰大海 さんが参加しました",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"夢想家: マスクを応援！！🚀\"}",
        "火星の弟: 一人いくらですか？",
        "テックファン: かっこいい！火星に行きたい！",
        "未来はすぐそこに: どうやって申し込むの？",
        "小さなロケット: 🌹🌹🌹",
        "宇宙最強: 詳細を教えて",
        "東方不敗: マスク最高！👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "コメントを入力...",
      "icons_count": 4,
      "icons": ["ショッピングカート", "ギフトボックス", "ハートの惑星", "プラス記号"]
    },
    "floating_reactions": {
      "position": "右下",
      "elements": "浮かび上がるハート、いいね、笑い顔の絵文字のスタック"
    }
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="E コマースのメイン画像 - ライブ配信コマースのインターフェースモックアップ - Image 1">
</div>

#### 📌 詳細

- **作者:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **ソース:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **公開日:** 2026年4月19日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13557)**

---

### No. 115: E コマースのメイン画像 - 夏のビーチでの飲料コマーシャル風ショット

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

ビーチに置かれた缶飲料とグラスの爽やかな商品写真シーンを生成します。カスタマイズ可能な商品名テキストと、空に浮かぶキャッチコピーを含めることができます。

#### 📝 プロンプト

```
風化した木製テーブルの上に置かれた、爽やかな飲料の明るい夏のコマーシャル風商品写真。シャープな手前には、レモンスライス 1 枚とローズマリーの小枝を添えた、黄金色で泡立つ冷たい飲み物が入った背の高いグラスが 1 つあり、その隣には冷たい結露に覆われた銀色のアルミ缶が 1 つ置かれています。缶には、小さな金の星のロゴの下に「{argument name="product name" default="TOKYO HIGHBALL"}」という英語テキストが目立つように配置され、飲料自体のグラフィックと下部付近に「アルコール分 7%」という日本語テキストが記載されています。缶の右側には、カットされたレモンのくさび形が 2 つテーブルの上に置かれています。柔らかくぼかされた背景には、輝くターコイズブルーの海と澄み渡る青空が広がる晴れたビーチの光景が広がっています。背景の左側には、白いノースリーブのトップスと水色のスカートを身にまとい、海を見つめる長い茶髪の若い女性が 1 人立っています。シーンの上の空には、「{argument name="catchphrase" default="夏、これがいい。"}」という日本語テキストが優雅に浮かんでいます。全体的に光が明るく魅力的で、きらめくボケ味とレンズフレアが、完璧な夏の一日の冷たく爽やかな雰囲気を強調しています。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="E コマースのメイン画像 - 夏のビーチでの飲料コマーシャル風ショット - Image 1">
</div>

#### 📌 詳細

- **作者:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **ソース:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **公開日:** 2026年4月18日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14023)**

---

### No. 116: E コマースのメイン画像 - 4 分割広告グリッドコンセプト

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

スキンケア、食品、旅行、テクノロジーの各業界を網羅した、2x2 の日本向け広告グリッドを生成します。

#### 📝 プロンプト

```
{
  "type": "2x2 広告バナーグリッド",
  "layout": "4 つの異なる業界の広告を配置した 4 分割レイアウト",
  "quadrants": [
    {
      "position": "左上",
      "industry": "スキンケア",
      "visuals": "頬に触れるアジア人女性、浮かぶ水滴、白いポンプボトル",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "透明感あふれる、新しいわたしへ。",
        "features_count": 3,
        "features_labels": ["高保湿", "肌荒れ予防", "美白ケア*"]
      }
    },
    {
      "position": "右上",
      "industry": "レストラン・食品",
      "visuals": "粉チーズとパセリをかけたボロネーゼパスタのクローズアップ、ダークで落ち着いた照明",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "期間限定",
        "description": "黒毛和牛のボロネーゼ 〜トリュフの香り〜"
      }
    },
    {
      "position": "左下",
      "industry": "旅行",
      "visuals": "バックパックを背負い、美しい山湖を眺める女性、明るい日差し",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "自然の中で、心が動き出す。",
        "script": "Find your freedom.",
        "banner_details": ["初夏の特別キャンペーン", "6 月 1 日 (土) - 6 月 30 日 (日)", "最大 20% OFF", "今だけの特別プラン多数！"]
      }
    },
    {
      "position": "右下",
      "industry": "SaaS アプリ",
      "visuals": "4 つのスケジュール項目が表示されたタスク管理アプリのインターフェースを持つスマートフォン",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "1 日を、デザインしよう。",
        "features_count": 3,
        "features_labels": ["直感的な操作性", "チームで共有可能", "どこでもアクセス"],
        "bottom_banner": "7 日間無料トライアル実施中！"
      }
    }
  ]
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="E コマースのメイン画像 - 4 分割広告グリッドコンセプト - Image 1">
</div>

#### 📌 詳細

- **作者:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **ソース:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **公開日:** 2026年4月18日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13928)**

---

### No. 117: E コマースのメイン画像 - E-commerce Livestream UI モックアップ

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

プレゼンター、商品ボックス、ライブチャット、プロモーション用オーバーレイを備えた、詳細な中国の E-commerce ライブ配信インターフェースを生成します。

#### 📝 プロンプト

```
{
  "type": "e-commerce ライブ配信スクリーンショットモックアップ",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"Sam Altman に似た白人男性\"}",
    "clothing": "ダークグリーンのクルーネックセーター",
    "action": "片手に黒い商品ボックスを持ち、もう片方の手でそれを指差している",
    "setting": "左側にマイクがある暗いスタジオ、背景にうっすらと「AI」の文字",
    "props": [
      "白い OpenAI ロゴ入りの黒いマグカップ",
      "右側に積み上げられた 4 つの黒い商品ボックス"
    ]
  },
  "product_design": {
    "box_color": "黒",
    "logo": "オレンジのアスタリスクまたはサンバースト",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Anthropic 公式旗艦店",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"より強力な推論・より高い知能\"}",
      "sub_subtitle": "最強のモデル: Opus 4.7 がついに登場！",
      "bullet_points_count": 3,
      "bullet_points": ["超強力な推論能力", "コード生成能力の頂点", "複雑なタスクも簡単に解決"]
    },
    "top_right_live_status": {
      "viewer_info": "ライブ配信中 | 52.8 万人が視聴",
      "promo_banner": "ライブ限定特典 期間限定割引・お見逃しなく",
      "countdown": "カウントダウン 00:09:47"
    },
    "middle_right_price_card": {
      "header": "{argument name=\"product name\" default=\"Claude Opus 4.7\"} ライブ配信限定価格",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/100 万トークン〜",
      "original_price": "通常価格: ¥1.89",
      "button": "今すぐ購入"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "コメントを入力..."
    },
    "bottom_right_banner": {
      "headline": "Altman も推奨！Claude Opus 4.7 をチェック",
      "subheadline": "よりスマートに · より安全に · より確実に",
      "feature_tags_count": 4,
      "feature_tags": ["強力な推論", "コーディングの神ツール", "安全で信頼性抜群", "超高速レスポンス"]
    },
    "floating_elements": [
      {
        "type": "ステッカー",
        "position": "商品ボックスの右中央上",
        "text": "{argument name=\"sticker text\" default=\"史上最強の AI モデル！\"}"
      }
    ]
  }
}
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="E コマースのメイン画像 - E-commerce Livestream UI モックアップ - Image 1">
</div>

#### 📌 詳細

- **作者:** [程序员Left](https://x.com/coder_left)
- **ソース:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **公開日:** 2026年4月18日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13995)**

---

### No. 118: E コマースのメイン画像 - 薬膳チキンスープのラベルデザイン変換

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

販促用の鶏肉ポスターを、特定の薬膳食材が入ったバスケットと調理説明テキストを添えた詳細な製品ラベルへと変換します。

#### 📝 プロンプト

```
REFERENCE_0 をベーススタイルとして使用し、中央の鶏のイラストを維持したまま、薬膳スープミックスの製品パッケージラベルに変換してください。鶏のイラストを右側に配置します。上部のテキストを、大きく太い黒の筆文字の見出し {argument name="main headline" default="元气祛湿 鸡煲汤包"} と、それより小さいサブタイトル {argument name="subtitle" default="吃山林土货 味道当然好!"} に置き換えてください。左側には、6 種類の食材（木の根のスティック、白い立方体、輪切りにした茶色の根、黄色い大豆、乾燥したオレンジの皮の細切り、濃い赤色のナツメ）が入った新しい編みかごを追加してください。これらの食材には、白い文字が書かれた 6 枚の小さな茶色の長方形ラベルを付けてください。鶏の下には、{argument name="ingredients list" default="内含有:五指毛桃、茯苓、土茯苓、黄豆、陈皮、红枣"} というテキストが入った円形のオレンジ色のバッジを追加してください。下部には、調理鍋のアイコン、{argument name="usage instructions" default="用法:把汤料清洗干净放入锅中，加入姜片煮20分钟，后加入鸡肉再煮20分钟即可。"} というテキスト、およびサブスローガン {argument name="bottom slogan" default="天然好料 滋补好汤"} を記載した、オレンジ色の長方形のバナーを作成してください。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="E コマースのメイン画像 - 薬膳チキンスープのラベルデザイン変換 - Image 1">
</div>

#### 📌 詳細

- **作者:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **ソース:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **公開日:** 2026年4月18日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13993)**

---

### No. 119: E コマースのメイン画像 - 格納庫内のスポーツカーと旅客機

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

反射する格納庫の中で、商用旅客機の前に駐車されたスポーツカーのフォトリアルな画像を生成します。

#### 📝 プロンプト

```
巨大な航空機格納庫の手前に駐車された {argument name="car model and color" default="鮮やかなブルーの Alpine A110 R スポーツカー"} を撮影した、高解像度でフォトリアルな商用写真。車にはブラックのカーボンファイバー製ボンネット、ブラックのルーフ、ブラックのアルミホイールが装備され、フロントナンバープレートには「{argument name="license plate text" default="A110 R"}」と記載されています。車のすぐ後ろには、背景を圧倒するようなブルーの尾翼を持つ {argument name="airplane model" default="ホワイトの Airbus A320 商用旅客機"} が配置されています。格納庫の床は非常に光沢のあるコンクリートで、車と飛行機を鏡のように映し出しています。左側の金属壁には「{argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"}」と書かれた看板が掲げられています。格納庫の扉は大きく開かれており、明るい曇り空と遠くの都市の風景が見えます。照明は柔らかく映画のような雰囲気で、両方の車両の滑らかな空力曲線を引き立てています。
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="E コマースのメイン画像 - 格納庫内のスポーツカーと旅客機 - Image 1">
</div>

#### 📌 詳細

- **作者:** [nazca alwave](https://x.com/AlwaveNazca)
- **ソース:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **公開日:** 2026年4月18日
- **言語:** en

**[👉 今すぐ試す →](https://gptimage2api.net/?id=14043)**

---

### No. 120: E コマースのメイン画像 - リアルな VTuber グッズのモックアップ

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 説明

標準的な VTuber ファン向けグッズのリアルな実写写真を生成するための GPT-Image2 用プロンプトです。

#### 📝 プロンプト

```
{argument name="style" default="実写"} スタイルの標準的な {argument name="character type" default="VTuber"} 向け {argument name="items" default="ファングッズ"} を作成してください
```

#### 🖼️ 生成画像

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="E コマースのメイン画像 - リアルな VTuber グッズのモックアップ - Image 1">
</div>

#### 📌 詳細

- **作者:** [WTR](https://x.com/wtry1102)
- **ソース:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **公開日:** 2026年4月17日
- **言語:** ja

**[👉 今すぐ試す →](https://gptimage2api.net/?id=13868)**

