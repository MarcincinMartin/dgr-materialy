## Design a grafika, 1. IT

- [Principy grafického designu](#principy-grafického-designu)
  - [🎨 Barvy](#-barvy)
    - [🏳️‍🌈 Barevné prostory](#️-barevné-prostory)
      - [**RGB**](#rgb)
      - [**HEX**](#hex)
      - [**CMYK**](#cmyk)
      - [**HSL**](#hsl)
    - [🎨 Barevné palety](#-barevné-palety)
      - [**Monochromatická paleta**](#monochromatická-paleta)
      - [**Analogická paleta**](#analogická-paleta)
      - [**Doplňková paleta**](#doplňková-paleta)
  - [🔠 Typografie](#-typografie)
    - [🅰️ Font a jeho vlastnosti](#️-font-a-jeho-vlastnosti)
      - [Patkové _serif_](#patkové-serif)

# Principy grafického designu

## 🎨 Barvy

### 🏳️‍🌈 Barevné prostory

> - **RGB**
> - **HEX**
> - **CMYK**
> - **HSL**
> - [▶️ The Slow Mo Guys: How a TV Works in Slow Motion](https://www.youtube.com/watch?v=3BJU2drrtCM&t=601s)

#### **RGB**

- Red, Green, Blue
- **aditivní** barevný prostor
- skládání světla
- **256** hodnot pro každou barvu
- **16 777 216** barev

_Příklady:_

- `rgb(0, 0, 0)` = černá
- `rgb(255, 255, 255)` = bílá
- `rgb(100, 100, 100)` = světle šedá
- `rgb(255, 0, 0)` = červená
- `rgb(0, 255, 0)` = zelená
- `rgb(0, 0, 255)` = modrá

**_Hodnoty odpovídají svítivosti subpixelů v displeji, monitoru, ..._**

---

#### **HEX**

- Jiný zápis RGB
- Čísla v hexadecimálním tvaru
- Často v CSS

_Příklady:_

- `#000000` = černá
- `#FFFFFF` = bílá
- `#646464` = světle šedá
- `#FF0000` = červená
- `#00FF00` = zelená
- `#0000FF` = modrá

---

#### **CMYK**

- Cyan, Magenta, Yellow, Black (Key)
- **subtraktivní** barevný prostor
- skládání barev

_Příklady:_

- `cmyk(0, 0, 0, 0)` = bílá
- `cmyk(0, 0, 0, 100%)` = černá
- `cmyk(100%, 0, 0, 0)` = cyan
- `cmyk(0, 100%, 0, 0)` = magenta
- `cmyk(0, 0, 100%, 0)` = žlutá

**_Hodnoty odpovídají množství toneru._**

---

#### **HSL**

- Hue, Saturation, Lightness
- Barva, sytost, světlost
- `hsl(240deg, 100%, 50%)`

---

### 🎨 Barevné palety

> - **Monochromatická**
> - **Analogická**
> - **Doplňková**
> - [Paletton](https://paletton.com/)
> - [▶️ Beginning Graphic Design: Color](https://www.youtube.com/watch?v=_2LLXnUdUIc)

_Další zdroje palet:_

- [Paletton.com](https://paletton.com/)
- [ColorDesigner.io](https://colordesigner.io/)
- [Coolors](https://coolors.co/)
- [ColorSpace](https://mycolor.space/)
- [Colorhunt](https://colorhunt.co/)
- [ColorPalettes.Earth](https://colorpalettes.earth/)
- [HueMint](https://huemint.com/)
- [CSS Gradient](https://cssgradient.io/)
- [Parametric Mixer](https://colormixer.web.app/02332971ff623007ff9bc9505a440301ffff7c5f55610300/Sunset)
- [Palettte.](https://palettte.app/)
- [Grabient](https://www.grabient.com/)
- [Easing Gradients](https://larsenwork.com/easing-gradients/#editor)

---

<div style="height: 20px; background: linear-gradient(
  to right, 
  hsl(88, 57%, 91%) 0%,
  hsl(88, 57%, 91%) 15%,
  hsl(87, 40%, 80%) 15%,
  hsl(87, 40%, 80%) 30%,
  hsl(86, 30%, 70%) 30%,
  hsl(86, 30%, 70%) 45%,
  hsl(84, 21%, 57%) 45%, 
  hsl(84, 21%, 57%) 60%,
  hsl(82, 18%, 51%) 60%,
  hsl(82, 18%, 51%) 75%,
  hsl(83, 21%, 42%) 75%,
  hsl(83, 21%, 42%) 100%
);" ></div>

#### **Monochromatická paleta**

- Odstíny jedné barvy.
- V prostoru HSL stejné _H - hue_.

_Příklad palety:_

- `hsl(88, 57%, 91%)`,
- `hsl(87, 40%, 80%)`,
- `hsl(86, 30%, 70%)`,
- `hsl(84, 21%, 57%)`,
- `hsl(82, 18%, 51%)`,
- `hsl(83, 21%, 42%)`.

---

<div style="height: 20px; background: linear-gradient(
  to right,
  hsl(349, 98%, 24%) 0%,
  hsl(349, 98%, 24%) 20%,
  hsl(39, 92%, 59%) 20%,
  hsl(39, 92%, 59%) 40%,
  hsl(29, 72%, 50%) 40%,
  hsl(29, 72%, 50%) 60%,
  hsl(16, 69%, 51%) 60%,
  hsl(16, 69%, 51%) 80%,
  hsl(3, 67%, 46%) 80%,
  hsl(3, 67%, 46%) 100%
);">
</div>

#### **Analogická paleta**

- Odstíny barev vedle sebe v barevném kruhu.
- V prostoru HSL podobné hodnoty _H - hue_.

_Příklad palety:_

- `hsl(349, 98%, 24%)`,
- `hsl(39, 92%, 59%)`,
- `hsl(29, 72%, 50%)`,
- `hsl(16, 69%, 51%)`,
- `hsl(3, 67%, 46%)`.

---

<div style="height: 20px; background: linear-gradient(
  to right,
  hsl(349, 98%, 24%) 0%,
  hsl(349, 98%, 24%) 20%,
  hsl(349, 50%, 12%) 20%,
  hsl(349, 50%, 12%) 40%,
  hsl(169, 98%, 60%) 40%,
  hsl(169, 98%, 60%) 60%,
  hsl(169, 98%, 24%) 60%,
  hsl(169, 98%, 24%) 80%,
  hsl(169, 68%, 12%) 80%,
  hsl(169, 68%, 12%) 80%
);">
</div>

#### **Doplňková paleta**

- Barvy naproti sobě v barevném kruhu.
- V prostoru HSL rozdíl v hodnotě _H - hue_ přibližně 180°.

_Příklad palety:_

- `hsl(349, 98%, 24%)`,
- `hsl(349, 50%, 12%)`,
- `hsl(169, 98%, 60%)`,
- `hsl(169, 98%, 24%)`,
- `hsl(169, 68%, 12%)`.

---

## 🔠 Typografie

### 🅰️ Font a jeho vlastnosti

> - **Patkové** _serif_
> - **Bezpatkové** _sans-serif_
> - **Neproporciální** _monospace_
> - **VERZÁLKY** a **minusky**
> - **Řez** a **Stín**
> - **Řádkování** _line spacing_
> - **Prokládání** _letter spacing_
> - [▶️ Beggining Graphics Design: Typography](https://www.youtube.com/watch?v=sByzHoiYFX0)
> - [Google Fonts](https://fonts.google.com/)

---

#### Patkové _serif_

- **Patky** na koncích písmen
- tradičnější vzhled
- snadnější čtení na papíře

_Příklad: Times New Roman_

>  <p style="font-family: 'Times New Roman', serif;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum libero autem consequatur officiis et quidem repellendus temporibus recusandae numquam? Asperiores nemo odio accusamus? Voluptates veritatis alias perspiciatis ea inventore expedita.</p>
