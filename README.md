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
- Jugador 2: flechas o `I J K L` (alternativa si tu teclado no registra todas las teclas a la vez)
- Control de consola (Gamepad): con un control conectado, lo usa el Jugador 2; con dos, el primero es J1 y el segundo J2. Stick o cruceta para moverse, `A` para interactuar, `X`/`Y` para subir o bajar de la chiva, gatillos/bumpers para correr.
- Subir o bajar de la chiva: `F` (o botón contextual). Los dos personajes viajan juntos.
- Conducir: Jugador 1 usa `W A S D`; Jugador 2 puede ayudar con las flechas; `Shift` (izquierdo o derecho) activa el turbo.
- Correr a pie: `Shift` izquierdo (J1) y `Shift` derecho (J2), cada jugador por separado
- Buscar huellas: acércate a los destellos de los primeros ocho sitios y pulsa `E` / `Enter` para recogerlos. Reúne dos de tres.
- Examinar: cuando ambos estén junto a la piedra y tengan dos huellas, pulsa `E` / `Enter`. Identifica la raíz y selecciona dos rasgos visibles del registro.
- Cámara: arrastrar con el mouse; rueda para acercar o alejar
- El sonido comienza al entrar; se puede silenciar desde el botón de sonido.

## Cuaderno de investigación

- **Observar:** al examinar un petroglifo, el panel incluye *Luz rasante*, *Relieve* y *Lupa* (arrastra sobre la imagen para desplazar el zoom).
- **Comparar (botón ✎ Cuaderno):** pone un petroglifo ya descubierto junto a un registro de otra cultura (Argentina, Chile, Teymareh), marca rasgos que se parecen o difieren y guarda una observación. No se afirma origen ni significado común.
- **Taller de signos:** dibuja un signo propio, describe sus rasgos, combina raíces descubiertas en un posible significante y escribe una hipótesis.
- **Mis registros:** lista lo guardado (se conserva en el navegador con `localStorage`) y permite descargarlo como `cuaderno-pirasumi.json`.
- Mientras el cuaderno está abierto, el Eco de Piedra y el movimiento quedan en pausa.

## Mundo ampliado

- **Ciclo de día y noche continuo:** amanecer, mañana, tarde, atardecer y noche, con sol y luna que se desplazan, estrellas, niebla, luz y colores del paisaje cambiantes. La duración del día se elige en el selector del encabezado (3, 6, 12 o 24 min, u hora fija).
- **Movimiento:** aceleración y desaceleración al caminar y al correr (Shift). Se corrigió la posición inicial, que dejaba a los personajes dentro de la colisión de la barandilla de arranque.
- **Zona del bosque tropical** al occidente con helechos y palmas que se mecen con el viento, formaciones rocosas grandes, charcos que forman ondas al pisarlos y hojas que flotan.
- **Cementerio simbólico:** escenario ficticio y respetuoso, con túmulos, lajas y piedras, y un cartel que lo aclara. No documenta prácticas funerarias reales ni de la cultura Cartama.
- **Criatura (el Vigía de Ceniza):** observa a distancia, aparece sobre todo de noche y cerca del cementerio, y se desvanece si se le acercan. No ataca.
- **Mapa interactivo (tecla M):** representación ficticia del mundo del juego que se revela al explorar, con petroglifos, puente, quebrada, cementerio y jugadores. El mapa municipal real de Támesis se conserva aparte.
- **Ambiente sonoro** sintetizado: viento, agua cerca de la quebrada, grillos y búhos de noche, y aves de día.

## Contenido

Los diez niveles se desarrollan en un mismo mundo 3D. El progreso y las imágenes iconográficas usadas por el juego están incluidos en el HTML. Los datos iconográficos se conservan como registros de la investigación y las interpretaciones se presentan como parte de la propuesta lúdica.

El inicio del recorrido recrea una plaza de Támesis con iglesia de torre y casas de corredor, construidas en 3D con geometría del juego. Una chiva colorida recorre el territorio; acérquense y pulsen `F` para subir, conduzcan con `W A S D` y pulsen `F` para bajar. El segundo nivel incluye un puente colgante sobre una quebrada y cambia de día a noche con niebla. Cada sitio tiene un arco de piedras que enmarca el registro y fragmentos luminosos que se rastrean en el terreno. En los primeros ocho niveles, los jugadores deben reunir huellas y resolver una observación iconográfica; los dos últimos trabajan sintaxis y creación de mensajes. La poza con cascada aparece en una escena posterior. El botón **Mapa** muestra el mapa municipal de Támesis aportado a la investigación junto con la lista esquemática de sitios; no se dibujan coordenadas arqueológicas que no hayan sido documentadas.

## Licencia de Three.js

El juego incorpora Three.js r128, distribuido bajo licencia MIT. Consulta `THREE-LICENSE.txt` para el texto completo de la licencia.

