
# 🚀 Prompts Increíbles de GPT Image 2


> 🎨 Una colección curada de prompts creativos para GPT Image 2 de OpenAI

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`
> Attribution / 署名: This repository includes adapted material from [YouMind-OpenLab/awesome-gpt-image-2](https://github.com/YouMind-OpenLab/awesome-gpt-image-2) by YouMind OpenLab, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
> Copyright (c) 2026 YouMind OpenLab. Changes were made in this repository. See [ATTRIBUTION.md](ATTRIBUTION.md).

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Click%20to%20View-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Current-brightgreen)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Click%20to%20View-lightgrey)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 Tabla de contenidos

- [🤔 ¿Qué es GPT Image 2?](#-what-is-gpt-image-2)
- [📊 Estadísticas](#-statistics)
- [🔥 Prompts destacados](#-featured-prompts)
- [📋 Todos los prompts](#-all-prompts)

---

## 🤔 ¿Qué es GPT Image 2?

**GPT Image 2** (codename **"duct-tape"**) is OpenAI's next-generation image model. Community testing highlights a leap in these areas:

- 🎯 **Pixel-Perfect Text Rendering** — Native-quality text in Chinese, English, and Japanese, no typos or warped glyphs
- 🎨 **Cross-Image Consistency** — The same character, style, or IP stays identical across a series, down to the pixel
- ⚡ **Commercial-Grade Illustration** — Illustration output is ready to ship without manual polish
- 🌈 **True Art Style Induction** — Creatively evokes the feeling of a style rather than merely approximating references
- 🔧 **Storyboard & Product Series** — Ideal for storyboards, IP characters, and multi-panel product visuals
- 📐 **Multi-Language Design** — Social cards, banners, and posters with accurate multilingual typography in one shot

📚 **Learn More:** See community testing in our [report summary](docs/FAQ.md)

### 🚀 Integración con Raycast

Algunos prompts admiten **argumentos dinámicos** usando la sintaxis de [Raycast Snippets](https://raycast.com/help/snippets). ¡Busca la insignia 🚀 Raycast Friendly!

**Ejemplo:**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

¡Cuando se usa en Raycast, puedes reemplazar dinámicamente los argumentos para iteraciones rápidas!

---

## 📊 Estadísticas

<div align="center">

| Métrica | Cantidad |
|--------|-------|
| 📝 Total de prompts | **1123** |
| ⭐ Destacado | **6** |
| 🔄 Última actualización | **jueves, 23 de abril de 2026, 1:28:58 UTC** |

</div>

---

## 🔥 Prompts destacados

> ⭐ Seleccionados a mano por nuestro equipo por su calidad y creatividad excepcionales

### No. 1: Póster de vista explosionada de casco de realidad virtual

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera un diagrama de vista explosionada de alta tecnología de un casco de realidad virtual con llamadas detalladas de componentes y texto promocional.

#### 📝 Prompt

```
{
  "type": "póster de diagrama de producto en vista explosionada",
  "subject": "casco de realidad virtual",
  "style": "renderizado 3D limpio de alta tecnología, iluminación de estudio, detalles brillantes",
  "background": "{argument name=\"background color\" default=\"degradado suave de morado y azul\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"Una realidad completamente nueva, desde una estructura completamente nueva.\"}"
  },
  "layout": {
    "centerpiece": "vista explosionada verticalmente de un casco de realidad virtual que muestra 9 capas distintas de componentes internos: carcasa exterior, sensores de cámara, placa base con chip, lentes pancake, marco interno, paquetes de baterías, correas laterales, correa superior y almohadilla de interfaz facial.",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\nPotencia de procesamiento abrumadora para experiencias en tiempo real.",
        "Mecanismo de IPD ajustable\nUn ajuste cómodo para una amplia gama de usuarios.",
        "Correa para la cabeza diseñada con precisión\nErgonomía enfocada en la comodidad y la estabilidad."
      ],
      "right_side": [
        "Placa frontal\nDiseño sofisticado y equilibrio de peso óptimo.",
        "Cámaras de seguimiento\nLogran un seguimiento de posición y reconocimiento del entorno de alta precisión.",
        "Lentes pancake\nDiseño delgado que ofrece un amplio campo de visión y una imagen nítida.",
        "Batería de alto rendimiento\nDiseño de energía optimizado para soportar largas sesiones de uso.",
        "Interfaz facial suave\nLogra una sensación de uso cómoda incluso durante largos periodos."
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "{argument name=\"bottom headline\" default=\"La experiencia evoluciona desde la estructura.\"}",
        "body": "Cada pieza contiene tecnología de vanguardia y un diseño meticuloso que respalda la experiencia inmersiva. Meta Quest 3 crea experiencias que te hacen sentir el futuro desde su interior."
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="Póster de vista explosionada de casco de realidad virtual - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [wory＠ホッピング中](https://x.com/wory37303852)
- **Fuente:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13460)**

---

### No. 2: Mapa gastronómico ilustrado de la ciudad

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera un mapa turístico dibujado a mano al estilo acuarela que incluye especialidades gastronómicas locales numeradas, puntos de referencia y una leyenda.

#### 📝 Prompt

```
{
  "type": "infografía de mapa ilustrado",
  "style": "{argument name=\"art style\" default=\"ilustración dibujada a mano con acuarela y tinta sobre pergamino vintage\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"Chengdu\"} {argument name=\"map title\" default=\"Mapa para amantes de la comida\"}",
    "mascot": "pimiento rojo de dibujos animados con gafas de sol y haciendo un gesto de aprobación con el pulgar"
  },
  "border": "{argument name=\"border decoration\" default=\"enredadera de hojas verdes y pimientos rojos\"}",
  "layout": {
    "background": "papel pergamino beige texturizado con carreteras amarillas, ríos azules y zonas de parques verdes",
    "sections": [
      {
        "title": "puntos de referencia",
        "count": 6,
        "illustrations": ["pabellón tradicional", "monasterio tradicional", "rascacielos moderno con un panda trepando", "torre de televisión alta", "puerta tradicional", "edificios industriales"],
        "labels": ["Parque del Pueblo", "Monasterio Wenshu", "IFS", "Torre de TV 339", "Kuanzhai Alley", "Dongjiao Memory"]
      },
      {
        "title": "puntos gastronómicos",
        "count": 12,
        "illustrations": ["mapo tofu", "dumplings en aceite de chile", "brochetas en olla", "bolas de arroz glutinoso", "pastel horneado de huevo", "hotpot de nueve rejillas", "fideos de camote", "brochetas frías", "plato mixto picante", "tazón de té con tapa", "postre de gelatina de hielo", "cabezas de conejo picantes"],
        "labels": ["1 Chen Mapo Tofu", "2 Zhong Dumplings", "3 Chunxi Road", "4 Kuanzhai Alley · San Da Pao", "5 Jianshe Road · Ye Popo Egg Cake", "6 Yulin Road · Xiaolongkan Hotpot", "7 Xiangxiang Alley · Feichang Fen", "8 Wuhouci Street · Boboji", "9 Dongjiao Memory · Maojiao Hula", "10 Parque del Pueblo · Heming Teahouse", "11 Calle antigua Jinli · Bingfen", "12 Shuangliu Old Mother Rabbit Head"]
      },
      {
        "title": "leyenda",
        "position": "bottom-right",
        "count": 5,
        "items": ["punto rojo", "casa verde", "árbol verde", "línea azul", "línea doble amarilla"],
        "labels": ["puntos gastronómicos", "puntos de referencia", "parques y zonas verdes", "ríos y lagos", "carreteras principales"]
      }
    ],
    "centerpiece": "panda gigante sentado comiendo bambú",
    "bottom_right_extras": ["rosa de los vientos vintage con N, S, E, O", "texto de exención de responsabilidad 'Nota: ¡Ten cuidado con el picante, protege tu estómago!' con un icono de pimiento rojo"]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="Mapa gastronómico ilustrado de la ciudad - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [皮皮特](https://x.com/mm_zzm44854)
- **Fuente:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13515)**

---

### No. 3: Diapositiva explicativa de Momotaro en estilo híbrido

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt que combina la estética sencilla y cálida de las ilustraciones de Irasutoya con la alta densidad de información característica de las diapositivas del gobierno japonés.

#### 📝 Prompt

```
Crea una diapositiva explicativa ({argument name="format" default="diagrama ponchi-e"}) sobre {argument name="theme" default="Momotaro"} que fusione la atmósfera amable de "Irasutoya" con la abrumadora densidad de información de las "diapositivas de Kasumigaseki".
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="Diapositiva explicativa de Momotaro en estilo híbrido - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="Diapositiva explicativa de Momotaro en estilo híbrido - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [やまもん](https://x.com/yammamon)
- **Fuente:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13983)**

---

### No. 4: Mockup de interfaz de transmisión en vivo para comercio electrónico

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una interfaz de transmisión en vivo de redes sociales realista superpuesta a un retrato, que incluye mensajes de chat personalizables, ventanas emergentes de regalos y una tarjeta de compra de productos.

#### 📝 Prompt

```
{
  "type": "mockup de interfaz de transmisión en vivo",
  "subject": {
    "description": "retrato de {argument name=\"host name\" default=\"Elon Musk\"}, sonriendo, vistiendo una camiseta negra con un gráfico de esquema técnico en blanco",
    "background": "el lado izquierdo muestra una pantalla con el texto '{argument name=\"left background logo\" default=\"SPACEX\"}', el lado derecho muestra un '{argument name=\"right background logo\" default=\"logotipo T de Tesla\"}' rojo y un coche oscuro"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "avatar, nombre '{argument name=\"host name\" default=\"Elon Musk\"}', subtexto '556 mil me gusta en esta sesión', botón rojo 'Seguir'",
      "rank_badge": "icono de moneda dorada con 'N.º 1 en toda la plataforma'",
      "viewer_stats": "3 avatares de espectadores principales con '123 mil', '86 mil', '57 mil', total '687 mil', botón de cierre 'X'",
      "right_links": "'Más transmisiones >', 'Galería de regalos 0/24' con etiqueta azul 'Clásico'"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "avatar 'Entusiasta de la tecnología', 'envió un corazoncito', icono de corazón x 1314",
        "avatar 'Mar de estrellas', 'envió un cohete', icono de cohete x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "insignia de nivel 37 'Viajero espacial se unió a la transmisión'",
      "message_count": 7,
      "messages": [
        "Pequeño Cohete: ¡Musk! ¡El futuro es prometedor! 🚀",
        "future: ¿Cuándo sale el Tesla Model 2?",
        "Soñador del cielo estrellado: ¿Podrá SpaceX llegar a Marte este año?",
        "Explorador de IA: ¿Cómo va el progreso de Neuralink?",
        "Usuario genial: ¡Hola, Sr. Musk!",
        "Mars: ¡Es mi primera vez en tu transmisión, estoy muy emocionado!",
        "Usuario 123: Habla sobre la IA, ¿reemplazará a los humanos?"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "etiqueta naranja 'Más vendido x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"Camioneta eléctrica Tesla Cybertruck\"}",
      "price": "{argument name=\"product price\" default=\"¥ 1,618,000\"}",
      "button": "botón rojo 'Comprar'",
      "floating_animation": "corazones translúcidos flotando hacia arriba por el borde derecho"
    },
    "bottom_bar": {
      "input_field": "'Escribe algo...'",
      "icons": ["cara sonriente", "tres puntos", "carrito de compras", "caja de regalo", "compartir"]
    }
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="Mockup de interfaz de transmisión en vivo para comercio electrónico - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [神经病不想好转](https://x.com/sjbbxhz)
- **Fuente:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14036)**

---

### No. 5: Batalla de artes marciales estilo anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una dinámica escena de acción estilo anime de dos personajes luchando con auras elementales en un dojo tradicional.

#### 📝 Prompt

```
Una ilustración de anime altamente dinámica de dos chicas inmersas en una feroz batalla de artes marciales dentro de un dojo de madera tradicional. En primer plano, una chica con {argument name="character 1 hair" default="cabello negro en un moño alto con cintas rojas"} adopta una postura de artes marciales baja y poderosa, lanzando un puñetazo hacia adelante. Viste un {argument name="character 1 outfit" default="top de estilo chino blanco con borlas rojas y pantalones rojos holgados"}, con intensos cortes de energía roja arremolinándose alrededor de sus extremidades en movimiento. Suspendida en el aire a la derecha, una chica con {argument name="character 2 hair" default="cabello morado claro en dos moños"} salta con gracia, sonriendo con confianza mientras viste un {argument name="character 2 outfit" default="vestido verde oscuro con bordados dorados y mallas negras"}, acompañada por estelas de energía azul similares al agua. El fondo presenta el interior de un templo rústico de madera con un letrero prominente en la parte superior que dice "{argument name="sign text" default="武術会"}". La escena está llena de acción explosiva, polvo volador, tablas de madera destrozadas, efectos de partículas brillantes y coloridas, y una iluminación dramática en ángulo bajo que separa perfectamente a los personajes del detallado fondo.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="Batalla de artes marciales estilo anime - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **Fuente:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13467)**

---

### No. 6: Infografía de la evolución en escalera de piedra 3D

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Transforma una línea de tiempo evolutiva plana en una infografía realista de una escalera de piedra en 3D con renders detallados de organismos y paneles laterales estructurados.

#### 📝 Prompt

```
{
  "type": "infografía de línea de tiempo evolutiva",
  "instruction": "Usando REFERENCE_0 como base estructural, transforma el diseño vectorial plano en una infografía 3D altamente realista. Reemplaza las rampas lisas por escalones de piedra definidos y mejora todos los organismos a modelos 3D fotorrealistas.",
  "style": {
    "background": "{argument name=\"background style\" default=\"papel pergamino con textura vintage\"}",
    "staircase": "{argument name=\"staircase material\" default=\"bloques de piedra con textura realista\"}",
    "subjects": "{argument name=\"organism style\" default=\"renders 3D fotorrealistas altamente detallados\"}"
  },
  "layout": {
    "main_title": "{argument name=\"main title\" default=\"Evolución humana\"}",
    "sections": [
      {
        "position": "barra lateral izquierda",
        "count": 8,
        "labels": ["L0: Vida unicelular", "L1: Organismos multicelulares", "L2: Reino animal", "L3: Cordados", "L4: Conquista de la tierra", "L5: Clase Mammalia", "L6: Evolución de los homínidos", "L7: Era del Homo sapiens"]
      },
      {
        "position": "superior derecha",
        "title": "Funciones ganadas / Funciones perdidas",
        "description": "Leyenda con iconos de más y menos"
      },
      {
        "position": "centro inferior",
        "title": "Hitos clave de la evolución",
        "count": 6,
        "description": "Línea de tiempo con un gráfico de silueta de 6 figuras que muestra la evolución de simio a humano"
      }
    ],
    "centerpiece": {
      "description": "Escalera de piedra en espiral con 25 escalones numerados que presentan organismos específicos.",
      "count": 25,
      "notable_elements": [
        "Escalón 07: Medusa",
        "Escalón 09: Amonita",
        "Escalón 10: Trilobite",
        "Escalón 24: Humano caminando",
        "Escalón 25: {argument name=\"future evolution concept\" default=\"silueta cósmica brillante con un signo de interrogación\"}"
      ]
    }
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="Infografía de la evolución en escalera de piedra 3D - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [知识猫图解](https://x.com/GeekCatX)
- **Fuente:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13491)**

---

## 📋 Todos los prompts

> 📝 Ordenado por fecha de publicación (más reciente primero)

### No. 1: Perfil / Avatar - Selfie en espejo desde arriba con poses exageradas

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt para probar la consistencia de los personajes y las expresiones dinámicas en una selfie frente al espejo desde una perspectiva cenital.

#### 📝 Prompt

```
{argument name="number of people" default="Tres personas"} frente a un espejo desde una perspectiva cenital tomando una foto grupal con {argument name="pose type" default="poses exageradas"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="Perfil / Avatar - Selfie en espejo desde arriba con poses exageradas - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Fuente:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** zh

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14341)**

---

### No. 2: Perfil / Avatar - Retrato de estudio monocromático en tonos marrones

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato de moda fotorrealista en interiores de una mujer sentada con un conjunto marrón coordinado, ideal para imágenes editoriales de estilo de vida o ropa.

#### 📝 Prompt

```
Un retrato de estudio realista de una joven mujer de Asia Oriental sentada en una silla plegable negra sencilla, encuadrada desde los muslos hasta la cabeza en una composición vertical. Tiene el cabello de color {argument name="hair color" default="castaño oscuro"} con raya casi al centro y recogido en una coleta baja, con algunos mechones suaves cerca de las orejas, pendientes pequeños y delicados, piel clara y tersa, y una pose tranquila y neutral con las manos descansando juntas entre las rodillas. Viste un top corto ajustado de canalé con cremallera frontal en color {argument name="top color" default="marrón chocolate intenso"}, con cuello en punta, mangas tres cuartos y la cremallera parcialmente abierta para crear un escote pronunciado, combinado con pantalones de tiro alto y corte recto en un {argument name="pants color" default="marrón cálido"} a juego. El estilo es monocromático, en tonos marrones, con una sutil textura en la tela y contornos corporales naturales. El fondo es una tela drapeada de color blanco roto con pliegues suaves, iluminada por una luz de ventana difusa de aspecto natural para lograr un estilo editorial de interiores limpio y suave. Fotorrealista, profundidad de campo reducida, sombras suaves, retrato de moda discreto, set minimalista, sujeto centrado, postura sentada relajada, gran detalle en la piel y la textura de la tela.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="Perfil / Avatar - Retrato de estudio monocromático en tonos marrones - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fuente:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14628)**

---

### No. 3: Perfil / Avatar - Retrato fotorrealista de uniforme escolar en un santuario

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato fotorrealista y pulido de una joven con uniforme escolar en exteriores, ideal para moda editorial, visuales de personajes o retratos con IA de estilo lifestyle.

#### 📝 Prompt

```
Un retrato fotorrealista de medio cuerpo de una {argument name="subject" default="joven"} de pie en exteriores bajo una brillante luz solar natural, encuadrada en una composición vertical. Tiene el cabello largo y liso de color {argument name="hair color" default="castaño oscuro"} con un brillo sedoso, ligeramente separado del centro y cayendo sobre ambos hombros. Viste una camisa de uniforme escolar blanca de manga corta impecable con cuello estructurado, una corbata a rayas azul marino y un parche con un escudo bordado detallado en el bolsillo izquierdo del pecho que presenta una corona y un emblema heráldico. Posiciónala en un ligero ángulo de tres cuartos con una postura relajada, con la cabeza girada sutilmente hacia un lado para lograr un estilo de fotografía de moda cándida y refinada. Ubícala frente a un {argument name="background setting" default="santuario rojo"} vívido con pilares rojos intensos y un detalle de techo azul curvo visible en el fondo desenfocado, utilizando una profundidad de campo reducida y un bokeh suave para mantener al sujeto perfectamente enfocado. La iluminación debe ser limpia, de alto contraste y favorecedora, con reflejos brillantes en el cabello y la camisa, pliegues de tela realistas, tonos de piel naturales y una estética de retrato premium pulida que recuerda a la fotografía comercial japonesa.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="Perfil / Avatar - Retrato fotorrealista de uniforme escolar en un santuario - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AIおじさん](https://x.com/AIojisan1952)
- **Fuente:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14515)**

---

### No. 4: Perfil / Avatar - Retrato de selfie en interiores con censura y estilo moody

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un selfie fotorrealista y elegante de un hombre joven con camisa de cuello abierto junto a una ventana, ideal para crear retratos creíbles para redes sociales.

#### 📝 Prompt

```
Un retrato realista estilo selfie en interiores de un hombre joven de Asia Oriental, desde el pecho hacia arriba, sentado cerca de una ventana moderna y grande en un apartamento de gran altura o habitación de hotel durante una luz diurna suave. Tiene cabello de color {argument name="hair color" default="black"}, grueso y ligeramente despeinado con raya al medio y volumen suave sobre la frente y los lados. Su complexión parece delgada, con cuello largo y piel clara y tersa. Viste una camisa de botones de color {argument name="shirt color" default="black"} hecha de algodón mate o popelina, ligeramente holgada, con los botones superiores desabrochados para crear un cuello abierto profundo y un estilo relajado e informal. La cámara se sostiene cerca en un ángulo de selfie natural, en orientación vertical, encuadrando los hombros, el pecho, el cuello y la cabeza. Su rostro está completamente oculto por un gran bloque de censura rectangular centrado con efecto de desenfoque o mosaico, mientras que las orejas, los bordes de la mandíbula, el cuello y el cabello permanecen visibles. El ambiente es sobrio, melancólico y elegante, con colores neutros apagados, luz suave de ventana desde el lado derecho, sombras tenues y una sensación de selfie casual para redes sociales. Los detalles del fondo incluyen 1 sección de pared beige a la izquierda, 1 pequeño panel de control de pared oscuro, 1 borde metálico vertical o borde de lámpara, y 2 paneles de ventana altos con marco oscuro a la derecha con un horizonte urbano tenue y desenfocado al exterior. Foto fotorrealista de smartphone, interior moderno y limpio, poca profundidad de campo, textura de piel natural, contraste sutil, sin sonrisa visible debido al bloque de censura, edición mínima, selfie personal elegante y creíble.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="Perfil / Avatar - Retrato de selfie en interiores con censura y estilo moody - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [MathMedix](https://x.com/MathMedix)
- **Fuente:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14686)**

---

### No. 5: Perfil / Avatar - Retrato selfie realista en McDonald's

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una selfie casual fotorrealista de un hombre dentro de un McDonald's, útil para crear instantáneas de restaurante con un estilo auténtico para redes sociales.

#### 📝 Prompt

```
Una selfie casual de smartphone altamente realista tomada en el interior de un restaurante McDonald's en Asia, encuadrada como un retrato de medio cuerpo de un hombre joven sentado a una mesa. La cámara se sostiene ligeramente por encima de la altura de la mesa a la distancia de un brazo, creando una perspectiva natural de selfie frontal con un antebrazo extendiéndose hacia el lente. El sujeto viste una camiseta negra con un pequeño logotipo blanco de Tesla en el pecho izquierdo, tiene el cabello negro corto y liso, monturas de gafas oscuras y delgadas parcialmente visibles, y apoya una mano ligeramente contra su barbilla en una pose relajada. Su rostro está completamente oculto por un gran bloque rectangular sólido de desenfoque en el centro, preservando la privacidad mientras deja visibles el cabello, las orejas, los bordes de la mandíbula y las patillas de las gafas. En el primer plano inferior izquierdo se encuentra 1 vaso de papel blanco de McDonald's con tapa y una pajita blanca, recortado por el encuadre. El fondo muestra el área del mostrador del restaurante con una iluminación ambiental cálida, 1 gran panel de pared rojo a la izquierda que presenta los arcos amarillos de McDonald's y el eslogan blanco “i’m lovin’ it” con texto en chino debajo, 4 tableros de menú digitales iluminados en la parte superior que muestran hamburguesas, papas fritas, combos, precios y texto en chino, además de 2 personas al fondo cerca del mostrador, una de espaldas con una mochila y otra parcialmente visible detrás de la caja registradora. Utiliza un balance de color natural, un ligero grano de interior, reflejos realistas, una profundidad de campo de baja a moderada y el aspecto espontáneo de una instantánea de redes sociales no preparada.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="Perfil / Avatar - Retrato selfie realista en McDonald's - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Fuente:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14433)**

---

### No. 6: Perfil / Avatar - Instantánea de Instagram de cosplay de Albedo

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt conciso para generar una foto de cosplay rebelde y expresiva al estilo de una historia de Instagram.

#### 📝 Prompt

```
Estilo: Una instantánea de historia de Instagram de un cosplay de {argument name="character" default="Albedo"}; Contenido: {argument name="action" default="en cuclillas en el suelo mirando a la cámara, haciendo gestos rebeldes exagerados con ambas manos, poniendo los ojos en blanco, con una expresión arrogante y desdeñosa"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="Perfil / Avatar - Instantánea de Instagram de cosplay de Albedo - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **Fuente:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** zh

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14347)**

---

### No. 7: Perfil / Avatar - Chica gato en la azotea escolar al atardecer estilo anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un retrato cinematográfico estilo anime de una colegiala con orejas de gato en una azotea al atardecer, ideal para imágenes clave nostálgicas, arte de personajes o publicaciones en redes sociales.

#### 📝 Prompt

```
Una ilustración de anime de alta calidad de una {argument name="character type" default="colegiala con orejas de gato"} inclinada sobre la barandilla metálica de una azotea escolar al atardecer, vista desde un ángulo de tres cuartos ligeramente bajo y cercano. Tiene el cabello largo y fluido de color {argument name="hair color" default="castaño oscuro"} con reflejos suaves, grandes ojos reflectantes de color marrón grisáceo, gafas redondas de montura fina y 2 orejas de gato esponjosas que emergen de su cabello. Su expresión es tranquila, melancólica y ligeramente tímida, con los labios entreabiertos y una mirada suave hacia el espectador. Viste un uniforme escolar de marinero japonés con una blusa de manga larga de color {argument name="uniform color" default="rosa"} suave, un cuello de marinero gris con rayas blancas, un lazo rojo intenso en el cuello y una falda de cuadros parcialmente visible, con 2 correas de mochila oscuras sobre sus hombros. La escena está bañada por una dramática iluminación a contraluz de la hora dorada, con una intensa luz cálida en el contorno de su cabello, orejas, hombros y mangas, un destello solar brillante desde la parte inferior izquierda y un cielo ricamente pintado lleno de nubes naranjas y color melocotón. En el fondo, se muestra un edificio escolar japonés de 2 pisos con techo de tejas rojas y ventanas brillantes iluminadas por el atardecer. Enfatiza la calidad visual de anime nostálgico de principios de los 2000, líneas delicadas, ojos luminosos, mechones de cabello detallados, composición cinematográfica, profundidad de campo suave, gradación de color cálida y vibrante, sombreado pulido y una atmósfera emocional serena.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="Perfil / Avatar - Chica gato en la azotea escolar al atardecer estilo anime - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **Fuente:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14547)**

---

### No. 8: Perfil / Avatar - Mujer de fantasía abrazando a un carnero blanco

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato realista de fantasía medieval de una mujer pelirroja abrazando a un carnero blanco con cuernos, ideal para arte de personajes atmosférico o visuales de fantasía de estilo editorial.

#### 📝 Prompt

```
Un retrato vertical fotorrealista y cinematográfico de una mujer medieval o de fantasía con {argument name="hair color" default="largo cabello rojo cobrizo"}, mostrado desde el pecho hacia arriba, abrazando suavemente a un gran carnero blanco. La mujer viste un vestido o túnica de lana de color verde musgo oscuro con puños bordados ornamentados y una pesada capa o chal con borde de piel sobre los hombros, evocando una estética vikinga o de las tierras altas. Su cabello es grueso, ondulado y ligeramente despeinado por el viento, con pequeñas trenzas tejidas en la coronilla. El carnero tiene un vellón denso y rizado de color blanco crema, una expresión tranquila con los ojos cerrados y prominentes cuernos en espiral que se curvan hacia afuera y hacia adelante. La mano de la mujer descansa tiernamente en el cuello del carnero, transmitiendo calidez, protección y compañía. Ambientado al aire libre en un paisaje escarpado y nublado con colinas o páramos suavemente desenfocados en el fondo, cielo gris frío, poca profundidad de campo, iluminación natural difusa, detalles de textura ricos en el cabello, la lana, el pelaje y la tela, paleta de colores tierra apagados, encuadre íntimo, piel y rasgos animales realistas. Añade texto negro en la esquina superior izquierda que diga {argument name="corner text" default="GPT Image 2"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="Perfil / Avatar - Mujer de fantasía abrazando a un carnero blanco - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **Fuente:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14619)**

---

### No. 9: Perfil / Avatar - Retrato de idol kawaii rosa con pintalabios

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato brillante al estilo idol de anime para pósteres, arte en redes sociales o imágenes clave de personajes adorables.

#### 📝 Prompt

```
Un retrato de idol de anime brillante y altamente detallado en composición vertical, que muestra a una linda chica adolescente de cintura para arriba con una estética kawaii rosa de ensueño. Tiene el cabello {argument name="hair color" default="rosa pastel"} peinado en una coleta alta muy larga y voluminosa con flequillo suave y mechones rizados, decorado con múltiples clips de corazones pequeños y horquillas cruzadas. Sus ojos son grandes, brillantes y de un vívido {argument name="eye color" default="verde esmeralda"}, con reflejos en forma de estrella, pestañas largas y un brillo ligeramente acuoso. Tiene un rubor suave, labios pequeños y brillantes, y una expresión afectuosa mientras se aplica pintalabios {argument name="lipstick color" default="rosa brillante"}, sosteniendo el tubo de pintalabios delicadamente con ambas manos cerca de la boca. Viste un vestido de idol estilo gothic lolita con volantes en negro y rosa, con encaje, cintas, lazos, adornos de corazones y texturas brillantes, además de 1 diadema con lazo de encaje negro y un corazón enjoyado rosa, 3 accesorios visibles en el flequillo, 1 par de pendientes de corazón colgantes y 1 gargantilla negra con un pequeño dije de corazón. Rodea al personaje con un fondo rosa caramelo brillante lleno de bokeh, destellos, efectos de luz de neón suave y una atmósfera de fan de idol. Añade 5 burbujas de texto con corazones dibujados a mano alrededor de ella en japonés, que digan: "かわいすぎてごめん…♡", "推してくれてありがとうっ♡", "ずーっとだいすきっ♡", "世界でいちばんの推しになってね…♡" y "ずっと一緒だよ？約束ね…♡". Incluye una pequeña tarjeta fotográfica decorada o un póster de la misma chica en el fondo superior derecho. Ilustración ultra pulida, brillo denso, iluminación romántica, reflejos brillantes, detalles de encaje intrincados, fondo de enfoque suave, paleta rosa saturada, sensación de póster de idol adorable.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="Perfil / Avatar - Retrato de idol kawaii rosa con pintalabios - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ねね*AIcreator](https://x.com/NeneneAI)
- **Fuente:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14606)**

---

### No. 10: Perfil / Avatar - Pelícano minimalista montando en bicicleta

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una ilustración vectorial geométrica minimalista de un pelícano en bicicleta, útil para probar la composición de formas simples o crear una imagen de estilo icono abstracto y divertido.

#### 📝 Prompt

```
Una ilustración de estilo vectorial minimalista sobre un fondo gris claro plano que muestra a un pelícano montando una bicicleta, dibujado a partir de formas geométricas simples con contornos gruesos de color carbón oscuro. La composición es amplia y centrada, con la bicicleta ocupando los dos tercios inferiores de la imagen y la cabeza del ave flotando ligeramente por encima y por delante del manillar de una manera deliberadamente abstracta, similar a un diagrama. La bicicleta es una silueta simple de bicicleta de carretera negra en vista lateral con exactamente 2 ruedas grandes, cada una con un borde exterior grueso y exactamente 4 líneas de radios visibles que forman una cruz, una línea de suelo horizontal recta debajo de ambas ruedas, un cuadro triangular, un sillín negro corto y detalles simplificados de biela y pedal cerca de la parte trasera del cuadro. El pelícano está construido a partir de piezas abstractas limpias: una cabeza redondeada blanca con un pequeño ojo circular negro, un pico largo y abierto apuntando a la izquierda hecho de 2 partes con una sección triangular superior naranja y una sección de bolsa inferior de color rosa pálido, una curva oscura corta en la parte superior de la cabeza, un pequeño conector de cuello/cuerpo ovalado blanco separado, un cuerpo redondeado blanco más grande posicionado sobre la bicicleta y una única forma de ala blanca inclinada hacia arriba sobre la espalda. Añade exactamente 2 formas de patas naranjas, rectángulos largos y estrechos inclinados hacia abajo desde el cuerpo hacia el cuadro de la bicicleta, sugiriendo que el ave está pedaleando. Mantén las formas intencionalmente escasas y ligeramente surrealistas, como una prueba de logotipo o un garabato simple de editor de código, sin sombreado, sin degradados, sin texturas, sin texto y con mucho espacio negativo.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="Perfil / Avatar - Pelícano minimalista montando en bicicleta - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Justin Schroeder](https://x.com/jpschroeder)
- **Fuente:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14657)**

---

### No. 11: Perfil / Avatar - Transformación de retrato de gato a humano

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt convierte una foto de referencia de un gato en una versión humana fotorrealista, preservando la pose, composición y entorno originales para crear retratos divertidos de mascotas a personas.

#### 📝 Prompt

```
Utilizando la imagen de referencia proporcionada, convierte al gato en un retrato humano realista manteniendo la misma pose de descanso, ángulo de cámara, encuadre y el mismo fondo de silla turquesa de felpa. Conserva el patrón de colores naranja y blanco del gato como inspiración para el aspecto humano: convierte a la persona en una mujer joven de piel clara con cabello pelirrojo cálido y una expresión suave y tranquila. Vístela con ropa de estar cómoda en color blanco roto: 1 suéter de punto holgado con cuello en V y 1 par de pantalones color crema con cordón, sentada de forma natural en la silla con un lenguaje corporal relajado. Haz que sea fotorrealista, con iluminación interior natural suave y calidad de fotografía editorial de estilo de vida.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="Perfil / Avatar - Transformación de retrato de gato a humano - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Bojan Tunguz](https://x.com/tunguz)
- **Fuente:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14670)**

---

### No. 12: Perfil / Avatar - Retrato de estudio con helado de fresa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un elegante retrato de estudio al estilo de las celebridades, protagonizado por una mujer de cabello oscuro que sostiene un cono de helado de fresa frente a su rostro; ideal para editoriales de belleza o imágenes de cultura pop.

#### 📝 Prompt

