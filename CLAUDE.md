# Web de Elena Rocha (elenarocha.es)

Elena Rocha es creativa gastronómica (Extremadura · España / Portugal · Latinoamérica). Esta web se publica sola en el hosting de Raiola al subir cambios a `main` (`.github/workflows/publicar.yml`, por FTP). Los datos de acceso están en los Secrets del repositorio: nunca se escriben en el código.

## Reglas de marca
- **Ningún texto termina en punto**. Es seña de marca. Sí se usan comas, interrogaciones y puntos suspensivos
- Tono: cercano, poético, gamberro e inclusivo. Poco texto, mucho aire. Fino, delicado y especial
- Frases propias: "Esta vez, déjate cuidar", "La belleza no es un lujo. Es una forma de cuidar", "Un ratito a contracorriente"
- No se menciona Badajoz como ubicación. Se dice "Creativa gastronómica", no "chef privada"
- Evitar fotos donde se vean caras de invitados, salvo que Elena lo pida

## Diseño
- Colores: papel `#fbf9f1`, tarjeta `#f2ecd9`, tinta `#2a1a22`, gris `#7a6a6f`, rojo amapola `#eb4537`, salvia `#86aa70`. Experiencias: fondo `#1c1714`
- Tipografías: Cormorant Garamond (títulos), Bricolage Grotesque (etiquetas, menú, botones), Arimo (texto)
- Los botones son una raya corta + texto ("—— Hablemos"). El índice no lleva raya
- Imágenes en WebP (máx. 1650 px), vídeos H.264 sin audio salvo el vídeo principal de cada mesa, con `+faststart`

## Estructura
- `index.html`: toda la web (vistas por `#`: inicio, sientate-a-la-mesa, cada mesa, experiencias, libre-albedrio, legal)
- `img/`: fotos y vídeos
- Mesas en el array `M` del script; experiencias en `X`
