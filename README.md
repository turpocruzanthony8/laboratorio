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
