<div align="center">

# 🏛️ BharatTantra

**Indian Polity & Civil Services Explained**

From Gram Panchayat to President, and from board exams to IAS and IPS. A free, plain-language visual guide to how India is governed and how India is served.

[![Live site](https://img.shields.io/badge/live-political.wondermayank.indevs.in-573AFC)](https://political.wondermayank.indevs.in/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#-tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#-tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#-tech-stack)
[![No build step](https://img.shields.io/badge/build-none-22c55e)](#-run-locally)

### 🔗 [political.wondermayank.indevs.in](https://political.wondermayank.indevs.in/)

</div>

---

## 📖 About

**BharatTantra** explains the two "ladders" that run through Indian governance:

- 🗳️ **The political ladder:** Gram Panchayat → MLA and Chief Minister → Lok Sabha and Rajya Sabha → Prime Minister → President
- 🎓 **The service ladder:** Board exams → UPSC Civil Services → IAS, IPS and other central services → SDM and State PCS

It is useful for students, UPSC / State PCS / SSC aspirants, and anyone curious about how Indian institutions actually work.

> Content is educational and simplified for clarity. For exam preparation, always confirm details with official sources such as the Constitution of India, UPSC and the Election Commission of India.

## 📚 What's inside (16 pages)

### Political System (`/political/`)

| Page | Topic |
|------|-------|
| [Overview](https://political.wondermayank.indevs.in/political/) | Hub page for the political ladder |
| [Local Governance](https://political.wondermayank.indevs.in/political/local-governance.html) | Gram Panchayat, Panchayat Samiti, Zilla Parishad, Municipal bodies |
| [Chief Minister & MLA](https://political.wondermayank.indevs.in/political/chief-minister-mla.html) | How an MLA is elected and how a state gets its CM |
| [Lok Sabha](https://political.wondermayank.indevs.in/political/lok-sabha.html) | The House of the People and government formation |
| [Rajya Sabha](https://political.wondermayank.indevs.in/political/rajya-sabha.html) | The Council of States and indirect election |
| [Prime Minister](https://political.wondermayank.indevs.in/political/prime-minister.html) | The path from a Lok Sabha seat to leading the government |
| [Council of Ministers](https://political.wondermayank.indevs.in/political/council-of-ministers.html) | Cabinet Minister, MoS (Independent Charge), MoS, portfolios |
| [President & Governor](https://political.wondermayank.indevs.in/political/president-governor.html) | Electoral college and gubernatorial appointment |
| [Parties & Elections](https://political.wondermayank.indevs.in/political/parties-elections.html) | Party registration, recognition, candidates, elections |

### Civil Services (`/education/`)

| Page | Topic |
|------|-------|
| [Overview](https://political.wondermayank.indevs.in/education/) | Hub page for the service ladder |
| [Exam Ladder](https://political.wondermayank.indevs.in/education/exam-ladder.html) | Board exams to UPSC, State PCS, SSC and Banking |
| [UPSC CSE](https://political.wondermayank.indevs.in/education/upsc-cse.html) | Prelims, Mains and Interview |
| [IAS & IPS Allocation](https://political.wondermayank.indevs.in/education/ias-ips-allocation.html) | How one rank leads to different services and training |
| [SDM & State Services](https://political.wondermayank.indevs.in/education/sdm-state-services.html) | State PCS and the path from SDM to District Magistrate |
| [Other Services](https://political.wondermayank.indevs.in/education/other-services.html) | IRS, IFS, IRTS, IPoS and the police hierarchy |

## ✨ Features

- 🪜 **"The Ladder" design motif:** numbered rungs that mirror real hierarchies
- 🌗 Light and dark mode (saved in `localStorage`)
- 📱 Fully responsive, with a mobile menu
- ⚡ Plain HTML, CSS and JS: no framework, no build, fast loading
- ✨ Scroll-reveal animations and a loading screen
- 🔎 **SEO ready:** unique titles and descriptions, canonical URLs, Open Graph and Twitter cards, JSON-LD (`WebSite`, `WebPage`, `BreadcrumbList`), `sitemap.xml` and `robots.txt`

## 🚀 Run locally

No build step and no dependencies.

```bash
# 1. Clone the repository
git clone https://github.com/wondermayank/political.git

# 2. Go into the folder
cd political

# 3. Open index.html in your browser, or use any static server
python -m http.server 8000
```

Then visit `http://localhost:8000`. Google Fonts load from the internet, so you need a connection for the exact typography.

## 📂 Project structure

```
political/
├── index.html                  # Homepage
├── political/                  # Political System section (9 pages)
│   ├── index.html
│   ├── local-governance.html
│   ├── chief-minister-mla.html
│   ├── lok-sabha.html
│   ├── rajya-sabha.html
│   ├── prime-minister.html
│   ├── council-of-ministers.html
│   ├── president-governor.html
│   └── parties-elections.html
├── education/                  # Civil Services section (6 pages)
│   ├── index.html
│   ├── exam-ladder.html
│   ├── upsc-cse.html
│   ├── ias-ips-allocation.html
│   ├── sdm-state-services.html
│   └── other-services.html
├── assets/
│   ├── style.css               # Design system (colours, type, components)
│   ├── main.js                 # Menu, theme toggle, scroll reveal, loader
│   └── img/Hero1.png           # Homepage hero image
├── og-image.png                # 1200x630 social preview image
├── favicon.svg
├── sitemap.xml
├── robots.txt
└── README.md
```

## 🎨 Customise

All colours, spacing and type tokens live as CSS variables at the top of `assets/style.css`. Edit them to retheme the whole site at once.

| Token | Value |
|-------|-------|
| Primary | `#573AFC` |
| Fonts | Sora (headings), Inter (body), JetBrains Mono (labels) |

## 🔎 SEO notes

- Canonical base URL: `https://political.wondermayank.indevs.in`
- When you add a page, add it to `sitemap.xml` and give it a unique `<title>`, `<meta name="description">`, canonical link and Open Graph tags.
- Submit `https://political.wondermayank.indevs.in/sitemap.xml` in Google Search Console and Bing Webmaster Tools.

## 🛠️ Tech stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, light/dark themes) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts |
| Hosting | Static hosting |

## 🤝 Contributing

Corrections and improvements are welcome, especially factual fixes.

1. Fork this repository
2. Create a branch: `git checkout -b fix/my-change`
3. Commit your changes: `git commit -m "Describe your change"`
4. Push the branch: `git push origin fix/my-change`
5. Open a Pull Request

## 📬 Contact

- 🌐 Website: [wondermayank.in](https://wondermayank.in)
- 📧 Email: contact@wondermayank.indevs.in
- 🐙 GitHub: [@wondermayank](https://github.com/wondermayank)

## 📄 License

Free to use for learning and personal use. Please give credit to **Wondermayank** if you share or reuse it.

---

<div align="center">

Made with ❤️ in India by **Wondermayank**

</div>
