# Curriculum Vitae — Cristiano Ronaldo

Primer proyecto de HTML desarrollado durante el **Módulo 1** de mi formación 
en Desarrollo Front-End. Consiste en un CV ficticio de Cristiano Ronaldo, 
con 4 páginas enlazadas y estilos en CSS.

Este repositorio incluye **dos versiones** del proyecto:
- **`docs/`** — versión final del proyecto, con CSS externo y estructura corregida (publicada en GitHub Pages)
- **`version-original/`** — versión tal como la entregué en el Módulo 1, con CSS inline

La comparación entre ambas refleja mi proceso de aprendizaje y las mejoras 
que fui incorporando a medida que avanzaba.

---

## 🎯 Objetivo del ejercicio

Practicar las bases de HTML y CSS construyendo un sitio multipágina con:
- Estructura semántica (`nav`, `h1`-`h2`, `p`, `ul`, `ol`, `table`)
- Enlaces internos entre páginas
- Imágenes con texto alternativo
- Estilos aplicados con CSS

---

## 🛠️ Tecnologías usadas

- **HTML5** — estructura y contenido
- **CSS3** — estilos y presentación

---

## 📁 Estructura del proyecto

```
01-curriculum-futbolista/
├── README.md
├── docs/
│   ├── index.html
│   ├── formacion.html
│   ├── portafolio.html
│   ├── resumen.html
│   ├── css/
│   │   └── style.css
│   └── assets/
│       └── images/
└── version-original/
    ├── index.html
    ├── formacion.html
    ├── portafolio.html
    ├── resumen.html
    └── assets/
        └── images/

```

---

## 🔄 Diferencias entre versiones

| Aspecto | Versión original | Versión final |
|---|---|---|
| **CSS** | Inline (`<style>` en cada HTML) | Externo (`css/style.css`) |
| **Menú de navegación** | Tabla (`<table>`) | Semántico (`<nav>`) |
| **Atributo `lang`** | `en` (inglés) | `es` (español) |
| **Títulos `<h1>`** | Duplicados en algunas páginas | Único por página |
| **Etiquetas huérfanas** | Presentes | Corregidas |
| **`<title>`** | Faltante en algunas páginas | Presente en todas |

---

## 🧠 Aprendizajes

- Estructura básica de HTML5
- Uso de etiquetas semánticas
- Enlazado entre múltiples páginas
- Organización de archivos en carpetas (`css/`, `assets/`)
- Separación de estructura (HTML) y presentación (CSS) mediante archivo externo
- Buenas prácticas: `alt` en imágenes, `lang` correcto, rutas relativas

---

## 📅 Línea de tiempo

- **Ago 2024** — Ejercicio original del Módulo 1 de HTML (Desafío Latam)
- **Sep 2024** — Primeras mejoras
- **Sep 2026** — Revisión final: CSS externo, correcciones de estructura
- **Sep 2026** — Publicado en GitHub como primera pieza de portafolio

---

## 👤 Autor

**Joaquín Felipe Ferro Vasco**
- 🎨 Diseñador Gráfico | Desarrollador Front-End en formación
- 📧 [joaquin.ferro@gmail.com](mailto:joaquin.ferro@gmail.com)
- 🐙 [GitHub](https://github.com/JoaquinFerro)

---

*Este proyecto es parte de mi proceso de aprendizaje en desarrollo front-end. 
Agradezco cualquier comentario o sugerencia.*