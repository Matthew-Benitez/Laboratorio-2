# Laboratorio 2
  1. OBJETIVOS
- Objetivo General:
   
   - Aplicar el método de corrientes de malla y aplicarlo para analizar un circuito y comprobar que el método es efectivo y eficiente.
   
- Objetivos Específicos:
 
   - Analizar cada malla dispuesta en el circuito y determinar su respectiva corriente.
   - Determinar las diferencias entre los cálculos medidos y los cálculos simulados y observar sus características.
   - Observar si el método de mallas ayuda a determinar todas las corrientes sin errores potenciales.
   
2. MARCO TEÓRICO


![image](https://user-images.githubusercontent.com/75439689/103955604-ae46bf80-5114-11eb-940b-6ff920c44f82.png)
![image](https://user-images.githubusercontent.com/75439689/103955621-ba328180-5114-11eb-9d16-f15a2c87dd47.png)
3. DIAGRAMAS

    - Modelo del Circuito
    
  ![image](https://user-images.githubusercontent.com/75439689/103944208-4b97f880-5101-11eb-8e16-335b629c4c3f.png)
  
  *Figura 3.1*
  
   - Circuito Simulado
   
   ![image](https://user-images.githubusercontent.com/75439689/103955337-0b8e4100-5114-11eb-803b-6bb66d8d6550.png)
   
   *Figura 3.2*

   - Corriente de la Malla 1
   
   ![image](https://user-images.githubusercontent.com/75439689/103947720-8e100400-5106-11eb-968c-7599f97e5ac0.png)
   
   *Figura 3.3*
   
   - Corriente de la Malla 2
   
   ![image](https://user-images.githubusercontent.com/75439689/103947853-c6afdd80-5106-11eb-8192-5bb3f1ab2ecf.png)
   
   *Figrua 3.4*
   
   - Corriente de la Malla 3
   
   ![image](https://user-images.githubusercontent.com/75439689/103947906-d92a1700-5106-11eb-963e-a9e451553322.png)
   
   *Figura 3.5*

4. LISTA DE COMPONENTES

![image](https://user-images.githubusercontent.com/75439689/103948156-52296e80-5107-11eb-96e9-2984d64dbf5a.png)

*Tabla 4.1*

5. EXPLICACIÓN

   5.1. Procedimiento

     - Ingresar a la plataforma *Tinkercad* y crear un nuevo circuito, en el cual se escogen los componentes listados anteriormente.
     - Conectar el primer suministro de energía de 18 voltios a un extremo de la placa de pruebas (*protoboard*) uniendo respectivamente los polos positivos y negativos deL suministro y la placa; y de la misma manera, se conecta la otra fuente de voltaje de 5 voltios pero al otro extremo de la placa.
     - A continuación se conecta en escalera las cinco resistencias, generándose así un circuito de tres mallas.
     - Para finalizar la creación del circuito planteado, se conecta los suministros de energía a cada lado del circuito en escalera con sus respectivas terminales (la fuente de 18 voltios se conecta en serie con la primera malla y la fuente de 5 voltios con la tercera malla).
     
   5.2. Mida cada una de las corrientes de malla y anote los resultados en la *tabla 5.2.1.*
   
     Una vez realizado el circuito se procede a calcular las corrientes de cada malla por el método de corrientes de malla.
     
     Para la obtención de los resultados primero se determinaron las mallas existentes en el circuito, posteriormente, se basó en dos partes, los resultados analíticos, los cuales son hechos a mano, y los resultados experimentales, los cuales son tomados por parte del simulador con herramientas digitales (amperímetro). Obteniendo así los resultados descritos en la *tabla 5.2.1.*
     
     ![image](https://user-images.githubusercontent.com/75439689/103953561-5908af00-5110-11eb-9d0a-9dc6423a81a1.png)
     
     *Tabla 5.2.1.*
     
   5.3. Comparación de los valores de la *tabla 5.2.1.* y realice conclusiones.
   
   Los resultados obtenidos en la tabla fueron recogidos de manera analítica y experimental, y se pudo observar que estas corrientes de malla no difieren exponencialmente una de otra, más bien sus resultados son idénticos si es que se utiliza el método de redondeo. 
   
   Sin embargo, resalta en la tabla, en la parte de resultados analíticos, que estos datos tienen más cifras significativas que la parte de resultados experimentados, por lo que, como resolución, los resultados analíticos son más acertados que los que son parte de los simulados.
   
   Para finalizar, los datos fueron comparados mediante los cálculos de errores que se muestran a continuación. Y se denota que el error más grande es por parte del resultado experimental de la Malla 1.
   
   -	Porcentajes de Errores de la *tabla 5.2.1*
   
   ![image](https://user-images.githubusercontent.com/75439689/103953733-aab13980-5110-11eb-91d6-90325bb4764e.png)

     
6. CONCLUSIONES

7. BIBLIOGRAFÍA


