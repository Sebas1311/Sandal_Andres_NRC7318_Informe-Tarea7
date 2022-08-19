# Sandal_Andres_NRC7318_Informe-Tarea7

                                                 Universidad de las Fuerzas Armadas - Espe
                                                   Fundamentos de circuitos electrónicos 
- Nombre: Andrés Sandal
- NRC: 7318
- Fecha de entrega: 19/08/2022
- Ing. Alulema Darwin

                                                          Informe Tarea N°7
                                                     
1.- Tema: Introducción a la corriente y al voltaje alternos / Capacitores

2.- Objetivos:

  2.1.- Objetivo general:
  
Determinar la definición de los inductores y transformadores, por medio de identificar los tipos y características que se hacen presentes al estar en serie y/o paralelo o aus vez cuando estan en un circuito CD y CA para poder resolver adecuadamente los ejercicios e incognitas planteadas en cada tema.
        
  2.2.- Objetivo específicos:
  
        - Describir la construcción y las características básicas de un inductor para diferenciar los varios tipos de inductores y analizar su comportamiento en los distintos circuitos.
        - Describir cómo se construye un transformador y cómo funciona al estar en incremento y disminución del voltaje con el fin de analizar el efecto de una carga resistiva a través del devanado secundario.
        - Resolver los ejercicios planteados, utilizando los conocimientos adquiridos en cada tema y subtema, de este modo lograr poner en práctica lo aprendido teóricamente.
        
3.- Marco teórico

![image](https://user-images.githubusercontent.com/105684550/185208987-52c7c034-9078-41e2-9d66-699af038ffcb.png)
Link del mapa mental: https://www.canva.com/design/DAFJibkupsc/yzPZbQU68SV6Ojy-v_4RBA/view?utm_content=DAFJibkupsc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
![image](https://user-images.githubusercontent.com/105684550/185532453-0f19a5e4-85ec-4348-859a-fa0b7d14be4c.png)

4.- Resolución

                                                                 13.- INDUCTORES
                                                                 
2. Convierta los siguientes valores en microhenries:

a) 300mH=300000µH

b) 0.08H=80000µH

c) 5mH=5000µH

d) 0.00045H=450µH

4. Se inducen 50 volts en una bobina de 25 mH. ¿Con qué rapidez cambia la corriente?

Vind=L(di/dt)

Vind/L=di/dt

50V/25mH=di/dt

di/dt=2000A/s

6. ¿Cuántas vueltas se requieren para producir 30 mH con una bobina enrollada sobre un núcleo cilíndrico cuya área de sección transversal mide 10×10^(-5) m^(2) y tiene longitud de 0.05 m? La permeabilidad del núcleo es de 1.2×10^(-6) H/m .

L=(N^2µA)/l

√((L×l)/(µA))=N

N=√((L×l)/(µA))=√(((30mH)(0.05m))/((1.2×10^(-6) H/m)(10×10^(-5) m^(2))))=√((1.5×10^(-3))/(1.2×10^(-10)))

N=√12500000=3535.534

8. Compare la inductancia de dos inductores idénticos excepto que el inductor 2 tiene dos veces la cantidad de vueltas del inductor 1.

- a) L=(N^2µA)/l,donde N=500,l=0.02m,A=3×10^(-6) m^(2),µ=0.2×10^(-3) H/m

L=(N^2µA)/l=((500)^2×(0.2×10^(-3) H/m)(3×10^(-6) m^(2)))/0.02m

L=0.75mH

- b) L=(N^2µA)/l,donde N=1000,l=0.02m,A=3×10^(-6) m^(2),µ=0.2×10^(-3) H/m

L=(N^2µA)/l=((1000)^2×(0.2×10^(-3) H/m)(3×10^(-6) m^(2)))/0.02m

L=30mH

La inductancia del inductor 1 es menor en comparación al inductor 2 que tiene el doble de vueltas, es decir, que mientras más vueltas haya en el inductor mayor será la inductancia y a su vez mientras menor sea la cantidad de vueltas menor será la inductancia.

10. Un estudiante enrolla 100 vueltas de alambre sobre un lápiz de 7 mm de diámetro como se muestra en la figura 13-43. El lápiz es un núcleo no magnético de tal suerte que su permeabilidad es igual a la de un vacío (4π×10^(-6) H/m). Determine la inductancia de la bobina que se formó. 

