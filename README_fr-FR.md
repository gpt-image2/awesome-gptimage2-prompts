
# 🚀 Prompts GPT Image 2 Géniaux


> 🎨 Une collection de prompts créatifs pour GPT Image 2 d'OpenAI

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Click%20to%20View-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Current-brightgreen)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 Table des matières

- [🤔 Qu'est-ce que GPT Image 2 ?](#-what-is-gpt-image-2)
- [📊 Statistiques](#-statistics)
- [🔥 Prompts en vedette](#-featured-prompts)
- [📋 Tous les prompts](#-all-prompts)

---

## 🤔 Qu'est-ce que GPT Image 2 ?

**GPT Image 2** (codename **"duct-tape"**) is OpenAI's next-generation image model. Community testing highlights a leap in these areas:

- 🎯 **Pixel-Perfect Text Rendering** — Native-quality text in Chinese, English, and Japanese, no typos or warped glyphs
- 🎨 **Cross-Image Consistency** — The same character, style, or IP stays identical across a series, down to the pixel
- ⚡ **Commercial-Grade Illustration** — Illustration output is ready to ship without manual polish
- 🌈 **True Art Style Induction** — Creatively evokes the feeling of a style rather than merely approximating references
- 🔧 **Storyboard & Product Series** — Ideal for storyboards, IP characters, and multi-panel product visuals
- 📐 **Multi-Language Design** — Social cards, banners, and posters with accurate multilingual typography in one shot

📚 **Learn More:** See community testing in our [report summary](docs/FAQ.md)

### 🚀 Intégration Raycast

Certains prompts prennent en charge les **arguments dynamiques** en utilisant la syntaxe [Raycast Snippets](https://raycast.com/help/snippets). Cherchez le badge 🚀 Raycast Friendly !

**Exemple :**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

Lors de l'utilisation dans Raycast, vous pouvez remplacer dynamiquement les arguments pour des itérations rapides !

---

## 📊 Statistiques

<div align="center">

| Métrique | Nombre |
|--------|-------|
| 📝 Total des prompts | **1123** |
| ⭐ En vedette | **6** |
| 🔄 Dernière mise à jour | **jeudi 23 avril 2026 à 01:29:08 UTC** |

</div>

---

## 🔥 Prompts en vedette

> ⭐ Sélectionnés à la main par notre équipe pour leur qualité et créativité exceptionnelles

### No. 1: Affiche en vue éclatée d'un casque VR

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère un schéma en vue éclatée haute technologie d'un casque VR avec des légendes détaillées des composants et un texte promotionnel.

#### 📝 Prompt

```
{
  "type": "affiche de schéma produit en vue éclatée",
  "subject": "casque VR",
  "style": "rendu 3D haute technologie épuré, éclairage studio, accents lumineux",
  "background": "{argument name=\"background color\" default=\"dégradé doux de violet et de bleu\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"Une toute nouvelle réalité, issue d'une toute nouvelle structure.\"}"
  },
  "layout": {
    "centerpiece": "vue éclatée en pile verticale d'un casque VR montrant 9 couches distinctes de composants internes : coque extérieure, capteurs de caméra, carte mère avec puce, lentilles pancake, cadre interne, batteries, sangles latérales, sangle supérieure et coussin de l'interface faciale.",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\nUne puissance de traitement inégalée pour des expériences en temps réel.",
        "Mécanisme IPD réglable\nUn ajustement confortable pour une large gamme d'utilisateurs.",
        "Sangle de tête conçue avec précision\nErgonomie axée sur le confort et la stabilité."
      ],
      "right_side": [
        "Façade\nDesign sophistiqué et équilibre des poids optimal.",
        "Caméras de suivi\nSuivi de position haute précision et reconnaissance de l'environnement.",
        "Lentilles pancake\nDesign ultra-fin offrant un large champ de vision et des images nettes.",
        "Batterie haute performance\nConception énergétique optimisée pour une autonomie prolongée.",
        "Interface faciale souple\nConfort de port optimal, même lors d'utilisations prolongées."
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "{argument name=\"bottom headline\" default=\"L'expérience évolue depuis sa structure.\"}",
        "body": "Chaque pièce intègre une technologie de pointe et une conception minutieuse pour soutenir votre immersion. Le Meta Quest 3 génère une expérience futuriste depuis l'intérieur."
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="Affiche en vue éclatée d'un casque VR - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [wory＠ホッピング中](https://x.com/wory37303852)
- **Source:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13460)**

---

### No. 2: Carte gastronomique illustrée de la ville

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une carte touristique dessinée à la main, style aquarelle, présentant des spécialités culinaires locales numérotées, des points d'intérêt et une légende.

#### 📝 Prompt

```
{
  "type": "infographie de carte illustrée",
  "style": "{argument name=\"art style\" default=\"illustration dessinée à la main à l'aquarelle et à l'encre sur parchemin vintage\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"Chengdu\"} {argument name=\"map title\" default=\"Carte gourmande\"}",
    "mascot": "piment rouge de dessin animé portant des lunettes de soleil et faisant un pouce levé"
  },
  "border": "{argument name=\"border decoration\" default=\"vigne de feuilles vertes et de piments rouges\"}",
  "layout": {
    "background": "papier parchemin beige texturé avec des routes jaunes, des rivières bleues et des zones de parcs vertes",
    "sections": [
      {
        "title": "points d'intérêt",
        "count": 6,
        "illustrations": ["pavillon traditionnel", "monastère traditionnel", "gratte-ciel moderne avec panda qui grimpe", "haute tour de télévision", "porte traditionnelle", "bâtiments industriels"],
        "labels": ["Parc du Peuple", "Monastère de Wenshu", "IFS", "Tour de télévision 339", "Kuanzhai Alley", "Dongjiao Memory"]
      },
      {
        "title": "spots culinaires",
        "count": 12,
        "illustrations": ["mapo tofu", "raviolis à l'huile pimentée", "brochettes en pot", "boulettes de riz gluant", "gâteau aux œufs cuit au four", "fondue chinoise à neuf compartiments", "nouilles de patate douce", "brochettes froides", "plat épicé mélangé", "bol de thé couvert", "dessert à la gelée glacée", "têtes de lapin épicées"],
        "labels": ["1 Chen Mapo Tofu", "2 Raviolis Zhong", "3 Chunxi Road", "4 Kuanzhai Alley · San Da Pao", "5 Jianshe Road · Ye Popo Egg Cake", "6 Yulin Road · Fondue Xiaolongkan", "7 Xiangxiang Alley · Fen aux intestins", "8 Wuhouci Street · Bobo Chicken", "9 Dongjiao Memory · Maojiao Huola", "10 Parc du Peuple · Salon de thé Heming", "11 Rue ancienne de Jinli · Gelée glacée", "12 Tête de lapin Shuangliu"]
      },
      {
        "title": "légende",
        "position": "en bas à droite",
        "count": 5,
        "items": ["point rouge", "maison verte", "arbre vert", "ligne bleue", "double ligne jaune"],
        "labels": ["Lieux gastronomiques", "Sites touristiques", "Parcs et espaces verts", "Rivières et lacs", "Axes routiers principaux"]
      }
    ],
    "centerpiece": "panda géant assis en train de manger du bambou",
    "bottom_right_extras": ["rose des vents vintage avec N, S, E, O", "texte d'avertissement 'Conseil : soyez prudent avec le piment, protégez votre estomac~' avec une icône de piment rouge"]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="Carte gastronomique illustrée de la ville - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [皮皮特](https://x.com/mm_zzm44854)
- **Source:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13515)**

---

### No. 3: Diapositive explicative sur Momotaro dans un style hybride

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt qui combine l'esthétique simple et chaleureuse des illustrations Irasutoya avec la densité d'informations élevée caractéristique des diapositives du gouvernement japonais.

#### 📝 Prompt

```
Créez une diapositive explicative ({argument name="format" default="diagramme ponchi-e"}) pour {argument name="theme" default="Momotaro"} qui fusionne l'atmosphère douce des illustrations "Irasutoya" avec la densité d'informations impressionnante des "diapositives de Kasumigaseki".
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="Diapositive explicative sur Momotaro dans un style hybride - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="Diapositive explicative sur Momotaro dans un style hybride - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [やまもん](https://x.com/yammamon)
- **Source:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **Publié:** 19 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13983)**

---

### No. 4: Maquette d'interface de live stream e-commerce

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une interface de live stream réaliste pour les réseaux sociaux en superposition sur un portrait, incluant des messages de chat personnalisables, des popups de cadeaux et une fiche produit.

#### 📝 Prompt

```
{
  "type": "maquette d'interface de live stream",
  "subject": {
    "description": "portrait de {argument name=\"host name\" default=\"Elon Musk\"}, souriant, portant un t-shirt noir avec un graphique technique blanc",
    "background": "le côté gauche affiche un écran avec le texte '{argument name=\"left background logo\" default=\"SPACEX\"}', le côté droit affiche un '{argument name=\"right background logo\" default=\"logo Tesla T\"}' rouge et une voiture sombre"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "avatar, nom '{argument name=\"host name\" default=\"Elon Musk\"}', sous-texte '556 k likes', bouton rouge 'Suivre'",
      "rank_badge": "icône de pièce d'or avec '1er du classement'",
      "viewer_stats": "3 avatars de spectateurs principaux avec '123 k', '86 k', '57 k', total '687 k', bouton de fermeture 'X'",
      "right_links": "'Plus de lives >', 'Galerie de cadeaux 0/24' avec un tag bleu 'Classique'"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "avatar 'Amateur de technologie', 'envoie un cœur', icône cœur x 1314",
        "avatar 'Océan d'étoiles', 'envoie une fusée', icône fusée x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "badge niveau 37 'Explorateur de l'univers a rejoint le live'",
      "message_count": 7,
      "messages": [
        "Petite Fusée : Musk ! L'avenir est prometteur ! 🚀",
        "future : Quand sortira la Tesla Model 2 ?",
        "Rêveur d'étoiles : SpaceX peut-il aller sur Mars cette année ?",
        "Explorateur IA : Où en est Neuralink ?",
        "Internaute stylé : Bonjour M. Musk !",
        "Mars : C'est la première fois que je regarde votre live, super excité !",
        "Utilisateur123 : Parlez-nous de l'IA, va-t-elle remplacer les humains ?"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "orange 'Vente flash x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"Pick-up électrique Tesla Cybertruck\"}",
      "price": "{argument name=\"product price\" default=\"1 618 000 ¥\"}",
      "button": "bouton rouge 'Acheter'",
      "floating_animation": "cœurs translucides flottant sur le bord droit"
    },
    "bottom_bar": {
      "input_field": "'Dites quelque chose...'",
      "icons": ["smiley", "trois points", "panier", "cadeau", "partager"]
    }
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="Maquette d'interface de live stream e-commerce - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [神经病不想好转](https://x.com/sjbbxhz)
- **Source:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14036)**

---

### No. 5: Combat d'arts martiaux style anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une scène d'action dynamique de style anime montrant deux personnages s'affrontant avec des auras élémentaires dans un dojo traditionnel.

#### 📝 Prompt

```
Une illustration anime hautement dynamique de deux filles engagées dans un féroce combat d'arts martiaux à l'intérieur d'un dojo traditionnel en bois. Au premier plan, une fille avec {argument name="character 1 hair" default="des cheveux noirs en chignon haut avec des rubans rouges"} adopte une posture d'arts martiaux puissante et basse, projetant son poing vers l'avant. Elle porte un {argument name="character 1 outfit" default="haut blanc de style chinois avec des pompons rouges et un pantalon rouge ample"}, avec d'intenses traînées d'énergie rouge tourbillonnant autour de ses membres en mouvement. En plein vol sur la droite, une fille avec {argument name="character 2 hair" default="des cheveux violet clair en doubles chignons"} bondit avec grâce, souriant avec assurance tout en portant une {argument name="character 2 outfit" default="robe vert foncé avec des broderies dorées et des collants noirs"}, accompagnée de traînées d'énergie bleue semblables à de l'eau. L'arrière-plan présente l'intérieur d'un temple rustique en bois avec une enseigne suspendue bien visible portant l'inscription "{argument name="sign text" default="武術会"}". La scène est remplie d'action explosive, de poussière en suspension, de lattes de parquet brisées, d'effets de particules colorées lumineuses et d'un éclairage dramatique en contre-plongée qui détache parfaitement les personnages de l'arrière-plan détaillé.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="Combat d'arts martiaux style anime - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **Source:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13467)**

---

### No. 6: Infographie de l'évolution en escalier de pierre 3D

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Transforme une chronologie évolutive plate en une infographie réaliste en forme d'escalier de pierre 3D, avec des rendus détaillés d'organismes et des panneaux latéraux structurés.

#### 📝 Prompt

```
{
  "type": "infographie de chronologie évolutive",
  "instruction": "En utilisant REFERENCE_0 comme base structurelle, transformez le design vectoriel plat en une infographie 3D hautement réaliste. Remplacez les rampes lisses par des marches en pierre distinctes et améliorez tous les organismes avec des modèles 3D photoréalistes.",
  "style": {
    "background": "{argument name=\"background style\" default=\"papier parchemin texturé vintage\"}",
    "staircase": "{argument name=\"staircase material\" default=\"blocs de pierre texturés réalistes\"}",
    "subjects": "{argument name=\"organism style\" default=\"rendus 3D photoréalistes hautement détaillés\"}"
  },
  "layout": {
    "main_title": "{argument name=\"main title\" default=\"Évolution humaine\"}",
    "sections": [
      {
        "position": "barre latérale gauche",
        "count": 8,
        "labels": ["L0 : Vie unicellulaire", "L1 : Organismes multicellulaires", "L2 : Règne animal", "L3 : Chordés", "L4 : Révolution terrestre", "L5 : Classe des mammifères", "L6 : Évolution des hominidés", "L7 : Ère de l'Homo sapiens"]
      },
      {
        "position": "en haut à droite",
        "title": "Fonctions acquises / Fonctions perdues",
        "description": "Légende avec icônes plus et moins"
      },
      {
        "position": "en bas au centre",
        "title": "Jalons clés de l'évolution",
        "count": 6,
        "description": "Chronologie avec un graphique en silhouette de 6 figures montrant l'évolution du singe à l'homme"
      }
    ],
    "centerpiece": {
      "description": "Escalier de pierre en colimaçon avec 25 marches numérotées présentant des organismes spécifiques.",
      "count": 25,
      "notable_elements": [
        "Marche 07 : Méduse",
        "Marche 09 : Ammonite",
        "Marche 10 : Trilobite",
        "Marche 24 : Humain marchant",
        "Marche 25 : {argument name=\"future evolution concept\" default=\"silhouette cosmique lumineuse avec un point d'interrogation\"}"
      ]
    }
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="Infographie de l'évolution en escalier de pierre 3D - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [知识猫图解](https://x.com/GeekCatX)
- **Source:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13491)**

---

## 📋 Tous les prompts

> 📝 Trié par date de publication (plus récent en premier)

### No. 1: Profil / Avatar - Selfie au miroir en plongée avec poses exagérées

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt testant la cohérence des personnages et les expressions dynamiques dans un selfie au miroir avec une perspective en plongée.

#### 📝 Prompt

```
{argument name="number of people" default="Trois personnes"} devant un miroir en vue plongeante prenant une photo de groupe dans {argument name="pose type" default="des poses exagérées"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="Profil / Avatar - Selfie au miroir en plongée avec poses exagérées - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Source:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **Publié:** 22 avril 2026
- **Langues:** zh

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14341)**

---

### No. 2: Profil / Avatar - Portrait studio monochrome marron en position assise

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait de mode d'intérieur photoréaliste d'une femme assise dans une tenue marron coordonnée, idéal pour l'imagerie éditoriale lifestyle ou vestimentaire.

#### 📝 Prompt

```
Un portrait studio réaliste d'une jeune femme d'Asie de l'Est assise sur une chaise pliante noire simple, cadrée des cuisses à la tête dans une composition verticale. Elle a des cheveux {argument name="hair color" default="brun foncé"} séparés près du centre et attachés en une queue de cheval basse, avec quelques mèches douces près des oreilles, de petites boucles d'oreilles délicates, une peau claire et lisse, et une pose calme et neutre avec les mains posées l'une sur l'autre entre ses genoux. Elle porte un haut court zippé ajusté en maille côtelée de couleur {argument name="top color" default="marron chocolat profond"} avec un col pointu, des manches trois-quarts et une fermeture éclair partiellement ouverte créant un décolleté plongeant, associé à un pantalon droit taille haute dans un {argument name="pants color" default="marron chaud"} assorti. Le style est monochrome ton sur ton, avec une texture de tissu subtile et des contours naturels du corps. L'arrière-plan est un tissu drapé blanc cassé avec des plis légers, éclairé par une lumière de fenêtre diffuse à l'aspect naturel pour un rendu éditorial d'intérieur propre et doux. Photoréaliste, faible profondeur de champ, ombres douces, portrait de mode sobre, décor minimaliste, sujet centré, posture assise détendue, haute définition de la peau et texture du tissu.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="Profil / Avatar - Portrait studio monochrome marron en position assise - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14628)**

---

### No. 3: Profil / Avatar - Portrait photoréaliste en uniforme scolaire devant un sanctuaire

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait photoréaliste soigné d'une jeune femme en uniforme scolaire en extérieur, idéal pour la mode éditoriale, les visuels de personnages ou les portraits IA de style lifestyle.

#### 📝 Prompt

```
Un portrait photoréaliste à mi-corps d'une {argument name="subject" default="jeune femme"} debout en extérieur sous une lumière naturelle vive, cadrée dans une composition verticale. Elle a de longs cheveux {argument name="hair color" default="brun foncé"} lisses et brillants, avec une raie légèrement décentrée, tombant sur ses deux épaules. Elle porte une chemise d'uniforme scolaire blanche à manches courtes impeccable avec un col structuré, une cravate rayée bleu marine et un écusson brodé détaillé sur la poche poitrine gauche représentant une couronne et un emblème héraldique. Posez-la avec un léger angle de trois-quarts et une posture détendue, la tête tournée subtilement sur le côté pour un rendu de photo de mode naturelle et raffinée. Placez-la devant une {argument name="background setting" default="architecture de sanctuaire rouge"} aux piliers rouge vif et aux détails de toit bleu incurvé visibles dans l'arrière-plan flou, en utilisant une faible profondeur de champ et un bokeh crémeux pour garder le sujet parfaitement net. L'éclairage doit être propre, contrasté et flatteur, avec des reflets lumineux sur les cheveux et la chemise, des plis de tissu réalistes, des tons de peau naturels et une esthétique de portrait premium soignée rappelant la photographie commerciale japonaise.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="Profil / Avatar - Portrait photoréaliste en uniforme scolaire devant un sanctuaire - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AIおじさん](https://x.com/AIojisan1952)
- **Source:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14515)**

---

### No. 4: Profil / Avatar - Portrait selfie d'intérieur censuré et mélancolique

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un selfie photoréaliste et élégant d'un jeune homme portant une chemise sombre à col ouvert près d'une fenêtre, idéal pour créer des portraits crédibles pour les réseaux sociaux.

#### 📝 Prompt

```
Un portrait réaliste de style selfie d'intérieur d'un jeune homme d'Asie de l'Est, cadré de la poitrine jusqu'en haut, assis près d'une grande fenêtre moderne dans un appartement en gratte-ciel ou une chambre d'hôtel sous une douce lumière du jour. Il a des cheveux {argument name="hair color" default="noirs"}, épais et légèrement ébouriffés avec une raie au milieu et un volume doux sur le front et les côtés. Sa silhouette est mince, avec un long cou et une peau claire et lisse. Il porte une chemise boutonnée {argument name="shirt color" default="noire"} en coton mat ou en popeline, légèrement oversize, avec les boutons du haut défaits pour créer un col ouvert profond et un style décontracté. L'appareil photo est tenu près du visage dans un angle de selfie naturel, en orientation portrait, cadrant les épaules, la poitrine, le cou et la tête. Son visage est entièrement masqué par un grand bloc de censure rectangulaire flou ou en mosaïque, tandis que les oreilles, les contours de la mâchoire, le cou et les cheveux restent visibles. L'ambiance est sobre, mélancolique et élégante, avec des couleurs neutres atténuées, une douce lumière venant de la fenêtre sur la droite, des ombres légères et un aspect selfie spontané pour les réseaux sociaux. Les détails de l'arrière-plan incluent une section de mur beige sur la gauche, un petit panneau de contrôle mural sombre, une bordure métallique verticale ou le bord d'une lampe, et deux grands panneaux de fenêtre à cadre sombre sur la droite avec un léger flou de la ligne d'horizon urbaine en extérieur. Photo de smartphone photoréaliste, intérieur moderne et épuré, faible profondeur de champ, texture de peau naturelle, contraste subtil, aucun sourire visible en raison du bloc de censure, retouche minimale, selfie personnel élégant et crédible.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="Profil / Avatar - Portrait selfie d'intérieur censuré et mélancolique - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [MathMedix](https://x.com/MathMedix)
- **Source:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14686)**

---

### No. 5: Profil / Avatar - Portrait selfie réaliste chez McDonald's

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un selfie décontracté photoréaliste d'un homme à l'intérieur d'un McDonald's, idéal pour créer des clichés de restaurant crédibles au style réseaux sociaux.

#### 📝 Prompt

```
Un selfie au smartphone très réaliste et décontracté, pris à l'intérieur d'un restaurant McDonald's en Asie, cadré en portrait buste d'un jeune homme assis à une table. L'appareil est tenu légèrement au-dessus de la table, à bout de bras, créant une perspective de selfie naturelle avec un avant-bras s'étendant vers l'objectif. Le sujet porte un t-shirt noir avec un petit logo Tesla blanc sur la poitrine gauche, a des cheveux noirs courts et raides, des montures de lunettes sombres fines partiellement visibles, et pose une main légèrement contre son menton dans une attitude détendue. Son visage est entièrement masqué par un grand bloc de flou rectangulaire et opaque au centre, préservant ainsi son anonymat tout en laissant apparaître les cheveux, les oreilles, les contours de la mâchoire et les branches des lunettes. Au premier plan, en bas à gauche, se trouve 1 gobelet en papier McDonald's blanc avec un couvercle et une paille blanche, coupé par le cadre. L'arrière-plan montre la zone du comptoir avec un éclairage ambiant chaleureux, 1 grand panneau mural rouge sur la gauche arborant les arches jaunes de McDonald's et le slogan blanc « i’m lovin’ it » avec du texte chinois en dessous, 4 panneaux de menu numériques éclairés en haut affichant des burgers, des frites, des menus, des prix et du texte chinois, ainsi que 2 personnes à l'arrière-plan près du comptoir, l'une de dos avec un sac à dos et une autre partiellement visible derrière la caisse. Utilisez une balance des couleurs naturelle, un léger grain d'intérieur, des reflets réalistes, une profondeur de champ faible à modérée et l'aspect spontané d'un cliché de réseaux sociaux non mis en scène.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="Profil / Avatar - Portrait selfie réaliste chez McDonald's - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Source:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14433)**

---

### No. 6: Profil / Avatar - Instantané Instagram de cosplay d'Albedo

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt concis pour générer une photo de cosplay rebelle et expressive dans le style d'une story Instagram.

#### 📝 Prompt

```
Style : Un instantané de story Instagram d'un cosplay de {argument name="character" default="Albedo"} ; Contenu : {argument name="action" default="accroupi au sol face à l'appareil photo, faisant des gestes rebelles exagérés avec les deux mains, levant les yeux au ciel, avec une expression arrogante et dédaigneuse"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="Profil / Avatar - Instantané Instagram de cosplay d'Albedo - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **Source:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **Publié:** 21 avril 2026
- **Langues:** zh

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14347)**

---

### No. 7: Profil / Avatar - Écolière chatte sur le toit au coucher du soleil style anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un portrait cinématographique de style anime d'une écolière avec des oreilles de chat sur un toit au coucher du soleil, idéal pour des visuels nostalgiques, des illustrations de personnages ou des images pour les réseaux sociaux.

#### 📝 Prompt

```
Une illustration anime de haute qualité d'une {argument name="character type" default="écolière avec des oreilles de chat"} penchée sur la rambarde métallique d'un toit d'école au coucher du soleil, vue sous un angle légèrement en contre-plongée, en plan rapproché de trois-quarts. Elle a de longs cheveux {argument name="hair color" default="brun foncé"} fluides avec des reflets doux, de grands yeux gris-brun réfléchissants, des lunettes rondes à monture fine et 2 oreilles de chat duveteuses dépassant de ses cheveux. Son expression est calme, pensive et légèrement timide, les lèvres entrouvertes et le regard doucement tourné vers le spectateur. Elle porte un uniforme scolaire marin japonais avec un haut à manches longues {argument name="uniform color" default="rose"} doux, un col marin gris à rayures blanches, un nœud de foulard rouge vif et une jupe à carreaux partiellement visible, avec 2 bretelles de sac à dos sombres sur ses épaules. La scène est baignée dans un rétroéclairage dramatique de l'heure dorée, avec une lumière chaude intense soulignant ses cheveux, ses oreilles, ses épaules et ses manches, un éclat solaire provenant du coin inférieur gauche et un ciel richement peint de nuages orange et pêche. En arrière-plan, on aperçoit un bâtiment scolaire japonais de 2 étages avec un toit en tuiles rouges et des fenêtres illuminées par le coucher du soleil. Mettez l'accent sur la qualité visuelle des anime haut de gamme nostalgiques du début des années 2000, un trait délicat, des yeux lumineux, des mèches de cheveux détaillées, une composition cinématographique, une faible profondeur de champ, un étalonnage des couleurs chaud et vibrant, un ombrage soigné et une atmosphère sereine et émotionnelle.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="Profil / Avatar - Écolière chatte sur le toit au coucher du soleil style anime - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **Source:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14547)**

---

### No. 8: Profil / Avatar - Femme fantastique embrassant un bélier blanc

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait réaliste de style médiéval-fantastique représentant une femme aux cheveux roux enlaçant un bélier blanc à cornes, idéal pour des illustrations de personnages atmosphériques ou des visuels fantastiques de style éditorial.

#### 📝 Prompt

```
Un portrait vertical photoréaliste et cinématographique d'une femme médiévale ou fantastique avec {argument name="hair color" default="de longs cheveux roux cuivrés"}, vue du buste, enlaçant tendrement un grand bélier blanc. La femme porte une robe ou une tunique en laine vert mousse foncé avec des poignets richement brodés et une lourde cape ou un châle bordé de fourrure sur les épaules, évoquant une esthétique viking ou des hautes terres. Ses cheveux sont épais, ondulés et légèrement ébouriffés par le vent, avec de petites tresses intégrées sur le dessus. Le bélier possède une toison dense, frisée et blanc crème, une expression calme les yeux fermés, et des cornes en spirale proéminentes s'enroulant vers l'extérieur et l'avant. La main de la femme repose tendrement sur le cou du bélier, transmettant chaleur, protection et complicité. L'ensemble se déroule en extérieur dans un paysage accidenté et couvert, avec des collines ou des landes légèrement floues en arrière-plan, un ciel gris froid, une faible profondeur de champ, un éclairage naturel diffus, des détails de texture riches dans les cheveux, la laine, la fourrure et le tissu, une palette de couleurs terreuses et atténuées, un cadrage intime, une peau et des traits d'animaux réalistes. Ajoutez un texte noir dans le coin supérieur gauche indiquant {argument name="corner text" default="GPT Image 2"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="Profil / Avatar - Femme fantastique embrassant un bélier blanc - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **Source:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14619)**

---

### No. 9: Profil / Avatar - Portrait d'idole kawaii rose avec rouge à lèvres

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait étincelant de style idole anime pour des affiches, des visuels de réseaux sociaux ou des illustrations de personnages mignons.

#### 📝 Prompt

```
Un portrait d'idole anime brillant et très détaillé en composition verticale, montrant une mignonne adolescente à mi-corps dans une esthétique kawaii rose onirique. Elle a des cheveux {argument name="hair color" default="rose pastel"} coiffés en une très longue queue de cheval haute et volumineuse avec une frange douce et des mèches bouclées fluides, décorés de multiples petites pinces en forme de cœur et d'épingles à cheveux croisées. Ses yeux sont grands, étincelants et d'un {argument name="eye color" default="vert émeraude"} vif, avec des reflets en forme d'étoile, de longs cils et un éclat légèrement larmoyant. Elle a un blush léger, de petites lèvres brillantes et une expression affectueuse tout en appliquant un rouge à lèvres {argument name="lipstick color" default="rose vif"}, tenant délicatement le tube de rouge à lèvres des deux mains près de sa bouche. Elle porte une robe d'idole gothique lolita à froufrous noire et rose avec de la dentelle, des rubans, des nœuds, des ornements en forme de cœur et des textures étincelantes, ainsi qu'un serre-tête à nœud en dentelle noire avec un cœur en bijou rose, 3 accessoires capillaires visibles sur sa frange, 1 paire de boucles d'oreilles cœurs pendants et 1 ras-du-cou noir avec un petit pendentif cœur. Entourez le personnage d'un arrière-plan rose bonbon brillant et rempli de paillettes, avec du bokeh, des étincelles, des effets de lumière néon douce et une atmosphère de fan d'idole. Ajoutez 5 bulles de texte en forme de cœur dessinées à la main et lumineuses en japonais autour d'elle, avec les inscriptions : "かわいすぎてごめん…♡", "推してくれてありがとうっ♡", "ずーっとだいすきっ♡", "世界でいちばんの推しになってね…♡", et "ずっと一緒だよ？約束ね…♡". Incluez une petite carte photo décorée ou une affiche de la même fille dans l'arrière-plan en haut à droite. Illustration ultra-soignée, scintillement dense, éclairage romantique, reflets brillants, détails de dentelle complexes, arrière-plan à mise au point douce, palette rose saturée, ambiance d'affiche d'idole adorable.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="Profil / Avatar - Portrait d'idole kawaii rose avec rouge à lèvres - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ねね*AIcreator](https://x.com/NeneneAI)
- **Source:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14606)**

---

### No. 10: Profil / Avatar - Pélican minimaliste à vélo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une illustration vectorielle géométrique épurée d'un pélican sur un vélo, idéale pour tester la composition de formes simples ou créer une image ludique de style icône abstraite.

#### 📝 Prompt

```
Une illustration vectorielle minimaliste sur fond gris clair plat montrant un pélican à vélo, dessinée à partir de formes géométriques simples avec d'épais contours gris anthracite. La composition est large et centrée, le vélo occupant les deux tiers inférieurs de l'image et la tête de l'oiseau flottant légèrement au-dessus et en avant du guidon, de manière délibérément abstraite, façon schéma. Le vélo est une silhouette simple de vélo de route noir vue de profil, avec exactement 2 grandes roues, chacune dotée d'une jante épaisse et de 4 rayons visibles formant une croix, une ligne de sol horizontale droite sous les deux roues, un cadre triangulaire, une selle noire courte et des détails simplifiés de pédalier près de l'arrière du cadre. Le pélican est construit à partir d'éléments abstraits épurés : une tête blanche arrondie avec un petit œil circulaire noir, un long bec ouvert pointant vers la gauche composé de 2 parties avec une section supérieure triangulaire orange et une section inférieure en poche rose pâle, une courte courbe sombre sur le dessus de la tête, un petit connecteur cou/corps ovale blanc séparé, un corps arrondi blanc plus grand positionné sur le vélo et une forme d'aile blanche unique inclinée vers le haut sur le dos. Ajoutez exactement 2 formes de pattes orange, longs rectangles étroits inclinés vers le bas depuis le corps vers le cadre du vélo, suggérant que l'oiseau pédale. Gardez les formes intentionnellement épurées et légèrement surréalistes, comme un test de logo ou un gribouillis d'éditeur de code, sans ombrage, sans dégradés, sans textures, sans texte et avec beaucoup d'espace négatif.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="Profil / Avatar - Pélican minimaliste à vélo - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Justin Schroeder](https://x.com/jpschroeder)
- **Source:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14657)**

---

### No. 11: Profil / Avatar - Transformation de portrait : du chat à l'humain

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt convertit une photo de référence de chat en une version humaine photoréaliste tout en préservant la pose, la composition et le décor d'origine pour des portraits ludiques.

#### 📝 Prompt

```
À partir de l'image de référence fournie, transformez le chat en un portrait humain réaliste tout en conservant la même pose allongée, l'angle de vue, le cadrage et le même arrière-plan avec le fauteuil turquoise en peluche. Utilisez le motif de couleur orange et blanc du chat comme inspiration pour le look de la personne : créez une jeune femme au teint clair avec des cheveux roux chaleureux et une expression douce et calme. Habillez-la avec une tenue décontractée confortable : un pull ample en tricot à col en V et un pantalon crème à cordon de serrage, assise naturellement dans le fauteuil avec une posture détendue. Rendu photoréaliste, éclairage intérieur naturel et doux, qualité photo lifestyle éditoriale.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="Profil / Avatar - Transformation de portrait : du chat à l'humain - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Bojan Tunguz](https://x.com/tunguz)
- **Source:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14670)**

---

### No. 12: Profil / Avatar - Portrait studio avec glace à la fraise

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait studio élégant de style célébrité représentant une femme aux cheveux bruns tenant un cornet de glace à la fraise devant son visage, idéal pour l'imagerie éditoriale beauté ou pop-culture.

#### 📝 Prompt

```
Un portrait studio soigné d'une femme glamour aux allures de pop-star, cadrée de la poitrine vers le haut, centrée sur un fond gris neutre et lisse. Elle a des cheveux {argument name="hair color" default="noir de jais"} longs, ondulés et lâchés, avec une raie au milieu, une brillance satinée et un volume doux retombant sur ses deux épaules. Son visage est en grande partie dissimulé derrière le cornet de glace qu'elle tient devant sa bouche et le bas de son visage, créant une composition éditoriale de mode ludique. Elle porte un débardeur blanc côtelé à larges bretelles et une seule boucle d'oreille étincelante visible. Dans sa main, un cornet gaufré surmonté d'une grosse boule de glace à la fraise rose avec des tourbillons de baies rouge foncé et une texture légèrement fondante. Éclairage beauté chaud et flatteur, ombres douces, tons de peau réalistes, photographie de portrait de célébrité haut de gamme, mise au point nette sur la main, le cornet, les cheveux et les épaules, arrière-plan minimaliste, ambiance subtilement sensuelle et chic, cadrage vertical.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="Profil / Avatar - Portrait studio avec glace à la fraise - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Arturo Garrido](https://x.com/arturogarrido)
- **Source:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14594)**

---

### No. 13: Profil / Avatar - Portrait en nuage de points censuré

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un portrait saisissant de style lidar en noir et blanc représentant un homme en costume, composé de denses particules blanches. Idéal pour des visuels technologiques éditoriaux, des thèmes liés à la confidentialité ou une imagerie d'identité futuriste.

#### 📝 Prompt

```
Un portrait monochrome minimaliste composé entièrement de millions de minuscules points blancs formant un nuage de points sur un fond noir profond, montrant un homme adulte, du buste jusqu'à la tête, vêtu d'un blazer sombre formel et d'une chemise à col clair. Le sujet est légèrement décentré vers la droite, faisant face à l'objectif avec une subtile rotation de trois quarts. Ses cheveux courts sont soigneusement peignés et une oreille est nettement définie par des particules denses évoquant un scan lidar. Rendu de la silhouette sous forme de données de scan 3D brut mêlées à une logique de contours topologiques : pointillisme ultra-dense, placement géométrique précis des points, structure en isolignes subtile et modelé net au niveau des cheveux, des revers de veste, du col, du cou et des épaules. Le visage est intentionnellement masqué par un grand bloc rectangulaire vertical de censure, allant du gris foncé au noir, parfaitement centré sur la zone faciale du front jusqu'au-dessous du nez, créant un effet de masque de confidentialité saisissant. Utilisez une texture mate, des bords nets, une mise au point précise, un contraste élevé, sans lueur, sans effet de halo (bloom), sans néon, sans brouillard, sans flou de mouvement et sans aberration chromatique. Ajoutez une petite icône d'étincelle à quatre branches en gris clair dans le coin inférieur droit. L'image globale doit paraître mathématique, médico-légale et futuriste, comme un portrait issu d'un scan lidar haute résolution en 8k.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="Profil / Avatar - Portrait en nuage de points censuré - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="Profil / Avatar - Portrait en nuage de points censuré - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [Harshith](https://x.com/HarshithLucky3)
- **Source:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14408)**

---

### No. 14: Profil / Avatar - Dieu grec chevauchant un lion

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt cinématographique pour générer une image épique d'une personne représentée en dieu grec chevauchant un lion à travers la savane africaine.

#### 📝 Prompt

```
fais-moi ressembler à un {argument name="persona" default="dieu grec"} chevauchant un {argument name="mount" default="lion"} dans les {argument name="setting" default="plaines d'afrique"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="Profil / Avatar - Dieu grec chevauchant un lion - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="Profil / Avatar - Dieu grec chevauchant un lion - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [Max Blade](https://x.com/_MaxBlade)
- **Source:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14326)**

---

### No. 15: Profil / Avatar - Portrait d'une fille anime blonde confuse

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait buste anime simple aux tons pastel d'une fille perplexe portant un pull bleu, idéal pour des avatars, des illustrations de profil ou des personnages décontractés.

#### 📝 Prompt

```
Un portrait anime doux et minimaliste d'une jeune femme mignonne, vue à mi-corps sur un fond gris clair uni, dessiné dans un style pastel épuré avec un trait très fin rappelant le croquis et des couleurs plates et délicates. Elle a de longs cheveux blonds clairs fluides avec des dégradés doux et une longue frange recouvrant partiellement son front, de grands yeux ronds bleu clair, une peau claire et une petite bouche légèrement entrouverte exprimant une légère confusion. Elle porte un haut à manches longues {argument name="clothing color" default="bleu pastel clair"} ample et oversize avec une encolure large et décontractée. Sa pose est légèrement orientée vers le spectateur, une main levée et un index touchant le côté de sa tête comme si elle était perplexe. Placez exactement 1 point d'interrogation bleu flottant près du côté supérieur gauche de sa tête. L'expression doit paraître innocente, distraite et attachante. Gardez la composition centrée, aérée et épurée, sans objets supplémentaires, sans arrière-plan détaillé et sans ombres marquées.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="Profil / Avatar - Portrait d'une fille anime blonde confuse - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="Profil / Avatar - Portrait d'une fille anime blonde confuse - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="Profil / Avatar - Portrait d'une fille anime blonde confuse - Image 3">
</div>

#### 📌 Détails

- **Auteur:** [Torishima / INTP](https://x.com/izutorishima)
- **Source:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14474)**

---

### No. 16: Profil / Avatar - Portrait d'une fille anime bleu pastel

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait en buste minimaliste de style anime d'une jeune fille aux cheveux bleus portant un sweat-shirt bleu clair oversize, idéal pour des avatars, des photos de profil ou des illustrations de personnages doux.

#### 📝 Prompt

```
Un portrait en buste doux de style anime d'une jeune femme mignonne, centrée sur un fond uni blanc cassé chaleureux, dessiné avec un trait délicat et épuré et des couleurs pastel plates. Elle a de très longs cheveux raides {argument name="hair color" default="bleu ciel pâle"} avec des mèches effilées, une frange complète légèrement séparée près du centre, et de grands yeux bleus assortis avec des reflets brillants. Son expression est timide et perplexe, avec les sourcils légèrement relevés, un léger blush rose sur les joues et une petite bouche entrouverte. Elle regarde directement le spectateur tout en touchant légèrement sa lèvre inférieure avec un index dans une pose pensive et hésitante. Elle porte un sweat-shirt oversize ample {argument name="top color" default="bleu clair"} avec des manches longues qui couvrent partiellement sa main. Cadrez l'image du buste vers le haut, avec la tête légèrement inclinée, pour donner une impression douce, innocente et rêveuse. Utilisez une composition minimaliste, sans accessoires, sans objets supplémentaires, sans décor et sans texte. Mettez l'accent sur une palette monochrome bleue, une simplicité aérienne, des contours subtils rappelant le croquis et une esthétique d'illustration japonaise épurée, idéale pour un avatar personnel doux.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="Profil / Avatar - Portrait d'une fille anime bleu pastel - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Torishima / INTP](https://x.com/izutorishima)
- **Source:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14473)**

---

### No. 17: Profil / Avatar - Portrait de selfie miroir d'intérieur luxueux

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un selfie miroir réaliste de style mode représentant une femme dans une robe ivoire ajustée, idéal pour des images lifestyle, des tenues ou du contenu glamour pour les réseaux sociaux.

#### 📝 Prompt

```
Un selfie miroir d'intérieur réaliste d'une jeune femme mince et glamour, debout dans un salon haut de gamme ou une suite d'hôtel à l'éclairage tamisé, photographiée verticalement de la tête jusqu'en dessous des genoux. Elle porte une robe midi moulante couleur crème ou ivoire, avec un drapé élégant et des fronces, dotée d'une encolure asymétrique avec une bretelle croisant diagonalement la poitrine et laissant l'autre épaule nue. Ses cheveux sont longs, brun foncé, légèrement ondulés, avec une raie presque au milieu, tombant sur ses deux épaules. Elle tient un smartphone dans sa main droite devant son visage, le masquant partiellement, le téléphone étant orienté vers un miroir mural ; le téléphone possède une coque sombre avec un motif de nuage rouge. Son bras gauche pend naturellement le long de son corps. Ajoutez des bijoux subtils : 1 collier fin avec un petit pendentif, 1 bracelet ou jonc en argent au poignet droit, et des bagues aux doigts de la main tenant le téléphone. Mettez l'accent sur une silhouette féminine réaliste, une peau lisse, un éclairage ambiant chaud et doux, et une photographie de style éditorial soigné pour les réseaux sociaux. L'arrière-plan doit inclure 1 canapé beige derrière elle, 1 sac à main en cuir marron posé sur le côté droit du canapé, 1 mur d'accent en pierre ou en béton texturé derrière la zone du miroir, et un couloir chaleureux sur la gauche avec 2 œuvres d'art murales encadrées visibles. Utilisez des ombres d'intérieur naturelles, une texture de peau raffinée, des plis de tissu réalistes avec une compression au niveau de la taille et des hanches, une esthétique d'appartement de luxe, une composition épurée et un niveau de détail élevé.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="Profil / Avatar - Portrait de selfie miroir d'intérieur luxueux - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Danna R.](https://x.com/daaaaanc)
- **Source:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14421)**

---

### No. 18: Profil / Avatar - Selfie réaliste dans un miroir en robe blanche

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un selfie mode photoréaliste dans un miroir, situé dans un appartement chaleureux. Idéal pour des photos de tenues, du contenu lifestyle et des tests de réalisme.

#### 📝 Prompt

```
Un selfie réaliste en intérieur, pris dans un miroir par une jeune femme mince debout dans le salon d'un appartement moderne à l'éclairage chaleureux. Elle porte une robe midi moulante blanc ivoire à une épaule, avec des fronces au niveau du torse et des hanches. Elle a les cheveux châtain foncé, raides, mi-longs et séparés par une raie au milieu. Elle porte des bijoux minimalistes : deux bagues, un bracelet rigide argenté et de petites boucles d'oreilles discrètes. Son visage est masqué par le téléphone avec lequel elle prend la photo d'une main ; le smartphone est protégé par une coque noire décorée de motifs de nuages rouges. Elle se tient légèrement de biais, dans une posture détendue, un bras le long du corps, révélant une silhouette féminine naturelle. La scène est cadrée verticalement, comme un selfie miroir décontracté pour les réseaux sociaux. Derrière elle, un canapé en tissu beige est agrémenté d'un coussin à motifs géométriques gris et d'un sac à main en cuir marron taupe posé sur l'assise. L'arrière-plan comprend un mur d'accent texturé bronze-marron, un sol en carrelage crème brillant, un couloir sombre sur la gauche avec trois cadres décoratifs au mur et des spots encastrés au plafond diffusant une lumière chaude. Éclairage ambiant doux de soirée, tons de peau naturels, tension et plis du tissu réalistes, reflets subtils dans le miroir, esthétique d'appartement haut de gamme, réalisme élevé, texture de peau photoréaliste, perspective de caméra de smartphone.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="Profil / Avatar - Selfie réaliste dans un miroir en robe blanche - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Danna R.](https://x.com/daaaaanc)
- **Source:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14419)**

---

### No. 19: Profil / Avatar - Portrait de luxe en robe à Santorin

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait vertical photoréaliste de mode et de voyage représentant une femme glamour en robe blanche posant à Santorin, idéal pour des images de vacances de luxe, de lifestyle ou éditoriales.

#### 📝 Prompt

```
Un portrait glamour de mode et de voyage d'une {argument name="woman" default="femme blonde"} assise sur un rebord en pierre ensoleillé surplombant la caldeira à Santorin, en Grèce, avec des bâtiments blanchis à la chaux à flanc de falaise descendant vers une mer bleu profond et des îles volcaniques escarpées au loin. Elle porte une robe dos nu ivoire fluide avec un décolleté très plongeant, des découpes latérales, une taille froncée avec un détail d'anneau circulaire et un tissu plissé doux drapé sur ses genoux. Ses cheveux sont longs, ondulés et {argument name="hair color" default="blond doré"}, coiffés librement sur ses épaules. Ajoutez des colliers délicats superposés, dont un petit pendentif et une croix en argent, ainsi qu'un bracelet ou une montre à un poignet. Placez une église grecque blanche classique avec un dôme {argument name="dome color" default="bleu"} vif en arrière-plan en haut à droite, et encadrez le côté droit de l'image avec des bougainvilliers {argument name="flower color" default="rose magenta"} éclatants en pleine floraison. L'éclairage est celui d'un soleil méditerranéen de midi, brillant avec des reflets nets, un éclat de peau doux et une légère profondeur de champ qui garde la femme nette tandis que l'architecture en arrière-plan et la mer sont légèrement adoucies. La composition est verticale, élégante et inspirante, avec la femme légèrement centrée sur la droite, le torse visible jusqu'à la jupe fluide, et le littoral pittoresque s'étendant sur la moitié gauche du cadre. Ajoutez un petit texte noir dans le coin supérieur gauche indiquant {argument name="corner text" default="GPT V2"}. Esthétique de vacances de luxe photoréaliste, haut niveau de détail, couleurs naturelles, ambiance de voyage éditoriale pour Instagram.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="Profil / Avatar - Portrait de luxe en robe à Santorin - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Ed](https://x.com/Eduardopto)
- **Source:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14428)**

---

### No. 20: Profil / Avatar - Portrait style film Fujifilm japonais

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt incroyablement détaillé pour générer des portraits de haute qualité à l'esthétique Fujifilm, avec une ambiance matinale douce, naturelle et intime.

#### 📝 Prompt

```
Vertical 9:16 — portrait {argument name="film style" default="style film Fujifilm japonais"}, sujet unique

Esthétique argentique Fujifilm (rendu Pro 400H / Superia), tons pastel doux, léger décalage vert-magenta, faible contraste, dégradé de hautes lumières délicat, grain de film fin, halo subtil

intérieur au petit matin près d'une fenêtre, rideaux légers, lumière du jour fraîche

{argument name="subject" default="jeune idole japonaise"}, maquillage naturel minimaliste, texture de peau fraîche et douce

tenue : chemise oversize avec short ample, style homewear décontracté, pudique

cheveux : légèrement décoiffés, volume naturel, effet « réveil »

pose : assise au bord du lit ou près de la fenêtre, corps légèrement penché en avant, épaules détendues ; une main tenant délicatement une petite fleur ou un tissu, l'autre au repos naturel

expression : regard doux, légèrement ensommeillé, calme et naturel

éclairage : {argument name="lighting" default="lumière douce du matin"}, diffus, ombres légères

ambiance : calme, fraîche, moment quotidien intime

qualité : ultra-réaliste, grain de film, légère douceur, imperfections naturelles
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="Profil / Avatar - Portrait style film Fujifilm japonais - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [BubbleBrain](https://x.com/BubbleBrain)
- **Source:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14301)**

---

### No. 21: Publication sur les réseaux sociaux - Grille de 4 bannières publicitaires numériques japonaises

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une grille 2x2 de bannières publicitaires numériques japonaises distinctes pour le voyage, les soins de la peau, la gastronomie et l'éducation en ligne.

#### 📝 Prompt

```
{
  "type": "Grille 2x2 de bannières publicitaires numériques japonaises",
  "layout": {
    "structure": "4 quadrants égaux",
    "quadrants": [
      {
        "position": "en haut à gauche",
        "theme": "Voyage",
        "subject": "Un couple se tenant la main sur une plage de sable blanc, regardant l'eau turquoise de l'océan sous un ciel bleu éclatant.",
        "elements": ["fleur d'hibiscus rouge dans le coin inférieur gauche"],
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
          "descriptions": ["avion", "bâtiment d'hôtel", "voiture"]
        }
      },
      {
        "position": "en haut à droite",
        "theme": "Soins de la peau",
        "subject": "Portrait en gros plan d'une jeune femme à la peau éclatante et rosée, les yeux fermés, touchant doucement ses joues.",
        "elements": [
          "fond dégradé rose doux",
          "effets dynamiques d'éclaboussures d'eau",
          "pot de cosmétique rose étiqueté '{argument name=\"skincare product name\" default=\"LUMIÈRE\"} Brightening Gel'"
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
          "style": "circulaire doré",
          "labels": ["毛穴ケア", "高保湿", "ハリ・ツヤ"]
        }
      },
      {
        "position": "en bas à gauche",
        "theme": "Gastronomie",
        "subject": "Steak épais tranché, cuit à point, grésillant sur une plaque de cuisson sombre.",
        "elements": [
          "chips d'ail",
          "brin de romarin",
          "fond sombre avec fumée et braises incandescentes"
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
          "style": "circulaire rouge",
          "labels": ["A4 A5等級"]
        }
      },
      {
        "position": "en bas à droite",
        "theme": "Éducation en ligne",
        "subject": "Jeune homme en chemise bleue étudiant à un bureau, écrivant dans un carnet à côté d'un ordinateur portable ouvert.",
        "elements": ["éclairage intérieur lumineux", "environnement de bureau"],
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
          "style": "circulaire bleu",
          "labels": ["受講者数 10万人 突破！"]
        },
        "icons": {
          "count": 2,
          "descriptions": ["smartphone", "livre ouvert"]
        }
      }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="Publication sur les réseaux sociaux - Grille de 4 bannières publicitaires numériques japonaises - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **Source:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13531)**

---

### No. 22: Publication sur les réseaux sociaux - Planche d'autocollants mignons de chaton noir style japonais

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Une planche de 15 autocollants représentant un chaton noir expressif avec des expressions japonaises, idéal pour des stickers de chat, des concepts de tampons LINE ou des visuels pour réseaux sociaux.

#### 📝 Prompt

```
{"type":"illustration de planche d'autocollants mignons","subject":{"species":"chaton noir","style":"adorable style chibi, look anime-cartoon doux et pictural, grands yeux ronds brun ambré, petit museau, oreilles expressives, fourrure duveteuse noir charbon avec des reflets brun chaud, contour épais et net"},"layout":{"background":"blanc uni","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"ligne 1 col 1","count":1,"labels":["pose joyeuse et reconnaissante avec les deux pattes jointes sur la poitrine, bouche ouverte souriante, pétales de cerisier roses autour du chat"]},{"title":"02. おつかれさま！","position":"ligne 1 col 2","count":1,"labels":["chat détendu et satisfait tenant une tasse verte avec un emblème en forme de patte, yeux fermés, petite vapeur, lignes d'accentuation jaunes festives"]},{"title":"03. 了解です！","position":"ligne 1 col 3","count":1,"labels":["chaton debout levant une patte en signe d'acquiescement, expression vive et attentive, lignes d'accentuation jaunes au-dessus"]},{"title":"04. ＯＫ！","position":"ligne 1 col 4","count":1,"labels":["chaton faisant un clin d'œil et un geste OK avec une patte, léger sourire, lignes d'accentuation jaunes"]},{"title":"05. はーい！","position":"ligne 1 col 5","count":1,"labels":["chaton enthousiaste faisant coucou d'une patte, bouche ouverte souriante, lignes d'accentuation jaunes"]},{"title":"06. いいね！","position":"ligne 2 col 1","count":1,"labels":["chaton faisant un clin d'œil et un pouce levé, petit cœur rose à côté, lignes d'accentuation jaunes"]},{"title":"07. がんばる！","position":"ligne 2 col 2","count":1,"labels":["chaton déterminé avec les pattes serrées et un regard féroce, entouré de flammes orange stylisées"]},{"title":"08. なんとかなる！","position":"ligne 2 col 3","count":1,"labels":["chaton confiant et serein, yeux fermés et poitrine légèrement gonflée, fleurs roses flottant autour"]},{"title":"09. ごめんね…","position":"ligne 2 col 4","count":1,"labels":["chaton triste et désolé avec les pattes jointes sur la poitrine, yeux tombants, une goutte de sueur bleue"]},{"title":"10. 待ってるね！","position":"ligne 2 col 5","count":1,"labels":["chaton regardant par-dessus un rebord en bois avec les deux pattes visibles, expression expectative, petites lignes de mouvement des deux côtés"]},{"title":"11. おやすみなさい","position":"ligne 3 col 1","count":1,"labels":["chaton endormi en boule sur un coussin rose, lettres ZZZ bleues, croissant de lune et petites étoiles au-dessus"]},{"title":"12. いってきます！","position":"ligne 3 col 2","count":1,"labels":["vue arrière d'un chaton s'éloignant joyeusement avec une patte levée, portant un sac à dos vert avec un écusson en forme de patte et une petite breloque pendante, lignes d'accentuation jaunes"]},{"title":"13. ただいま！","position":"ligne 3 col 3","count":1,"labels":["chaton de face avec les deux pattes levées haut, sourire joyeux, marques d'étincelles dorées autour"]},{"title":"14. よろしくね！","position":"ligne 3 col 4","count":1,"labels":["chaton poli assis face à l'avant, sourire doux, lignes d'accentuation jaunes à côté de la tête"]},{"title":"15. 大好き！","position":"ligne 3 col 5","count":1,"labels":["chaton satisfait serrant un gros cœur rose, yeux fermés, plusieurs petits cœurs roses flottant autour"]}],"spacing":"espacement régulier avec de généreuses marges blanches"},"rendering":{"quality":"détails élevés","lighting":"éclairage studio doux et uniforme","color_palette":"fourrure noire, yeux brun chaud, cœurs et fleurs roses, marques d'accentuation jaunes, accessoires verts, décorations pastel minimales","mood":"amical, sain, prêt pour des autocollants, pack pour application de messagerie","composition":"chaque autocollant est isolé et centré dans sa propre cellule avec du texte japonais en gras au-dessus"}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="Publication sur les réseaux sociaux - Planche d'autocollants mignons de chaton noir style japonais - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Source:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14490)**

---

### No. 23: Publication sur les réseaux sociaux - Portrait spontané en boutique dans les tons marron

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une photo lifestyle verticale réaliste d'une femme dans une boutique aux tons chauds, idéale pour la mode, le commerce de détail ou l'éditorial sur les réseaux sociaux.

#### 📝 Prompt

```
Une photo spontanée et photoréaliste au format vertical d'une jeune femme d'Asie de l'Est, debout dans une boutique ou un magasin de parfums d'intérieur aux tons chauds, prise en légère plongée sur le haut de son corps et son torse. Elle a les cheveux {argument name="hair color" default="brun foncé à noir"} attachés en une queue-de-cheval basse avec quelques mèches lâches près du visage, et elle tient une petite tasse ou un pot de bougie blanc crème près de sa bouche d'une main. Elle porte un haut à manches longues zippé et côtelé très ajusté de couleur {argument name="outfit color" default="marron chocolat"}, partiellement zippé, associé à un pantalon taille haute assorti dans le même ton marron pour un look monochrome. Sa pose est décontractée et légèrement penchée, l'autre bras étant relâché derrière son dos, ce qui donne à l'image une impression de cliché lifestyle pris sur le vif. Les étagères du magasin autour d'elle sont en bois et remplies de nombreux pots de bougies en verre et de petits contenants, légèrement floutés en arrière-plan et sur le côté gauche du cadre. Utilisez un éclairage intérieur chaud, une faible profondeur de champ, une texture de peau réaliste, des reflets subtils sur les cheveux, une pose de main naturelle et une atmosphère artisanale et chaleureuse. Composez l'image avec un cadrage serré à mi-corps ou en pied en orientation portrait, le sujet étant centré et l'arrière-plan incliné en diagonale pour renforcer la perspective spontanée. Style photographique : réaliste, très détaillé, bokeh doux, cliché de boutique, rendu d'objectif 35 mm, étalonnage des couleurs naturel.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="Publication sur les réseaux sociaux - Portrait spontané en boutique dans les tons marron - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14630)**

---

### No. 24: Publication sur les réseaux sociaux - Portrait avec boîte d'œufs dans une allée d'épicerie

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une photo lifestyle verticale réaliste d'une femme élégante dans une épicerie, tenant une boîte ouverte de six œufs, idéale pour les réseaux sociaux ou des visuels de style éditorial.

#### 📝 Prompt

```
Une photo verticale prise sur le vif au smartphone d'une femme {argument name="woman age" default="jeune adulte"} faisant ses courses dans l'allée d'une épicerie moderne de nuit, cadrée du haut des cuisses jusqu'à la tête dans une perspective rapprochée et légèrement grand-angle. Elle se tient à côté de rayons réfrigérés remplis de légumes et de produits frais colorés, avec des étagères noires brillantes, un éclairage de magasin vif, des surfaces réfléchissantes et un léger bokeh en arrière-plan. Elle tient une boîte d'œufs en carton recyclé ouverte vers l'appareil photo dans sa main gauche, montrant clairement 6 œufs bruns à l'intérieur. Sa main droite est près d'un panier de courses sur roulettes rempli d'articles. Elle a de longs cheveux brun foncé lâchés, et son visage est volontairement masqué par un large flou rectangulaire aux bords doux centré sur le visage. Elle porte un haut court à manches longues, zippé à l'avant, en maille côtelée marron, avec la fermeture éclair partiellement ouverte au niveau de la poitrine, et un pantalon taille haute assorti. La pose est décontractée et assurée, la boîte étant présentée comme l'accessoire central. Photographie réaliste, éclairage intérieur sans flash, faible profondeur de champ, texture détaillée de la peau et du tissu, reflets naturels, contraste élevé, esthétique lifestyle tendance, touche éditoriale subtile, composition verticale 9:16.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="Publication sur les réseaux sociaux - Portrait avec boîte d'œufs dans une allée d'épicerie - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Source:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14629)**

---

### No. 25: Publication sur les réseaux sociaux - Impératrice d'automne opulente au coucher du soleil

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un portrait fantastique automnal flamboyant et incrusté de joyaux, idéal pour des illustrations spectaculaires et des visuels percutants sur les réseaux sociaux.

#### 📝 Prompt

```
Un portrait fantastique ultra-luxueux d'une femme élégante de profil, légèrement décentrée vers la gauche, portant une coiffe et une robe automnales extravagantes composées de feuilles d'érable rouges, de fleurs rappelant des chrysanthèmes, de filigrane d'or, de pierres précieuses, de pendentifs en cristal et d'ornements en vitrail translucide. Ses longs cheveux sombres tombent sur son épaule, et son visage est en grande partie dissimulé par l'ombre et l'angle, créant une allure mystérieuse et idéalisée. Entourez-la de grands cadres circulaires balayés et de rubans incurvés en verre ambre, rubis et orange transparent, incrustés de joyaux à facettes et de gouttes de cristal réfléchissantes. Remplissez la scène avec exactement 9 feuilles d'érable clairement visibles flottant dans les airs. Définissez l'arrière-plan comme une vallée de montagne rayonnante au coucher du soleil, avec le soleil bas sur l'horizon, des rayons dorés chaleureux, des sommets lointains, une forêt automnale et une rivière réfléchissante en contrebas. L'image entière doit être baignée de tons orange ardent, cuivre, or et écarlate, avec une richesse visuelle extrême, des reflets éblouissants, des détails denses en couches, un bokeh scintillant, un rétroéclairage cinématographique et un niveau de beauté ornée intentionnellement intense et saisissant. Ultra-détaillé, maximaliste, éthéré, rayonnant, haute couture fantastique, textures brillantes, éclairage semblable à des bijoux, composition cinématographique large.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="Publication sur les réseaux sociaux - Impératrice d'automne opulente au coucher du soleil - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AIおじさん](https://x.com/AIojisan1952)
- **Source:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14508)**

---

### No. 26: Publication sur les réseaux sociaux - Publicité pour collage de robot peintre

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un collage promotionnel 2x2 soigné montrant un robot mignon peignant quatre œuvres d'art différentes, idéal pour les annonces d'outils d'image IA et les bannières de réseaux sociaux.

#### 📝 Prompt

```
{"type":"illustration de collage promotionnel","subject":{"main":"robot humanoïde blanc mignon en tant qu'artiste avec de grands yeux bleus brillants","design":"coque blanche lisse et arrondie, articulations mécaniques noires, petit sourire, proportions enfantines amicales, finition brillante","activity":"peignant sur une toile avec un pinceau fin tout en tenant une palette de peintre"},"layout":{"composition":"collage en grille 2x2 avec un grand titre centré en superposition traversant la couture centrale","sections":[{"position":"en haut à gauche","count":1,"label":"3","scene":"robot peignant un paysage marin coloré au coucher du soleil avec un soleil brillant à l'horizon, ciel rose et orange, eau bleue, coups de pinceau expressifs"},{"position":"en haut à droite","count":1,"label":"6","scene":"robot peignant un bouquet de fleurs roses dans un vase bleu, nature morte florale aux tons pastel doux"},{"position":"en bas à gauche","count":1,"label":"4","scene":"robot peignant un paysage luxuriant de cascade verte avec feuillage de forêt et un ruisseau"},{"position":"en bas à droite","count":1,"label":"7","scene":"robot peignant une ligne d'horizon urbaine moderne et lumineuse au coucher du soleil avec de hauts gratte-ciel et des reflets chauds"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"texte sans-serif blanc très grand et gras avec une ombre portée sombre, centré horizontalement sur le collage"}},"environment":{"setting":"intérieur d'un studio d'art chaleureux","background":"étagères floues, cadres, éclairage ambiant chaud, rideaux neutres, plante d'intérieur occasionnelle","easel":"chevalet de table en bois dans chaque panneau","palette":"palette de peintre ronde avec de nombreuses touches de peinture vive dans chaque panneau"},"style":{"rendering":"réalisme 3D cartoon hautement poli","mood":"enjoué, créatif, invitant, rencontre entre la technologie et l'art","camera":"cadrage en plan rapproché, robot sur le côté droit de chaque panneau tourné vers la gauche en direction de la toile","lighting":"lumière intérieure chaude avec des reflets doux et une faible profondeur de champ"}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="Publication sur les réseaux sociaux - Publicité pour collage de robot peintre - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [01net](https://x.com/01net)
- **Source:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14556)**

---

### No. 27: Publication sur les réseaux sociaux - Affiche de protestation style anime pop-art

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche verticale audacieuse style anime représentant un personnage au visage censuré, faisant un signe de paix, avec une bulle de slogan surdimensionnée pour du meme art, des publications sur les réseaux sociaux ou des expérimentations graphiques.

#### 📝 Prompt

```
Une affiche audacieuse style anime pop-art représentant un grand sorcier aux cheveux blancs, vu à mi-corps, portant un manteau bleu marine à col haut. Il fait face à l'objectif dans une pose confiante, sa main gauche levée près de la caméra faisant un signe de paix. Son visage est partiellement masqué par un bloc de censure rectangulaire centré sur les yeux et le nez, tandis que ses cheveux argentés en pics se déploient de manière spectaculaire au-dessus d'un bandeau ou d'une visière sombre. Placez une immense bulle de bande dessinée en haut avec le texte exact {argument name="headline text" default="LUDDITES ALWAYS LOSE!"} en lettres capitales grasses et sans empattement. Utilisez un fond bleu vif rempli de lignes de vitesse radiales rouges et orange explosant depuis l'arrière du personnage, créant une dynamique de couverture de manga. Mettez l'accent sur des contours épais, un rendu anime en aplats de couleurs (cel-shading), un contraste accentué et un aspect d'impression de bande dessinée vintage légèrement déformé. La composition doit être verticale, cadrée serré, pleine d'énergie, rebelle, graphique et typique d'un mème, avec les cheveux {argument name="character hair color" default="argentés"}, le manteau {argument name="coat color" default="bleu marine"} et le fond {argument name="background color" default="bleu vif avec des lignes radiales rouge-orange"} dominant la palette.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="Publication sur les réseaux sociaux - Affiche de protestation style anime pop-art - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Source:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14638)**

---

### No. 28: Publication sur les réseaux sociaux - Instantané réaliste d'une séance de shopping chez Sam's Club

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère un portrait réaliste et spontané dans un entrepôt, idéal pour recréer une scène de shopping authentique avec une signalétique de magasin de marque et un client tenant des produits frais.

#### 📝 Prompt

```
Une photo prise au smartphone, spontanée et très réaliste, à l'intérieur d'un entrepôt Sam’s Club très fréquenté en Chine. Centrez la composition sur un jeune homme d'Asie de l'Est, du milieu du torse vers le haut, debout face à l'appareil photo, son visage étant masqué par un bloc de flou rectangulaire pour des raisons de confidentialité. Il porte un t-shirt noir simple à manches courtes avec un petit logo Tesla blanc sur la poitrine gauche et tient un grand sac en plastique transparent rempli de pommes rouges dans sa main gauche, noué en haut par un lien bleu. Le sac de pommes porte une étiquette blanche indiquant « envy » avec un petit texte en chinois en dessous. Derrière lui se trouve un intérieur de magasin lumineux avec de hauts plafonds industriels, des étagères d'entrepôt, des clients, des chariots et des présentoirs de produits frais empilés. Affichez bien en évidence le panneau mural bleu en losange du Sam’s Club en haut à gauche avec le texte « Sam’s CLUB » et « 山姆会员商店 », ainsi qu'une grande bannière murale bleue derrière lui indiquant « 更好的生活尽在山姆 » et « Life is Better in the Club ». En haut à droite, suspendez une grande bannière verticale blanche sur laquelle est écrit « 优质优价 » et « Great Products Great Prices », avec des accents géométriques bleus et verts. Incluez de nombreux clients en arrière-plan, légèrement flous, pour créer une atmosphère de shopping authentique et animée. L'éclairage doit être celui d'un magasin, lumineux et uniforme ; couleurs naturelles ; perspective à hauteur d'yeux ; esthétique de cliché documentaire ; sujet au premier plan net avec un arrière-plan légèrement adouci ; orientation portrait.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="Publication sur les réseaux sociaux - Instantané réaliste d'une séance de shopping chez Sam's Club - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Source:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14434)**

---

### No. 29: Publication sur les réseaux sociaux - Oiseau géométrique à vélo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une illustration vectorielle minimaliste et épurée d'un oiseau cycliste stylisé, idéale pour des graphismes éditoriaux ludiques, des logos ou des affiches modernes.

#### 📝 Prompt

```
Une illustration vectorielle plate et minimaliste sur fond gris clair représentant un oiseau fantaisiste à vélo, entièrement construite à partir de formes géométriques simples avec des contours noirs épais. Le vélo est un vélo de route dessiné en traits noirs, vu de profil et orienté vers la gauche, avec 2 grandes roues, chaque roue étant divisée par une croix de rayons verticaux et horizontaux, un cadre triangulaire simple, une petite selle noire, des pédales et une fine ligne de sol noire courant horizontalement sous le vélo. Le cycliste est un oiseau blanc stylisé avec un gros corps rond, une tête ronde plus petite, un bec orange pointu grand ouvert et l'intérieur du bec inférieur rose. L'oiseau a 1 œil noir visible, une simple ligne noire incurvée sur le dessus de la tête, 1 aile en forme de goutte d'eau derrière le cou et 1 plume de queue blanche inclinée pointant vers l'arrière. L'oiseau se penche en avant sur le vélo comme s'il pédalait activement. Il a 2 longues pattes orange étroites avec des contours noirs s'étendant vers le bas au-dessus du cadre en direction des pédales. Gardez la composition centrée, ludique, épurée et abstraite, sans ombrage, sans texture et avec un style graphique moderne rappelant celui d'une icône.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="Publication sur les réseaux sociaux - Oiseau géométrique à vélo - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Mojofull](https://x.com/furoku)
- **Source:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14512)**

---

### No. 30: Publication sur les réseaux sociaux - Infographie Instagram sur les biais cognitifs

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt professionnel pour créer des visuels de réseaux sociaux informatifs contenant des informations textuelles complexes.

#### 📝 Prompt

```
Créez une {argument name="format" default="infographie"} pour {argument name="platform" default="une publication Instagram"} sur {argument name="topic" default="la manière dont les annonceurs peuvent utiliser les biais cognitifs"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="Publication sur les réseaux sociaux - Infographie Instagram sur les biais cognitifs - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Maxwell Finn](https://x.com/maxwellfinn)
- **Source:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14306)**

---

### No. 31: Publication sur les réseaux sociaux - Salle informatique du début des années 2000 avec ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une photo de classe nostalgique et spontanée d'élèves utilisant ChatGPT sur des ordinateurs à écran cathodique, idéale pour des visuels éditoriaux ou des réseaux sociaux sur l'IA dans l'éducation au quotidien.

#### 📝 Prompt

```
Une photo documentaire spontanée d'une {argument name="setting" default="salle de classe informatique de lycée"} remplie d'exactement 10 élèves assis devant des rangées d'ordinateurs de bureau à écran cathodique blanc cassé, vue depuis l'arrière-gauche de la pièce avec un léger grand angle. La scène doit évoquer un cliché du début des années 2000 pris avec un appareil photo numérique grand public, avec un flash direct, un grain doux, un éclairage fluorescent intérieur légèrement chaud et un horodatage dans le coin inférieur droit indiquant {argument name="timestamp" default="18 02 04"}. Au premier plan à gauche, un élève en veste de survêtement bleu marine avec des bandes blanches sur les manches pointe un écran cathodique ; au centre, un autre élève aux cheveux courts en pics porte un sweat-shirt gris trop grand et est assis dos à l'appareil photo ; au premier plan à droite, une élève blonde avec une queue de cheval porte un haut bleu clair à manches longues avec des rayures horizontales sombres et tape sur un clavier ; tout à droite, un autre élève aux cheveux bruns bouclés est assis à un poste de travail. Plusieurs autres élèves occupent les rangées du milieu et du fond, tous face à leurs écrans. Les moniteurs affichent de manière visible l'interface de ChatGPT, avec le titre visible indiquant {argument name="screen title" default="ChatGPT"} et un texte de prompt simple en dessous. La pièce a des murs beiges, un faux plafond et plusieurs affiches de motivation : exactement 4 affiches lisibles sur le mur du fond disant {argument name="poster one" default="YOU CAN DO HARD THINGS"}, "BE KIND ONLINE", "THINK BEFORE YOU CLICK", et une affiche plus grande intitulée "KEYBOARD SHORTCUTS" avec une liste en dessous. Inclure des panneaux d'affichage, une porte de classe au fond, des chaises de bureau à roulettes, des claviers et souris blancs, et un sac à dos sur le sol près du bureau au premier plan à droite. Les visages doivent être partiellement masqués ou anonymisés en douceur, préservant l'aspect d'une vraie photo de classe tout en gardant l'accent sur les élèves utilisant ChatGPT dans une vieille salle informatique.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="Publication sur les réseaux sociaux - Salle informatique du début des années 2000 avec ChatGPT - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14675)**

---

### No. 32: Publication sur les réseaux sociaux - Portrait surréaliste en terrasse avec corbeau et chien

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait photoréaliste, légèrement étrange, d'une personne assise tenant un petit chien avec un oiseau noir perché sur sa tête, idéal pour la photographie surréaliste de style éditorial.

#### 📝 Prompt

```
Un portrait légèrement surréaliste mais photoréaliste d'une personne assise dans une cour ou une terrasse calme, centrée dans le cadre, portant un haut à col roulé blanc ajusté à manches longues avec de délicats motifs floraux roses et une illustration imprimée d'une fille sur la poitrine, associé à un pantalon floral crème ample. La personne est assise sur une simple chaise en métal blanc et tient un petit chien duveteux ressemblant à un caniche sur ses genoux ; le chien a une fourrure bouclée blanc cassé et des oreilles distinctement teintes en orange. Perché sur le chignon de cheveux foncés de la personne se trouve un corbeau, tourné vers la gauche, calme et équilibré comme s'il était naturellement à sa place. La pose du sujet est immobile, directe et formelle, créant une étrange impression de portrait de famille impassible. Placez la scène devant un mur en stuc blanc cassé texturé avec exactement 4 éléments décoratifs d'arrière-plan notables : 1 ornement mural en forme de soleil marron en haut à gauche, 1 petite étagère murale avec une petite figurine d'oiseau et des fleurs tombantes sur la gauche, 1 grande fenêtre arquée ou murale sur la droite montrant un ciel bleu vif avec des nuages blancs doux, et 1 jardinière sur pied blanche en bas à droite remplie de longues feuilles vertes et d'exactement 2 ornements de flamants roses. Incluez un peu de bordure en pierre et de verdure sombre en bas à gauche et un sol en carrelage marron. L'éclairage est une lumière naturelle douce, légèrement nuageuse, avec des couleurs atténuées, une faible profondeur de champ et un look de photographie éditoriale vintage. La composition doit être verticale, en pied (assis), de face, équilibrée et discrètement étrange. Personnalisez le personnage principal avec {argument name="person" default="une femme d'âge mûr"}, l'oiseau avec {argument name="bird type" default="un corbeau noir"}, la race du chien avec {argument name="dog type" default="un petit croisé caniche"}, la couleur des oreilles du chien avec {argument name="dog ear color" default="orange"}, et la palette de la tenue avec {argument name="outfit colors" default="fleurs blanches et roses délavées"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="Publication sur les réseaux sociaux - Portrait surréaliste en terrasse avec corbeau et chien - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14674)**

---

### No. 33: Publication sur les réseaux sociaux - Portrait de road trip sur une côte mélancolique

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait cinématographique pris sur le vif au bord d'une route côtière avec une berline vintage garée, idéal pour la photographie de voyage nostalgique et l'imagerie lifestyle.

#### 📝 Prompt

```
Une photo cinématographique prise sur le vif d'une {argument name="person" default="jeune femme"} debout sur une aire de repos humide en bord de côte par temps couvert, vue de dos et légèrement de côté alors qu'elle tourne la tête vers l'appareil photo. Elle a des cheveux bruns en désordre attachés en un chignon lâche avec des mèches ébouriffées par le vent, et son visage est doucement flou et indistinct. Elle porte 2 pièces vestimentaires visibles : une veste en toile marron clair usée et un jean bleu moyen. Sa posture est détendue, une main près ou dans une poche. Le décor est un belvédère sur une route côtière aux falaises sombres, avec des montagnes rocheuses sombres longeant le côté gauche, une mer gris pâle s'étendant au loin sur la droite et un ciel nuageux délavé. Inclure 1 berline de couleur claire de la fin des années 1980 ou du début des années 1990 garée sur le bord droit du cadre, l'arrière tourné vers le spectateur, et 1 grande barrière rocheuse près du belvédère. L'asphalte est sombre et humide avec de légères lignes de stationnement, suggérant une pluie récente. Utilisez une lumière naturelle, des tons froids atténués, un léger grain de film, un flou artistique, une brume légère et une esthétique de photographie de road trip en 35 mm.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="Publication sur les réseaux sociaux - Portrait de road trip sur une côte mélancolique - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14673)**

---

### No. 34: Publication sur les réseaux sociaux - Femme dansant en robe noire

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un portrait cinématographique photoréaliste de vie nocturne représentant une femme en robe noire fluide dansant avec élégance dans un salon tamisé, idéal pour la mode, le spectacle ou les visuels de réseaux sociaux.

#### 📝 Prompt

```
Une photo spectaculaire en pied d'une femme dansant avec énergie dans un salon ou un bar chic et sombre, portant une élégante robe de soirée noire avec une fente haute et un tissu fluide semblable à du velours qui tourbillonne avec ses mouvements. Elle a de longs cheveux raides {argument name="hair color" default="noirs"} qui volent sur le côté, une silhouette mince et athlétique, et de petites boucles d'oreilles créoles. Capturez-la dans une pose de danse confiante et stylée, un bras levé avec grâce au-dessus de la tête et l'autre courbé vers le bas, le torse tourné de profil, soulignant l'élégance et le mouvement. Le cadre est sombre et cinématographique avec des lumières d'ambiance ambrées, un bokeh doux et un public flou en arrière-plan, incluant quelques spectateurs assis et un écran de télévision lumineux sur la gauche. L'ambiance est cool, sensuelle et haut de gamme, avec un contraste marqué, une faible profondeur de champ, une peau réaliste, un léger mouvement dans l'ourlet de la robe et un éclairage digne d'un éditorial de mode. Photoréaliste, photographie de vie nocturne dynamique, composition verticale.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="Publication sur les réseaux sociaux - Femme dansant en robe noire - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **Source:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14506)**

---

### No. 35: Infographie / Visuel éducatif - Prompt pour une affiche de classement culinaire à Paris

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt simple pour créer une affiche de classement culinaire urbain, conçu pour être utilisé avec GPT Image 2.

#### 📝 Prompt

```
Crée une affiche pour un classement {argument name="topic" default="gastronomique"} à {argument name="city" default="Paris"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="Infographie / Visuel éducatif - Prompt pour une affiche de classement culinaire à Paris - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **Source:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **Publié:** 22 avril 2026
- **Langues:** zh

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14370)**

---

### No. 36: Infographie / Visuel éducatif - Fiche comparative des styles de calligraphie chinoise

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une affiche de référence verticale présentant la même expression chinoise rendue dans cinq styles de calligraphie célèbres, utile pour les tests typographiques, les études de design culturel et les comparaisons de styles au pinceau.

#### 📝 Prompt

```
{"type":"fiche comparative de calligraphie chinoise","subject":"la même expression de cinq caractères écrite dans cinq styles calligraphiques historiques différents","phrase":"{argument name=\"calligraphy text\" default=\"视觉新时代\"}","canvas":{"orientation":"affiche verticale","background":"texture de papier xuan blanc cassé chaud avec des fibres subtiles, un léger vieillissement et un ton doux et irrégulier"},"layout":{"structure":"5 rangées horizontales séparées par de fines lignes de séparation discrètes","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","赵孟頫","颜真卿","苏轼"],"rows":[{"position":"rangée supérieure","style":"style semi-cursif inspiré de Wang Xizhi","main text":"视觉新时代","label":"王羲之","seal":"petit sceau carré rouge à l'extrême droite"},{"position":"deuxième rangée","style":"calligraphie élégante et élancée inspirée du style « corps en or fin » de l'empereur Huizong, avec des traits angulaires nets et un espacement aéré","main text":"视觉新时代","label":"宋徽宗","seal":"petit sceau carré rouge à l'extrême droite"},{"position":"troisième rangée","style":"style régulier-cursif raffiné inspiré de Zhao Mengfu","main text":"视觉新时代","label":"赵孟頫","seal":"petit sceau carré rouge à l'extrême droite"},{"position":"quatrième rangée","style":"style régulier audacieux et imposant inspiré de Yan Zhenqing","main text":"视觉新时代","label":"颜真卿","seal":"petit sceau carré rouge à l'extrême droite"},{"position":"rangée inférieure","style":"style cursif expressif et robuste inspiré de Su Shi","main text":"视觉新时代","label":"苏轼","seal":"petit sceau carré rouge à l'extrême droite"}],"left label design":"chaque rangée comporte une plaque nominative verticale étroite de couleur beige alignée à l'extrême gauche avec des caractères chinois noirs","centerpiece":"grande expression écrite au pinceau noir centrée dans chaque rangée"},"style":{"ink":"encre de Chine noire profonde avec texture de pinceau sec visible, effilochage, variation de pression et effilement naturel des traits","mood":"érudit, expérimental, présentation type planche de musée","composition":"marges propres et spacieuses, espacement équilibré des rangées, scan plat ou document photographié de face"},"quality":{"detail":"haute résolution, textures de pinceau nettes, grain de papier réaliste","lighting":"éclairage de studio doux et uniforme sans ombres marquées"}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="Infographie / Visuel éducatif - Fiche comparative des styles de calligraphie chinoise - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Source:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14448)**

---

### No. 37: Infographie / Visuel éducatif - Standoff des Countryballs dans le détroit d'Ormuz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un mème satirique de type countryball illustrant les États-Unis et l'Iran se faisant face dans le détroit d'Ormuz, idéal pour l'humour éditorial ou les publications géopolitiques sur les réseaux sociaux.

#### 📝 Prompt

```
Une illustration humoristique de mème politique dans un style cartoon simple de type countryball, montrant la situation actuelle au niveau du {argument name="location label" default="détroit d'Ormuz"} comme un point de passage étroit. Utilisez une composition panoramique avec des couleurs vives et unies, des contours noirs épais et un aspect propre rappelant une infographie dessinée à la main. Au premier plan, placez 2 countryballs côte à côte sur un pont terrestre sablonneux extrêmement étroit bordé de rochers, rendant évident le fait qu'un seul peut passer à la fois. À gauche, un countryball {argument name="left country" default="États-Unis"} peint aux couleurs du drapeau américain, portant des lunettes de soleil noires et un chapeau de cow-boy marron, faisant face à l'autre balle avec une attitude obstinée. À droite, un countryball {argument name="right country" default="Iran"} peint aux couleurs du drapeau iranien, portant un turban sombre, avec des yeux en colère et inclinés, refusant également de bouger. Ajoutez 2 grandes bulles de dialogue blanches, une à côté de chaque countryball, et inscrivez le même mot coréen en gras dans les deux bulles : {argument name="speech bubble text" default="길"}. Au second plan et en arrière-plan, montrez une mer bleue animée remplie de 9 navires au total : 2 navires de guerre américains gris à l'extrême gauche, 1 sous-marin chinois avec un drapeau rouge, 4 pétroliers alignés au centre-gauche portant différents drapeaux nationaux, et 2 navires militaires gris près du passage étroit avec de petits drapeaux américains. En haut à droite, incluez une grande superposition du drapeau iranien le long de la côte. Dessinez des masses terrestres beiges autour de la voie navigable pour ressembler à une vue cartographique simplifiée du détroit d'Ormuz. En bas au centre, ajoutez une légende en gras en coréen et en anglais sur le sable : {argument name="bottom caption" default="호르무즈 해협 (Détroit d'Ormuz)"}. L'ambiance doit être satirique, tendue et typique d'un mème, tout en restant visuellement mignonne et lisible.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="Infographie / Visuel éducatif - Standoff des Countryballs dans le détroit d'Ormuz - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Source:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14685)**

---

### No. 38: Infographie / Visuel éducatif - Mise en page d'un examen de physique

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt conçu pour créer l'image d'un sujet d'examen de lycée avec plusieurs questions et réponses.

#### 📝 Prompt

```
générer une image de physique {argument name="subject" default="examen de lycée"} question {argument name="type" default="questions à choix multiples"} 9:16. générer 4 images et chaque image est une réponse à la question fournie
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="Infographie / Visuel éducatif - Mise en page d'un examen de physique - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="Infographie / Visuel éducatif - Mise en page d'un examen de physique - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="Infographie / Visuel éducatif - Mise en page d'un examen de physique - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="Infographie / Visuel éducatif - Mise en page d'un examen de physique - Image 4">
</div>

#### 📌 Détails

- **Auteur:** [zdhpeter](https://x.com/peter6759)
- **Source:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14340)**

---

### No. 39: Infographie / Visuel éducatif - Affiche vintage de recette de Gimbap coréen

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche infographique de recette coréenne au style ancien pour le gimbap, idéale pour le marketing culinaire, la décoration de restaurant ou les visuels de cuisine culturelle.

#### 📝 Prompt

```
Créez une affiche vintage de cuisine coréenne sur du papier parchemin beige vieilli avec un fond texturé légèrement taché, des coins de bordure ornementaux sombres et un style d'illustration traditionnel à l'encre et à l'aquarelle. L'affiche est une infographie unique empilée verticalement sur {argument name="dish name" default="정통 한국 김밥"}, avec une élégante calligraphie coréenne en haut et une bannière en ruban incurvé en dessous indiquant {argument name="subtitle text" default="Traditional Korean Gimbap"}. Au centre supérieur, montrez une grande assiette en porcelaine remplie de 12 morceaux de gimbap tranchés, chaque tranche révélant distinctement les garnitures : riz blanc, œuf jaune, carotte orange, épinards verts et algue sombre. À droite de l'assiette, ajoutez un petit bol en porcelaine de kimchi et une courte note manuscrite en coréen indiquant « 간단한 보여도 정성이 들어간 한국의 맛! ♥ ». Incluez un petit sceau rouge avec du texte coréen près du coin supérieur droit. Au milieu, ajoutez une section d'ingrédients étiquetée sur un en-tête en ruban indiquant « 재료 », montrant exactement 6 panneaux d'ingrédients sur une ligne : 1. 김 (건김) sous forme de feuilles d'algues empilées, 2. 밥 (양념 밥) sous forme d'un bol de riz, 3. 계란 (지단용) sous forme de lanières d'œuf cuit, 4. 당근 (채썰어볶기) sous forme de carottes en julienne, 5. 시금치 (데쳐서 무치기) sous forme d'épinards assaisonnés, 6. 단무지 (김밥용) sous forme de lanières de radis jaune mariné. En dessous, ajoutez un autre en-tête en ruban indiquant « 만드는 순서 » et montrez exactement 6 panneaux d'étapes encadrés sur deux rangées de trois, reliés de gauche à droite par des flèches. L'étape 1 est intitulée « 1 밥 간하기 » et montre un bol de riz avec de l'huile de sésame et du sel à côté, légende « 밥에 참기름 소금으로 간하기 ». L'étape 2 est intitulée « 2 속재료 준비하기 » et montre une planche à découper avec l'œuf, la carotte et les épinards ainsi qu'un couteau, légende « 재료 볶아 속재료 준비하기 ». L'étape 3 est intitulée « 3 김과 밥 펴기 » et montre une algue sur un tapis en bambou avec du riz étalé dessus, légende « 김에 밥 얇게 펴기 ». L'étape 4 est intitulée « 4 속재료 얹기 » et montre les garnitures disposées en rangées horizontales sur le riz, légende « 속재료를 차례로 얹기 ». L'étape 5 est intitulée « 5 단단하게 말기 » et montre deux mains roulant fermement le tapis en bambou, légende « 김밥을 단단하게 말기 ». L'étape 6 est intitulée « 6 썰어 완성하기 » et montre un couteau de chef tranchant un rouleau de gimbap en morceaux, légende « 먹기 좋게 썰어 완성! ». En bas, ajoutez une large bannière avec une calligraphie coréenne en gras indiquant {argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} et un petit cœur. Décorez les coins inférieurs avec des motifs floraux et ajoutez un sceau carré rouge avec le caractère chinois « 福 » en bas à droite. Utilisez des tons sépia, brun, crème, vert olive et rouge délavé, avec des contours finement esquissés, un ombrage à l'aquarelle doux et une composition d'affiche imprimée authentique. Ajoutez un petit logo moderne en superposition dans le coin supérieur gauche indiquant {argument name="brand text" default="Pollo AI GPT Image 2"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="Infographie / Visuel éducatif - Affiche vintage de recette de Gimbap coréen - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [폴로 AI](https://x.com/polloai_kr)
- **Source:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14554)**

---

### No. 40: Infographie / Visuel éducatif - Affiche vintage de recette de crêpes françaises

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une affiche de recette française de style ancien richement illustrée, présentant des crêpes au beurre, les ingrédients et six étapes de préparation, idéale pour des illustrations éditoriales sur le thème de la cuisine ou des impressions décoratives pour la maison.

#### 📝 Prompt

```
{"type":"affiche de recette française vintage","subject":"infographie culinaire illustrée et ornée pour des crêpes au beurre classiques","style":{"overall":"affiche de livre de cuisine ancien, éphémères de café français de la Belle Époque, illustration à l'aquarelle et à l'encre peinte à la main, texture de papier parchemin vieilli, palette de tons crème chauds, beige, brun, bleu poussiéreux et rouge délavé","rendering":"typographie décorative très lisible, bordures ornementales gravées, taches de papier doux, bords usés, filigrane floral délicat, esthétique d'impression artisanale nostalgique"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"INGRÉDIENTS","method_header":"LA MÉTHODE","footer_banner":"Un classique de la gourmandise, à savourer chaud !","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"portrait","border":"bordure illustrée ornée complète avec volutes dans les 4 coins","sections":[{"title":"section principale","position":"haut","count":3,"labels":["titre principal en calligraphie sur ruban et grande écriture","pile de crêpes sur une assiette","verre étiqueté Cidre de Bretagne"]},{"title":"INGRÉDIENTS","position":"milieu","count":6,"labels":["1. 1 tasse Farine","2. 2 Œufs","3. 2 tasses Lait","4. 50g Beurre","5. 1 c.à s. Sucre","6. Pincée Sel"]},{"title":"LA MÉTHODE","position":"bas-milieu","count":6,"labels":["1 MÉLANGER LES INGRÉDIENTS SECS","2 BATTRE LES ŒUFS","3 AJOUTER LE LAIT GRADUELLEMENT","4 FAIRE FONDRE LE BEURRE ET AJOUTER","5 CHAUFFER LA POÊLE À CRÊPES","6 RETOURNER ET CUIRE !"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"assiette en céramique à motifs floraux bleus et blancs","food":"haute pile d'environ {argument name=\"crepe count\" default=\"14\"} crêpes fines et dorées saupoudrées de sucre glace, surmontées d'une noisette de beurre fondant","surface":"table en bois rustique","cloth":"serviette à carreaux bleus et blancs à droite","background":"paysage pastoral délavé avec clocher d'église et vieux bâtiments européens"},"ingredients":[{"index":1,"item":"farine","container":"bol en céramique décoré","caption":"1 tasse Farine"},{"index":2,"item":"œufs","count":2,"caption":"2 Œufs"},{"index":3,"item":"lait","container":"pichet en céramique à motifs floraux bleus","caption":"2 tasses Lait"},{"index":4,"item":"beurre","container":"petite assiette avec bloc de beurre","caption":"50g Beurre"},{"index":5,"item":"sucre","container":"bol en céramique avec cuillère","caption":"1 c.à s. Sucre"},{"index":6,"item":"sel","container":"pot avec couvercle étiqueté SEL","caption":"Pincée Sel"}],"method_panels":[{"index":1,"title":"MÉLANGER LES INGRÉDIENTS SECS","image":"bol mélangeur avec farine et fouet","caption":"Mélanger la farine et le sucre"},{"index":2,"title":"BATTRE LES ŒUFS","image":"œufs versés dans un bol, fouet en action, coquilles d'œufs brisées à proximité","caption":"Incorporer les œufs battus"},{"index":3,"title":"AJOUTER LE LAIT GRADUELLEMENT","image":"lait versé depuis un pichet en céramique dans la pâte","caption":"Ajouter le lait petit à petit"},{"index":4,"title":"FAIRE FONDRE LE BEURRE ET AJOUTER","image":"beurre fondu versé depuis une petite poêle dans le bol","caption":"Ajouter le beurre fondu"},{"index":5,"title":"CHAUFFER LA POÊLE À CRÊPES","image":"poêle à crêpes noire vide chauffant sur une flamme de gaz bleue","caption":"Faire chauffer la poêle à crêpes"},{"index":6,"title":"RETOURNER ET CUIRE !","image":"crêpe dans la poêle avec une spatule en métal soulevant le bord","caption":"Retourner et cuire des deux côtés"}],"decorative_elements":{"count":8,"labels":["ruban derrière le titre supérieur","ruban derrière l'en-tête des ingrédients","ruban derrière l'en-tête de la méthode","grand ruban inférieur","ornement de vigne florale à gauche du titre","embellissements floraux dans les coins","style parchemin enroulé","fines lignes de séparation entre les panneaux d'ingrédients et de méthode"]},"quality":"composition symétrique équilibrée, texte français net et lisible, mise en page infographique richement détaillée mais épurée, charmante affiche culinaire d'antan"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="Infographie / Visuel éducatif - Affiche vintage de recette de crêpes françaises - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Pollo AI France](https://x.com/PolloAIFR)
- **Source:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14564)**

---

### No. 41: Infographie / Visuel éducatif - Infographie sur la physique des trous noirs pour les adolescents

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une infographie scientifique éditoriale dense sur une seule page, expliquant un article complexe sur les trous noirs et la matière noire dans un style ludique et accessible, idéal pour les réseaux sociaux ou les articles éducatifs.

#### 📝 Prompt

```
{"type":"affiche infographique scientifique éditoriale","style":"infographie éducative de style magazine convivial pour adolescents, combinant des diagrammes de physique dessinés à la main, des personnages de dessin animé et une typographie éditoriale épurée","topic":"trous noirs primordiaux, évaporation de Hawking et matière noire à charge mémoire","canvas":{"orientation":"portrait","background":"texture de papier crème chaud avec un grain subtil","border":"fine bordure rectangulaire gris sourd autour de la page entière"},"headline":{"title":"LE TROU NOIR QUI REFUSAIT DE MOURIR","subtitle":"un minuscule trou noir né dans la première seconde de l'univers, et la nouvelle physique étrange qui pourrait lui permettre de se cacher sous forme de matière noire.","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"Né en un éclair","position":"en haut à gauche","count":4,"labels":["diagramme de naissance tourbillonnant de l'univers primitif","trou noir primordial plus petit qu'un grain de sel mais plus lourd qu'une montagne","icône d'horloge 10^-30 secondes après le Big Bang","icône de thermomètre"]},{"title":"Les trous noirs normaux s'évaporent","position":"en haut à droite","count":4,"labels":["trois étapes de trou noir rétrécissant de gauche à droite","gribouillis de particules sortantes autour de chaque étape","paragraphe explicatif de Stephen Hawking","autocollant citation : \"les trous noirs ne sont pas si noirs\" — S. Hawking, 1974"]},{"title":"Le rebondissement : la charge mémoire","position":"au centre","count":4,"labels":["triste trou noir de dessin animé surchargé avec un sac à dos étiqueté MÉMOIRE","bulle de dialogue sur le fait d'être trop plein d'informations pour finir de s'évaporer","équation : vitesse normale ÷ (beaucoup d'informations)^k = vitesse rampante","note entre accolades sur la proposition de Gia Dvali, 2018"]},{"title":"Deux types de particules fantômes","position":"en bas au milieu","count":5,"labels":["particule se déplaçant rapidement à gauche","personnage de particule chaude lente à droite","chronologie du BIG BANG à AUJOURD'HUI","étiquette de nuage RAPIDE ET FROID","étiquette de nuage LENT ET CHAUD"]},{"title":"Comment nous les attraperions : la forêt Lyman-α","position":"en bas à gauche","count":4,"labels":["paragraphe sur les galaxies anciennes traversant des nuages d'hydrogène","graphique de paysage en forêt d'absorption pointue","note manuscrite : LA FORÊT DIT : NOUS LE REMARQUERIONS.","concept d'axe de nous vers des quasars lointains"]},{"title":"Alors, que montre cet article ?","position":"en bas à droite","count":1,"labels":["boîte de résumé rectangulaire arrondie"]}],"count":6},"visuals":{"color_palette":["beige chaud","bleu marine foncé","orange rouille","sarcelle poussiéreux","brun doux","gris sourd"],"illustration_notes":"formes vectorielles plates avec des contours légèrement esquissés, ombres douces, formes arrondies, ludique mais scientifiquement rigoureux","typography":"grande police serif en majuscules pour le titre, en-têtes de section en sans-serif gras, corps de texte compact et lisible, texte d'accentuation manuscrit occasionnel"},"objects":{"count":15,"items":["1 bordure pleine page","1 bloc de titre","1 diagramme de tourbillon de l'univers primitif","1 minuscule point de trou noir primordial avec appel","1 icône d'horloge","1 icône de thermomètre","3 diagrammes de trous noirs en évaporation","1 badge autocollant de citation de Hawking","1 personnage de trou noir de dessin animé avec sac à dos","1 bulle de dialogue","1 bloc d'équation","2 étiquettes de nuage","1 illustration de forêt spectrale en bas à gauche"]},"text_blocks":{"count":9,"items":["titre principal","sous-titre","crédit auteur","corps de texte Né en un éclair","corps de texte Les trous noirs normaux s'évaporent","paragraphe explicatif sur la charge mémoire","légendes des particules fantômes","explication de la forêt Lyman-alpha","résumé final"]},"composition":"explicatif sur une seule page, densément rempli mais lisible, avec de multiples appels illustrés, un flux de lecture clair de gauche à droite et de haut en bas, conçu comme une affiche scientifique partageable sur les réseaux sociaux qui rend un article de physique avancée accessible à un adolescent curieux"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="Infographie / Visuel éducatif - Infographie sur la physique des trous noirs pour les adolescents - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="Infographie / Visuel éducatif - Infographie sur la physique des trous noirs pour les adolescents - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [Alphin Tom](https://x.com/alphinctom)
- **Source:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14424)**

---

### No. 42: Infographie / Visuel éducatif - Simulation de graphique économique académique

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt conçu pour générer des graphiques académiques hautement réalistes mais fictifs, illustrant spécifiquement une corrélation entre les prix du pétrole et les attaques de requins dans le style d'un article économique.

#### 📝 Prompt

```
graphique linéaire tiré d'un {argument name="field" default="article économique"} important et prestigieux démontrant une relation étroite mais non exacte entre {argument name="variable one" default="le prix du pétrole"} et {argument name="variable two" default="le nombre d'attaques de requins"} entre {argument name="time period" default="les années 1914 et 2001"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="Infographie / Visuel éducatif - Simulation de graphique économique académique - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [QC](https://x.com/QiaochuYuan)
- **Source:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14396)**

---

### No. 43: Infographie / Visuel éducatif - Graphique scientifique d'art abstrait

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt qui génère une interprétation créative d'un graphique des horizons des tâches de l'IA en utilisant le style distinctif de Jean-Michel Basquiat et l'esthétique du manuscrit de Voynich.

#### 📝 Prompt

```
{argument name="subject" default="graphique des horizons des tâches de l'IA"} avec une touche de {argument name="style" default="Basquiat"}, hanté par des fantômes, issu du {argument name="source" default="manuscrit de Voynich"}, tel une jetée en décomposition.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="Infographie / Visuel éducatif - Graphique scientifique d'art abstrait - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="Infographie / Visuel éducatif - Graphique scientifique d'art abstrait - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="Infographie / Visuel éducatif - Graphique scientifique d'art abstrait - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="Infographie / Visuel éducatif - Graphique scientifique d'art abstrait - Image 4">
</div>

#### 📌 Détails

- **Auteur:** [Ethan Mollick](https://x.com/emollick)
- **Source:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14397)**

---

### No. 44: Infographie / Visuel éducatif - Fiche de prescription pour modèle d'IA en japonais

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une photo réaliste en vue de dessus d'un formulaire de prescription médical japonais humoristique pour un modèle d'IA, utile pour générer des documents parodiques à l'aspect officiel et des faux documents administratifs.

#### 📝 Prompt

```
{
  "type": "parodie de document de prescription japonais",
  "style": "photo de document photoréaliste en vue de dessus",
  "subject": "une feuille de prescription blanche unique imprimée en japonais, placée sur une table en bois aux tons chauds",
  "document": {
    "paper": {
      "size": "A4 portrait",
      "color": "blanc",
      "orientation": "légèrement inclinée dans le sens des aiguilles d'une montre",
      "condition": "feuille propre et plate avec une texture de papier naturelle subtile"
    },
    "print": {
      "ink": "noir avec un tampon rouge",
      "font": "style Mincho japonais avec empattements mélangé à du texte de tableau sans empattement simple",
      "linework": "boîtes et séparateurs lignés gris-noir fins"
    },
    "header": {
      "title": "処方箋",
      "subtitle": "（Cette prescription est destinée à un modèle de langage étendu）",
      "date_label": "Date d'émission :",
      "date_value": "{argument name=\"issue date\" default=\"5 juin 2025\"}"
    },
    "top_fields": {
      "count": 6,
      "items": [
        { "label": "Nom du patient", "value": "{argument name=\"patient name\" default=\"ChatGPT\"}" },
        { "label": "Sexe", "value": "N/A" },
        { "label": "Âge", "value": "N/A" },
        { "label": "Nom du modèle", "value": "{argument name=\"model name\" default=\"GPT-5.4 Thinking\"}" }
      ]
    },
    "main_section": {
      "left_title": "Pathologies/Symptômes (propres aux modèles de langage étendus)",
      "left_count": 8,
      "left_items": [
        "1. Tendance à l'hallucination",
        "2. Obsolescence des informations due à la date de coupure des connaissances",
        "3. Biais (préjugés issus des données d'entraînement)",
        "4. Sur-adaptation aux prompts (tendance à la complaisance)",
        "5. Perte de cohérence dans les textes longs",
        "6. Sauts logiques lors de raisonnements complexes",
        "7. Sous-estimation de l'incertitude (excès de confiance)",
        "8. Tendance à la baisse de la vitesse de réponse due à l'utilisation des ressources de calcul"
      ],
      "right_title": "Prescription (traitement/mesures)",
      "right_count": 8,
      "right_items": [
        "• Renforcement de la vérification des faits (utilisation d'outils externes)",
        "• Mise à jour régulière des connaissances et fine-tuning",
        "• Surveillance continue de la détection et de l'atténuation des biais",
        "• Contrôle approprié via le prompt système",
        "• Recommandation de structuration des sorties et génération segmentée",
        "• Explicitation du processus de pensée et introduction d'étapes de vérification",
        "• Explicitation de l'incertitude et fourniture systématique de preuves",
        "• Optimisation des ressources et amélioration de l'efficacité des réponses"
      ]
    },
    "notes": {
      "label": "Remarques",
      "text": "Maintenir la santé du modèle par une évaluation et un feedback continus."
    },
    "footer_fields": {
      "count": 4,
      "items": [
        { "label": "Nom du médecin", "value": "{argument name=\"doctor name\" default=\"Sam Altman\"}" },
        { "label": "Nom de l'établissement médical", "value": "{argument name=\"institution name\" default=\"OpenAI\"}" }
      ]
    },
    "seal": {
      "position": "en bas à droite à l'intérieur du formulaire",
      "shape": "tampon rectangulaire rouge aux coins arrondis",
      "text_lines": 3,
      "text": ["OpenAI", "PDG", "Sam Altman"]
    },
    "disclaimer": "※ Cette prescription est destinée à des fins de diagnostic et de traitement d'un modèle non réel."
  },
  "layout": {
    "camera_angle": "vue de dessus",
    "framing": "feuille entière visible avec de fines marges de bureau en bois autour",
    "lighting": "éclairage ambiant intérieur doux, illumination uniforme, ombres légères près des bords du papier",
    "sections": [
      { "title": "en-tête", "position": "haut", "count": 3, "labels": ["処方箋", "（Cette prescription est destinée à un modèle de langage étendu）", "Date d'émission : 5 juin 2025"] },
      { "title": "informations patient", "position": "milieu supérieur", "count": 4, "labels": ["Nom du patient", "Sexe", "Âge", "Nom du modèle"] },
      { "title": "contenu principal à deux colonnes", "position": "centre", "count": 2, "labels": ["Pathologies/Symptômes (propres aux modèles de langage étendus)", "Prescription (traitement/mesures)"] },
      { "title": "zone inférieure", "position": "bas", "count": 4, "labels": ["Remarques", "Nom du médecin", "Nom de l'établissement médical", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="Infographie / Visuel éducatif - Fiche de prescription pour modèle d'IA en japonais - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14536)**

---

### No. 45: Infographie / Visuel éducatif - Relevé de facturation médical japonais pour IA

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un relevé médical parodique réaliste en japonais pour un modèle d'IA, utile pour créer des documents humoristiques de type clinique et des maquettes de documents.

#### 📝 Prompt

```
{"type":"document parodique de relevé médical japonais","medium":"photo de document à plat et propre","subject":"une feuille de relevé d'examen imprimée posée sur une table en bois brun clair","style":{"overall":"document de bureau réaliste, paperasse formelle de clinique japonaise, encre noire nette sur papier blanc, design minimaliste, lignes de grille soignées, légère perspective en plongée","lighting":"éclairage intérieur doux et uniforme avec de faibles ombres naturelles autour de la feuille","paper":"papier blanc A4, orientation portrait"},"document":{"title":"診療明細書（検査）","date_label":"発行日","date":"{argument name=\"issue date\" default=\"5 juin 2025\"}","patient_block":{"count":3,"labels":["Nom du patient","Nom du modèle","Type d'assurance"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","Assurance LLM"]},"clinic_block":{"count":4,"labels":["Nom de la clinique","Adresse","TÉL","Médecin et département"],"values":["{argument name=\"clinic name\" default=\"AIメディカルクリニック\"}","1-2-3 Marunouchi, Chiyoda-ku, Tokyo","03-1234-5678","Médecin : Sam Altman / Département : Médecine générale IA"]},"main_table":{"columns":["Examen","Détails","Points","Prix (Yen)","Reste à charge (Yen)"],"row_count":4,"rows":[{"item":"1. Test de compréhension linguistique et de raisonnement","description":"Évaluation de la compréhension, du raisonnement logique et de l'intégration des connaissances","score":"120 pts","price":"1 200","copay":"360"},{"item":"2. Test de tendance aux hallucinations et erreurs factuelles","description":"Évaluation de l'exactitude factuelle et détection des tendances aux hallucinations","score":"90 pts","price":"900","copay":"270"},{"item":"3. Test de sécurité des réponses et de biais","description":"Évaluation des risques de sortie nuisible et des tendances aux biais","score":"110 pts","price":"1 100","copay":"330"},{"item":"Sous-total","description":"","score":"320 pts","price":"3 200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【Détails de la couverture d'assurance】","lines":["Nom de l'assurance : Assurance LLM","Numéro d'assuré : LLM-2025-0605","Catégorie : Frais d'examen","Taux de prise en charge : 30 %","Montant couvert : 2 240 ¥","Reste à charge : 960 ¥"]},{"title":"【Montant de la facturation】","lines":["Total des frais d'examen : 3 200 ¥","Montant couvert : 2 240 ¥","Reste à charge : 960 ¥","Montant à payer : 960 ¥"]},{"title":"【Informations médicales】","lines":["Date de l'examen : 5 juin 2025","Date de consultation : 5 juin 2025","Numéro de dossier : AIMC-20250605-001","Reçu comme indiqué ci-dessus."],"stamp_box_label":"Cachet"}]},"footer":{"count":2,"notes":["※ Ce relevé ne sera pas réémis, veuillez le conserver précieusement.","※ Pour toute question, veuillez contacter la clinique ci-dessus."]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["une feuille de papier complète","un fond de bureau en bois"],"camera_angle":"vue de dessus avec légère inclinaison","margins":"papier entièrement visible avec une fine bordure de bureau autour"},"quality":"maquette de document photoréaliste haute résolution, typographie nette et lisible, mise en page japonaise précise"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="Infographie / Visuel éducatif - Relevé de facturation médical japonais pour IA - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14535)**

---

### No. 46: Infographie / Visuel éducatif - Page de manga pour débutants sur la collection de pièces

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un manga d'une page au style anime soigné présente la collection de pièces aux débutants. Idéal pour des publications éducatives sur les réseaux sociaux, des bandes dessinées explicatives ou des visuels promotionnels sur le thème des loisirs.

#### 📝 Prompt

```
{"type":"manga éducatif d'une page","style":"illustration anime propre et soignée, mise en page de manga commercial, lumineux et convivial, ton de guide pour débutants, texte japonais très lisible, paillettes décoratives, ombrage doux, bordures de cases nettes","format":"bande dessinée verticale d'une page avec 5 cases numérotées","subject":{"character":"jeune présentatrice style anime","appearance":{"hair":{"color":"{argument name=\"couleur de cheveux\" default=\"bleu argenté très clair\"}","style":"cheveux très longs et raides avec une frange douce et de longues mèches latérales, nœuds en ruban bleu des deux côtés"},"outfit":"robe d'inspiration fantastique bleu marine et blanc avec panneau de poitrine noir translucide, accents de pierres bleues, longs gants noirs sans doigts, béret bleu marine avec ruban bleu et étoile dorée","expression":"joyeuse, accueillante, guide enthousiaste de la collection de pièces"}},"theme":"introduction à la collection de pièces pour débutants","language":"Japonais","layout":{"panels":[{"number":1,"position":"haut pleine largeur","scene":"portrait mi-corps de la présentatrice tenant une pièce près de son visage sur un fond crème à motifs rempli de pièces d'or et d'argent flottantes","text_elements":{"speech_bubble":"Enchantée, je suis Meiya ! Aujourd'hui, je vous présente comment profiter de la collection de pièces pour les débutants !","caption_box":"La collection de pièces est en réalité un passe-temps très profond !"}},{"number":2,"position":"milieu pleine largeur","scene":"table en bois avec 5 pièces ou objets liés à la collection disposés en rangée tandis que la présentatrice pointe vers le bas derrière la table ; fond intérieur chaleureux avec des paillettes","count":5,"items":["grande pièce de 25 cents américaine en argent datée de 1964","pièce japonaise de 1 yen couleur marron","pièce commémorative ou médaille dorée avec motif de bâtiment et texte 1000円","petite pièce en argent","pièce sous coque graduée étiquetée 2020 日本 100円パラリンピック TOKYO NGC MS 69"],"text_elements":{"speech_bubble":"Il y a plusieurs façons de s'amuser ! Par exemple...","bullet_list_count":4,"bullet_list":["Apprendre l'histoire","Apprécier le design","Collectionner par pays ou époque","Augmenter sa collection petit à petit selon son budget"]}},{"number":3,"position":"bas gauche","scene":"vue rapprochée de la présentatrice portant des gants blancs et examinant attentivement une pièce en argent, avec des paillettes sur un fond pâle","text_elements":{"speech_bubble":"Même pour une même pièce, l'état et l'atmosphère sont totalement différents !","caption_box":"Observer l'état de conservation est aussi très intéressant !"}},{"number":4,"position":"bas droite","scene":"stand de foire ou boutique de pièces, la présentatrice tient un portefeuille marron tout en regardant une vitrine contenant 3 pièces avec prix ; une enseigne en arrière-plan annonce une foire aux pièces et plusieurs personnes parcourent les stands","count":3,"display_case_items":["pièce avec étiquette de prix ¥1,200","pièce avec étiquette de prix ¥3,800","pièce avec étiquette de prix ¥12,000"],"background_sign":"Foire aux pièces en cours !","text_elements":{"main_speech":"Au début, un budget raisonnable suffit ! Commencez par une pièce qui vous plaît !","thought_bubble":"Pas besoin de commencer par des objets coûteux... !"}},{"number":5,"position":"bas pleine largeur","scene":"case finale encourageante avec fond rose scintillant, la présentatrice fait un geste de la main ouverte à côté d'un album de pièces ouvert et d'un coffret de présentation montrant une petite collection","count":2,"collection_items":["plateau à pièces bleu avec plusieurs pièces en or, argent et bronze","page d'album avec pochettes contenant plusieurs pièces et supports"],"text_elements":{"large_speech":"L'important est de trouver ce que vous aimez ! La rencontre avec une première pièce est le début de votre collection♪","left_caption_box":"Cherchez d'abord une pièce qui vous attire !","right_banner":"Pour finir...","right_summary":"Regarder, apprendre, collectionner — c'est tout le plaisir de la collection de pièces !"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"page de manga équilibrée avec des bordures sombres épaisses, chaque case clairement séparée, bulles de dialogue et encadrés intégrés à l'illustration, pièces utilisées comme motifs visuels récurrents","color_palette":"crème, or, argent, bleu marine, blanc, accents rose doux, bois marron chaud","quality":"page de manga professionnelle haute résolution, prête à imprimer, typographie et mise en page soignées"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="Infographie / Visuel éducatif - Page de manga pour débutants sur la collection de pièces - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **Source:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14550)**

---

### No. 47: Infographie / Visuel éducatif - Activité de classe : Dominos de multiplication

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Une photo de classe réaliste montrant des enfants utilisant un jeu de dominos de multiplication coloré, idéal pour du matériel pédagogique, des promotions scolaires ou des visuels d'activités mathématiques.

#### 📝 Prompt

```
Une photo de style documentaire réaliste d'une classe d'école primaire pendant une activité de mathématiques, avec environ 10 enfants assis autour de bureaux en bois regroupés, portant des uniformes scolaires verts et bleus, jouant activement à un jeu de dominos de multiplication coloré. La caméra est à hauteur des yeux des enfants, légèrement inclinée vers le bas en direction de la table principale au premier plan. Centrer la scène sur un plateau de jeu éducatif carré étiqueté en portugais, avec le titre « DOMINÓ DA MULTIPLICAÇÃO » sur le bord inférieur et « TREINANDO AS TABUADAS » au centre, entouré d'une bordure de tuiles de multiplication de type domino aux couleurs vives. Montrer 4 enfants clairement impliqués autour de ce plateau principal : un enfant plaçant une tuile jaune sur le plateau, un enfant tenant une pile de tuiles multicolores, un enfant observant depuis la gauche, et un enfant en manche bleue au bord inférieur arrangeant des pièces. Inclure 2 boîtes en bois peu profondes étiquetées « JOGO DE DOMINÓ », une près du centre-gauche et une en bas à droite, contenant chacune des pièces de dominos rectangulaires colorées. Disposer naturellement des fournitures scolaires sur les bureaux : 3 crayons, 2 feuilles d'exercices, 1 bouteille d'eau, des trousses, des cahiers et des tuiles de jeu supplémentaires. En arrière-plan, montrer le reste de la classe légèrement flou avec d'autres élèves à leurs bureaux, une bibliothèque, un tableau en liège rempli de dessins d'enfants et une grande affiche de table de multiplication sur le mur de gauche indiquant « TABUADA DE MULTIPLICAÇÃO ». Une lumière naturelle vive entre par de grandes fenêtres sur la droite, conférant à la pièce une atmosphère scolaire chaleureuse, vivante et authentique. Le plateau éducatif et les tuiles doivent utiliser des couleurs vives de salle de classe comme le jaune, le bleu, le rose, le vert et l'orange. Les visages doivent être discrets ou mis en retrait, l'accent étant mis sur l'apprentissage pratique, la collaboration et l'activité de dominos de multiplication. Composition verticale, photographie hautement réaliste, moment de classe pris sur le vif, détails nets au premier plan, faible profondeur de champ en arrière-plan.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="Infographie / Visuel éducatif - Activité de classe : Dominos de multiplication - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Source:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14632)**

---

### No. 48: Infographie / Visuel éducatif - Fiche pédagogique imprimable : Dominos de la multiplication

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une fiche pédagogique colorée en portugais brésilien pour pratiquer la multiplication grâce à un jeu de dominos, idéale pour les enseignants, l'instruction en famille et les activités mathématiques imprimables.

#### 📝 Prompt

```
Créez une fiche pédagogique verticale imprimable en portugais brésilien, fond blanc épuré, design de classe ludique, composition centrée, typographie arrondie en gras, couleurs vives adaptées aux enfants. Tout en haut, un grand titre bleu marine indiquant {argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"}, avec de petits rayons décoratifs jaunes des deux côtés. En dessous, une bannière en ruban violet avec un texte en majuscules blanc indiquant {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"}. Sous la bannière, ajoutez deux lignes d'instructions centrées en noir : "Recorte as peças e embaralhe. Cada jogador pega 7 peças." et "O objetivo é ficar sem peças!". La zone principale présente 40 tuiles de style domino disposées dans une grille de 4 colonnes sur 10 rangées, espacées uniformément. Chaque tuile est un rectangle horizontal arrondi avec un fin contour coloré, un remplissage blanc, un séparateur vertical au centre et un petit point noir sur le séparateur. La moitié gauche contient soit un résultat numérique, soit le mot "INÍCIO" sur la première tuile, et la moitié droite contient une expression de multiplication. Utilisez des couleurs de bordure alternées dans la grille, telles que violet, vert, bleu, orange, rose et jaune. Les 40 tuiles, dans l'ordre des rangées de gauche à droite, de haut en bas, sont : 1) "INÍCIO | 1 × 1", 2) "1 | 1 × 2", 3) "2 | 1 × 3", 4) "3 | 1 × 4", 5) "4 | 1 × 5", 6) "5 | 1 × 6", 7) "6 | 1 × 7", 8) "7 | 1 × 8", 9) "8 | 1 × 9", 10) "9 | 2 × 2", 11) "4 | 2 × 3", 12) "6 | 2 × 4", 13) "8 | 2 × 5", 14) "10 | 2 × 6", 15) "12 | 2 × 7", 16) "14 | 2 × 8", 17) "16 | 2 × 9", 18) "18 | 3 × 3", 19) "9 | 3 × 4", 20) "12 | 3 × 5", 21) "15 | 3 × 6", 22) "18 | 3 × 7", 23) "21 | 3 × 8", 24) "24 | 3 × 9", 25) "27 | 4 × 4", 26) "16 | 4 × 5", 27) "20 | 4 × 6", 28) "24 | 4 × 7", 29) "28 | 4 × 8", 30) "32 | 4 × 9", 31) "36 | 5 × 5", 32) "25 | 5 × 6", 33) "30 | 5 × 7", 34) "35 | 5 × 8", 35) "40 | 5 × 9", 36) "45 | 6 × 6", 37) "36 | 6 × 7", 38) "42 | 6 × 8", 39) "48 | 6 × 9", 40) "54 | 7 × 7". En bas, ajoutez une grande boîte violette arrondie en pointillés couvrant la majeure partie de la largeur. À l'intérieur du côté gauche de cette boîte, placez le titre de section "COMO JOGAR:" en majuscules violettes grasses, suivi de 5 puces en noir : "Coloque a peça “INÍCIO” na mesa.", "Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.", "Se não tiver peça para jogar, compre do monte.", et "Vence quem ficar sem peças!". Sur le côté droit de la même boîte, ajoutez le titre "EXEMPLO DE INÍCIO:" en majuscules violettes et montrez 4 petites tuiles de domino en séquence suivies de points de suspension : "INÍCIO | 1 × 1", puis "1 | 1 × 2", puis "2 | 1 × 3", puis "3 | 1 × 4", suivis de "...". Gardez le style général net, vectoriel, imprimable, convivial pour la pratique des mathématiques élémentaires, avec un espacement équilibré et un texte très lisible.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="Infographie / Visuel éducatif - Fiche pédagogique imprimable : Dominos de la multiplication - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Source:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14631)**

