import math

# Función para convertir coordenadas polares a rectangulares
def polares_a_rectangulares(r, theta):
    x = r * math.cos(math.radians(theta))
    y = r * math.sin(math.radians(theta))
    return x, y

# Función para convertir coordenadas rectangulares a polares
def rectangulares_a_polares(x, y):
    r = math.sqrt(x ** 2 + y ** 2)
    theta = math.degrees(math.atan2(y, x))
    return r, theta

# Aquí se le pregunta al usuario qué tipo de coordenadas desea ingresar. 1 = Polares, 2 = Rectangulares
opcion = input("¿Deseas ingresar coordenadas polares o rectangulares? (1/2) ")

if opcion.upper() == "1":
    # Aquí s le pide al usuario las coordenadas polares
    r = float(input("Ingresa el valor de r: "))
    theta = float(input("Ingresa el valor de theta en grados: "))

    # Convierto las coordenadas polares a rectangulares
    x, y = polares_a_rectangulares(r, theta)

    # Imprimo las coordenadas rectangulares
    print(f"Las coordenadas rectangulares son: ({x}, {y})")

elif opcion.upper() == "2":
    # Aquí se le pide al usuario las coordenadas rectangulares
    x = float(input("Ingresa el valor de x: "))
    y = float(input("Ingresa el valor de y: "))

    # Convierto las coordenadas rectangulares a polares
    r, theta = rectangulares_a_polares(x, y)

    # Imprimo las coordenadas polares
    print(f"Las coordenadas polares son: ({r}, {theta} grados)")

else:
    # Si el usuario pone algo que no ses "1" o "2", muestra entonces un mensaje de error
    print("Opción inválida. Por favor ingresa '1' o '2' como respuesta.")
    #Fin del código
