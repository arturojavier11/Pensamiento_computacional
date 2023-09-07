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





	Para i<-0 Hasta 100 Con Paso 2 Hacer
			Escribir i
		Fin Para






	Definir num Como Entero
		Definir res como Entero
		Escribir "dime de que numero quieres la tabla"
		Leer num
		Para i<-1 Hasta 10 Con Paso 1 Hacer 
			res<-i*num
			Escribir num, " x ",i," = ",res
		Fin Para
		
		
		
		
		
		Definir nombre Como Caracter
	Definir veces Como Entero
	Escribir "ingresa nombre"
	leer nombre
	Escribir "cuantas veces quieres imprimir"
	Leer veces
	Para i<-1 Hasta veces Con Paso 1 Hacer
		Escribir i, " ", nombre
	Fin Para
		
		




	Definir nombre Como Caracter
		Definir calif Como Real
		Definir promedio Como Real
		Definir veces Como Entero
		Definir suma Como Real
		Definir numero_de_alumnos Como Entero
		Escribir "numero de alumnos"
		leer numero_de_alumnos
		Para j<-1 Hasta numero_de_alumnos Con Paso 1 Hacer
			Escribir "ingresa nombre del alumno ",j
			Leer nombre
			Escribir "cuantas calificaciónes tiene ", nombre
			Leer veces
			Para i<-1 Hasta veces Con Paso 1 Hacer
				Escribir "ingresa calificación ", i, " de ",nombre
				leer calif
				suma<- suma+calif
				promedio<- suma/veces
			Fin Para
			Escribir "el promedio de ",nombre, " es de ",promedio
		Fin Para
		
		
		
		
		
		
		wihile
		
		Definir nombre Como Caracter
	Definir opción Como Caracter
	Escribir "ingresa tu nombre"	
	Leer nombre
	Escribir "quieres imprimir tu nombre si o no"
	Leer opción
	Mientras opción= " si " O opción= " no "   Hacer
		Escribir nombre
		Escribir "quieres imprimir si o no"
		Leer opción
	Fin Mientras
	
	
	
	
	
	
	Definir nombre Como Caracter
	Definir veces Como Entero
	Definir i Como Entero
	Escribir "ingresa nombre"
	Leer nombre
	Escribir "cuantas veces"
	Leer veces
	Mientras i < veces Hacer
		Escribir nombre
	Fin Mientras
	
	
	
	
	
	Definir num_secreto Como Entero
	Definir num_usuario Como Entero
	num_secreto<-( azar (99))+1
	Escribir "adivina el numero de secreto"
	leer num_usuario
	Mientras num_secreto <> num_usuario Hacer
		Escribir "adivina el numero secreto"
		Leer numero_secreto
	Fin Mientras
	
	
	
	
	
	Definir num_secreto Como Entero
	Definir num_usuario Como Entero
	Definir vidas Como Entero
	vidas<-5
	num_secreto<-azar(99)+1
	
	Escribir "adivina el numero secreto tines 5 oportunidades"
	leer num_usuario
	Mientras num_secreto <> num_usuario y vidas>0 Hacer
		Si num_secreto > num_usuario Entonces
			Escribir "numero secreto es mayor al que ingresaste"
		SiNo
			Escribir "el numero secreto es menor al que ingresaste"
		Fin Si
		Escribir "adivina el numero secreto tienes " ,vidas, " vidas "
		Leer num_usuario
		vidas<-vidas-1
	Fin Mientras
	Si num_secreto = num_usuario Entonces
		Escribir "felicidades le atinaste"
	SiNo
		Escribir "mala suerte no acertaste"
	Fin Si

![image](https://github.com/arturojavier11/Pensamiento_computacional/assets/125502848/8bcc6080-e538-4514-a39c-f61a6147f130)
