# Calculadora-scientific-
es una calculadora en psleint
Hasta Que edad >=18 
// Ingresa al sistema horario//
Escribir"Hola Mrs " nombre " Bienvenido al sistema horario"
	Definir hora,minuto,segund2 como entero
	Definir horat,minutut,sugunt Como Caracter
	Escribir "Debe ingrezar su hora actual"
	Escribir "ingrese hora"
	Leer hora
	Escribir "ingrese minuto"
	Leer minuto
	Escribir "ingrese segund2"
	Leer segund2
	Mientras hora <= 23 Hacer
		Mientras minuto <=59 Hacer
			Mientras segund2 <= 59 Hacer
				Limpiar Pantalla
				si hora > 9 Entonces
					Escribir hora Sin Saltar
				SiNo
					Escribir "0", hora Sin Saltar
				FinSi
				
				si minuto > 9 Entonces
					Escribir":", minuto Sin Saltar
				sino
					Escribir ":0", minuto Sin Saltar
				FinSi
				si segund2 > 9 Entonces
					Escribir ":", segund2 Sin Saltar
				SiNo
					Escribir ":0", segund2 Sin Saltar
					
				FinSi
				
				segund2 = segund2 +1
				Esperar 1 Segundo
			FinMientras
			segund2 = 0
			minuto = minuto +1
		FinMientras
		
		minuto = 0
		hora = hora +1
		si hora == 24 Entonces
			hora = 0
		FinSi
	FinMientras

FinAlgoritmo

