# 🧠 Portal Web - Cuaderno Digital de Inteligencia Artificial

## Descripción

Este es un portal web dinámico e interactivo creado como parte del proyecto grupal del **Cuaderno Digitalizado de IA**. La página presenta toda la información y recursos educativos relacionados con las unidades de Inteligencia Artificial de manera moderna y profesional.

## ✨ Características Principales

### 🎨 Diseño Moderno y Responsivo
- **Interfaz profesional** con degradados modernos
- **Totalmente responsivo** - Se adapta perfectamente a dispositivos móviles, tablets y escritorio
- **Animaciones fluidas** que mejoran la experiencia del usuario
- **Paleta de colores atractiva** basada en tonos de azul, rosa y ámbar

### 🎯 Funcionalidades Interactivas

#### 1. **Navegación Inteligente**
- Menú hamburguesa para dispositivos móviles
- Desplazamiento suave entre secciones
- Barra de navegación fija en la parte superior

#### 2. **Fondo Animado**
- Canvas con partículas flotantes interconectadas
- Crea un efecto visual de red neural
- Gradiente de fondo dinámico

#### 3. **Sección de Descarga de Materiales**
- **Cuaderno Completo de IA** (1.3 MB)
  - Contenido integral sobre IA
  - Todas las unidades incluidas
- **Unidades 3 y 4 Especializadas** (368 KB)
  - Fundamentos avanzados
  - Aplicaciones prácticas

#### 4. **Estructura de Unidades**
- **Unidad 1:** Fundamentos de IA
- **Unidad 2:** Machine Learning
- **Unidad 3:** Deep Learning
- **Unidad 4:** Aplicaciones Prácticas

#### 5. **Recursos Complementarios**
- Frameworks y librerías
- Tutoriales y cursos
- Artículos académicos
- Comunidades de profesionales

#### 6. **Formulario de Contacto**
- Validación de campos
- Verificación de email
- Notificaciones visuales

#### 7. **Animaciones y Transiciones**
- Elementos que aparecen al hacer scroll
- Contadores animados en la sección de estadísticas
- Efectos hover en botones y tarjetas
- Transiciones suaves en toda la página

## 📁 Estructura de Archivos

```
/
├── index.html          # Página principal HTML
├── styles.css          # Estilos y diseño responsivo
├── script.js           # Funcionalidad JavaScript
└── README.md           # Este archivo
```

## 🚀 Cómo Usar

### Opción 1: Ver en Navegador Local
1. Descarga o clona el repositorio
2. Abre el archivo `index.html` en tu navegador web preferido
3. ¡Disfruta de la experiencia interactiva!

### Opción 2: Usar con GitHub Pages
1. Ve a la rama `web-portal` en el repositorio
2. Habilita GitHub Pages en los ajustes del repositorio
3. Selecciona la rama `web-portal` como fuente
4. Accede a la URL proporcionada por GitHub

## 🛠️ Funciones JavaScript

### Inicialización
```javascript
document.addEventListener('DOMContentLoaded', () => {
    addAnimationStyles();      // Agregar animaciones CSS
    initCanvasAnimation();      // Animar fondo
    initHamburgerMenu();        // Menú móvil
    initScrollAnimation();      // Animaciones en scroll
    initCounterAnimation();     // Contadores numéricos
    initFormHandler();          // Manejo de formulario
});
```

### Funciones Principales

- **`initCanvasAnimation()`** - Crea partículas animadas de fondo
- **`initHamburgerMenu()`** - Maneja el menú responsivo
- **`scrollToSection()`** - Desplazamiento suave entre secciones
- **`initScrollAnimation()`** - Anima elementos al hacer scroll
- **`initFormHandler()`** - Valida y procesa el formulario
- **`showNotification()`** - Muestra notificaciones visuales

## 🎓 Educativo

Este portal fue diseñado pensando en:
- **Estudiantes** que necesitan acceder fácilmente al material
- **Profesores** que quieren presentar contenido de manera moderna
- **Profesionales** interesados en aprender sobre IA

## 🌐 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Diseño responsivo y animaciones
- **JavaScript Vanilla** - Interactividad sin dependencias externas
- **Canvas API** - Animaciones de fondo
- **Intersection Observer API** - Animaciones al hacer scroll
- **Font Awesome 6.4.0** - Iconos profesionales

## 📱 Compatibilidad

- ✅ Chrome / Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Navegadores móviles modernos
- ✅ Tablets

## 🎨 Personalización

### Cambiar Colores Principales
En `styles.css`, modifica las variables CSS:
```css
:root {
    --primary-color: #6366f1;      /* Azul índigo */
    --secondary-color: #ec4899;    /* Rosa */
    --accent-color: #f59e0b;       /* Ámbar */
}
```

### Ajustar Animaciones
- Velocidad: Modifica los valores de `transition` en CSS
- Partículas: Cambia `particleCount` en `script.js`
- Distancia de conexión: Ajusta el valor `150` en `connectParticles()`

## 📊 Mejoras Futuras

- [ ] Integración con base de datos para comentarios
- [ ] Sistema de búsqueda de contenido
- [ ] Modo oscuro mejorado
- [ ] Reproducción de videos integrada
- [ ] Quiz interactivos
- [ ] Sistema de certificados
- [ ] Chat en vivo para soporte

## 👥 Colaboradores

Proyecto grupal del Cuaderno Digital de IA

## 📞 Soporte

¿Preguntas o sugerencias? Utiliza el formulario de contacto en la página o abre un issue en el repositorio.

## 📄 Licencia

Este proyecto es parte de un material educativo grupal.

---

**Última actualización:** Junio 2026  
**Versión:** 1.0.0  
**Estado:** ✅ Completado
