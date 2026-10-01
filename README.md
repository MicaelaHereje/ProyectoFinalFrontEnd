# UMBRA — E-commerce de ropa streetwear

## Qué es

UMBRA es una landing page de e-commerce de ropa urbana, con estética
nocturna (negro, gris oscuro y un acento en tono bronce). El proyecto
muestra un catálogo de productos, reseñas de clientes y un formulario
de contacto funcional.

Hecho como trabajo práctico / pre-entrega de un curso de desarrollo web.

## Estructura del proyecto

```
umbra/
├── index.html
├── styles.css
├── README.md
└── assets/
    └── img/
        ├── logo.png
        ├── hero-image.jpg
        └── (imágenes de productos)
```

## Secciones de la página

- **Header**: logo, navegación y botones de "Mi cuenta" / "Carrito".
- **Hero**: imagen de fondo con título y descripción.
- **Productos**: catálogo de productos en tarjetas, organizado con **Flexbox**.
- **Reseñas**: testimonios de clientes, organizados con **CSS Grid**.
- **Contacto**: formulario (nombre, email, mensaje) conectado a **Formspree**.
- **Footer**: logo, enlaces, redes sociales y datos legales.

## Cómo verlo

Abrir `index.html` en el navegador. No requiere instalación ni servidor.

## Tecnologías usadas

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 (Flexbox, Grid, Media Queries, variables CSS, degradés)
- [Google Fonts](https://fonts.google.com/) — Archivo + Space Grotesk
- [Font Awesome](https://fontawesome.com/) — íconos
- [Formspree](https://formspree.io/) — manejo del formulario de contacto sin backend propio

## Responsive

El sitio se adapta a pantallas chicas mediante media queries (breakpoint
en 768px): el header y el footer pasan a disposición en columna, la
grilla de reseñas pasa de 3 a 1 columna, y los productos se reacomodan
automáticamente gracias a Flexbox.

