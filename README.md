# core-code-from-scratch-readme

# Desafio Semana 1(Miercoles)

## Algoritmo para Hacer una Pizza
1. Paso 1: Conseguir los ingredientes
2. Paso 2:Hacer y Amazar la Masa
3. Paso 3: Dejar reposar la masa durante 8 horas a temperatura ambiente.
4. Paso 4: Divide la masa en dos y aplana cada una en forma redonda.
5. Paso 5: Unta con salsa de tomate y agrega los complementos que gustes.
6. Paso 6: Ingresa la pizza en el horno de 10 a 15 min.
7. Paso 7: Saca la pizza del horno y Listo para Degustar.


## Algoritmo para Convertir de Grados Celsius a Fahrenheit 
1. Leer la temperatura
2. Validar en que el tipo de temperatura: Celsius o Fahrenheit
3. Si temperatura es Celsius entonces: 
* Temperatura Fahrenhei=((Temperatura Celsius*(9/5))+32)
* La Temperatura Convertida es = Temperatura Fahrenhei
4. Por el Contraio, Si la temperatura es Fahrenhei entonces:
* Temperatura Celsius=((Temperatura Fahrenhei-32)*5/9)
* La Temperatura Convertida es = Temperatura Celsius

## Algoritmo para Obtener el Volumen de un Cubo, Piramide o Esfera
1. Ingrese el Tipo de Objeto
2. Leer el tipo de Objeto
3. Si el Tipo Objeto es Piramide Entonces:
* Ingrese la Longitud de Base: Leer Base
* Ingrese Ancho de  Base: Leer Ancho
* Ingrese la Altura de la Piramide: Leer Altura
* Calcular Volumen: Volumen=1/3x(Base)x(Ancho)x(Altura)
* Mostrar el Volumen.
4. Por el contrario si Tipo es Cubo Entonces:
* Ingrese la tamaño de un lado: Leer lado
* Calcular Volumen: Volumen=(lado)x(lado)x(lado)
* Mostrar el Volumen.
5. Por el contrario si Tipo es Esfera Entonces:
* Ingrese el radio de la Esfera: Leer Radio
* Calcular Volumen: Volumen=((4/3)x(3.1416)x(Radio)x(Radio)x(Radio))
* Mostrar Volumen


# Desafio Semana 1(Jueves)

## Numero Par o Impar
1. Cual es el numero a evaluar
2. Leer el numeroEvaluar
3. Evaluar si numeroEvaluar es divisible entre 2.
4. Hacer la division de numeroEvaluar/2
5. Si el residuo de la division es = 0 Entonces:
6. Mostar: El Numero es Par
7. Por el contrario, Si el residuo es diferente de = 0 Entonces:
8. Mostrar: El Numero es Impar
9. Fin.

## Edad de una Persona
1. Ingrese la fecha de Nacimiento
2. Leer FechaNacimiento
3. Ingrese el año actual
4. Leer AñoActual
5. Evaluar: Restar a la Fecha de Nacimineto el Año Actual
6. EdadPersona=(FechaNacimiento)-(AñoActual)
7. Mostrar: Su edad es = EdadPersona.
8. Fin

## Tesoro Escondido

### Contradicciones
1. Cofre izquierdo: El cofre del medio tiene el tesoro:
Al ser una mentira se descarta que el cofre derecho tenga el teroso
2. Cofre Medio: Todos estos cofres tienen tesoros en ellos:
Al ser otra mentira se descartaria que absolutamente todos tengan un tesoro.
3. Cofre derecho: Sólo uno de estos cofres tiene tesoros:
Dado que este tambien es mentira se entiende que no solo hay un tesoro si no dos. En dos cofres distintos

Sacadas las contradicciones se puede entender que hay almenos dos cofres con tesoro y que no esta en el del medio.
#### La respuesta seria: Cofre Derecho e Izquierdo.


# Desafio Semana 2(Lunes)


#### Analizando el problema deduje lo siguiente:
1. Alice: No dice la verdad ya que si ninguno estudio la incluye a ella por lo que para que sea verdad quiere decir que ella debio haber estudiado.
2. Bob: 1 persona estudio si esta fuera una verdad podria ser el unico que haber estudiado ya que si dice que solo 1 que seria el mismo.
3. Charlie, Dan y Eva ellos mismo se contradicen, por que si ellos hubiesen dicho la verdad entonces se descarta la verdad de los demas por lo que hay una contradiccion.
##### La respuesta correcta seria Bob.

