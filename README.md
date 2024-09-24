# Pr-en-clase-temperatura-fahrenheit
Alvaro Campechano Estrada 3W

print(" ")
print("Alvaro Campechano practica en clase en donde se solicite el ingreso de una temperatura en escala fahrenheit y muestre el equivalente en grados celsius")
print(" ")

# Programa para convertir grados Fahrenheit a Celsius

# Función para convertir Fahrenheit a Celsius
def fahrenheit_a_celsius(fahrenheit):
    # Aplicamos la fórmula de conversión
    celsius = (5/9) * (fahrenheit - 32)
    return celsius

# Solicitar al usuario que ingrese la temperatura en Fahrenheit
entrada = input("Ingrese la temperatura en grados Fahrenheit (puede incluir decimales): ")

try:
    # Convertir la entrada a un número decimal
    fahrenheit = float(entrada)
    
    # Llamar a la función para obtener el equivalente en Celsius
    celsius = fahrenheit_a_celsius(fahrenheit)
    
    # Mostrar el resultado al usuario
    print(f"{fahrenheit} grados Fahrenheit son equivalentes a {celsius:.2f} grados Celsius.")
except ValueError:
    # Manejar el caso en que la entrada no sea un número válido
    print("Por favor, ingrese un número válido.")

    ![image](https://github.com/user-attachments/assets/490f5cc7-eca8-4330-aab4-a96545a73570)