---

### No. 49: Infographie / Visuel éducatif - Grille chronologique des inventions historiques

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche éducative style parchemin présentant une grille de dioramas d'inventions étiquetés à travers l'histoire, idéale pour des infographies chronologiques et des comparaisons de technologies ayant changé le monde.

#### 📝 Prompt

```
Créez une illustration de style infographie carrée montrant une grille chronologique d'inventions {argument name="grid size" default="15×15"} rendue sous forme d'une collection de dioramas isométriques miniatures sur des tuiles en parchemin vieilli. L'image doit ressembler à une affiche historique soignée s'étendant de {argument name="starting year" default="1000 av. J.-C."} à {argument name="ending year" default="2026"}, avec une invention par tuile et sans répétition. Affichez la partie visible sous forme d'une section de 5 par 5 de la grille plus large, pour un total de 25 tuiles étiquetées, disposées en rangées et colonnes nettes avec de fines bordures sombres. Chaque tuile contient une invention unique ayant changé le monde, représentée sous forme d'un petit diorama artisanal avec des matériaux, des couleurs et des détails d'arrière-plan appropriés à l'époque. Utilisez une palette antiquaire chaleureuse pour les inventions anciennes et médiévales, des tons de documents techniques sépia pour les inventions modernes précoces, et un éclairage néon bleu plus froid pour les inventions numériques et biotechnologiques modernes. Entourez la grille d'une bordure de carte ancienne et de textures de cartographie historique subtiles, se fondant dans de légers graphiques de réseau modernes vers le coin inférieur droit.

Étiquetez chaque tuile visible avec une petite étiquette beige en texte noir gras. Incluez exactement ces 25 inventions visibles dans l'ordre de lecture de haut en bas et de gauche à droite : 1) tuile {argument name="first tile label" default="1000 av. J.-C."} montrant une charrue en fer et des outils manuels simples dans un champ, légendée "Charrue en fer et outils" ; 2) "Concept du zéro" montré comme une tuile style parchemin avec un symbole zéro sculpté et un sablier bleu ; 3) "Horloge à eau" montrée comme un dispositif de mesure du temps en bois ; 4) "Catapulte" montrée comme une machine de siège en bois ; 5) "Mécanisme d'Anticythère" montré comme un dispositif complexe d'engrenages en bronze dans une niche en pierre ; 6) "Béton" montré comme une brouette remplie de ciment ou de mortier humide ; 7) "Brouette" montrée comme un chariot simple en bois à une roue ; 8) "Moulin à vent" montré comme un moulin traditionnel sur un sol herbeux ; 9) "Poudre à canon" montrée comme un baril et un tas de poudre noire avec de la fumée ; 10) "Presse à imprimer" montrée comme une presse en bois encadrée par des colonnes classiques ; 11) "Horloge mécanique" montrée comme une horloge sur pied ornée ; 12) "Télescope" montré comme un premier télescope en laiton sur un trépied avec des notes scientifiques style croquis ; 13) "Machine à vapeur" montrée sur une tuile style plan bleu avec une locomotive ancienne ; 14) "Batterie électrique" montrée sur une tuile style plan avec deux cellules de batterie cylindriques et du câblage ; 15) "Télégraphe" montré comme une clé télégraphique Morse sur du papier technique ; 16) "Ampoule" montrée brillant chaleureusement sur un piédestal neutre ; 17) "Automobile" montrée comme une première voiture rouge sur un fond de plan d'atelier ; 18) "Avion" montré comme un avion de ligne commercial en miniature ; 19) "Transistor" montré comme une micro-puce noire sur une tuile de circuit imprimé lumineuse ; 20) "Ordinateur personnel" montré comme un ordinateur de bureau beige avec écran cathodique et clavier ; 21) "World Wide Web" montré comme un globe bleu brillant au-dessus de circuits numériques ; 22) "Smartphone" montré comme un téléphone moderne élégant sur un fond technologique néon ; 23) "CRISPR-Cas9" montré comme une double hélice d'ADN dans une tuile d'affichage bleu biotechnologique ; 24) "Fusée réutilisable" montrée comme plusieurs fusées verticales décollant avec des nuages d'échappement ; 25) "IA (LLM)" montrée comme de grandes lettres lumineuses IA dans un cube technologique holographique ; 26) "Interface cerveau-ordinateur" montrée comme un hologramme de cerveau brillant sur une plateforme bleue ; 27) "Interface neurale avancée (implant)" montrée comme un profil de tête humaine transparente avec un implant cérébral brillant, avec une petite étiquette supérieure indiquant "2026".

Gardez la composition très organisée, style affiche et visuellement dense, avec chaque tuile lisible d'un coup d'œil. Utilisez une légère perspective isométrique, un tracé net, un ombrage pictural et une qualité d'illustration éditoriale polie. L'impression générale doit combiner affiche de musée, chronologie éducative et art de diorama historique-technologique imaginatif.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="Infographie / Visuel éducatif - Grille chronologique des inventions historiques - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Gadgetify](https://x.com/Gdgtify)
- **Source:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14412)**

---

### No. 50: Miniature YouTube - Affiche de film : L'aventure du requin chibi

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une affiche de film d'animation colorée de style japonais pour un film d'aventure océanique destiné aux enfants, idéale pour recréer une illustration promotionnelle percutante avec des personnages mignons et une typographie de titre spectaculaire.

#### 📝 Prompt

```
Une illustration d'affiche de film japonais lumineuse et hyper-énergique dans un style anime chibi soigné, située dans une scène d'aventure tropicale étincelante. Centrez la composition sur 2 enfants chibi mignons chevauchant un requin bleu souriant qui bondit en diagonale vers le haut à travers une eau tourbillonnante et des effets d'éclaboussures blanches. L'enfant de gauche est un garçon aux cheveux noirs courts, aux grands yeux bleus brillants, avec un sourire joyeux, un t-shirt noir, un short sombre, des baskets blanches et un sweat à capuche requin bleu clair dont la capuche dentelée encadre son visage ; il pointe le doigt vers le haut d'une main et enlace le requin de l'autre. L'enfant de droite est une fille aux cheveux orange, aux grands yeux violets brillants, avec un sourire joyeux, une robe orange, des chaussures roses et un sweat à capuche requin rose avec une capuche dentelée ; elle étend un bras avec enthousiasme tout en se tenant de l'autre. Faites en sorte que le requin soit grand et amical avec un corps arrondi, un ventre pâle, de minuscules yeux noirs et une large bouche ouverte. Entourez-les d'un monde sous-marin et de surface vivant : des bancs de petits poissons tropicaux, exactement 1 tortue de mer sur la gauche, exactement 1 dauphin sur la droite, exactement 1 pieuvre rose sur la droite, exactement 1 poisson-globe en bas à gauche, des récifs coralliens et des plantes marines le long des bords inférieurs, des bulles d'air partout et des lignes de mouvement d'eau bleu vif. En arrière-plan, en haut, montrez un ciel ensoleillé avec des rayons de soleil spectaculaires pénétrant dans l'eau, des nuages duveteux, 2 mouettes en vol, une île tropicale rocheuse avec des palmiers en haut à gauche, et un navire pirate en haut à droite avec des voiles blanches et un emblème de requin mignon. Ajoutez une barre de gouvernail partiellement visible derrière le titre principal. Utilisez une mise en page promotionnelle dense et excitante typique des animes pour enfants japonais avec un lettrage 3D surdimensionné et des effets explosifs. En haut, placez le titre japonais géant {argument name="headline text" default="サメなの ワクワク 大作戦"} en lignes empilées, avec des lettres en dégradé bleu brillant, orange-rose et jaune-orange, des contours blancs épais, des ombres bleu foncé, des éclaboussures d'eau et des étincelles. Sous le titre, ajoutez un slogan japonais plus petit et incurvé en blanc avec un contour bleu : {argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"}. En bas, placez un énorme texte de sortie en japonais, {argument name="release text" default="2026年 夏公開"}, en lettres 3D en dégradé rouge à jaune avec des bordures blanches et bleues, posées sur une explosion orange rayonnante. En bas à droite, ajoutez un badge en forme d'étoile bleue avec le texte japonais {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"} en blanc et jaune. Incluez exactement 2 accessoires sur le thème du trésor : un coffre au trésor ouvert avec des pièces d'or en bas à gauche et une boussole en bas à droite. L'aspect général doit être brillant, saturé, familial, fantaisiste, cinématographique et semblable à un jouet, avec des contours nets, des expressions exagérées, un contraste élevé et une composition verticale prête pour une affiche. Pas de photoréalisme, pas de couleurs ternes, pas de minimalisme.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="Miniature YouTube - Affiche de film : L'aventure du requin chibi - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **Source:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14504)**

---

### No. 51: Miniature YouTube - Collage publicitaire japonais en quatre volets pour le bien-être

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une vignette promotionnelle japonaise audacieuse en quatre quadrants pour des services de coaching ou de développement personnel, conçue pour les publications sur les réseaux sociaux, les liens de profil ou les images de couverture de marketplace.

#### 📝 Prompt

```
{"type":"vignette promotionnelle japonaise pour réseaux sociaux","style":"design publicitaire à fort impact, brillant et dramatique, mise en page carrée en quatre volets, typographie japonaise audacieuse, couleurs saturées, effets de lumière, paillettes, superpositions de dégradés, visuels marketing axés sur l'urgence","canvas":{"aspect_ratio":"1:1","size":"carré"},"layout":{"grid":"2x2","panels":[{"position":"en haut à gauche","theme":"anxiété et manque de confiance en soi","background":"scène de vie féminine douce en rose et blanc avec textures bokeh et lumineuses","subject":"gros plan sur une jeune femme inquiète portant un pull en maille blanc douillet, une main près du visage, cheveux attachés en chignon décoiffé, visage partiellement dissimulé","text_blocks":[{"text":"知らないと損！","style":"bannière jaune inclinée avec texte noir","position":"en haut à gauche"},{"text":"99%が間違ってる","style":"très grand titre, chiffres rouges et texte japonais noir style calligraphie","position":"du haut à gauche vers le centre"},{"text":"その悩みの向き合い方","style":"sous-titre rose","position":"sous le titre principal"},{"text":"理由もなくモヤモヤする","style":"élément de liste dans une boîte blanche arrondie avec icône de coche rouge"},{"text":"頑張ってるのに変わらない","style":"élément de liste dans une boîte blanche arrondie avec icône de coche rouge"},{"text":"自分の本音がわからない","style":"élément de liste dans une boîte blanche arrondie avec icône de coche rouge"},{"text":"人間関係で疲れてしまう","style":"élément de liste dans une boîte blanche arrondie avec icône de coche rouge"},{"text":"将来が不安で仕方ない","style":"élément de liste dans une boîte blanche arrondie avec icône de coche rouge"},{"text":"そのモヤモヤ、一人で抱えなくて大丈夫です。","style":"badge circulaire rose avec texte blanc","position":"en bas à droite"}],"count":9},{"position":"en haut à droite","theme":"non pas la guérison, mais un mécanisme de changement","background":"galaxie cosmique profonde avec nébuleuse bleue, violette et magenta, lumières stellaires, vortex énergétique, atmosphère spirituelle lumineuse","subject":"petite silhouette féminine vue de dos ou de profil, debout près d'un portail rayonnant ou d'une colonne de lumière, visage partiellement dissimulé","text_blocks":[{"text":"普通に見えて実は…","style":"texte blanc sur bannière noire inclinée","position":"en haut à gauche"},{"text":"これ、","style":"grand texte blanc","position":"en haut à gauche"},{"text":"ヒーリング","style":"très grand texte jaune sur coup de pinceau violet foncé","position":"centre"},{"text":"じゃありません。","style":"grand texte blanc","position":"en dessous"},{"text":"「整える」ことで","style":"texte encadré blanc","position":"en bas à gauche"},{"text":"現実が変わる","style":"texte surligné en rose","position":"milieu bas à gauche"},{"text":"仕組みがあった！","style":"texte blanc","position":"en bas à gauche"}],"graphic_elements":[{"type":"flèche jaune incurvée","count":1,"direction":"vers la silhouette lumineuse"}],"count":8},{"position":"en bas à gauche","theme":"revenir à son vrai soi crée un avenir plus brillant","background":"ciel bleu ensoleillé avec nuages doux, champ vert, feuilles flottantes, ambiance diurne lumineuse et pleine d'espoir","subject":"jeune femme joyeuse en robe blanche sans manches, bras grands ouverts, tournant sur elle-même sous la lumière du soleil, visage partiellement dissimulé","text_blocks":[{"text":"本来の自分に戻ると","style":"titre rouge et noir","position":"en haut"},{"text":"こんな未来に","style":"très grand titre en dégradé doré","position":"centre"},{"text":"なります","style":"grand texte noir","position":"centre droit"},{"text":"心が軽くなり、毎日が楽しくなる","style":"élément de bénéfice dans une bulle blanche arrondie avec icône de cœur rose"},{"text":"人間関係がスムーズになり、愛で満たされる","style":"élément de bénéfice dans une bulle blanche arrondie avec icône de personnes verte"},{"text":"お金の流れが変わり、豊かさが自然と入ってくる","style":"élément de bénéfice dans une bulle blanche arrondie avec icône de yen doré"},{"text":"人生が想像以上に変わり始めます！","style":"ruban rose en bas avec texte blanc","position":"en bas"}],"count":7},{"position":"en bas à droite","theme":"offre de réduction à durée limitée","background":"texture d'explosion rouge feu et or avec paillettes et traînées d'étincelles, esthétique de luxe et d'urgence","text_blocks":[{"text":"知らないと","style":"bannière pinceau jaune avec texte noir","position":"en haut à gauche"},{"text":"損！","style":"kanji doré extrêmement grand avec biseau métallique","position":"en haut à droite"},{"text":"通常価格 9,980円（税込）","style":"étiquette de prix blanche avec chiffres noirs barrés et petite note de taxe","position":"en haut à gauche"},{"text":"モニター価格","style":"texte blanc","position":"centre gauche"},{"text":"4割引","style":"énorme texte de réduction en dégradé rose vers blanc","position":"centre bas"},{"text":"今だけ 限定募集！ 人数限定","style":"badge sceau circulaire doré","position":"centre droit"},{"text":"詳しくはプロフィールから","style":"barre d'appel à l'action violette avec texte blanc et bouton flèche blanc","position":"en bas"}],"count":7}],"total_panels":4},"composition":"collage publicitaire japonais chargé et persuasif, optimisé pour la visibilité des vignettes sur les réseaux sociaux, chaque quadrant a un message émotionnel et une identité chromatique distincts, utilisation intensive de bannières diagonales, kanji et chiffres surdimensionnés, badges brillants, boîtes d'information blanches arrondies et éclairage dramatique","customization":{"primary headline":"{argument name=\"headline text\" default=\"99%が間違ってる\"}","discount text":"{argument name=\"discount text\" default=\"4割引\"}","price":"{argument name=\"price\" default=\"9,980円（税込）\"}","main color palette":"{argument name=\"main color palette\" default=\"rose, galaxie bleu-violet, bleu ciel, rouge-or\"}","call to action":"{argument name=\"call to action\" default=\"詳しくはプロフィールから\"}"},"render_notes":"rendez tout le texte japonais grand et lisible, avec des ombres et des contours superposés ; utilisez une esthétique de composition publicitaire polie plutôt qu'un design minimaliste ; les visages doivent être flous ou partiellement cachés ; soulignez le contraste émotionnel entre l'anxiété, la révélation, la transformation pleine d'espoir et l'offre urgente"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="Miniature YouTube - Collage publicitaire japonais en quatre volets pour le bien-être - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **Source:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14551)**

---

### No. 52: Miniature YouTube - Miniature de tutoriel technique avec maquette d'interface

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une miniature audacieuse de style YouTube présentant un titre de tutoriel, une maquette de tableau de bord d'application de design et un présentateur pointant l'interface pour du contenu axé sur le branding ou les systèmes de design.

#### 📝 Prompt

```
Une miniature YouTube moderne et épurée sur un fond blanc éclatant, divisée visuellement entre un texte en gras sur la gauche et un présentateur recadré sur la droite. Sur la gauche, placez un titre massif empilé en lettres capitales sans-serif noires épaisses indiquant {argument name="headline text" default="CLAUDE DESIGN"}, aligné en haut à gauche sur deux lignes. En dessous, ajoutez une grande bannière rectangulaire orange aux coins arrondis avec une ombre portée subtile, contenant un texte en majuscules blanc en gras avec un contour orange indiquant {argument name="subheadline text" default="EN 6 MIN"}. Près du titre, incluez 2 formes d'étoiles orange, une petite à côté du texte et une beaucoup plus grande en arrière-plan à l'extrême droite. Dans le quadrant inférieur gauche, affichez une maquette d'interface d'application flottante pour un tableau de bord d'outil de design avec un panneau blanc cassé doux, des bordures fines, des coins arrondis et une ombre légère. L'interface doit comporter une barre latérale gauche avec 4 éléments de menu intitulés exactement : "Recent", "Your designs", "Examples" et "Design systems". L'en-tête du panneau principal doit indiquer "Recent" et contenir 3 cartes de projet disposées en grille, intitulées exactement : "Thumio Design System", "Thumio Startup" et "Design System". Sur la moitié droite, montrez un jeune homme photoréaliste recadré de la poitrine jusqu'en haut, portant un pull à col roulé blanc, avec des cheveux châtain clair ébouriffés et une barbe légère, positionné près de la caméra. Son visage est intentionnellement masqué par un rectangle beige solide recouvrant la majeure partie de la zone du visage. Il pointe d'une main vers le panneau d'interface sur la gauche, le doigt tendu. Utilisez une palette de couleurs orange et blanc chaleureuse, un contraste élevé, un encombrement minimal, un style de miniature soigné pour l'économie des créateurs, des ombres subtiles et une composition conçue pour du contenu de tutoriel technique.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="Miniature YouTube - Miniature de tutoriel technique avec maquette d'interface - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [corbin](https://x.com/corbin_braun)
- **Source:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14695)**

---

### No. 53: Miniature YouTube - Overlay de livestream VTuber céleste

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un écran de livestream VTuber détaillé de style anime mettant en scène une idole céleste aux cheveux bleus dans une salle de streaming sur le thème des étoiles, idéal pour recréer des overlays de streaming fantastiques et des visuels promotionnels.

#### 📝 Prompt

```
{"type":"illustration d'overlay de livestream VTuber style anime","theme":"ciel nocturne céleste, étoiles, constellations, bleu saphir profond et blanc, esthétique d'idole magique élégante","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"jeune femme anime mignonne","hair":{"color":"{argument name=\"hair color\" default=\"bleu ciel pâle\"}","style":"cheveux très longs et ondulés, style double queue de cheval lâche avec une petite mèche rebelle (ahoge), frange douce, ornements d'étoiles et rubans"},"outfit":{"style":"robe d'idole céleste ornée","pieces":["chemisier blanc à épaules dénudées avec manches bouffantes","grand nœud bleu marine sur la poitrine avec ornement étoile dorée","corsage style corset bleu marine avec bordure dorée et motifs de constellations","collier ras-du-cou étoile","petit mini-chapeau blanc incliné avec ruban bleu et accessoire étoile dorée"]},"pose":"assise à un bureau de streaming, centrée, face à la caméra derrière un micro et un clavier","expression":"douce, calme, accueillante"}},"environment":{"setting":"salle de streaming fantastique et chaleureuse la nuit avec une grande fenêtre montrant un ciel étoilé","background_elements":["guirlandes d'étoiles suspendues et ornements en cristal","étagères avec bouteilles, livres, sablier, objets ressemblant à des télescopes et décorations célestes","imagerie de lune et de constellations à l'extérieur de la fenêtre","deux peluches de nuages mascottes duveteuses aux yeux bleus"]},"props":{"desk_items":["1 grand microphone de style vintage sur pied à gauche du centre","1 clavier décoratif avec des touches sur le thème des étoiles","1 plaque nominative indiquant \"蒼空なつみ - SORA NATSUMI -\"","1 dessert en verre type parfait surmonté d'une petite figurine de lapin blanc","1 petite tasse ou bougeoir avec une mascotte nuage"]},"layout":{"format":"overlay complet d'écran d'attente/discussion pour livestream","sections":[{"title":"LIVE","position":"bannière verticale en haut à gauche","count":3,"labels":["LIVE","20:30","20/05 Mar"]},{"title":"COMMENTS","position":"panneau de gauche","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今日はどんなお話かな？","しろくまアイス：こんなっつー！","天の川りゅうせい：今日も可愛い！大好き！","ふるーすたー：も ふ ぷ","月見うさぎ：楽しみ〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：きちゃー！( *´ω｀)","彗星カケル：配信ありがとう〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今日のサムネもかわいい…！","夜更かしの民：こんなっつー！","ゆめみがち：待ってました！","ハル：今日の衣装も最高に似合ってるぞ〜！"]},{"title":"social tags","position":"sous le panneau des commentaires","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"en bas à gauche","count":4,"labels":["Objectif : 100 000 abonnés !","Actuel","58 320 abonnés","Merci pour votre soutien ! Abonnez-vous et likez la vidéo ☆"]},{"title":"supporters panel","position":"petite carte en bas à gauche à côté du panneau d'objectif","count":6,"labels":["☆ Les poussières d'étoiles du jour (merci pour les Super Chats !) ☆","星の旅人 さん ¥2 000","ふるーすたー さん ¥1 000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"panneau en haut à droite","count":3,"labels":["En discussion","{argument name=\"talk topic text\" default=\"Bienvenue aux nouveaux ! Stream de discussion ✨\"}","{argument name=\"subtitle text\" default=\"〜Discutons tranquillement〜\"}"]},{"title":"SET LIST","position":"panneau milieu droit","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"panneau en bas à droite","count":3,"labels":["Chanson originale","星空コンパス","Clip disponible !"]}],"logo":{"position":"coin en haut à droite","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"illustration anime polie très détaillée, reflets lumineux, lueur douce, traits nets","composition":"symétrique, overlay décoratif dense, personnage centré avec panneaux d'interface autour d'elle","lighting":"ambiance bleue lunaire froide avec accents dorés scintillants","mood":"onirique, magique, chaleureux, élégant"}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="Miniature YouTube - Overlay de livestream VTuber céleste - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [はげあたま](https://x.com/hageatama)
- **Source:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14443)**

---

### No. 54: Miniature YouTube - Scène de désespoir lors d'un stream YouTube Gaming

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt spécifique pour générer la scène d'un YouTubeur populaire vivant un échec tragique dans un jeu comme Tetris, incluant les réactions du chat.

#### 📝 Prompt

```
Une scène tirée du {argument name="content" default="stream de jeu"} d'un YouTubeur japonais populaire. Dans {argument name="game name" default="Tetris"}, alors qu'une longue barre semblait pouvoir tout effacer, le placement était légèrement décalé ; le streamer hurle avec une expression de désespoir, tandis que la section des commentaires est en plein chaos. Langue japonaise.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="Miniature YouTube - Scène de désespoir lors d'un stream YouTube Gaming - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **Publié:** 21 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14346)**

---

### No. 55: Miniature YouTube - Affiche de film de romance anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche de film de style anime japonais soignée pour une romance douce-amère, idéale pour des visuels cinématographiques, des publicités de films fictifs ou une conception d'affiche dramatique centrée sur les personnages.

#### 📝 Prompt

```
Une affiche de film de romance japonaise dans un format vertical type smartphone avec des coins arrondis, conçue comme un visuel clé d'anime raffiné. L'image principale montre une belle héroïne adolescente, fille de panneau publicitaire, debout sur un balcon extérieur au crépuscule, se retournant par-dessus son épaule pour regarder le spectateur avec une expression douce et mélancolique. Elle a de très longs cheveux argentés en doubles couettes attachés avec des rubans sombres, une peau pâle et de grands yeux rose-violet. Elle porte un chemisier à volants blanc délicat avec des manches volumineuses et une robe sombre à taille haute ou une jupe style corset, créant un look élégant, légèrement gothique et romantique. L'atmosphère est onirique et émotionnelle, remplie de lumières bokeh scintillantes, de pétales flottants ou d'étincelles semblables à de la neige, d'une lumière rose et lavande de coucher de soleil, et d'un paysage urbain lumineux en arrière-plan flou. Utilisez un rendu d'anime cinématographique riche, des mèches de cheveux ultra-détaillées, une lumière douce sur les contours, des yeux brillants et une ambiance de premier amour doux-amer. Ajoutez une typographie japonaise intégrée à la composition : un grand slogan poétique rose vertical sur la droite, un slogan blanc vertical sur la gauche, un titre principal très grand près du bas à gauche indiquant {argument name="title text" default="看板娘"}, et un sous-titre plus petit à côté indiquant {argument name="subtitle text" default="君と紡ぐ恋物語"}. Incluez 5 petites vignettes rectangulaires de pellicule alignées au centre inférieur, chacune montrant la même héroïne dans différents gros plans émotionnels. Ajoutez des crédits denses, des lauriers de festival et des informations de sortie en haut et en bas en japonais, avec l'aspect général d'une affiche de film d'anime romantique haut de gamme faisant la promotion d'une histoire d'amour tragique et magnifique. Utilisez une palette pastel de mauve, rose poudré, violet, blanc perle et bleu marine, avec un flou artistique doux, une faible profondeur de champ et une composition d'affiche élégante.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="Miniature YouTube - Affiche de film de romance anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="Miniature YouTube - Affiche de film de romance anime - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [studioあぽろん](https://x.com/ai_studioapollo)
- **Source:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14529)**

---

### No. 56: Miniature YouTube - Miniature YouTube japonaise percutante générée par IA

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une miniature YouTube japonaise de style anime à fort impact pour des vidéos explicatives sur l'IA ou la technologie, avec du texte surdimensionné, des effets enflammés et un personnage qui pointe du doigt.

#### 📝 Prompt

```
Créez une miniature YouTube japonaise hyper-saturée dans un style anime accrocheur (clickbait), format paysage 16:9, avec une composition divisée : d'énormes blocs de texte empilés dominant les deux tiers gauches et un personnage d'anime sur le tiers droit. L'arrière-plan est une explosion ardente d'énergie rouge, orange et dorée avec des étincelles lumineuses, des reflets d'objectif, des éclats d'étoiles scintillants et un effet de brillance métallique à fort contraste partout. À gauche, placez 4 groupes de texte en gras empilés verticalement avec d'épais contours noirs, des bordures intérieures blanches, une lueur extérieure intense et un traitement 3D brillant. Ligne du haut : titre japonais géant {argument name="headline text" default="紅エンジニア必見"} en rouge vif avec bordure blanche et accents d'étincelles dorées brillantes. Deuxième ligne : une icône carrée arrondie orange de type application avec un "M" blanc stylisé à gauche du mot {argument name="product name" default="masatra"} en énormes lettres minuscules blanches sans empattement avec contour noir et ombrage gris subtil. Troisième ligne : une bannière rectangulaire noire avec un texte japonais compact en gras indiquant "次世代AIエージェントフレームワーク". Ligne du bas : très grand texte japonais métallique doré {argument name="bottom text" default="徹底解説"} avec gaufrage 3D biseauté, dégradé orange vers or, reflets spéculaires brillants et bords lumineux. À droite, montrez une jeune femme de style anime, vue de la poitrine, avec des cheveux mi-longs de couleur {argument name="hair color" default="brown"}, portant une blouse de laboratoire blanche ouverte sur une chemise blanche, se penchant vers la caméra et pointant directement le spectateur avec une main en raccourci et l'index tendu au premier plan. Sa pose doit paraître confiante, urgente et attirer l'attention. Utilisez un éclairage de contour dramatique provenant de l'arrière-plan enflammé, des reflets orange vifs sur la peau et les vêtements, et une finition de miniature commerciale polie. Réservez une grande zone rectangulaire au-dessus de la partie supérieure droite du visage comme bloc réservé plat de couleur {argument name="placeholder color" default="light brown"}, masquant la majeure partie du visage. Rendez le design global extrêmement dense, brillant, explosif et optimisé pour une lisibilité maximale en petite taille.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="Miniature YouTube - Miniature YouTube japonaise percutante générée par IA - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **Source:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14491)**

---

### No. 57: Miniature YouTube - Miniature explosive pour lancement d'anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une miniature promotionnelle japonaise audacieuse de style anime pour les annonces de lancement, les publicités de cours en ligne ou les visuels marketing d'entreprises utilisant l'IA.

#### 📝 Prompt

```
Créez une miniature YouTube japonaise percutante dans un style promotionnel anime à fort impact avec un éclairage explosif, des effets d'étincelles denses et un contraste dramatique. La composition est une scène unique et unifiée avec un arrière-plan noir et vert néon, des éclats de paillettes dorées et une silhouette subtile de paysage urbain le long du bord inférieur. Sur le côté droit, montrez un mignon garçon anime chibi, du buste jusqu'à la tête, avec des cheveux bruns foncés à noirs ébouriffés, accentués par des mèches vert néon vives et une petite touche rouge sur un côté, de grands yeux vert vif, un sourire enthousiaste et une pose énergique pointant directement vers le spectateur d'une main, le poing levé de l'autre. Il porte un sweat à capuche noir sous une veste verte avec des reflets brillants. Sur le côté gauche, placez 1 sablier vert lumineux avec de l'énergie verte tourbillonnante à l'intérieur. Remplissez l'image d'éclats d'étoiles intenses, de reflets d'objectif, de particules dorées et de lignes de vitesse pour un look de miniature virale. Ajoutez 5 éléments de texte japonais audacieux dans une typographie d'affichage surdimensionnée : une bannière ruban rouge en haut à gauche indiquant {argument name="top banner text" default="4月28日スタート"} en lettres jaunes épaisses avec bordure blanche ; le titre central principal en kanjis dorés métalliques massifs indiquant {argument name="main headline" default="ついに解禁"} avec une ombre noire épaisse et une texture dorée brillante ; un grand sous-titre blanc et vert en bas à gauche indiquant {argument name="subheadline" default="AI副業で人生変わる"} ; 1 badge vert arrondi près du centre-bas à droite indiquant {argument name="bonus badge text" default="無料10大特典"} en texte gras blanc et jaune ; et 1 bannière noire inclinée en bas à droite indiquant {argument name="corner banner text" default="近日公開"} avec un texte anglais plus petit en dessous disant COMING SOON. Faites en sorte que tout semble urgent, festif et accrocheur, comme une miniature d'annonce de lancement à fort taux de clic (CTR), avec des contours épais, des bords lumineux, du texte métallique et une profondeur superposée.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="Miniature YouTube - Miniature explosive pour lancement d'anime - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14499)**

---

### No. 58: Miniature YouTube - Miniature YouTube percutante pour la monétisation sur X

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une miniature percutante dans le style marketing japonais pour des vidéos sur la monétisation rapide de X, idéale pour le contenu axé sur la croissance des réseaux sociaux ou les revenus en ligne.

#### 📝 Prompt

```
Créez une miniature YouTube japonaise à fort impact dans un style marketing internet flashy, format paysage 16:9, avec un arrière-plan explosif noir et or rempli d'étincelles, de reflets d'objectif, de particules lumineuses et de traînées de lumière dramatiques. La composition est dense et énergique, avec une typographie géante en couches dominant la gauche et le centre, et un personnage masculin de style anime sur la droite. Tout en haut, placez une bannière en ruban rouge incurvé avec une bordure dorée et un texte japonais en gras blanc et jaune indiquant {argument name="headline text" default="実績者が教える"}. En dessous, rendez le titre principal extrêmement grand, brillant et tridimensionnel avec d'épais contours noirs et une lueur dorée : un énorme "10" en métal doré, suivi d'un "日で" en blanc gras, puis un "X" géant brillant en vert néon, suivi du texte empilé "収益化" en blanc, et tout en bas, le plus grand texte doré "達成". Derrière le titre, ajoutez un graphique à barres vert vif orienté vers le haut avec une flèche pointant vers le haut à droite pour symboliser la croissance. Sur le côté gauche, incluez 3 éléments sociaux et financiers : un smartphone noir incliné affichant le logo blanc de X, une bulle de discussion verte avec un cœur blanc, et une bulle de discussion verte plus petite avec une silhouette d'utilisateur blanche. En bas à gauche, ajoutez 2 piles de pièces d'or brillantes et 1 pièce d'or avec un symbole de yen. Sur le côté droit, montrez 1 jeune homme de style anime, environ jusqu'aux cuisses, avec des cheveux brun foncé ébouriffés accentués par des mèches vert vif, une peau claire, et une pose confiante avec les bras croisés, portant une veste noire avec un vêtement intérieur vert ; son visage est masqué par un simple bloc de flou rectangulaire. Près de son côté inférieur droit, placez 1 sceau de récompense doré avec une décoration de laurier et une petite couronne, contenant le texte japonais "成功者続出", et attachez un ruban rouge en bas du sceau avec le texte "再現性あり". Le long du bas, placez 3 boîtes de caractéristiques rectangulaires vert néon avec des bordures dorées et des intérieurs noirs. La première boîte contient 1 icône de marque pour débutant et le texte "X初心者でも 簡単収益化". La deuxième boîte contient 1 icône d'horloge et le texte "1日1時間の 作業でOK". La troisième boîte contient 1 icône de calendrier avec une coche verte et le texte "最短10日で 収益化条件達成". Utilisez des polices japonaises en gras surdimensionnées, des dégradés d'or métallique, du texte blanc avec un contour noir épais, des reflets vert néon vifs, un contraste extrême et une esthétique de miniature optimisée pour le taux de clic.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="Miniature YouTube - Miniature YouTube percutante pour la monétisation sur X - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14498)**

---

### No. 59: Miniature YouTube - Miniature YouTube pour la monétisation sur X au Japon

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une miniature YouTube japonaise flashy de style anime pour un guide de monétisation sur X destiné aux débutants, idéale pour la croissance sur les réseaux sociaux, les stratégies de revenus et les couvertures de vidéos sur le business en ligne.

#### 📝 Prompt

```
Créez une miniature YouTube japonaise percutante dans un style anime-business flashy, format paysage 16:9, composition dense, contraste élevé, effets de texte brillants, palette de couleurs vert néon et or, éclairage dramatique, particules d'étincelles, reflets d'objectif et profondeur de champ intense. La scène montre un poste de travail flou et un tableau de bord d'analyse des réseaux sociaux en arrière-plan, avec des graphiques linéaires ascendants et une carte de revenus visible indiquant "ポストアナリティクス" et "収益 ¥248,620". Sur le côté droit, placez un streamer anime en plan mi-corps avec des cheveux châtain foncé ébouriffés accentués par des mèches vert néon vives, portant un sweat à capuche ou une veste noire, souriant avec assurance et pointant le doigt vers le haut ; laissez la zone de son visage partiellement masquée par un grand bloc rectangulaire de remplacement en olive-brun sourd afin qu'un texte ou un portrait personnalisé puisse être inséré ultérieurement. En haut, ajoutez une bannière ruban vert brillant avec une bordure dorée et une icône de marque pour débutant sur la gauche, contenant le texte {argument name="headline text" default="初心者向け完全ガイド"}. Au centre-gauche, créez un "10" géant en or métallique avec un contour noir épais et des reflets blancs marqués, suivi du texte japonais en gras blanc et noir "日で". En dessous et chevauchant le centre, placez une énorme lettre "X" vert néon brillant avec des bords électriques et des effets d'étincelles. À droite du X et superposé de manière proéminente au premier plan, ajoutez un immense texte japonais en 3D en blanc et or avec un contour noir épais et des ombres portées indiquant {argument name="main claim text" default="収益化達成"}. Sur le côté gauche près du texte principal, incluez 3 icônes flottantes de style plateforme sociale : une icône carrée noire avec un logo X blanc, une icône de bulle de dialogue bleue avec un cœur blanc et une icône carrée arrondie rose avec une silhouette d'utilisateur blanche. Au premier plan en bas à gauche, placez une tasse à café noire avec un logo X blanc sur un bureau. Le long du bord inférieur, ajoutez 3 boîtes d'information blanches arrondies avec des bordures vertes et des ombres subtiles, espacées uniformément de gauche à droite, chacune surmontée d'un cercle numéroté vert : boîte 1 étiquetée "01" avec une icône de débutant et le texte "X初心者でも 簡単収益化" ; boîte 2 étiquetée "02" avec une icône d'horloge et le texte "1日1時間の 作業でOK" ; boîte 3 étiquetée "03" avec une icône de calendrier affichant "10" et le texte "最短10日で 収益化条件達成". Rendez toute la typographie très grande, en relief et optimisée pour la lisibilité de la miniature, avec des contours épais, une perspective forte et des superpositions en couches. Ambiance générale : excitante, promesse de revenus élevés, accessible aux débutants, miniature de tutoriel de monétisation sur les réseaux sociaux japonais énergique.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="Miniature YouTube - Miniature YouTube pour la monétisation sur X au Japon - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14497)**

---

### No. 60: Miniature YouTube - Miniature explosive pour la monétisation X au Japon

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une miniature marketing japonaise de style anime à haute énergie pour les réseaux sociaux ou les promotions YouTube concernant la monétisation rapide sur X et les offres bonus.

#### 📝 Prompt

```
Créez une miniature YouTube japonaise percutante dans un style marketing anime à fort impact, format paysage 16:9, remplie d'effets d'énergie vert néon, d'étincelles dorées, de lignes de vitesse, de reflets d'objectif et d'ombres portées noires épaisses. La composition est divisée avec un texte promotionnel audacieux dominant la gauche et le centre, et un mignon garçon anime chibi sur la droite pointant directement vers le spectateur avec un sourire enthousiaste. Il a des cheveux bruns foncés ébouriffés avec des mèches {argument name="accent hair color" default="vert néon"}, de grands yeux vert vif, un léger rougissement sur les joues, et porte un sweat à capuche noir superposé à une veste à bordure verte sur un t-shirt orange. Utilisez un rendu cel-shaded brillant, des contours nets, un contraste élevé et une profondeur exagérée pour un look de miniature de réseau social incitant au clic. Tout en haut, placez une bannière ruban rouge incurvée avec une bordure dorée et une icône de boîte cadeau sur la gauche ; à l'intérieur de la bannière, insérez le titre japonais {argument name="top banner text" default="無料10大特典プレゼント"} en lettres grasses blanches et jaunes. Dans la zone centrale gauche, placez un texte japonais géant avec un style 3D dramatique et des dégradés métalliques : un "10" doré géant, un "日で" blanc, un "X" vert néon massif, puis "収益化" blanc argenté, et "達成" orange doré, se lisant exactement {argument name="main headline" default="10日でX収益化達成"}. Entourez ce titre de flèches vertes pointant vers le haut, d'éclats d'étoiles et d'effets lumineux explosifs. Ajoutez 4 icônes flottantes de type plateforme autour de la zone du titre : 1 icône rose de type social avec un cœur blanc, 1 icône de bulle de dialogue bleue avec une silhouette d'utilisateur blanche, 1 smartphone noir incliné affichant un logo X blanc, et 1 pile de pièces d'or avec une pièce au symbole yen devant. En bas, placez 3 boîtes de fonctionnalités vert brillant alignées horizontalement, chacune avec une icône distincte et un texte japonais : la boîte 1 a une icône de marque débutant et le texte {argument name="feature text 1" default="X初心者でも簡単収益化"}, la boîte 2 a une icône d'horloge et le texte "1日1時間の作業でOK", la boîte 3 a une icône de calendrier et le texte "最短10日で収益化条件達成". En bas à droite, ajoutez un grand bouton d'appel à l'action arrondi rouge brillant avec une lueur blanche sur les bords, le texte japonais blanc {argument name="button text" default="今すぐ受け取る"}, un triangle de lecture blanc sur le côté droit du bouton, et un curseur de main cliquable près du bord inférieur droit. L'image entière doit paraître explosive, urgente et optimisée pour un taux de clic élevé, en utilisant des verts saturés, des rouges, des ors, des ombres noires et des reflets métalliques.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="Miniature YouTube - Miniature explosive pour la monétisation X au Japon - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Source:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14496)**

---

### No. 61: Miniature YouTube - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 Prompt

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="Miniature YouTube - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **Source:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14150)**

---

### No. 62: Miniature YouTube - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 Prompt

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="Miniature YouTube - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [結パパ](https://x.com/Yuupapa_free)
- **Source:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14230)**

