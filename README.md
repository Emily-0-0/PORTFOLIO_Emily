# Portafolio · Emily Cárdenas

Portafolio web de **Emily Cárdenas**, aprendiz de Animación 3D. Reúne sus proyectos de modelado y escenarios 3D (Blender, Unreal Engine, Twinmotion), con galería de imágenes, visor 3D interactivo y contacto por correo.

🔗 **Ver la página:** `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`
*(cambia TU-USUARIO y NOMBRE-DEL-REPOSITORIO por los tuyos, una vez activado GitHub Pages)*

## Cómo se navega

La página abre en la portada. Desde allí, los botones **Acerca de mí**, **Proyectos** y **Contacto** llevan a cada sección, y la flecha de arriba a la izquierda vuelve a la portada. Cada proyecto se abre en su propia vista, con su galería y, en algunos, un visor 3D.

## Contenido del repositorio

```
index.html      → la página completa (es el archivo que GitHub Pages muestra)
assets/
  img/          → imágenes, íconos, flores decorativas y galerías de cada proyecto
  3d/           → modelos 3D (.fbx) y fondo del visor
LEEME.txt       → guía paso a paso para publicar y actualizar la página
README.md       → esta descripción
```

## Publicar con GitHub Pages

1. Sube `index.html`, la carpeta `assets`, `README.md` y `LEEME.txt` a la raíz del repositorio.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama **main** y carpeta **/(root)**, y pulsa **Save**.
4. Espera uno o dos minutos: GitHub mostrará el enlace público de la página.

Hay instrucciones más detalladas en `LEEME.txt`.

## Notas técnicas

- Es una página estática: HTML, CSS y JavaScript, sin instalación ni servidor propio.
- El visor 3D carga la librería Three.js desde internet (jsDelivr) y los modelos desde `assets/3d/`, por lo que necesita conexión y funciona al abrir la página desde GitHub Pages (no al abrir el archivo con doble clic).
- Las tipografías se cargan desde Google Fonts.

## Contacto

emily.cardenas.art@gmail.com
