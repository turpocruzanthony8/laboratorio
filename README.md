print(1+6)
print(5.3/8)
print(ULaSalle)
#la edad inicial es 18
edad = 18
print(edad)

#la edad final es 21
edad = 21
print(edad)

#variable nombre
nombre = 'Cristina'

print(nombre,

'tiene '

,edad,

' años')

a=
”yo “ a=

”U La Salle”

b=
“estudio ” print(a*5)
c=
“en “
d=
“U La Salle”
print(a+b+c+d)

x=5
print(type(x))
# Programa para calcular la estatura de Pedro
def calcular_estatura():
    estatura_maria = float(input("Introduce la estatura de María en cm: "))
    estatura_pedro = estatura_maria + 53  # Pedro le lleva 53 cm
    print(f"La estatura de Pedro es: {estatura_pedro} cm")

calcular_estatura()

# Programa para calcular las cajas que debe pedir José
def calcular_pedido_chocolates():
    chocolates_diarios = int(input("¿Cuántos chocolates se producirán diariamente? "))
    chocolates_totales = chocolates_diarios * 7  # producción semanal
    cajas_necesarias = chocolates_totales // 12  # cada caja tiene 12 chocolates
    if chocolates_totales % 12 != 0:
        cajas_necesarias += 1  # Si hay chocolates sobrantes, se necesita una caja más
    print(f"José debe pedir {cajas_necesarias} cajas de chocolates.")

calcular_pedido_chocolates()

import math

# Programa para calcular la hipotenusa
def calcular_hipotenusa():
    cateto_1 = float(input("Introduce el valor del primer cateto: "))
    cateto_2 = float(input("Introduce el valor del segundo cateto: "))
    hipotenusa = math.sqrt(cateto_1**2 + cateto_2**2)  # Teorema de Pitágoras
    print(f"La hipotenusa del triángulo rectángulo es: {hipotenusa:.2f}")

calcular_hipotenusa()

# Programa para convertir Fahrenheit a Celsius
def convertir_a_celsius():
    fahrenheit = float(input("Introduce la temperatura en grados Fahrenheit: "))
    celsius = (fahrenheit - 32) * 5 / 9  # Fórmula de conversión
    print(f"{fahrenheit} grados Fahrenheit equivalen a {celsius:.2f} grados Celsius.")

convertir_a_celsius()

• Prueba las siguientes instrucciones:
• print('AND')
• print('True and True =>'

, True and True)

• print('True and False =>'

, True and False)

• print('False and True =>'

, False and True)

• print('False and False =>'

, False and False)

• print(10 > 5 and 5 < 10)
• print(10 > 5 and 5 > 10)

stock = input('Ingrese el numero de stock => ')
stock = int(stock)
print(stock >= 100 and stock <= 1000)
• print('OR')
• print('True or True =>'

, True or True)

• print('True or False =>'

, True or False)

• print('False or True =>'

, False or True)

• print('False or False =>'

, False or False)

role = input('Digita el rol => ')
print(role == 'admin' or role == 'seller')

print(not True)
• print(not False)
• print('NOT AND')
• print('not True and True =>'

, not (True and True))

• print('not True and False =>'

, not (True and False))

• print('not False and True =>'

, not (False and True))

• print('not False and False =>'

, not (False and False))

• stock = input('Ingrese el numero de stock => ')
stock = int(stock)
print(not (stock >= 100 and stock <= 1000))

# Verificar si el número es 31
def verificar_numero():
    numero = int(input("Ingresa un número: "))
    if numero == 31:
        print("El número es 31.")
    else:
        print("El número no es 31.")

verificar_numero()

# Verificar el peso promedio según la estatura
def verificar_peso_promedio():
    estatura = float(input("Introduce tu estatura en metros: "))
    peso_minimo = (estatura - 1) * 100 + 50 - 5  # Estatura - 1 metro, rango +-5 kg
    peso_maximo = (estatura - 1) * 100 + 50 + 5
    peso_usuario = float(input(f"Introduce tu peso (en kg): "))

    if peso_minimo <= peso_usuario <= peso_maximo:
        print(f"Tu peso está en el rango adecuado de {peso_minimo} kg a {peso_maximo} kg.")
    else:
        print(f"Tu peso no está en el rango adecuado. El rango es de {peso_minimo} kg a {peso_maximo} kg.")

verificar_peso_promedio()

# Verificar edades de los usuarios
def verificar_edades():
    edad1 = int(input("Introduce la primera edad: "))
    edad2 = int(input("Introduce la segunda edad: "))

    if edad1 < 18 or edad2 < 18:
        print("Hay un menor de edad.")
    else:
        print("Todos son mayores de edad.")

verificar_edades()

