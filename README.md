# Proyecto Robots


### Robot con 3 grados de libertad

Nuestro proyecto para la clase de fundamentos de robot manipuladores consistirá en la simulación 
programada para la obtención de matrices utilizando el famoso método de matriz de transformación 
homogénea denavit-hartenberg

La elaboración de la matriz homogénea se obtendrá con la ayuda del software MATLAB. Por nuestra 
parte desarrollaremos las matrices como el profesor nos ha proporcionado el conocimiento en clase 
haciendo los a mano, para verificar y comprobar que la obtención de los resultados sea de manera 
coherente, afirmativa y correcta.

De tal forma que después de la obtención correcta de los resultados, migraremos la información 
establecida de nuestro programa local al software Arduino. 

Justo después de la migración a Arduino intentaremos corroborar la información obtenido en sus 
respectivos softwares simuladores, tanto electrónicos como mecánicos. Con las debidas medidas de 
seguridad y prevención médica intentaremos de ser posible llevar los cálculos a un modelo físico.

En el programa calculamos con atuda del métode denavit-hartenberg las matrices de traslacion y 
rotación. Este programa se le ingresa los numero de los brazos y los valores para el calculo de las 
matrices.

De manera directa nos podemos encontrar con los siguientes archivos:

Este repositorio cuenta con 4 programas

1. Este programa incluye los cálculos para la cinemática directa de cualquier robot con sus respectivos brazos. Este programa esta elaborado en MATLAB y al correr el programa despliega una pantalla preguntando el numero de eslabones que contiene el brazo robotico para sus respectivos cálculos. Se tienen que ingresar igualmente lo valores para cada unos de los brazos y al finalizar muestra las matrices resultantes.

2. Este programa se descarga una libreria para que Matlab simule de manera en que sale un brazo robotico con las especificaciones dadas en la matriz, para asi corroborar que los valores de la cinematica directa comparada con los valores de los angulos y las distancias sean correctas.

3. Esta programa de comunicación entre MATLAB + Arduino, se instala un complemento de hardware para arduino que se llama "MATLAB Support package for Arduino Hardware", esto nos permirte declarar el arduino y revisar la comunición, el puerto que se esta utilizando, la placa Arduino, los pines disponibles y las librerias que se pueden utilizar. Para el movimiento se declara el arduino con el puerto y la placa que se esta utilizando, al declarar los servomotores se pone en que pines esta conectado y a que arduino para asi escribir la posicion en la que se tiene que mover.

4. Para el cuarto programa se utilizo el software Tinkercad, que se pueden hacer distintas simulaciones electronicas y nosotros utilizamos un arduino Uno para la simulacion de movimiento de los servomotores teniendo dos modos de uso, el primer modo con un movimiento manual el cual nos permite mediante potenciometros manipular cada uno de los servomotores de nuestra simulación. Para el cambio de modo utilizamos un switch, una vez que se activa este switch cambia al modo Matlab, en este modo introduciremos los valores mediante el monitor serial para asi modificar cada una de las posiciones o angulos de nuestros servomotores. 

Este repositorio tambien cuenta con dos modelos, uno representa el modelo fisico con sus eslabones mientras que el otro mostrara los movimientos de los servomotores controlados por un arduino.

Por ultimo, se agrego un documento en extensión .pdf que contiene todas las investigaciones realizadas para la elaboración de este proyecto y sus resultados pertinentes asi como algunas explicaciones de algunos materiales para la elaboración fisica de este proyecto.

Igualmente se encuentran dos carpetas en el repositorio, la carpeta "Codigos" contiene todos los codigos de las simulacione en formato de nota de texto .txt para una sencilla manipulación de los codigos, la segunda carpeta "Escrito_Proyecto" contiene el trabajo escrito que contiene todos los detalles del proyecto.

### Archivos en Git

| Archivos | Contenido |
| --- | --- |
| Link_Modelo.txt | Link del modelo del brazo y servomotores |
| Modelo_brazo_mecánico_FDRM.zip | Modelo del brazo en extensión .obj |
| Movimiento.mlx | Archivo movimiento y conexión MATLAB y Arduino |
| Proyecto_Final_Robots.pdf | Documento final del proyecto |
| Readme | Caracteristicas generales del proyecto |
| Servomotor_Arduino_Programa.txt | Programa en idioma Arduino para movimiento de servomotores |
| Untitled.mlx | Archivo solución de matrices MATLAB |

### Equipo 

| Integrantes | Clave |
| --- | --- |
| Andrade Tirado Marco Antonio | 171632 |
| Cisneros Noriega Mario Alberto | 172134 |
| Hernandez Sanabria Diego Amaury | 171990 |
| Pérez Ponce Luis Antonio | 170856 |
| Sanchez Rodriguez Alberto Andres | 171547 |
