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

# Desafio Semana 4(Lunes)

## Comision y Promedio de Ventas
Algoritmo ventas
	
	Escribir "Ingrese la cantidad de Ventas: "
	Leer venta
	SumTot=0
	Para i=1 Hasta venta Con Paso 1 Hacer
		
		Imprimir "Ingrese el Monto de la Venta "+ConvertirATexto(i)
		Leer monto		
		SumTot=+monto
		
	FinPara
	
	promedio=SumTot/venta
	comision=0
	
	Si  venta<=5 & venta>0 Entonces
		
		comision=SumTot*0.10
		
	FinSi
	
	Si venta>5
			comision=SumTot*0.15
	FinSi

	Imprimir "El Promedio de Ventas es: "+ConvertirATexto(promedio)	
	Imprimir "La comision por sus ventas fue: "+ConvertirATexto(comision)	
	
	
FinAlgoritmo

## Numeros Pares o Impares
Algoritmo paroimpar
	
	Repetir
		Imprimir "Ingrese un numero entre 1-50"
		Leer num
		
		Si num>50 | num<0
			Imprimir "Por favor ingrese un numero entre 1-50"
		FinSi
		
	Mientras Que num>50 | num<=0
	
	numPar=num%2=0
	
	Para i=0 Hasta num Con Paso 1 Hacer
		Si i%2=0 & numPar Entonces
			Imprimir i
		FinSi
		Si i%2=1 & ~(numPar) Entonces
			Imprimir i
		FinSi		
	FinPara
	
FinAlgoritmo

# Desafio Semana 4(Martes)

## Nombre con Letras Mayusculas
Algoritmo nombre
	
	Imprimir "Ingrese el Nombre"
	Leer nom
	
	Imprimir "Ingrese su Apellido"
	Leer ape
	
	nombreP = Mayusculas(Subcadena(nom,0,0)) + Minusculas(Subcadena(nom,1,Longitud(nom)-1))
	apellido=Mayusculas(Subcadena(ape,0,0)) + Minusculas(Subcadena(ape,1,Longitud(ape)-1))
	
	Imprimir nombreP +" "+apellido
	
FinAlgoritmo

## Tira de Dados
Algoritmo dados
	
	Definir dado1 Como Entero
	Definir dado2 Como Entero
	
	Para i=1 Hasta 10 Con Paso 1 Hacer
		
		dado1=Aleatorio(1,6)
		dado2=Aleatorio(1,6)
		
		Si dado1=dado2 Entonces
			Imprimir dado1," ",dado2," Los dados son iguales"
			
		SiNo
			Imprimir dado1," ",dado2
		FinSi
		
	FinPara
	
FinAlgoritmo

# Desafio Semana 4(Miercoles)

## Distancia a Cero

Algoritmo distanciadeCero
	
	Imprimir "Ingrese un numero"
	Leer num
	
	Para i=1 Hasta 4 Con Paso 1 Hacer
		Imprimir "Ingrese un numero"
		Leer numero
		Si Abs(numero) > Abs(num) Entonces
			num=numero
		FinSi
	FinPara
	
	Imprimir "El numero mas alejado de 0 es",Trunc(num)
	
	
FinAlgoritmo

## Lanzar Moneda

Algoritmo lanzarMoneda
	
	Imprimir "Ingrese el nombre del primer Jugador"
	Leer jug1
	
	Imprimir "Ingrese el monto del jugador 1"
	Leer monto1
	
	Imprimir "Ingrese el nombre del segundo Jugador"
	Leer jug2
	
	Imprimir "Ingrese el monto del jugador 2"
	Leer monto2
	
	Si monto1<=0 | monto2 <=0 Entonces
		Si monto1<=0 & monto2 <=0 Entonces
			Imprimir "Juego Cancelado"
			
		SiNo
			SI monto1<=0 Entonces
				Imprimir "Jugador Ganador ",Mayusculas(jug2)," Monto 0"
			Sino
					Imprimir "Jugador Ganador ",Mayusculas(jug1)," Monto 0"
			FinSi
		FinSi
	SiNo
		Si Aleatorio(1,2) =1 Entonces
			Imprimir "Jugador Ganador ", Mayusculas(jug1)," Monto ",monto2
		SiNo
			Imprimir "Jugador Ganador ", Mayusculas(jug2)," Monto ",monto1
		FinSi
		
	FinSi
	
	
