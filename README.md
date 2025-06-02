# ev2_jorquera-ugalde
# Evaluación Parcial 2 - AVY1101

## Nombre: Valentina Jorquera, Antonella Ugalde  
## Carrera: Informática Biomédica  
## Ramo: Big Data 
## Docente: Fernando Fuentes
## Fecha: 01/06/2025

---

## 🧠 Introducción

En esta evaluación puse en práctica los conocimientos adquiridos durante las sesiones de clases, especialmente los relacionados con el desarrollo web utilizando HTML y CSS. El objetivo fue construir un sitio web básico con estructura y estilo, aplicando buenas prácticas de codificación y diseño.

---

## 🛠️ Desarrollo del Proyecto

### 🗂️ Estructura del Sitio Web

Para la construcción del sitio utilicé los siguientes archivos:

- `index.html`: archivo principal que contiene la estructura del sitio.
- `style.css`: archivo de estilos utilizado para mejorar la presentación.

### 🧱 HTML

El documento HTML contiene las siguientes secciones:

- Encabezado con título principal (`<h1>`) y subtítulos.
- Navegación con enlaces (`<nav>` y `<a>`).
- Contenido principal con párrafos e imágenes.
- Pie de página (`<footer>`).

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi Sitio Web</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Bienvenidos a mi sitio</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#sobre-mi">Sobre mí</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>
  <main>
    <section id="inicio">
      <p>Este es un sitio de ejemplo construido con HTML y CSS.</p>
    </section>
  </main>
  <footer>
    <p>Creado por Antonella Ugalde</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
  color: #333;
  margin: 0;
  padding: 0;
}
header {
  background-color: #5C6BC0;
  color: white;
  padding: 1em;
  text-align: center;
}
nav a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
}