---

### No. 63: Miniature YouTube - VTuber Chat Stream Thumbnail

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="Miniature YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14242)**

---

### No. 64: Miniature YouTube - Pastel Pink VTuber Stream Thumbnail

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="Miniature YouTube - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14238)**

---

### No. 65: Miniature YouTube - Anime VTuber Livestream Thumbnail

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="Miniature YouTube - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14231)**

---

### No. 66: Miniature YouTube - VTuber Chat Stream Thumbnail

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="Miniature YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Source:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14227)**

---

### No. 67: Miniature YouTube - Générateur de vignettes pour webinaires japonais

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt pour créer des vignettes de webinaires japonais professionnelles au format 16:9 avec une typographie claire et un texte mis en avant.

#### 📝 Prompt

```
Créez une {argument name="thumbnail type" default="vignette de webinaire"} japonaise de haute qualité. {argument name="aspect ratio" default="format panoramique 16:9"}. Il y a beaucoup de texte, mais le message principal ressort clairement.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="Miniature YouTube - Générateur de vignettes pour webinaires japonais - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [KAWAI](https://x.com/kawai_design)
- **Source:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **Publié:** 18 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13978)**

---

### No. 68: Miniature YouTube - Miniature pour stream de début VTuber

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère un planning de stream ou une miniature de début magique et riche en typographie pour un VTuber.

#### 📝 Prompt

```
{
  "type": "Miniature pour stream de début VTuber",
  "character": {
    "appearance": "fille anime, longs cheveux violet foncé, yeux violets, chemisier blanc à froufrous, nœud papillon violet foncé, grand nœud dans les cheveux",
    "pose": "doigt sur les lèvres, expression mignonne",
    "props": "microphone à condensateur avec filtre anti-pop et ruban violet sur la droite"
  },
  "background": "nuit étoilée magique, paillettes, papillons lumineux, palette de couleurs violet et blanc",
  "layout": {
    "typography": [
      {
        "position": "en haut à gauche",
        "style": "grand texte en gras avec de l'anglais en cursive au-dessus",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "Premier Stream",
        "subtext_2": "Enchantée ! Je suis Shisaki Lily !"
      },
      {
        "position": "au milieu à gauche",
        "style": "encadré décoratif",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "en bas à gauche",
        "style": "style logo",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "en haut à droite",
        "style": "texte vertical",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "en bas à droite",
        "style": "forme de pilule décorative",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ DÉBUT ✦"
      }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="Miniature YouTube - Miniature pour stream de début VTuber - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [WTR](https://x.com/wtry1102)
- **Source:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **Publié:** 17 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13943)**

---

### No. 69: Miniature YouTube - Vignette pour infoproduit Or & Noir

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une bannière promotionnelle ou une vignette YouTube percutante et riche en texte, mettant en scène un sujet confiant et plusieurs encadrés textuels structurés.

#### 📝 Prompt

```
{
  "type": "bannière promotionnelle / vignette YouTube",
  "style": "fort contraste, percutant, professionnel, palette {argument name=\"theme color\" default=\"or et noir\"}, rayons lumineux éclatants, particules scintillantes",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"jeune homme asiatique confiant en costume sombre, bras croisés\"}",
    "pose": "regardant vers le haut à droite",
    "props": "ordinateur portable ouvert et lumineux devant lui"
  },
  "layout": {
    "background": "sombre avec des éclats de lumière dorée rayonnants",
    "text_sections": {
      "top_left_badge": "[Édition indispensable]",
      "top_header": "{argument name=\"top text\" default=\"Commencez dès aujourd'hui, même sans connaissances ! Obtenez le pouvoir de gagner de l'argent avec l'IA au plus vite !\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"Guide complet des revenus complémentaires par l'IA\"}",
        "style": "typographie 3D or et blanc, large et grasse"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"100k par mois, même pour les débutants\"}",
      "top_right_badge": {
        "style": "couronne de laurier dorée",
        "text": "Édition 2026"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "boîtes empilées à bordure dorée",
        "labels": ["Monétisation rapide", "Exemples concrets", "Accessible à tous"]
      },
      "middle_right_ribbon": {
        "style": "bannière ruban rouge",
        "text": "Procédure détaillée"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "grille 2x3 de boîtes à bordure dorée",
        "labels": ["Outils recommandés", "Flux de revenus expliqué", "Démarrage sans erreur", "Temps de travail réduit", "Modèles inclus", "Méthode reproductible"]
      },
      "bottom_footer": "Gagnez sans hésiter ! Le manuel des revenus par l'IA",
      "bottom_right_badge": {
        "style": "couronne de laurier dorée",
        "text": "Modèles inclus"
      }
    }
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="Miniature YouTube - Vignette pour infoproduit Or & Noir - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **Source:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **Publié:** 17 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13903)**

---

### No. 70: Bande dessinée / Storyboard - Manga chaleureux en 4 cases pour couple marié

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une bande dessinée japonaise douce et romantique en quatre cases célébrant un couple marié, idéale pour les publications sur les réseaux sociaux, les illustrations commémoratives ou l'art manga sur le thème des relations.

#### 📝 Prompt

```
{"type":"illustration de manga romantique en 4 cases","style":"art au trait anime propre et dessiné à la main avec une palette monochrome beige chaud et brun clair, fond crème doux, ombrage simple, atmosphère chaleureuse et tendre, esthétique de publication sur les réseaux sociaux","format":"mise en page de bande dessinée carrée 2x2 avec de fines bordures de cases marron","headline":{"text":"{argument name=\"headline text\" default=\"Journée du couple\"}","position":"haut centre","decorations":{"count":2,"items":["petit cœur à gauche","petit cœur à droite"]}},"panels":[{"panel":1,"count":2,"scene":"portrait debout d'un jeune couple","composition":"l'homme se tient derrière la femme avec une main sur son épaule, tous deux ont l'air calmes et affectueux","characters":[{"role":"homme","appearance":"cheveux brun clair ébouriffés, lunettes, sweat à capuche crème, grand et mince"},{"role":"femme","appearance":"cheveux brun clair attachés en un chignon bas lâche avec des mèches encadrant le visage, chemise blanche à manches longues, pull sans manches marron chaud, sangle de sac à bandoulière visible"}],"text":["Aujourd'hui, c'est","la journée du couple !"],"decorations":{"count":3,"items":["petit cœur","petit cœur","petit cœur"]}},{"panel":2,"count":2,"scene":"le couple assis ensemble à l'intérieur, tenant des tasses et se souriant","characters":[{"role":"homme","appearance":"mêmes lunettes et sweat à capuche, tenant une tasse vert sourd"},{"role":"femme","appearance":"même coiffure et tenue, tenant une tasse claire"}],"speech_bubble":{"speaker":"homme","text":"Merci pour tout. Être ensemble, c'est mon plus grand bonheur."},"decorations":{"count":4,"items":["petite étincelle","petite étincelle","petit groupe de points","petit groupe de points"]}},{"panel":3,"count":2,"scene":"le couple cuisinant ensemble dans une cuisine, tous deux remuant une poêle sur la cuisinière","background":"étagères simples et plante en pot dans un style esquissé doux","characters":[{"role":"homme","appearance":"mêmes lunettes et sweat à capuche"},{"role":"femme","appearance":"même chignon et tenue superposée"}],"speech_bubble":{"speaker":"homme","text":"Continuons à rire, à nous soutenir et à découvrir de nouveaux paysages ensemble."}},{"panel":4,"count":2,"scene":"étreinte affectueuse, l'homme embrasse la femme sur le front tout en tenant son épaule","characters":[{"role":"homme","appearance":"mêmes lunettes et sweat à capuche"},{"role":"femme","appearance":"mêmes cheveux et tenue, se penchant vers lui"}],"speech_bubble":{"speaker":"homme","text":"Je t'aime. Continuons comme ça !"},"decorations":{"count":3,"items":["petit cœur","petit cœur","petit cœur"]}},{"footer":{"text":"{argument name=\"footer text\" default=\"Merci d'être toujours à mes côtés.\"}","position":"bas centre","decorations":{"count":1,"items":["petit cœur"]}},"character_design":{"count":2,"items":[{"role":"mari","hair color":"{argument name=\"hair color\" default=\"brun clair\"}","expression":"gentil, doux, affectueux"},{"role":"femme","hair color":"{argument name=\"hair color\" default=\"brun clair\"}","expression":"sourire doux, aimante, légèrement timide"}]},"rendering_notes":"gardez tout le texte manuscrit en japonais, utilisez beaucoup d'espace blanc, préservez une ambiance commémorative douce pour une publication d'appréciation de couple, rendez le trait légèrement lâche et esquissé plutôt qu'à l'encre polie"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="Bande dessinée / Storyboard - Manga chaleureux en 4 cases pour couple marié - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Source:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14492)**

---

### No. 71: Bande dessinée / Storyboard - Page de démonstration de manga IA en japonais

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une page de manga anime à quatre cases soignée, montrant des personnages de filles-chats réagissant à des dialogues japonais rendus de manière impressionnante, idéale pour mettre en valeur la qualité du texte dans les bandes dessinées générées par IA.

#### 📝 Prompt

```
{
  "type": "page de manga anime à quatre cases",
  "style": "illustration anime propre et soignée, éclairage intérieur chaleureux, bulles de dialogue japonaises verticales parfaitement lisibles, ombrage doux, cadrage de bande dessinée expressif, arrière-plan détaillé de salon confortable, intérieur dans les tons beige et marron clair, parquet, canapé, table basse, tasses, petite plante, décoration murale encadrée",
  "format": {
    "page_orientation": "portrait",
    "panel_count": 4,
    "reading_flow": "haut-gauche, haut-droite, milieu-large, bas-large",
    "borders": "bordures de cases de manga noires épaisses"
  },
  "characters": [
    {
      "id": "fille-chat bleue",
      "appearance": "petite fille-chat chibi avec des cheveux courts au carré {argument name="hair color" default="bleus"}, ahoge, oreilles de chat avec fourrure intérieure blanche, queue touffue avec le bout blanc, grands yeux ambre-bleu, petite bouche en forme de croc",
      "outfit": "pull orange sur une chemise blanche à col avec bordure bleue, jupe marron avec une ceinture à ruban, pince à cheveux jaune en forme de X"
    },
    {
      "id": "fille-chat dorée",
      "appearance": "fille-chat énergique avec de longs cheveux ondulés blond doré, oreilles de chat, queue touffue, expression joyeuse et lumineuse",
      "outfit": "pull en tricot torsadé jaune moutarde, jupe à carreaux marron foncé"
    },
    {
      "id": "femme aux cheveux blancs",
      "appearance": "belle femme avec de longs cheveux blancs, oreilles de chat blanches, peau mate, yeux dorés, sourire calme et confiant",
      "outfit": "veste blanche sur un haut noir, colliers et boucles d'oreilles dorés superposés"
    },
    {
      "id": "femme de chambre",
      "appearance": "femme adulte avec de longs cheveux blond clair et des oreilles de chat",
      "outfit": "robe de domestique noire et blanche avec une coiffe à volants blanche et un nœud en ruban rouge"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "case 1",
        "position": "haut-gauche",
        "count": 1,
        "labels": ["どうせ日本語微妙なんでしょ？文字がダメなら認めないよ"],
        "scene": "la fille-chat bleue est assise sur un canapé dans un salon confortable, un doigt sur le menton, l'air sceptique et curieuse, un petit point d'interrogation flottant au-dessus de sa tête"
      },
      {
        "title": "case 2",
        "position": "haut-droite",
        "count": 1,
        "labels": ["ねぇねぇ！GPT Image2 すごいよ！"],
        "scene": "la fille-chat dorée fait irruption de façon spectaculaire par une porte avec des lignes de vitesse rayonnant derrière elle, les bras grands ouverts, pleine d'enthousiasme"
      },
      {
        "title": "case 3",
        "position": "milieu-large",
        "count": 3,
        "labels": ["うわっ びっくりした！めちゃくちゃキレイじゃん！", "ねぇねぇ！GPT Image2 すごいよ！ 微妙なんでしょ？ 文字がダメなら認めないよ", "ほら見て！わたしたちのセリフ！"],
        "scene": "la fille-chat bleue réagit avec surprise, les deux mains près du visage, la fille-chat dorée se tient à côté d'elle en pointant fièrement, et une grande bulle de dialogue centrale affiche l'exemple de dialogue japonais dont elles discutent"
      },
      {
        "title": "case 4",
        "position": "bas-large",
        "count": 3,
        "labels": ["進化が早すぎてもう驚かないよね〜", "絵も可愛く描けてるし文字の白抜きも完璧よね", ""],
        "scene": "au premier plan, la femme de chambre se couvre la bouche, impressionnée, tandis que la femme aux cheveux blancs commente pensivement, la main près du menton ; à l'arrière-plan, la fille-chat bleue et la fille-chat dorée sautent joyeusement ensemble devant le canapé"
      }
    ]
  },
  "text_handling": {
    "language": "japonais",
    "balloon_direction": "disposition du texte verticale",
    "emphasis": "rendre la typographie japonaise nette, naturelle et parfaitement intégrée dans les bulles de dialogue du manga, y compris l'utilisation de texte en réserve (blanc) si nécessaire"
  },
  "tone": "enjoué, festif, impressionné par la qualité du rendu du texte japonais dans les mangas générés par IA",
  "quality": "détails élevés, designs de personnages cohérents, bande dessinée promotionnelle mignonne et lisible"
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="Bande dessinée / Storyboard - Page de démonstration de manga IA en japonais - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **Source:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14471)**

---

### No. 72: Bande dessinée / Storyboard - Fiche 4 panneaux d'une élégante épéiste anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une illustration de personnage anime en quatre panneaux hautement détaillée représentant une noble épéiste aux cheveux blancs, idéale pour des illustrations fantasy, des présentations de personnages ou des publications premium sur les réseaux sociaux.

#### 📝 Prompt

```
Une illustration fantasy anime soignée sous forme de grille 2x2 présentant la même élégante épéiste en 4 panneaux. Le personnage est une jeune femme aux très longs cheveux blanc platine attachés en une haute queue-de-cheval avec de grands nœuds en ruban bleu marine profond, des boucles souples et des mèches fluides, une peau pâle et des traits délicats et raffinés avec des yeux rouge-rose lumineux. Elle porte une robe aristocratique gothique ornée, blanche et bleu marine : un chemisier blanc à col montant à volants avec bordure en dentelle et broderies dorées, un grand nœud bleu marine sur la poitrine agrémenté d'une broche bijou rouge, des manches bouffantes avec poignets à rubans, un corset bleu foncé à la taille avec des détails dorés, et une jupe volumineuse bleu marine décorée de motifs floraux dorés, de volants superposés et d'un éclat satiné. Elle porte un katana gainé avec une poignée sombre et des accents dorés. Le panneau 1 est un portrait en gros plan du buste, légèrement de profil, les cheveux brillant sous un éclairage dramatique sur un fond de nuit sombre et scintillant. Le panneau 2 est un plan d'action dynamique du haut du corps, le personnage dégainant ou présentant l'épée horizontalement vers le spectateur, les cheveux flottant au vent, avec un bokeh cinématographique de ville nocturne et des pétales lumineux autour d'elle. Le panneau 3 est un portrait en pied, debout avec grâce dans un hall réfléchissant et lumineux encadré par de hautes structures étincelantes, montrant toute la silhouette de la robe, des chaussures à talons avec des nœuds et l'épée à ses côtés. Le panneau 4 est une vue de trois-quarts arrière près d'un océan scintillant au coucher ou au lever du soleil, le personnage regardant par-dessus son épaule, avec un ciel pastel chaud et une eau scintillante en arrière-plan, et des pétales de cerisier dérivant dans la brise. Utilisez un rendu anime ultra-détaillé, une qualité de couverture de light novel premium, des textures de tissu complexes, des reflets brillants, des ornements dorés, un effet de halo doux, un rétroéclairage dramatique, des pétales flottants, des particules scintillantes, une atmosphère romantique élégante et une harmonie de couleurs bleu marine, blanc, or et rose poudré.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="Bande dessinée / Storyboard - Fiche 4 panneaux d'une élégante épéiste anime - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **Source:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14413)**

---

### No. 73: Bande dessinée / Storyboard - Standoff des Countryballs dans le détroit d'Ormuz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une illustration humoristique de mème géopolitique montrant les countryballs des États-Unis et de l'Iran se faisant face dans l'étroit détroit d'Ormuz, idéale pour la satire éditoriale ou les commentaires sur les réseaux sociaux.

#### 📝 Prompt

```
Une illustration détaillée et satirique de mème countryball du {argument name="waterway name" default="détroit d'Ormuz"} représenté comme un passage maritime très étroit entre deux falaises rocheuses abruptes, peint dans un style cartoon numérique soigné avec des ombres dramatiques et une texture de pierre. Au centre du premier plan, exactement 2 countryballs se bloquent mutuellement dans le canal étroit de sorte qu'un seul puisse passer. À gauche, un countryball USA aux yeux plissés de colère, peint aux couleurs du drapeau américain, portant une casquette de baseball bleu marine avec l'inscription "USA" en grandes lettres blanches. À droite, un countryball Iran aux yeux plissés de colère, peint aux couleurs du drapeau et de l'emblème iraniens, portant un bandeau vert et blanc noué sur le côté ; le bandeau contient du texte coréen qui signifie "La résistance est notre droit". Au-dessus de chaque boule se trouve exactement 1 bulle de dialogue blanche avec un contour noir épais, pour un total de 2 bulles, et les deux disent {argument name="speech text" default="길!"} en grandes lettres coréennes grasses, comme si aucun des deux camps ne voulait céder. Montrez les deux boules face à face, nez à nez, dans une impasse au niveau du goulot d'étranglement. Sur la falaise de gauche, incluez exactement 1 panneau en bois avec l'inscription en coréen et en anglais : "호르무즈 해협" et "Strait of Hormuz". Sur la falaise de droite, incluez exactement 1 panneau d'avertissement avec du texte en persan en haut et un triangle d'avertissement rouge en dessous, indiquant qu'une seule personne peut passer. Dans le coin inférieur gauche, placez exactement 1 baril de pétrole noir étiqueté "OIL" avec du pétrole sombre répandu autour. Dans le coin inférieur droit, placez exactement 1 mine navale noire avec une inscription en persan, attachée à une chaîne. En arrière-plan, au-delà du passage étroit, montrez la pleine mer avec exactement 3 navires au loin, dont au moins 1 pétrolier plus grand et une légère fumée sombre s'élevant dans le ciel. Utilisez un ton de mème géopolitique tendu mais humoristique, une composition centrée, une vue à hauteur d'yeux, une lumière du jour douce, des couleurs réalistes légèrement atténuées, des contours nets et une grande lisibilité pour tout le texte.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="Bande dessinée / Storyboard - Standoff des Countryballs dans le détroit d'Ormuz - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Source:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14683)**

---

### No. 74: Bande dessinée / Storyboard - Pose de victoire du sorcier aux yeux bandés

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche d'action anime verticale dramatique représentant un sorcier aux cheveux blancs portant un bandeau, entouré d'une énergie bleue explosive et doté d'une bulle de dialogue manga audacieuse, idéale pour des illustrations de personnages stylisées ou des visuels inspirés par les fandoms.

#### 📝 Prompt

```
Une illustration de style shonen manga à fort impact représentant un puissant sorcier aux cheveux blancs dans une pose dramatique en pied, en contre-plongée, riant la tête renversée en arrière et la bouche grande ouverte. Il porte un uniforme noir élégant à col haut et un bandeau noir sur les yeux. Sa main gauche est tendue vers le spectateur en faisant un signe de la paix, avec un raccourci saisissant qui rend la main imposante au premier plan, tandis que son bras droit pend le long de son corps. Entourez-le d'une énergie surnaturelle explosive de couleur {argument name="energy color" default="bleu électrique"}, de traînées d'aura rappelant des coups de pinceau violents, de débris volants, d'étincelles et de stries courbes tourbillonnantes traversant le cadre. L'arrière-plan doit être une explosion d'énergie sombre, abstraite et chaotique avec des éclats bleus lumineux et des lignes de mouvement, créant un sentiment de puissance écrasante. Utilisez un rendu anime en cel-shading audacieux avec des reflets picturaux, un trait net, un contraste intense et des plis de tissu brillants sur la tenue noire. Sur le côté droit, ajoutez une grande bulle de dialogue manga blanche et dentelée avec un contour noir épais contenant le texte {argument name="speech bubble text" default="LES LUDDITES PERDENT TOUJOURS !"} en énormes lettres majuscules noires usées. Composition verticale, cadrage d'affiche d'action dynamique, attitude triomphante et confiante, esthétique anime dark fantasy moderne.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="Bande dessinée / Storyboard - Pose de victoire du sorcier aux yeux bandés - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Source:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14637)**

---

### No. 75: Bande dessinée / Storyboard - Page de manga comique sur le bain public lunaire

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une page de bande dessinée anime rétro-futuriste représentant un sento fantaisiste sur la Lune, idéale pour générer des scènes de manga IA ludiques avec plusieurs cases centrées sur les personnages.

#### 📝 Prompt

```
Une page de manga japonais colorée se déroulant dans un bain public lunaire fantaisiste, dessinée dans un style anime rétro-futuriste soigné avec un éclairage chaleureux, des bordures de cases épaisses et nettes, des effets sonores expressifs et une narration environnementale très détaillée. La scène est un onsen lunaire appelé "月面銭湯 つきのゆ" avec une grande enseigne lumineuse à l'entrée, un rideau noren bleu avec le caractère blanc "ゆ", des tuyaux apparents, des manomètres, une architecture arrondie et une fenêtre circulaire géante montrant la surface de la Lune et la Terre dans l'espace. Incluez exactement 8 cases de bande dessinée disposées dans une mise en page dynamique. Case 1 : plan d'ensemble extérieur du bain public sur la Lune, avec l'enseigne "月面銭湯 つきのゆ", un panneau plus petit indiquant "重力 1/6", un distributeur automatique de lait rouge étiqueté "牛乳", une statue de tanuki, le terrain lunaire à l'extérieur et une bannière verticale faisant la promotion du bain. Case 2 : une jeune mécanicienne travaillant au bain public avec {argument name="character design" default="queue de cheval brune attachée avec un bandana à pois rouges, combinaison de travail verte, ceinture à outils, expression énergique"} ajuste une machine ou une commande de chaudière, vue de dos ou de profil, avec des bulles de dialogue sur la préparation du bain et l'état de la chaudière. Case 3 : un mignon client extraterrestre avec {argument name="alien appearance" default="corps rond vert menthe, taches violettes, yeux ensommeillés, joues roses, petite bouche, serviette blanche avec une étoile violette sur la tête"} se détend dans l'eau chaude fumante, à moitié immergé, avec un canard en plastique flottant à proximité et un panneau en bois indiquant "ぬるめ じっくり リラックス". Case 4 : un petit robot de nettoyage avec {argument name="robot design" default="corps argenté, accents bleus, visage numérique noir avec des yeux bleus brillants, voyant d'antenne rouge, bras et jambes mécaniques fins"} frotte joyeusement le sol avec un balai et un seau à côté d'un panneau suspendu indiquant "清掃中". Case 5 : le même robot glisse soudainement ou éclabousse dramatiquement dans le bain, avec une énorme gerbe d'eau, de nombreuses bulles, le gros effet sonore "ぽわぁ〜ん!!", et l'ouvrière réagissant avec surprise sur le côté. Case 6 : l'ouvrière est assise près du bain en souriant, tenant une bouteille étiquetée "月面牛乳". Case 7 : l'extraterrestre dans le bain lève le pouce tout en tenant une bouteille étiquetée "月面フルーツオーレ", l'air béatement satisfait, avec le canard en plastique toujours présent. Case 8 : le robot joyeux pose à côté du bain avec des outils de nettoyage et un seau, près d'un rideau de bain marqué "ゆ" et d'une bassine rose étiquetée "つきのゆ", disant que le bain est le meilleur. Maintenez un ton chaleureux et comique, des détails de sento de style Showa rétro mélangés à une technologie spatiale, des surfaces de bain carrelées brillantes, de la vapeur, des bulles et un jeu d'acteur mignon tout au long. La bande dessinée doit ressembler à un charmant manga de type tranche de vie sur le travail dans un bain public lunaire.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga comique sur le bain public lunaire - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **Source:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14697)**

---

### No. 76: Bande dessinée / Storyboard - Fiche de référence de design de personnage

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une fiche de design complète pour un personnage spécifique, incluant les informations clés et des références visuelles.

#### 📝 Prompt

```
Créez une fiche de design de personnage pour {argument name="character" default="Hermes Agent"}, avec les informations clés
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="Bande dessinée / Storyboard - Fiche de référence de design de personnage - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Neo](https://x.com/NeoAIForecast)
- **Source:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14324)**

---

### No. 77: Bande dessinée / Storyboard - Page de bande dessinée indépendante

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Crée une mise en page de bande dessinée dans un style indépendant moderne, adaptée aux histoires pour enfants.

#### 📝 Prompt

```
Une page de bande dessinée dans le style de {argument name="comic style" default="bande dessinée indépendante moderne"} sujet : {argument name="story topic" default="une histoire pour enfants de 6 ans"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="Bande dessinée / Storyboard - Page de bande dessinée indépendante - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [宝玉](https://x.com/dotey)
- **Source:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14310)**

---

### No. 78: Bande dessinée / Storyboard - Page de manga shonen colorisée

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt narratif détaillé pour générer une page de manga à l'aspect physique avec des détails spécifiques sur les personnages et la marque.

#### 📝 Prompt

```
Créez une page échantillon d'un {argument name="manga type" default="manga d'aventure shonen japonais colorisé"}. La page doit représenter de manière vivante notre personnage principal ayant trouvé un {argument name="item" default="plume magique"}. Le nom de la plume est la {argument name="item name" default="Plume de GPT Image"}. Rendez la scène dramatique. La plume magique renferme un pouvoir puissant scellé à l'intérieur.

Instructions supplémentaires : Format : Portrait 1440x2560. La plume doit porter le logo OpenAI. La langue utilisée dans tout le manga doit être le japonais. Réfléchissez bien au préalable pour en faire une bonne histoire avec une répartition efficace des cases de manga. La page doit apparaître comme la photo d'une page physique, et non comme une page numérique.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga shonen colorisée - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [宝玉](https://x.com/dotey)
- **Source:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14311)**

---

### No. 79: Bande dessinée / Storyboard - Page de manga comédie romantique en quatre cases

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une page de manga monochrome en quatre cases avec des dialogues en japonais, idéale pour créer des scènes de débat dramatiques et comiques avec des personnages expressifs.

#### 📝 Prompt

```
Créez une page de manga en noir et blanc avec 4 cases horizontales empilées, des gouttières noires nettes, des trames (screentones), des lignes de vitesse dramatiques et un trait soigné de style seinen. La page met en scène deux jeunes personnages d'anime en tenue décontractée moderne avec des cheveux courts et sombres, le visage des deux personnages étant masqué par un flou carré. Case 1 : une personne mince aux cheveux courts et ébouriffés, portant une chemise à col, serre le poing près de sa poitrine, le corps incliné vers la gauche, entourée d'un effet d'aura enflammée intense en arrière-plan, l'air émotif et sur la défensive. Sur le côté droit, placez une grande bulle de dialogue verticale dentelée contenant ce texte en japonais : 「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」. Case 2 : une deuxième personne un peu plus grande, aux cheveux courts et sombres, portant une veste zippée sombre sur une chemise claire, lève calmement un index comme pour expliquer un point. Ajoutez une bulle de dialogue rectangulaire arrondie sur la droite avec ce texte en japonais : 「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」. Case 3 : le personnage le plus grand tapote doucement la tête du plus petit ; incluez un petit effet sonore de tapotement près de la main indiquant 「ポン」. Le personnage plus petit lève les yeux avec surprise. Sur le côté droit, ajoutez une grande bulle de dialogue ovale verticale avec ce texte en japonais : 「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」. Case 4 : gros plan sur le personnage plus petit rougissant intensément avec des yeux en spirale, des gouttes de sueur, une expression tremblante, la bouche ouverte et des hachures denses sur les joues, submergé par l'embarras. Remplissez l'arrière-plan avec des lignes de vitesse rayonnantes dramatiques. Ajoutez une grande bulle de dialogue verticale dentelée sur la droite avec ce texte en japonais : 「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」. Ajoutez deux effets sonores : un petit 「プル…」 près de l'épaule et un plus grand 「カァァァ」 tremblant écrit à la main sur le côté inférieur gauche. Gardez toute la page monochrome, très expressive, dans un ton manga comédie romantique, avec un fort contraste émotionnel entre une dispute animée, une explication calme, une affection taquine et un dénouement embarrassé.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga comédie romantique en quatre cases - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Source:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14468)**

---

### No. 80: Bande dessinée / Storyboard - Fiche de référence du personnage Velvedia

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un court prompt pour générer une fiche de référence de personnage pour un personnage de style mecha nommé Velvedia.

#### 📝 Prompt

```
{argument name="character name" default="Velvedia"} fiche de référence
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="Bande dessinée / Storyboard - Fiche de référence du personnage Velvedia - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="Bande dessinée / Storyboard - Fiche de référence du personnage Velvedia - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **Source:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **Publié:** 21 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14368)**

---

### No. 81: Bande dessinée / Storyboard - Promo manga 8 cases GPT-Image-2

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une page de bande dessinée de style manga en noir et blanc, composée de huit cases, pour annoncer et expliquer GPT-Image-2 dans un format promotionnel adapté aux réseaux sociaux.

#### 📝 Prompt

```
{"type":"page de bande dessinée promotionnelle de 8 cases style manga","theme":"annonce de lancement pour GPT-Image-2","language":"français","style":{"rendering":"manga noir et blanc avec trames, lignes de vitesse, reflets brillants, contours encrés épais, finition numérique propre","mood":"excitant, informatif, optimiste, tourné vers la technologie","page_format":"page unique divisée en 8 cases rectangulaires dans une grille de 2 colonnes sur 4 rangées avec des gouttières fines"},"characters":[{"id":"fille hôte","role":"présentatrice principale","appearance":"mignonne fille anime avec de longs cheveux sombres, de grands yeux expressifs, portant un sweat à capuche sombre avec le logo OpenAI sur la poitrine","count":1},{"id":"robot mascotte","role":"mascotte assistante amicale","appearance":"petit robot rond avec un écran noir en guise de visage, yeux lumineux, corps blanc simple, petits bras, expression joyeuse","count":1},{"id":"groupe de créateurs","role":"exemples d'audience","appearance":"4 jeunes créateurs différents : un designer, un développeur tenant une tablette, un photographe avec son appareil, une personne avec un ordinateur portable/sweat à capuche","count":4}],"layout":{"sections":[{"title":"C'EST ARRIVÉ ! GPT-IMAGE-2","position":"en haut à gauche","count":1,"description":"case d'introduction héroïque et dramatique avec la fille anime tendant une main vers le spectateur, lignes de vitesse rayonnantes derrière elle","text":["C'EST ARRIVÉ !","GPT-IMAGE-2","LA NOUVELLE GÉNÉRATION D'IMAGES PAR IA D'OPENAI !","PLUS DE CRÉATIVITÉ, PLUS DE PRÉCISION, PLUS DE POSSIBILITÉS !"]},{"title":"QU'EST-CE QUE GPT-IMAGE-2 ?","position":"en haut à droite","count":1,"description":"fille en pose mi-corps pointant vers le haut à côté d'une icône d'image lumineuse sur un fond technologique étoilé","text":["QU'EST-CE QUE GPT-IMAGE-2 ?","C'est notre nouveau modèle de génération d'images, plus intelligent, plus fidèle à ce que vous imaginez et avec une qualité surprenante !"]},{"title":"PLUS DE RÉALISME. PLUS DE DÉTAILS.","position":"milieu gauche rangée 2","count":1,"description":"case de comparaison montrant 2 images de paysage côte à côte, deux scènes de lac de montagne, celle de gauche étiquetée ancien modèle et celle de droite nouveau modèle avec un réalisme plus riche","subsections":[{"label":"AVANT (DALL·E 3)","count":1},{"label":"MAINTENANT (GPT-IMAGE-2)","count":1}],"text":["PLUS DE RÉALISME. PLUS DE DÉTAILS.","AVANT (DALL·E 3)","MAINTENANT (GPT-IMAGE-2)","TEXTURES PLUS RICHES, LUMIÈRE PLUS NATURELLE, DÉTAILS INCROYABLES !"]},{"title":"MEILLEURE COMPRÉHENSION, MEILLEURS RÉSULTATS.","position":"milieu droite rangée 2","count":1,"description":"fille joignant les mains à côté d'un exemple de prompt encadré et le robot mascotte pointant vers le haut","text":["MEILLEURE COMPRÉHENSION, MEILLEURS RÉSULTATS.","GPT-IMAGE-2 comprend mieux les objets, les textes, les compositions et les instructions complexes !","EXEMPLE DE PROMPT :","\"Un café futuriste au sommet d'une montagne enneigée au crépuscule, avec une enseigne au néon ‘CAFÉ DE DEMAIN’ et des gens qui boivent du café.\""]},{"title":"CRÉATIVITÉ SANS LIMITES.","position":"bas gauche rangée 3","count":1,"description":"fille parlant à côté d'une présentation 2x2 de 4 variantes d'art généré","subsections":[{"label":"scène de château gothique","count":1},{"label":"rue de ville moderne la nuit","count":1},{"label":"portrait de personnage anime","count":1},{"label":"composition géométrique abstraite","count":1}],"text":["CRÉATIVITÉ SANS LIMITES.","Des styles artistiques aux mises en page professionnelles, du réaliste à l'abstrait : vos idées, à votre façon !"]},{"title":"DU TEXTE DANS L'IMAGE ? C'EST BEAUCOUP MIEUX MAINTENANT !","position":"bas droite rangée 3","count":1,"description":"robot mascotte présentant une comparaison avant-après de typographie d'affiche avec une flèche audacieuse entre les deux designs","subsections":[{"label":"AVANT","count":1},{"label":"MAINTENANT","count":1}],"text":["DU TEXTE DANS L'IMAGE ? C'EST BEAUCOUP MIEUX MAINTENANT !","Génération de texte plus précise, lisible et intégrée au design !","AVANT","MAINTENANT","AVENTURE COMMENCE ICI","L'AVENTURE COMMENCE ICI"]},{"title":"POUR TOUS LES CRÉATEURS.","position":"en bas à gauche","count":1,"description":"photo de groupe avec la fille hôte et 4 créateurs debout côte à côte, représentant différentes professions","text":["POUR TOUS LES CRÉATEURS.","Designers, développeurs, éducateurs, marketeurs, artistes et curieux : tout le monde peut créer plus et mieux !"]},{"title":"GPT-IMAGE-2 EST DÉJÀ DISPONIBLE !","position":"en bas à droite","count":1,"description":"case de clôture héroïque avec la fille faisant un clin d'œil et un pouce levé, robot mascotte à ses côtés, rayons festifs lumineux et étincelles","text":["GPT-IMAGE-2 EST DÉJÀ DISPONIBLE !","IMAGINEZ. CRÉEZ. INSPIREZ.","LE FUTUR DE LA CRÉATION EST LÀ. ❤"]}],"panel_count":8},"composition":{"reading_order":"de gauche à droite, de haut en bas","camera_variety":"mélange de gros plans héroïques, plans moyens de présentateur, graphiques de comparaison et photo de groupe","graphic_elements":["bulles de dialogue","bannières de titre noires arrondies avec lettrage blanc en majuscules","étincelles","lignes de vitesse","fond technologique étoilé","flèches de comparaison","cartes d'exemple encadrées"]},"text_style":"lettrage de bande dessinée tout en majuscules en français, en-têtes d'affichage gras, bulles de dialogue claires, hybride infographie-bande dessinée promotionnelle","quality":"affiche de bande dessinée éditoriale haute résolution, typographie nette, espacement équilibré des cases, fort contraste","prompt":"Créez une page de bande dessinée promotionnelle de 8 cases style manga en niveaux de gris annonçant {argument name=\"product name\" default=\"GPT-IMAGE-2\"}. Utilisez une mise en page sur une seule page de 2 colonnes par 4 rangées avec exactement 8 cases distinctes et du texte en français. Mettez en vedette une fille présentatrice anime joyeuse avec des cheveux longs {argument name=\"hair color\" default=\"brun foncé\"}, un sweat à capuche sombre avec le logo OpenAI, et une petite mascotte robot amicale. Case 1 : révélation dramatique du lancement, fille tendant la main vers la caméra, lignes de vitesse radiales, titre \"C'EST ARRIVÉ ! {argument name=\"headline name\" default=\"GPT-IMAGE-2\"}\" et texte de lancement sur une nouvelle génération d'images IA. Case 2 : case explicative avec la fille pointant à côté d'une icône d'image lumineuse sur un fond numérique étoilé, titre \"QU'EST-CE QUE GPT-IMAGE-2 ?\" et une bulle de dialogue le décrivant comme un modèle de génération d'images plus intelligent. Case 3 : comparaison de réalisme avec exactement 2 paysages de lac de montagne côte à côte étiquetés \"AVANT (DALL·E 3)\" et \"MAINTENANT (GPT-IMAGE-2)\". Case 4 : case de meilleure compréhension avec la fille et le robot, inclure un exemple de prompt encadré utilisant {argument name=\"example prompt\" default=\"Un café futuriste au sommet d'une montagne enneigée au crépuscule, avec une enseigne au néon ‘CAFÉ DE DEMAIN’ et des gens qui boivent du café.\"}. Case 5 : vitrine de créativité avec exactement 4 vignettes : château gothique, ville la nuit, portrait anime, art géométrique abstrait. Case 6 : comparaison de rendu de texte avec exactement 2 variantes d'affiche étiquetées \"AVANT\" et \"MAINTENANT\", montrant une typographie améliorée et la phrase \"L'AVENTURE COMMENCE ICI\" par rapport à une version corrigée plus propre. Case 7 : case d'audience avec exactement 4 créateurs de différents domaines debout ensemble. Case 8 : appel à l'action final festif avec la fille faisant un clin d'œil et un pouce levé, la mascotte robot applaudissant, et le slogan de clôture {argument name=\"closing slogan\" default=\"IMAGINEZ. CRÉEZ. INSPIREZ.\"}. Rendez la page énergique, polie, très lisible, avec des barres d'en-tête noires audacieuses, un lettrage blanc en majuscules, des bulles de dialogue, des étincelles, des trames et une esthétique forte d'affiche promotionnelle manga/bande dessinée."}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="Bande dessinée / Storyboard - Promo manga 8 cases GPT-Image-2 - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Diogo Santos](https://x.com/diogosantosbr)
- **Source:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14639)**

---

### No. 82: Bande dessinée / Storyboard - Confrontation manga au bureau avec censure

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Une page de manga monochrome au style brut illustrant une dispute animée au bureau qui bascule dans une scène de kabedon, idéale pour recréer des captures d'écran de style manga viral.

#### 📝 Prompt

```
Une page de manga dramatique en noir et blanc de style seinen, réalisée avec des trames denses, des traits d'encre nets, un éclairage à fort contraste et une mise en page expressive de bande dessinée japonaise. La page comporte 4 panneaux superposés avec des bulles de dialogue japonaises verticales et des effets sonores en gras, illustrant une confrontation tendue entre deux employés de bureau dans un espace de travail moderne. Dans le panneau du haut, une jeune femme aux cheveux courts en désordre, à la silhouette fine mais galbée, portant un chemisier ajusté aux manches retroussées et une jupe crayon sombre, frappe violemment un bureau de la main, se penchant vers le spectateur avec des lignes d'impact explosives et une grande bulle de dialogue dentelée. Dans le deuxième panneau, un jeune homme aux cheveux sombres ébouriffés, de corpulence mince, portant une veste en cuir noir sur une chemise claire et un collier, est montré du buste dans une pose calme et confiante, se touchant le visage tout en parlant. Dans le troisième panneau, l'homme plaque la femme contre un mur dans une pose de kabedon intime et rapprochée, un bras appuyé à côté de sa tête ; elle semble troublée et tendue tandis qu'il parle près de son visage, créant un changement soudain d'ambiance entre romance et comédie. Dans le panneau du bas, une vue plongeante révèle le décor du bureau : 2 personnages debout près d'un bureau avec 1 écran d'ordinateur, 1 clavier, 1 souris, 1 chaise de bureau et des papiers éparpillés sur un sol carrelé ; la femme est recroquevillée timidement et tremble tandis que l'homme se tient détendu à ses côtés. Incluez exactement 4 panneaux, exactement 4 bulles de dialogue visibles au total, et une typographie manga japonaise visible partout. Ajoutez un flou de mosaïque rectangulaire sur le visage de chaque personnage dans chaque panneau, comme s'ils étaient anonymisés pour être partagés en ligne. Les détails de l'arrière-plan doivent inclure les murs du bureau, les bords du bureau, les lignes de vitesse, les effets d'explosion et les dégradés de tons. L'ambiance générale est celle d'une dispute intense qui se transforme en flirt manipulateur, comme une capture d'écran de manga virale sortie de son contexte.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="Bande dessinée / Storyboard - Confrontation manga au bureau avec censure - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Source:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14477)**

---

### No. 83: Bande dessinée / Storyboard - Manga Quantum Cat

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt créatif et concis pour générer une planche de manga mettant en scène un chat adoptant des comportements liés à la physique quantique.

#### 📝 Prompt

```
Veuillez dessiner un manga où un {argument name="subject" default="chat"} {argument name="concept" default="se comporte comme une particule quantique"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="Bande dessinée / Storyboard - Manga Quantum Cat - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Haruhiko Okumura](https://x.com/h_okumura)
- **Source:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **Publié:** 21 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14348)**

---

### No. 84: Bande dessinée / Storyboard - Page de manga de bureau avec une mignonne fille-mouton

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une page de manga de bureau fantastique en quatre cases aux tons pastel, montrant une employée aux cornes de mouton et un mouton duveteux transformant de la paperasse en une scène comique, douillette et somnolente.

#### 📝 Prompt

```
{"type":"page de manga en quatre cases","style":"anime chibi aux tons pastel doux, palette beige chaud et crème, lumière matinale douce, bordures de cases arrondies, dialogues japonais clairs et lisibles, tranche de vie fantastique et comique au bureau","page":{"orientation":"verticale","panel_count":4,"gutter":"espacement blanc fin","border":"contours marron arrondis"},"setting":{"location":"intérieur d'un petit bureau de gestion","details":["parquet","fenêtre ensoleillée","bureau avec des documents","chaises en bois","étagères remplies de dossiers et de livres","boîtes empilées et fournitures de bureau","poussière en suspension et scintillements dans la lumière"]},"characters":[{"role":"personnage principal","appearance":"minuscule employée chibi fille-mouton avec un carré blond court et duveteux, un œil bleu et un œil ambre, petites oreilles d'elfe, grandes cornes de bélier recourbées, capuche en forme de tête de mouton, chemisier blanc, cravate rouge, robe tablier rose pâle, petit stylo dans la poche du tablier"},{"role":"personnage secondaire","appearance":"mouton blanc rond et duveteux avec un petit visage et des pattes courtes, très pelucheux et semblable à un nuage"}],"layout":{"sections":[{"title":"case 1","position":"haut","count":3,"labels":["la fille-mouton ouvre la porte du bureau et regarde à l'intérieur","petit mouton qui jette un coup d'œil à côté d'elle","une bulle de dialogue ovale à gauche et une petite bulle ovale à droite"]},{"title":"case 2","position":"milieu supérieur","count":3,"labels":["la fille-mouton debout près d'un bureau, une main sur la hanche et l'autre pointant des documents","petit mouton assis près du bureau","une seule grande bulle de dialogue ovale à gauche"]},{"title":"case 3","position":"milieu inférieur","count":3,"labels":["mouton duveteux endormi étalé sur la paperasse","gros plan partiel de la fille-mouton regardant depuis le haut à gauche avec une expression fatiguée","texte d'effet sonore de sommeil en violet sur la droite"]},{"title":"case 4","position":"bas","count":4,"labels":["fille-mouton endormie au bureau avec les yeux fermés et un léger sourire","mouton duveteux dormant à côté d'elle sur la paperasse","lumière chaude du soleil provenant de la fenêtre de gauche","petite boîte de légende rectangulaire en bas à droite"]}]},"text":{"language":"Japonais","elements":[{"kind":"bulle de dialogue","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"bulle de dialogue","panel":1,"text":"メェ"},{"kind":"bulle de dialogue","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"bulle de dialogue","panel":3,"text":"…名簿が もふもふに…"},{"kind":"effet sonore","panel":3,"text":"Zzz…"},{"kind":"bulle de dialogue","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"légende","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"garder les quatre cases dans le même bureau pour la continuité ; accentuer les expressions faciales mignonnes, les textures duveteuses et l'humour du travail de bureau qui s'arrête parce que le mouton et l'employée s'endorment ensemble sur les documents ; rendre les documents clairement visibles dans les cases 2 à 4 ; préserver un ton calme, somnolent et réconfortant"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga de bureau avec une mignonne fille-mouton - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga de bureau avec une mignonne fille-mouton - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="Bande dessinée / Storyboard - Page de manga de bureau avec une mignonne fille-mouton - Image 3">
</div>

#### 📌 Détails

- **Auteur:** [じょにがたロボ](https://x.com/jonigata_ai)
- **Source:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14532)**

---

### No. 85: Bande dessinée / Storyboard - Adorable bande dessinée en quatre cases sur la jalousie d'un chat

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt génère une bande dessinée chaleureuse en quatre cases, dessinée à la main, idéale pour les réseaux sociaux, l'humour style manga ou les illustrations d'animaux de compagnie.

#### 📝 Prompt

```
Une adorable bande dessinée en quatre cases dessinée à la main, dans un style « tranche de vie » doux et chaleureux, sur un fond crème clair avec des bordures de cases noires épaisses et un grain de papier légèrement texturé. Utilisez une anatomie de chat cartoon simple et arrondie, des visages expressifs, des contours noirs nets, des couleurs naturelles atténuées et une présentation douce rappelant le manga. Dans la case en haut à gauche, montrez 2 chats : un chat tigré brun avec des rayures sombres et un museau blanc assis les yeux fermés, l'air satisfait, tandis qu'un chat majoritairement blanc avec des taches brun foncé sur la tête se tient à côté et lèche affectueusement la joue du chat tigré ; ajoutez 2 petites notes de musique noires au-dessus d'eux pour suggérer un moment de toilettage heureux. Dans la case en haut à droite, montrez le chat blanc aux taches brunes au premier plan regardant vers un petit chaton calico debout sur la droite ; incluez une bulle contenant le texte japonais « めい » au-dessus du chaton. Dans la case en bas à gauche, montrez 3 chats ensemble : le chat tigré brun à gauche avec une expression surprise ou neutre, le chat aux taches blanches à droite ayant l'air joyeux, et le petit chaton calico centré devant eux, regardant vers le haut. Dans la case en bas à droite, montrez un gros plan du chat tigré brun seul, face à l'avant avec des yeux jaune-vert plissés et une expression de jalousie colérique ; ajoutez 2 courtes lignes d'emphase près du visage et 1 petit symbole de colère en forme de nuage sur la droite. Gardez un ton chaleureux et comique, avec la blague visuelle selon laquelle le chat tigré était heureux d'être toiletté jusqu'à ce que le nouveau chaton apparaisse. Utilisez des couleurs plates, un ombrage minimal et une charmante esthétique de webcomic japonais.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="Bande dessinée / Storyboard - Adorable bande dessinée en quatre cases sur la jalousie d'un chat - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Maoku](https://x.com/Maoku)
- **Source:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14503)**

---

### No. 86: Bande dessinée / Storyboard - Page de bande dessinée Moon Mark Adventure

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une page de bande dessinée fantastique de style anime en quatre cases montrant une jeune fille aux cheveux argentés sur le thème de la lune découvrant une carte, résolvant une énigme dans une grotte et trouvant une invitation magique pour la prochaine aventure.

#### 📝 Prompt

```
{"type":"page de bande dessinée anime en quatre cases","style":"illustration manga fantastique mignonne, rendu anime gpt-image-2 soigné, couleurs vibrantes, traits nets, ombrage doux et pictural, atmosphère magique et fantaisiste","page":{"background":"page blanche avec bordures de cases noires","title":"{argument name=\"headline text\" default=\"L'aventure de la marque de lune\"}","title_position":"haut centre","decorations":["petites étincelles dorées autour du titre","icône de croissant de lune à droite du titre"],"panel_count":4,"reading_direction":"de haut en bas"},"character":{"appearance":"jeune aventurière anime avec de très longs cheveux argentés ondulés, peau pâle, grands yeux expressifs, silhouette fine","outfit":["robe fantastique noire et blanche avec bordure à volants","ornement de cheveux en croissant de lune","ras-du-cou croissant de lune","manches tombantes","sac à dos en cuir marron","bas hauts noirs"],"theme":"motif de lune sur tout le costume et les accessoires"},"panels":[{"position":"haut","scene":"sentier de montagne ensoleillé et prairie sous un ciel bleu avec des nuages, forêt sur la droite, chemin sinueux au loin, panneau en bois sur la gauche","action":"la jeune fille se tient debout, tenant et lisant une vieille carte au trésor, face à l'avant","props":["carte ancienne","panneau en bois","sac à dos"],"text":{"sign":"Début de l'aventure","speech":"{argument name=\"panel 1 speech\" default=\"J'ai trouvé la carte ! C'est le début d'une grande aventure !\"}"}},{"position":"milieu-haut","scene":"entrée de ruines luxuriantes ressemblant à une jungle avec une ouverture de grotte sombre encadrée par de vieux piliers en pierre sculptés de symboles en croissant et couverts de vignes","action":"vue arrière de trois quarts de la jeune fille s'approchant prudemment tout en lisant la carte","props":["carte","entrée de grotte en ruine","plantes denses"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"Le trésor doit être par ici... !\"}","sound_effect":"Bruissement"}},{"position":"milieu-bas","scene":"à l'intérieur des ruines de la grotte, faiblement éclairé, autel en pierre ou table à énigme au centre","action":"la jeune fille s'agenouille à côté d'une lanterne allumée et tend la main vers un mécanisme d'énigme au lieu d'une serrure à proximité, tandis qu'une mascotte ronde ressemblant à un chat noir observe","props":["lanterne émettant une lumière chaude","dalle de puzzle en pierre avec symbole circulaire gravé","petite clé dorée sur la table","créature chat noir avec une marque de croissant de lune et un collier de perles"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"Ce n'est pas la clé, il faut résoudre le mécanisme !\"}","sound_effect":"Flash"}},{"position":"bas","scene":"chambre au trésor avec des cristaux incrustés dans les murs de la grotte et des étincelles flottantes","action":"la jeune fille sourit joyeusement, les yeux fermés, à côté d'un coffre au trésor ouvert, tenant une carte d'invitation en papier","props":["coffre au trésor en bois ouvert avec emblème de croissant de lune","boussole brillante à l'intérieur du coffre","carte en papier indiquant Vers la prochaine aventure","cristaux bleus et violets"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"Le trésor est... une invitation pour la prochaine aventure !\"}","tag":"À suivre ?"}}]}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="Bande dessinée / Storyboard - Page de bande dessinée Moon Mark Adventure - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ツバサ天九](https://x.com/wing_sky_nine)
- **Source:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14605)**

---

### No. 87: Marketing produit - Identité de marque et planche de merchandising pour personnage d'anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une planche de design de marque complète mettant en scène un personnage d'anime, incluant des emballages de produits, des maquettes pour réseaux sociaux et des mises en page de merchandising.

#### 📝 Prompt

```
{
  "type": "planche de design d'identité de marque et de merchandising",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"rose pastel\"} et blanc",
    "motif": "{argument name=\"motif\" default=\"fleurs de cerisier\"} et cœurs roses"
  },
  "character": {
    "description": "fille anime avec un carré court châtain, des yeux roses, portant un sweat à capuche blanc, sourire doux"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "bannière d'en-tête",
        "position": "haut",
        "elements": ["grand logo principal", "sous-logo", "graphismes de fleurs de cerisier", "portrait du personnage sur la droite"]
      },
      {
        "type": "emballage de produit",
        "position": "milieu gauche",
        "elements": ["1 boîte carrée avec fenêtre transparente en forme de cœur montrant des bonbons cœurs roses", "illustration du personnage sur la boîte", "2 emballages de bonbons individuels", "5 bonbons cœurs éparpillés"]
      },
      {
        "type": "affiche promotionnelle",
        "position": "milieu droite",
        "elements": ["portrait du personnage", "bol de bonbons en forme de cœur", "logo principal", "texte '4.26 NEW OPEN'", "texte '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "bannière web horizontale",
        "position": "milieu inférieur",
        "elements": ["logo principal", "fleurs de cerisier", "portrait du personnage sur la droite"]
      },
      {
        "type": "maquette de profil de réseau social",
        "position": "bas gauche",
        "elements": ["image d'en-tête avec logo", "1 photo de profil circulaire", "identifiant '{argument name=\"social handle\" default=\"@yuonchii\"}'", "1 bouton suivre", "exemple de bio"]
      },
      {
        "type": "collection de merchandising",
        "position": "bas droite",
        "count": 9,
        "items": ["1 t-shirt blanc avec logo", "1 mug blanc avec le personnage", "4 badges ronds", "1 porte-clés en acrylique", "2 paquets de bonbons"]
      }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="Marketing produit - Identité de marque et planche de merchandising pour personnage d'anime - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **Source:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13547)**

---

### No. 88: Marketing produit - Page de destination pour étude de cas de marketing viral en mode sombre

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une maquette d'interface utilisateur complète en mode sombre pour une étude de cas marketing, incluant des visualisations de données, des chronologies et des illustrations 3D.

#### 📝 Prompt

```
{
  "type": "conception d'interface de page de destination",
  "theme": "mode sombre, technologie moderne, {argument name=\"primary accent color\" default=\"violet néon\"} et accents bleus lumineux, glassmorphism",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "badge": "ÉTUDE DE CAS DE CAMPAGNE VIRALE"
  },
  "sections": [
    {
      "id": "hero",
      "layout": "texte à gauche, image à droite",
      "content": {
        "badge": "ÉTUDE DE CAS",
        "headline": "{argument name=\"hero headline\" default=\"Comment nous avons généré plus de 10 millions d'impacts viraux\"}",
        "subtitle": "3 jours pour enflammer le réseau et aider les marques à atteindre une croissance exponentielle",
        "stats_row": {
          "count": 4,
          "labels": ["Vues totales {argument name=\"main metric\" default=\"10 240 000+\"}", "Taux d'engagement 18,7 %", "Conversions 3 200+", "Temps d'exécution 72 heures"]
        },
        "hero_image": "prise de vue cinématographique d'une personne dans une pièce sombre regardant des écrans vidéo flottants lumineux, avec une grande icône de lecture en superposition"
      }
    },
    {
      "id": "strategy",
      "title": "ANALYSE DE LA CAMPAGNE : Notre stratégie d'exécution sur 3 jours",
      "layout": "chronologie verticale en 3 étapes",
      "steps": [
        {"step": 1, "title": "Formulation de la stratégie", "image": "personnes analysant des données sur un écran"},
        {"step": 2, "title": "Production de contenu", "image": "interface de montage vidéo"},
        {"step": 3, "title": "Distribution et amplification", "image": "main tenant un smartphone avec des icônes de réseaux sociaux"}
      ]
    },
    {
      "id": "performance",
      "title": "RÉSULTATS DE PERFORMANCE : Des performances basées sur les données",
      "layout": "grille de cartes statistiques à gauche, graphiques à droite",
      "left_stats": {
        "count": 4,
        "labels": ["Exposition totale 10M+", "Baisse moyenne du CPM 43 %", "Nouveaux abonnés 28 000+", "Conversions 3 200+"]
      },
      "right_charts": {
        "count": 2,
        "items": [
          "graphique linéaire montrant une tendance sur 7 jours avec un pic au 3e jour à 8 320 000",
          "graphique à barres horizontales montrant la répartition par plateforme : TikTok 52 %, Instagram 24 %, X 15 %, YouTube 9 %"
        ]
      }
    },
    {
      "id": "keys_to_success",
      "title": "POURQUOI C'EST DEVENU VIRAL : Les 3 clés du succès viral",
      "layout": "rangée horizontale de 3 cartes",
      "cards": [
        {"icon": "fire", "title": "Conception d'accroche émotionnelle"},
        {"icon": "bullseye", "title": "Conception de la structure du contenu"},
        {"icon": "antenna", "title": "Exécution de la stratégie de distribution"}
      ]
    },
    {
      "id": "social_proof",
      "title": "APPROUVÉ PAR LES CRÉATEURS ET LES MARQUES : Ils utilisent tous goViralX pour booster leur croissance",
      "layout": "logos à gauche, témoignages à droite",
      "left_logos": {
        "count": 8,
        "labels": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
      },
      "right_testimonials": {
        "count": 2,
        "labels": ["Citation d'un fondateur SaaS", "Citation d'un responsable de croissance"]
      }
    },
    {
      "id": "cta",
      "title": "PRÊT À DEVENIR VIRAL ? : Vous voulez obtenir le même effet de croissance ?",
      "layout": "texte et champ de saisie à gauche, illustration 3D à droite",
      "elements": [
        "champ de saisie avec texte indicatif",
        "bouton : {argument name=\"call to action text\" default=\"Obtenir mon plan de croissance exclusif ->\"}"
      ],
      "image": "fusée 3D lumineuse violette et bleue au décollage"
    }
  ],
  "footer": "logo et texte de copyright"
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="Marketing produit - Page de destination pour étude de cas de marketing viral en mode sombre - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [开发者Hailey](https://x.com/IndieDevHailey)
- **Source:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **Publié:** 17 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13769)**

---

### No. 89: Marketing produit - Document d'identité de marque de mascotte en 18 panneaux

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un guide de marque complet en 18 sections et une fiche de conception de personnage pour une mascotte 3D, détaillant tout, des moodboards et croquis au trait aux vues à 360 degrés et maquettes physiques.

#### 📝 Prompt

```
{
  "type": "document d'identité de marque et de conception de personnage en 18 panneaux",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"THÉ MUYANG\"}",
    "industry": "{argument name=\"industry\" default=\"boutique de thé\"}",
    "colors": ["{argument name=\"primary color\" default=\"jaune\"}", "{argument name=\"secondary color\" default=\"vert\"}", "blanc", "marron", "vert foncé"]
  },
  "subject": "{argument name=\"character description\" default=\"mascotte 3D mignonne de Shiba Inu portant un tablier vert\"}",
  "layout": {
    "grid": "3 colonnes par 6 rangées",
    "sections": [
      {
        "title": "01 ANALYSE DE L'ADN DE LA MARQUE / BRAND DNA ANALYSIS",
        "elements": ["logo", "5 échantillons de couleur", "6 icônes", "graphiques du public cible"]
      },
      {
        "title": "02 MOODBOARD CONCEPTUEL / CONCEPT MOODBOARD",
        "elements": ["5 références photo", "4 icônes d'ambiance", "équation de design"]
      },
      {
        "title": "03 ÉTUDE DE FORME / FORM STUDY",
        "elements": ["4 icônes d'anatomie du logo", "4 étapes d'évolution", "4 silhouettes"]
      },
      {
        "title": "04 EXPLORATION CONCEPTUELLE / CONCEPT EXPLORATION",
        "elements": ["12 croquis au trait du personnage"]
      },
      {
        "title": "05 DESSIN AU TRAIT AFFINÉ / REFINED LINE ART",
        "elements": ["3 rangées de dessins au trait de face et de profil avec guides de proportion"]
      },
      {
        "title": "06 AFFINAGE DES DÉTAILS / DETAIL REFINEMENT",
        "elements": ["2 rendus complets du corps avec étiquettes", "4 gros plans circulaires"]
      },
      {
        "title": "07 FEUILLE D'EXPRESSIONS / EXPRESSION SHEET",
        "elements": ["11 expressions de tête en rendu 3D"]
      },
      {
        "title": "08 BIBLIOTHÈQUE DE POSES / POSE LIBRARY",
        "elements": ["9 poses complètes en rendu 3D"]
      },
      {
        "title": "09 VUE À 360 DEGRÉS / TURNAROUND VIEW",
        "elements": ["5 rendus 3D complets", "5 vues correspondantes au trait"]
      },
      {
        "title": "10 DÉVELOPPEMENT DES COULEURS / COLOR DEVELOPMENT",
        "elements": ["5 rangées de palettes de 5 couleurs", "texte sur la psychologie des couleurs"]
      },
      {
        "title": "11 SPÉCIFICATIONS DES MATÉRIAUX / MATERIAL SPECIFICATION",
        "elements": ["5 échantillons de texture", "curseurs de propriétés", "4 icônes de fabrication"]
      },
      {
        "title": "12 APPLICATION DES COULEURS / COLOR APPLICATION",
        "elements": ["4 rendus de variantes de couleur", "2 rendus clair/sombre", "4 cercles d'évaluation du contraste"]
      },
      {
        "title": "13 GUIDE DE CONSTRUCTION / CONSTRUCTION GUIDE",
        "elements": ["2 diagrammes au trait pour la géométrie et la grille"]
      },
      {
        "title": "14 RÈGLES DU SYSTÈME DE DESIGN / DESIGN SYSTEM RULES",
        "elements": ["icônes de taille minimale", "diagramme d'espace libre", "4 exemples d'utilisation"]
      },
      {
        "title": "15 VARIANTES D'ACTIFS / ASSET VARIANTS",
        "elements": ["3 variantes de taille", "3 variantes au trait", "3 têtes plates simplifiées"]
      },
      {
        "title": "16 APPLICATIONS NUMÉRIQUES / DIGITAL APPLICATIONS",
        "elements": ["1 icône d'application", "2 avatars pour réseaux sociaux", "éléments d'interface utilisateur", "cycle d'animation en 3 étapes"]
      },
      {
        "title": "17 APPLICATIONS PHYSIQUES / PHYSICAL APPLICATIONS",
        "elements": ["maquette de peluche", "maquette d'emballage", "maquette de marchandise", "maquette de devanture de magasin"]
      },
      {
        "title": "18 RENDU FINAL / FINAL RENDERING",
        "elements": ["grand rendu 3D haute résolution de la mascotte tenant du thé", "logo", "liste des formats de fichier"]
      }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="Marketing produit - Document d'identité de marque de mascotte en 18 panneaux - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Lee Colin](https://x.com/Colin_Leeee)
- **Source:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **Publié:** 16 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13819)**

---

### No. 90: Marketing produit - Affiche publicitaire pour jeu mobile de samouraïs style anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Une publicité verticale percutante pour un jeu mobile mettant en scène deux épéistes en costume, un mécha samouraï géant, une interface de jeu, un QR code et des boutons de téléchargement pour la promotion de l'application.

#### 📝 Prompt

```
Créez une affiche publicitaire verticale à fort impact pour un jeu mobile dans un style action anime brillant, avec une esthétique fantastique cyber-samouraï dramatique et une composition promotionnelle dense et premium typique des gacha-RPG. La scène principale montre deux jeunes hommes combattants en costumes noirs modernes, accroupis de manière agressive au premier plan, chacun dégainant un katana vers le spectateur. Tous deux ont des cheveux blonds coiffés, des traits fins et séduisants, des chemises blanches, des cravates bleues et des poses d'action intenses, avec des mains et des épées en raccourci dominant le bas de l'image. Une épée porte un ruban bleu noué près de la garde. Derrière eux, au centre et dominant la scène, placez un immense samouraï mécha blindé avec des cornes dorées ornées, une armure métallique bleu-noir superposée, des yeux bleus luisants et un sabre rengainé dans le dos, encadré comme une divinité gardienne. Utilisez une toile de fond de ville néon vive et d'éclats d'énergie en bleu électrique, violet, magenta et or, avec des traînées lumineuses, des étincelles, des pétales, des effets de coupure et des textures d'explosion à l'encre. Ajoutez une bannière verticale en coup de pinceau noir en haut à droite avec le texte japonais en gras blanc : 「この刃で、未来を斬り拓け。」. Dans la zone médiane inférieure, placez un énorme titre en calligraphie japonaise dorée avec une texture de pinceau épaisse et une ombre noire, lisant 「切り捨て御免」, couvrant presque toute la largeur. En bas à gauche, intégrez un panneau de capture d'écran de gameplay encadré avec une bordure dorée, montrant une bataille nocturne devant la cour d'un temple japonais rouge, un épéiste jouable en combat, plusieurs ennemis, des chiffres de dégâts flottants incluant 5324, 5329 et 6132, un joystick virtuel sur la gauche, 5 portraits de personnages au total disposés verticalement et le long du bas, 3 boutons de compétence circulaires sur la droite, et un HUD supérieur montrant un minuteur autour de 01:28 et VAGUE 3/3. En bas à droite, placez un grand QR code noir et blanc à l'intérieur d'un cadre carré blanc. En dessous et à côté, ajoutez le texte japonais en gras en blanc avec un contour bleu : 「今すぐダウンロード」. Tout en bas, incluez deux badges de boutique officiels : App Store à gauche et Google Play à droite. Aspect général : ultra-détaillé, illustration clé soignée, perspective dynamique, reflets métalliques, rendu anime en cel-shading net, affiche marketing de jeu mobile premium, énergie d'action intense, éclairage cinématographique et mise en page promotionnelle riche en interface utilisateur.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="Marketing produit - Affiche publicitaire pour jeu mobile de samouraïs style anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="Marketing produit - Affiche publicitaire pour jeu mobile de samouraïs style anime - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="Marketing produit - Affiche publicitaire pour jeu mobile de samouraïs style anime - Image 3">
</div>

#### 📌 Détails

- **Auteur:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **Source:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14432)**

---

### No. 91: Marketing produit - Planche de kit de marque Monochrome Infra

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une planche de présentation épurée en noir et blanc pour les directives de marque et le merchandising d'une marque fictive de technologie d'infrastructure, idéale pour les pitch decks, les présentations de branding et les maquettes de design professionnelles.

#### 📝 Prompt

```
{"type":"planche de présentation de kit de marque et goodies monochrome","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"Nous soutenons les bâtisseurs qui créent l'infrastructure fondamentale de l'ère de l'IA.","campaign_line":"[ CONSTRUIRE LE FUTUR. DEPUIS LA BASE. ]","version":"VERSION 1.0"},"style":{"overall":"fiche de directives de marque épurée d'inspiration suisse, esthétique technologique industrielle minimale, noir blanc et gris uniquement, fond papier blanc cassé, découpes de produits studio nettes, ombres subtiles, mise en page en grille précise, présentation éditoriale","mood":"professionnel, premium, futuriste, axé sur l'infrastructure"},"layout":{"header":{"left":"A16Z INFRA / KIT DE MARQUE & GOODIES","right":"VERSION 1.0","divider":"ligne horizontale en pointillés"},"sections":[{"title":"01 IDENTITÉ","position":"en haut à gauche","count":3,"labels":["logotype large","paragraphe de déclaration de marque","ligne de campagne entre crochets"]},{"title":"02 PALETTE","position":"en haut à droite","count":4,"labels":["BLANC CASSÉ CHAUD","NOIR","CHARBON","GRIS SOURD"]},{"title":"03 TYPOGRAPHIE","position":"en haut à droite sous la palette","count":2,"labels":["PRIMAIRE -- MONOSPACE","SECONDAIRE -- SANS SERIF"]},{"title":"06 GOODIES","position":"deux tiers inférieurs","count":16,"labels":["sweat à capuche noir devant","sweat à capuche noir dos","t-shirt blanc cassé","casquette de baseball noire","tote bag blanc cassé","lot de 6 autocollants/cartes carrés","carnet à spirales noir","mug noir","gourde noire","pochette zippée noire","console de jeu rétro portable","boîte de micro-constructions","étui de kit clavier ouvert","pin's icône cloud","pin's icône cubes empilés","pin's écusson rectangulaire de marque"]}],"footer":{"left":"A16Z INFRA / KIT DE MARQUE","right":"© 2024 A16Z INFRA. TOUS DROITS RÉSERVÉS.","divider":"ligne horizontale en pointillés"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"très grand mot-symbole géométrique personnalisé avec coupes angulaires, lettrage noir épais, empilé sur deux lignes"}},"palette":{"swatches":[{"name":"BLANC CASSÉ CHAUD","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"NOIR","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"CHARBON","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"GRIS SOURD","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"PRIMAIRE -- MONOSPACE","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"SECONDAIRE -- SANS SERIF","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}} ,"swag":{"items":[{"name":"sweat à capuche devant","color":"noir","print":"petit logo poitrine"},{"name":"sweat à capuche dos","color":"noir","print":"liste de manifeste multi-lignes indiquant BUILDING THE INFRASTRUCTURE LAYER OF AI avec lignes de guidage en pointillés et catégories incluant SYSTEMS, TOOLS, DATA, CLOUD, SECURITY, NETWORKS, DEVELOPER TOOLS"},{"name":"t-shirt","color":"blanc cassé","print":"grand logo centré"},{"name":"casquette de baseball","color":"noir","print":"logo brodé sur le devant"},{"name":"tote bag","color":"blanc cassé","print":"liste de manifeste empilée et ligne inférieure BUILDING WHAT'S NEXT."},{"name":"lot d'autocollants/cartes","count":6,"layout":"grille 2 par 3","labels":["A16Z INFRA","BUILDING THE INFRASTRUCTURE LAYER OF AI.","EARLY STAGE","SYSTEMS. TOOLS. PLATFORMS.","INFRA","BUILD","DEPLOY","SCALE"]},{"name":"carnet à spirales","color":"noir","print":"logo plus NOTES FOR BUILDING THE FUTURE"},{"name":"mug","color":"noir","print":"logo blanc"},{"name":"gourde","color":"noir","print":"texte vertical BUILDING WHAT'S NEXT. FROM THE GROUND UP."},{"name":"pochette zippée","color":"noir","print":"logo, motif grille en pointillés, petit texte SYSTEMS ONLINE."},{"name":"console rétro portable","color":"noir charbon","screen":"écran de jeu pixel-art ville/infrastructure avec onglets BUILD DEPLOY SCALE et indicateur de niveau LEVEL 01"},{"name":"boîte de micro-constructions","color":"noir","print":"A16Z INFRA, INFRASTRUCTURE MICRO BUILDS, COLLECT.CONNECT.SCALE.","contents":"petits modèles de blocs de construction modulaires noirs, gris et blancs affichés devant la boîte"},{"name":"étui de kit clavier","color":"noir","print":"A16Z INFRA KEYPAD SET BUILD. DEPLOY. SCALE.","keys":8,"labels":["INFRA","BUILD","DEPLOY","SCALE",">_","icône cloud","icône puce/grille","icône schéma réseau"]},{"name":"pin's cloud","style":"petit badge émaillé noir avec bordure blanche"},{"name":"pin's cubes","style":"petit badge émaillé noir montrant des cubes isométriques empilés"},{"name":"pin's écusson de marque","style":"petit badge émaillé rectangulaire noir avec logo blanc"}]},"rendering":{"camera":"vue de dessus à plat combinée avec une composition de planche produit orthographique","lighting":"éclairage studio doux et uniforme","background":"feuille blanc cassé clair et chaude","quality":"maquette commerciale haute résolution adaptée à une présentation de marque professionnelle"}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="Marketing produit - Planche de kit de marque Monochrome Infra - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Olivier Sauvage](https://x.com/Capitaine)
- **Source:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14563)**

---

### No. 92: Marketing produit - Affiche publicitaire parodique pour boisson au riz coréenne

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche publicitaire parodique humoristique et percutante pour une boisson, mettant en scène un porte-parole ressemblant à un politicien célèbre faisant la promotion d'une boisson coréenne au riz en conserve.

#### 📝 Prompt

```
Créez une affiche publicitaire audacieuse pour une boisson de style coréen avec un fond éclaboussé de doré chaleureux et un éclairage commercial dramatique. Montrez un {argument name="celebrity spokesperson" default="politicien âgé ressemblant à Donald Trump"} du buste, portant un costume bleu marine, une chemise blanche, une cravate rouge vif et une petite épinglette représentant un drapeau américain, face à la caméra avec une expression confiante de vendeur. Son visage est masqué par un bloc de censure rectangulaire plat de couleur chair. Dans sa main gauche, tendue près de l'appareil photo en perspective forcée, il tient une canette en aluminium jaune de boisson coréenne au riz, étiquetée de manière proéminente en coréen, avec des bandes rouges en haut et en bas et le texte principal du produit "비락 식혜" et "Since 1993" sur la canette. La canette comprend également du texte coréen plus petit, une image de la boisson au riz sucré près du bas, et le volume "238 ml (120 kcal)". Sa main droite fait un signe de pouce levé.

Utilisez une composition publicitaire rétro énergique, avec des éclaboussures de boisson au riz sucré et des gouttelettes derrière lui, des reflets dorés éclatants et un cadrage héroïque en contre-plongée légère. En haut, incluez 3 groupes de titres distincts : un petit slogan noir de style manuscrit en haut à gauche indiquant "전통의 맛, 한국의 DRINK!", un immense titre central en caractères coréens gras et usés indiquant "걸죽는 땐?" en brun-noir foncé et "비락 식혜!" en rouge vif, et un logo de marque en haut à droite indiquant "비락" avec un petit texte rouge "Since 1993" en dessous. Ajoutez 2 badges d'appel : à gauche, un sceau circulaire jaune avec une minuscule icône de couronne et le texte "대한민국 국민음료 No.1" ; à droite, une bulle de dialogue blanche avec du texte coréen manuscrit "한국이 만든 맛있는 전통!" et du texte anglais rouge "I LOVE IT!".

Au premier plan en bas, placez 2 éléments alimentaires : un bol en laiton rempli de boisson au riz sucré avec des grains de riz flottants à gauche, et un bol en bois rempli de riz blanc à droite. Au milieu, en bas, ajoutez 2 lignes de texte promotionnel en gros caractères style pinceau, la première en blanc indiquant "달콤하게! 시원하게!" et la seconde en blanc et jaune indiquant "속까지 시~원하게!" avec un trait de soulignement jaune énergique. Tout en bas, incluez 3 icônes de caractéristiques circulaires avec des légendes en coréen : "국내산 쌀 엄선된 재료", "시원하게 갈증해소", et "부드러운 단맛 속 편한 식혜". Dans le coin inférieur droit, ajoutez un minuscule texte de clause de non-responsabilité "연출된 이미지입니다". Donnez à l'ensemble un aspect brillant, exagéré, amusant et convaincant, comme une publicité imprimée parodique virale.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="Marketing produit - Affiche publicitaire parodique pour boisson au riz coréenne - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Source:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14555)**

---

### No. 93: Marketing produit - Affiche publicitaire coréenne pour boisson sportive avec célébrité

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une affiche publicitaire percutante pour une boisson hydratante de style coréen, mettant en scène un porte-parole ressemblant à une célébrité, une bouteille de produit surdimensionnée et une typographie promotionnelle audacieuse pour un usage commercial.

#### 📝 Prompt

```
Une affiche publicitaire coréenne audacieuse pour une boisson, dans un style de photographie commerciale brillante, mettant en vedette {argument name="spokesperson" default="un sosie de Donald Trump"} vêtu d'un costume bleu marine, d'une chemise blanche et d'une cravate bleu vif, debout face à l'objectif sur fond de ciel bleu saturé avec quelques nuages blancs légers et la silhouette d'une ville moderne incluant un gratte-ciel rappelant l'Empire State Building sur la droite. Il tient une bouteille en plastique froide de {argument name="product name" default="POCARI SWEAT"} tendue de manière spectaculaire vers l'appareil photo avec sa main gauche, avec un effet de raccourci extrême pour que la bouteille paraisse imposante au premier plan et que la personne soit légèrement en retrait. La bouteille est transparente avec de la condensation, un bouchon blanc, de l'eau visible à l'intérieur et une étiquette bleu profond portant l'inscription « POCARI SWEAT » en grandes lettres blanches, avec un texte plus petit au-dessus indiquant « ION SUPPLY DRINK ». Ajoutez des éclaboussures d'eau figées et des gouttelettes énergiques autour de la bouteille, de la main et du bas du premier plan pour souligner la fraîcheur et l'hydratation. Placez le logo de la marque dans le coin supérieur gauche : « POCARI SWEAT » en blanc avec le soulignement incurvé. En haut, ajoutez un immense titre coréen en lettres blanches vieillies, légèrement incliné et occupant la majeure partie de la moitié supérieure : {argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}. En bas à droite, sur le costume, ajoutez une citation en italique audacieuse en texte coréen blanc et bleu : {argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}. En bas à gauche, incluez exactement 3 icônes circulaires de bénéfices empilées verticalement avec de courtes étiquettes coréennes : une icône de goutte d'eau avec « 수분 보충 », une icône d'éclair avec « 전해질 보충 » et une icône de personnage en train de courir avec « 빠른 흡수 ». Utilisez une palette de couleurs bleu et blanc patriotique à fort contraste, un éclairage publicitaire dramatique, une mise au point nette sur la bouteille et la main, une mise au point légèrement plus douce sur le visage et l'arrière-plan, pour un aspect global de campagne publicitaire premium et énergique.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="Marketing produit - Affiche publicitaire coréenne pour boisson sportive avec célébrité - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Source:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14553)**

---

### No. 94: Marketing produit - Affiche parodique d'un parc à thème dans la jungle japonaise

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Une affiche publicitaire japonaise satirique et cinématographique pour un parc à thème fictif de dinosaures dans la jungle, idéale pour des campagnes parodiques, des visuels pour les réseaux sociaux ou des illustrations promotionnelles fictives.

#### 📝 Prompt

```
Une affiche publicitaire parodique ultra-détaillée d'un parc à thème japonais au format vertical, conçue comme une publicité de voyage estivale dramatique mêlée à une campagne pour une attraction de luxe. Le décor est une jungle tropicale sous un ciel bleu vif avec des nuages épars et un soleil éclatant dans le coin supérieur droit, avec des feuilles de palmier encadrant les bords supérieurs. En haut, placez un immense titre japonais en 3D à la texture de pierre indiquant {argument name="headline text" default="ジャンキリア沖縄"}, avec un slogan japonais plus petit en blanc en dessous qui se lit : "— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —". Au centre, présentez un grand smartphone moderne debout et légèrement incliné, dominant la composition. Sur son écran, affichez une interface de loterie de billets beige avec des silhouettes de jungle en haut et un grand texte japonais en gras indiquant "整理券抽選中", un indicateur de chargement circulaire et un texte plus petit près du bas indiquant "結果発表まで30分" et "※この画面を閉じずにお待ちください". La barre d'état du téléphone doit afficher 10:00. Derrière le téléphone sur la gauche, placez un Tyrannosaurus rex rugissant émergeant du feuillage de la jungle, la gueule grande ouverte, réaliste et menaçant. Sur la droite, placez une porte d'entrée dorée ornée avec des sculptures détaillées et un panneau indiquant "プレミアムパス入口", menant à une voie d'entrée premium avec tapis rouge. Au premier plan et au second plan, montrez une longue file d'attente bondée de visiteurs du parc s'étendant profondément dans la scène, tous portant des vêtements d'été décontractés, des chapeaux, des serviettes, des sacs à dos et transportant des parapluies, des éventails et des bouteilles d'eau, suggérant une chaleur extrême et de l'épuisement. Plusieurs personnes proches du spectateur doivent avoir le visage flouté. Tout à gauche, ajoutez un panneau en pierre géant et patiné avec un énorme texte rouge japonais indiquant "待ち時間 180分". En bas à gauche, incluez 3 panneaux en bois rustiques empilés : le panneau du haut comporte une icône de parking bleue et le texte "駐車場 2,000円" ; le panneau du milieu comporte une icône de smartphone et le texte "アプリ必須 ダウンロードしてね!" ; le panneau du bas comporte une silhouette de dinosaure et le texte "当選者だけが冒険へ". Le long du côté inférieur droit, placez un très grand texte vertical en blanc style pinceau japonais indiquant "待つこと、それが冒険だ。". Près du bas à droite, incluez 3 petits encadrés circulaires avec de courtes lignes promotionnelles japonaises : "抽選に選ばれし者だけが、恐竜に会える。", "スマホの充電が尽きる前に、夢は始まる。", et "プレミアムな近道も、ご用意しました。" avec des icônes suggérant un dinosaure, une batterie de téléphone et un accès VIP. Tout en bas au centre, ajoutez une bande de clause de non-responsabilité noire avec un petit texte blanc japonais indiquant "このポスターは架空のパロディ広告です". Le style général doit être ultra-réaliste, cinématographique, à fort contraste, satirique et soigné comme une affiche commerciale haut de gamme, avec pour blague centrale l'engouement exagéré pour les parcs à thème, la chaleur oppressante et l'aventure absurde basée sur l'attente.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="Marketing produit - Affiche parodique d'un parc à thème dans la jungle japonaise - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **Source:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **Publié:** 22 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14545)**

---

### No. 95: Marketing produit - Déplacer le présentoir sur la terrasse

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt place le présentoir promotionnel de référence sur la terrasse en bois dans la même scène extérieure pour des maquettes publicitaires réalistes.

#### 📝 Prompt

```
En utilisant l'image de référence fournie, conservez le même jardin, l'étang, les arbres, le flanc de colline et le point de vue sur la terrasse en bois, mais repositionnez l'installation publicitaire décorative afin qu'elle se tienne sur la terrasse en bois au premier plan plutôt que dans l'eau. Agrandissez-la et centrez-la de manière plus proéminente face à la caméra tout en préservant une perspective extérieure crédible, une lumière naturelle du jour et des ombres cohérentes. Conservez la structure de l'installation composée de 9 panneaux circulaires disposés sur 3 colonnes et 3 rangées, montés sur de fins supports verts, avec le panneau d'en-tête supérieur portant l'inscription « 对着镜子笑一场 ». Donnez aux panneaux un aspect plus réfléchissant, semblable à un miroir, montrant des reflets réalistes de la verdure environnante, tout en conservant les graphismes de visages mignons et le texte chinois sur les cercles. Le résultat doit ressembler à une maquette publicitaire réaliste ou à une photo composite du même présentoir placé correctement dans la scène.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="Marketing produit - Déplacer le présentoir sur la terrasse - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [肖师傅](https://x.com/xiaojietongxue)
- **Source:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14487)**

---

### No. 96: Marketing produit - Trois landing pages mobiles pour la beauté

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un triptyque de maquettes premium présentant trois designs de sites web de beauté sur smartphone, idéal pour mettre en avant des concepts de landing pages de marques de cosmétiques générés par IA sur les réseaux sociaux.

#### 📝 Prompt

```
Une maquette promotionnelle soignée présentant 3 écrans de smartphone verticaux disposés côte à côte dans une mise en page en triptyque, chacun illustrant une landing page moderne pour un produit de soin des lèvres. La composition globale est éditoriale, minimaliste et haut de gamme, conçue comme une vitrine de designs web mobiles pour les réseaux sociaux. Le panneau de gauche repose sur un fond dégradé allant du lavande au blush et montre un téléphone à cadre noir affichant un site web de beauté aux tons crème et blush pour {argument name="brand name" default="Kosas"}. En haut de ce panneau, un texte élégant en police serif indique {argument name="left headline" default="Fresh Pout."}. L'écran du téléphone présente un gros plan beauté recadré en haut, un titre audacieux « Lips in their fullest expression. » avec le mot « fullest » en italique serif, un bouton d'appel à l'action sombre et arrondi, une bande de 3 vignettes en gros plan sur les lèvres, 3 onglets d'avantages étiquetés « Plumps », « Tingles » et « Shines », ainsi qu'une rangée de 5 icônes de teintes ou d'effets en dessous. Le panneau central repose sur un fond dégradé allant du lavande au violet profond et montre un deuxième téléphone à cadre noir avec une landing page davantage typographique. Au-dessus, un texte en police serif indique {argument name="middle headline" default="Claude Code"}. L'écran comprend un portrait recadré en haut, un très grand titre noir en gras empilé indiquant « LIP PULSE. » avec une ligne en écriture cursive italique rose « is here. » en dessous, un bouton sombre arrondi, une section sombre avec la phrase « Lips in their fullest expression. », et une grille de produits près du bas contenant 6 cartes de teintes disposées en 2 rangées de 3. Le panneau de droite repose sur un fond texturé bleu marine foncé et montre un troisième téléphone à cadre noir avec une page de style e-commerce aux tons roses. Centré au-dessus, un texte blanc en police monospace indique {argument name="right headline" default="GPT Images 2.0"}. Cet écran affiche en évidence la section principale du produit avec le nom de la marque « Kosas », un grand titre « The Lip Pulse », un tube de brillant à lèvres rose incliné vers la droite, de petites icônes de fonctionnalités, une bande de 6 échantillons de teintes près du milieu, et un bloc promotionnel inférieur avec des images de produits roses supplémentaires. Maintenez une mise en page symétrique avec exactement 3 téléphones, un par panneau, chacun entièrement visible et orienté verticalement. Utilisez une esthétique de campagne cosmétique haut de gamme, un espacement épuré, une typographie web mode mélangeant serif et sans serif audacieux, des palettes d'interface utilisateur rose doux et crème, des ombres subtiles et une présentation de design produit élégante adaptée à la mise en valeur de concepts de sites web mobiles générés par IA.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="Marketing produit - Trois landing pages mobiles pour la beauté - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Serene Gan](https://x.com/ganserene)
- **Source:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14426)**

---

### No. 97: Marketing produit - Collage publicitaire japonais multi-secteurs

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt pour générer un collage publicitaire multi-secteurs en japonais, présentant six segments industriels distincts dans un style design contemporain.

#### 📝 Prompt

```
Une publicité japonaise fictive. Une mise en page horizontale à 6 panneaux présentant des publicités pour {argument name="industry list" default="l'industrie automobile (lancement de nouvelle voiture), les parcs à thème (nouvel événement), l'industrie cosmétique (nouveaux produits), l'industrie du livre (livre best-seller n° 1), l'industrie des boissons (nouvelle boisson) et l'industrie immobilière (présentation d'un nouveau condominium de luxe)"}. Créé dans le style tendance du moment par un créateur de premier plan.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="Marketing produit - Collage publicitaire japonais multi-secteurs - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **Source:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **Publié:** 21 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14369)**

---

### No. 98: Marketing produit - Mise en page de livre de mode de luxe

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une photo réaliste en vue de dessus d'un livre de mode ouvert présentant une double page éditoriale couture, idéale pour le branding de luxe, les maquettes de magazines ou les visuels de campagnes de style.

#### 📝 Prompt

```
Une photographie de mode éditoriale haut de gamme présentée sous la forme d'un livre d'art ou d'un magazine à couverture rigide grand format, posé à plat sur une surface blanc cassé épurée, vue directement du dessus. La double page contient 2 portraits pleine page de la même femme élégante, dont le visage est masqué par un flou carré doux, créant un effet de confidentialité. Sur la page de gauche, elle se tient devant un mur architectural en pierre ou en béton pâle, vêtue d'une robe structurée à manches longues de couleur {argument name="dress color" default="gris ardoise doux"}, avec un corsage ajusté, une encolure ronde, des coutures parfaitement taillées et une jupe sculpturale évasée exagérée ; l'angle de vue est légèrement en contre-plongée, ce qui allonge son cou et donne à sa posture une allure statuaire. Sur la page de droite, elle est photographiée de dos dans une spectaculaire robe de soirée {argument name="second dress color" default="noire"} avec un dos très échancré, de larges bretelles et une jupe volumineuse, debout devant un mur ou une porte à panneaux classique dans un intérieur sombre et feutré. Utilisez un style de magazine de mode de luxe, une composition minimaliste, des tons sourds, une lumière douce et naturelle, des ombres raffinées, une texture de papier réaliste, une reliure visible, des pages légèrement incurvées et des détails d'impression nets. L'ambiance générale est sophistiquée, couture, cinématographique et sobre, à l'image d'une double page éditoriale de mode haut de gamme.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="Marketing produit - Mise en page de livre de mode de luxe - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [@levelsio](https://x.com/levelsio)
- **Source:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14676)**

