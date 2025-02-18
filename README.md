# product-landing-page

## 1. Explicacion y Justificación de la Elección de la Estructura Semántica

### Header y Nav

- `<header>`: Contiene el logo y el menú de navegación, lo cual es una práctica estándar y semántica.
- `<nav>`: Específicamente para la navegación principal del sitio, con una lista (`<ul>`) que contiene los enlaces.

**Justificación**: Mejora la accesibilidad y permite que los motores de búsqueda y lectores de pantalla interpreten correctamente la estructura del sitio.

### Sección Hero

- `<section id="hero">`: Representa la primera impresión del sitio, con una imagen llamativa y un título destacado.
- `<h1 id="hero-title">`: Se usa para definir el título principal del sitio.

**Justificación**: Utilizar una sección separada mejora la claridad del contenido y la experiencia del usuario.

### Sección de Características

- `<section id="features">`: Se usa para agrupar las características del producto o servicio.
- `<div class="features-container">`: Una estructura `grid` para distribuir los elementos visualmente de manera responsiva.
- `<div class="feature-item">`: Cada característica está en su propio contenedor para facilitar la organización y escalabilidad.

**Justificación**: Separa el contenido de forma modular, haciéndolo más reutilizable y accesible.

### Sección de Envíos y Métodos de Pago

- `<section id="delivery">` y `<section id="payment-methods">`: Estas secciones organizan información importante de forma clara.

**Justificación**: Usar secciones separadas mejora la legibilidad y la mantenibilidad del código.

### Footer

- `<footer>`: Contiene la información de derechos de autor y enlaces adicionales.

- `<nav>` dentro de `<footer>`: Un submenú con enlaces legales.

**Justificación**: Mejora la usabilidad y la organización del contenido, manteniendo la coherencia con la navegación principal.

## 2. Uso de CSS para Mantener la Semántica y la Accesibilidad

- **Tipografía y colores contrastantes** (`color: #ffc107` en títulos, `color: #fff` en texto general) garantizan una buena legibilidad.
- **Uso de `gap` en flexbox y grid** para mantener la separación visual sin necesidad de márgenes innecesarios.
- **Media queries** para mejorar la adaptabilidad en dispositivos móviles, como la conversión del `grid-template-columns: repeat(2, 1fr);` a `grid-template-columns: 1fr;` en pantallas pequeñas.

## Conclusión

Esta estructura semántica es excelente porque:
 **Es accesible** (usa etiquetas correctas y contrastes adecuados).
 **Es escalable y modular** (cada sección es independiente y reutilizable).
 **Es SEO-friendly** (usa encabezados y etiquetas semánticas bien distribuidas).
 **Es responsiva** (gracias a la estructura CSS y media queries).

### Prompt Utilizado en ChatGPT

Hola ChatGPT, quiero que entres en el rol de un programador senior front-end y mejores el HTML que voy a compartir a continuación.  

Implementa el uso de estilos básicos de CSS que incluyan:  

- Espaciado y márgenes básicos  
- Padding internos  
- Márgenes entre secciones  
- Agregar 3 imágenes con `background`
