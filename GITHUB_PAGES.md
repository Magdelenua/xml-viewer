# Guía de Despliegue en GitHub Pages

## 📦 Archivos Necesarios para GitHub Pages

Para GitHub Pages solo necesitas el archivo **`index.html`** que es 100% estático y funciona sin servidor Python.

## 🚀 Pasos para Subir a GitHub Pages

### 1. Crear Repositorio en GitHub

```bash
# Inicializar repositorio local
git init

# Agregar archivos (solo necesitas index.html para GitHub Pages)
git add index.html ejemplo.xml README.md

# Hacer commit
git commit -m "Initial commit: XML Viewer app"

# Crear repositorio en GitHub (desde la web)
# Luego conectar tu repositorio local:
git remote add origin https://github.com/TU-USUARIO/xml-viewer.git
git branch -M main
git push -u origin main
```

### 2. Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Click en **Settings** (⚙️)
3. En el menú lateral, click en **Pages**
4. En **Source**, selecciona **main** branch
5. Deja la carpeta en **/ (root)**
6. Click en **Save**

### 3. Acceder a tu Aplicación

Tu aplicación estará disponible en:
```
https://TU-USUARIO.github.io/xml-viewer/
```

¡Listo! La aplicación funcionará completamente en GitHub Pages sin necesidad de servidor.

## 📁 Estructura para GitHub Pages

```
xml-viewer/
│
├── index.html         ← ¡Este es el único archivo necesario!
├── ejemplo.xml        ← Archivo de prueba (opcional)
└── README.md          ← Documentación
```

## ✨ Características de la Versión GitHub Pages

- ✅ **100% JavaScript** - Sin necesidad de Python o servidor
- ✅ **Funciona offline** - Procesa archivos localmente
- ✅ **Sin instalación** - Solo abre el navegador
- ✅ **Tres vistas**:
  - XML Formateado
  - Vista de Árbol
  - Datos en JSON
- ✅ **Estadísticas** - Muestra número de elementos y tamaño

## 🔄 Actualizar tu Aplicación

```bash
# Hacer cambios en index.html
git add index.html
git commit -m "Actualización de funcionalidad"
git push

# GitHub Pages se actualizará automáticamente en 1-2 minutos
```

## 🎯 Versión con Backend Python (Flask)

Si prefieres usar la versión con Flask (backend Python), necesitarás desplegarlo en:

- **Heroku** (gratuito con limitaciones)
- **Render** (gratuito)
- **PythonAnywhere** (gratuito con limitaciones)
- **Railway** (gratuito con créditos iniciales)

Para eso usa los archivos:
- `app.py`
- `templates/index.html`
- `requirements.txt`

## 💡 Recomendación

Para GitHub Pages, usa **`index.html`** (versión estática).
Es más simple, rápida y no requiere servidor.
