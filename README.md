# Informe Proyecto 1

# 1. Objetivos

Identicar como funciona un circuito conectado con diferentes compotenentes que interactuan entre si al armar un circuito con caracteristicas especificas que realiza un funcion requerida y mediante la ingenieria inversa entender de mejor manera su funcionamiento 

# 2. Marco Teorico

El circuito armado tiene como finalidad mediante la deteccion de cantidad de luz en el ambiente encender leds que alumbraran o se apagaran por completo dependiendo de la situacion, esto de forma autmatica por el foto resistor incorporado, para que el circuito funcione correctamente se requieren de elementos especificos los cuales cumpliran una funcion en este circuito.

A continuacion se enumeran los componentes usados y la funcion que cumplen en este proyecto.

    1. Protoboard
  
Una placa de pruebas o placa de inserción es un tablero con orificios que se encuentran conectados eléctricamente entre sí de manera interna, habitualmente siguiendo patrones de líneas. En este caso, este elemento sera el fundamental ya que es donde se arma todo el circuito 
  
    2. Transistor
El transistor es un dispositivo electrónico semiconductor utilizado para entregar una señal de salida en respuesta a una señal de entrada.
En este caso, la señal de entrada sera dada por el foto resistor que se mencionara mas adelante, mediante la señal de entrada se producira la señal de salida la cual activara los leds conectados en serie a uno de sus canales.

    3. Resistencias
La resistencia es una medida de la oposición al flujo de corriente en un circuito eléctrico. La resistencia se mide en ohmios, que se simbolizan con la letra griega omega (Ω). En este caso las resistencias utilizadas se opondran al flujo del corriente suministrada por la fuente de voltaje haciendo que primero los leds no se fundan/quemen/dañen.
   
    4. Potenciometro
Es uno de los dos usos que posee la resistencia o resistor variable mecánica. El usuario al manipularlo, obtiene entre el terminal central y uno de los extremos una fracción de la diferencia de potencial total, se comporta como un divisor de tensión o divisor de voltaje. En el circuito armado este se comportara coo una gran resistencia que se impida al paso de corriente pero que podamos midificar cuanta corriente querramos que pase, lo que repercute directamenten en la intensidad de los leds, es decir en su luminosidad.
   
    5. Leds
Un diodo emisor de luz o led es una fuente de luz constituida por un material semiconductor dotado de dos terminales. Se trata de un diodo de unión p-n, que emite luz cuando está activado. En este caso el led tendra el papel de señal de alerta o de funcionamiento ya que dependiendo se si se enciende o no, sabremos si el circuito funciona correctamente.
   
    6. Foto resistor
    
Es un componente electrónico cuya resistencia se modifica, con el aumento de intensidad de luz incidente. Puede también ser llamado fotoconductor, célula fotoeléctrica o resistor dependiente de la luz, cuyas siglas, LDR, se originan de su nombre en inglés light-dependent resistor. En el caso del circuito este componente sera el encargado de enviar la señal del nivel de luz que existe en el entorno.
     
    7. Pila
Una pila eléctrica es el formato industrializado y comercial de la celda galvánica o voltaica. Es un dispositivo que convierte energía química en energía eléctrica por un proceso químico transitorio. Usamos una pila de 9v siendo la fuente de poder de todo el circuito.

# 3. Explicacion del Procedimiento

Componentes a usar

    1. Protoboard
    2. Reistencias: 10k ohm y 220 ohm
    3. Transistor 2n 3904
    4. Potenciometro de 100k
    5. Dos leds color amarillo
    6. Una fotoresistencia
    7. Cables de cobre

Comenzamos por tener en cuenta el diagrama del circuito.

![image](https://user-images.githubusercontent.com/116781677/204458896-773c51f7-cb8a-4e51-957a-16e9bce1b385.png)

Procedemos a seguir el circuito y armarlo en nuestra protoboard dandonos el siguiente resultado.

![WhatsApp Image 2022-11-29 at 01 52 07](https://user-images.githubusercontent.com/116781677/204459344-516a3d36-3805-49fa-8a4e-772fe5ad581b.jpg)

Verificamos su funcinamiento

    Con luz en el ambiente

![WhatsApp Image 2022-11-29 at 01 54 40](https://user-images.githubusercontent.com/116781677/204459792-29af2bc4-4ab7-4ecd-9aba-bf3182f21243.jpg)

    Sin luz en el ambiente
    
![WhatsApp Image 2022-11-29 at 01 54 40](https://user-images.githubusercontent.com/116781677/204459861-7bcb4a6d-a1b2-4617-bbad-7d179b63e5d9.jpg)

# 4. Video

# 5. Conclusiones

-El modelo de un led nocturno automatico resulta ser un total exito.

-Se aprecia correctamente el como actua la cantidad de corriente en un circuito cerrado.

-Se implemento componente mas complejos con funcionalidades especificas las cuales mediante el armado del circuito se aprecia de que manera funcionan.

-La complejidad del armado de este circuito es leve, no requiere de muchos componentes y el seguimiento del esquema asegura el funcionamiento del mismo.

# 6. Referencias

ELECLAM2018. (15 de Abril de 2020). Electronica Lam. Recuperado el Noviembre de 2022, de Componentes electrónicos: https://www.electronicalam.com/componentes-electronicos/

Electrónica, E. (s.f.). ELECTRÓNICA. Recuperado el Noviembre de 2022, de Guía de estudio 7: Mallas y Nodos: http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf

Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.). México: Pearson Educación. Recuperado el Noviembre de 2022


