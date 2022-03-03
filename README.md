# Portafolio de Programación
Este portafolio fue creado con la finalidad de introducir a nuevos usuarios que quieren empezar a leer el lenguaje de programación python, empezando por el concepo de python, que son las variables y así mismo ejemplos de cada uno para una mayor comprensión del portafolio.

# ¿Qué es Python?
Python es un lenguaje de programación de alto nivel y sencillo de comprender debido a que no es tan complejo, este lenguaje de programación es de codigo abierto,
gratuito y es un lenguaje de programación interpretado(quiere decir que el codigo programado es traducido mediante un intérprete conforme sea necesario), también permite a programadores crear softwares sin límite alguno debido sus amplias posibilidades. Sabiendo esto procederemos a estudiar lo que es una variable.

# ¿Qué es una variable?
El concepto de variable depende de cada lenguaje de programación, en este caso tomaremos "variable" como una "caja", en la cual puede estar almacenado un valor o bien agregarle un valor, para la creación de variables es necesaria una asignación de un valor a esta, para llevar a cabo la asignación se usará el operador "=", esta asignacion le dice al programa que almacene lo que esté de lado derecho de la variable para luego almacenarlo, para la creacion de las variables deberemos colocar la variable del lado izquierdo, después la asignación "=", y por último el valor que le daremos a nuestra variable. Debemos tener en cuenta que al ser una variable, no siempre se mantendrá en un mismo valor, ya que puede variar conforme se vaya ejecuando el algoritmo. 

Correcta asignación de una variable:
```python
a = 5
```
```python
b = 8
```
Incorrecta asignación de una variable:
```python
5 = a
```
```python
8 = b
```
## Nombrando una variable
Para nombrar una variable debemos tener en cuenta el colocar un nombre que se relacione con el dato que representará, por ejemplo:
```python
marca_laptop = 'lenovo'
```
En el ejemplo anterior podemos observar como creé una variable la cual le asigné el nombre "marca_laptop", (ten en cuenta que no puedes colocar espacios y para evitar problemas, tratemos de escribir todo con minúscula, si no quieres escribir todo unido, puedes separar las palabras con un " _ ", es necesario que sea un guión bajo) y contiene la marca de una laptop, después coloqué el operador de asignación " = ", y por último escribí la marca de una laptop en este caso "lenovo", que viene a ser lo que nuestra variable está almacenando, una vez comprendido el como nombrar una variable, podemos seguir con la asignación de valores a una variable.

Ejemplo Extra:
```python
marca_celular = 'Huawei'
```
## Asignando valores a una variable
En este apartado aprenderemos a asignar un valor o dato a una variable, los valores o datos es lo que nuestra variable anteriormente creada almacenará dentro, para esto debemos tener pensado si nuestra variable almacenará un valor numérico o un valor , a continuación se le mostrará un ejemplo de  como asignar a nuestra variable un valor y un dato.

Asignando un valor numérico a nuestra variable:
```python
valor_numerico = 5
```
Como puedes observar, el valor colocado no lleva las comillas que llevaban los anteriores ejemplos, esto se debe a que al no llevar comillas, python lo podrá reconocer automáicamente como valor numérico, por lo que si al valor 5 le asignamos las comillas, python lo interpretará como texto.

Asignando una variable de texto:
```python
nombre_comida = 'hamburguesa'
```
En este otro ejemplo, volvemos a ver las comillas, guiándonos por la anterior explicación, podemos deducir que la palabra hamburguesa es un texto debido a que tiene comillas, cuando colocamos comillas, ya sean simples o dobles, python interpretara nuestro dato colocado como texto y lo imprimirá en pantalla.

## Operadores básicos
Entre los operadores básicos en python encontramos el operador + (suma), - (resta), * (multiplicación), / (División), y % (Módulo). Para definir el orden en los que se llevará a cabo cada operación podemos hacer uso de los paréntesis (). Por ejemplo:
```python
print((2+4)*6)
```
Lo que pasará luego de ejecutar el programa será lo siguiente, la primera operación que se realizará primero será la que se encuentre dentro del paréntesis, en este caso 2+4, el resulado de esta operación se multiplicará por 6 y el resultado final se imprimirá en pantalla.

### Suma
El operador lógico suma funciona igual que la suma en las matemáticas que conocemos de toda la vida, suma los dos numeros colocados por el programador o usuario, para poder llevar a cabo este operador en python solo necesitamos escribir lo siguiente:
```python
resultado = 4 + 8
print(resultado)
```
Como pudimos observar en el ejemplo llevado a cabo, creé una variable que dentro contenga una operación, en este caso una suma entre el número 4 y el número 8, posteriormente escribí print y dentro coloqué el nombre de la variable que en este caso es "resultado", lo que pasará a continuación es que se imprimirá el resultado de la operación 4+8, es decir, se imprimirá en pantalla el número 12.

