# 🚀 Portfolio de Data Science

Este es mi portfolio profesional creado con **Jekyll** y publicado en **GitHub Pages**.  
Incluye secciones de presentación, proyectos, blog técnico y contacto.  

Puedes verlo online aquí: [https://JacquetAlexis23.github.io](https://JacquetAlexis23.github.io)

---

## 📂 Estructura del repositorio

```
_portfolio/
├── _config.yml          # Configuración principal de Jekyll
├── index.md             # Página de inicio
├── about.md             # Sobre mí
├── projects.md          # Proyectos destacados
├── blog.md              # Blog técnico
├── contact.md           # Contacto
├── _posts/              # Artículos del blog (en formato Markdown)
│   └── 2024-09-15-deep-cnn-sentiment-analysis.md
├── assets/              # Imágenes, CSS, JS
│   ├── css/
│   │   └── style.css    # Estilos personalizados
│   ├── images/          # Imágenes del portfolio
│   ├── icons/           # Iconos de tecnologías
│   └── blog/            # Imágenes para artículos
└── README.md            # Este archivo
```

---

## ⚙️ Requisitos previos

Necesitas tener instalado en tu máquina:

- [Ruby](https://www.ruby-lang.org/en/downloads/) (>= 2.7)
- [Jekyll](https://jekyllrb.com/docs/installation/) y Bundler:

```bash
gem install jekyll bundler
```

---

## ▶️ Cómo correr el sitio localmente

1. **Clona el repositorio:**
```bash
git clone https://github.com/JacquetAlexis23/portfolio.git
cd portfolio/_portfolio
```

2. **Instala dependencias:**
```bash
bundle install
```

3. **Corre el servidor local:**
```bash
bundle exec jekyll serve
```

4. **Abre en tu navegador:**
```
http://localhost:4000
```

---

## 🌐 Publicación en GitHub Pages

### Opción 1: Repositorio principal (recomendado)

1. **Crea un repositorio con el nombre:**
   ```
   JacquetAlexis23.github.io
   ```

2. **Sube la carpeta `_portfolio` como contenido principal:**
   ```bash
   cd _portfolio
   git init
   git add .
   git commit -m "Initial portfolio setup"
   git branch -M main
   git remote add origin https://github.com/TuUsuario/TuUsuario.github.io.git
   git push -u origin main
   ```

3. **Ve a Settings > Pages:**
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`

4. **Tu sitio estará disponible en:**
   ```
   https://TuUsuario.github.io
   ```

### Opción 2: Repositorio de proyecto

1. **Sube el repositorio con cualquier nombre:**
   ```
   portfolio
   ```

2. **Ve a Settings > Pages:**
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/_portfolio`

3. **Tu sitio estará disponible en:**
   ```
   https://TuUsuario.github.io/portfolio
   ```

---

## ✏️ Personalización

### 1. Configuración básica

Edita `_config.yml` para cambiar:
- Título y descripción del sitio
- Tu información personal (email, LinkedIn, GitHub)
- URLs y configuraciones de Jekyll

```yaml
title: "Tu Nombre - Data Scientist"
author: "Tu Nombre"
email: "tu-email@gmail.com"
description: "Tu descripción profesional"
url: "https://TuUsuario.github.io"
linkedin_username: "tu-perfil-linkedin"
github_username: "TuUsuario"
```

### 2. Información personal

Actualiza los siguientes archivos:
- `about.md`: Tu biografía, skills y experiencia
- `contact.md`: Información de contacto y formulario
- `index.md`: Presentación en la página principal

### 3. Proyectos

Edita `projects.md` para agregar tus proyectos:

```markdown
### 🎯 [Nombre del Proyecto](https://github.com/usuario/repo)
**Descripción breve** | Tecnologías utilizadas
- **Tech Stack**: Python, TensorFlow, etc.
- **Impacto**: Métricas de negocio
- **ROI**: Retorno de inversión estimado
```

### 4. Blog

Agrega nuevos posts en la carpeta `_posts/` con formato:
```
YYYY-MM-DD-titulo-del-post.md
```

Ejemplo de post:
```markdown
---
layout: post
title: "Título del Artículo"
date: 2024-10-02
categories: [machine-learning, data-science]
tags: [Python, TensorFlow, CNN]
author: "Tu Nombre"
excerpt: "Breve descripción del artículo"
---

Contenido del artículo en Markdown...
```

### 5. Imágenes

Organiza las imágenes en `assets/`:
```
assets/
├── profile.jpg           # Tu foto de perfil
├── projects/            # Imágenes de proyectos
│   ├── sentiment-analysis.jpg
│   ├── business-analytics.jpg
│   └── translator.jpg
├── blog/               # Imágenes para artículos
└── icons/              # Iconos de tecnologías
```

---

## 🎨 Personalización de Estilos

### Colores principales

Edita las variables CSS en `assets/css/style.css`:

```css
:root {
  --primary-color: #2c3e50;      /* Color principal */
  --secondary-color: #3498db;     /* Color secundario */
  --accent-color: #e74c3c;        /* Color de acento */
  --success-color: #27ae60;       /* Color de éxito */
  
  /* Personaliza según tu marca personal */
}
```

### Fuentes

Cambia las fuentes en las variables CSS:
```css
:root {
  --font-primary: 'Inter', sans-serif;
  --font-secondary: 'JetBrains Mono', monospace;
}
```

### Layout responsive

El diseño es completamente responsive y se adapta a:
- 🖥️ Desktop (1200px+)
- 💻 Laptop (768px-1199px)
- 📱 Tablet (481px-767px)
- 📱 Mobile (≤480px)

---

## 📊 Funcionalidades incluidas

### ✅ Características principales

- **📱 Responsive Design**: Se adapta a todos los dispositivos
- **🔍 SEO Optimizado**: Meta tags, sitemap, robots.txt
- **⚡ Performance**: Imágenes optimizadas, CSS minificado
- **🎨 Animaciones suaves**: Transiciones y hover effects
- **📧 Formulario de contacto**: Listo para integrar con servicios
- **🏷️ Filtros de proyectos**: JavaScript para filtrar por categorías
- **📝 Blog integrado**: Sistema de posts con categorías y tags
- **🌙 Dark mode**: Soporte opcional para tema oscuro

### 🛠️ Componentes reutilizables

- **Hero Section**: Presentación principal con foto y CTA
- **Stats Grid**: Métricas destacadas en números
- **Project Cards**: Tarjetas de proyectos con hover effects
- **Skill Bars**: Barras de progreso para habilidades
- **Contact Form**: Formulario completo de contacto
- **Filter Buttons**: Sistema de filtros para proyectos
- **Social Links**: Enlaces a redes sociales

---

## 🚀 Optimización y Performance

### SEO

El portfolio incluye optimización SEO completa:
- Meta descriptions únicas por página
- Open Graph tags para redes sociales
- Schema.org markup para mejor indexación
- Sitemap.xml automático
- URLs amigables

### Performance

- CSS y JavaScript minificados
- Imágenes optimizadas (WebP cuando sea posible)
- Lazy loading para imágenes
- Compresión Gzip habilitada
- Cache headers optimizados

### Analytics (opcional)

Agrega Google Analytics editando `_config.yml`:
```yaml
google_analytics: "UA-XXXXXXXXX-X"
```

---

## 🔧 Solución de problemas

### El sitio no se construye

1. **Verifica la sintaxis YAML** en `_config.yml`
2. **Revisa los nombres de archivos** en `_posts/`
3. **Comprueba las rutas de imágenes** sean correctas

### Estilos no se aplican

1. **Limpia la cache** del navegador
2. **Verifica la ruta del CSS** en `_config.yml`
3. **Rebuilda el sitio** con `bundle exec jekyll build --force`

### Imágenes no cargan

1. **Usa rutas absolutas** comenzando con `/assets/`
2. **Verifica nombres de archivo** (case-sensitive)
3. **Comprueba permisos** de archivos

---

## 🆕 Actualizaciones futuras

### Funcionalidades planeadas

- [ ] **Modo oscuro/claro**: Toggle dinámico
- [ ] **Búsqueda en blog**: Función de búsqueda con Lunr.js
- [ ] **Comentarios**: Sistema de comentarios con Disqus
- [ ] **Newsletter**: Integración con Mailchimp
- [ ] **PWA**: Progressive Web App capabilities
- [ ] **Multiidioma**: Soporte para español/inglés

### Integraciones adicionales

- [ ] **Formulario de contacto**: Netlify Forms o Formspree
- [ ] **Analytics avanzado**: Google Analytics 4
- [ ] **A/B Testing**: Google Optimize
- [ ] **Chat widget**: Integración con chatbot

---

## 📞 Contacto y soporte

Si necesitas ayuda con la configuración o personalización:

- 📧 **Email**: [tu-email@gmail.com](mailto:tu-email@gmail.com)
- 💼 **LinkedIn**: [linkedin.com/in/tu-perfil](https://linkedin.com/in/tu-perfil)
- 🐙 **GitHub**: [github.com/TuUsuario](https://github.com/TuUsuario)

---

## 📜 Licencia

Este portfolio está bajo la licencia MIT. Siéntete libre de usarlo como base para tu propio portfolio.

---

**💡 Tip profesional**: Mantén tu portfolio actualizado regularmente. Agrega nuevos proyectos, actualiza tu información y publica artículos en el blog para mantener el sitio fresco y relevante.

¡Mucha suerte con tu carrera en Data Science! 🚀