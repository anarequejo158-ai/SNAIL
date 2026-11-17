# Flash: Salto Submarino — prototipo web

## Contenido
- `index.html`: juego jugable en navegador, pensado para pantalla vertical.
- `assets/`: fondos, interfaz, enemigos, plataformas, potenciadores y música A–E.
- `source_models/`: modelos originales FBX y BLEND para la integración 3D posterior.

## Ejecutar localmente
Abre `index.html` en un navegador moderno. Para probar en celular, publica el proyecto en GitHub Pages o usa un servidor local HTTPS.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y la carpeta `assets` (con su contenido).
3. En Settings → Pages, elige Deploy from a branch, selecciona `main` y `/root`.
4. Guarda y abre la URL que GitHub Pages genere.

## Controles
- Celular: inclina el dispositivo a izquierda/derecha. En iOS puede aparecer una solicitud de permiso después de tocar JUGAR.
- Escritorio: flechas izquierda/derecha o A/D.
- También se puede arrastrar/tocar a izquierda/derecha en el área de juego.

## Alcance del prototipo
La lógica de salto, plataformas móviles, enemigos, potenciadores, tres niveles, pausa, game over, selección de color y música está implementada. El caracol está dibujado provisionalmente en 2D: el ZIP entregado contiene `caracoles.fbx` y `caracoles.blend`, pero no un `.glb`; se requiere convertir/exportar el modelo y revisar materiales/animaciones para sustituirlo por el personaje 3D final. Las animaciones de enemigos son movimientos provisionales; los movimientos finos de tentáculos/pinzas y escalado del pez globo quedan como integración posterior.