# Verificar si el número es par o impar
def verificar_par_impar():
    numero = int(input("Introduce un número: "))

    if numero % 2 == 0:
        print("El número es par.")
    else:
        print("El número es impar.")

verificar_par_impar()

# Programa para dividir dos números y verificar si la división es exacta
def dividir_numeros():
    num1 = int(input("Introduce el primer número entero: "))
    num2 = int(input("Introduce el segundo número entero: "))

    if num2 == 0:
        print("Error: No se puede dividir por cero.")
    else:
        division = num1 / num2
        if num1 % num2 == 0:
            print(f"La división es exacta. El resultado es {division}.")
        else:
            print(f"La división no es exacta. El resultado es {division}.")

dividir_numeros()

# Programa mejorado para dividir dos números y verificar si la división es exacta
def dividir_numeros_mejorado():
    num1 = int(input("Introduce el primer número entero: "))
    num2 = int(input("Introduce el segundo número entero: "))

    if num2 == 0:
        print("Error: No se puede dividir por cero.")
    else:
        division = num1 / num2
        if num1 % num2 == 0:
            print(f"La división es exacta. El resultado es {division}.")
        else:
            print(f"La división no es exacta. El resultado es {division:.2f}.")

dividir_numeros_mejorado()

# Programa para verificar si el mayor es múltiplo del menor
def verificar_multiplo():
    num1 = int(input("Introduce el primer número entero: "))
    num2 = int(input("Introduce el segundo número entero: "))

    if num1 > num2:
        mayor = num1
        menor = num2
    else:
        mayor = num2
        menor = num1

    if mayor % menor == 0:
        print(f"{mayor} es múltiplo de {menor}.")
    else:
        print(f"{mayor} no es múltiplo de {menor}.")

verificar_multiplo()

# Programa mejorado para verificar si el mayor es múltiplo del menor, sin números negativos ni cero
def verificar_multiplo_mejorado():
    num1 = int(input("Introduce el primer número entero (positivo): "))
    num2 = int(input("Introduce el segundo número entero (positivo): "))

    if num1 <= 0 or num2 <= 0:
        print("Error: Ambos números deben ser positivos.")
    else:
        if num1 > num2:
            mayor = num1
            menor = num2
        else:
            mayor = num2
            menor = num1

        if mayor % menor == 0:
            print(f"{mayor} es múltiplo de {menor}.")
        else:
            print(f"{mayor} no es múltiplo de {menor}.")

verificar_multiplo_mejorado()

# Programa para verificar si un año es bisiesto
def verificar_bisiesto():
    año = int(input("Introduce un año: "))

    if (año % 4 == 0 and año % 100 != 0) or (año % 400 == 0):
        print(f"{año} es un año bisiesto.")
    else:
        print(f"{año} no es un año bisiesto.")

verificar_bisiesto()

while True:
print('se ejecuto')
• counter = 0
while counter < 10:
counter += 1
print(counter)

• counter = 0
while counter < 20:
counter += 1
if counter == 15:
break
print(counter)

• counter = 0
while counter < 20:
counter += 1
if counter < 15:
continue
print(counter)

# Preguntar si desea continuar con el programa (respuesta "sí")
def continuar_si():
    while True:
        respuesta = input("¿Deseas continuar con el programa? (sí/no): ")
        if respuesta == "sí":
            print("Continuando con el programa...")
        else:
            print("Finalizando el programa...")
            break

continuar_si()

# Preguntar si desea terminar el programa (respuesta "SI")
def terminar_si():
    while True:
        respuesta = input("¿Deseas terminar el programa? (SI/no): ")
        if respuesta == "SI":
            print("Terminando el programa...")
            break
        else:
            print("Continuando con el programa...")

terminar_si()

# Preguntar si desea continuar con el programa (respuestas "S" o "s")
def continuar_con_s():
    while True:
        respuesta = input("¿Deseas continuar con el programa? (S/s para continuar): ")
        if respuesta == "S" or respuesta == "s":
            print("Continuando con el programa...")
        else:
            print("Finalizando el programa...")
            break

continuar_con_s()

# Preguntar si desea terminar el programa (respuestas "S" o "s")
def terminar_con_s():
    while True:
        respuesta = input("¿Deseas terminar el programa? (S/s para continuar): ")
        if respuesta == "S" or respuesta == "s":
            print("Continuando con el programa...")
        else:
            print("Terminando el programa...")
            break

terminar_con_s()

# Solicitar una contraseña y volver a pedirla hasta que coincidan
def verificar_contraseña():
    while True:
        contraseña1 = input("Introduce tu contraseña: ")
        contraseña2 = input("Vuelve a introducir tu contraseña: ")
        if contraseña1 == contraseña2:
            print("Contraseñas coinciden. Acceso permitido.")
            break
        else:
            print("Las contraseñas no coinciden. Intenta de nuevo.")

