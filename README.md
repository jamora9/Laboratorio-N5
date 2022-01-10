# Laboratorio-N5
# Objetivos

# Objetivo General
- Analizar el circuito esquemático propuesto, aplicando el teorema de Thevenin, para comprobar mediante un experimento práctico los resultados analíticos y experimentales para llegar a plantear conclusiones que ayuden al endentimiento total de este teorema.

# Ojetivos específicos

1. Explicar de manera teórica el Teorema de Thevening por medio de un cuadro sinóptico.
2. Comprobar experimentalmente el Teorema de Superposición en un circuito resistivo.
3. Interpreatar los resultados de los valores del circuito equivalente obtenidos los cuales permitan dar conclusiones respecto al teorema utilizado.

# Marco teórico
![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Teorema%20de%20Thevenin%201.png)
![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Teorema%20de%20Thevenin%202.1.png)

- Material y equipo requerido

|Cantidad| Material o Equipo|
|--------|------------------|
|2| Fuente de Voltaje de C.D.|
|2| Multímetro Digital|
|1| Resistor de 560 Ω|
|1| Resistor de 4.7 kΩ|
|1| Resistor de 330 Ω|
|1| Resistor de 100 Ω|
|1| Resistor de 1 kΩ|
|1|Potenciómetro de precisión de 1 kΩ|
|1|Protoboard|

# Procedimiento
- Implemente el circuito que se presenta en la figura

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20173452.png)

- Resolución simulada

Conección del circuito

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20195708.png)

Voltaje del circuito original

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20202219.png)

Corriente del circuito original

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20202407.png)

Voltaje de Thevenin

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20202629.png)

Resistencia de Thevenin

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20195445.png)

Circuito equivalente de Thevenin

Voltaje 

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20201024.png)
![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-10%20145410.png)

Corriente

![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-06%20201336.png)
![](https://github.com/jamora9/Laboratorio-N5/blob/main/Ima/Captura%20de%20pantalla%202022-01-10%20145552.png)

- Resolución analitica
Arme el circuito que se presenta en la figura 5.1

Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93900233/148816500-8eea7924-a10c-4658-b9b7-09877eb044d8.png)
![image](https://user-images.githubusercontent.com/93900233/148816732-3a94a99c-bcb6-48f0-879b-38e648a759dc.png)

Desconecte la resistencia R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93900233/148816925-250c20c9-b766-4bf2-aa2c-57ecb67309d2.png)

![image](https://user-images.githubusercontent.com/93900233/148817019-eb9fd91b-b122-4e4b-9bb6-0fb8c0e4d38d.png)

![image](https://user-images.githubusercontent.com/93900233/148817074-4cdd49eb-2ead-4827-886d-8480f98f3c8c.png)

![image](https://user-images.githubusercontent.com/93900233/148817192-d26527f5-1ebf-4b90-a0e8-c29cd8a3fa7f.png)

![image](https://user-images.githubusercontent.com/93900233/148817366-602f0d59-4af5-4bdf-a562-a008b3d492a5.png)

![image](https://user-images.githubusercontent.com/93900233/148817416-ab5e0a26-61bc-4712-88ac-9346b4efb987.png)

Anule el efecto de las fuentes de alimentacion. Desconectó R5 y desde el circuito abierto resultó mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93900233/148817701-12341d0a-d6ab-47a5-b2df-23206ac9623d.png)

Implemente el circuito equivalente de Thévenin, agregue la resistencia R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93900233/148817856-7bf91b57-30b2-4740-8267-4b9edda855a3.png)

- Resultados obtenidos para el circuito.

ERRORES

![image](https://user-images.githubusercontent.com/93900233/148818132-045adb6d-e5a8-4ecb-af88-31ce32478350.png)

![image](https://user-images.githubusercontent.com/93900233/148818221-5b0e5568-4735-4be5-9f00-126eeaec8be1.png)


Tabla 5.1. Valores del Circuito Equivalente de Thevenin

|VTH |(V)|RTH |(Ω)|
|----|---|---|----|
|Calculado|5.05 [V]|Calculado|298.85 [Ω]|
|Medido|5.06 [V]|Medido|299 [Ω]|

Tabla 5.2. Comprobación del Teorema de Thevenin.

|Parámetro eléctrico|Circuito Original|Circuito equivalente de Thevenin|
|-------------------|-----------------|--------------------------------|

||Calculado|Medido|Calculado|Medido|
|-|--------|-------|--------|------|
|Voltaje (V)|3.88 [V]|3.89 [V]|3.88 [V]|3.90 [V]|
|Corriente (mA)|3.88 [mA]|3.89 [mA]|3.88 [mA]|3.89 [mA]|
# Video

https://youtu.be/C2Qhv9twRkM

# Conclusiones 
En conclusión, comprobamos que se cumple el teorema de Thévenin, llegamos a la conclusión de que este teorema nos sirve para simplificar el circuito para de esta forma hacer un circuito equivalente con menos elementos, o sea, en el planeta de las aplicaciones nos sirve para emular circuitos de productos originales y obtener uno equivalente, sin embargo disminuyendo el precio de construcción. 

# Bibliografía

- Floyd, T. (2007). Principios de circuitos eléctricos (8a. Ed.) (8a ed.). Naucalpan de Juárez: Pearson Educación.
