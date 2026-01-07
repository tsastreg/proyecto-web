# TJA Gym - Proyecto Web

Este es el proyecto de nuestra página web para el gimnasio **TJA Gym**. El objetivo principal es practicar HTML y CSS montando un sitio web sencillo pero funcional con varias páginas enlazadas.

## 📂 Estructura del proyecto

La web consta de los siguientes archivos:

* **index.html**: Página de inicio con la presentación del gimnasio.
* **content.html**: Información sobre las áreas del gym (cardio, musculación, nutrición).
* **detail.html**: Página de detalle de producto (nuestra proteína TJA Whey).
* **info.html**: Información sobre el proyecto y los autores.
* **style.css**: Hoja de estilos con todo el diseño visual.
* **Carpeta `imagenes/`**: Contiene las fotos del gimnasio y el logo.

## 🎨 Diseño y Estilos (CSS)

Hemos creado una hoja de estilos (`style.css`) para dar personalidad a la web, evitando usar las variables (que son más avanzadas) y utilizando código estándar que hemos aprendido.

**Características principales del diseño:**

* **Paleta de Colores:** Hemos usado los colores corporativos del logo:
    * 🔵 **Azul Oscuro (#1B263B):** Para el encabezado y el pie de página.
    * 🟠 **Naranja (#E07A2E):** Para destacar botones, enlaces y subrayados de títulos.
    * ⚪ **Gris Claro/Blanco:** Para los fondos y secciones de lectura.
* **Maquetación:**
    * Uso de **Flexbox** para alinear el menú de navegación y las listas.
    * Márgenes y rellenos (*padding*) para que el texto no se vea pegado a los bordes.
* **Diseño Responsivo (Adaptable):**
    * Hemos añadido `media queries` para que el menú se vea bien en móviles (se pone en columna en lugar de fila).
    * Las imágenes se ajustan automáticamente al tamaño de la pantalla.

## 📝 Implementación de Formularios

Hemos añadido dos formularios funcionales (Login y Contacto) siguiendo las buenas prácticas de desarrollo web:

* **Tipos de entrada (Inputs):** Hemos utilizado HTML semántico adecuado para cada dato:
    * `type="email"`: Para validar automáticamente el formato del correo.
    * `type="password"`: Para ocultar los caracteres en el inicio de sesión.
    * `<textarea>`: Para permitir escribir mensajes largos en el contacto.
* **Diseño y Coherencia:**
    * Los formularios se integran con la estética de la web usando el **Azul Osuro (#1B263B)** para los textos y el **Naranja (#E07A2E)** para los botones y los bordes al escribir (`focus`).
    * Hemos usado **Flexbox** (`flex-direction: column`) para que los campos estén perfectamente alineados y se adapten a pantallas de móviles (*responsive*).
* **Validación:**
    * Controlamos que no se envíen datos vacíos usando el atributo `required` de HTML5 en todos los campos obligatorios.
    * Aprovechamos la validación nativa del navegador para los emails.

## 🚀 Cómo ver la web

1.  Descarga el repositorio o los archivos.
2.  Asegúrate de que el archivo `style.css` está en la misma carpeta que los HTML.
3.  Abre el archivo `index.html` en tu navegador (Chrome, Firefox, Edge, etc.).
4.  Navega por las secciones usando el menú superior.

---

Trabajo realizado por:
* Tomeu Sastre Garcés
* Jordi Valarezo Méndez
* Adrián Pascual Lara