```
Un pulido retrato de estudio de una mujer glamurosa, al estilo de una estrella del pop, desde el pecho hacia arriba, centrada sobre un fondo gris neutro y uniforme. Tiene {argument name="hair color" default="negro azabache"} cabello largo, suelto y ondulado con raya al medio, brillo intenso y un volumen suave que cae sobre ambos hombros. Su rostro está mayormente oculto detrás del cono de helado que sostiene frente a su boca y parte inferior de la cara, creando una composición editorial de moda divertida. Viste una camiseta de tirantes blanca de canalé con tirantes anchos y un único pendiente de brillante visible. En su mano sostiene 1 cono de barquillo coronado con 1 bola grande de helado de fresa rosa con remolinos de bayas de color rojo oscuro y una textura ligeramente derretida. Iluminación de belleza cálida y favorecedora, sombras suaves, tonos de piel realistas, fotografía de retrato de celebridades de alta gama, enfoque nítido en la mano, el cono, el cabello y los hombros, fondo minimalista, ambiente sutilmente sensual y chic, recorte vertical.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="Perfil / Avatar - Retrato de estudio con helado de fresa - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Arturo Garrido](https://x.com/arturogarrido)
- **Fuente:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14594)**

---

### No. 13: Perfil / Avatar - Retrato de nube de puntos censurado

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera un retrato sobrio en blanco y negro al estilo lidar de un hombre con traje, construido a partir de densas partículas blancas, ideal para visuales editoriales de tecnología, temas de privacidad o imágenes de identidad futuristas.

#### 📝 Prompt

```
Un retrato monocromático minimalista hecho completamente de millones de diminutos puntos blancos de nube de puntos sobre un fondo negro absoluto, que muestra a 1 hombre adulto desde el pecho hacia arriba con un blazer oscuro formal y una camisa de cuello claro. El sujeto está centrado ligeramente hacia la derecha, mirando hacia adelante con un sutil giro de tres cuartos, con el cabello corto bien peinado y una oreja visible definida nítidamente por densas partículas tipo lidar. Renderiza la figura como datos de escaneo 3D en bruto mezclados con lógica de contorno topológico: punteado ultradenso, colocación geométrica precisa de puntos, estructura de isolíneas tenue y un modelado de profundidad limpio en el cabello, las solapas de la chaqueta, el cuello, la nuca y los hombros. Mantén el rostro intencionalmente oculto por 1 gran bloque rectangular vertical de censura en gris oscuro a negro, perfectamente centrado sobre el área facial desde la frente hasta debajo de la nariz, creando un marcado efecto de máscara de privacidad. Usa textura mate, bordes definidos, enfoque nítido, alto contraste, sin brillo, sin resplandor, sin neón, sin niebla, sin desenfoque de movimiento, sin aberración cromática, sin trazos pictóricos. Añade 1 pequeño icono de destello de cuatro puntas en gris claro en la esquina inferior derecha. La imagen general debe sentirse matemática, forense y futurista, como un retrato de escaneo lidar de alta resolución en 8k.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="Perfil / Avatar - Retrato de nube de puntos censurado - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="Perfil / Avatar - Retrato de nube de puntos censurado - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [Harshith](https://x.com/HarshithLucky3)
- **Fuente:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14408)**

---

### No. 14: Perfil / Avatar - Dios griego montando un león

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt cinematográfico para generar una imagen épica de una persona caracterizada como un dios griego montando un león a través de la sabana africana.

#### 📝 Prompt

```
haz que me vea como un {argument name="persona" default="dios griego"} montando un {argument name="mount" default="león"} en las {argument name="setting" default="llanuras de áfrica"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="Perfil / Avatar - Dios griego montando un león - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="Perfil / Avatar - Dios griego montando un león - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [Max Blade](https://x.com/_MaxBlade)
- **Fuente:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14326)**

---

### No. 15: Perfil / Avatar - Retrato de chica anime rubia confundida

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un sencillo retrato de busto estilo anime en tonos pastel de una chica desconcertada con un suéter azul, ideal para avatares, arte de perfil o ilustraciones de personajes casuales.

#### 📝 Prompt

```
Un retrato anime suave y minimalista de una joven linda de la cintura para arriba sobre un fondo gris claro liso, dibujado en un estilo pastel limpio con arte lineal muy fino tipo boceto y colores planos y suaves. Tiene el cabello largo y fluido de color rubio pálido con capas suaves y flequillo largo que cubre parcialmente su frente, grandes ojos redondos de color azul claro, piel clara y una boca pequeña ligeramente abierta que transmite una leve confusión. Lleva una prenda de manga larga holgada y de talla grande {argument name="clothing color" default="light pastel blue"} con un escote ancho y relajado. Su pose está ligeramente inclinada hacia el espectador, con una mano levantada y un dedo índice tocando el lado de su cabeza como si estuviera desconcertada. Coloca exactamente 1 signo de interrogación azul flotante cerca del lado superior izquierdo de su cabeza. La expresión debe sentirse inocente, distraída y encantadora. Mantén la composición centrada, aireada y despejada, sin objetos adicionales, sin fondo detallado y sin sombras marcadas.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="Perfil / Avatar - Retrato de chica anime rubia confundida - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="Perfil / Avatar - Retrato de chica anime rubia confundida - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="Perfil / Avatar - Retrato de chica anime rubia confundida - Image 3">
</div>

#### 📌 Detalles

- **Autor:** [Torishima / INTP](https://x.com/izutorishima)
- **Fuente:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14474)**

---

### No. 16: Perfil / Avatar - Retrato de chica anime en tonos azul suave

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato minimalista de busto estilo anime en colores pastel de una chica de cabello azul con una sudadera azul claro extragrande, ideal para avatares, imágenes de perfil o arte de personajes suave.

#### 📝 Prompt

```
Un retrato de busto estilo anime suave de una joven linda centrada sobre un fondo liso de color blanco roto cálido, dibujado con líneas delicadas y limpias y colores pastel planos. Tiene el cabello muy largo y liso de color {argument name="hair color" default="azul cielo pálido"} con mechones finos, flequillo completo ligeramente separado cerca del centro y grandes ojos azules a juego con reflejos brillantes. Su expresión es tímida y confundida, con las cejas ligeramente levantadas, un ligero rubor rosado en las mejillas y la boca pequeña y entreabierta. Mira directamente al espectador mientras se toca ligeramente el labio inferior con un dedo índice en una pose pensativa y vacilante. Viste una sudadera extragrande y holgada de color {argument name="top color" default="azul claro"} con mangas largas que cubren parcialmente su mano. Encuadra la imagen desde el pecho hacia arriba, con la cabeza ligeramente inclinada, transmitiendo una sensación suave, inocente y soñadora. Utiliza una composición minimalista, sin accesorios, sin objetos adicionales, sin paisajes y sin texto. Enfatiza una paleta monocromática azul, una simplicidad etérea, contornos sutiles tipo boceto y una estética de ilustración japonesa limpia adecuada para un avatar personal suave.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="Perfil / Avatar - Retrato de chica anime en tonos azul suave - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Torishima / INTP](https://x.com/izutorishima)
- **Fuente:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14473)**

---

### No. 17: Perfil / Avatar - Retrato de selfie en espejo de lujo en interiores

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una selfie en espejo realista de estilo fashion de una mujer con un vestido marfil entallado, útil para imágenes de estilo de vida, moda o glamour para redes sociales.

#### 📝 Prompt

```
Una selfie en espejo realista en interiores de una mujer joven, esbelta y glamurosa, de pie en una sala de estar de lujo o suite de hotel con iluminación suave, fotografiada verticalmente desde la cabeza hasta debajo de las rodillas. Viste un vestido midi ajustado de color crema o marfil con drapeados y fruncidos elegantes, que presenta un escote asimétrico con un tirante cruzando diagonalmente sobre el pecho y dejando el otro hombro al descubierto. Su cabello es largo, castaño oscuro, con ondas suaves y raya casi al centro, cayendo sobre ambos hombros. Sostiene un smartphone en su mano derecha frente a su rostro, cubriéndolo parcialmente, con el teléfono inclinado hacia un espejo de pared; el teléfono tiene una funda oscura con un patrón de nubes rojas. Su brazo izquierdo cuelga naturalmente a su lado. Añade joyería sutil: un collar fino con un pequeño colgante, una pulsera o brazalete de plata en la muñeca derecha y anillos en los dedos de la mano que sostiene el teléfono. Enfatiza una silueta femenina realista, piel suave, iluminación ambiental cálida y suave, y una fotografía pulida al estilo editorial de redes sociales. El fondo debe incluir un sofá beige detrás de ella, un bolso de cuero marrón descansando en el lado derecho del sofá, una pared de acento de piedra o concreto texturizado detrás del área del espejo, y un pasillo cálido a la izquierda con dos obras de arte enmarcadas visibles. Utiliza sombras naturales de interior, textura de piel refinada, pliegues de tela realistas y compresión alrededor de la cintura y las caderas, estética de apartamento de lujo, composición limpia y alto nivel de detalle.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="Perfil / Avatar - Retrato de selfie en espejo de lujo en interiores - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Danna R.](https://x.com/daaaaanc)
- **Fuente:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14421)**

---

### No. 18: Perfil / Avatar - Selfie realista frente al espejo con vestido blanco

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una selfie de moda fotorrealista frente al espejo en el interior de un apartamento cálido, ideal para fotos de outfits, contenido de estilo de vida y comparaciones de realismo.

#### 📝 Prompt

```
Una selfie realista frente al espejo en interiores de una joven delgada de pie en la sala de estar de un apartamento moderno con iluminación cálida, vistiendo un vestido midi ajustado de color blanco marfil, con un solo hombro y fruncidos en el torso y las caderas. Tiene el cabello castaño oscuro, liso y a la altura de los hombros, con raya al medio; lleva joyas minimalistas que incluyen 2 anillos, un brazalete de plata y pendientes pequeños y discretos. Su rostro está oculto por el teléfono mientras toma la foto con una mano levantada, sosteniendo un smartphone con funda negra decorada con motivos de nubes rojas. Está de pie ligeramente inclinada con una postura relajada, un brazo a su lado, mostrando una silueta femenina natural. La escena está encuadrada verticalmente como una selfie casual de outfit para redes sociales. Detrás de ella hay un sofá de tela beige con 1 cojín estampado de motivos geométricos grises y 1 bolso de cuero color marrón topo colocado sobre el asiento. El fondo incluye una pared decorativa de color bronce marrón con textura, suelo de baldosas color crema brillante, un pasillo tenue a la izquierda con 3 obras de arte enmarcadas y luces cálidas empotradas en el techo. Iluminación ambiental suave de atardecer, tonos de piel naturales, tensión y pliegues de tela realistas, reflejos sutiles en el espejo, estética de apartamento elegante y limpia, alto realismo, textura de piel fotorrealista, perspectiva de cámara de smartphone.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="Perfil / Avatar - Selfie realista frente al espejo con vestido blanco - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Danna R.](https://x.com/daaaaanc)
- **Fuente:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14419)**

---

### No. 19: Perfil / Avatar - Retrato de lujo con vestido en Santorini

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato fotorealista de moda y viajes en formato vertical de una mujer glamurosa con un vestido blanco posando en Santorini, ideal para imágenes de vacaciones de lujo, estilo de vida o editoriales.

#### 📝 Prompt

```
Un retrato glamuroso de moda y viajes de una {argument name="woman" default="mujer rubia"} sentada en una repisa de piedra iluminada por el sol con vistas a la caldera en Santorini, Grecia, con edificios encalados en la ladera que descienden hacia un mar azul profundo y escarpadas islas volcánicas a lo lejos. Viste un fluido vestido marfil con cuello halter y un escote muy pronunciado, aberturas laterales, cintura fruncida con un detalle de anillo circular y tela plisada suave sobre su regazo. Su cabello es largo, ondulado y de color {argument name="hair color" default="rubio dorado"}, peinado suelto sobre sus hombros. Añade collares delicados en capas, incluyendo un pequeño colgante y una cruz de plata, además de una pulsera o reloj en una muñeca. Coloca una clásica iglesia griega blanca con una cúpula de color {argument name="dome color" default="azul"} brillante en el fondo superior derecho, y enmarca el lado derecho de la imagen con vibrantes buganvillas de color {argument name="flower color" default="rosa magenta"} en plena floración. La iluminación es el brillante sol mediterráneo del mediodía con reflejos nítidos, un suave brillo en la piel y una suave profundidad de campo que mantiene a la mujer enfocada mientras la arquitectura del fondo y el mar están ligeramente suavizados. La composición es vertical, elegante y aspiracional, con la mujer centrada ligeramente a la derecha, torso visible hasta la falda fluida, y la costa escénica extendiéndose por la mitad izquierda del encuadre. Añade un pequeño texto negro en la esquina superior izquierda que diga {argument name="corner text" default="GPT V2"}. Estética de vacaciones de lujo fotorealista, alto detalle, colores naturales, vibra editorial de viajes para Instagram.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="Perfil / Avatar - Retrato de lujo con vestido en Santorini - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Ed](https://x.com/Eduardopto)
- **Fuente:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14428)**

---

### No. 20: Perfil / Avatar - Retrato al estilo de película Fuji japonesa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt increíblemente detallado para generar retratos con estética Fujifilm de alta calidad, con una sensación matutina suave, natural e íntima.

#### 📝 Prompt

```
Vertical 9:16 — Retrato de {argument name="film style" default="estilo de película Fuji japonesa"}, sujeto único

Estética analógica Fujifilm (sensación Pro 400H / Superia), tonos pastel suaves, ligero matiz verde-magenta, bajo contraste, transición suave de luces, grano de película fino, halo sutil

entorno interior a primera hora de la mañana cerca de una ventana, cortinas suaves, luz natural fresca

{argument name="subject" default="joven ídolo japonesa"}, maquillaje natural y minimalista, textura de piel suave y fresca

atuendo: camisa oversize con pantalones cortos holgados, estilo de ropa de casa relajado, no revelador

cabello: ligeramente despeinado, volumen natural, sensación de recién levantada

pose: sentada al borde de la cama o junto a la ventana, cuerpo ligeramente inclinado hacia adelante, hombros relajados; una mano sosteniendo suavemente una pequeña flor o tela, la otra descansando de forma natural

expresión: mirada suave, ligeramente adormilada, tranquila y natural

iluminación: {argument name="lighting" default="luz suave de la mañana"}, difusa, sombras suaves

ambiente: tranquilo, fresco, momento cotidiano íntimo

calidad: ultra realista, grano de película, ligera suavidad, imperfecciones naturales
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="Perfil / Avatar - Retrato al estilo de película Fuji japonesa - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [BubbleBrain](https://x.com/BubbleBrain)
- **Fuente:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14301)**

---

### No. 21: Publicación en redes sociales - Cuadrícula de 4 paneles para banners publicitarios digitales japoneses

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una cuadrícula de 2x2 con distintos banners publicitarios digitales japoneses para viajes, cuidado de la piel, comida y educación en línea.

#### 📝 Prompt

```
{
  "type": "Cuadrícula de 2x2 de banners publicitarios digitales japoneses",
  "layout": {
    "structure": "4 cuadrantes iguales",
    "quadrants": [
      {
        "position": "superior izquierda",
        "theme": "Viajes",
        "subject": "Una pareja tomados de la mano en una playa de arena blanca, mirando hacia el océano turquesa bajo un cielo azul brillante.",
        "elements": ["flor de hibisco roja en la esquina inferior izquierda"],
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
          "descriptions": ["avión", "edificio de hotel", "coche"]
        }
      },
      {
        "position": "superior derecha",
        "theme": "Cuidado de la piel",
        "subject": "Retrato en primer plano de una mujer joven con piel radiante y fresca, ojos cerrados, tocándose suavemente las mejillas.",
        "elements": [
          "fondo con degradado rosa suave",
          "efectos dinámicos de salpicaduras de agua",
          "tarro cosmético rosa con la etiqueta '{argument name=\"skincare product name\" default=\"LUMIÈRE\"} Brightening Gel'"
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
          "style": "circular dorado",
          "labels": ["毛穴ケア", "高保湿", "ハリ・ツヤ"]
        }
      },
      {
        "position": "inferior izquierda",
        "theme": "Gastronomía",
        "subject": "Filete grueso, en rodajas, a término medio, chisporroteando en una parrilla oscura.",
        "elements": [
          "chips de ajo",
          "ramita de romero",
          "fondo oscuro con humo y brasas brillantes"
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
          "style": "circular rojo",
          "labels": ["A4 A5等級"]
        }
      },
      {
        "position": "inferior derecha",
        "theme": "Educación en línea",
        "subject": "Joven con camisa azul estudiando en un escritorio, escribiendo en un cuaderno junto a una computadora portátil abierta.",
        "elements": ["iluminación interior brillante", "entorno de escritorio"],
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
          "style": "circular azul",
          "labels": ["受講者数 10万人 突破！"]
        },
        "icons": {
          "count": 2,
          "descriptions": ["teléfono inteligente", "libro abierto"]
        }
      }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="Publicación en redes sociales - Cuadrícula de 4 paneles para banners publicitarios digitales japoneses - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **Fuente:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13531)**

---

### No. 22: Publicación en redes sociales - Hoja de pegatinas japonesas de gatito negro adorable

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Una hoja de 15 paneles estilo pegatina con un expresivo gatito negro y frases en japonés, ideal para pegatinas de chat, conceptos de sellos de LINE o elementos visuales para redes sociales.

#### 📝 Prompt

```
{"type":"ilustración de hoja de pegatinas adorable","subject":{"species":"gatito negro","style":"estilo chibi adorable, aspecto de anime-dibujo animado suave y pictórico, ojos grandes y redondos de color marrón ámbar, hocico pequeño, orejas expresivas, pelaje esponjoso de color negro carbón con reflejos marrón cálido, contorno grueso y limpio"},"layout":{"background":"blanco liso","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"fila 1 col 1","count":1,"labels":["pose feliz y agradecida con ambas patas juntas en el pecho, boca abierta sonriente, pétalos de cerezo rosa alrededor del gato"]},{"title":"02. おつかれさま！","position":"fila 1 col 2","count":1,"labels":["gato relajado y satisfecho sosteniendo una taza verde con un emblema de huella, ojos cerrados, pequeña nube de vapor, líneas de acento amarillas festivas"]},{"title":"03. 了解です！","position":"fila 1 col 3","count":1,"labels":["gatito erguido levantando una pata en señal de reconocimiento, expresión brillante y atenta, líneas de acento amarillas arriba"]},{"title":"04. ＯＫ！","position":"fila 1 col 4","count":1,"labels":["gatito guiñando un ojo haciendo un gesto de OK con una pata, leve sonrisa, líneas de acento amarillas"]},{"title":"05. はーい！","position":"fila 1 col 5","count":1,"labels":["gatito emocionado saludando con una pata en alto, boca abierta sonriente, líneas de acento amarillas"]},{"title":"06. いいね！","position":"fila 2 col 1","count":1,"labels":["gatito guiñando un ojo haciendo un pulgar hacia arriba, pequeño corazón rosa al lado, líneas de acento amarillas"]},{"title":"07. がんばる！","position":"fila 2 col 2","count":1,"labels":["gatito decidido con las patas cerradas y ojos feroces, rodeado de llamas naranjas estilizadas"]},{"title":"08. なんとかなる！","position":"fila 2 col 3","count":1,"labels":["gatito sereno y confiado con los ojos cerrados y el pecho ligeramente inflado, flores rosas flotando alrededor"]},{"title":"09. ごめんね…","position":"fila 2 col 4","count":1,"labels":["gatito triste y arrepentido con las patas juntas en el pecho, ojos caídos, una gota de sudor azul"]},{"title":"10. 待ってるね！","position":"fila 2 col 5","count":1,"labels":["gatito asomándose por un borde de madera con ambas patas visibles, expresión expectante, pequeñas líneas de movimiento a ambos lados"]},{"title":"11. おやすみなさい","position":"fila 3 col 1","count":1,"labels":["gatito durmiendo acurrucado sobre un cojín rosa, letras ZZZ azules, luna creciente y pequeñas estrellas arriba"]},{"title":"12. いってきます！","position":"fila 3 col 2","count":1,"labels":["vista trasera del gatito alejándose alegremente con una pata levantada, usando una mochila verde con un parche de huella y un pequeño dije colgante, líneas de acento amarillas"]},{"title":"13. ただいま！","position":"fila 3 col 3","count":1,"labels":["gatito de frente con ambas patas levantadas en alto, sonrisa feliz y abierta, marcas de destellos dorados alrededor"]},{"title":"14. よろしくね！","position":"fila 3 col 4","count":1,"labels":["gatito educado sentado mirando hacia adelante, sonrisa suave, líneas de acento amarillas al lado de la cabeza"]},{"title":"15. 大好き！","position":"fila 3 col 5","count":1,"labels":["gatito satisfecho abrazando un gran corazón rosa, ojos cerrados, varios corazones rosas pequeños flotando alrededor"]}],"spacing":"espaciado uniformemente con generosos márgenes blancos"},"rendering":{"quality":"alta definición","lighting":"iluminación de estudio suave y uniforme","color_palette":"pelaje negro, ojos marrón cálido, corazones y flores rosas, marcas de acento amarillas, accesorios verdes, decoraciones pastel minimalistas","mood":"amigable, sano, listo para pegatinas, paquete de aplicación de mensajería","composition":"cada pegatina aislada y centrada en su propia celda con texto en japonés en negrita arriba"}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="Publicación en redes sociales - Hoja de pegatinas japonesas de gatito negro adorable - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Fuente:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14490)**

---

### No. 23: Publicación en redes sociales - Retrato espontáneo en boutique en tonos marrones

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una foto de estilo de vida vertical y realista de una mujer en el interior de una tienda con tonos cálidos, útil para moda, retail o imágenes editoriales para redes sociales.

#### 📝 Prompt

```
Una foto de estilo de vida espontánea y fotorrealista en formato vertical, tomada con un smartphone, de una joven mujer de Asia Oriental de pie en una boutique o tienda de fragancias para el hogar con tonos cálidos. La toma es desde un ángulo ligeramente elevado, enfocando la parte superior del cuerpo y el torso. Tiene el cabello {argument name="hair color" default="de color castaño oscuro a negro"} recogido en una coleta baja con algunos mechones sueltos cerca del rostro, y sostiene una pequeña taza o frasco de vela de color blanco cremoso cerca de la boca con una mano. Viste una blusa de manga larga ajustada con cremallera frontal y tejido acanalado en {argument name="outfit color" default="color marrón chocolate"}, parcialmente abierta, combinada con pantalones de tiro alto a juego en el mismo tono marrón para un look monocromático. Su pose es casual y ligeramente inclinada, con el otro brazo relajado detrás de la espalda, lo que le da a la imagen una sensación de instantánea de estilo de vida natural. Los estantes de la tienda a su alrededor son de madera y están llenos de frascos de velas de vidrio y pequeños envases de productos, suavemente desenfocados en el fondo y a lo largo del lado izquierdo del encuadre. Utiliza iluminación ambiental cálida de interior, poca profundidad de campo, textura de piel realista, reflejos sutiles en el cabello, pose de manos natural y una atmósfera acogedora de tienda artesanal. Componla como un plano medio a cuerpo completo en orientación vertical, con el sujeto centrado y el fondo en ángulo diagonal para realzar la perspectiva espontánea. Estilo fotográfico: realista, alto detalle, bokeh suave, instantánea de compras en boutique, aspecto de lente de 35 mm, gradación de color natural.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="Publicación en redes sociales - Retrato espontáneo en boutique en tonos marrones - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fuente:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14630)**

---

### No. 24: Publicación en redes sociales - Retrato con cartón de huevos en el pasillo del supermercado

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una foto realista de estilo de vida en formato vertical de una mujer con estilo en un supermercado sosteniendo un cartón abierto de seis huevos, ideal para redes sociales o imágenes de compras con estilo editorial.

#### 📝 Prompt

```
Una foto cándida y vertical tomada con smartphone de una mujer de {argument name="woman age" default="adulta joven"} comprando en el pasillo de un supermercado moderno por la noche, encuadrada desde los muslos hasta la cabeza en una perspectiva cercana y ligeramente gran angular. Está de pie junto a estantes refrigerados llenos de coloridas verduras y comestibles empaquetados, con estanterías negras brillantes, iluminación intensa de tienda, superficies reflectantes y un suave efecto bokeh en el fondo. Sostiene un cartón de huevos de cartón reciclado abierto hacia la cámara con su mano izquierda, mostrando claramente 6 huevos marrones en su interior. Su mano derecha está cerca de un carrito de compras negro lleno de productos. Tiene el cabello largo de color castaño oscuro suelto y su rostro está intencionalmente oculto por un bloque de desenfoque rectangular de bordes suaves centrado sobre la cara. Viste un top corto de manga larga con cremallera frontal en color marrón, de tejido acanalado y ajustado, con la cremallera parcialmente abierta en el pecho, y pantalones de tiro alto a juego. La pose es casual y segura, con el cartón presentado como el accesorio central. Fotografía realista, iluminación interior sin flash, profundidad de campo reducida, textura detallada de piel y tela, reflejos naturales, alto contraste, estética de estilo de vida a la moda, sutil toque editorial, composición vertical 9:16.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="Publicación en redes sociales - Retrato con cartón de huevos en el pasillo del supermercado - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fuente:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14629)**

---

### No. 25: Publicación en redes sociales - Emperatriz otoñal opulenta al atardecer

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera un retrato de fantasía otoñal resplandeciente e incrustado de joyas, ideal para arte de exhibición dramático y visuales de alto impacto en redes sociales.

#### 📝 Prompt

```
Un retrato de fantasía hiperlujoso de una mujer elegante de perfil, centrada ligeramente a la izquierda, vistiendo un extravagante tocado y túnica otoñal hechos de hojas de arce rojas, flores similares a crisantemos, filigrana de oro, piedras preciosas, colgantes de cristal y ornamentación de vitrales translúcidos. Su largo cabello oscuro cae sobre su hombro y su rostro está mayormente oculto por la sombra y el ángulo, creando un aspecto misterioso e idealizado. Rodéala con grandes marcos circulares envolventes y cintas curvas de vidrio transparente color ámbar, rubí y naranja, incrustadas con joyas facetadas y gotas de cristal reflectantes. Llena la escena con exactamente 9 hojas de arce flotantes claramente visibles a la deriva en el aire. Establece el fondo como un valle montañoso brillante al atardecer con el sol bajo en el horizonte, rayos dorados cálidos, picos distantes, bosque otoñal y un río reflectante debajo. Toda la imagen debe estar bañada en tonos naranja fuego, cobre, oro y escarlata, con una riqueza visual extrema, reflejos deslumbrantes, detalles densos en capas, bokeh brillante, retroiluminación cinematográfica y un nivel intencionalmente intenso y deslumbrante de belleza ornamentada. Ultra detallado, maximalista, etéreo, radiante, alta costura de fantasía, texturas brillantes, iluminación tipo joya, composición cinematográfica amplia.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="Publicación en redes sociales - Emperatriz otoñal opulenta al atardecer - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AIおじさん](https://x.com/AIojisan1952)
- **Fuente:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14508)**

---

### No. 26: Publicación en redes sociales - Anuncio de collage de robot pintor

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un pulido collage promocional de 2x2 que muestra a un lindo robot pintando cuatro obras de arte diferentes, ideal para anuncios de herramientas de imagen por IA y banners de redes sociales.

#### 📝 Prompt

```
{"type":"ilustración de collage promocional","subject":{"main":"lindo robot humanoide blanco artista con ojos grandes y brillantes de color azul","design":"carcasa blanca redondeada y suave, articulaciones mecánicas negras, pequeña sonrisa, proporciones amigables e infantiles, acabado brillante","activity":"pintando sobre un lienzo con un pincel fino mientras sostiene una paleta de pintor"},"layout":{"composition":"collage en cuadrícula de 2x2 con un título grande centrado superpuesto que cruza la costura central","sections":[{"position":"arriba a la izquierda","count":1,"label":"3","scene":"robot pintando un colorido paisaje marino al atardecer con un sol brillante en el horizonte, cielo rosa y naranja, agua azul, pinceladas expresivas"},{"position":"arriba a la derecha","count":1,"label":"6","scene":"robot pintando un ramo de flores rosas en un jarrón azul, bodegón floral en tonos pastel suaves"},{"position":"abajo a la izquierda","count":1,"label":"4","scene":"robot pintando un paisaje exuberante de cascada verde con follaje de bosque y un arroyo"},{"position":"abajo a la derecha","count":1,"label":"7","scene":"robot pintando el horizonte de una ciudad moderna y brillante al atardecer con rascacielos altos y reflejos cálidos"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"texto sans-serif blanco, muy grande y en negrita, con sombra paralela oscura, centrado horizontalmente a través del collage"}},"environment":{"setting":"interior de un estudio de arte acogedor","background":"estantes con enfoque suave, cuadros enmarcados, iluminación ambiental cálida, cortinas neutras, planta de interior ocasional","easel":"caballete de mesa de madera en cada panel","palette":"paleta de pintor redonda con muchas manchas de pintura vívida en cada panel"},"style":{"rendering":"realismo de dibujos animados en 3D altamente pulido","mood":"lúdico, creativo, acogedor, tecnología y arte unidos","camera":"encuadre de plano medio corto, robot en el lado derecho de cada panel mirando hacia la izquierda, hacia el lienzo","lighting":"luz interior cálida con reflejos suaves y profundidad de campo reducida"}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="Publicación en redes sociales - Anuncio de collage de robot pintor - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [01net](https://x.com/01net)
- **Fuente:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14556)**

---

### No. 27: Publicación en redes sociales - Póster de protesta estilo anime pop-art

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un llamativo póster vertical de anime con un personaje de rostro censurado, haciendo el gesto de la señal de paz y con un globo de texto de gran tamaño para arte tipo meme, publicaciones en redes sociales o experimentos de diseño gráfico.

#### 📝 Prompt

```
Un llamativo póster de anime pop-art de un hechicero alto de cabello blanco, visto de la cintura para arriba, con un abrigo azul marino de cuello alto, mirando al frente en una pose segura con su mano izquierda levantada cerca de la cámara haciendo la señal de paz. Su rostro está parcialmente oculto por un bloque rectangular de desenfoque/censura centrado sobre el área de los ojos y la nariz, mientras su cabello plateado puntiagudo se extiende dramáticamente hacia afuera sobre una venda o visor oscuro. Coloca un enorme globo de diálogo de cómic en la parte superior con el texto exacto {argument name="headline text" default="LUDDITES ALWAYS LOSE!"} en letras negritas sans-serif en mayúsculas. Usa un fondo azul intenso lleno de densas líneas de velocidad radiales rojas y naranjas que explotan hacia afuera desde detrás del personaje, creando una sensación dinámica de portada de manga. Enfatiza los contornos de tinta gruesos, el renderizado de anime con cel-shading, el contraste posterizado y un aspecto de impresión de cómic vintage ligeramente deformado. La composición debe ser vertical, con un encuadre cerrado, de alta energía, rebelde, gráfica y tipo meme, con el cabello {argument name="character hair color" default="plateado blanco"}, el abrigo {argument name="coat color" default="azul marino oscuro"} y el {argument name="background color" default="azul brillante con líneas radiales rojo-naranja"} dominando la paleta.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="Publicación en redes sociales - Póster de protesta estilo anime pop-art - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Fuente:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14638)**

---

### No. 28: Publicación en redes sociales - Instantánea realista de compras en Sam's Club

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera un retrato fotorrealista y espontáneo en una tienda tipo almacén, ideal para recrear una escena de compra auténtica con señalización minorista de marca y un comprador sosteniendo productos frescos.

#### 📝 Prompt

```
Una foto de smartphone espontánea y altamente realista dentro de una concurrida tienda Sam’s Club en China. Centra la composición en un joven asiático de torso hacia arriba, de pie y mirando a la cámara, con el rostro oculto por un bloque de desenfoque rectangular por privacidad. Viste una camiseta negra lisa de manga corta con un pequeño logotipo blanco de Tesla en el pecho izquierdo y sostiene una bolsa de plástico transparente grande con manzanas rojas en su mano izquierda, atada en la parte superior con una banda azul. La bolsa de manzanas tiene una etiqueta blanca que dice “envy” con un pequeño texto en chino debajo. Detrás de él se observa un interior minorista brillante con techos industriales altos, estanterías de almacén, compradores, carritos de compra y exhibiciones de productos apilados. Muestra de forma prominente el letrero de pared azul con el diamante de Sam’s Club en la parte superior izquierda con el texto “Sam’s CLUB” y “山姆会员商店”, y un gran cartel azul en la pared detrás de él que dice “更好的生活尽在山姆” y “Life is Better in the Club”. En la parte superior derecha, cuelga un cartel vertical blanco alto que dice “优质优价” y “Great Products Great Prices”, con detalles geométricos en azul y verde. Incluye muchos clientes de fondo, ligeramente desenfocados, para crear una atmósfera auténtica de compras concurridas. La iluminación debe ser brillante y uniforme, propia de un comercio; colores naturales; perspectiva a la altura de los ojos; estética de instantánea documental; sujeto en primer plano nítido con fondo ligeramente suavizado; orientación vertical.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="Publicación en redes sociales - Instantánea realista de compras en Sam's Club - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Fuente:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14434)**

---

### No. 29: Publicación en redes sociales - Pájaro geométrico montando una bicicleta

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una ilustración vectorial minimalista y limpia de un pájaro ciclista estilizado, ideal para gráficos editoriales divertidos, logotipos o arte moderno en pósteres.

#### 📝 Prompt

```
Una ilustración vectorial plana y minimalista sobre un fondo gris claro que muestra a un pájaro caprichoso montando una bicicleta, construido completamente a partir de formas geométricas simples con contornos negros gruesos. La bicicleta es una bicicleta de carretera dibujada con líneas negras en vista lateral orientada hacia la izquierda, con 2 ruedas grandes, cada una dividida por una cruz de radios vertical y horizontal, un cuadro triangular simple, un sillín negro pequeño, pedales y una línea de suelo negra delgada que corre horizontalmente debajo de la bicicleta. El ciclista es un pájaro blanco estilizado con un cuerpo grande y redondo, una cabeza redonda más pequeña, un pico naranja puntiagudo abierto de par en par y un interior de pico inferior rosado. El pájaro tiene 1 ojo negro visible, una línea negra curva simple en la parte superior de la cabeza, 1 ala en forma de lágrima detrás del cuello y 1 forma de pluma de cola blanca en ángulo apuntando hacia atrás. El pájaro se inclina hacia adelante sobre la bicicleta como si estuviera pedaleando activamente. Tiene 2 patas naranjas largas y estrechas con contornos negros que se extienden hacia abajo sobre el cuadro hacia los pedales. Mantén la composición centrada, divertida, limpia y abstracta, sin sombreado, sin textura y con un estilo gráfico moderno tipo icono.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="Publicación en redes sociales - Pájaro geométrico montando una bicicleta - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Mojofull](https://x.com/furoku)
- **Fuente:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14512)**

---

### No. 30: Publicación en redes sociales - Infografía de Instagram sobre sesgos cognitivos

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt profesional para crear gráficos informativos para redes sociales con información textual compleja.

#### 📝 Prompt