### Resta
El operador lógico resta en cuanto a como aplicar y como funciona, es igual a la suma, a diferencia de que en lugar de sumar los números asignados, los restará y dará el resultado al usuario, a continuación un ejemplo de como aplicarlo en python:
```python
resultado = 10 - 5
print(resultado)
```
En este ejemplo ocurrirá lo que ocurrió con el operador suma, se realizará la operación correspondiente restando 10-5, dando como resultado el número 5 e imprimiendolo en pantalla. 

### Multiplicación
Este operador lógico en programación se lo representa de la siguiente forma: * , ya que es el símbolo que usa el intérprete de python para referirnos que la operación que se llevará a cabo será una multiplicación, en cuanto a como aplicarlo no se diferencia a la suma y a la resta, a continuación se le presentará un ejemplo:
```python
resultado = 2 * 4
print(resultado)
```
Al igual que los anteriores ejemplos, el programa multiplicará 2 por 4, guardando el resultado en la variable "resultado" y mostrando en pantalla el resultado, el cual es el número 8.

### División
En caso del operador división, no se usará el signo ya conocido %, ya que en python no le pertenece a la división, por lo tanto, el signo que usaremos en lugar del ya conocido, se usará el slash /, el cual indica que la operación que se llevará a continuación es una división, realizando el mismo proceso que con los anteriores operadores.

Ejemplo del Operador División:
```python
resultado = 26 / 2
print(resultado)
```
En el ejemplo observado se llevará a cabo la división entre el numero 26 y el número 2, la cuál se lleva a cabo y una vez obtenido el resultado, en este caso el número 13, se lo imprimirá en pantalla.

### Módulo
El módulo es una operación aritmética en la que se divide un valor por otro, y el residuo se devuelve. El simbolo usado para este operador es el % (en Python este simbolo se usa para obtener el módulo de una operación), la aplicación de la operación es igual de simple que el de los anteriores operadores. Veamos un ejemplo:
```python
resultado = 7 % 2
print(resultado)
```
En este ejemplo se llevará a cabo la operación, dando como resultado el número 1, debido a que dos entre siete es igual a 3 veces 2, que da igual a 6 y faltando 1 para llegar a 7, siendo 1 el resultado y mostrándolo en pantalla.

# Tipos de datos en Python
Existen diversos tipos de datos en python, estos datos son representados por sus palabras reservadas, cuentan con diferentes características y clasificaciones, entre estos tipos de datos tenemos: 
Integer(enteros)

float (flotantes)

string (texto). 

## Integer
Los datos tipo integer se refiere a todo el conjunto de números enteros y en python se usan colocanto "int()", pero dado a que el conjunto es infinito, este se limita en python por la capacidad de memoria disponible, un número int o entero se crea a partir de un dato que esté represenado con un número entero, ya sea como resultado de una expresión o función.

Representacion de números enteros en python:
```python
a = int(4)
print(a)
```
En este ejemplo hacemos uso de int(), comando el cual da a conocer que el dato introducido o que se va a introducir es un número entero, una vez aclarado esto, damos a conocer que la variable a contiene un número entero, en este caso es el número 4, al momento de imprimir en pantalla la variable "a", se imprimirá el número 4.

## Float
La función float o flotante, permite representar un número positivo o negativo con decimales, es decir, con números reales, por lo que si creamos una variable que contenga dentro un valor decimal, su resultado será un número flotante(de tipo float).
Ejemplo de una variable con resultado de tipo flotante:
```python
resultado = 1.2 + 1.1
print(resultado)
```
Si ejecutamos el programa, el resultado de este ejercicio será 2.3, un número decimal, por lo cual vendría a ser un valor float o flotante, otra forma de saber qué tipo es nuestro número introducido o resultado puedes aplicar el siguiente comando:
```python
resultado = 1.2 + 1.1
print(resultado)
print(type(resultado))  #Se imprimirá <class 'float'>
```
En este otro ejemplo, el programa luego de imprimir el resultado en pantalla, debajo de este imprimirá el tipo de dato que és en el siguiente formato: <class 'float'>, que da a entender que el tipo de dato resultante es float o flotante.

## String
Los strings o cadenas, son datos compuestos por secuencias de caracteres (letras) que representan un texto. Las cadenas de texto son de tipo str(string) y se representan mediante pares de comillas simples o doblesm ya que no afectará al código. A continuación se mostrará un ejemplo de como usar un string en python.

Ejemplo de String en Python(comillas dobles):
```python
mi_nombre = "Me llamo Josue" 
print(minombre)             
```
Ejemplo de String en Python(comillas simples):
```python
minombre = 'Me llamo Josue'
print(minombre)             
```
## Casting en Python
El casting o cast en python, se trata en convertir un tipo de dato a otro, por ejemplo, convertir un dato string a int o un dato int a float.

