# 🚀 Inicio Rápido - 3 Pasos

## Para GitHub Pages (Recomendado)

### 1️⃣ Inicializar Git
```bash
cd xml-viewer
git init
git add .
git commit -m "Initial commit"
```

### 2️⃣ Subir a GitHub
Crea un repositorio en GitHub y ejecuta:
```bash
git remote add origin https://github.com/TU-USUARIO/xml-viewer.git
git branch -M main
git push -u origin main
```

### 3️⃣ Activar GitHub Pages
- Ve a Settings → Pages
- Source: **main** branch
- Carpeta: **/ (root)**
- Save

**¡Tu app estará en:** `https://TU-USUARIO.github.io/xml-viewer/`

---

## Para Probar Localmente

Simplemente abre `index.html` en tu navegador. ¡Eso es todo!

---

## Estructura de Archivos

```
xml-viewer/
├── index.html          ← ¡Archivo principal! Abre esto
├── ejemplo.xml         ← Archivo de prueba
├── README.md           ← Documentación completa
└── flask-version/      ← Versión Python (opcional)
```

---

**¿Dudas?** Lee `README.md` o `GITHUB_PAGES.md` 📖
