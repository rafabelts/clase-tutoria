# Calculadora simple: 
Haz un programa que realice operaciones de suma, resta, multiplicación y división dependiendo de la opción ingresada por el usuario.

InicioAlgoritmo

repetir

escribir "1) Suma";
escribir "2) Resta";
escribir "3) Multiplicacion";
escribir "4) Division";
escribir "5) Salir";
leer opcion 

segun opcion hacer 

1:
   escribir "Ingresa un numero"
   leer num1
   escribir "Ingresa un numero"
   leer num2
   escribir num1 "+", num2, "=" (num1 + num2);
2:
   escribir "Ingresa un numero"
   leer num1
   esribir "ingresa un numero"
   leer num2 
   escribir num1 "-", num2, "=" (num1 - num2);
3:
   escribir "Ingresa un numero"
   leer num1 
   escribir "Ingresa un numero"
   leer num2
   escribir num1 "*", num2, "=" (num1 * num2);
4:
   escribir "Ingresa un numero"
   leer num1
   escribir "Ingresa un numero"
   leer num2
   escribir num1 "/", num2, "=" (num1 / num2);

hasta que opcion == 5
FinSegun
FinAlgoritmo