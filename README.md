# Portafolio Web - Proyecto de Práctica en HTML y CSS
Este proyecto es una simulación de un portafolio funcional desarrollado para poner en práctica conceptos de HTML y CSS. La estructura incluye secciones como presentación personal, habilidades, servicios, proyectos y contacto.

## ✨ Características Principales
- Diseño responsivo
- Secciones interactivas con efectos hover
- Animaciones CSS personalizadas
- Formulario de contacto funcional
- Integración con redes sociales
- Diseño modular y fácil de personalizar
- Optimizado para SEO básico

## 🛠 Tecnologías Utilizadas
- **HTML5** (Estructura semántica)
- **CSS3** (Estilos avanzados)
- Google Fonts (Tipografía)
- Boxicons (Iconos modernos)
- CSS Variables (Personalización temática)

## 📌 Conceptos HTML Implementados
1. **Estructura Semántica**
   - Uso de `<header>`, `<section>`, `<footer>`
   - Etiquetas semánticas para mejor SEO
   - Sistema de navegación con anclajes
2. **Meta Tags para Responsividad**
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```
3. **Integración de Recursos Externos**
    - Fuentes de Google Fonts
    - Iconos de Boxicons
    - Sistema de archivos organizado

## 🎨 Conceptos CSS Destacados
1. **Custom Properties (Variables CSS)**
    ```css
    :root {
        --main-color: #ff5733;
        --bg-color: #f7f7f7;
    }
    ```
2. **Flexbox para Layouts**
    - Diseños flexibles
    - Alineación precisa
    - Distribución de espacios
3. **Efectos y Transiciones**
    ```css
    .social-media a:hover {
        transform: scale(1.2) translateY(-1rem);
        transition: .3s ease;
    }
    ```
4. **Animaciones con Keyframes**
    ```css
    Copy
    @keyframes floatImage {
        0% { transform: translateY(0); }
        50% { transform: translateY(-2.4rem); }
        100% { transform: translateY(0); }
    }
    ```
5. **Diseño Responsivo**
    - Unidades relativas (rem, vw)
    - Media Queries implícitas
    - Contenido adaptable

## 🚀 Instalación
1. Clonar el repositorio
    ````bash
    git clone https://github.com/tu-usuario/tu-portfolio.git
    ````
2. Abre index.html en tu navegador