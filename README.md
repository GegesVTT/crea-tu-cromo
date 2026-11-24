# Crea tu cromo

Creación de personajes interactiva para el juego de rol de mesa **Hechicería y Magia** (adaptación en español de *Witchcraft and Wizardry*, de TableStory, sobre el sistema *Powered by the Apocalypse*).

Once escenas, de la carta de admisión al banquete de bienvenida, con una escena puente de llegada al castillo entre el tren y La Selección. Cada escena se resuelve de a un paso: se elige tocando, y «Seguir» solo cambia de escena. Al terminar, el personaje queda listo para jugar: se puede imprimir, descargar como `.json` y volver a cargar.

## Cómo se usa

Abrí la página y tocá **Empezar**. El avance se guarda en el navegador, así que podés cerrar la página y seguir después.

## Estructura

- `index.html`: toda la herramienta (HTML, CSS y JavaScript, sin dependencias).
- `audio/musica-partida-2020.mp3`: música original hecha para la partida de 2020. Suena solo si se activa el sonido.
- `fuentes/`: IM Fell English (texto y títulos) y las cuatro letras de firma para el nombre: Pinyon Script, Mrs Saint Delafield, Homemade Apple y Caveat. Licencias en `fuentes/LICENCIAS.md`. La ficha para la mesa las lleva adentro para funcionar sin conexión.
- `guiones/`: guiones de storyboard (formato Storyboard Studio): el del arte nuevo de las escenas (`guion-escenas-crea-tu-cromo.md`) y los del arte que falta dibujar: puerta del Gran Comedor, Sombrero, mascotas, núcleos, caprichos y familias.
- `arte/llegada-NN.webp`: cuadros de la escena puente entre el tren y La Selección (del carrito de golosinas al techo del Gran Comedor), tomados de la biblia visual de GG.
- `prototipos/`: pruebas de diseño que todavía no están en la herramienta. `espejo.html` rehace la escena 3 (elegir con un toque y ordenar al final); `llegada.html` es la escena puente de la llegada al castillo.
- `arte/eNN-fNN.webp`: cuadros del storyboard original. Quedan como respaldo y para La llegada, donde todavía faltan cuadros nuevos.
- `arte/v2/`: arte de las escenas en el estilo de la selección vieja. `eNN-fNN` son los cuadros de cada escena, `eNN-pNN` las placas de cada opción (familia, núcleo, mascota, casa, hechizo), `eNN-dNN` los destellos de transición entre escenas y `obj-` los objetos sueltos. `arte/v2/LEEME.md` dice de dónde salió cada imagen y qué falta. Para cambiar una ilustración, se reemplaza el archivo con el mismo nombre.

## Aviso

Guía no oficial, hecha por fans y sin fines comerciales. No tiene relación con los titulares de la obra en la que se inspira. Arte de GG. Música original de [@rodrigesualdo](https://www.instagram.com/rodrigesualdo).