verificar_contraseña()

# Simulación de una alcancía
def alcancia():
    objetivo = float(input("¿Cuánto deseas ahorrar? (Objetivo): "))
    total_ahorrado = 0.0

    while total_ahorrado < objetivo:
        cantidad = float(input("Introduce la cantidad que deseas ahorrar: "))
        total_ahorrado += cantidad
        print(f"Total ahorrado: {total_ahorrado} (Objetivo: {objetivo})")

    print(f"¡Felicidades! Has alcanzado tu objetivo de ahorrar {total_ahorrado}.")

alcancia()

# Sumar los primeros 10 enteros pares
def sumar_pares():
    total = 0
    for i in range(2, 21, 2):  # Comienza en 2 y avanza de 2 en 2 hasta 20
        total += i
    print(f"La suma de los 10 primeros enteros pares es: {total}")

sumar_pares()

# Calcular el promedio de las calificaciones
def promedio_clase():
    calificaciones = []
    for i in range(10):  # Para 10 estudiantes
        calificacion = int(input(f"Introduce la calificación del estudiante {i+1}: "))
        calificaciones.append(calificacion)

    promedio = sum(calificaciones) / len(calificaciones)
    print(f"El promedio de la clase es: {promedio:.2f}")

promedio_clase()

# Contar cuántas 'a' hay en la frase
def contar_letras_a():
    frase = input("Introduce una frase: ")
    contador_a = frase.lower().count('a')  # Convertimos la frase a minúsculas para contar todas las 'a'
    print(f"La cantidad de letras 'a' en la frase es: {contador_a}")

contar_letras_a()

# Mostrar los múltiplos de 3 hasta el número que el usuario indique
def multiplos_de_3():
    limite = int(input("Introduce un número límite: "))
    for i in range(3, limite + 1, 3):
        print(i, end=" ")
    print()  # Para salto de línea al final

multiplos_de_3()

# Verificar que el segundo número sea mayor que el primero
def pedir_numeros():
    num1 = int(input("Introduce el primer número entero: "))
    num2 = int(input("Introduce el segundo número entero: "))

    while num2 <= num1:
        print("El segundo número debe ser mayor que el primero.")
        num2 = int(input("Introduce nuevamente el segundo número entero: "))

    print(f"Los dos números ingresados son: {num1} y {num2}")

pedir_numeros()

# Pedir números enteros mientras sean cada vez más grandes
def pedir_numeros_crecientes():
    num_anterior = int(input("Introduce el primer número: "))

    while True:
        num_actual = int(input("Introduce un número mayor que el anterior: "))
        if num_actual > num_anterior:
            num_anterior = num_actual
        else:
            print("El número debe ser mayor que el anterior. Fin del programa.")
            break

pedir_numeros_crecientes()

text = 'En ULaSalle sabemos programar en
Python'
print('ULaSalle' in text)
print('Visual' in text)
if 'ULaSalle' in text:
print('Elegiste bien!!')
else:
print('Mala elección')
size = len(text)
print(size)

print(text)
print(text.upper())
print(text.lower())
print(text.count('a'))
print(text.swapcase())
print(text.startswith('En'))
print(text.endswith('Arduino'))
print(text.replace('Python', 'Kotlin'))
text_2 = 'somos creadores de tecnología'
print(text_2)
print(text_2.capitalize())
print(text_2.title())
print(text_2.isdigit())
print("398".isdigit())

text = "En ULaSalle aprendemos Python"
print(text[0])
print(text[1])
# print(text[999])
size = len(text)
print('size => ',size)
print(text[size - 1])
print(text[-1])

print(text[0:9])
print(text[10:20])
print(text[:10])
print(text[3:-1])
print(text[3:])
print(text[:])
print(text[10:20:1])
print(text[10:20:2])
print(text[::2])

# Lista inicial
letters = ["A", "B", "C", "D", "E", "F"]

# 1. Agregar la letra 'G' al final de la lista
letters.append("G")

# 2. Reemplazar la letra en la posición 0 con la letra 'Z'
letters[0] = "Z"

# 3. Eliminar la letra 'C' de la lista
letters.remove("C")

# 4. Imprimir la lista resultante al revés
print(letters[::-1])

# Escriba un programa que pida las notas de un grupo,
# Listas para almacenar las notas aprobadas y desaprobadas
notas_aprobadas = []
notas_desaprobadas = []

