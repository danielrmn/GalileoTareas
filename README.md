# GalileoTareas

Introducción a la programación de computadoras
Actividad Extra- Unidad II
Título de la actividad: Actividad Extra
Modalidad: Individual
Fecha última de entrega: lunes 06 de febrero a las 23:55 hrs
Valor: 05 pts
Explicación a la solución del problema
Primero leamos el ejercicio completo y entendamos el problema.
Primero nos indica el ejercicio que creemos una variable en donde almacenaremos el valor numérico dicho valor representa un mes del año.
// la variable tendra de nombre valor
// usamos prompt para obtener un valor a través de un alert.
También debemos hacer que el valor que obtenga el prompt sea un valor numérico, usaremos parseInt (prompt por defecto tiene un valor de string).
let valor = parseInt(prompt("ingresa un numero del 1 al 12"));también debemos crear dos variables, una de nombre y otra de carne
let name = "Daniel"
let carne = 32746 
ahora vienen las condicionales
// Usaramos un if para dar un rango de números, nos piden los números entre el 1 y el 12
if( valor1 && valor <=12)
// Usaré las sentencia switch para crear los 4 diferentes escenarios de respuesta.
switch(valor) { case 1: case 2: case 3: alert("invierno " + nameCarne); break; case 4: case 5: case 6: alert("primavera " + nameCarne); break; case 7: case 8: case 9: alert("Verano " + nameCarne); break; case 10: case 11: case 12: alert("Otoño " + nameCarne); break; default: }
// y para finalizar el else, que sera nuestra alerta de dato invalido
else{ alert("Valor invalido"); }
