# Selección de características 

En este ejercicio seleccionaré las diferentes variables de una base de datos de vinos para poder determinar la calidad de algún vino, para esto hare uso de librerías especializadas. Se realizará un proceso de selección de características hacia adelante y de eliminación hacia atrás en una regresión lineal múltiple.

Los datos originales se obtuvieron de UCI Machine Learning Repository:   
[https://archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality)

Y se reportaron originalmente en "Modeling wine preferences by data mining from physicochemical properties" en la revista "Decision Support Systems":  
[https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub](https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub)

La base de datos cuenta con la siguiente información:  
* “acidezFija”. Acidez fija del vino, en gramos de ácido tartárico por decímetro cúbico.  
* “acidezVolatil”. Acidez volátil del vino, en gramos de ácido acético por decímetro cúbico.  
* “acidoCitrico”. Gramos de ácido cítrico por decímetro cúbico.  
* “azucarResidual”. Gramos de azúcar por decímetro cúbico.  
* “cloruros”. Gramos de cloruro de sodio por decímetro cúbico.  
* “dioxidoAzufreLibre”. Miligramos de dióxido de azufre libre por decímetro cúbico.  
* “dioxidoAzufreTotal”. Miligramos de dióxido de azufre total por decímetro cúbico.  
* “densidad”. Gramos por centímetro cúbico.  
* “pH”. Valor del vino en la escala de pH.  
* “sulfatos”. Gramos de sulfato de potasio por decímetro cúbico.  
* “alcohol”. Porcentaje de volumen de alcohol.  
* “calidad”. Mediana de la calidad otorgada por catadores, en escala de 0 a 10.  

-[Ver la selección de características](SeleccionVariables.html)    
-[Descargar archivo CSV (La base de datos)](Datos1_4.csv)    
-[Descargar archivo Jupyter Notebook (.ipynb)](SeleccionVariables.ipynb)
