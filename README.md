# 🐾 PetShop Amigos Peludos

**PetShop Amigos Peludos** maskoten denda baterako webgune moderno bat da, **HTML, SCSS eta Bootstrap** erabiliz garatua. Diseinu arduratsua, **modu iluna**, eta nabigazio aktiboa ditu.

---

## 📌 Deskribapena

Webgune honek honako atalak eskaintzen ditu:

- Produktu nabarmenduak  
- Zerbitzuak (ile-apainketa eta albaitaritza)  
- Harremanetarako atala mapa interaktiboarekin  
- Modu argia / modu iluna  
- Nabigazio-barra aktiboa scroll-aren arabera  

Frontend garapeneko proiektu praktikoa da, **SCSS modularra** eta **erabiltzailearen esperientzia** ardatz hartuta.

---

## 🛠️ Erabilitako teknologiak

- **HTML5**
- **SCSS (Sass)**
  - Variables
  - Mixins
  - Fitxategi modularrak
- **Bootstrap 5.3**
- **JavaScript (Vanilla)**
  - Modu iluna
  - Nabigazio aktiboa (`IntersectionObserver`)
- **Google Maps Embed**

---

## 📁 Proiektuaren egitura

```/
├── index.html
├── src/
│ ├── css/
│ │ └── styles.css
│ ├── scss/
│ │ ├── _variables.scss
│ │ ├── _mixins.scss
│ │ ├── _components.scss
│ │ └── styles.scss
│ └── img/
│ └── irudiak
└── README.md
```

---

## 🎨 Ezaugarri nagusiak

### 🌗 Modu iluna
- Nabigazio-barratik aktibagarria
- Elementu hauei eragiten die:
  - Atzeko planoa
  - Txartelak (cards)
  - Modalak
  - Footer-a
  - Navbar-a eta esteka aktiboak
- `<body>`-an `dark-mode` klasearen bidez

---

### 🧭 Nabigazio-barra adimenduna
- Goialdean finkatua
- Uneko atala automatikoki nabarmentzen du:
  - Testua lodiz
  - Beheko marra batekin
- Modu argi eta ilunarekin bateragarria
- `IntersectionObserver` erabiliz inplementatua

---

### 🧱 SCSS modularra
- `@use` erabilera
- Mixins berrerabilgarriak:
  - `transition-all`
  - `card-hover`
  - `rounded`
  - `dark-mode`
  - `flex-center`
  - `responsive-text`
- Aldagai zentralizatuak kolore eta tipografiarako

---

### 📞 Harremanetarako atala
- Txarteletan oinarritutako diseinua
- Informazioa:
  - Emaila
  - Telefonoa
  - Helbidea
- **Mapa interaktiboa iframe bidez**
- Scroll doikuntza navbar-ak atala ez estaltzeko

---

## 🚀 Nola erabili

1. Klonatu edo deskargatu proiektua
2. Ireki `index.html` nabigatzailean  

SCSS konpilatzeko:
```bash
sass src/scss/styles.scss src/css/styles.css --watch
