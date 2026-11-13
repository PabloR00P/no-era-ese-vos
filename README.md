# NO ERA ESE, VOS

Juego para el reto **"Difícil a propósito"**.

Es Nochebuena en Guatemala y ya merito son las 12. Tenés una bomba de pólvora con mechas de colores y una pista que dice en qué orden cortarlas. Cortalas antes de que el reloj llegue a cero. A veces la pista te babosea.

## Cómo se juega

- Tocá las mechas en el orden que dice la pista.
- Mecha equivocada: −3 segundos.
- Reloj en cero: ¡PUM!
- Cada bomba desactivada trae otra más difícil.
- Cada 5 bombas te ganás un tamal.

En computadora también se puede jugar con las teclas 1–7 (cortan la mecha de esa fila) y M apaga la música.

### Trampas

- **La pista te babosea:** hay que hacerlo al revés.
- **Las mechas no se están quietas:** cambian de lugar tras cada corte.
- **Grabátelo:** la pista se borra a los pocos segundos.
- **Se fue la luz:** las mechas se quedan sin color ni número a ratos.

## Reglas del reto

| Regla | Cómo se cumple |
| --- | --- |
| Máximo 32 KB sin comprimir | Todo el juego es un solo `index.html` de 21.9 KB (21,871 bytes). El navegador no descarga nada más. |
| Código propio, sin librerías | JavaScript puro, sin frameworks ni motores. |
| Cero assets | Sin imágenes, audio ni fuentes. Todo se dibuja con Canvas 2D y suena con WebAudio. |
| Repo público + link para jugar | Este repo, publicado con GitHub Pages. |

## Detalles chapines

- De fondo, los volcanes de Agua, Acatenango y Fuego. Si perdés, el de Fuego hace erupción.
- La música es ritmo de posada: tortuga, chinchín y pito, generados por código.
- La bomba 24 es la de Nochebuena.

## Correrlo en tu compu

Abrí `index.html` en el navegador. No necesita servidor ni instalación.
