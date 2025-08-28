# Mapa Político Interactivo de Colombia

## Descripción del Proyecto

Este proyecto presenta un mapa político interactivo de Colombia que permite a los usuarios explorar información detallada sobre diferentes departamentos del país. Actualmente incluye información completa sobre **Casanare** y referencias a **Meta** y **Santander**.

## Características Principales

### 🗺️ Mapa Interactivo
- Mapa político de Colombia con áreas clicables
- Implementado con HTML `<map>` e `<area>` tags para crear regiones interactivas
- Navegación intuitiva entre departamentos

### 📍 Información Detallada por Departamento

#### Casanare (Completamente Desarrollado)
- **Descripción general**: Historia, geografía y características principales
- **Sitios Turísticos**:
  - Parque Nacional Natural El Tuparro
  - Caño Cristales ("río de los cinco colores")
  - Laguna de la Herrera
  - Yopal (capital)
  - Hato La Aurora
- **Gastronomía Típica**:
  - Carne a la Llanera
  - Majarete
  - Chigüiro
  - Arepa de Chicharrón
  - Sopa de Gallina Criolla
- **Datos Poblacionales y Económicos**:
  - Población: ~420,000 habitantes
  - Economía basada en petróleo, ganadería y agricultura

## Estructura del Proyecto

```
proyecto/
├── index.html              # Página principal con mapa interactivo
├── casanare.html           # Página detallada de Casanare
├── meta.html               # Página de Meta (referenciada)
├── santander.html          # Página de Santander (referenciada)
└── images/
    ├── img01.jpg           # Mapa principal de Colombia
    ├── Casanare.jpeg       # Imagen del departamento
    ├── Tuparro.jpeg        # Parque Nacional El Tuparro
    ├── Cristales.jpeg      # Caño Cristales
    ├── Laguna.jpeg         # Laguna de la Herrera
    ├── Yopal.jpeg          # Capital Yopal
    ├── Hato.jpeg           # Hato La Aurora
    ├── Carne.jpeg          # Carne a la Llanera
    ├── Majarete.jpeg       # Postre Majarete
    ├── Chiguiro.jpeg       # Chigüiro
    ├── ArepaC.jpeg         # Arepa de Chicharrón
    ├── Sopa.jpeg           # Sopa de Gallina
    ├── Estad.jpeg          # Estadísticas
    └── BanderaC.jpeg       # Bandera de Casanare
```

## Tecnologías Utilizadas

- **HTML5**: Estructura y contenido
- **CSS inline**: Estilos básicos y diseño responsivo
- **Image Maps**: Para crear áreas clicables en el mapa
- **Multimedia**: Integración de imágenes para cada sección

## Características Técnicas

### Responsive Design
- Uso de porcentajes para dimensiones de imágenes
- Meta viewport configurado para dispositivos móviles
- Diseño adaptable a diferentes tamaños de pantalla

### Navegación
- Enlaces de retorno al mapa principal
- Áreas del mapa definidas con coordenadas precisas
- Apertura de páginas en nueva pestaña (`target="_blank"`)

### Accesibilidad
- Atributos `alt` en todas las imágenes
- Estructura semántica con encabezados jerárquicos
- Títulos descriptivos en las áreas del mapa

## Instalación y Uso

1. **Clonar o descargar** el proyecto
2. **Asegurarse** de que la carpeta `images/` contiene todas las imágenes necesarias
3. **Abrir** `index.html` en un navegador web
4. **Hacer clic** en las regiones del mapa para explorar los departamentos

## Desarrollo Futuro

### Próximas Implementaciones
- [ ] Completar páginas de Meta y Santander
- [ ] Agregar más departamentos al mapa interactivo
- [ ] Implementar CSS externo para mejor organización
- [ ] Añadir efectos de hover en las áreas del mapa
- [ ] Incluir información sobre clima y festividades
- [ ] Agregar galería de imágenes expandible

### Mejoras Técnicas Sugeridas
- [ ] Implementar CSS Grid/Flexbox para mejor layout
- [ ] Añadir JavaScript para interacciones avanzadas
- [ ] Optimizar imágenes para mejor rendimiento
- [ ] Implementar lazy loading para las imágenes
- [ ] Añadir meta tags SEO

## Contribuciones

Este proyecto está abierto a contribuciones para:
- Completar información de departamentos faltantes
- Mejorar el diseño visual
- Añadir funcionalidades interactivas
- Optimizar la experiencia de usuario

## Recursos Educativos

Este proyecto puede ser utilizado como:
- **Material educativo** sobre geografía colombiana
- **Ejemplo de implementación** de mapas interactivos en HTML
- **Referencia cultural** sobre tradiciones regionales
- **Base para proyectos** de turismo virtual

---

*Desarrollado como herramienta educativa e informativa sobre la diversidad geográfica y cultural de Colombia.*