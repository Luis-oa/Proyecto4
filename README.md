# Proyecto4

Contenido del repositorio:

El archivo p4.py contiene el proyecto 4 para cualquier IDE de python. Por cualquier cosa, se agrega también el .ipynb para abrirlo en el 
notebook de jupyer. Como adicional, se presenta el .html como presentación habitual del proyecto.

Descipción del proyecto:

- En primer lugar, se busca simular el sistema de comunicaciones utilizando una modulación QPSK en lugar de una modulación BPSK. La intención
es mostrar si este modelo puede recuperar de manera similar la imagen con una portadora diferente. Es importante destacar que según la
teorìa, el error entre las imgánenes en cuestión debe ser aproximadamente igual para ambos modelos. Se modifica la relación señal-a-ruido del 
canal y se modifica el criterio de detecciòn de energìa de la demoduladora para generar una imagen recuperada muy similar a la original. 

- Seguidamente, se procede a hacer pruebas de estacionalidad y ergodicidad. Para ello, se recurre al código implementado en el laboratorio 4. Se 
calcula el promedio de la media de las 4 ondas por separado. Estas ondas se generan con las 4 posibles combinaciones de variable aleatoria presentes
para la moduladora QPSK, este promedio se compara con la media de la 'senal_TX' (señal modulada) y se agregan conclusiones de los resultados.

- Por último, se grafica la densidad espectral de potencia para la señal modulada senal_Tx. Para esto, se implementa el método que brinda el profesor
en el video del proyecto. Este genera una gráfica con el espectro de la transformada de fourier para la señal modulada del método QPSK (senal_Tx).

Estudiante: Luis Oviedo
Carné: B65206