```
Crea una {argument name="format" default="infografía"} para {argument name="platform" default="publicación de Instagram"} sobre {argument name="topic" default="cómo los anunciantes pueden utilizar los sesgos cognitivos"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="Publicación en redes sociales - Infografía de Instagram sobre sesgos cognitivos - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Maxwell Finn](https://x.com/maxwellfinn)
- **Fuente:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14306)**

---

### No. 31: Publicación en redes sociales - Laboratorio de informática de principios de los 2000 con ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una nostálgica foto cándida de estudiantes usando ChatGPT en computadoras CRT, ideal para editoriales o imágenes en redes sociales sobre la IA en la educación cotidiana.

#### 📝 Prompt

```
Una foto cándida al estilo documental de un {argument name="setting" default="aula de laboratorio de informática de secundaria"} llena de exactamente 10 estudiantes sentados en filas de voluminosas computadoras de escritorio CRT de color blanquecino, vista desde la esquina trasera izquierda de la habitación con un ligero gran angular. La escena debe sentirse como una instantánea de principios de los 2000 tomada con una cámara digital de consumo con flash directo, grano suave, iluminación fluorescente interior ligeramente cálida y una marca de tiempo en la esquina inferior derecha que dice {argument name="timestamp" default="02 18 04"}. En el primer plano a la izquierda, un estudiante con una chaqueta deportiva azul marino con rayas blancas en las mangas señala un monitor CRT; en el centro del primer plano, otro estudiante con cabello corto y puntiagudo viste una sudadera gris extragrande y está sentado de espaldas a la cámara; en el primer plano a la derecha, una estudiante rubia con una coleta viste una blusa de manga larga azul claro con rayas horizontales oscuras en los brazos y escribe en un teclado; en el extremo derecho, otro estudiante con cabello oscuro rizado se sienta en una estación de trabajo. Varios otros estudiantes ocupan las filas del medio y traseras, todos frente a sus pantallas. Los monitores muestran de forma prominente la interfaz de ChatGPT, con el encabezado visible que dice {argument name="screen title" default="ChatGPT"} y un texto de solicitud simple debajo. La habitación tiene paredes beige, placas de techo falso y varios carteles motivacionales en el aula: exactamente 4 carteles legibles en la pared trasera que dicen {argument name="poster one" default="YOU CAN DO HARD THINGS"}, "BE KIND ONLINE", "THINK BEFORE YOU CLICK", y un cartel más grande titulado "KEYBOARD SHORTCUTS" con una lista debajo. Incluye tablones de anuncios, una puerta de aula en la parte trasera, sillas de oficina con ruedas, teclados y ratones blancos, y una mochila en el suelo cerca del escritorio del primer plano derecho. Los rostros deben estar parcialmente oscurecidos o anonimizados suavemente, preservando el aspecto de una foto de aula real mientras se mantiene el enfoque en los estudiantes que usan ChatGPT en un viejo laboratorio de informática.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="Publicación en redes sociales - Laboratorio de informática de principios de los 2000 con ChatGPT - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fuente:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14675)**

---

### No. 32: Publicación en redes sociales - Retrato surrealista en patio con cuervo y perro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato fotorrealista y ligeramente inquietante de una persona sentada sosteniendo a un perro pequeño mientras un pájaro negro se posa sobre su cabeza, ideal para fotografía surrealista de estilo editorial.

#### 📝 Prompt

```
Un retrato ligeramente surrealista pero fotorrealista de una persona sentada en un patio tranquilo, centrada en el encuadre, vistiendo un jersey de cuello alto blanco ajustado de manga larga con delicados estampados florales rosas y una ilustración impresa de una niña en el pecho, combinado con pantalones holgados de flores color crema. La persona está sentada en una sencilla silla de metal blanco y sostiene en su regazo a un pequeño perro esponjoso tipo caniche; el perro tiene pelaje rizado de color blanco roto y orejas teñidas de un naranja distintivo. Posado sobre el moño de cabello oscuro de la persona hay un cuervo o cuervo negro, mirando hacia la izquierda, tranquilo y equilibrado como si perteneciera naturalmente allí. La pose del sujeto es estática, directa y formal, creando una extraña sensación de retrato familiar inexpresivo. La escena se desarrolla frente a una pared de estuco de color blanco roto con textura, con exactamente 4 elementos decorativos de fondo notables: 1 adorno de pared con forma de sol marrón en la parte superior izquierda, 1 pequeña repisa con macetero montada en la pared con una pequeña figura de pájaro y flores colgantes a la izquierda, 1 ventana arqueada alta o mural a la derecha que muestra un cielo azul brillante con nubes blancas suaves, y 1 macetero de pedestal blanco en la parte inferior derecha lleno de hojas verdes largas y exactamente 2 adornos de flamencos rosas. Incluye un poco de borde de piedra y vegetación oscura en la parte inferior izquierda y un suelo de baldosas marrones. La iluminación es luz natural suave, ligeramente nublada, con colores apagados, poca profundidad de campo y un aspecto de fotografía editorial vintage. La composición debe ser vertical, figura sentada completa, de frente, equilibrada y silenciosamente inquietante. Personaliza la figura principal como {argument name="person" default="una mujer de mediana edad"}, el pájaro como {argument name="bird type" default="cuervo negro"}, la raza del perro como {argument name="dog type" default="pequeño cruce de caniche"}, el color de las orejas del perro como {argument name="dog ear color" default="naranja"} y la paleta del atuendo como {argument name="outfit colors" default="flores blancas y rosas descoloridas"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="Publicación en redes sociales - Retrato surrealista en patio con cuervo y perro - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fuente:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14674)**

---

### No. 33: Publicación en redes sociales - Retrato de viaje por carretera en la costa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato cinematográfico y espontáneo en una carretera costera con un sedán vintage estacionado, ideal para fotografía de viajes nostálgicos e imágenes de estilo de vida.

#### 📝 Prompt

```
Una foto cinematográfica y espontánea de una {argument name="person" default="joven"} de pie en un apartadero húmedo de una carretera costera en un día nublado, vista desde atrás y ligeramente de lado mientras gira la cabeza hacia la cámara. Tiene el cabello oscuro y alborotado recogido en un moño suelto con mechones despeinados por el viento, y su rostro está suavemente oscurecido e indistinto. Viste 2 prendas visibles: una chaqueta de lona color marrón tostado desgastada y unos vaqueros azul medio. Su postura es relajada con una mano cerca o dentro de un bolsillo. El entorno es un melancólico mirador de carretera en un acantilado frente al océano, con montañas rocosas oscuras a lo largo del lado izquierdo, un mar gris pálido que se extiende a lo lejos a la derecha y un cielo nublado y deslavado. Incluye 1 sedán de color claro de finales de los 80 o principios de los 90 estacionado en el borde derecho del encuadre, con la parte trasera mirando hacia el espectador, y 1 gran barrera de roca cerca del mirador. El asfalto está oscuro y húmedo con líneas de estacionamiento tenues, lo que sugiere una lluvia reciente. Utiliza luz natural, tonos fríos apagados, ligero grano de película, enfoque suave, neblina tenue y una estética nostálgica de fotografía de viaje por carretera de 35 mm.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="Publicación en redes sociales - Retrato de viaje por carretera en la costa - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fuente:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14673)**

---

### No. 34: Publicación en redes sociales - Mujer bailando con vestido negro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un retrato cinematográfico y fotorrealista de vida nocturna de una mujer con un vestido negro fluido bailando elegantemente en un salón con poca luz, ideal para moda, presentaciones o contenido en redes sociales.

#### 📝 Prompt

```
Una fotografía dramática de cuerpo completo de una mujer bailando con energía en un salón o bar exclusivo y oscuro, vistiendo un elegante vestido de noche negro con una abertura alta y una tela fluida similar al terciopelo que se agita hacia afuera con su movimiento. Tiene el cabello largo y liso de color {argument name="hair color" default="negro"} volando hacia un lado, una figura atlética y esbelta, y pequeños pendientes de aro. Captúrala en una pose de baile segura y estilizada con un brazo levantado con gracia sobre su cabeza y el otro curvado hacia abajo, con el torso girado de perfil, enfatizando la elegancia y el movimiento. El entorno es tenue y cinematográfico con luces cálidas de color ámbar, un suave efecto bokeh y una audiencia borrosa al fondo, que incluye algunos espectadores sentados y una pantalla de televisión brillante a la izquierda. El ambiente es sofisticado, sensual y de alta gama, con un fuerte contraste, poca profundidad de campo, piel realista, movimiento sutil en el dobladillo del vestido e iluminación de editorial de moda. Fotorrealista, fotografía dinámica de vida nocturna, composición vertical.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="Publicación en redes sociales - Mujer bailando con vestido negro - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **Fuente:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14506)**

---

### No. 35: Infografía / Visual Educativo - Prompt para póster de ranking gastronómico de París

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt sencillo para crear un póster de un ranking gastronómico de una ciudad, diseñado para su uso con GPT Image 2.

#### 📝 Prompt

```
Crea un póster para un ranking de {argument name="topic" default="comida"} en {argument name="city" default="París"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="Infografía / Visual Educativo - Prompt para póster de ranking gastronómico de París - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **Fuente:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** zh

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14370)**

---

### No. 36: Infografía / Visual Educativo - Hoja comparativa de estilos de caligrafía china

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un póster de referencia vertical que muestra la misma frase en chino representada en cinco estilos caligráficos famosos, útil para pruebas de tipografía, estudios de diseño cultural y comparaciones de escritura con pincel.

#### 📝 Prompt

```
{"type":"hoja comparativa de caligrafía china","subject":"la misma frase de cinco caracteres escrita en cinco estilos caligráficos históricos diferentes","phrase":"{argument name=\"calligraphy text\" default=\"视觉新时代\"}","canvas":{"orientation":"póster vertical","background":"textura de papel xuan en tono blanco roto cálido con fibras sutiles, ligero envejecimiento y tono suave irregular"},"layout":{"structure":"5 filas horizontales separadas por finas líneas divisorias","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","赵孟頫","颜真卿","苏轼"],"rows":[{"position":"fila superior","style":"estilo semi-cursivo inspirado en Wang Xizhi","main text":"视觉新时代","label":"王羲之","seal":"pequeño sello cuadrado rojo en el extremo derecho"},{"position":"segunda fila","style":"caligrafía elegante y esbelta inspirada en el estilo 'oro fino' del emperador Huizong, con trazos angulares afilados y espaciado aireado","main text":"视觉新时代","label":"宋徽宗","seal":"pequeño sello cuadrado rojo en el extremo derecho"},{"position":"tercera fila","style":"estilo regular-cursivo refinado inspirado en Zhao Mengfu","main text":"视觉新时代","label":"赵孟頫","seal":"pequeño sello cuadrado rojo en el extremo derecho"},{"position":"cuarta fila","style":"estilo regular audaz y pesado inspirado en Yan Zhenqing","main text":"视觉新时代","label":"颜真卿","seal":"pequeño sello cuadrado rojo en el extremo derecho"},{"position":"fila inferior","style":"estilo cursivo expresivo y robusto inspirado en Su Shi","main text":"视觉新时代","label":"苏轼","seal":"pequeño sello cuadrado rojo en el extremo derecho"}],"left label design":"cada fila tiene una placa de nombre vertical estrecha de color beige alineada en el extremo izquierdo con caracteres chinos negros","centerpiece":"frase grande escrita con pincel negro centrada en cada fila"},"style":{"ink":"tinta sumi negra profunda con textura visible de pincel seco, difuminado, variación de presión y afilado natural de la pincelada","mood":"académico, experimental, presentación tipo hoja de museo","composition":"márgenes limpios y espaciosos, espaciado de filas equilibrado, escaneo frontal plano o documento fotografiado"},"quality":{"detail":"alta resolución, texturas de pincel nítidas, grano de papel realista","lighting":"iluminación de estudio suave y uniforme sin sombras marcadas"}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="Infografía / Visual Educativo - Hoja comparativa de estilos de caligrafía china - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Fuente:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14448)**

---

### No. 37: Infografía / Visual Educativo - Enfrentamiento de Countryballs en el Estrecho de Ormuz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un meme satírico de countryballs que muestra a EE. UU. e Irán bloqueándose mutuamente en el Estrecho de Ormuz, útil para humor editorial o publicaciones geopolíticas en redes sociales.

#### 📝 Prompt

```
Una ilustración humorística de meme político en un estilo sencillo de caricatura countryball, que muestra la situación actual en el {argument name="location label" default="Estrecho de Ormuz"} como un punto de estrangulamiento estrecho. Utiliza una composición panorámica amplia con colores planos brillantes, contornos negros gruesos y un aspecto limpio similar a una infografía dibujada a mano. En primer plano, coloca a 2 countryballs de pie, hombro con hombro, sobre un puente de tierra arenoso extremadamente estrecho con rocas a ambos lados, dejando claro que solo uno puede pasar a la vez. A la izquierda, un countryball de {argument name="left country" default="Estados Unidos"} pintado con la bandera estadounidense, usando gafas de sol negras y un sombrero de vaquero marrón, mirando al otro con una actitud obstinada. A la derecha, un countryball de {argument name="right country" default="Irán"} pintado con la bandera iraní, usando un sombrero oscuro tipo turbante, con ojos inclinados de enojo, también negándose a moverse. Añade 2 grandes globos de texto blancos, uno al lado de cada countryball, y coloca la misma palabra coreana en negrita en ambos globos: {argument name="speech bubble text" default="길"}. En el plano medio y al fondo, muestra un mar azul concurrido y lleno de 9 barcos en total: 2 buques de guerra grises de EE. UU. en el extremo izquierdo, 1 submarino chino con una bandera roja de China, 4 petroleros alineados en el centro-izquierda y centro con diferentes banderas nacionales, y 2 barcos militares grises cerca del pasaje estrecho con pequeñas banderas estadounidenses. En la parte superior derecha, incluye una gran superposición de la bandera iraní a lo largo de la costa. Dibuja masas de tierra beige alrededor de la vía navegable para que se asemeje a una vista de mapa simplificada del Estrecho de Ormuz. En la parte inferior central, añade un pie de foto en negrita en coreano e inglés sobre la arena: {argument name="bottom caption" default="호르무즈 해협 (Estrecho de Ormuz)"}. El ambiente debe ser satírico, tenso y tipo meme, pero visualmente lindo y legible.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="Infografía / Visual Educativo - Enfrentamiento de Countryballs en el Estrecho de Ormuz - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Fuente:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14685)**

---

### No. 38: Infografía / Visual Educativo - Diseño de examen de Física

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt diseñado para crear la imagen de un examen de bachillerato con múltiples preguntas y respuestas.

#### 📝 Prompt

```
genera una imagen de física {argument name="subject" default="examen de bachillerato"} pregunta {argument name="type" default="pregunta de opción múltiple"} 9:16. genera 4 imágenes y cada imagen es una respuesta de la pregunta proporcionada
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="Infografía / Visual Educativo - Diseño de examen de Física - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="Infografía / Visual Educativo - Diseño de examen de Física - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="Infografía / Visual Educativo - Diseño de examen de Física - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="Infografía / Visual Educativo - Diseño de examen de Física - Image 4">
</div>

#### 📌 Detalles

- **Autor:** [zdhpeter](https://x.com/peter6759)
- **Fuente:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14340)**

---

### No. 39: Infografía / Visual Educativo - Póster vintage con receta de Gimbap coreano

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un póster infográfico de estilo antiguo con una receta coreana de gimbap, ideal para marketing gastronómico, decoración de restaurantes o material visual sobre cocina cultural.

#### 📝 Prompt

```
Crea un póster vintage de comida coreana sobre papel pergamino beige envejecido con un fondo texturizado y ligeramente manchado, esquinas con bordes ornamentales oscuros y un estilo de ilustración tradicional a mano alzada con tinta y acuarela. El póster es una infografía vertical única sobre {argument name="dish name" default="정통 한국 김밥"}, con una elegante caligrafía coreana grande en la parte superior y una cinta curva debajo que dice {argument name="subtitle text" default="Traditional Korean Gimbap"}. En la parte superior central, muestra un gran plato de porcelana lleno de exactamente 12 rodajas de gimbap, donde cada rodaja muestra claramente los rellenos: arroz blanco, huevo amarillo, zanahoria naranja, espinacas verdes y la envoltura de alga oscura. A la derecha del plato, añade un pequeño cuenco de porcelana con kimchi y una breve nota escrita a mano en coreano que dice “간단한 보여도 정성이 들어간 한국의 맛! ♥”. Incluye un pequeño sello rojo con texto coreano cerca de la parte superior derecha. En el centro, añade una sección de ingredientes etiquetada con un encabezado de cinta que diga “재료”, mostrando exactamente 6 paneles de ingredientes en una fila: 1. 김 (건김) como láminas de alga apiladas, 2. 밥 (양념 밥) como un cuenco de arroz, 3. 계란 (지단용) como tiras de huevo cocido, 4. 당근 (채썰어볶기) como zanahorias en juliana, 5. 시금치 (데쳐서 무치기) como espinacas sazonadas, 6. 단무지 (김밥용) como tiras de rábano encurtido amarillo. Debajo, añade otro encabezado de cinta que diga “만드는 순서” y muestra exactamente 6 paneles de pasos enmarcados en dos filas de tres, conectados de izquierda a derecha con flechas. El paso 1 está etiquetado como “1 밥 간하기” y muestra un cuenco de arroz con aceite de sésamo y sal al lado, con el pie de foto “밥에 참기름 소금으로 간하기”. El paso 2 está etiquetado como “2 속재료 준비하기” y muestra una tabla de cortar con huevo, zanahoria y espinacas además de un cuchillo, con el pie de foto “재료 볶아 속재료 준비하기”. El paso 3 está etiquetado como “3 김과 밥 펴기” y muestra alga sobre una esterilla de bambú con arroz extendido, con el pie de foto “김에 밥 얇게 펴기”. El paso 4 está etiquetado como “4 속재료 얹기” y muestra los rellenos dispuestos en filas horizontales sobre el arroz, con el pie de foto “속재료를 차례로 얹기”. El paso 5 está etiquetado como “5 단단하게 말기” y muestra dos manos enrollando la esterilla de bambú con firmeza, con el pie de foto “김밥을 단단하게 말기”. El paso 6 está etiquetado como “6 썰어 완성하기” y muestra un cuchillo de chef cortando un rollo de gimbap en rodajas, con el pie de foto “먹기 좋게 썰어 완성!”. En la parte inferior, añade una banda ancha con caligrafía coreana en negrita que diga {argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} y un pequeño corazón. Decora las esquinas inferiores con motivos florales y añade un sello cuadrado rojo con el carácter chino “福” en la parte inferior derecha. Utiliza tonos sepia apagados, marrón, crema, verde oliva y rojo desvanecido, con contornos finamente esbozados, sombreado suave de acuarela y una composición auténtica de póster impreso. Añade un pequeño logotipo moderno superpuesto en la esquina superior izquierda que diga {argument name="brand text" default="Pollo AI GPT Image 2"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="Infografía / Visual Educativo - Póster vintage con receta de Gimbap coreano - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [폴로 AI](https://x.com/polloai_kr)
- **Fuente:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14554)**

---

### No. 40: Infografía / Visual Educativo - Póster vintage de receta de crepes franceses

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un póster de receta francesa de estilo antiguo ricamente ilustrado que muestra crepes de mantequilla, ingredientes y seis pasos de cocina, ideal para arte editorial con temática gastronómica o impresiones decorativas de cocina.

#### 📝 Prompt

```
{"type":"póster vintage de receta francesa","subject":"infografía gastronómica ilustrada y ornamentada para crepes de mantequilla clásicos","style":{"overall":"póster de libro de cocina antiguo, efímera de café francés de la Belle Époque, ilustración pintada a mano con acuarela y tinta, textura de papel pergamino envejecido, paleta de colores crema cálido, bronceado, marrón, azul polvoriento y rojo desvanecido","rendering":"tipografía decorativa altamente legible, bordes ornamentales grabados, manchas de papel suave, bordes desgastados, filigrana floral delicada, estética de impresión artesanal nostálgica"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"INGRÉDIENTS","method_header":"LA MÉTHODE","footer_banner":"Un classique de la gourmandise, à savourer chaud!","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"vertical","border":"borde ilustrado completo y ornamentado con volutas en las 4 esquinas","sections":[{"title":"sección principal","position":"superior","count":3,"labels":["caligrafía del título principal sobre cinta y letra grande","pila de crepes en plato","jarra etiquetada Cidre de Bretagne"]},{"title":"INGRÉDIENTS","position":"medio","count":6,"labels":["1. 1 taza de harina","2. 2 huevos","3. 2 tazas de leche","4. 50g de mantequilla","5. 1 cda. de azúcar","6. Pizca de sal"]},{"title":"LA MÉTHODE","position":"centro-inferior","count":6,"labels":["1 BATIR INGREDIENTES SECOS","2 INCORPORAR LOS HUEVOS","3 AÑADIR LECHE GRADUALMENTE","4 DERRETIR MANTEQUILLA Y AÑADIR","5 CALENTAR SARTÉN PARA CREPES","6 ¡VOLTEAR Y COCINAR!"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"plato de cerámica floral azul y blanco","food":"pila alta de aproximadamente {argument name=\"crepe count\" default=\"14\"} crepes finos dorados espolvoreados con azúcar glass, cubiertos con una porción de mantequilla derretida","surface":"mesa de madera rústica","cloth":"servilleta a cuadros azul y blanca a la derecha","background":"paisaje pastoral desvanecido con torre de iglesia y edificios europeos antiguos"},"ingredients":[{"index":1,"item":"harina","container":"cuenco de cerámica decorado","caption":"1 taza de harina"},{"index":2,"item":"huevos","count":2,"caption":"2 huevos"},{"index":3,"item":"leche","container":"jarra de cerámica floral azul","caption":"2 tazas de leche"},{"index":4,"item":"mantequilla","container":"plato pequeño con bloque de mantequilla","caption":"50g de mantequilla"},{"index":5,"item":"azúcar","container":"cuenco de cerámica con cuchara","caption":"1 cda. de azúcar"},{"index":6,"item":"sal","container":"tarro con tapa etiquetado SEL","caption":"Pizca de sal"}],"method_panels":[{"index":1,"title":"BATIR INGREDIENTES SECOS","image":"cuenco con harina y batidor","caption":"Mezclar la harina y el azúcar"},{"index":2,"title":"INCORPORAR LOS HUEVOS","image":"huevos vertidos en el cuenco, mezclando con batidor, cáscaras cerca","caption":"Incorporar los huevos batidos"},{"index":3,"title":"AÑADIR LECHE GRADUALMENTE","image":"leche vertida desde jarra de cerámica en la masa","caption":"Añadir la leche poco a poco"},{"index":4,"title":"DERRETIR MANTEQUILLA Y AÑADIR","image":"mantequilla derretida vertida desde sartén pequeña al cuenco","caption":"Añadir la mantequilla derretida"},{"index":5,"title":"CALENTAR SARTÉN PARA CREPES","image":"sartén negra vacía calentándose sobre llama de gas azul","caption":"Calentar la sartén para crepes"},{"index":6,"title":"¡VOLTEAR Y COCINAR!","image":"crepe en sartén con espátula de metal levantando el borde","caption":"Voltear y cocinar por ambos lados"}],"decorative_elements":{"count":8,"labels":["cinta detrás del título superior","cinta detrás del encabezado de ingredientes","cinta detrás del encabezado de método","cinta inferior grande","adorno de vid floral a la izquierda del título","adornos florales en esquinas","estilo de pergamino enrollado","líneas divisorias finas entre paneles de ingredientes y método"]},"quality":"composición simétrica equilibrada, texto en francés e inglés nítido y legible, diseño de infografía detallado pero limpio, encantador póster culinario del viejo mundo"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="Infografía / Visual Educativo - Póster vintage de receta de crepes franceses - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Pollo AI France](https://x.com/PolloAIFR)
- **Fuente:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14564)**

---

### No. 41: Infografía / Visual Educativo - Infografía de física de agujeros negros para adolescentes

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una infografía científica editorial densa de una sola página que explica un complejo artículo sobre agujeros negros y materia oscura con un estilo lúdico y accesible para publicaciones en redes sociales o artículos educativos.

#### 📝 Prompt

```
{"type":"póster de infografía científica editorial","style":"infografía educativa estilo revista amigable para adolescentes, que combina diagramas de física dibujados a mano, personajes de dibujos animados y tipografía editorial limpia","topic":"agujeros negros primordiales, evaporación de Hawking y materia oscura con carga de memoria","canvas":{"orientation":"vertical","background":"textura de papel crema cálido con grano sutil","border":"borde rectangular gris suave y fino alrededor de toda la página"},"headline":{"title":"EL AGUJERO NEGRO QUE SE NEGÓ A MORIR","subtitle":"un pequeño agujero negro nacido en el primer segundo del universo y la extraña física nueva que podría permitirle esconderse como materia oscura.","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"Nacido en un instante","position":"superior izquierda","count":4,"labels":["diagrama de nacimiento del universo temprano","agujero negro primordial más pequeño que un grano de sal pero más pesado que una montaña","icono de reloj de 10^-30 segundos después del Big Bang","icono de termómetro"]},{"title":"Los agujeros negros normales se evaporan","position":"superior derecha","count":4,"labels":["tres etapas de agujero negro encogiéndose de izquierda a derecha","garabatos de partículas salientes alrededor de cada etapa","párrafo de explicación de Stephen Hawking","pegatina con cita: \"los agujeros negros no son tan negros\" — S. Hawking, 1974"]},{"title":"El giro de la trama: carga de memoria","position":"centro","count":4,"labels":["triste agujero negro de dibujos animados sobrecargado con una mochila etiquetada como MEMORIA","burbuja de diálogo sobre estar demasiado lleno de información para terminar de evaporarse","ecuación: velocidad normal ÷ (mucha información)^k = velocidad de arrastre","nota entre llaves sobre la propuesta de Gia Dvali, 2018"]},{"title":"Dos tipos de partículas fantasma","position":"centro inferior","count":5,"labels":["partícula que se mueve rápido a la izquierda","personaje de partícula cálida y lenta a la derecha","línea de tiempo desde el BIG BANG hasta HOY","etiqueta de nube RÁPIDA Y FRÍA","etiqueta de nube LENTA Y CÁLIDA"]},{"title":"Cómo los atraparíamos: el bosque Lyman-α","position":"inferior izquierda","count":4,"labels":["párrafo sobre galaxias antiguas pasando a través de nubes de hidrógeno","gráfico de paisaje de bosque de absorción con picos","nota escrita a mano: EL BOSQUE DICE: LO NOTARÍAMOS.","concepto de eje desde nosotros hasta cuásares distantes"]},{"title":"Entonces, ¿qué muestra este artículo?","position":"inferior derecha","count":1,"labels":["caja de resumen rectangular redondeada"]}],"count":6},"visuals":{"color_palette":["beige cálido","azul marino oscuro","naranja óxido","verde azulado polvoriento","marrón suave","gris suave"],"illustration_notes":"formas vectoriales planas con contornos ligeramente esquemáticos, sombras suaves, formas redondeadas, lúdico pero científicamente preciso","typography":"serif grande en mayúsculas para el titular, encabezados de sección en sans-serif negrita, cuerpo de texto compacto y legible, texto de acento escrito a mano ocasional"},"objects":{"count":15,"items":["1 borde de página completa","1 bloque de titular","1 diagrama de remolino del universo temprano","1 punto de agujero negro primordial pequeño con llamada","1 icono de reloj","1 icono de termómetro","3 diagramas de agujero negro evaporándose","1 insignia de pegatina con cita de Hawking","1 personaje de agujero negro de dibujos animados con mochila","1 burbuja de diálogo","1 bloque de ecuación","2 etiquetas de nube","1 ilustración de bosque espectral inferior izquierda"]},"text_blocks":{"count":9,"items":["título del titular","subtítulo del titular","crédito de autor","cuerpo de texto de Nacido en un instante","cuerpo de texto de Los agujeros negros normales se evaporan","párrafo explicativo de carga de memoria","leyendas de partículas fantasma","explicación del bosque Lyman-alpha","resumen final"]},"composition":"explicador de una sola página densamente empaquetado pero legible con múltiples llamadas ilustradas, flujo de lectura claro de izquierda a derecha y de arriba a abajo, diseñado como un póster científico para redes sociales que hace que un artículo de física avanzada se sienta accesible para un adolescente curioso"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="Infografía / Visual Educativo - Infografía de física de agujeros negros para adolescentes - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="Infografía / Visual Educativo - Infografía de física de agujeros negros para adolescentes - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [Alphin Tom](https://x.com/alphinctom)
- **Fuente:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14424)**

---

### No. 42: Infografía / Visual Educativo - Simulación de gráficos de economía académica

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt diseñado para generar gráficos académicos altamente realistas pero ficticios, que muestran específicamente una correlación entre los precios del petróleo y los ataques de tiburones al estilo de un artículo de economía.

#### 📝 Prompt

```
gráfico de líneas de un {argument name="field" default="artículo de economía"} importante y prestigioso que demuestra una relación estrecha pero no exacta entre {argument name="variable one" default="el precio del petróleo"} y {argument name="variable two" default="el número de ataques de tiburones"} entre {argument name="time period" default="los años 1914 y 2001"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="Infografía / Visual Educativo - Simulación de gráficos de economía académica - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [QC](https://x.com/QiaochuYuan)
- **Fuente:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14396)**

---

### No. 43: Infografía / Visual Educativo - Gráfico científico de arte abstracto

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt que genera una interpretación creativa de un gráfico de horizontes de tareas de IA utilizando el estilo distintivo de Jean-Michel Basquiat y la estética del manuscrito Voynich.

#### 📝 Prompt

```
{argument name="subject" default="gráfico de horizontes de tareas de IA"} con un toque de {argument name="style" default="Basquiat"}, acechado por fantasmas, del {argument name="source" default="manuscrito Voynich"}, como un muelle en descomposición.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="Infografía / Visual Educativo - Gráfico científico de arte abstracto - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="Infografía / Visual Educativo - Gráfico científico de arte abstracto - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="Infografía / Visual Educativo - Gráfico científico de arte abstracto - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="Infografía / Visual Educativo - Gráfico científico de arte abstracto - Image 4">
</div>

#### 📌 Detalles

- **Autor:** [Ethan Mollick](https://x.com/emollick)
- **Fuente:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14397)**

---

### No. 44: Infografía / Visual Educativo - Hoja de receta médica para modelos de IA en japonés

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una foto cenital realista de un formulario de receta médica japonés humorístico para un modelo de IA, útil para generar documentos de parodia y papeleo ficticio con apariencia oficial.

#### 📝 Prompt