## Cereales o Leche
1. Conseguir los ingredientes: Leche, Cereal, Recipinetes, otros complementos.
2. Poner el cereal en el recipiente.
3. Aplicar la Leche
4. Preguntar si quiere agregar otro complemento.
5. Si quiere complemento: Agregarlo y Disfrute.

# Desafio Semana (Martes)

## Instalacion de PSeInt
![image](https://user-images.githubusercontent.com/114757669/232182823-c40875c2-ce72-4126-90fc-d648e9832417.png)


## Imprimir nombre

Algoritmo miNombre	

	Imprimir  'Alvaro Luis Cadenas'
	
FinAlgoritmo

## Imprimir nombre y edad

Algoritmo miNombre

	Imprimir 'Alvaro Luis Cadenas'
	
	Imprimir 21
	
FinAlgoritmo

# Desafio Semana 2(Miercoles)

## Juego de Algoritmos
![image](https://user-images.githubusercontent.com/114757669/232183731-9fbc8ad5-d89f-4729-9d53-8f6ac2b50e9b.png)

## MOD

Algoritmo calculo

	leer num
	
	mod=num%2
	
	Imprimir mod
	
FinAlgoritmo

## Fomulario de Registro

Algoritmo Formulario
	
	Imprimir  'Ingrese su nombre:'
	Leer nombre
	
	Imprimir  'Ingrese su Apellido:'
	Leer apellido
	
	Imprimir  'Ingrese su Edad:'
	Leer edad
	
	Imprimir  'Ingrese su Correo:'
	Leer correo
	
	Imprimir  'Ingrese su Direccion:'
	Leer direccion
	
	Imprimir 'Datos de Formulario:'
	Imprimir '_____________________'
	Imprimir nombre
	Imprimir apellido
	Imprimir edad
	Imprimir correo
	Imprimir direccion
	Imprimir '_____________________'
	
FinAlgoritmo


# Desafio Semana 2(Jueves)

## Tablas de Verdad
1. T T = T &✅
2. T F = F &✅
3. F T = T &❌
4. F F = F &✅
5. T T = T |✅
6. T F = F |❌
7. F T = T |✅
8. F F = F |✅
9. ~T = T ❌
10. ~F = T ✅
11. (t f) (F) = T &|~✅
12. (T F ) (F F) = T |&|❌
13. ~((T F ) (F F)) F = F |&|&✅
14. ~((T F ) (F F)) T = T |&|&✅

## Resultados Booleanos
Algoritmo resultados 

	a <- 5 == 3
	//a es Falso ya que 5 no es igual a 3.
	b <- 4 <> 3
	//b es Verdadero ya que 4 no es diferente a 3.
	c <- 7 > 7
	//c es Falso ya que 7 no es mayor que 7.
	d <- 4 < 4
	//d es Falso ya que 4 no es menor que 4.
	e <- 100 <= 90
	//e es Falso ya que 100 no es menor que 90 ni tampoco igual.
	f <- 40 >= 40
	//f es Verdadero ya que 40  es igual que 40.
	
FinAlgoritmo

## Numeros Pares o Impares
Algoritmo paroimpar
	
	Imprimir  'Ingrese el numero a evaluar'
	leer num
	
	si num%2 ==0 Entonces
		Imprimir 'El numero '+ConvertirATexto(num)+' Es Par'
	sino
		Imprimir 'El numero '+ConvertirATexto(num)+' Es Impar'
	FinSi
	
FinAlgoritmo

# Desafio Semana 3(Lunes)


## Numeros Calculadora Simple
Algoritmo calculadora
	
	Imprimir "========================="
	Imprimir "Ingrese su primer numero"
	leer num1
	Imprimir "Ingrese el segundo numero"
	leer num2
	Imprimir "Seleccione numero de la operacion a realizar: "
	Imprimir " + , - , * , /"
	leer op
	Si op=="+" | op=="-" | op=="*" | op=="/" Entonces
		Si op=="+" Entonces
			Imprimir "La Suma de "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2)
			Imprimir "Es total: "+ConvertirATexto(num1+num2)
		SiNo
			Si op=="-" Entonces
				Imprimir "La Resta de "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2)
				Imprimir "Es total: "+ConvertirATexto(num1-num2)
			SiNo
				si op=="*" Entonces
					Imprimir "La Multiplicacion de "+ConvertirATexto(num1)+ " x "+ConvertirATexto(num2)
					Imprimir "Es total: "+ConvertirATexto(num1+num2)
				SiNo
					Si op=="/" Entonces
						Imprimir "La Division de "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2)
						Imprimir "Es total: "+ConvertirATexto(num1+num2)
					FinSi
				FinSi
			FinSi
		Fin Si
	SiNo
		Imprimir "Ingrese el Operador Correcto"
	Fin Si
	
