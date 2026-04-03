<div align="center">

<img src="./img/logo.png" width="150" style="border-radius: 20%"/>

# 🎬 Multiplus+

### Plataforma de entretenimiento para ver **Series**, **Películas** y **Anime**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)](https://jquery.com/)


![Tipo](https://img.shields.io/badge/Tipo-Frontend%20Estático-4CC9F0?style=flat-square)


</div>

---

## 📖 Descripción

**Multiplus** es una plataforma web de entretenimiento que simula un servicio de streaming. Permite navegar por catálogos de **series**, **películas** y **anime**, ver fichas de detalle de cada título y reproducir contenido directamente desde el navegador.

> 🚫 No requiere backend ni base de datos — es 100% frontend estático.

---

## ✨ Características

| Característica | Descripción |
|---|---|
| 📱 **Responsive** | Adaptado para móvil, tablet y escritorio |
| 🎠 **Carrusel animado** | Hero interactivo con Owl Carousel en la página de inicio |
| ▶️ **Reproductor de video** | Integrado con Plyr en todas las páginas de reproducción |
| 🔍 **Filtrado de contenido** | Filtros animados por categorías usando MixItUp |
| 🍔 **Menú hamburguesa** | Navegación móvil con SlickNav |
| 🎨 **SASS Modular** | Arquitectura SCSS con variables, mixins y parciales |
| 🔐 **Login & Registro** | Formularios de autenticación estilizados |
| 🎌 **Anime, Series & Películas** | Tres categorías de contenido con páginas propias |

---

## 🛠️ Tecnologías utilizadas

### Base

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" title="HTML5"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" title="CSS3"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" title="JavaScript"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" width="50" title="SASS"/>

</div>

| Tecnología | Rol |
|---|---|
| **HTML5** | Estructura de todas las páginas |
| **CSS3** | Estilos base y animaciones |
| **JavaScript (ES6)** | Lógica e interactividad |
| **SASS / SCSS** | Estilos modulares con variables, mixins y parciales |

---

### Frameworks & Librerías

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="50" title="Bootstrap 4"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" width="50" title="jQuery"/>

</div>

| Librería | Versión | Rol |
|---|---|---|
| **Bootstrap** | 4.x | Grid responsive y componentes UI |
| **jQuery** | 3.3.1 | Manipulación del DOM y base para plugins |

---

### Plugins

| Plugin | Archivo | Rol |
|---|---|---|
| **Plyr** | `plyr.css` / `player.js` | Reproductor de video personalizado |
| **Owl Carousel** | `owl.carousel.min.js` | Carruseles de contenido animados |
| **MixItUp** | `mixitup.min.js` | Filtrado animado por categorías |
| **SlickNav** | `jquery.slicknav.js` | Menú hamburguesa para móviles |
| **Nice Select** | `jquery.nice-select.min.js` | Selectores de formulario estilizados |

---

### Iconografía & Fuentes

<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/Font_Awesome_5_logo.svg/200px-Font_Awesome_5_logo.svg.png" width="50" title="Font Awesome"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="50" title="Google Fonts"/>

</div>

| Recurso | Uso |
|---|---|
| **Font Awesome** | Iconografía general |
| **Elegant Icons** | Iconos decorativos adicionales |
| **Google Fonts** | Tipografías web importadas |

---

### Entorno de desarrollo

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="50" title="VS Code"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50" title="Git"/>
&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="50" title="GitHub"/>

</div>

| Herramienta | Uso |
|---|---|
| **VS Code** | Editor principal |
| **Git** | Control de versiones |
| **GitHub** | Repositorio y colaboración |

---

## 📄 Páginas del sitio

```
🏠  index.html                          → Página principal
│
├── 🎌  pages/categories/anime/
│   ├── Anime Categories.html           → Catálogo anime (pág. 1)
│   ├── Anime Categories2.html          → Catálogo anime (pág. 2)
│   ├── details animes/
│   │   └── anime details.html          → Ficha de detalle
│   └── watch animes/
│       └── watch anime.html            → Reproductor
│
├── 🎬  pages/categories/movies/
│   ├── Movie Categories.html           → Catálogo películas (pág. 1)
│   ├── Movie Categories2.html          → Catálogo películas (pág. 2)
│   ├── Movie Categories3.html          → Catálogo películas (pág. 3)
│   ├── details movie/
│   │   ├── movie detail1.html
│   │   ├── movie detail2.html
│   │   └── movie detail3.html
│   └── watch movie/
│       └── watch movie1.html           → Reproductor
│
├── 📺  pages/categories/series/
│   ├── Series Categories.html          → Catálogo series (pág. 1)
│   ├── Series Categories2.html         → Catálogo series (pág. 2)
│   ├── Series Categories3.html         → Catálogo series (pág. 3)
│   ├── details series/
│   │   └── serie detail.html           → Ficha de detalle
│   └── watch series/
│       └── Ver Serie.html              → Reproductor
│
└── 🔐  pages/menu/
    ├── login.html                      → Inicio de sesión
    ├── Register.html                   → Registro de usuario
    └── About us.html                   → Información del sitio
```

---

## 🗂️ Estructura de archivos

```
Multiplus/
├── index.html
├── css/
│   ├── style.css
│   ├── bootstrap.min.css
│   ├── font-awesome.min.css
│   ├── elegant-icons.css
│   ├── owl.carousel.min.css
│   ├── plyr.css
│   ├── nice-select.css
│   └── slicknav.min.css
├── sass/
│   ├── style.scss
│   ├── _variable.scss
│   ├── _base.scss
│   ├── _mixins.scss
│   ├── _header.scss
│   ├── _footer.scss
│   ├── _hero.scss
│   ├── _product.scss
│   ├── _breadcrumb.scss
│   ├── _login.scss
│   ├── _signup.scss
│   ├── _anime-details.scss
│   ├── _anime-watching.scss
│   ├── _blog.scss
│   ├── _blog-details.scss
│   └── _responsive.scss
├── js/
│   ├── main.js
│   ├── player.js
│   ├── jquery-3.3.1.min.js
│   ├── bootstrap.min.js
│   ├── owl.carousel.min.js
│   ├── mixitup.min.js
│   ├── jquery.slicknav.js
│   └── jquery.nice-select.min.js
├── fonts/
└── img/
    ├── logo.png
    └── inicio/
        ├── carrusel/
        ├── 1tendencia_ahora/
        ├── 2mas_populares/
        ├── 3agregados_recientemente/
        ├── 4recomendados/
        ├── 5top_vistas/
        └── 6mas_comentado/
```

---

## 🚀 Cómo ejecutar

**Opción 1 — Directo**
```
Doble click en index.html
```

**Opción 2 — Live Server (recomendado)**
```
Click derecho en index.html → "Open with Live Server"
```

**Opción 3 — Python**
```bash
python -m http.server 8000
# Luego ir a: http://localhost:8000
```

> ⚠️ Se recomienda un servidor local para evitar problemas con rutas relativas.

---

## 🧩 Arquitectura SASS

```
sass/
├── _variable.scss       → Variables globales (colores, tipografía, breakpoints)
├── _mixins.scss         → Mixins reutilizables
├── _base.scss           → Reset y estilos base
├── _header.scss         → Cabecera y navegación
├── _hero.scss           → Banner/carrusel principal
├── _product.scss        → Cards de contenido
├── _breadcrumb.scss     → Migas de pan
├── _footer.scss         → Pie de página
├── _login.scss          → Formulario de inicio de sesión
├── _signup.scss         → Formulario de registro
├── _anime-details.scss  → Página de detalle de anime
├── _anime-watching.scss → Vista de reproducción
├── _blog.scss           → Sección blog
├── _blog-details.scss   → Detalle de post
├── _responsive.scss     → Media queries
└── style.scss           → Archivo principal
```

---

<div align="center">

**Multiplus** · Proyecto Académico · Carrera de Informática — UMSA

</div>