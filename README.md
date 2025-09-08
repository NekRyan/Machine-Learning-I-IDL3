Modelo Predictivo de Cambio de Hábitos por Temor a la Inseguridad
ENAPRES 2023 – Capítulo 600

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
________________________________________
# 2. Tecnologías utilizadas
•	Python 3
•	Pandas, Numpy
•	Scikit-learn
•	XGBoost
•	Matplotlib, Seaborn
•	Jupyter Notebook / Google Colab
________________________________________
# 3. Estructura del repositorio
├── data/
│   └── CAP600_data_limpia.csv       # Dataset utilizado Enapres Cap. 600
├── notebooks/
│   └── IDL3_Modelo_Predictivo.ipynb # Notebook con fases 1-9
├── src/
│   └── modelo_enapres.py            # Código en formato .py
├── results/
│   ├── metricas_cv.csv              # Resultados de validación cruzada
│   ├── resultados_predicciones.csv  # Predicciones de modelos optimizados
│   └── graficos/                    # Gráficas ROC, PR, importancia de variables, etc.
└── README.md                        # Documentación del proyecto
________________________________________
# 4. Resultados principales
•	Los modelos de ensamble (Random Forest y XGBoost) alcanzaron las mejores métricas de desempeño.
•	Recall > 0.90 y F1-score > 0.70 en la clase positiva (cambio de hábito).
•	Variables más influyentes: percepción de inseguridad, confianza en la policía, edad, sexo y experiencias de victimización.
________________________________________
# 5. Conclusiones y recomendaciones
•	Los modelos predictivos permiten identificar poblaciones más propensas a modificar hábitos frente a la inseguridad.
•	Mujeres y adultos mayores son los grupos con mayor propensión al cambio de hábitos.
•	Se recomienda implementar este tipo de análisis en plataformas Big Data (Hadoop, Spark) y dashboards interactivos (Power BI, Looker Studio).
________________________________________
# 6. Autor
•	Nek Ryan Jimenez Mandujano – Estudiante de Ciencia de Datos e IA
•	Curso: Machine Learning I
•	Docente: Sergio Victor Orizano Salvador
•	Instituto: Continental
•	Año: 2025

# 7 Ejecución del proyecto
•	Entorno virtual
python -m venv_Machine-Learning-I-IDL3
venv_Machine-Learning-I-IDL3\Scripts\activate.bat

•	Librerias
anyio==4.10.0
argon2-cffi==25.1.0
argon2-cffi-bindings==25.1.0
arrow==1.3.0
asttokens==3.0.0
async-lru==2.0.5
attrs==25.3.0
babel==2.17.0
beautifulsoup4==4.13.4
bleach==6.2.0
certifi==2025.8.3
cffi==1.17.1
charset-normalizer==3.4.3
colorama==0.4.6
comm==0.2.3
contourpy==1.3.3
cycler==0.12.1
debugpy==1.8.16
decorator==5.2.1
defusedxml==0.7.1
executing==2.2.0
fastjsonschema==2.21.2
fonttools==4.59.1
fqdn==1.5.1
h11==0.16.0
httpcore==1.0.9
httpx==0.28.1
idna==3.10
ipykernel==6.30.1
ipython==9.4.0
ipython_pygments_lexers==1.1.1
ipywidgets==8.1.7
isoduration==20.11.0
jedi==0.19.2
Jinja2==3.1.6
joblib==1.5.1
json5==0.12.1
jsonpointer==3.0.0
jsonschema==4.25.0
jsonschema-specifications==2025.4.1
jupyter==1.1.1
jupyter-console==6.6.3
jupyter-events==0.12.0
jupyter-lsp==2.2.6
jupyter_client==8.6.3
jupyter_core==5.8.1
jupyter_server==2.16.0
jupyter_server_terminals==0.5.3
jupyterlab==4.4.6
jupyterlab_pygments==0.3.0
jupyterlab_server==2.27.3
jupyterlab_widgets==3.0.15
kiwisolver==1.4.9
lark==1.2.2
MarkupSafe==3.0.2
matplotlib==3.10.5
matplotlib-inline==0.1.7
mistune==3.1.3
nbclient==0.10.2
nbconvert==7.16.6
nbformat==5.10.4
nest-asyncio==1.6.0
notebook==7.4.5
notebook_shim==0.2.4
numpy==2.3.2
overrides==7.7.0
packaging==25.0
pandas==2.3.1
pandocfilters==1.5.1
parso==0.8.4
pillow==11.3.0
platformdirs==4.3.8
prometheus_client==0.22.1
prompt_toolkit==3.0.51
psutil==7.0.0
pure_eval==0.2.3
pycparser==2.22
Pygments==2.19.2
pyparsing==3.2.3
python-dateutil==2.9.0.post0
python-json-logger==3.3.0
pytz==2025.2
pywin32==311
pywinpty==3.0.0
PyYAML==6.0.2
pyzmq==27.0.1
referencing==0.36.2
requests==2.32.4
rfc3339-validator==0.1.4
rfc3986-validator==0.1.1
rfc3987-syntax==1.1.0
rpds-py==0.27.0
scikit-learn==1.7.1
scipy==1.16.1
seaborn==0.13.2
Send2Trash==1.8.3
setuptools==80.9.0
six==1.17.0
sniffio==1.3.1
soupsieve==2.7
stack-data==0.6.3
terminado==0.18.1
threadpoolctl==3.6.0
tinycss2==1.4.0
tornado==6.5.2
traitlets==5.14.3
types-python-dateutil==2.9.0.20250809
typing_extensions==4.14.1
tzdata==2025.2
uri-template==1.3.0
urllib3==2.5.0
wcwidth==0.2.13
webcolors==24.11.1
webencodings==0.5.1
websocket-client==1.8.0
widgetsnbextension==4.0.14
xgboost==2.1.1

pip install -r requirements.txt

•	Clonar repositorio
git clone https://github.com/NekRyan/Machine-Learning-I-IDL3.git