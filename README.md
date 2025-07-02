# Lector de PDF con IA (PDF-reader)
Una aplicación web elegante y minimalista para convertir documentos PDF en audiolibros y obtener resúmenes inteligentes generados por IA.

[Ver demostración en vivo »](https://herbertspencer.net/PDF-reader)

## Descripción
Este proyecto nace de la necesidad de consumir contenido de PDFs de una manera más accesible y eficiente. La aplicación permite a los usuarios cargar un archivo PDF desde su dispositivo y lo convierte en un audiolibro utilizando la API de Síntesis de Voz nativa del navegador.

Además de la funcionalidad de audio, la aplicación se integra con la API de Gemini de Google para ofrecer dos potentes herramientas de análisis:

Resumen de Página: Genera un resumen conciso del contenido de la página actual.

Puntos Clave: Analiza las primeras páginas del documento para extraer un resumen ejecutivo o los puntos más importantes.

El diseño está inspirado en la estética humanista y la tipografía de Edward Tufte, utilizando fuentes con serif (Lora) y una paleta de colores cálidos (tonos ahuesados y naranjas) para una experiencia de lectura y uso más agradable y menos fatigante.

La privacidad es fundamental: Todo el procesamiento de los archivos PDF se realiza localmente en el navegador del usuario. El contenido del PDF no se sube a ningún servidor, garantizando que los documentos permanezcan privados. Únicamente el texto seleccionado para análisis se envía a la API de Gemini.

### Características Principales

- Conversión a Audiolibro: Escucha tus documentos PDF con voces naturales.
- Controles de Reproducción: Funciones de Play, Pausa y Stop.
- Ajustes de Voz: Personaliza la voz, la velocidad y el tono de la narración.
- Resúmenes con IA: Resume la página actual con un solo clic.
- Puntos Clave con IA: Obtén las ideas principales de todo el documento.
- Diseño Elegante: Interfaz limpia, centrada en la legibilidad y la calma.
- 100% Client-Side: Máxima privacidad y seguridad. No requiere instalación ni backend.
- Responsivo: Funciona en computadoras de escritorio y dispositivos móviles.

### Cómo Utilizar

1. Visita https://herbertspencer.net/PDF-reader.

2. Haz clic en el área de "Selecciona un archivo PDF para comenzar" y elige un documento de tu dispositivo.

3. Una vez cargado, aparecerán los controles de reproducción y los botones de IA.

4. Usa el botón ▶️ para iniciar la lectura en voz alta.

5. Usa los botones "✨ Resumir Página" o "✨ Puntos Clave" para activar las funciones de IA.

### Tecnologías Utilizadas
HTML5

- CSS3 con Tailwind CSS para un diseño rápido y moderno.
- JavaScript (ES6+) para toda la lógica de la aplicación.
- [PDF.js](https://mozilla.github.io/pdf.js/): Biblioteca de Mozilla para renderizar y extraer texto de archivos PDF en el navegador.
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API): Para la síntesis de voz nativa del navegador.
- [Google Gemini API](https://ai.google.dev/): Para las funciones de resumen y análisis de texto.

#### 📄 Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.