![image](https://user-images.githubusercontent.com/105684550/185227291-0aac7d32-15d8-410f-a6a2-3c6f12f4543b.png)

l=3.5cm=0.035m

A=πr^2=π〖(3.85×〖10〗^(-3) m)〗^2=4.657×〖10〗^(-5) m^2

L=(N^2µA)/l=((100)^2×(4π×〖10〗^(-6)  H/m)(4.657×〖10〗^(-5) m^2))/0.035m

L=0.167mH

12. Usted requiere una inductancia total de 50 mH. Tiene disponibles una bobina de 10 mH y otra de 22 mH. ¿Cuánta inductancia adicional necesita?

LT=L1+L2+LA

50mH=10mH+22mH+LA

LA=50mH-10mH-22mH

LA=18mH     →    inductancia adicional 

14. En la figura 13-45, ¿cuál es la inductancia total entre los puntos A y B con cada posición del interruptor? 

![image](https://user-images.githubusercontent.com/105684550/185227337-47e006d6-d6af-4b98-8f07-5e6234755fdb.png)

- Interruptor 1:

LT=L1+L2+L4=330µH+680µH+800µH=1810µH

- Interruptor 2:

LT=L2+L4=680µH+800µH=1480µH

- Interruptor 3:

LT=L4=800µH

- Interruptor 4:

LT=L3+L4=1500µH+800µH=2300µH

16. Usted tiene un inductor de 12 mH, y éste es su valor más bajo, pero necesita una inductancia de 8 mH. ¿Qué valor puede utilizar en paralelo con el inductor de 12 mH para obtener 8 mH?

LT=1/(1/L1+1/L2),LT=8mH,L1=12mH

1/L1+1/L2=1/LT

L2=1/(1/LT-1/L1)=1/(1/8-1/12)=1/(1/24)=24mH    →     Se necesita un inductor de este valor

18. Determine la inductancia total de cada circuito mostrado en la figura 13-47.

![image](https://user-images.githubusercontent.com/105684550/185229513-2f9e5f58-4b0c-4b99-bb4c-aa3b1fa0724c.png)

- A) L1 y L2 están en paralelo, y en serie con el paralelo de L3 y L4.

1/(1/100+1/50)+1/(1/60+1/40)

33.33 mH+24 mH=57.33 mH

- B) L1 y L2 están en serie, y en paralelo con la serie de L3 y L4.

1/(1/(8+4)+1/(4+2))=1/(1/12+1/6)=4 mH

- C) L3 y L4 están en serie, L5 y L2 también están en serie. 

L3+L4= 1mH + 1Mh= 2Mh

L5+L2= 2mH + 2Mh= 4Mh

Las resistencias resultantes se encuentran en paralelo y a su vez en serie con la resistencia L1

4+1/(1/2+1/4)=5.33 mH

20. En un circuito RL en serie, determine cuánto tiempo se lleva la corriente para incrementarse a su valor total con cada una de las siguientes combinaciones:
-Usando la fórmula de la constante de tiempo RL

- a) R= 56 Ω, L = 50 µH.

τ=L/R=(50µH)/56Ω=0.89 µs

- b) R= 3300 Ω, L = 15 mH

τ=L/R=15mH/3300Ω=4.54µs

- c) R= 22 kΩ, L = 100 mH

τ=L/R=100mH/22kΩ=4.54 µs

22. Para el inductor ideal de la figura 13-49, calcule la corriente en cada uno de los siguientes instantes:

![image](https://user-images.githubusercontent.com/105684550/185229554-4a878353-a8ad-417a-a650-e54dbb1121f4.png)

La constante de tiempo del circuito es: 

τ=L/R=(75 mH)/(8.2 kΩ)=9.14 µs

La corriente final del circuito es: 

I=Vs/R=10V/8.2kΩ=1.21 mA

- a) 10µs

i=0.63(1.21)=0.76 mA

- b) 20µs

i=0.86(1.21)=1.04 mA

- c) 30µs

i=0.95(1.21)=1.14 mA

24. Repita el problema 22 para los siguientes instantes:

a) 65µs

i=0.37(1.21)=0.44 mA

b) 75µs

i=0.14(1.21)=0.16 mA

c) 85µs

i=0.5(1.21)=0.6 mA

26. ¿Cuál es la polaridad del voltaje inducido en el inductor de la figura 13-49 cuando la onda cuadrada está creciendo?

A medida que la onda cuadrada para de cero a su valor máximo de 10V, se induce un voltaje entre las terminales del inductor que se opone a este cambio conforme aumenta el campo magnético, a medida que el campo magnético aumenta al voltaje inducido disminuye haciendo que su polaridad cambie. 

¿Cuál es la corriente justo antes de que la onda cuadrada se reduzca a cero?

i=0.2(1.21)=0.24 mA

30. Determine la resistencia total para cada circuito de la figura 13-46 cuando se aplica voltaje a una frecuencia de 5 kHz entre las terminales.

![image](https://user-images.githubusercontent.com/105684550/185229613-a873ca80-1a9e-4799-be08-9a5a453c79d8.png)

- A) Determinando la inductancia total

LT=1/(1/10+1/5)+1=4.33 H

