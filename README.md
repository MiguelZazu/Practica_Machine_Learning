Realizo la prediccion, leyendo y analizando el csv. Después, elimino columnas redundantes o columnas que no añaden valor viendo la correlación que tienen con otras columnas. Además, transformo las columnas de texto que son utiles en números para poder ejecutar el modelo. 
Pruebo por encima modelos de regresión lineal, random forest, XGBoost y lightGBM y me decanto por el modelo de Random Forest aunque tiene un mse un poco por encima al de XGBoost. Me doy cuenta que puedo mejorar el entrenamiento eliminando outliers muy fuera de lo común y
vuelvo a probar el modelo.