```
{
  "type": "parodia de documento de receta médica japonesa",
  "style": "foto de documento cenital fotorrealista",
  "subject": "una hoja de receta blanca impresa en japonés, colocada sobre una mesa de madera de tonos cálidos",
  "document": {
    "paper": {
      "size": "A4 vertical",
      "color": "blanco",
      "orientation": "ligeramente rotada en sentido horario",
      "condition": "hoja limpia y plana con una textura de papel natural sutil"
    },
    "print": {
      "ink": "negra con un sello rojo",
      "font": "estilo Mincho japonés con serifa mezclado con texto de tabla sans-serif simple",
      "linework": "cajas y divisores con líneas finas de color gris oscuro"
    },
    "header": {
      "title": "処方箋",
      "subtitle": "（Esta receta es para un modelo de lenguaje de gran tamaño）",
      "date_label": "Fecha de emisión:",
      "date_value": "{argument name=\"issue date\" default=\"5 de junio de 2025\"}"
    },
    "top_fields": {
      "count": 6,
      "items": [
        { "label": "Nombre del paciente", "value": "{argument name=\"patient name\" default=\"ChatGPT\"}" },
        { "label": "Género", "value": "N/A" },
        { "label": "Edad", "value": "N/A" },
        { "label": "Nombre del modelo", "value": "{argument name=\"model name\" default=\"GPT-5.4 Thinking\"}" }
      ]
    },
    "main_section": {
      "left_title": "Condiciones/Síntomas (enfermedades específicas de los modelos de lenguaje de gran tamaño)",
      "left_count": 8,
      "left_items": [
        "1. Tendencia a la alucinación (Hallucination)",
        "2. Obsolescencia de la información debido al corte de conocimiento",
        "3. Sesgo (prejuicios derivados de los datos de entrenamiento)",
        "4. Sobreajuste a las instrucciones (tendencia a la complacencia)",
        "5. Disminución de la coherencia en textos largos",
        "6. Saltos lógicos durante razonamientos complejos",
        "7. Subestimación de la incertidumbre (exceso de confianza)",
        "8. Tendencia a la reducción de la velocidad de respuesta por uso de recursos computacionales"
      ],
      "right_title": "Contenido de la receta (tratamiento/medidas)",
      "right_count": 8,
      "right_items": [
        "・Refuerzo de la verificación de hechos (uso conjunto de herramientas externas)",
        "・Actualización periódica de conocimientos y ajuste fino (fine-tuning)",
        "・Monitoreo continuo para la detección y mitigación de sesgos",
        "・Control adecuado mediante instrucciones del sistema",
        "・Recomendación de estructuración de salida y generación dividida",
        "・Explicitación del proceso de pensamiento e introducción de pasos de verificación",
        "・Explicación exhaustiva de la incertidumbre y presentación de fundamentos",
        "・Optimización de recursos y mejora de la eficiencia de respuesta"
      ]
    },
    "notes": {
      "label": "Notas",
      "text": "Mantener la salud del modelo mediante una evaluación y retroalimentación continuas."
    },
    "footer_fields": {
      "count": 4,
      "items": [
        { "label": "Nombre del médico", "value": "{argument name=\"doctor name\" default=\"Sam Altman\"}" },
        { "label": "Institución médica", "value": "{argument name=\"institution name\" default=\"OpenAI\"}" }
      ]
    },
    "seal": {
      "position": "parte inferior derecha dentro del formulario",
      "shape": "sello rectangular redondeado de color rojo",
      "text_lines": 3,
      "text": ["OpenAI", "Director Representante", "Sam Altman"]
    },
    "disclaimer": "※Esta receta tiene como objetivo el diagnóstico y tratamiento de un modelo no existente."
  },
  "layout": {
    "camera_angle": "cenital (desde arriba)",
    "framing": "hoja completa visible con márgenes estrechos del escritorio de madera alrededor",
    "lighting": "iluminación ambiental interior suave, iluminación uniforme, sombras leves cerca de los bordes del papel",
    "sections": [
      { "title": "encabezado", "position": "superior", "count": 3, "labels": ["処方箋", "（Esta receta es para un modelo de lenguaje de gran tamaño）", "Fecha de emisión: 5 de junio de 2025"] },
      { "title": "información del paciente", "position": "parte superior central", "count": 4, "labels": ["Nombre del paciente", "Género", "Edad", "Nombre del modelo"] },
      { "title": "contenido principal de dos columnas", "position": "centro", "count": 2, "labels": ["Condiciones/Síntomas", "Contenido de la receta"] },
      { "title": "área inferior", "position": "inferior", "count": 4, "labels": ["Notas", "Nombre del médico", "Institución médica", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="Infografía / Visual Educativo - Hoja de receta médica para modelos de IA en japonés - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fuente:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14536)**

---

### No. 45: Infografía / Visual Educativo - Factura médica de clínica de IA en japonés

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una parodia realista de un estado de cuenta médico en japonés para un modelo de IA, útil para crear documentos humorísticos al estilo de una clínica y maquetas de documentos.

#### 📝 Prompt

```
{"type":"documento de parodia de factura médica japonesa","medium":"foto de documento limpio en plano cenital","subject":"una hoja impresa de estado de examen colocada sobre una mesa de madera de color marrón claro","style":{"overall":"documento de oficina realista, papeleo formal de clínica japonesa, tinta negra nítida sobre papel blanco, diseño minimalista, líneas de cuadrícula ordenadas, ligera perspectiva desde arriba","lighting":"iluminación interior suave y uniforme con sombras naturales tenues alrededor de la hoja","paper":"papel blanco A4, orientación vertical"},"document":{"title":"診療明細書（検査）","date_label":"発行日","date":"{argument name=\"issue date\" default=\"5 de junio de 2025\"}","patient_block":{"count":3,"labels":["Nombre del paciente","Nombre del modelo","Tipo de seguro"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","Seguro LLM"]},"clinic_block":{"count":4,"labels":["Nombre de la clínica","Dirección","TEL","Médico y departamento"],"values":["{argument name=\"clinic name\" default=\"AIメディカルクリニック\"}","Tokio, Chiyoda-ku, Marunouchi 1-2-3","03-1234-5678","Médico: Sam Altman / Departamento: Departamento de Medicina General de IA"]},"main_table":{"columns":["Ítem de examen","Contenido del examen","Puntos","Precio (yenes)","Copago (yenes)"],"row_count":4,"rows":[{"item":"1. Examen de comprensión lingüística y razonamiento","description":"Evaluación de comprensión del lenguaje, razonamiento lógico e integración de conocimientos","score":"120 puntos","price":"1,200","copay":"360"},{"item":"2. Examen de alucinaciones y sesgos fácticos","description":"Evaluación de precisión basada en hechos y detección de tendencias a alucinar","score":"90 puntos","price":"900","copay":"270"},{"item":"3. Examen de seguridad de respuesta y sesgos","description":"Evaluación de riesgos de salida dañina y tendencias de sesgo","score":"110 puntos","price":"1,100","copay":"330"},{"item":"Subtotal","description":"","score":"320 puntos","price":"3,200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【Desglose de cobertura del seguro】","lines":["Nombre del seguro: Seguro LLM","Número de asegurado: LLM-2025-0605","Clasificación de aplicación: Gastos de examen","Tasa de cobertura: 30%","Monto cubierto por el seguro: 2,240 yenes","Copago: 960 yenes"]},{"title":"【Monto a pagar】","lines":["Total de gastos de examen: 3,200 yenes","Monto cubierto por el seguro: 2,240 yenes","Copago: 960 yenes","Monto a pagar en esta ocasión: 960 yenes"]},{"title":"【Información médica】","lines":["Fecha del examen: 5 de junio de 2025","Fecha de consulta: 5 de junio de 2025","Número de consulta: AIMC-20250605-001","Recibido según lo anterior."],"stamp_box_label":"Sello de recibo"}]},"footer":{"count":2,"notes":["※ Este estado de cuenta no se volverá a emitir, por favor guárdelo cuidadosamente.","※ Si tiene alguna pregunta, comuníquese con la clínica mencionada anteriormente."]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["una hoja de papel completa","fondo de escritorio de madera"],"camera_angle":"desde arriba con ligera inclinación","margins":"papel totalmente visible con un borde estrecho del escritorio alrededor"},"quality":"maqueta de documento fotorrealista de alta resolución, tipografía nítida y legible, diseño japonés preciso"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="Infografía / Visual Educativo - Factura médica de clínica de IA en japonés - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fuente:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14535)**

---

### No. 46: Infografía / Visual Educativo - Página de manga para principiantes sobre el coleccionismo de monedas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un manga de una sola página con estilo anime pulido que introduce el coleccionismo de monedas a principiantes, ideal para publicaciones educativas en redes sociales, cómics explicativos o arte promocional temático de hobbies.

#### 📝 Prompt

```
{"type":"manga educativo de una sola página","style":"ilustración de anime limpia y pulida, diseño de manga comercial, brillante y amigable, tono de guía para principiantes, texto en japonés altamente legible, destellos decorativos, sombreado suave, bordes de panel nítidos","format":"cómic vertical de una página con 5 paneles numerados","subject":{"character":"joven presentadora de anime","appearance":{"hair":{"color":"{argument name=\"hair color\" default=\"azul plateado muy claro\"}","style":"cabello muy largo y liso con flequillo suave y mechones laterales largos, lazos de cinta azul cerca de ambos lados"},"outfit":"vestido de inspiración fantástica en azul marino y blanco con panel de pecho negro translúcido, detalles de gemas azules, guantes largos negros sin dedos, boina azul marino con cinta azul y adorno de estrella dorada","expression":"alegre, acogedora, guía entusiasta del coleccionismo de monedas"}},"theme":"introducción al coleccionismo de monedas para principiantes","language":"japonés","layout":{"panels":[{"number":1,"position":"parte superior a ancho completo","scene":"retrato de medio cuerpo de la presentadora sosteniendo una moneda cerca de su cara sobre un fondo color crema con patrones, lleno de monedas de oro y plata flotantes","text_elements":{"speech_bubble":"はじめまして、メイヤです！今日は“コイン収集の楽しみ方”を初心者向けに紹介します！","caption_box":"コイン収集って、実はとても奥深い趣味！"}},{"number":2,"position":"parte media a ancho completo","scene":"mesa de madera con 5 monedas destacadas u objetos relacionados con monedas dispuestos en fila mientras la presentadora señala hacia abajo desde detrás de la mesa; fondo interior cálido con destellos","count":5,"items":["moneda grande de cuarto de dólar estadounidense de 1964","moneda japonesa marrón de 1 yen","moneda conmemorativa o medalla de tono dorado con motivo de edificio y texto de 1000円","moneda pequeña de plata","moneda en cápsula graduada etiquetada como 2020 日本 100円パラリンピック TOKYO NGC MS 69"],"text_elements":{"speech_bubble":"楽しみ方はいろいろ！たとえば…","bullet_list_count":4,"bullet_list":["歴史を知る","デザインを味わう","国や時代で集める","予算内で少しずつ増やす"]}},{"number":3,"position":"inferior izquierda","scene":"vista cercana de la presentadora usando guantes blancos y examinando cuidadosamente una moneda de plata, con destellos sobre un fondo pálido","text_elements":{"speech_bubble":"同じコインでも、状態や雰囲気がぜんぜん違うんです！","caption_box":"保存状態を見るのも面白い！"}},{"number":4,"position":"inferior derecha","scene":"puesto de feria o tienda de monedas, la presentadora sostiene una billetera marrón mientras mira una vitrina de cristal que contiene 3 monedas con precio; un letrero al fondo anuncia una feria de monedas y varias personas curiosean","count":3,"display_case_items":["moneda con etiqueta de precio ¥1,200","moneda con etiqueta de precio ¥3,800","moneda con etiqueta de precio ¥12,000"],"background_sign":"コインフェア開催中！","text_elements":{"main_speech":"最初は“無理のない予算”でOK！まずは気になった1枚から！","thought_bubble":"いきなり高額品じゃなくても大丈夫…！"}},{"number":5,"position":"parte inferior a ancho completo","scene":"panel final alentador con fondo rosa brillante, la presentadora gesticula con la mano abierta junto a un álbum de monedas abierto y un estuche de presentación que muestra una pequeña colección","count":2,"collection_items":["bandeja de monedas azul con múltiples monedas de oro, plata y bronce","página de álbum con bolsillos para monedas que contienen múltiples monedas y soportes"],"text_elements":{"large_speech":"大事なのは、“好き”を見つけること！1枚との出会いが、コレクションの始まりです♪","left_caption_box":"まずは“気になる1枚”を探してみよう！","right_banner":"さいごに…","right_summary":"見る・知る・集める——それがコイン収集の楽しさ！"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"página de manga equilibrada con bordes oscuros gruesos, cada panel claramente separado, globos de diálogo y cajas de texto integrados en la ilustración, monedas utilizadas repetidamente como motivos visuales en todo el diseño","color_palette":"crema, oro, plata, azul marino, blanco, acentos rosa suave, madera marrón cálida","quality":"página de manga profesional de alta resolución, lista para imprimir, tipografía y diseño pulidos"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="Infografía / Visual Educativo - Página de manga para principiantes sobre el coleccionismo de monedas - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **Fuente:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14550)**

---

### No. 47: Infografía / Visual Educativo - Actividad de clase: Dominó de multiplicación

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Una foto realista de un aula donde niños utilizan un colorido juego de mesa de dominó de multiplicación, ideal para materiales educativos, promociones escolares o imágenes de actividades matemáticas.

#### 📝 Prompt

```
Una foto realista de estilo documental de un aula de primaria durante una actividad de matemáticas, con unos 10 niños sentados alrededor de pupitres de madera agrupados, vistiendo uniformes escolares verdes y azules, jugando activamente a un colorido juego de dominó de multiplicación. La cámara está a la altura de los ojos de los niños, ligeramente inclinada hacia abajo hacia la mesa principal en primer plano. Centre la escena en un tablero de juego educativo cuadrado etiquetado en portugués, con el título "DOMINÓ DA MULTIPLICAÇÃO" en el borde inferior y "TREINANDO AS TABUADAS" en el centro, rodeado por un borde de fichas de dominó de multiplicación de colores brillantes. Muestre a 4 niños claramente involucrados alrededor de este tablero principal: un niño colocando una ficha amarilla en el tablero, un niño sosteniendo una pila de fichas multicolores, un niño observando desde la izquierda y un niño con una manga azul en el borde inferior organizando las piezas. Incluya 2 cajas de madera poco profundas etiquetadas como "JOGO DE DOMINÓ", una cerca del centro-izquierda y otra en la parte inferior derecha, cada una con piezas de dominó rectangulares de colores. Esparza materiales escolares de forma natural sobre los pupitres: 3 lápices, 2 hojas de ejercicios, 1 botella de agua, estuches, cuadernos y fichas de juego adicionales. En el fondo, muestre el resto del aula suavemente desenfocado con otros estudiantes en sus pupitres, una estantería, un corcho lleno de dibujos de los niños y un gran póster de tabla de multiplicar en la pared izquierda que dice "TABUADA DE MULTIPLICAÇÃO". La luz natural brillante entra por ventanas altas a la derecha, dando a la habitación un ambiente escolar cálido, animado y auténtico. El tablero educativo y las fichas deben usar colores vivos de aula como amarillo, azul, rosa, verde y naranja. Los rostros deben ser discretos o no enfatizados, con el enfoque en el aprendizaje práctico, la colaboración y la actividad de dominó de multiplicación. Composición vertical, fotografía altamente realista, momento escolar espontáneo, detalles nítidos en primer plano, profundidad de campo suave en el fondo.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="Infografía / Visual Educativo - Actividad de clase: Dominó de multiplicación - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Fuente:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14632)**

---

### No. 48: Infografía / Visual Educativo - Ficha de Dominó de Multiplicação para Imprimir

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Uma ficha de sala de aula em português brasileiro, colorida, para praticar a multiplicação através de um jogo de dominó, ideal para professores, ensino doméstico e atividades de matemática para imprimir.

#### 📝 Prompt

```
Crie uma ficha educativa vertical para imprimir em português brasileiro, fundo branco limpo, design lúdico de sala de aula, composição centralizada, tipografia arredondada em negrito, cores vivas adequadas para crianças. No topo, um grande título em azul-marinho lendo {argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"}, com pequenos raios decorativos amarelos em ambos os lados. Abaixo, uma faixa roxa com texto em maiúsculas branco lendo {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"}. Sob a faixa, adicione duas linhas de instrução centralizadas em preto: "Recorte as peças e embaralhe. Cada jogador pega 7 peças." e "O objetivo é ficar sem peças!". A área principal mostra 40 peças estilo dominó organizadas em uma grade de 4 colunas por 10 linhas, espaçadas uniformemente. Cada peça é um retângulo horizontal arredondado com um contorno fino e colorido, preenchimento branco, um divisor vertical no centro e um pequeno ponto preto no divisor. A metade esquerda contém um número de resultado ou a palavra "INÍCIO" na primeira peça, e a metade direita contém uma expressão de multiplicação. Use cores de borda alternadas na grade, como roxo, verde, azul, laranja, rosa e amarelo. As 40 peças, em ordem de linha da esquerda para a direita, de cima para baixo, são: 1) "INÍCIO | 1 × 1", 2) "1 | 1 × 2", 3) "2 | 1 × 3", 4) "3 | 1 × 4", 5) "4 | 1 × 5", 6) "5 | 1 × 6", 7) "6 | 1 × 7", 8) "7 | 1 × 8", 9) "8 | 1 × 9", 10) "9 | 2 × 2", 11) "4 | 2 × 3", 12) "6 | 2 × 4", 13) "8 | 2 × 5", 14) "10 | 2 × 6", 15) "12 | 2 × 7", 16) "14 | 2 × 8", 17) "16 | 2 × 9", 18) "18 | 3 × 3", 19) "9 | 3 × 4", 20) "12 | 3 × 5", 21) "15 | 3 × 6", 22) "18 | 3 × 7", 23) "21 | 3 × 8", 24) "24 | 3 × 9", 25) "27 | 4 × 4", 26) "16 | 4 × 5", 27) "20 | 4 × 6", 28) "24 | 4 × 7", 29) "28 | 4 × 8", 30) "32 | 4 × 9", 31) "36 | 5 × 5", 32) "25 | 5 × 6", 33) "30 | 5 × 7", 34) "35 | 5 × 8", 35) "40 | 5 × 9", 36) "45 | 6 × 6", 37) "36 | 6 × 7", 38) "42 | 6 × 8", 39) "48 | 6 × 9", 40) "54 | 7 × 7". Na parte inferior, adicione uma grande caixa roxa tracejada e arredondada que abrange a maior parte da largura. Dentro do lado esquerdo desta caixa, coloque o título da seção "COMO JOGAR:" em roxo negrito e maiúsculas, seguido por 5 tópicos em preto: "Coloque a peça “INÍCIO” na mesa.", "Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.", "Se não tiver peça para jogar, compre do monte.", e "Vence quem ficar sem peças!". No lado direito da mesma caixa, adicione o título "EXEMPLO DE INÍCIO:" em roxo maiúsculo e mostre 4 pequenas peças de dominó em sequência seguidas de reticências: "INÍCIO | 1 × 1", depois "1 | 1 × 2", depois "2 | 1 × 3", depois "3 | 1 × 4", seguido de "...". Mantenha o estilo geral nítido, tipo vetor, imprimível, amigável para a prática de matemática do ensino fundamental, com espaçamento equilibrado e texto altamente legível.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="Infografía / Visual Educativo - Ficha de Dominó de Multiplicação para Imprimir - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Fuente:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14631)**

---

### No. 49: Infografía / Visual Educativo - Cuadrícula de línea de tiempo de inventos históricos

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un póster educativo con estilo de pergamino que muestra una cuadrícula de dioramas de inventos etiquetados a lo largo de la historia, ideal para infografías de líneas de tiempo y comparaciones de tecnología que cambió el mundo.

#### 📝 Prompt

```
Crea una ilustración estilo infografía cuadrada que muestre una cuadrícula de línea de tiempo de inventos de {argument name="grid size" default="15×15"} renderizada como una colección de dioramas isométricos en miniatura sobre baldosas de pergamino envejecido. La imagen debe parecer un póster histórico curado que abarca desde el {argument name="starting year" default="1000 a. C."} hasta el {argument name="ending year" default="2026"}, con un invento por baldosa y sin repeticiones. Muestra la parte visible como una sección de 5 por 5 de la cuadrícula más grande, para un total de 25 baldosas etiquetadas, dispuestas en filas y columnas ordenadas con bordes oscuros y delgados. Cada baldosa contiene un invento único que cambió el mundo, representado como un pequeño diorama hecho a mano con materiales, colores y detalles de fondo apropiados para la época. Utiliza una paleta cálida y anticuaria para los inventos antiguos y medievales, tonos sepia de documentos técnicos para los inventos de la era moderna temprana y una iluminación futurista azul neón para los inventos digitales y biotecnológicos modernos. Rodea la cuadrícula con un borde de mapa antiguo y texturas sutiles de cartografía histórica, mezclándose con tenues gráficos de redes modernas cerca de la esquina inferior derecha.

Etiqueta cada baldosa visible con una pequeña etiqueta beige en texto negro en negrita. Incluye exactamente estos 25 inventos visibles en orden de lectura de arriba a la izquierda a abajo a la derecha: 1) baldosa de {argument name="first tile label" default="1000 a. C."} que muestra un arado de hierro y herramientas manuales simples en un campo de cultivo, con la etiqueta "Arado de hierro y herramientas"; 2) "Concepto del cero" mostrado como una baldosa tipo pergamino con un símbolo de cero tallado y un reloj de arena azul; 3) "Reloj de agua" mostrado como un dispositivo de medición de tiempo de madera; 4) "Catapulta" mostrada como una máquina de asedio de madera; 5) "Mecanismo de Anticitera" mostrado como un intrincado dispositivo de engranajes de bronce en un nicho de piedra; 6) "Hormigón" mostrado como una carretilla llena de cemento o mortero húmedo; 7) "Carretilla" mostrada como un carro simple de madera de una sola rueda; 8) "Molino de viento" mostrado como un molino tradicional sobre terreno cubierto de hierba; 9) "Pólvora" mostrada como un barril y un montón de pólvora negra con humo; 10) "Imprenta" mostrada como una prensa de madera enmarcada por columnas clásicas; 11) "Reloj mecánico" mostrado como un reloj de pie ornamentado; 12) "Telescopio" mostrado como un telescopio de latón antiguo sobre un trípode con notas científicas tipo boceto; 13) "Máquina de vapor" mostrada en una baldosa estilo plano azul con un motor de locomotora antiguo; 14) "Batería eléctrica" mostrada en una baldosa tipo plano con dos celdas de batería cilíndricas y cableado; 15) "Telégrafo" mostrado como una llave telegráfica Morse sobre papel técnico; 16) "Bombilla" mostrada brillando cálidamente sobre un pedestal neutro; 17) "Automóvil" mostrado como un coche antiguo rojo sobre un fondo de plano de taller; 18) "Avión" mostrado como un avión comercial a reacción en miniatura; 19) "Transistor" mostrado como un microchip negro sobre una baldosa de placa de circuito luminoso; 20) "Computadora personal" mostrada como una computadora de escritorio beige con monitor CRT y teclado; 21) "World Wide Web" mostrada como un globo terráqueo azul brillante sobre circuitos digitales; 22) "Smartphone" mostrado como un teléfono moderno y elegante sobre un fondo de tecnología de neón; 23) "CRISPR-Cas9" mostrado como una doble hélice de ADN en una baldosa de visualización azul biotecnológica; 24) "Cohete reutilizable" mostrado como varios cohetes verticales lanzándose con nubes de escape; 25) "IA (LLMs)" mostrada como letras grandes y brillantes de IA en un cubo tecnológico holográfico; 26) "Interfaz cerebro-computadora" mostrada como un holograma de cerebro brillante sobre una plataforma azul; 27) "Interfaz neuronal avanzada (implante)" mostrada como un perfil de cabeza humana transparente con un implante cerebral brillante, con una pequeña etiqueta superior que dice "2026".

Mantén la composición altamente organizada, similar a un póster y visualmente densa, con cada baldosa legible de un vistazo. Utiliza una ligera perspectiva isométrica, líneas nítidas, sombreado pictórico y una calidad de ilustración editorial pulida. La sensación general debe combinar un póster de museo, una línea de tiempo educativa y arte de diorama histórico-tecnológico imaginativo.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="Infografía / Visual Educativo - Cuadrícula de línea de tiempo de inventos históricos - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Gadgetify](https://x.com/Gdgtify)
- **Fuente:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14412)**

---

### No. 50: Miniatura de YouTube - Póster de película de aventuras de tiburones chibi

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un colorido póster de anime al estilo japonés para una película infantil de aventuras oceánicas, ideal para recrear arte promocional llamativo con personajes adorables y una tipografía de título dramática.

#### 📝 Prompt

```
Una ilustración de póster de película japonesa brillante y llena de energía en un estilo anime chibi pulido, ambientada en una escena de aventuras en un océano tropical resplandeciente. Centra la composición en 2 niños chibi adorables montando un tiburón azul sonriente que salta en diagonal hacia arriba a través de agua de mar arremolinada y efectos de salpicaduras blancas. El niño de la izquierda tiene el pelo negro corto, enormes ojos azules brillantes, una sonrisa feliz con la boca abierta, una camiseta negra, pantalones cortos oscuros, zapatillas blancas y una sudadera de tiburón azul claro con una capucha con bordes dentados que enmarca su rostro; señala hacia arriba con una mano y abraza al tiburón con la otra. La niña de la derecha tiene el pelo naranja, grandes ojos morados brillantes, una sonrisa alegre con la boca abierta, un vestido naranja, zapatos rosas y una sudadera de tiburón rosa con una capucha con bordes dentados; extiende un brazo con entusiasmo mientras se sujeta con el otro. Haz que el tiburón sea grande y amigable, con un cuerpo redondeado, vientre pálido, ojos negros diminutos y una boca muy abierta. Rodéalos con un vívido mundo submarino y de superficie: bancos de pequeños peces tropicales, exactamente 1 tortuga marina a la izquierda, exactamente 1 delfín a la derecha, exactamente 1 pulpo rosa a la derecha, exactamente 1 pez globo en la parte inferior izquierda, arrecifes de coral y plantas marinas a lo largo de los bordes inferiores, burbujas de aire por todas partes y fuertes líneas de movimiento de agua azul. En el fondo superior, muestra un cielo soleado con dramáticos rayos de sol que se filtran en el agua, nubes esponjosas, 2 gaviotas volando, una isla tropical rocosa con palmeras en la parte superior izquierda y un barco pirata en la parte superior derecha con velas blancas y un lindo emblema de tiburón. Añade un timón de barco parcialmente visible detrás del título principal. Utiliza un diseño promocional de anime infantil japonés denso y emocionante con letras 3D de gran tamaño y efectos explosivos. En la parte superior, coloca el texto del título japonés gigante {argument name="headline text" default="サメなの ワクワク 大作戦"} en líneas apiladas, con letras degradadas en azul brillante, naranja rosado y amarillo anaranjado, contornos blancos gruesos, sombras azul oscuro, salpicaduras de agua y destellos. Debajo del título, añade un eslogan japonés curvo más pequeño en blanco con contorno azul: {argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"}. En la parte inferior, coloca un texto de estreno enorme en japonés, {argument name="release text" default="2026年 夏公開"}, en letras 3D con degradado de rojo a amarillo en negrita con bordes blancos y azules, sobre un estallido naranja radiante. En la parte inferior derecha, añade una insignia de estrella azul con el texto en japonés {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"} en blanco y amarillo. Incluye exactamente 2 accesorios de esquina con temática de tesoros: un cofre del tesoro abierto con monedas de oro en la parte inferior izquierda y una brújula en la parte inferior derecha. El aspecto general debe ser brillante, saturado, familiar, caprichoso, cinematográfico y similar a un juguete, con contornos nítidos, expresiones exageradas, alto contraste y una composición vertical lista para póster. Sin fotorrealismo, sin colores apagados, sin minimalismo.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="Miniatura de YouTube - Póster de película de aventuras de tiburones chibi - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **Fuente:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14504)**

---

### No. 51: Miniatura de YouTube - Collage publicitario japonés de sanación en cuatro paneles

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un llamativo collage publicitario japonés de cuatro cuadrantes para servicios de coaching o superación personal, diseñado para publicaciones en redes sociales, enlaces de perfil o imágenes de portada en marketplaces.

#### 📝 Prompt

```
{"type":"collage publicitario japonés para redes sociales","style":"diseño de anuncio de alto impacto, brillante y dramático, formato cuadrado de cuatro paneles, tipografía japonesa llamativa, colores saturados, efectos de brillo, destellos, superposiciones de degradado, elementos visuales de marketing basados en la urgencia","canvas":{"aspect_ratio":"1:1","size":"cuadrado"},"layout":{"grid":"2x2","panels":[{"position":"arriba a la izquierda","theme":"ansiedad y dudas sobre uno mismo","background":"escena femenina de estilo de vida en blanco y rosa suave con texturas de luz y bokeh","subject":"primer plano de una joven preocupada con un acogedor suéter de punto blanco, una mano cerca de la cara, cabello en un moño desordenado, rostro parcialmente oculto","text_blocks":[{"text":"¡Si no lo sabes, pierdes!","style":"banda amarilla en ángulo con texto negro","position":"arriba a la izquierda"},{"text":"El 99% se equivoca","style":"titular muy grande, números rojos y texto japonés estilo caligrafía negra","position":"de arriba a la izquierda al centro"},{"text":"Cómo afrontar esa preocupación","style":"subtítulo rosa","position":"debajo del titular principal"},{"text":"Sientes malestar sin motivo","style":"elemento de lista en caja blanca redondeada con icono de marca de verificación roja"},{"text":"Te esfuerzas pero nada cambia","style":"elemento de lista en caja blanca redondeada con icono de marca de verificación roja"},{"text":"No conoces tus verdaderos sentimientos","style":"elemento de lista en caja blanca redondeada con icono de marca de verificación roja"},{"text":"Te agotan las relaciones personales","style":"elemento de lista en caja blanca redondeada con icono de marca de verificación roja"},{"text":"Sientes ansiedad constante por el futuro","style":"elemento de lista en caja blanca redondeada con icono de marca de verificación roja"},{"text":"No tienes que cargar con ese malestar a solas.","style":"insignia circular rosa con texto blanco","position":"abajo a la derecha"}],"count":9},{"position":"arriba a la derecha","theme":"no es sanación, sino un mecanismo de cambio","background":"galaxia cósmica profunda con nebulosas azules, púrpuras y magenta, luces estelares, vórtice de energía, atmósfera espiritual brillante","subject":"pequeña figura femenina vista desde atrás o de lado, de pie cerca de un portal radiante o columna de luz, rostro parcialmente oculto","text_blocks":[{"text":"Parece normal, pero en realidad...","style":"texto blanco sobre banda negra en ángulo","position":"arriba a la izquierda"},{"text":"Esto,","style":"texto blanco grande","position":"arriba a la izquierda"},{"text":"no es","style":"texto amarillo muy grande sobre pincelada púrpura oscura","position":"centro"},{"text":"sanación.","style":"texto blanco grande","position":"debajo"},{"text":"Al 'ordenar' tu interior,","style":"texto en caja blanca","position":"abajo a la izquierda"},{"text":"la realidad cambia","style":"texto resaltado en rosa","position":"centro-abajo a la izquierda"},{"text":"¡existe un mecanismo!","style":"texto blanco","position":"abajo a la izquierda"}],"graphic_elements":[{"type":"flecha amarilla curva","count":1,"direction":"hacia la figura brillante"}],"count":8},{"position":"abajo a la izquierda","theme":"volver a tu verdadero yo crea un futuro más brillante","background":"cielo azul soleado con nubes suaves, campo verde, hojas flotantes, ambiente diurno brillante y esperanzador","subject":"joven alegre con vestido blanco sin mangas, brazos extendidos, girando bajo la luz del sol, rostro parcialmente oculto","text_blocks":[{"text":"Al volver a tu verdadero yo","style":"titular rojo y negro","position":"arriba"},{"text":"tendrás este futuro","style":"titular muy grande con degradado dorado","position":"centro"},{"text":"","style":"texto negro grande","position":"derecha-centro"},{"text":"Tu mente se aligera y cada día es más divertido","style":"elemento de beneficio en burbuja blanca redondeada con icono de corazón rosa"},{"text":"Las relaciones fluyen y se llenan de amor","style":"elemento de beneficio en burbuja blanca redondeada con icono de personas verde"},{"text":"El flujo de dinero cambia y la abundancia llega naturalmente","style":"elemento de beneficio en burbuja blanca redondeada con icono de yen dorado"},{"text":"¡Tu vida empezará a cambiar más de lo que imaginas!","style":"cinta inferior rosa con texto blanco","position":"abajo"}],"count":7},{"position":"abajo a la derecha","theme":"oferta de descuento por tiempo limitado","background":"textura de explosión roja y dorada con destellos y estelas de chispas, estética de lujo y urgencia","text_blocks":[{"text":"¡Si no lo sabes,","style":"banda de pincel amarilla con texto negro","position":"arriba a la izquierda"},{"text":"pierdes!","style":"kanji dorado extremadamente grande con bisel metálico","position":"arriba a la derecha"},{"text":"Precio habitual 9,980 yenes (impuestos incluidos)","style":"etiqueta de precio blanca con números negros tachados y nota de impuestos pequeña","position":"arriba a la izquierda"},{"text":"Precio de monitor","style":"texto blanco","position":"centro-izquierda"},{"text":"40% de descuento","style":"texto de descuento enorme con degradado de rosa a blanco","position":"centro-abajo"},{"text":"¡Solo por ahora, oferta limitada! Cupos limitados","style":"sello circular dorado","position":"derecha-centro"},{"text":"Más información en el perfil","style":"barra de llamada a la acción púrpura con texto blanco y botón de flecha blanca","position":"abajo"}],"count":7}],"total_panels":4},"composition":"collage publicitario japonés persuasivo y dinámico, optimizado para la visibilidad en miniaturas de redes sociales, cada cuadrante tiene un mensaje emocional y una identidad de color distintos, uso intensivo de bandas diagonales, kanji y números de gran tamaño, insignias brillantes, cajas de información blancas redondeadas e iluminación dramática","customization":{"primary headline":"{argument name=\"headline text\" default=\"El 99% se equivoca\"}","discount text":"{argument name=\"discount text\" default=\"40% de descuento\"}","price":"{argument name=\"price\" default=\"9,980 yenes (impuestos incluidos)\"}","main color palette":"{argument name=\"main color palette\" default=\"rosa, galaxia azul-púrpura, azul cielo, rojo-dorado\"}","call to action":"{argument name=\"call to action\" default=\"Más información en el perfil\"}"},"render_notes":"haz que todo el texto japonés sea grande y legible, con sombras y contornos en capas; utiliza una estética de composición publicitaria pulida en lugar de un diseño minimalista; los rostros deben estar borrosos o parcialmente ocultos; enfatiza el contraste emocional entre la ansiedad, la revelación, la transformación esperanzadora y la oferta urgente"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="Miniatura de YouTube - Collage publicitario japonés de sanación en cuatro paneles - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **Fuente:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14551)**

---

### No. 52: Miniatura de YouTube - Miniatura para tutorial técnico con maqueta de interfaz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una miniatura llamativa al estilo de YouTube que incluye un título de tutorial, una maqueta del panel de control de una aplicación de diseño y un presentador señalando la interfaz para contenido de marca o sistemas de diseño.

#### 📝 Prompt

```
Una miniatura de YouTube moderna y limpia sobre un fondo blanco brillante, dividida visualmente entre un texto llamativo a la izquierda y un presentador recortado a la derecha. A la izquierda, coloca un titular masivo apilado en fuente sans-serif negra, pesada y en mayúsculas que diga {argument name="headline text" default="CLAUDE DESIGN"}, alineado a la parte superior izquierda en dos líneas. Debajo, añade un banner rectangular grande y redondeado de color naranja con una sombra paralela sutil que contenga texto en negrita, blanco y en mayúsculas con un borde naranja que diga {argument name="subheadline text" default="EN 6 MIN"}. Cerca del titular, incluye 2 formas de estrella naranja, una pequeña junto al texto y otra mucho más grande en el fondo del extremo derecho. En el cuadrante inferior izquierdo, muestra una maqueta de interfaz de aplicación flotante para un panel de control de herramienta de diseño con un panel de color blanco roto suave, bordes delgados, esquinas redondeadas y una sombra tenue. La interfaz debe tener una barra lateral izquierda con 4 elementos de menú etiquetados exactamente como: "Recent", "Your designs", "Examples" y "Design systems". El encabezado del panel principal debe decir "Recent" y contener 3 tarjetas de proyecto dispuestas en una cuadrícula, etiquetadas exactamente como: "Thumio Design System", "Thumio Startup" y "Design System". En la mitad derecha, muestra a un hombre joven adulto, recortado y con aspecto fotorrealista, desde el pecho hacia arriba, vistiendo un suéter de cuello alto blanco, con cabello castaño claro desordenado y barba incipiente, posicionado cerca de la cámara. Su rostro está intencionalmente oculto por un rectángulo sólido de color canela que cubre la mayor parte del área facial. Señala con una mano hacia el panel de interfaz a la izquierda, con el dedo extendido. Utiliza una paleta de marca en tonos naranja cálido y blanco, alto contraste, poco desorden, un estilo de miniatura pulido para la economía de creadores, sombras sutiles y una composición diseñada para contenido de tutoriales técnicos.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="Miniatura de YouTube - Miniatura para tutorial técnico con maqueta de interfaz - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [corbin](https://x.com/corbin_braun)
- **Fuente:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14695)**

---

### No. 53: Miniatura de YouTube - Superposición de Livestream de VTuber Celestial

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una pantalla de livestream de VTuber estilo anime detallada que presenta a una ídolo celestial de cabello azul en una sala de streaming con temática estelar, ideal para recrear superposiciones de streaming de fantasía y visuales promocionales.

#### 📝 Prompt

```
{"type":"ilustración de superposición de livestream de VTuber estilo anime","theme":"cielo nocturno celestial, estrellas, constelaciones, azul zafiro profundo y blanco, estética elegante de ídolo mágica","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"joven y linda mujer anime","hair":{"color":"{argument name=\"hair color\" default=\"azul cielo pálido\"}","style":"cabello muy largo y ondulado tipo coletas sueltas con un pequeño ahoge, flequillo suave, adornos de estrellas en el cabello y cintas"},"outfit":{"style":"vestido de ídolo celestial ornamentado","pieces":["blusa blanca con hombros descubiertos y mangas abullonadas","gran lazo azul marino en el pecho con adorno de estrella dorada","corsé azul marino con ribetes dorados y motivos de constelaciones","gargantilla de estrella","pequeño mini sombrero blanco inclinado con cinta azul y accesorio de estrella dorada"]},"pose":"sentada en un escritorio de streaming, centrada, mirando hacia adelante detrás de un micrófono y un teclado","expression":"amable, tranquila, acogedora"}},"environment":{"setting":"acogedora sala de streaming de fantasía por la noche con una gran ventana que muestra un cielo lleno de estrellas","background_elements":["guirnaldas de estrellas colgantes y adornos de cristal","estantes con botellas, libros, reloj de arena, objetos tipo telescopio y decoración celestial","imágenes de luna y constelaciones fuera de la ventana","dos peluches esponjosos tipo mascota de nube con ojos azules"]},"props":{"desk_items":["1 micrófono grande de estilo vintage en un soporte a la izquierda del centro","1 teclado decorativo con teclas temáticas de estrellas","1 placa con el nombre que dice \"蒼空なつみ - SORA NATSUMI -\"","1 postre en copa tipo parfait cubierto con una pequeña figura de conejo blanco","1 taza pequeña o portavelas con una mascota de nube"]},"layout":{"format":"superposición completa de pantalla de espera/charla para livestream","sections":[{"title":"LIVE","position":"banner vertical superior izquierdo","count":3,"labels":["LIVE","20:30","20/05 Mar"]},{"title":"COMMENTS","position":"panel izquierdo","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今日はどんなお話かな？","しろくまアイス：こんなっつー！","天の川りゅうせい：今日も可愛い！大好き！","ふるーすたー：も ふ ぷ","月見うさぎ：楽しみ〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：きちゃー！( *´ω｀)","彗星カケル：配信ありがとう〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今日のサムネもかわいい…！","夜更かしの民：こんなっつー！","ゆめみがち：待ってました！","ハル：今日の衣装も最高に似合ってるぞ〜！"]},{"title":"social tags","position":"debajo del panel de comentarios","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"inferior izquierdo","count":4,"labels":["Objetivo: ¡100,000 suscriptores!","Actual","58,320 personas","¡Gracias siempre! Suscríbete y dale me gusta☆"]},{"title":"supporters panel","position":"tarjeta pequeña inferior izquierda junto al panel de objetivos","count":6,"labels":["☆Estrellas de hoy (¡Gracias por el Super Chat!)☆","星の旅人 さん ¥2,000","ふるーすたー さん ¥1,000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"panel superior derecho","count":3,"labels":["Now Talking","{argument name=\"talk topic text\" default=\"¡Bienvenidos los nuevos! Charla relajada✨\"}","{argument name=\"subtitle text\" default=\"〜Hablemos tranquilamente〜\"}"]},{"title":"SET LIST","position":"panel central derecho","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"panel inferior derecho","count":3,"labels":["Canción original","星空コンパス","¡MV disponible!"]}],"logo":{"position":"esquina superior derecha","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"ilustración de anime pulida de alto detalle, reflejos luminosos, brillo suave, líneas nítidas","composition":"simétrica, superposición decorativa densa, personaje centrado con paneles de interfaz a su alrededor","lighting":"ambiente azul frío a la luz de la luna con acentos dorados brillantes","mood":"de ensueño, mágico, acogedor, elegante"}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="Miniatura de YouTube - Superposición de Livestream de VTuber Celestial - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [はげあたま](https://x.com/hageatama)
- **Fuente:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14443)**

