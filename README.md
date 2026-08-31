# Mashruuca 1 — Clipboard Landing Page

![Design preview for the Clipboard landing page coding challenge](preview.jpg)

## Ku soo dhawoow 👋

Kani waa **Mashruuca Koowaad** ee koorsada Frontend-ka. Waxaad ku dhisi doontaa
**landing page** buuxa adigoo isticmaalaya **HTML** iyo **CSS** oo keliya.

Naqshadda (design) waa mid la siiyay. Shaqadaadu waa inaad code-ka ku dhistid si ay
u eg tahay naqshadda ugu dhow ee suurtogal ah — mobile iyo desktop labadaba.

> **Waxa lagaa filayo inaad horay u taqaan:** HTML tags-ka aasaasiga ah,
> CSS selectors, box model, iyo waxoogaa Flexbox ah. Wixii kale mashruucaan
> ayaad ku baran doontaa.

---

## 🎯 Hadafka mashruuca

Marka aad dhammayso, waa inaad awoodid inaad:

- Qaadid naqshad (design) oo aad u beddeshid HTML **semantic** ah
- Isticmaashid **Flexbox** iyo **CSS Grid** si aad layout u dhistid
- Dhistid bog **responsive** ah oo si fiican uga muuqda mobile iyo desktop
- Ku darid **hover states** dhammaan link-yada iyo button-nada
- Isticmaashid **Git** iyo **GitHub**: fork, clone, commit, push, pull request

---

## 🔗 Link-yada muhiimka ah

