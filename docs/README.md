# Investigacion de Operaciones

### Esteban Chinchilla Brenes

---

### 03-10-2021

## Mathematica como herramienta de programacion

### Investigacion de Operaciones

Metodo cientifico aplicado a la solucion de problemas y a la toma de decisiones por parte de la gerencia, estas decisiones entorno a objetivos previamente establecidos.

Sitio para descargar Mathematica

https://www.escinf.una.ac.cr/CDF/index.php/obtener-tecnologias-de-wolfram

### Mathematica comandos basicos

Mathematica trabaja por celdas para hacer una nueva celda se realiza mediante el cursos.

Para ejecutar una celda se debe posicionar en la celda y presionar Shift + enter

Al poner ; en una celda, no abra output de esa linea.


**Mathematica trabaja con memoria global**

Cada palabra reservada inicia en mayuscula.


[] Argumentos de las funciones de Mathematica
`Cos[230]`

() Expresiones aritmeticas
`Cos[3(2+3)]`

{} Listas o vectores
`{1,2}`

*Comando Plot*: Representa graficamente una funcion.
`Plot[x^3, {x, -1, 1}]`
Plot[*expresion*, {*variable*, *inicio rango*, *final rango*}]

**Comentarios en Mathematica**
`(* Esto es un comentario *)`

**Uso de %**

Nos permite llamar al ultimo resultado que Mathematica ha emitido, %% seria el penultimo, %%% el antepenultimo y asi sucesivamente.

**Uso de ?**

Retorna valor y nombre global de una variable, tambien para una palabra reservada nos brinda informacion basica, ?? nos brinda informacion mas detallada, y ???

`?a`
`?Plot`
`?*Plot* comandos que contienen palabra Plot`

*Podemos utilizar el libro de ayuda*, se haciendo lo siguiente:
1. Ayuda
2. Primera opcion del menu


**Paletas**

Usualmente usar paleta basica introductoria de Mathematica

*Tenemos en el lenguaje los operadores logicos tipicos*

**Constantes**
Se establecen de la siguiente manera

`x := 3`

`f[x_] := x^2`

*x_ ya que es un parametro, ademas se utiliza := al establecer funciones ya que no queremos que cambie*

**Usos igual =**

== es usado para comparaciones 

`5+6 == 9+2`

**Comando Random**

Brinda numeros random entre 0 y 1

`Random[]`

**Resolver ecuaciones**

Usamos el comando Solve

`Solve[expresion, variable con respecto a solucionar]`

`Solve[x + 3v == 3v - x, x]`

**Liberar variable**

Usamos Clear

`Clear[a]`











