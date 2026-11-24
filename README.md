# Sitio personal — Miguel Puma P.

Portafolio personal estático construido con HTML, CSS y JavaScript. Preparado para publicarse mediante GitHub Pages y utilizar un dominio personalizado.

## Estructura

```text
miguel-puma-portfolio/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── main.js
    └── images/
        ├── favicon.svg
        ├── foto.webp
        ├── caos-lorenz.webp
        ├── generador-primos.webp
        └── logic-pro-arreglos.webp
```

## Imágenes incluidas

- `foto.webp`: retrato de portada.
- `caos-lorenz.webp`: visualización del simulador del atractor de Lorenz.
- `generador-primos.webp`: captura de salida del generador de primos gigantes.
- `logic-pro-arreglos.webp`: captura de arreglos multipista en Logic Pro.

Las imágenes se convirtieron a WebP y se optimizaron para reducir el peso de descarga.

## Ver el sitio localmente

Desde esta carpeta, ejecuta:

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000`.

## Publicar con GitHub Pages

1. Crea un repositorio público llamado `TU-USUARIO.github.io`.
2. Copia el contenido de esta carpeta a la raíz del repositorio.
3. Sube los archivos a la rama `main`.
4. En GitHub, abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`.
6. Guarda los cambios y espera a que GitHub Pages publique el sitio.
7. La dirección inicial será `https://TU-USUARIO.github.io`.

## Dominio personalizado

Cuando tengas un dominio, configúralo desde **Settings → Pages → Custom domain** y añade los registros DNS que GitHub indique. Activa **Enforce HTTPS** cuando esté disponible. Después conviene añadir la URL canónica y el sitemap con el dominio definitivo.

## Actualizar el contenido

- Texto y secciones: `index.html`.
- Colores, composición y diseño responsive: `assets/css/styles.css`.
- Menú móvil y animaciones: `assets/js/main.js`.
- Fotografías y capturas: `assets/images/`.

## Privacidad

La web no incluye teléfono, dirección, correo personal ni perfiles privados. Todo archivo del sitio publicado en GitHub Pages será accesible públicamente, aunque el repositorio que lo alimenta sea privado. No subas contraseñas, tokens, documentos privados ni datos sensibles.

## SEO

El título, encabezado principal y metadatos están orientados al nombre exacto `Miguel Puma P.` y describen el portafolio sin intentar posicionarlo para búsquedas generales por ubicación o profesión. La indexación y la posición en Google no están garantizadas.


## Tema claro y oscuro

La cabecera incluye un botón para alternar entre tema oscuro (azul noche) y tema claro. La preferencia se guarda en el navegador mediante `localStorage`; si el almacenamiento está bloqueado, el selector sigue funcionando durante la visita actual.

La escala tipográfica se ha aumentado para facilitar la lectura en pantallas de escritorio y móviles.
# web-personal
# web-personal
