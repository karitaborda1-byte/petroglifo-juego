# Voces de piedra / Pirasumi

Videojuego de exploración 3D de petroglifos, preparado como sitio estático para GitHub Pages.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `THREE-LICENSE.txt` y este `README.md` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`; pulsa **Save**.
5. Espera a que termine el despliegue y abre la URL que GitHub muestra en esa misma sección.

El juego incluye Three.js y sus imágenes dentro de `index.html`; no necesita instalar paquetes ni configurar un servidor. Requiere un navegador moderno con WebGL.

## Controles

- Jugador 1: `W A S D`
- Jugador 2: flechas
- Correr: `Shift`
- Examinar: `E` o `Enter` cuando ambos estén cerca del petroglifo
- Cámara: arrastrar con el mouse; rueda para acercar o alejar
- El sonido comienza al entrar; se puede silenciar desde el botón de sonido.

## Contenido

Los diez niveles se desarrollan en un mismo mundo 3D. El progreso y las imágenes iconográficas usadas por el juego están incluidos en el HTML. Los datos iconográficos se conservan como registros de la investigación y las interpretaciones se presentan como parte de la propuesta lúdica.

## Licencia de Three.js

El juego incorpora Three.js r128, distribuido bajo licencia MIT. Consulta `THREE-LICENSE.txt` para el texto completo de la licencia.