FinAlgoritmo

## Numero Especial

Algoritmo specialNumber

	Imprimir "Ingrese un numero"
	Leer n
	Si n == 100 Entonces
		Imprimir "¡Este es un número especial!"
	FinSi
	Si n < 1000 & n%10==0 Entonces
		Imprimir "Este numero es casi especial"
	SiNo
		Imprimir "Solo un numero regular"
	FinSi

FinAlgoritmo


# Desafio Semana 3(Martes)

## Calculadora con Switch

Algoritmo calculadora
	
	Imprimir "========================="
	Imprimir "Ingrese su primer numero"
	leer num1
	Imprimir "Ingrese el segundo numero"
	leer num2
	Imprimir "Seleccione numero de la operacion a realizar: "
	Imprimir " + , - , * , /"
	leer op
	Si op=="+" | op=="-" | op=="*" | op=="/" Entonces
		Segun op Hacer
			"+":
				Imprimir "La Suma de "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2)
				Imprimir "Es total: "+ConvertirATexto(num1+num2)
			"-":
				Imprimir "La Resta de "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2)
				Imprimir "Es total: "+ConvertirATexto(num1-num2)
			"*":
				Imprimir "La Multiplicacion de "+ConvertirATexto(num1)+ " x "+ConvertirATexto(num2)
				Imprimir "Es total: "+ConvertirATexto(num1+num2)
			"/":
				Imprimir "La Division de "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2)
				Imprimir "Es total: "+ConvertirATexto(num1+num2)
			De Otro Modo:
				Imprimir "Operacion no valida"
		Fin Segun
	SiNo
		Imprimir "Ingrese el Operador Correcto"
	Fin Si
		
FinAlgoritmo

## Programa Multi Opcion

Algoritmo multiOpcion
	Imprimir "-----------------------------"
	Imprimir "Programa Multi-Opcion"
	Imprimir "1-Suma de Dos Numeros"
	Imprimir "2-Mostrar dia de la Semana"
	Imprimir "3-Longitud de una cadenas"
	Imprimir "Seleccione el numero de la seleccion"
	Leer op
	Segun op Hacer
		1:
			Imprimir "Suma de dos numeros: "
			Imprimir "Ingrese el primero numero"
			Leer num1
			Imprimir "Ingrese el segundo numero"
			Leer num2
			Imprimir "La Suma de "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2)
			Imprimir "Es total: "+ConvertirATexto(num1+num2)

		2:
			Imprimir "Muestras de Dias de la Semana"
			Imprimir "Ingrese el numero de 1 a 7"
			Leer dia
			Segun dia Hacer
				1:
					Imprimir "Lunes"
				2:
					Imprimir "Martes"
				3:
					Imprimir "Miercoles"
				4:
					Imprimir "Jueves"
				5:
					Imprimir "Viernes"
				6:
					Imprimir "Sabado"
				7:
					Imprimir "Domingo"
				De Otro Modo:
					Imprimir "Seleccione un dia del 1 a 7"
			Fin Segun
		3:
			Imprimir "Longitud de Texto"
			Imprimir "Ingrese la cadena de texto"
			Leer texto
			Imprimir "EL tamaño del texto es: " + ConvertirATexto(Longitud(texto))
		De Otro Modo:
			Imprimir "Seleccione una opcion correcta"
	Fin Segun
FinAlgoritmo

# Desafio Semana 3(Miercoles)

## Tablas de Multiplicar

Algoritmo TablasMulti
	
	Imprimir "Tabla de Multiplicacion"
	Imprimir  "Ingrese el el numero de la tabla a calcular"
	Leer tab
	
	i=1
	Imprimir "=========================="
	Imprimir  "Tabla del "+ConvertirATexto(tab)
	Mientras i<=10 Hacer
		Imprimir ConvertirATexto(tab)+ " * " +ConvertirATexto(i)+ " = " +ConvertirATexto(tab*i)
		i=i+1
	FinMientras
	Imprimir "=========================="
	
	
