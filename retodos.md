1. Implementar un algoritmo que reciba 2 argumentos y los sume, el resultado se
deberá imprimir en pantalla
     
     Algoritmo SUMA
        
        Definir total como Entero
        Definir   a   como Entero
        Definir   b   como Entero

        Escribir "Ingresa un número"
         Leer a
        Escribir "Ingresa otro número"
         Leer b

        Total = (a + b)
        Escribir "Resultado"," " total

     FinAlgoritmo

2. Un estudiante realiza 4 exámenes, calcular el promedio de estos

     Algoritmo PROMEDIO

        Definir Resultado como real
        Definir N1 como real
        Definir N2 como real
        Definir N3 como real
        Definir N4 como real

        Escribir "Ingresa nota de Examen1"
         Leer N1
        Escribir "Ingresa nota de Examen2"
         Leer N2
        Escribir "Ingresa nota de Examen3"
         Leer N3
        Escribir "Ingresa nota de Examen4"
         Leer N4
      
        Resultado = ((N1 + N2 + N3 + N4)/4)
        Escribir "Tu promedio es"," " Resultado

     FinAlgoritmo

3. Calcular el área de un rectángulo

     Algoritmo AREADERECTANGULO

        Definir Resultado como entero
        Definir b como entero
        Definir h como entero

        Escribir "Ingresar base del rectángulo"
         Leer b
        Escribir "Ingresar altura del rectángulo"
         Leer h

        Resultado = (b*h)
        Escribir "El área del rectángulo es", " " Resultado

     FinAlgoritmo  

4. Calcular el área de un triángulo

     Algoritmo AreadeTriangulo

        Definir Resultado como entero
        Definir b como entero
        Definir h como entero

        Escribir "Ingresar base del triángulo"
         Leer b
        Escribir "Ingresar altura del triángulo"
         Leer h

        Resultado = ((b*h)/2)
        Escribir "El área del triángulo es"," " Resultado

     FinAlgoritmo 

5. Calcular el área de una circunferencia

     Algoritmo AreadeCircunferencia
      
        Definir Resultado como entero
        Definir r  como real
        Definir pi como real
        p <- 3.1416;

        Escribir "Ingresar radio de circunferencia"
         Leer r
      
        Resultado = (p*r^2)
	    Escribir "El área de circunferencia es"," " Resultado;

     FinAlgoritmo
      
6. Determinar el sueldo semanal de un trabajador basándose en sus horas
trabajadas y su salario de hora hombre

     Algoritmo SUELDO

        Definir Horas
        Definir SueldoHora
        Definir HorasSemana
        Definir Salario

        Escribir "Ingresar Horas Trabajadas"
         Leer Horas
        Escribir "Ingresar Sueldo por Hora"
         Leer SueldoHora
      
        HorasSemana = (Horas*7)
        Salario = (HorasSemana * SueldoHora)
        Escribir "Sueldo semanal es", " " Salario

     FinAlgoritmo

7. Una modista, para realizar sus prendas de vestir, encarga las telas al extranjero.
Para cada pedido, tiene que proporcionar las medidas de la tela en pulgadas,
pero ella generalmente las tiene en metros. Realice un algoritmo para ayudar a resolver el problema, determinando cuantas pulgadas debe pedir con base en
los metros que requiere. Represéntelo mediante el diagrama de flujo y el
pseudocódigo (1 pulgada = 0.0254 m).

    Algoritmo MODISTA

	    Definir resultado Como Real
	    Definir pulgada Como Real
	    Definir metro Como Real
	    pulgada <- 0.0254
	
	
	    Escribir  "Ingresar cantidad de metros de tela"
	     Leer metro
	    resultado = metro/pulgada
	    Escribir "Cantidad de pulgadas a pedir es", " " resultado
    FinAlgoritmo


8. Una empresa importadora desea determinar cuántos dólares puede adquirir
con equis cantidad de dinero peruano

   Algoritmo DOLARES

	    Definir resultado Como Real
	    Definir dólares Como Real
	    Definir soles Como Real
	    dólares <- 3.4;
	
	    Escribir "Ingrese cantidad en soles"
	     Leer soles
	    resultado = soles*dólares
	    Escribir "Puede adquirir"," " "$" resultado 

   FinAlgoritmo 

9. Una empresa que contrata personal requiere determinar la edad de las
personas que solicitan trabajo, pero cuando se les realiza la entrevista sólo se
les pregunta el año en que nacieron

  Algoritmo TRABAJO
	
	    Definir resultado Como Entero
	    Definir  año1 Como Entero
	    Definir edad Como Entero
	    año1 <- 0;
	    edad <- 0;

	    Escribir  "Ingrese año de nacimiento"
	     Leer año
	    Escribir  "Ingrese el año actual"
	     Leer año1
	    resultado = (año1 - año)
	    Escribir "La edad es", " " resultado

  FinAlgoritmo

10. Se tiene el nombre y la edad de tres personas. Se desea saber el nombre y la
edad de la persona de menor edad

   Algoritmo EDADMENOR

	    Definir edad1, edad2,edad3 Como Entero
	    Escribir "Ingrese edad uno"
	     leer edad1
	    Escribir "Ingrese edad dos"
	     leer edad2
	    Escribir "Ingrese edad tres"
	     Leer edad3
	      Si edad1 <= edad2 y edad1 <= edad3
		     Imprimir "El menor es edad uno con"," " edad1," " "años"
		
            	 SiNo
		            Si edad2 < edad3
			            Imprimir " El menor es edad dos con"," " edad2," " "años"
		         SiNo
			         Imprimir "El menor es edad  tres con"," " edad3," " "años"
		FinSi
	FinSi

FinAlgoritmo

11. Se les dará un bono por antigüedad a los empleados de una tienda. Si tienen un
año, se les dará $100; si tienen 2 años, $200, y así sucesivamente hasta los 5
años. Para los que tengan más de 5, el bono será de $1000. Realice un algoritmo
y represéntelo ,que permita determinar el bono que recibirá un trabajador

    Algoritmo BonoporAntiguedad

	    Definir antiguedad Como Real
	    Definir  bono Como Real
	
	    Escribir "Ingrese el año de antiguedad"
	     Leer antiguedad
	    Si antiguedad <= 5 Entonces
		 bono<- antiguedad*100;
	    SiNo
		 bono <- 1000;
	    FinSi
	    Escribir "valor de bono", " " bono;
	
    FinAlgoritmo

12. Un profesor tiene un salario inicial de $1500, y recibe un incremento de 10 % anual
durante 6 años. ¿Cuál es su salario al cabo de 6 años? ¿Qué salario ha recibido
en cada uno de los 6 años? Realice el algoritmo y representan la solución,
utilizando el ciclo apropiado
13. Realice un algoritmo para leer las calificaciones de N alumnos y determine el
número de aprobados y reprobados
14. Una compañía, fabrica focos de colores (verdes, blancos y rojos). Se desea
contabilizar, de un lote de N focos, el número de focos de cada color que hay en
existencia
15. Realice un algoritmo para determinar si una persona puede votar con base en
su edad en las próximas elecciones

    AlgoritmoVOTARENELECCIONES
     
     Definir edad como Entero
     
     Escribir "Ingresa tu edad"
     Leer edad

     Si (edad >=18) Entonces
     Escribir "Puedes Votar" 

     SiNo
     Escribir "No puedes votar"
    
    FinSi 




    
