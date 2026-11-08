# Among LAN 👾

Juego web **tipo Among Us** para jugar con amigos en la **misma Wi-Fi (LAN)**, sin ningún servidor: los navegadores se conectan directamente entre sí (WebRTC) intercambiando un código de invitación.

> Proyecto personal y sin ánimo de lucro entre amigos. No afiliado a Innersloth.

## 🎮 Cómo jugar

1. Un jugador pulsa **«Crear partida (anfitrión)»**.
2. Los demás escriben su nombre y color, y pulsan **«Unirse con invitación»**.
3. Cada jugador que se une genera un **código**: se lo manda al anfitrión (WhatsApp, etc.).
4. El anfitrión lo pega en su pantalla («Aceptar jugador») y le **devuelve un código de respuesta** al jugador.
5. El jugador pega el código de respuesta… ¡conectado!
6. El anfitrión pulsa **«🚀 Empezar partida»** (5–10 jugadores idealmente, 2 mínimo).

Todo el tráfico va **directo entre dispositivos por la red local**. Si estáis en la misma Wi-Fi, la conexión es LAN pura.

## 🕹️ Controles

- **PC:** WASD o flechas para moverte. Botones USAR / MATAR / REPORTAR / REUNIÓN con clic.
- **Móvil:** joystick táctil (arrastra en cualquier parte de la pantalla) y botones táctiles.

## 📋 Mecánicas

- 1 impostor (o 2 con 8+ jugadores) contra tripulantes.
- Cada tripulante tiene 3 tareas con minijuegos (cables, descargas, teclado, tarjeta).
- Impostor: matar (recarga 30 s), tareas fingidas, sin votación de ventaja.
- Reportar cuerpos, reunión de emergencia en la cafetería, votación con chat.
- Los muertos se vuelven fantasma 👻 y pueden seguir moviéndose.

## 🖼️ Sprites

El juego usa unos personajes dibujados por código, pero si pones PNGs en la carpeta `sprites/` los usará automáticamente. Nombres esperados:

```
sprites/rojo.png      sprites/rosa.png     sprites/cian.png
sprites/azul.png     sprites/naranja.png  sprites/lima.png
sprites/verde.png    sprites/amarillo.png sprites/fantasma.png
sprites/negro.png    sprites/morado.png
sprites/blanco.png   sprites/marron.png
```

Súbelos arrastrando los archivos dentro de la carpeta `sprites/` en la web de GitHub (Add file → Upload files). También cada jugador puede cargarlos en su navegador desde el menú («Cargar sprites PNG»); se guardan en su dispositivo.

## 🌐 Activar GitHub Pages

1. Entra en el repo → **Settings** → **Pages**.
2. Source: **Deploy from a branch** → rama `main`, carpeta `(root)`.
3. Guarda. En 1–2 minutos estará en: **https://thiaguito00.github.io/among-lan/**

Comparte ese enlace con tus amigos y a jugar.
