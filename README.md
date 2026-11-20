# Ligero

Lector de PDF rápido y ligero para dispositivos Android de tinta electrónica, hecho para el **Boox Go Color 7 (Gen II)**. Aquí solo se publican las versiones para probar; el código no es público.

*A fast, lightweight PDF reader for e-ink Android devices, built for the Boox Go Color 7 (Gen II). This repository only hosts test builds. English below.*

## Qué hace

- **Planos, mapas y dibujos:** pellizcar para ampliar, arrastrar y doble toque en el centro, como en cualquier lector de PDF. Al soltar, solo la zona visible se dibuja nítida.
- **Libros escaneados:** separa las dobles páginas, recorta márgenes y endereza.
- **Modo reflow:** vuelve a maquetar la página escaneada con la letra más grande, sin OCR y sin errores de texto.
- **Convertir a EPUB** con reconocimiento de texto en el propio dispositivo.
- **Refresco e-ink automático en los Boox:** rápido al mover y hojear, limpio al soltar.

Comparado con NeoReader, el lector de serie, con los mismos planos de AutoCAD y en el mismo Boox, Ligero abre el PDF unas 3 veces más rápido, pasa página unas 2,7 veces más rápido y gasta entre 3 y 5 veces menos memoria.

## Instalar

1. Abre la [última versión](../../releases/latest) desde el Boox y descarga `Ligero-x.y.apk`.
2. Ábrelo. Si Android lo pide, permite instalar apps de ese origen.

Requisitos: Android 10 o posterior y procesador ARM de 64 bits (todos los Boox recientes). Está probado en el Go Color 7 Gen II; en los demás dispositivos es justo lo que queremos averiguar.

### Recibir las actualizaciones solo

Instala [Obtainium](https://github.com/ImranR98/Obtainium), pulsa **Añadir app** y pega:

```
https://github.com/F-N-LL/ligero-releases
```

Te avisará de cada versión nueva y la instalará encima, conservando tus libros y posiciones.

## Contar qué tal va

Abre un [issue](../../issues/new/choose): hay una plantilla para fallos y otra para ideas. Lo más útil es saber **el modelo del dispositivo y qué tipo de PDF** (escaneado, digital, plano...). Si el fallo es con un archivo concreto y puedes compartirlo, mejor aún.

---

## English

**Install:** open the [latest release](../../releases/latest) on the device, download `Ligero-x.y.apk` and open it (allow installs from that source if asked). Android 10+, 64-bit ARM. Tested on the Boox Go Color 7 Gen II.

**Updates:** in [Obtainium](https://github.com/ImranR98/Obtainium), add `https://github.com/F-N-LL/ligero-releases`.

**Feedback:** [open an issue](../../issues/new/choose) with your device model and the kind of PDF.

The app's interface is in Spanish and English.
