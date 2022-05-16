# Alejandro
Universidad

"""Primera Actividad"""
minombrees="Alejandro Jose Caracas Torrealba"

print("Hola Prog1, Soy "+minombrees)
----------------------------------------------

"""Segunda Actividad"""
"""Primera parte"""

'''Tupla:'''deporte  = ( 'Futbol')
print ( "Me encanta el:" , deporte [ : ])

'''segunda parte'''

Edad = [ 2 , 7 , 58 , 7 , 45 , 26 , 10 , 8 , 56 , 57 , 97 ,
 19 , 11 , 53 , 3 , 99 , 62 , 78 , 29 , 9 , 37 , 42 , 56 , 86 , 
 28 , 86 , 95 ,26 , 49 , 67 , 21 , 815 , 67 , 10 , 58 , 512 , 24 
 , 92 , 89 , 67 , 53 , 10 , 9 , 83 , 1 , 44 , 10 , 77 , 98 , 73 , 57 ]


for indice in Edad:
    if indice ==10:
        Edad.remove( 10 )

print (Edad)

'''tercera parte'''
'''parte 1'''

'5.1 Defina Una funcion en Python que acepte el radio y devuelva el valor'
'del area de un circulo de esas dimensiones'

from math import pi

r = float(input("Digite un el numero para el radio: "))

def funcion(r):
    
    return pi * r**2

a = funcion(r)


print("El resultado es igual a: ",a)

'''parte2'''

'5.2 Defina una funcion en python que acepte 3 valores y devuelva'
'solo el maximo de los 3'

a = float(input("Digite un numero: "))
b = float(input("Digite un numero: "))
c = float(input("Digite un numero: "))

def main(a,b,c):
 
 if (a > b) and (a > c): {
 
  print("El numero mayor es: ",a)
 }
  
 if (b > a) and (b > c): {

  print("El numero mayor es: ",b)
 }
  
 if (c > a) and (c > a): {

  print("El numero mayor es: ",c)
 }

 return 

j = main(a,b,c)

'''parte3'''

'Dado a la lista de enteros, defina una funcion en python que devuelva la suma de solo'
'los valores impares de dicha lista'

numeros = [1,2,3,4,5,6,7,8,9,10]

def variable(numeros):
 
 suma_impares =0
 for numero in numeros:
    if numero % 2 != 0:
        suma_impares += numero
    

 return suma_impares

resultado = variable(numeros)
 
print("Suma de valores impares en el rango 1 a 10: ",resultado)

'''parte4'''

'Desarolle una funcion en python que acepte una variable'
'string como primer parametro y la cantidad de caracteres'
'de como segundo parametro. La funcion debe devolver un'
'nuevo string que consista en el string original y el'
'numero correcto de caracteres necesarios para que el string'
'se salga centrado. No se agregan caracteres al final del string'

frase = 'Bienvenidos'

def variable():

 print("valor original: ",frase)
 print(len(frase))
 print('{:^30}'.format(frase))

variable()
