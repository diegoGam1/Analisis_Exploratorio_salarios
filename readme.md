#  Análisis Exploratorio de Salarios en el Sector Tecnologico 
**Autor:** Diego Gamarra

---

###  Contenido

- `src/` → Contiene el archivo Jupyter Notebook `Analisis_Salarial.ipynb` con el análisis exploratorio completo, y una carpeta:
  - `data/` → Contiene:
    - `global_tech_salary.csv` → Dataset original con salarios en el sector tecnologico.
- `requirements.txt` → Lista de librerías necesarias para reproducir el análisis.

---

###  Cómo usar

1. Cloná el repositorio:
```bash
git clone https://github.com/diegoGam1/Analisis_Exploratorio_salarios.git
```

2. Instalá las dependencias:
```bash
pip install -r requirements.txt
```

---

###  Resumen del Proyecto

####  Descripción  
Este proyecto de análisis exploratorio de datos (EDA) tiene como objetivo entender la distribución de salarios en el sector de tecnología. A través de visualizaciones, estadísticas descriptivas y pruebas de hipótesis, se busca obtener insights que puedan ser útiles para comprender tendencias, desigualdades y patrones en el mercado laboral.

---

###  Objetivos Específicos
- Entender la distribución de los salarios estandarizados en USD.
- Identificar la influencia de variables como experiencia, país, modalidad de trabajo y tamaño de empresa en los salarios.
- Detectar outliers y analizarlos por separado.
- Comparar tendencias por categoría laboral y evolución a lo largo de los años.
- Probar hipótesis estadísticas sobre el promedio salarial de ciertos perfiles.

---

###  Datos Utilizados

El dataset contiene información de profesionales del sector de datos, con variables como:

-   `work_year`: Año en que se pagó el salario.
-   `experience_level`: Nivel de experiencia en el trabajo durante el año.
-   `employment_type`: Tipo de empleo para el puesto.
-   `job_title`: El rol en el que se trabajó durante el año.
-   `salary`: El monto total del salario bruto pagado.
-   `salary_currency`: La moneda del salario pagado como un código de moneda ISO 4217.
-   `salary_in_usd`: El salario en USD (tasa de cambio dividida por la tasa promedio de USD para el año correspondiente a través de fxdata.foorilla.com).
-   `employee_residence`: País de residencia principal del empleado durante el año laboral como un código de país ISO 3166.
-   `remote_ratio`: La cantidad total de trabajo realizado de forma remota.
-   `company_location`: El país de la oficina principal del empleador o sucursal contratante.
-   `company_size`: El número promedio de personas que trabajaron para la empresa durante el año.

---


### Conclusiones y Hallazgos Clave

- La mayoría de los salarios altos corresponden a profesionales en EE.UU., modalidad full time y categoría senior.
- Existe una relación positiva entre experiencia y salario, aunque no muy marcada.
- Las empresas medianas concentran la mayor parte del mercado.
- La categoría "EN" (Entry) muestra un crecimiento constante a lo largo de los años.
- Modalidades remotas y presenciales tienen mejores salarios que la híbrida.
- La prueba de hipótesis no dio suficiente evidencia para afirmar que los Data Scientists ganen menos de 150k USD, ni que ganen más.



---