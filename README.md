# Reporte_sobre_los_habitantes_por_vivienda_usando_los_datos_del_ENIF

## **1. Descripción General de la Base de Datos**

La base de datos proviene de la **Encuesta Nacional de Inclusión Financiera (ENIF) 2024**, realizada por el **INEGI**. Esta encuesta fue aplicada a un total de **13,303 personas**, quienes respondieron preguntas sobre diversas características de su vivienda y situación económica. Para más información revisar este [link](https://www.inegi.org.mx/app/descarga/ficha.html?tit=2534415&ag=0&f=csv).

## **2. Variable de Interés**

La variable de interés en este proyecto es **"personas por vivienda"**, que se utiliza como objetivo para predecir. Esta variable está representada en la columna **`fac_viv`** en la base de datos, la cual indica el número de personas que habitan en cada vivienda dentro de la muestra.

## **3. Descripción de las Variables**

La base de datos contiene varias variables tanto categóricas como numéricas. A continuación, se describe algunas de las principales variables:

* **`p0_4_1A`**: Número de automóviles en la vivienda (numérica)
* **`p0_4_2`**: Si la vivienda tiene acceso a internet (categórica: 1 para Sí, 2 para No)
* **`p1_1`**: Año de construcción de la vivienda (numérica)
* **`p1_2`**: Si las personas comparten el mismo gasto para comida (categórica: 1 para Sí, 2 para No)
* **`p1_3`**: Número de grupos de personas con gasto separado para comida (numérica)
* **`folio`**: Folio único de registro (categórica)
* **`ent`**: Estado donde se encuentra la vivienda (categórica)
* **`tloc`**: Tamaño de localidad (categórica)
* **`region`**: Región geográfica del país (categórica)

Estas variables permiten realizar un análisis detallado de las condiciones económicas y sociales en las viviendas.

## **4. Análisis y Modelos**

Se aplicaron varios modelos de regresión para analizar la relación entre las variables explicativas y la variable dependiente de interés.

## **5. Referencias**

* **INEGI**. (s. f.). *Descarga masiva*. Recuperado el 14 de agosto de 2025, de [INEGI](https://www.inegi.org.mx/app/descarga/ficha.html?tit=2534415&ag=0&f=csv).
* **ChatGPT**. (2025). *IA para redacción de proyectos*. Recuperado el 14 de agosto de 2025, de [ChatGPT](https://chatgpt.com/).

## **6. Conclusiones**

Este análisis proporciona una visión general de cómo las características económicas y de vivienda pueden influir en la cantidad de personas por vivienda. Los modelos de regresión, aunque no extremadamente precisos, ayudan a identificar algunas de las variables más influyentes, como los baños completos y la cantidad de cuartos a dormir.

## Archivos relevantes:
* [Archivo en ipynb](Proyecto_1.ipynb)
* [Archivo en HTML](Proyecto_1.html)
* [Base de datos](conjunto_de_datos_tvivienda_enif2024.csv)
* [Diccionario de la base de datos](diccionario_datos_tvivienda_enif2024.csv)
