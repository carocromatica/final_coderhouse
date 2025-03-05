# Proyecto Portafolio de Caro
# Entrega final curso desarrollo web Coderhouse

## Descripción
Este es mi prototipo de portafolio personal, donde muestro mis proyectos y habilidades en diseño y desarrollo web. Está construido utilizando HTML y SASS, con una estructura modular y organizada para facilitar la escalabilidad y el mantenimiento. El propósito de este proyecto es aplicar buenas prácticas de desarrollo web aprendidas en **Coderhouse** y asi optimizar la experiencia de usuario desde una perspectiva más técnica en proyectos posteriores.

## 🌍 Deploy del Proyecto

El portafolio está desplegado en las siguientes plataformas:

- 🌎 **Netlify**: [carocromatica.netlify.app](https://carocromatica.netlify.app/)
- 🚀 **GitHub Pages**: [carocromatica.github.io/final_coderhouse](https://carocromatica.github.io/final_coderhouse/)



## 🚀 Tecnologías utilizadas
- **HTML5** → Para la estructura semántica del sitio.
- **SASS** (SCSS) → Para estilos organizados y reutilizables.
- **AOS** (Animate On Scroll) → Para animaciones de entrada elegantes al hacer scroll.
- **JavaScript** → Para funcionalidades interactivas.
- **SEO** Optimizado → Configuración de metadatos y etiquetas adecuadas para mejorar la visibilidad en buscadores.
-  **Open Graph (OG)** para mejorar la visualización del sitio en redes sociales, permitiendo una mejor presentación de imágenes y descripciones en redes sociales.
- **Netlify** → Implementación continua y hosting del portafolio.

- **Google Analytics & Hotjar** → Se implementaron para el seguimiento del comportamiento de usuarios, pero quedaron **comentados** en el código, ya que impactaban en el rendimiento de la página.

## Estructura del Repositorio
```
📦 📁 [nombre-del-repositorio]
│── 📁 assets                 # Recursos como imágenes, iconos y otros elementos gráficos
│── 📁 css                    # Archivos CSS y mapas de fuente generados
│   ├── main.css
│   ├── main.css.map
│── 📁 js                     # Archivos JavaScript
│   ├── analytics.js
│   ├── hotjar.js
│── 📁 sass                   # Archivos fuente SASS/SCSS organizados por secciones
│   ├── 📁 components         # Componentes reutilizables de la UI
│   │   ├── _buttons.scss
│   │   ├── _cards.scss
│   │   ├── _headings.scss
│   │   ├── _navbar.scss
│   │   ├── _overlay.scss
│   │   ├── _skip-link.scss
│   │   ├── _video.scss
│   ├── 📁 foundations        # Estilos base como reseteo y variables globales
│   │   ├── _reset.scss
│   │   ├── _variables.scss
│   ├── 📁 layout             # Estilos de secciones específicas de la página
│   │   ├── _bento.scss
│   │   ├── _blobs.scss
│   │   ├── _experience-section.scss
│   │   ├── _footer.scss
│   │   ├── _hero-section.scss
│   │   ├── _hero-services.scss
│   │   ├── main.scss         # Archivo SASS principal que importa todos los estilos
│── 📄 .gitignore             # Archivos y carpetas ignoradas por Git
│── 📄 LICENSE                # Licencia del proyecto
│── 📄 README.md              # Documentación del proyecto
│── 📄 index.html             # Página principal del sitio
│── 📄 bento.html             # Página relacionada con "Bento"
│── 📄 contacto.html          # Página de contacto
│── 📄 envo.html              # Página relacionada con "Envo"
│── 📄 kibernum.html          # Página relacionada con "Kibernum"
│── 📄 servicios.html         # Página de servicios

```

##  Detalle entrega final  

- Se ha desarrollado un sitio web con **5 páginas**:  
  - 🏠 **Inicio** (`index.html`)  
  - 💼 **Servicios** (`servicios.html`)  
  - 📞 **Contacto** (`contacto.html`)  
  - 📁 **Proyectos** (`kibernum.html`, `envo.html`)  

- La estructura HTML sigue las **buenas prácticas de SEO**, con etiquetas semánticas y atributos optimizados.  
- Se implementó **Bootstrap** para la maquetación y el diseño responsive.
- Se incorporó un **"Bento Layout"** en la sección de **servicios**, siguiendo las tendencias actuales de diseño web.  
- Se usó **SASS (SCSS)** para estructurar y organizar los estilos de manera modular y eficiente.  
- Se agregaron **animaciones con AOS (Animate On Scroll)** para mejorar la experiencia de usuario en el `index.html`.  
- Se realizaron **tests de accesibilidad** para mejorar la usabilidad y la experiencia de los usuarios.  
- El sitio fue **subido a Netlify y GitHub Pages**, garantizando accesibilidad pública.  
- Se verificaron y corrigieron rutas para asegurar que las imágenes, estilos y enlaces funcionen correctamente después del deploy.  
- Se optimizaron **imágenes y archivos** para mejorar la velocidad de carga y el rendimiento del sitio.  
- 📷 **Optimización de imágenes**: Se crearon versiones en **formato WebP** para mejorar la carga del sitio sin sacrificar calidad.  
- Se incorporaron **Google Analytics y Hotjar**, pero quedaron comentados para evitar impacto en el rendimiento. 

## 📊 Rendimiento del Sitio  

El análisis de performance se realizó sin **Google Analytics ni Hotjar**, ya que estos servicios afectan la velocidad de carga del sitio.  

Puedes ver la vista previa del rendimiento en el siguiente enlace:  
[🔗 Ver imagen](assets/rendimiento_lighthouse.png)


## Próximos Pasos
- Se realizarán mejoras en la performance del sitio, principalmente optimizando el uso de los cdn
- Actualiación de Analytics y Hotjar con nueva url
- Se investigará como mejorar el rendimiento utilizando herramientas de terceros, como Analytics y Hotjar para no generar problemas de cookies de terceros.
- Incorporación de mensaje de uso de cookies y autorizacion. Para ello se investigará como implementar dicha funcionalidad.
- Se incorporarán nuevas páginas con proyectos.

---
_Última actualización: [mie, 05 de marzo]_
