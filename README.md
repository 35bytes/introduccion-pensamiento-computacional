<div align="center">
  <h1>Introducción al Pensamiento Computacional con Python</h1>
</div>

<div align="center"> 
  <img src="readme_img/python.png" width="250">
</div>

# Tabla de contenido
- [Introducción al pensamiento computacional](#Introducción-al-pensamiento-computacional)
  - [Introducción al cómputo](#Introducción-al-cómputo)
  - [Lenguajes de programación](#Lenguajes-de-programación)
- [Introducción a Python](#Introducción-a-Python)
  - [Preparación de tu computadora](#Preparación-de-tu-computadora)
  - [Elementos básicos de Python](#Elementos-básicos-de-Python)
  - [Objetos, expresiones y tipos numéricos](#Objetos,-expresiones-y-tipos-numéricos)
  - [Asignación de variables](#Asignación-de-variables)
  

# Introducción al pensamiento computacional
## Introducción al cómputo

Posiblemente la primera computadora fue creada por los **antiguos griegos** el cual tenia el proposito de calcular las posiciones del Sol, Luna y algunos otros cuerpos celestes.

<br>
<div align="center"> 
  <img src="readme_img/computadora-griega.jpg" width="250">
  <h5>Mecanismo Anticitera</h5>
</div>
<br>

Miles de años despues se creo el **telar de Jacquard**, en donde las se creaban tarjetas con agujeros que representaban la información que tiene que hacer un pedazo de tela.

<br>
<div align="center"> 
  <img src="readme_img/Telar-de-Jacquard.jpg" width="350">
  <h5>Telar de Jacquard</h5>
</div>
<br>

Despues llego el **motor analítico de Charles Babbage**, el cual ocupo la tecnología de punta en su epoca para poder realizar cálculos.

<br>
<div align="center"> 
  <img src="readme_img/motor-babbage.jpg" width="350">
  <h5>Motor analítico de Charles Babbage</h5>
</div>
<br>

Durante el siglo IXX el gobierno de EE.UU. tenia serios problemas para realizar los censos como mandaba la constitución. En este momento fue cuando llego la **máquina tabuladora**, la cual se utilizo para realizar los censos con tarjetas, obteniendo resultados mas rápidos y certeros.

<br>
<div align="center"> 
  <img src="readme_img/maquina-tabuladora.jpg" width="350">
  <h5>Máquina Tabuladora</h5>
</div>
<br>

Antiguamente existia la **profesión de computadora**, la cual eran personas que se dedicaban a seguir ciertas instrucciones para obtener los resultados. Sin embargo estos resultados estaban plagados de errores. Al inicio del siglo XX ya existian compañias que tenian la necesidad de realizar calculos exactos y a gran escala. Es aquí donde llegan **Alan Turing** y **Alonzo Church** con la idea de que todos los algoritmos desarrollados por la humanidad podían ser reducidas a una maquina imaginaria, que tuviera una cinta infinita donde apuntarian símbolos y estos símbolos se pudieran manipular. Es aquí donde se comenzo la carrera para crear la primera computadora electrónica, el cual fue el **ENIAC**.

<br>
<div align="center"> 
  <img src="readme_img/church_alonzo.jpg" height="200">
  <img src="readme_img/alan-turing.jpg" height="200">
  <img src="readme_img/eniac.jpg" height="200">
  <h5>Alonzo Chruch, Alan Turing y la maquina ENIAC respectivamente.</h5>
</div>
<br>

**John von Neumann** se dio cuenta que en el hardware no solo se podía almacenar el poder de computo, tambien los programas para ejecutar. A esta arquitectura se le llama la **arquitectura de von Neumman.** De esta arquitectura nace la máquina **EDVAC** (Electronic Discrete Automatic Computer).

<br>
<div align="center"> 
  <img src="readme_img/neumann-edvac.jpeg" width="350">
  <h5>John von Neumann junto a la maquina EDVAC.</h5>
</div>
<br>

<br>
<div align="center"> 
  <img src="readme_img/arquitectura-neumann.png" width="350">
  <h5>La arquitectura von Neumann.</h5>
</div>
<br>

Con la llegada de los **microchips** llego la pauta para la computación de hoy en día. Estos microchips se hicieron tan pequeños con el tiempo usando la tecnología de la **fotónica.**

<br>
<div align="center"> 
  <img src="readme_img/microchips.jpg" height="200">
  <img src="readme_img/oblea-silicio.jpg" height="200">
  <h5>Microchip y Oblea de Silicio respectivamente.</h5>
</div>
<br>

Ya en nuestros tiempos llego la **nube**, el cual son data centers que no son mas que miles o millones de computadoras.

<br>
<div align="center"> 
  <img src="readme_img/nube.jpg" width="350">
  <h5>Sala de servidores de una nube</h5>
</div>
<br>

**Richar Feyman** nos dio las bases del computo cuantico, el pensaba que no podiamos simular los sistemas cuanticos si no teniamos una computadora cuántica, por lo cual hoy en día estamos en la carrera de la **computación cuantica.**

<br>
<div align="center"> 
  <img src="readme_img/feynman.jpeg" height="200">
  <img src="readme_img/computador-cuantico.png" height="200">
  <h5>Richard Feyman y una computadora cuántica respectivamente.</h5>
</div>
<br>

## Lenguajes de programación

¿Cómo le damos instrucciones a las computadoras? Primero debemos saber que existen **conocimiento declarativo e imperativo.** El conocimiento **declarativo** define las relaciones que existen entre diversas variables, por ejemplo una fórmula matemática. En el caso del **imperativo** nos dice como llegar a un resultado, y dentro de este existen los **algoritmos.**

Un **algoritmo** es una _lista finita de instrucciones_ que describen un cómputo, que cuando se ejecuta con ciertas entradas _(inputs)_ ejecuta pasos intermedios para llegar a un resultado _(output)_. Los algoritmos se conocen desde los antiguos griegos, y fue la evolución de estos que nos dieron los primeros **lenguajes de programación.**

**Ada Lovelace** se dio cuenta que con las bases teóricas del _motor analítico_ podía calcular una serie de los _números_ de Bernoulli_, y así creo el primer programa de computación.

<br>
<div align="center"> 
  <img src="readme_img/lovelace.jpg" width="350">
  <h5>Ada Lovelace</h5>
</div>
<br>

**Grace Murray Hopper** fue pionera en el mundo de las ciencias de la computación y la primera programadora que utilizó el _Mark I_. Entre las décadas de los 50 y 60 desarrolló el primer compilador para un lenguaje de programación así como también propició métodos de validación. Grace se le ocurrió la idea de tomar unas instrucciones de 1 y 0 para simplificarlos en una instrucción mas entendible para las personas, idea que fue el punta pie inicial para los **lenguajes de programación modernos.**

<br>
<div align="center"> 
  <img src="readme_img/Grace-Murray-Hopper.jpg" width="350">
  <h5>Grace Murray Hopper</h5>
</div>
<br>

En el sentido de la idea de los lenguajes de programación llega **Dennis Ritchie**, el cual fue el inventor del lenguaje _C_, posiblemente uno de los lenguajes mas importantes de la historia.

<br>
<div align="center"> 
  <img src="readme_img/dennis-ritchie.jpg" width="350">
  <h5>Dennis Ritchie</h5>
</div>
<br>


**Guido van Rossum**, tenia en mente crear un lenguaje de programación que fuera lo mas comprensible posible, eliminando símbolos y sintaxis extrañas, cercano al lenguaje natural. Fue por esta idea en donde nació _Python_.

<br>
<div align="center"> 
  <img src="readme_img/van-rossum.jpg" width="350">
  <h5>Guido van Rossum</h5>
</div>
<br>


Los **lenguajes de programación** modernos se les conoce como **Turing completeness** ya que implementan todos los principios para implementar cualquier tipo de _algoritmo._

Todos los **lenguajes** tienen:
- **Sintaxis:** Define la secuencia de símbolos que está bien formada.
- **Semántica estática:** Define que enunciados con sintaxis correcta tienen significado.
- **Semántica:** Define el significado. En los lenguajes de programación sólo hay un significado.

# Introducción a Python

## Preparación de tu computadora

Antes de comenzar este curso asegúrate de preparar tu entorno de trabajo para poder hacer todos los ejercicios. A continuación te compartiré los pasos que debes seguir para configurar tu computadora.

Si estás usando Windows asegúrate de instalar lo siguiente en tu computadora:

### Python 3.7 (o superior)
1. Para obtener el instalador dirígete a [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Descarga el instalador y ejecútalo en tu computadora.
3. Habilita la casilla de verificación en Install launcher for all users y Add Python 3.8 to PATH. A continuación presiona en Install Now. Windows te solicitará permisos para instalar Python en tu computadora.
4. Al finalizar la instalación se abrirá una ventana, en ella deberás presionar en la opción Disable path length limit. Windows te solicitará permisos para realizar este cambio.

### Visual Studio Code

Visual Studio Code es un editor de textos que tiene integradas varias herramientas que te ayudarán a desarrollar tus ejercicios con facilidad. Para obtenerlo en tu computadora, dirígete a: [https://code.visualstudio.com/](https://code.visualstudio.com/)

1. Realiza una instalación normal de Visual Studio code.
2. En Visual Studio Code dirígete al panel de Extensiones, se encuentra en el panel lateral izquierdo. Ahí deberás buscar la extensión llamada Python.
3. Selecciona la extensión creada por Microsoft. Una vez seleccionada, instálala.
4. Una vez instalada, reinicia Visual Studio Code.

Listo con esto podrás correr los programas que escribas en python en la terminal de Visual Studio Code.

## Elementos básicos de Python

En esta sección veremos los elementos básicos de Python, sin embargo estaremos _aprendiendo_ sobre los **elementos básicos** de cualquier lenguaje de programación.

En los lenguajes tenemos definiciones como:

- Bajo nivel vs alto nivel: 
  **Bajo nivel** significa que esta diseñado para las **máquinas**. **Alto nivel** por su parte es orientado a los **humanos.**

- General vs dominio específico: Los lenguajes **generales** tienen todos los primitivos de Turing para poder implementar y computar cualquier tipo de algoritmo. Por otro lado los de **dominio específico** son lenguajes especializados a tareas muy específicas.

- Interpretado vs compilado: En los lenguajes **interpretados** mientras corre el programa se traduce la instrucción a lenguaje máquina que para ejecutar, en cambio para los lenguajes **compilados** estos toman todas las instrucciones y las traduce _antes_ a lenguaje máquina.

Python es un lenguaje de _alto nivel, general e interpretado_.

Los elementos básicos son:

- **Literales:** son formas simples de inicializar objetos directamente en memoria.
  ```
  literales = 1, 'abc', 2.0, True
  ```

- **Operadores:** son los operadores algebraicos.
  ```
  operadores = + / % ** = ==
  ```

Podemos interpolar _literales_ y _operadores_ en nuestros algoritmos. Si el significado dentro de nuestra instrucción no tiene sentido para el lenguaje nos devolverá el tipo de error que tengamos. Para iniciar en consola él interprete lo haremos escribiendo.

```bash
python3
```

Con esto dentro de la consola podremos escribir código de Python.

```py
>>> 1 + 2
3

>>> 1 3.0 # error sintáctico
  File "<stdin>", line 1
    1 3.0
      ^
SyntaxError: invalid syntax

>>> 5 / 'Texto' # error semántico estático
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: unsupported operand type(s) for /: 'int' and 'str'

>>> 5 * 'Texto'
'TextoTextoTextoTextoTexto'

>>> print('Hello, world!') # statement o enunciado
Hello, world!
```

## Objetos, expresiones y tipos numéricos

Vamos hablar de **objetos, expresiones y tipos numéricos.**

- **Objetos**: son la abstracción más alta de cualquier lenguaje de programación, son la forma en que modelamos el mundo dentro de nuestros programas. Los objetos se encuentran en memoria y podemos referenciarlas con algún tipo de variable.

- **Tipos**: los _objetos_ pueden ser enteros, flotantes, booleanos e incluso pueden ser objetos más complejos como el modelo de un humano con todos sus características y atributos. 

- **Escalares vs no escalares**: los **escalares** son datos que podemos subdividir en piezas fundamentales, estos pueden ser enteros, flotantes, etc. Los **no escalares** son los datos que no podemos _subdividir_.

```py
>>> <objeto> <operador> <objeto>  # Esta es una expresión
<valor>

>>> 'Estoy' + 'Programando!'      # Con esta expresión
'EstoyProgramando!'               # Obtenemos este valor

>>> 2 + 2                         # Con esta expresión
4                                 # Obtenemos este valor
```

En Python podemos ver los tipos de datos que contienen nuestros objetos _(variables)_, para esto usamos la función **Type.**

```bash
>>> my_int = 1
>>> my_float = 1.0
>>> my_bool = False
>>> my_none = None

# Imprimiremos los tipos de nuestras variables.

>>> type(my_int)
<class 'int'> 

>>> type(my_float)
<class 'float'>

>>> type(my_bool)
<class 'bool'>

>>> type(my_none)
<class 'NoneType'>
```

## Asignación de variables

Las **variables** son simplemente _nombres_ que se vinculan con un _valor en memoria_, y la forma en la que los _vinculamos_ es a través del **operador de asignación (=)**, y para _comparar_ su valor utilizamos **2 veces el operador de asignación (==).** La forma correcta de nombrar nuestras variables es darles un nombre _descriptivo_.

```py
# Tenemos unas variables que no entendemos que representan
a = 2
x = 4
z = (a * x) / 2

# Y las cambiamos por unas mas descriptivas
base = 2
altura = 4
area = (base * altura) / 2
```

También podemos **reasignar** valores a nuestras _variables_.

```bash
# A my_var le asignamos un valor
>>> my_var = 'Hello, world'
>>> print(my_var)
Hello, world

# Luego reasignamos otro valor
>>> my_var = 3
>>> print(my_var)
3
```

Cuando el espacio en memoria ya no tiene ninguna variable que la referencie, el **garabage collector** libera este espacio.

Cada uno de los lenguajes de programación tiene sus reglas. Algunas reglas para las variables en Python son:

- Pueden contener mayúsculas, minusculas, numeros(sin comenzar con uno) y el simbolo _
- No pueden llamarse como las **palabras reservadas**.

Los lenguajes tienen algo llamado **palabras reservadas**, estas son objetos dentro del lenguaje que ya tienen alguna función o valor asignado.

<br>
<div align="center"> 
  <img src="readme_img/reserved-words-python.png" width="500">
</div>
<br>