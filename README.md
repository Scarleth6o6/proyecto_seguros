🏥 Predicción y Protección de Datos para una Compañía de Seguros
Este proyecto analiza el comportamiento de los clientes de la aseguradora Sure Tomorrow mediante modelos de Machine Learning para resolver cuatro tareas clave: 
identificación de clientes similares, predicción de prestaciones de seguro, estimación del número de prestaciones y protección de datos personales.

📌 Objetivos
Identificación de clientes similares:

Utilizar el algoritmo k-Nearest Neighbors (KNN) para encontrar clientes con características similares a un cliente determinado.
Ayudar a los agentes de la compañía con estrategias de marketing más precisas.
Predicción de prestaciones de seguro:

Desarrollar un modelo de clasificación para predecir la probabilidad de que un cliente reciba una prestación.
Comparar el rendimiento del modelo con un modelo dummy.
Estimación del número de prestaciones:

Aplicar regresión lineal para predecir cuántas prestaciones podría recibir un cliente.
Ofuscación de datos sin afectar el rendimiento del modelo:

Implementar un método de transposición de matrices para proteger los datos personales.
Evaluar el impacto de la transformación en la calidad de los modelos.
📂 Estructura del Proyecto
📁 proyecto-seguros

│── 📂 data/                  # Carpeta para almacenar los datos (vacía por privacidad)

│── 📂 notebooks/             # Análisis y desarrollo en Jupyter Notebooks

│── 📄 README.md              # Este archivo

│── 📄 requirements.txt       # Dependencias necesarias

⚠️ Nota: El dataset utilizado (insurance_us.csv) no se encuentra en el repositorio por razones de privacidad. Puedes reemplazarlo con un dataset similar o utilizar tus propios datos.

⚙️ Instalación
Clona este repositorio:
git clone https://github.com/Scarleth6o6/proyecto_seguros
cd proyecto-seguros

Instala las dependencias:
pip install -r requirements.txt

🚀 Uso
Para entrenar y evaluar los modelos, ejecuta el notebook principal en la carpeta notebooks/.
Puedes probar diferentes valores de distancia euclidiana y distancia Manhattan para ver su impacto en los resultados.

📊 Resultados
Se compararon los resultados con distancias Euclidiana y Manhattan para evaluar la precisión del modelo KNN.
Se aplicó regresión lineal para estimar el número de prestaciones con un rendimiento satisfactorio.
La técnica de ofuscación de datos mediante transposición de matrices permitió proteger la información sin afectar significativamente el desempeño del modelo.

👨‍💻 Autor
Proyecto realizado por Scarleth San Martin como parte del bootcamp de Data Science.
