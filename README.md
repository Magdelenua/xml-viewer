# 📄 Visualizador de XML

Aplicación web sencilla para visualizar y analizar archivos XML de forma clara y organizada.

![XML Viewer](https://img.shields.io/badge/HTML-100%25-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Características

- 📤 Carga de archivos XML desde tu dispositivo
- 📋 Vista de XML formateado con indentación clara
- 🌳 Vista de árbol jerárquico del contenido
- 📊 Vista JSON de los datos
- 📈 Estadísticas automáticas (elementos, tamaño, raíz)
- 🎨 Interfaz moderna y responsive
- ⚡ Procesamiento 100% en el navegador (sin servidor)

## 🚀 Despliegue Rápido en GitHub Pages

### Paso 1: Clonar o Descargar
Descarga esta carpeta completa en tu computadora.

### Paso 2: Crear Repositorio en GitHub
```bash
cd xml-viewer
git init
git add .
git commit -m "🎉 Initial commit: XML Viewer"
```

Ve a GitHub y crea un nuevo repositorio llamado `xml-viewer`

```bash
git remote add origin https://github.com/TU-USUARIO/xml-viewer.git
git branch -M main
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Click en **Settings** ⚙️
3. En el menú lateral → **Pages**
4. En **Source** → selecciona **main** branch
5. Carpeta: **/ (root)**
6. Click **Save**

### Paso 4: ¡Listo! 🎊
Tu aplicación estará disponible en:
```
https://TU-USUARIO.github.io/xml-viewer/
```

## 💻 Uso Local (Sin Internet)

Simplemente abre el archivo `index.html` en tu navegador:
```bash
# En Windows
start index.html

# En macOS
open index.html

# En Linux
xdg-open index.html
```

## 📁 Estructura del Proyecto

```
xml-viewer/
│
├── index.html              ← Aplicación principal (GitHub Pages)
├── ejemplo.xml             ← Archivo XML de prueba
├── README.md               ← Este archivo
├── GITHUB_PAGES.md         ← Guía detallada de despliegue
├── .gitignore              ← Archivos ignorados por Git
│
└── flask-version/          ← Versión alternativa con Python (opcional)
    ├── app.py
    ├── requirements.txt
    └── templates/
        └── index.html
```

## 🎯 Cómo Usar la Aplicación

1. Abre la aplicación en tu navegador
2. Click en **"Elegir archivo"**
3. Selecciona un archivo XML (puedes usar `ejemplo.xml`)
4. La aplicación mostrará automáticamente:
   - **XML Formateado**: Código con indentación
   - **Vista de Árbol**: Estructura jerárquica
   - **Datos JSON**: Representación en JSON
   - **Estadísticas**: Número de elementos y tamaño

## 🧪 Archivo de Ejemplo

Incluye `ejemplo.xml` con una biblioteca de libros para probar la aplicación.

## 🐍 Versión Flask (Opcional)

Si prefieres la versión con backend Python, está en la carpeta `flask-version/`:

```bash
cd flask-version
pip install -r requirements.txt
python app.py
```

Abre http://localhost:5000

**Nota:** Esta versión requiere despliegue en Heroku, Render, o PythonAnywhere (no GitHub Pages).

## 🛠️ Tecnologías

- **HTML5** - Estructura
- **CSS3** - Diseño moderno con gradientes
- **JavaScript Vanilla** - Procesamiento XML
- **DOMParser API** - Parseo de XML nativo del navegador

## 📝 Licencia

MIT License - Uso libre para proyectos personales y comerciales.

## 🤝 Contribuciones

¡Contribuciones son bienvenidas! Puedes:
- Reportar bugs
- Sugerir nuevas características
- Mejorar el diseño
- Agregar más formatos de exportación

## 📞 Soporte

Si tienes problemas o preguntas:
1. Revisa `GITHUB_PAGES.md` para guía detallada
2. Abre un Issue en GitHub
3. Verifica que tu archivo XML esté bien formado

---

**¡Disfruta visualizando tus archivos XML!** 🎉
