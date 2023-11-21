## Webové aplikace, 1. IT

- [🌐 Odkazy](#-odkazy)
- [🪛 Nástroje](#-nástroje)
  - [🖥️ Vývojové prostředí](#️-vývojové-prostředí)
    - [Visual Studio Code](#visual-studio-code)
    - [Prettier](#prettier)
    - [W3C Web Validator](#w3c-web-validator)
    - [Emmet](#emmet)
  - [🌐 Internetový prohlížeč](#-internetový-prohlížeč)
    - [Google Chrome](#google-chrome)
  - [⌨️ Klávesové zkratky](#️-klávesové-zkratky)
    - [Obecné (Windows)](#obecné-windows)
    - [Prohlížeč](#prohlížeč)
  - [💾 Správa verzí](#-správa-verzí)
    - [Git](#git)
    - [GitHub](#github)

# 🌐 Odkazy

- [HTML Standard](https://html.spec.whatwg.org/)
- [W3Schools](https://www.w3schools.com/)
- [MDN Web Docs](https://developer.mozilla.org/en-US/)
- [Can I Use](https://caniuse.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- [GitHub](http://github.com)
- [Můj web](http://marcincin.epsilon.spstrutnov.cz/vyuka/1itwap/)

# 🪛 Nástroje

## 🖥️ Vývojové prostředí

### [Visual Studio Code](https://code.visualstudio.com/)

> **_Visual Studio Code_** je editor, který budeme používat po celou dobu studia.
> Je zdarma, multiplatformní a má spoustu rozšíření.

1. Stáhněte si [VS Code](https://code.visualstudio.com/).
2. Spusťte instalaci.
3. Po instalaci spusťte VS Code.

> **Tip:**
> Na úvodní stránce VS Code je možné si vybrat barevné téma.  
> Já používám výchozí, pokud vyberete jiné, budete mít jinak zvýrazněný kód, barvy budou mít jiný význam.

---

### [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

> **_Prettier_** je rozšíření, které nám pomůže formátovat kód.
> Je zdarma a multiplatformní.

1. V levém menu klikněte na Extensions. _(`Ctrl`+`Shift`+`X`)_
2. Do vyhledávacího pole napište **_prettier_**.
3. Vyberte výsledek **_Prettier - Code formatter_**.
4. Nainstalujte rozšíření.
5. Otevřte nastaení VS Code. _(`Ctrl`+`,`)_
6. Do vyhledávacího pole napište **_format_**.
7. Zatrhněte políčko **_Format On Save_**.
8. V seznamu **_default formater_** vyberte **_Prettier - Code formatter_**.

> **Tip:**
> V nastavení je možné zvolit _Auto Save._

---

### [W3C Web Validator](https://marketplace.visualstudio.com/items?itemName=Umoxfo.vscode-w3cvalidation)

> **_Validator_** je nástroj, který nám pomůže zkontrolovat, zda je náš kód validní, tj. splňuje (některé) požadavky specifikace.

1. V levém menu klikněte na Extensions. _(`Ctrl`+`Shift`+`X`)_
2. Do vyhledávacího pole napište **_validator_**.
3. Vyberte výsledek **_W3C Web Validator_**.
4. Nainstalujte rozšíření.

> **Tip:**
> V nastavení je možné zapnout _Validate on Save_.

---

### [Emmet](https://marketplace.visualstudio.com/items?itemName=emmetio.emmet)

> **_Emmet_** je rozšíření, které nám pomůže psát HTML a CSS rychleji.
> Není nutné ho instalovat, je součástí VS Code.

Některé příklady:

- `!` => HTML šablona
- `div` => `<div></div>`
- `div#id` => `<div id="id"></div>`
- `div.class` => `<div class="class"></div>`
- `ul>li*3` => `<ul><li></li><li></li><li></li></ul>`

---

## 🌐 Internetový prohlížeč

### [Google Chrome](https://www.google.com/intl/cs_CZ/chrome/)

- Freeware
- Vývojářské nástroje (DevTools) pomocí `F12`

## ⌨️ Klávesové zkratky

### Obecné (Windows)

- `Ctrl`+`C` => Zkopírovat
- `Ctrl`+`V` => Vložit
- `Ctrl`+`X` => Vyjmout
- `Ctrl`+`Z` => Zpět
- `Ctrl`+`Y` => Vpřed
- `Ctrl`+`S` => Uložit
- `Alt`+`Tab` => Přepínání oken
- `Alt`+`F4` => Zavřít okno
- `Ctrl`+`Tab` => Přepínání panelů
- `Ctrl`+`F4` => Zavřít panel
- `Ctrl`+ `0` => Nastavit velikost zobrazení na 100%

### Prohlížeč

- `F5` => Obnovit stránku
- `Shift`+`F5` => Obnovit stránku (ignoruje cache)
- `F12` => Otevřít vývojářské nástroje

## 💾 Správa verzí

### [Git](https://git-scm.com/)

> **_Git_** je nástroj, který nám umožňuje spravovat zdrojové kódy a jejich verze.

1. Stáhněte si [Git](https://git-scm.com/).
2. Spusťte instalaci.
3. Restartujte VS Code.

### [GitHub](http://github.com)

> **_GitHub_** je webová služba používající Git.

1. Vytvořte si účet na [GitHubu](http://github.com).
2. Připojte se ke třídě a zadání pomocí odkazu v MS Teams.
3. Otevřete odkaz "Open in VS Code".
4. Odsouhlaste instalaci rozšíření.
5. Otevřete terminál. _(`Ctrl`+`;`)_
6. Zadejte postupně:
   ```powershell
    git config --global user.name "uživatelské jméno na GitHub"
    git config --global user.email "email na GitHub"
   ```
7. Ve škole navíc zadejte:
   ```powershell
    git config --global http.proxy "adresa proxy"
   ```
8. Otevřete rozšíření GitHub _(logo kočky)_.
9. Přihlaste se.
10. Otevřete zadání.

---
