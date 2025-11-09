# Simulador Sísmico Educativo

Proyecto listo para abrir en **Visual Studio Code**. No requiere build: usa React UMD + Babel Standalone directo en el navegador.

## Requisitos (opción A: Live Server)
1. Instala la extensión **Live Server** en VS Code (Ritwick Dey).
2. Abre la carpeta `simulador-sismico-educativo`.
3. Clic derecho sobre `index.html` → **Open with Live Server**.

## Requisitos (opción B: Node + lite-server)
1. Tener Node.js instalado.
2. En la carpeta del proyecto:
   ```bash
   npm i
   npm start
   ```
   Se abrirá `http://localhost:3000` o similar con la app.

## Estructura
- `index.html`: todo el código (HTML, estilos y React JSX usando `<script type="text/babel">`).
- `package.json`: script `npm start` con **lite-server**.

> **Nota:** El proyecto carga React, ReactDOM, Babel y Chart.js desde CDNs.
