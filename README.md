
# Modelo Predictivo de Cambio de Hábitos por Temor a la Inseguridad
# ENAPRES 2023 – Capítulo 600

# 1. Descripción
Este proyecto desarrolla un modelo de Machine Learning para predecir el cambio de hábitos de los ciudadanos por temor a la inseguridad en Lima Metropolitana, utilizando la base de datos de la Encuesta Nacional de Programas Presupuestales (ENAPRES 2023, Capítulo 600).
El trabajo incluye todas las fases del pipeline de aprendizaje automático:
1.	Preparación del entorno y datos.
2.	Entrenamiento de modelos base (Árbol de Decisión, Random Forest, Regresión Logística, XGBoost).
3.	Validación cruzada.
4.	Optimización de hiperparámetros.
5.	Evaluación comparativa de modelos.
6.	Análisis de sesgo y varianza.
7.	Visualizaciones y análisis estadístico.
8.	Conclusiones y recomendaciones.
9.  Anexos
________________________________________
# 2. Tecnologías utilizadas
- Python 3
- Pandas, Numpy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab
________________________________________
# 3. Estructura del repositorio
- data/
    - CAP600_data_limpia.csv        # Dataset utilizado Enapres Cap. 600
- notebooks/
    - Machine_Learning_I_IDL3.ipynb # Notebook con fases 1-9
- results/
    - resultados_cv.csv             # Resultados de validación cruzada
    - resultados_predicciones.csv   # Predicciones de modelos optimizados
    - graficos/                     # Gráficas ROC, PR, importancia de variables, etc.
    - README.md                     # Documentación del proyecto
- documentación
    - CPP1_Jimenez_Nek.docx         # Archivo word con conceptos clave
________________________________________
# 4. Resultados principales
- Los modelos de ensamble (Random Forest y XGBoost) alcanzaron las mejores métricas de desempeño.
- Recall > 0.90 y F1-score > 0.70 en la clase positiva (cambio de hábito).
- Variables más influyentes: percepción de inseguridad, confianza en la policía, edad, sexo y experiencias de victimización.
________________________________________
# 5. Conclusiones y recomendaciones
- Los modelos predictivos permiten identificar poblaciones más propensas a modificar hábitos frente a la inseguridad.
- Mujeres y adultos mayores son los grupos con mayor propensión al cambio de hábitos.
- Se recomienda implementar este tipo de análisis en plataformas Big Data (Hadoop, Spark) y dashboards interactivos (Power BI, Looker Studio).
________________________________________
# 6. Autor
- Nek Ryan Jimenez Mandujano – Estudiante de Ciencia de Datos e IA
- Curso: Machine Learning I
- Docente: Sergio Victor Orizano Salvador
- Instituto: Continental
- Año: 2025

# 7. Ejecución del proyecto
- Entorno virtual

python -m venv_Machine-Learning-I-IDL3
venv_Machine-Learning-I-IDL3\Scripts\activate.bat
pip install -r requirements.txt

- Clonar repositorio

git clone https://github.com/NekRyan/Machine-Learning-I-IDL3.git
