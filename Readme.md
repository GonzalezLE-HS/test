## 
1.- ¿Cómo crear un entorno virtual? (1 puntos).<br>
R :

2.- ¿Cómo instalar librerías a partir de un archivo requirements.txt? (1 puntos).<br>
R:

3.- ¿Qué hace el siguiente código?  (2 puntos).<br>
R:

```py
from typing import List

ages: List[int] = [
    18,
    30,
    5,
    30,
    55,
    30
]

sum_years: List[int] = [age + 2 for age in ages]
```

4.- ¿Cuál es la diferencia entre usar comillas "" y comillas """""" ? (1 puntos).<br>
R:

5.- documenta la sugiente función y corrige el error (1 puntos). <br>

```py
def area(base: float, altura: float):
    area:float = base * altura / 2
    return area
```

6.- poner el tipado de las varibles dependiento su valor (1 puntos).

```py

is_succes = False

name = 'Lorem input ...'

age = 25

mean = 8.5

frutas = ['apple','watermelon','orange']

student = {
    name: '',
    last_name:''
}

students = [
    {
        name: '',
        last_name:''
    },
    {
        name: '',
        last_name:''
    }
]
```

6.- ¿Pon 3 ejemplos de cómo concatenar cadenas con variables? (1 puntos). <br>
R:


7.- La siguiente cadena contiene la información de un paciente, “Reto” transformar la cadena para obtener un diccionario .


```py
# datos de entrada Cadena de ejemplo
cadena = '|\^&|P|luis gonzalez|||||||R|1|test1|5|R|2|test2|10^|R|3|test3|85^'


# datos de salida Diccionario de ejemplo
{
    'paciente':'luis gonzalez',
    'resultados':[
        {
            'codigo':'test1'
            'resultado': 5
        },{
            'codigo':'test2'
            'resultado': 10
        },,{
            'codigo':'test3'
            'resultado': 85
        }
    ],
    'cadena':'||P|luis gonzalez|||||||R|1|test1|5|R|2|test2|10|R|3|test3|85'
}
```

Nota: 
Los signos (^,\,&) son basura en la cadena debes de limpiarla para ponerla en el diccionario. <br>



Puntos que se tomarán en cuenta
* 1.- Crear una clases con el nombre Clean_string que va a ser la encargada de limpiar la cadena, en el método constructor debe de recibir la cadena (3 puntos).
* 2.- Crear una clase con el nombre Parse que herede de la clase Clean_string esta clase igual debe de recibir por el método constructor la cadena (2 puntos).
* 3.- Crear un método en la clase  Parse con el nombre run_parse donde genere el Diccionario mencionado anteriormente. (4 puntos).
* 4.-Crear archivo donde crees la instancia de la clase y mandes a llamar al metodo run_parse.(1 puntos).

