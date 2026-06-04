# Bienes Raíces

Sitio web estático para una inmobiliaria, creado con HTML, SCSS, JavaScript y Gulp. El proyecto presenta páginas informativas, listados de propiedades, artículos de blog, una ficha de propiedad y un formulario de contacto.

## Autor

Desarrollado por Antonio José Escrucería Uribe.

## Tecnologías

- HTML5
- SCSS
- JavaScript
- Gulp 4
- Modernizr
- CSS minificado con PostCSS, Autoprefixer y CSSNano
- Optimización de imágenes y generación de versiones WebP

## Estructura del proyecto

```text
bienesraices/
├── build/              # Archivos compilados para producción
│   ├── css/
│   ├── img/
│   └── js/
├── src/                # Archivos fuente
│   ├── img/
│   ├── js/
│   └── scss/
├── *.html              # Páginas del sitio
├── gulpfile.js         # Tareas de automatización
├── package.json        # Dependencias del proyecto
└── README.md
```

## Páginas incluidas

- `index.html`: página principal.
- `nosotros.html`: información de la empresa.
- `anuncios.html`: listado de propiedades.
- `anuncio.html`: detalle de una propiedad.
- `blog.html`: listado de entradas del blog.
- `entrada.html`: detalle de una entrada del blog.
- `contacto.html`: formulario de contacto.

## Instalación

Para trabajar con las tareas de Gulp, instala las dependencias del proyecto:

```bash
npm install
```

## Uso

Ejecuta Gulp para compilar SCSS, minificar JavaScript, optimizar imágenes y generar versiones WebP:

```bash
npx gulp
```

El sitio puede abrirse directamente desde `index.html` o servirse desde un entorno local como XAMPP.

## Despliegue en Netlify

El proyecto incluye `netlify.toml` para publicar el sitio como proyecto estático.

Configuración recomendada en Netlify:

- Build command: dejar vacío.
- Publish directory: `.`
- Branch de despliegue: `master`.

Después de conectar el repositorio de GitHub con Netlify, cada nuevo `git push` a `master` publicará los cambios automáticamente.

## Estado del proyecto

El proyecto cuenta con una base funcional y versionada en Git. Las siguientes mejoras recomendadas son:

- Corregir ortografía y acentos en todos los textos visibles.
- Actualizar metadatos del proyecto y autor en `package.json`.
- Reemplazar textos de ejemplo por contenido final.
- Mejorar accesibilidad del menú, modo oscuro, imágenes y formulario.
- Revisar y comentar el código fuente de manera consistente.
- Regenerar archivos de `build/` después de ajustar SCSS y JavaScript.

## Repositorio

Repositorio remoto:

```text
https://github.com/Escruceria/bienesraices.git
```