# Iniciar el ciclo para ingresar notas
while True:
    # Solicitar la nota del estudiante
    try:
        nota = float(input("Ingrese la nota del estudiante: "))
    except ValueError:
        print("Por favor, ingrese un número válido para la nota.")
        continue

    # Clasificar la nota en aprobada o desaprobada
    if nota >= 60:
        notas_aprobadas.append(nota)
    else:
        notas_desaprobadas.append(nota)

    # Preguntar si desea seguir ingresando notas
    continuar = input("¿Desea ingresar otra nota? (Sí/SÍ/sí para continuar): ").strip().lower()

    # Si la respuesta no es Sí/SÍ/sí, salir del bucle
    if continuar not in ['sí', 'si']:
        break

# Mostrar las listas de notas aprobadas y desaprobadas
print("\nNotas Aprobadas:", notas_aprobadas)
print("Notas Desaprobadas:", notas_desaprobadas)

# Pedir el nombre de 5 asignaturas y
# Lista vacía para almacenar los nombres de las asignaturas y las notas
asignaturas = []
notas = []

# Pedir los nombres de las asignaturas y sus notas
for i in range(5):
    asignatura = input(f"Ingrese el nombre de la asignatura {i + 1}: ")
    nota = float(input(f"Ingrese la nota de la asignatura {asignatura}: "))

    # Guardar la asignatura y su nota en las listas correspondientes
    asignaturas.append(asignatura)
    notas.append(nota)

# Mostrar los resultados
for i in range(5):
    print(f"En la asignatura {asignaturas[i]} sacó {notas[i]}.")


#Un estacionamiento cobra S/3.00 p
def calcular_cargo_estacionamiento(horas):
    if horas <= 1:
        return 3.00  # Si es 1 hora o menos, cobra 3.00
    elif horas <= 23:
        cargo = 3.00 + (horas - 1) * 0.50  # Cobra S/0.50 por cada hora extra
        return min(cargo, 12.00)  # El cargo máximo es 12.00
    else:
        return 12.00  # Si son 24 horas o más, el cargo es 12.00

# Solicitar la cantidad de horas al usuario
horas = float(input("Ingrese el número de horas: "))
cargo = calcular_cargo_estacionamiento(horas)
print(f"El cargo es: S/{cargo:.2f}")

# Escriba un programa que pida las notas de un grupo,
# Listas para almacenar las notas aprobadas y desaprobadas
notas_aprobadas = []
notas_desaprobadas = []

# Iniciar el ciclo para ingresar notas
while True:
    # Solicitar la nota del estudiante
    try:
        nota = float(input("Ingrese la nota del estudiante: "))
    except ValueError:
        print("Por favor, ingrese un número válido para la nota.")
        continue

    # Clasificar la nota en aprobada o desaprobada
    if nota >= 60:
        notas_aprobadas.append(nota)
    else:
        notas_desaprobadas.append(nota)

    # Preguntar si desea seguir ingresando notas
    continuar = input("¿Desea ingresar otra nota? (Sí/SÍ/sí para continuar): ").strip().lower()

    # Si la respuesta no es Sí/SÍ/sí, salir del bucle
    if continuar not in ['sí', 'si']:
        break

# Mostrar las listas de notas aprobadas y desaprobadas
print("\nNotas Aprobadas:", notas_aprobadas)
print("Notas Desaprobadas:", notas_desaprobadas)


# Pedir el nombre de 5 asignaturas y
# Lista vacía para almacenar los nombres de las asignaturas y las notas
asignaturas = []
notas = []

# Pedir los nombres de las asignaturas y sus notas
for i in range(5):
    asignatura = input(f"Ingrese el nombre de la asignatura {i + 1}: ")
    nota = float(input(f"Ingrese la nota de la asignatura {asignatura}: "))

    # Guardar la asignatura y su nota en las listas correspondientes
    asignaturas.append(asignatura)
    notas.append(nota)

# Mostrar los resultados
for i in range(5):
    print(f"En la asignatura {asignaturas[i]} sacó {notas[i]}.")


ef loteria():
    numeros = []

    while True:
        numero = int(input("Introduce un número ganador de la lotería: "))
        numeros.append(numero)

        continuar = input("¿Quieres seguir ingresando números? (Sí/SÍ/sí): ").lower()
        if continuar != "sí":
            break

    numeros.sort()  # Ordenar la lista de menor a mayor
    print("Números ganadores ordenados:", numeros)

    boliyapa = int(input("Introduce el número de la boliyapa: "))
    numeros.append(boliyapa)

    print("Lista final con la boliyapa:", numeros)

loteria()

def abecedario_modificado():
    abecedario = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']

    # Eliminar las letras en posiciones múltiplos de 3 (considerando índice 0)
    abecedario = [letra for i, letra in enumerate(abecedario) if (i + 1) % 3 != 0]

    print("Lista resultante del abecedario:", abecedario)

abecedario_modificado()
