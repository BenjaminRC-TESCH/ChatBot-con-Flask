# Chatbot con Flask
Este proyecto implementa un chatbot utilizando Flask y un archivo CSV para almacenar preguntas y respuestas de entrenamiento.

## Funcionalidad
El chatbot permite a los usuarios interactuar seleccionando categorías desde una página HTML y obteniendo respuestas basadas en un archivo CSV de entrenamiento.

## Características
Interfaz de Usuario: Una interfaz web simple donde los usuarios pueden seleccionar categorías para preguntar al chatbot.

Respuestas Basadas en CSV: Utiliza un archivo CSV llamado entrena.csv para almacenar preguntas y respuestas de entrenamiento.

## Tecnologías Utilizadas
- Flask: Framework web utilizado para crear el servidor y manejar las rutas.
- HTML/CSS/JS: Para la interfaz de usuario y la interacción cliente-servidor.
- Python: Lenguaje de programación principal para la lógica del chatbot.
- CSV: Archivo utilizado para almacenar las preguntas y respuestas de entrenamiento.

## Requisitos
- Python 3.x
- Flask
- Un navegador web compatible

## Instalación y Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/BenjaminRC-TESCH/FlaskChatBot-Asistente-Conversacional-con-Flask.git
   ```
2. Instala las dependencias de Python:
   ```bash
   pip install flask
   ```

3. Ejecuta la aplicación:
   ```bash
   python app.py
   ```

4. Abre tu navegador y visita http://localhost:5000 para interactuar con el chatbot.

## Estructura del Proyecto
app.py: El archivo principal de Flask que maneja las rutas y la lógica del chatbot.
templates/: Carpeta que contiene los archivos HTML para la interfaz de usuario.
static/: Carpeta opcional que puede contener archivos estáticos como CSS o JavaScript.

## Archivo CSV entrena.csv
El archivo CSV entrena.csv debe seguir el siguiente formato:
   ```bash
pregunta,respuesta,categoria
¿Qué es Python?,Python es un lenguaje de programación interpretado y de alto nivel,dudas
   ```
Cada línea del archivo contiene una pregunta seguida de una respuesta y una categoría separadas por comas.

## Contribuciones
¡Las contribuciones son bienvenidas! Siéntete libre de bifurcar el repositorio y enviar solicitudes de extracción para sugerir mejoras o características adicionales.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
