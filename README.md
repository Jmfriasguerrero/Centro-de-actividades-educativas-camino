# Centro de Actividades Educativas Camino

Este proyecto es un sitio web estático desarrollado como parte del curso de Desarrollo Web en Coderhouse. El sitio web tiene como objetivo proporcionar información sobre el **Centro de Actividades Educativas Camino**.

## Descripción del Proyecto

El sitio web incluye la siguiente estructura:

- **`index.html`**: Página principal que proporciona una visión general del centro.
- **`nosotros.html`**: Información sobre quiénes somos y el equipo detrás del centro.
- **`ubicacion.html`**: Detalles sobre la ubicación del centro y cómo llegar.
- **`que-hacemos.html`**: Descripción de las actividades y servicios que ofrece el centro.
- **`contacto.html`**: Formulario de contacto para que los usuarios puedan comunicarse con el centro.

## Tecnologías y Herramientas Utilizadas

Este proyecto utiliza una variedad de tecnologías y herramientas para su desarrollo:

### Tecnologías Principales

- **HTML5**: Estructuración del contenido web.
- **CSS3**: Estilización de las páginas del sitio web.
  - **SCSS**: Preprocesador CSS para un desarrollo más eficiente y modular.
- **Bootstrap**: Framework CSS para un diseño responsivo y componentes predefinidos.

### Herramientas y Dependencias

- **Node.js**: Entorno de ejecución para JavaScript en el servidor.
- **npm**: Gestor de paquetes para instalar y gestionar dependencias.
- **`nodemon`**: Herramienta para reiniciar automáticamente el servidor durante el desarrollo. 

El archivo `package.json` incluye las siguientes configuraciones:

```json
{
  "name": "desarrolo-web-jm",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "nodemon": "^3.1.0"
  }
}
## Optimización para Motores de Búsqueda (SEO)

El sitio web ha sido optimizado para mejorar su visibilidad y rendimiento en motores de búsqueda. A continuación se detallan las prácticas de SEO implementadas:

### Meta Etiquetas

- **`<meta charset="UTF-8">`**: Establece la codificación de caracteres para asegurar que el contenido se muestre correctamente en todos los navegadores.
- **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Asegura que el sitio sea responsivo y se visualice adecuadamente en dispositivos móviles.
- **`<meta name="description" content="Caec es un centro educativo terapeútico que hace más de 20 años alberga jóvenes y adultos con discapacidad. Estamos ubicados en Vicente López, Provincia de Buenos Aires.">`**: Proporciona una descripción breve del contenido del sitio, que aparece en los resultados de búsqueda.
- **`<meta name="keywords" content="CAEC, CENTRO TERAPÉUTICO, CENTRO DE DÍA, CENTRO ACTIVIDADES EDUCATIVAS CAMINO, VICENTE LOPEZ, 20 AÑOS">`**: Incluye palabras clave relevantes para el sitio, ayudando a los motores de búsqueda a entender el contenido del sitio.

### Estructura del Contenido

- **Uso de Encabezados (`<h1>`, `<h2>`, `<h3>`)**: Se utilizan encabezados adecuados para organizar el contenido y mejorar la legibilidad tanto para usuarios como para motores de búsqueda.
- **Texto Alternativo en Imágenes (`alt` attribute)**: Se proporciona texto alternativo descriptivo para todas las imágenes para mejorar la accesibilidad y el SEO.

### Enlaces Internos y Externos

- **Enlaces Internos**: Se han implementado enlaces internos para facilitar la navegación y distribuir el valor SEO a lo largo del sitio.
- **Enlaces Externos**: En el footer, se incluyen enlaces a las redes sociales del centro, proporcionando más contexto y conexiones externas relevantes.

### Otros Aspectos

- **Optimización de Imágenes**: Se han utilizado formatos de imagen adecuados y optimizados para asegurar tiempos de carga rápidos y mejorar la experiencia del usuario.
- **Estructura de URL**: Las URLs de las páginas están bien estructuradas y son descriptivas, lo que facilita la indexación y mejora la visibilidad en los motores de búsqueda.