FinAlgoritmo

# Desafio Semana 4(Jueves)

## Precio Total
Funcion  total <- TotalPrice(precio,iva)
	
	SI precio>3000

		totalIVa=precio*(iva/100)
		descuento=(precio+totalIVa)*0.1
		total=(precio+totalIVa)-descuento
	SiNo
		
		totalIVa=precio*(iva/100)
		total=precio+totalIVa
		
	FinSi
	

	
FinFuncion


Algoritmo precioTotal
	
	Imprimir TotalPrice(5000,21)

	
FinAlgoritmo

## Letras al Reves

Funcion reves<-textoReves(texto)
	
	Definir textoRev Como Caracter;
	textoRev=""
	tam=Longitud(texto)
	Para i = tam Hasta 0 Con Paso -1 Hacer
		
		may= Subcadena(texto,i,i);
		
		SI may=Mayusculas(may) Entonces
			
			may=Minusculas(may)
			
		SiNo

			may=Mayusculas(may)
			
		FinSi
		
		textoRev = Concatenar(textoRev, may)
	FinPara
	reves=textoRev
FinFuncion


Algoritmo letrasReves
	
	Imprimir textoReves("Hola")
	
FinAlgoritmo

# Desafio Semana 5(Lunes)

## Convertidor de Tiempo

Funcion tiempo <- conversor(seg)
	
	Definir min, hora, dias Como Entero 
	min=Trunc(seg/60)
	hora=Trunc(seg/3600)
	dias=Trunc(seg/86400)
	
	tiempo= "días: "+ConvertirATexto(Trunc(dias))+" horas: "+ConvertirATexto(hora%24)+" min: "+ConvertirATexto(min%60)+" seg: "+ConvertirATexto(seg%60)
	
FinFuncion

Algoritmo conversorDeTiempo

	Imprimir conversor(40000 )
	
FinAlgoritmo

## Comparar Distancias

Funcion resultado <- Comparacion()

	i=0;
	negat=0
	posit=0
	
	Mientras i<5 Hacer
		Imprimir "Ingrese un Numero:"
		leer num
		si(num>0)
			posit=posit+num
		SiNo
			negat=negat+num
		FinSi
		i=i+1;
	FinMientras

	SI(posit>Abs(negat))
		resultado=Verdadero
	SiNo
		resultado=falso
	FinSi
	
FinFuncion

Algoritmo compararDistancia

	Imprimir Comparacion();
	
FinAlgoritmo

# Desafio Semana 5(Martes)

## Suma de Pares

Funcion resultado<-suma()

	sum=0
	num=0
	Hacer
		Imprimir "Ingrese un numero entre 1 a 100"
		leer num
		si num<1 | num >100
			Imprimir "Numero Incorrecto"
		SiNo
			Si num%2 =0
				sum=sum+num
			FinSi
		FinSi
	Mientras Que num>1 & num<=100
	resultado=sum
	
FinFuncion

Algoritmo sumPar

	Imprimir suma()
	
FinAlgoritmo

## Punto Medio

Funcion resultado<-medio(num1,num2)

	Si num1 > 0 Entonces
		Si num2 > 0 Entonces
			SI num1 > num2 Entonces
				resultado = num2 + ((num1 - num2) / 2); 
			SiNo
				resultado = num1 + ((num2 - num1) / 2);
			FinSi
		SiNo
			resultado = num1 - ( (num1 + Abs(num2))/2);
		FinSi
	SiNo
		SI num2 > 0 Entonces
			resultado = num1 + ( (num2 + Abs(num1))/2)	;
		SiNo
			SI Abs(num1) > Abs(num2) Entonces
				resultado = num1 + ((Abs(num1) - Abs(num2)) / 2); 
			SiNo
				resultado = num2 + ((Abs(num2) - Abs(num1)) / 2); 
			FinSi
		FinSi
	FinSi
