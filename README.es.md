<p align="center">
  <img src="docs/icon.svg" alt="Vidal Technologies" width="72" />
</p>

<h1 align="center">Vidal Technologies — landing page</h1>

<p align="center">
  Landing page de <strong>Vidal Technologies</strong>, empresa que crea sitios web, sistemas, automatizaciones y agentes de IA para empresas.<br />
  Disponible en portugués, inglés y español.
</p>

<p align="center">
  <a href="README.md">Português</a> · <a href="README.en.md">English</a> · <strong>Español</strong>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img alt="Sin dependencias" src="https://img.shields.io/badge/dependencias-0-FBC105" />
  <img alt="Hostinger" src="https://img.shields.io/badge/Hosting-Hostinger-673DE6?logo=hostinger&logoColor=white" />
</p>

![Landing page de Vidal Technologies en español](docs/screenshots/inicio-es.png)

## Sobre el proyecto

Este repositorio contiene la landing page de Vidal Technologies, una página única pensada
para campañas y para el primer contacto con nuevos clientes. Presenta los problemas que
resuelve y los servicios, y lleva al visitante directo a WhatsApp o al e-mail.

La página está hecha con HTML, CSS y JavaScript puros, en un único archivo, sin librerías
y sin etapa de build. El código es abierto y forma parte del portafolio de la empresa.

### Objetivos

- Presentar la empresa de forma visual y directa, en módulos.
- Mostrar los problemas que la tecnología resuelve y los servicios, sin exceso de texto.
- Atender clientes en Brasil y en el exterior, con el contenido en tres idiomas.
- Llevar al visitante al contacto con un clic.

## Funcionalidades

- **Tres idiomas:** portugués, inglés y español, con cambio por banderas en la esquina
  superior derecha. La elección queda guardada y también puede venir en la dirección (`?lang=en` o `?lang=es`).
- **Inicio:** título con una palabra que gira sola ("Tecnología que *atiende* / *vende* /
  *organiza* por ti"), fondo de partículas animado y el botón de WhatsApp.
- **Conversación animada:** un celular muestra a un agente de IA atendiendo a un cliente por
  WhatsApp, mensaje por mensaje.
- **Franja de palabras:** los servicios pasando en bucle.
- **Problemas y soluciones:** tres dolores comunes que se tachan al desplazarse, con la
  solución apareciendo después.
- **Servicios:** Sitios web, Aplicaciones web, Automatización y Agentes de IA en tarjetas
  cortas, con un brillo dorado que sigue al mouse.
- **Llamada final y WhatsApp fijo:** bloque dorado con el contacto y un botón de WhatsApp
  siempre visible en la esquina, con mensaje listo en el idioma elegido.
- **Responsivo:** diseño pensado para computadora y celular.
- **Identidad visual propia:** fondo negro, tonos grafito y dorado `#FBC105`, fuente
  Schibsted Grotesk y logo dibujado en SVG.

## Pantallas

### Computadora

| Problemas y soluciones | Servicios |
| --- | --- |
| ![Problemas y soluciones](docs/screenshots/problemas.png) | ![Servicios](docs/screenshots/servicos.png) |

| Llamada final | |
| --- | --- |
| ![Llamada final](docs/screenshots/contato.png) | |

### Otros idiomas

| Portugués (predeterminado) | Inglés (`?lang=en`) |
| --- | --- |
| ![Landing page en portugués](docs/screenshots/inicio.png) | ![Landing page en inglés](docs/screenshots/inicio-en.png) |

### Celular

| Inicio | Conversación animada | Llamada final |
| --- | --- | --- |
| <img src="docs/screenshots/celular-inicio.png" alt="Inicio en el celular" width="260" /> | <img src="docs/screenshots/celular-conversa.png" alt="Conversación en el celular" width="260" /> | <img src="docs/screenshots/celular-contato.png" alt="Llamada final en el celular" width="260" /> |

## Tecnologías

| Tecnología | Para qué sirve |
| --- | --- |
| HTML5 | Estructura y contenido de la página |
| CSS3 | Estilos, diseño, animaciones y versión para celular |
| JavaScript | Cambio de idioma, palabra que gira, conversación animada, fondo de partículas (Canvas) y animaciones al desplazarse |
| SVG | Logo, íconos, banderas e ilustraciones |
| [Google Fonts](https://fonts.google.com/) | Fuentes Schibsted Grotesk y Urbanist |

La página no usa base de datos, frameworks ni librerías externas. Todo está en un único
`index.html`, lo que hace la página liviana, rápida y fácil de alojar.

## Cómo ejecutarla en tu computadora

Basta con abrir el archivo `index.html` en el navegador. Si prefieres un servidor local:

```bash
git clone https://github.com/vidaltechnologies/vidaltechnologies-lp.git
cd vidaltechnologies-lp
python3 -m http.server 8000
```

Después, abre http://localhost:8000. Las versiones en inglés y español están en
http://localhost:8000/?lang=en y http://localhost:8000/?lang=es.

## Estructura del código

```
index.html          # Página completa: HTML, CSS, JavaScript y los textos en los tres idiomas
docs/
├── icon.svg        # Ícono usado en este README
└── screenshots/    # Imágenes usadas en este README
```

---

© Vidal Technologies. Todos los derechos reservados.
