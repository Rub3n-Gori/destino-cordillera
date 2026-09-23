# Destino Cordillera - Plataforma de Turismo Local

Sitio web promocional y plataforma informativa para la comuna turística ficticia **"Destino Cordillera"**, desarrollado como proyecto de evaluación colaborativo enfocado en buenas prácticas de desarrollo web, semántica HTML5, estilos CSS3 propios y diseño responsivo.

---

## Integrantes del Equipo

- **Arquímedes Barraza** - `sebamancillabarraza@gmail.com`
- **Rubén Gorigoitia** - `ruben.gorigoitia@cloud.uautonoma.cl`
- **Jesús Poturo** - `jesuspoturo08@gmail.com`

---

## Descripción del Sitio

**Destino Cordillera** es una propuesta digital para fomentar el turismo de montaña, ecoturismo y aventura en la zona cordillerana de los Andes. La plataforma ofrece a los visitantes una experiencia integral a través de cuatro páginas interconectadas:

1. **Inicio (`index.html`)**: Presentación general del destino turístico, imagen de portada, reseña de bienvenida y accesos directos destacados a las distintas áreas del sitio.
2. **Panoramas (`panorama.html`)**: Catálogo con seis actividades y excursiones imperdibles (Trekking al Glaciar, Día de Nieve y Esquí, Termas Naturales, Cabalgatas con Arrieros, Rafting Extremo y Astroturismo), con información detallada de dificultad, duración y recomendaciones de alta montaña.
3. **Alojamiento y Gastronomía (`alojamiento-gastronomia.html`)**: Opciones seleccionadas para hospedaje (hoteles, cabañas rústicas y hostales) y servicios gastronómicos típicos (restaurantes de montaña, cafeterías y pizzerías locales), presentadas mediante tarjetas informativas estructuradas.
4. **Reserva y Contacto (`reserva-contacto.html`)**: Formulario interactivo que permite cotizar y solicitar reservas de panoramas y alojamientos con cálculo dinámico de costos estimados, datos de contacto oficiales, horarios de atención y mapa de ubicación referencial.

---

## Tecnologías Utilizadas

- **HTML5**: Estructuración semántica del contenido (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<fieldset>`, `<footer>`).
- **CSS3 Propio y Externo (`css/styles.css`)**:
  - Hoja de estilos personalizada sin dependencias de frameworks externos.
  - Maquetación responsiva mediante **CSS Grid** y **Flexbox**.
  - Reglas personalizadas de tipografía, paleta de colores, tarjetas con efectos *hover*, transiciones y media queries para dispositivos móviles y de escritorio.
- **JavaScript (Vanilla JS)**: Lógica interactiva en la página de reservas para el cálculo en tiempo real de subtotales, recargo por servicio y total estimado según el número de personas y servicios seleccionados.

---

## Estructura del Proyecto

```text
destino-cordillera/
├── index.html                      # Página principal de inicio
├── panorama.html                   # Página de actividades y excursiones
├── alojamiento-gastronomia.html    # Hospedaje y gastronomía local
├── reserva-contacto.html           # Formulario de reserva, cotización y contacto
├── css/
│   └── styles.css                  # Hoja de estilos CSS propia y externa
├── img/
│   └── recursos/                   # Fotografías, íconos y recursos visuales
└── README.md                       # Documentación general del proyecto
```

---

## Instrucciones para Ejecutar y Visualizar el Sitio

El proyecto está construido con tecnologías web estándares, por lo que no requiere instalación de dependencias ni compilación previa.

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Rub3n-Gori/destino-cordillera.git
   ```
2. **Navegar a la carpeta del proyecto**:
   ```bash
   cd destino-cordillera
   ```
3. **Visualizar el sitio**:
   - Abrir directamente el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
   - O bien, ejecutarlo mediante una extensión de servidor local como **Live Server** en Visual Studio Code.

---

## Distribución de Responsabilidades

| Integrante | Rol y Responsabilidades Principales |
| :--- | :--- |
| **Rubén Gorigoitia** | Estructuración inicial del repositorio, desarrollo de la página de inicio (`index.html`), maquetación base, configuración de la barra de navegación compartida y estilos generales en `styles.css`. |
| **Arquímedes Barraza** | Redacción y desarrollo completo de la página de actividades (`panorama.html`), selección y optimización de imágenes para las 6 experiencias turísticas, sección de recomendaciones de montaña y revisión de consistencia semántica. |
| **Jesús Poturo** | Desarrollo de la página de hospedaje y comida (`alojamiento-gastronomia.html`), desarrollo de la página de reservas y contacto (`reserva-contacto.html`), integración del formulario, lógica de cálculo interactivo y mapa referencial. |

---

## Control de Versiones

El desarrollo colaborativo se encuentra registrado mediante un historial de commits en GitHub, evidenciando la participación equitativa y coordinada de los tres integrantes del equipo.