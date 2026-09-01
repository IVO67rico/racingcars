# Racing Legends 3D — edición STL

Esta versión integra los cinco STL suministrados como los cinco autos seleccionables del juego.

## Mapeo

- Cometa S → `models/comet.stl` (original: `coche.stl`)
- Rally Fox → `models/rally.stl` (original: `Coche (1).stl`)
- Toro V8 → `models/muscle.stl` (original: `coche (2).stl`)
- Drift Katana → `models/drift.stl` (original: `Coche (3).stl`)
- Interceptor X → `models/police.stl` (original: `coche (4).stl`)

Los modelos se normalizan automáticamente: Z-up del STL → Y-up de Three.js, detección del eje longitudinal, orientación al frente, centrado y escala común. El color elegido en el garaje se aplica al STL y el selector de tuneo controla el acabado del material (brillante, metalizado, mate o perlado).

## Ejecutar

Como los STL se cargan con `fetch()`, sirve esta carpeta por HTTP/HTTPS. GitHub Pages funciona directamente. Para una prueba local puedes usar cualquier servidor estático, por ejemplo `python -m http.server 8000`, y abrir `http://localhost:8000`.

Three.js sigue cargándose desde el CDN que ya usaba el código original.
