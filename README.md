# Instagram Feed Clone

Este proyecto es un clon de un feed de Instagram, implementado con tecnologías web modernas. La aplicación muestra publicaciones en dos formatos diferentes: una vista de cuadrícula (3 fotos por fila) y una vista de lista (1 foto por fila con detalles).

## Características principales

- **Dos modos de visualización**: 
  - Vista de cuadrícula (estilo Instagram)
  - Vista de lista con detalles de publicación
- **Responsive design**: Se adapta a diferentes tamaños de pantalla
- **Componentes interactivos**:
  - Modal para crear nuevas publicaciones
  - Menú desplegable de configuración
  - Pestañas para cambiar entre vistas

## Tecnologías utilizadas

- **HTML5**: Estructura semántica del documento
- **CSS3**: Estilos personalizados y responsive design
- **Bootstrap 5**: Framework para el diseño y componentes UI
  - Sistema de grid responsive
  - Componentes como modales, dropdowns y tabs
  - Utilización de Bootstrap Icons
- **Font Awesome**: Iconos adicionales
- **JavaScript**: Interactividad básica (a través de Bootstrap)

## Estructura del proyecto

1. **Barra de navegación superior**: 
   - Logo de Instagram
   - Botón para crear nueva publicación (modal)
   - Menú desplegable de configuración

2. **Modal de nueva publicación**:
   - Área para descripción
   - Botones para añadir foto y ubicación

3. **Contenido principal**:
   - Selector de vista (cuadrícula o lista)
   - Galería de publicaciones:
     - Vista cuadrícula: 3 columnas en pantallas grandes, 2 en medianas, 1 en pequeñas
     - Vista lista: Publicaciones individuales con título, imagen y descripción

## Personalización CSS

Se han añadido estilos personalizados para:
- Ajustar la altura de las imágenes de la galería
- Personalizar el aspecto de las pestañas de navegación
- Mejorar la experiencia de usuario en diferentes dispositivos

## Cómo ejecutar

Simplemente abre el archivo `index.html` en cualquier navegador web moderno.