# Laboratorio Extra

**1. OBJETIVOS** 

**Objetivo General:**

* Analizar y comprender el funcionamiento de varios circuitos para implementar la materia estudiada a partir de simuladores. 

**Objetivo Específicos:**

* Comprender el metodo de la maxima transferencia de potencia a partir del simulador tinkercad construyendo un circuito simple.

* Relacionar el circuito de maxima transferencia de potencia con el vatimetro a partir del simulador dcac lab. 

* Analizar el metodo de superpocicion para determinar los valores que solicita el problema para obtener un mejor conocimiento sobre lo que sucede con este metodo.

* Examinar el circuito de Thevenin para resolver problemas sintetizando varias partes del circuito para encontrar valores especificos. 

**2. MARCO TEORICO**

**Teorema de Superposicion**

![Teorema de Superposicion](https://user-images.githubusercontent.com/105677231/183779585-1b03486a-34cc-4254-8b9f-724ee45ec4a6.JPG)
***

**Teorema de Thevenin**

![Teorema de Thenevin](https://user-images.githubusercontent.com/105677231/183779622-ea299748-cc84-4351-994f-2c0c6d47798f.JPG)
***

**3. EXPLICACIÓN DEL PROCEDIMIENTO**

**CIRCUITO 1**
La primera pregunta indica que, mediante el circuito equivalente de Thevenin, se determine la potencia suministrada en la resistencia R3.

![image](https://user-images.githubusercontent.com/105677231/183782985-db0dea3b-fb36-4ad9-9761-4d5fa18efe9d.png)

- Primeramente se tiene que armar el circuito, obteniendo lo siguiente:

![image](https://user-images.githubusercontent.com/105677231/183783044-e79cb572-3baa-48fb-93a1-163bce45ba65.png)

-El teorema de Thevenin dice que, cualquier circuito puede ser simplificado obteniendo una fuente de voltaje y una resistencia a las que se las denominará con el voltaje y resistencia equivalente de Thevenin. 

-Para obtener estos valores se debe indicar una resistencia de carga, la cual se quitará para poder obtener el voltaje y resistencia de Thevenin. En este caso se quitará la resistencia de 2.2 kΩ. 

**Por lo tanto el voltaje de Thevenin es el siguiente:**

![image](https://user-images.githubusercontent.com/105677231/183783388-b08cdfaf-caae-4325-9f30-30032a37beef.png)

-Se coloca el multimetro en los extremos del circuito abierto para medir el voltaje de Thevenin.

**La resistencia equivalente de Thevenin es la siguiente:**

![image](https://user-images.githubusercontent.com/105677231/183783492-1861766b-7bc7-48e2-9e2f-c1dccba5ee8f.png)

-Para determinar la resistencia de Thevenin, se reemplazan las fuentes por su resistencia interna, la cual es un circuito cerrado o simplemente un cable de conexion. 

**El circuito de Thevenin:**

![image](https://user-images.githubusercontent.com/105677231/183783652-f708807f-f448-4112-8d55-019b02aa9df0.png)

-En este caso se ha utilizado un potenciometro para obtener el valor exacto de la resistencia calculada o medida en la parte de la resistencia equivalente de Thevenin. De esta manera se obtienen los resultados obtenidos para proceder a sacar la potencia que existe en R3 o resistencia de carga. 

![image](https://user-images.githubusercontent.com/105677231/183784022-a97cc58f-c4ef-4a8e-be4c-0725fa02398c.png)

-Para comprobar el resultado de la potencia, se utiliza un vatímetro, que ayudará en la medicion de esta magnitud. Utilizando el DCACLab.

![image](https://user-images.githubusercontent.com/105677231/183783895-b79c66d6-6493-4159-995a-2f201475a55f.png)







