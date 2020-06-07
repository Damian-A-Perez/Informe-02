# Informe-02
TEMA: PRACTICA  No. 2  ANALISIS DE MALLAS
ESTUDIANTES: MENESES JARRIN SANTIAGO JAVIER OSEJO CUESTA BRANDON DILLAN PEREZ CEDILLO DAMIAN ALEXANDER

DOCENTE: DARWIN OMAR ALULEMA FLORES

NRC: 8703

En esta practica demostraremos el funcionamiento  del análisis de mallas en un circuito resistivo basico . Usando herramientas de simulacion digital, determinaremos la certeridad de los valores previamente calculados usando las leyes de kirchhoff de corrientes como una de las bases importantes para demostrar el analsis en cada malla.

1 °  Plantamiento del problema

Determinaremos el valor de corriente en cada malla y en cada resistencia, tomando en cuenta que debe cumplirse la igualdad a cero en cada malla, asegurandonos de tener la misma cantidad de ecuaciones que de mallas para poder estableces un sistema y encontrar el valor  exacto de la corriente que atraviesa cada tramo del circuito

2 ° Ojetivo de la practica 

Comprobar experimentalmente el Análisis de Mallas. 

2.1 Objetivos especificos 

2.1.1:


3° Marco Teorico 

METODO DE CORRIENTES DE MALLAS

Es una técnica bien organizada para resolver circuitos y determinar la corriente de cualquier elemento dentro de un circuito plano . Dicha técnica esta basada en la ley de corrientes de kirchhoff, la ventaja de utilizar esta técnica es que facilita el análisis y produce un numero pequeño de ecuaciones a resolver.  Dicho sistema de ecuaciones a resolver es un sistema de 2E donde E es el numero de elementos dentro del circuito .

En un circuito electrico una malla es cualquier camino cerrado alrededor de un circuito. Para formarlo de manera correcta debes partir del terminal de un componente y trazar una linea que conecte el resto de los elementos  hasta llegar de regreso al punto de partida. Dentro de una malla o lazo, el camino solo puede dirigirse por un elemento una sola vez, de modo que el camino no se respita o en algún caso evitar que se forme un numero 8 con los elementos conectados. 

Existe una pequeña diferencia entre las definiciones de lazo y malla, debido a que  una malla es es un lazo que no contiene otros lazos o mallas, en cambio un lazo si puede contener una malla o más 

! [EJEMPLO DE MALLAS](https://github.com/Damian-A-Perez/Informe-02/blob/master/img/1e11477a94abdb9c8b8768f103cdb598fe9b5583.png)

| MALLA    | RESULTADOS ANALITICOS | RESULTADOS EXPERIMENTALES | RESULTADOS SIMULADOS |
|  :---:   |  :---:                |            :---:          |       :---:          |
|    M1    | 11.455[mA]                |11.5[mA]                   | 11.455[mA]           |
|    M2    | 2.847[mA]                |2.85[mA]                   |2.847[mA]             |
|    M3    | 0.488[mA]                |0.488[mA]                  |488.122[uA]           |
