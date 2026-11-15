<p align="center">
  <img src="docs/icon.svg" alt="Vidal Technologies" width="72" />
</p>

<h1 align="center">Vidal Technologies — landing page</h1>

<p align="center">
  Landing page for <strong>Vidal Technologies</strong>, a company that builds websites, systems, automations and AI agents for businesses.<br />
  Available in Portuguese, English and Spanish.
</p>

<p align="center">
  <a href="README.md">Português</a> · <strong>English</strong> · <a href="README.es.md">Español</a>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img alt="No dependencies" src="https://img.shields.io/badge/dependencies-0-FBC105" />
  <img alt="Hostinger" src="https://img.shields.io/badge/Hosting-Hostinger-673DE6?logo=hostinger&logoColor=white" />
</p>

![Vidal Technologies landing page in English](docs/screenshots/inicio-en.png)

## About the project

This repository holds the Vidal Technologies landing page, a single page built for
campaigns and for the first contact with new clients. It presents the services, shows how
the company works and leads visitors to get in touch via WhatsApp or e-mail.

The page is built with plain HTML, CSS and JavaScript in a single file, with no libraries
and no build step. The code is open and is part of the company's portfolio.

### Goals

- Present the company in a visual, direct way, organized in modules.
- Show the services and an example of a dashboard the company builds.
- Serve clients in Brazil and abroad, with the content in three languages.
- Lead visitors to contact with a single click.

## Features

- **Three languages:** Portuguese, English and Spanish, switched with the flags in the top
  right corner. The choice is saved and can also come in the address (`?lang=en` or `?lang=es`).
- **Hero:** title with gold highlights, animated particle background, key figures and a
  mini automation flow.
- **Services:** cards numbered 01 to 04 (Websites, Web applications, Process automation and
  AI agents) that open on click and rotate on their own.
- **About:** how we work (Conversation, Proposal and Delivery), a featured project and the "Meet Vidal" card.
- **Dashboard:** an illustrative dashboard with animated charts and live clocks for
  São Paulo, New York and Madrid.
- **Contact:** WhatsApp button, with a ready-made message in the chosen language, and e-mail button.
- **Responsive:** layout designed for desktop and mobile.
- **Own visual identity:** black background, graphite tones and gold `#FBC105`,
  Schibsted Grotesk font and an SVG logo.

## Screens

### Desktop

| Services | About |
| --- | --- |
| ![Services](docs/screenshots/servicos.png) | ![About](docs/screenshots/sobre.png) |

| Dashboard | Contact |
| --- | --- |
| ![Dashboard](docs/screenshots/painel.png) | ![Contact](docs/screenshots/contato.png) |

### Other languages

| Portuguese (default) | Spanish (`?lang=es`) |
| --- | --- |
| ![Landing page in Portuguese](docs/screenshots/inicio.png) | ![Landing page in Spanish](docs/screenshots/inicio-es.png) |

### Mobile

| Hero | Services | Contact |
| --- | --- | --- |
| <img src="docs/screenshots/celular-inicio.png" alt="Hero on mobile" width="260" /> | <img src="docs/screenshots/celular-servicos.png" alt="Services on mobile" width="260" /> | <img src="docs/screenshots/celular-contato.png" alt="Contact on mobile" width="260" /> |

## Technologies

| Technology | What it is used for |
| --- | --- |
| HTML5 | Page structure and content |
| CSS3 | Styles, bento grid layout, animations and mobile version |
| JavaScript | Language switching, particle background (Canvas), service cards, clocks and scroll animations |
| SVG | Logo, icons, flags and illustrations |
| [Google Fonts](https://fonts.google.com/) | Schibsted Grotesk and Urbanist fonts |

The page uses no database, frameworks or external libraries. Everything lives in a single
`index.html`, which keeps the page light, fast and easy to host.

## Running it locally

Just open `index.html` in your browser. If you prefer a local server:

```bash
git clone https://github.com/vidaltechnologies/vidaltechnologies-lp.git
cd vidaltechnologies-lp
python3 -m http.server 8000
```

Then open http://localhost:8000. The English and Spanish versions are at
http://localhost:8000/?lang=en and http://localhost:8000/?lang=es.

## Code structure

```
index.html          # Full page: HTML, CSS, JavaScript and the texts in all three languages
docs/
├── icon.svg        # Icon used in this README
└── screenshots/    # Images used in this README
```

---

© Vidal Technologies. All rights reserved.
