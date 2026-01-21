🚀 ICARUS RACERS

ICARUS RACERS es un prototipo de videojuego de carreras futuristas desarrollado en HTML5 Canvas + JavaScript, con estética sci-fi, música integrada y una experiencia completamente jugable desde el navegador.

Versión actual: v0.9


🎮 Descripción

ICARUS RACERS es un juego arcade de velocidad ambientado en el espacio, donde pilotas naves de la serie ICARUS a través de un circuito holográfico lleno de meteoritos, boosts y checkpoints.

Incluye:

Intro cinemática con vídeo (no omisible)

Menú animado con música

Selección de nave

Carrera con IA

Sistema de daños y destrucción

Pantalla de resultados

Todo el juego está contenido en un único archivo HTML, utilizando recursos externos (imágenes, vídeos y audio).

🕹️ Controles
Tecla	Acción
↑	Acelerar
↓	Frenar (mantener 2s = reversa)
← / →	Girar
Espacio	Boost
Botón “Reiniciar”	Reinicia la carrera
📁 Estructura del proyecto
/
├── index.html
├── imagen/
│   ├── logo1.png
│   ├── nave1.png
│   ├── nave_30.png
│   ├── nave_31.png
│   ├── nave_32.png
│   ├── meteorito1.png
│   ├── earth1.png
│   ├── track_holo_base.png
│   ├── track_holo_glow.png
│   └── track_decals.png
├── video/
│   ├── introvideo.webm
│   └── menu_bg_loop.webm
└── music/
    ├── music1.mp3
    ├── music2.mp3
    ├── intro2.mp3
    ├── ohno.mp3
    ├── engine_idle_loop.mp3
    ├── engine_throttle_loop.mp3
    ├── engine_boost_loop.mp3
    ├── engine_brake_loop.mp3
    ├── engine_start_one_shot.mp3
    └── engine_hit_one_shot.mp3


⚠️ Importante: el juego no funcionará correctamente si faltan estos archivos o si se abre el HTML sin servirlo desde un servidor local.

▶️ Cómo ejecutar
Opción recomendada (servidor local)
# con Python
python -m http.server


Luego abre en el navegador:

http://localhost:8000

Opción alternativa

Usa extensiones como Live Server en VS Code.

🛠️ Tecnologías usadas

HTML5 Canvas

JavaScript Vanilla

Web Audio API

Audio HTML5

Vídeo HTML5 (WebM)

CSS moderno (glassmorphism, blur, gradients)

🎧 Audio y vídeo

La intro no se puede omitir

Algunos navegadores bloquean el autoplay con audio → se muestra un botón para iniciar

El audio del motor es dinámico (idle, throttle, boost, brake)

🧪 Estado del proyecto

Este proyecto es un prototipo experimental:

Código no modularizado

Todo el juego vive en un solo archivo HTML

Pensado para exploración creativa y visual, no como producto final

📜 Créditos

© Disturbing Stories 2026
Vianda Visual
🌐 https://www.disturbingstories.com

📄 Licencia

Uso personal / demostrativo.
Para usos comerciales, redistribución o modificaciones, revisa los derechos de los assets (audio, imágenes y vídeo).
