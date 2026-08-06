# 🌸 かな Match

Juego para practicar **hiragana** y **katakana**. Dos versiones:

- **⚡ Clásico** — aparece un kana y buscas su pareja entre los 46. Rápido y visual.
- **✍️ Caligrafía** — además de emparejarlos, escribes los dos a mano, trazo a
  trazo y en el orden correcto del japonés. Más lento, se fija mucho más.

En ambos puedes jugar en los dos sentidos (あ→ア o ア→あ), oír cada kana, y
el juego guarda tu mejor tiempo por versión y sentido.

## Archivos

| Archivo | Qué es | Licencia |
|---|---|---|
| `index.html` | El juego completo: interfaz, lógica y estilos | MIT |
| `kana-strokes.js` | Datos de orden de trazos de los 92 kana | SIL OFL 1.1 |
| `LICENSE` | Licencia MIT del proyecto | — |
| `OFL.txt` | Licencia de los datos de trazos | — |

No necesita build ni servidor: se abre `index.html` en el navegador y listo.

## Licencia

El código del juego está bajo [MIT](LICENSE): puedes usarlo, modificarlo y
redistribuirlo libremente, incluso con fines comerciales, conservando el aviso
de copyright.

**Excepción:** `kana-strokes.js` no es MIT. Va bajo
[SIL OFL 1.1](OFL.txt) por derivar de la fuente Klee One. Si reutilizas el
proyecto, ese archivo debe seguir acompañado de `OFL.txt` y su aviso de
copyright. La OFL además no permite vender esos datos por separado (el juego
completo sí puede distribuirse sin problema).

## Créditos

Los datos de orden de trazos provienen de
[strokesvg](https://github.com/zhengkyl/strokesvg), cuyas formas derivan de la
fuente [Klee One](https://github.com/fontworks-fonts/Klee).

> Copyright 2020 The Klee Project Authors
> (https://github.com/fontworks-fonts/Klee)

`kana-strokes.js` se distribuye bajo la
[SIL Open Font License 1.1](https://openfontlicense.org/); el texto completo
está en [`OFL.txt`](OFL.txt). Esa licencia cubre únicamente ese archivo de
datos y no se extiende al resto del proyecto.

La pronunciación usa la Web Speech API del navegador, así que las voces
disponibles dependen de tu sistema operativo.