Ejemplo de conversión (int a str):
```python
a = 5
a = str(a)
print(a)
print(type(a)) #resultado <class 'str'>
```
Ejemplo de conversión (str a int):
```python
a = 5
a = int(a)
print(a)
print(type(a)) #resultado <class 'int'>
```
Ejemplo de conversión (float a int):
```python
a = 5.5
a = int(a)
print(a)
print(type(a)) #resultado <class 'int'>
```
## List
La función list en python, nos permite crear listas las cuales podremos usarlas para enlistar datos que vayamos a usar posteriormente en el programa, estos pueden ser tanto cadenas de texto, como números, decimales y más. Para declarar los datos que se encontrarán dentro de nuestra lista no debemos usar paréntesis (), en este caso usaremos corchetes []  Es importante también evitar las comillas si el dato es un entero o decimal, y agregar comillas si el dato es una cadena de texto.

Otro dato de las listas es que si quieres que se imprima un elemento en específico de la lista puedes usar el número de ese elemento, para esto debes saber que los elementos se cuentan de izquierda a derecha y se empieza a contar desde el número 0, es decir: 0, 1, 2, 3... 

Para poder llevar a cabo la creación de una lista podemos guiarnos del siguiente ejemplo:
```python
lista_ejemplo = ['pan', 'arroz', 'platano', 50, 1.5]
print(lista_ejemplo[0]) #imprimirá pan
```
También se encuentran las listas anidadas, es decir, listas dentro de otras listas la cual también puede ser usada con total normalidad, por ejemplo:
```python
lista_ejemplo = ['pan', 'arroz', 'platano', ['comino', 'enlatado'], 50, 1.5]
print(lista_ejemplo[3]) #imprimirá ['comino', 'enlatado']
```
## Tuple
Las tuplas en python es un conjunto ordenado de elementos que se encuentran encerrados por paréntesis y separados por comas, casi como si fuera una lista, debemos tener en cuenta que una tupla no puede ser una tupla vacía(no tener ningún elemento dentro). 

Ejemplo de una tupla en python:
```python
mitupla = (5, 10, 25, 'aguacate')
print(mitupla) #imprimirá (5, 10, 25, 'aguacate')
```

## Dictionary
Un diccionario en python es un tipo de datos que nos permite almacenar datos de cualquier tipo ya sea cadenas, enteros, flotantes, incluso listas... Una característica que diferencia al diccionario con las listas y tuplas, es que podemos encontrar elementos mediante una clave (key) que almacenamos en nuestro diccionario. Un dato que debemos tener muy en cuenta a la hora de crear un diccionario, es que debemos almacenar nuestros datos en {} o llaves.

Ejemplo de la creación de un diccionario en Python:
```python
diccionario = {'Nombre': 'Josue', 'Edad': 18}
print(diccionario)
```
# Tomando decisiones
Las decisiones en python son importantes al momento de decidir si nuestro programa debe ejecutar una orden, solo si se cumple con alguna condición anterior, para lograr esto en python, hacemos uso de la sentencia if.

## Sentencia if
Esta sentencia condicional llamada if, es usada en python para tomar decisiones y funciona de la siguiente manera, el programa ejecutará una condición, luego verificará si esta condición se cumple, y solo si la condición puesta por el programa se cumple, imprimirá la orden determinada por el programador, caso contrario puede imprimirse otra orden y finalizar el programa o puede no pasar nada y finalizar el programa. 

A continuación mostraré un ejemplo del uso de la sentencia if en python:
```python
x = 5
if x == 1:
    print('El número', x, 'es igual a 1')  # Solo se imprimirá si la variable x es igual a 1.
print("")                                  # Si la variable x no es igual a 1, no imprimirá nada y finalizará el programa.
```
En ese ejemplo se muestra que la variable x contiene el valor 0, luego usé if para preguntar al programa si x(5) es igual a 1, si es así debe mostrar en pantalla: El número 5, es igual a 1. En caso de que no sea cierto, solo no imprimirá nada y terminará la ejecución del programa.

También tenemos la sentencia else, que indica al programa, que si la condición anterior no se cumplió, imprima una orden distinta y finalize el programa.
```python
x = 5
if x == 1:
    print('El número', x, 'es igual a 1')
else:
    print('El número', x, 'no es igual a 1')      #Este programa imprimirá: El número, 5, no es igual a 1
print("")
```
## Ciclo For
El ciclo for en python, es una estructura que repite una serie de instrucciones por un número determinado de veces, a esto es lo que denominamos un bucle, algo que se repite.
Podemos usar el ciclo for para repetir una secuencia de bloques hasta que la misma ya no sea válida, por ejemplo:
```python
for i in range(5):
    print(i)           #Imprimirá Repetición: 0
                       #          Repetición: 1
                       #          Repetición: 2
                       #          Repetición: 3
                       #          Repetición: 4
```
Para el ejemplo mostrado, hice uso de "range" para determinar el número de repeticiones que deseamos que se ejecuten, en mi caso coloqué 5 repeticiones, por lo que el programa imprimió 5 repeticiones y luego finalizó.(Recordemos que en python se empieza a contar desde el número 0).
## Ciclo While

## Break

## Continue
