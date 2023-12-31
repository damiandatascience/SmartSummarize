# Resumidor de contenido



Este proyecto es un ejemplo de una aplicación simple que utiliza Langchain y GPT de OpenAI para resumir el contenido de una URL proporcionada por el usuario.

# Requisitos
Antes de ejecutar esta aplicación, asegúrate de tener instalados los siguientes elementos:

Python (versión 3.11 +)

Además, necesitarás una clave API de OpenAI para utilizar GPT. Puedes obtenerla registrándote en el sitio web de OpenAI y siguiendo sus instrucciones para obtener una clave API.

# Demo de la Aplicación
Puedes probar la aplicación en vivo accediendo a la siguiente URL:

https://damiandatascience-streamlit-streamlit-app-gdcp62.streamlit.app/

La aplicación permite a los usuarios ingresar una URL y obtener un resumen del contenido utilizando Langchain y GPT de OpenAI.






# Instalación

Clona este repositorio en tu máquina local:

Crea un entorno virtual (opcional pero recomendado) 
python -m venv env
En Windows: env\Scripts\activate
En macOS/Linux: source env/bin/activate
Instala las dependencias necesarias 
desde el archivo 'requirements.txt':

pip install -r requirements.txt
Configura la clave API de OpenAI:
Abre el archivo 'config.py' y reemplaza <TU_API_KEY> con tu clave API de OpenAI.

## Uso
Ejecuta la aplicación con el siguiente comando:

bash
Copy code
python app.py
La aplicación te pedirá ingresar una URL que desees resumir. Luego, utilizará Langchain para extraer el contenido de la URL y GPT de OpenAI para generar un resumen del contenido.



Licencia
Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.


Agradecimiento especial a OpenAI por proporcionar GPT y su documentación.
Agradecimiento a Langchain por su valiosa funcionalidad de extracción de contenido.


![Captura de pantalla](Captura%20de%20pantalla%202023-07-26%20011559.png)


