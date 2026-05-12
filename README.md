# Porfolio - Carlos Barrientos Arias

Portfolio web personal desarrollado con HTML5, CSS3 y JavaScript vanilla. Sitio estático responsive para mostrar proyectos y datos de contacto.

## Estructura del proyecto

```
Porfolio/
├── assets/              # Archivos descargables (CV PDF, etc.)
├── css/
│   └── styles.css       # Estilos globales, layout responsive, animaciones
├── js/
│   └── script.js        # Lógica: menú móvil, modal de imágenes, scroll reveal
├── .vscode/
│   └── settings.json    # Configuración de Live Preview
├── index.html            # Página principal (entry point)
├── LICENSE              # MIT License
└── README.md            # Este archivo
```

## Tecnologías

- **HTML5** - Estructura semántica
- **CSS3** - Flexbox, Grid, custom properties, diseño responsive (breakpoint 768px)
- **JavaScript** - Intersection Observer, manipulación del DOM, menú hamburguesa

## Características

- Diseño responsive (mobile-first)
- Menú de navegación sticky con versión hamburguesa en móvil
- Animaciones de entrada al hacer scroll (fade-in)
- Modal para vista ampliada de imágenes de proyectos
- Enlaces a GitHub, LinkedIn y descarga de CV
- Grilla de proyectos adaptable (2 columnas → 1 columna en móvil)

## Personalización

Editar `main.html` para cambiar:
- Nombre y título en la sección hero
- Enlaces a redes sociales (GitHub, LinkedIn)
- Tarjetas de proyecto (imagen, título, descripción)
- Ruta del archivo CV en `assets/`

Colores editables en `css/styles.css` (variables CSS en `:root`).

## Uso

Abrir `main.html` en cualquier navegador o usar Live Preview de VS Code.

## Licencia

MIT