| Waxa uu yahay                                               | Link                                                                                                                                 |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Figma design** (halkan ka eeg naqshadda oo dhammaystiran) | [Fur Figma](https://www.figma.com/design/SJApZMstnaLb0F9qeEjDdZ/clipboard-landing-page--Community-?node-id=0-2&t=hsp0aBFuTiZL0zeN-0) |
| **Challenge-ka asalka ah** ee Frontend Mentor               | [Fur Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9)                      |

> 💡 **Talo:** Figma-da ka eeg cabbirrada saxda ah ee `font-size`, `padding`,
> `margin` iyo `color`. Haddaadan Figma isticmaalin karin, sawirrada ku jira
> galka `design/` ayaa kugu filan — laakiin waxaad u baahan doontaa inaad
> waxoogaa qiyaasto (best judgment).

---

## 📁 Faylasha mashruuca

```
clipboard-landing-page-master/
├── index.html          ← Halkan ayaad HTML-kaaga ku qori doontaa
├── style-guide.md      ← Midabada, font-ka iyo cabbirrada (AKHRI KAN!)
├── preview.jpg         ← Sawir muujinaya sida uu bogga u ekaanayo
├── AGENTS.md           ← Tilmaamo loogu talagalay AI coding assistants
├── design/
│   ├── desktop-design.jpg   ← Naqshadda desktop-ka
│   ├── mobile-design.jpg    ← Naqshadda mobile-ka
│   └── active-states.jpg    ← Sida hover states-ku u ekaanayaan
└── images/             ← Dhammaan sawirrada, logo-yada iyo icon-nada
```

**Ogow:** Fayl `style.css` ah kuma jiro — adiga ayaa abuuraya. Waa inaad
ku xidhaa `index.html` adigoo isticmaalaya `<link>` tag-ga.

Sawirrada ku jira galka `images/` horay ayaa loo **optimize** gareeyay.
Ha beddelin magacyadooda.

---

## ✅ Shuruudaha (Requirements)

Isticmaalaha bogga (user) waa inuu awoodo:

- [ ] Inuu arko **layout** ku habboon cabbirka shaashadda uu isticmaalayo
      (mobile 375px iyo desktop 1440px)
- [ ] Inuu arko **hover state** dhammaan waxyaalaha la taabto —
      button-nada, link-yada iyo social icons-ka
- [ ] Bogga inuu si fiican uga muuqdo 320px ilaa shaashadaha waaweyn

Waxyaalaha technical-ka ah ee la eegayo marka code-kaaga la review-gareynayo:

- [ ] **Semantic HTML** — `<header>`, `<main>`, `<section>`, `<footer>`,
      `<nav>`, ee aan ahayn `<div>` oo keliya
- [ ] Dhammaan sawirrada waxay leeyihiin `alt` text macno leh
- [ ] **Responsive** — isticmaal `media queries`
- [ ] Magacyada CSS class-yadu waa inay macno leeyihiin (tusaale:
      `.hero-title` ee aan ahayn `.t1`)
- [ ] Code-ku waa inuu nadiif yahay: **indentation** sax ah, faylashuna
      inay habaysan yihiin
- [ ] Ma jiraan sawiro ama fayl aan la isticmaalin oo lagu daray

---

## 🛠️ Sida aad u bilaabayso — Git workflow-ka

Tani waa qaybta ugu muhiimsan. Si taxadar leh u raac tallaabooyinka.

### Tallaabo 1 — Fork

Fur repository-ga mashruuca ee GitHub, kadibna guji badhanka **Fork** ee ku
yaal xagga sare ee midig.

Tan macnaheedu waa: **koobi** ka mid ah repository-ga ayaa loo abuurayaa
account-kaaga GitHub. Koobigaas adigaa iska leh, wax kastana kaga bedeli kartaa
adigoon waxba u gelin repository-ga asalka ah.

### Tallaabo 2 — Clone

Hadda repository-ga ka soo **clone** garee account-kaaga oo geli computer-kaaga:

```bash
git clone https://github.com/<MAGACAAGA-GITHUB>/clipboard-landing-page-master.git
cd clipboard-landing-page-master
```

`clone` macnaheedu waa: soo dejinta faylasha internet-ka si aad locally ugu
shaqeyso.

### Tallaabo 3 — Abuur branch cusub

```bash
git checkout -b solution
```

**Branch** waa sida khad shaqo oo gooni ah. Waxaan door bidaynaa inaad ku
shaqeyso branch la yiraahdo `solution`, ee aadan si toos ah ugu shaqeyn `main`.

### Tallaabo 4 — Qor code-kaaga

Fur galka editor-kaaga (VS Code), kadibna:

1. Marka hore qor **HTML**-ka oo dhan `index.html` gudihiisa
2. Kadib abuur fayl la yiraahdo `style.css`
3. Ku xidh `index.html`:

```html
<link rel="stylesheet" href="./style.css" />
```

4. Ku bilow **mobile-ka** (mobile-first), kadibna ku dar `media queries`
   desktop-ka

### Tallaabo 5 — Commit

Marka aad qayb dhammayso, kaydi:

```bash
git add .
git commit -m "Add hero section HTML and styles"
```

**Commit** waa sida "save point" — waa diiwaan muujinaya waxa aad beddeshay.

> ⚠️ **Ha samayn hal commit oo weyn oo keliya.** Samee 5–10 commits oo yaryar
> oo mid walba qayb dhammaystiran ka muujiyo. Farriinta commit-ka (commit
> message) af Ingiriisi ku qor, sida `Add footer social icons`.

### Tallaabo 6 — Push

```bash
git push origin solution
```

**Push** macnaheedu waa: dir shaqadaada GitHub.

### Tallaabo 7 — Pull request

1. Aad repository-gaaga GitHub
2. Waxaa kuu soo bixi doona badhan yiraahda **Compare & pull request** — guji
3. Ku qor cinwaan cad, tusaale: `Solution: Clipboard landing page — Magacaaga`
4. Sharraxaadda (description) ku qor:
   - Waxaad baratay
   - Waxa kugu adkaaday
   - Su'aalaha aad qabtid
   - Link-ga live-ka ah (haddii aad deploy gareysay)
5. Guji **Create pull request**

**Pull request (PR)** macnaheedu waa: waxaad codsanaysaa in shaqadaada la
review-gareeyo lana isku daro repository-ga asalka ah.

---

## 👀 Sida review-gu u shaqeeyo

Marka aad pull request furto:

1. Macallimiintu waxay akhrin doonaan code-kaaga **line by line**
2. Waxay ku qori doonaan **comments** toos ah code-ka dushiisa —
   waxa fiican iyo waxa la beddelayo
3. Adiga waxaad hesheysaa mid ka mid ah:
   - ✅ **Approved** — shaqadu way dhammaatay
   - 🔄 **Changes requested** — wax baa la beddelayaa

Haddii **changes requested** la ku siiyo:

```bash
# wax ka beddel faylasha
git add .
git commit -m "Fix responsive layout on tablet"
git push origin solution
```

Pull request-ku **si toos ah ayuu isu cusboonaysiiyaa** — PR cusub ma baahnid
inaad furto.

> 💬 **Ha ka cabsan changes requested.** Taasi maaha guuldarro — sidaas ayaa
> loo shaqeeyaa shirkadaha software-ka oo dhan. Waa qayb ka mid ah barashada.

---

## 🎨 Style guide

Dhammaan midabada, font-ka iyo cabbirrada waxay ku qoran yihiin faylka
[`style-guide.md`](./style-guide.md). **Akhri intaadan bilaabin.**

Soo koobid:

- **Font:** [Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree) —
  weights 400 iyo 600
- **Body font-size:** 18px
- **Layout widths:** Mobile 375px · Desktop 1440px

Font-ka Google Fonts ka soo qaado, `<head>` gudihiisana ku dar.

---

## 🌍 Deploy (ikhtiyaari laakiin aad loogu talinayo)

Ka dhig bogga mid internet-ka ka muuqda si aad link u wadaagto:

**GitHub Pages** (ugu fudud):

1. Aad repository-gaaga → **Settings** → **Pages**
2. Source: dooro branch-ga `main` (ama `solution`) → **Save**
3. Sug 1–2 daqiiqo, waxaad heli doontaa link:
   `https://<MAGACAAGA-GITHUB>.github.io/clipboard-landing-page-master/`

Ikhtiyaaro kale: [Vercel](https://vercel.com/) ama [Netlify](https://www.netlify.com/)

Link-gaas ku dar pull request-kaaga.

---

## 💡 Talooyin

**Ku bilow qaab-dhismeedka (structure), ee ha ku bilaabin midabada.**
Marka hore qor HTML-ka oo dhan, kadibna ku dar CSS-ka. Waxay ka fududahay in
markiiba la isku daro labada.

**Isticmaal browser DevTools.** Guji `F12` (ama right-click → Inspect). Halkaas
waxaad ku arki kartaa cabbirrada iyo meesha khaladku ka jiro.

**Qayb qayb u qaad bogga.** Bogga waxaa ka kooban:
`header` → `hero` → `sections` → `logos` → `CTA` → `footer`.
Mid dhammee kadibna u gudub kan xiga.

**Naqshadda kuma qorna cabbir kasta.** Waa caadi in aad qiyaasto. Waxa muhiim
ah waa in natiijadu u eg tahay naqshadda — ee ma aha in pixel kasta uu sax
yahay.

**Ha koobiyayn code internet-ka.** Waxaad ku baran doontaa oo keliya adigoo
naftaada ku qoraya. Haddii aad ku adkaato, weydii macallinka.

---

## 🤖 Isticmaalka AI coding assistants

Waad isticmaali kartaa AI si aad wax u fahanto — laakiin **haddii aad code
koobiyayso adigoon fahmin, ma baranaysid waxba**, review-guna wuu muuqan doonaa.

---

## 📌 Marka aad dhammayso

Ka hor intaadan pull request furin, hubi:

- [ ] Bogga si fiican ayuu uga muuqdaa mobile **iyo** desktop
- [ ] Hover states way shaqeynayaan
- [ ] Ma jiraan errors console-ka (F12 → Console)
- [ ] Sawirradu waa muuqdaan, `alt` text-na way leeyihiin
- [ ] Code-ku waa nadiif yahay oo indentation sax ah leeyahay
- [ ] README-ga aad beddeshay oo aad ku sharraxday shaqadaada

---

Challenge-ka asalka ah waxaa leh [Frontend Mentor](https://www.frontendmentor.io?ref=challenge).

**Nasiib Wacan — hadda bilow!** 🚀
