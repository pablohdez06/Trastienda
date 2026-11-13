# 📚 La Trastienda - UD4

Proyecto de maquetación y diseño de interfaz web para una librería online especializada en novela negra y thriller, desarrollado para el módulo de **Diseño de Interfaces Web (DIWEB)** de **2º de Desarrollo de Aplicaciones Web (DAW)**.

---

## 📖 Descripción

**La Trastienda** es una interfaz web orientada a la experiencia de usuario (UX/UI), enfocada en un diseño accesible, semántico y adaptable a diferentes dispositivos (Mobile First / Responsive Design).

El proyecto simula una tienda de libros interactiva que permite a los usuarios:
- Explorar novedades y libros recomendados.
- Ver detalles de publicaciones literarias.
- Añadir libros a la cesta de la compra.
- Navegar intuitivamente entre secciones principales (Inicio, Explorar, Cesta, Perfil).

---

## 📁 Estructura del Proyecto

```text
trastienda-ud4/
│
├── css/
│   └── styles.css        # Hoja de estilos del proyecto (maquetación, tipografías, responsive)
│
├── img/                  # Recursos gráficos (portadas de libros, iconos, banners)
│
├── index.html            # Página principal de la tienda (catálogo y destacados)
├── carrito.html          # Página de la cesta de la compra y resumen de pedido
└── README.md             # Documentación del proyecto
```

---

## 🛠️ Tecnologías y Estándares

- **HTML5 Semántico**: Uso riguroso de etiquetas semánticas (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`) para mejorar el SEO y la accesibilidad.
- **Accesibilidad Web (A11y)**: Inclusión de atributos ARIA (`aria-label`, `aria-current`) para facilitar la navegación mediante lectores de pantalla.
- **CSS3**: Maquetación moderna (Flexbox / CSS Grid) y adaptabilidad mediante *media queries*.

---

## 🚀 Puesta en Marcha

Para visualizar el proyecto localmente:

1. **Clonar o descargar el repositorio**:
   ```bash
   git clone <url-del-repositorio>
   ```

2. **Abrir en el navegador**:
   - Puedes abrir directamente el archivo `index.html` con cualquier navegador web (Chrome, Firefox, Edge, etc.).
   - O bien utilizar una extensión de servidor local como **Live Server** en Visual Studio Code para recarga automática durante el desarrollo.

---

## 📋 Estado del Proyecto y Próximos Pasos

- [x] Estructura HTML semántica básica de la página principal (`index.html`).
- [x] Plantilla base para el carrito (`carrito.html`).
- [ ] Maquetación y estilos CSS en `css/styles.css` (diseño *Mobile First* y *Desktop*).
- [ ] Incorporación de portadas de libros en la carpeta `img/`.
- [ ] Maquetación completa de la vista del carrito (`carrito.html`).
- [ ] Desarrollo de las vistas secundarias:
  - `detalle.html` (Ficha del libro).
  - `explorar.html` (Buscador y filtros por género).
  - `perfil.html` (Área de usuario).

---

## 👤 Autor

- **Pablo Hernández Sánchez**
- **Curso**: 2º DAW (Desarrollo de Aplicaciones Web)
- **Módulo**: Diseño de Interfaces Web (DIWEB) - Unidad Didáctica 4

