# Portafolio Personal (MPA) - HTML y CSS

Este es el proyecto de un portafolio web personal, diseñado como una **Aplicación de Múltiples Páginas (MPA)**. El objetivo es crear una estructura limpia, minimalista y fácil de navegar, utilizando únicamente **HTML5** y **CSS3** puros, sin frameworks ni preprocesadores.

## 🎨 Diseño y Estilo

El diseño se basa en los siguientes principios:

* **Minimalismo:** Interfaces limpias, con amplio espacio en blanco y sin elementos decorativos innecesarios.
* **Monocromático:** Se utiliza una paleta de colores estricta basada en tonos de azul.
* **Placeholders (Skeletons):** No se utilizan imágenes o iconos reales. En su lugar, se emplean "esqueletos" (bloques de color sólido, generalmente un tono claro de la paleta) para marcar dónde irían los elementos visuales.
* **Tipografía:** Se utiliza `Roboto Mono` en todo el sitio para mantener una estética técnica y limpia.
* **Sin Gradientes:** El diseño se basa únicamente en colores sólidos.

## 🛠️ Stack Tecnológico

* **HTML5:** Para la estructura semántica de las diferentes páginas.
* **CSS3:** Para los estilos, el layout (posiblemente usando Flexbox o Grid) y la adherencia a la paleta de colores.

## 📂 Estructura de Archivos

El proyecto sigue una organización de carpetas clara para separar los recursos:
```
proyecto-portafolio/
├── index.html
├── src/
│   ├── html/
│   │   ├── about.html
│   │   ├── projects.html
│   │   ├── profile.html
│   │   ├── contact.html
│   ├── css/
│   │   ├── main.css
│   │   ├── about.css
│   │   ├── projects.css
│   │   ├── profile.css
│   │   ├── contact.css
│   └── images/│
└── README.md
```

## 🗺️ Arquitectura de Páginas (MPA)

La navegación se gestiona a través de enlaces directos a los diferentes archivos HTML, con una barra de navegación consistente en todas las vistas.

### 1. `index.html` (Landing Page / Inicio)

* **Ruta:** `/index.html` (Raíz del proyecto)
* **Propósito:** Es la página de aterrizaje principal.
* **Contenido:** Muestra una introducción breve y concisa. Incluye un título principal (ej. "Hola, soy [Tu Nombre]"), un subtítulo (ej. "Desarrollador de Software") y una breve descripción introductoria. Puede incluir un botón (CTA - Call to Action) que invite a ver los proyectos.

### 2. `about.html` (Sobre Mí)

* **Ruta:** `/src/html/about.html`
* **Propósito:** Combina la información profesional y académica en una sola vista.
* **Contenido:**
    * **Sección de Experiencia:** Un listado cronológico de la experiencia laboral. Cada ítem mostrará el puesto, la empresa y las fechas, seguido de una breve descripción de las responsabilidades.
    * **Sección de Educación:** Un listado de la formación académica y certificaciones relevantes, mostrando el título, la institución y las fechas.

### 3. `projects.html` (Proyectos)

* **Ruta:** `/src/html/projects.html`
* **Propósito:** Vista independiente dedicada a mostrar los proyectos desarrollados.
* **Contenido:** Se presenta como una galería (probablemente en formato de *grid*). Cada proyecto tendrá una "tarjeta" que incluirá:
    * Un *placeholder* (esqueleto) rectangular grande para la imagen del proyecto.
    * Título del proyecto.
    * Breve descripción.
    * Enlaces (ej. "Código Fuente", "Ver Demo").

### 4. `profile.html` (Perfil Personal)

* **Ruta:** `/src/html/profile.html`
* **Propósito:** Una vista tipo "Perfil de Usuario" con información personal y de contacto básico.
* **Contenido:**
    * Un *placeholder* grande (circular o cuadrado) para una foto de perfil.
    * Datos personales clave (Nombre, Ubicación).
    * Un párrafo de "Bio" más personal o un resumen profesional.
    * Quizás un listado simple de habilidades o tecnologías principales.

### 5. `contact.html` (Formulario de Contacto)

* **Ruta:** `/src/html/contact.html`
* **Propósito:** Página independiente con un formulario para que los visitantes puedan enviar un mensaje.
* **Contenido:** Un formulario HTML estándar (que, al no tener backend, usará un `mailto:` o simplemente servirá como maqueta estática).
    * Campo: Nombre
    * Campo: Email
    * Campo: Asunto
    * Campo: Mensaje (textarea)
    * Botón: Enviar

## 🎨 Paleta de Colores (Monocromática)

* **Fondo (Más claro):** `#eff8ff`
* **Fondos secundarios/Hover:** `#daefff`, `#bee3ff`
* **Bordes/Acentos:** `#91d3ff`, `#5ebafc`
* **Botones/Enlaces (Primario):** `#389af9`, `#227dee`
* **Texto (Más oscuro):** `#1e4c94`, `#162c55`
* **Placeholders (Skeletons):** Se usará un tono claro como `#bee3ff` o `#daefff` para simular la carga.

## ✒️ Tipografía

* **Fuente Principal:** `Roboto Mono` (se debe importar vía Google Fonts o alojar localmente).