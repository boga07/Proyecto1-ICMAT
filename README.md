Proyecto 1: Modelamiento Matemático con Python

IWG-400 Proyecto Inicial - Primer Semestre 2026

INTEGRANTES DEL EQUIPO

Francisco Andrés Barría González - fbarria@usm.cl

Bastián Alexander Olguín Pizarro - bolguinp@usm.cl

Cristobal Alonso Díaz Rojas - cdiazr@usm.cl

Gabriel Alonso Pereira Silva - gpereira@usm.cl

DESCRIPCIÓN PROYECTO 

Este proyecto aborda la Opción A: Dinámica de Poblaciones, enfocándose en el estudio de modelos de crecimiento poblacional (Malthus y Logístico) en versiones discretas y continuas. Se analiza la sensibilidad de los parámetros, el error del método numérico de Euler y se realiza una validación con datos reales. Como extensión (A3), se seleccionó el ajuste del modelo logístico a datos reales de crecimiento poblacional entre una raza y una subraza de mosquitos, comparando su comportamiento con el modelo de Malthus. 

ESTRUCTURA DEL REPOSITORIO
Proyecto1-ICMAT/
├── .gitignore
├── README.md
├── requirements.txt
├── data/
│   ├── Aedes_albopictus_study.pdf
│   └── README.md (Link: Harvard AM-115)
├── informe/
│   └── README.md (Link: Overleaf)
├── notebooks/
│   ├── 01_fase_base.ipynb
│   ├── 02_fase_analisis.ipynb
│   └── 03_fase_extension.ipynb
└── figs/
    ├── Análisis_de_Sensibilidad.png
    ├── Comparación_Logístico_Base.png
    ├── Comparación_Nativa_vs_Invasora.png
    ├── Crecimiento_Malthus_Mosquitos.png
    ├── Crecimiento_Logístico_Euler.png
    ├── Crecimiento_Logístico_Vector.png
    ├── Curva_Malthus_Parámetros.png
    ├── Diagrama_de_Telaraña_1.png
    ├── Diagrama_de_Telaraña_2.png
    ├── Error_Método_Euler.png
    ├── Modelo_Malthus_General.png
    └── Validación_Datos_Reales.png


INSTRUCCIONES DE INSTALACIÓN Y EJECUCIÓN

1. Preparación del entorno y dependencias, para asegurar que el código se ejecute sin errores, es necesario instalar las librerías requeridas. Recomendamos el uso de un entorno virtual. Desde la terminal en la carpeta raíz del proyecto, ejecute:
pip install -r requirements.txt
2. Ejecución de los Notebooks, los códigos fuente están organizados en la carpeta notebooks/. Para replicar los resultados del informe, deben ejecutarse en el siguiente orden:
Fase 1: Base poblacional (01_fase_base.ipynb): Implementación de los modelos de Malthus y Logístico (discreto y continuo) y el método numérico de Euler.

Fase 2: Análisis y Validación (02_fase_analisis.ipynb): Estudio de sensibilidad y validación con datos reales de levadura (Carlson).

Nota: Este notebook requiere conexión a internet para descargar el dataset directamente desde GitHub.

Fase 3: Extensión A3 (03_fase_extension.ipynb): Comparación biológica entre las razas de mosquitos Aedes albopictus.

Interactividad: Al ejecutar las celdas de simulación, el programa le solicitará por consola ingresar la Capacidad de carga (K) y el Tiempo (Generaciones). Para visualizar los escenarios del informe, se sugieren valores como 1000000 y 15.

Gráficos: El notebook genera un gráfico final interactivo mediante la librería Plotly, que permite inspeccionar valores específicos pasando el cursor sobre las curvas.

DECLARACIÓN USO DE IA

Se declara el uso de las IA's Chatgpt y Gemini, como unos guias para poder realizar tanto el codigo del proyecto como ajustar la redacción de los informes, tambien declaramos que lo utilizamos para resolver dudas a la hora de ocupar Python. Su aplicación se centró en:

Apoyo en la resolución de errores de sintaxis y optimización de algoritmos en Python (específicamente en la implementación de la lógica de la telaraña y gráficos interactivos).

Asistencia en la estructuración de las secciones del informe y refinamiento de la redacción técnica.