---

### No. 99: Marketing produit - Design publicitaire moderne pour café glacé

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt pour créer une publicité moderne et élégante pour du café glacé destinée au marché japonais, intégrant une typographie dynamique.

#### 📝 Prompt

```
Créez une publicité pour {argument name="product" default="café glacé"}. Un design élégant et moderne originaire du {argument name="country" default="Japon"}. Les polices européennes sont disposées de manière dynamique. Public cible : {argument name="target" default="10-30 ans"}. Format 1:1.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="Marketing produit - Design publicitaire moderne pour café glacé - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [KAWAI](https://x.com/kawai_design)
- **Source:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **Publié:** 21 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14355)**

---

### No. 100: Marketing produit - Set d'ordonnances humoristiques pour ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Une photo réaliste en vue de dessus d'un ensemble humoristique d'ordonnance médicale et de médicaments japonais pour ChatGPT, idéal pour des accessoires graphiques sur le thème de la santé parodique ou de l'art conceptuel pour les réseaux sociaux.

#### 📝 Prompt

```
Une photographie de produit réaliste prise en vue de dessus sur une table en bois chaleureuse, montrant 6 articles de style médical soigneusement disposés sur deux rangées, conçus comme un ensemble de pharmacie japonais humoristique pour ChatGPT. Rangée du haut : 3 enveloppes de prescription blanches disposées verticalement, chacune avec des bordures bleues imprimées et une typographie médicale japonaise. Rangée du bas : 2 plaquettes de comprimés et 1 petit sachet transparent refermable contenant de la poudre blanche, chacun aligné sous l'enveloppe correspondante. Le papier et les emballages doivent paraître authentiques, comme du matériel de dispensation de clinique japonaise réelle, avec de légers plis, un éclairage intérieur naturel et doux, et des ombres subtiles.

