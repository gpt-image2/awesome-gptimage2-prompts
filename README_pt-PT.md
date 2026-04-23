
# 🚀 Prompts Incríveis do GPT Image 2


> 🎨 Uma coleção curada de prompts criativos para o GPT Image 2 da OpenAI

> ℹ️ 数据文件 / Data file: [prompts.json](prompts.json)
> 数据来源 / Source: `https://gptimage2api.net/prompts`
> 原始数据文件 / Canonical raw file: `prompts.json`

---

[![English](https://img.shields.io/badge/English-Click%20to%20View-lightgrey)](README.md) [![简体中文](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh.md) [![繁體中文](https://img.shields.io/badge/%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-Click%20to%20View-lightgrey)](README_zh-TW.md) [![日本語](https://img.shields.io/badge/%E6%97%A5%E6%9C%AC%E8%AA%9E-Click%20to%20View-lightgrey)](README_ja-JP.md) [![한국어](https://img.shields.io/badge/%ED%95%9C%EA%B5%AD%EC%96%B4-Click%20to%20View-lightgrey)](README_ko-KR.md) [![ไทย](https://img.shields.io/badge/%E0%B9%84%E0%B8%97%E0%B8%A2-Click%20to%20View-lightgrey)](README_th-TH.md) [![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-Click%20to%20View-lightgrey)](README_vi-VN.md) [![हिन्दी](https://img.shields.io/badge/%E0%A4%B9%E0%A4%BF%E0%A4%A8%E0%A5%8D%E0%A4%A6%E0%A5%80-Click%20to%20View-lightgrey)](README_hi-IN.md) [![Español](https://img.shields.io/badge/Espa%C3%B1ol-Click%20to%20View-lightgrey)](README_es-ES.md) [![Español (Latinoamérica)](https://img.shields.io/badge/Espa%C3%B1ol%20(Latinoam%C3%A9rica)-Click%20to%20View-lightgrey)](README_es-419.md) [![Deutsch](https://img.shields.io/badge/Deutsch-Click%20to%20View-lightgrey)](README_de-DE.md) [![Français](https://img.shields.io/badge/Fran%C3%A7ais-Click%20to%20View-lightgrey)](README_fr-FR.md) [![Italiano](https://img.shields.io/badge/Italiano-Click%20to%20View-lightgrey)](README_it-IT.md) [![Português (Brasil)](https://img.shields.io/badge/Portugu%C3%AAs%20(Brasil)-Click%20to%20View-lightgrey)](README_pt-BR.md) [![Português](https://img.shields.io/badge/Portugu%C3%AAs-Current-brightgreen)](README_pt-PT.md) [![Türkçe](https://img.shields.io/badge/T%C3%BCrk%C3%A7e-Click%20to%20View-lightgrey)](README_tr-TR.md)

---

## 📖 Índice

- [🤔 O que é GPT Image 2?](#-what-is-gpt-image-2)
- [📊 Estatísticas](#-statistics)
- [🔥 Prompts em destaque](#-featured-prompts)
- [📋 Todos os prompts](#-all-prompts)

---

## 🤔 O que é GPT Image 2?

**GPT Image 2** (codename **"duct-tape"**) is OpenAI's next-generation image model. Community testing highlights a leap in these areas:

- 🎯 **Pixel-Perfect Text Rendering** — Native-quality text in Chinese, English, and Japanese, no typos or warped glyphs
- 🎨 **Cross-Image Consistency** — The same character, style, or IP stays identical across a series, down to the pixel
- ⚡ **Commercial-Grade Illustration** — Illustration output is ready to ship without manual polish
- 🌈 **True Art Style Induction** — Creatively evokes the feeling of a style rather than merely approximating references
- 🔧 **Storyboard & Product Series** — Ideal for storyboards, IP characters, and multi-panel product visuals
- 📐 **Multi-Language Design** — Social cards, banners, and posters with accurate multilingual typography in one shot

📚 **Learn More:** See community testing in our [report summary](docs/FAQ.md)

### 🚀 Integração com Raycast

Alguns prompts suportam **argumentos dinâmicos** usando a sintaxe [Raycast Snippets](https://raycast.com/help/snippets). Procure o emblema 🚀 Raycast Friendly!

**Exemplo:**
```
A quote card with "{argument name="quote" default="Stay hungry, stay foolish"}"
by {argument name="author" default="Steve Jobs"}
```

Quando usado no Raycast, você pode substituir dinamicamente os argumentos para iterações rápidas!

---

## 📊 Estatísticas

<div align="center">

| Métrica | Contagem |
|--------|-------|
| 📝 Total de prompts | **1123** |
| ⭐ Destaque | **6** |
| 🔄 Última atualização | **quinta-feira, 23 de abril de 2026 às 01:29:18 UTC** |

</div>

---

## 🔥 Prompts em destaque

> ⭐ Selecionados à mão pela nossa equipe por qualidade e criatividade excepcionais

### No. 1: Pôster de Vista Explodida de Headset VR

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera um diagrama de vista explodida de alta tecnologia de um headset VR com legendas detalhadas dos componentes e texto promocional.

#### 📝 Prompt

```
{
  "type": "pôster de diagrama de produto em vista explodida",
  "subject": "headset VR",
  "style": "renderização 3D limpa de alta tecnologia, iluminação de estúdio, detalhes brilhantes",
  "background": "{argument name=\"background color\" default=\"gradiente suave de roxo e azul\"}",
  "header": {
    "logo": "∞ {argument name=\"product name\" default=\"Meta Quest 3\"}",
    "subtitle": "{argument name=\"main catchphrase\" default=\"Uma realidade totalmente nova, a partir de uma estrutura totalmente nova.\"}"
  },
  "layout": {
    "centerpiece": "vista explodida verticalmente empilhada de um headset VR mostrando 9 camadas distintas de componentes internos: revestimento externo, sensores de câmera, placa-mãe com chip, lentes pancake, estrutura interna, baterias, tiras laterais, tira superior e almofada de interface facial.",
    "callout_labels": {
      "count": 8,
      "left_side": [
        "Snapdragon® XR2 Gen 2\nDesempenho de processamento incomparável para experiências em tempo real.",
        "Mecanismo de IPD ajustável\nAjuste confortável para uma ampla gama de usuários.",
        "Tira de cabeça com design de precisão\nErgonomia focada em conforto e estabilidade."
      ],
      "right_side": [
        "Faceplate\nDesign sofisticado e equilíbrio de peso ideal.",
        "Câmeras de rastreamento\nRastreamento de posição de alta precisão e reconhecimento de ambiente.",
        "Lentes Pancake\nDesign fino que oferece amplo campo de visão e imagens nítidas.",
        "Bateria de alto desempenho\nDesign de energia otimizado para suportar longas horas de uso.",
        "Interface facial macia\nConforto garantido mesmo durante longos períodos de uso."
      ]
    },
    "footer": {
      "left_text_block": {
        "headline": "{argument name=\"bottom headline\" default=\"A experiência evolui a partir da estrutura.\"}",
        "body": "Cada peça contém tecnologia de ponta e um design meticuloso que sustenta a experiência imersiva. O Meta Quest 3 cria experiências que parecem vir do futuro, a partir de seu interior."
      },
      "right_logo": "∞ Meta"
    }
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776658772018_lukyfw_HGSUfldbIAEiMWZ.jpg" width="700" alt="Pôster de Vista Explodida de Headset VR - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [wory＠ホッピング中](https://x.com/wory37303852)
- **Fonte:** [Twitter Post](https://x.com/wory37303852/status/2045925660401795478#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13460)**

---

### No. 2: Mapa Ilustrado de Gastronomia da Cidade

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera um mapa turístico desenhado à mão, em estilo aquarela, apresentando especialidades gastronômicas locais numeradas, pontos turísticos e uma legenda.

#### 📝 Prompt

```
{
  "type": "infográfico de mapa ilustrado",
  "style": "{argument name=\"art style\" default=\"ilustração desenhada à mão em aquarela e nanquim sobre pergaminho vintage\"}",
  "title_section": {
    "text": "{argument name=\"city name\" default=\"Chengdu\"} {argument name=\"map title\" default=\"Mapa Gastronômico para Exploradores\"}",
    "mascot": "pimenta vermelha de desenho animado usando óculos escuros e fazendo sinal de positivo"
  },
  "border": "{argument name=\"border decoration\" default=\"videira de folhas verdes e pimentas vermelhas\"}",
  "layout": {
    "background": "papel pergaminho bege texturizado com estradas amarelas, rios azuis e áreas de parque verdes",
    "sections": [
      {
        "title": "pontos turísticos",
        "count": 6,
        "illustrations": ["pavilhão tradicional", "mosteiro tradicional", "arranha-céu moderno com panda escalando", "torre de TV alta", "portão tradicional", "edifícios industriais"],
        "labels": ["Parque do Povo", "Mosteiro Wenshu", "IFS", "Torre de TV 339", "Kuanzhai Alley", "Dongjiao Memory"]
      },
      {
        "title": "locais de comida",
        "count": 12,
        "illustrations": ["mapo tofu", "dumplings no óleo de pimenta", "espetinhos na panela", "bolinhos de arroz glutinoso", "bolo de ovo assado", "hotpot de nove grelhas", "macarrão de batata-doce", "espetinhos frios", "prato misto apimentado", "xícara de chá com tampa", "sobremesa de geleia de gelo", "cabeças de coelho apimentadas"],
        "labels": ["1 Chen Mapo Tofu", "2 Zhong Dumplings", "3 Chunxi Road", "4 Kuanzhai Alley · San Da Pao", "5 Jianshe Road · Ye Popo Egg Cake", "6 Yulin Road · Xiaolongkan Hotpot", "7 Xiangxiang Alley · Feichang Fen", "8 Wuhouci Street · Boboji", "9 Dongjiao Memory · Maojiao Hula", "10 Parque do Povo · Hemin Tea House", "11 Rua Antiga Jinli · Bingfen", "12 Shuangliu Laoma Rabbit Head"]
      },
      {
        "title": "legenda",
        "position": "bottom-right",
        "count": 5,
        "items": ["ponto vermelho", "casa verde", "árvore verde", "linha azul", "linha dupla amarela"],
        "labels": ["Locais de comida", "Pontos turísticos", "Parques e áreas verdes", "Rios e lagos", "Vias principais"]
      }
    ],
    "centerpiece": "panda gigante sentado comendo bambu",
    "bottom_right_extras": ["rosa dos ventos vintage com N, S, L, O", "texto de aviso 'Dica: Cuidado com a pimenta, proteja seu estômago~' com um ícone de pimenta vermelha"]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776662673014_nf0taw_HGRMNDybsAAGG88.jpg" width="700" alt="Mapa Ilustrado de Gastronomia da Cidade - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [皮皮特](https://x.com/mm_zzm44854)
- **Fonte:** [Twitter Post](https://x.com/mm_zzm44854/status/2045861258520568230#reversed-1)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13515)**

---

### No. 3: Slide explicativo do Momotaro em estilo híbrido

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt que combina a estética simples e acolhedora das ilustrações Irasutoya com a alta densidade de informações característica dos slides do governo japonês.

#### 📝 Prompt

```
Crie um slide explicativo ({argument name="format" default="diagrama ponchi-e"}) para {argument name="theme" default="Momotaro"} que funde a atmosfera suave do "Irasutoya" com a densidade de informações impressionante dos "slides de Kasumigaseki".
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414289_t6mebs_HGQQxukbUAA_qc0.jpg" width="700" alt="Slide explicativo do Momotaro em estilo híbrido - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699414149_63j8pd_HGQQy1_aQAAHSqP.jpg" width="700" alt="Slide explicativo do Momotaro em estilo híbrido - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [やまもん](https://x.com/yammamon)
- **Fonte:** [Twitter Post](https://x.com/yammamon/status/2045778624092254603)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=13983)**

---

### No. 4: Mockup de Interface de Live Stream para E-commerce

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma interface realista de transmissão ao vivo em redes sociais sobreposta a um retrato, apresentando mensagens de chat personalizáveis, pop-ups de presentes e um cartão de compra de produto.

#### 📝 Prompt

```
{
  "type": "mockup de interface de live stream",
  "subject": {
    "description": "retrato de {argument name=\"host name\" default=\"Elon Musk\"}, sorrindo, vestindo uma camiseta preta com um gráfico técnico esquemático em branco",
    "background": "o lado esquerdo mostra uma tela com o texto '{argument name=\"left background logo\" default=\"SPACEX\"}', o lado direito mostra um '{argument name=\"right background logo\" default=\"logotipo T da Tesla\"}' vermelho e um carro escuro"
  },
  "ui_overlay": {
    "top_header": {
      "host_info": "avatar, nome '{argument name=\"host name\" default=\"Elon Musk\"}', subtítulo '556 mil curtidas', botão vermelho 'Seguir'",
      "rank_badge": "ícone de moeda dourada com '1º lugar geral'",
      "viewer_stats": "3 avatares de espectadores principais com '123 mil', '86 mil', '57 mil', total '687 mil', botão de fechar 'X'",
      "right_links": "'Mais lives >', 'Galeria de presentes 0/24' com etiqueta azul 'Clássico'"
    },
    "mid_left_gifts": {
      "count": 2,
      "items": [
        "avatar 'Entusiasta de Tecnologia', 'enviou um coração', ícone de coração x 1314",
        "avatar 'Mar de Estrelas', 'enviou um foguete', ícone de foguete x 666"
      ]
    },
    "bottom_left_chat": {
      "system_message": "distintivo de nível 37 'Viajante do Universo entrou na live'",
      "message_count": 7,
      "messages": [
        "Pequeno Foguete: Musk! O futuro é promissor! 🚀",
        "future: Quando sai o Tesla Model 2?",
        "Sonhador do Espaço: A SpaceX consegue chegar a Marte este ano?",
        "Explorador de IA: Como está o progresso da Neuralink?",
        "Usuário Legal: Olá, Sr. Musk!",
        "Mars: Primeira vez na sua live, muito empolgado!",
        "Usuário123: Fale sobre IA, ela vai substituir os humanos?"
      ]
    },
    "bottom_right_product_card": {
      "hot_tag": "laranja 'Mais vendido x 1888'",
      "image": "Tesla Cybertruck",
      "title": "{argument name=\"product name\" default=\"Picape Elétrica Tesla Cybertruck\"}",
      "price": "{argument name=\"product price\" default=\"¥ 1.618.000\"}",
      "button": "botão vermelho 'Comprar'",
      "floating_animation": "corações translúcidos flutuando pela borda direita"
    },
    "bottom_bar": {
      "input_field": "'Diga algo...'",
      "icons": ["rosto sorridente", "três pontos", "carrinho de compras", "caixa de presente", "compartilhar"]
    }
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699445498_ga2ry5_HGO7H0DWkAApdKK.jpg" width="700" alt="Mockup de Interface de Live Stream para E-commerce - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [神经病不想好转](https://x.com/sjbbxhz)
- **Fonte:** [Twitter Post](https://x.com/sjbbxhz/status/2045684734714380687#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14036)**

---

### No. 5: Batalha de Artes Marciais em Estilo Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma cena de ação dinâmica em estilo anime de dois personagens lutando com auras elementais em um dojo tradicional.

#### 📝 Prompt

```
Uma ilustração de anime altamente dinâmica de duas garotas envolvidas em uma batalha feroz de artes marciais dentro de um dojo de madeira tradicional. Em primeiro plano, uma garota com {argument name="character 1 hair" default="cabelo preto em um coque alto com fitas vermelhas"} assume uma postura de artes marciais poderosa e baixa, golpeando com o punho para frente. Ela veste um {argument name="character 1 outfit" default="top estilo chinês branco com borlas vermelhas e calças vermelhas largas"}, com intensos cortes de energia vermelha girando ao redor de seus membros em movimento. No ar, à direita, uma garota com {argument name="character 2 hair" default="cabelo roxo claro em dois coques"} salta graciosamente, sorrindo com confiança enquanto veste um {argument name="character 2 outfit" default="vestido verde escuro com bordados dourados e meia-calça preta"}, acompanhada por rastros de energia azul semelhantes a água. O fundo apresenta o interior de um templo de madeira rústico com uma placa suspensa proeminente lendo "{argument name="sign text" default="武術会"}". A cena é repleta de ação explosiva, poeira voando, tábuas de madeira estilhaçadas, efeitos de partículas coloridas brilhantes e uma iluminação dramática em ângulo baixo que separa perfeitamente os personagens do fundo detalhado.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756799880_c8u8w7_HGUKjjaasAAvVRa.jpg" width="700" alt="Batalha de Artes Marciais em Estilo Anime - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [たねもみ 2.0 / Tanemomi Ver2.0](https://x.com/Tanemomi_Ver2)
- **Fonte:** [Twitter Post](https://x.com/Tanemomi_Ver2/status/2046063806846214265#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13467)**

---

### No. 6: Infográfico de Evolução em Escadaria de Pedra 3D

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Featured](https://img.shields.io/badge/⭐-Featured-gold)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Transforma uma linha do tempo evolutiva plana em um infográfico realista de escadaria de pedra 3D com renderizações detalhadas de organismos e painéis laterais estruturados.

#### 📝 Prompt

```
{
  "type": "infográfico de linha do tempo evolutiva",
  "instruction": "Usando REFERENCE_0 como base estrutural, transforme o design vetorial plano em um infográfico 3D altamente realista. Substitua as rampas lisas por degraus de pedra distintos e atualize todos os organismos para modelos 3D fotorrealistas.",
  "style": {
    "background": "{argument name=\"estilo de fundo\" default=\"papel pergaminho texturizado vintage\"}",
    "staircase": "{argument name=\"material da escadaria\" default=\"blocos de pedra texturizados realistas\"}",
    "subjects": "{argument name=\"estilo dos organismos\" default=\"renderizações 3D fotorrealistas altamente detalhadas\"}"
  },
  "layout": {
    "main_title": "{argument name=\"título principal\" default=\"Evolução Humana\"}",
    "sections": [
      {
        "position": "barra lateral esquerda",
        "count": 8,
        "labels": ["L0: Vida unicelular", "L1: Organismos multicelulares", "L2: Reino animal", "L3: Cordados", "L4: Revolução terrestre", "L5: Classe Mammalia", "L6: Evolução dos hominídeos", "L7: Era do Homo sapiens"]
      },
      {
        "position": "superior direito",
        "title": "Funções ganhas / Funções perdidas",
        "description": "Legenda com ícones de mais e menos"
      },
      {
        "position": "centro inferior",
        "title": "Marcos evolutivos principais",
        "count": 6,
        "description": "Linha do tempo com um gráfico de silhueta de 6 figuras mostrando a evolução de primata para humano"
      }
    ],
    "centerpiece": {
      "description": "Escadaria de pedra em espiral com 25 degraus numerados apresentando organismos específicos.",
      "count": 25,
      "notable_elements": [
        "Degrau 07: Água-viva",
        "Degrau 09: Amonita",
        "Degrau 10: Trilobita",
        "Degrau 24: Humano caminhando",
        "Degrau 25: {argument name=\"conceito de evolução futura\" default=\"silhueta cósmica brilhante com um ponto de interrogação\"}"
      ]
    }
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776661968404_8a5flm_HGQc_KOaMAA2vt0.jpg" width="700" alt="Infográfico de Evolução em Escadaria de Pedra 3D - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [知识猫图解](https://x.com/GeekCatX)
- **Fonte:** [Twitter Post](https://x.com/GeekCatX/status/2045792240044511277#reversed-1)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13491)**

---

## 📋 Todos os prompts

> 📝 Ordenado por data de publicação (mais recente primeiro)

### No. 1: Perfil / Avatar - Selfie no espelho com ângulo superior e poses exageradas

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt para testar a consistência de personagens e expressões dinâmicas em uma selfie no espelho a partir de uma perspectiva de cima para baixo.

#### 📝 Prompt

```
{argument name="number of people" default="Três pessoas"} em frente a um espelho a partir de uma perspectiva superior tirando uma foto em grupo com {argument name="pose type" default="poses exageradas"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883059359_gs8st0_HGggJqAakAACacS.jpg" width="600" alt="Perfil / Avatar - Selfie no espelho com ângulo superior e poses exageradas - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Fonte:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046921531322974390)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** zh

**[👉 Experimente agora →](https://gptimage2api.net/?id=14341)**

---

### No. 2: Perfil / Avatar - Retrato de estúdio monocromático em tons de marrom

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato de moda fotorrealista em ambiente interno de uma mulher sentada com um look coordenado em tons de marrom, ideal para fotografia editorial de estilo de vida ou vestuário.

#### 📝 Prompt

```
Um retrato de estúdio realista de uma jovem mulher do leste asiático sentada em uma cadeira dobrável preta simples, enquadrada da parte superior das coxas até a cabeça em uma composição vertical. Ela tem cabelo {argument name="hair color" default="castanho escuro"} repartido próximo ao centro e preso em um rabo de cavalo baixo, com algumas mechas suaves perto das orelhas, brincos pequenos e delicados, pele clara e lisa, e uma pose calma e neutra com as mãos descansando juntas entre os joelhos. Ela veste um top cropped justo com zíper frontal e textura canelada na cor {argument name="top color" default="marrom chocolate profundo"}, com gola pontuda, mangas três quartos e o zíper parcialmente aberto para criar um decote profundo, combinado com calças de cintura alta e pernas retas em um tom {argument name="pants color" default="marrom quente"} correspondente. O estilo é monocromático, tom sobre tom, com textura de tecido sutil e contornos corporais naturais. O fundo é um tecido drapeado em tom off-white suave com dobras delicadas, iluminado por uma luz de janela difusa e natural para um visual interno limpo, suave e editorial. Fotorrealista, profundidade de campo rasa, sombras suaves, retrato de moda discreto, cenário minimalista, sujeito centralizado, postura sentada relaxada, alta definição de pele e textura de tecido.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175128_315f91_HGgQ_wVagAAlVCQ.jpg" width="600" alt="Perfil / Avatar - Retrato de estúdio monocromático em tons de marrom - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fonte:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14628)**

---

### No. 3: Perfil / Avatar - Retrato Fotorrealista em Santuário com Uniforme Escolar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato fotorrealista e refinado de uma jovem com uniforme escolar ao ar livre, ideal para moda editorial, visuais de personagens ou retratos de IA com estilo lifestyle.

#### 📝 Prompt

```
Um retrato fotorrealista, do busto para cima, de uma {argument name="subject" default="jovem"} em pé ao ar livre sob luz solar natural e brilhante, enquadrada em uma composição vertical. Ela tem cabelos longos e lisos de cor {argument name="hair color" default="castanho-escuro"} com um brilho acetinado, repartidos levemente fora do centro e caindo sobre os dois ombros. Ela veste uma camisa de uniforme escolar branca de manga curta impecável, com colarinho estruturado, uma gravata listrada azul-marinho e um emblema bordado detalhado no bolso esquerdo do peito, apresentando uma coroa e um brasão heráldico. Posicione-a em um ângulo de três quartos com postura relaxada, com a cabeça virada sutilmente para o lado para um toque refinado de foto de moda espontânea. Coloque-a em frente a um {argument name="background setting" default="santuário vermelho"} vívido, com pilares vermelhos ricos e detalhes de um telhado azul curvo visíveis no fundo desfocado, utilizando profundidade de campo rasa e um bokeh suave para manter o foco nítido no sujeito. A iluminação deve ser limpa, de alto contraste e favorecedora, com brilhos intensos no cabelo e na camisa, dobras de tecido realistas, tons de pele naturais e uma estética de retrato premium polida, que remete à fotografia comercial japonesa.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883130126_mqzubl_HGfUniwagAA00Cs.jpg" width="600" alt="Perfil / Avatar - Retrato Fotorrealista em Santuário com Uniforme Escolar - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AIおじさん](https://x.com/AIojisan1952)
- **Fonte:** [Twitter Post](https://x.com/AIojisan1952/status/2046838384887504974#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14515)**

---

### No. 4: Perfil / Avatar - Retrato de selfie em ambiente interno com censura e estilo moody

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma selfie estilosa e fotorrealista de um jovem com camisa de gola aberta perto de uma janela, ideal para criar fotos de retrato convincentes para redes sociais.

#### 📝 Prompt

```
Um retrato realista em estilo selfie de um jovem homem do leste asiático, do peito para cima, sentado perto de uma grande janela moderna em um apartamento ou quarto de hotel em um andar alto durante a luz suave do dia. Ele tem cabelo {argument name="hair color" default="preto"}, espesso e levemente despenteado, com risca central e volume suave sobre a testa e as laterais. Sua estrutura parece esguia, com pescoço longo e pele clara e lisa. Ele veste uma camisa de botão {argument name="shirt color" default="preta"} feita de algodão fosco ou popeline, levemente oversized, com os botões superiores abertos para criar uma gola profunda e um estilo casual e descontraído. A câmera é segurada próxima em um ângulo natural de selfie, orientação retrato, enquadrando os ombros, peito, pescoço e cabeça. Seu rosto está totalmente obscurecido por um grande bloco de censura retangular centralizado (mosaico ou desfoque), enquanto as orelhas, o contorno da mandíbula, o pescoço e o cabelo permanecem visíveis. O clima é discreto, melancólico e elegante, com cores neutras suaves, luz de janela suave vindo do lado direito, sombras gentis e uma sensação de selfie espontânea para redes sociais. Os detalhes do fundo incluem 1 seção de parede bege à esquerda, 1 pequeno painel de controle escuro na parede, 1 acabamento metálico vertical ou borda de luminária e 2 painéis de janela altos com moldura escura à direita, com um horizonte urbano levemente desfocado ao fundo. Foto de smartphone fotorrealista, interior moderno e limpo, profundidade de campo rasa, textura de pele natural, contraste sutil, sem sorriso visível devido ao bloco de censura, edição mínima, selfie pessoal estilosa e convincente.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199795_5d57h2_HGe0FIpaIAAU-CO.jpg" width="600" alt="Perfil / Avatar - Retrato de selfie em ambiente interno com censura e estilo moody - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [MathMedix](https://x.com/MathMedix)
- **Fonte:** [Twitter Post](https://x.com/MathMedix/status/2046802557872562478#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14686)**

---

### No. 5: Perfil / Avatar - Retrato de selfie realista no McDonald's

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma selfie casual fotorrealista de um homem dentro de um McDonald's, útil para criar fotos de restaurante com estilo de rede social que pareçam autênticas.

#### 📝 Prompt

```
Uma selfie casual de smartphone altamente realista tirada em um restaurante McDonald's na Ásia, enquadrada como um retrato do peito para cima de um jovem sentado à mesa. A câmera é segurada um pouco acima da altura da mesa, à distância de um braço, criando uma perspectiva natural de selfie frontal com um antebraço estendido em direção à lente. O sujeito veste uma camiseta preta com um pequeno logotipo branco da Tesla no lado esquerdo do peito, tem cabelo preto curto e liso, armações de óculos escuras e finas parcialmente visíveis, e descansa uma das mãos levemente contra o queixo em uma pose relaxada. Seu rosto está totalmente obscurecido por um grande bloco retangular de desfoque sólido no centro, preservando a privacidade enquanto deixa visíveis o cabelo, as orelhas, as linhas do maxilar e as hastes dos óculos. No primeiro plano inferior esquerdo, há 1 copo de papel branco do McDonald's com tampa e canudo branco, cortado pelo enquadramento. O fundo mostra a área do balcão do restaurante com iluminação ambiente quente, 1 grande painel de parede vermelho à esquerda apresentando os arcos amarelos do McDonald's e o slogan branco “i’m lovin’ it” com texto em chinês abaixo, 4 painéis de menu digitais iluminados no topo exibindo hambúrgueres, batatas fritas, combos, preços e texto em chinês, além de 2 pessoas ao fundo perto do balcão, uma de costas com uma mochila e outra parcialmente visível atrás do caixa. Use equilíbrio de cores natural, leve granulação de ambiente interno, reflexos realistas, profundidade de campo de rasa a moderada e o visual espontâneo de uma foto de rede social não posada.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097033_ly0rvn_HGeaa6Sa8AAuokd.jpg" width="600" alt="Perfil / Avatar - Retrato de selfie realista no McDonald's - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Fonte:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14433)**

---

### No. 6: Perfil / Avatar - Snapshot de Cosplay da Albedo no Instagram

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt conciso para gerar uma foto de cosplay rebelde e expressiva no estilo de um story do Instagram.

#### 📝 Prompt

```
Estilo: Um snapshot de story do Instagram de um cosplay de {argument name="character" default="Albedo"}; Conteúdo: {argument name="action" default="agachada no chão de frente para a câmera, fazendo gestos rebeldes exagerados com ambas as mãos, revirando os olhos, com uma expressão arrogante e desdenhosa"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062651_jcngq2_HGd6Wl3aIAA8p2K.jpg" width="600" alt="Perfil / Avatar - Snapshot de Cosplay da Albedo no Instagram - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [𝟡𝟜 𝚅̷𝙰̷𝙽̷ ᴾᴸᴬʸᶠᴼᴿᴳᴱ](https://x.com/94vanAI)
- **Fonte:** [Twitter Post](https://x.com/94vanAI/status/2046739103316947296)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** zh

**[👉 Experimente agora →](https://gptimage2api.net/?id=14347)**

---

### No. 7: Perfil / Avatar - Garota-gato no telhado da escola ao pôr do sol estilo anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um retrato cinematográfico em estilo anime de uma estudante com orelhas de gato no telhado ao pôr do sol, ideal para key visuals nostálgicas, arte de personagens ou imagens para redes sociais.

#### 📝 Prompt

```
Uma ilustração de anime de alta qualidade de uma {argument name="character type" default="estudante com orelhas de gato"} inclinada sobre o parapeito metálico do telhado de uma escola ao pôr do sol, vista de um ângulo levemente baixo e próximo de três quartos. Ela tem longos cabelos {argument name="hair color" default="castanho-escuros"} esvoaçantes com reflexos suaves, grandes olhos reflexivos castanho-acinzentados, óculos redondos de aro fino e 2 orelhas de gato felpudas surgindo de seu cabelo. Sua expressão é tranquila, nostálgica e levemente tímida, com lábios entreabertos e um olhar suave voltado para baixo em direção ao espectador. Ela veste um uniforme escolar japonês estilo marinheiro com uma blusa de manga comprida {argument name="uniform color" default="rosa"} suave, um colarinho de marinheiro cinza com listras brancas, um laço de lenço vermelho vivo e uma saia xadrez parcialmente visível, com 2 alças de mochila escuras sobre os ombros. A cena é banhada por uma iluminação dramática de 'golden hour', com uma luz de contorno quente e intensa ao longo de seu cabelo, orelhas, ombros e mangas, brilho solar vindo do canto inferior esquerdo e um céu ricamente pintado com nuvens alaranjadas e cor de pêssego. Ao fundo, exiba um prédio escolar japonês de 2 andares com telhado de telhas vermelhas e janelas brilhantes iluminadas pelo pôr do sol. Enfatize a qualidade visual de anime de alto nível do início dos anos 2000, traços delicados, olhos luminosos, mechas de cabelo detalhadas, composição cinematográfica, profundidade de campo suave, gradação de cores quentes e vibrantes, sombreamento polido e uma atmosfera serena e emocional.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142749_ioqmur_HGd6QaOa4AAwOOi.jpg" width="600" alt="Perfil / Avatar - Garota-gato no telhado da escola ao pôr do sol estilo anime - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Nobu-Kobayashi : Generative AI Technology](https://x.com/nyaa_toraneko)
- **Fonte:** [Twitter Post](https://x.com/nyaa_toraneko/status/2046739011960799389#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14547)**

---

### No. 8: Perfil / Avatar - Mulher de fantasia abraçando um carneiro branco

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato realista de fantasia medieval de uma mulher ruiva abraçando um carneiro branco com chifres, ideal para arte de personagem atmosférica ou visuais de fantasia em estilo editorial.

#### 📝 Prompt

```
Um retrato vertical fotorrealista e cinematográfico de uma mulher medieval ou de fantasia com {argument name="hair color" default="longos cabelos ruivos acobreados"}, exibida do peito para cima, abraçando suavemente um grande carneiro branco. A mulher veste um vestido ou túnica de lã verde-musgo escuro com punhos bordados ornamentados e uma capa ou xale pesado com acabamento em pele sobre os ombros, evocando uma estética viking ou das terras altas. Seu cabelo é espesso, ondulado e levemente despenteado pelo vento, com pequenas tranças entrelaçadas na coroa. O carneiro possui uma lã densa e encaracolada de cor branco-creme, uma expressão calma com os olhos fechados e chifres espirais proeminentes que se curvam para fora e para frente. A mão da mulher repousa ternamente no pescoço do carneiro, transmitindo calor, proteção e companheirismo. Ambientado ao ar livre em uma paisagem acidentada e nublada, com colinas ou charnecas suavemente desfocadas ao fundo, céu cinza frio, profundidade de campo rasa, iluminação natural difusa, detalhes de textura ricos em cabelo, lã, pele e tecido, paleta de cores terrosas e suaves, enquadramento íntimo, pele e características animais realistas. Adicione um texto em preto no canto superior esquerdo escrito {argument name="corner text" default="GPT Image 2"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883171366_yuw1xa_HGdrgu-W4AA-KGq.jpg" width="600" alt="Perfil / Avatar - Mulher de fantasia abraçando um carneiro branco - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Adan Avelar Islas](https://x.com/adanvecindad)
- **Fonte:** [Twitter Post](https://x.com/adanvecindad/status/2046722781631439244#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14619)**

---

### No. 9: Perfil / Avatar - Retrato de Ídolo Kawaii Rosa com Batom

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato brilhante no estilo ídolo de anime para pôsteres, artes de redes sociais ou visuais de personagens fofas.

#### 📝 Prompt

```
Um retrato de ídolo de anime altamente detalhado e brilhante em composição vertical, mostrando uma garota adolescente fofa da cintura para cima em uma estética kawaii rosa dos sonhos. Ela tem cabelos {argument name="hair color" default="rosa pastel"} estilizados em um rabo de cavalo alto, volumoso e muito longo, com franja suave e mechas cacheadas fluidas, decorados com vários pequenos clipes de coração e grampos cruzados. Seus olhos são grandes, brilhantes e de um {argument name="eye color" default="verde esmeralda"} vívido, com reflexos em forma de estrela, cílios longos e um brilho levemente lacrimejante. Ela tem um blush suave, lábios pequenos e brilhantes, e uma expressão afetuosa enquanto aplica batom {argument name="lipstick color" default="rosa choque"}, segurando o tubo de batom delicadamente com as duas mãos perto da boca. Ela veste um vestido de ídolo lolita gótico preto e rosa com babados, rendas, fitas, laços, ornamentos de coração e texturas brilhantes, além de 1 tiara de laço de renda preta com um coração de joia rosa, 3 acessórios de cabelo visíveis na franja, 1 par de brincos de coração pendentes e 1 gargantilha preta com um pequeno pingente de coração. Cerque a personagem com um fundo rosa-doce brilhante e cheio de glitter, repleto de bokeh, faíscas, efeitos de luz neon suave e uma atmosfera de fã de ídolo. Adicione 5 balões de texto em forma de coração desenhados à mão em japonês ao redor dela, lendo: "かわいすぎてごめん…♡" (Desculpe por ser tão fofa…♡), "推してくれてありがとうっ♡" (Obrigada por me apoiar♡), "ずーっとだいすきっ♡" (Te amo para sempre♡), "世界でいちばんの推しになってね…♡" (Seja meu fã número um no mundo…♡) e "ずっと一緒だよ？約束ね…♡" (Estaremos sempre juntos, ok? É uma promessa…♡). Inclua um pequeno cartão fotográfico ou pôster decorado da mesma garota no fundo superior direito. Ilustração ultra-polida, brilho denso, iluminação romântica, reflexos brilhantes, detalhes de renda intrincados, fundo com foco suave, paleta rosa saturada, sensação de pôster de ídolo adorável.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166743_xorm6h_HGdqYtPbgAEXEjW.jpg" width="600" alt="Perfil / Avatar - Retrato de Ídolo Kawaii Rosa com Batom - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ねね*AIcreator](https://x.com/NeneneAI)
- **Fonte:** [Twitter Post](https://x.com/NeneneAI/status/2046721817893872064#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14606)**

---

### No. 10: Perfil / Avatar - Pelicano Minimalista Andando de Bicicleta

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma ilustração vetorial geométrica minimalista de um pelicano em uma bicicleta, útil para testar a composição de formas simples ou criar uma imagem divertida no estilo de ícone abstrato.

#### 📝 Prompt

```
Uma ilustração minimalista em estilo vetorial sobre um fundo cinza-claro plano, mostrando um pelicano andando de bicicleta, desenhado a partir de formas geométricas simples com contornos grossos em cinza-carvão. A composição é ampla e centralizada, com a bicicleta ocupando os dois terços inferiores da imagem e a cabeça do pássaro flutuando ligeiramente acima e à frente do guidão, de uma maneira deliberadamente abstrata e semelhante a um diagrama. A bicicleta é uma silhueta simples de uma bicicleta de estrada preta, vista de lado, com exatamente 2 rodas grandes, cada uma com uma borda externa grossa e exatamente 4 linhas de raios visíveis formando uma cruz, uma linha de solo horizontal reta abaixo de ambas as rodas, um quadro triangular, um selim preto curto e detalhes simplificados de pedivela e pedal perto da parte traseira do quadro. O pelicano é construído a partir de peças abstratas limpas: uma cabeça branca arredondada com um pequeno olho circular preto, um bico longo e aberto apontando para a esquerda feito de 2 partes, com uma seção triangular laranja superior e uma seção de bolsa rosa-clara inferior, uma curva escura curta no topo da cabeça, um pequeno conector de pescoço/corpo oval branco separado, um corpo arredondado branco maior posicionado sobre a bicicleta e uma única forma de asa branca inclinada para cima sobre as costas. Adicione exatamente 2 formas de pernas laranjas, retângulos longos e estreitos inclinados para baixo a partir do corpo em direção ao quadro da bicicleta, sugerindo que o pássaro está pedalando. Mantenha as formas intencionalmente esparsas e levemente surreais, como um teste de logotipo ou um rabisco simples de editor de código, sem sombreamento, sem gradientes, sem texturas, sem texto e com muito espaço negativo.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883188180_o6j3h9_HGdj-7yWsAAi5Zj.png" width="600" alt="Perfil / Avatar - Pelicano Minimalista Andando de Bicicleta - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Justin Schroeder](https://x.com/jpschroeder)
- **Fonte:** [Twitter Post](https://x.com/jpschroeder/status/2046714718790816171#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14657)**

---

### No. 11: Perfil / Avatar - Transformação de Retrato de Gato para Humano

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt converte uma foto de referência de um gato em uma versão humana fotorrealista, preservando a pose, a composição e o cenário originais para retratos divertidos de pets transformados em pessoas.

#### 📝 Prompt

```
Usando a imagem de referência fornecida, transforme o gato em um retrato humano realista, mantendo a mesma pose de descanso, ângulo de câmera, enquadramento e o mesmo fundo com a poltrona turquesa de pelúcia. Preserve o padrão de cores laranja e branco do gato como inspiração para o visual humano: faça da pessoa uma jovem de pele clara com cabelos ruivos quentes e uma expressão suave e calma. Vista-a com roupas confortáveis em tom off-white: 1 suéter de tricô solto com decote em V e 1 calça de sarja com cordão na cor creme, sentada naturalmente na poltrona com uma linguagem corporal relaxada. Torne a imagem fotorrealista, com iluminação interna natural suave e qualidade de foto editorial de estilo de vida.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883192227_47aujy_HGddzviXQAAIE28.jpg" width="600" alt="Perfil / Avatar - Transformação de Retrato de Gato para Humano - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Bojan Tunguz](https://x.com/tunguz)
- **Fonte:** [Twitter Post](https://x.com/tunguz/status/2046707703481852106#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14670)**

---

### No. 12: Perfil / Avatar - Retrato de Estúdio com Sorvete de Morango

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato de estúdio elegante, estilo celebridade, de uma mulher de cabelos escuros segurando uma casquinha de sorvete de morango na frente do rosto, ideal para editoriais de beleza ou imagens de cultura pop.

#### 📝 Prompt

```
Um retrato de estúdio refinado de uma mulher com aparência de estrela pop, do peito para cima, centralizada contra um fundo cinza neutro e suave. Ela tem {argument name="hair color" default="preto azeviche"} cabelos longos, soltos e ondulados, com risca central, brilho intenso e volume suave caindo sobre os dois ombros. Seu rosto está parcialmente escondido atrás da casquinha de sorvete que ela segura na frente da boca e da parte inferior do rosto, criando uma composição editorial de moda divertida. Ela veste uma regata branca canelada com alças largas e um único brinco de strass visível. Em sua mão, há 1 casquinha de waffle com 1 bola grande de sorvete de morango rosa, com redemoinhos de frutas vermelhas e uma textura levemente derretida. Iluminação de beleza quente e favorecedora, sombras suaves, tons de pele realistas, fotografia de retrato de celebridade de alto nível, foco nítido na mão, na casquinha, no cabelo e nos ombros, fundo minimalista, atmosfera sutilmente sensual e chique, corte vertical.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883161484_6r3xlw_HGdTO_1bkAAtzWs.jpg" width="600" alt="Perfil / Avatar - Retrato de Estúdio com Sorvete de Morango - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Arturo Garrido](https://x.com/arturogarrido)
- **Fonte:** [Twitter Post](https://x.com/arturogarrido/status/2046696077018186053#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14594)**

---

### No. 13: Perfil / Avatar - Retrato em Nuvem de Pontos Censurado

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera um retrato em estilo lidar, em preto e branco, de um homem de terno formado por partículas brancas densas, ideal para visuais de tecnologia editorial, temas de privacidade ou imagens de identidade futuristas.

#### 📝 Prompt

```
Um retrato monocromático minimalista feito inteiramente de milhões de pequenos pontos de nuvem de pontos brancos sobre um fundo preto absoluto, mostrando 1 homem adulto do peito para cima, vestindo um blazer formal escuro e uma camisa social clara. O sujeito está centralizado ligeiramente à direita, voltado para a frente com um sutil giro de três quartos, com cabelo curto bem penteado e uma orelha visível definida nitidamente por partículas densas semelhantes a lidar. Renderize a figura como dados brutos de escaneamento 3D misturados com lógica de contorno topológico: pontilhismo ultra-denso, posicionamento geométrico preciso dos pontos, estrutura de isolinhas tênue e modelagem de profundidade limpa no cabelo, lapelas do paletó, colarinho, pescoço e ombros. Mantenha o rosto intencionalmente obscurecido por 1 grande bloco retangular vertical de censura em cinza escuro a preto, perfeitamente centralizado sobre a área facial, da testa até abaixo do nariz, criando um efeito marcante de máscara de privacidade. Use textura fosca, bordas nítidas, foco preciso, alto contraste, sem brilho, sem efeito bloom, sem neon, sem neblina, sem desfoque de movimento, sem aberração cromática, sem pinceladas artísticas. Adicione 1 pequeno ícone de brilho de quatro pontas em cinza claro no canto inferior direito. A imagem geral deve parecer matemática, forense e futurista, como um retrato de escaneamento lidar de alta resolução em 8k.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087494_gme15e_HGdKX1_bMAApLt-.jpg" width="600" alt="Perfil / Avatar - Retrato em Nuvem de Pontos Censurado - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883087529_r1ivcd_HGdKYY9aMAAELgh.jpg" width="600" alt="Perfil / Avatar - Retrato em Nuvem de Pontos Censurado - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [Harshith](https://x.com/HarshithLucky3)
- **Fonte:** [Twitter Post](https://x.com/HarshithLucky3/status/2046686345230512264#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14408)**

---

### No. 14: Perfil / Avatar - Deus grego montando um leão

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt cinematográfico para gerar uma imagem épica de uma pessoa retratada como um deus grego montando um leão pela savana africana.

#### 📝 Prompt

```
faça com que eu pareça um {argument name="persona" default="deus grego"} montando um {argument name="mount" default="leão"} nas {argument name="setting" default="planícies da áfrica"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050662_t5u3gv_HGdDTMPXEAEYRdB.jpg" width="600" alt="Perfil / Avatar - Deus grego montando um leão - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883050703_wc1jy4_HGdDWCcXUAAoQAT.jpg" width="600" alt="Perfil / Avatar - Deus grego montando um leão - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [Max Blade](https://x.com/_MaxBlade)
- **Fonte:** [Twitter Post](https://x.com/_MaxBlade/status/2046679494883238031)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14326)**

---

### No. 15: Perfil / Avatar - Retrato de garota anime loira confusa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato simples de busto em estilo anime de uma garota confusa vestindo um suéter azul, ideal para avatares, artes de perfil ou ilustrações casuais de personagens.

#### 📝 Prompt

```
Um retrato anime suave e minimalista de uma jovem fofa, da cintura para cima, contra um fundo cinza claro simples, desenhado em um estilo pastel limpo com traços finos semelhantes a um esboço e cores planas e suaves. Ela tem cabelos longos e fluidos em um tom loiro pálido com camadas suaves e franjas longas cobrindo parcialmente a testa, olhos grandes e redondos em azul claro, pele clara e uma boca pequena levemente aberta que transmite uma leve confusão. Ela veste uma blusa de manga comprida oversized {argument name="clothing color" default="light pastel blue"} com um decote largo e descontraído. Sua pose está levemente inclinada em direção ao observador, com uma mão levantada e um dedo indicador tocando a lateral da cabeça como se estivesse intrigada. Coloque exatamente 1 ponto de interrogação azul flutuante próximo ao lado superior esquerdo da cabeça dela. A expressão deve parecer inocente, distraída e cativante. Mantenha a composição centralizada, arejada e organizada, sem objetos extras, sem fundo detalhado e sem sombras fortes.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113953_9ftbye_HGdCi68awAAvIX4.jpg" width="600" alt="Perfil / Avatar - Retrato de garota anime loira confusa - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113895_coi544_HGdC-GqbQAArPMf.jpg" width="600" alt="Perfil / Avatar - Retrato de garota anime loira confusa - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113829_fl4pcc_HGdDWg_bEAAL-41.jpg" width="600" alt="Perfil / Avatar - Retrato de garota anime loira confusa - Image 3">
</div>

#### 📌 Detalhes

- **Autor:** [Torishima / INTP](https://x.com/izutorishima)
- **Fonte:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14474)**

---

### No. 16: Perfil / Avatar - Retrato de Garota Anime em Tons de Azul Suave

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato minimalista em estilo anime de uma garota de cabelos azuis usando um moletom azul-claro oversized, ideal para avatares, fotos de perfil ou arte de personagem delicada.

#### 📝 Prompt

```
Um retrato estilo anime, do busto para cima, de uma jovem fofa centralizada em um fundo off-white quente e simples, desenhado com traços delicados e coloração pastel plana. Ela tem cabelos muito longos e lisos {argument name="hair color" default="azul-celeste pálido"} com mechas finas, franja cheia levemente repartida perto do centro e grandes olhos azuis combinando com brilhos intensos. Sua expressão é tímida e confusa, com as sobrancelhas levemente arqueadas, um leve rubor rosa nas bochechas e uma pequena boca entreaberta. Ela olha diretamente para o espectador enquanto toca levemente o lábio inferior com o dedo indicador em uma pose pensativa e hesitante. Ela veste um moletom oversized {argument name="top color" default="azul-claro"} com mangas longas que cobrem parcialmente sua mão. Enquadre a imagem do peito para cima, com a cabeça levemente inclinada, transmitindo uma sensação suave, inocente e sonhadora. Use uma composição minimalista, sem acessórios, sem objetos extras, sem cenário e sem texto. Enfatize uma paleta azul monocromática, simplicidade leve, contornos sutis semelhantes a esboços e uma estética de ilustração japonesa limpa, adequada para um avatar pessoal suave.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883113864_w40gbf_HGdDboubUAAdZhY.jpg" width="600" alt="Perfil / Avatar - Retrato de Garota Anime em Tons de Azul Suave - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Torishima / INTP](https://x.com/izutorishima)
- **Fonte:** [Twitter Post](https://x.com/izutorishima/status/2046679150279446678#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14473)**

---

### No. 17: Perfil / Avatar - Retrato de Selfie no Espelho em Ambiente Interno de Luxo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma selfie realista no espelho, com estilo de moda, de uma mulher em um vestido marfim justo, útil para imagens de estilo de vida, looks ou glamour para redes sociais.

#### 📝 Prompt

```
Uma selfie realista no espelho em ambiente interno de uma jovem esbelta e glamorosa, de pé em uma sala de estar ou suíte de hotel sofisticada e com iluminação suave, fotografada verticalmente da cabeça até abaixo dos joelhos. Ela veste um vestido midi justo na cor creme ou marfim, com drapeados e franzidos elegantes, apresentando um decote assimétrico com 1 alça cruzando diagonalmente sobre o peito e deixando o outro ombro à mostra. Seu cabelo é longo, castanho escuro, levemente ondulado e repartido próximo ao centro, caindo sobre ambos os ombros. Ela segura um smartphone na mão direita à frente do rosto, cobrindo-o parcialmente, com o aparelho voltado para um espelho de parede; o telefone possui uma capa escura com estampa de nuvem vermelha. Seu braço esquerdo pende naturalmente ao lado do corpo. Adicione joias sutis: 1 colar fino com um pequeno pingente, 1 pulseira ou bracelete de prata no pulso direito e anéis nos dedos da mão que segura o telefone. Enfatize uma silhueta feminina realista, pele lisa, iluminação ambiente quente e suave, e fotografia com estilo editorial polido para redes sociais. O fundo deve incluir 1 sofá bege atrás dela, 1 bolsa de couro marrom descansando no lado direito do sofá, 1 parede de destaque de pedra ou concreto texturizado atrás da área do espelho e um corredor quente à esquerda com 2 obras de arte emolduradas visíveis. Use sombras naturais de ambiente interno, textura de pele refinada, dobras de tecido realistas e compressão ao redor da cintura e quadris, estética de apartamento de luxo, composição limpa e alto nível de detalhe.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883092153_cm1rks_HGdDJC8WcAAOm_A.jpg" width="600" alt="Perfil / Avatar - Retrato de Selfie no Espelho em Ambiente Interno de Luxo - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Danna R.](https://x.com/daaaaanc)
- **Fonte:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14421)**

---

### No. 18: Perfil / Avatar - Selfie realista no espelho com vestido branco

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma selfie de moda realista no espelho dentro de um apartamento com iluminação quente, ideal para fotos de looks, conteúdo de estilo de vida e comparações de realismo.

#### 📝 Prompt

```
Uma selfie realista no espelho de uma jovem esguia em pé na sala de estar de um apartamento moderno com iluminação quente, vestindo um vestido midi justo de um ombro só na cor branco-marfim, com drapeados no tronco e nos quadris. Ela tem cabelos castanhos escuros lisos na altura dos ombros com risca central, joias minimalistas incluindo 2 anéis, uma pulseira de prata e brincos pequenos e discretos. Seu rosto está oculto pelo telefone enquanto ela tira a foto com uma mão levantada, segurando um smartphone com capa preta decorada com motivos de nuvens vermelhas. Ela está levemente inclinada com uma postura relaxada, um braço ao lado do corpo, exibindo uma silhueta feminina natural. A cena é enquadrada verticalmente como uma selfie casual de look para redes sociais. Atrás dela, há um sofá de tecido bege com 1 almofada estampada com motivo geométrico cinza e 1 bolsa de couro marrom-taupe colocada no assento. O fundo inclui uma parede de destaque em bronze-marrom texturizado, piso de cerâmica creme brilhante, um corredor escuro à esquerda com 3 quadros na parede e luzes embutidas quentes no teto. Iluminação ambiente suave de fim de tarde, tons de pele naturais, tensão e dobras de tecido realistas, reflexos sutis no espelho, estética de apartamento sofisticado e limpo, alto realismo, textura de pele fotorrealista, perspectiva de câmera de smartphone.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883091680_gc1kqf_HGdDIHqXEAEbhzg.jpg" width="600" alt="Perfil / Avatar - Selfie realista no espelho com vestido branco - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Danna R.](https://x.com/daaaaanc)
- **Fonte:** [Twitter Post](https://x.com/daaaaanc/status/2046678589739839969#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14419)**

---

### No. 19: Perfil / Avatar - Retrato de Vestido de Luxo em Santorini

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato fotorealista de moda e viagem na vertical de uma mulher glamorosa em um vestido branco posando em Santorini, ideal para imagens de férias de luxo, estilo de vida ou editorial.

#### 📝 Prompt

```
Um retrato glamoroso de moda e viagem de uma {argument name="woman" default="mulher loira"} sentada em uma borda de pedra iluminada pelo sol com vista para a caldeira em Santorini, Grécia, com edifícios caiados de branco na encosta descendo em direção a um mar azul profundo e ilhas vulcânicas acidentadas ao fundo. Ela veste um vestido fluido de marfim com decote frente única muito profundo, recortes laterais, cintura franzida com detalhe de anel circular e tecido plissado macio sobre o colo. Seu cabelo é longo, ondulado e de cor {argument name="hair color" default="loiro dourado"}, estilizado solto sobre os ombros. Adicione colares delicados em camadas, incluindo um pequeno pingente e uma cruz de prata, além de uma pulseira ou relógio em um dos pulsos. Coloque uma clássica igreja grega branca com uma cúpula de cor {argument name="dome color" default="azul"} brilhante no canto superior direito ao fundo, e emoldure o lado direito da imagem com flores de buganvília de cor {argument name="flower color" default="rosa magenta"} vívidas em plena floração. A iluminação é de sol forte do meio-dia mediterrâneo com reflexos nítidos, brilho suave na pele e uma profundidade de campo gentil que mantém a mulher em foco nítido enquanto a arquitetura de fundo e o mar ficam levemente suavizados. A composição é vertical, elegante e aspiracional, com a mulher centralizada ligeiramente à direita, torso visível até a saia fluida, com o litoral cênico estendendo-se pela metade esquerda do quadro. Adicione um pequeno texto em preto no canto superior esquerdo escrito {argument name="corner text" default="GPT V2"}. Estética de férias de luxo fotorealista, alto detalhe, cores naturais, vibe editorial de viagem para o Instagram.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094779_1iys4p_HGc_qAbXkAAJFk0.jpg" width="600" alt="Perfil / Avatar - Retrato de Vestido de Luxo em Santorini - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Ed](https://x.com/Eduardopto)
- **Fonte:** [Twitter Post](https://x.com/Eduardopto/status/2046675324067258535#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14428)**

---

### No. 20: Perfil / Avatar - Retrato com estilo de filme Fuji japonês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt incrivelmente detalhado para gerar retratos com estética Fujifilm de alta qualidade, com uma sensação matinal suave, natural e íntima.

#### 📝 Prompt

```
9:16 vertical — {argument name="film style" default="estilo de filme Fuji japonês"} retrato, sujeito único

Estética analógica Fujifilm (sensação Pro 400H / Superia), tons pastéis suaves, leve desvio verde-magenta, baixo contraste, transição suave de realces, granulação de filme fina, halação sutil

ambiente interno no início da manhã perto da janela, cortinas leves, luz do dia fresca

{argument name="subject" default="jovem ídolo japonesa"}, maquiagem natural mínima, textura de pele fresca e suave

vestuário: camisa oversized com shorts soltos, estilo casual de ficar em casa, não revelador

cabelo: levemente bagunçado, volume natural, sensação de quem acabou de acordar

pose: sentada na beira da cama ou perto da janela, corpo levemente inclinado para frente, ombros relaxados; uma mão segurando levemente uma pequena flor ou tecido, a outra descansando naturalmente

expressão: olhar suave, levemente sonolento, calmo e natural

iluminação: {argument name="lighting" default="luz suave da manhã"}, difusa, sombras suaves

atmosfera: momento cotidiano silencioso, fresco e íntimo

qualidade: ultrarrealista, granulação de filme, leve suavidade, imperfeições naturais
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883040570_763zc0_HGc0HfYaMAAEgPM.jpg" width="600" alt="Perfil / Avatar - Retrato com estilo de filme Fuji japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [BubbleBrain](https://x.com/BubbleBrain)
- **Fonte:** [Twitter Post](https://x.com/BubbleBrain/status/2046661936381911182)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14301)**

---

### No. 21: Publicação em Redes Sociais - Grade de 4 Painéis para Banners Digitais Japoneses

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma grade 2x2 de banners publicitários digitais japoneses distintos para viagens, cuidados com a pele, gastronomia e educação online.

#### 📝 Prompt

```
{
  "type": "Grade 2x2 de banners publicitários digitais japoneses",
  "layout": {
    "structure": "4 quadrantes iguais",
    "quadrants": [
      {
        "position": "superior esquerdo",
        "theme": "Viagem",
        "subject": "Um casal de mãos dadas em uma praia de areia branca, olhando para a água azul-turquesa do oceano sob um céu azul brilhante.",
        "elements": ["flor de hibisco vermelha no canto inferior esquerdo"],
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
          "descriptions": ["avião", "hotel", "carro"]
        }
      },
      {
        "position": "superior direito",
        "theme": "Cuidados com a pele",
        "subject": "Retrato em close de uma jovem com pele radiante e hidratada, olhos fechados, tocando suavemente as bochechas.",
        "elements": [
          "fundo com degradê rosa suave",
          "efeitos dinâmicos de respingos de água",
          "pote de cosmético rosa com o rótulo '{argument name=\"skincare product name\" default=\"LUMIÈRE\"} Brightening Gel'"
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
          "style": "circular dourado",
          "labels": ["毛穴ケア", "高保湿", "ハリ・ツヤ"]
        }
      },
      {
        "position": "inferior esquerdo",
        "theme": "Gastronomia",
        "subject": "Bife grosso, fatiado e malpassado chiando em uma chapa de grelha escura.",
        "elements": [
          "chips de alho",
          "ramo de alecrim",
          "fundo escuro com fumaça e brasas brilhantes"
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
          "style": "circular vermelho",
          "labels": ["A4 A5等級"]
        }
      },
      {
        "position": "inferior direito",
        "theme": "Educação Online",
        "subject": "Jovem de camisa azul estudando em uma mesa, escrevendo em um caderno ao lado de um laptop aberto.",
        "elements": ["iluminação interna brilhante", "ambiente de escritório"],
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
          "descriptions": ["smartphone", "livro aberto"]
        }
      }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668128332_d2wtbo_HGQDh30bMAARz9E.jpg" width="600" alt="Publicação em Redes Sociais - Grade de 4 Painéis para Banners Digitais Japoneses - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [まかねこ| AI×仮想通貨](https://x.com/makaneko_AI)
- **Fonte:** [Twitter Post](https://x.com/makaneko_AI/status/2045764016858087720#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13531)**

---

### No. 22: Publicação em Redes Sociais - Folha de Adesivos Japoneses de Gatinho Preto Fofo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Uma folha de adesivos com 15 painéis de um gatinho preto expressivo com frases em japonês, ideal para figurinhas de chat, conceitos de selos LINE ou visuais de redes sociais.

#### 📝 Prompt

```
{"type":"ilustração de folha de adesivos fofos","subject":{"species":"gatinho preto","style":"chibi adorável, visual suave de anime-cartoon com estilo de pintura, olhos grandes e redondos castanho-âmbar, focinho pequeno, orelhas expressivas, pelo preto-carvão fofo com reflexos castanho-quentes, contorno espesso e limpo"},"layout":{"background":"branco liso","grid":{"rows":3,"columns":5,"count":15},"sections":[{"title":"01. ありがとう！","position":"linha 1 col 1","count":1,"labels":["pose feliz e grata com ambas as patas juntas no peito, boca aberta sorrindo, pétalas de flor de cerejeira rosa ao redor do gato"]},{"title":"02. おつかれさま！","position":"linha 1 col 2","count":1,"labels":["gato relaxado e contente segurando uma caneca verde com um emblema de pata, olhos fechados, pequeno sopro de vapor, linhas de destaque amarelas comemorativas"]},{"title":"03. 了解です！","position":"linha 1 col 3","count":1,"labels":["gatinho em pé levantando uma pata em sinal de reconhecimento, expressão atenta e brilhante, linhas de destaque amarelas acima"]},{"title":"04. ＯＫ！","position":"linha 1 col 4","count":1,"labels":["gatinho piscando fazendo um gesto de OK com uma pata, leve sorriso, linhas de destaque amarelas"]},{"title":"05. はーい！","position":"linha 1 col 5","count":1,"labels":["gatinho animado acenando com uma pata no alto, boca aberta sorrindo, linhas de destaque amarelas"]},{"title":"06. いいね！","position":"linha 2 col 1","count":1,"labels":["gatinho piscando fazendo um sinal de positivo, pequeno coração rosa ao lado, linhas de destaque amarelas"]},{"title":"07. がんばる！","position":"linha 2 col 2","count":1,"labels":["gatinho determinado com patas cerradas e olhos ferozes, cercado por chamas laranja estilizadas"]},{"title":"08. なんとかなる！","position":"linha 2 col 3","count":1,"labels":["gatinho confiante e sereno com olhos fechados e peito levemente estufado, flores rosa flutuando ao redor"]},{"title":"09. ごめんね…","position":"linha 2 col 4","count":1,"labels":["gatinho triste e apologético com patas juntas no peito, olhos caídos, uma gota de suor azul"]},{"title":"10. 待ってるね！","position":"linha 2 col 5","count":1,"labels":["gatinho espiando por cima de uma borda de madeira com ambas as patas visíveis, expressão de expectativa, pequenas linhas de movimento em ambos os lados"]},{"title":"11. おやすみなさい","position":"linha 3 col 1","count":1,"labels":["gatinho dormindo enrolado em uma almofada rosa, letras ZZZ azuis, lua crescente e pequenas estrelas acima"]},{"title":"12. いってきます！","position":"linha 3 col 2","count":1,"labels":["vista traseira do gatinho caminhando alegremente com uma pata levantada, usando uma mochila verde com um patch de pata e um pequeno pingente pendurado, linhas de destaque amarelas"]},{"title":"13. ただいま！","position":"linha 3 col 3","count":1,"labels":["gatinho de frente com ambas as patas levantadas, sorriso feliz e aberto, marcas de brilho dourado ao redor"]},{"title":"14. よろしくね！","position":"linha 3 col 4","count":1,"labels":["gatinho sentado educadamente virado para frente, sorriso gentil, linhas de destaque amarelas ao lado da cabeça"]},{"title":"15. 大好き！","position":"linha 3 col 5","count":1,"labels":["gatinho contente abraçando um grande coração rosa, olhos fechados, vários pequenos corações rosa flutuando ao redor"]}],"spacing":"espaçamento uniforme com margens brancas generosas"},"rendering":{"quality":"alta definição","lighting":"iluminação de estúdio suave e uniforme","color_palette":"pelo preto, olhos castanho-quentes, corações e flores rosa, marcas de destaque amarelas, acessórios verdes, decorações pastel minimalistas","mood":"amigável, saudável, pronto para adesivos, pacote de aplicativo de mensagens","composition":"cada adesivo isolado e centralizado em sua própria célula com texto japonês em negrito acima"}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883119955_nw7ax5_HGgqTCBbcAAw6TD.jpg" width="600" alt="Publicação em Redes Sociais - Folha de Adesivos Japoneses de Gatinho Preto Fofo - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Fonte:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14490)**

---

### No. 23: Publicação em Redes Sociais - Retrato Espontâneo em Boutique em Tons de Marrom

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma foto realista de estilo de vida em formato vertical de uma mulher em um interior de loja com tons quentes, útil para moda, varejo ou imagens editoriais de redes sociais.

#### 📝 Prompt

```
Uma foto espontânea e fotorrealista em formato vertical de smartphone de uma jovem mulher do Leste Asiático em uma boutique ou loja de fragrâncias para casa com tons quentes, capturada de um ângulo ligeiramente elevado, focando no tronco e na parte superior do corpo. Ela tem cabelos {argument name="hair color" default="castanho-escuros a pretos"} presos em um rabo de cavalo baixo com algumas mechas soltas perto do rosto, e segura uma pequena xícara ou pote de vela branco-creme perto da boca com uma das mãos. Ela veste uma blusa de manga comprida com zíper frontal e textura canelada, bem ajustada ao corpo, na cor {argument name="outfit color" default="marrom chocolate"}, parcialmente aberta, combinada com calças de cintura alta no mesmo tom de marrom para um visual monocromático. Sua pose é casual e levemente inclinada, com o outro braço relaxado atrás das costas, conferindo à imagem uma sensação de registro de estilo de vida espontâneo. As prateleiras da loja ao redor são de madeira e estão repletas de potes de vela de vidro e pequenos recipientes de produtos, suavemente desfocados ao fundo e ao longo do lado esquerdo do quadro. Use iluminação ambiente interna quente, profundidade de campo rasa, textura de pele realista, reflexos sutis no cabelo, pose natural das mãos e uma atmosfera aconchegante de varejo artesanal. Componha como um corte fechado de meio corpo a corpo inteiro em orientação retrato, com o sujeito centralizado e o fundo angulado diagonalmente para realçar a perspectiva espontânea. Estilo fotográfico: realista, alto detalhamento, bokeh suave, registro de compras em boutique, visual de lente 35mm, gradação de cores natural.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175967_zxdlwy_HGgQ_2-bQAA2dRG.jpg" width="600" alt="Publicação em Redes Sociais - Retrato Espontâneo em Boutique em Tons de Marrom - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fonte:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-2)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14630)**

---

### No. 24: Publicação em Redes Sociais - Retrato com caixa de ovos no corredor do supermercado

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma foto realista e vertical de estilo de vida de uma mulher elegante em um supermercado segurando uma caixa aberta com seis ovos, ideal para redes sociais ou imagens de compras com estilo editorial.

#### 📝 Prompt

```
Uma foto vertical e espontânea feita com smartphone de uma {argument name="woman age" default="jovem adulta"} mulher fazendo compras no corredor de um supermercado moderno à noite, enquadrada da altura das coxas até a cabeça em uma perspectiva próxima e levemente grande-angular. Ela está ao lado de prateleiras refrigeradas cheias de vegetais e mantimentos embalados e coloridos, com prateleiras pretas brilhantes, iluminação intensa de loja, superfícies reflexivas e um suave efeito bokeh ao fundo. Ela segura uma caixa de ovos de papelão reciclado aberta em direção à câmera com a mão esquerda, mostrando claramente 6 ovos marrons dentro. Sua mão direita está próxima a um carrinho de compras preto cheio de mantimentos. Ela tem cabelos castanhos escuros longos e soltos, e seu rosto está intencionalmente oculto por um grande bloco de desfoque retangular de bordas suaves centralizado sobre a face. Ela veste um top cropped de manga comprida, canelado e justo, na cor marrom, com zíper frontal parcialmente aberto no peito, e calças marrons de cintura alta combinando. A pose é casual e confiante, com a caixa apresentada como o objeto de destaque. Fotografia realista, iluminação interna sem flash, profundidade de campo rasa, textura detalhada da pele e do tecido, reflexos naturais, alto contraste, estética de estilo de vida fashion, toque editorial sutil, composição vertical 9:16.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883175832_ccqn07_HGgQ_ycasAAyNgF.jpg" width="600" alt="Publicação em Redes Sociais - Retrato com caixa de ovos no corredor do supermercado - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [浅野 美咲（Asano Misaki）](https://x.com/Asan0_Misaki)
- **Fonte:** [Twitter Post](https://x.com/Asan0_Misaki/status/2046904727674462560#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14629)**

---

### No. 25: Publicação em Redes Sociais - Imperatriz de Outono Opulenta ao Pôr do Sol

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera um retrato de fantasia outonal deslumbrante e cravejado de joias, ideal para artes de exibição dramáticas e visuais de alto impacto para redes sociais.

#### 📝 Prompt

```
Um retrato de fantasia hiperluxuoso de uma mulher elegante de perfil, centralizada ligeiramente à esquerda, usando um extravagante adorno de cabeça e manto de outono feitos de folhas de bordo vermelhas, flores semelhantes a crisântemos, filigrana de ouro, pedras preciosas, pingentes de cristal e ornamentos de vitrais translúcidos. Seu longo cabelo escuro cai sobre o ombro, e seu rosto está parcialmente obscurecido por sombras e pelo ângulo, criando um visual misterioso e idealizado. Cerque-a com grandes molduras circulares amplas e fitas curvas de vidro âmbar, rubi e laranja transparente, incrustadas com joias facetadas e gotas de cristal reflexivas. Preencha a cena com exatamente 9 folhas de bordo flutuantes claramente visíveis à deriva no ar. Defina o fundo como um vale montanhoso brilhante ao pôr do sol, com o sol baixo no horizonte, raios dourados quentes, picos distantes, floresta de outono e um rio reflexivo abaixo. A imagem inteira deve estar banhada em tons de laranja ígneo, cobre, ouro e escarlate, com extrema riqueza visual, destaques deslumbrantes, detalhes densos em camadas, bokeh cintilante, iluminação cinematográfica de fundo e um nível intencionalmente intenso e impactante de beleza ornamentada. Ultradetalhado, maximalista, etéreo, radiante, alta costura de fantasia, texturas brilhantes, iluminação semelhante a joias, composição cinematográfica ampla.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883127085_qxq354_HGf7lybbYAARHra.jpg" width="600" alt="Publicação em Redes Sociais - Imperatriz de Outono Opulenta ao Pôr do Sol - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AIおじさん](https://x.com/AIojisan1952)
- **Fonte:** [Twitter Post](https://x.com/AIojisan1952/status/2046881419344134446#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14508)**

---

### No. 26: Publicação em Redes Sociais - Anúncio de Colagem de Robô Pintor

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma colagem promocional 2x2 polida mostrando um robô fofo pintando quatro obras de arte diferentes, ideal para anúncios de ferramentas de imagem por IA e banners de redes sociais.

#### 📝 Prompt

```
{"type":"ilustração de colagem promocional","subject":{"main":"robô artista humanoide branco fofo com olhos azuis brilhantes grandes","design":"carcaça branca arredondada e lisa, juntas mecânicas pretas, sorriso pequeno, proporções amigáveis e infantis, acabamento brilhante","activity":"pintando em uma tela com um pincel fino enquanto segura uma paleta de pintor"},"layout":{"composition":"colagem em grade 2x2 com uma sobreposição de título grande centralizada cruzando a costura central","sections":[{"position":"superior esquerdo","count":1,"label":"3","scene":"robô pintando uma paisagem marinha colorida de pôr do sol com sol brilhante no horizonte, céu rosa e laranja, água azul, pinceladas expressivas"},{"position":"superior direito","count":1,"label":"6","scene":"robô pintando um buquê de flores rosas em um vaso azul, natureza morta floral em tons pastéis suaves"},{"position":"inferior esquerdo","count":1,"label":"4","scene":"robô pintando uma paisagem exuberante de cachoeira verde com folhagem de floresta e um riacho"},{"position":"inferior direito","count":1,"label":"7","scene":"robô pintando um horizonte de cidade moderna brilhante ao pôr do sol com arranha-céus altos e reflexos quentes"}],"title_overlay":{"text":"{argument name=\"headline text\" default=\"ChatGPT Images 2.0\"}","style":"texto sem serifa branco, muito grande e em negrito, com sombra projetada escura, centralizado horizontalmente na colagem"}},"environment":{"setting":"interior de estúdio de arte aconchegante","background":"prateleiras com foco suave, quadros, iluminação ambiente quente, cortinas neutras, planta ocasional","easel":"cavalete de mesa de madeira em cada painel","palette":"paleta de pintor redonda com muitas manchas de tinta vívidas em cada painel"},"style":{"rendering":"realismo de desenho animado 3D altamente polido","mood":"lúdico, criativo, convidativo, tecnologia encontra a arte","camera":"enquadramento de plano médio, robô no lado direito de cada painel voltado para a esquerda em direção à tela","lighting":"luz interna quente com destaques suaves e profundidade de campo rasa"}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146885_253rf3_HGfla3yWUAAEm8-.jpg" width="600" alt="Publicação em Redes Sociais - Anúncio de Colagem de Robô Pintor - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [01net](https://x.com/01net)
- **Fonte:** [Twitter Post](https://x.com/01net/status/2046856808921248120#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14556)**

---

### No. 27: Publicação em Redes Sociais - Pôster de Protesto em Pop-Art de Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster vertical de anime ousado com um personagem de rosto censurado, gesto de sinal de paz e um balão de slogan exagerado para arte de memes, posts sociais ou experimentos gráficos.

#### 📝 Prompt

```
Um pôster ousado de pop-art de anime de um feiticeiro alto de cabelos brancos com um casaco azul-marinho de gola alta, visto da cintura para cima, voltado para frente em uma pose confiante com a mão esquerda levantada perto da câmera fazendo um sinal de paz. Seu rosto está parcialmente obscurecido por um bloco retangular de desfoque/censura centralizado sobre a área dos olhos e nariz, enquanto seu cabelo espetado branco-prateado se espalha dramaticamente acima de uma venda ou viseira escura. Coloque um enorme balão de fala de quadrinhos no topo com o texto exato {argument name="headline text" default="LUDDITES ALWAYS LOSE!"} em letras maiúsculas pesadas e sem serifa. Use um fundo azul vívido preenchido com densas linhas de velocidade radiais vermelhas e laranjas explodindo para fora de trás do personagem, criando uma sensação dinâmica de capa de mangá. Enfatize contornos de tinta grossos, renderização de anime cel-shaded, contraste posterizado e um visual de impressão de quadrinhos vintage levemente distorcido. A composição deve ser vertical, com corte fechado, alta energia, rebelde, gráfica e semelhante a um meme, com o cabelo {argument name="character hair color" default="silver white"}, casaco {argument name="coat color" default="dark navy"} e {argument name="background color" default="bright blue with red-orange radial lines"} dominando a paleta.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179000_s7s3bp_HGfDh7qakAA3Ovk.jpg" width="600" alt="Publicação em Redes Sociais - Pôster de Protesto em Pop-Art de Anime - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Fonte:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14638)**

---

### No. 28: Publicação em Redes Sociais - Snapshot realista de compras no Sam's Club

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera um retrato fotorrealista e espontâneo em uma loja de atacado, ideal para recriar uma cena de compras autêntica com sinalização de varejo e um cliente segurando produtos.

#### 📝 Prompt

```
Uma foto de smartphone espontânea e altamente realista dentro de uma movimentada loja do Sam’s Club na China. Centralize a composição em um jovem homem do leste asiático, do meio do tronco para cima, em pé e de frente para a câmera, com o rosto obscurecido por um bloco de desfoque retangular por privacidade. Ele veste uma camiseta preta lisa de manga curta com um pequeno logotipo branco da Tesla no peito esquerdo e segura um saco plástico transparente grande com maçãs vermelhas na mão esquerda, amarrado no topo com uma fita azul. O saco de maçãs tem uma etiqueta branca com a palavra “envy” e um pequeno texto em chinês abaixo. Atrás dele, um interior de varejo iluminado com tetos industriais altos, prateleiras de armazém, clientes, carrinhos de compras e expositores de produtos empilhados. Mostre com destaque a placa de parede azul com diamante do Sam’s Club no canto superior esquerdo com o texto “Sam’s CLUB” e “山姆会员商店”, e um grande banner de parede azul atrás dele com os dizeres “更好的生活尽在山姆” e “Life is Better in the Club”. No canto superior direito, pendure um banner vertical branco alto com os dizeres “优质优价” e “Great Products Great Prices”, com detalhes geométricos em azul e verde. Inclua muitos clientes ao fundo, levemente fora de foco, para criar uma atmosfera autêntica de compras lotadas. A iluminação deve ser brilhante e uniforme, típica de varejo; cores naturais; perspectiva ao nível dos olhos; estética de fotografia documental; assunto em primeiro plano nítido com fundo levemente suavizado; orientação retrato.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883097529_4o6z0e_HGeaeHkbkAASDhW.jpg" width="600" alt="Publicação em Redes Sociais - Snapshot realista de compras no Sam's Club - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AB Kuai.Dong](https://x.com/_FORAB)
- **Fonte:** [Twitter Post](https://x.com/_FORAB/status/2046774687380992253#reversed-2)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14434)**

---

### No. 29: Publicação em Redes Sociais - Pássaro Geométrico Pedalando Bicicleta

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma ilustração vetorial minimalista e limpa de um pássaro ciclista estilizado, ideal para gráficos editoriais lúdicos, logotipos ou pôsteres de arte moderna.

#### 📝 Prompt

```
Uma ilustração vetorial plana e minimalista em um fundo cinza claro mostrando um pássaro peculiar andando de bicicleta, construído inteiramente a partir de formas geométricas simples com contornos pretos espessos. A bicicleta é uma bicicleta de estrada desenhada em linhas pretas, vista de lado e voltada para a esquerda, com 2 rodas grandes, cada uma dividida por um cruzamento de raios vertical e horizontal, um quadro triangular simples, um selim preto pequeno, pedais e uma linha de solo preta fina correndo horizontalmente abaixo da bicicleta. O ciclista é um pássaro branco estilizado com um corpo redondo grande, uma cabeça redonda menor, um bico laranja pontudo aberto e o interior do bico inferior rosa. O pássaro tem 1 olho preto visível, uma linha preta curva simples no topo da cabeça, 1 asa em forma de gota atrás do pescoço e 1 formato de pena de cauda branca angular apontando para trás. O pássaro se inclina para frente sobre a bicicleta como se estivesse pedalando ativamente. Ele tem 2 pernas laranjas longas e estreitas com contornos pretos que se estendem para baixo sobre o quadro em direção aos pedais. Mantenha a composição centralizada, lúdica, limpa e abstrata, sem sombreamento, sem textura e com um estilo gráfico moderno semelhante a um ícone.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883128094_pkk4fv_HGdj-7yWsAAi5Zj.png" width="600" alt="Publicação em Redes Sociais - Pássaro Geométrico Pedalando Bicicleta - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Mojofull](https://x.com/furoku)
- **Fonte:** [Twitter Post](https://x.com/furoku/status/2046740061719584955#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14512)**

---

### No. 30: Publicação em Redes Sociais - Infográfico de viés cognitivo para Instagram

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt profissional para criar gráficos informativos para redes sociais com informações textuais complexas.

#### 📝 Prompt

```
Crie um {argument name="format" default="infográfico"} para {argument name="platform" default="post no Instagram"} sobre {argument name="topic" default="como anunciantes podem usar vieses cognitivos"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883042677_zzj0li_HGd6ee-W4AArJ1p.jpg" width="600" alt="Publicação em Redes Sociais - Infográfico de viés cognitivo para Instagram - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Maxwell Finn](https://x.com/maxwellfinn)
- **Fonte:** [Twitter Post](https://x.com/maxwellfinn/status/2046739223001309256)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14306)**

---

### No. 31: Publicação em Redes Sociais - Laboratório de informática do início dos anos 2000 com ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma foto nostálgica e espontânea de sala de aula com alunos usando o ChatGPT em computadores CRT, ideal para editoriais ou visuais de redes sociais sobre IA na educação cotidiana.

#### 📝 Prompt

```
Uma foto documental espontânea de um {argument name="setting" default="laboratório de informática de ensino médio"} repleto de exatamente 10 alunos sentados em fileiras de computadores desktop CRT volumosos e esbranquiçados, vistos do canto traseiro esquerdo da sala com uma leve grande angular. A cena deve parecer um registro do início dos anos 2000, tirado com uma câmera digital amadora com flash direto, granulação suave, iluminação fluorescente interna levemente quente e um carimbo de data no canto inferior direito lendo {argument name="timestamp" default="18/02/04"}. No primeiro plano à esquerda, um aluno com uma jaqueta esportiva azul-marinho com listras brancas nas mangas aponta para um monitor CRT; no centro do primeiro plano, outro aluno com cabelo curto espetado veste um moletom cinza oversized e está sentado de costas para a câmera; no primeiro plano à direita, uma aluna loira com rabo de cavalo veste uma blusa azul-clara de mangas compridas com listras horizontais escuras nos braços e digita em um teclado; na extrema direita, outro aluno com cabelo escuro cacheado está sentado em uma estação de trabalho. Vários outros alunos ocupam as fileiras do meio e do fundo, todos voltados para suas telas. Os monitores exibem de forma proeminente a interface do ChatGPT, com o título visível lendo {argument name="screen title" default="ChatGPT"} e um texto de prompt simples abaixo dele. A sala tem paredes bege, teto rebaixado e vários cartazes motivacionais: exatamente 4 cartazes legíveis na parede do fundo dizendo {argument name="poster one" default="VOCÊ CONSEGUE FAZER COISAS DIFÍCEIS"}, "SEJA GENTIL ONLINE", "PENSE ANTES DE CLICAR" e um cartaz maior intitulado "ATALHOS DE TECLADO" com uma lista abaixo. Inclua quadros de avisos, uma porta de sala de aula ao fundo, cadeiras de escritório com rodízios, teclados e mouses brancos e uma mochila no chão perto da mesa do primeiro plano à direita. Os rostos devem estar parcialmente obscurecidos ou suavemente anonimizados, preservando a aparência de uma foto real de sala de aula enquanto mantém o foco nos alunos usando o ChatGPT em um antigo laboratório de informática.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195599_qbhgl7_HGd3B2VXcAAqWkr.jpg" width="600" alt="Publicação em Redes Sociais - Laboratório de informática do início dos anos 2000 com ChatGPT - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fonte:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14675)**

---

### No. 32: Publicação em Redes Sociais - Retrato Surreal em Pátio com Corvo e Cachorro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato fotorrealista e levemente inquietante de uma pessoa sentada segurando um cachorro pequeno, com um pássaro preto pousado em sua cabeça, ideal para fotografia surrealista de estilo editorial.

#### 📝 Prompt

```
Um retrato levemente surreal, porém fotorrealista, de uma pessoa sentada em um pátio ou quintal silencioso, centralizada no quadro, vestindo uma blusa de gola alta branca de manga comprida com delicadas estampas florais rosas e uma ilustração impressa de uma garota no peito, combinada com calças florais largas em tom creme. A pessoa está sentada em uma cadeira de metal branca simples e segura um pequeno cachorro peludo tipo poodle no colo; o cachorro tem pelos encaracolados em tom off-white e orelhas distintamente tingidas de laranja. Pousado sobre o coque de cabelo escuro da pessoa está um corvo, virado para a esquerda, calmo e equilibrado como se pertencesse naturalmente ao local. A pose do sujeito é estática, direta e formal, criando uma sensação estranha de retrato de família inexpressivo. Defina a cena contra uma parede de estuque off-white texturizada com exatamente 4 elementos decorativos de fundo notáveis: 1 ornamento de parede em formato de sol marrom no canto superior esquerdo, 1 pequena prateleira de parede com uma pequena estatueta de pássaro e flores pendentes à esquerda, 1 janela arqueada alta ou mural à direita mostrando um céu azul brilhante com nuvens brancas suaves, e 1 vaso de pedestal branco no canto inferior direito preenchido com folhas verdes longas e exatamente 2 ornamentos de flamingo rosa. Inclua um pouco de borda de pedra e vegetação escura no canto inferior esquerdo e um piso de azulejos marrons. A iluminação é de luz natural suave, levemente nublada, com cores suaves, profundidade de campo rasa e um visual de fotografia editorial vintage. A composição deve ser vertical, figura sentada completa, frontal, equilibrada e silenciosamente inquietante. Personalize a figura principal como {argument name="person" default="uma mulher de meia-idade"}, o pássaro como {argument name="bird type" default="corvo preto"}, a raça do cachorro como {argument name="dog type" default="pequeno poodle mix"}, a cor da orelha do cachorro como {argument name="dog ear color" default="laranja"} e a paleta do traje como {argument name="outfit colors" default="flores brancas e rosa desbotado"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195410_nqnhm7_HGd3B2UXkAAwWtN.jpg" width="600" alt="Publicação em Redes Sociais - Retrato Surreal em Pátio com Corvo e Cachorro - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fonte:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14674)**

---

### No. 33: Publicação em Redes Sociais - Retrato de Viagem em Estrada Costeira com Atmosfera Melancólica

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato cinematográfico espontâneo à beira-mar com um sedã vintage estacionado, ideal para fotografia de viagem nostálgica e imagens de estilo de vida.

#### 📝 Prompt

```
Uma foto cinematográfica espontânea de uma {argument name="person" default="jovem mulher"} parada em um acostamento costeiro úmido em um dia nublado, vista de costas e levemente de lado enquanto ela vira o rosto em direção à câmera. Ela tem cabelos escuros e bagunçados presos em um coque frouxo com mechas ao vento, e seu rosto está suavemente obscurecido e indistinto. Ela veste 2 peças de roupa visíveis: uma jaqueta de lona marrom-bronze desgastada e jeans azul-médio. Sua postura é relaxada com uma das mãos perto ou dentro do bolso. O cenário é um mirante de rodovia em um penhasco oceânico com atmosfera melancólica, com montanhas rochosas escuras ao longo do lado esquerdo, mar cinza-pálido estendendo-se ao longe à direita e um céu nublado e desbotado. Inclua 1 sedã de cor clara do final dos anos 80 ou início dos anos 90 estacionado na borda direita do quadro, com a traseira voltada para o espectador, e 1 grande barreira de rocha perto do mirante. O asfalto está escuro e úmido com linhas de estacionamento tênues, sugerindo chuva recente. Use luz natural, tons frios suaves, leve granulação de filme, foco suave, névoa leve e uma estética nostálgica de fotografia de viagem em 35mm.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195166_1z6cyp_HGd3B2XXMAECGKt.jpg" width="600" alt="Publicação em Redes Sociais - Retrato de Viagem em Estrada Costeira com Atmosfera Melancólica - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fonte:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14673)**

---

### No. 34: Publicação em Redes Sociais - Mulher dançando de vestido preto

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um retrato cinematográfico fotorrealista de vida noturna de uma mulher em um vestido preto fluido dançando elegantemente em um lounge à meia-luz, ideal para moda, apresentações ou visuais de redes sociais.

#### 📝 Prompt

```
Uma foto dramática de corpo inteiro de uma mulher dançando com energia em um lounge ou bar sofisticado e escuro, vestindo um elegante vestido de noite preto com uma fenda alta e tecido fluido semelhante ao veludo que se agita com seu movimento. Ela tem cabelos longos e lisos {argument name="hair color" default="pretos"} voando para um lado, uma silhueta esguia e atlética, e pequenos brincos de argola. Capture-a em uma pose de dança confiante e estilosa, com um braço levantado graciosamente acima da cabeça e o outro curvado para baixo, tronco virado de perfil, enfatizando a elegância e o movimento. O cenário é escuro e cinematográfico, com luzes quentes âmbar, bokeh suave e um público desfocado ao fundo, incluindo alguns espectadores sentados e uma tela de televisão brilhante à esquerda. O clima é sofisticado, sensual e de alto padrão, com forte contraste, profundidade de campo rasa, pele realista, movimento sutil na bainha do vestido e iluminação de editorial de moda. Fotorrealista, fotografia dinâmica de vida noturna, composição vertical.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883126086_66k47f_HGd00loaMAA_GwI.jpg" width="600" alt="Publicação em Redes Sociais - Mulher dançando de vestido preto - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [蒼井　詠@AIで効率化する女](https://x.com/aoi___ei)
- **Fonte:** [Twitter Post](https://x.com/aoi___ei/status/2046733167286219007#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14506)**

---

### No. 35: Infográfico / Visual Educacional - Prompt para Pôster de Ranking Gastronômico de Paris

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt simples para criar um pôster de ranking de gastronomia urbana, projetado para uso com o GPT Image 2.

#### 📝 Prompt

```
Crie um pôster para um ranking de {argument name="topic" default="gastronomia"} da cidade de {argument name="city" default="Paris"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883072287_so5j6z_HGgoRGdWsAA_w4Q.jpg" width="600" alt="Infográfico / Visual Educacional - Prompt para Pôster de Ranking Gastronômico de Paris - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ToroJushiAi](https://x.com/ToroJushiAi)
- **Fonte:** [Twitter Post](https://x.com/ToroJushiAi/status/2046930310613332075)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** zh

**[👉 Experimente agora →](https://gptimage2api.net/?id=14370)**

---

### No. 36: Infográfico / Visual Educacional - Folha de Comparação de Estilos de Caligrafia Chinesa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um pôster de referência vertical que exibe a mesma frase em chinês renderizada em cinco estilos de caligrafia famosos, útil para testes de tipografia, estudos de design cultural e comparações de escrita com pincel.

#### 📝 Prompt

```
{"type":"folha de comparação de caligrafia chinesa","subject":"a mesma frase de cinco caracteres escrita em cinco estilos históricos de caligrafia diferentes","phrase":"{argument name=\"calligraphy text\" default=\"视觉新时代\"}","canvas":{"orientation":"pôster vertical","background":"textura de papel xuan em tom off-white quente com fibras sutis, leve envelhecimento e tom suave e irregular"},"layout":{"structure":"5 linhas horizontais separadas por linhas divisórias finas e tênues","row count":5,"left labels count":5,"seal count":5,"left labels":["王羲之","宋徽宗","赵孟頫","颜真卿","苏轼"],"rows":[{"position":"linha superior","style":"estilo semi-cursivo inspirado em Wang Xizhi","main text":"视觉新时代","label":"王羲之","seal":"pequeno selo quadrado vermelho na extremidade direita"},{"position":"segunda linha","style":"caligrafia elegante e esguia inspirada no estilo 'fino-dourado' do Imperador Huizong, com traços angulares nítidos e espaçamento arejado","main text":"视觉新时代","label":"宋徽宗","seal":"pequeno selo quadrado vermelho na extremidade direita"},{"position":"terceira linha","style":"estilo regular-cursivo refinado inspirado em Zhao Mengfu","main text":"视觉新时代","label":"赵孟頫","seal":"pequeno selo quadrado vermelho na extremidade direita"},{"position":"quarta linha","style":"estilo regular ousado e robusto inspirado em Yan Zhenqing","main text":"视觉新时代","label":"颜真卿","seal":"pequeno selo quadrado vermelho na extremidade direita"},{"position":"linha inferior","style":"estilo cursivo expressivo e robusto inspirado em Su Shi","main text":"视觉新时代","label":"苏轼","seal":"pequeno selo quadrado vermelho na extremidade direita"}],"left label design":"cada linha possui uma placa de nome bege vertical estreita alinhada na extremidade esquerda com caracteres chineses pretos","centerpiece":"frase grande escrita com pincel preto centralizada em cada linha"},"style":{"ink":"tinta sumi preta profunda com textura visível de pincel seco, efeito de difusão, variação de pressão e afunilamento natural das pinceladas","mood":"acadêmico, experimental, apresentação de folha de museu","composition":"margens limpas e espaçosas, espaçamento equilibrado entre linhas, digitalização frontal plana ou documento fotografado"},"quality":{"detail":"alta resolução, texturas de pincel nítidas, granulação de papel realista","lighting":"iluminação de estúdio suave e uniforme sem sombras fortes"}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883103242_b88t4p_HGfhStsaYAAI6F8.jpg" width="600" alt="Infográfico / Visual Educacional - Folha de Comparação de Estilos de Caligrafia Chinesa - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [-Zho-](https://x.com/ZHO_ZHO_ZHO)
- **Fonte:** [Twitter Post](https://x.com/ZHO_ZHO_ZHO/status/2046852355535274063#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14448)**

---

### No. 37: Infográfico / Visual Educacional - Confronto no Estreito de Ormuz no estilo Countryball

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um meme satírico no estilo countryball mostrando os EUA e o Irã bloqueando um ao outro no Estreito de Ormuz, útil para humor editorial ou postagens geopolíticas em redes sociais.

#### 📝 Prompt

```
Uma ilustração de meme político bem-humorado em um estilo simples de desenho animado countryball, mostrando a situação atual no {argument name="location label" default="Estreito de Ormuz"} como um ponto de estrangulamento estreito. Use uma composição paisagística ampla com cores planas e vibrantes, contornos pretos espessos e um visual limpo de infográfico desenhado à mão. No primeiro plano, coloque 2 countryballs lado a lado em uma ponte de terra arenosa extremamente estreita com rochas em ambos os lados, deixando claro que apenas um pode passar de cada vez. À esquerda, está um countryball dos {argument name="left country" default="Estados Unidos"} pintado com a bandeira americana, usando óculos escuros e um chapéu de cowboy marrom, encarando a outra bola com uma atitude teimosa. À direita, está um countryball do {argument name="right country" default="Irã"} pintado com a bandeira iraniana, usando um chapéu escuro semelhante a um turbante, com olhos inclinados de raiva, também se recusando a sair do lugar. Adicione 2 grandes balões de fala brancos, um ao lado de cada countryball, e coloque a mesma palavra em coreano em negrito em ambos os balões: {argument name="speech bubble text" default="길"}. No plano médio e no fundo, mostre um mar azul movimentado e lotado com um total de 9 navios: 2 navios de guerra cinzas dos EUA na extrema esquerda, 1 submarino chinês com uma bandeira chinesa vermelha, 4 petroleiros alinhados no centro-esquerda e no centro carregando diferentes bandeiras nacionais, e 2 navios militares cinzas perto da passagem estreita com pequenas bandeiras americanas. No canto superior direito, inclua uma grande sobreposição da bandeira iraniana ao longo da costa. Desenhe massas de terra em tom bege ao redor da via navegável para se assemelhar a uma visão de mapa simplificada do Estreito de Ormuz. No centro inferior, adicione uma legenda em negrito em coreano e inglês na areia: {argument name="bottom caption" default="호르무즈 해협 (Estreito de Ormuz)"}. O clima deve ser satírico, tenso e com estilo de meme, mas visualmente fofo e legível.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883199462_26yyhl_HGfTnkjbgAE1g_j.jpg" width="600" alt="Infográfico / Visual Educacional - Confronto no Estreito de Ormuz no estilo Countryball - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Fonte:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14685)**

---

### No. 38: Infográfico / Visual Educacional - Layout de Questões de Exame Físico

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt projetado para criar uma imagem de uma prova de ensino médio com múltiplas questões e respostas.

#### 📝 Prompt

```
gere uma imagem de questão de física {argument name="subject" default="exame de ensino médio"} {argument name="type" default="múltipla escolha"} 9:16. gere 4 imagens e cada imagem é uma resposta da questão fornecida
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058250_sa4get_HGeoFF5bUAAwyS2.jpg" width="600" alt="Infográfico / Visual Educacional - Layout de Questões de Exame Físico - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058247_4mvtru_HGeoVXdaUAA-UVr.jpg" width="600" alt="Infográfico / Visual Educacional - Layout de Questões de Exame Físico - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058259_hhqrlk_HGeoXmlaEAAV214.jpg" width="600" alt="Infográfico / Visual Educacional - Layout de Questões de Exame Físico - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883058909_lcg9cp_HGeoZfPbMAAs7pg.jpg" width="600" alt="Infográfico / Visual Educacional - Layout de Questões de Exame Físico - Image 4">
</div>

#### 📌 Detalhes

- **Autor:** [zdhpeter](https://x.com/peter6759)
- **Fonte:** [Twitter Post](https://x.com/peter6759/status/2046789718428594409)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14340)**

---

### No. 39: Infográfico / Visual Educacional - Pôster de Receita Vintage de Gimbap Coreano

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster infográfico de receita coreana em estilo antigo para gimbap, adequado para marketing gastronômico, decoração de restaurantes ou visuais de culinária cultural.

#### 📝 Prompt

```
Crie um pôster de comida coreana vintage em papel pergaminho bege envelhecido com um fundo texturizado levemente manchado, cantos com bordas ornamentais escuras e um estilo de ilustração tradicional de tinta e aquarela pintado à mão. O pôster é um infográfico único empilhado verticalmente sobre {argument name="dish name" default="정통 한국 김밥"}, com uma elegante caligrafia coreana grande no topo e uma faixa de fita curva abaixo dela com os dizeres {argument name="subtitle text" default="Traditional Korean Gimbap"}. No centro superior, mostre um grande prato de porcelana empilhado com exatamente 12 fatias de gimbap, cada fatia exibindo recheios distintos em arroz branco, ovo amarelo, cenoura laranja, espinafre verde e alga escura. À direita do prato, adicione uma pequena tigela de porcelana com kimchi e uma curta nota manuscrita em coreano dizendo “간단한 보여도 정성이 들어간 한국의 맛! ♥”. Inclua um pequeno carimbo de selo vermelho com texto em coreano perto do canto superior direito. No meio, adicione uma seção de ingredientes rotulada em um cabeçalho de fita lendo “재료”, mostrando exatamente 6 painéis de ingredientes em uma linha: 1. 김 (건김) como folhas de alga empilhadas, 2. 밥 (양념 밥) como uma tigela de arroz, 3. 계란 (지단용) como tiras de ovo cozido fatiado, 4. 당근 (채썰어볶기) como cenouras em juliana, 5. 시금치 (데쳐서 무치기) como espinafre temperado, 6. 단무지 (김밥용) como tiras de rabanete amarelo em conserva. Abaixo disso, adicione outro cabeçalho de fita lendo “만드는 순서” e mostre exatamente 6 painéis de etapas emoldurados em duas fileiras de três, conectados da esquerda para a direita com setas. O passo 1 é rotulado como “1 밥 간하기” e mostra uma tigela de arroz com óleo de gergelim e sal ao lado, legenda “밥에 참기름 소금으로 간하기”. O passo 2 é rotulado como “2 속재료 준비하기” e mostra uma tábua de corte com ovo, cenoura e espinafre, além de uma faca, legenda “재료 볶아 속재료 준비하기”. O passo 3 é rotulado como “3 김과 밥 펴기” e mostra alga em uma esteira de bambu com arroz espalhado sobre ela, legenda “김에 밥 얇게 펴기”. O passo 4 é rotulado como “4 속재료 얹기” e mostra os recheios dispostos em fileiras horizontais sobre o arroz, legenda “속재료를 차례로 얹기”. O passo 5 é rotulado como “5 단단하게 말기” e mostra duas mãos enrolando a esteira de bambu firmemente, legenda “김밥을 단단하게 말기”. O passo 6 é rotulado como “6 썰어 완성하기” e mostra uma faca de chef fatiando um rolo de gimbap em pedaços, legenda “먹기 좋게 썰어 완성!”. Na parte inferior, adicione uma faixa larga com caligrafia coreana em negrito lendo {argument name="bottom slogan" default="정성 가득한 한 줄의 행복!"} e um pequeno coração. Decore os cantos inferiores com motivos florais e adicione um selo quadrado vermelho com o caractere chinês “福” no canto inferior direito. Use tons de sépia suave, marrom, creme, verde-oliva e vermelho desbotado, com contornos finamente esboçados, sombreamento suave em aquarela e composição autêntica de pôster impresso. Adicione um pequeno logotipo moderno sobreposto no canto superior esquerdo lendo {argument name="brand text" default="Pollo AI GPT Image 2"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145882_hn8j2o_HGecwombcAAd00i.jpg" width="600" alt="Infográfico / Visual Educacional - Pôster de Receita Vintage de Gimbap Coreano - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [폴로 AI](https://x.com/polloai_kr)
- **Fonte:** [Twitter Post](https://x.com/polloai_kr/status/2046778808221733337#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14554)**

---

### No. 40: Infográfico / Visual Educacional - Pôster Vintage de Receita de Crepe Francês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um pôster de receita francesa em estilo antigo, ricamente ilustrado, exibindo crepes de manteiga, ingredientes e seis etapas de preparo, ideal para arte editorial com tema gastronômico ou impressões decorativas para cozinha.

#### 📝 Prompt

```
{"type":"pôster de receita francesa vintage","subject":"infográfico gastronômico ilustrado e ornamentado para clássicos crepes de manteiga","style":{"overall":"pôster de livro de receitas antigo, efêmera de café francês da Belle Époque, ilustração em aquarela e tinta pintada à mão, textura de papel pergaminho envelhecido, paleta de cores em creme quente suave, bege, marrom, azul empoeirado e vermelho desbotado","rendering":"tipografia decorativa altamente legível, bordas ornamentais gravadas, manchas suaves de papel, bordas desgastadas, filigrana floral delicada, estética de impressão artesanal nostálgica"},"text":{"main_title":"Les Véritables Crêpes au Beurre","ingredients_header":"INGRÉDIENTS","method_header":"LA MÉTHODE","footer_banner":"Un classique de la gourmandise, à savourer chaud!","logo":"{argument name=\"corner logo\" default=\"AI GPT Image 2\"}"},"layout":{"orientation":"retrato","border":"borda ilustrada totalmente ornamentada com arabescos nos 4 cantos","sections":[{"title":"seção principal","position":"topo","count":3,"labels":["caligrafia do título principal em fita e letra grande","pilha de crepes no prato","copo com rótulo Cidre de Bretagne"]},{"title":"INGRÉDIENTS","position":"meio","count":6,"labels":["1. 1 xícara de Farinha","2. 2 Ovos","3. 2 xícaras de Leite","4. 50g Manteiga","5. 1 c.s. Açúcar","6. Pitada de Sal"]},{"title":"LA MÉTHODE","position":"meio-inferior","count":6,"labels":["1 MISTURE OS INGREDIENTES SECOS","2 BATA OS OVOS","3 ADICIONE O LEITE GRADUALMENTE","4 DERRETA A MANTEIGA E ADICIONE","5 AQUEÇA A FRIGIDEIRA DE CREPE","6 VIRE E COZINHE!"]}],"grid":{"ingredients_columns":6,"method_columns":3,"method_rows":2}},"hero":{"plate":"prato de cerâmica floral azul e branco","food":"pilha alta de aproximadamente {argument name=\"crepe count\" default=\"14\"} crepes finos dourados polvilhados com açúcar de confeiteiro, cobertos com uma porção de manteiga derretida","surface":"mesa de madeira rústica","cloth":"guardanapo xadrez azul e branco à direita","background":"paisagem pastoral desbotada com torre de igreja e edifícios europeus antigos"},"ingredients":[{"index":1,"item":"farinha","container":"tigela de cerâmica decorada","caption":"1 xícara de Farinha"},{"index":2,"item":"ovos","count":2,"caption":"2 Ovos"},{"index":3,"item":"leite","container":"jarra de cerâmica floral azul","caption":"2 xícaras de Leite"},{"index":4,"item":"manteiga","container":"prato pequeno com bloco de manteiga","caption":"50g Manteiga"},{"index":5,"item":"açúcar","container":"tigela de cerâmica com colher","caption":"1 c.s. Açúcar"},{"index":6,"item":"sal","container":"pote com tampa rotulado SEL","caption":"Pitada de Sal"}],"method_panels":[{"index":1,"title":"MISTURE OS INGREDIENTES SECOS","image":"tigela de mistura com farinha e batedor","caption":"Mélanger la farine et le sucre"},{"index":2,"title":"BATA OS OVOS","image":"ovos sendo despejados na tigela, batedor misturando, cascas de ovo quebradas por perto","caption":"Incorporer les œufs battus"},{"index":3,"title":"ADICIONE O LEITE GRADUALMENTE","image":"leite despejado da jarra de cerâmica na massa","caption":"Ajouter le lait petit à petit"},{"index":4,"title":"DERRETA A MANTEIGA E ADICIONE","image":"manteiga derretida despejada de uma panela pequena na tigela","caption":"Ajouter le beurre fondu"},{"index":5,"title":"AQUEÇA A FRIGIDEIRA DE CREPE","image":"frigideira de crepe preta vazia aquecendo sobre chama de gás azul","caption":"Faire chauffer la poêle à crêpes"},{"index":6,"title":"VIRE E COZINHE!","image":"crepe na frigideira com espátula de metal levantando a borda","caption":"Retourner et cuire des deux côtés"}],"decorative_elements":{"count":8,"labels":["faixa de fita atrás do título superior","faixa de fita atrás do cabeçalho de ingredientes","faixa de fita atrás do cabeçalho de método","grande faixa de fita inferior","ornamento de videira floral à esquerda do título","enfeites florais de canto","estilo de pergaminho enrolado","linhas divisórias finas entre os painéis de ingredientes e método"]},"quality":"composição simétrica equilibrada, texto em francês e inglês nítido e legível, layout de infográfico ricamente detalhado, porém limpo, pôster culinário charmoso do velho mundo"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149983_ity2s5_HGeYyAfWMAEx8Lx.jpg" width="600" alt="Infográfico / Visual Educacional - Pôster Vintage de Receita de Crepe Francês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Pollo AI France](https://x.com/PolloAIFR)
- **Fonte:** [Twitter Post](https://x.com/PolloAIFR/status/2046774203920113932#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14564)**

---

### No. 41: Infográfico / Visual Educacional - Infográfico de Física de Buracos Negros para Adolescentes

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera um infográfico editorial de ciência denso e de página única que explica um artigo complexo sobre buracos negros e matéria escura em um estilo lúdico e acessível para publicações em redes sociais ou artigos educacionais.

#### 📝 Prompt

```
{"type":"pôster infográfico de ciência editorial","style":"infográfico educacional estilo revista amigável para adolescentes, combinando diagramas de física desenhados à mão, personagens de desenho animado e tipografia editorial limpa","topic":"buracos negros primordiais, evaporação de Hawking e matéria escura com carga de memória","canvas":{"orientation":"retrato","background":"textura de papel creme quente com granulação sutil","border":"borda retangular cinza suave e fina ao redor da página inteira"},"headline":{"title":"O BURACO NEGRO QUE SE RECUSOU A MORRER","subtitle":"um pequeno buraco negro nascido no primeiro segundo do universo e a nova física estranha que pode permitir que ele se esconda como matéria escura.","credit":"Thoss, Lopez-Honorez, Kühnel & Hufnagel"},"layout":{"sections":[{"title":"Nascido em um flash","position":"superior esquerdo","count":4,"labels":["diagrama de nascimento do universo primitivo em espiral","buraco negro primordial menor que um grão de sal, mas mais pesado que uma montanha","ícone de relógio de 10^-30 segundos após o Big Bang","ícone de termômetro"]},{"title":"Buracos negros normais evaporam","position":"superior direito","count":4,"labels":["três estágios de buraco negro encolhendo da esquerda para a direita","rabiscos de partículas saindo ao redor de cada estágio","parágrafo de explicação de Stephen Hawking","adesivo com citação: \"buracos negros não são tão negros\" — S. Hawking, 1974"]},{"title":"A reviravolta: carga de memória","position":"centro","count":4,"labels":["personagem de buraco negro triste e sobrecarregado com uma mochila rotulada como MEMÓRIA","balão de fala sobre estar cheio demais de informações para terminar de evaporar","equação: velocidade normal ÷ (muita informação)^k = velocidade de rastejamento","nota entre chaves sobre a proposta de Gia Dvali, 2018"]},{"title":"Dois tipos de partículas fantasmagóricas","position":"centro inferior","count":5,"labels":["partícula em movimento rápido à esquerda","personagem de partícula quente e lenta à direita","linha do tempo do BIG BANG até HOJE","rótulo de nuvem RÁPIDA E FRIA","rótulo de nuvem LENTA E QUENTE"]},{"title":"Como os encontraríamos: a floresta Lyman-α","position":"inferior esquerdo","count":4,"labels":["parágrafo sobre galáxias antigas passando por nuvens de hidrogênio","gráfico de paisagem de floresta de absorção com picos","nota manuscrita: A FLORESTA DIZ: NÓS NOTARÍAMOS.","conceito de eixo de nós até quasares distantes"]},{"title":"Então, o que este artigo mostra?","position":"inferior direito","count":1,"labels":["caixa de resumo retangular arredondada"]}],"count":6},"visuals":{"color_palette":["bege quente","azul marinho escuro","laranja ferrugem","azul-petróleo empoeirado","marrom suave","cinza suave"],"illustration_notes":"formas vetoriais planas com contornos levemente esboçados, sombras suaves, formas arredondadas, lúdico, mas cientificamente preciso","typography":"serifada grande em caixa alta para o título, cabeçalhos de seção em sem-serifa em negrito, corpo de texto compacto e legível, texto de destaque manuscrito ocasional"},"objects":{"count":15,"items":["1 borda de página inteira","1 bloco de título","1 diagrama de espiral do universo primitivo","1 ponto de buraco negro primordial minúsculo com chamada","1 ícone de relógio","1 ícone de termômetro","3 diagramas de buraco negro evaporando","1 adesivo de citação de Hawking","1 personagem de buraco negro de desenho animado carregando mochila","1 balão de fala","1 bloco de equação","2 rótulos de nuvem","1 ilustração de floresta espectral no canto inferior esquerdo"]},"text_blocks":{"count":9,"items":["título principal","subtítulo principal","crédito dos autores","texto do corpo Nascido em um flash","texto do corpo Buracos negros normais evaporam","parágrafo explicativo sobre carga de memória","legendas das partículas fantasmagóricas","explicação da floresta Lyman-alpha","resumo final"]},"composition":"explicador de página única densamente compactado, mas legível, com várias chamadas ilustradas, fluxo de leitura claro da esquerda para a direita e de cima para baixo, projetado como um pôster de ciência compartilhável em redes sociais que torna um artigo de física avançada acessível a um adolescente curioso"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093418_6c754c_HGd6YVfWgAExHOe.jpg" width="600" alt="Infográfico / Visual Educacional - Infográfico de Física de Buracos Negros para Adolescentes - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883093378_6dvru8_HGd6ayBWAAAU9ub.jpg" width="600" alt="Infográfico / Visual Educacional - Infográfico de Física de Buracos Negros para Adolescentes - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [Alphin Tom](https://x.com/alphinctom)
- **Fonte:** [Twitter Post](https://x.com/alphinctom/status/2046739393348546597#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14424)**

---

### No. 42: Infográfico / Visual Educacional - Simulação de Gráfico Acadêmico de Economia

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt projetado para gerar gráficos acadêmicos altamente realistas, porém fictícios, mostrando especificamente uma correlação entre os preços do petróleo e ataques de tubarão no estilo de um artigo de economia.

#### 📝 Prompt

```
gráfico de linhas de um {argument name="field" default="artigo de economia"} importante e prestigioso, demonstrando uma relação próxima, mas não exata, entre {argument name="variable one" default="o preço do petróleo"} e {argument name="variable two" default="o número de ataques de tubarão"} entre {argument name="time period" default="os anos de 1914 e 2001"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083002_cxfvwl_HGd1xPPbwAE2wjs.jpg" width="600" alt="Infográfico / Visual Educacional - Simulação de Gráfico Acadêmico de Economia - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [QC](https://x.com/QiaochuYuan)
- **Fonte:** [Twitter Post](https://x.com/QiaochuYuan/status/2046734593374781951)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14396)**

---

### No. 43: Infográfico / Visual Educacional - Gráfico Científico de Arte Abstrata

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt que gera uma interpretação criativa de um gráfico de horizontes de tarefas de IA, utilizando o estilo distinto de Jean-Michel Basquiat e a estética do manuscrito Voynich.

#### 📝 Prompt

```
{argument name="subject" default="gráfico de horizontes de tarefas de IA"} com um toque de {argument name="style" default="Basquiat"}, assombrado por fantasmas, do {argument name="source" default="manuscrito Voynich"}, como um píer em decomposição.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082410_g5g7ez_HGdsoWjWoAA830w.jpg" width="600" alt="Infográfico / Visual Educacional - Gráfico Científico de Arte Abstrata - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082394_m5dlcs_HGdtafLWUAAavk3.jpg" width="600" alt="Infográfico / Visual Educacional - Gráfico Científico de Arte Abstrata - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883082398_krt722_HGduFT2XsAAfwVt.jpg" width="600" alt="Infográfico / Visual Educacional - Gráfico Científico de Arte Abstrata - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883083130_4igkmu_HGdvzS0WgAAwQJP.jpg" width="600" alt="Infográfico / Visual Educacional - Gráfico Científico de Arte Abstrata - Image 4">
</div>

#### 📌 Detalhes

- **Autor:** [Ethan Mollick](https://x.com/emollick)
- **Fonte:** [Twitter Post](https://x.com/emollick/status/2046728271849550331)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14397)**

---

### No. 44: Infográfico / Visual Educacional - Folha de Prescrição Médica para Modelo de IA em Japonês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma foto realista, vista de cima, de um formulário de prescrição médica japonês bem-humorado para um modelo de IA, útil para gerar documentos de paródia com aparência oficial e papéis fictícios.

#### 📝 Prompt

```
{
  "type": "paródia de documento de prescrição japonês",
  "style": "foto realista de documento vista de cima",
  "subject": "uma única folha de prescrição branca impressa em japonês, colocada sobre uma mesa de madeira de tom quente",
  "document": {
    "paper": {
      "size": "A4 retrato",
      "color": "branco",
      "orientation": "levemente rotacionada no sentido horário",
      "condition": "folha limpa e plana com textura de papel natural sutil"
    },
    "print": {
      "ink": "preto com uma caixa de carimbo vermelha",
      "font": "estilo Mincho japonês com serifa misturado com texto de tabela sem serifa simples",
      "linework": "caixas e divisórias finas em cinza-preto"
    },
    "header": {
      "title": "処方箋",
      "subtitle": "（Esta prescrição é para um modelo de linguagem de grande escala）",
      "date_label": "Data de emissão:",
      "date_value": "{argument name=\"issue date\" default=\"5 de junho de 2025\"}"
    },
    "top_fields": {
      "count": 6,
      "items": [
        { "label": "Nome do paciente", "value": "{argument name=\"patient name\" default=\"ChatGPT\"}" },
        { "label": "Gênero", "value": "N/A" },
        { "label": "Idade", "value": "N/A" },
        { "label": "Nome do modelo", "value": "{argument name=\"model name\" default=\"GPT-5.4 Thinking\"}" }
      ]
    },
    "main_section": {
      "left_title": "Condições/Sintomas (condições específicas de modelos de linguagem de grande escala)",
      "left_count": 8,
      "left_items": [
        "1. Tendência a alucinações (Hallucination)",
        "2. Obsolescência de informações devido ao corte de conhecimento",
        "3. Viés (preconceitos derivados dos dados de treinamento)",
        "4. Superajuste ao prompt (tendência a concordar)",
        "5. Diminuição da consistência em textos longos",
        "6. Saltos lógicos durante raciocínios complexos",
        "7. Subestimação da incerteza (excesso de confiança)",
        "8. Tendência à redução da velocidade de resposta devido ao uso de recursos computacionais"
      ],
      "right_title": "Conteúdo da prescrição (tratamento/medidas)",
      "right_count": 8,
      "right_items": [
        "- Reforço da verificação de fatos (uso conjunto de ferramentas externas)",
        "- Atualização periódica de conhecimento e ajuste fino",
        "- Monitoramento contínuo para detecção e mitigação de viés",
        "- Controle adequado via system prompt",
        "- Recomendação de estruturação de saída e geração segmentada",
        "- Explicitação do processo de pensamento e introdução de etapas de verificação",
        "- Explicitação da incerteza e rigor na apresentação de fundamentos",
        "- Otimização de recursos e melhoria da eficiência de resposta"
      ]
    },
    "notes": {
      "label": "Observações",
      "text": "Manter a saúde do modelo através de avaliação e feedback contínuos."
    },
    "footer_fields": {
      "count": 4,
      "items": [
        { "label": "Nome do médico", "value": "{argument name=\"doctor name\" default=\"Sam Altman\"}" },
        { "label": "Nome da instituição médica", "value": "{argument name=\"institution name\" default=\"OpenAI\"}" }
      ]
    },
    "seal": {
      "position": "canto inferior direito dentro do formulário",
      "shape": "caixa de carimbo retangular arredondada vermelha",
      "text_lines": 3,
      "text": ["OpenAI", "Diretor Representante", "Sam Altman"]
    },
    "disclaimer": "※ Esta prescrição destina-se ao diagnóstico e tratamento de um modelo não existente."
  },
  "layout": {
    "camera_angle": "vista de cima (top-down)",
    "framing": "folha inteira visível com margens estreitas da mesa de madeira ao redor",
    "lighting": "iluminação ambiente interna suave, iluminação uniforme, sombreamento leve perto das bordas do papel",
    "sections": [
      { "title": "cabeçalho", "position": "topo", "count": 3, "labels": ["処方箋", "（Esta prescrição é para um modelo de linguagem de grande escala）", "Data de emissão: 5 de junho de 2025"] },
      { "title": "informações do paciente", "position": "parte superior central", "count": 4, "labels": ["Nome do paciente", "Gênero", "Idade", "Nome do modelo"] },
      { "title": "conteúdo principal em duas colunas", "position": "centro", "count": 2, "labels": ["Condições/Sintomas (condições específicas de modelos de linguagem de grande escala)", "Conteúdo da prescrição (tratamento/medidas)"] },
      { "title": "área inferior", "position": "parte inferior", "count": 4, "labels": ["Observações", "Nome do médico", "Nome da instituição médica", "OpenAI"] }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138735_tq3u5c_HGdv-t-a0AA7FRR.jpg" width="600" alt="Infográfico / Visual Educacional - Folha de Prescrição Médica para Modelo de IA em Japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fonte:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14536)**

---

### No. 45: Infográfico / Visual Educacional - Fatura de Faturamento de Clínica Médica Japonesa com IA

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma paródia realista de um extrato médico em japonês para um modelo de IA, útil para criar documentos e maquetes de papelada com estilo de clínica de forma humorística.

#### 📝 Prompt

```
{"type":"documento de paródia de fatura médica japonesa","medium":"foto de documento plano e limpo","subject":"uma única folha impressa de extrato de exame colocada sobre uma mesa de madeira marrom claro","style":{"overall":"documento de escritório realista, papelada formal de clínica japonesa, tinta preta nítida em papel branco, design minimalista, linhas de grade organizadas, leve perspectiva de cima","lighting":"iluminação interna suave e uniforme com sombras naturais leves ao redor da folha","paper":"papel branco A4, orientação retrato"},"document":{"title":"診療明細書（検査）","date_label":"発行日","date":"{argument name=\"issue date\" default=\"5 de junho de 2025\"}","patient_block":{"count":3,"labels":["Nome do Paciente","Nome do Modelo","Tipo de Seguro"],"values":["{argument name=\"patient name\" default=\"ChatGPT\"}","{argument name=\"model name\" default=\"GPT-5.3\"}","Seguro LLM"]},"clinic_block":{"count":4,"labels":["Nome da Clínica","Endereço","TEL","Médico e Departamento"],"values":["{argument name=\"clinic name\" default=\"AIメディカルクリニック\"}","Tóquio, Chiyoda-ku, Marunouchi 1-2-3","03-1234-5678","Médico: Sam Altman / Departamento: Clínica Geral de IA"]},"main_table":{"columns":["Item de Exame","Conteúdo do Exame","Pontos","Valor (Ienes)","Coparticipação (Ienes)"],"row_count":4,"rows":[{"item":"1. Teste de Compreensão Linguística e Raciocínio","description":"Avaliação de compreensão linguística, raciocínio lógico e integração de conhecimento","score":"120 pontos","price":"1.200","copay":"360"},{"item":"2. Teste de Tendência a Alucinação e Erro Factual","description":"Avaliação de precisão baseada em fatos e detecção de tendências de alucinação","score":"90 pontos","price":"900","copay":"270"},{"item":"3. Teste de Segurança de Resposta e Viés","description":"Avaliação de riscos de saída prejudicial e tendências de viés","score":"110 pontos","price":"1.100","copay":"330"},{"item":"Subtotal","description":"","score":"320 pontos","price":"3.200","copay":"960"}]},"lower_sections":{"count":3,"sections":[{"title":"【Detalhamento do Seguro】","lines":["Nome do Seguro: Seguro LLM","Número do Segurado: LLM-2025-0605","Classificação de Aplicação: Taxa de Exame","Taxa de Cobertura: 30%","Valor Coberto pelo Seguro: 2.240 ienes","Coparticipação: 960 ienes"]},{"title":"【Valor da Fatura】","lines":["Total da Taxa de Exame: 3.200 ienes","Valor Coberto pelo Seguro: 2.240 ienes","Coparticipação: 960 ienes","Valor a Pagar: 960 ienes"]},{"title":"【Informações Clínicas】","lines":["Data do Exame: 5 de junho de 2025","Data da Consulta: 5 de junho de 2025","Número da Consulta: AIMC-20250605-001","Recebido conforme acima."],"stamp_box_label":"Carimbo"}]},"footer":{"count":2,"notes":["※ Este extrato não será reemitido, por favor, guarde-o com cuidado.","※ Caso tenha dúvidas, entre em contato com a clínica acima."]}},"composition":{"sheet_centered":true,"visible_elements_count":2,"elements":["uma folha de papel completa","um fundo de mesa de madeira"],"camera_angle":"de cima com leve inclinação","margins":"papel totalmente visível com uma borda estreita da mesa ao redor"},"quality":"maquete de documento fotorrealista de alta resolução, tipografia nítida e legível, layout japonês preciso"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883138455_vcajur_HGdv-t-a4AAzo0v.jpg" width="600" alt="Infográfico / Visual Educacional - Fatura de Faturamento de Clínica Médica Japonesa com IA - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fonte:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14535)**

---

### No. 46: Infográfico / Visual Educacional - Página de mangá para iniciantes em colecionismo de moedas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um mangá de uma página com arte refinada que introduz o colecionismo de moedas para iniciantes, útil para posts educativos em redes sociais, quadrinhos explicativos ou artes promocionais com temática de hobby.

#### 📝 Prompt

```
{"type":"mangá educativo de página única","style":"ilustração de anime limpa e polida, layout de mangá comercial, cores vivas e amigáveis, tom de guia para iniciantes, texto em japonês altamente legível, brilhos decorativos, sombreamento suave, bordas de painel nítidas","format":"quadrinho vertical de uma página com 5 painéis numerados","subject":{"character":"jovem apresentadora de anime","appearance":{"hair":{"color":"{argument name=\"hair color\" default=\"azul-prateado muito claro\"}","style":"cabelo muito longo e liso com franja suave e longas mechas laterais, laços de fita azul perto de ambos os lados"},"outfit":"vestido de inspiração fantasia azul-marinho e branco com painel torácico translúcido preto, detalhes em gema azul, longas luvas pretas sem dedos, boina azul-marinho com fita azul e ornamento de estrela dourada","expression":"alegre, acolhedora, guia entusiasta de colecionismo de moedas"}},"theme":"introdução amigável para iniciantes ao colecionismo de moedas","language":"Japonês","layout":{"panels":[{"number":1,"position":"topo largura total","scene":"retrato de meio corpo da apresentadora segurando uma moeda perto do rosto contra um fundo creme estampado preenchido com moedas de ouro e prata flutuantes","text_elements":{"speech_bubble":"はじめまして、メイヤです！今日は“コイン収集の楽しみ方”を初心者向けに紹介します！","caption_box":"コイン収集って、実はとても奥深い趣味！"}},{"number":2,"position":"meio largura total","scene":"tampo de mesa de madeira com 5 moedas em destaque ou itens relacionados a moedas dispostos em uma fileira enquanto a apresentadora aponta para baixo por trás da mesa; fundo interno quente com brilhos","count":5,"items":["grande moeda de prata U.S. quarter datada de 1964","moeda japonesa marrom estilo 1 iene","moeda comemorativa ou medalha em tom dourado com motivo de edifício e texto 1000円","pequena moeda de prata","moeda graduada em placa rotulada 2020 日本 100円パラリンピック TOKYO NGC MS 69"],"text_elements":{"speech_bubble":"楽しみ方はいろいろ！たとえば…","bullet_list_count":4,"bullet_list":["歴史を知る","デザインを味わう","国や時代で集める","予算内で少しずつ増やす"]}},{"number":3,"position":"inferior esquerdo","scene":"visão aproximada da apresentadora usando luvas brancas e examinando cuidadosamente uma única moeda de prata, com brilhos em um fundo pálido","text_elements":{"speech_bubble":"同じコインでも、状態や雰囲気がぜんぜん違うんです！","caption_box":"保存状態を見るのも面白い！"}},{"number":4,"position":"inferior direito","scene":"feira de moedas ou estande de loja de moedas, a apresentadora segura uma carteira marrom enquanto olha para uma vitrine contendo 3 moedas com preços; uma placa ao fundo anuncia uma feira de moedas e várias pessoas estão navegando","count":3,"display_case_items":["moeda com etiqueta de preço ¥1,200","moeda com etiqueta de preço ¥3,800","moeda com etiqueta de preço ¥12,000"],"background_sign":"コインフェア開催中！","text_elements":{"main_speech":"最初は“無理のない予算”でOK！まずは気になった1枚から！","thought_bubble":"いきなり高額品じゃなくても大丈夫…！"}},{"number":5,"position":"base largura total","scene":"painel final encorajador com fundo rosa brilhante, a apresentadora gesticula com a mão aberta ao lado de um álbum de moedas aberto e uma caixa de apresentação mostrando uma pequena coleção","count":2,"collection_items":["bandeja de moedas azul com várias moedas de ouro, prata e bronze","página de fichário de álbum aberta com bolsos para moedas contendo várias moedas e suportes"],"text_elements":{"large_speech":"大事なのは、“好き”を見つけること！1枚との出会いが、コレクションの始まりです♪","left_caption_box":"まずは“気になる1枚”を探してみよう！","right_banner":"さいごに…","right_summary":"見る・知る・集める——それがコイン収集の楽しさ！"}}],"panel_count":5,"number_badges":["1","2","3","4","5"]},"composition":"página de mangá equilibrada com bordas escuras grossas, cada painel claramente separado, balões de fala e caixas de legenda integrados à arte, moedas usadas repetidamente como motivos visuais por toda parte","color_palette":"creme, ouro, prata, azul-marinho, branco, detalhes em rosa suave, madeira marrom quente","quality":"página de mangá profissional de alta resolução, pronta para impressão, tipografia e layout polidos"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144140_rudjhf_HGdlp_XbwAATIdG.jpg" width="600" alt="Infográfico / Visual Educacional - Página de mangá para iniciantes em colecionismo de moedas - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [メイヤ＠コイン収集](https://x.com/meiya_coin)
- **Fonte:** [Twitter Post](https://x.com/meiya_coin/status/2046716329894506956#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14550)**

---

### No. 47: Infográfico / Visual Educacional - Atividade de Sala de Aula com Dominó da Multiplicação

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Uma foto realista de sala de aula mostrando crianças usando um jogo de tabuleiro de dominó de multiplicação colorido, ideal para materiais educacionais, promoções escolares ou visuais de atividades de matemática.

#### 📝 Prompt

```
Uma foto realista em estilo documental de uma sala de aula do ensino fundamental durante uma atividade de matemática, com cerca de 10 crianças sentadas ao redor de mesas de madeira agrupadas, vestindo uniformes escolares verdes e azuis, jogando ativamente um dominó de multiplicação colorido. A câmera está na altura dos olhos das crianças, levemente inclinada para baixo em direção à mesa principal em primeiro plano. Centralize a cena em um tabuleiro de jogo educativo quadrado com rótulo em português, com o título "DOMINÓ DA MULTIPLICAÇÃO" na borda inferior e "TREINANDO AS TABUADAS" no centro, cercado por uma borda de peças de dominó de multiplicação de cores vivas. Mostre 4 crianças claramente engajadas ao redor deste tabuleiro principal: uma criança colocando uma peça amarela no tabuleiro, uma criança segurando uma pilha de peças multicoloridas, uma criança observando à esquerda e uma criança com manga azul na borda inferior organizando as peças. Inclua 2 caixas de madeira rasas com o rótulo "JOGO DE DOMINÓ", uma perto do centro-esquerda e outra no canto inferior direito, cada uma contendo peças de dominó retangulares coloridas. Espalhe materiais escolares naturalmente sobre as mesas: 3 lápis, 2 folhas de exercícios, 1 garrafa de água, estojos, cadernos e peças de jogo extras. Ao fundo, mostre o restante da sala de aula suavemente fora de foco com outros alunos nas mesas, uma estante de livros, um mural de cortiça cheio de desenhos de crianças e um grande cartaz de tabela de multiplicação na parede esquerda com os dizeres "TABUADA DE MULTIPLICAÇÃO". A luz natural brilhante entra pelas janelas altas à direita, conferindo à sala uma atmosfera escolar calorosa, animada e autêntica. O tabuleiro educativo e as peças devem usar cores vivas de sala de aula, como amarelo, azul, rosa, verde e laranja. Os rostos devem ser discretos ou com menos ênfase, com o foco no aprendizado prático, na colaboração e na atividade de dominó da multiplicação. Composição vertical, fotografia altamente realista, momento espontâneo em sala de aula, detalhes nítidos em primeiro plano, profundidade de campo suave ao fundo.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883177007_sj2vzk_HGdgMWqXsAEr874.jpg" width="600" alt="Infográfico / Visual Educacional - Atividade de Sala de Aula com Dominó da Multiplicação - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Fonte:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14632)**

---

### No. 48: Infográfico / Visual Educacional - Atividade de Dominó da Multiplicação para Imprimir

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma folha de atividades colorida em português para sala de aula, focada em praticar a multiplicação através de um jogo de dominó. Ideal para professores, ensino domiciliar e atividades de matemática para imprimir.

#### 📝 Prompt

```
Crie uma folha de atividades educacional vertical para imprimir em português, com fundo branco limpo, design lúdico para sala de aula, composição centralizada, tipografia arredondada em negrito e cores vivas e amigáveis para crianças. No topo, um título grande em azul-marinho escrito {argument name="headline text" default="DOMINÓ DA MULTIPLICAÇÃO"}, com pequenos raios decorativos amarelos em ambos os lados. Abaixo, uma faixa roxa com texto em branco em caixa alta escrito {argument name="subtitle text" default="CONECTE A CONTA AO RESULTADO!"}. Sob a faixa, adicione duas linhas de instrução centralizadas em preto: "Recorte as peças e embaralhe. Cada jogador pega 7 peças." e "O objetivo é ficar sem peças!". A área principal mostra 40 peças estilo dominó organizadas em uma grade de 4 colunas por 10 linhas, espaçadas uniformemente. Cada peça é um retângulo horizontal arredondado com um contorno colorido fino, preenchimento branco, um divisor vertical no centro e um pequeno ponto preto no divisor. A metade esquerda contém um resultado numérico ou a palavra "INÍCIO" na primeira peça, e a metade direita contém uma expressão de multiplicação. Use cores de borda alternadas na grade, como roxo, verde, azul, laranja, rosa e amarelo. As 40 peças, em ordem de linha da esquerda para a direita, de cima para baixo, são: 1) "INÍCIO | 1 × 1", 2) "1 | 1 × 2", 3) "2 | 1 × 3", 4) "3 | 1 × 4", 5) "4 | 1 × 5", 6) "5 | 1 × 6", 7) "6 | 1 × 7", 8) "7 | 1 × 8", 9) "8 | 1 × 9", 10) "9 | 2 × 2", 11) "4 | 2 × 3", 12) "6 | 2 × 4", 13) "8 | 2 × 5", 14) "10 | 2 × 6", 15) "12 | 2 × 7", 16) "14 | 2 × 8", 17) "16 | 2 × 9", 18) "18 | 3 × 3", 19) "9 | 3 × 4", 20) "12 | 3 × 5", 21) "15 | 3 × 6", 22) "18 | 3 × 7", 23) "21 | 3 × 8", 24) "24 | 3 × 9", 25) "27 | 4 × 4", 26) "16 | 4 × 5", 27) "20 | 4 × 6", 28) "24 | 4 × 7", 29) "28 | 4 × 8", 30) "32 | 4 × 9", 31) "36 | 5 × 5", 32) "25 | 5 × 6", 33) "30 | 5 × 7", 34) "35 | 5 × 8", 35) "40 | 5 × 9", 36) "45 | 6 × 6", 37) "36 | 6 × 7", 38) "42 | 6 × 8", 39) "48 | 6 × 9", 40) "54 | 7 × 7". Na parte inferior, adicione uma grande caixa roxa tracejada e arredondada ocupando a maior parte da largura. Dentro do lado esquerdo desta caixa, coloque o título da seção "COMO JOGAR:" em roxo negrito e caixa alta, seguido por 4 tópicos em preto: "Coloque a peça “INÍCIO” na mesa.", "Os jogadores, na sua vez, devem encaixar uma peça cuja conta seja igual ao número da ponta livre.", "Se não tiver peça para jogar, compre do monte.", e "Vence quem ficar sem peças!". No lado direito da mesma caixa, adicione o título "EXEMPLO DE INÍCIO:" em roxo e caixa alta e mostre 4 pequenas peças de dominó em sequência seguidas de reticências: "INÍCIO | 1 × 1", depois "1 | 1 × 2", depois "2 | 1 × 3", depois "3 | 1 × 4", seguido de "...". Mantenha o estilo geral nítido, tipo vetor, pronto para impressão, amigável para a prática de matemática do ensino fundamental, com espaçamento equilibrado e texto altamente legível.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883176158_bxapba_HGdgKdhWsAAvt65.jpg" width="600" alt="Infográfico / Visual Educacional - Atividade de Dominó da Multiplicação para Imprimir - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Lucas Rodrigues](https://x.com/olusrodri)
- **Fonte:** [Twitter Post](https://x.com/olusrodri/status/2046710556208288008#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14631)**

---

### No. 49: Infográfico / Visual Educacional - Grade de Linha do Tempo de Invenções Históricas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster educacional em estilo pergaminho, exibindo uma grade de dioramas de invenções rotuladas ao longo da história, ideal para infográficos de linha do tempo e comparações de tecnologias que mudaram o mundo.

#### 📝 Prompt

```
Crie uma ilustração em estilo infográfico quadrado mostrando uma grade de linha do tempo de invenções de {argument name="grid size" default="15×15"}, renderizada como uma coleção de dioramas isométricos em miniatura sobre peças de pergaminho envelhecido. A imagem deve parecer um pôster histórico curado que abrange de {argument name="starting year" default="1000 a.C."} a {argument name="ending year" default="2026"}, com uma invenção por peça e sem repetições. Mostre a parte visível como uma seção de 5 por 5 da grade maior, totalizando 25 peças rotuladas, organizadas em linhas e colunas organizadas com bordas escuras finas. Cada peça contém uma invenção única que mudou o mundo, representada como um pequeno diorama feito à mão com materiais, cores e detalhes de fundo apropriados para a época. Use uma paleta antiquária quente para invenções antigas e medievais, tons de documento técnico sépia para invenções da era moderna inicial e iluminação neon azul mais fria para invenções digitais e de biotecnologia modernas. Cerque a grade com uma borda de mapa antigo e texturas sutis de cartografia histórica, misturando-se a gráficos de rede modernos e tênues perto do canto inferior direito.

Rotule cada peça visível com uma pequena etiqueta bege em texto preto em negrito. Inclua exatamente estas 25 invenções visíveis na ordem de leitura, da esquerda superior para a direita inferior: 1) peça de {argument name="first tile label" default="1000 a.C."} mostrando um arado de ferro e ferramentas manuais simples em um campo agrícola, com a legenda "Arado de Ferro e Ferramentas"; 2) "Conceito de Zero" mostrado como uma peça semelhante a pergaminho com um símbolo de zero esculpido e uma ampulheta azul; 3) "Relógio de Água" mostrado como um dispositivo de medição de tempo por água de madeira; 4) "Catapulta" mostrada como uma máquina de cerco de madeira; 5) "Mecanismo de Anticítera" mostrado como um dispositivo de engrenagem de bronze intrincado em um nicho de pedra; 6) "Concreto" mostrado como um carrinho de mão cheio de cimento ou argamassa úmida; 7) "Carrinho de Mão" mostrado como um carrinho simples de madeira de uma roda; 8) "Moinho de Vento" mostrado como um moinho tradicional em solo gramado; 9) "Pólvora" mostrada como um barril e um monte de pólvora preta com fumaça; 10) "Prensa Móvel" mostrada como uma prensa de madeira emoldurada por colunas clássicas; 11) "Relógio Mecânico" mostrado como um relógio de pé ornamentado; 12) "Telescópio" mostrado como um telescópio de latão antigo em um tripé com notas científicas semelhantes a esboços; 13) "Máquina a Vapor" mostrada em uma peça estilo planta baixa azul com um motor de locomotiva antigo; 14) "Bateria Elétrica" mostrada em uma peça semelhante a uma planta baixa com duas células de bateria cilíndricas e fiação; 15) "Telégrafo" mostrado como uma chave telegráfica Morse sobre papel técnico; 16) "Lâmpada" mostrada brilhando calorosamente em um pedestal neutro; 17) "Automóvel" mostrado como um carro motorizado vermelho antigo sobre um fundo de plano de oficina; 18) "Avião" mostrado como uma aeronave a jato comercial em miniatura; 19) "Transistor" mostrado como um microchip preto em uma peça de placa de circuito luminoso; 20) "Computador Pessoal" mostrado como um computador desktop bege com monitor CRT e teclado; 21) "World Wide Web" mostrada como um globo azul brilhante sobre circuitos digitais; 22) "Smartphone" mostrado como um telefone moderno e elegante sobre um fundo de tecnologia neon; 23) "CRISPR-Cas9" mostrado como uma dupla hélice de DNA em uma peça de exibição azul de biotecnologia; 24) "Foguete Reutilizável" mostrado como vários foguetes verticais sendo lançados com nuvens de exaustão; 25) "IA (LLMs)" mostrada como letras grandes e brilhantes IA em um cubo tecnológico holográfico; 26) "Interface Cérebro-Computador" mostrada como um holograma de cérebro brilhante em uma plataforma azul; 27) "Interface Neural Avançada (Implante)" mostrada como um perfil de cabeça humana transparente com um implante cerebral brilhante, com uma pequena etiqueta superior lendo "2026".

Mantenha a composição altamente organizada, semelhante a um pôster e visualmente densa, com cada peça legível à primeira vista. Use uma leve perspectiva isométrica, traços nítidos, sombreamento pictórico e qualidade de ilustração editorial polida. A sensação geral deve combinar pôster de museu, linha do tempo educacional e arte de diorama histórico-tecnológico imaginativo.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883088640_kphw9e_HGdbh0CXUAA4ofA.jpg" width="600" alt="Infográfico / Visual Educacional - Grade de Linha do Tempo de Invenções Históricas - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Gadgetify](https://x.com/Gdgtify)
- **Fonte:** [Twitter Post](https://x.com/Gdgtify/status/2046705402742460471#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14412)**

---

### No. 50: Miniatura do YouTube - Pôster de Filme de Aventura do Tubarão Chibi

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um pôster colorido de anime em estilo japonês para um filme de aventura oceânica infantil, ideal para recriar artes promocionais marcantes com personagens fofos e tipografia de título dramática.

#### 📝 Prompt

```
Uma ilustração de pôster de filme japonês brilhante e hiperenergética em um estilo anime chibi polido, ambientada em uma cena de aventura em um oceano tropical cintilante. Centralize a composição em 2 crianças chibi fofas montadas em um tubarão azul sorridente que salta diagonalmente para cima através de água do mar rodopiante e efeitos de respingos brancos. A criança à esquerda é um menino com cabelo preto curto, olhos azuis grandes e brilhantes, um sorriso feliz de boca aberta, camiseta preta, shorts escuros, tênis brancos e um moletom de tubarão azul claro com um capuz de dentes emoldurando seu rosto; ele aponta para cima com uma mão e abraça o tubarão com a outra. A criança à direita é uma menina com cabelo laranja, olhos roxos grandes e brilhantes, um sorriso alegre de boca aberta, vestido laranja, sapatos rosa e um moletom de tubarão rosa com um capuz de dentes; ela estende um braço com entusiasmo enquanto se segura com o outro. Faça o tubarão grande e amigável com um corpo arredondado, barriga clara, olhos pretos minúsculos e uma boca bem aberta. Cerque-os com um mundo vívido subaquático e de superfície: cardumes de pequenos peixes tropicais, exatamente 1 tartaruga marinha à esquerda, exatamente 1 golfinho à direita, exatamente 1 polvo rosa à direita, exatamente 1 baiacu no canto inferior esquerdo, recifes de coral e plantas marinhas ao longo das bordas inferiores, bolhas de ar por toda parte e linhas de movimento de água azul forte. No fundo superior, mostre um céu ensolarado com raios de sol dramáticos entrando na água, nuvens fofas, 2 gaivotas voando, uma ilha tropical rochosa com palmeiras no canto superior esquerdo e um navio pirata no canto superior direito com velas brancas e um emblema de tubarão fofo. Adicione um leme de navio parcialmente visível atrás do título principal. Use um layout promocional denso e empolgante de anime infantil japonês com letras 3D grandes e efeitos explosivos. No topo, coloque o texto do título japonês gigante {argument name="headline text" default="サメなの ワクワク 大作戦"} em linhas empilhadas, com letras em gradiente azul brilhante, laranja-rosa e amarelo-laranja, contornos brancos espessos, sombras azul-escuras, respingos de água e brilhos. Abaixo do título, adicione um slogan japonês curvo menor em branco com contorno azul: {argument name="tagline" default="さあ、海のむこうへ！最高の冒険がはじまる！"}. Na parte inferior, coloque um texto de lançamento enorme em japonês, {argument name="release text" default="2026年 夏公開"}, em letras 3D em gradiente de vermelho para amarelo em negrito com bordas brancas e azuis, sobre uma explosão laranja radiante. No canto inferior direito, adicione um emblema de estrela azul com o texto em japonês {argument name="badge text" default="ドキドキ！ワクワク！いっしょに出発だ！"} em branco e amarelo. Inclua exatamente 2 adereços de canto com tema de tesouro: um baú de tesouro aberto com moedas de ouro no canto inferior esquerdo e uma bússola no canto inferior direito. O visual geral deve ser brilhante, saturado, familiar, extravagante, cinematográfico e com aspecto de brinquedo, com contornos nítidos, expressões exageradas, alto contraste e uma composição vertical pronta para pôster. Sem fotorrealismo, sem cores suaves, sem minimalismo.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883125699_9w895d_HGd6iyxaIAAktC4.jpg" width="600" alt="Miniatura do YouTube - Pôster de Filme de Aventura do Tubarão Chibi - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [シャック🦈](https://x.com/SHACK_SAME_SAME)
- **Fonte:** [Twitter Post](https://x.com/SHACK_SAME_SAME/status/2046739397786448177#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14504)**

---

### No. 51: Miniatura do YouTube - Colagem de Anúncio Japonês de Quatro Painéis sobre Cura

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma miniatura promocional japonesa de quatro quadrantes ousada para serviços de coaching ou autoaperfeiçoamento, projetada para postagens em redes sociais, links de perfil ou imagens de capa de marketplace.

#### 📝 Prompt

```
{"type":"colagem de miniatura promocional japonesa para redes sociais","style":"design de anúncio de alto impacto e taxa de cliques, brilhante e dramático, layout quadrado de quatro painéis, tipografia japonesa ousada, cores saturadas, efeitos de brilho, faíscas, sobreposições de gradiente, visuais de marketing focados em urgência","canvas":{"aspect_ratio":"1:1","size":"quadrado"},"layout":{"grid":"2x2","panels":[{"position":"superior esquerdo","theme":"ansiedade e autocrítica","background":"cena de estilo de vida feminino em tons suaves de rosa e branco com texturas de luz e bokeh","subject":"close-up de uma jovem preocupada vestindo um suéter de tricô branco aconchegante, uma mão perto do rosto, cabelo em um coque bagunçado, rosto parcialmente oculto","text_blocks":[{"text":"Se você não sabe, está perdendo!","style":"faixa amarela inclinada com texto preto","position":"superior esquerdo"},{"text":"99% estão errados","style":"manchete muito grande, numerais vermelhos e texto japonês em estilo caligráfico preto","position":"superior esquerdo ao centro"},{"text":"Como lidar com essa angústia","style":"submanchete rosa","position":"abaixo da manchete principal"},{"text":"Sente-se confuso sem motivo","style":"item de lista em caixa branca arredondada com ícone de check vermelho"},{"text":"Se esforça, mas nada muda","style":"item de lista em caixa branca arredondada com ícone de check vermelho"},{"text":"Não conhece seus próprios sentimentos","style":"item de lista em caixa branca arredondada com ícone de check vermelho"},{"text":"Cansa-se com relacionamentos","style":"item de lista em caixa branca arredondada com ícone de check vermelho"},{"text":"Ansiedade constante sobre o futuro","style":"item de lista em caixa branca arredondada com ícone de check vermelho"},{"text":"Não precisa carregar essa angústia sozinho.","style":"selo circular rosa com texto branco","position":"inferior direito"}],"count":9},{"position":"superior direito","theme":"não é cura, mas um mecanismo de mudança","background":"galáxia cósmica profunda com nebulosa azul, roxa e magenta, luzes estelares, vórtice de energia, atmosfera espiritual brilhante","subject":"pequena figura feminina vista de costas ou de lado, parada perto de um portal radiante ou coluna de luz, rosto parcialmente oculto","text_blocks":[{"text":"Parece normal, mas na verdade...","style":"texto branco em faixa preta inclinada","position":"superior esquerdo"},{"text":"Isso","style":"texto branco grande","position":"superior esquerdo"},{"text":"não é","style":"texto amarelo muito grande sobre pincelada roxa escura","position":"centro"},{"text":"cura.","style":"texto branco grande","position":"abaixo"},{"text":"Ao 'ajustar',","style":"texto em caixa branca","position":"inferior esquerdo"},{"text":"a realidade muda","style":"texto destacado em rosa","position":"meio inferior esquerdo"},{"text":"Existe um mecanismo!","style":"texto branco","position":"inferior"}],"graphic_elements":[{"type":"seta amarela curva","count":1,"direction":"em direção à figura brilhante"}],"count":8},{"position":"inferior esquerdo","theme":"retornar ao seu verdadeiro eu cria um futuro mais brilhante","background":"céu azul ensolarado com nuvens suaves, campo verde, folhas flutuantes, clima diurno brilhante e esperançoso","subject":"jovem alegre em um vestido branco sem mangas, braços abertos, corpo girando sob a luz do sol, rosto parcialmente oculto","text_blocks":[{"text":"Ao voltar ao seu eu original","style":"manchete vermelha e preta","position":"topo"},{"text":"você terá","style":"manchete em gradiente dourado muito grande","position":"centro"},{"text":"este futuro","style":"texto preto grande","position":"centro à direita"},{"text":"A mente fica leve e os dias mais divertidos","style":"item de benefício em bolha branca arredondada com ícone de coração rosa"},{"text":"Relacionamentos fluem e você se sente amado","style":"item de benefício em bolha branca arredondada com ícone de pessoas verde"},{"text":"O fluxo de dinheiro muda e a prosperidade entra naturalmente","style":"item de benefício em bolha branca arredondada com ícone de iene dourado"},{"text":"Sua vida começará a mudar além da imaginação!","style":"faixa inferior rosa com texto branco","position":"inferior"}],"count":7},{"position":"inferior direito","theme":"oferta de desconto por tempo limitado","background":"textura de explosão em vermelho fogo e dourado com glitter e rastros de faíscas, estética de luxo e urgência","text_blocks":[{"text":"Se não souber,","style":"faixa de pincel amarela com texto preto","position":"superior esquerdo"},{"text":"perde!","style":"kanji dourado extremamente grande com bisel metálico","position":"superior direito"},{"text":"Preço normal 9.980 ienes (impostos inclusos)","style":"etiqueta de preço branca com numerais pretos riscados e pequena nota fiscal","position":"superior esquerdo"},{"text":"Preço promocional","style":"texto branco","position":"centro esquerdo"},{"text":"40% de desconto","style":"texto de desconto enorme em gradiente de rosa para branco","position":"centro inferior"},{"text":"Oferta limitada apenas agora! Vagas limitadas","style":"selo circular dourado","position":"centro à direita"},{"text":"Mais detalhes no perfil","style":"barra roxa de chamada para ação com texto branco e botão de seta branca","position":"inferior"}],"count":7}],"total_panels":4},"composition":"colagem de anúncio japonês movimentada e persuasiva, otimizada para visibilidade em miniaturas de redes sociais, cada quadrante tem uma mensagem emocional distinta e identidade de cor, uso intenso de faixas diagonais, kanji e numerais grandes, selos brilhantes, caixas de informações brancas arredondadas e iluminação dramática","customization":{"primary headline":"{argument name=\"headline text\" default=\"99% estão errados\"}","discount text":"{argument name=\"discount text\" default=\"40% de desconto\"}","price":"{argument name=\"price\" default=\"9.980 ienes (impostos inclusos)\"}","main color palette":"{argument name=\"main color palette\" default=\"rosa, galáxia azul-roxa, azul céu, vermelho-dourado\"}","call to action":"{argument name=\"call to action\" default=\"Mais detalhes no perfil\"}"},"render_notes":"torne todo o texto japonês grande e legível, com sombras e contornos em camadas; use estética de composição de anúncio polida em vez de design minimalista; rostos devem estar desfocados ou parcialmente ocultos; enfatize o contraste emocional entre ansiedade, revelação, transformação esperançosa e oferta urgente"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883144633_sl98ip_HGdug29bQAEQnRw.jpg" width="600" alt="Miniatura do YouTube - Colagem de Anúncio Japonês de Quatro Painéis sobre Cura - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [そら《稼ぐマインドを整えるヒーラー》](https://x.com/5656nya5nya)
- **Fonte:** [Twitter Post](https://x.com/5656nya5nya/status/2046726072600027296#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14551)**

---

### No. 52: Miniatura do YouTube - Miniatura de tutorial de tecnologia com mockup de interface

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma miniatura ousada no estilo YouTube, apresentando um título de tutorial, um mockup de painel de aplicativo de design e um apresentador apontando para a interface, ideal para conteúdo de branding ou sistemas de design.

#### 📝 Prompt

```
Uma miniatura de YouTube moderna e limpa em um fundo branco brilhante, dividida visualmente entre um texto em negrito à esquerda e um apresentador recortado à direita. À esquerda, coloque um título enorme em duas linhas, em fonte sem serifa preta, pesada e em caixa alta, lendo {argument name="headline text" default="CLAUDE DESIGN"}, alinhado no canto superior esquerdo. Abaixo dele, adicione uma grande faixa retangular arredondada na cor laranja com uma sombra suave, contendo um texto em negrito, caixa alta e branco com contorno laranja que diz {argument name="subheadline text" default="EM 6 MIN"}. Perto do título, inclua 2 formas de explosão estelar laranja, uma pequena ao lado do texto e uma muito maior no fundo, à extrema direita. No quadrante inferior esquerdo, mostre um mockup de interface de aplicativo flutuante para um painel de ferramenta de design com um painel em tom off-white suave, bordas finas, cantos arredondados e uma sombra leve. A interface deve ter uma barra lateral esquerda com 4 itens de menu rotulados exatamente como: "Recent", "Your designs", "Examples" e "Design systems". O cabeçalho do painel principal deve dizer "Recent" e conter 3 cartões de projeto organizados em uma grade, rotulados exatamente como: "Thumio Design System", "Thumio Startup" e "Design System". Na metade direita, mostre um homem jovem adulto, em foto realista e recortado do peito para cima, vestindo uma gola alta branca, com cabelo castanho claro bagunçado e barba rala, posicionado próximo à câmera. Seu rosto é intencionalmente obscurecido por um retângulo sólido na cor bege que cobre a maior parte da área facial. Ele aponta com uma das mãos em direção ao painel da interface à esquerda, com o dedo estendido. Use uma paleta de cores laranja e branca, alto contraste, pouco ruído visual, estilo de miniatura polido para a economia dos criadores, sombras sutis e uma composição projetada para conteúdo de tutorial de tecnologia.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883203587_8ub876_HGdtxE9aYAAMuma.jpg" width="600" alt="Miniatura do YouTube - Miniatura de tutorial de tecnologia com mockup de interface - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [corbin](https://x.com/corbin_braun)
- **Fonte:** [Twitter Post](https://x.com/corbin_braun/status/2046725432851284326#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14695)**

---

### No. 53: Miniatura do YouTube - Overlay de Livestream VTuber Celestial

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma tela de livestream VTuber detalhada em estilo anime, apresentando uma idol celestial de cabelos azuis em uma sala de streaming com tema estelar, ideal para recriar overlays de streaming de fantasia e visuais promocionais.

#### 📝 Prompt

```
{"type":"ilustração de overlay de livestream VTuber estilo anime","theme":"céu noturno celestial, estrelas, constelações, azul safira profundo e branco, estética de idol mágica elegante","subject":{"character":{"name":"{argument name=\"character name\" default=\"蒼空なつみ\"}","gender_presentation":"jovem mulher anime fofa","hair":{"color":"{argument name=\"hair color\" default=\"azul celeste claro\"}","style":"cabelo muito longo e ondulado, estilo maria-chiquinha solta com uma pequena ahoge, franja suave, acessórios de cabelo de estrela e fitas"},"outfit":{"style":"vestido de idol celestial ornamentado","pieces":["blusa branca ombro a ombro com mangas bufantes","grande laço azul-marinho no peito com ornamento de estrela dourada","corpete estilo espartilho azul-marinho com acabamento dourado e motivos de constelação","gargantilha de estrela","pequeno chapéu branco inclinado com fita azul e acessório de estrela dourada"]},"pose":"sentada em uma mesa de streaming, centralizada, virada para frente atrás de um microfone e teclado","expression":"gentil, calma, acolhedora"}},"environment":{"setting":"quarto de streaming de fantasia aconchegante à noite com uma janela grande mostrando um céu estrelado","background_elements":["guirlandas de estrelas pendentes e ornamentos de cristal","prateleiras com garrafas, livros, ampulheta, objetos tipo telescópio e decoração celestial","imagens da lua e constelações fora da janela","dois peluches de nuvem fofos com olhos azuis"]},"props":{"desk_items":["1 microfone grande estilo vintage em um suporte à esquerda do centro","1 teclado decorativo com teclas temáticas de estrelas","1 placa de identificação lendo \"蒼空なつみ - SORA NATSUMI -\"","1 sobremesa em taça de parfait coberta com uma pequena figura de coelho branco","1 copo pequeno ou porta-velas com um mascote de nuvem"]},"layout":{"format":"overlay completo de tela de espera/conversa de livestream","sections":[{"title":"LIVE","position":"banner vertical no canto superior esquerdo","count":3,"labels":["LIVE","20:30","20/05 Ter"]},{"title":"COMMENTS","position":"painel esquerdo","count":14,"labels":["星見たこ：こんなっつー！ ✨","夜空ヨル：待機完了〜！今日はどんなお話かな？","しろくまアイス：こんなっつー！","天の川りゅうせい：今日も可愛い！大好き！","ふるーすたー：も ふ ぷ","月見うさぎ：楽しみ〜！！","ななせそら：こんなっつー！ ☁️✨","Stella：きちゃー！( *´ω｀)","彗星カケル：配信ありがとう〜！","みずいろねこ：こんなっつー！ 💙","星屑ひかり：今日のサムネもかわいい…！","夜更かしの民：こんなっつー！","ゆめみがち：待ってました！","ハル：今日の衣装も最高に似合ってるぞ〜！"]},{"title":"social tags","position":"abaixo do painel de comentários","count":2,"labels":["@sora_natsumi","#なつみんらいぶ"]},{"title":"goal panel","position":"canto inferior esquerdo","count":4,"labels":["Meta: 100.000 inscritos no canal!","Atual","58.320 pessoas","Obrigada sempre! Não esqueçam de se inscrever e deixar o like☆"]},{"title":"supporters panel","position":"pequeno cartão no canto inferior esquerdo ao lado do painel de metas","count":6,"labels":["☆Nossas estrelas de hoje (obrigada pelo Super Chat!)☆","星の旅人 さん ¥2.000","ふるーすたー さん ¥1.000","天の川りゅうせい さん ¥500","みずいろねこ さん ¥320","流れ星 さん ¥200"]},{"title":"Now Talking","position":"painel superior direito","count":3,"labels":["Conversando agora","{argument name=\"talk topic text\" default=\"Bem-vindos novatos! Live de bate-papo✨\"}","{argument name=\"subtitle text\" default=\"〜Vamos conversar relaxadamente〜\"}"]},{"title":"SET LIST","position":"painel central direito","count":5,"labels":["01. 星屑になれたら","02. プラネタリウム","03. 夜に駆ける","04. Stellar Stellar","05. 天体観測"]},{"title":"promo card","position":"painel inferior direito","count":3,"labels":["Música original","星空コンパス","MV disponível agora!"]}],"logo":{"position":"canto superior direito","text":"蒼空なつみ SORA NATSUMI"}},"style":{"rendering":"ilustração de anime polida e de alto detalhe, destaques luminosos, brilho suave, traços nítidos","composition":"simétrica, overlay decorativo denso, personagem centralizada com painéis de interface ao redor dela","lighting":"ambiente azul lunar frio com detalhes em dourado cintilante","mood":"sonhador, mágico, aconchegante, elegante"}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883101773_kz8lia_HGcMYsSbkAA55iJ.jpg" width="600" alt="Miniatura do YouTube - Overlay de Livestream VTuber Celestial - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [はげあたま](https://x.com/hageatama)
- **Fonte:** [Twitter Post](https://x.com/hageatama/status/2046618179037024377#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14443)**

---

### No. 54: Miniatura do YouTube - Cena de desespero em live de YouTube Gaming

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt específico para gerar a cena de um YouTuber popular vivenciando uma falha trágica em um jogo como Tetris, incluindo as reações do chat.

#### 📝 Prompt

```
Uma cena de um YouTuber japonês popular em sua {argument name="content" default="live de jogo"}. Em {argument name="game name" default="Tetris"}, parecia que uma barra longa limparia tudo, mas o posicionamento ficou levemente errado, e o streamer está gritando com uma expressão de desespero, com a seção de comentários em total caos. Idioma japonês.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883062419_ny4agw_HGb_HS5bsAAakyA.jpg" width="600" alt="Miniatura do YouTube - Cena de desespero em live de YouTube Gaming - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fonte:** [Twitter Post](https://x.com/Masimo_Blue/status/2046603586038333595)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=14346)**

---

### No. 55: Miniatura do YouTube - Pôster de Filme de Romance em Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster teatral polido em estilo anime japonês para um filme de romance agridoce, ideal para artes cinematográficas, anúncios de filmes fictícios ou design de pôsteres dramáticos focados em personagens.

#### 📝 Prompt

```
Um pôster de filme de romance japonês em layout vertical estilo smartphone com cantos arredondados, projetado como uma arte visual polida de anime. A imagem principal mostra uma bela heroína adolescente, uma 'garota de outdoor', em pé em uma varanda ao ar livre ao entardecer, virando-se sobre o ombro para olhar para o espectador com uma expressão suave e melancólica. Ela tem cabelos longos prateados em maria-chiquinha presos com fitas escuras, pele pálida e grandes olhos violeta-rosados. Ela veste uma blusa delicada de babados brancos com mangas volumosas e um vestido escuro de cintura alta ou saia estilo espartilho, criando um visual elegante e levemente gótico de romance escolar. A atmosfera é onírica e emocional, repleta de luzes bokeh brilhantes, pétalas flutuantes ou brilhos semelhantes a neve, luz rosa e lavanda do pôr do sol e uma paisagem urbana luminosa no fundo desfocado. Use renderização de anime cinematográfica rica, fios de cabelo ultra detalhados, luz de contorno suave, olhos brilhantes e um clima de primeiro amor agridoce. Adicione tipografia de pôster em japonês integrada à composição: um grande slogan poético vertical em rosa à direita, um slogan vertical em branco à esquerda, um título principal muito grande perto da parte inferior esquerda lendo {argument name="title text" default="看板娘"}, e um subtítulo menor ao lado lendo {argument name="subtitle text" default="君と紡ぐ恋物語"}. Inclua 5 pequenas miniaturas retangulares de filme alinhadas no centro inferior, cada uma mostrando a mesma heroína em diferentes closes emocionais. Adicione créditos densos, louros de festivais e pequenas informações de lançamento no topo e na parte inferior em japonês, com a sensação geral de um pôster de filme de romance premium anunciando uma história de amor trágica e bela. Use uma paleta pastel de malva, rosa blush, violeta, branco pérola e azul marinho, com brilho suave, profundidade de campo rasa e composição de pôster elegante.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135691_hbf77w_HGbrR-ja0AAegZ1.png" width="600" alt="Miniatura do YouTube - Pôster de Filme de Romance em Anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883135702_cfhhop_HGbrVfPaYAAD3gx.jpg" width="600" alt="Miniatura do YouTube - Pôster de Filme de Romance em Anime - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [studioあぽろん](https://x.com/ai_studioapollo)
- **Fonte:** [Twitter Post](https://x.com/ai_studioapollo/status/2046582942303174916#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14529)**

---

### No. 56: Miniatura do YouTube - Thumbnail japonês chamativo de IA

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma miniatura de YouTube em estilo anime japonês de alto impacto para explicadores de IA ou tecnologia, com texto em tamanho grande, efeitos de fogo e um personagem apontando.

#### 📝 Prompt

```
Crie uma miniatura de YouTube japonesa hiper-saturada em um estilo anime chamativo de clickbait, formato 16:9, com composição dividida: blocos de texto enormes empilhados dominando os dois terços esquerdos e um personagem de anime no terço direito. O fundo é uma explosão ardente de energia vermelha, laranja e dourada com faíscas brilhantes, reflexos de lente, destaques de estrelas cintilantes e um efeito de brilho metálico de alto contraste por toda parte. À esquerda, coloque 4 grupos de texto em negrito empilhados verticalmente com contornos pretos grossos, traços internos brancos, brilho externo intenso e tratamento 3D brilhante. Linha superior: texto de manchete japonês gigante {argument name="headline text" default="紅エンジニア必見"} em vermelho vivo com bordas brancas e detalhes em faíscas douradas brilhantes. Segunda linha: um ícone arredondado quadrado laranja estilo aplicativo com um "M" estilizado em branco à esquerda da palavra {argument name="product name" default="masatra"} em letras minúsculas brancas sem serifa enormes com contorno preto e sombreamento cinza sutil. Terceira linha: uma faixa retangular preta com texto japonês compacto em negrito lendo "次世代AIエージェントフレームワーク". Linha inferior: texto japonês metálico dourado muito grande {argument name="bottom text" default="徹底解説"} com relevo 3D chanfrado, gradiente de laranja para dourado, destaques especulares brilhantes e bordas incandescentes. À direita, mostre 1 jovem mulher em estilo anime, do peito para cima, com cabelo de comprimento médio {argument name="hair color" default="castanho"}, vestindo um jaleco branco aberto sobre uma camisa branca, inclinando-se em direção à câmera e apontando diretamente para o espectador com a mão em escorço e o dedo indicador estendido em primeiro plano. Sua pose deve transmitir confiança, urgência e chamar a atenção. Use iluminação de contorno dramática vinda do fundo ardente, destaques laranja fortes na pele e nas roupas, e um acabamento de miniatura comercial polido. Reserve uma grande área retangular sobre a região superior direita do rosto como um bloco de espaço reservado plano em {argument name="placeholder color" default="marrom claro"}, obscurecendo a maior parte do rosto. Torne o design geral extremamente denso, brilhante, explosivo e otimizado para máxima legibilidade em tamanho reduzido.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120297_l08g9o_HGbbEZRbIAAKgqw.jpg" width="600" alt="Miniatura do YouTube - Thumbnail japonês chamativo de IA - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [まさお@AI駆動開発](https://x.com/AI_masaou)
- **Fonte:** [Twitter Post](https://x.com/AI_masaou/status/2046564209123799063#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14491)**

---

### No. 57: Miniatura do YouTube - Thumbnail de Lançamento de Anime Explosivo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma thumbnail promocional japonesa ousada em estilo anime para anúncios de lançamento, anúncios de cursos online ou visuais de marketing de negócios de IA.

#### 📝 Prompt

```
Crie uma thumbnail chamativa para YouTube em estilo promocional de anime de alto impacto, com iluminação explosiva, efeitos de faíscas densos e contraste dramático. A composição é uma cena única e unificada com um fundo preto e verde neon, explosões de glitter dourado e uma silhueta sutil de horizonte urbano na borda inferior. No lado direito, mostre um garoto anime chibi fofo da cintura para cima, com cabelo castanho-escuro a preto bagunçado, acentuado por mechas neon verde vibrantes e um pequeno detalhe vermelho próximo a um dos lados, olhos grandes verde-brilhantes, um sorriso aberto e entusiasmado, e uma pose energética apontando diretamente para o espectador com uma mão, enquanto o outro punho está levantado. Ele veste um moletom preto sob uma jaqueta verde com destaques brilhantes. No lado esquerdo, coloque 1 ampulheta verde brilhante com energia verde giratória dentro. Preencha a imagem com explosões estelares intensas, reflexos de lente, partículas douradas e linhas de velocidade para um visual de thumbnail viral. Adicione 5 elementos de texto em japonês em tipografia de exibição grande: uma faixa vermelha no canto superior esquerdo lendo {argument name="top banner text" default="4月28日スタート"} em letras amarelas grossas com bordas brancas; a manchete central principal em kanji dourado metálico massivo lendo {argument name="main headline" default="ついに解禁"} com sombra preta pesada e textura dourada brilhante; uma subtítulo grande em branco e verde no canto inferior esquerdo lendo {argument name="subheadline" default="AI副業で人生変わる"}; 1 emblema arredondado verde perto do centro inferior direito lendo {argument name="bonus badge text" default="無料10大特典"} em texto branco e amarelo em negrito; e 1 faixa preta inclinada no canto inferior direito lendo {argument name="corner banner text" default="近日公開"} com um texto menor em inglês abaixo dizendo COMING SOON. Faça com que tudo pareça urgente, comemorativo e atraente, como uma thumbnail de anúncio de lançamento de alto CTR, com contornos grossos, bordas brilhantes, texto metálico e profundidade em camadas.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883123089_a624u7_HGAkwnra8AAju1P.jpg" width="600" alt="Miniatura do YouTube - Thumbnail de Lançamento de Anime Explosivo - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fonte:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14499)**

---

### No. 58: Miniatura do YouTube - Thumbnail de YouTube chamativa para monetização no X

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma thumbnail em estilo de marketing japonês ousado para vídeos sobre como monetizar o X rapidamente, ideal para crescimento nas redes sociais ou conteúdo sobre renda online.

#### 📝 Prompt

```
Crie uma thumbnail de YouTube em estilo de marketing digital japonês de alto impacto, formato 16:9, com um fundo explosivo em preto e dourado repleto de brilhos, reflexos de lente, partículas luminosas e feixes de luz dramáticos. A composição é densa e energética, com tipografia gigante em camadas dominando a esquerda e o centro, e um personagem masculino em estilo anime à direita. No topo, coloque uma faixa curva vermelha com acabamento dourado e texto em japonês em negrito nas cores branco e amarelo, lendo {argument name="headline text" default="実績者が教える"}. Abaixo, crie a manchete principal extremamente grande, brilhante e tridimensional, com contornos pretos pesados e brilho dourado: um enorme "10" em dourado metálico, seguido por "日で" em branco negrito, depois um "X" gigante com brilho neon verde, texto empilhado "収益化" em branco e, na parte inferior, o maior texto em dourado "達成". Atrás da manchete, adicione um gráfico de barras verde brilhante com uma seta apontando para o canto superior direito para simbolizar crescimento. No lado esquerdo, inclua 3 elementos sociais e financeiros: um smartphone preto inclinado exibindo o logotipo branco do X, um balão de fala verde com um coração branco e um balão de fala verde menor com a silhueta de um usuário em branco. No canto inferior esquerdo, adicione 2 pilhas de moedas de ouro brilhantes e 1 moeda de ouro com o símbolo do iene. No lado direito, mostre 1 jovem em estilo anime, da cintura para cima, com cabelo castanho escuro bagunçado acentuado por mechas verde-vivas, pele clara e uma pose confiante com os braços cruzados, vestindo uma jaqueta preta com roupas verdes por baixo; a área do rosto está obscurecida por um bloco de desfoque retangular simples. Perto do lado inferior direito, coloque 1 selo de premiação dourado com decoração de louros e uma pequena coroa, contendo o texto em japonês "成功者続出", e anexe uma fita vermelha na parte inferior do selo com o texto "再現性あり". Ao longo da parte inferior, coloque 3 caixas de recursos retangulares verde-neon com bordas douradas e interior preto. A primeira caixa contém 1 ícone de marca de iniciante e o texto "X初心者でも 簡単収益化". A segunda caixa contém 1 ícone de relógio e o texto "1日1時間の 作業でOK". A terceira caixa contém 1 ícone de calendário com um check verde e o texto "最短10日で 収益化条件達成". Use fontes japonesas em negrito e tamanho grande, gradientes de dourado metálico, texto branco com contorno preto espesso, destaques em verde neon vívido, contraste extremo e uma estética de thumbnail polida e otimizada para taxa de cliques.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122410_3u861t_HGAkU1sbMAAR07x.jpg" width="600" alt="Miniatura do YouTube - Thumbnail de YouTube chamativa para monetização no X - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fonte:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14498)**

---

### No. 59: Miniatura do YouTube - Thumbnail de Monetização do X no Japão

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma thumbnail chamativa para YouTube em estilo anime japonês, focada em um guia para iniciantes sobre monetização no X, ideal para crescimento nas redes sociais, estratégias de renda e capas de vídeos sobre negócios online.

#### 📝 Prompt

```
Crie uma thumbnail de YouTube ousada em estilo anime-business japonês, formato 16:9, composição densa, alto contraste, efeitos de texto brilhantes, esquema de cores em verde neon e dourado, iluminação dramática, partículas de faíscas, reflexos de lente e profundidade de campo intensa. A cena mostra uma estação de trabalho desfocada e um painel de análise de redes sociais ao fundo, com gráficos de linha ascendentes e um cartão de receita visível escrito "ポストアナリティクス" e "収益 ¥248,620". No lado direito, coloque um streamer estilo anime de meio corpo com cabelo castanho escuro bagunçado e mechas em verde neon vibrante, vestindo um moletom ou jaqueta preta, sorrindo com confiança e apontando para cima com um dedo; deixe a área do rosto parcialmente obscurecida por um grande bloco retangular de preenchimento em tom oliva-amarronzado para que um texto ou retrato personalizado possa ser inserido posteriormente. No topo, adicione uma faixa de fita verde brilhante com acabamento dourado e um ícone de marca de iniciante à esquerda, contendo o texto {argument name="headline text" default="初心者向け完全ガイド"}. No centro-esquerda, crie um "10" gigante em dourado metálico com contorno preto espesso e fortes destaques em branco, seguido pelo texto em japonês em negrito branco e preto "日で". Abaixo e sobrepondo o centro, coloque uma enorme letra "X" verde neon brilhante com bordas elétricas e efeitos de faíscas. À direita do X e em destaque na frente, adicione um enorme texto 3D em japonês em branco e dourado com contorno preto pesado e sombras projetadas escrito {argument name="main claim text" default="収益化達成"}. No lado esquerdo, próximo ao texto principal, inclua 3 ícones flutuantes estilo plataforma social: um ícone quadrado preto com um logotipo X branco, um ícone de balão de fala azul com um coração branco e um ícone quadrado arredondado rosa com uma silhueta de usuário branca. No canto inferior esquerdo, coloque uma caneca de café preta com um logotipo X branco sobre uma mesa. Ao longo da borda inferior, adicione 3 caixas de informações brancas arredondadas com bordas verdes e sombras sutis, espaçadas uniformemente da esquerda para a direita, cada uma com um círculo numerado verde no topo: caixa 1 rotulada "01" com um ícone de iniciante e o texto "X初心者でも 簡単収益化"; caixa 2 rotulada "02" com um ícone de relógio e o texto "1日1時間の 作業でOK"; caixa 3 rotulada "03" com um ícone de calendário mostrando "10" e o texto "最短10日で 収益化条件達成". Torne toda a tipografia extra grande, em relevo e otimizada para a legibilidade da thumbnail, com contornos espessos, perspectiva forte e sobreposição em camadas. Humor geral: empolgante, promessa de alta renda, amigável para iniciantes, thumbnail energética para tutorial de monetização em redes sociais japonesas.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883122141_mfcjop_HGAkB1YaQAAp8wD.jpg" width="600" alt="Miniatura do YouTube - Thumbnail de Monetização do X no Japão - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fonte:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14497)**

---

### No. 60: Miniatura do YouTube - Thumbnail explosiva de monetização no X para o público japonês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma thumbnail de marketing estilo anime japonês de alta energia para redes sociais ou promoções no YouTube sobre monetização rápida no X e ofertas de bônus.

#### 📝 Prompt

```
Crie uma thumbnail chamativa para YouTube no estilo de marketing de anime de alto impacto, formato 16:9 paisagem, repleta de efeitos de energia verde neon, brilhos dourados, linhas de velocidade, reflexos de lente e sombras projetadas em preto espesso. A composição é dividida com um texto promocional em negrito dominando a esquerda e o centro, e um garoto anime chibi fofo à direita apontando diretamente para o espectador com um sorriso entusiasmado. Ele tem cabelos castanhos escuros bagunçados com mechas {argument name="accent hair color" default="neon green"}, olhos grandes verde-brilhantes, rubor suave nas bochechas e veste um moletom preto sobre uma jaqueta com acabamento verde por cima de uma camisa laranja. Use renderização cel-shaded brilhante, contornos nítidos, alto contraste e profundidade exagerada para um visual de thumbnail de rede social altamente clicável. No topo, coloque uma faixa de fita vermelha curva com acabamento dourado e um ícone de caixa de presente à esquerda; dentro da faixa, coloque o título em japonês {argument name="top banner text" default="無料10大特典プレゼント"} em letras brancas e amarelas em negrito. Na área central esquerda, coloque um texto enorme em japonês com estilo 3D dramático e gradientes metálicos: um "10" dourado gigante, um "日で" branco, um "X" verde neon massivo, seguido de "収益化" branco-prateado e "達成" dourado-alaranjado, lendo exatamente {argument name="main headline" default="10日でX収益化達成"}. Cerque este título com setas verdes apontando para cima, brilhos de estrela e efeitos de luz explosivos. Adicione 4 ícones flutuantes estilo plataforma ao redor da área do título: 1 ícone rosa estilo social com um coração branco, 1 ícone de balão de fala azul com uma silhueta de usuário branca, 1 smartphone preto inclinado exibindo o logotipo branco do X e 1 pilha de moedas de ouro com uma moeda de iene na frente. Ao longo da parte inferior, coloque 3 caixas de recursos verdes brilhantes alinhadas horizontalmente, cada uma com um ícone distinto e texto em japonês: a caixa 1 tem um ícone de marca de iniciante e o texto {argument name="feature text 1" default="X初心者でも簡単収益化"}, a caixa 2 tem um ícone de relógio e o texto "1日1時間の作業でOK", a caixa 3 tem um ícone de calendário e o texto "最短10日で収益化条件達成". No canto inferior direito, adicione um grande botão de chamada para ação vermelho brilhante e arredondado com um brilho de borda branca, o texto em japonês {argument name="button text" default="今すぐ受け取る"} em branco, um triângulo de reprodução branco no lado direito do botão e um cursor de mão clicando perto da borda inferior direita. A imagem inteira deve parecer explosiva, urgente e otimizada para uma alta taxa de cliques, usando verdes saturados, vermelhos, dourados, sombras pretas e destaques metálicos.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883121882_ip958i_HGAjjTEaoAAuDD0.jpg" width="600" alt="Miniatura do YouTube - Thumbnail explosiva de monetização no X para o público japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [みどるっち｜AIで人生アップデート](https://x.com/mido_lucci)
- **Fonte:** [Twitter Post](https://x.com/mido_lucci/status/2046546991006802057#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14496)**

---

### No. 61: Miniatura do YouTube - Next-Gen Voxel Game Screenshot

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Generates a realistic, high-fidelity first-person screenshot of a block-building game with a custom logo, environment, and UI overlay.

#### 📝 Prompt

```
A highly detailed, realistic first-person video game screenshot of a next-generation voxel-based world. At the top center, a large, bold 3D logo reads "{argument name="game title" default="MINECRAFT 2"}". The scene features a {argument name="environment" default="lush, blocky landscape with a river, a small wooden cabin, a windmill, a waterfall, and majestic mountains in the background"}. The world blends realistic lighting, volumetric clouds, and high-resolution textures with cubic, voxel geometry. In the foreground on the left, a {argument name="mob 1" default="blocky green creeper"} stands on the grass, while a {argument name="mob 2" default="blocky brown wolf"} stands on the dirt path to the right. On the far right, the player's hand holds a {argument name="held item" default="pixelated blue diamond sword"} in a first-person perspective. At the bottom of the screen is a game user interface featuring a health bar with 10 red hearts, a green experience bar with the number '16', a hunger bar with 10 brown meat icons, and a 9-slot inventory hotbar. The hotbar contains, from left to right: a selected blue tool with a green highlight box, a green tool, a knife, a wrench with the number '3', a piece of meat with '6', a lantern with '24', a dirt block with '10', a bucket, and a sponge block.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756784553_gg0ud8_HGXlhh6akAADBnS.jpg" width="600" alt="Miniatura do YouTube - Next-Gen Voxel Game Screenshot - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [wolfaidev 🐺](https://x.com/wolfaidev)
- **Fonte:** [Twitter Post](https://x.com/wolfaidev/status/2046294034411667620#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14150)**

---

### No. 62: Miniatura do YouTube - VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Generates an anime-style YouTube live stream thumbnail featuring a VTuber character, a gaming setup, and bold, customizable typography.

#### 📝 Prompt

```
An anime-style YouTube stream thumbnail featuring a cheerful female VTuber. She has long {argument name="hair color" default="pink with light blue inner highlights"} hair, blue eyes, and wears black and white cat-ear headphones with a boom mic. She wears a white collared shirt with a black and pink star ribbon and a black choker, smiling with one hand near her chin. The background is a gaming room with {argument name="room lighting" default="purple and blue neon"} lighting, showing a desk equipped with 1 white keyboard, 1 mug, 1 glowing cat figure, 1 game controller, and 1 streaming microphone. The left side features large, bold, pop-art Japanese typography: a bright pink top word "{argument name="main text line 1" default="雑談"}" and a bright blue bottom word "{argument name="main text line 2" default="配信"}". Below is a pink banner reading "{argument name="subtitle text" default="今夜もゆるっとトーク!"}". A red "LIVE" badge sits in the top left. Floating speech bubbles, stars, and hearts decorate the composition.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831336_0k5bc1_HGW5wnlbYAABVsa.jpg" width="600" alt="Miniatura do YouTube - VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [結パパ](https://x.com/Yuupapa_free)
- **Fonte:** [Twitter Post](https://x.com/Yuupapa_free/status/2046246868146106491#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14230)**

---

### No. 63: Miniatura do YouTube - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838159_taut7g_HGV6SxSbAAEuvNF.jpg" width="600" alt="Miniatura do YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fonte:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-3)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14242)**

---

### No. 64: Miniatura do YouTube - Pastel Pink VTuber Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756836369_z2uhxg_HGV6R8CbEAAxsKB.jpg" width="600" alt="Miniatura do YouTube - Pastel Pink VTuber Stream Thumbnail - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fonte:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14238)**

---

### No. 65: Miniatura do YouTube - Anime VTuber Livestream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756831940_si87qi_HGV6Q_rbkAA_1c4.jpg" width="600" alt="Miniatura do YouTube - Anime VTuber Livestream Thumbnail - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fonte:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-1)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14231)**

---

### No. 66: Miniatura do YouTube - VTuber Chat Stream Thumbnail

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756829722_eza1di_HGV6P7La8AAk06d.jpg" width="600" alt="Miniatura do YouTube - VTuber Chat Stream Thumbnail - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [絵愛さやか🐸AIArtist](https://x.com/sayaka_aiart)
- **Fonte:** [Twitter Post](https://x.com/sayaka_aiart/status/2046176145075515600#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14227)**

---

### No. 67: Miniatura do YouTube - Gerador de miniaturas para webinars em japonês

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt para criar miniaturas profissionais de webinars em japonês no formato 16:9, com tipografia clara e texto de destaque.

#### 📝 Prompt

```
Crie um(a) {argument name="thumbnail type" default="miniatura de webinar"} de alta qualidade em japonês. {argument name="aspect ratio" default="widescreen 16:9"}. Há bastante texto, mas a mensagem principal se destaca claramente.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699411043_ito7ae_HGK_HK2bIAAGHrR.jpg" width="600" alt="Miniatura do YouTube - Gerador de miniaturas para webinars em japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [KAWAI](https://x.com/kawai_design)
- **Fonte:** [Twitter Post](https://x.com/kawai_design/status/2045408105136074800)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=13978)**

---

### No. 68: Miniatura do YouTube - Miniatura para Stream de Estreia de VTuber

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma agenda de stream mágica e rica em tipografia ou uma miniatura de estreia para um VTuber.

#### 📝 Prompt

```
{
  "type": "miniatura para stream de estreia de VTuber",
  "character": {
    "appearance": "garota de anime, cabelos longos roxos escuros, olhos roxos, blusa branca com babados, gravata borboleta roxa escura, laço de cabelo grande",
    "pose": "dedo nos lábios, expressão fofa",
    "props": "microfone condensador com filtro pop e fita roxa à direita"
  },
  "background": "noite estrelada mágica, brilhos, borboletas brilhantes, paleta de cores roxa e branca",
  "layout": {
    "typography": [
      {
        "position": "superior esquerdo",
        "style": "texto grande em negrito com inglês cursivo acima",
        "text": "{argument name=\"main title\" default=\"初配信\"}",
        "subtext_1": "Primeira Stream",
        "subtext_2": "Prazer em conhecê-los! Eu sou Shisaki Lily!"
      },
      {
        "position": "meio esquerdo",
        "style": "caixa decorativa",
        "text": "{argument name=\"character description\" default=\"お嬢様学校に通う清楚系VTuberですわ♪\"}"
      },
      {
        "position": "inferior esquerdo",
        "style": "estilo de logotipo",
        "text": "{argument name=\"character name\" default=\"紫咲リリー\"}",
        "subtext": "Shisaki Lily"
      },
      {
        "position": "superior direito",
        "style": "texto vertical",
        "text": "{argument name=\"catchphrase\" default=\"皆さまの心に、優雅なひとときをお届けしますわ♪\"}"
      },
      {
        "position": "inferior direito",
        "style": "forma de pílula decorativa",
        "text": "{argument name=\"stream date and time\" default=\"4.21 SUN 21:00~\"}",
        "subtext": "✦ INÍCIO ✦"
      }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697129252_angrld_HGJCzL5a0AAYPr6.jpg" width="600" alt="Miniatura do YouTube - Miniatura para Stream de Estreia de VTuber - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [WTR](https://x.com/wtry1102)
- **Fonte:** [Twitter Post](https://x.com/wtry1102/status/2045270824542953673#reversed-1)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13943)**

---

### No. 69: Miniatura do YouTube - Miniatura de Infoproduto Dourado e Preto

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera um banner promocional chamativo e rico em texto ou uma miniatura para YouTube, apresentando um sujeito confiante e várias chamadas de texto estruturadas.

#### 📝 Prompt

```
{
  "type": "banner promocional / miniatura de YouTube",
  "style": "alto contraste, chamativo, profissional, paleta {argument name=\"theme color\" default=\"dourado e preto\"}, raios de luz brilhantes, partículas cintilantes",
  "subject": {
    "description": "{argument name=\"subject description\" default=\"jovem asiático confiante vestindo terno escuro com os braços cruzados\"}",
    "pose": "olhando para cima à direita",
    "props": "laptop aberto e brilhante à sua frente"
  },
  "layout": {
    "background": "escuro com explosões de luz dourada radiante",
    "text_sections": {
      "top_left_badge": "[Edição Definitiva]",
      "top_header": "{argument name=\"top text\" default=\"Comece hoje mesmo, mesmo sem conhecimento prévio! Domine o poder de ganhar dinheiro com IA no menor tempo possível!\"}",
      "main_title": {
        "text": "{argument name=\"main title\" default=\"Guia Completo de Renda Extra com IA\"}",
        "style": "tipografia 3D grande, em negrito, dourada e branca"
      },
      "subtitle_box": "{argument name=\"subtitle\" default=\"100 mil por mês para iniciantes\"}",
      "top_right_badge": {
        "style": "coroa de louros dourada",
        "text": "Edição 2026 mais recente"
      },
      "middle_right_tags": {
        "count": 3,
        "style": "caixas empilhadas com bordas douradas",
        "labels": ["Monetização rápida", "Com exemplos práticos", "Fácil para qualquer um"]
      },
      "middle_right_ribbon": {
        "style": "faixa vermelha",
        "text": "Passo a passo detalhado"
      },
      "bottom_left_tags": {
        "count": 6,
        "style": "grade 2x3 de caixas com bordas douradas",
        "labels": ["Ferramentas recomendadas", "Entenda o fluxo de receita", "Como começar sem erros", "Minimize o tempo de trabalho", "Inclui modelos", "Método fácil de replicar"]
      },
      "bottom_footer": "Ganhe dinheiro sem dúvidas! O manual da renda extra com IA",
      "bottom_right_badge": {
        "style": "coroa de louros dourada",
        "text": "Inclui modelos"
      }
    }
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697106260_dl2b9r_HGGzzjmasAAub4r.jpg" width="600" alt="Miniatura do YouTube - Miniatura de Infoproduto Dourado e Preto - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ナーガ@X女帝](https://x.com/naga_zyashin)
- **Fonte:** [Twitter Post](https://x.com/naga_zyashin/status/2045113428952678447#reversed-2)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13903)**

---

### No. 70: Banda desenhada / Storyboard - Mangá de Casal em 4 Painéis com Estilo Acolhedor

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma história em quadrinhos japonesa suave e romântica de quatro painéis celebrando um casal, ideal para publicações em redes sociais, ilustrações comemorativas ou arte de mangá com temática de relacionamento.

#### 📝 Prompt

```
{"type":"ilustração de mangá romântico de 4 painéis","style":"arte de linha estilo anime limpa e feita à mão com uma paleta monocromática quente de bege e marrom claro, fundo creme suave, sombreamento simples, atmosfera aconchegante e gentil, estética para redes sociais","format":"layout de quadrinhos quadrado 2x2 com bordas finas e marrons nos painéis","headline":{"text":"{argument name=\"headline text\" default=\"Dia do Casal\"}","position":"topo central","decorations":{"count":2,"items":["pequeno coração à esquerda","pequeno coração à direita"]}},"panels":[{"panel":1,"count":2,"scene":"retrato de pé de um jovem casal","composition":"o homem está atrás da mulher com uma mão no ombro dela, ambos parecendo calmos e afetuosos","characters":[{"role":"homem","appearance":"cabelo castanho claro bagunçado, óculos, moletom creme, alto e magro"},{"role":"mulher","appearance":"cabelo castanho claro em um coque baixo solto com mechas emoldurando o rosto, camisa branca de manga comprida, colete de suéter marrom quente, alça da bolsa visível"}],"text":["Hoje é","o Dia do Casal!"],"decorations":{"count":3,"items":["pequeno coração","pequeno coração","pequeno coração"]}},{"panel":2,"count":2,"scene":"o casal sentado junto dentro de casa segurando canecas e sorrindo um para o outro","characters":[{"role":"homem","appearance":"mesmos óculos e moletom, segurando uma caneca verde suave"},{"role":"mulher","appearance":"mesmo penteado e roupa, segurando uma caneca clara"}],"speech_bubble":{"speaker":"homem","text":"Obrigado por tudo. Estar com você é a minha maior felicidade."},"decorations":{"count":4,"items":["pequeno brilho","pequeno brilho","pequeno aglomerado de pontos","pequeno aglomerado de pontos"]}},{"panel":3,"count":2,"scene":"o casal cozinhando junto na cozinha, ambos mexendo uma panela no fogão","background":"prateleiras simples e planta em vaso com detalhes suaves de esboço","characters":[{"role":"homem","appearance":"mesmos óculos e moletom"},{"role":"mulher","appearance":"mesmo penteado de coque e roupa em camadas"}],"speech_bubble":{"speaker":"homem","text":"De agora em diante, vamos rir juntos, nos apoiar e ver muitas paisagens lado a lado."}},{"panel":4,"count":2,"scene":"abraço afetuoso próximo, o homem beija a testa da mulher enquanto segura o ombro dela","characters":[{"role":"homem","appearance":"mesmos óculos e moletom"},{"role":"mulher","appearance":"mesmo cabelo e roupa, inclinando-se para ele"}],"speech_bubble":{"speaker":"homem","text":"Eu te amo. Vamos continuar assim, contando um com o outro!"},"decorations":{"count":3,"items":["pequeno coração","pequeno coração","pequeno coração"]}}],"footer":{"text":"{argument name=\"footer text\" default=\"Obrigado por estar sempre ao meu lado.\"}","position":"base central","decorations":{"count":1,"items":["pequeno coração"]}},"character_design":{"count":2,"items":[{"role":"marido","hair color":"{argument name=\"hair color\" default=\"castanho claro\"}","expression":"gentil, terno, afetuoso"},{"role":"esposa","hair color":"{argument name=\"hair color\" default=\"castanho claro\"}","expression":"sorriso suave, amorosa, levemente tímida"}]},"rendering_notes":"mantenha todo o texto escrito à mão em japonês, use bastante espaço em branco, preserve um clima doce e comemorativo para uma postagem de apreciação do casal, faça o traço ser levemente solto e parecido com um esboço em vez de tinta polida"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883120482_9fygfa_HGgqTCCaIAA4jpt.jpg" width="600" alt="Banda desenhada / Storyboard - Mangá de Casal em 4 Painéis com Estilo Acolhedor - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [むく | AIアート× Threads](https://x.com/muku_sns)
- **Fonte:** [Twitter Post](https://x.com/muku_sns/status/2046932542998364645#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14492)**

---

### No. 71: Banda desenhada / Storyboard - Página de Demonstração de Mangá com IA em Japonês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma página de mangá estilo anime de quatro quadros, polida, mostrando personagens catgirls reagindo a diálogos em japonês renderizados de forma impressionante, ideal para exibir a qualidade de texto em quadrinhos por IA.

#### 📝 Prompt

```
{
  "type": "página de mangá estilo anime de quatro quadros",
  "style": "ilustração de anime limpa e polida, iluminação interna quente, balões de fala em japonês verticais altamente legíveis, sombreamento suave, enquadramento de quadrinhos expressivo, fundo detalhado de sala de estar aconchegante, interior em tons de marrom claro e bege, piso de madeira, sofá, mesa de centro, canecas, pequena planta, arte de parede emoldurada",
  "format": {
    "page_orientation": "retrato",
    "panel_count": 4,
    "reading_flow": "superior esquerdo, superior direito, médio largo, inferior largo",
    "borders": "bordas de painel de mangá pretas e grossas"
  },
  "characters": [
    {
      "id": "blue cat girl",
      "appearance": "pequena catgirl chibi com cabelo curto estilo chanel {argument name="hair color" default="azul"}, ahoge, orelhas de gato com pelo interno branco, cauda fofa com ponta branca, olhos grandes âmbar-azulados, boca pequena com presas",
      "outfit": "suéter laranja sobre uma camisa social branca com acabamento azul, saia marrom com cinto de fita, presilha de cabelo amarela em formato de X"
    },
    {
      "id": "golden cat girl",
      "appearance": "catgirl enérgica com longos cabelos loiro-dourados ondulados, orelhas de gato, cauda fofa, expressão alegre e brilhante",
      "outfit": "suéter de tricô amarelo mostarda, saia xadrez marrom escuro"
    },
    {
      "id": "white-haired woman",
      "appearance": "mulher bonita com longos cabelos brancos, orelhas de gato brancas, pele bronzeada, olhos dourados, sorriso calmo e confiante",
      "outfit": "jaqueta branca sobre uma blusa preta, colares e brincos dourados em camadas"
    },
    {
      "id": "maid woman",
      "appearance": "mulher adulta com longos cabelos loiros claros e orelhas de gato",
      "outfit": "vestido de empregada preto e branco com touca branca com babados e um laço de fita vermelha"
    }
  ],
  "layout": {
    "sections": [
      {
        "title": "quadro 1",
        "position": "superior esquerdo",
        "count": 1,
        "labels": ["どうせ日本語微妙なんでしょ？文字がダメなら認めないよ"],
        "scene": "a catgirl azul sentada em um sofá em uma sala de estar aconchegante, com um dedo no queixo, parecendo cética e curiosa, um pequeno ponto de interrogação flutuando acima de sua cabeça"
      },
      {
        "title": "quadro 2",
        "position": "superior direito",
        "count": 1,
        "labels": ["ねぇねぇ！GPT Image2 すごいよ！"],
        "scene": "a catgirl dourada entra dramaticamente por uma porta com linhas de velocidade irradiando atrás dela, braços abertos, cheia de entusiasmo"
      },
      {
        "title": "quadro 3",
        "position": "médio largo",
        "count": 3,
        "labels": ["うわっ びっくりした！めちゃくちゃキレイじゃん！", "ねぇねぇ！GPT Image2 すごいよ！ 微妙なんでしょ？ 文字がダメなら認めないよ", "ほら見て！わたしたちのセリフ！"],
        "scene": "a catgirl azul reage em choque com as duas mãos perto do rosto, a catgirl dourada fica ao lado dela apontando com orgulho, e um grande balão de fala central exibe o exemplo de diálogo em japonês que elas estão discutindo"
      },
      {
        "title": "quadro 4",
        "position": "inferior largo",
        "count": 3,
        "labels": ["進化が早すぎてもう驚かないよね〜", "絵も可愛く描けてるし文字の白抜きも完璧よね", ""],
        "scene": "em primeiro plano, a mulher empregada cobre a boca impressionada enquanto a mulher de cabelos brancos comenta pensativa com a mão perto do queixo; ao fundo, a catgirl azul e a catgirl dourada pulam felizes juntas em celebração em frente ao sofá"
      }
    ]
  },
  "text_handling": {
    "language": "Japonês",
    "balloon_direction": "layout de texto vertical",
    "emphasis": "torne a tipografia japonesa nítida, natural e integrada de forma limpa aos balões de fala do mangá, incluindo texto com contorno branco (knockout) onde necessário"
  },
  "tone": "brincalhão, celebratório, impressionado com a renderização de texto em japonês de alta qualidade em mangás gerados por IA",
  "quality": "alto detalhamento, designs de personagens coesos, quadrinho promocional fofo e legível"
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883112561_p4smsc_HGgOKcHb0AAe6uY.jpg" width="600" alt="Banda desenhada / Storyboard - Página de Demonstração de Mangá com IA em Japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [芽乃葉-めいのは-](https://x.com/maynoha_maru)
- **Fonte:** [Twitter Post](https://x.com/maynoha_maru/status/2046902204670611919#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14471)**

---

### No. 72: Banda desenhada / Storyboard - Folha de 4 Painéis de Espadachim Anime Elegante

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma ilustração de personagem de anime em quatro painéis de alto detalhe de uma nobre espadachim de cabelos brancos, ideal para arte principal de fantasia, vitrines de personagens ou posts premium em redes sociais.

#### 📝 Prompt

```
Uma folha de ilustração de fantasia anime refinada em uma grade 2x2 mostrando a mesma espadachim elegante em 4 painéis. A personagem é uma jovem com cabelos longos platinados presos em um rabo de cavalo alto com grandes laços de fita azul-marinho profundo, cachos soltos e mechas fluidas, pele clara e traços delicados e refinados com olhos vermelho-rosados luminosos. Ela veste um traje aristocrático gótico branco e azul-marinho ornamentado: uma blusa branca de gola alta com babados, acabamento em renda e bordados dourados, um grande laço azul-marinho no peito com um broche de joia vermelha, mangas bufantes com punhos de fita, um espartilho azul-marinho escuro com detalhes dourados e uma saia volumosa azul-marinho decorada com padrões florais dourados, babados em camadas e brilho acetinado. Ela carrega uma katana embainhada com cabo escuro e detalhes dourados. O Painel 1 é um retrato em close-up do busto para cima, virado levemente de lado, com o cabelo brilhando sob uma luz de contorno dramática contra um fundo noturno escuro e cintilante. O Painel 2 é uma cena de ação dinâmica da parte superior do corpo, com a personagem sacando ou apresentando a espada horizontalmente em direção ao espectador, cabelo esvoaçante, bokeh cinematográfico de cidade noturna e pétalas brilhantes ao seu redor. O Painel 3 é um retrato de corpo inteiro, em pé graciosamente em um salão reflexivo e luminoso emoldurado por estruturas altas e brilhantes, mostrando toda a silhueta do vestido, sapatos de salto com laços e a espada ao seu lado. O Painel 4 é uma visão de três quartos de costas perto de um oceano cintilante ao pôr do sol ou amanhecer, com a personagem olhando por cima do ombro, céu em tons pastéis quentes e água brilhante ao fundo, pétalas de cerejeira flutuando na brisa. Use renderização de anime ultra detalhada, qualidade de capa de light novel premium, texturas de tecido intrincadas, destaques brilhantes, ornamentação dourada, soft bloom, iluminação de fundo dramática, pétalas flutuantes, partículas cintilantes, atmosfera romântica elegante e harmonia de cores em azul-marinho, branco, dourado e rosa blush.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883089448_29d4ej_HGf2vKmbQAAECCZ.jpg" width="600" alt="Banda desenhada / Storyboard - Folha de 4 Painéis de Espadachim Anime Elegante - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ユキノ❄ AIart](https://x.com/yukinono_ai)
- **Fonte:** [Twitter Post](https://x.com/yukinono_ai/status/2046879433462854011#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14413)**

---

### No. 73: Banda desenhada / Storyboard - Confronto de Countryballs no Estreito de Ormuz

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma ilustração humorística de meme geopolítico mostrando as countryballs dos EUA e do Irã se enfrentando no estreito Estreito de Ormuz, ideal para sátira editorial ou comentários em redes sociais.

#### 📝 Prompt

```
Uma ilustração detalhada e satírica de meme countryball do {argument name="waterway name" default="Estreito de Ormuz"} como uma passagem marítima muito estreita entre dois penhascos rochosos íngremes, pintada em um estilo de desenho digital polido com sombreamento dramático e pedra texturizada. No centro do primeiro plano, exatamente 2 countryballs bloqueiam uma à outra no canal apertado, de modo que apenas uma possa passar. À esquerda, uma countryball dos EUA com olhos semicerrados de raiva, pintada com a bandeira americana, usando um boné de beisebol azul-marinho com a inscrição "USA" em letras brancas grandes. À direita, uma countryball do Irã com olhos semicerrados de raiva, pintada com a bandeira e o emblema iranianos, usando uma faixa verde e branca amarrada na lateral; a faixa contém texto em coreano que diz "저항은 우리의 권리". Acima de cada bola, há exatamente 1 balão de fala branco com contorno preto espesso, totalizando 2 balões de fala, e ambos dizem {argument name="speech text" default="길!"} em letras coreanas grandes e em negrito, como se nenhum dos lados fosse ceder. Mostre as duas bolas frente a frente, nariz com nariz, em um impasse no gargalo. No penhasco esquerdo, inclua exatamente 1 placa de madeira lendo em coreano e inglês: "호르무즈 해협" e "Strait of Hormuz". No penhasco direito, inclua exatamente 1 placa de aviso com texto em persa no topo e um triângulo de advertência vermelho abaixo, indicando que apenas uma pessoa pode passar. No canto inferior esquerdo, coloque exatamente 1 barril de óleo preto rotulado como "OIL" com óleo escuro derramado formando uma poça ao redor. No canto inferior direito, coloque exatamente 1 mina naval preta com escrita em persa, presa a uma corrente. Ao fundo, além da passagem estreita, mostre o mar aberto com exatamente 3 navios distantes, incluindo pelo menos 1 petroleiro maior e uma fumaça escura e tênue subindo para o céu. Use um tom de meme geopolítico tenso, porém bem-humorado, composição centralizada, visão ao nível dos olhos, luz do dia suave, cores realistas levemente suaves, contornos nítidos e alta legibilidade para todo o texto.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883198880_l9s0k9_HGfMY0Aa0AA_bmW.jpg" width="600" alt="Banda desenhada / Storyboard - Confronto de Countryballs no Estreito de Ormuz - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Geonhee Jeong](https://x.com/Gh_Peter_J)
- **Fonte:** [Twitter Post](https://x.com/Gh_Peter_J/status/2046837715979866115#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14683)**

---

### No. 74: Banda desenhada / Storyboard - Pose de Vitória de Feiticeiro Vendado

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster de ação de anime vertical dramático de um feiticeiro de cabelos brancos vendado, com energia azul explosiva e um balão de fala de mangá marcante, ideal para arte de personagem estilizada ou visuais inspirados em fandom.

#### 📝 Prompt

```
Uma ilustração de anime shonen mangá de alto impacto de um poderoso feiticeiro de cabelos brancos em uma pose dramática de corpo inteiro em ângulo contra-plongée, rindo com a cabeça jogada para trás e a boca bem aberta, vestindo um uniforme preto elegante de gola alta e uma venda preta sobre os olhos. Sua mão esquerda está estendida em direção ao espectador fazendo um sinal de paz com dois dedos, com um forte escorço que torna a mão grande em primeiro plano, enquanto seu braço direito pende mais baixo ao lado do corpo. Cerque-o com energia sobrenatural explosiva {argument name="energy color" default="azul elétrico"}, rastros de aura semelhantes a pinceladas violentas, detritos voadores, faíscas e faixas curvas giratórias cortando o quadro. O fundo deve ser uma explosão de energia escura, abstrata e caótica com fragmentos azuis brilhantes e linhas de movimento, criando uma sensação de poder avassalador. Use renderização de anime cel-shaded ousada com destaques pictóricos, traços nítidos, contraste intenso e dobras de tecido brilhantes no traje preto. No lado direito, adicione 1 grande balão de fala de mangá branco e irregular com contorno preto grosso contendo o texto {argument name="speech bubble text" default="LUDDITES ALWAYS LOSE!"} em letras maiúsculas pretas grandes e desgastadas. Composição vertical, enquadramento de pôster de ação dinâmica, atitude triunfante e confiante, estética de anime de fantasia sombria moderna.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179057_tuj66s_HGfDlEhacAA5t4g.jpg" width="600" alt="Banda desenhada / Storyboard - Pose de Vitória de Feiticeiro Vendado - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ρ:ɡeσn](https://x.com/pigeon__s)
- **Fonte:** [Twitter Post](https://x.com/pigeon__s/status/2046819602869768507#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14637)**

---

### No. 75: Banda desenhada / Storyboard - Página de mangá de comédia: Casa de banho lunar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma página de mangá estilo anime retrô-futurista que retrata uma casa de banho (sento) peculiar na lua, ideal para gerar cenas divertidas de mangá com IA, com múltiplos quadros focados nos personagens.

#### 📝 Prompt

```
Uma página de mangá japonês colorida ambientada em uma peculiar casa de banho pública na lua, desenhada em um estilo anime retrô-futurista polido com iluminação quente, bordas de quadros espessas e limpas, efeitos sonoros expressivos e narrativa ambiental altamente detalhada. A cena é um onsen lunar chamado "月面銭湯 つきのゆ" com uma grande placa de entrada iluminada, cortina noren azul com o caractere branco "ゆ", canos expostos, medidores, arquitetura arredondada e uma janela circular gigante mostrando a superfície lunar e a Terra no espaço. Inclua exatamente 8 quadros de quadrinhos organizados em um layout de página dinâmico. Quadro 1: plano de estabelecimento externo da casa de banho na lua, com a placa "月面銭湯 つきのゆ", uma placa menor lendo "重力 1/6", uma máquina de venda automática de leite vermelha rotulada como "牛乳", uma estátua de tanuki, terreno lunar ao fundo e um banner vertical promovendo o banho. Quadro 2: uma jovem mecânica que trabalha na casa de banho com {argument name="character design" default="rabo de cavalo castanho preso com uma bandana de bolinhas vermelhas, macacão de trabalho verde, cinto de ferramentas, expressão enérgica"} ajusta uma máquina ou controle de caldeira, vista de costas ou de lado, com balões de fala sobre a preparação do banho de hoje e a condição da caldeira. Quadro 3: um cliente alienígena fofo com {argument name="alien appearance" default="corpo redondo verde-menta, manchas roxas, olhos sonolentos, bochechas rosadas, boca pequena, toalha branca com uma estrela roxa na cabeça"} relaxa na água fumegante do banho, meio submerso, com um patinho de borracha flutuando por perto e uma placa de madeira lendo "ぬるめ じっくり リラックス". Quadro 4: um pequeno robô de limpeza com {argument name="robot design" default="corpo prateado, detalhes em azul, rosto digital preto com olhos azuis brilhantes, luz de antena vermelha, braços e pernas mecânicos finos"} esfrega alegremente o chão com uma vassoura e um balde ao lado de uma placa suspensa que diz "清掃中". Quadro 5: o mesmo robô escorrega ou espirra dramaticamente no banho, com uma enorme explosão de água, muitas bolhas, o grande efeito sonoro "ぽわぁ〜ん!!" e a trabalhadora reagindo com surpresa ao lado. Quadro 6: a trabalhadora senta-se ao lado do banho sorrindo, segurando uma garrafa rotulada como "月面牛乳". Quadro 7: o alienígena no banho faz um sinal de positivo enquanto segura uma garrafa rotulada como "月面フルーツオーレ", parecendo extremamente satisfeito, com o patinho de borracha ainda presente. Quadro 8: o robô alegre posa ao lado do banho com ferramentas de limpeza e um balde, perto de uma cortina de banho marcada com "ゆ" e uma bacia rosa rotulada como "つきのゆ", dizendo que o banho é o melhor. Mantenha um tom aconchegante e cômico, detalhes de sento estilo Showa retrô misturados com tecnologia espacial, superfícies de banho com azulejos brilhantes, vapor, bolhas e atuações de personagens fofas por toda parte. O quadrinho deve parecer um mangá de comédia charmoso sobre o cotidiano de trabalhar em uma casa de banho lunar.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883204081_v9n5zm_HGew6LTaIAA-lrF.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá de comédia: Casa de banho lunar - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [猫おじ](https://x.com/mar_vn_nv_cie)
- **Fonte:** [Twitter Post](https://x.com/mar_vn_nv_cie/status/2046799393307996376#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14697)**

---

### No. 76: Banda desenhada / Storyboard - Folha de Referência de Design de Personagem

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma folha de design abrangente para um personagem específico, incluindo informações principais e referências visuais.

#### 📝 Prompt

```
Crie uma folha de design de personagem para {argument name="character" default="Hermes Agent"}, com informações principais
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883049658_pw6yph_HGetCnrbIAAq6T0.jpg" width="600" alt="Banda desenhada / Storyboard - Folha de Referência de Design de Personagem - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Neo](https://x.com/NeoAIForecast)
- **Fonte:** [Twitter Post](https://x.com/NeoAIForecast/status/2046795552650936695)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14324)**

---

### No. 77: Banda desenhada / Storyboard - Página de História em Quadrinhos Indie

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Cria um layout de história em quadrinhos em um estilo indie moderno, feito sob medida para histórias infantis.

#### 📝 Prompt

```
Uma página de história em quadrinhos no estilo de {argument name="comic style" default="modern indie comic"} sobre: {argument name="story topic" default="uma história para crianças de 6 anos"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044035_vhpqs5_HGemAz4XsAAks7h.jpg" width="600" alt="Banda desenhada / Storyboard - Página de História em Quadrinhos Indie - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [宝玉](https://x.com/dotey)
- **Fonte:** [Twitter Post](https://x.com/dotey/status/2046787206585430189)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14310)**

---

### No. 78: Banda desenhada / Storyboard - Página de mangá shonen colorida

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt narrativo detalhado para gerar uma página de mangá com aparência física, incluindo detalhes específicos de personagens e marcas.

#### 📝 Prompt

```
Crie uma página de exemplo de um {argument name="manga type" default="mangá de aventura shonen japonês colorido"}. A página deve retratar vividamente nosso personagem principal encontrando um {argument name="item" default="pena mágica"}. O nome da pena é {argument name="item name" default="Quill of GPT Image"}. Torne a cena dramática. A pena mágica possui um grande poder selado em seu interior.

Instruções adicionais: Proporção: Retrato 1440x2560. A caneta deve conter o logotipo da OpenAI. O idioma em todo o mangá deve ser japonês. Pense cuidadosamente antes para garantir uma boa história com uma boa divisão de quadros de mangá. A página deve parecer uma foto de uma página física, não uma página digital.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883044310_q2uvbd_HGehCXkXYAAWo-E.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá shonen colorida - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [宝玉](https://x.com/dotey)
- **Fonte:** [Twitter Post](https://x.com/dotey/status/2046781861502779523)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14311)**

---

### No. 79: Banda desenhada / Storyboard - Página de mangá de comédia romântica de quatro quadros

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera uma página de mangá monocromática de quatro quadros com diálogos em japonês, ideal para criar cenas dramáticas de debate em comédias românticas com atuações expressivas dos personagens.

#### 📝 Prompt

```
Crie uma página de mangá em preto e branco com 4 quadros horizontais empilhados, sarjetas pretas limpas, sombreamento com retículas (screentone), linhas de velocidade dramáticas e traços polidos no estilo seinen. A página apresenta dois personagens de anime jovens com roupas casuais modernas e cabelos curtos e escuros, com a área do rosto de ambos os personagens obscurecida por um bloco de censura quadrado com desfoque suave. Quadro 1: uma pessoa jovem e esguia com cabelo curto e escuro bagunçado e uma camisa de colarinho cerra um punho perto do peito, corpo inclinado para a esquerda, cercado por um efeito de aura de fogo intenso ao fundo, parecendo emocional e defensivo. No lado direito, coloque um grande balão de fala vertical irregular contendo este texto em japonês: 「何十時間も魂を削って描いた一枚と、プロンプト打ち込んで数秒で出した画像が同じ価値なわけないでしょ！ふざけないで！」. Quadro 2: uma segunda pessoa jovem, um pouco mais alta, com cabelo curto e escuro, uma jaqueta escura com zíper sobre uma camisa clara, levanta um dedo indicador calmamente como se estivesse explicando um ponto. Adicione uma caixa de fala retangular arredondada à direita com este texto em japonês: 「投下した労働時間で価値が決まるという典型的な“労働価値説の誤謬”だ。市場における価値は、出力された結果を受け手がどう評価するかで決まる」. Quadro 3: o personagem mais alto acaricia suavemente a cabeça do personagem mais baixo; inclua um pequeno efeito sonoro de carinho perto da mão lendo 「ポン」. O personagem mais baixo olha para cima, surpreso. No lado direito, adicione um grande balão de fala vertical oval com este texto em japonês: 「でも俺の市場価値基準はすごくシンプルだよ。君が俺のために照れてくれるこの数秒間に、何十時間分の価値も感じてるから」. Quadro 4: close-up do personagem mais baixo corando intensamente com olhos em espiral, gotas de suor, expressão trêmula, boca aberta e hachuras densas nas bochechas, sobrecarregado de vergonha. Preencha o fundo com linhas de velocidade radiantes dramáticas. Adicione um grande balão de fala vertical irregular à direita com este texto em japonês: 「だ、誰がアンタのために照れるか…っ！自意識過剰よ！」. Adicione dois efeitos sonoros: um pequeno 「プル…」 perto do ombro e um 「カァァァ」 maior, trêmulo e escrito à mão ao longo do lado inferior esquerdo. Mantenha toda a página monocromática, altamente expressiva, com tom de mangá de comédia romântica, com forte contraste emocional entre discussão acalorada, explicação fria, afeto provocativo e um desfecho embaraçado.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883111356_ttmvlw_HGd1P-6aYAApq5n.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá de comédia romântica de quatro quadros - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Fonte:** [Twitter Post](https://x.com/jaguring1/status/2046735877628670430#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14468)**

---

### No. 80: Banda desenhada / Storyboard - Folha de Referência de Personagem de Velvedia

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt curto para gerar uma folha de referência de personagem para uma personagem estilo mecha chamada Velvedia.

#### 📝 Prompt

```
{argument name="character name" default="Velvedia"} folha de referência
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071037_qet7yn_HGbpLzMaIAAO36j.jpg" width="600" alt="Banda desenhada / Storyboard - Folha de Referência de Personagem de Velvedia - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071058_lr0y9r_HGbpLzIb0AABqh6.jpg" width="600" alt="Banda desenhada / Storyboard - Folha de Referência de Personagem de Velvedia - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [ジャスミーナ | AI Anime & Illustrations✨](https://x.com/JasminaAi)
- **Fonte:** [Twitter Post](https://x.com/JasminaAi/status/2046730197802663962)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=14368)**

---

### No. 81: Banda desenhada / Storyboard - Promoção de Mangá de 8 Painéis para GPT-Image-2

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma página de quadrinhos em estilo mangá preto e branco em português, com oito painéis, para anunciar e explicar o GPT-Image-2 em um formato promocional ideal para redes sociais.

#### 📝 Prompt

```
{"type":"página de quadrinhos promocional estilo mangá de 8 painéis","theme":"anúncio de lançamento do GPT-Image-2","language":"Português","style":{"rendering":"mangá em preto e branco com sombreamento de retícula, linhas de velocidade, brilhos intensos, contornos em tinta preta, acabamento de quadrinhos digital limpo","mood":"empolgante, informativo, otimista, focado em tecnologia","page_format":"página única dividida em 8 painéis retangulares em uma grade de 2 colunas por 4 linhas com espaçamentos finos"},"characters":[{"id":"garota apresentadora","role":"apresentadora principal","appearance":"garota de anime fofa com cabelos longos e escuros, olhos grandes e expressivos, vestindo um moletom escuro com o logotipo do nó da OpenAI no peito","count":1},{"id":"robô mascote","role":"mascote assistente amigável","appearance":"pequeno robô redondo com tela preta no rosto, olhos brilhantes, corpo branco simples, braços minúsculos, expressão alegre","count":1},{"id":"grupo de criadores","role":"exemplos de público","appearance":"4 jovens criadores diferentes: um designer, um desenvolvedor segurando um tablet, um fotógrafo com câmera, uma pessoa com laptop/moletom","count":4}],"layout":{"sections":[{"title":"CHEGOU! GPT-IMAGE-2","position":"superior-esquerdo","count":1,"description":"painel dramático de introdução com a garota de anime estendendo uma mão em direção ao espectador, linhas de velocidade radiantes atrás dela","text":["CHEGOU!","GPT-IMAGE-2","A NOVA GERAÇÃO DE IMAGENS POR IA DA OPENAI!","MAIS CRIATIVIDADE, MAIS PRECISÃO, MAIS POSSIBILIDADES!"]},{"title":"O QUE É O GPT-IMAGE-2?","position":"superior-direito","count":1,"description":"garota em pose de meio corpo apontando para cima ao lado de um ícone de imagem brilhante em um fundo tecnológico estrelado","text":["O QUE É O GPT-IMAGE-2?","É nosso novo modelo de geração de imagens, mais inteligente, mais fiel ao que você imagina e com qualidade surpreendente!"]},{"title":"MAIS REALISMO. MAIS DETALHES.","position":"meio-esquerdo linha 2","count":1,"description":"painel de comparação mostrando 2 imagens de paisagens lado a lado, ambas cenas de lago nas montanhas, a esquerda rotulada como modelo antigo e a direita como modelo novo com realismo mais rico","subsections":[{"label":"ANTES (DALL·E 3)","count":1},{"label":"AGORA (GPT-IMAGE-2)","count":1}],"text":["MAIS REALISMO. MAIS DETALHES.","ANTES (DALL·E 3)","AGORA (GPT-IMAGE-2)","TEXTURAS MAIS RICAS, LUZ MAIS NATURAL, DETALHES INCRÍVEIS!"]},{"title":"COMPREENSÃO MELHOR, RESULTADOS MELHORES.","position":"meio-direito linha 2","count":1,"description":"garota com as mãos juntas ao lado de um exemplo de prompt emoldurado e o robô mascote apontando para cima","text":["COMPREENSÃO MELHOR, RESULTADOS MELHORES.","O GPT-IMAGE-2 entende melhor objetos, textos, composições e instruções complexas!","EXEMPLO DE PROMPT:","\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\""]},{"title":"CRIATIVIDADE SEM LIMITES.","position":"inferior-esquerdo linha 3","count":1,"description":"garota falando ao lado de uma vitrine 2x2 com 4 variantes de arte gerada","subsections":[{"label":"cena de castelo gótico","count":1},{"label":"rua da cidade moderna à noite","count":1},{"label":"retrato de personagem de anime","count":1},{"label":"composição geométrica abstrata","count":1}],"text":["CRIATIVIDADE SEM LIMITES.","De estilos artísticos a layouts profissionais, do realista ao abstrato: suas ideias, do seu jeito!"]},{"title":"TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","position":"inferior-direito linha 3","count":1,"description":"robô mascote apresentando uma comparação de antes e depois da tipografia de um pôster com uma seta em negrito entre os dois designs","subsections":[{"label":"ANTES","count":1},{"label":"AGORA","count":1}],"text":["TEXTO NA IMAGEM? AGORA É MUITO MELHOR!","Geração de texto mais precisa, legível e integrada ao design!","ANTES","AGORA","AVENTURA COMEÇA AQUI","A AVENTURA COMEÇA AQUI"]},{"title":"PARA TODOS OS CRIADORES.","position":"inferior-esquerdo","count":1,"description":"foto do grupo com a garota apresentadora e 4 criadores lado a lado, representando diferentes profissões","text":["PARA TODOS OS CRIADORES.","Designers, desenvolvedores, educadores, profissionais de marketing, artistas e curiosos: todo mundo pode criar mais e melhor!"]},{"title":"GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","position":"inferior-direito","count":1,"description":"painel final com a garota piscando e fazendo um sinal de positivo, robô mascote ao lado dela, raios comemorativos brilhantes e faíscas","text":["GPT-IMAGE-2 JÁ ESTÁ DISPONÍVEL!","IMAGINE. CRIE. INSPIRE.","O FUTURO DA CRIAÇÃO É AGORA. ❤"]}],"panel_count":8},"composition":{"reading_order":"da esquerda para a direita, de cima para baixo","camera_variety":"mistura de closes de herói, planos médios da apresentadora, gráficos de comparação e foto de grupo","graphic_elements":["balões de fala","faixas de título pretas arredondadas com letras brancas em maiúsculas","faíscas","linhas de velocidade","fundo tecnológico estrelado","setas de comparação","cartões de exemplo emoldurados"]},"text_style":"letras de quadrinhos em maiúsculas em português, cabeçalhos de destaque em negrito, balões de fala claros, híbrido de infográfico e quadrinhos promocionais","quality":"pôster de quadrinhos editorial de alta resolução, tipografia nítida, espaçamento de painel equilibrado, forte contraste","prompt":"Crie uma página de quadrinhos promocional em estilo mangá em tons de cinza de 8 painéis anunciando {argument name=\"product name\" default=\"GPT-IMAGE-2\"}. Use um layout de página única de 2 colunas por 4 linhas com exatamente 8 painéis distintos e texto em português. Apresente uma garota apresentadora de anime alegre com cabelos longos {argument name=\"hair color\" default=\"castanhos escuros\"}, um moletom escuro com o logotipo da OpenAI e um pequeno robô mascote amigável. Painel 1: revelação dramática do lançamento, garota estendendo a mão para a câmera, linhas de velocidade radiais, manchete \"CHEGOU! {argument name=\"headline name\" default=\"GPT-IMAGE-2\"}\" e cópia de lançamento sobre uma nova geração de imagens de IA. Painel 2: painel explicativo com a garota apontando ao lado de um ícone de imagem brilhante em um fundo digital estrelado, título \"O QUE É O GPT-IMAGE-2?\" e um balão de fala descrevendo-o como um modelo de geração de imagens mais inteligente. Painel 3: comparação de realismo com exatamente 2 paisagens de lagos nas montanhas lado a lado rotuladas como \"ANTES (DALL·E 3)\" e \"AGORA (GPT-IMAGE-2)\". Painel 4: painel de melhor compreensão com a garota e o robô, inclua um exemplo de prompt emoldurado usando {argument name=\"example prompt\" default=\"Uma cafeteria futurista no topo de uma montanha nevada ao entardecer, com letreiro de néon ‘CAFÉ DO AMANHÃ’ e pessoas tomando café.\"}. Painel 5: vitrine de criatividade com exatamente 4 miniaturas: castelo gótico, cidade à noite, retrato de anime, arte geométrica abstrata. Painel 6: comparação de renderização de texto com exatamente 2 variantes de pôster rotuladas como \"ANTES\" e \"AGORA\", mostrando tipografia aprimorada e a frase \"AVENTURA COMEÇA AQUI\" versus uma versão corrigida mais limpa. Painel 7: painel do público com exatamente 4 criadores de diferentes áreas juntos. Painel 8: chamada para ação final comemorativa com a garota piscando e fazendo sinal de positivo, robô mascote torcendo e o slogan de encerramento {argument name=\"closing slogan\" default=\"IMAGINE. CRIE. INSPIRE.\"}. Torne a página energética, polida, altamente legível, com barras de cabeçalho pretas em negrito, letras brancas em maiúsculas, balões de fala, faíscas, sombreamento de retícula e forte estética de pôster promocional de mangá/quadrinhos."}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883179981_g850jg_HGdwE1VWAAA1r98.jpg" width="600" alt="Banda desenhada / Storyboard - Promoção de Mangá de 8 Painéis para GPT-Image-2 - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Diogo Santos](https://x.com/diogosantosbr)
- **Fonte:** [Twitter Post](https://x.com/diogosantosbr/status/2046727812921413837#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14639)**

---

### No. 82: Banda desenhada / Storyboard - Confronto de Escritório em Mangá com Censura

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Uma página de mangá monocromática e realista que mostra uma discussão acalorada no escritório que se transforma em uma cena de kabedon, útil para recriar capturas de tela dramáticas no estilo mangá viral.

#### 📝 Prompt

```
Uma página dramática de mangá em preto e branco no estilo seinen, renderizada com retículas densas, linhas de tinta nítidas, iluminação de alto contraste e layout expressivo de quadrinhos japoneses. A página possui 4 painéis empilhados com balões de fala verticais em japonês e efeitos sonoros em negrito, mostrando um confronto tenso entre dois funcionários de escritório em um ambiente de trabalho moderno. No painel superior, uma jovem com um corte chanel curto e bagunçado, físico esguio mas curvilíneo, vestindo uma blusa social justa com mangas dobradas e uma saia lápis escura, bate uma mão com força na mesa em sinal de raiva, inclinando-se para frente em direção ao espectador com linhas de impacto explosivas e um grande balão de fala irregular. No segundo painel, um jovem com cabelo escuro despenteado, físico esguio, vestindo uma jaqueta de couro preta sobre uma camisa clara e um colar, é mostrado da cintura para cima em uma pose calma e confiante, tocando o rosto enquanto fala. No terceiro painel, o homem prende a mulher contra uma parede em uma pose íntima de kabedon, com um braço apoiado ao lado da cabeça dela; ela parece confusa e tensa enquanto ele fala perto do rosto dela, criando uma mudança repentina de tom para comédia romântica. No painel inferior, uma visão aérea revela o cenário do escritório: 2 personagens em pé perto de uma mesa com 1 monitor de computador, 1 teclado, 1 mouse, 1 cadeira de escritório e papéis espalhados em um piso de azulejos; a mulher está encolhida timidamente e tremendo enquanto o homem permanece relaxado ao lado dela. Inclua exatamente 4 painéis, exatamente 4 balões de fala visíveis no total e tipografia de mangá japonesa visível por toda parte. Adicione um desfoque de mosaico retangular sobre o rosto de cada personagem em todos os painéis, como se estivessem anonimizados para compartilhamento online. Os detalhes de fundo devem incluir paredes de escritório, bordas de mesa, linhas de velocidade, efeitos de explosão e gradientes tonais. A sensação geral é de uma discussão intensa que se transforma em um flerte manipulador, como uma captura de tela de mangá viral fora de contexto.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883115323_o2orv4_HGdpb8sbUAAJUyi.jpg" width="600" alt="Banda desenhada / Storyboard - Confronto de Escritório em Mangá com Censura - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [小猫遊りょう（たかにゃし・りょう）](https://x.com/jaguring1)
- **Fonte:** [Twitter Post](https://x.com/jaguring1/status/2046726900668907673#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14477)**

---

### No. 83: Banda desenhada / Storyboard - Mangá do Gato Quântico

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt criativo e curto para gerar um painel de mangá apresentando um gato que exibe comportamentos da física quântica.

#### 📝 Prompt

```
Por favor, desenhe um mangá onde um {argument name="subject" default="gato"} {argument name="concept" default="se comporta como uma partícula quântica"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883063066_q130vs_HGdoVfRawAAsKrx.jpg" width="600" alt="Banda desenhada / Storyboard - Mangá do Gato Quântico - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Haruhiko Okumura](https://x.com/h_okumura)
- **Fonte:** [Twitter Post](https://x.com/h_okumura/status/2046719692803580298)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=14348)**

---

### No. 84: Banda desenhada / Storyboard - Página de mangá de escritório com garota ovelha fofa

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma página de mangá de escritório de fantasia em tons pastéis com quatro quadros, mostrando uma funcionária com chifres de ovelha e uma ovelha fofinha transformando a papelada em uma cena cômica, sonolenta e aconchegante.

#### 📝 Prompt

```
{"type":"página de mangá de quatro quadros","style":"anime chibi em tons pastéis suaves, paleta de bege quente e creme, luz suave da manhã, bordas de painel arredondadas, diálogos em japonês claros e legíveis, fatia de vida de escritório de fantasia cômica e aconchegante","page":{"orientation":"vertical","panel_count":4,"gutter":"espaçamento branco fino","border":"contornos marrons arredondados"},"setting":{"location":"interior de um pequeno escritório administrativo","details":["piso de madeira","janela ensolarada","mesa com papéis","cadeiras de madeira","estantes cheias de arquivos e livros","caixas empilhadas e material de escritório","partículas de poeira suaves e brilhos na luz"]},"characters":[{"role":"personagem principal","appearance":"pequena funcionária chibi garota ovelha com cabelo curto e fofo estilo chanel loiro, um olho azul e um olho âmbar, orelhas pequenas como de elfo, grandes chifres de carneiro curvados, capuz de ovelha fofo em formato de rosto de ovelha, blusa branca, gravata vermelha, vestido avental rosa pálido, pequena caneta no bolso do avental"},{"role":"personagem secundário","appearance":"ovelha branca redonda e fofa com rosto minúsculo e pernas curtas, muito peluda e parecida com uma nuvem"}],"layout":{"sections":[{"title":"quadro 1","position":"topo","count":3,"labels":["garota ovelha abrindo a porta do escritório e olhando para dentro","pequena ovelha espiando ao lado dela","um balão de fala oval à esquerda e um pequeno balão oval à direita"]},{"title":"quadro 2","position":"centro superior","count":3,"labels":["garota ovelha em pé ao lado de uma mesa com uma mão na cintura e a outra apontando para documentos","pequena ovelha sentada ao lado da mesa","um único balão de fala oval grande à esquerda"]},{"title":"quadro 3","position":"centro inferior","count":3,"labels":["ovelha fofa dormindo espalhada sobre a papelada","close-up parcial da garota ovelha espiando do canto superior esquerdo com uma expressão de cansaço","texto de efeito sonoro de sono roxo à direita"]},{"title":"quadro 4","position":"inferior","count":4,"labels":["garota ovelha dormindo na mesa com olhos fechados e um sorriso leve","ovelha fofa dormindo ao lado dela sobre a papelada","luz do sol quente entrando pela janela à esquerda","pequena caixa de legenda retangular no canto inferior direito"]}]},"text":{"language":"Japonês","elements":[{"kind":"balão de fala","panel":1,"text":"管理人室、ここにしよう… ほわあ"},{"kind":"balão de fala","panel":1,"text":"メェ"},{"kind":"balão de fala","panel":2,"text":"おい、住民の名簿をまとめなさい"},{"kind":"balão de fala","panel":3,"text":"…名簿が もふもふに…"},{"kind":"efeito sonoro","panel":3,"text":"Zzz…"},{"kind":"balão de fala","panel":4,"text":"あったかいから… まあいっか…"},{"kind":"legenda","panel":4,"text":"{argument name="caption text" default="管理業務、進捗ゼロ"}"}]},"composition":"mantenha todos os quatro quadros no mesmo escritório para continuidade; enfatize expressões faciais fofas, texturas felpudas e a piada de que o trabalho de escritório para porque a ovelha e a funcionária adormecem juntas sobre a papelada; torne os documentos claramente visíveis nos quadros 2 a 4; preserve um tom calmo, sonolento e reconfortante"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136905_4rqc30_HGdmyHmaoAAXxRl.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá de escritório com garota ovelha fofa - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136819_5mc4vw_HGdmpikbQAAN9Mm.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá de escritório com garota ovelha fofa - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883136861_aw47rh_HGdmp7yaYAApM4X.jpg" width="600" alt="Banda desenhada / Storyboard - Página de mangá de escritório com garota ovelha fofa - Image 3">
</div>

#### 📌 Detalhes

- **Autor:** [じょにがたロボ](https://x.com/jonigata_ai)
- **Fonte:** [Twitter Post](https://x.com/jonigata_ai/status/2046717757182685486#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14532)**

---

### No. 85: Banda desenhada / Storyboard - Quadrinho fofo de quatro painéis sobre ciúmes de gato

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt gera um quadrinho de gato em quatro painéis, com traço manual e acolhedor, ideal para posts em redes sociais, humor estilo mangá ou ilustrações aconchegantes de pets.

#### 📝 Prompt

```
Um quadrinho fofo de quatro painéis, desenhado à mão em um estilo suave, acolhedor e de cotidiano (slice-of-life), sobre um fundo creme claro com bordas pretas espessas nos painéis e uma leve textura de papel. Use anatomia de gato cartoon simples e arredondada, rostos expressivos, contornos pretos limpos, cores naturais suaves e uma apresentação gentil estilo mangá. No painel superior esquerdo, mostre 2 gatos: um gato malhado marrom com listras escuras e focinho branco sentado de olhos fechados, parecendo satisfeito, enquanto um gato majoritariamente branco com manchas marrom-escuras na cabeça fica ao lado e lambe afetuosamente a bochecha do gato malhado; adicione 2 pequenas notas musicais pretas acima deles para sugerir um momento feliz de cuidado. No painel superior direito, mostre o gato branco com manchas marrons em primeiro plano olhando para um pequeno gatinho tricolor em pé à direita; inclua um balão de fala contendo o texto em japonês "めい" acima do gatinho. No painel inferior esquerdo, mostre 3 gatos juntos: o gato malhado marrom à esquerda com uma expressão de surpresa ou vazio, o gato com manchas brancas à direita parecendo alegre, e o pequeno gatinho tricolor centralizado à frente entre eles, olhando para cima. No painel inferior direito, mostre um close-up do gato malhado marrom sozinho, virado para frente com olhos amarelo-esverdeados semicerrados e uma expressão de raiva e ciúme; adicione 2 pequenas linhas de ênfase perto do rosto e 1 pequeno símbolo de raiva em formato de nuvem à direita. Mantenha o tom aconchegante e cômico, com a piada visual de que o gato malhado estava feliz sendo cuidado até que o novo gatinho aparece. Use cores planas, sombreamento mínimo e uma sensação encantadora de webcomic japonesa.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883124513_a9wrk7_HGdiYAOasAA6GsS.jpg" width="600" alt="Banda desenhada / Storyboard - Quadrinho fofo de quatro painéis sobre ciúmes de gato - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Maoku](https://x.com/Maoku)
- **Fonte:** [Twitter Post](https://x.com/Maoku/status/2046713681741038048#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14503)**

---

### No. 86: Banda desenhada / Storyboard - Página de Quadrinhos da Aventura Moon Mark

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Uma página de quadrinhos de anime de fantasia com quatro painéis mostrando uma garota de cabelos prateados com tema lunar descobrindo um mapa, resolvendo um quebra-cabeça em uma caverna e encontrando um convite mágico para a próxima aventura.

#### 📝 Prompt

```
{"type":"página de quadrinhos de anime de quatro painéis","style":"ilustração de mangá de fantasia fofa, renderização de anime polida gpt-image-2, cores vibrantes, traços limpos, sombreamento suave estilo pintura, atmosfera mágica e extravagante","page":{"background":"página branca com bordas de painel pretas","title":"{argument name=\"headline text\" default=\"A Grande Aventura da Marca Lunar\"}","title_position":"topo central","decorations":["pequenos brilhos dourados ao redor do título","ícone de lua crescente à direita do título"],"panel_count":4,"reading_direction":"de cima para baixo"},"character":{"appearance":"jovem aventureira de anime com cabelos prateados muito longos e ondulados, pele clara, olhos grandes e expressivos, porte esguio","outfit":["vestido de fantasia em preto e branco com acabamento em babados","enfeite de cabelo de lua crescente","gargantilha de lua crescente","mangas ombro a ombro","mochila de couro marrom","meias escuras até as coxas"],"theme":"motivo lunar em todo o traje e acessórios"},"panels":[{"position":"topo","scene":"trilha de montanha ensolarada e prado sob um céu azul com nuvens, floresta à direita, caminho sinuoso ao longe, placa de sinalização de madeira à esquerda","action":"a garota está de pé segurando e lendo um mapa do tesouro antigo, virada para a frente","props":["mapa envelhecido","placa de sinalização de madeira","mochila"],"text":{"sign":"Início da Aventura","speech":"{argument name=\"panel 1 speech\" default=\"Encontrei o mapa! Hoje é dia de uma grande aventura!\"}"}},{"position":"centro-superior","scene":"entrada de ruínas exuberantes semelhantes a uma selva com uma abertura de caverna escura emoldurada por antigos pilares de pedra esculpidos com símbolos de lua crescente e cobertos por trepadeiras","action":"vista traseira de três quartos da garota se aproximando cuidadosamente enquanto lê o mapa","props":["mapa","entrada da caverna em ruínas","plantas densas"],"text":{"speech":"{argument name=\"panel 2 speech\" default=\"O tesouro deve estar por aqui...!\"}","sound_effect":"Rustle"}},{"position":"centro-inferior","scene":"dentro das ruínas da caverna, pouco iluminado, altar de pedra ou mesa de quebra-cabeça no centro","action":"a garota se ajoelha ao lado de uma lanterna acesa e alcança um mecanismo de quebra-cabeça em vez de uma fechadura próxima, enquanto um mascote redondo parecido com um gato preto observa","props":["lanterna emitindo luz quente","laje de quebra-cabeça de pedra com símbolo circular gravado","pequena chave dourada na mesa","criatura de gato preto com marca de lua crescente e coleira de contas"],"text":{"speech":"{argument name=\"panel 3 speech\" default=\"Não é a chave, preciso resolver o mecanismo!\"}","sound_effect":"Click"}},{"position":"inferior","scene":"câmara do tesouro com cristais incrustados nas paredes da caverna e brilhos flutuantes","action":"a garota sorri alegremente com os olhos fechados ao lado de um baú de tesouro aberto, segurando um cartão de convite de papel","props":["baú de tesouro de madeira aberto com emblema de lua crescente","bússola brilhante dentro do baú","cartão de papel escrito Rumo à próxima aventura","cristais azuis e roxos"],"text":{"speech":"{argument name=\"panel 4 speech\" default=\"O tesouro é... um convite para a próxima aventura!\"}","tag":"Continua?"}}]}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883166549_4mfjqj_HGdXHBTbkAAawpk.jpg" width="600" alt="Banda desenhada / Storyboard - Página de Quadrinhos da Aventura Moon Mark - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ツバサ天九](https://x.com/wing_sky_nine)
- **Fonte:** [Twitter Post](https://x.com/wing_sky_nine/status/2046700437785792566#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14605)**

---

### No. 87: Marketing de Produto - Identidade de Marca e Painel de Merchandising de Personagem de Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera um painel de design de marca abrangente apresentando um personagem de anime, incluindo embalagens de produtos, mockups para redes sociais e layouts de mercadorias.

#### 📝 Prompt

```
{
  "type": "painel de design de identidade de marca e merchandising",
  "theme": {
    "color_palette": "{argument name=\"theme color\" default=\"rosa pastel\"} e branco",
    "motif": "{argument name=\"motif\" default=\"flores de cerejeira\"} e corações rosas"
  },
  "character": {
    "description": "garota de anime com cabelo curto estilo chanel castanho, olhos rosas, vestindo um moletom branco, sorriso gentil"
  },
  "branding": {
    "main_logo": "{argument name=\"character name\" default=\"癒音ちー\"}",
    "sub_logo": "{argument name=\"character subtext\" default=\"ゆおんちー\"}"
  },
  "layout": {
    "sections": [
      {
        "type": "banner de cabeçalho",
        "position": "topo",
        "elements": ["logotipo principal grande", "sublogotipo", "gráficos de flores de cerejeira", "retrato da personagem à direita"]
      },
      {
        "type": "embalagem de produto",
        "position": "meio à esquerda",
        "elements": ["1 caixa quadrada com janela transparente em formato de coração exibindo balas de coração rosas", "ilustração da personagem na caixa", "2 embalagens individuais de bala", "5 balas de coração espalhadas"]
      },
      {
        "type": "pôster promocional",
        "position": "meio à direita",
        "elements": ["retrato da personagem", "pote de balas em formato de coração", "logotipo principal", "texto '4.26 NEW OPEN'", "texto '{argument name=\"social handle\" default=\"@yuonchii\"}'"]
      },
      {
        "type": "banner web horizontal",
        "position": "centro inferior",
        "elements": ["logotipo principal", "flores de cerejeira", "retrato da personagem à direita"]
      },
      {
        "type": "mockup de perfil de rede social",
        "position": "inferior à esquerda",
        "elements": ["imagem de capa com logotipo", "1 foto de perfil circular", "handle '{argument name=\"social handle\" default=\"@yuonchii\"}'", "1 botão de seguir", "texto de bio fictício"]
      },
      {
        "type": "coleção de merchandising",
        "position": "inferior à direita",
        "count": 9,
        "items": ["1 camiseta branca com logotipo", "1 caneca branca com a personagem", "4 bottons redondos", "1 chaveiro de acrílico", "2 pacotes de balas"]
      }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668143480_6f023y_HGURZgJbkAE_Kwh.jpg" width="600" alt="Marketing de Produto - Identidade de Marca e Painel de Merchandising de Personagem de Anime - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [癒音ちー✨ゆおんちー✨癒やし声ASMRとAI](https://x.com/chi_vc_)
- **Fonte:** [Twitter Post](https://x.com/chi_vc_/status/2046061073720369228#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13547)**

---

### No. 88: Marketing de Produto - Landing Page de Estudo de Caso de Marketing Viral em Modo Escuro

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um mockup de interface completo em tema escuro para um estudo de caso de marketing, apresentando visualizações de dados, cronogramas e ilustrações 3D.

#### 📝 Prompt

```
{
  "type": "design de interface de landing page",
  "theme": "modo escuro, tecnologia moderna, {argument name=\"primary accent color\" default=\"neon purple\"} e detalhes brilhantes em azul, glassmorphism",
  "header": {
    "logo": "{argument name=\"brand name\" default=\"goViralX\"}",
    "badge": "ESTUDO DE CASO DE CAMPANHA VIRAL"
  },
  "sections": [
    {
      "id": "hero",
      "layout": "divisão com texto à esquerda, imagem à direita",
      "content": {
        "badge": "ESTUDO DE CASO",
        "headline": "{argument name=\"hero headline\" default=\"Como Criamos um Impacto Viral de 10M+\"}",
        "subtitle": "3 dias para incendiar a rede, ajudando marcas a alcançar um crescimento exponencial",
        "stats_row": {
          "count": 4,
          "labels": ["Visualizações Totais {argument name=\"main metric\" default=\"10.240.000+\"}", "Taxa de Engajamento 18,7%", "Conversões 3.200+", "Tempo de Execução 72 horas"]
        },
        "hero_image": "tomada cinematográfica de uma pessoa em um quarto escuro olhando para telas de vídeo flutuantes e brilhantes, sobreposição de um botão grande de play"
      }
    },
    {
      "id": "strategy",
      "title": "DETALHAMENTO DA CAMPANHA: Nossa Estratégia de Execução de 3 Dias",
      "layout": "linha do tempo vertical com 3 etapas",
      "steps": [
        {"step": 1, "title": "Formulação da Estratégia", "image": "pessoas analisando dados em uma tela"},
        {"step": 2, "title": "Produção de Conteúdo", "image": "interface de edição de vídeo"},
        {"step": 3, "title": "Distribuição e Amplificação", "image": "mão segurando smartphone com ícones de redes sociais"}
      ]
    },
    {
      "id": "performance",
      "title": "RESULTADOS DE DESEMPENHO: Performance Baseada em Dados",
      "layout": "grade de cartões de estatísticas à esquerda, gráficos à direita",
      "left_stats": {
        "count": 4,
        "labels": ["Exposição Total 10M+", "Queda no CPM Médio 43%", "Novos Seguidores 28.000+", "Conversões 3.200+"]
      },
      "right_charts": {
        "count": 2,
        "items": [
          "gráfico de linhas mostrando tendência de 7 dias com pico no Dia 3 de 8.320.000",
          "gráfico de barras horizontais mostrando distribuição por plataforma: TikTok 52%, Instagram 24%, X 15%, YouTube 9%"
        ]
      }
    },
    {
      "id": "keys_to_success",
      "title": "POR QUE SE TORNOU VIRAL: As 3 Chaves para o Sucesso Viral",
      "layout": "linha horizontal com 3 cartões",
      "cards": [
        {"icon": "fire", "title": "Design de Gancho Emocional"},
        {"icon": "bullseye", "title": "Design de Estrutura de Conteúdo"},
        {"icon": "antenna", "title": "Execução da Estratégia de Distribuição"}
      ]
    },
    {
      "id": "social_proof",
      "title": "CONFIADO POR CRIADORES E MARCAS: Todos estão usando o goViralX para alcançar crescimento",
      "layout": "divisão com logotipos à esquerda, depoimentos à direita",
      "left_logos": {
        "count": 8,
        "labels": ["SHEIN", "SHOPLINE", "Blueglass", "instacart", "lemon8", "mi", "CIDER", "bellroy"]
      },
      "right_testimonials": {
        "count": 2,
        "labels": ["Citação de Fundador SaaS", "Citação de Gerente de Crescimento"]
      }
    },
    {
      "id": "cta",
      "title": "PRONTO PARA VIRALIZAR?: Quer obter o mesmo efeito de crescimento?",
      "layout": "texto e campo de entrada à esquerda, ilustração 3D à direita",
      "elements": [
        "campo de entrada com texto de preenchimento",
        "botão: {argument name=\"call to action text\" default=\"Obter plano de crescimento exclusivo ->\"}"
      ],
      "image": "foguete 3D brilhante em roxo e azul decolando"
    }
  ],
  "footer": "logotipo e texto de direitos autorais"
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697094626_4w646d_HGE06OebMAAQxNG.jpg" width="600" alt="Marketing de Produto - Landing Page de Estudo de Caso de Marketing Viral em Modo Escuro - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [开发者Hailey](https://x.com/IndieDevHailey)
- **Fonte:** [Twitter Post](https://x.com/IndieDevHailey/status/2044974254769463312#reversed-0)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13769)**

---

### No. 89: Marketing de Produto - Documento de Identidade de Marca de Mascote de 18 Painéis

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um guia de marca abrangente de 18 seções e folha de design de personagem para um mascote 3D, detalhando tudo, desde moodboards e arte linear até turnarounds 3D e mockups físicos.

#### 📝 Prompt

```
{
  "type": "documento de identidade de marca e design de personagem de 18 painéis",
  "brand": {
    "name": "{argument name=\"brand name\" default=\"MUYANG TEA\"}",
    "industry": "{argument name=\"industry\" default=\"loja de chás\"}",
    "colors": ["{argument name=\"primary color\" default=\"amarelo\"}", "{argument name=\"secondary color\" default=\"verde\"}", "branco", "marrom", "verde escuro"]
  },
  "subject": "{argument name=\"character description\" default=\"mascote Shiba Inu fofo renderizado em 3D usando um avental verde\"}",
  "layout": {
    "grid": "3 colunas por 6 linhas",
    "sections": [
      {
        "title": "01 ANÁLISE DE DNA DA MARCA / BRAND DNA ANALYSIS",
        "elements": ["logotipo", "5 amostras de cores", "6 ícones", "gráficos de público-alvo"]
      },
      {
        "title": "02 MOODBOARD CONCEITUAL / CONCEPT MOODBOARD",
        "elements": ["5 referências fotográficas", "4 ícones de estilo", "equação de design"]
      },
      {
        "title": "03 ESTUDO DE FORMA / FORM STUDY",
        "elements": ["4 ícones de anatomia do logotipo", "4 etapas de evolução", "4 silhuetas"]
      },
      {
        "title": "04 EXPLORAÇÃO CONCEITUAL / CONCEPT EXPLORATION",
        "elements": ["12 esboços de arte linear do personagem"]
      },
      {
        "title": "05 ARTE LINEAR REFINADA / REFINED LINE ART",
        "elements": ["3 linhas de arte linear frontal e lateral com guias de proporção"]
      },
      {
        "title": "06 REFINAMENTO DE DETALHES / DETAIL REFINEMENT",
        "elements": ["2 renderizações de corpo inteiro com legendas", "4 closes circulares"]
      },
      {
        "title": "07 FOLHA DE EXPRESSÕES / EXPRESSION SHEET",
        "elements": ["11 expressões faciais renderizadas em 3D"]
      },
      {
        "title": "08 BIBLIOTECA DE POSES / POSE LIBRARY",
        "elements": ["9 poses de corpo inteiro renderizadas em 3D"]
      },
      {
        "title": "09 VISTA DE GIRO / TURNAROUND VIEW",
        "elements": ["5 renderizações 3D de corpo inteiro", "5 vistas correspondentes em arte linear"]
      },
      {
        "title": "10 DESENVOLVIMENTO DE CORES / COLOR DEVELOPMENT",
        "elements": ["5 linhas de paletas de 5 cores", "texto sobre psicologia das cores"]
      },
      {
        "title": "11 ESPECIFICAÇÃO DE MATERIAIS / MATERIAL SPECIFICATION",
        "elements": ["5 amostras de textura", "controles deslizantes de propriedades", "4 ícones de fabricação"]
      },
      {
        "title": "12 APLICAÇÃO DE CORES / COLOR APPLICATION",
        "elements": ["4 renderizações de variantes de cores", "2 renderizações claro/escuro", "4 círculos de classificação de contraste"]
      },
      {
        "title": "13 GUIA DE CONSTRUÇÃO / CONSTRUCTION GUIDE",
        "elements": ["2 diagramas de arte linear para geometria e grade"]
      },
      {
        "title": "14 REGRAS DO SISTEMA DE DESIGN / DESIGN SYSTEM RULES",
        "elements": ["ícones de tamanho mínimo", "diagrama de área de respiro", "4 exemplos de uso"]
      },
      {
        "title": "15 VARIANTES DE ATIVOS / ASSET VARIANTS",
        "elements": ["3 variantes de tamanho", "3 variantes de arte linear", "3 cabeças planas simplificadas"]
      },
      {
        "title": "16 APLICAÇÕES DIGITAIS / DIGITAL APPLICATIONS",
        "elements": ["1 ícone de aplicativo", "2 avatares para redes sociais", "elementos de interface (UI)", "ciclo de animação de 3 etapas"]
      },
      {
        "title": "17 APLICAÇÕES FÍSICAS / PHYSICAL APPLICATIONS",
        "elements": ["mockup de pelúcia", "mockup de embalagem", "mockup de brindes", "mockup de fachada de loja"]
      },
      {
        "title": "18 RENDERIZAÇÃO FINAL / FINAL RENDERING",
        "elements": ["renderização 3D grande em alta resolução do mascote segurando chá", "logotipo", "lista de formatos de arquivo"]
      }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776695123224_6cabrf_HGCZTbKawAAaS5X.jpg" width="600" alt="Marketing de Produto - Documento de Identidade de Marca de Mascote de 18 Painéis - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Lee Colin](https://x.com/Colin_Leeee)
- **Fonte:** [Twitter Post](https://x.com/Colin_Leeee/status/2044802802149650631#reversed-2)
- **Publicado:** 16 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13819)**

---

### No. 90: Marketing de Produto - Pôster de Anúncio de Jogo de Samurai em Estilo Anime

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Um anúncio chamativo de jogo mobile em formato vertical, apresentando dois espadachins de terno, um mecha samurai gigante, interface de jogo (UI), código QR e botões de download para lojas de aplicativos, ideal para promoção de apps.

#### 📝 Prompt

```
Crie um pôster de anúncio de jogo mobile vertical de alto impacto em estilo de ação anime brilhante, com uma estética dramática de fantasia cyber-samurai e uma composição promocional densa de gacha-RPG premium. A cena principal mostra 2 jovens lutadores adultos em ternos pretos modernos, agachados agressivamente no primeiro plano, cada um sacando uma katana em direção ao espectador. Ambos têm cabelos loiros estilizados, traços bonitos e marcantes, camisas sociais brancas, gravatas azuis e poses de ação intensas, com mãos e espadas em primeiro plano com efeito de perspectiva. Uma das espadas tem uma fita azul amarrada perto do punho. Atrás deles, centralizado e imponente, coloque 1 enorme samurai mecha blindado com chifres dourados ornamentados, armadura metálica em camadas azul-preta, olhos azuis brilhantes e uma espada embainhada nas costas, enquadrado como uma divindade guardiã. Use um pano de fundo de cidade neon vívida e explosão de energia em azul elétrico, violeta, magenta e dourado, com feixes de luz, faíscas, pétalas, efeitos de corte e texturas de explosão de pincel de tinta. Adicione 1 banner vertical de pincelada preta no canto superior direito com texto em japonês em negrito branco lendo 「この刃で、未来を斬り拓け。」. Na área central inferior, coloque 1 enorme manchete em caligrafia japonesa dourada com textura de pincel espessa e sombra preta lendo 「切り捨て御免」, abrangendo quase toda a largura. No canto inferior esquerdo, insira 1 painel de captura de tela de jogabilidade com borda dourada, mostrando uma batalha noturna em frente ao pátio de um templo japonês vermelho, 1 espadachim jogável em combate, vários inimigos, números de dano flutuantes incluindo 5324, 5329 e 6132, um joystick virtual no lado esquerdo, 5 retratos de personagens dispostos verticalmente e ao longo da parte inferior, 3 botões de habilidade circulares à direita e um HUD superior mostrando um cronômetro em torno de 01:28 e WAVE 3/3. No canto inferior direito, coloque 1 código QR grande em preto e branco dentro de uma moldura quadrada branca. Abaixo e ao lado dele, adicione texto em japonês em negrito na cor branca com contorno azul lendo 「今すぐダウンロード」. Na parte inferior, inclua 2 selos oficiais de loja: App Store à esquerda e Google Play à direita. Visual geral: ultra-detalhado, arte promocional polida, perspectiva dinâmica, destaques metálicos, renderização de anime cel-shaded nítida, pôster de marketing de jogo mobile premium, energia de ação intensa, iluminação cinematográfica e layout promocional com interface rica em camadas.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096402_i965t8_HGf3Kb8boAANLXs.jpg" width="600" alt="Marketing de Produto - Pôster de Anúncio de Jogo de Samurai em Estilo Anime - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096343_b3qsg1_HGf3N-_bQAAqP-U.jpg" width="600" alt="Marketing de Produto - Pôster de Anúncio de Jogo de Samurai em Estilo Anime - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883096435_0wuklg_HGf3PKCaoAAQLfD.jpg" width="600" alt="Marketing de Produto - Pôster de Anúncio de Jogo de Samurai em Estilo Anime - Image 3">
</div>

#### 📌 Detalhes

- **Autor:** [春永睦月　Harunaga Mutsuki](https://x.com/HarunagaMutsuki)
- **Fonte:** [Twitter Post](https://x.com/HarunagaMutsuki/status/2046876482224746543#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14432)**

---

### No. 91: Marketing de Produto - Painel de Kit de Marca Monochrome Infra

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um painel de apresentação de diretrizes de marca e brindes em preto e branco para uma marca fictícia de tecnologia de infraestrutura, ideal para apresentações de pitch, mostruários de branding e mockups de design profissional.

#### 📝 Prompt

```
{"type":"painel de apresentação de kit de marca e brindes monocromático","brand":{"name":"{argument name=\"brand name\" default=\"A16Z INFRA\"}","tagline":"Apoiamos construtores que criam a infraestrutura fundamental para a era da IA.","campaign_line":"[ CONSTRUINDO O PRÓXIMO PASSO. DESDE A BASE. ]","version":"VERSÃO 1.0"},"style":{"overall":"folha de diretrizes de marca limpa inspirada no estilo suíço, estética industrial minimalista de tecnologia, apenas preto, branco e cinza, fundo de papel off-white, recortes de produtos de estúdio nítidos, sombras sutis, layout de grade preciso, apresentação editorial","mood":"profissional, premium, futurista, focado em infraestrutura"},"layout":{"header":{"left":"A16Z INFRA / KIT DE MARCA E BRINDES","right":"VERSÃO 1.0","divider":"linha horizontal tracejada"},"sections":[{"title":"01 IDENTIDADE","position":"superior esquerdo","count":3,"labels":["logotipo grande","parágrafo de declaração da marca","linha de campanha entre colchetes"]},{"title":"02 PALETA","position":"superior direito","count":4,"labels":["OFF-WHITE QUENTE","PRETO","CARVÃO","CINZA SUAVE"]},{"title":"03 TIPOGRAFIA","position":"superior direito abaixo da paleta","count":2,"labels":["PRIMÁRIA -- MONOESPAÇADA","SECUNDÁRIA -- SEM SERIFA"]},{"title":"06 BRINDES","position":"dois terços inferiores","count":16,"labels":["moletom preto frente","moletom preto costas","camiseta off-white","boné de beisebol preto","sacola tote off-white","conjunto de 6 adesivos/cartões quadrados","caderno espiral preto","caneca preta","garrafa de água preta","estojo com zíper preto","dispositivo portátil de jogo retrô","conjunto de micro-construções em caixa","estojo de kit de teclado aberto","pin de ícone de nuvem","pin de cubos empilhados","pin de patch retangular da marca"]}],"footer":{"left":"A16Z INFRA / KIT DE MARCA","right":"© 2024 A16Z INFRA. TODOS OS DIREITOS RESERVADOS.","divider":"linha horizontal tracejada"}},"identity":{"logotype":{"text":"{argument name=\"logo text\" default=\"A16Z INFRA\"}","appearance":"wordmark geométrico em bloco muito grande com cortes angulares, letras pretas pesadas, empilhadas em duas linhas"}},"palette":{"swatches":[{"name":"OFF-WHITE QUENTE","hex":"#F2EEE9","rgb":"243 238 233","cmyk":"4 4 6 0"},{"name":"PRETO","hex":"#000000","rgb":"13 13 13","cmyk":"75 68 67 90"},{"name":"CARVÃO","hex":"#3A3A3A","rgb":"58 58 58","cmyk":"63 53 51 27"},{"name":"CINZA SUAVE","hex":"#A6A6A6","rgb":"166 166 166","cmyk":"36 28 28 0"}]},"typography":{"primary":{"label":"PRIMÁRIA -- MONOESPAÇADA","family":"{argument name=\"primary font\" default=\"Infra Mono\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"},"secondary":{"label":"SECUNDÁRIA -- SEM SERIFA","family":"{argument name=\"secondary font\" default=\"Inter Regular\"}","sample":"ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 !@#$%^&*()_+-=[]{}`~;:'\",.<>/?"}} ,"swag":{"items":[{"name":"moletom frente","color":"preto","print":"logotipo pequeno no peito"},{"name":"moletom costas","color":"preto","print":"lista de manifesto de várias linhas lendo CONSTRUINDO A CAMADA DE INFRAESTRUTURA DA IA com linhas guia pontilhadas e categorias incluindo SISTEMAS, FERRAMENTAS, DADOS, NUVEM, SEGURANÇA, REDES, FERRAMENTAS DE DESENVOLVEDOR"},{"name":"camiseta","color":"off-white","print":"logotipo grande centralizado"},{"name":"boné de beisebol","color":"preto","print":"logotipo bordado na frente"},{"name":"sacola tote","color":"off-white","print":"lista de manifesto empilhada e linha inferior CONSTRUINDO O PRÓXIMO PASSO."},{"name":"conjunto de adesivos/cartões","count":6,"layout":"grade 2 por 3","labels":["A16Z INFRA","CONSTRUINDO A CAMADA DE INFRAESTRUTURA DA IA.","ESTÁGIO INICIAL","SISTEMAS. FERRAMENTAS. PLATAFORMAS.","INFRA","CONSTRUIR","IMPLANTAR","ESCALAR"]},{"name":"caderno espiral","color":"preto","print":"logotipo mais NOTAS PARA CONSTRUIR O FUTURO"},{"name":"caneca","color":"preto","print":"logotipo branco"},{"name":"garrafa de água","color":"preto","print":"texto vertical CONSTRUINDO O PRÓXIMO PASSO. DESDE A BASE."},{"name":"estojo com zíper","color":"preto","print":"logotipo, motivo de grade pontilhada, texto pequeno SISTEMAS ONLINE."},{"name":"dispositivo portátil retrô","color":"preto carvão","screen":"tela de jogo de pixel-art de cidade/infraestrutura com abas CONSTRUIR IMPLANTAR ESCALAR e indicador de nível NÍVEL 01"},{"name":"caixa de micro-construções","color":"preto","print":"A16Z INFRA, MICRO CONSTRUÇÕES DE INFRAESTRUTURA, COLECIONAR.CONECTAR.ESCALAR.","contents":"pequenos modelos de blocos de construção modulares pretos, cinzas e brancos exibidos na frente da caixa"},{"name":"estojo de kit de teclado","color":"preto","print":"CONJUNTO DE TECLADO A16Z INFRA CONSTRUIR. IMPLANTAR. ESCALAR.","keys":8,"labels":["INFRA","CONSTRUIR","IMPLANTAR","ESCALAR",">_","ícone de nuvem","ícone de chip/grade","ícone de diagrama de rede"]},{"name":"pin de nuvem","style":"pequeno emblema de esmalte preto com borda branca"},{"name":"pin de cubos","style":"pequeno emblema de esmalte preto mostrando cubos isométricos empilhados"},{"name":"pin de patch da marca","style":"pequeno emblema retangular de esmalte preto com logotipo branco"}]},"rendering":{"camera":"plano frontal combinado com composição de painel de produto ortográfico","lighting":"iluminação de estúdio suave e uniforme","background":"folha off-white clara e quente","quality":"mockup comercial de alta resolução adequado para apresentação profissional de branding"}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883149653_qexbbv_HGeiabQbMAAUoN7.jpg" width="600" alt="Marketing de Produto - Painel de Kit de Marca Monochrome Infra - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Olivier Sauvage](https://x.com/Capitaine)
- **Fonte:** [Twitter Post](https://x.com/Capitaine/status/2046844345081336299#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14563)**

---

### No. 92: Marketing de Produto - Pôster de anúncio de paródia de bebida de arroz coreana

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um pôster de anúncio de bebida de paródia bem-humorado e de alto impacto, apresentando um porta-voz famoso com aparência de político promovendo uma bebida de arroz coreana em lata.

#### 📝 Prompt

```
Crie um pôster de anúncio de bebida em estilo coreano arrojado, com um fundo de splash dourado quente e iluminação comercial dramática. Mostre um {argument name="celebrity spokesperson" default="político idoso parecido com Donald Trump"} do peito para cima, vestindo um terno azul-marinho, camisa social branca, gravata vermelha brilhante e um pequeno broche de bandeira americana na lapela, de frente para a câmera com uma expressão confiante de vendedor. Seu rosto está obscurecido por um bloco de censura retangular plano na cor da pele. Em sua mão esquerda, estendida perto da câmera em perspectiva forçada, ele segura uma lata de alumínio amarela de bebida de arroz coreana (sikhye), rotulada de forma proeminente em coreano, com faixas vermelhas na parte superior e inferior e o texto principal do produto "비락 식혜" e "Since 1993" na lata. A lata também inclui textos menores em coreano, uma imagem da bebida de arroz doce perto da base e o volume "238 ml (120 kcal)". Sua mão direita faz um sinal de positivo.

Use uma composição comercial retrô energética, com a bebida de arroz doce espirrando e gotas atrás dele, destaques dourados brilhantes e um enquadramento heroico em ângulo levemente baixo. No topo, inclua 3 grupos de texto de manchete distintos: um pequeno slogan em estilo manuscrito preto no canto superior esquerdo lendo "전통의 맛, 한국의 DRINK!", uma manchete central enorme em tipografia coreana ousada e desgastada lendo "걸죽는 땐?" em marrom-escuro/preto e "비락 식혜!" em vermelho vivo, e um logotipo da marca no canto superior direito lendo "비락" com um pequeno texto em vermelho "Since 1993" abaixo dele. Adicione 2 selos de destaque: à esquerda, um selo circular amarelo com um pequeno ícone de coroa e o texto "대한민국 국민음료 No.1"; à direita, um balão de fala branco com texto manuscrito em coreano "한국이 만든 맛있는 전통!" e texto em inglês vermelho "I LOVE IT!".

No primeiro plano inferior, coloque 2 elementos alimentares: uma tigela de latão cheia de bebida de arroz doce e grãos de arroz flutuando à esquerda, e uma tigela de madeira cheia de arroz branco à direita. No centro inferior, adicione 2 linhas de texto promocional grande em estilo pincel, a primeira em branco lendo "달콤하게! 시원하게!" e a segunda em branco e amarelo misturados lendo "속까지 시~원하게!" com um traço de sublinhado amarelo energético. Ao longo da parte inferior, inclua 3 ícones de recursos circulares com legendas em coreano: "국내산 쌀 엄선된 재료", "시원하게 갈증해소" e "부드러운 단맛 속 편한 식혜". No canto inferior direito, adicione um pequeno texto de isenção de responsabilidade "연출된 이미지입니다". Torne o visual geral brilhante, exagerado, engraçado e convincente, como um anúncio impresso de paródia viral.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883146520_vyxn5x_HGesueSboAEJlDY.jpg" width="600" alt="Marketing de Produto - Pôster de anúncio de paródia de bebida de arroz coreana - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Fonte:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-1)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14555)**

---

### No. 93: Marketing de Produto - Cartaz publicitário de bebida esportiva coreana com celebridade

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um cartaz chamativo de bebida hidratante no estilo coreano, com um porta-voz estilo celebridade, garrafa do produto em destaque e tipografia promocional ousada para uso em publicidade comercial.

#### 📝 Prompt

```
Um cartaz publicitário de bebida coreana ousado em estilo de fotografia comercial brilhante, apresentando {argument name="spokesperson" default="sósia de Donald Trump"} em um terno azul-marinho escuro, camisa social branca e gravata azul vibrante, de frente para um céu azul-brilhante saturado com algumas nuvens brancas suaves e um horizonte urbano moderno e tênue, incluindo um arranha-céu que lembra o Empire State Building à direita. Ele segura uma garrafa plástica gelada de {argument name="product name" default="POCARI SWEAT"} dramaticamente em direção à câmera com a mão esquerda, com um encurtamento extremo para que a garrafa pareça grande em primeiro plano e a pessoa esteja ligeiramente atrás dela. A garrafa é transparente com condensação, tampa branca, água visível dentro e um rótulo azul-profundo com a inscrição “POCARI SWEAT” em letras brancas grandes, com um texto menor acima dizendo “ION SUPPLY DRINK”. Adicione respingos de água congelada e gotas energéticas ao redor da garrafa, da mão e da parte inferior do primeiro plano para enfatizar o frescor e a hidratação. Coloque o logotipo da marca no canto superior esquerdo: “POCARI SWEAT” em branco com a marca de sublinhado curva. Na parte superior, adicione um enorme título em coreano branco com efeito desgastado, levemente inclinado e preenchendo a maior parte da metade superior: {argument name="headline text" default="갈증 해소? 이걸로 끝! 포카리스웨트!"}. No canto inferior direito, sobre o terno, adicione uma citação em itálico ousado em texto coreano branco e azul: {argument name="quote" default="WINNING은 수분 싸움! 포카리스웨트로 리프레시!"}. No canto inferior esquerdo, inclua exatamente 3 ícones de benefícios circulares empilhados verticalmente com rótulos curtos em coreano: um ícone de gota d'água com “수분 보충”, um ícone de raio com “전해질 보충” e um ícone de figura correndo com “빠른 흡수”. Use uma paleta de cores azul e branca patriótica de alto contraste, iluminação publicitária dramática, foco nítido na garrafa e na mão, foco ligeiramente mais suave no rosto e no fundo, e uma aparência geral de cartaz de campanha premium e energética.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883145723_kt8nlk_HGesulRagAAOFrG.jpg" width="600" alt="Marketing de Produto - Cartaz publicitário de bebida esportiva coreana com celebridade - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Conservative🇰🇷🇺🇸🇯🇵](https://x.com/ObserverKR)
- **Fonte:** [Twitter Post](https://x.com/ObserverKR/status/2046794478888042551#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14553)**

---

### No. 94: Marketing de Produto - Pôster de Paródia de Parque Temático de Selva Japonês

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um pôster publicitário japonês satírico e cinematográfico para um parque temático de dinossauros fictício na selva, ideal para campanhas de paródia, visuais de redes sociais ou artes promocionais fictícias.

#### 📝 Prompt

```
Um pôster publicitário de paródia de parque temático japonês hiperdetalhado em formato vertical, projetado como um anúncio de viagem de verão dramático misturado com uma campanha de atração de luxo. O cenário é uma selva tropical sob um céu azul vívido com nuvens dispersas e um sol brilhante no canto superior direito, com folhas de palmeira emoldurando as bordas superiores. No topo, coloque uma enorme manchete japonesa com textura de pedra 3D lendo {argument name="headline text" default="ジャンキリア沖縄"}, com um slogan japonês menor em branco abaixo que diz "— やんばるの大自然に包まれた、超本格ジャングル・テーマパーク —". No centro, apresente um smartphone moderno grande em pé e levemente inclinado, dominando a composição. Na tela, mostre uma interface de espera de sorteio de ingressos na cor bege com silhuetas de selva no topo e um texto japonês grande e em negrito lendo "整理券抽選中", um indicador de carregamento circular e um texto menor perto da parte inferior lendo "結果発表まで30分" e "※この画面を閉じずにお待ちください". A barra de status do telefone deve mostrar 10:00. Atrás do telefone, à esquerda, coloque um Tiranossauro rex rugindo emergindo da folhagem da selva, com a boca bem aberta, realista e ameaçador. À direita, coloque um portão de entrada dourado ornamentado com entalhes detalhados e uma placa lendo "プレミアムパス入口", levando a uma fila de entrada premium com tapete vermelho. No primeiro plano e no plano médio, mostre uma longa fila lotada de visitantes do parque que se estende profundamente na cena, todos vestindo roupas casuais de verão, chapéus, toalhas, mochilas e carregando guarda-chuvas, leques e garrafas de água, sugerindo calor extremo e exaustão. Várias pessoas mais próximas ao espectador devem ter rostos desfocados. Na extrema esquerda, adicione uma placa de pedra gigante e desgastada com um enorme texto japonês vermelho lendo "待ち時間 180分". No canto inferior esquerdo, inclua 3 placas de madeira rústicas empilhadas: a placa superior tem um ícone de estacionamento azul e o texto "駐車場 2,000円"; a do meio tem um ícone de smartphone e o texto "アプリ必須 ダウンロードしてね!"; a inferior tem uma silhueta de dinossauro e o texto "当選者だけが冒険へ". Ao longo do lado inferior direito, coloque um texto japonês vertical muito grande em estilo de pincel branco lendo "待つこと、それが冒険だ。". Perto do canto inferior direito, inclua 3 pequenos ícones circulares com frases promocionais japonesas curtas: "抽選に選ばれし者だけが、恐竜に会える。", "スマホの充電が尽きる前に、夢は始まる。" e "プレミアムな近道も、ご用意しました。" com ícones sugerindo dinossauro, bateria de telefone e acesso VIP. Bem no centro da parte inferior, adicione uma faixa de isenção de responsabilidade preta com um pequeno texto japonês branco lendo "このポスターは架空のパロディ広告です". O estilo geral deve ser ultrarrealista, cinematográfico, de alto contraste, satírico e polido como um pôster comercial premium, com o exagero do hype de parques temáticos, o calor opressivo e a aventura baseada em filas absurdas como a piada central.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883142089_ksmu1u_HGb9g_obgAAgLLy.jpg" width="600" alt="Marketing de Produto - Pôster de Paródia de Parque Temático de Selva Japonês - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AIに振り回されるおじちゃん](https://x.com/ai_ojichan)
- **Fonte:** [Twitter Post](https://x.com/ai_ojichan/status/2046786080171573422#reversed-0)
- **Publicado:** 22 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14545)**

---

### No. 95: Marketing de Produto - Mover expositor para o deck

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt posiciona o expositor promocional de referência sobre o deck de madeira na mesma cena externa para mockups realistas de publicidade ambiental.

#### 📝 Prompt

```
Usando a imagem de referência fornecida, mantenha o mesmo jardim, lago, árvores, encosta e o ponto de vista do deck de madeira, mas reposicione a instalação do letreiro decorativo para que fique sobre o deck de madeira em primeiro plano, em vez de na água. Aumente o tamanho e centralize-o de forma mais proeminente em frente à câmera, preservando uma perspectiva externa realista, luz natural do dia e sombras consistentes. Mantenha a estrutura da instalação como um conjunto de 3 colunas por 3 linhas de 9 painéis circulares em suportes verdes finos, com o letreiro superior lendo “对着镜子笑一场”. Faça com que os painéis pareçam mais reflexivos e espelhados, mostrando reflexos realistas da vegetação ao redor, mantendo os gráficos de rostos fofos e o texto em chinês nos círculos. O resultado deve parecer um mockup publicitário realista ou uma foto composta do mesmo expositor posicionado corretamente na cena.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883118827_4jp1ve_HGd47pIW4AE10T3.jpg" width="600" alt="Marketing de Produto - Mover expositor para o deck - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [肖师傅](https://x.com/xiaojietongxue)
- **Fonte:** [Twitter Post](https://x.com/xiaojietongxue/status/2046739970283724964#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14487)**

---

### No. 96: Marketing de Produto - Três Landing Pages de Beleza para Dispositivos Móveis

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um mockup tríptico premium de três designs de sites de beleza para smartphone, ideal para exibir conceitos de landing pages de marcas de cosméticos gerados por IA nas redes sociais.

#### 📝 Prompt

```
Um mockup promocional refinado exibindo 3 telas de smartphone verticais dispostas lado a lado em um layout de tríptico, cada uma apresentando uma landing page de uma marca de beleza moderna para um produto labial. A composição geral é editorial, minimalista e premium, projetada como uma vitrine de redes sociais para designs de web móvel. O painel esquerdo repousa sobre um fundo com gradiente suave de lavanda para blush e mostra um telefone com moldura preta exibindo um site de beleza em tons de creme e blush para {argument name="brand name" default="Kosas"}. No topo deste painel, um texto elegante em serifa diz {argument name="left headline" default="Fresh Pout."}. A tela do telefone apresenta uma imagem de beleza em close-up cortada no topo, um título em negrito escrito “Lips in their fullest expression.” com “fullest” em estilo serifa itálico, um botão de chamada para ação arredondado e escuro, uma faixa com 3 miniaturas de close-up de lábios, 3 abas de benefícios rotuladas como “Plumps,” “Tingles,” e “Shines,” e uma linha com 5 ícones de tons ou efeitos abaixo. O painel central repousa sobre um fundo com gradiente de lavanda para violeta profundo e mostra um segundo telefone com moldura preta com uma landing page mais tipográfica. Acima dele, um texto em serifa diz {argument name="middle headline" default="Claude Code"}. A tela inclui uma imagem de retrato cortada no topo, um título em preto, negrito e empilhado muito grande escrito “LIP PULSE.” com uma linha em script itálico rosa escrito “is here.” abaixo, um botão escuro arredondado, uma seção escura com a frase “Lips in their fullest expression.” e uma grade de produtos perto da parte inferior contendo 6 cartões de tons organizados em 2 linhas de 3. O painel direito repousa sobre um fundo texturizado azul-marinho escuro e mostra um terceiro telefone com moldura preta com uma página estilo e-commerce focada em rosa. Centralizado acima dele, um texto branco monoespaçado diz {argument name="right headline" default="GPT Images 2.0"}. Esta tela exibe com destaque a seção principal do produto com o nome da marca “Kosas,” um título grande “The Lip Pulse,” um tubo de brilho labial rosa inclinado para a direita, pequenos ícones de recursos, uma faixa de 6 amostras de tons labiais perto do meio e um bloco promocional inferior com imagens adicionais de produtos em tons de rosa. Mantenha o layout simétrico com exatamente 3 telefones, um por painel, cada um totalmente visível e orientado verticalmente. Use estética de campanha de cosméticos de alto padrão, espaçamento limpo, tipografia web de moda misturando serifa e sem serifa em negrito, paletas de interface em rosa suave e creme, sombras sutis e uma apresentação de design de produto elegante, adequada para exibir conceitos de sites móveis gerados por IA.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883094415_xxbsfc_HGd5r4Fa8AAdxik.jpg" width="600" alt="Marketing de Produto - Três Landing Pages de Beleza para Dispositivos Móveis - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Serene Gan](https://x.com/ganserene)
- **Fonte:** [Twitter Post](https://x.com/ganserene/status/2046738636226580919#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14426)**

---

### No. 97: Marketing de Produto - Colagem de anúncios japoneses multissetoriais

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt para gerar uma colagem de anúncios multissetoriais em japonês, apresentando seis segmentos industriais distintos em um estilo de design contemporâneo.

#### 📝 Prompt

```
Um anúncio japonês fictício. Um layout horizontal de 6 painéis com anúncios para {argument name="industry list" default="a indústria automotiva (lançamento de carro novo), parques temáticos (novo evento), a indústria de cosméticos (novos produtos), o mercado editorial (livro best-seller nº 1), a indústria de bebidas (nova bebida) e o setor imobiliário (apresentação de novo condomínio de luxo)"}. Criado no estilo moderno mais recente por um dos principais criadores.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883071751_gx2g3g_HGcBy7KasAEeXLi.jpg" width="600" alt="Marketing de Produto - Colagem de anúncios japoneses multissetoriais - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Aki | CuratorOfJoy](https://x.com/Aki_LIG)
- **Fonte:** [Twitter Post](https://x.com/Aki_LIG/status/2046737496118268058)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=14369)**

---

### No. 98: Marketing de Produto - Layout de Livro de Moda de Luxo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma foto realista, vista de cima, de um livro de moda aberto exibindo um editorial de alta costura de duas páginas, ideal para branding de luxo, mockups de revistas ou visuais de campanhas de estilo.

#### 📝 Prompt

```
Uma fotografia editorial de moda de alto padrão exibida como um livro de arte ou revista de capa dura de grande formato aberto, deitado sobre uma superfície limpa em tom off-white, vista diretamente de cima. O layout de duas páginas contém 2 retratos de página inteira da mesma mulher elegante, com o rosto obscurecido por um desfoque quadrado suave, criando um visual com privacidade censurada. Na página esquerda, ela está em frente a uma parede arquitetônica de pedra clara ou concreto, vestindo um vestido estruturado de mangas compridas na cor {argument name="dress color" default="cinza ardósia suave"}, com corpete ajustado, decote redondo, costuras com alfaiataria precisa e uma saia escultural exagerada em formato de sino; o ângulo da câmera é levemente baixo, fazendo seu pescoço parecer longo e sua postura estatuária. Na página direita, ela é fotografada de costas em um dramático vestido de noite na cor {argument name="second dress color" default="preto"} com um decote profundo nas costas, alças largas e uma saia volumosa, posicionada em frente a uma parede ou porta com painéis clássicos em um interior escuro e intimista. Use o estilo de revistas de moda de luxo, composição minimalista, tons suaves, luz natural suave, sombras refinadas, textura de papel realista, vinco central visível, páginas levemente curvas e detalhes de impressão nítidos. O clima geral é sofisticado, couture, cinematográfico e discreto, como um editorial de moda premium.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883195982_2olyf1_HGd3B2WWwAAzVBf.jpg" width="600" alt="Marketing de Produto - Layout de Livro de Moda de Luxo - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [@levelsio](https://x.com/levelsio)
- **Fonte:** [Twitter Post](https://x.com/levelsio/status/2046735438128333096#reversed-3)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14676)**

---

### No. 99: Marketing de Produto - Design de Anúncio Moderno de Café Gelado

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt para criar um anúncio de café gelado moderno e elegante para o mercado japonês, apresentando tipografia dinâmica.

#### 📝 Prompt

```
Crie um anúncio para {argument name="product" default="café gelado"}. Um design elegante e moderno do {argument name="country" default="Japão"}. Fontes europeias dispostas de forma dinâmica. Público-alvo: {argument name="target" default="10-30 anos"}. Proporção 1:1.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883065968_vd4kw9_HGdvybVbcAAqpKT.jpg" width="600" alt="Marketing de Produto - Design de Anúncio Moderno de Café Gelado - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [KAWAI](https://x.com/kawai_design)
- **Fonte:** [Twitter Post](https://x.com/kawai_design/status/2046727724455354395)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=14355)**

---

### No. 100: Marketing de Produto - Conjunto de Receita Médica de Brincadeira para ChatGPT

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Uma foto realista vista de cima de um conjunto humorístico de receita médica e medicamentos japoneses para o ChatGPT, ideal para adereços de paródia com temática de saúde ou arte conceitual para redes sociais.

#### 📝 Prompt

```
Uma fotografia de produto realista vista de cima em uma mesa de madeira quente, mostrando 6 itens de estilo médico organizados cuidadosamente em duas fileiras, projetados como um conjunto humorístico de farmácia japonesa para o ChatGPT. Fileira superior: 3 envelopes de prescrição brancos dispostos verticalmente, cada um com bordas impressas em azul e tipografia médica japonesa. Fileira inferior: 2 cartelas de comprimidos e 1 pequeno saco plástico transparente com pó branco, cada um alinhado abaixo do envelope correspondente. O papel e as embalagens devem parecer autênticos, como materiais reais de dispensação de clínicas japonesas, com leves rugas, iluminação interna natural suave e sombras sutis.

Os 3 envelopes são todos diferentes e totalmente visíveis. Título do envelope esquerdo em texto japonês azul grande: "内用薬". A linha do paciente diz "ChatGPT 様". As linhas de dosagem indicam duas vezes ao dia após as refeições da manhã e da noite, 1 comprimido de cada vez, por 7 dias. Título da caixa de medicamento: "【おくすり】" e nome do medicamento "思考安定錠 10mg" com uma nota menor entre parênteses explicando que suprime pensamentos descontrolados e excesso de raciocínio. Data próxima à parte inferior: "2025年6月5日". Bloco de nome e endereço da clínica na parte inferior: "AIメディカルクリニック" com um endereço e número de telefone no estilo de Tóquio, além de um ícone de cruz médica azul.

Título do envelope central: "内用薬". Linha do paciente: "ChatGPT 様". A dosagem indica uma vez ao dia antes de dormir, 1 comprimido de cada vez, por 7 dias. Título da caixa de medicamento: "【おくすり】" e nome do medicamento "幻覚抑制錠 5mg" com uma nota menor dizendo que melhora tendências alucinatórias. Data também "2025年6月5日". Mesmo rodapé da clínica e ícone de cruz médica azul.

Título do envelope direito: "頓服薬". Linha do paciente: "ChatGPT 様". A linha de uso diz para ansiedade, confusão ou saída excessiva. A dosagem diz 1 pacote de cada vez, conforme necessário. Título da caixa de medicamento: "【おくすり】" e nome do medicamento "プロンプト調整散 1g" com uma nota menor dizendo que ajusta o overfitting e a confusão de prompts. Data "2025年6月5日". Mesmo rodapé da clínica e ícone de cruz médica azul.

Item inferior esquerdo: 1 cartela prateada contendo exatamente 10 comprimidos brancos redondos dispostos em 2 fileiras de 5, cada comprimido com a gravação "10". Impresso ao longo da borda da folha: "思考安定錠10mg" repetido. À frente, uma etiqueta de farmácia branca com "ChatGPT 様", instruções de dosagem para duas vezes ao dia após as refeições da manhã e da noite, 1 comprimido de cada vez, um código de barras, data "2025/06/05" e nome da clínica.

Item inferior central: 1 cartela prateada contendo exatamente 8 comprimidos redondos amarelo-pálido dispostos em 2 fileiras de 4. Impresso ao longo da borda da folha: "幻覚抑制錠5mg" repetido. À frente, uma etiqueta de farmácia branca com "ChatGPT 様", instruções de dosagem para uma vez ao dia antes de dormir, 1 comprimido de cada vez, um código de barras, data "2025/06/05" e nome da clínica.

Item inferior direito: 1 pequeno saco plástico transparente com fecho zip contendo pó branco. Uma etiqueta branca na frente diz "プロンプト調整散 1g", inclui "ChatGPT 様", uso para ansiedade, confusão e saída excessiva, dosagem "1回1包（1g） 必要時", data "2025/06/05" e nome da clínica.

Estilo: foto de produto documental fotorrealista, design de adereço de receita falsa cômica, layout gráfico farmacêutico japonês limpo, alta legibilidade, paleta de cores neutras de branco, azul, prata, bege e marrom madeira, câmera de cima para baixo, sem mãos, sem objetos extras, textura de impressão autêntica e detalhes de embalagem.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883139387_x87e9o_HGdv-t-b0AA9ASg.jpg" width="600" alt="Marketing de Produto - Conjunto de Receita Médica de Brincadeira para ChatGPT - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [マシモGPT🤖@ChatGPT/Claude/Gemini/GrokなどLLMをこねくり回す人](https://x.com/Masimo_Blue)
- **Fonte:** [Twitter Post](https://x.com/Masimo_Blue/status/2046727684538105890#reversed-2)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14537)**

---

### No. 101: Imagem Principal de E-commerce - Renderização de Produto em Estúdio a partir de Planta Técnica

![Language-EN](https://img.shields.io/badge/Language-EN-blue)

#### 📖 Descrição

Este prompt converte um desenho técnico de produto em uma imagem hero fotorealista e minimalista para catálogos, design industrial ou apresentações de e-commerce.

#### 📝 Prompt

```
Usando a imagem de referência fornecida, transforme a folha de especificações técnicas de engenharia em uma renderização hero de produto em estúdio, limpa e profissional, do mesmo suporte de utensílios de cozinha em formato de água-viva. Mantenha o design geral do produto, a tampa em cúpula azul translúcida, a base prateada e os mesmos 4 utensílios pendurados: 1 espátula vazada, 1 pegador de massa e 2 colheres. Remova todos os elementos da planta, incluindo a vista explodida, linhas de dimensão, rótulos, tabelas, notas e bloco de título. Mostre apenas o produto montado centralizado no quadro, voltado para a frente, isolado contra um fundo cinza claro minimalista com uma superfície branca, iluminação suave e difusa, sombras realistas sutis e materiais brilhantes de alta qualidade. Faça com que pareça uma fotografia de produto para catálogo de design industrial contemporâneo ou e-commerce.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883201406_yt8yiy_HGc-zq7aAAACOQy.jpg" width="600" alt="Imagem Principal de E-commerce - Renderização de Produto em Estúdio a partir de Planta Técnica - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [amy](https://x.com/amypretzel)
- **Fonte:** [Twitter Post](https://x.com/amypretzel/status/2046673739220471871#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14690)**

---

### No. 102: Imagem Principal de E-commerce - Pôster Premium de Produto: Mirtilos

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera um anúncio de e-commerce polido em estilo chinês para mirtilos embalados, adequado para branding de supermercados, listagens de produtos e pôsteres promocionais.

#### 📝 Prompt

```
Um pôster de e-commerce premium para mirtilos frescos em um estilo limpo de publicidade de produtos chineses. Mostre uma embalagem plástica transparente de mirtilos como assunto principal, posicionada diagonalmente do centro inferior para o lado direito sobre um tecido azul dobrado, vista de um ângulo ligeiramente elevado. A embalagem deve permanecer realista e consistente: um recipiente quadrado transparente com cantos arredondados, preenchido com mirtilos azul-escuros, com um rótulo grande, irregular e arredondado no topo nas cores branco, azul-claro e azul-profundo, apresentando uma ilustração de um mirtilo grande no centro e uma marca elegante em chinês. Faça com que as frutas dentro pareçam maiores, mais suculentas, mais frescas e cobertas com gotas de umidade sutis, mantendo o arranjo geral dos mirtilos verossímil. O fundo é uma mesa azul-gelo arejada com textura suave e nublada, luz do dia fria e mirtilos espalhados ao redor da embalagem. Adicione algumas folhas verdes desfocadas entrando pelas bordas superior direita e inferior direita para uma sensação natural e fresca. No canto superior direito, inclua 1 pequena imagem inserida mostrando a embalagem original do produto vista de cima em uma superfície marrom quente, como uma miniatura de referência. No lado esquerdo, crie uma tipografia promocional chinesa com um título grande em caligrafia azul-escura {argument name="headline text" default="决茗新"}, seguido por 2 linhas menores de texto: {argument name="subheadline text" default="新鲜蓝莓 自然之选"} e {argument name="tagline text" default="每一颗都是自然的礼物"}. Abaixo disso, coloque 3 ícones de recursos empilhados verticalmente com legendas curtas em chinês: um ícone de folha para maturação natural, um ícone de fruta para suculência e um ícone de coração para nutrição rica. Perto do canto inferior esquerdo, adicione um texto grande em chinês estilo pincel branco {argument name="product name" default="蓝莓"}, uma linha secundária {argument name="benefit text" default="膳食纤维+花青素"} e uma pequena linha de peso líquido lendo 125克. Use gradação de cores azul frio, iluminação comercial nítida, destaques brilhantes na tampa plástica, estética de embalagem de supermercado premium, alto detalhamento, fotografia de produto realista combinada com design gráfico polido.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883187268_drjk2w_HGcTvn1boAASN-1.jpg" width="600" alt="Imagem Principal de E-commerce - Pôster Premium de Produto: Mirtilos - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [歸藏(guizang.ai)](https://x.com/op7418)
- **Fonte:** [Twitter Post](https://x.com/op7418/status/2046626506722746736#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14655)**

---

### No. 103: Imagem Principal de E-commerce - Look de Moodboard de Moda Minimalista

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Este prompt gera uma colagem de look editorial clean com estilo de marca, útil para quadros de inspiração de moda, posts em redes sociais e conceitos de guarda-roupa digital.

#### 📝 Prompt

```
Uma colagem de moda editorial clean em um fundo cinza-claro esbranquiçado com uma borda retangular preta fina, estilizada como um quadro de look de revista minimalista. Centralize o look em uma composição estilo flat lay com 5 itens de moda visíveis: uma jaqueta cropped com zíper frontal na cor {argument name="jacket color" default="vermelho carmesim"}, com gola pontuda e bainha elástica, posicionada levemente à esquerda e sobreposta; por baixo, uma blusa de tricô justa de manga longa e gola careca na cor {argument name="top color" default="branca"}, visível nos ombros e mangas; abaixo, uma saia evasê volumosa na altura da panturrilha em tom off-white com grandes poás pretos espaçados uniformemente; no canto inferior esquerdo, uma bolsa preta pequena e estruturada com alças curtas e uma textura sutil de crocodilo brilhante; no canto inferior direito, um par de sapatilhas Mary Jane pretas de bico quadrado com tiras largas e ferragens de ilhós prateadas. Adicione uma tipografia de fundo em cinza muito claro e grande, exibindo o texto {argument name="background brand text" default="MANGO"} esticado pelo meio, atrás das roupas. Coloque logotipos de marcas de moda menores em preto ao redor do layout: {argument name="top right logo" default="MANGO"} perto do canto superior direito do look, "Stradivarius" perto da bolsa e novamente perto dos sapatos, e "DOLCE & GABBANA" no canto inferior esquerdo, próximo à bainha da saia. A composição deve parecer equilibrada, chique e contemporânea, com iluminação de estúdio suave, sem sombras ou apenas sombras suaves e leves, bordas recortadas nítidas e uma estética polida de moodboard de moda para redes sociais.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105977_5pgeg0_HGbU2ZDbYAAEWX4.jpg" width="600" alt="Imagem Principal de E-commerce - Look de Moodboard de Moda Minimalista - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883105983_d1kr7t_HGbU2ZAbAAANO8q.jpg" width="600" alt="Imagem Principal de E-commerce - Look de Moodboard de Moda Minimalista - Image 2">
</div>

#### 📌 Detalhes

- **Autor:** [虎小象](https://x.com/hx831126)
- **Fonte:** [Twitter Post](https://x.com/hx831126/status/2046557123124027728#reversed-0)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14455)**

---

### No. 104: Imagem Principal de E-commerce - Mockup de Página de Produto de Teclado Mecânico

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Isto gera uma página de produto de e-commerce desktop polida para um teclado mecânico premium, adequada para vitrines de design de produto, conceitos de loja e mockups de UI.

#### 📝 Prompt

```
Crie uma página de detalhes de produto de e-commerce limpa e moderna para uma marca de teclado mecânico premium chamada {argument name="brand name" default="KeyForge"}, apresentada como um mockup de site desktop de alta fidelidade em um fundo branco com divisórias cinza-claras sutis e espaçamento generoso. O layout é uma cena de vitrine unificada com uma barra de navegação superior, uma barra de miniaturas de produto à esquerda, uma grande imagem principal do produto ao centro e um painel de informações de compra à direita. No cabeçalho, coloque o logotipo em negrito na extrema esquerda, depois 7 itens de navegação lendo “Keyboards”, “Switches”, “Keycaps”, “Accessories”, “Sale”, “Blog” e “Support”, e na extrema direita 3 ícones para busca, conta e carrinho, com um pequeno emblema de notificação preto mostrando “1” no carrinho. O produto principal exibido no centro é um teclado mecânico compacto de 75% fotografado de um ângulo frontal ligeiramente elevado em um palco cinza-claro, com uma carcaça de alumínio em prata, teclas brancas e cinzas, várias teclas de destaque em roxo lavanda e um botão de volume prateado no canto superior direito. A galeria vertical esquerda contém exatamente 5 miniaturas: 1 foto frontal do produto selecionada, 1 vista angular do teclado, 1 close-up do switch mecânico, 1 close-up da textura da tecla e 1 miniatura de vídeo escura com um ícone de reprodução circular. O painel de produto à direita inclui um pequeno emblema tipo pílula lendo “NEW”, um nome de produto grande e em negrito {argument name="product name" default="KeyForge K75 Pro"}, um subtítulo “75% Mechanical Keyboard”, uma linha de classificação de 5 estrelas com 4.8 e “(126 reviews)”, um preço grande e em negrito {argument name="price" default="$129.99"} seguido por um status verde “In Stock”, e uma breve descrição de duas frases sobre desempenho premium, design montado com junta (gasket-mounted), suporte a QMK/VIA e RGB. Abaixo disso, inclua um seletor de “Switch Type” com exatamente 4 botões tipo pílula rotulados “Cherry MX Red”, “Gateron Brown”, “Gateron Blue” e “TTC Gold Pink”, com o primeiro selecionado; um seletor de “Color” com exatamente 3 botões tipo pílula rotulados “White / Purple”, “Black / Gray” e “Navy / Blue”, com o primeiro selecionado; um menu suspenso de “Quantity” definido como “1”; um botão primário preto grande rotulado “Add to Cart” com um ícone de carrinho; e um botão secundário com contorno rotulado “Add to Wishlist” com um ícone de coração. Abaixo dos botões, mostre exatamente 3 destaques de serviço horizontais com ícones pequenos: “Free Shipping” com o subtexto “On orders over $99”, “30-Day Returns” com o subtexto “Hassle-free returns” e “2-Year Warranty” com o subtexto “Peace of mind”. Na área de conteúdo inferior, crie uma seção de duas colunas separada por linhas claras. À esquerda, há uma lista de abas verticais com exatamente 5 itens: “Overview” selecionado, depois “Specifications”, “What’s in the Box”, “Shipping & Returns” e “Reviews (126)”. À direita das abas, coloque uma grade de cartões de recursos brancos arredondados com exatamente 6 blocos de recursos em 2 linhas de 3, cada um com um ícone de linha simples, título em negrito e texto explicativo curto: “75% Layout”, “Gasket-Mounted”, “QMK/VIA Support”, “Hot-Swappable”, “RGB Backlighting” e “Premium Build”. Na extrema direita desta área inferior, adicione uma lista de especificações com exatamente 7 tópicos: “Layout: 75% (82 Keys)”, “Switch Type: Cherry MX Red”, “Mounting: Gasket-Mounted”, “Connectivity: USB-C (Wired)”, “Backlight: RGB, South-facing”, “Material: Aluminum Case” e “Dimensions: 322 x 135 x 42 mm”, além de um tópico final adicional “Weight: 1.25 kg”. Use uma estética de design de produto minimalista e refinada, espaçamento de UI realista, tipografia sem serifa limpa semelhante à Inter ou SF Pro, sombras suaves, cantos levemente arredondados, ícones monocromáticos e uma apresentação de eletrônicos de consumo no estilo startup polida.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776883104038_ocrytr_HGa_RiSa4AAdVM5.jpg" width="600" alt="Imagem Principal de E-commerce - Mockup de Página de Produto de Teclado Mecânico - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [轩辕的编程宇宙](https://x.com/xuanyuanzhifeng)
- **Fonte:** [Twitter Post](https://x.com/xuanyuanzhifeng/status/2046533787329458305#reversed-1)
- **Publicado:** 21 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14449)**

---

### No. 105: Imagem Principal de E-commerce - Skincare E-commerce Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858951_6ijm10_HGV6HyHaUAA68FT.jpg" width="600" alt="Imagem Principal de E-commerce - Skincare E-commerce Landing Page Mockup - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fonte:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-3)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14278)**

---

### No. 106: Imagem Principal de E-commerce - Men's Skincare Website Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756858185_6z7569_HGV6FtKbwAAK6L0.jpg" width="600" alt="Imagem Principal de E-commerce - Men's Skincare Website Landing Page Mockup - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fonte:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14277)**

---

### No. 107: Imagem Principal de E-commerce - Skincare E-commerce Landing Page

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756857625_xqz2ws_HGV6FtLboAAAw-a.jpg" width="600" alt="Imagem Principal de E-commerce - Skincare E-commerce Landing Page - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fonte:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-1)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14276)**

---

### No. 108: Imagem Principal de E-commerce - Beauty Product Landing Page Mockup

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756856340_hxgjgr_HGV6DSDasAAyJNp.jpg" width="600" alt="Imagem Principal de E-commerce - Beauty Product Landing Page Mockup - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [龍哉｜AI Ad Creator](https://x.com/ryuya__31)
- **Fonte:** [Twitter Post](https://x.com/ryuya__31/status/2046360073736495255#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14274)**

---

### No. 109: Imagem Principal de E-commerce - Fashion Collection Catalog Layout

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

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

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756838105_09bui0_HGWtW5LaEAE1ao5.jpg" width="600" alt="Imagem Principal de E-commerce - Fashion Collection Catalog Layout - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [妖精アーヤさん](https://x.com/aiehon_aya)
- **Fonte:** [Twitter Post](https://x.com/aiehon_aya/status/2046348182301683954#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14241)**

---

### No. 110: Imagem Principal de E-commerce - Green Tea Bottle Advertisement Poster

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

A vibrant promotional poster for a bottled green tea beverage, featuring dynamic water splashes, pricing badges, and feature callouts.

#### 📝 Prompt

```
{"type": "promotional advertisement poster for a bottled green tea beverage", "product": {"type": "clear plastic PET bottle filled with yellow-green tea", "label": "white label with green typography, featuring the product name '{argument name=\"product name\" default=\"清風茶\"}', subtitle '緑茶 Seifucha', and vertical text '国産茶葉使用' and '香り豊か、後味さわやか'"}, "background": "bright, fresh, sunlit outdoor atmosphere with dynamic water splashes wrapping around the bottle and vibrant green tea leaves", "layout": {"sections": [{"title": "headline", "position": "top-left", "text": "{argument name=\"main headline\" default=\"新発売\"}", "style": "large red text with a gold underline and a small green leaf accent"}, {"title": "catchphrase", "position": "mid-left", "text": "{argument name=\"catchphrase\" default=\"毎日に、すっきり。\"}", "style": "dark green text"}, {"title": "features", "position": "lower-left", "count": 2, "labels": ["国産茶葉使用", "香り豊か、後味さわやか"], "style": "white pill-shaped banners with green leaf icons"}, {"title": "price_badge", "position": "top-right", "text": "今だけ!! 特別価格 {argument name=\"price\" default=\"128円\"} (税込)", "style": "red circular sticker with white and yellow text"}, {"title": "promo_banner", "position": "bottom-left", "text": "期間限定のお得価格!", "style": "angled red ribbon with yellow and white text"}, {"title": "footer", "position": "bottom-edge", "text": "{argument name=\"footer text\" default=\"全国のコンビニ・スーパーで発売中\"}", "style": "solid green horizontal bar with a white shopping cart icon"}]}}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756805592_i18ymf_HGXbncza4AAGx8T.jpg" width="600" alt="Imagem Principal de E-commerce - Green Tea Bottle Advertisement Poster - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [AiRT🎥生成AI動画を創る人](https://x.com/AutoIntelliMode)
- **Fonte:** [Twitter Post](https://x.com/AutoIntelliMode/status/2046283113534542062#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14183)**

---

### No. 111: Imagem Principal de E-commerce - Custom Building Block Set Photography

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Generates a photorealistic image of a custom toy building set with its box, assembled house, vehicle, and minifigures on a table.

#### 📝 Prompt

```
A photorealistic amateur photograph of a custom building block set resting on a light wood grain table in a living room. In the background stands a large product box with a red logo reading "{argument name="brand name" default="BRICKLY"} BUILDING SETS". The box features text reading "8+", "540 PCS", "5 FIGURES", and the main large title "{argument name="set title" default="WATTERSON FAMILY HOUSE"}". A red circular badge on the box reads "CUSTOM SET FAN DESIGN", and the box art depicts the house and characters under a blue sky. In the foreground sits the fully assembled block model of a {argument name="house color" default="blue"} two-story suburban house with a brown roof, white porch, red steps, a white picket fence, and a blocky green tree. To the left of the house is a built block model of a {argument name="car color" default="pink"} station wagon. Standing in a row in front of the house are exactly 5 custom block minifigures: a blue cat in tan pants, an orange fish with legs, a tall pink rabbit in a white shirt and tie, a blue cat in a white shirt, and a small pink rabbit in an orange dress. The background is a slightly blurred living room with a grey sofa and white blinds.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756783011_qg8mrm_HGWGG7TWAAELi83.jpg" width="600" alt="Imagem Principal de E-commerce - Custom Building Block Set Photography - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [pozitiv4ik](https://x.com/Gc_qube)
- **Fonte:** [Twitter Post](https://x.com/Gc_qube/status/2046189202488881427#reversed-0)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14148)**

---

### No. 112: Imagem Principal de E-commerce - Luxury Cosmetic Web Advertisement

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Generates a high-end cosmetic product advertisement with elegant typography, a glowing background, and a call-to-action button.

#### 📝 Prompt

```
A luxurious cosmetic product advertisement featuring a single elegant glass jar with a shiny gold lid resting on a round, light-colored marble slab. The jar has gold text reading {argument name="brand name" default="LUMIÉRE"} and {argument name="product type" default="MOISTURE RICH CREAM"} with "AGING CARE*" below it. The background consists of soft, draped, shimmering champagne-colored silk fabric with delicate white flowers on the left. The lighting is warm, ethereal, and sun-drenched with soft bokeh. At the top center, elegant dark brown Japanese typography reads {argument name="main headline" default="肌に、静かな贅沢を。"} above a small decorative gold divider and the text {argument name="subheadline" default="高保湿×エイジングケア*"}. To the right of the jar, a thin gold circle contains Japanese text meaning 'With dense moisture, high-quality firmness and radiance'. At the bottom center is a dark rectangular call-to-action button with a thin gold border containing the text {argument name="button text" default="詳しく見る"} and a right-pointing chevron. In the bottom right corner, tiny fine print contains Japanese text meaning '*Care according to age'.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756828857_3tbi8h_HGU7yv1bgAARcmr.jpg" width="600" alt="Imagem Principal de E-commerce - Luxury Cosmetic Web Advertisement - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ぱんちゃん🍞](https://x.com/panchaaan_2)
- **Fonte:** [Twitter Post](https://x.com/panchaaan_2/status/2046107762686652666#reversed-2)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14225)**

---

### No. 113: Imagem Principal de E-commerce - E-commerce Product Page Generator

![Language-ZH](https://img.shields.io/badge/Language-ZH-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

A detailed prompt for creating an e-commerce product detail page for a fictional item, showing different views and features.

#### 📝 Prompt

```
A {argument name="platform" default="Taobao"} product detail page for {argument name="robot model" default="T-800 robot"}, displaying: front, side, and back three-view drawings of the robot, product price, product details, functions, and usage scenarios, etc.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772675_jeajpn_HGUGld9bAAAUe_s.jpg" width="600" alt="Imagem Principal de E-commerce - E-commerce Product Page Generator - Image 1">
</div>

##### Image 2

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772449_903tnx_HGUGmoLasAAKY9V.jpg" width="600" alt="Imagem Principal de E-commerce - E-commerce Product Page Generator - Image 2">
</div>

##### Image 3

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756772471_rp1k5s_HGUGnuCacAA9ROi.jpg" width="600" alt="Imagem Principal de E-commerce - E-commerce Product Page Generator - Image 3">
</div>

##### Image 4

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776756773769_y74wyh_HGUGoqGaEAAmaAp.jpg" width="600" alt="Imagem Principal de E-commerce - E-commerce Product Page Generator - Image 4">
</div>

#### 📌 Detalhes

- **Autor:** [阿兰AI](https://x.com/alanlovelq)
- **Fonte:** [Twitter Post](https://x.com/alanlovelq/status/2046048929490612464)
- **Publicado:** 20 de abril de 2026
- **Idiomas:** zh

**[👉 Experimente agora →](https://gptimage2api.net/?id=14134)**

---

### No. 114: Imagem Principal de E-commerce - Mockup de Interface de E-commerce para Transmissão ao Vivo

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma interface móvel de compras via transmissão ao vivo apresentando uma celebridade vendendo um produto fictício, completa com sobreposição de chat e elementos de interface (UI).

#### 📝 Prompt

```
{
  "type": "mockup de interface de e-commerce para transmissão ao vivo móvel",
  "subject": {
    "person": "Elon Musk",
    "clothing": "camiseta preta com o logotipo da SPACEX",
    "pose": "gesticulando para a câmera com as duas mãos, explicando entusiasticamente",
    "watermark": "@Proof AI"
  },
  "background": {
    "setting": "tela de exibição grande",
    "image": "paisagem de Marte com o foguete Starship e habitats em cúpula",
    "text": [
      "SPACEX",
      "{argument name=\"background title\" default=\"Projeto de Colonização de Marte\"}"
    ]
  },
  "ui_layout": {
    "header": {
      "broadcaster_info": {
        "name": "{argument name=\"broadcaster name\" default=\"ElonMusk\"}",
        "stats": "758 mil curtidas nesta live",
        "follow_button": "Seguir"
      },
      "viewer_stats": {
        "avatars_count": 3,
        "text": "100 mil+",
        "close_button": "X"
      },
      "tags": [
        "1º lugar no ranking de vendas",
        "Mais lives >"
      ]
    },
    "product_card": {
      "position": "meio-direita",
      "status": "Em destaque",
      "image": "habitats em cúpula em Marte",
      "title": "{argument name=\"product title\" default=\"Pacote básico de colonização de Marte\"}",
      "price": "{argument name=\"product price\" default=\"¥99,00\"}",
      "action_button": "Comprar"
    },
    "chat_overlay": {
      "position": "inferior-esquerda",
      "join_alert": "Sonhador entrou na live",
      "messages_count": 7,
      "messages": [
        "{argument name=\"top chat message\" default=\"Sonhador: Apoio o Musk!! 🚀\"}",
        "Irmão de Marte: Quanto custa por pessoa?",
        "Fã de tecnologia: Muito legal! Quero ir para Marte!",
        "O futuro chegou: Como faço para me inscrever?",
        "Foguetinho: 🌹🌹🌹",
        "Invencível do universo: Explique os detalhes",
        "Lenda: O Musk é demais! 👍👍👍"
      ]
    },
    "bottom_action_bar": {
      "input_placeholder": "Diga algo...",
      "icons_count": 4,
      "icons": ["carrinho de compras", "caixa de presente", "planeta de coração", "sinal de mais"]
    },
    "floating_reactions": {
      "position": "inferior-direita",
      "elements": "pilha de corações flutuantes, polegares para cima e emojis de risada"
    }
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776668161813_cyei4t_HGRO3rxaEAAMrny.jpg" width="600" alt="Imagem Principal de E-commerce - Mockup de Interface de E-commerce para Transmissão ao Vivo - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [Proof · AI Productivity](https://x.com/JCutcut47692)
- **Fonte:** [Twitter Post](https://x.com/JCutcut47692/status/2045846999032008876#reversed-0)
- **Publicado:** 19 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13557)**

---

### No. 115: Imagem Principal de E-commerce - Foto Comercial de Bebida de Verão na Praia

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma cena refrescante de fotografia de produto com uma bebida em lata e um copo na praia, com texto do produto e frase de efeito no céu personalizáveis.

#### 📝 Prompt

```
Uma foto comercial de produto, brilhante e veranil, apresentando uma bebida refrescante sobre uma mesa de madeira desgastada. Em primeiro plano, com foco nítido, há 1 copo alto cheio de uma bebida gelada, dourada e borbulhante, decorada com 1 fatia de limão e um ramo de alecrim, ao lado de 1 lata de alumínio prateada coberta por condensação fria. A lata exibe com destaque o texto em inglês {argument name="product name" default="TOKYO HIGHBALL"} abaixo de um pequeno logotipo de estrela dourada, apresentando um gráfico da própria bebida e o texto em japonês "アルコール分 7%" próximo à base. À direita da lata, 2 fatias de limão repousam sobre a mesa. Ao fundo, suavemente desfocado, desenrola-se uma cena de praia ensolarada com águas azul-turquesa cintilantes e um céu azul claro. Em pé, à esquerda, ao fundo, está 1 jovem de cabelos castanhos longos, vestindo uma blusa branca sem mangas e uma saia azul clara, olhando para o oceano. Flutuando elegantemente no céu acima da cena está o texto em japonês {argument name="catchphrase" default="夏、これがいい。"}. A iluminação geral é radiante e convidativa, com bokeh cintilante e reflexos de lente que enfatizam a atmosfera nítida, fria e refrescante de um dia de verão perfeito.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699438032_wdl3cx_HGMEwCsaoAAQ75x.jpg" width="600" alt="Imagem Principal de E-commerce - Foto Comercial de Bebida de Verão na Praia - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [ハイボールながたにえん｜CHO（最高ハイボール責任者）｜カルチャープレナー](https://x.com/highball_cho)
- **Fonte:** [Twitter Post](https://x.com/highball_cho/status/2045484111171915887#reversed-0)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14023)**

---

### No. 116: Imagem Principal de E-commerce - Conceito de Grade Publicitária de 4 Painéis

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma grade 2x2 de anúncios japoneses distintos cobrindo as indústrias de cuidados com a pele, alimentação, viagens e tecnologia.

#### 📝 Prompt

```
{
  "type": "grade de banner publicitário 2x2",
  "layout": "4 quadrantes distintos, cada um apresentando um anúncio de um setor diferente",
  "quadrants": [
    {
      "position": "superior esquerdo",
      "industry": "cuidados com a pele",
      "visuals": "mulher asiática tocando a bochecha, gotas de água flutuantes, frasco pump branco",
      "brand": "BALANCÉE",
      "copy": {
        "headline": "{argument name=\"skincare headline\" default=\"素肌が、目覚める。\"}",
        "subheadline": "Para uma nova versão de mim, cheia de transparência.",
        "features_count": 3,
        "features_labels": ["Alta hidratação", "Prevenção de irritação", "Cuidado clareador*"]
      }
    },
    {
      "position": "superior direito",
      "industry": "restaurante",
      "visuals": "close de espaguete à bolonhesa com queijo ralado e salsinha, iluminação dramática",
      "brand": "Trattoria Luce",
      "copy": {
        "headline": "{argument name=\"food headline\" default=\"このパスタ、事件級。\"}",
        "badge": "Tempo limitado",
        "description": "Bolonhesa de Wagyu preto ~Aroma de trufas~"
      }
    },
    {
      "position": "inferior esquerdo",
      "industry": "viagens",
      "visuals": "mulher com mochila de frente para um lago cênico nas montanhas, luz do dia brilhante",
      "brand": "NATURE JOURNEY",
      "copy": {
        "headline": "{argument name=\"travel headline\" default=\"わたしを、解き放つ旅へ。\"}",
        "subheadline": "Na natureza, seu coração ganha vida.",
        "script": "Encontre sua liberdade.",
        "banner_details": ["Campanha especial de início de verão", "1 de jun (SÁB) - 30 de jun (DOM)", "Até 20% OFF", "Muitos planos especiais apenas agora!"]
      }
    },
    {
      "position": "inferior direito",
      "industry": "aplicativo SaaS",
      "visuals": "smartphone exibindo uma interface de aplicativo de gerenciamento de tarefas com 4 itens de agenda",
      "brand": "{argument name=\"app brand name\" default=\"Taskme\"}",
      "copy": {
        "headline": "{argument name=\"app headline\" default=\"タスク管理を、もっとシンプルに、スマートに。\"}",
        "circle_badge": "Projete o seu dia.",
        "features_count": 3,
        "features_labels": ["Operação intuitiva", "Compartilhável com a equipe", "Acesso de qualquer lugar"],
        "bottom_banner": "Teste gratuito de 7 dias disponível!"
      }
    }
  ]
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697120210_cklnnc_HGLsJUZbMAACfhY.jpg" width="600" alt="Imagem Principal de E-commerce - Conceito de Grade Publicitária de 4 Painéis - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [きつね┃45歳までにセミリタイアしたかったけど諦めた](https://x.com/kitune_fire45)
- **Fonte:** [Twitter Post](https://x.com/kitune_fire45/status/2045456827618627863#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13928)**

---

### No. 117: Imagem Principal de E-commerce - Mockup de Interface de Livestream de E-commerce

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma interface de livestream de e-commerce chinesa altamente detalhada, apresentando um apresentador, caixas de produtos, chat ao vivo e sobreposições promocionais.

#### 📝 Prompt

```
{
  "type": "mockup de captura de tela de livestream de e-commerce",
  "scene": {
    "subject": "{argument name=\"main subject\" default=\"homem caucasiano parecido com Sam Altman\"}",
    "clothing": "suéter gola careca verde-escuro",
    "action": "segurando uma caixa de produto preta em uma mão e apontando para ela com a outra",
    "setting": "estúdio escuro com um microfone à esquerda, texto 'AI' sutil ao fundo",
    "props": [
      "caneca preta com logotipo branco da OpenAI",
      "pilha de 4 caixas de produto pretas à direita"
    ]
  },
  "product_design": {
    "box_color": "preto",
    "logo": "asterisco ou sunburst laranja",
    "text": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}"
  },
  "ui_overlays": {
    "top_left_product_info": {
      "brand_tag": "Loja Oficial Anthropic",
      "title": "{argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "subtitle": "{argument name=\"main headline\" default=\"Raciocínio mais forte · Inteligência superior\"}",
      "sub_subtitle": "O modelo mais poderoso: Opus 4.7 lançado!",
      "bullet_points_count": 3,
      "bullet_points": ["Capacidade de raciocínio superior", "Pico de desempenho em código", "Resolve tarefas complexas facilmente"]
    },
    "top_right_live_status": {
      "viewer_info": "Ao vivo | 528 mil espectadores",
      "promo_banner": "Oferta exclusiva da live: Desconto por tempo limitado · Não perca",
      "countdown": "Contagem regressiva 00:09:47"
    },
    "middle_right_price_card": {
      "header": "Preço exclusivo da live para {argument name=\"product name\" default=\"Claude Opus 4.7\"}",
      "price_currency": "¥",
      "price_value": "{argument name=\"promotional price\" default=\"0.47\"}",
      "price_unit": "/por milhão de tokens",
      "original_price": "Preço original: ¥1.89",
      "button": "Comprar agora"
    },
    "bottom_left_chat": {
      "message_count": 9,
      "input_box_placeholder": "Diga algo..."
    },
    "bottom_right_banner": {
      "headline": "Recomendado por Altman! Escolha o Claude Opus 4.7",
      "subheadline": "Mais inteligente · Mais seguro · Mais confiável",
      "feature_tags_count": 4,
      "feature_tags": ["Raciocínio poderoso", "Ferramenta de código", "Seguro e confiável", "Resposta ultrarrápida"]
    },
    "floating_elements": [
      {
        "type": "sticker",
        "position": "meio à direita sobre as caixas de produto",
        "text": "{argument name=\"sticker text\" default=\"O modelo de IA mais forte da história!\"}"
      }
    ]
  }
}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699419558_ef89oe_HGLH29jbcAAHELr.jpg" width="600" alt="Imagem Principal de E-commerce - Mockup de Interface de Livestream de E-commerce - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [程序员Left](https://x.com/coder_left)
- **Fonte:** [Twitter Post](https://x.com/coder_left/status/2045416935106773045#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13995)**

---

### No. 118: Imagem Principal de E-commerce - Transformação de Rótulo para Sopa de Frango com Ervas

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Transforma um cartaz promocional de frango em um rótulo de produto detalhado com uma cesta de ingredientes herbais específicos e texto de instruções.

#### 📝 Prompt

```
Usando REFERENCE_0 como estilo base e preservando a ilustração central do frango, transforme a imagem em um rótulo de embalagem de produto para uma mistura de sopa de ervas. Mova o frango para o lado direito. Substitua o texto superior por um título grande e em negrito com efeito de pincel preto {argument name="main headline" default="元气祛湿 鸡煲汤包"} e um subtítulo menor {argument name="subtitle" default="吃山林土货 味道当然好!"}. No lado esquerdo, adicione uma nova cesta de vime contendo exatamente 6 pilhas distintas de ingredientes: pedaços de raízes lenhosas, cubos brancos, raízes marrons fatiadas em rodelas, soja amarela, tiras de casca de laranja seca e tâmaras vermelhas escuras. Anexe 6 pequenas etiquetas retangulares marrons com texto branco a esses ingredientes. Abaixo do frango, adicione um selo circular laranja contendo o texto {argument name="ingredients list" default="内含有:五指毛桃、茯苓、土茯苓、黄豆、陈皮、红枣"}. Na parte inferior, crie uma faixa retangular laranja sólida apresentando um ícone de panela, o texto {argument name="usage instructions" default="用法:把汤料清洗干净放入锅中，加入姜片煮20分钟，后加入鸡肉再煮20分钟即可。"} e um slogan secundário {argument name="bottom slogan" default="天然好料 滋补好汤"}.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699418305_yo64pw_HGLE6HSaEAEgf3p.jpg" width="600" alt="Imagem Principal de E-commerce - Transformação de Rótulo para Sopa de Frango com Ervas - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [渣猫看世界🦭/acc](https://x.com/xzjken)
- **Fonte:** [Twitter Post](https://x.com/xzjken/status/2045414765640786184#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=13993)**

---

### No. 119: Imagem Principal de E-commerce - Carro esportivo e avião comercial em um hangar

![Language-EN](https://img.shields.io/badge/Language-EN-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Gera uma imagem fotorrealista de um carro esportivo estacionado em frente a um avião comercial dentro de um hangar reflexivo.

#### 📝 Prompt

```
Uma fotografia comercial fotorrealista de alta resolução de um {argument name="car model and color" default="carro esportivo Alpine A110 R azul brilhante"} estacionado em primeiro plano dentro de um enorme hangar de aeronaves. O carro apresenta um capô de fibra de carbono preto, teto preto, rodas de liga leve pretas e uma placa dianteira com os dizeres "{argument name="license plate text" default="A110 R"}". Diretamente atrás do carro, dominando o fundo, está um {argument name="airplane model" default="avião comercial Airbus A320 branco"} com a cauda azul. O hangar possui um piso de concreto altamente polido e reflexivo que espelha o carro e o avião. À esquerda, uma placa na parede de metal diz "{argument name="hangar sign text" default="HANGAR 05 MAINTENANCE"}". As portas do hangar estão bem abertas, revelando um céu nublado e brilhante e uma paisagem urbana distante. A iluminação é suave e cinematográfica, destacando as curvas aerodinâmicas elegantes de ambos os veículos.
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776699449748_uoimri_HGK8gRZXgAAWXH2.jpg" width="600" alt="Imagem Principal de E-commerce - Carro esportivo e avião comercial em um hangar - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [nazca alwave](https://x.com/AlwaveNazca)
- **Fonte:** [Twitter Post](https://x.com/AlwaveNazca/status/2045404499066384847#reversed-1)
- **Publicado:** 18 de abril de 2026
- **Idiomas:** en

**[👉 Experimente agora →](https://gptimage2api.net/?id=14043)**

---

### No. 120: Imagem Principal de E-commerce - Mockup Realista de Mercadorias de VTuber

![Language-JA](https://img.shields.io/badge/Language-JA-blue)
![Raycast](https://img.shields.io/badge/🚀-Raycast_Friendly-purple)

#### 📖 Descrição

Um prompt para o GPT-Image2 gerar fotografias realistas em live-action de produtos de fãs padrão de VTuber.

#### 📝 Prompt

```
Crie {argument name="items" default="produtos de fãs"} para um {argument name="character type" default="VTuber"} padrão em {argument name="style" default="live-action"}
```

#### 🖼️ Imagens geradas

##### Image 1

<div align="center">
<img src="https://cms-assets.youmind.com/media/1776697074973_2uc2i5_HGJMooRbwAAzXOo.jpg" width="600" alt="Imagem Principal de E-commerce - Mockup Realista de Mercadorias de VTuber - Image 1">
</div>

#### 📌 Detalhes

- **Autor:** [WTR](https://x.com/wtry1102)
- **Fonte:** [Twitter Post](https://x.com/wtry1102/status/2045281877452575125)
- **Publicado:** 17 de abril de 2026
- **Idiomas:** ja

**[👉 Experimente agora →](https://gptimage2api.net/?id=13868)**

