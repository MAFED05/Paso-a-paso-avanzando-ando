# Paso a paso avanzando ando

Buen día, hoy les vengo a mostrar como realicé el reto #5 de la clase de programación. Se sufrió pero se logró.

## Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
Para este primer punto el código quedó algo así.

``` 
b : int
b = int(input("Ingrese un número entero"))
if b == 97 :
    print ("El número indicado pertenece a la vocal 'a' en el código ASCII")
elif b == 101 :
    print ("El número indicado pertenece a la vocal 'e' en el código ASCII")
elif b == 105 :
    print ("El número indicado pertenece a la vocal 'i' en el código ASCII")    
elif b == 111 :
    print ("El número indicado pertenece a la vocal 'o' en el código ASCII")
elif b == 117 : 
    print ("El número indicado pertenece a la vocal 'u' en el código ASCII")
else :
    print ("El número indicado no pertenece a una vocal minúscula en el código ASCII")
    
    ``` 
    Y en Visual Studio Code lo podríamos ver algo así: 
    [![Captura-de-pantalla-2023-03-10-135305.png](https://i.postimg.cc/rpsxhrzx/Captura-de-pantalla-2023-03-10-135305.png)](https://postimg.cc/GB04t9Fm)
    
