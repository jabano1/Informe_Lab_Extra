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

**CIRCUITO 2**

-EL segundo ejercicio dice que se debe encontrar la corriente y el voltaje a traves de la resistencia de 12Ω mediante el teorema de superposición. 

![image](https://user-images.githubusercontent.com/105677231/184025417-de69e5de-ced4-4843-bcd7-13b23b2bac79.png)

- Primeramente se tiene que armar el circuito, obteniendo lo siguiente:

![image](https://user-images.githubusercontent.com/105677231/184025522-6f4939d2-ff9f-48ce-a7b1-2b6782ca41f6.png)

-El teorema de superposicion indica que se deben reemplazar las fuentes de corriente y de voltaje por su resistencia interna. Dependiendo de cuantas fuentes de corriente o de voltaje se tenga, se formaran los circuitos. En otras palabras, el numero de fuentes de voltaje o de corriente es igual al numero de circuitos. 

- Para formar el primer circuito, se reemplazará la fuente de 10 voltios por su resistencia interna la cual tiene un valor de cero. Se procede a medir el voltaje que pasa a traves de la resistencia de 12Ω. 

![image](https://user-images.githubusercontent.com/105677231/184026134-cc6a5c34-628a-4097-a9ae-0053ee37878e.png)

-A su vez se tiene que medir la corriente que pasa por la misma resistencia. 

![image](https://user-images.githubusercontent.com/105677231/184026187-53b5c655-e427-4b80-9b05-15fbdbaac993.png)

- Para formar el segundo circuito, se reemplazará la fuente de 16 voltios por su resistencia interna la cual tiene un valor de cero. Se procede a medir el voltaje que pasa a traves de la resistencia de 12Ω.

![image](https://user-images.githubusercontent.com/105677231/184026239-e6371258-e220-4513-8ce5-01c3bf17e0f9.png)

-A su vez se tiene que medir la corriente que pasa por la misma resistencia. 

![image](https://user-images.githubusercontent.com/105677231/184026273-666f299a-b28c-451d-b0b7-4b70a42200ec.png)

-Finalmente, se procede a calcular la corriente total y el voltaje total que pasa por esa resistencia. 

![image](https://user-images.githubusercontent.com/105677231/184026490-f43f9068-8572-46e9-9576-b8bcf6bba889.png)


**CIRCUITO 3**

-El planteamiento de este circuito indica que se debe calcular la intensidad que pasará por la resistencia de 5Ω utilizando Thevenin. Para esto se tiene que armar el circuito, dando como resultado: 

![image](https://user-images.githubusercontent.com/105677231/184026741-e5be52fb-0a2d-49a2-ad8f-7efd16288dff.png)

-Como se habia mencionado antes, el teorema de Thevenin dicta que, cualquier circuito puede ser simplificado obteniendo una fuente de voltaje y una resistencia a las que se las denominará con el voltaje y resistencia equivalente de Thevenin. 

-En este caso la resistencia de carga será la de 5Ω, y es la que se quiere calcular la intensidad de corriente. 

**Por lo tanto el voltaje de Thevenin quitando la resistencia de 5ohms es el siguiente:**

![image](https://user-images.githubusercontent.com/105677231/184026942-446332a0-7f51-422b-a0ac-1a47b20ccda1.png)

-Se coloca el multimetro en los extremos del circuito abierto para medir el voltaje de Thevenin.

**La resistencia equivalente de Thevenin es la siguiente:**

![image](https://user-images.githubusercontent.com/105677231/184027030-2a4a2cc0-ea7c-4384-8a54-1c45fc30fc23.png)

-Para determinar la resistencia de Thevenin, se reemplazan las fuentes por su resistencia interna, la cual es un circuito cerrado o simplemente un cable de conexion. 

**El circuito de Thevenin:**

![image](https://user-images.githubusercontent.com/105677231/184027097-a899518b-3d50-4966-afdb-c2f0019322d1.png)

-Como ya se conoce, se coloca un poteciometro para indicar el valor exacto de la resistencia de thevenin. Finalmente se procede a medir la corriente que pasa por la resistencia de 5ohms.

![image](https://user-images.githubusercontent.com/105677231/184027294-69a36013-4228-414c-9138-df16f81a010b.png)

**4.VIDEO**

https://youtu.be/kU3Ja30fJ54

**5.CONCLUSIONES**

-Se puede concluir que el teorema de superposicion es muy util al momento de trabajar con dos o mas fuentes de corriente y voltaje, ya que al simplificar los pasos para resolver un problema se vuelve mas facil su planteamiento.

-El teorema de Thevenin es muy util para convertir un circuito grande en uno mas simple para resolver las incognitas solicitadas, debido a esta simplificacion se puede determinar con facilidad el valor de la corriente y voltaje de un circuito complejo.

-La mayoria de los teoremas estudiados en clase, ayudaran en el momento de resolver problemas de diferentes planteamientos, permitiendo determinar tambien la potencia de un elemento o circuito. 

**6.BIBLIOGRAFÍA**

Floyd, Thomas. 2007. Principios de circuitos eléctricos. Octava edición.