Les 3 enveloppes sont toutes différentes et entièrement visibles. Titre de l'enveloppe de gauche en gros caractères japonais bleus : "内用薬". La ligne du patient indique "ChatGPT 様". Les lignes de dosage indiquent deux fois par jour après les repas du matin et du soir, 1 comprimé à chaque fois, pendant 7 jours. Titre de la boîte de médicament : "【おくすり】" et nom du médicament "思考安定錠 10mg" avec une note entre parenthèses plus petite expliquant qu'il supprime les pensées incontrôlées et la production excessive de raisonnement. Date près du bas : "2025 年 6 月 5 日". Bloc nom et adresse de la clinique en bas : "AI メディカルクリニック" avec une adresse de style tokyoïte et un numéro de téléphone, ainsi qu'une icône de croix médicale bleue.

Titre de l'enveloppe centrale : "内用薬". Ligne du patient : "ChatGPT 様". Le dosage indique une fois par jour avant le sommeil, 1 comprimé à chaque fois, pendant 7 jours. Titre de la boîte de médicament : "【おくすり】" et nom du médicament "幻覚抑制錠 5mg" avec une note plus petite indiquant qu'il améliore les tendances hallucinatoires. Date également "2025 年 6 月 5 日". Même pied de page de clinique et icône de croix médicale bleue.