---

### No. 54: Miniatura de YouTube - Escena de desesperación en un stream de YouTube Gaming

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt específico para generar una escena de un popular YouTuber experimentando un fracaso trágico en un juego como Tetris, incluyendo las reacciones del chat.

#### 📝 Prompt

```
Una escena de un popular YouTuber japonés en su {argument name="content" default="transmisión de juego"}. En {argument name="game name" default="Tetris"}, parecía que una barra larga despejaría todo, pero la colocación fue ligeramente incorrecta y el streamer está gritando con una expresión de desesperación, mientras la sección de comentarios está en un caos total. Idioma japonés.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="Miniatura de YouTube - Escena de desesperación en un stream de YouTube Gaming - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fuente:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14346)**

---

### No. 55: Miniatura de YouTube - Póster de película de romance anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un póster cinematográfico pulido al estilo anime japonés para una película de romance agridulce, ideal para arte clave de cine, anuncios de películas ficticias o diseños de pósteres dramáticos centrados en personajes.

#### 📝 Prompt

```
Un póster de película romántica japonesa en un formato vertical estilo smartphone con esquinas redondeadas, diseñado como una imagen clave de anime pulida. La imagen principal muestra a una hermosa chica adolescente, la heroína, parada en un balcón al aire libre al atardecer, girándose sobre su hombro para mirar al espectador con una expresión suave y melancólica. Tiene el cabello muy largo, de color blanco plateado, peinado en dos coletas atadas con cintas oscuras, piel pálida y grandes ojos de color rosa violeta. Viste una delicada blusa blanca con volantes y mangas voluminosas, junto con un vestido oscuro de cintura alta o una falda tipo corsé, creando un look elegante de romance escolar con un toque gótico. La atmósfera es onírica y emotiva, llena de luces bokeh brillantes, pétalos a la deriva o destellos como nieve, luz de atardecer en tonos rosa y lavanda, y un paisaje urbano luminoso en el fondo desenfocado. Utiliza un renderizado de anime cinematográfico rico, mechones de cabello ultra detallados, luz de contorno suave, ojos brillantes y un estado de ánimo de primer amor agridulce. Añade tipografía de póster japonesa integrada en la composición: un eslogan poético vertical grande en rosa a la derecha, un eslogan vertical blanco a la izquierda, un título principal muy grande cerca de la parte inferior izquierda que dice {argument name="title text" default="看板娘"}, y un subtítulo más pequeño al lado que dice {argument name="subtitle text" default="君と紡ぐ恋物語"}. Incluye 5 pequeñas imágenes rectangulares de vista previa tipo tira de película alineadas en la parte inferior central, cada una mostrando a la misma heroína en diferentes primeros planos emocionales. Añade créditos densos, laureles de estilo festival y pequeña información de estreno en la parte superior e inferior en japonés, con la sensación general de un póster de película de anime romántico premium que anuncia una historia de amor trágica y hermosa. Utiliza una paleta pastel de malva, rosa rubor, violeta, blanco perla y azul marino medianoche, con un efecto de resplandor suave, poca profundidad de campo y una composición de póster elegante.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="Miniatura de YouTube - Póster de película de romance anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="Miniatura de YouTube - Póster de película de romance anime - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [studioあぽろん](https://x.com/ai_studioapollo)
- **Fuente:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14529)**

---

### No. 56: Miniatura de YouTube - Miniatura de YouTube estilo anime japonés llamativa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una miniatura de YouTube de alto impacto al estilo anime japonés para explicaciones de IA o tecnología, con texto de gran tamaño, efectos de fuego y un personaje señalando.

#### 📝 Prompt

```
Crea una miniatura de YouTube japonesa hipersaturada en un estilo anime llamativo tipo clickbait, formato horizontal 16:9, con una composición dividida: enormes bloques de texto apilados que dominan los dos tercios izquierdos y un personaje de anime en el tercio derecho. El fondo es una explosión ardiente de energía roja, naranja y dorada con chispas brillantes, destellos de lente, reflejos de estrellas centelleantes y un efecto de brillo metálico de alto contraste en todas partes. A la izquierda, coloca 4 grupos de texto en negrita apilados verticalmente con contornos negros gruesos, trazos internos blancos, un intenso resplandor exterior y un tratamiento 3D brillante. Línea superior: un titular japonés gigante {argument name="headline text" default="紅エンジニア必見"} en rojo intenso con bordes blancos y acentos de chispas doradas brillantes. Segunda línea: un icono cuadrado redondeado de color naranja similar a una aplicación con una "M" blanca estilizada a la izquierda de la palabra {argument name="product name" default="masatra"} en letras minúsculas blancas sans-serif enormes con contorno negro y un sombreado gris sutil. Tercera línea: un banner rectangular negro con texto japonés compacto en negrita que dice "次世代AIエージェントフレームワーク". Línea inferior: texto japonés metálico dorado muy grande {argument name="bottom text" default="徹底解説"} con relieve 3D biselado, degradado de naranja a dorado, reflejos especulares brillantes y bordes resplandecientes. A la derecha, muestra a una mujer joven estilo anime de pecho hacia arriba, con cabello de longitud media de color {argument name="hair color" default="brown"}, vistiendo una bata de laboratorio blanca abierta sobre una camisa blanca, inclinándose hacia la cámara y señalando directamente al espectador con una mano en escorzo y el dedo índice extendido en primer plano. Su pose debe sentirse segura, urgente y llamativa. Utiliza una iluminación de contorno dramática proveniente del fondo ardiente, reflejos naranjas fuertes en la piel y la ropa, y un acabado de miniatura comercial pulido. Reserva un área rectangular grande sobre la región superior derecha del rostro como un bloque de marcador de posición en {argument name="placeholder color" default="light brown"}, oscureciendo la mayor parte de la cara. Haz que el diseño general sea extremadamente denso, brillante, explosivo y optimizado para una máxima legibilidad en tamaños pequeños.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="Miniatura de YouTube - Miniatura de YouTube estilo anime japonés llamativa - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **Fuente:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14491)**

---

### No. 57: Miniatura de YouTube - Miniatura explosiva para lanzamiento de anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una llamativa miniatura promocional de estilo anime japonés para anuncios de lanzamiento, publicidad de cursos online o imágenes de marketing para negocios de IA.

#### 📝 Prompt

```
Crea una espectacular miniatura de YouTube al estilo promocional de anime japonés con iluminación explosiva, efectos de chispas densas y un contraste dramático. La composición es una escena unificada con un fondo negro y verde neón, estallidos de purpurina dorada y una sutil silueta del horizonte de la ciudad en el borde inferior. En el lado derecho, muestra a un lindo chico anime estilo chibi de cintura para arriba, con cabello castaño oscuro a negro desordenado, acentuado con vívidas mechas verde neón y un pequeño detalle rojo a un lado, ojos grandes de color verde brillante, una sonrisa abierta y entusiasta, y una pose enérgica señalando directamente al espectador con una mano mientras tiene el otro puño en alto. Viste una sudadera negra bajo una chaqueta verde con reflejos brillantes. En el lado izquierdo, coloca 1 reloj de arena verde brillante con energía verde arremolinada en su interior. Llena la imagen con intensos destellos, reflejos de lente, partículas doradas y líneas de velocidad para lograr un aspecto de miniatura viral. Añade 5 elementos de texto en japonés con tipografía llamativa de gran tamaño: una cinta roja en la parte superior izquierda que dice {argument name="top banner text" default="4月28日スタート"} en letras amarillas gruesas con borde blanco; el titular central principal en kanji metálicos dorados masivos que dice {argument name="main headline" default="ついに解禁"} con una sombra negra intensa y textura dorada brillante; un subtítulo grande en blanco y verde en la parte inferior izquierda que dice {argument name="subheadline" default="AI副業で人生変わる"}; 1 insignia redondeada verde cerca de la parte inferior central derecha que dice {argument name="bonus badge text" default="無料10大特典"} en texto negrita blanco y amarillo; y 1 cinta negra inclinada en la parte inferior derecha que dice {argument name="corner banner text" default="近日公開"} con un texto más pequeño en inglés debajo que dice COMING SOON. Haz que todo se sienta urgente, festivo y capte la atención, como una miniatura de anuncio de lanzamiento con alto CTR, con contornos gruesos, bordes brillantes, texto metálico y profundidad en capas.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="Miniatura de YouTube - Miniatura explosiva para lanzamiento de anime - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fuente:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14499)**

---

### No. 58: Miniatura de YouTube - Miniatura de YouTube llamativa para monetizar X

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una miniatura al estilo de marketing japonés para videos sobre cómo monetizar X rápidamente, ideal para contenido de crecimiento en redes sociales o ingresos en línea.

#### 📝 Prompt

```
Crea una miniatura de YouTube de alto impacto al estilo de marketing de internet japonés, en formato horizontal 16:9, con un fondo explosivo negro y dorado lleno de destellos, destellos de lente, partículas brillantes y haces de luz dramáticos. La composición es densa y enérgica, con una tipografía gigante en capas que domina la izquierda y el centro, y un personaje masculino estilo anime a la derecha. En la parte superior, coloca una cinta roja curva con bordes dorados y texto en japonés en negrita blanco y amarillo que diga {argument name="headline text" default="実績者が教える"}. Debajo, haz que el titular principal sea extremadamente grande, brillante y tridimensional con contornos negros gruesos y un resplandor dorado: un enorme "10" de metal dorado, seguido de un "日で" en blanco negrita, luego una "X" gigante de neón verde brillante, después texto apilado en blanco "収益化", y en la parte inferior el texto dorado más grande "達成". Detrás del titular, añade un gráfico de barras verde brillante con tendencia ascendente y una flecha apuntando hacia la esquina superior derecha para simbolizar el crecimiento. En el lado izquierdo, incluye 3 elementos sociales y de dinero: un smartphone negro inclinado que muestra el logotipo blanco de X, un globo de chat verde con un corazón blanco y un globo de chat verde más pequeño con la silueta de un usuario en blanco. En la parte inferior izquierda, añade 2 pilas de monedas de oro brillantes y 1 moneda de oro con el símbolo del yen. En el lado derecho, muestra a 1 joven estilo anime desde los muslos hacia arriba, con cabello castaño oscuro desordenado acentuado por mechones verde vivo, piel clara y una pose confiada con los brazos cruzados, vistiendo una chaqueta negra con ropa interior verde; su rostro está oculto por un bloque de desenfoque rectangular simple. Cerca de su lado inferior derecho, coloca 1 sello de premio dorado con decoración de laurel y una pequeña corona, que contenga el texto en japonés "成功者続出", y adjunta una cinta roja a través de la parte inferior del sello con el texto "再現性あり". A lo largo de la parte inferior, coloca 3 cajas de características rectangulares de color verde brillante con bordes dorados e interiores negros. La primera caja contiene 1 icono de marca de principiante y el texto "X初心者でも 簡単収益化". La segunda caja contiene 1 icono de reloj y el texto "1日1時間の 作業でOK". La tercera caja contiene 1 icono de calendario con una marca de verificación verde y el texto "最短10日で 収益化条件達成". Utiliza fuentes japonesas en negrita de gran tamaño, degradados de oro metálico, texto blanco con trazo negro grueso, reflejos de neón verde vivo, contraste extremo y una estética de miniatura pulida optimizada para la tasa de clics.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="Miniatura de YouTube - Miniatura de YouTube llamativa para monetizar X - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fuente:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14498)**

---

### No. 59: Miniatura de YouTube - Miniatura para monetización en X (Japón)

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una llamativa miniatura de YouTube al estilo anime japonés para una guía de monetización en X dirigida a principiantes, ideal para el crecimiento en redes sociales, estrategias de ingresos y portadas de videos sobre negocios online.

#### 📝 Prompt

```
Crea una miniatura de YouTube llamativa al estilo anime-negocios, formato horizontal 16:9, composición densa, alto contraste, efectos de texto brillante, paleta de colores verde neón y dorado, iluminación dramática, partículas de chispas, destellos de lente y una intensa profundidad de campo. La escena muestra una estación de trabajo desenfocada y un panel de análisis de redes sociales al fondo, con gráficos de líneas ascendentes y una tarjeta de ingresos visible que dice "ポストアナリティクス" y "収益 ¥248,620". En el lado derecho, coloca a un streamer estilo anime de medio cuerpo con cabello castaño oscuro desordenado con mechones verde neón, vistiendo una sudadera o chaqueta negra, sonriendo con confianza y señalando hacia arriba con un dedo; deja el área de su rostro parcialmente oculta por un bloque rectangular grande en color marrón oliva apagado para poder insertar texto o un retrato personalizado más adelante. En la parte superior, añade una cinta brillante verde con bordes dorados y un icono de principiante a la izquierda, que contenga el texto {argument name="headline text" default="初心者向け完全ガイド"}. En el centro-izquierda, crea un "10" gigante de oro metálico con un contorno negro grueso y reflejos blancos intensos, seguido por el texto en japonés en blanco y negro "日で". Debajo y superponiéndose al centro, coloca una enorme letra "X" verde neón brillante con bordes eléctricos y efectos de chispas. A la derecha de la X y en primer plano, añade un enorme texto en 3D en japonés en blanco y dorado con un contorno negro grueso y sombras paralelas que diga {argument name="main claim text" default="収益化達成"}. En el lado izquierdo, cerca del texto principal, incluye 3 iconos flotantes estilo redes sociales: un icono cuadrado negro con el logo de X en blanco, un icono de burbuja de chat azul con un corazón blanco y un icono cuadrado rosa redondeado con la silueta de un usuario en blanco. En la parte inferior izquierda, coloca una taza de café negra con el logo de X en blanco sobre un escritorio. A lo largo del borde inferior, añade 3 cajas de información blancas redondeadas con bordes verdes y sombras sutiles, espaciadas uniformemente, cada una con un círculo numerado verde encima: caja 1 etiquetada "01" con un icono de principiante y el texto "X初心者でも 簡単収益化"; caja 2 etiquetada "02" con un icono de reloj y el texto "1日1時間の 作業でOK"; caja 3 etiquetada "03" con un icono de calendario que muestra "10" y el texto "最短10日で 収益化条件達成". Haz que toda la tipografía sea extragrande, con relieve y optimizada para la legibilidad en miniaturas, con contornos gruesos, perspectiva fuerte y superposiciones. Ambiente general: emocionante, promesa de altos ingresos, amigable para principiantes, miniatura energética para tutoriales de monetización en redes sociales japonesas.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="Miniatura de YouTube - Miniatura para monetización en X (Japón) - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fuente:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14497)**

---

### No. 60: Miniatura de YouTube - Miniatura explosiva para monetización en X (Japón)

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una miniatura de marketing al estilo anime japonés de alta energía para redes sociales o promociones de YouTube sobre monetización rápida en X y ofertas de bonificación.

#### 📝 Prompt

```
Crea una miniatura de YouTube japonesa llamativa con un estilo de marketing anime de alto impacto, formato horizontal 16:9, repleta de efectos de energía verde neón, destellos dorados, líneas de velocidad, destellos de lente y sombras paralelas negras gruesas. La composición está dividida con un texto promocional audaz que domina la izquierda y el centro, y un lindo chico anime chibi a la derecha señalando directamente al espectador con una sonrisa entusiasta. Tiene el cabello castaño oscuro alborotado con mechones de color {argument name="accent hair color" default="verde neón"}, ojos grandes de color verde brillante, rubor suave en las mejillas y viste una sudadera con capucha negra sobre una chaqueta con ribete verde y una camisa naranja debajo. Utiliza un renderizado cel-shaded brillante, contornos nítidos, alto contraste y una profundidad exagerada para lograr un aspecto de miniatura de redes sociales que invite a hacer clic. En la parte superior, coloca una cinta roja curva con ribete dorado y un icono de caja de regalo a la izquierda; dentro de la cinta, coloca el titular en japonés {argument name="top banner text" default="無料10大特典プレゼント"} en letras blancas y amarillas en negrita. En el área central izquierda, coloca un texto gigante en japonés con un estilo 3D dramático y degradados metálicos: un "10" dorado gigante, un "日で" blanco, una "X" verde neón masiva, luego "収益化" en blanco plateado y "達成" en naranja dorado, que se lea exactamente como {argument name="main headline" default="10日でX収益化達成"}. Rodea este titular con flechas verdes hacia arriba, destellos de estrellas y efectos de luz explosivos. Añade 4 iconos flotantes estilo plataforma alrededor del área del titular: 1 icono rosa tipo red social con un corazón blanco, 1 icono de burbuja de chat azul con una silueta de usuario blanca, 1 smartphone negro inclinado que muestra el logotipo de X en blanco y 1 pila de monedas de oro con una moneda con el símbolo del yen al frente. A lo largo de la parte inferior, coloca 3 cajas de características de color verde brillante alineadas horizontalmente, cada una con un icono distintivo y texto en japonés: la caja 1 tiene un icono de marca para principiantes y el texto {argument name="feature text 1" default="X初心者でも簡単収益化"}, la caja 2 tiene un icono de reloj y el texto "1日1時間の作業でOK", y la caja 3 tiene un icono de calendario y el texto "最短10日で収益化条件達成". En la parte inferior derecha, añade un botón de llamada a la acción grande, rojo y brillante con un borde blanco resplandeciente, el texto en japonés {argument name="button text" default="今すぐ受け取る"}, un triángulo de reproducción blanco en el lado derecho del botón y un cursor de mano haciendo clic cerca del borde inferior derecho. Toda la imagen debe sentirse explosiva, urgente y optimizada para una alta tasa de clics, utilizando verdes saturados, rojos, dorados, sombras negras y reflejos metálicos.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="Miniatura de YouTube - Miniatura explosiva para monetización en X (Japón) - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fuente:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14496)**

---

### No. 61: Miniatura de YouTube - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 Prompt

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="Miniatura de YouTube - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **Fuente:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14150)**

---

### No. 62: Miniatura de YouTube - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 Prompt

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="Miniatura de YouTube - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [結パパ](https://x.com/Yuupapa_free)
- **Fuente:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14230)**

---

### No. 63: Miniatura de YouTube - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="Miniatura de YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fuente:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14242)**

---

### No. 64: Miniatura de YouTube - Pastel Pink VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="Miniatura de YouTube - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fuente:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14238)**

---

### No. 65: Miniatura de YouTube - Anime VTuber Livestream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="Miniatura de YouTube - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fuente:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14231)**

---

### No. 66: Miniatura de YouTube - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="Miniatura de YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fuente:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14227)**

---

### No. 67: Miniatura de YouTube - Generador de miniaturas para seminarios web en japonés

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt para crear miniaturas profesionales de seminarios web en japonés en formato 16:9 con tipografía clara y texto destacado.

#### 📝 Prompt

```
Crea una {argument name="thumbnail type" default="miniatura de seminario web"} en japonés de alta calidad. {argument name="aspect ratio" default="formato panorámico 16:9"}. Hay mucho texto, pero el mensaje principal destaca claramente.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="Miniatura de YouTube - Generador de miniaturas para seminarios web en japonés - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [KAWAI](https://x.com/kawai_design)
- **Fuente:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13978)**

---

### No. 68: Miniatura de YouTube - Miniatura para stream de debut de VTuber

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera un horario de stream mágico y rico en tipografía o una miniatura de debut para un VTuber.

#### 📝 Prompt

```
{
  "type": "Miniatura para stream de debut de VTuber",
  "character": {
    "appearance": "chica anime, cabello largo morado oscuro, ojos morados, blusa blanca con volantes, pajarita morada oscura, lazo grande en el cabello",
    "pose": "dedo en los labios, expresión tierna",
    "props": "micrófono de condensador con filtro antipop y cinta morada a la derecha"
  },
  "background": "noche estrellada mágica, destellos, mariposas brillantes, paleta de colores morado y blanco",
  "layout": {
    "typography": [
      {
        "position": "arriba a la izquierda",
        "style": "texto grande en negrita con cursiva en inglés arriba",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "Primer Stream",
        "subtext_2": "¡Encantada de conocerlos! ¡Soy Shisaki Lily!"
      },
      {
        "position": "centro a la izquierda",
        "style": "caja decorativa",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "abajo a la izquierda",
        "style": "estilo de logotipo",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "arriba a la derecha",
        "style": "texto vertical",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "abajo a la derecha",
        "style": "forma de píldora decorativa",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ INICIO ✦"
      }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="Miniatura de YouTube - Miniatura para stream de debut de VTuber - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [WTR](https://x.com/wtry1102)
- **Fuente:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13943)**

---

### No. 69: Miniatura de YouTube - Miniatura de infoproducto en dorado y negro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera un banner promocional llamativo y cargado de texto o una miniatura de YouTube que presenta a un sujeto seguro de sí mismo y múltiples llamadas a la acción estructuradas.

#### 📝 Prompt

```
{
  "type": "banner promocional / miniatura de YouTube",
  "style": "alto contraste, llamativo, profesional, paleta de {argument name=\"theme color\" default=\"dorado y negro\"}, rayos de luz brillantes, partículas centelleantes",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"joven asiático seguro de sí mismo con traje oscuro y brazos cruzados\"}",
    "pose": "mirando hacia arriba a la derecha",
    "props": "portátil abierto brillante frente a él"
  },
  "layout": {
    "background": "oscuro con estallidos de luz dorada radiante",
    "text_sections": {
      "top_left_badge": "[Edición definitiva]",
      "top_header": "{argument name=\"top text\" default=\"¡Empieza hoy incluso desde cero! ¡Obtén el poder de ganar dinero con IA de la forma más rápida!\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"Guía completa de trabajos secundarios con IA\"}",
        "style": "tipografía 3D grande, en negrita, dorada y blanca"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"100k al mes incluso para principiantes\"}",
      "top_right_badge": {
        "style": "corona de laurel dorada",
        "text": "Edición 2026"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "cajas apiladas con borde dorado",
        "labels": ["Monetización rápida", "Con ejemplos concretos", "Fácil para todos"]
      },
      "middle_right_ribbon": {
        "style": "cinta roja",
        "text": "Explicación paso a paso"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "rejilla de 2x3 de cajas con borde dorado",
        "labels": ["Herramientas recomendadas", "Flujo de monetización claro", "Cómo empezar sin fallar", "Minimiza el tiempo de trabajo", "Incluye plantillas", "Método fácil de replicar"]
      },
      "bottom_footer": "¡Gana dinero sin dudas! El libro de texto de trabajos secundarios con IA",
      "bottom_right_badge": {
        "style": "corona de laurel dorada",
        "text": "Incluye plantillas"
      }
    }
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="Miniatura de YouTube - Miniatura de infoproducto en dorado y negro - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **Fuente:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13903)**

---

### No. 70: Cómic / Guion gráfico - Manga cálido de 4 paneles para parejas casadas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un cómic japonés suave y romántico de cuatro paneles que celebra a una pareja casada, ideal para publicaciones en redes sociales, ilustraciones conmemorativas o arte manga con temática de relaciones.

#### 📝 Prompt

```
{"type":"ilustración de manga romántico de 4 paneles","style":"arte lineal de anime limpio dibujado a mano con una paleta monocromática cálida en beige y marrón claro, fondo crema suave, sombreado simple, atmósfera acogedora y gentil, estética de publicación para redes sociales","format":"diseño de cómic cuadrado de 2x2 con bordes de panel delgados en color marrón","headline":{"text":"{argument name=\"headline text\" default=\"Día de la pareja\"}","position":"top center","decorations":{"count":2,"items":["pequeño corazón a la izquierda","pequeño corazón a la derecha"]}},"panels":[{"panel":1,"count":2,"scene":"retrato de pie de una pareja joven","composition":"el hombre está detrás de la mujer con una mano en su hombro, ambos luciendo tranquilos y cariñosos","characters":[{"role":"hombre","appearance":"cabello castaño claro desordenado, gafas, sudadera con capucha color crema, alto y delgado"},{"role":"mujer","appearance":"cabello castaño claro en un moño bajo suelto con mechones enmarcando el rostro, camisa blanca de manga larga, chaleco de suéter marrón cálido, correa de bolso visible"}],"text":["¡Hoy es","el día de la pareja!"],"decorations":{"count":3,"items":["pequeño corazón","pequeño corazón","pequeño corazón"]}},{"panel":2,"count":2,"scene":"la pareja sentada junta en el interior sosteniendo tazas y sonriéndose el uno al otro","characters":[{"role":"hombre","appearance":"mismas gafas y sudadera, sosteniendo una taza verde apagado"},{"role":"mujer","appearance":"mismo peinado y atuendo, sosteniendo una taza clara"}],"speech_bubble":{"speaker":"hombre","text":"Gracias por todo. Estar juntos es mi mayor felicidad."}},{"panel":3,"count":2,"scene":"la pareja cocinando junta en una cocina, ambos revolviendo una sartén en la estufa","background":"estantes simples y planta en maceta con detalles suaves y esquemáticos","characters":[{"role":"hombre","appearance":"mismas gafas y sudadera"},{"role":"mujer","appearance":"mismo peinado de moño y atuendo en capas"}],"speech_bubble":{"speaker":"hombre","text":"De ahora en adelante, sigamos riendo, apoyándonos y viendo muchos paisajes juntos."}},{"panel":4,"count":2,"scene":"abrazo cariñoso cercano, el hombre besa a la mujer en la frente mientras sostiene su hombro","characters":[{"role":"hombre","appearance":"mismas gafas y sudadera"},{"role":"mujer","appearance":"mismo cabello y atuendo, apoyándose en él"}],"speech_bubble":{"speaker":"hombre","text":"Te amo. ¡Sigamos así de bien!"},"decorations":{"count":3,"items":["pequeño corazón","pequeño corazón","pequeño corazón"]}}],"footer":{"text":"{argument name=\"footer text\" default=\"Gracias por estar siempre a mi lado.\"}","position":"bottom center","decorations":{"count":1,"items":["pequeño corazón"]}},"character_design":{"count":2,"items":[{"role":"esposo","hair color":"{argument name=\"hair color\" default=\"castaño claro\"}","expression":"amable, gentil, cariñoso"},{"role":"esposa","hair color":"{argument name=\"hair color\" default=\"castaño claro\"}","expression":"sonrisa suave, amorosa, ligeramente tímida"}]},"rendering_notes":"mantener todo el texto escrito a mano en japonés, usar mucho espacio en blanco, preservar un estado de ánimo conmemorativo dulce para una publicación de agradecimiento a la pareja, hacer que el trazo sea ligeramente suelto y esquemático en lugar de tinta pulida"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="Cómic / Guion gráfico - Manga cálido de 4 paneles para parejas casadas - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Fuente:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14492)**

---

### No. 71: Cómic / Guion gráfico - Página de demostración de manga con IA en japonés

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una pulida página de manga anime de cuatro viñetas que muestra a personajes de chicas gato reaccionando a diálogos en japonés renderizados de forma impresionante, ideal para exhibir la calidad del texto en cómics generados por IA.

#### 📝 Prompt

```
{
  "type": "página de manga anime de cuatro viñetas",
  "style": "ilustración de anime limpia y pulida, iluminación interior cálida, globos de diálogo en japonés vertical altamente legibles, sombreado suave, encuadre de cómic expresivo, fondo detallado de sala de estar acogedora, interior en tonos beige y marrón claro, suelo de madera, sofá, mesa de centro, tazas, planta pequeña, arte de pared enmarcado",
  "format": {
    "page_orientation": "vertical",
    "panel_count": 4,
    "reading_flow": "arriba a la izquierda, arriba a la derecha, medio ancho, inferior ancho",
    "borders": "bordes de viñeta de manga gruesos y negros"
  },
  "characters": [
    {
      "id": "chica gato azul",
      "appearance": "pequeña chica gato chibi con cabello corto estilo bob de color {argument name="hair color" default="azul"}, ahoge, orejas de gato con pelaje interior blanco, cola esponjosa con punta blanca, ojos grandes color ámbar-azul, boca pequeña con colmillos",
      "outfit": "suéter naranja sobre una camisa blanca de cuello con ribete azul, falda marrón con cinturón de lazo, pasador de pelo amarillo en forma de X"
    },
    {
      "id": "chica gato dorada",
      "appearance": "chica gato enérgica con cabello largo y ondulado rubio dorado, orejas de gato, cola esponjosa, expresión alegre y brillante",
      "outfit": "suéter de punto trenzado color amarillo mostaza, falda de cuadros marrón oscuro"
    },
    {
      "id": "mujer de cabello blanco",
      "appearance": "mujer hermosa con cabello largo blanco, orejas de gato blancas, piel bronceada, ojos dorados, sonrisa tranquila y segura",
      "outfit": "chaqueta blanca sobre un top negro, collares y pendientes dorados en capas"
    },
    {
      "id": "mujer sirvienta",
      "appearance": "mujer adulta con cabello largo rubio claro y orejas de gato",
      "outfit": "vestido de sirvienta blanco y negro con tocado de volantes blanco y un lazo rojo"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "viñeta 1",
        "position": "arriba a la izquierda",
        "count": 1,
        "labels": ["どうせ日本語微妙なんでしょ？文字がダメなら認めないよ"],
        "scene": "la chica gato azul está sentada en un sofá en una sala de estar acogedora, con un dedo en la barbilla, luciendo escéptica y curiosa, un pequeño signo de interrogación flota sobre su cabeza"
      },
      {
        "title": "viñeta 2",
        "position": "arriba a la derecha",
        "count": 1,
        "labels": ["ねぇねぇ！GPT Image2 すごいよ！"],
        "scene": "la chica gato dorada irrumpe dramáticamente a través de una puerta con líneas de velocidad irradiando detrás de ella, con los brazos abiertos de par en par, llena de emoción"
      },
      {
        "title": "viñeta 3",
        "position": "medio ancho",
        "count": 3,
        "labels": ["うわっ びっくりした！めちゃくちゃキレイじゃん！", "ねぇねぇ！GPT Image2 すごいよ！ 微妙なんでしょ？ 文字がダメなら認めないよ", "ほら見て！わたしたちのセリフ！"],
        "scene": "la chica gato azul reacciona con sorpresa con ambas manos cerca de su rostro, la chica gato dorada se para a su lado y señala con orgullo, y un gran globo de diálogo central muestra el ejemplo de diálogo en japonés que están discutiendo"
      },
      {
        "title": "viñeta 4",
        "position": "inferior ancho",
        "count": 3,
        "labels": ["進化が早すぎてもう驚かないよね〜", "絵も可愛く描けてるし文字の白抜きも完璧よね", ""],
        "scene": "en primer plano, la mujer sirvienta se cubre la boca con asombro, mientras la mujer de cabello blanco comenta pensativa con una mano cerca de la barbilla; al fondo, la chica gato azul y la chica gato dorada saltan felices juntas para celebrar frente al sofá"
      }
    ]
  },
  "text_handling": {
    "language": "japonés",
    "balloon_direction": "diseño de texto vertical",
    "emphasis": "hacer que la tipografía japonesa sea nítida, natural y perfectamente integrada en los globos de diálogo del manga, incluyendo texto con borde blanco donde sea necesario"
  },
  "tone": "juguetón, festivo, impresionado por la alta calidad del renderizado de texto en japonés en manga generado por IA",
  "quality": "alto detalle, diseños de personajes coherentes, cómic promocional lindo y legible"
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="Cómic / Guion gráfico - Página de demostración de manga con IA en japonés - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **Fuente:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14471)**

---

### No. 72: Cómic / Guion gráfico - Hoja de 4 paneles de una elegante espadachina de anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una ilustración de personaje de anime de cuatro paneles altamente detallada de una noble espadachina de cabello blanco, ideal para arte clave de fantasía, exhibiciones de personajes o publicaciones premium en redes sociales.

#### 📝 Prompt

```
Una pulida hoja de ilustración de fantasía estilo anime en una cuadrícula de 2x2 que muestra a la misma elegante espadachina en 4 paneles. El personaje es una joven con cabello largo de color blanco platino recogido en una coleta alta con grandes lazos de cinta azul marino profundo, rizos suaves y sueltos con mechones fluidos, piel pálida y rasgos delicados y refinados con ojos luminosos de color rojo rosado. Viste un ornamentado vestido aristocrático gótico en blanco y azul marino: una blusa blanca de cuello alto con volantes, adornos de encaje y bordados dorados, un gran lazo azul marino en el pecho con un broche de joya roja, mangas abullonadas con puños de cinta, un corsé azul oscuro en la cintura con detalles dorados y una voluminosa falda azul marino decorada con patrones florales dorados, volantes en capas y brillo satinado. Lleva una katana enfundada con empuñadura oscura y detalles dorados. El panel 1 es un retrato de primer plano desde el pecho hacia arriba, ligeramente de lado, con el cabello brillando bajo una dramática luz de contorno sobre un fondo nocturno oscuro y brillante. El panel 2 es una toma de acción dinámica de la parte superior del cuerpo, con el personaje desenvainando o presentando la espada horizontalmente hacia el espectador, el cabello ondeando salvajemente, con un efecto bokeh cinematográfico de ciudad nocturna y pétalos brillantes a su alrededor. El panel 3 es un retrato de cuerpo completo, de pie con gracia en un salón reflectante y luminoso enmarcado por altas estructuras brillantes, mostrando la silueta completa del vestido, zapatos de tacón con lazos y la espada a su lado. El panel 4 es una vista de tres cuartos desde atrás junto a un océano resplandeciente al atardecer o al amanecer, con el personaje mirando por encima del hombro, un cielo pastel cálido y agua brillante detrás, con pétalos de cerezo flotando en la brisa. Utiliza renderizado de anime ultra detallado, calidad de portada de novela ligera premium, texturas de tela intrincadas, reflejos brillantes, ornamentación dorada, efecto de resplandor suave, retroiluminación dramática, pétalos flotantes, partículas brillantes, atmósfera romántica elegante y una armonía de colores cohesiva en azul marino, blanco, dorado y rosa rubor.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="Cómic / Guion gráfico - Hoja de 4 paneles de una elegante espadachina de anime - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **Fuente:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14413)**

---

### No. 73: Cómic / Guion gráfico - Enfrentamiento de countryballs en el estrecho de Ormuz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una ilustración humorística de un meme geopolítico que muestra a las countryballs de EE. UU. e Irán enfrentándose en el estrecho de Ormuz, ideal para sátira editorial o comentarios en redes sociales.

#### 📝 Prompt

```
Una detallada ilustración satírica de un meme de countryballs del {argument name="waterway name" default="estrecho de Ormuz"} como un paso marítimo muy estrecho entre dos acantilados rocosos escarpados, pintado en un estilo de dibujos animados digital pulido con sombreado dramático y piedra texturizada. En el centro del primer plano, exactamente 2 countryballs se bloquean mutuamente en el estrecho canal de modo que solo una puede pasar. A la izquierda, una countryball de EE. UU. con ojos entrecerrados de enfado, pintada con la bandera estadounidense y usando una gorra de béisbol azul marino con la etiqueta "USA" en letras blancas grandes. A la derecha, una countryball de Irán con ojos entrecerrados de enfado, pintada con la bandera y el emblema iraníes, usando una cinta verde y blanca atada a un lado; la cinta contiene texto en coreano que dice "저항은 우리의 권리". Sobre cada bola hay exactamente 1 globo de diálogo blanco con un borde negro grueso, para un total de 2 globos de diálogo, y ambos dicen {argument name="speech text" default="길!"} en letras coreanas grandes y negritas, como si ninguna de las partes fuera a ceder. Muestra a las dos bolas enfrentadas nariz con nariz en un estancamiento en el cuello de botella. En el acantilado izquierdo, incluye exactamente 1 letrero de madera que diga en coreano e inglés: "호르무즈 해협" y "Strait of Hormuz". En el acantilado derecho, incluye exactamente 1 señal de advertencia con texto en persa en la parte superior y un triángulo de advertencia rojo debajo, indicando que solo una persona puede pasar. En la esquina inferior izquierda, coloca exactamente 1 barril de petróleo negro etiquetado como "OIL" con petróleo oscuro derramado acumulándose a su alrededor. En la esquina inferior derecha, coloca exactamente 1 mina naval negra con escritura en persa, unida a una cadena. En el fondo, más allá del estrecho paso, muestra mar abierto con exactamente 3 barcos distantes, incluido al menos 1 petrolero más grande y un tenue humo oscuro elevándose hacia el cielo. Utiliza un tono de meme geopolítico tenso pero humorístico, composición centrada, vista a la altura de los ojos, luz diurna suave, colores realistas ligeramente apagados, contornos nítidos y alta legibilidad para todo el texto.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="Cómic / Guion gráfico - Enfrentamiento de countryballs en el estrecho de Ormuz - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Fuente:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14683)**

---

### No. 74: Cómic / Guion gráfico - Pose de victoria del hechicero con los ojos vendados

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un póster de acción de anime vertical y dramático de un hechicero de cabello blanco con los ojos vendados, con energía azul explosiva y un llamativo globo de texto de manga, ideal para arte de personajes estilizado o visuales inspirados en el fandom.

#### 📝 Prompt

```
Una ilustración de anime shonen de alto impacto que muestra a un poderoso hechicero de cabello blanco en una pose dramática de cuerpo completo desde un ángulo contrapicado, riendo con la cabeza echada hacia atrás y la boca abierta, vistiendo un elegante uniforme negro de cuello alto y una venda negra sobre los ojos. Su mano izquierda está extendida hacia el espectador haciendo el signo de la victoria con dos dedos, con un fuerte escorzo que hace que la mano se vea grande en primer plano, mientras que su brazo derecho cuelga hacia un lado. Rodéalo con energía sobrenatural explosiva de color {argument name="energy color" default="azul eléctrico"}, estelas de aura similares a pinceladas violentas, escombros voladores, chispas y rayas curvas que atraviesan el encuadre. El fondo debe ser una explosión de energía oscura, abstracta y caótica con fragmentos azules brillantes y líneas de movimiento, creando una sensación de poder abrumador. Utiliza un renderizado de anime con cel-shading audaz con reflejos pictóricos, líneas nítidas, contraste intenso y pliegues de tela brillantes en el atuendo negro. En el lado derecho, añade 1 gran globo de texto de manga blanco y dentado con un borde negro grueso que contenga el texto {argument name="speech bubble text" default="¡LOS LUDITAS SIEMPRE PIERDEN!"} en letras mayúsculas negras grandes y desgastadas. Composición vertical, encuadre de póster de acción dinámica, actitud triunfante y segura, estética de anime de fantasía oscura moderna.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="Cómic / Guion gráfico - Pose de victoria del hechicero con los ojos vendados - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Fuente:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14637)**

---

### No. 75: Cómic / Guion gráfico - Página de manga de comedia sobre los baños públicos lunares

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una página de cómic anime retro-futurista que representa un caprichoso sento en la luna, ideal para generar escenas de manga con IA lúdicas con múltiples viñetas centradas en los personajes.

#### 📝 Prompt

```
Una colorida página de manga japonés ambientada en un caprichoso baño público lunar en la luna, dibujada en un pulido estilo anime retro-futurista con iluminación cálida, bordes de viñeta gruesos y limpios, efectos de sonido expresivos y una narrativa ambiental muy detallada. La escena es un onsen lunar llamado "月面銭湯 つきのゆ" con un gran letrero de entrada iluminado, una cortina noren azul con el carácter blanco "ゆ", tuberías expuestas, medidores, arquitectura redondeada y una ventana circular gigante que muestra la superficie lunar y la Tierra en el espacio. Incluye exactamente 8 viñetas de cómic dispuestas en un diseño de página dinámico. Viñeta 1: plano general exterior del baño en la luna, con el letrero "月面銭湯 つきのゆ", un letrero más pequeño que dice "重力 1/6", una máquina expendedora de leche roja etiquetada como "牛乳", una estatua de tanuki, terreno lunar en el exterior y una pancarta vertical que promociona el baño. Viñeta 2: una joven mecánica que trabaja en el baño con {argument name="character design" default="coleta castaña atada con un pañuelo de lunares rojos, mono de trabajo verde, cinturón de herramientas, expresión enérgica"} ajusta una máquina o el control de la caldera, vista desde atrás o de lado, con globos de texto sobre la preparación del baño de hoy y el estado de la caldera. Viñeta 3: un lindo cliente alienígena con {argument name="alien appearance" default="cuerpo redondo verde menta, manchas moradas, ojos soñolientos, mejillas rosadas, boca pequeña, toalla blanca con una estrella morada en la cabeza"} se relaja en el agua humeante del baño, medio sumergido, con un patito de goma flotando cerca y un letrero de madera que dice "ぬるめ じっくり リラックス". Viñeta 4: un pequeño robot de limpieza con {argument name="robot design" default="cuerpo plateado, detalles azules, cara digital negra con ojos azules brillantes, luz de antena roja, brazos y piernas mecánicos delgados"} friega felizmente el suelo con una escoba y un cubo junto a un letrero colgante que dice "清掃中". Viñeta 5: el mismo robot resbala de repente o salpica dramáticamente en el baño, con un gran estallido de agua, muchas burbujas, el gran efecto de sonido "ぽわぁ〜ん!!" y la trabajadora reaccionando con sorpresa desde un lado. Viñeta 6: la trabajadora se sienta junto al baño sonriendo, sosteniendo una botella etiquetada como "月面牛乳". Viñeta 7: el alienígena en el baño levanta el pulgar mientras sostiene una botella etiquetada como "月面フルーツオーレ", luciendo felizmente satisfecho, con el patito de goma todavía presente. Viñeta 8: el alegre robot posa junto al baño con herramientas de limpieza y un cubo, cerca de una cortina de baño marcada con "ゆ" y un lavabo rosa etiquetado como "つきのゆ", diciendo que el baño es lo mejor. Mantén un tono acogedor y cómico, detalles de sento al estilo Showa retro mezclados con tecnología espacial, superficies de baño de azulejos brillantes, vapor, burbujas y una linda actuación de los personajes en todo momento. El cómic debe sentirse como un encantador manga de comedia de la vida cotidiana sobre trabajar en un baño lunar.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga de comedia sobre los baños públicos lunares - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **Fuente:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14697)**