X_L=2πfL=2π(50∙〖10〗^3 )(4.33)=1.36 MΩ

- B) Determinando la inductancia total

LT=1/(1/100+1/100)=50mH

X_L=2πfL=2π(50∙〖10〗^3 )(50∙〖10〗^(-3) )= 15.7kΩ

- C) Determinando la inductancia total

LT=1/(1/400+1/200+1/100)=57.14 µH

X_L=2πfL=2π(50∙〖10〗^3 )(57.14∙〖10〗^(-6) )= 17.95Ω

32. En la figura 13-51, determine la corriente rms total. ¿Cuáles son las corrientes a través de L2 y L3?

![image](https://user-images.githubusercontent.com/105684550/185229658-c01df79e-4527-49d0-9e56-ea4e4baa5e59.png)

- Obteniendo la inductancia total:

LT=1/(1/40+1/20)+50=63.33 µH

Datos:

2.5 kHz = 2.5∙〖10〗^3 Hz

63.33 µH= 63.33∙〖10〗^(-6) H

Por lo tanto XL=

X_L=2πfL=2π(2.5∙〖10〗^3 )(63.33∙〖10〗^(-6) )=0.9947 Ω

Entonces la corriente rms total es: 

I_rms=Vrms/XL=10/0.9947=10.05 A

- Calculando la corriente en L2 

Datos:

2.5 kHz = 2.5∙〖10〗^3 Hz

20 µH= 20∙〖10〗^(-6) H

X_L=2πfL=2π(2.5∙〖10〗^3 )(20∙〖10〗^(-6) )=0.3141 Ω

I_rms=Vrms/XL=2.1/0.3141=6.68 A

- Calculando la corriente en L3

Datos:

2.5 kHz = 2.5∙〖10〗^3 Hz

40 µH= 40∙〖10〗^(-6) H

X_L=2πfL=2π(2.5∙〖10〗^3 )(40∙〖10〗^(-6) )=0.6283 Ω

I_rms=Vrms/XL=2.1/0.6283=3.34 A

34. En la figura 13-51, determine la potencia reactiva.

![image](https://user-images.githubusercontent.com/105684550/185234747-d2c00967-5a3b-4e5a-928c-28901380fd1c.png)

Hallar la reactancia inductiva y los valores de corriente

L_2eq=((L_2*L_3)/(L_2+L_3 ))=13.33 µH

L_T=L_1+L_2eq=50+13.33=63.33 µH

X_L=2πF_L=2π(2.5*〖10〗^3 Hz)(0.01mH)=50π=157.08 Ω

I=V_S/X_L =(10 V)/(157.08 Ω)=63.6 mA
 
X_L=〖I^2*X〗_L=(63.6 mA)^2*(157.08 Ω)=0.6353 VAR

                                                                14.- TRANSFORMADORES
                                                                
2. Determine el coeficiente de acoplamiento cuando LM = 1 µH, L1 = 8 µH, y L2 = 2 µH.

L_M=k*√(L_1*L_2 )

L_M/√(L_1*L_2 )=k

(1µH)/√(8µH*2µH)=k

k=(1µH)/(4µH)=0.25

4. Cierto transformador tiene 250 vueltas en su devanado primario. Para duplicar el voltaje, ¿cuántas vueltas debe haber en el devanado secundario?

n=N_sec/N_pri 

N_pri*n=N_sec

N_sec=250*2=500 vueltas

6. Para elevar 240 V de ca a 720 V, ¿cuál debe ser la relación de vueltas?

V_sec=n*V_pri

n=V_sec/V_pri 

n=(720 V)/(240 V)=3 vueltas

8. ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 10 para obtener un voltaje secundario de 60 V de ca?

V_sec=n*V_pri

V_sec/n=V_pri

V_pri=(60 V)/10=6 V

10. El devanado primario de un transformador tiene 1200 V a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 0.2?

V_sec=n*V_pri

V_sec=0.2*1200 V

V_sec=240 V

12. ¿Cuál es el voltaje a través de la carga en cada uno de los circuitos de la figura 14-43?


V_sec=n*V_pri

V_sec=0.05*120 V

V_sec=6 V

![image](https://user-images.githubusercontent.com/105684550/185235216-6bb2a666-2504-44b2-b7d0-8392f8a0e33f.png)

V_sec=n*V_pri

V_sec=2*12 V

V_sec=24 V

Carga del devanado secundario

14. Determine Is en la figura 14-45. ¿Cuál es el valor de RL?

![image](https://user-images.githubusercontent.com/105684550/185235254-eee673a7-5e38-4c31-b6f0-c78ade58c9a7.png)

I_sec=(1/n)*I_pri

I_sec=(1/3)*100 mA=33 mA

R_pri=V_pri/I_pri 

R_pri=20V/(0.1 A)=200Ω

R_pri=(1/n)^2*R_L

R_L=R_pri/(1/n)^2 

R_L=(200 Ω)/(1/n)^2 =1800 Ω

16. ¿Cuál es la resistencia en la carga vista por la fuente en la figura 14-47?

![image](https://user-images.githubusercontent.com/105684550/185235872-e7731829-8b7a-4ddb-aff0-10140eb5b94c.png)

Rpri=〖(1/n)〗^2 Rl=(1/5)^2 (680)=27.2Ω

18. En el circuito de la figura 14-49, encuentre la relación de vueltas requerida para suministrar potencia máxima al altavoz de 4 Ω

![image](https://user-images.githubusercontent.com/105684550/185235932-1befa3f0-00ef-4445-8606-569568df3765.png)

n=√(RL/Rpri)=√(4Ω/16Ω)=0.5

22. ¿Cuál es la eficiencia del transformador en el problema 21?

Datos 

Pentrada = 100W

Psalidad = 94.5W

n=(Psal/Pent)100%

n=(100W/94.5W)100%=94.5%

24. La potencia nominal de cierto transformador es de 1 kVA. El transformador opera a 60 Hz y 120 V de ca. El voltaje secundario es de 600 V.

- a) ¿Cuál es la corriente máxima en la carga?

ILi1=Psec/Vsec=5kVA/120=0.042kA=42 A

ILi2=Psec/Vsec=5kVA/600=0.008kA=8 A

La corriente máxima en la carga es de 42A

- b) ¿Cuál es el valor RL más pequeño que puede ser excitado?

Il1= 42A

V=120

Rli1=V/IL=120/42=2.86 Ω

Il2=8A

V=600V

Rli2=V/IL=600/8=72.03 Ω

El valor de RL mas pequeño es de 2.86 Ω

26. La potencia nominal de cierto transformador es de 5 kVA, 2400/120 V, a 60 Hz.

- a) ¿Cuál es la relación de vueltas si los 120 V son el voltaje secundario?

Vsec=nVpri

n=Vsec/Vpri=120V/2400V = 0.05

- b) ¿Cuál es la corriente nominal del secundario si los 2400 V son el voltaje primario?

I=Psec/Vsec

I=5kVA/2400V=0.002kA=2A

28. Con los voltajes indicados en la figura 14-52, determine la relación de vueltas de cada sección de toma del devanado secundario al devanado primario

![image](https://user-images.githubusercontent.com/105684550/185236137-0ae060c1-e386-4c56-8775-9b98f5077755.png)

Vsec=nVpri

n1=V1/Vpri=24V/12V=2

n3=V1/Vpri=6V/12V=0.5

n3=V1/Vpri=3V/12V=0.25

30. En la figura 14-54, cada primario puede acomodar 120 V de ca. ¿Cómo se deberán conectar los primarios
para que operen con 240 V de ca? Determine cada voltaje secundario para operación con 240 V

![image](https://user-images.githubusercontent.com/105684550/185236170-ec029558-d743-4a36-bbaf-6cd0a2628144.png)

Vsec=nVpri

Vsec=(0.1)(240)=24V

Vsec=(0.2)(240)=48V

Vsec=(0.5)(240)=120V

Vsec=(1)(240)=240V

5.- Video

6.- Conclusiones

- Los inductores o bobinas son recursos lineales y pasivos que tienen la posibilidad de guardar y liberar energía basándose en fenómenos involucrados con campos magnéticos. Una aplicación de los inductores, consistente en bloquear las señales de AC de alta frecuencia en circuitos de radio, dio origen a que con dicho término se realice alusión a los inductores que se emplean en aplicaciones donde su costo no es crítico y que por consiguiente aceptan monumentales tolerancias. 

- La diferencia primordial que hay entre el transformador ideal y erreal, es que en el transformador ideal no se piensan ningún tipo de perdidas, y en el transformador real se piensan las pérdidas, como las de dispersión, las de las bobinas (cobre) y las del núcleo. teniendo presente que El transformador, es un dispositio que no posee piezas móviles, el cual transfiérela energía eléctrica de un circuito a otro bajo el inicio de inducción electromagnética. La transferencia de energía la hace en la mayoría de los casos con cambios en los valores de voltajes y corrientes lo que nos sugiere si el transformador. 

- Con los transformadores se han podido solucionar una gigantesca proporción de inconvenientes eléctricos, en los que si no fuera por dichos, seria imposible solucionar. Debido a los transformadores el reparto de energía eléctrica se a podido utilizar y repartir a las diversas metrópolis de todo el mundo, a partir de las plantas generadoras de electricidad, independientemente de la generadora. 

7.- Bibliografía

Floyd, T. (2007). Principios de circuitos eléctricos (Octava ed.). PEARSON EDUCACIÓN.
