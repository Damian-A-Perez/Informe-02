# Informe-02
TEMA: PRACTICA  No. 2  ANALISIS DE MALLAS
ESTUDIANTES: MENESES JARRIN SANTIAGO JAVIER OSEJO CUESTA BRANDON DILLAN PEREZ CEDILLO DAMIAN ALEXANDER

DOCENTE: DARWIN OMAR ALULEMA FLORES

NRC: 8703

En esta practica demostraremos el funcionamiento  del análisis de mallas en un circuito resistivo basico . Usando herramientas de simulacion digital, determinaremos la certeridad de los valores previamente calculados usando las leyes de kirchhoff de corrientes como una de las bases importantes para demostrar el analsis en cada malla.

1 °  Plantamiento del problema

Determinaremos el valor de corriente en cada malla y en cada resistencia, tomando en cuenta que debe cumplirse la igualdad a cero en cada malla, asegurandonos de tener la misma cantidad de ecuaciones que de mallas para poder estableces un sistema y encontrar el valor  exacto de la corriente que atraviesa cada tramo del circuito.

2 ° Ojetivo de la practica 

Comprobar experimentalmente el Análisis de Mallas. 

2.1 Objetivos especificos 

2.1.1: Entender como actua la corriente mediante el metodo de mallas.
2.1.2: Aclarar la forma de usar los instrumentos de medicion.
2.1.3: Identificar las trayectorias de la corriente.
2.1.4: Recordar la ley de voltajes de Kirchhoff para el entendimiento del metodo de mallas.


3° Marco Teorico 

METODO DE CORRIENTES DE MALLAS

Es una técnica bien organizada para resolver circuitos y determinar la corriente de cualquier elemento dentro de un circuito plano . Dicha técnica esta basada en la ley de voltajes  de kirchhoff, la ventaja de utilizar esta técnica es que facilita el análisis y produce un numero pequeño de ecuaciones a resolver.  Dicho sistema de ecuaciones a resolver es un sistema de 2E donde E es el numero de elementos dentro del circuito.

En un circuito electrico una malla es cualquier camino cerrado alrededor de un circuito. Para formarlo de manera correcta debes partir del terminal de un componente y trazar una linea que conecte el resto de los elementos  hasta llegar de regreso al punto de partida. Dentro de una malla o lazo, el camino solo puede dirigirse por un elemento una sola vez, de modo que el camino no se respita o en algún caso evitar que se forme un numero 8 con los elementos conectados. 

Existe una pequeña diferencia entre las definiciones de lazo y malla, debido a que  una malla es es un lazo que no contiene otros lazos o mallas, en cambio un lazo si puede contener una malla o más 

![Ejemplo mallas](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/Mallas%20de%20un%20circuito.png)

En el circuito se puede ver como existen 3 mallas por separado, pero podemos tomar un lazo que contenga a las 3 y recorra todo el circuito

La dirección de las corrientes por cada malla son dependientes de una fuente de corriente y de su polaridad, por lo general su dirección va en sentido de positivo a negativo, es decir, en sentido horario, en casos de existir dos fuentes o mas dentro del mismo circuito, la direcccion de la corriente varia en movimento antihorario en la malla en que se encuentre la otra fuente de poder, para cumplir con el sentido de la dirrecion de positivo a negativo, pero existen momento en que al analizar circuitos como este con ambas corrientes en sentidos contrarios, que el valor encontrado suele dar negativo, eso nos da a entender que la dirrecion de la corriente real, sera contraria a la pre-estimada

Para encontrar las ecuaciones a utilizar, se usa la ley de voltajes de kirchhoff, la cual nos dice que la sumatoria de voltajes dentro de una malla o lazo, debe ser igual a cero, usando el principio base de la ley de omh, reemplazamos y obtendremos ecuaciones en funcion de la variable I(corriente o intensidad).

4° Material y Equipo Requerido

![Tabla Material Necesario](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/Material%20y%20Equipo.png)

5° Procedimiento 
  
  IMPLEMENTE EL CIRCUITO QUE SE PRESENTA A CONTINUACION
  
![Circuito](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/Circuito%20analisis%20de%20mallas.png)

Mida cada una de las corrientes de la malla, y anotelas a continuacion 

| MALLA    | RESULTADOS ANALITICOS | RESULTADOS EXPERIMENTALES | RESULTADOS SIMULADOS |
|  :---:   |  :---:                |            :---:          |       :---:          |
|    M1    | 11.455[mA]                |-                   | 11.455[mA]           |
|    M2    | 2.847[mA]                |-                 |2.847[mA]             |
|    M3    | 0.488[mA]                |-               |488.122[uA]           |

![simulacion](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/Simulador(2).png)

6 Explicación del codigo fuente 

Para un buen montado del circuito dentro del simulador debemos tomar primero la fuente de voltaje con los datos correctos a proporcionar al circuito, tomar el protoboar y realizar una conexión directa con los polos negativos y positivos de la fuente de poder, realizar un puente de un extremo del protoboarda al otro para asegurar que la corriente  pase por todos los tramos de la plataforma y poder utilizar mas espacio de trabajo, tener en cuenta que cada nodo de conexíon dentro del protoboard, se representa como una linea vertical de espacios para poder conectar los elementos en el nodo respectivo. El circuito requiere dos fuentes de poder, una de 18(v) y otra de 5 (V) al extremo contrario, para ello tomaremos ambas fuentes y conectaremos el tierra en la misma linea de conexión para despues trasladarla al extremo contrario del protoboard, asi tendremos ambas corrientes  circulando por el circuito luego de eso procededemos a conectar los elementos uno a uno simulando el circuito proporcionado anterior mente, tomando en cuenta que la primera resistencia ira conectad al positivo de la primera fuente y la ultima resistencia ire conectada al positivo de la segunda fuente de poder.


7° CONCLUSIONES

7.1: Las mediciones de amperaje realizadas, concuerdan con los calculos del metodo de mallas, siendo que la implementacion del circuito es la correcta, asi como la utilizacion de los instrumentos de medicion.

7.2: Reconocemos el metodo de malla como una herramienta para encontar corrientes.


8° Cronograma

![timeline](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/L2I2.png)