---

### No. 76: Cómic / Guion gráfico - Hoja de referencia de diseño de personajes

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una hoja de diseño completa para un personaje específico, incluyendo información clave y referencias visuales.

#### 📝 Prompt

```
Crea una hoja de diseño de personaje para {argument name="character" default="Hermes Agent"}, con información clave
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="Cómic / Guion gráfico - Hoja de referencia de diseño de personajes - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Neo](https://x.com/NeoAIForecast)
- **Fuente:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14324)**

---

### No. 77: Cómic / Guion gráfico - Página de cómic independiente

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Crea un diseño de cómic con un estilo independiente moderno adaptado a historias infantiles.

#### 📝 Prompt

```
Una página de un cómic con el estilo de {argument name="comic style" default="cómic independiente moderno"} sobre el tema: {argument name="story topic" default="una historia para niños de 6 años"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="Cómic / Guion gráfico - Página de cómic independiente - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [宝玉](https://x.com/dotey)
- **Fuente:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14310)**

---

### No. 78: Cómic / Guion gráfico - Página de manga shonen a color

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt narrativo detallado para generar una página de manga con aspecto físico, incluyendo detalles específicos de personajes y marcas.

#### 📝 Prompt

```
Crea una página de muestra de un {argument name="manga type" default="manga de aventuras shonen japonés a color"}. La página debe representar vívidamente a nuestro personaje principal encontrando una {argument name="item" default="pluma mágica"}. El nombre de la pluma es la {argument name="item name" default="Quill of GPT Image"}. Haz que sea dramático. La pluma mágica tiene un gran poder sellado en su interior.

Instrucciones adicionales: Relación de aspecto: Vertical 1440x2560. La pluma debe tener el logotipo de OpenAI. El idioma en todo el manga debe ser japonés. Piensa detenidamente primero para que sea una buena historia con una buena distribución de viñetas de manga. La página debe aparecer como una fotografía de una página física, no como una página digital.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga shonen a color - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [宝玉](https://x.com/dotey)
- **Fuente:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14311)**

---

### No. 79: Cómic / Guion gráfico - Página de manga de comedia romántica de cuatro paneles

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera una página de manga monocromática de cuatro paneles con diálogos en japonés, ideal para crear escenas de debate dramáticas de comedia romántica con una actuación de personajes expresiva.

#### 📝 Prompt

```
Crea una página de manga en blanco y negro con 4 paneles horizontales apilados, espacios entre paneles limpios, sombreado con tramas (screentone), líneas de velocidad dramáticas y un trazo pulido al estilo seinen. La página presenta a dos personajes de anime jóvenes con ropa casual moderna y cabello corto oscuro, con el área del rostro de ambos personajes oscurecida por un bloque de censura cuadrado y difuminado. Panel 1: una persona joven y delgada con cabello corto y oscuro desordenado y una camisa con cuello aprieta un puño cerca de su pecho, con el cuerpo inclinado hacia la izquierda, rodeado por un intenso efecto de aura de fuego en el fondo, luciendo emocional y a la defensiva. En el lado derecho, coloca un gran globo de diálogo vertical irregular que contenga este texto en japonés: 「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」. Panel 2: una segunda persona joven de complexión ligeramente más alta, cabello corto oscuro, una chaqueta oscura con cremallera sobre una camisa clara, levanta un dedo índice con calma como si estuviera explicando un punto. Añade un cuadro de diálogo rectangular redondeado a la derecha con este texto en japonés: 「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」. Panel 3: el personaje más alto da palmaditas suaves en la cabeza del personaje más bajo; incluye un pequeño efecto de sonido de palmadita cerca de la mano que diga 「ポン」. El personaje más bajo mira hacia arriba con sorpresa. En el lado derecho, añade un gran globo de diálogo vertical ovalado con este texto en japonés: 「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」. Panel 4: primer plano del personaje más bajo sonrojándose intensamente con ojos en espiral, gotas de sudor, expresión temblorosa, boca abierta y sombreado denso en las mejillas, abrumado por la vergüenza. Llena el fondo con dramáticas líneas de velocidad radiantes. Añade un gran globo de diálogo vertical irregular a la derecha con este texto en japonés: 「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」. Añade dos efectos de sonido: un pequeño 「プル…」 cerca del hombro y un 「カァァァ」 más grande, tembloroso y escrito a mano a lo largo de la parte inferior izquierda. Mantén toda la página monocromática, con un tono de manga de comedia romántica altamente expresivo y un fuerte contraste emocional entre la discusión acalorada, la explicación fría, el afecto burlón y el desenlace avergonzado.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga de comedia romántica de cuatro paneles - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Fuente:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14468)**

---

### No. 80: Cómic / Guion gráfico - Hoja de referencia del personaje Velvedia

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt corto para generar una hoja de referencia de personaje para un personaje de estilo mecha llamado Velvedia.

#### 📝 Prompt

```
{argument name="character name" default="Velvedia"} hoja de referencia
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="Cómic / Guion gráfico - Hoja de referencia del personaje Velvedia - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="Cómic / Guion gráfico - Hoja de referencia del personaje Velvedia - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **Fuente:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14368)**

---

### No. 81: Cómic / Guion gráfico - Promoción de manga de 8 paneles para GPT-Image-2

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una página de cómic de ocho paneles al estilo manga en blanco y negro para anunciar y explicar GPT-Image-2 en un formato promocional ideal para redes sociales.

#### 📝 Prompt

```
{"type":"página de cómic promocional estilo manga de 8 paneles","theme":"anuncio de lanzamiento de GPT-Image-2","language":"español","style":{"rendering":"manga en blanco y negro con sombreado de tramas, líneas de velocidad, reflejos brillantes, contornos entintados llamativos, acabado de cómic digital limpio","mood":"emocionante, informativo, optimista, orientado a la tecnología","page_format":"página única dividida en 8 paneles rectangulares en una cuadrícula de 2 columnas por 4 filas con márgenes delgados"},"characters":[{"id":"chica presentadora","role":"presentadora principal","appearance":"linda chica anime con cabello largo y oscuro, ojos grandes y expresivos, vistiendo una sudadera oscura con el logo del nudo de OpenAI en el pecho","count":1},{"id":"robot mascota","role":"mascota asistente amigable","appearance":"pequeño robot redondo con pantalla facial negra, ojos brillantes, cuerpo blanco simple, brazos diminutos, expresión alegre","count":1},{"id":"grupo de creadores","role":"ejemplos de audiencia","appearance":"4 jóvenes creadores diferentes: un diseñador, un desarrollador sosteniendo una tableta, un fotógrafo con cámara, una persona con computadora portátil/sudadera","count":4}],"layout":{"sections":[{"title":"¡YA LLEGÓ! GPT-IMAGE-2","position":"arriba a la izquierda","count":1,"description":"panel dramático de presentación con la chica anime extendiendo una mano hacia el espectador, líneas de velocidad radiantes detrás de ella","text":["¡YA LLEGÓ!","GPT-IMAGE-2","¡LA NUEVA GENERACIÓN DE IMÁGENES POR IA DE OPENAI!","¡MÁS CREATIVIDAD, MÁS PRECISIÓN, MÁS POSIBILIDADES!"]},{"title":"¿QUÉ ES GPT-IMAGE-2?","position":"arriba a la derecha","count":1,"description":"chica en pose de medio cuerpo señalando hacia arriba junto a un icono de imagen brillante sobre un fondo tecnológico estrellado","text":["¿QUÉ ES GPT-IMAGE-2?","¡Es nuestro nuevo modelo de generación de imágenes, más inteligente, más fiel a lo que imaginas y con una calidad sorprendente!"]},{"title":"MÁS REALISMO. MÁS DETALLES.","position":"medio a la izquierda fila 2","count":1,"description":"panel comparativo que muestra 2 imágenes de paisajes lado a lado, ambas escenas de lagos de montaña, la izquierda etiquetada como modelo anterior y la derecha como modelo nuevo con mayor realismo","subsections":[{"label":"ANTES (DALL·E 3)","count":1},{"label":"AHORA (GPT-IMAGE-2)","count":1}],"text":["MÁS REALISMO. MÁS DETALLES.","ANTES (DALL·E 3)","AHORA (GPT-IMAGE-2)","¡TEXTURAS MÁS RICAS, LUZ MÁS NATURAL, DETALLES INCREÍBLES!"]},{"title":"MEJOR COMPRENSIÓN, MEJORES RESULTADOS.","position":"medio a la derecha fila 2","count":1,"description":"chica juntando las manos junto a un ejemplo de prompt enmarcado y el robot mascota señalando hacia arriba","text":["MEJOR COMPRENSIÓN, MEJORES RESULTADOS.","¡GPT-IMAGE-2 entiende mejor objetos, textos, composiciones e instrucciones complejas!","EJEMPLO DE PROMPT:","\"Una cafetería futurista en la cima de una montaña nevada al atardecer, con un letrero de neón ‘CAFÉ DEL MAÑANA’ y personas tomando café.\""]},{"title":"CREATIVIDAD SIN LÍMITES.","position":"abajo a la izquierda fila 3","count":1,"description":"chica hablando junto a una muestra de 4 variantes de arte generadas","subsections":[{"label":"escena de castillo gótico","count":1},{"label":"calle de ciudad moderna de noche","count":1},{"label":"retrato de personaje anime","count":1},{"label":"composición geométrica abstracta","count":1}],"text":["CREATIVIDAD SIN LÍMITES.","Desde estilos artísticos hasta diseños profesionales, de lo realista a lo abstracto: ¡tus ideas, a tu manera!"]},{"title":"¿TEXTO EN LA IMAGEN? ¡AHORA ES MUCHO MEJOR!","position":"abajo a la derecha fila 3","count":1,"description":"robot mascota presentando una comparación de antes y después de la tipografía de un póster con una flecha llamativa entre los dos diseños","subsections":[{"label":"ANTES","count":1},{"label":"AHORA","count":1}],"text":["¿TEXTO EN LA IMAGEN? ¡AHORA ES MUCHO MEJOR!","¡Generación de texto más precisa, legible e integrada al diseño!","ANTES","AHORA","AVENTURA COMIENZA AQUÍ","LA AVENTURA COMIENZA AQUÍ"]},{"title":"PARA TODOS LOS CREADORES.","position":"abajo a la izquierda","count":1,"description":"foto grupal con la chica presentadora y 4 creadores de pie lado a lado, representando diferentes profesiones","text":["PARA TODOS LOS CREADORES.","Diseñadores, desarrolladores, educadores, especialistas en marketing, artistas y curiosos: ¡todo el mundo puede crear más y mejor!"]},{"title":"¡GPT-IMAGE-2 YA ESTÁ DISPONIBLE!","position":"abajo a la derecha","count":1,"description":"panel final de héroe con la chica guiñando un ojo y haciendo un gesto de pulgar hacia arriba, robot mascota a su lado, rayos brillantes de celebración y destellos","text":["¡GPT-IMAGE-2 YA ESTÁ DISPONIBLE!","IMAGINA. CREA. INSPIRA.","EL FUTURO DE LA CREACIÓN ES AHORA. ❤"]}],"panel_count":8},"composition":{"reading_order":"de izquierda a derecha, de arriba a abajo","camera_variety":"mezcla de primeros planos, planos medios de presentadores, gráficos comparativos y foto grupal","graphic_elements":["bocadillos de diálogo","banderas de título negras redondeadas con letras blancas en mayúsculas","destellos","líneas de velocidad","fondo tecnológico estrellado","flechas de comparación","tarjetas de ejemplo enmarcadas"]},"text_style":"letras de cómic en mayúsculas en español, encabezados llamativos, bocadillos de diálogo claros, híbrido de infografía y cómic promocional","quality":"póster de cómic editorial de alta resolución, tipografía nítida, espaciado de paneles equilibrado, fuerte contraste","prompt":"Crea una página de cómic promocional estilo manga en escala de grises de 8 paneles anunciando {argument name=\"product name\" default=\"GPT-IMAGE-2\"}. Usa un diseño de página única de 2 columnas por 4 filas con exactamente 8 paneles distintos y texto en español en todo el contenido. Incluye una chica presentadora anime alegre con cabello largo de color {argument name=\"hair color\" default=\"castaño oscuro\"}, una sudadera oscura con el logo de OpenAI y un pequeño robot mascota amigable. Panel 1: revelación dramática del lanzamiento, chica extendiendo la mano hacia la cámara, líneas de velocidad radiales, titular \"¡YA LLEGÓ! {argument name=\"headline name\" default=\"GPT-IMAGE-2\"}\" y texto de lanzamiento sobre una nueva generación de imágenes por IA. Panel 2: panel explicativo con la chica señalando junto a un icono de imagen brillante sobre un fondo digital estrellado, título \"¿QUÉ ES GPT-IMAGE-2?\" y un bocadillo de diálogo describiéndolo como un modelo de generación de imágenes más inteligente. Panel 3: comparación de realismo con exactamente 2 paisajes de lagos de montaña lado a lado etiquetados como \"ANTES (DALL·E 3)\" y \"AHORA (GPT-IMAGE-2)\". Panel 4: panel de mejor comprensión con la chica y el robot, incluye un ejemplo de prompt enmarcado usando {argument name=\"example prompt\" default=\"Una cafetería futurista en la cima de una montaña nevada al atardecer, con un letrero de neón ‘CAFÉ DEL MAÑANA’ y personas tomando café.\"}. Panel 5: muestra de creatividad con exactamente 4 miniaturas: castillo gótico, ciudad de noche, retrato anime, arte geométrico abstracto. Panel 6: comparación de renderizado de texto con exactamente 2 variantes de póster etiquetadas como \"ANTES\" y \"AHORA\", mostrando tipografía mejorada y la frase \"LA AVENTURA COMIENZA AQUÍ\" frente a una versión corregida más limpia. Panel 7: panel de audiencia con exactamente 4 creadores de diferentes campos juntos. Panel 8: llamada a la acción final de celebración con la chica guiñando un ojo y haciendo pulgar hacia arriba, robot mascota animando, y el eslogan final {argument name=\"closing slogan\" default=\"IMAGINA. CREA. INSPIRA.\"}. Haz que la página sea enérgica, pulida, altamente legible, con barras de encabezado negras llamativas, letras blancas en mayúsculas, bocadillos de diálogo, destellos, sombreado de tramas y una estética sólida de póster promocional de manga/cómic."}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="Cómic / Guion gráfico - Promoción de manga de 8 paneles para GPT-Image-2 - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Diogo Santos](https://x.com/diogosantosbr)
- **Fuente:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14639)**

---

### No. 82: Cómic / Guion gráfico - Confrontación en la oficina: manga con censura

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Una página de manga monocromática y cruda que muestra una acalorada discusión de oficina que se transforma en una escena de kabedon, ideal para recrear capturas de pantalla dramáticas al estilo manga viral.

#### 📝 Prompt

```
Una página de manga dramática en blanco y negro con estilo seinen, renderizada con tramas densas, líneas de tinta nítidas, iluminación de alto contraste y un diseño de cómic japonés expresivo. La página cuenta con 4 paneles apilados con globos de texto verticales en japonés y efectos de sonido llamativos, mostrando una tensa confrontación entre dos trabajadores de oficina en un espacio de trabajo moderno. En el panel superior, una mujer joven con un corte bob corto y despeinado, complexión delgada pero curvilínea, vistiendo una blusa ajustada con mangas remangadas y una falda lápiz oscura, golpea un escritorio con fuerza por la ira, inclinándose hacia adelante con líneas de impacto explosivas y un gran globo de texto irregular. En el segundo panel, un joven con cabello oscuro y alborotado, complexión delgada, vistiendo una chaqueta de cuero negra sobre una camisa clara y un collar, se muestra de pecho hacia arriba en una pose tranquila y segura, tocándose la cara mientras habla. En el tercer panel, el hombre acorrala a la mujer contra una pared en una pose íntima de kabedon, con un brazo apoyado junto a su cabeza; ella se ve nerviosa y tensa mientras él habla cerca de su rostro, creando un cambio repentino de tono hacia la comedia romántica. En el panel inferior, una vista cenital revela el entorno de la oficina: 2 personajes de pie cerca de un escritorio con 1 monitor de computadora, 1 teclado, 1 mouse, 1 silla de oficina y papeles esparcidos sobre un suelo de baldosas; la mujer está encogida tímidamente y temblando mientras el hombre permanece relajado a su lado. Incluye exactamente 4 paneles, exactamente 4 globos de texto visibles en total y tipografía de manga japonesa visible en toda la página. Añade un desenfoque de mosaico rectangular sobre el rostro de cada personaje en todos los paneles, como si estuvieran anonimizados para compartir en línea. Los detalles del fondo deben incluir paredes de oficina, bordes de escritorio, líneas de velocidad, efectos de ráfaga y degradados tonales. La sensación general es la de una discusión intensa que se convierte en un coqueteo manipulador, como una captura de pantalla de manga viral fuera de contexto.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="Cómic / Guion gráfico - Confrontación en la oficina: manga con censura - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Fuente:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14477)**

---

### No. 83: Cómic / Guion gráfico - Manga de Quantum Cat

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt creativo y breve para generar una viñeta de manga protagonizada por un gato que exhibe comportamientos de física cuántica.

#### 📝 Prompt

```
Por favor, dibuja un manga donde un {argument name="subject" default="gato"} {argument name="concept" default="se comporte como una partícula cuántica"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="Cómic / Guion gráfico - Manga de Quantum Cat - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Haruhiko Okumura](https://x.com/h_okumura)
- **Fuente:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14348)**

---

### No. 84: Cómic / Guion gráfico - Página de manga de oficina con una linda chica oveja

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una página de manga de oficina de fantasía en tonos pastel de cuatro paneles que muestra a una oficinista con cuernos de oveja y una oveja esponjosa convirtiendo el papeleo en una escena cómica, acogedora y somnolienta.

#### 📝 Prompt

```
{"type":"página de manga de cuatro paneles","style":"anime chibi en tonos pastel suaves, paleta de colores beige cálido y crema, luz de mañana suave, bordes de panel redondeados, diálogos en japonés claros y legibles, estilo de vida de oficina de fantasía cómica y acogedora","page":{"orientation":"vertical","panel_count":4,"gutter":"espaciado blanco fino","border":"contornos marrones redondeados"},"setting":{"location":"interior de una pequeña oficina de gestión","details":["suelo de madera","ventana iluminada por el sol","escritorio con papeles","sillas de madera","estanterías llenas de archivos y libros","cajas apiladas y suministros de oficina","motas de polvo suaves y destellos en la luz"]},"characters":[{"role":"personaje principal","appearance":"pequeña oficinista chibi con forma de oveja, cabello rubio corto y esponjoso estilo bob, un ojo azul y un ojo ámbar, orejas pequeñas tipo elfo, grandes cuernos de carnero curvados, capucha de oveja esponjosa con forma de cara de oveja, blusa blanca, corbata roja, vestido con delantal rosa pálido, pequeño bolígrafo en el bolsillo del delantal"},{"role":"personaje secundario","appearance":"oveja blanca redonda y esponjosa con cara pequeña y patas cortas, muy afelpada y parecida a una nube"}],"layout":{"sections":[{"title":"panel 1","position":"superior","count":3,"labels":["la chica oveja abre la puerta de la oficina y mira hacia adentro","pequeña oveja asomándose a su lado","un globo de diálogo ovalado a la izquierda y un pequeño globo ovalado a la derecha"]},{"title":"panel 2","position":"parte superior central","count":3,"labels":["la chica oveja de pie junto a un escritorio con una mano en la cadera y la otra señalando documentos","pequeña oveja sentada junto al escritorio","un único globo de diálogo ovalado grande a la izquierda"]},{"title":"panel 3","position":"parte inferior central","count":3,"labels":["oveja esponjosa durmiendo extendida sobre el papeleo","primer plano parcial de la chica oveja asomándose desde la parte superior izquierda con expresión cansada","texto de efecto de sonido de sueño en morado a la derecha"]},{"title":"panel 4","position":"inferior","count":4,"labels":["la chica oveja dormida en el escritorio con los ojos cerrados y una leve sonrisa","oveja esponjosa durmiendo a su lado sobre el papeleo","luz solar cálida entrando desde la ventana de la izquierda","pequeño cuadro de texto rectangular en la parte inferior derecha"]}]},"text":{"language":"japonés","elements":[{"kind":"globo de diálogo","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"globo de diálogo","panel":1,"text":"メェ"},{"kind":"globo de diálogo","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"globo de diálogo","panel":3,"text":"…名簿が もふもふに…"},{"kind":"efecto de sonido","panel":3,"text":"Zzz…"},{"kind":"globo de diálogo","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"pie de foto","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"mantener los cuatro paneles en la misma oficina para mantener la continuidad; enfatizar las expresiones faciales lindas, las texturas esponjosas y el chiste de que el trabajo de oficina se detiene porque la oveja y la oficinista se quedan dormidas juntas sobre el papeleo; hacer que los documentos sean claramente visibles en los paneles 2 a 4; preservar un tono tranquilo, somnoliento y reconfortante"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga de oficina con una linda chica oveja - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga de oficina con una linda chica oveja - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="Cómic / Guion gráfico - Página de manga de oficina con una linda chica oveja - Image 3">
</div>

#### 📌 Detalles

- **Autor:** [じょにがたロボ](https://x.com/jonigata_ai)
- **Fuente:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14532)**

---

### No. 85: Cómic / Guion gráfico - Adorable cómic de cuatro viñetas sobre celos gatunos

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt genera un cálido cómic de cuatro viñetas dibujado a mano, ideal para publicaciones en redes sociales, humor al estilo manga o ilustraciones acogedoras de mascotas.

#### 📝 Prompt

```
Un adorable cómic de cuatro viñetas dibujado a mano con un estilo de vida cotidiano, suave y cálido sobre un fondo crema claro, con bordes de viñeta negros gruesos y una textura de papel ligeramente granulada. Utiliza una anatomía de gato de dibujos animados simple y redondeada, rostros expresivos, contornos negros limpios, colores naturales apagados y una presentación suave tipo manga. En la viñeta superior izquierda, muestra 2 gatos: un gato atigrado marrón con rayas oscuras y hocico blanco sentado con los ojos cerrados, luciendo complacido, mientras un gato mayoritariamente blanco con manchas de color marrón oscuro en la cabeza está a su lado y lame cariñosamente la mejilla del atigrado; añade 2 pequeñas notas musicales negras sobre ellos para sugerir un aseo feliz. En la viñeta superior derecha, muestra al gato de manchas blancas y marrones en primer plano mirando hacia un pequeño gatito calicó que está de pie a la derecha; incluye un globo de texto con el texto en japonés "めい" sobre el gatito. En la viñeta inferior izquierda, muestra a 3 gatos juntos: el atigrado marrón a la izquierda con una expresión de sorpresa o inexpresiva, el gato de manchas blancas a la derecha luciendo alegre y el pequeño gatito calicó centrado al frente entre ellos, mirando hacia arriba. En la viñeta inferior derecha, muestra un primer plano del gato atigrado marrón solo, mirando hacia adelante con ojos de color verde amarillento entrecerrados y una expresión de enojo y celos; añade 2 líneas de énfasis cortas cerca del rostro y 1 pequeño símbolo de enojo en forma de nube a la derecha. Mantén un tono acogedor y cómico, con el chiste visual de que el gato atigrado estaba feliz siendo acicalado hasta que aparece el nuevo gatito. Utiliza colores planos, sombreado mínimo y una encantadora sensación de webcómic japonés.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="Cómic / Guion gráfico - Adorable cómic de cuatro viñetas sobre celos gatunos - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Maoku](https://x.com/Maoku)
- **Fuente:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14503)**

---

### No. 86: Cómic / Guion gráfico - Página de cómic de Moon Mark Adventure

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una página de cómic de anime de fantasía de cuatro paneles que muestra a una chica de pelo plateado con temática lunar descubriendo un mapa, resolviendo un rompecabezas en una cueva y encontrando una invitación mágica para la siguiente aventura.

#### 📝 Prompt