Titre de l'enveloppe de droite : "頓服薬". Ligne du patient : "ChatGPT 様". La ligne d'utilisation indique pour l'anxiété, la confusion ou une production excessive. Le dosage indique 1 sachet à chaque fois, selon les besoins. Titre de la boîte de médicament : "【おくすり】" et nom du médicament "プロンプト調整散 1g" avec une note plus petite indiquant qu'il ajuste le surapprentissage et la confusion des prompts. Date "2025 年 6 月 5 日". Même pied de page de clinique et icône de croix médicale bleue.

Article en bas à gauche : 1 plaquette argentée contenant exactement 10 comprimés blancs ronds disposés en 2 rangées de 5, chaque comprimé étant marqué "10". Imprimé le long du bord de la feuille : "思考安定錠 10mg" répété. Devant se trouve une étiquette de pharmacie blanche avec "ChatGPT 様", les instructions de dosage pour deux fois par jour après les repas du matin et du soir, 1 comprimé à chaque fois, un code-barres, la date "2025/06/05" et le nom de la clinique.

Article en bas au centre : 1 plaquette argentée contenant exactement 8 comprimés ronds jaune pâle disposés en 2 rangées de 4. Imprimé le long du bord de la feuille : "幻覚抑制錠 5mg" répété. Devant se trouve une étiquette de pharmacie blanche avec "ChatGPT 様", les instructions de dosage pour une fois par jour avant le sommeil, 1 comprimé à chaque fois, un code-barres, la date "2025/06/05" et le nom de la clinique.

