# 🏎️ Fórmula 1 (Temporada 2026)

¡Bienvenido a **Formula 1**! Este proyecto es una plataforma web estática de tipo institucional dedicada a la máxima categoría del automovilismo mundial, enfocada en la revolucionaria temporada 2026. 

Desarrollado como **Evaluación Final del curso de Desarrollo Web**, el sitio combina una experiencia de usuario fluida, optimización de rendimiento de vanguardia y un diseño responsivo adaptado a la identidad visual de la Fórmula 1.

---

## 🚀 Enlaces del Proyecto

* **🔗 Sitio Web en Producción (Live Demo):** [PEGÁ_ACÁ_EL_LINK_DE_VERCEL_O_NETLIFY]
* **📦 Repositorio de Código (GitHub):** [PEGÁ_ACÁ_EL_LINK_DE_TU_GITHUB]

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **HTML5 Semántico:** Estructuración limpia y accesible utilizando etiquetas de organización (`<main>`, `<section>`, `<article>`, `<header>`, `<footer>`).
* **SASS (Preprocesador CSS):** Arquitectura modular avanzada mediante el uso de parciales (`@use`), variables globales de identidad, anidamiento (*nesting*) y mixins configurables para transiciones.
* **Bootstrap 5 (Customizado):** Implementación del sistema de grilla adaptativa (`Grid System`) para diseño 100% responsivo, con sobreescritura de estilos nativos del framework para reflejar una paleta cromática propia (Negro Carbono, Rojo F1 y Grises).
* **Imágenes de Alto Rendimiento (AVIF):** Optimización extrema de carga y performance mediante el uso del formato multimedia de última generación `.avif` en la sección de circuitos.
* **Git & GitHub:** Flujo de trabajo basado en ramas de características (`Feature Branch Workflow`) e historial cronológico de control de versiones.

---

## 📂 Estructura del Proyecto

El proyecto sigue una arquitectura de diseño limpia y desacoplada, donde solo el punto de acceso principal permanece en la raíz:

```text
├── css/
│   ├── main.css          # Archivo CSS compilado por SASS
│   └── main.css.map      # Mapa de depuración de SASS
├── images/
│   ├── circuitos/        # Trazados neon en formato .avif
│   ├── pilotos/          # Fotos oficiales de la parrilla
│   ├── about-section.jpg
│   └── hero-bg.jpg       # Imagen principal del Jumbotron
├── pages/
│   ├── circuitos.html    # Fichas técnicas de las 22 pistas
│   ├── contacto.html     # Formulario interactivo con focus custom
│   ├── equipos.html      # Las 11 escuderías (con Cadillac F1 Team)
│   └── pilotos.html      # Parrilla completa con dorsales vectoriales
├── sass/
│   ├── base/
│   │   ├── _reset.scss   # Normalización del modelo de caja y márgenes
│   │   └── _variables.scss # Paleta de colores, tipografías y radios
│   ├── pages/
│   │   ├── _circuitos.scss
│   │   ├── _contacto.scss
│   │   ├── _equipos.scss
│   │   ├── _home.scss
│   │   └── _pilotos.scss
│   ├── _mixins.scss      # Mixin de transiciones y animaciones globales
│   └── style.scss        # Punto de entrada y compilación de partials
└── index.html            # Landing page principal (Inicio)