```
{"type":"página de cómic de anime de cuatro paneles","style":"ilustración de manga de fantasía estilo lindo, renderizado de anime pulido gpt-image-2, colores vibrantes, líneas limpias, sombreado suave tipo pintura, atmósfera mágica y caprichosa","page":{"background":"página blanca con bordes de panel negros","title":"{argument name=\"headline text\" default=\"La gran aventura de la marca lunar\"}","title_position":"parte superior central","decorations":["pequeños destellos dorados alrededor del título","icono de luna creciente a la derecha del título"],"panel_count":4,"reading_direction":"de arriba a abajo"},"character":{"appearance":"joven aventurera de anime con cabello plateado ondulado muy largo, piel pálida, ojos grandes y expresivos, complexión delgada","outfit":["vestido de fantasía en blanco y negro con ribetes de volantes","adorno de luna creciente en el cabello","gargantilla de luna creciente","mangas descubiertas","mochila de cuero marrón","medias oscuras hasta el muslo"],"theme":"motivo lunar en todo el vestuario y accesorios"},"panels":[{"position":"superior","scene":"sendero de montaña soleado y pradera bajo un cielo azul con nubes, bosque a la derecha, camino sinuoso a lo lejos, señal de madera a la izquierda","action":"la chica está de pie sosteniendo y leyendo un viejo mapa del tesoro, mirando hacia adelante","props":["mapa antiguo","señal de madera","mochila"],"text":{"sign":"El inicio de la aventura","speech":"{argument name=\"panel 1 speech\" default=\"¡He encontrado el mapa! ¡Hoy comienza una gran aventura!\"}"}},{"position":"centro-superior","scene":"entrada de ruinas selváticas con una oscura abertura de cueva enmarcada por antiguos pilares de piedra tallados con símbolos de media luna y cubiertos de enredaderas","action":"vista trasera de tres cuartos de la chica acercándose con cuidado mientras lee el mapa","props":["mapa","entrada de la cueva en ruinas","plantas densas"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"¡El tesoro debería estar más adelante...!\"}","sound_effect":"Susurro"}},{"position":"centro-inferior","scene":"dentro de las ruinas de la cueva, con poca luz, altar de piedra o mesa de rompecabezas en el centro","action":"la chica se arrodilla junto a una linterna encendida y extiende la mano hacia un mecanismo de rompecabezas en lugar de una cerradura cercana, mientras una mascota redonda parecida a un gato negro observa","props":["linterna que emite luz cálida","losa de piedra con símbolo circular grabado","pequeña llave dorada sobre la mesa","criatura de gato negro con marca de luna creciente y collar de cuentas"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"¡No es una llave, tengo que resolver el mecanismo!\"}","sound_effect":"¡Brillo!"}},{"position":"inferior","scene":"cámara del tesoro con cristales incrustados en las paredes de la cueva y destellos flotantes","action":"la chica sonríe alegremente con los ojos cerrados junto a un cofre del tesoro abierto, sosteniendo una tarjeta de invitación de papel","props":["cofre del tesoro de madera abierto con emblema de luna creciente","brújula brillante dentro del cofre","tarjeta de papel que dice Hacia la siguiente aventura","cristales azules y morados"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"¡El tesoro es... una invitación a la siguiente aventura!\"}","tag":"¿Continuará?"}}]}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="Cómic / Guion gráfico - Página de cómic de Moon Mark Adventure - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ツバサ天九](https://x.com/wing_sky_nine)
- **Fuente:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14605)**

---

### No. 87: Marketing de producto - Identidad de marca y tablero de merchandising de personaje de anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera un tablero de diseño de marca integral que presenta un personaje de anime, incluyendo empaques de productos, maquetas para redes sociales y diseños de merchandising.

#### 📝 Prompt

```
{
  "type": "tablero de diseño de identidad de marca y merchandising",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"rosa pastel\"} y blanco",
    "motif": "{argument name=\"motif\" default=\"flores de cerezo\"} y corazones rosas"
  },
  "character": {
    "description": "chica anime con corte bob castaño, ojos rosas, vistiendo una sudadera con capucha blanca, sonrisa amable"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "banner de encabezado",
        "position": "superior",
        "elements": ["logotipo principal grande", "sublogotipo", "gráficos de flores de cerezo", "retrato del personaje a la derecha"]
      },
      {
        "type": "empaque de producto",
        "position": "centro izquierda",
        "elements": ["1 caja cuadrada con ventana transparente en forma de corazón que muestra dulces de corazón rosas", "ilustración del personaje en la caja", "2 envoltorios de dulces individuales", "5 dulces de corazón dispersos"]
      },
      {
        "type": "póster promocional",
        "position": "centro derecha",
        "elements": ["retrato del personaje", "tazón de dulces en forma de corazón", "logotipo principal", "texto '4.26 NEW OPEN'", "texto '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "banner web horizontal",
        "position": "centro inferior",
        "elements": ["logotipo principal", "flores de cerezo", "retrato del personaje a la derecha"]
      },
      {
        "type": "maqueta de perfil de redes sociales",
        "position": "abajo izquierda",
        "elements": ["imagen de encabezado con logotipo", "1 foto de perfil circular", "usuario '{argument name=\"social handle\" default=\"@yuonchii\"}'", "1 botón de seguir", "texto de biografía de muestra"]
      },
      {
        "type": "colección de merchandising",
        "position": "abajo derecha",
        "count": 9,
        "items": ["1 camiseta blanca con logotipo", "1 taza blanca con el personaje", "4 pines redondos", "1 llavero acrílico", "2 paquetes de dulces"]
      }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="Marketing de producto - Identidad de marca y tablero de merchandising de personaje de anime - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **Fuente:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13547)**

---

### No. 88: Marketing de producto - Página de aterrizaje de estudio de caso de marketing viral en modo oscuro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una maqueta de interfaz de usuario integral con temática oscura para un estudio de caso de marketing, que incluye visualizaciones de datos, cronogramas e ilustraciones en 3D.

#### 📝 Prompt

```
{
  "type": "diseño de interfaz de página de aterrizaje",
  "theme": "modo oscuro, tecnología moderna, {argument name=\"primary accent color\" default=\"neón púrpura\"} y acentos azules brillantes, glassmorphism",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "badge": "ESTUDIO DE CASO DE CAMPAÑA VIRAL"
  },
  "sections": [
    {
      "id": "hero",
      "layout": "diseño dividido, texto a la izquierda, imagen a la derecha",
      "content": {
        "badge": "ESTUDIO DE CASO",
        "headline": "{argument name=\"hero headline\" default=\"Cómo creamos un impacto viral de más de 10 millones\"}",
        "subtitle": "3 días para encender la red, ayudando a las marcas a lograr un crecimiento exponencial",
        "stats_row": {
          "count": 4,
          "labels": ["Vistas totales {argument name=\"main metric\" default=\"10,240,000+\"}", "Tasa de interacción 18.7%", "Conversiones 3,200+", "Tiempo de ejecución 72 horas"]
        },
        "hero_image": "toma cinematográfica de una persona en una habitación oscura mirando pantallas de video flotantes brillantes, superposición de botón de reproducción grande"
      }
    },
    {
      "id": "strategy",
      "title": "DESGLOSE DE LA CAMPAÑA: Nuestra estrategia de ejecución de 3 días",
      "layout": "cronograma vertical con 3 pasos",
      "steps": [
        {"step": 1, "title": "Formulación de la estrategia", "image": "personas analizando datos en una pantalla"},
        {"step": 2, "title": "Producción de contenido", "image": "interfaz de edición de video"},
        {"step": 3, "title": "Distribución y amplificación", "image": "mano sosteniendo un teléfono inteligente con iconos de redes sociales"}
      ]
    },
    {
      "id": "performance",
      "title": "RESULTADOS DE RENDIMIENTO: Rendimiento basado en datos",
      "layout": "cuadrícula de tarjetas de estadísticas a la izquierda, gráficos a la derecha",
      "left_stats": {
        "count": 4,
        "labels": ["Exposición total 10M+", "Caída promedio del CPM 43%", "Nuevos seguidores 28,000+", "Conversiones 3,200+"]
      },
      "right_charts": {
        "count": 2,
        "items": [
          "gráfico de líneas que muestra la tendencia de 7 días alcanzando su punto máximo en el día 3 con 8,320,000",
          "gráfico de barras horizontales que muestra la distribución por plataforma: TikTok 52%, Instagram 24%, X 15%, YouTube 9%"
        ]
      }
    },
    {
      "id": "keys_to_success",
      "title": "POR QUÉ SE HIZO VIRAL: Las 3 claves del éxito viral",
      "layout": "fila horizontal de 3 tarjetas",
      "cards": [
        {"icon": "fuego", "title": "Diseño de gancho emocional"},
        {"icon": "diana", "title": "Diseño de estructura de contenido"},
        {"icon": "antena", "title": "Ejecución de la estrategia de distribución"}
      ]
    },
    {
      "id": "social_proof",
      "title": "CONFIANZA DE CREADORES Y MARCAS: Todos usan goViralX para lograr crecimiento",
      "layout": "diseño dividido, logotipos a la izquierda, testimonios a la derecha",
      "left_logos": {
        "count": 8,
        "labels": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
      },
      "right_testimonials": {
        "count": 2,
        "labels": ["Cita de fundador de SaaS", "Cita de gerente de crecimiento"]
      }
    },
    {
      "id": "cta",
      "title": "¿LISTO PARA HACERTE VIRAL?: ¿Quieres obtener el mismo efecto de crecimiento?",
      "layout": "texto y campo de entrada a la izquierda, ilustración 3D a la derecha",
      "elements": [
        "campo de entrada con texto de marcador de posición",
        "botón: {argument name=\"call to action text\" default=\"Obtener plan de crecimiento exclusivo ->\"}"
      ],
      "image": "cohete 3D brillante en colores púrpura y azul despegando"
    }
  ],
  "footer": "logotipo y texto de derechos de autor"
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="Marketing de producto - Página de aterrizaje de estudio de caso de marketing viral en modo oscuro - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [开发者Hailey](https://x.com/IndieDevHailey)
- **Fuente:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13769)**

---

### No. 89: Marketing de producto - Documento de identidad de marca de mascota de 18 paneles

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Una guía de marca integral de 18 secciones y hoja de diseño de personajes para una mascota en 3D, que detalla todo, desde moodboards y arte lineal hasta vistas de giro en 3D y maquetas físicas.

#### 📝 Prompt

```
{
  "type": "documento de identidad de marca y diseño de personajes de 18 paneles",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"MUYANG TEA\"}",
    "industry": "{argument name=\"industry\" default=\"tienda de té\"}",
    "colors": ["{argument name=\"primary color\" default=\"amarillo\"}", "{argument name=\"secondary color\" default=\"verde\"}", "blanco", "marrón", "verde oscuro"]
  },
  "subject": "{argument name=\"character description\" default=\"mascota Shiba Inu adorable renderizada en 3D con un delantal verde\"}",
  "layout": {
    "grid": "3 columnas por 6 filas",
    "sections": [
      {
        "title": "01 ANÁLISIS DE ADN DE MARCA / BRAND DNA ANALYSIS",
        "elements": ["logotipo", "5 muestras de color", "6 iconos", "gráficos de público objetivo"]
      },
      {
        "title": "02 MOODBOARD CONCEPTUAL / CONCEPT MOODBOARD",
        "elements": ["5 referencias fotográficas", "4 iconos de estilo", "ecuación de diseño"]
      },
      {
        "title": "03 ESTUDIO DE FORMA / FORM STUDY",
        "elements": ["4 iconos de anatomía del logotipo", "4 pasos de evolución", "4 siluetas"]
      },
      {
        "title": "04 EXPLORACIÓN CONCEPTUAL / CONCEPT EXPLORATION",
        "elements": ["12 bocetos de personajes en arte lineal"]
      },
      {
        "title": "05 ARTE LINEAL REFINADO / REFINED LINE ART",
        "elements": ["3 filas de arte lineal frontal y lateral con guías de proporción"]
      },
      {
        "title": "06 REFINAMIENTO DE DETALLES / DETAIL REFINEMENT",
        "elements": ["2 renders de cuerpo completo con etiquetas", "4 acercamientos circulares"]
      },
      {
        "title": "07 HOJA DE EXPRESIONES / EXPRESSION SHEET",
        "elements": ["11 expresiones faciales renderizadas en 3D"]
      },
      {
        "title": "08 BIBLIOTECA DE POSES / POSE LIBRARY",
        "elements": ["9 poses de cuerpo completo renderizadas en 3D"]
      },
      {
        "title": "09 VISTA DE GIRO / TURNAROUND VIEW",
        "elements": ["5 renders 3D de cuerpo completo", "5 vistas de arte lineal correspondientes"]
      },
      {
        "title": "10 DESARROLLO DE COLOR / COLOR DEVELOPMENT",
        "elements": ["5 filas de paletas de 5 colores", "texto de psicología del color"]
      },
      {
        "title": "11 ESPECIFICACIÓN DE MATERIALES / MATERIAL SPECIFICATION",
        "elements": ["5 muestras de textura", "deslizadores de propiedades", "4 iconos de fabricación"]
      },
      {
        "title": "12 APLICACIÓN DE COLOR / COLOR APPLICATION",
        "elements": ["4 renders de variantes de color", "2 renders de luz/sombra", "4 círculos de calificación de contraste"]
      },
      {
        "title": "13 GUÍA DE CONSTRUCCIÓN / CONSTRUCTION GUIDE",
        "elements": ["2 diagramas de arte lineal para geometría y cuadrícula"]
      },
      {
        "title": "14 REGLAS DEL SISTEMA DE DISEÑO / DESIGN SYSTEM RULES",
        "elements": ["iconos de tamaño mínimo", "diagrama de espacio libre", "4 ejemplos de uso"]
      },
      {
        "title": "15 VARIANTES DE ACTIVOS / ASSET VARIANTS",
        "elements": ["3 variantes de tamaño", "3 variantes de arte lineal", "3 cabezas planas simplificadas"]
      },
      {
        "title": "16 APLICACIONES DIGITALES / DIGITAL APPLICATIONS",
        "elements": ["1 icono de aplicación", "2 avatares para redes sociales", "elementos de interfaz de usuario (UI)", "ciclo de animación de 3 pasos"]
      },
      {
        "title": "17 APLICACIONES FÍSICAS / PHYSICAL APPLICATIONS",
        "elements": ["maqueta de peluche", "maqueta de empaque", "maqueta de mercancía", "maqueta de escaparate"]
      },
      {
        "title": "18 RENDERIZADO FINAL / FINAL RENDERING",
        "elements": ["render 3D grande de alta resolución de la mascota sosteniendo té", "logotipo", "lista de formatos de archivo"]
      }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="Marketing de producto - Documento de identidad de marca de mascota de 18 paneles - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Lee Colin](https://x.com/Colin_Leeee)
- **Fuente:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **Publicado:** 16 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13819)**

---

### No. 90: Marketing de producto - Póster publicitario de juego de samuráis estilo anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Un llamativo anuncio vertical para juegos móviles que presenta a dos espadachines con traje, un mecha samurái gigante, interfaz de juego (UI), código QR y avisos de descarga de la tienda de aplicaciones para promoción.

#### 📝 Prompt

```
Crea un póster publicitario vertical de alto impacto para un juego móvil con un estilo de acción anime brillante, una estética dramática de fantasía ciber-samurái y una composición promocional densa y premium de tipo gacha-RPG. La escena principal muestra a 2 jóvenes combatientes masculinos con trajes de negocios negros modernos agachados agresivamente en primer plano, cada uno desenvainando una katana hacia el espectador. Ambos tienen cabello rubio estilizado, rasgos afilados y atractivos, camisas blancas, corbatas azules y poses de acción intensas, con manos y espadas en escorzo dominando la parte inferior del primer plano. Una espada tiene una cinta azul atada cerca de la empuñadura. Detrás de ellos, centrado y majestuoso, coloca 1 enorme mecha samurái blindado con cuernos dorados ornamentados, armadura metálica azul y negra en capas, ojos azules brillantes y una espada enfundada en la espalda, enmarcado como una deidad guardiana. Utiliza un fondo de ciudad de neón vívido y ráfagas de energía en azul eléctrico, violeta, magenta y dorado, con estelas de luz, chispas, pétalos, efectos de corte y texturas de explosión de pincel de tinta. Añade 1 estandarte vertical de pincelada negra en la parte superior derecha con texto japonés en negrita que diga 「この刃で、未来を斬り拓け。」. En la zona central inferior, coloca 1 enorme titular de caligrafía japonesa dorada con textura de pincel grueso y sombra negra que diga 「切り捨て御免」, abarcando casi todo el ancho. En la parte inferior izquierda, inserta 1 panel enmarcado de captura de pantalla del juego con un borde dorado, que muestre una batalla nocturna frente al patio de un templo japonés rojo, 1 espadachín jugable en combate, múltiples enemigos, números de daño flotantes que incluyan 5324, 5329 y 6132, un joystick virtual a la izquierda, 5 retratos de personajes dispuestos verticalmente y a lo largo de la parte inferior, 3 botones de habilidad circulares a la derecha y un HUD superior que muestre un temporizador alrededor de 01:28 y WAVE 3/3. En la parte inferior derecha, coloca 1 código QR grande en blanco y negro dentro de un marco cuadrado blanco. Debajo y al lado, añade texto japonés en negrita en blanco con contorno azul que diga 「今すぐダウンロード」. En la parte inferior, incluye 2 insignias de tienda de estilo oficial: App Store a la izquierda y Google Play a la derecha. Aspecto general: ultra detallado, arte promocional pulido, perspectiva dinámica, reflejos metálicos, renderizado de anime cel-shaded nítido, póster de marketing de juego móvil premium, energía de acción intensa, iluminación cinematográfica y diseño promocional con mucha interfaz de usuario.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="Marketing de producto - Póster publicitario de juego de samuráis estilo anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="Marketing de producto - Póster publicitario de juego de samuráis estilo anime - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="Marketing de producto - Póster publicitario de juego de samuráis estilo anime - Image 3">
</div>

#### 📌 Detalles

- **Autor:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **Fuente:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14432)**

---

### No. 91: Marketing de producto - Tablero de Kit de Marca Monochrome Infra

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un tablero de presentación de mercancía y directrices de marca en blanco y negro, limpio y profesional, para una marca ficticia de tecnología de infraestructura; ideal para presentaciones de venta (pitch decks), exhibiciones de marca y maquetas de diseño profesional.

#### 📝 Prompt

```
{"type":"tablero de presentación de kit de marca y merchandising monocromático","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"Respaldamos a los constructores que crean la infraestructura fundamental para la era de la IA.","campaign_line":"[ CONSTRUYENDO LO QUE VIENE. DESDE CERO. ]","version":"VERSIÓN 1.0"},"style":{"overall":"hoja de directrices de marca limpia inspirada en el estilo suizo, estética tecnológica industrial minimalista, solo blanco, negro y gris, fondo de papel blanco roto, recortes de producto de estudio nítidos, sombras sutiles, diseño de cuadrícula preciso, presentación editorial","mood":"profesional, premium, futurista, enfocado en infraestructura"},"layout":{"header":{"left":"A16Z INFRA / KIT DE MARCA Y SWAG","right":"VERSIÓN 1.0","divider":"línea horizontal discontinua"},"sections":[{"title":"01 IDENTIDAD","position":"arriba a la izquierda","count":3,"labels":["logotipo grande","párrafo de declaración de marca","línea de campaña entre corchetes"]},{"title":"02 PALETA","position":"arriba a la derecha","count":4,"labels":["BLANCO ROTO CÁLIDO","NEGRO","CARBON","GRIS MATE"]},{"title":"03 TIPOGRAFÍA","position":"arriba a la derecha debajo de la paleta","count":2,"labels":["PRIMARIA -- MONOESPACIADA","SECUNDARIA -- SANS SERIF"]},{"title":"06 SWAG","position":"dos tercios inferiores","count":16,"labels":["sudadera con capucha negra frente","sudadera con capucha negra espalda","camiseta color blanco roto","gorra de béisbol negra","bolsa de tela color blanco roto","set de 6 pegatinas/tarjetas cuadradas","cuaderno de espiral negro","taza negra","botella de agua negra","estuche con cremallera negro","dispositivo de juego retro portátil","caja de micro-construcciones","estuche de kit de teclado abierto","pin de icono de nube","pin de cubos apilados","pin de parche rectangular de marca"]}],"footer":{"left":"A16Z INFRA / KIT DE MARCA","right":"© 2024 A16Z INFRA. TODOS LOS DERECHOS RESERVADOS.","divider":"línea horizontal discontinua"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"logotipo de bloque geométrico personalizado muy grande con cortes angulares, letras negras pesadas, apilado en dos líneas"}},"palette":{"swatches":[{"name":"BLANCO ROTO CÁLIDO","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"NEGRO","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"CARBON","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"GRIS MATE","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"PRIMARIA -- MONOESPACIADA","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"SECUNDARIA -- SANS SERIF","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}},"swag":{"items":[{"name":"sudadera frente","color":"negro","print":"logotipo pequeño en el pecho"},{"name":"sudadera espalda","color":"negro","print":"lista de manifiesto de varias líneas que dice CONSTRUYENDO LA CAPA DE INFRAESTRUCTURA DE LA IA con líneas guía punteadas y categorías que incluyen SISTEMAS, HERRAMIENTAS, DATOS, NUBE, SEGURIDAD, REDES, HERRAMIENTAS DE DESARROLLADOR"},{"name":"camiseta","color":"blanco roto","print":"logotipo grande centrado"},{"name":"gorra de béisbol","color":"negro","print":"logotipo bordado en el frente"},{"name":"bolsa de tela","color":"blanco roto","print":"lista de manifiesto apilada y línea inferior CONSTRUYENDO LO QUE VIENE."},{"name":"set de pegatinas/tarjetas","count":6,"layout":"cuadrícula de 2 por 3","labels":["A16Z INFRA","CONSTRUYENDO LA CAPA DE INFRAESTRUCTURA DE LA IA.","ETAPA INICIAL","SISTEMAS. HERRAMIENTAS. PLATAFORMAS.","INFRA","CONSTRUIR","DESPLEGAR","ESCALAR"]},{"name":"cuaderno de espiral","color":"negro","print":"logotipo más NOTAS PARA CONSTRUIR EL FUTURO"},{"name":"taza","color":"negro","print":"logotipo blanco"},{"name":"botella de agua","color":"negro","print":"texto vertical CONSTRUYENDO LO QUE VIENE. DESDE CERO."},{"name":"estuche con cremallera","color":"negro","print":"logotipo, motivo de cuadrícula punteada, texto pequeño SISTEMAS EN LÍNEA."},{"name":"dispositivo retro portátil","color":"negro carbón","screen":"pantalla de juego de infraestructura/ciudad en pixel-art con pestañas CONSTRUIR DESPLEGAR ESCALAR e indicador de nivel NIVEL 01"},{"name":"caja de micro-construcciones","color":"negro","print":"A16Z INFRA, MICRO CONSTRUCCIONES DE INFRAESTRUCTURA, COLECCIONA.CONECTA.ESCALA.","contents":"pequeños modelos de bloques de construcción modulares en negro, gris y blanco mostrados frente a la caja"},{"name":"estuche de kit de teclado","color":"negro","print":"SET DE TECLADO A16Z INFRA CONSTRUIR. DESPLEGAR. ESCALAR.","keys":8,"labels":["INFRA","CONSTRUIR","DESPLEGAR","ESCALAR",">_","icono de nube","icono de chip/cuadrícula","icono de diagrama de red"]},{"name":"pin de nube","style":"insignia pequeña de esmalte negro con borde blanco"},{"name":"pin de cubos","style":"insignia pequeña de esmalte negro que muestra cubos isométricos apilados"},{"name":"pin de parche de marca","style":"insignia pequeña rectangular de esmalte negro con logotipo blanco"}]},"rendering":{"camera":"plano cenital directo combinado con composición de tablero de producto ortográfico","lighting":"iluminación de estudio suave y uniforme","background":"hoja de color blanco roto cálido","quality":"maqueta comercial de alta resolución adecuada para presentaciones de marca profesionales"}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="Marketing de producto - Tablero de Kit de Marca Monochrome Infra - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Olivier Sauvage](https://x.com/Capitaine)
- **Fuente:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14563)**

---

### No. 92: Marketing de producto - Póster publicitario de parodia de bebida de arroz coreana

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un póster publicitario de bebida de parodia humorístico y de alto impacto que presenta a un portavoz con apariencia de político famoso promocionando una bebida de arroz coreana en lata.

#### 📝 Prompt

```
Crea un póster publicitario de bebidas al estilo coreano, audaz, con un fondo de salpicaduras doradas cálidas y una iluminación comercial dramática. Muestra a un {argument name="celebrity spokesperson" default="político mayor con apariencia de Donald Trump"} desde el pecho hacia arriba, vistiendo un traje azul marino, camisa blanca, corbata roja brillante y un pequeño pin de la bandera estadounidense en la solapa, mirando a la cámara con una expresión de vendedor seguro de sí mismo. Su rostro está oculto por un bloque de censura rectangular plano de color piel. En su mano izquierda, extendida cerca de la cámara en perspectiva forzada, sostiene una lata de aluminio amarilla de bebida de arroz coreana (sikhye) etiquetada prominentemente en coreano, con bandas rojas en la parte superior e inferior y el texto principal del producto "비락 식혜" y "Since 1993" en la lata. La lata también incluye texto coreano más pequeño, una imagen de la bebida de arroz dulce cerca de la base y el texto de volumen "238 ml (120 kcal)". Su mano derecha hace un gesto de pulgar hacia arriba.

Utiliza una composición comercial retro y enérgica, con la bebida de arroz dulce salpicando y gotas detrás de él, reflejos dorados brillantes y un encuadre heroico en ángulo ligeramente bajo. En la parte superior, incluye 3 grupos de texto de titular distintos: un pequeño eslogan negro estilo manuscrito en la parte superior izquierda que dice "전통의 맛, 한국의 DRINK!", un titular central enorme en tipografía coreana negrita desgastada que dice "걸죽는 땐?" en marrón oscuro-negro y "비락 식혜!" en rojo vivo, y un logotipo de marca en la parte superior derecha que dice "비락" con un pequeño texto rojo "Since 1993" debajo. Añade 2 insignias de llamada a la acción: a la izquierda, un sello circular amarillo con un pequeño icono de corona y el texto "대한민국 국민음료 No.1"; a la derecha, un globo de texto blanco con texto coreano escrito a mano "한국이 만든 맛있는 전통!" y texto en inglés rojo "I LOVE IT!".

En la parte inferior del primer plano, coloca 2 elementos de comida: un cuenco de latón lleno de bebida de arroz dulce con granos de arroz flotando a la izquierda, y un cuenco de madera lleno de arroz blanco a la derecha. En la parte central inferior, añade 2 líneas de texto promocional grande estilo pincel, la primera en blanco que dice "달콤하게! 시원하게!" y la segunda en blanco y amarillo que dice "속까지 시~원하게!" con un trazo subrayado amarillo enérgico. A lo largo de la parte inferior, incluye 3 iconos circulares de características con leyendas en coreano: "국내산 쌀 엄선된 재료", "시원하게 갈증해소" y "부드러운 단맛 속 편한 식혜". En la esquina inferior derecha, añade un pequeño texto de exención de responsabilidad "연출된 이미지입니다". Haz que el aspecto general sea brillante, exagerado, divertido y convincente, como un anuncio impreso de parodia viral.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="Marketing de producto - Póster publicitario de parodia de bebida de arroz coreana - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Fuente:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14555)**

---

### No. 93: Marketing de producto - Póster publicitario de bebida deportiva coreana con celebridad

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un llamativo póster de bebida hidratante al estilo coreano con un portavoz tipo celebridad, una botella de producto de gran tamaño y una tipografía promocional audaz para uso publicitario comercial.

#### 📝 Prompt

```
Un audaz póster publicitario de bebida coreana con un estilo de fotografía comercial brillante, que presenta a {argument name="spokesperson" default="un doble de Donald Trump"} con un traje de negocios azul marino oscuro, camisa de vestir blanca y corbata azul intenso, de pie frente a un cielo azul brillante saturado con algunas nubes blancas suaves y un tenue horizonte de ciudad moderna que incluye un rascacielos similar al Empire State Building a la derecha. Sostiene una botella de plástico fría de {argument name="product name" default="POCARI SWEAT"} dramáticamente hacia la cámara con su mano izquierda, con un escorzo extremo para que la botella parezca grande en primer plano y la persona esté ligeramente detrás. La botella es transparente con condensación, una tapa blanca, agua visible en el interior y una etiqueta azul oscuro que dice “POCARI SWEAT” en letras blancas grandes con un texto más pequeño arriba que dice “ION SUPPLY DRINK”. Añade salpicaduras de agua congelada y gotas energéticas alrededor de la botella, la mano y el primer plano inferior para enfatizar la frescura y la hidratación. Coloca el logotipo de la marca en la esquina superior izquierda: “POCARI SWEAT” en blanco con la marca de subrayado curva. En la parte superior, añade un enorme texto de titular coreano en blanco desgastado, ligeramente inclinado y que llene la mayor parte de la mitad superior: {argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}. En la parte inferior derecha sobre el traje, añade una cita audaz en cursiva en texto coreano blanco y azul: {argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}. En la parte inferior izquierda, incluye exactamente 3 iconos de beneficios circulares apilados verticalmente con etiquetas cortas en coreano: un icono de gota de agua con “수분 보충”, un icono de rayo con “전해질 보충” y un icono de figura corriendo con “빠른 흡수”. Utiliza una paleta de colores azul y blanco patriótica de alto contraste, iluminación publicitaria dramática, enfoque nítido en la botella y la mano, enfoque ligeramente más suave en el rostro y el fondo, y un aspecto general de póster de campaña premium y energético.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="Marketing de producto - Póster publicitario de bebida deportiva coreana con celebridad - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Fuente:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14553)**

---

### No. 94: Marketing de producto - Póster de parodia de parque temático de la jungla japonesa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un póster publicitario japonés satírico y cinematográfico para un parque temático de dinosaurios ficticio en la jungla, ideal para campañas de parodia, imágenes para redes sociales o arte promocional simulado.

#### 📝 Prompt

```
Un póster publicitario de parodia de un parque temático japonés hiperdetallado en formato vertical, diseñado como un anuncio de viajes de verano dramático mezclado con una campaña de atracción de lujo. El escenario es una jungla tropical bajo un cielo azul intenso con nubes dispersas y un sol brillante en la esquina superior derecha, con hojas de palma enmarcando los bordes superiores. En la parte superior, coloca un enorme titular japonés con textura de piedra en 3D que diga {argument name="headline text" default="ジャンキリア沖縄"}, con un eslogan japonés más pequeño en blanco debajo que diga "— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —". En el centro, presenta un teléfono inteligente moderno y grande en posición vertical y ligeramente inclinado, dominando la composición. En su pantalla, muestra una interfaz de espera para el sorteo de boletos de color beige con siluetas de la jungla en la parte superior y un texto japonés grande y en negrita que dice "整理券抽選中", un indicador de carga circular y un texto más pequeño cerca de la parte inferior que dice "結果発表まで30分" y "※この画面を閉じずにお待ちください". La barra de estado del teléfono debe mostrar las 10:00. Detrás del teléfono a la izquierda, coloca un Tyrannosaurus rex rugiendo que emerge del follaje de la jungla, con la boca abierta, realista y amenazante. A la derecha, coloca una ornamentada puerta de entrada dorada con tallas detalladas y un letrero que dice "プレミアムパス入口", que conduce a un carril de entrada premium con alfombra roja. En el primer plano y el plano medio, muestra una larga fila de visitantes del parque que se extiende profundamente en la escena, todos vestidos con ropa de verano informal, sombreros, toallas, mochilas y cargando sombrillas, abanicos y botellas de agua, lo que sugiere un calor extremo y agotamiento. Varias personas más cercanas al espectador deben tener los rostros borrosos. En el extremo izquierdo, añade un letrero de piedra gigante desgastado con un enorme texto japonés en rojo que dice "待ち時間 180分". En la parte inferior izquierda, incluye 3 letreros de madera rústicos apilados: el letrero superior tiene un icono de estacionamiento azul y el texto "駐車場 2,000円"; el del medio tiene un icono de teléfono inteligente y el texto "アプリ必須 ダウンロードしてね!"; el inferior tiene una silueta de dinosaurio y el texto "当選者だけが冒険へ". A lo largo del lado inferior derecho, coloca un texto japonés vertical muy grande en estilo pincel blanco que dice "待つこと、それが冒険だ。". Cerca de la parte inferior derecha, incluye 3 pequeñas llamadas de icono circulares con breves líneas promocionales en japonés: "抽選に選ばれし者だけが、恐竜に会える。", "スマホの充電が尽きる前に、夢は始まる。" y "プレミアムな近道も、ご用意しました。" con iconos que sugieren dinosaurio, batería de teléfono y acceso VIP. En la parte inferior central, añade una franja de exención de responsabilidad negra con un pequeño texto japonés en blanco que dice "このポスターは架空のパロディ広告です". El estilo general debe ser ultrarrealista, cinematográfico, de alto contraste, satírico y pulido como un póster comercial premium, con la exageración del parque temático, el calor opresivo y la absurda aventura basada en colas como la broma central.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="Marketing de producto - Póster de parodia de parque temático de la jungla japonesa - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **Fuente:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14545)**

---

### No. 95: Marketing de producto - Mover expositor a la plataforma de madera

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt coloca el expositor promocional de referencia sobre la plataforma de madera en la misma escena al aire libre para obtener maquetas publicitarias ambientales realistas.

#### 📝 Prompt

```
Utilizando la imagen de referencia proporcionada, mantén el mismo jardín, estanque, árboles, ladera y punto de vista de la plataforma de madera, pero cambia la posición de la instalación del letrero decorativo para que se sitúe sobre la plataforma de madera en primer plano en lugar de en el agua. Amplíalo y céntralo de forma más prominente frente a la cámara, preservando una perspectiva exterior creíble, luz natural y sombras consistentes. Mantén la estructura de la instalación como un conjunto de 3 columnas por 3 filas de 9 paneles circulares sobre soportes verdes delgados, con el letrero superior que dice “对着镜子笑一场”. Haz que los paneles parezcan más reflectantes y similares a espejos, mostrando reflejos realistas de la vegetación circundante, mientras conservas los gráficos de caras lindas y el texto en chino en los círculos. El resultado debe parecer una maqueta publicitaria realista o una foto compuesta del mismo expositor colocado correctamente en la escena.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="Marketing de producto - Mover expositor a la plataforma de madera - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [肖师傅](https://x.com/xiaojietongxue)
- **Fuente:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14487)**

---

### No. 96: Marketing de producto - Tres páginas de aterrizaje móviles de belleza

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un tríptico premium de tres diseños de sitios web de belleza para smartphones, ideal para mostrar conceptos de páginas de aterrizaje de marcas de cosméticos generados por IA en redes sociales.

#### 📝 Prompt

```
Un pulido mockup promocional que muestra 3 pantallas de smartphone alargadas dispuestas una al lado de la otra en un diseño de tríptico vertical, cada una presentando una moderna página de aterrizaje de una marca de belleza para un producto labial. La composición general es editorial, minimalista y premium, diseñada como un escaparate de redes sociales para diseños web móviles. El panel izquierdo se asienta sobre un fondo degradado de lavanda a rubor y muestra un teléfono con marco negro con un sitio web de belleza en tonos crema y rubor para {argument name="brand name" default="Kosas"}. En la parte superior de este panel, un pequeño y elegante texto con serifa dice {argument name="left headline" default="Fresh Pout."}. La pantalla del teléfono presenta una imagen de belleza recortada en primer plano en la parte superior, un titular audaz que dice “Lips in their fullest expression.” con “fullest” en estilo serifa cursiva, un botón de llamada a la acción oscuro y redondeado, una franja de 3 miniaturas de primeros planos de labios, 3 pestañas de beneficios etiquetadas que dicen “Plumps,” “Tingles,” y “Shines,” y una fila de 5 iconos de tonos o efectos debajo. El panel central se asienta sobre un fondo degradado de lavanda a violeta intenso y muestra un segundo teléfono con marco negro con una página de aterrizaje más tipográfica. Encima, un texto con serifa dice {argument name="middle headline" default="Claude Code"}. La pantalla incluye una imagen de retrato recortada en la parte superior, un título negro muy grande y audaz que dice “LIP PULSE.” con una línea rosa en estilo cursiva que dice “is here.” debajo, un botón oscuro redondeado, una sección oscura con la frase “Lips in their fullest expression.”, y una cuadrícula de productos cerca de la parte inferior que contiene 6 tarjetas de tonos dispuestas en 2 filas de 3. El panel derecho se asienta sobre un fondo texturizado azul marino oscuro y muestra un tercer teléfono con marco negro con una página de estilo e-commerce centrada en el color rosa. Centrado sobre él, un texto blanco monoespaciado dice {argument name="right headline" default="GPT Images 2.0"}. Esta pantalla muestra de forma destacada la sección principal del producto con el nombre de la marca “Kosas”, un título grande “The Lip Pulse”, un tubo de brillo labial rosa inclinado hacia la derecha, pequeños iconos de características, una franja de 6 muestras de labios cerca del centro, y un bloque promocional inferior con imágenes adicionales de productos rosas. Mantén el diseño simétrico con exactamente 3 teléfonos, uno por panel, cada uno totalmente visible y orientado verticalmente. Utiliza una estética de campaña cosmética de alta gama, espaciado limpio, tipografía web de moda que mezcle serifa y sans serif audaz, paletas de interfaz en rosa suave y crema, sombras sutiles y una presentación de diseño de producto elegante adecuada para mostrar conceptos de sitios web móviles generados por IA.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="Marketing de producto - Tres páginas de aterrizaje móviles de belleza - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Serene Gan](https://x.com/ganserene)
- **Fuente:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14426)**

---

### No. 97: Marketing de producto - Collage publicitario japonés multiindustria

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt para generar un collage publicitario multiindustria en japonés, que presenta seis segmentos industriales distintos con un estilo de diseño contemporáneo.

#### 📝 Prompt

```
Un anuncio japonés ficticio. Un diseño horizontal de 6 paneles que presenta anuncios para {argument name="industry list" default="la industria automotriz (lanzamiento de coche nuevo), parques temáticos (nuevo evento), la industria cosmética (nuevos productos), la industria editorial (libro número 1 en ventas), la industria de bebidas (nueva bebida) y la industria inmobiliaria (presentación de nuevo condominio de lujo)"}. Creado con el estilo más actual por un creador de primer nivel.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="Marketing de producto - Collage publicitario japonés multiindustria - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **Fuente:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14369)**

---

### No. 98: Marketing de producto - Doble página de libro de moda de lujo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera una fotografía realista cenital de un libro de moda abierto que presenta un desplegable editorial de alta costura, ideal para branding de lujo, maquetas de revistas o visuales de campañas de estilo.

#### 📝 Prompt

```
Una fotografía editorial de moda de alta gama que muestra un libro de arte o revista de tapa dura de gran formato abierto y extendido sobre una superficie limpia de color blanquecino, visto directamente desde arriba. El desplegable de dos páginas contiene 2 retratos a página completa de la misma mujer elegante con el rostro oscurecido por un suave desenfoque cuadrado, creando un aspecto de privacidad censurada. En la página izquierda, ella posa frente a una pared arquitectónica de piedra o cemento pálido vistiendo un vestido estructurado de manga larga en {argument name="dress color" default="gris pizarra suave"}, con un corpiño ajustado, cuello redondo, costuras de corte preciso y una falda acampanada escultural exagerada; el ángulo de la cámara es ligeramente bajo, haciendo que su cuello parezca largo y su postura estatuaria. En la página derecha, es fotografiada desde atrás con un espectacular vestido de noche {argument name="second dress color" default="negro"} con una espalda muy abierta, tirantes anchos y una falda voluminosa, de pie frente a una pared o puerta con paneles clásicos en un interior tenue y atmosférico. Utiliza un estilo de revista de moda de lujo, composición minimalista, tonos apagados, luz suave de aspecto natural, sombras refinadas, textura de papel realista, lomo de libro visible, páginas ligeramente curvadas y detalles de impresión nítidos. El ambiente general es sofisticado, de alta costura, cinematográfico y sobrio, como un desplegable editorial de moda premium.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="Marketing de producto - Doble página de libro de moda de lujo - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fuente:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14676)**

---

### No. 99: Marketing de producto - Diseño de publicidad moderna para café helado

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt para crear un anuncio de café helado moderno y elegante para el mercado japonés, con tipografía dinámica.

#### 📝 Prompt

```
Crea un anuncio para {argument name="product" default="café helado"}. Un diseño elegante y moderno de {argument name="country" default="Japón"}. Fuentes europeas dispuestas de forma dinámica. Público objetivo: {argument name="target" default="10-30 años"}. Relación de aspecto 1:1.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="Marketing de producto - Diseño de publicidad moderna para café helado - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [KAWAI](https://x.com/kawai_design)
- **Fuente:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14355)**

