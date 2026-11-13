
# Web Design - Proyecto Final

Sitio web desarrollado como proyecto final del curso de Desarrollo Web de Coderhouse.

## 🌐 Sitio web publicado

[Visitar el sitio web](https://beamish-vacherin-0b65f1.netlify.app/)

## 📌 Descripción del proyecto

El proyecto consiste en el desarrollo de un sitio web responsive, organizado en distintas secciones para presentar información, formaciones y recursos.

El sitio está compuesto por cinco páginas:

- **Inicio:** presentación del sitio.
- **Sobre mí:** información personal y profesional.
- **Formaciones:** presentación de propuestas formativas.
- **Recursos:** materiales y recursos disponibles.
- **Contacto:** formulario y medios de contacto.

## 🛠️ Tecnologías utilizadas

- **HTML5:** estructura semántica del contenido.
- **CSS3:** estilos y diseño visual.
- **Sass (SCSS):** organización modular de estilos, variables, mixins, nesting y reutilización de código.
- **Bootstrap 5:** componentes y diseño responsive.
- **AOS (Animate On Scroll):** animaciones al desplazarse por el sitio.
- **Google Fonts:** tipografías.
- **Netlify:** publicación y despliegue del sitio web.
- **Git y GitHub:** control de versiones y gestión del código.

## ✨ Características

- Diseño responsive adaptable a distintos dispositivos.
- Navegación mediante menú responsive.
- Estructura HTML semántica.
- Optimización SEO básica mediante títulos, descripciones y palabras clave.
- Imágenes con atributos alternativos (`alt`).
- Estilos organizados en archivos parciales SCSS.
- Transiciones y animaciones.
- Sitio publicado mediante Netlify.

## 📁 Estructura del proyecto

```text
WebDesignCoderhouse2/
│
├── index.html
├── pages/
│   ├── sobremi.html
│   ├── formaciones.html
│   ├── recursos.html
│   └── contacto.html
│
├── assets/
│   ├── susanabacha.jpg
│   ├── carousel1.jpg
│   ├── carousel2.jpg
│   └── carousel3.jpg
│
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── main.scss
│
├── styles/
│   └── main.css
│
└── README.md
```

## 💻 Compilación de Sass

Para compilar los archivos SCSS y generar el CSS, ejecutar el siguiente comando desde la terminal, en la carpeta raíz del proyecto:

```bash
npx sass scss/main.scss styles/main.css
```

## 🚀 Publicación

El sitio web se encuentra publicado en Netlify:

https://beamish-vacherin-0b65f1.netlify.app/

---

**Proyecto desarrollado como entrega final del curso de Desarrollo Web - Coderhouse.**