# Laboratorio 3: Teorema de superposición
**Integrantes:** Caillamara Leonardo, González Ariel
## 1. OBJETIVOS

### Objetivo general:
* Comprobar y analizar el teorema de Superposición

### Objetivos específicos
* 
* 

## 2. MARCO TEÓRICO
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

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/circuito_cerrado.png)

Apagar una fuente de corriente significa que hacemos I = 0. Es lo mismo que reemplazar la fuente de corriente con un circuito abierto.

![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/circuito_abierto.png)

## 3. EQUIPOS Y MATERIALES

* **TinkerCad:** Programa online de simulación con capacidad de simular circuitos.
* **Protoboard:** Es una placa de pruebas en la que se pueden insertar elementos electrónicos y cables con los que se arman circuitos sin la necesidad de soldar ninguno de los componentes.
* **Resistencias eléctricas:** Elemento eléctrico que se opone al paso de corriente.
* **Cables puente:** Cables de ayuda para realizar conexiones provisionales.
* **Multímetro:** Es un instrumento analógico o digital portátil que se usa para medir directamente magnitudes eléctricas.
* **Batería o fuente energética:** Dispositivo que provee energía a un circuito al cual es conectada.

## 4. PROCEDIMIENTO
* Entramos a la página de Tinkercad y creamos un nuevo circuito.
* Utilizando las distintas herramientas de dicho simulador representamos el circuito de la figura.
![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/Captura%20de%20pantalla%20(35).png)
* Conectamos los multímetros necesarios en dicho circuito damos Iniciar la simulación, tomamos datos y llenamos las tablas respectivas.
* Tanto para cálculos como para la simulación se debe determinar VA cuando todas las fuentes están activas, cuando v1=0 y cuando v2=0.
* Hacer lo mismo que en el punto anterior pero esta vez se mide Ix.
* Tomar las medidas necesarias y realizar los cálculos pertinentes.

## 5. TABLAS DE MEDICIÓN Y CÁLCULOS
### Tabla 5.1 Medición de voltaje aplicando superposición.
![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/calculo_voltajes.png)

### Tabla 5.2 Medición de corriente aplicando superposición.
![](https://github.com/ArielAGH/Laboratorio3/blob/main/Img/calculo_corrientes.png)

Los cálculos respectivos están en la carpeta denominada Cálculos y para el cálculo del error en cada malla se usa la siguiente fórmula para los tres casos.

![](https://github.com/KevinCaillamara/Laboratorio_2/blob/main/Im%C3%A1genes/formula_error.png)

## 6. ANÁLISIS DE RESULTADOS
Después de realizar los cálculos del Voltaje VA, tanto de forma analítica como por medio del simulador, podemos observar que los datos son muy similares y, por lo tanto, el error es mínimo. Sucede lo mismo con los valores de VA cuando V2=0 y cuando V1=0. Los errores son cercanos a cero y, por consiguiente, podemos tomar en cuenta la confiabilidad que nos ofrece el teorema de superposición de circuitos.

Por otra parte, los resultados calculados y simulados de la corriente Ix también fueron tomados y tabulados y, al igual que con el voltaje, los datos son bastante similares, lo que nos otorga valores de error cercanos a cero. Cuando V2=0 el valor del error es del 0% puesto que no tenemos corriente Ix al haber cambiado el circuito.

## 7. CONCLUSIONES

## 8. BIBLIOGRAFÍA
* Durán, J. (2012). *Electrotecnia*. Barcelona: Editorial Lexus.
* Fraile, J. (2012). *Circuitos eléctricos*. Madrid: Editorial Pearson.
* Maldonado, A. (2016). *Tecnología eléctrica*. Quito: Poli Ediciones.
* Sadiku, M. (2006). *Fundamentos de circuitos eléctricos*. México: Editorial Mc Graw Hill.
* Thomas, L. (2007). *Principios de circuitos eléctricos*. México: Editorial Pearson.
