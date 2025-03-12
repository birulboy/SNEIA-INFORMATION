![image](https://github.com/user-attachments/assets/1959697a-13b7-44af-bfc5-2af78bf4ec64)# SNEIA-INFORMATION

Que es una red neuronal?
es un modelo computacional que imita una neurona

como funciona?
https://github.com/user-attachments/assets/d55dd5e8-e4ba-40f9-b07d-cce66adcbcb7
existen unas entradas las cuales se multiplican por los pesos.
la sumatoria de los pesos se manda como activacion.
siempre tiene que haber una funcion de activacion
calculo de perdida mide el error entre el valor dado y el esperado

![image](https://github.com/user-attachments/assets/b6ab5f8d-c946-44c4-8e44-4b7d34519ffc)

Los datos tienen que estar preprocesados
El cerebro humano siempre recibe informacion de varias partes , se busca quitar el "ruido" y dejar solo la actividad cerebral


señal sucia , es la que entra el modelo 
señal limpia , son las respuestas correctas 


np.sign ( algo asi)


izquierda limpia , derecha con ruido
![image](https://github.com/user-attachments/assets/c62a5b75-72d2-461f-84e1-09c562aa9ecc)



Hay que escalar los datos, siempre intentar manejar modelos computacional mente pequeños

No se pueden usar todos los datos para entrenar , por que la red no debe aprender de todo , siempre se tiene que enfrenter la incertidumbre , si se le entregan todos los datos se los va a aprender pero no va a ser capaz de enfrentarse a nuevos datos.


 hyperparametros , parametros que si se le pueden dar a la red.
 test:size tamaño del teseo
 random.state reproducibilidad

 Validacion Cruzada , entrenar con una parte de los datos


 Bias es un valor adicinal que se suma al resultado de las entradas multiplicadas ( Entrada de la neurona) 
 se pone para evitar el sobreentrenamiento 
 ![image](https://github.com/user-attachments/assets/612ddaaf-7d4e-4538-8841-49403442d260)
 ![image](https://github.com/user-attachments/assets/977bb71a-7a1b-4b26-b85f-5b256b583721)
 explotacion del gradiente genera demasiado aumento en el peso de esta , inhabilitando las respuestas de las demas
 el desvanecimiento reduce a 0 el peso de una neurona inhabilitando a esta y las siguientes que esten relacionadas.
![image](https://github.com/user-attachments/assets/8334b5d2-f2c8-433a-a7f5-65b894b5eaa4)
![image](https://github.com/user-attachments/assets/926d6819-0b70-4ebb-8db2-fe7bd1f994a4)

![image](https://github.com/user-attachments/assets/f9123918-a160-41f2-bab9-3d4afb41eca1)


MSE castiga mas los valores alejads
MAE castiga mas los valores atipicos                               
Tolerancia , hasta que punto estoy bien


Secuenciales , densos
secuenciales sigue neurona tras neurona ( de manera lineal ).
denso todas las neuronas estan conectadas.

![image](https://github.com/user-attachments/assets/e28e2aad-5393-41fb-ae74-faf146a01b1d)
La ultima capa siempre se cambia ( Para Expresar la salida dependiendo de lo requerido ). 