FinFuncion

Algoritmo puntoMedio

	Imprimir  medio(40,80)
	
FinAlgoritmo

# Desafio Semana 5(Miercoles)

## Cajero

Funcion opc <- menu()
	
	saldo=1000
	Repetir
		Imprimir "Seleccione una Opcion"
		Imprimir "a-Depositar"
		Imprimir "b-Retirar"
		Imprimir "c-Cerrar Sesion"
		leer op
		Si op="a"
			Saldo=Saldo+Deposito()
		FinSi
		Si op="b"
			Saldo=Saldo-Salida()
		FinSi
	Mientras Que op="a" | op="b"
	
	opc=Saldo
	
FinFuncion

Funcion egreso <-Salida()

	Imprimir "Ingrese el monto a Retirar"
	Leer egreso
	
FinFuncion

Funcion ingreso <- Deposito()

	Imprimir "Ingrese el monto a Depositar"
	Leer ingreso
	
FinFuncion

Algoritmo Banco

	Imprimir menu()
	
FinAlgoritmo

## Promedio de Tiempo

Funcion result <- grados()
	
	celsius=0
	i=0
	grad=0
	Repetir
		Imprimir "Seleccione una Opcion: "
		Imprimir "a-Grados Celsius"
		Imprimir "b-Grados Fahrenheit"
		Imprimir "c-Salir"
		Leer op
		si op="a"
			Imprimir "Ingrese los grados en Celsius"
			leer grad
			celsius=celsius+grad
		FinSi
		Si op="b"
			Imprimir "Ingrese los grados en Fahrenheit"
			leer grad
			celsius=celsius+Conversor(grad)
		FinSi
		i=i+1
	Mientras Que op="a" | op="b"
	result=celsius/i
	
FinFuncion

Funcion gcelsius<-Conversor(g)

	gcelsius=(g - 32 ) / 1.8
	
FinFuncion

Algoritmo promTiempo
	
	Imprimir grados()
	
FinAlgoritmo

# Desafio Semana 5(Jueves)

## Condicion IF

if(hora>5){
	console.log('Buenas Noches')
}else{
	console.log('Buenas Tardes')
}

## Condicion While
while (i < 5) {
    console.log("Numero: " + i);
    i = i + 1;
  }


## Condicion For

  for (let i = 0; i < 10; i++) {
    console.log("Numero: " + i);
  }
  
# Desafio Semana 6(Lunes)

