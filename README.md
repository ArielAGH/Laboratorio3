# Laboratorio 3: Teorema de superposición
**Integrantes:** Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Comprobar y analizar el teorema de Superposición

### Objetivos específicos
* 
* 

## Marco teórico
En un circuito eléctrico podemos tener varias fuentes de corriente y voltaje que podrían complicar nuestro análisis en ese circuito. Por esta razón utilizamos el teorema de superposición. 

Este teorema consiste en trabajar individualmente con cada una de las fuentes de corriente o voltaje independientes. Si se trabaja con fuentes de voltaje se debe poner en corto el resto de las fuentes, en cambio, si se trabaja con fuentes de corriente, el resto de las fuentes debe ser un circuito abierto. La finalidad de hacer estos cambios es la de simplificar el diagrama del circuito, luego se obtienen valores de voltaje y corriente en cada elemento correspondientes a cada caso donde la fuente es tratada individualmente. 

Al final de este proceso se debe realizar una suma algebraica de todos los valores de cada elemento obtenidos individualmente y así encontrar el valor real de estos elementos cuando se trabaja con todas las fuentes a la vez. 

Si el circuito cuenta con fuentes dependientes de voltaje o corriente no se las deberá hacer nada, ya que su magnitud depende de otra. Así pues, dependiendo el circuito se determinará si es factible aplicar este teorema ya que se busca simplificar al circuito y no alargar cálculos.

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/definicion_superposicion.jpg)

También podemos decir que el principio de superposición es otro nombre para la propiedad aditiva de la linealidad, lo que se representa como:

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/formula_linealidad.png)

El principio de superposición se define usando notación funcional, así podemos decir que los circuitos se pueden representar como funciones (leyes de Ohm y de Kirchhoff).

Para aplicar la superposición necesitamos aplicar las entradas una a la vez. Esto significa que tenemos que apagar todas las entradas excepto una. Cuando apagamos una entrada decimos que está suprimida.

Apagar una fuente de voltaje signidica que hacemos V = 0. Esto es lo mismo que reemplazar la fuente de voltaje o la batería con un cortocircuito.

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/corriente_cerrada.png)

Apagar una fuente de corriente significa que hacemos I = 0. Es lo mismo que reemplazar la fuente de corriente con un circuito abierto.

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/corriente_abierta.png)
