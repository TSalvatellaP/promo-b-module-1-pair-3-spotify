# Proyecto Spotify - Frontend

Este proyecto es una implementación frontend de una página web inspirada en Spotify. El proyecto está estructurado para ser modular y mantenible, utilizando HTML, SCSS y posiblemente JavaScript.

## Estructura de Carpetas
```
├── partials/
│   ├── footer.html
│   ├── header.html
│   ├── seccion-blue.html
│   └── seccion-white.html
├── scss/
│   ├── components/
│   │   ├── _code.scss
│   │   └── _links.scss
│   ├── core/
│   │   ├── _mixins.scss
│   │   ├── _reset.scss
│   │   └── _variables.scss
│   ├── layout/
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _seccion-blue.scss
│   │   └── _seccion-white.scss
│   └── pages/
│       ├── main.scss
│       └── signup.scss
├── index.html
├── signup.html
├── .eslintrc.json
├── .gitignore
└── desktop.jpg
```

## Descripción de Carpetas y Archivos

### `partials/`

Contiene fragmentos HTML reutilizables para diferentes secciones de la página.

* `footer.html`: HTML para el pie de página.
* `header.html`: HTML para la cabecera.
* `seccion-blue.html`: HTML para una sección con fondo azul.
* `seccion-white.html`: HTML para una sección con fondo blanco.

### `scss/`

Contiene archivos SCSS para la estilización del proyecto.

* `components/`: Estilos para componentes UI reutilizables.
    * `_code.scss`: Estilos para bloques de código.
    * `_links.scss`: Estilos para enlaces.
* `core/`: Archivos SCSS fundamentales.
    * `_mixins.scss`: Mixins SCSS reutilizables.
    * `_reset.scss`: Estilos para resetear o normalizar estilos CSS.
    * `_variables.scss`: Variables SCSS para colores, fuentes, etc.
* `layout/`: Estilos para el layout general de la página.
    * `_footer.scss`: Estilos para el pie de página.
    * `_header.scss`: Estilos para la cabecera.
    * `_seccion-blue.scss`: Estilos para la sección azul.
    * `_seccion-white.scss`: Estilos para la sección blanca.
* `pages/`: Estilos específicos para páginas.
    * `main.scss`: Estilo principal para la página principal.
    * `signup.scss`: Estilos para la página de registro.

### Archivos Raíz

* `index.html`: Página principal del sitio.
* `signup.html`: Página de registro.
* `.eslintrc.json`: Configuración para ESLint (linter de JavaScript).
* `.gitignore`: Archivo para especificar archivos y carpetas que Git debe ignorar.
* `desktop.jpg`: Imagen de fondo o imagen principal.

## Uso

1.  Asegúrate de tener un compilador de SCSS instalado (por ejemplo, `node-sass` o `sass`).
2.  Compila los archivos SCSS a CSS usando tu compilador preferido.
3.  Abre `index.html` en tu navegador para ver la página principal.

## Contribución

Si deseas contribuir a este proyecto, sigue estos pasos:

1.  Haz un fork del repositorio.
2.  Crea una rama para tu contribución (`git checkout -b feature/nueva-caracteristica`).
3.  Realiza tus cambios.
4.  Haz commit de tus cambios (`git commit -m 'Añade nueva característica'`).
5.  Sube tus cambios a tu fork (`git push origin feature/nueva-caracteristica`).
6.  Crea un pull request.

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).