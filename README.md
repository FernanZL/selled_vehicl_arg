# Análisis y Forecasting Registros de la Propiedad del Automotor

Este proyecto realiza un análisis estadístico y un forecasting sobre un dataset del registro de la propiedad del automor en Argentina.
En la página del [IPECD](https://estadistica.corrientes.gob.ar/datosabiertos/), se encuentra este dataset [DNRPA](https://estadistica.corrientes.gob.ar/datosabiertos/files?dataset=5), que contiene el número de registros de autos y motos de Argentina, por provincia, desde el 2014 hasta el 2024. Puedes descargar el dataset mediante el mencionado enlace.
La idea es realizar un breve análisis estadístico y entrenar un modelo simple para predecir la cantidad de registros a futuro. 
Puedes ver el gráfico de Tableau en el siguiente [enlace](https://public.tableau.com/views/Book1_17405003357540/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Archivos incluidos

- 'selled_vehicles_arg.ipynb': notebook que contiene el análisis realizado.
- 'Reg_vehic_arg.png': imagen del gráfico de Tableau.
- 'selled_vehicles_arg.pdf': captura en pdf del archivo de Power BI.
- 'selled_vehicles_arg.pbix': archivo Power BI.

## Requisitos

Para ejecutar el proyecto, se necesita Python 3.9 y las siguientes librerias: 
- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn
- jupyter
- lightgbm
- optuna
- statsmodeels
- scipy

Para instalar las dependencias, puedes usar el siguiente comando:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn lightgbm optuna statsmodels scipy jupyter
```

## Descargar el Dataset
Antes de ejecutar el proyecto, descarga el dataset desde el link provisto más arriba y colócalo en la misma carpeta donde se encuentra la notebook de Jupyter ('selled_vehicles_arg.ipynb').

## Como Ejecutar

1. Clona el repositorio
Si no tienes Git instalado, primero [instálalo](https://git-scm.com/), luego ejecuta este comando en tu terminal para clonar el repositorio:
```bash
git clone https://github.com/FernanZL/selled_vehicl_arg.git
```

2. Instala las dependencias
Una vez que hayas clonado el repositorio, instala las librerías necesarias con el siguiente comando:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn lightgbm optuna statsmodels scipy jupyter
```

3. Abrir la notebook
Para abrir la notebook en Jupyter, ejecuta el siguiente comando en la terminal:

```bash
jupyter notebook selled_vehicl_arg.ipynb
```

Dentro de la notebook de Jupyter, puedes ejecutar las celdas del código una a una presionando Shift + Enter para realizar el análisis y obtener los resultados.
