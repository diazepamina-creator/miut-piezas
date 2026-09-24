# Las piezas de Miut

Manipulativo de factorización, mcd y mcm para 1.º y 2.º de ESO. Un rediseño paralelo de [El templo de Miut](https://diazepamina-creator.github.io/templo-de-miut/) con una sola idea que se toca: **cada número es una bolsa de piezas**, una por factor primo, con el número escrito y el color de su primo.

Cuatro juegos, todos a toques (sin arrastrar, para que funcione en la pizarra digital y en el móvil):

- **Romper** — el número es una piedra; se golpea con primos hasta dejarla en 1. Es la descomposición en factores primos.
- **Lo común · mcd** — con las piezas de un número y con las del otro hay que construir la misma torre, la más grande posible.
- **Todo · mcm** — la torre más pequeña en la que quepan los dos números.
- **La pareja** — las torres del mcd y del mcm, juntas, son las piezas de los dos números: mcd · mcm = a · b.

Cada juego sube en cuatro etapas —colores, texturas, lisas y sin piezas— en las que las piezas ayudan cada vez menos. Además:

- **Guía**: una visita con un foco sobre cada parte de la mesa. Se abre sola la primera vez.
- **Practicar**: ejercicios nuevos sin fin, con cuatro dificultades o **Auto** (se ajusta sola), que se eligen tocando la etiqueta de arriba. En «Más», mezclar los cuatro juegos, el reto de las 7 vidas, que es el modo muy difícil (siete vidas para toda la serie; cinco seguidos a la primera devuelven una), repasar lo fallado y poner tus números.
- **Acta**: resumen de lo hecho en el aparato, con nombre, código de verificación y código de expediente, para copiarla o descargarla y entregarla.
- **Ajustes**: mesa clara u oscura, decir el número antes de voltear y patas sin animación.
- **Retos por enlace**: una dirección abre un ejercicio concreto en Practicar, para ponerla en una ficha con un QR. Por ejemplo, `?j=comun&n=36,48&d=1`:
  - `j` es el juego: `romper`, `comun` (mcd), `todo` (mcm) o `pareja`;
  - `n`, los números, separados por comas (uno en Romper, dos en La pareja, de dos a cuatro en el mcd y el mcm);
  - `d`, la dificultad: `0` fácil, `1` media, `2` difícil, `3` sin piezas.

  En Ajustes, «Para el profesor» da la dirección del ejercicio que está en la mesa.

Es un solo archivo, `index.html`, sin dependencias: se abre en el navegador y ya está.

© 2026 Andrés Asensio · [CC BY-NC-SA 4.0](LICENSE.md)