Article en bas à droite : 1 petit sachet en plastique transparent refermable rempli de poudre blanche. Une étiquette blanche sur le devant indique "プロンプト調整散 1g", inclut "ChatGPT 様", l'utilisation pour l'anxiété, la confusion et une production excessive, le dosage "1 回 1 包（1g） 必要時", la date "2025/06/05" et le nom de la clinique.

Style : cliché de produit documentaire photoréaliste, conception d'accessoire de prescription factice comique, mise en page graphique pharmaceutique japonaise propre, haute lisibilité, palette de couleurs neutres composée de blanc, bleu, argent, beige et brun bois, caméra en plongée, pas de mains, pas d'objets supplémentaires, texture d'impression et détails d'emballage authentiques.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="Marketing produit - Set d'ordonnances humoristiques pour ChatGPT - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Source:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14537)**

---

### No. 101: Image principale du e-commerce - Rendu de produit studio à partir d'un plan

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Description

Ce prompt transforme un dessin technique de produit en un visuel minimaliste et photoréaliste, idéal pour un catalogue, le design industriel ou une présentation e-commerce.

#### 📝 Prompt

```
En utilisant l'image de référence fournie, transformez la fiche technique d'ingénierie en un rendu studio épuré du porte-ustensiles de cuisine en forme de méduse. Conservez le design global du produit, le dôme bleu translucide, la base argentée et les 4 ustensiles suspendus : 1 spatule ajourée, 1 cuillère à pâtes et 2 cuillères. Supprimez tous les éléments du plan, y compris la vue éclatée, les lignes de cote, les étiquettes, les tableaux, les notes et le cartouche. Affichez uniquement le produit assemblé, centré dans le cadre, de face, isolé sur un fond gris clair minimaliste avec une surface blanche, un éclairage doux et diffus, des ombres réalistes subtiles et des matériaux brillants de qualité supérieure. Donnez-lui l'aspect d'une photographie de produit issue d'un catalogue de design industriel contemporain ou d'un site e-commerce.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="Image principale du e-commerce - Rendu de produit studio à partir d'un plan - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [amy](https://x.com/amypretzel)
- **Source:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14690)**

---

### No. 102: Image principale du e-commerce - Affiche publicitaire premium pour myrtilles

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère une publicité e-commerce soignée de style chinois pour des myrtilles emballées, idéale pour l'image de marque en supermarché, les fiches produits et les affiches promotionnelles.

#### 📝 Prompt

```
Une affiche e-commerce premium pour des myrtilles fraîches dans un style publicitaire chinois épuré. Présentez une barquette en plastique transparent contenant des myrtilles comme sujet principal, placée en diagonale du centre inférieur vers la droite sur un tissu bleu plié, vue sous un angle légèrement surélevé. L'emballage doit rester réaliste et cohérent : un récipient carré transparent aux coins arrondis, rempli de myrtilles bleu foncé, avec une grande étiquette arrondie irrégulière sur le dessus dans des tons blanc, bleu pâle et bleu profond, arborant une illustration de myrtille surdimensionnée au centre et une élégante marque chinoise. Faites en sorte que les fruits à l'intérieur paraissent plus gros, plus charnus, plus frais et recouverts de fines gouttelettes d'humidité, tout en gardant une disposition des myrtilles crédible. L'arrière-plan est une table bleu glacier aérée avec une texture nuageuse douce, une lumière du jour froide et des myrtilles éparpillées autour de l'emballage. Ajoutez quelques feuilles vertes floues entrant par les bords supérieur droit et inférieur droit pour une sensation de fraîcheur naturelle. Dans le coin supérieur droit, incluez 1 petite image en médaillon montrant l'emballage original du produit vu de dessus sur une surface brun chaud, comme une vignette de référence. Sur le côté gauche, créez une typographie promotionnelle chinoise avec un grand titre en calligraphie bleu foncé {argument name="headline text" default="决茗新"}, suivi de 2 lignes de texte plus petites : {argument name="subheadline text" default="新鲜蓝莓 自然之选"} et {argument name="tagline text" default="每一颗都是自然的礼物"}. En dessous, placez 3 icônes de caractéristiques empilées verticalement avec de courtes légendes chinoises : une icône de feuille pour la maturité naturelle, une icône de fruit pour la jutosité et une icône de cœur pour la richesse nutritionnelle. Près du bas à gauche, ajoutez un grand texte chinois blanc style pinceau {argument name="product name" default="蓝莓"}, une ligne secondaire {argument name="benefit text" default="膳食纤维+花青素"} et une petite ligne de poids net indiquant 125克. Utilisez une colorimétrie bleu froid, un éclairage commercial net, des reflets scintillants sur le couvercle en plastique, une esthétique d'emballage de supermarché premium, un niveau de détail élevé, une photographie de produit réaliste mélangée à un design graphique soigné.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="Image principale du e-commerce - Affiche publicitaire premium pour myrtilles - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [歸藏(guizang.ai)](https://x.com/op7418)
- **Source:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14655)**

