    Algoritmo sin_titulo
      nombre_del_alumno<-""
      calificacion1<-0
      calificacion2<-0
      calificacion3<-0
      calificacion4<-0
      promedio<-0 
      escribir"ingresa nombre del alumno"
      leer nombre 
      escribir "ingresa calificacion1"
      leer calificacion_1
      escribir "ingresa calificacion2"
      leer calificacion_2
      escribir "ingresa calificacion3"
      leer calificacion_3
      escribir "ingresa calificacion4"
      leer calificacion_4 
      promedio=(calificacion_1+calificacion_2+calificacion_3+calificacion_4)/4
      escribir"el aulumno tuvo un promedio de ",promedio

    FinAlgoritmo





    EJERCICIO DE INTERES COMPUESTO
    
    
    Algoritmo sin_titulo
	Definir prestamo Como real
	Definir mensualidad como entero
	Definir total_a_pagar Como Real
	Definir interes Como Real
	Definir pago_mensual como real
	
    FinAlgoritmo





    CONDICIONALES
     
     REALIZA EL EJERCICIO DE UN PROGRAMA QUE CALCULA EL PROMEDIO, Y EL ESTATUS APROBADO O REPROBADO DE UN ALUMNO DE ALGUNO DE LOS SIGUIENTES 3 GRUPOS: 
     GRUPO 1: ESPAÑOL, MATEMATICAS Y CIENCIAS
     GRUPO 2: ESPAÑOL, MATEMATICAS, CIENCIAS Y INGLES
     GRUPO 3: ESPAÑOL, MATEMATICAS, CIENCIAS, INGLES Y MATEMATICAS
      
      INGRESA EL NOMBRE DEL ALUMNO
      CALIFICACIONES DE CADA MATERIA 
      PROMEDIO
      RESULTADO
      
      
     
	
	
	Definir nombre_del_alumno Como Caracter
	Definir español como real
	Definir matematicas como real
	Definir ciencias Como Real
	Definir promedio Como Real
	escribir "ingresa_nombre_del_alumno"
	leer nombre
	escribir "ingresa_calificacion_de_español"
	leer español
	
	
	Si español>10 Entonces
		escribir "calificación_invalida"
	fin si
	
	escribir "ingresa_calificacion_de_matematicas"
	leer matematicas 
	
	Si matematicas>10 Entonces
     escribir "calificación_invalida"
	SiNo
	Fin Si
	
	escribir "ingresa_calificacion_de_ciencias"
	leer ciencias
	
	Si ciencias>10 Entonces
		escribir "calificación_invalida"
	SiNo
	Fin Si
	
	promedio<-(españo+matematicas+ciencias/3)
	
	escribir "el_promedio_del_alumno",nombre_del_alumno,"es de",promedio
	Si promedio >=6 Entonces
		escribir "aprobado"
	SiNo
		escribir "reprobado"
Fin Si







Algoritmo sin_titulo
	Definir numero_1, numero_2, resultado Como Real
	Definir operación Como Caracter
	Escribir "calculadora, opciones(+, -, *, /, ^ ,MOD)"
	Leer numero_1
	Leer operación
	Leer numero_2
	Segun operación Hacer
		"+":
			resultado<- numero_1+numero_2
		"-":
			resultado<- numero_1-numero_2
		"/":
			Si numero_2 = 0 Entonces
				Escribir "no_se_divide_entre_cero"
			SiNo
				resultado<- numero_1 / numero_2
			Fin Si
		"*":
			resultado<- numero_1 * numero_2
		"**":
			resultado<- numero_1 ^ numero_2
		"//":
			resultado<- numero_1 MOD numero_2
		"%":
			resultado<- TRUNC(numero_1 / numero_2)
		De Otro Modo:
			Escribir "operador_no_valido"
	Fin Segun
	Escribir numero_1," ", operación," ", numero_2, " = ", resultado
FinAlgoritmo
