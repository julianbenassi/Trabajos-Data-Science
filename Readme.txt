Los códigos corresponden al trabajo final del curso Data Science en Digital House.

Se trata de un trabajo de clasificación de archivos informáticos maliciosos desconocidos. Estos archivos se encuentran en un dataset específico. 

El primer paso (Parte 1) consistió en agrupar los archivos maliciosos desconocidos, de acuerdo a las características que los definen como maliciosos.
Para esto se clusterizaron los datos utilizando KMEANS. El resultado determinó que los archivos maliciosos se agrupen en 2 clusters.

El segundo paso (Parte 2 y 3) fue entrenar algoritmos de clasificación, con distintos grados de complejidad, de acuerdo a un dataset que contaba con archivos maliciosos clasificados.
Este dataset difiere del utilizado para el paso 1.

Una vez entrenados los modelos, considerando que sus performances eran correctas, se testearon con los clusters del paso 1. Esto determinó que los archivos maliciosos puedan ser clasificados.
Pudo observarse que en los modelos menos complejos, los archivos maliciosos se dividían en 4 tipos de archivos. Mientras que al incrementar la complejidad de los algoritmos, los archivos desconocidos caían dentro de 2 grupos mayoritarios. Lo que nos permitió llegar a conclusiones apropiadas.

Los datos utilizados son verídicos y corresponden a archivos maliciosos de diferentes países de Sudamérica.  

   