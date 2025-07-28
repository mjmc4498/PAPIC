# PAPIC: Generador de Pictogramas Dinámicos

¡Bienvenido a PAPIC! Una herramienta web innovadora y accesible para la creación de secuencias de pictogramas dinámicos.

PAPIC (Plataforma de Apoyo para la Comunicación Inclusiva) es un sistema web diseñado para facilitar la comunicación a través de pictogramas. Está especialmente pensado para niños, personas con discapacidad cognitiva o cualquier persona que se beneficie de un apoyo visual para la comunicación.

El sistema permite a los usuarios escribir una frase y genera automáticamente una secuencia de pictogramas que la representa. Todo funciona de manera local en tu navegador, sin necesidad de instalaciones complejas ni servidores externos.

**[Ver la demo en vivo en GitHub Pages](https://mjmc4498.github.io/PAPIC)**

## Características Principales

- **Generación Dinámica:** Escribe una frase y observa cómo se transforma en una secuencia de pictogramas al instante.
- **Interpretación Inteligente:** El sistema detecta combinaciones de sustantivo + verbo para buscar imágenes más contextuales (p. ej., "niño corriendo").
- **Búsqueda Integrada:** Encuentra el pictograma perfecto buscando en la extensa base de datos de [ARASAAC](https://arasaac.org/).
- **Edición en Tiempo Real:** Modifica el texto o reemplaza cualquier pictograma fácilmente.
- **Exportación a PDF:** Guarda tus secuencias de pictogramas como un archivo PDF con un solo clic.
- **Diseño Responsivo:** Utiliza PAPIC en cualquier dispositivo, desde un móvil hasta un ordenador de escritorio.
- **Sin Dependencias Externas:** Funciona entièrement con HTML, CSS y JavaScript puro, utilizando Bootstrap 5 para el diseño.

## Manual de Uso

1.  **Escribe una Frase:**
    -   Simplemente haz clic en el área de texto grande y escribe lo que quieras comunicar.
    -   A medida que escribes, los pictogramas aparecerán automáticamente debajo.

2.  **Edita una Palabra:**
    -   Si quieres cambiar una palabra, haz clic en el texto debajo del pictograma correspondiente.
    -   Podrás editarlo directamente. Al terminar, el pictograma se actualizará automáticamente.

3.  **Reemplaza un Pictograma:**
    -   Haz clic en la imagen del pictograma que deseas cambiar. Se marcará con un borde azul.
    -   Luego, en la sección "Buscador de Iconos", puedes:
        -   Hacer clic en uno de los iconos fijos (feliz, triste, etc.).
        -   O buscar una nueva palabra en el buscador (p. ej., "coche") y hacer clic en el resultado que prefieras.
    -   El pictograma seleccionado se actualizará con la nueva imagen.

4.  **Exporta a PDF:**
    -   Cuando tu secuencia de pictogramas esté lista, haz clic en el botón verde **"Exportar a PDF"**.
    -   Se generará un archivo PDF que se descargará automáticamente en tu dispositivo.

## Instalación Local

Aunque la forma más fácil de usar PAPIC es a través del [enlace de GitHub Pages](https://mjmc4498.github.io/PAPIC), también puedes usarlo de forma local en tu ordenador.

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/mjmc4498/PAPIC.git
    ```
2.  **Navega a la carpeta:**
    ```bash
    cd PAPIC
    ```
3.  **Abre el archivo `index.html`:**
    -   Simplemente haz doble clic en el archivo `index.html` para abrirlo en tu navegador web preferido (como Chrome, Firefox, etc.).
    -   ¡Y listo! Ya puedes empezar a usar la aplicación.

## Despliegue en GitHub Pages

Este proyecto está listo para ser desplegado gratuitamente con GitHub Pages.

### Cómo activarlo

1.  Ve a la página principal de tu repositorio en GitHub: [https://github.com/mjmc4498/PAPIC](https://github.com/mjmc4498/PAPIC).
2.  Haz clic en la pestaña de **"Settings"** (Configuración).
3.  En el menú de la izquierda, haz clic en **"Pages"**.
4.  En la sección "Build and deployment", bajo "Source", selecciona **"Deploy from a branch"**.
5.  En la sección "Branch", asegúrate de que la rama seleccionada sea `main` (o la rama principal que estés usando) y la carpeta sea `/ (root)`.
6.  Haz clic en **"Save"**.

Después de unos minutos, tu página estará activa en: **[https://mjmc4498.github.io/PAPIC](https://mjmc4498.github.io/PAPIC)**

## Créditos

Este proyecto fue creado y es mantenido por [mjmc4498](https://github.com/mjmc4498).

Los pictogramas son obtenidos de [ARASAAC](https://arasaac.org/), propiedad de CATEDU bajo licencia Creative Commons.
