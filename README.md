# Mi Proyecto Web

Proyecto web estático en HTML creado para aprender el flujo de trabajo con Git y GitHub: repositorio local y remoto, ramas por funcionalidad y Pull Requests.

## Tabla de contenido

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Estructura](#estructura)
- [Mejoras implementadas](#mejoras-implementadas)
- [Flujo de trabajo con Git](#flujo-de-trabajo-con-git)

## Descripción

La página (`index.html`) parte de una estructura básica con un título y un párrafo. Sobre ella se han ido añadiendo mejoras en ramas independientes, usando solo HTML y un poco de CSS embebido, y se han fusionado en `main` mediante Pull Requests.

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/dbrosedg-coder/mi-proyecto-web.git
   ```

2. Entra en la carpeta del proyecto:

   ```bash
   cd mi-proyecto-web
   ```

3. Abre `index.html` en el navegador. No necesita servidor ni dependencias.

> Para ver el mapa y las imágenes de la galería hace falta conexión a internet, porque se cargan desde servidores externos.

## Estructura

```
.
├── index.html    # Página principal con todas las mejoras
├── README.md     # Documentación del proyecto
└── .gitignore    # Ficheros excluidos (incluye la carpeta .vscode/)
```

## Mejoras implementadas

| Mejora | Rama | Descripción |
|---|---|---|
| Menú de navegación | `feature/menu` | Barra con enlaces internos (Inicio, Sobre mí, Contacto) y estilos propios. |
| Mapa "Dónde estamos" | `mapa-campus` | Sección con la dirección del centro y un mapa de Google Maps incrustado. |
| Formulario de inscripción | `formulario` | Formulario sin funcionalidad con campos de texto, fecha, radio, casillas, desplegable, rango, área de texto y subida de PDF. |
| Comandos Git que he aprendido | `feature/comandos-git` | Lista de comandos básicos y desplegables con preguntas sobre Pull Requests y ramas. |
| Galería de imágenes | `galeria` | Seis imágenes con texto alternativo. |
| Horario de clases | `feature/tabla` | Tabla semanal con encabezados, recreo (`colspan`) y leyenda. |
| Footer con redes sociales | `footer` | Pie de página con enlaces a redes sociales (Twitter, Instagram, LinkedIn, GitHub y YouTube). |
| Mejoras visuales | `Mejoras-visuales` | Ajustes de estilo y presentación de la página. |

## Flujo de trabajo con Git

- La rama principal es `main`.
- Cada mejora se desarrolla en su propia rama `feature/...`.
- Los cambios se suben con `git push origin <rama>` y se fusionan en `main` mediante un Pull Request en GitHub.
- La documentación se añadió en la rama `docs/readme`.
- El fichero `.gitignore` evita subir archivos innecesarios, como la carpeta `.vscode/`.