## Iniciar en HTML
![image](https://github.com/alvcd21/core-code-from-scratch-readme/assets/114757669/8ceb03a5-ef2c-4f69-9001-d80276e3d972)

# Desafio Semana 6(Martes)

## Variables

const saludo="Hello Word"

## Que es X

//El valor de X es: 'Geeta'

## Varias Variables

let flower = 'rose';
let tree = 'maple';

## Reasignacion

//El valor de x despues de la reasignacion es: 'Toe'

## Asignar variables
//El valor de x despues de la asignacion de la varible X es: 'Hardy'

# Desafio Semana 6(Miercoles)

## Funciones

function hello(){
return 'Hello world!'
}

## Multiples Funciones

function a(){
return 'Hello a!'
}

function b(){
return 'Hello b!'
}

## Llamadas a Funciones

function greet(){
return 'Haydo!'
}

let salutation=greet()

## Que es X(Version Funciones)
//El valor que devuelve X es: 'How do you do?'

## Parametros
function echo(Greta){
return Greta
}

# Desafio Semana 6(Jueves)

## Instrumentos de cuerda

function greet (dato){
  return 'Hello '+dato+'!'
}

greet('Ada');

## Tamaño de Cadenas

function length(texto){
  return texto.length;
}

## toUpperCase y toLowerCase

function toCase(texto){
   return texto.toLowerCase()+'-'+texto.toUpperCase()
}

## CharAt

function shortcut(text1, text2){
  
  return text1.charAt(0)+text2.charAt(0)

}

## indexOf

function indexOfIgnoreCase(text1, text2){

   return text1.toLowerCase().indexOf(text2.toLowerCase())

}

# Desafio Semana 7(Lunes)

## Condicion IF
function firstWord(dato){

    return dato.substr(0,dato.indexOf(' '))

}

# Desafio Semana 7(Martes)

## Primeros Pasos con Code Wars

![image](https://github.com/alvcd21/core-code-from-scratch-readme/assets/114757669/935d5394-7168-4046-9923-264f7fc2aa68)

## Objetos

function animal(obj) {
  return "This " + obj.color + " " + obj.name + " has " + obj.legs + " legs.";
}

## Return to Sanity

function mystery() {
  var results = {sanity: 'Hello'};
  return results;
}

## Depuracion de Sintaxis de Objeto

var rooms = {
  first: {
    description: 'This is the first room',
    items: {
      chair: 'The old chair looks comfortable',
      lamp: 'This lamp looks ancient'
      }
  },
  second: {
    description: 'This is the second room',
    items: {
      couch: 'This couch looks like it would hurt your back',
      table: 'On the table there is an unopened bottle of water'
    }
  }
}

# Desafio Semana 7(Miercoles)

## Contar Cadena de Objetos

function strCount(obj) {
  let count = 0;

  for (let key in obj) {
    if (typeof obj[key] === "string") {
      count++;
    } else if (typeof obj[key] === "object" && obj[key] !== null) {
      count += strCount(obj[key]);
    }
  }

  return count;
}

## Extending JavaScript Objects: Get First & Last Array Element

Array.prototype.first = function() {
  return this[0];
};

Array.prototype.last = function() {
  return this[this.length - 1];
};

## Object Oriented Piracy

function Ship(draft,crew) {
 this.draft = draft;
 this.crew = crew;
  
  this.isWorthIt = function (){
    return (this.draft - this.crew * 1.5) > 20;
  }
}
## Convertir de String a Numero

const stringToNumber = function(str){
  // put your code here
  return Number(str);
}

## Convertir de Numero a Array

function digitize(n) {
  //code here
  var digits = String(n).split('');
  return digits.reverse().map(Number);
}

## Truthy y Falsy
const truthy = [true,"false",2,[],{}];
const falsy = [false,"",0,null,undefined];

## Tipos de datos básicos: matriz

function getLength(arr){
  //return length of arr
  
  return arr.length;
}
function getFirst(arr){
  //return the first element of arr
  return arr[0];
}
function getLast(arr){
  //return the last element of arr
  
  return arr[arr.length-1];
}
function pushElement(arr){
  //push el to arr
  arr.push("Hello");
  return arr
}
function popElement(arr){
  //pop an element from arr
  arr.pop();
  return arr
}
# Desafio Semana 8(Lunes)

## If, Else y Operador 
function saleHotdogs(n){
  var precio;
  if(n<5) precio=100*n;
  else if(n>=5 && n<10) precio=95*n;
  else if(n>=10) precio=90*n;
  return precio;
}
## Switch
function howManydays(month){
  var days;
switch (month){
    
    case 1:
      days=31;
    break;
    case 3:
      days=31;
    break;
    case 5:
      days=31;
    break;
    case 7:
      days=31;
    break;
    case 8:
      days=31;
    break;
    case 10:
      days=31;
    break;
    case 12:
      days=31;
    break;
    
    
    case 4:
      days=30;
    break;  
    case 6:
      days=30;
    break;   
    case 9:
      days=30;
    break;
    case 11:
      days=30;
    break;
    
    case 2:
      days=28;
    break;
  
  }
  return days;
}

## Calculadora

function calculate(num1, operation, num2) {
 //TODO: make a basic calculator. 
    switch(operation){
        case '+': 
            return num1 + num2;
        break;
        case '-': 
            return num1-num2;
        break;
       case '*': 
            return num1*num2;
        break;
        case '/': 
            return num2 !=0 ? num1/num2: null;
        break;
        default:
        
        return null;
        
    }
}
# Desafio Semana 8(Martes)
## Par o Impar 
function evenOrOdd(number) {
  
  if(number%2==0){
    return "Even";
  }else{
    return "Odd"
  }
  
}
## Un lobo con piel de oveja 
function warnTheSheep(queue) {
  
  let loboP=queue.indexOf('wolf');
  let ovejaP=queue.length-(loboP+1);
  if(loboP===queue.length-1){
    return "Pls go away and stop eating my sheep";
  }else{
    return "Oi! Sheep number "+ovejaP+"! You are about to be eaten by a wolf!";
  }
   
}

## Decodificar el código morse

decodeMorse = function(morseCode){
  // Your code here
  // You can use MORSE_CODE[morse]
  
  let palabras=morseCode.trim().split('   ');
  let letras=[];
  let frase=[];
  
  for(let i=0; i<palabras.length;i++){
    
    letras=palabras[i].split(' ');
    
    for(let j=0; j<letras.length; j++){    
      
      letras[j]=MORSE_CODE[letras[j]]
      
    }
    frase.push(letras.join(''));
    
  }
  return frase.join(' ').trim();
  
}


# Desafio Semana 8(Miercoles)

## ¿A quién le gusta?

function likes(names) {
  // TODO
  var nombres=[];
   if(names.length==0){
     return "no one likes this";
   }else{
      
      for(let i=0;i<names.length;i++){
        
        nombres.push(names[i]);
        
      }
      
      if(nombres.length==1){
          return nombres.join(' and ')+' likes this';
      }else if(nombres.length==2){        
          return nombres[0]+' and '+nombres[1]+' like this';
      }else if(nombres.length==3){        
          return nombres[0]+', '+nombres[1]+' and '+nombres[2]+' like this';
      }else if(nombres.length>=4){
          return nombres[0]+', '+nombres[1]+' and '+(nombres.length-2)+' others like this';
      }
   }

 
}
## Conteo de bits
var countBits = function(n) {
  // Program Me
    let numb=[];
    numb=n.toString(2).split('');
    let cont=0;
  for(let i=0; i<numb.length;i++){
    
    numb[i]==1 ? cont++:cont
    
  }
  
  return cont;
  
};

## Su pedido, por favor

function order(words){
  // ...
  let palab=[];
  let texto=[];
  palab=words.trim().split(' ');
  
  for(let i=0; i<=palab.length;i++ ){
    for(let j=0; j<palab.length; j++){
      if (palab[j].indexOf(i) >= 0) {
        texto.push(palab[j]);
      }
    }
  }
  return texto.join(' ').trim()
}

## Conteo de Duplicados

function duplicateCount(text){
  var count=0;
  let texto=text.toLowerCase();
  
  for(let i=0; i<texto.length;i++){
    
   if (texto.indexOf(texto[i]) !== texto.lastIndexOf(texto[i])) {
      count++;
      texto = texto.replace(new RegExp(texto[i], 'g'), '');
      i = i - 1;
    }
    
  }
  return count;
    
}

## Cifre Esto

function encrypt(palab){
  
  if(palab.length===1) return palab.charCodeAt(0);
  const chB=palab[1];
  palab=palab.replace(palab[0], palab.charCodeAt(0));
  palab=palab.replace(chB, palab[palab.length - 1]);
  palab=palab.replace(/\w$/, chB);
  return palab;
}
var encryptThis = function(text) {
    
  let tArr=text.split(' ');
  let resultado='';
  
  tArr.forEach((wd)=>{
    resultado=resultado+' '+encrypt(wd);
  });
  
  return resultado.trim();
  
}

## Paréntesis válidos

function validParentheses(parens) {
  return [...parens].reduce((a, c) => (a + c).replace('()', ''), '') === '';
}

## Convertir cadena a estuche de camello

function toCamelCase(str){
  return str.replace(/-/g, '_').split('_').map((word, i) => (i > 0 ? word.toUpperCase()[0] + word.substr(1) : word)).join('');
}
