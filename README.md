Parte 1: Estructura Principal de un Programa
PSEINT:

pseint
Copiar código
Algoritmo CalculoAnios100
    Escribir "Introduzca su nombre:"
    Leer nombre
    Escribir "¿Cuántos años tiene actualmente?"
    Leer edad

    anio_actual <- 2024
    anio_100 <- anio_actual + (100 - edad)

    Escribir "Hola ", nombre, ". El año en que cumplirás 100 años será ", anio_100
FinAlgoritmo

Python:

python
Copiar código
# Programa para determinar el año en que cumplirás 100 años
nombre = input("Introduzca su nombre: ")
edad = int(input("¿Cuántos años tiene actualmente? "))

anio_actual = 2024
anio_100 = anio_actual + (100 - edad)

print(f"Hola {nombre}. El año en que cumplirás 100 años será {anio_100}")


Parte 2: Tipos de Datos, Constantes y Variables
PSEINT:

pseint
Copiar código
Algoritmo EjemploVariables
    Const porcentaje_iva = 0.21
    Definir precio_base Como Real
    Definir precio_final Como Real
    Definir descripcion Como Cadena

    precio_base <- 150.75
    descripcion <- "Precio con IVA"

    precio_final <- precio_base * (1 + porcentaje_iva)

    Escribir descripcion
    Escribir "El precio base es: ", precio_base
    Escribir "El precio final con IVA es: ", precio_final
FinAlgoritmo


Python:

python
Copiar código
# Declaración de tipos de datos y constantes
PORCENTAJE_IVA = 0.21
precio_base = 150.75
descripcion = "Precio con IVA"

# Cálculo del precio final
precio_final = precio_base * (1 + PORCENTAJE_IVA)

print(descripcion)
print(f"El precio base es: {precio_base}")
print(f"El precio final con IVA es: {precio_final}")
Parte 3: Operaciones Básicas y Expresiones
PSEINT:



Algoritmo OperacionesYComparaciones
    Definir numero1, numero2 Como Real
    Definir suma, diferencia, producto, cociente Como Real

    Escribir "Ingrese el primer número:"
    Leer numero1
    Escribir "Ingrese el segundo número:"
    Leer numero2

    suma <- numero1 + numero2
    diferencia <- numero1 - numero2
    producto <- numero1 * numero2

    Si numero2 <> 0 Entonces
        cociente <- numero1 / numero2
    Sino
        Escribir "Error: División por cero"
        cociente <- 0
    FinSi

    Escribir "Suma: ", suma
    Escribir "Diferencia: ", diferencia
    Escribir "Producto: ", producto
    Escribir "Cociente: ", cociente

    Si suma < producto Entonces
        Escribir "La suma es menor que el producto"
    Sino
        Escribir "La suma no es menor que el producto"
    FinSi
FinAlgoritmo


Python:

python
Copiar código
# Solicitar dos números al usuario
numero1 = float(input("Ingrese el primer número: "))
numero2 = float(input("Ingrese el segundo número: "))

# Realizar operaciones aritméticas
suma = numero1 + numero2
diferencia = numero1 - numero2
producto = numero1 * numero2

# Manejo de división por cero
if numero2 != 0:
    cociente = numero1 / numero2
else:
    print("Error: División por cero")
    cociente = None

# Mostrar resultados
print(f"Suma: {suma}")
print(f"Diferencia: {diferencia}")
print(f"Producto: {producto}")
if cociente is not None:
    print(f"Cociente: {cociente}")

# Comparación lógica
if suma < producto:
    print("La suma es menor que el producto")
else:
    print("La suma no es menor que el producto")
        
