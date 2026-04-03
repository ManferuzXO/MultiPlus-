<div align="center">

<div align="center">
  <img src="./img/logo.png" width="120" style="border-radius: 20%"/>
  <p><strong></strong></p>

### 🎬 Plataforma de entretenimiento para ver **Series**, **Películas** y **Anime**

<br/>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)


</div>

---

## 📖 Descripción

**Multiplus** es una plataforma web de entretenimiento que simula un servicio de streaming. Permite navegar por catálogos de **series**, **películas** y **anime**, ver fichas de detalle de cada título y reproducir contenido directamente desde el navegador.

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

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="50" title="HTML5"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="50" title="CSS3"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" title="JavaScript"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" width="50" title="SASS / SCSS"/>
</p>

| Tecnología | Rol |
|---|---|
| **HTML5** | Estructura de todas las páginas |
| **CSS3** | Estilos base y animaciones |
| **JavaScript (ES6)** | Lógica e interactividad |
| **SASS / SCSS** | Estilos modulares con variables, mixins y parciales por componente |

---

### Frameworks & Librerías

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="50" title="Bootstrap 4"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" width="50" title="jQuery"/>
</p>

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

<p>
  Font Awesome
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="50" title="Google Fonts"/>
</p>

| Recurso | Uso |
|---|---|
| **Font Awesome** | Iconografía general (`font-awesome.min.css`) |
| **Elegant Icons** | Iconos decorativos adicionales (`elegant-icons.css`) |
| **Google Fonts** | Tipografías web importadas |

---

### Entorno de desarrollo

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="50" title="VS Code"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50" title="Git"/>
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="50" title="GitHub"/>
</p>

| Herramienta | Uso |
|---|---|
| **VS Code** | Editor principal (incluye `.vscode/settings.json`) |
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
│   │   └── movie detail3.html          → Fichas de detalle
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
│   ├── ElegantIcons.eot / .svg / .ttf / .woff
│   └── fontawesome-webfont.eot / .svg / .ttf / .woff / .woff2
├── img/
│   ├── logo.png
│   ├── normal-breadcrumb.jpg
│   └── inicio/
│       ├── carrusel/
│       ├── 1tendencia_ahora/
│       ├── 2mas_populares/
│       ├── 3agregados_recientemente/
│       ├── 4recomendados/
│       ├── 5top_vistas/
│       └── 6mas_comentado/
└── pages/
    ├── categories/
    │   ├── anime/
    │   ├── movies/
    │   └── series/
    └── menu/
```





---

## 🧩 Arquitectura SASS

El proyecto usa una arquitectura modular SCSS con parciales separados por componente:

```
sass/
├── _variable.scss       → Variables globales (colores, tipografía, breakpoints)
├── _mixins.scss         → Mixins reutilizables
├── _base.scss           → Reset y estilos base
├── _header.scss         → Cabecera y navegación
├── _hero.scss           → Sección banner/carrusel principal
├── _product.scss        → Cards de contenido (series, películas, anime)
├── _breadcrumb.scss     → Navegación de migas de pan
├── _footer.scss         → Pie de página
├── _login.scss          → Formulario de inicio de sesión
├── _signup.scss         → Formulario de registro
├── _anime-details.scss  → Página de detalle de anime
├── _anime-watching.scss → Vista de reproducción
├── _blog.scss           → Sección blog/noticias
├── _blog-details.scss   → Detalle de post
├── _responsive.scss     → Media queries para responsive design
└── style.scss           → Archivo principal que importa todos los parciales
```

---

<div align="center">

**Multiplus** · Proyecto Académico · Carrera de Informática — UMSA

*Plataforma frontend estática de entretenimiento*

</div>#   M u l t i P l u s -  
 #   M u l t i P l u s -  
 