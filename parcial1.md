# <CENTER><span style="color:blue">Universidad de Colima
## <CENTER><span style="color:blue"> Computacion Inteligente
## <CENTER><span style="color:blue">Apuntes Primera Parcial
### <CENTER><span style="color:blue">Python
### <CENTER><span style="color:blue"> Yuli Janeth Flores Pascual
#### <CENTER><span style="color:blue"> 3"B"

# Listas #
#tambien se conocen como collection#


def Suma (a,b):
    return a + b
def Resta (a,b):
    return a - b
def Multiplicacion (a,b):
    return a * b
def Division (a,b):
    return a / b

Operaciones = Suma, Resta ,  Multiplicacion, Division

print(Operaciones[0](5,4))
print(Operaciones[1](5,4))
print(Operaciones[2](5,4))
print(Operaciones[3](5,4))

lista = [1,2,3,4,5, True, 4.5, "hola",[1,2,3]]


# es indexable 

lista[0]


def suma (a, b):
    pass
print(suma(3,4))


def operaciones (a, b):
    return [a+b,a-b, a*b, a/b]
respustas = operaciones(5,4)
print('respuestas')
w,x,y,z = operaciones (5,4)
print(w)


res_suma,_,_,_ = operaciones(5,4)
res_suma



#tuple

tupla_funciones = ("suma,resta, multiplicacion, divison")
print(tupla_funciones [1](5, 4))
tupla = [1,2,3,4,5, True, 4.5, "hola",[1,2,3]]


 # otro
def suma(a: int, b: int)->int:
    return a + b 


def operacion (a: int, b: int ) -> (int, int):
    return (a + b , a - b)

(a,b)= operacion (5, 6)
a,b = operacion(6,6)
print(a , b)
 


#range
numeros = range(10)
print(numeros)


for i in numeros:
    print(i, end= '')


    numeros = range (5,10)
    numeros

    numeros_pares = range(2,11,2)
    for par in numeros_pares:
        print(par, end='')


        for item in range (2, 11,2):
            print(item,end='') 


lista[3,6,7,48,34,64,89]
max(lista)


min(lista)


sum(lista)






lista.sport(reversed,True)
lista

while True:
    print("nMi Calculadora")
    print("1. Suma")
    print("2. Resta")
    print("3.Multiplicacion")
    print("4. Division")
    print("5.Salir")

    opcion = input("Selecciona una opcion: ")

    if opcion == '5':
    print ()
    break


num = ""
n = int(input("dame un numero entero positivo"))
if n%2 == 0:
    num = "par"
else:
    num = "impar"

num


n = int(input("Dame un numero entero positivo"))
(num:= "par" if n%2 == 0 else "impar")
num


#### casting
Conversion de tipos 
num_str ="3"
num_int = int(num_str)
print (f"num_int: {num_int}")

num_float = 3.14
num_int =  int(num_float)
print(f"num_int: {num_int}")

num_str = str (num_float)
res_tupla = (num_str, num_int)
print(f"num_str : () ")




#### mi_set = {1,2,3,3,3,3,3}
#### mi_set

#### data = [1,2,3,4,5,6,7,8,9,10,1,2,1,2,1,2]
#### list(set(data))


### True
### False 
 if 5 > 4:
    print(True)
    print(False)
    print('5 > 7')

    nombre: str  = "Hugo"
    print(nombre)
    print(type(nombre))
    nombre.capitalize()
    nombre.upper()


    num: int = 10
    pi:float = 3.1416
     """


""" print(5-4)
print(5+4)
print(5*4)
print(5/4)
print(5%4)
print(5//4)
print(5**4) """

""" print(True and False)
print(True or False)
print(not False)

n1: int = 10
n2: int = 20
if n1 > n2:
    print(f"{n1} > {n2}")
