# Trabajo-de-investigacion-2

1. OBEJTIVOS

  * Objetivo General:
    
    - Aplicar los Teoremas de Circuitos y Conversiones para la comprensión y simplificación de circuitos de corriente alterna en serie-paralelo.
    
  * Objetivos Específicos:

    - Describir la relación entre corriente y voltaje en un circuito RC en serie-paralelo.
   
    - Determinar impedancia y admitancia en un circuito RC en paralelo.
   
    - Determinar la impedancia de un circuito RC en serie.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/76132461/108800660-c60dc200-7561-11eb-89bc-fe25d29368df.png)

![image](https://user-images.githubusercontent.com/76132461/108800472-3cf68b00-7561-11eb-8f6e-928fd3792c5a.png)

![image](https://user-images.githubusercontent.com/76132461/108800143-5814cb00-7560-11eb-9299-56123756069b.png)

![image](https://user-images.githubusercontent.com/76132461/108800005-f05e8000-755f-11eb-8368-db60b723e61f.png)


3. EJERCICIOS
4. LISTA DE COMPONENTES

  ![image](https://user-images.githubusercontent.com/76134214/108808757-4db0fc00-7575-11eb-8b19-602b6cb67d77.png)

5. EXPLICACION

 Los circuitos han sido simulados en ThinkerCAD y en Proteus con el fin de que la explicación sea un poco más visual.

Cómo podemos observar en este primer circuito es el ejercicio 24 en este nos pide que determinemos la impedancia expresada en forma rectangular para cada una de las frecuencias ya que nuestra fuente de voltaje de corriente alterna no variar entre 100 500 1000 y 2500 Hz, también nos indica que nuestra nueva capacitancia será de 0.0047 microfaradios. En este circuito aplicamos reactancia de la forma Xc con la fórmula X_c=1/2π(Frecuencia)(Capacitancia) =ΚΩ de la cual obtendremos un valor en KOhms. Luego determinamos la impedancia representada por la letra Z la cual utiliza como fórmula de forma rectangular Z=Resistor-J(Reactancia), al reemplazar los valores tendremos nuestro primer resultado. Ahora se reemplazó en la fórmula de reactancia las siguientes 4 frecuencias.

Nuestro siguiente circuito a resolver será en paralelo, en este circuito para encontrar la magnitud de cada corriente de rama y corriente total se aplicó  las fórmulas de reactancia e impedancia, de igual manera debido a que nos demanda un valor de corriente total aplicamos también ley de ohm para sacar la resistencia equivalente en el circuito. Cabe resaltar que en la fórmula de reactancia a nuestro valor del capacitador debemos multiplicarlo por 10 a la -6 (X_c=1/2π(Frecuencia)(Capacitancia)(10^-6)) ya que nos brinda la unidad de microfaradios. Contino a esto debemos aplicar nuestra fórmula de impedancia de forma polar (Z=((R.Equivalente) +(Reactancia total) )/√((R.Equivalente)^2+(Reactancia total)^2 )<-tan^(-1)⁡(231,49ΚΩ/147ΚΩ)) ya que en nuestro ejercicio nos está pidiendo el ángulo de fácil entre el voltaje aplicado y la corriente total. Nuestra corriente total va a tomar el valor de la división entre voltaje fuente y nuestra impedancia total brindándonos un valor en miliamperios. Luego de obtener este valor tendremos que ir por cada rama del circuito midiendo y calculando por ley de ohm o leyes de Kirchhoff, nuestras intensidades de corrientes individuales.

6. APORTES

TinkerCAD
![image](https://user-images.githubusercontent.com/76134214/108809102-227adc80-7576-11eb-8c9d-cf2e4b0a7287.png)

Proteus
![image](https://user-images.githubusercontent.com/76134214/108809109-2575cd00-7576-11eb-8535-b02bc0a7559c.png) 

TinkerCAD
![image](https://user-images.githubusercontent.com/76134214/108809123-29a1ea80-7576-11eb-8be9-f8b31b0191c7.png)

Proteus
![image](https://user-images.githubusercontent.com/76134214/108809129-2d357180-7576-11eb-9db0-1c4f3f11e77b.png)

7. CONCLUSIONES
 - En conclusión, la impedancia es un parámetro de gran importancia en la caracterización de circuitos y componentes electrónicos, tambien se debe tener en cuenta que la impedancia tiene una parte real y una parte imaginaria.
 - Los voltajes y las corrientes en un circuito RC en serie-paralelo, siguen las mismas leyes de la ley de ohm, con base en estas leyes se puede llegar a una solución en el caso que se presenten condensadores o resistencias.
 - Para concluir, en los calculos de las impedancias, se tienen que tener muy en claro las fórmulas y el despeje necesario que se debe hacer para poder resolver estos ejercicios.
 
8. BIBLIOGRAFIA

 Floyd, T.L. (2007). Principios de circuitos eléctricos (Octava ed.)