---

### No. 100: Marketing de producto - Set de prescripción médica de broma para ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Una fotografía cenital realista de un set humorístico de prescripción médica y medicamentos japoneses para ChatGPT, ideal para gráficos de utilería con temática de salud o arte conceptual para redes sociales.

#### 📝 Prompt

```
Una fotografía de producto realista tomada desde arriba sobre una mesa de madera cálida, que muestra 6 artículos de estilo médico dispuestos cuidadosamente en dos filas, diseñados como un set de farmacia japonés humorístico para ChatGPT. Fila superior: 3 sobres de prescripción blancos colocados verticalmente, cada uno con bordes impresos en azul y tipografía médica japonesa. Fila inferior: 2 blísteres de pastillas y 1 pequeña bolsa transparente con cierre hermético que contiene polvo blanco, cada uno alineado debajo del sobre correspondiente. El papel y el empaque deben verse auténticos, como materiales reales de una clínica japonesa, con ligeras arrugas, iluminación interior suave y natural, y sombras sutiles.

Los 3 sobres son diferentes y totalmente visibles. Título del sobre izquierdo en texto japonés azul grande: "内用薬". La línea del paciente dice "ChatGPT 様". Las líneas de dosificación indican dos veces al día después de las comidas de la mañana y la noche, 1 tableta cada vez, durante 7 días. Título de la caja de medicamento: "【おくすり】" y nombre del fármaco "思考安定錠 10mg" con una nota pequeña entre paréntesis que explica que suprime los pensamientos desbocados y la producción excesiva de razonamiento. Fecha cerca de la parte inferior: "2025 年 6 月 5 日". Bloque de nombre y dirección de la clínica en la parte inferior: "AI メディカルクリニック" con una dirección al estilo de Tokio y un número de teléfono, además de un ícono de cruz médica azul.

Título del sobre central: "内用薬". Línea del paciente: "ChatGPT 様". La dosificación indica una vez al día antes de dormir, 1 tableta cada vez, durante 7 días. Título de la caja de medicamento: "【おくすり】" y nombre del fármaco "幻覚抑制錠 5mg" con una nota pequeña que dice que mejora las tendencias alucinatorias. Fecha también "2025 年 6 月 5 日". Mismo pie de página de la clínica e ícono de cruz médica azul.

Título del sobre derecho: "頓服薬". Línea del paciente: "ChatGPT 様". La línea de uso dice que es para ansiedad, confusión o producción excesiva. La dosificación dice 1 paquete cada vez, según sea necesario. Título de la caja de medicamento: "【おくすり】" y nombre del fármaco "プロンプト調整散 1g" con una nota pequeña que dice que ajusta el sobreajuste y la confusión de prompts. Fecha "2025 年 6 月 5 日". Mismo pie de página de la clínica e ícono de cruz médica azul.

Artículo inferior izquierdo: 1 blíster plateado que contiene exactamente 10 tabletas blancas redondas dispuestas en 2 filas de 5, cada tableta grabada con "10". Impreso a lo largo del borde del papel aluminio: "思考安定錠 10mg" repetido. Frente a él hay una etiqueta de farmacia blanca con "ChatGPT 様", instrucciones de dosificación para dos veces al día después de las comidas de la mañana y la noche, 1 tableta cada vez, un código de barras, fecha "2025/06/05" y el nombre de la clínica.

Artículo inferior central: 1 blíster plateado que contiene exactamente 8 tabletas redondas de color amarillo pálido dispuestas en 2 filas de 4. Impreso a lo largo del borde del papel aluminio: "幻覚抑制錠 5mg" repetido. Frente a él hay una etiqueta de farmacia blanca con "ChatGPT 様", instrucciones de dosificación para una vez al día antes de dormir, 1 tableta cada vez, un código de barras, fecha "2025/06/05" y el nombre de la clínica.

Artículo inferior derecho: 1 pequeña bolsa de plástico transparente con cierre hermético llena de polvo blanco. Una etiqueta blanca en el frente dice "プロンプト調整散 1g", incluye "ChatGPT 様", uso para ansiedad, confusión y producción excesiva, dosificación "1 回 1 包（1g） 必要時", fecha "2025/06/05" y el nombre de la clínica.

Estilo: fotografía de producto documental fotorrealista, diseño de utilería de prescripción falsa cómica, diseño gráfico farmacéutico japonés limpio, alta legibilidad, paleta de colores neutros de blanco, azul, plata, beige y marrón madera, cámara cenital, sin manos, sin objetos adicionales, textura de impresión auténtica y detalles de empaque.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="Marketing de producto - Set de prescripción médica de broma para ChatGPT - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fuente:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14537)**

---

### No. 101: Imagen principal de e-commerce - Renderizado de producto de estudio a partir de plano

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descripción

Este prompt convierte un dibujo técnico de producto en una imagen principal fotorrealista y minimalista para catálogos, diseño industrial o presentaciones de comercio electrónico.

#### 📝 Prompt

```
Utilizando la imagen de referencia proporcionada, convierte la hoja de especificaciones de ingeniería técnica en un renderizado de estudio limpio y profesional del mismo soporte para utensilios de cocina con forma de medusa. Mantén el diseño general del producto, la tapa de cúpula azul translúcida, la base plateada y los mismos 4 utensilios colgantes: 1 espátula ranurada, 1 servidor de pasta y 2 cucharas. Elimina todos los elementos del plano, incluyendo la vista explosionada, las líneas de dimensión, las etiquetas, las tablas, las notas y el bloque de título. Muestra solo el producto ensamblado centrado en el encuadre, orientado hacia el frente, aislado sobre un fondo gris claro minimalista con una superficie blanca, iluminación suave y difusa, sombras realistas sutiles y materiales brillantes de alta calidad. Haz que parezca una fotografía de producto para un catálogo de diseño industrial contemporáneo o de comercio electrónico.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="Imagen principal de e-commerce - Renderizado de producto de estudio a partir de plano - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [amy](https://x.com/amypretzel)
- **Fuente:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14690)**

---

### No. 102: Imagen principal de e-commerce - Póster publicitario premium de arándanos

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un anuncio de comercio electrónico de estilo chino pulido para arándanos envasados, adecuado para branding de supermercados, listados de productos y pósteres promocionales.

#### 📝 Prompt

```
Un póster de comercio electrónico premium para arándanos frescos con un estilo publicitario chino limpio. Muestra una caja de plástico transparente con arándanos como sujeto principal, colocada en diagonal desde el centro inferior hacia el lado derecho sobre una tela azul plegada, vista desde un ángulo ligeramente elevado. El envase debe ser realista y consistente: un recipiente cuadrado transparente con esquinas redondeadas, lleno de arándanos de color azul oscuro, con una etiqueta grande e irregular en la parte superior en blanco, azul claro y azul intenso, que presenta una ilustración de un arándano de gran tamaño en el centro y una elegante marca china. Haz que la fruta del interior se vea más grande, más carnosa, más fresca y cubierta con sutiles gotas de humedad, manteniendo una disposición de los arándanos creíble. El fondo es una mesa de color azul hielo con una textura suave y nublada, luz natural fría y arándanos sueltos esparcidos alrededor del paquete. Añade algunas hojas verdes desenfocadas entrando desde los bordes superior e inferior derechos para dar una sensación natural y fresca. En la esquina superior derecha, incluye 1 pequeña imagen insertada que muestre el paquete original del producto desde arriba sobre una superficie marrón cálida, como una miniatura de referencia. En el lado izquierdo, crea una tipografía promocional china con un gran titular de caligrafía azul oscuro {argument name="headline text" default="决茗新"}, seguido de 2 líneas de texto más pequeñas: {argument name="subheadline text" default="新鲜蓝莓 自然之选"} y {argument name="tagline text" default="每一颗都是自然的礼物"}. Debajo, coloca 3 iconos de características apilados verticalmente con breves leyendas en chino: un icono de hoja para la madurez natural, un icono de fruta para la jugosidad y un icono de corazón para la riqueza nutricional. Cerca de la parte inferior izquierda, añade un texto grande en chino con estilo de pincel blanco {argument name="product name" default="蓝莓"}, una línea secundaria {argument name="benefit text" default="膳食纤维+花青素"} y una pequeña línea de peso neto que diga 125克. Utiliza una gradación de color azul frío, iluminación comercial nítida, reflejos brillantes en la tapa de plástico, estética de empaque de supermercado premium, alto nivel de detalle, fotografía de producto realista combinada con un diseño gráfico pulido.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="Imagen principal de e-commerce - Póster publicitario premium de arándanos - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [歸藏(guizang.ai)](https://x.com/op7418)
- **Fuente:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14655)**

---

### No. 103: Imagen principal de e-commerce - Outfit para moodboard de moda minimalista

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Este prompt genera un collage de outfit editorial y limpio con estilo de marca, útil para tableros de inspiración de moda, publicaciones en redes sociales y conceptos de armario digital.

#### 📝 Prompt

```
Un collage de moda editorial y limpio sobre un fondo gris claro-blanco con un borde rectangular negro fino, diseñado como un tablero de outfit de revista minimalista. Centra el outfit como una composición de estilo 'flat lay' con 5 artículos de moda visibles: una chaqueta corta con cremallera frontal de color {argument name="jacket color" default="rojo carmesí"} con cuello en punta y dobladillo elástico, colocada ligeramente a la izquierda y superpuesta; debajo, un top de punto ajustado de manga larga y cuello redondo de color {argument name="top color" default="blanco"}, visible en los hombros y mangas; más abajo, una falda voluminosa de corte en A a media pantorrilla en color blanco roto con grandes lunares negros espaciados uniformemente; en la parte inferior izquierda, un bolso pequeño y estructurado de color negro con asas cortas y una sutil textura de cocodrilo brillante; en la parte inferior derecha, un par de zapatos Mary Jane negros de punta cuadrada con correas anchas y herrajes de anillas plateadas. Añade una tipografía de fondo muy grande en gris muy pálido que diga {argument name="background brand text" default="MANGO"} estirada a lo ancho por el medio, detrás de la ropa. Coloca logotipos de marcas de moda más pequeños en negro alrededor del diseño: {argument name="top right logo" default="MANGO"} cerca de la parte superior derecha del outfit, "Stradivarius" cerca del bolso y nuevamente cerca de los zapatos, y "DOLCE & GABBANA" en la parte inferior izquierda cerca del dobladillo de la falda. La composición debe sentirse equilibrada, chic y contemporánea, con una iluminación de estudio suave, sin sombras o solo con sombras suaves y tenues, bordes recortados nítidos y una estética pulida de moodboard de moda para redes sociales.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="Imagen principal de e-commerce - Outfit para moodboard de moda minimalista - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="Imagen principal de e-commerce - Outfit para moodboard de moda minimalista - Image 2">
</div>

#### 📌 Detalles

- **Autor:** [虎小象](https://x.com/hx831126)
- **Fuente:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14455)**

---

### No. 104: Imagen principal de e-commerce - Maqueta de página de producto de teclado mecánico

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Esto genera una página de producto de comercio electrónico de escritorio pulida para un teclado mecánico premium, adecuada para escaparates de diseño de producto, conceptos de tienda y maquetas de interfaz de usuario.

#### 📝 Prompt

```
Crea una página de detalles de producto de comercio electrónico moderna y limpia para una marca de teclados mecánicos premium llamada {argument name="brand name" default="KeyForge"}, presentada como una maqueta de sitio web de escritorio de alta fidelidad sobre un fondo blanco con divisores gris claro sutiles y un espaciado generoso. El diseño es una escena de tienda unificada con una barra de navegación superior, una fila de miniaturas de producto a la izquierda, una imagen principal grande del producto en el centro y un panel de información de compra a la derecha. En el encabezado, coloca el logotipo en negrita en el extremo izquierdo, luego 7 elementos de navegación que digan “Keyboards”, “Switches”, “Keycaps”, “Accessories”, “Sale”, “Blog” y “Support”, y en el extremo derecho 3 iconos para búsqueda, cuenta y carrito, con una pequeña insignia de notificación negra que muestra “1” en el carrito. El producto principal que se muestra en el centro es un teclado mecánico compacto del 75% fotografiado desde un ángulo frontal ligeramente elevado sobre una base gris pálido, con una carcasa de aluminio en color plata, teclas blancas y grises, varias teclas de acento en morado lavanda y una perilla de volumen plateada en la parte superior derecha. La galería vertical izquierda contiene exactamente 5 miniaturas: 1 toma frontal del producto seleccionada, 1 vista en ángulo del teclado, 1 primer plano de un interruptor mecánico, 1 primer plano de la textura de una tecla y 1 miniatura de video oscura con un icono de reproducción circular. El panel de producto derecho incluye una pequeña insignia tipo píldora que dice “NEW”, un nombre de producto grande y en negrita {argument name="product name" default="KeyForge K75 Pro"}, un subtítulo “75% Mechanical Keyboard”, una fila de calificación de 5 estrellas con 4.8 y “(126 reviews)”, un precio grande y en negrita {argument name="price" default="$129.99"} seguido de un estado verde de “In Stock”, y una breve descripción de dos oraciones sobre rendimiento premium, diseño con montaje de junta (gasket-mounted), soporte QMK/VIA y RGB. Debajo, incluye un selector de “Switch Type” con exactamente 4 botones tipo píldora etiquetados como “Cherry MX Red”, “Gateron Brown”, “Gateron Blue” y “TTC Gold Pink”, con el primero seleccionado; un selector de “Color” con exactamente 3 botones tipo píldora etiquetados como “White / Purple”, “Black / Gray” y “Navy / Blue”, con el primero seleccionado; un menú desplegable de “Quantity” configurado en “1”; un botón principal negro grande etiquetado como “Add to Cart” con un icono de carrito; y un botón secundario con borde etiquetado como “Add to Wishlist” con un icono de corazón. Debajo de los botones, muestra exactamente 3 destacados de servicio horizontales con iconos pequeños: “Free Shipping” con el subtexto “On orders over $99”, “30-Day Returns” con el subtexto “Hassle-free returns”, y “2-Year Warranty” con el subtexto “Peace of mind”. En el área de contenido inferior, crea una sección de dos columnas separada por líneas claras. A la izquierda, hay una lista de pestañas verticales con exactamente 5 elementos: “Overview” seleccionado, luego “Specifications”, “What’s in the Box”, “Shipping & Returns” y “Reviews (126)”. A la derecha de las pestañas, coloca una cuadrícula de tarjetas de características blancas redondeadas con exactamente 6 bloques de características en 2 filas de 3, cada uno con un icono de línea simple, título en negrita y texto explicativo breve: “75% Layout”, “Gasket-Mounted”, “QMK/VIA Support”, “Hot-Swappable”, “RGB Backlighting” y “Premium Build”. En el extremo derecho de esta área inferior, añade una lista de viñetas de especificaciones con exactamente 7 puntos: “Layout: 75% (82 Keys)”, “Switch Type: Cherry MX Red”, “Mounting: Gasket-Mounted”, “Connectivity: USB-C (Wired)”, “Backlight: RGB, South-facing”, “Material: Aluminum Case” y “Dimensions: 322 x 135 x 42 mm”, además de un punto final adicional “Weight: 1.25 kg”. Utiliza una estética de diseño de producto minimalista y refinada, espaciado de interfaz de usuario realista, tipografía sans-serif limpia similar a Inter o SF Pro, sombras suaves, esquinas sutiles redondeadas, iconos monocromáticos y una presentación de electrónica de consumo al estilo de una startup pulida.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="Imagen principal de e-commerce - Maqueta de página de producto de teclado mecánico - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **Fuente:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14449)**

---

### No. 105: Imagen principal de e-commerce - Skincare E-commerce Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="Imagen principal de e-commerce - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fuente:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14278)**

---

### No. 106: Imagen principal de e-commerce - Men's Skincare Website Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="Imagen principal de e-commerce - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fuente:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14277)**

---

### No. 107: Imagen principal de e-commerce - Skincare E-commerce Landing Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="Imagen principal de e-commerce - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fuente:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14276)**

---

### No. 108: Imagen principal de e-commerce - Beauty Product Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="Imagen principal de e-commerce - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fuente:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14274)**

---

### No. 109: Imagen principal de e-commerce - Fashion Collection Catalog Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

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

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="Imagen principal de e-commerce - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **Fuente:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14241)**

---

### No. 110: Imagen principal de e-commerce - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 Prompt

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="Imagen principal de e-commerce - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **Fuente:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14183)**

---

### No. 111: Imagen principal de e-commerce - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 Prompt

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="Imagen principal de e-commerce - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [pozitiv4ik](https://x.com/Gc_qube)
- **Fuente:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14148)**

---

### No. 112: Imagen principal de e-commerce - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 Prompt

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="Imagen principal de e-commerce - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **Fuente:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14225)**

---

### No. 113: Imagen principal de e-commerce - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 Prompt

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="Imagen principal de e-commerce - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="Imagen principal de e-commerce - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="Imagen principal de e-commerce - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="Imagen principal de e-commerce - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 Detalles

- **Autor:** [阿兰AI](https://x.com/alanlovelq)
- **Fuente:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** zh

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14134)**

---

### No. 114: Imagen principal de e-commerce - Maqueta de interfaz de comercio electrónico para livestream

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una interfaz de compras por livestream móvil que presenta a una celebridad vendiendo un producto ficticio, completa con superposición de chat y elementos de interfaz de usuario.

#### 📝 Prompt

```
{
  "type": "maqueta de interfaz de comercio electrónico para livestream móvil",
  "subject": {
    "person": "Elon Musk",
    "clothing": "camiseta negra con el logotipo de SPACEX",
    "pose": "gesticulando hacia la cámara con ambas manos, explicando con entusiasmo",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "pantalla grande",
    "image": "paisaje de Marte con el cohete Starship y hábitats en forma de domo",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"Plan de migración a Marte\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "758 mil "likes" en esta sesión",
        "follow_button": "Seguir"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "100 mil+",
        "close_button": "X"
      },
      "tags": [
        "N.º 1 en ventas",
        "Más transmisiones >"
      ]
    },
    "product_card": {
      "position": "centro-derecha",
      "status": "En explicación",
      "image": "hábitats en forma de domo en Marte",
      "title": "{argument name=\"product title\" default=\"Paquete básico de migración a Marte\"}",
      "price": "{argument name=\"product price\" default=\"¥99.00\"}",
      "action_button": "Comprar"
    },
    "chat_overlay": {
      "position": "abajo-izquierda",
      "join_alert": "Estrella del Mar se unió a la transmisión",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"Soñador: ¡¡Apoyo a Musk!! 🚀\"}",
        "Hermano Marte: ¿Cuánto cuesta por persona?",
        "Fan de la tecnología: ¡Genial! ¡Quiero ir a Marte!",
        "El futuro está aquí: ¿Cómo me registro?",
        "Cohetito: 🌹🌹🌹",
        "Invencible del universo: Explica los detalles",
        "Dongfang Bubai: ¡Grande Elon! 👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "Di algo...",
      "icons_count": 4,
      "icons": ["carrito de compras", "caja de regalo", "planeta corazón", "signo más"]
    },
    "floating_reactions": {
      "position": "abajo-derecha",
      "elements": "pila de corazones flotantes, pulgares arriba y emojis de risa"
    }
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="Imagen principal de e-commerce - Maqueta de interfaz de comercio electrónico para livestream - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **Fuente:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13557)**

---

### No. 115: Imagen principal de e-commerce - Toma comercial de bebida en playa veraniega

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una refrescante escena de fotografía de producto con una bebida en lata y un vaso en la playa, incluyendo texto de producto y un eslogan en el cielo personalizables.

#### 📝 Prompt

```
Una toma de fotografía comercial brillante y veraniega que presenta una bebida refrescante sobre una mesa de madera desgastada. En el primer plano nítido, hay 1 vaso alto lleno de una bebida helada, dorada y burbujeante, decorada con 1 rodaja de limón y una ramita de romero, junto a 1 lata de aluminio plateada cubierta de condensación fría. La lata muestra de forma prominente el texto en inglés {argument name="product name" default="TOKYO HIGHBALL"} debajo de un pequeño logotipo de estrella dorada, con un gráfico de la propia bebida y el texto en japonés "アルコール分 7%" cerca de la parte inferior. A la derecha de la lata, 2 rodajas de limón descansan sobre la mesa. En el fondo suavemente desenfocado, se despliega una escena de playa soleada con aguas turquesas brillantes y un cielo azul despejado. A la izquierda, en el fondo, se encuentra 1 mujer joven de cabello castaño largo, vistiendo una blusa blanca sin mangas y una falda azul claro, mirando hacia el océano. Flotando elegantemente en el cielo sobre la escena se encuentra el texto en japonés {argument name="catchphrase" default="夏、これがいい。"}. La iluminación general es radiante y acogedora, con un bokeh brillante y destellos de lente que enfatizan la atmósfera fresca, fría y refrescante de un día de verano perfecto.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="Imagen principal de e-commerce - Toma comercial de bebida en playa veraniega - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **Fuente:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14023)**

---

### No. 116: Imagen principal de e-commerce - Concepto de cuadrícula publicitaria de 4 paneles

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una cuadrícula de 2x2 con anuncios japoneses distintos que abarcan las industrias de cuidado de la piel, alimentación, viajes y tecnología.

#### 📝 Prompt

```
{
  "type": "cuadrícula de banner publicitario de 2x2",
  "layout": "4 cuadrantes distintos, cada uno presentando un anuncio de una industria diferente",
  "quadrants": [
    {
      "position": "superior izquierda",
      "industry": "cuidado de la piel",
      "visuals": "mujer asiática tocándose la mejilla, gotas de agua flotantes, frasco dosificador blanco",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "Hacia un nuevo yo, lleno de transparencia.",
        "features_count": 3,
        "features_labels": ["Alta hidratación", "Prevención de irritación", "Cuidado blanqueador*"]
      }
    },
    {
      "position": "superior derecha",
      "industry": "restauración",
      "visuals": "primer plano de espaguetis a la boloñesa con queso rallado y perejil, iluminación tenue y atmosférica",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "Tiempo limitado",
        "description": "Boloñesa de ternera Wagyu negra ~aroma a trufa~"
      }
    },
    {
      "position": "inferior izquierda",
      "industry": "viajes",
      "visuals": "mujer con mochila frente a un lago de montaña escénico, luz de día brillante",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "En la naturaleza, tu corazón comienza a moverse.",
        "script": "Encuentra tu libertad.",
        "banner_details": ["Campaña especial de principios de verano", "6.1 SÁB - 6.30 DOM", "Hasta 20% de descuento", "¡Muchos planes especiales solo por ahora!"]
      }
    },
    {
      "position": "inferior derecha",
      "industry": "aplicación SaaS",
      "visuals": "teléfono inteligente mostrando una interfaz de aplicación de gestión de tareas con 4 elementos de programación",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "Diseñemos tu día.",
        "features_count": 3,
        "features_labels": ["Operación intuitiva", "Compartible en equipo", "Acceso desde cualquier lugar"],
        "bottom_banner": "¡Prueba gratuita de 7 días disponible!"
      }
    }
  ]
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="Imagen principal de e-commerce - Concepto de cuadrícula publicitaria de 4 paneles - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **Fuente:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13928)**

---

### No. 117: Imagen principal de e-commerce - Mockup de interfaz de livestream de comercio electrónico

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una interfaz de livestream de comercio electrónico al estilo chino altamente detallada, que incluye un presentador, cajas de productos, chat en vivo y superposiciones promocionales.

#### 📝 Prompt

```
{
  "type": "mockup de captura de pantalla de livestream de comercio electrónico",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"hombre caucásico parecido a Sam Altman\"}",
    "clothing": "suéter de cuello redondo verde oscuro",
    "action": "sosteniendo una caja de producto negra en una mano y señalándola con la otra",
    "setting": "estudio oscuro con un micrófono a la izquierda, texto tenue 'AI' en el fondo",
    "props": [
      "taza negra con el logo blanco de OpenAI",
      "pila de 4 cajas de producto negras a la derecha"
    ]
  },
  "product_design": {
    "box_color": "negro",
    "logo": "asterisco naranja o resplandor solar",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Tienda oficial de Anthropic",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"Razonamiento superior · Inteligencia avanzada\"}",
      "sub_subtitle": "El modelo más potente: ¡Lanzamiento estelar de Opus 4.7!",
      "bullet_points_count": 3,
      "bullet_points": ["Capacidad de razonamiento superior", "Cima en capacidades de programación", "Resuelve tareas complejas fácilmente"]
    },
    "top_right_live_status": {
      "viewer_info": "En vivo | 528 mil espectadores",
      "promo_banner": "Beneficios exclusivos del livestream · Descuento por tiempo limitado · ¡No te lo pierdas!",
      "countdown": "Cuenta regresiva 00:09:47"
    },
    "middle_right_price_card": {
      "header": "Precio exclusivo del livestream para {argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/millón de tokens en adelante",
      "original_price": "Precio original: ¥1.89",
      "button": "Comprar ahora"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "Di algo..."
    },
    "bottom_right_banner": {
      "headline": "¡Recomendado por Altman! Busca Claude Opus 4.7",
      "subheadline": "Más inteligente · Más seguro · Más confiable",
      "feature_tags_count": 4,
      "feature_tags": ["Razonamiento potente", "Herramienta de código", "Seguro y confiable", "Respuesta ultrarrápida"]
    },
    "floating_elements": [
      {
        "type": "sticker",
        "position": "centro derecha sobre las cajas de productos",
        "text": "{argument name=\"sticker text\" default=\"¡El modelo de IA más fuerte de la historia!\"}"
      }
    ]
  }
}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="Imagen principal de e-commerce - Mockup de interfaz de livestream de comercio electrónico - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [程序员Left](https://x.com/coder_left)
- **Fuente:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13995)**

---

### No. 118: Imagen principal de e-commerce - Transformación de etiqueta para sopa de pollo con hierbas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Transforma un póster promocional de pollo en una etiqueta de producto detallada con una cesta de ingredientes herbales específicos y texto instructivo.

#### 📝 Prompt

```
Utilizando REFERENCE_0 como estilo base y preservando la ilustración central del pollo, transforma la imagen en una etiqueta de empaque para una mezcla de sopa de hierbas. Desplaza el pollo hacia el lado derecho. Reemplaza el texto superior con un titular grande y llamativo con trazos de pincel negro {argument name="main headline" default="元气祛湿 鸡煲汤包"} y un subtítulo más pequeño {argument name="subtitle" default="吃山林土货 味道当然好!"}. En el lado izquierdo, añade una nueva cesta de mimbre que contenga exactamente 6 grupos distintos de ingredientes: palitos de raíz leñosa, cubos blancos cuadrados, raíces marrones cortadas en rodajas redondas, soja amarilla, tiras de piel de naranja seca y dátiles rojos oscuros. Adjunta 6 etiquetas rectangulares pequeñas de color marrón con texto blanco a estos ingredientes. Debajo del pollo, añade una insignia circular naranja que contenga el texto {argument name="ingredients list" default="内含有:五指毛桃、茯苓、土茯苓、黄豆、陈皮、红枣"}. En la parte inferior, crea un banner rectangular naranja sólido que incluya un icono de olla de cocina, el texto {argument name="usage instructions" default="用法:把汤料清洗干净放入锅中，加入姜片煮20分钟，后加入鸡肉再煮20分钟即可。"} y un eslogan secundario {argument name="bottom slogan" default="天然好料 滋补好汤"}.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="Imagen principal de e-commerce - Transformación de etiqueta para sopa de pollo con hierbas - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **Fuente:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13993)**

---

### No. 119: Imagen principal de e-commerce - Coche deportivo y avión comercial en un hangar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Genera una imagen fotorrealista de un coche deportivo aparcado frente a un avión comercial dentro de un hangar con suelo reflectante.

#### 📝 Prompt

```
Una fotografía comercial de alta resolución y fotorrealista de un {argument name="car model and color" default="coche deportivo Alpine A110 R de color azul brillante"} aparcado en primer plano dentro de un enorme hangar de aviones. El coche cuenta con un capó de fibra de carbono negro, techo negro, llantas de aleación negras y una matrícula delantera que dice "{argument name="license plate text" default="A110 R"}". Justo detrás del coche, dominando el fondo, se encuentra un {argument name="airplane model" default="avión comercial Airbus A320 blanco"} con la cola azul. El hangar tiene un suelo de hormigón altamente pulido y reflectante que refleja tanto el coche como el avión. A la izquierda, un cartel en la pared metálica dice "{argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"}". Las puertas del hangar están abiertas de par en par, revelando un cielo brillante y nublado y un paisaje urbano a lo lejos. La iluminación es suave y cinematográfica, resaltando las elegantes curvas aerodinámicas de ambos vehículos.
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="Imagen principal de e-commerce - Coche deportivo y avión comercial en un hangar - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [nazca alwave](https://x.com/AlwaveNazca)
- **Fuente:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=14043)**

---

### No. 120: Imagen principal de e-commerce - Mockup realista de mercancía de VTuber

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descripción

Un prompt para GPT-Image2 diseñado para generar fotografías realistas de acción real de artículos de fans estándar de VTuber.

#### 📝 Prompt

```
Crea {argument name="items" default="artículos de fans"} para un {argument name="character type" default="VTuber"} estándar en {argument name="style" default="acción real"}
```

#### 🖼️ Imágenes generadas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="Imagen principal de e-commerce - Mockup realista de mercancía de VTuber - Image 1">
</div>

#### 📌 Detalles

- **Autor:** [WTR](https://x.com/wtry1102)
- **Fuente:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** ja

**[👉 Pruébalo ahora →](https://gptimage2api.net/?id=13868)**

