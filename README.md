# Destino Cordillera - Plataforma de Turismo Local

Sitio web promocional y plataforma informativa para la comuna turística ficticia **"Destino Cordillera"**, desarrollado como proyecto de evaluación colaborativo enfocado en buenas prácticas de desarrollo web, semántica HTML5, estilos CSS3 propios y diseño responsivo.

---

## 1. Nombre del Proyecto

**Destino Cordillera**

## 2. Integrantes del Equipo

- **Arquímedes Barraza** - `sebamancillabarraza@gmail.com`
- **Rubén Gorigoitia** - `ruben.gorigoitia@cloud.uautonoma.cl`
- **Jesús Poturo** - `jesuspoturo08@gmail.com`

---

## 3. Descripción del Sitio

**Destino Cordillera** es una propuesta digital para fomentar el turismo de montaña, ecoturismo y aventura en la zona cordillerana de los Andes. La plataforma ofrece a los visitantes una experiencia integral a través de cuatro páginas interconectadas:

1. **Inicio (`index.html`)**: Presentación general del destino turístico, imagen de portada, reseña de bienvenida y accesos directos.
2. **Panoramas (`panorama.html`)**: Catálogo con seis actividades y excursiones imperdibles, con información de dificultad, duración y recomendaciones.
3. **Alojamiento y Gastronomía (`alojamiento-gastronomia.html`)**: Opciones seleccionadas para hospedaje y servicios gastronómicos típicos presentadas mediante tarjetas informativas.
4. **Reserva y Contacto (`reserva-contacto.html`)**: Formulario visual para solicitar cotizaciones de panoramas y alojamientos, acompañado de datos de contacto, horario de atención y mapa de ubicación.

---

---

## 4. Instrucciones para Ejecutar y Visualizar el Sitio

El proyecto está construido puramente con HTML y CSS, por lo que no requiere instalaciones externas.

1. **Clonar el repositorio**:

`git clone https://github.com/Rub3n-Gori/destino-cordillera.git`

2. **Navegar a la carpeta del proyecto**:

`cd destino-cordillera`

3. **Visualizar el sitio**:
   Abrir directamente el archivo `index.html` en cualquier navegador web (Chrome, Mozilla Firefox, Microsoft Edge, etc).

- O bien, ejecutarlo mediante una extensión de servidor local como **Live Server** en Visual Studio Code.

---

## 5. Tecnologías Utilizadas

- **HTML5**: Estructuración semántica del contenido (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3 Propio (`css/styles.css`)**:
  - Hoja de estilos personalizada (sin uso de Bootstrap ni frameworks externos).
  - Maquetación responsiva y estructuración limpia basado en **Flexbox**.
  - Reglas estandarizadas en unidades absolutas **px** para asegurar consistencia, paleta de colores corporativa y media queries para adaptabilidad en dispositivos móviles y de escritorio.

---

## 6. Estructura del Proyecto

```text
destino-cordillera/
├── index.html                      # Página principal de inicio
├── panorama.html                   # Página de actividades y excursiones
├── alojamiento-gastronomia.html    # Hospedaje y gastronomía local
├── reserva-contacto.html           # Formulario de reserva, cotización y contacto
├── css/
│   └── styles.css                  # Hoja de estilos CSS propia y externa
├── img/
│   └── recursos/                   # Imagenes y recursos visuales
└── README.md                       # Documentación general del proyecto
```

---

## 7. Distribución de Responsabilidades

| Integrante             | Rol y Responsabilidades Principales                                                                                                                                                                                                  |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rubén Gorigoitia**   | Estructuración inicial del repositorio, desarrollo de la página de inicio (`index.html`), maquetación base, configuración de la barra de navegación compartida, refactorización general del CSS y estilos generales en `styles.css`. |
| **Arquímedes Barraza** | Redacción y desarrollo completo de la página de actividades (`panorama.html`), selección y optimización de imágenes para las 6 experiencias turísticas, sección de recomendaciones de montaña y revisión de consistencia semántica.  |
| **Jesús Poturo**       | Desarrollo de la página de hospedaje y comida (`alojamiento-gastronomia.html`), desarrollo de la página de reservas y contacto (`reserva-contacto.html`)                                                                             |

---

## Control de Versiones

El desarrollo colaborativo se encuentra registrado mediante un historial de commits en GitHub, evidenciando la participación equitativa y coordinada de nuestro equipo.
