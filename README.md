# 🎨 Tailwind CSS Portfolio

Un portfolio moderno y responsivo construido con **Tailwind CSS 4.1** que demuestra el poder de los utility-first frameworks y las nuevas características de diseño.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1-38B2AC?logo=tailwind-css&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## 🚀 [Ver Demo en Vivo](https://sirmax28.github.io/tailwind-presentation/)

## ✨ Características Destacadas

### 🎭 Diseño Visual

- **Máscara Radial Avanzada**: Implementación de `mask-radial` para efectos visuales únicos
- **Gradientes Dinámicos**: Uso de gradientes personalizados para cada tecnología
- **Iconografía SVG**: Sistema de sprites optimizado para rendimiento
- **Efectos Hover Sofisticados**: Transformaciones suaves con `group-hover`

### 🛠️ Tecnologías Implementadas

#### Frontend Core

- **HTML5**: Estructura semántica y accesible
- **Tailwind CSS 4.1**: Framework utility-first con configuración personalizada
- **CSS Grid**: Layout responsivo 3x2 para showcase de tecnologías
--**CSS FlexBox**: Organiza los elementos dentro de los contenedores de manera fácil
- **SVG Sprites**: Sistema de iconos escalable y optimizado


## 🏗️ Estructura del Proyecto

```
📁 tailwind-presentation/
├── 📄 index.html              # Página principal
├── 📁 assets/
│   ├── 🎨 output.css          # CSS compilado con variables personalizadas
│   ├── 🖼️ profile-pic.jpg     # Imagen de perfil con máscara radial
│   └── 🎭 sprite.svg          # Iconos SVG de tecnologías
├── 📋 README.md               # Documentación del proyecto
└── 🚫 .gitignore              # Configuración Git
```

### Componentes Reutilizables

Secciones como:
```css
.social-button {
  @apply p-2 size-10 xs:size-12 flex items-center justify-center 
           rounded-full hover:scale-110 transition-transform;
}
```

## 🎨 Características de Diseño
Paleta de colores Profesional de ([Colors](https://coolors.co/))

### 🌈 Sistema de Colores

- **Background Gradient**: Transición suave desde rosa hasta azul oscuro
- **Tecnología Específica**: Cada card usa colores representativos de la tecnología
- **Transparencias**: Bordes semitransparentes que se integran con gradientes

### 📱 Diseño Responsivo

- **Mobile First**: Diseño optimizado para dispositivos móviles
- **Breakpoints Personalizados**: Sistema xs personalizado (350px)
- **Grid Adaptativo**: Layout que se ajusta a diferentes pantallas

- **CSS Compilado**: Un solo archivo optimizado
- **SVG Sprites**: Reducción de requests HTTP
- **Imágenes Optimizadas**: Formato y tamaño apropiados


## 👨‍💻 Autor

**Samuel Steven Bernal**

- GitHub: [@SirMax28](https://github.com/SirMax28)
- Portfolio: [En Vivo](https://sirmax28.github.io/tailwind-presentation/)


## 📄 Advertencia

Este proyecto fue hecho para practicar en base a un curso y documentación, hay muchas cosas por mejorar aún 🚀

---