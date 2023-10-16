# Algoritmos
**Indicaciones:** Primero, modifique y corrija el pseudocódigo propuesto por Rodríguez (sf) , de acuerdo a las reglas de PseInt configuradas en el perfil "UNAM FCA" 
y de acuerdo a la estructura del algoritmo aprendido en la clase, en la lista de ejercicios, según su número de lista de grupo.

**Numero de lista: 18**

### Ejercicio 1
```
//Servín Ruiz Alan Tenyo
//Informatica
// Horario: Lunes y Miercoles 2-4pm
//ALGORITMO #12
//Autor origninal: Rodríguez (s.f.)

Proceso Aumento_Sueldo
	
	//1. Definición de variables y tipo de datos
	
		Definir sueldo, aumento Como Real;
		Definir catg Como Entero;
		
		//2.Inicialización de variables
		
		Escribir "Categorias 1 = 0.15";
		Escribir "Categorias 2 = 0.10";
		Escribir "Categorias 3 = 0.08";
		Escribir "Categorias 4 = 0.07";
		Escribir "Ingrese su categoria del 1-4: ";
		Leer catg;
		
		Si catg >= 1 Y catg <= 4 Entonces
			Escribir "Ingrese el sueldo actual: ";
			Leer sueldo;
			
			//3.Procesamiento
			
			Segun catg hacer
				Caso 1:
					aumento <- sueldo * 0.15;
				Caso 2:
					aumento <- sueldo * 0.10;
				Caso 3:
					aumento <- sueldo * 0.08;
				Caso 4:
					aumento <- sueldo * 0.07;
			FinSegun
			//4. Salida
			Escribir "El aumento de sueldo es: ", aumento;
			Escribir "Tu sueldo final es: ", sueldo + aumento;
			
		Sino
			Escribir "Categoría no reconocida";
		FinSi
FinProceso
```
### Ejercicio 2
```
//Servín Ruiz Alan Tenyo
//Informatica
// Horario: Lunes y Miercoles 2-4pm
//ALGORITMO #22
//Autor origninal: Rodríguez (s.f.)

Proceso Puntuacion
	
	//Definición de variables y tipos de datos
	
	Definir N1, N2, N3, N4 Como Entero;
	Definir prom Como Real;
	
	//Procesamiento
	
	Leer N1, N2, N3, N4;
	Si (N1>= 0 y N1<=100) y (N2>= 0 y N2<=100) y (N3>= 0 y N3<=100) y (N4>= 0 y N4<=100) Entonces
		prom= ( N1+ N2+ N3+ N4)/4;
	SiNo
		Escribir "Algún N esta fuera de rango";
	FinSi
	//procesamiento y fin
	Si (prom>= 0 y prom<= 59) Entonces
		Escribir "Tu puntuación es E";
	SiNo
		Si (prom>= 60 y prom<= 69) Entonces
			Escribir "Tu puntuación es d";
		SiNo
			Si (prom>= 70 y prom<= 79) Entonces
				Escribir "Tu puntuación es d";
			SiNo
				Si (prom>= 80 y prom<= 89) Entonces
					Escribir "Tu puntuación es C";
				SiNo
					Si (prom>= 90 y prom<= 100)  Entonces
						Escribir "Tu puntuación es A";
					FinSi
				FinSi
			FinSi
		FinSi
	FinSi
FinProceso
```
