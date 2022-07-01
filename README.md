Sitio web: [Football Match Prediction](https://Faegru.github.io/FMP_UB_final_project_2022/)

Repositorio Original del proyecto: [Capstone-Project-UB-Footbal_Match_Predicction](https://github.com/Faegru/Capstone-Project-UB-Footbal_Match_Predicction) (Importante: las versiones contenidas en ese repositorio estan desactualizadas)

Reconocimiento: El sitio web fue creado a partir del repositorio [fastpages](https://github.com/fastai/fastpages) siguiendo el tutorial "[How to build a Portfolio website that supports Jupyter notebooks using fastpages](https://www.youtube.com/watch?v=sepml4GLLSM)" de [Data Professor](https://www.youtube.com/c/DataProfessor).

# Capstone-Project-UB-Footbal_Match_Predicction
Proyecto final del posgrado de DataScience de la UB 2021/2022

Autor: Iván Fernández Aguirre

Este proyecto explora datos de partidos de fultbol buscando entender las distintas variables para desarrollar un modelo predictivo (aun bastante precario) para resultados de partidos.

El proyecto consta de bloques contenidos en la carpeta "/_notebooks":

1_Exploracion_Inicial: Aquí se explora el dataset original tratando de entender las distintas features. Este notebook carga directamente los datos originales.

2_Corrección_del_dataset: Aquí se corrigen los valores faltantes en el dataset, asi como se eliminan algunas muestras sin casi información. Se genera como resultado un nuevo dataset "FMP_clean". Este notebook carga directamente los datos originales.

3_Tratamiento_de_Variables: Aquí se hace el procesamiento de las features para tratar de mejorar su capacidad predictiva. Se genera como resultado un nuevo dataset: "FMP_final". Este notebook carga el dataset "FMP_clean", asique debe correse después del "2_Corrección_del_dataset".

4_Análisis_del_Dataset_Final: Este datset realiza un segundo analisis de datos, pero centrado en comprender un  poco las variables nuevas generadas. Este notebook carga el dataset "FMP_Final", asique debe correse después del "3_Tratamiento_de_Variables".

5_Modelado_de_los_datos: Aquí se desarrollan y ponen en uso los modelos predictivos. También se trabaja en en balanceo de las clases y en el shapping de los datos para su carga en los modelos. Se exportan dos datasets "FMP_Balance_V_vs_D" y "FMP_training_bal_tot", para luego analizar los datasets balanceados. Este notebook carga el dataset "FMP_Final", asique debe correse después del "3_Tratamiento_de_Variables".

6_Analisis_Data_Frame_Modelo: Se explora y compara los datasets "FMP_Balance_V_vs_D" y "FMP_training_bal_tot" en comparación con "FMP_Final".

Functions_for_FMP: Este notebook contiene una gran mayoria de las funciones utilizadas en todos los notebooks. Es utilizado como una librería o modulo.

Los datos fueron tomados de un desafío Kaggle: https://www.kaggle.com/c/football-match-probability-prediction y pertenecen a Octosport and Sportmonks.
