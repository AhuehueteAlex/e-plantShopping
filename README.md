# coding-project-template
# Paradise Nursery - Shopping Cart

Repositorio: **e-plantShopping**

Aplicación frontend de Paradise Nursery construida con **React + Redux Toolkit + Vite**.

## Requisitos
- Node.js 18+
- npm

## Ejecutar en local
```bash
npm install
npm run dev
```

## Build de producción
```bash
npm run build
```

## Deploy en GitHub Pages
Este proyecto ya incluye `gh-pages` y scripts de despliegue.

1. Asegúrate de tener remoto en GitHub:
```bash
git remote -v
```

2. Si no existe, agrega tu repositorio:
```bash
git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
```

3. Sube tu rama principal:
```bash
git push -u origin <tu-rama>
```

4. Ejecuta deploy:
```bash
npm run deploy
```

5. En GitHub ve a **Settings → Pages** y configura:
- **Source**: `Deploy from a branch`
- **Branch**: `gh-pages` / `/ (root)`

> Nota: después de desplegar, GitHub Pages puede tardar unos minutos en reflejar imágenes y contenido.
