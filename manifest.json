# InspectPro – App PWA de Inspección de Maquinaria

App web progresiva (PWA) para registrar inspecciones de maquinaria industrial.
Funciona sin conexión y se puede instalar en el móvil como app nativa.

---

## 📁 Archivos del proyecto

```
inspectpro/
├── index.html       ← App principal
├── manifest.json    ← Configuración PWA
├── sw.js            ← Service Worker (caché offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🚀 Publicar en GitHub Pages (paso a paso)

### 1. Crear cuenta en GitHub
Ve a https://github.com y crea una cuenta gratuita si no tienes una.

### 2. Crear repositorio
- Haz clic en el botón verde **"New"**
- Nombre del repositorio: `inspectpro` (o el que quieras)
- Selecciona **Public**
- Haz clic en **"Create repository"**

### 3. Subir los archivos
En la página del repositorio vacío:
- Haz clic en **"uploading an existing file"**
- Arrastra TODOS los archivos y la carpeta `icons/` al área de subida
- ⚠️ Asegúrate de que la carpeta `icons` se sube con su contenido
- Escribe un mensaje como `Primera versión` y haz clic en **"Commit changes"**

### 4. Activar GitHub Pages
- Ve a **Settings** (pestaña de configuración del repositorio)
- En el menú izquierdo, haz clic en **"Pages"**
- En **"Branch"**, selecciona `main` y carpeta `/ (root)`
- Haz clic en **"Save"**

### 5. Obtener la URL
Tras 1-2 minutos, GitHub Pages te mostrará la URL de tu app:
```
https://TU_USUARIO.github.io/inspectpro/
```

---

## 📲 Instalar en el móvil

### Android (Chrome)
1. Abre la URL en Chrome
2. Aparecerá un banner "Añadir a pantalla de inicio" — tócalo
3. O bien: menú (⋮) → "Añadir a pantalla de inicio"

### iPhone/iPad (Safari)
1. Abre la URL en **Safari** (no Chrome)
2. Toca el botón compartir (□↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. Toca **"Añadir"**

---

## ⚠️ Notas importantes

- Los **datos e imágenes** se guardan en el navegador (localStorage).
  Si borras los datos del navegador, se perderán.
- En **iOS**, el almacenamiento puede borrarse si no usas la app
  durante varias semanas (limitación de Apple).
- En **Android**, el almacenamiento es más persistente.
- Las fotos se pueden descargar como .jpg desde el detalle de cada inspección.
- El CSV exportado es compatible con Excel y Google Sheets.

---

## 🔄 Actualizar la app

Para actualizar la app después de cambios:
1. Sube el nuevo `index.html` a GitHub (arrastra y confirma)
2. En `sw.js`, cambia `inspectpro-v1` por `inspectpro-v2`
   (esto fuerza que los móviles descarguen la nueva versión)
3. Sube también el `sw.js` modificado

---

*InspectPro — Inspección de Maquinaria Industrial*
