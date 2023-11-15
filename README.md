# Machine-Learning
Creación de un manual de Machine Learning que permita brindar conocimientos generales, herramientas y código compilable con el fin de dar los primeros pasos en Inteligencia artificial y Machine learning.
El repositorio del Manual consta de 3 Elementos:

**Manual ML.ipynb**: El manual de Machine Learning en formato Jupyter Notebook. Es necesaria La conexión a internet
para acceder a diferentes datasets alojados en la nube.

**/Datos**: Posee distintos datasets en formato "csv" y "xlsx" usados para para desarrollar distintos modelos supervisados en el manual. Alojados en el repositorio de manera que el Manual sea autocontenido y no necesite de ningún archivo localmente, permitiendo al usuario ahorrar memoria y que sea un archivo manejable.

**requirements.txt**: Archivo de texto que contiene las dependencias del manual para que el usuario no tenga que instalarlas manualmente. Creado y modificado a partir del comando `pip freeze > requirements.txt`. Para instalar todas las dependecias del manual se siguen los siguientes pasos:

1. Abrir cmd.
2. Ejecutar el comando: `pip install -r requirements.txt`.
3. Esperar la descarga de las librerías.