FinAlgoritmo

## Calculadora Simple con DO WHILE
Algoritmo calculadoraDoWhile
	
	Repetir 
		
		Imprimir "========================="
		Imprimir "Ingrese su primer numero"
		leer num1
		Imprimir "Ingrese el segundo numero"
		leer num2
		Imprimir "Seleccione numero de la operacion a realizar: "
		Imprimir " + , - , * , /"
		leer op
		Si op=="+" | op=="-" | op=="*" | op=="/" Entonces
			Segun op Hacer
				"+":
					Imprimir "La Suma de "+ConvertirATexto(num1)+ " + "+ConvertirATexto(num2)
					Imprimir "Es total: "+ConvertirATexto(num1+num2)
				"-":
					Imprimir "La Resta de "+ConvertirATexto(num1)+ " - "+ConvertirATexto(num2)
					Imprimir "Es total: "+ConvertirATexto(num1-num2)
				"*":
					Imprimir "La Multiplicacion de "+ConvertirATexto(num1)+ " x "+ConvertirATexto(num2)
					Imprimir "Es total: "+ConvertirATexto(num1+num2)
				"/":
					Imprimir "La Division de "+ConvertirATexto(num1)+ " / "+ConvertirATexto(num2)
					Imprimir "Es total: "+ConvertirATexto(num1+num2)
				De Otro Modo:
					Imprimir "Operacion no valida"
			Fin Segun
		SiNo
			Imprimir "Ingrese el Operador Correcto"
		Fin Si
		Imprimir "Quiere realizar otra operacion"
		Leer verf
		
	Mientras Que verf="Si" || verf="si"
	
	
FinAlgoritmo

## Tablas de Multiplicar con FOR	
Algoritmo TablasMultiFor
	
	Imprimir "Tabla de Multiplicacion"
	Imprimir  "Ingrese el el numero de la tabla a calcular"
	Leer tab
	
	Imprimir "=========================="
	Imprimir  "Tabla del "+ConvertirATexto(tab)
	Para i=1 Hasta 10 Con Paso 1 Hacer
		
		Imprimir ConvertirATexto(tab)+ " * " +ConvertirATexto(i)+ " = " +ConvertirATexto(tab*i)
		
	FinPara
	Imprimir "=========================="
	
	
FinAlgoritmo

## Ordenar de Forma Ascendentes o Descendentes

Algoritmo numeroAsenoDesc
	
	Imprimir "================================="
	Imprimir "Numeros Asendentes o Descendentes"
	Imprimir "Ingrese el numero de referencia"
	Leer num
	Imprimir "Seleccione el numero de la opcion"
	Imprimir "1-Orden Asendente"
	Imprimir "2-Orden Descendentes"
	Leer op
	Segun op Hacer
		1:
			Para i=0 Hasta num Con Paso 1 Hacer
				Imprimir ConvertirATexto(i)
			Fin Para
		2:
			Para i=num Hasta 0 Con Paso -1 Hacer
				Imprimir ConvertirATexto(i)
			Fin Para
		De Otro Modo:
			Imprimir "Seleccione la Opcion correcta"
	Fin Segun
	
FinAlgoritmo

## Saludos
Algoritmo Saludos
	
	Imprimir "============================================="
	cantidad=0
	continuar=1
	Mientras continuar==1 Hacer
		
		Imprimir "Ingrse la hora representad en Fomato 24H(0-23)"
		Leer hora
		
		Si hora<=12 Entonces
			Imprimir "BUENOS DIAS :)"
			
		SiNo
			Si hora<=18 Entonces
				Imprimir "BUENAS TARDES :)"
				
			SiNo
				Si hora <=23 Entonces
					Imprimir "BUENAS NOCHES :)"
				FinSi
				
			FinSi
		FinSi
		
		Imprimir "Desea continuar con los saludos"
		Imprimir "1-Si   o   2-No"
		Leer continuar
		
		cantidad=cantidad+1;
	FinMientras
	
	Imprimir "El total de los saludos fue: "+ConvertirATexto(cantidad)
FinAlgoritmo

