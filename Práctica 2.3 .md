# Práctica 2.3. Pseudocódigo
### Parte 2
Estudie, a discreción, el curso de PSeInt y la guía de PSeInt con ejemplos y pruebe algunos ejemplos. Si lo prefiere, estudie el sistema de información para la operación de un estacionamiento en PSeInt. Descargue el archivo con el código fuente del pseudocódigo, disponible en la descripción de cada uno de ellos y observe el crecimiento progresivo de la aplicación.
Para desarrollar está parte de la práctica nos basamos unicamente en analizar los parámetros o datos de entrada, el pase valores (por valor y por referencia) y el valor de regreso.

```
// Está es la primera parte de 7 del código para la simulación de 
//la administración de un parquadero

Proceso Parqueadero
	
	//Definición de variables
	Definir  CANTIDADPUESTOS, opciono, ingresado como entero; 
	Definir  valorMinuto Como Real;
	CANTIDADPUESTOS=10;
	
	//Definición de vectores
	dimension placa[CANTIDADPUESTOS];
	dimension puesto[CANTIDADPUESTOS];
	dimension horaIngreso[CANTIDADPUESTOS];
	dimension horaSalida[CANTIDADPUESTOS];
	dimension propietario[CANTIDADPUESTOS];
	dimension ocupados[CANTIDADPUESTOS];
	
	//Inicializar variables
	opciono = 0;
	valorMinuto=300;
	ingresado=0;
	
	// A partir de aquí inicia la parte principal del código
	
	Para i=0 Hasta CANTIDADPUESTOS-1 Con Paso 1 Hacer
		puesto[i]="A"+ConvertirATexto(i);
		ocupados[i]=-1;
	FinPara
	
	Escribir "                ###############################";
	Escribir "                # Paqueadero MaxTechnology 24/7 #";
	Escribir "                ###############################";
	Escribir "";
	
	
	Repetir
		Escribir "-------------------------------";
		Escribir "| 1. Ingresar vehiculo        |";
		Escribir "| 2. Dar salida a un vehiculo |";
		Escribir "| 3. Consultar disponibilidad |";
		Escribir "| 4. Puestos asignados        |";
		Escribir "| 5. Salir                    |";
		Escribir "-------------------------------";
		Escribir "";
		leer opciong;
		
		//Para esta parte inician los subprocesos, ya que al ser varias 
		//opciones cuentan como datos de entrada y cada "Escribir" da el 
		//valor de regreso dependiendo de la opción que se seleccione 
		
		Segun opciono Hacer
			1:
				Escribir "Ingresar vehiculo";
			2:
				Escribir "Dar salida";
			3:
				Escribir "Disponibilidad";
			4:
				Escribir "Ocupados...";
			5:
				Borrar Pantalla;
				Escribir "Chao.";
			De Otro Modo:
				Escribir  "Opción no valida";
		FinSegun
		
	Hasta Que opciono=5
	
FinProceso
```
Para este ejemplo fue importante tener en consideración tener la configuración de lenguaje correcta:

![imagen](https://github.com/AlanServin/Informatica/assets/146912691/427ce4cb-70d5-4117-950f-e97cbb5dcfc1)
