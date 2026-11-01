# AluraPlay

Plataforma de videos inspirada en YouTube, construida con HTML y CSS puro siguiendo el enfoque **mobile-first**. Proyecto desarrollado durante mi formación en Alura Latam para practicar maquetación y diseño responsivo.

🔗 **Demo:** [alura-play-roan.vercel.app](https://alura-play-roan.vercel.app/)

## Funcionalidades

- **Cabecera** con logo, barra de búsqueda, búsqueda por voz y accesos rápidos (crear video, apps, notificaciones y perfil).
- **Menú lateral** con navegación principal, biblioteca, canales suscritos y categorías.
- **Barra de categorías** con filtros temáticos (Debates, En Vivo, Podcasts, Data Science, Marketing y más).
- **Galería de 16 videos** de YouTube integrados con `iframe`, cada uno con canal, título y vistas.
- **Efecto de zoom** al pasar el cursor sobre los videos en pantallas grandes.
- **Pie de página** con las áreas de formación de Alura organizadas por categoría.

## Diseño responsivo

El sitio se diseñó primero para móvil y se adapta con media queries a dos puntos de quiebre:

| Dispositivo | Ancho | Cambios principales |
|---|---|---|
| Móvil | < 834 px | Menú lateral compacto con íconos, videos en una columna |
| Tablet | ≥ 834 px | Barra de categorías con bordes, videos en cuadrícula, efecto de zoom |
| Escritorio | ≥ 1440 px | Menú lateral expandido con textos y separadores |

## Tecnologías

- HTML5 semántico (`header`, `nav`, `aside`, `section`, `footer`)
- CSS3 con Flexbox y variables CSS
- Media queries para diseño responsivo
- Metodología BEM para nombrar clases
- Google Fonts (Roboto)
- Despliegue en Vercel

## Estructura

```
index.html          Estructura de la página
css/reset.css       Reseteo de estilos del navegador
css/estilos.css     Estilos generales, colores y media queries
css/flexbox.css     Distribución de los elementos con Flexbox
img/                Íconos de la cabecera, del menú y de los canales
```

## Uso local

No requiere instalación. Clona el repositorio y abre `index.html` en el navegador:

```bash
git clone https://github.com/ManuelRodriguez176/Alura-Play.git
cd Alura-Play
```
