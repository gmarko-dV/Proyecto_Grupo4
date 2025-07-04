# Proyecto de Gestión de Películas

Este proyecto está basado principalmente en **estructuras de datos**, específicamente **listas doblemente enlazadas** y **recursividad**, que son utilizadas para gestionar y mostrar una selección de películas en una interfaz web. Las tecnologías clave que se utilizan son **Flask** para el desarrollo de la aplicación web y **ReportLab** para la generación de archivos PDF.

## Tecnologías utilizadas

- **Flask**: Framework web ligero para crear aplicaciones web en Python.
- **ReportLab**: Biblioteca utilizada para la creación de archivos PDF, especialmente para generar tickets de compra.
- **SQLite**: Base de datos utilizada para almacenar información sobre usuarios, películas y compras.

## Pasos para ejecutar el proyecto

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. **Abre PowerShell como administrador**  
   Haz clic derecho en PowerShell y selecciona **"Ejecutar como administrador"**.
   
2. **Configura la política de ejecución**  
   Ejecuta el siguiente comando en PowerShell:

   ```bash
   Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Acepta escribiendo Y y presionando Enter.

Instalar virtualenv
Ejecuta el siguiente comando para instalar virtualenv:

bash
Copiar
Editar
pip install virtualenv
Crear el entorno virtual
Ejecuta el siguiente comando para crear un entorno virtual:

bash
Copiar
Editar
python -m venv env
Activar el entorno virtual
Para activar el entorno virtual, ejecuta:

bash
Copiar
Editar
.\env\Scripts\activate
Instalar dependencias
Instala las dependencias necesarias para el proyecto:

bash
Copiar
Editar
pip install Flask
pip install reportlab
Inicializar la base de datos
Ejecuta el siguiente script para inicializar la base de datos:

bash
Copiar
Editar
python init_db.py
Correr el servidor de la aplicación
Finalmente, ejecuta el siguiente comando para correr la aplicación:

bash
Copiar
Editar
python app.py
Con estos pasos, podrás ejecutar la aplicación web en tu máquina local y empezar a gestionar las películas y compras.

Si tienes alguna duda o pregunta, no dudes en abrir un Issue en este repositorio.

markdown
Copiar
Editar

### Explicación de los cambios:

- **Descripción general** del proyecto con énfasis en el uso de **listas doblemente enlazadas** y **recursividad**.
- **Tecnologías usadas** mencionadas brevemente.
- **Instrucciones para ejecutar** el proyecto, organizadas paso a paso.

Este texto debe proporcionar a otros desarrolladores o usuarios toda la información necesaria para ejecutar el proyecto en su máquina local. Puedes copiar y pegar esta descripción directamente en tu archivo `README.md`.

Si necesitas hacer algún ajuste o añadir más información, ¡avísame!
