[README.md](https://github.com/user-attachments/files/33450940/README.md)
# Cartel SAR Balonmán (PWA)
Pega el Excel del fin de semana → se genera el cartel "Xogamos na casa" / "Xogamos fora".

## Subir a GitHub Pages
1. Crea un repositorio nuevo y sube TODO el contenido de esta carpeta (index.html, sw.js, manifest.webmanifest, assets/, icons/).
2. Settings → Pages → Branch: main, carpeta / (root) → Save.
3. Abre https://TUUSUARIO.github.io/NOMBRE-REPO/ y en el móvil "Añadir a pantalla de inicio".

## Uso
- **Nuevo:** pulsa «Cargar Excel (.xlsx)» y elige el archivo tal como lo envía la federación (RFEBM). Se queda solo con los equipos SAR y elige el próximo fin de semana. Los partidos sin hora asignada (00:00) salen como «--:--». Marca los grandes con la estrella ★.
- El sexo (FEM./MASC.) de cada equipo SAR se define en la constante `SEXO` de index.html, porque la federación no lo incluye.
- Alternativa: copia las filas en Excel (con la cabecera: Fecha, Hora, Local, Visitante, Categoría, Pabellón) y pégalas en el cuadro.
- Las filas con **color de relleno** pasan a tarjeta verde grande (máx. 4). También puedes marcarlas con la estrella ★ de la lista.
- Cambia entre CASA y FORA arriba. Descarga el PNG o compártelo.