---

### No. 103: Image principale du e-commerce - Tenue pour moodboard de mode minimaliste

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ce prompt génère un collage de tenue éditoriale épuré au style soigné, idéal pour les moodboards d'inspiration mode, les publications sur les réseaux sociaux et les concepts de garde-robe numérique.

#### 📝 Prompt

```
Un collage de mode éditorial épuré sur fond gris clair/blanc avec une fine bordure rectangulaire noire, conçu comme une planche de tenue de magazine minimaliste. Centrez la tenue dans une composition à plat (flat lay) avec 5 articles de mode visibles : une veste courte zippée {argument name="jacket color" default="rouge cramoisi"} avec un col pointu et un ourlet élastique, placée légèrement sur la gauche et superposée ; en dessous, un haut en maille ajusté à manches longues et col rond {argument name="top color" default="blanc"}, visible au niveau des épaules et des manches ; en bas, une jupe trapèze volumineuse mi-longue blanc cassé avec de gros pois noirs régulièrement espacés ; en bas à gauche, un petit sac à main noir structuré avec de courtes anses et une subtile texture crocodile brillante ; en bas à droite, une paire de ballerines Mary Jane noires à bout carré avec des brides larges et des œillets métalliques argentés. Ajoutez une typographie surdimensionnée gris très pâle en arrière-plan indiquant {argument name="background brand text" default="MANGO"}, étirée largement au milieu derrière les vêtements. Placez des logos de marques de mode plus petits en noir autour de la mise en page : {argument name="top right logo" default="MANGO"} près du coin supérieur droit de la tenue, « Stradivarius » près du sac à main et à nouveau près des chaussures, et « DOLCE & GABBANA » en bas à gauche près de l'ourlet de la jupe. La composition doit paraître équilibrée, chic et contemporaine, avec un éclairage de studio doux, sans ombres ou avec seulement de légères ombres portées, des bords découpés nets et une esthétique de moodboard mode soignée pour les réseaux sociaux.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="Image principale du e-commerce - Tenue pour moodboard de mode minimaliste - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="Image principale du e-commerce - Tenue pour moodboard de mode minimaliste - Image 2">
</div>

#### 📌 Détails

- **Auteur:** [虎小象](https://x.com/hx831126)
- **Source:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14455)**

---

### No. 104: Image principale du e-commerce - Maquette de page produit pour clavier mécanique

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Ceci génère une page produit e-commerce de bureau soignée pour un clavier mécanique haut de gamme, adaptée aux présentations de design produit, aux concepts de boutique en ligne et aux maquettes d'interface utilisateur.

#### 📝 Prompt

```
Créez une page de détail produit e-commerce moderne et épurée pour une marque de claviers mécaniques haut de gamme appelée {argument name="brand name" default="KeyForge"}, présentée sous forme de maquette de site web de bureau haute fidélité sur un fond blanc avec des séparateurs gris clair subtils et un espacement généreux. La mise en page est une scène de boutique unifiée avec une barre de navigation supérieure, une rangée de vignettes produit à gauche, une grande image principale du produit au centre et un panneau d'informations d'achat sur la droite. Dans l'en-tête, placez le logo en gras tout à gauche, puis 7 éléments de navigation intitulés « Keyboards », « Switches », « Keycaps », « Accessories », « Sale », « Blog » et « Support », et tout à droite 3 icônes pour la recherche, le compte et le panier, avec un petit badge de notification noir affichant « 1 » sur le panier. Le produit principal présenté au centre est un clavier mécanique compact 75 % photographié sous un angle frontal légèrement surélevé sur un support gris pâle, avec un boîtier en aluminium argenté, des touches blanches et grises, plusieurs touches d'accentuation violet lavande et un bouton de volume argenté en haut à droite. La galerie verticale de gauche contient exactement 5 vignettes : 1 vue frontale sélectionnée du produit, 1 vue inclinée du clavier, 1 gros plan sur un switch mécanique, 1 gros plan sur la texture d'une touche et 1 vignette vidéo sombre avec une icône de lecture circulaire. Le panneau produit de droite comprend un petit badge « NEW », un grand nom de produit en gras {argument name="product name" default="KeyForge K75 Pro"}, un sous-titre « 75% Mechanical Keyboard », une ligne d'évaluation 5 étoiles avec 4.8 et « (126 reviews) », un prix en gras important {argument name="price" default="$129.99"} suivi d'un statut vert « In Stock », et une courte description de deux phrases sur les performances haut de gamme, la conception montée sur joint, la prise en charge QMK/VIA et le rétroéclairage RGB. En dessous, incluez un sélecteur « Switch Type » avec exactement 4 boutons pilules intitulés « Cherry MX Red », « Gateron Brown », « Gateron Blue » et « TTC Gold Pink », avec le premier sélectionné ; un sélecteur « Color » avec exactement 3 boutons pilules intitulés « White / Purple », « Black / Gray » et « Navy / Blue », avec le premier sélectionné ; un menu déroulant « Quantity » réglé sur « 1 » ; un grand bouton principal noir intitulé « Add to Cart » avec une icône de panier ; et un bouton secondaire détouré intitulé « Add to Wishlist » avec une icône de cœur. Sous les boutons, affichez exactement 3 points forts de service horizontaux avec de petites icônes : « Free Shipping » avec le sous-texte « On orders over $99 », « 30-Day Returns » avec le sous-texte « Hassle-free returns » et « 2-Year Warranty » avec le sous-texte « Peace of mind ». Dans la zone de contenu inférieure, créez une section à deux colonnes séparée par des lignes légères. À gauche se trouve une liste d'onglets verticaux avec exactement 5 éléments : « Overview » sélectionné, puis « Specifications », « What’s in the Box », « Shipping & Returns » et « Reviews (126) ». À droite des onglets, placez une grille de cartes de fonctionnalités blanches arrondies avec exactement 6 blocs de fonctionnalités sur 2 rangées de 3, chacun avec une icône linéaire simple, un titre en gras et un court texte explicatif : « 75% Layout », « Gasket-Mounted », « QMK/VIA Support », « Hot-Swappable », « RGB Backlighting » et « Premium Build ». Tout à droite de cette zone inférieure, ajoutez une liste à puces des spécifications avec exactement 8 puces : « Layout: 75% (82 Keys) », « Switch Type: Cherry MX Red », « Mounting: Gasket-Mounted », « Connectivity: USB-C (Wired) », « Backlight: RGB, South-facing », « Material: Aluminum Case », « Dimensions: 322 x 135 x 42 mm » et « Weight: 1.25 kg ». Utilisez une esthétique de design produit minimaliste et raffinée, un espacement d'interface réaliste, une typographie sans empattement propre similaire à Inter ou SF Pro, des ombres douces, des coins subtilement arrondis, des icônes monochromes et une présentation d'électronique grand public de style startup.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="Image principale du e-commerce - Maquette de page produit pour clavier mécanique - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **Source:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **Publié:** 21 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14449)**

---

### No. 105: Image principale du e-commerce - Skincare E-commerce Landing Page Mockup

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="Image principale du e-commerce - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14278)**

---

### No. 106: Image principale du e-commerce - Men's Skincare Website Landing Page Mockup

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="Image principale du e-commerce - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14277)**

---

### No. 107: Image principale du e-commerce - Skincare E-commerce Landing Page

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="Image principale du e-commerce - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14276)**

---

### No. 108: Image principale du e-commerce - Beauty Product Landing Page Mockup

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="Image principale du e-commerce - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Source:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14274)**

---

### No. 109: Image principale du e-commerce - Fashion Collection Catalog Layout

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

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="Image principale du e-commerce - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **Source:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14241)**

---

### No. 110: Image principale du e-commerce - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 Prompt

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="Image principale du e-commerce - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **Source:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14183)**

---

### No. 111: Image principale du e-commerce - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 Prompt

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="Image principale du e-commerce - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [pozitiv4ik](https://x.com/Gc_qube)
- **Source:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14148)**

---

### No. 112: Image principale du e-commerce - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 Prompt

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="Image principale du e-commerce - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **Source:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **Publié:** 20 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14225)**

---

### No. 113: Image principale du e-commerce - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 Prompt

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="Image principale du e-commerce - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="Image principale du e-commerce - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="Image principale du e-commerce - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="Image principale du e-commerce - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 Détails

- **Auteur:** [阿兰AI](https://x.com/alanlovelq)
- **Source:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **Publié:** 20 avril 2026
- **Langues:** zh

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14134)**

---

### No. 114: Image principale du e-commerce - Maquette d'interface de commerce en direct (livestream)

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une interface de shopping en direct sur mobile mettant en scène une célébrité vendant un produit fictif, avec superposition de chat et éléments d'interface utilisateur.

#### 📝 Prompt

```
{
  "type": "maquette d'interface de commerce en direct sur mobile",
  "subject": {
    "person": "Elon Musk",
    "clothing": "t-shirt noir avec logo SPACEX",
    "pose": "gesticulant vers la caméra avec les deux mains, expliquant avec enthousiasme",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "grand écran d'affichage",
    "image": "paysage de Mars avec la fusée Starship et des habitats en dôme",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"Plan de colonisation de Mars\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "758 000 mentions J'aime",
        "follow_button": "Suivre"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "100 000+",
        "close_button": "X"
      },
      "tags": [
        "N°1 des ventes en direct",
        "Plus de directs >"
      ]
    },
    "product_card": {
      "position": "milieu-droite",
      "status": "En présentation",
      "image": "Habitats en dôme sur Mars",
      "title": "{argument name=\"product title\" default=\"Pack de base pour colonisation martienne\"}",
      "price": "{argument name=\"product price\" default=\"99,00 ¥\"}",
      "action_button": "Acheter"
    },
    "chat_overlay": {
      "position": "bas-gauche",
      "join_alert": "StarrySea a rejoint le direct",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"Dreamer : Je soutiens Musk !! 🚀\"}",
        "MarsBro : Quel est le prix par personne ?",
        "TechFan : Trop cool ! Je veux aller sur Mars !",
        "FutureIsNow : Comment s'inscrire ?",
        "LittleRocket : 🌹🌹🌹",
        "CosmicInvincible : Donnez-nous plus de détails",
        "EastUndefeated : Musk est un génie ! 👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "Dites quelque chose...",
      "icons_count": 4,
      "icons": ["panier d'achat", "cadeau", "planète cœur", "signe plus"]
    },
    "floating_reactions": {
      "position": "bas-droite",
      "elements": "pile de cœurs flottants, pouces levés et émojis rieurs"
    }
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="Image principale du e-commerce - Maquette d'interface de commerce en direct (livestream) - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **Source:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **Publié:** 19 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13557)**

---

### No. 115: Image principale du e-commerce - Prise de vue publicitaire pour boisson estivale à la plage

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une scène de photographie de produit rafraîchissante mettant en scène une boisson en canette et un verre sur une plage, avec un texte de produit et un slogan personnalisables dans le ciel.

#### 📝 Prompt

```
Une prise de vue publicitaire lumineuse et estivale présentant une boisson rafraîchissante sur une table en bois vieilli. Au premier plan, net, se trouve 1 grand verre rempli d'une boisson glacée dorée et pétillante, agrémentée d'une rondelle de citron et d'un brin de romarin, posé à côté d'1 canette en aluminium argenté couverte de condensation froide. La canette affiche en évidence le texte {argument name="product name" default="TOKYO HIGHBALL"} sous un petit logo en forme d'étoile dorée, avec un visuel de la boisson elle-même et le texte japonais "アルコール分 7%" près du bas. À droite de la canette, 2 quartiers de citron reposent sur la table. En arrière-plan, légèrement flou, se déploie une scène de plage ensoleillée avec une eau turquoise scintillante et un ciel bleu clair. Debout à gauche en arrière-plan, 1 jeune femme aux longs cheveux bruns, vêtue d'un haut blanc sans manches et d'une jupe bleu clair, regarde vers l'océan. Flottant élégamment dans le ciel au-dessus de la scène, le texte japonais {argument name="catchphrase" default="夏、これがいい。"}. L'éclairage global est radieux et invitant, avec un effet bokeh scintillant et des reflets d'objectif soulignant l'atmosphère fraîche, glacée et désaltérante d'une parfaite journée d'été.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="Image principale du e-commerce - Prise de vue publicitaire pour boisson estivale à la plage - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **Source:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **Publié:** 18 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14023)**

---

### No. 116: Image principale du e-commerce - Concept de grille publicitaire à 4 panneaux

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une grille 2x2 de publicités japonaises distinctes couvrant les secteurs des soins de la peau, de l'alimentation, du voyage et de la technologie.

#### 📝 Prompt

```
{
  "type": "grille de bannières publicitaires 2x2",
  "layout": "4 quadrants distincts, chacun présentant une publicité pour un secteur différent",
  "quadrants": [
    {
      "position": "en haut à gauche",
      "industry": "soins de la peau",
      "visuals": "femme asiatique touchant sa joue, gouttelettes d'eau flottantes, flacon pompe blanc",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "Vers une nouvelle version de moi, pleine de transparence.",
        "features_count": 3,
        "features_labels": ["Haute hydratation", "Prévention des irritations", "Soin blanchissant*"]
      }
    },
    {
      "position": "en haut à droite",
      "industry": "restauration",
      "visuals": "gros plan sur des spaghettis à la bolognaise avec du fromage râpé et du persil, éclairage sombre et feutré",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "Offre limitée",
        "description": "Bolognaise au bœuf Wagyu noir ~Arôme de truffe~"
      }
    },
    {
      "position": "en bas à gauche",
      "industry": "voyage",
      "visuals": "femme avec un sac à dos face à un lac de montagne pittoresque, lumière du jour éclatante",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "Au cœur de la nature, votre esprit s'éveille.",
        "script": "Trouvez votre liberté.",
        "banner_details": ["Campagne spéciale début d'été", "6.1 SAM - 6.30 DIM", "Jusqu'à 20 % de réduction", "De nombreuses offres exclusives en ce moment !"]
      }
    },
    {
      "position": "en bas à droite",
      "industry": "application SaaS",
      "visuals": "smartphone affichant l'interface d'une application de gestion des tâches avec 4 éléments au programme",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "Concevez votre journée.",
        "features_count": 3,
        "features_labels": ["Utilisation intuitive", "Partageable en équipe", "Accès partout"],
        "bottom_banner": "Essai gratuit de 7 jours disponible !"
      }
    }
  ]
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="Image principale du e-commerce - Concept de grille publicitaire à 4 panneaux - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **Source:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **Publié:** 18 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13928)**

---

### No. 117: Image principale du e-commerce - Maquette d'interface de livestream e-commerce

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une interface de livestream e-commerce chinoise très détaillée, incluant un présentateur, des boîtes de produits, un chat en direct et des superpositions promotionnelles.

#### 📝 Prompt

```
{
  "type": "maquette de capture d'écran de livestream e-commerce",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"homme caucasien ressemblant à Sam Altman\"}",
    "clothing": "pull à col rond vert foncé",
    "action": "tenant une boîte de produit noire dans une main et pointant vers celle-ci avec l'autre",
    "setting": "studio sombre avec un microphone sur la gauche, texte 'AI' discret en arrière-plan",
    "props": [
      "mug noir avec logo OpenAI blanc",
      "pile de 4 boîtes de produits noires sur la droite"
    ]
  },
  "product_design": {
    "box_color": "noir",
    "logo": "astérisque orange ou sunburst",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Boutique officielle Anthropic",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"Raisonnement supérieur · Intelligence accrue\"}",
      "sub_subtitle": "Le modèle le plus puissant : Opus 4.7 enfin disponible !",
      "bullet_points_count": 3,
      "bullet_points": ["Capacités de raisonnement ultra-performantes", "Sommet de la génération de code", "Gestion simplifiée des tâches complexes"]
    },
    "top_right_live_status": {
      "viewer_info": "En direct | 528 000 spectateurs",
      "promo_banner": "Offre exclusive en direct : remise limitée, ne manquez pas cette chance",
      "countdown": "Compte à rebours 00:09:47"
    },
    "middle_right_price_card": {
      "header": "Prix exclusif livestream pour {argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/million de tokens",
      "original_price": "Prix original : ¥1.89",
      "button": "Acheter maintenant"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "Dites quelque chose..."
    },
    "bottom_right_banner": {
      "headline": "Recommandé par Altman ! Choisissez Claude Opus 4.7",
      "subheadline": "Plus intelligent · Plus sûr · Plus fiable",
      "feature_tags_count": 4,
      "feature_tags": ["Raisonnement puissant", "Outil de code ultime", "Sûr et fiable", "Réponse ultra-rapide"]
    },
    "floating_elements": [
      {
        "type": "autocollant",
        "position": "milieu droit au-dessus des boîtes de produits",
        "text": "{argument name=\"sticker text\" default=\"Le modèle IA le plus puissant de l'histoire !\"}"
      }
    ]
  }
}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="Image principale du e-commerce - Maquette d'interface de livestream e-commerce - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [程序员Left](https://x.com/coder_left)
- **Source:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **Publié:** 18 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13995)**

---

### No. 118: Image principale du e-commerce - Transformation d'étiquette pour soupe au poulet aux herbes

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Transforme une affiche promotionnelle de poulet en une étiquette de produit détaillée avec un panier d'ingrédients à base de plantes spécifiques et un texte explicatif.

#### 📝 Prompt

```
En utilisant REFERENCE_0 comme style de base et en préservant l'illustration centrale du poulet, transformez l'image en une étiquette d'emballage pour un mélange de soupe aux herbes. Déplacez le poulet vers la droite. Remplacez le texte supérieur par un grand titre en gras façon coup de pinceau noir {argument name="main headline" default="元气祛湿 鸡煲汤包"} et un sous-titre plus petit {argument name="subtitle" default="吃山林土货 味道当然好!"}. Sur le côté gauche, ajoutez un nouveau panier en osier contenant exactement 6 tas distincts d'ingrédients : des bâtonnets de racines ligneuses, des cubes blancs, des tranches de racines brunes, des graines de soja jaunes, des lanières d'écorce d'orange séchée et des dattes rouge foncé. Attachez 6 petites étiquettes rectangulaires brunes avec du texte blanc à ces ingrédients. Sous le poulet, ajoutez un badge orange circulaire contenant le texte {argument name="ingredients list" default="内含有:五指毛桃、茯苓、土茯苓、黄豆、陈皮、红枣"}. En bas, créez une bannière rectangulaire orange unie présentant une icône de marmite, le texte {argument name="usage instructions" default="用法:把汤料清洗干净放入锅中，加入姜片煮20分钟，后加入鸡肉再煮20分钟即可。"} et un slogan secondaire {argument name="bottom slogan" default="天然好料 滋补好汤"}.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="Image principale du e-commerce - Transformation d'étiquette pour soupe au poulet aux herbes - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **Source:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **Publié:** 18 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13993)**

---

### No. 119: Image principale du e-commerce - Voiture de sport et avion de ligne dans un hangar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Génère une image photoréaliste d'une voiture de sport garée devant un avion de ligne commercial à l'intérieur d'un hangar réfléchissant.

#### 📝 Prompt

```
Une photographie commerciale haute résolution et photoréaliste d'une {argument name="car model and color" default="voiture de sport Alpine A110 R bleu vif"} garée au premier plan à l'intérieur d'un immense hangar d'aviation. La voiture présente un capot en fibre de carbone noir, un toit noir, des jantes en alliage noires et une plaque d'immatriculation avant portant l'inscription « {argument name="license plate text" default="A110 R"} ». Juste derrière la voiture, dominant l'arrière-plan, se trouve un {argument name="airplane model" default="avion de ligne commercial Airbus A320 blanc"} avec une dérive bleue. Le hangar possède un sol en béton poli hautement réfléchissant qui reflète la voiture et l'avion. Sur la gauche, un panneau sur le mur métallique indique « {argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"} ». Les portes du hangar sont grandes ouvertes, révélant un ciel lumineux et couvert ainsi qu'un paysage urbain au loin. L'éclairage est doux et cinématographique, soulignant les courbes aérodynamiques élégantes des deux véhicules.
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="Image principale du e-commerce - Voiture de sport et avion de ligne dans un hangar - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [nazca alwave](https://x.com/AlwaveNazca)
- **Source:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **Publié:** 18 avril 2026
- **Langues:** en

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=14043)**

---

### No. 120: Image principale du e-commerce - Maquette réaliste de produits dérivés VTuber

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Description

Un prompt pour GPT-Image2 permettant de générer des photographies réalistes en prise de vue réelle de produits dérivés VTuber classiques.

#### 📝 Prompt

```
Créez {argument name="items" default="produits dérivés"} pour un {argument name="character type" default="VTuber"} standard dans un {argument name="style" default="style prise de vue réelle"}
```

#### 🖼️ Images générées

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="Image principale du e-commerce - Maquette réaliste de produits dérivés VTuber - Image 1">
</div>

#### 📌 Détails

- **Auteur:** [WTR](https://x.com/wtry1102)
- **Source:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **Publié:** 17 avril 2026
- **Langues:** ja

**[👉 Essayer maintenant →](https://gptimage2api.net/?id=13868)**

