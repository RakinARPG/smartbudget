# SmartBudget

SmartBudget es una landing page para una aplicación de finanzas personales, diseñada para presentar de forma clara y atractiva las principales funcionalidades del producto.

El objetivo del proyecto es aplicar buenas prácticas de maquetado, organización de estilos y control de versiones utilizando tecnologías modernas de desarrollo frontend.

---

## 🚀 Demo

El proyecto puede ejecutarse de forma local abriendo el archivo `index.html` en el navegador.

---

## Tecnologías utilizadas

- **HTML5 semántico**
- **SASS (SCSS)**
- **CSS Grid & Flexbox**
- **Metodología BEM + SMACSS**
- **Patrón de arquitectura SASS 7–1**
- **Git & GitHub**

---

## Estructura del proyecto

```plaintext
smartbudget/
├── index.html
├── css/
│   └── main.css
├── sass/
│   ├── abstracts/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   ├── states/
│   ├── themes/
│   ├── vendors/
│   └── main.scss
├── README.md
└── .gitignore
```

## Desiciones técnicas

## Metodología CSS

Se utilizó BEM (Block, Element, Modifier) para la nomenclatura de clases, ya que permite una estructura clara, reutilizable y fácil de mantener.
Para los estados visuales (por ejemplo, links activos), se aplicó la convención SMACSS mediante clases como is-active, separando el estado del componente de su estructura.

## SASS y patrón 7–1

Se implementó SASS con el patrón 7–1 para organizar los estilos según su responsabilidad.
Esta estructura facilita la escalabilidad del proyecto y permite mantener los estilos ordenados a medida que el sitio crece.

## Layout y diseño

CSS Grid se utilizó en la sección de features para lograr una distribución flexible y responsive de las cards.

Flexbox se utilizó en el navbar y el hero para alinear y distribuir elementos de forma sencilla y controlada.

## Resposive Design

El diseño se abordó con una estrategia mobile-first, utilizando media queries para mejorar la experiencia en pantallas medianas y grandes sin romper la estructura base.

## Control de versionsa

Se utilizó Git desde el inicio del proyecto, realizando commits pequeños y descriptivos.
Se siguió una convención básica de commits:

feat: nuevas funcionalidades

fix: correcciones

chore: tareas de mantenimiento

docs: documentación

Esto permite mantener un historial claro y fácil de seguir


## Autor

RakinARPG
