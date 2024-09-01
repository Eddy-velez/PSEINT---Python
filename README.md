# PSEINT---Python
Operaciones básicas en PSEINT y Python
#def calcular_100_años():
    #nombre = input("Introduce tu nombre: ")
    #edad = int(input("Introduce tu edad: "))

    #año_actual = 2024
    #año_100 = año_actual + (100 - edad)

    #print(f"Hola {nombre}. Cumplirás 100 años en el año {año_100}.")

#calcular_100_años()


#def calculos_basicos():
    #numero_entero = 10
    #numero_flotante = 5.75
    #texto = "Resultado"

    #PI = 3.1416  # Constante

    #suma = numero_entero + numero_flotante
    #resta = numero_entero - numero_flotante
    #multiplicacion = numero_entero * PI
    #division = numero_entero / numero_flotante

    
    #print(f"Suma = {suma}")
    #print(f"Resta = {resta}")
    #print(f"Multiplicación con PI = {multiplicacion}")
    #print(f"División = {division}")

#calculos_basicos()

#def operaciones_y_comparaciones():
    #numero1 = float(input("Introduce el primer número: "))
    #numero2 = float(input("Introduce el segundo número: "))

    #suma = numero1 + numero2
    #resta = numero1 - numero2
    #multiplicacion = numero1 * numero2
    #division = numero1 / numero2

    #print("Resultados:")
    #print(f"Suma: {suma}")
    #print(f"Resta: {resta}")
    #print(f"Multiplicación: {multiplicacion}")
    #print(f"División: {division}")

    #if suma > multiplicacion:
        #print("La suma es mayor que la multiplicación.")
    #else:
        #print("La multiplicación es mayor o igual que la suma.")

    #if resta < division:
        #print("La resta es menor que la división.")
    #else:
        #rint("La resta es mayor o igual que la división.")

#operaciones_y_comparaciones()

Proceso Calcular_100_Años
		Definir nombre Como Caracter
		Definir edad, año_actual, año_100 Como Entero
		
		Escribir "Introduce tu nombre:"
		Leer nombre
		
		Escribir "Introduce tu edad:"
		Leer edad
		
		año_actual = 2024
		año_100 = año_actual + (100 - edad)
		
		Escribir "Hola ", nombre, ". Cumplirás 100 años en el año ", año_100, "."
FinProceso

Definir numero_entero Como Entero
    Definir numero_flotante Como Real
    Definir texto Como Caracter
	
    numero_entero = 10
    numero_flotante = 5.75
    texto = "Resultado"
	
    suma = numero_entero + numero_flotante
    resta = numero_entero - numero_flotante
    multiplicacion = numero_entero * PI
    division = numero_entero / numero_flotante
	
    Escribir "Suma = ", suma
    Escribir "Resta = ", resta
    Escribir "Multiplicación con PI = ", multiplicacion
    Escribir "División = ", division
FinProceso

Proceso Operaciones_Y_Comparaciones
    Definir numero1, numero2 Como Real
    Definir suma, resta, multiplicacion, division Como Real
	
    Escribir "Introduce el primer número:"
    Leer numero1
	
    Escribir "Introduce el segundo número:"
    Leer numero2
	
    suma = numero1 + numero2
    resta = numero1 - numero2
    multiplicacion = numero1 * numero2
    division = numero1 / numero2
	
    Escribir "Resultados:"
    Escribir "Suma: ", suma
    Escribir "Resta: ", resta
    Escribir "Multiplicación: ", multiplicacion
    Escribir "División: ", division
	
    Si suma > multiplicacion Entonces
        Escribir "La suma es mayor que la multiplicación."
    SiNo
        Escribir "La multiplicación es mayor o igual que la suma."
    FinSi
	
    Si resta < division Entonces
        Escribir "La resta es menor que la división."
    SiNo
        Escribir "La resta es mayor o igual que la división."
    FinSi
FinProceso
