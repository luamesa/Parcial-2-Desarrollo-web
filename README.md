# Portafolio Personal — Luis Mesa

Portafolio web personal desarrollado como proyecto académico de desarrollo web.

La aplicación presenta información profesional y académica, proyectos realizados, lenguajes de programación y áreas de interés mediante una interfaz web responsive.

## Características

* Hoja de vida web personal.
* Presentación de información académica y profesional.
* Sección de proyectos.
* Sección de habilidades y tecnologías.
* Áreas de interés profesional.
* Navegación mediante menú responsive.
* Diseño adaptable a dispositivos móviles.
* Animaciones al realizar scroll.
* Interfaz basada en componentes de Bootstrap.
* Efectos visuales mediante CSS y JavaScript.

## Tecnologías

* HTML5
* CSS3
* JavaScript
* Bootstrap
* Responsive Web Design
* Intersection Observer API

## Estructura del proyecto

```text
Parcial-2-Desarrollo-web/
│
├── css/
│   └── bootstrap.min.css
│
├── imagenes/
│   ├── logohoddie.png
│   ├── IMG_5662.jpg
│   └── ...
│
├── js/
│   └── bootstrap.min.js
│
└── index.html
```

## Secciones

### Inicio

Presentación personal con fotografía, nombre y perfil académico.

### Información personal

Sección destinada a información de contacto y datos personales.

### Estudios

Presenta la formación académica y el estado de los estudios.

### Proyectos

Muestra proyectos desarrollados durante el proceso de formación.

### Lenguajes de programación

Presenta las principales tecnologías y lenguajes utilizados durante la formación académica.

### Áreas de interés profesional

Incluye áreas relacionadas con:

* Diseño web.
* Diseño UI/UX.
* Desarrollo Front-End.

## Diseño responsive

La interfaz utiliza Bootstrap y reglas de diseño responsive para adaptar el contenido a diferentes tamaños de pantalla.

El menú de navegación utiliza el sistema responsive de Bootstrap para dispositivos móviles.

## Animaciones

El proyecto utiliza `IntersectionObserver` para detectar cuándo las secciones ingresan al área visible de la pantalla.

Cuando una sección entra en el viewport, se agrega dinámicamente la clase:

```javascript
visible
```

Esto permite ejecutar una animación de aparición mediante CSS.

## Navegación

El sitio utiliza navegación mediante enlaces internos:

```text
Información
Estudios
Proyectos
Lenguajes
Intereses
```

Cada opción dirige a su respectiva sección de la página.

## Ejecución

Este proyecto es una aplicación web estática.

No requiere servidor backend ni base de datos.

Para ejecutarlo localmente:

1. Clonar el repositorio.
2. Abrir la carpeta del proyecto.
3. Abrir `index.html` en un navegador.

También puede publicarse mediante servicios de hosting estático como GitHub Pages o Netlify.

## Objetivo académico

El proyecto fue desarrollado para aplicar conocimientos de desarrollo web relacionados con:

* Estructura HTML.
* Diseño mediante CSS.
* Framework Bootstrap.
* JavaScript.
* Diseño responsive.
* Manipulación del DOM.
* Animaciones e interacción.
* Organización de recursos web.

## Autor

**Luis Mesa**

Estudiante de Ingeniería Informática.
