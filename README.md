Proyecto de Python Avanzado: Generación y Análisis de Hostnames

📌 Descripción

Este proyecto tiene como objetivo la generación y análisis de hostnames basados en reglas predefinidas. Se utilizan Python, pandas, numpy, matplotlib y seaborn para manipular y visualizar los datos.

📂 Estructura del Proyecto

📁 Proyecto_Python_Avanzado
├── 📄 README.md  # Explicación del proyecto
├── 📄 requirements.txt  # Librerías necesarias
├── 📁 data  # Datos generados
│   ├── Resultados.xlsx
├── 📁 src  # Código fuente
│   ├── Practica_Sixto_Ramirez.ipynb  # Notebook principal
├── 📁 audio  # Archivos de audio si es necesario

🚀 Instalación

Para ejecutar el proyecto, instala las dependencias con:

pip install -r requirements.txt

🔍 Funcionalidades

✅ Generación de hostnames siguiendo reglas definidas.

✅ Clasificación por sistema operativo, entorno y país.

✅ Creación de un DataFrame estructurado.

✅ Visualización de datos con matplotlib y seaborn.

📊 Ejemplo de Uso

# Importar librerías
import pandas as pd
import matplotlib.pyplot as plt

# Cargar los datos generados
df = pd.read_excel("data/Resultados.xlsx")

# Visualizar los primeros datos
df.head()

# Crear un gráfico
df["sistema_operativo"].value_counts().plot(kind="bar")
plt.title("Distribución de Sistemas Operativos")
plt.show()



📢 Autor: Sixto Ramírez📧 Contacto: [Tu email o LinkedIn]

