# Examen de ProgramaciÃ³n

C.F.G.S Desarrollo de Aplicaciones Multiplataforma
MÃ³dulo: ProgramaciÃ³n
20 de marzo de 2018

# Instrucciones para la realizaciÃ³n y entrega del examen

*	Haz un fork desde tu cuenta de GitHub del siguiente repositorio:

	https://github.com/examentes/20180320damprog.


*	Ejecuta Eclipse y clona el fork que acabas de realizar.


*	Importa el proyecto si no lo has hecho durante la clonaciÃ³n.


*	Abre el fichero README.md y leelo completamente antes de realizar el examen.


*	Resuelve los ejercicios realizando una confirmaciÃ³n cada vez que completes cada uno de ellos.

*	En el proyecto de Eclipse se ha creado un paquete para cada ejercicio. Por tanto, las clases e interfaces que se definan en cada ejercicio deberÃ¡n pertenecer al paquete corresponidente.

### Ejercicio 1

Una empresa cualquiera desea desarrollar con Java una aplicaciÃ³n para gestionar el pago de las nomina serÃ¡ crear, utilizando las tÃ©cnicas de programaciÃ³n orientada a objetos que corresponda, las clases e interfaces que se deducen de las especificaciones siguientes:

*	Existen dos tipos de empleados: asalariados y contratistas. Todos ellos se caracterizan por su nombre, apellidos, fecha de contrataciÃ³n y nÂº de cuenta bancaria. El valor de estos atributos se podrÃ¡ consultar, pero no modificar, excepto el n.Âº de cuenta que se podrÃ¡ tanto consultar como modificar.


*	Los contratistas se caracterizan ademÃ¡s por poseer una o varias sociedades anÃ³nimas. Las sociedades anÃ³nimas son empresas especializadas en la realizaciÃ³n de determinados trabajos para los que, por la razÃ³n que sea, los empleados asalariados no estÃ¡n cualificados. Una sociedad anÃ³nima se caracteriza por su nombre (se puede consultar, pero no modificar) y por la lista de trabajos en los que estÃ¡ especializada que podrÃ¡ variar a lo largo del tiempo.


*	La empresa tambiÃ©n contrata empresas de servicios (catering, telefonÃ­a, electricidad, limpieza, etc) que se caracterizan por su nombre, el tipo de servicio prestado (ambos se pueden consultar pero no modificar) y un nÃºmero de cuenta bancaria (se puede modificar y consultar).


*	Tanto los empleados como las empresas de servicios tendrÃ¡n una interfaz comÃºn para la realizaciÃ³n del pago mediante ingreso en cuenta bancaria del importe de la nÃ³mina o del importe del servicio prestado. Simular el pago mediante mensajes por pantalla que indiquen que se realiza un ingreso en cuenta en concepto de lo que corresponda en cada caso (no es necesario especificar el importe del ingreso).

### Ejercicio 2

En el mÃ©todo main de una clase llamada `Ejercicio2`, poner a prueba las clases definidas en el ejercicio anterior con sentencias que pongan de manifiesto el uso de polimorfismo en el tratamiento de empleados y empresas de servicios, todos ellos almacenados en un mismo `ArrayList`.

### Ejercicio 3

Define la clase `StringUtil` con un Ãºnico mÃ©todo de clase llamado `contarLetrasUnicas`, que reciba como parÃ¡metro un `String` y retorne el nÃºmero de letras Ãºnicas en dicha cadena (no se harÃ¡ distinciÃ³n entre mayÃºsculas y minÃºsculas). Dado que es posible que durante la ejecuciÃ³n de un programa se invoque al mÃ©todo `contarLetrasUnicas` mÃ¡s de una vez pasÃ¡ndole la misma cadena, y teniendo en cuenta que contar el nÃºmero de letras Ãºnicas dentro de una cadena es una operaciÃ³n costosa, se pide que el mÃ©todo mantenga una cache de cadenas ya procesadas de forma que cuando se le pase una cadena ya procesada obtenga el resultado de la cache en lugar de volver a calcularlo. Utilizar las colecciones y/o mapas que se consideren necesarias para que el mÃ©todo funcione de forma eficiente.

**Ejemplo**: si el mÃ©todo recibe la cadena `"Examen de ProgramaciÃ³n"`, retornarÃ¡ el valor 8, ya que las letras x, d, p, o, g, c, i y Ã³ aparecen una sola vez.

### Ejercicio 4

Utilizando colecciones y/o mapas, crear un programa Java que establezca una concordancia entre los caracteres que aparecen en una cadena y las posiciones en las que aparecen y mostrarla por la pantalla en orden alfabÃ©tico. La cadena se recibe a travÃ©s de los parÃ¡metros de la lÃ­nea de comando. No se procesarÃ¡n los espacios en blanco ni se harÃ¡ distinciÃ³n entre mayÃºsculas y minÃºsculas.

A continuaciÃ³n se muestra un ejemplo de la salida que tendrÃ­a que mostrar el programa si se le pasa la cadena "Hola Mundo":

	{a=[3], d=[8], h=[0], l=[2], m=[5], n=[7], o[1, 9], u=[6]}

# Criterios de calificaciÃ³n

La puntuaciÃ³n mÃ¡xima de cada ejercicio serÃ¡:

*	Ejercicio 1: 3 puntos.


*	Ejercicio 2: 1 punto.


*	Ejercicio 3: 3 puntos.


*	Ejercicio 3: 3 puntos.

Los ejercicios con errores de sintaxis tendrÃ¡n una calificaciÃ³n de cero puntos.

Las soluciones parciales obtendrÃ¡n un porcentaje de la puntuaciÃ³n mÃ¡xima en funciÃ³n del grado de aproximaciÃ³n a alguna soluciÃ³n completa del problema siempre que no existan errores de sintaxis.

