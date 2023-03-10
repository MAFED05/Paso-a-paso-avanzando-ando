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

## Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
El código del segundo punto quedó algo así:

```
letra= input("ingrese una letra:")
a= ord(letra)

if a%2==0: 
    print("La letra "+ str(letra) + " pertenece al número par " + (str(a)) + " en el código ASCII")
else:
    print("La letra "+ str(letra) + " pertenece al número impar " + (str(a)) + " en el código ASCII")
```

En Visual Studio Code se tendría que ver de la siguente forma:

[![Captura-de-pantalla-2023-03-10-135954.png](https://i.postimg.cc/7LrbzJ0q/Captura-de-pantalla-2023-03-10-135954.png)](https://postimg.cc/jDvs05M1)

## Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

Para este punto, obtuve el siguiente código: 

```
b=input("Ingrese un solo carácter")
ord(b)
x=ord(b)
if x>57 or x<48:
    print("el carácter "+str(b)+" no es un dígito ")
else :
    print("el carácter "+str(b)+" es un dígito ")
```
Y en Visual Studio Code podríamos ver el código de la siguiente forma:

[![Captura-de-pantalla-2023-03-10-140407.png](https://i.postimg.cc/wvHVwv8p/Captura-de-pantalla-2023-03-10-140407.png)](https://postimg.cc/XZHdJnYH)

## Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero.

Para cada caso de debe imprimir el texto que se especifica a continuación:

+ Positivo: "El número x es positivo"
+ Negativo: "El número x es negativo"
+ Cero (0): "El número x es el neutro para la suma"

El código quedó de la siguiente manera:

```
b : float
b = float(input("Ingrese un número"))
if b > 0 :
    print ("El número " + str(b)+ " es positivo")
elif b < 0 :
    print ("El número " + str(b)+ " es negativo")
elif b==0 : 
    print ("El número " + str(b)+ " es neutro para la suma")
 
 ```
Y en Visual Studio Code se podría ver de la siguiente forma:

[![Captura-de-pantalla-2023-03-10-141207.png](https://i.postimg.cc/vBq0Dskw/Captura-de-pantalla-2023-03-10-141207.png)](https://postimg.cc/cg3R5VdF)

Ya casi acabamos...
Pero para lograr finalizar debemos continuar con el siguiente punto que es:

Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

```
x = float (input("Ingrese la coordenada en x del centro de la circunferencia"))
y = float (input("Ingrese la coordenada en x del centro de la circunferencia"))
radio = float(input("Ingrese el radio de la circunferencia"))
a = float (input("Ingrese la coodenada en x del punto R2"))
b = float (input("Ingrese la coordenada en y del punto R2"))
if((a-x)**2 + (b-y)**2 <= radio**2):
    print ("El punto en R2 " + str(a) + ", " + str(b) + " pertenece al interior de la circunferencia ")
else: 
    print ("El punto en R2 " + str(a) + ", " + str(b) + " no pertenece al interior de la circunferencia ") 
 ```
    
Y en Visual Studio Code, podríamos obtener algo así:

[![Captura-de-pantalla-2023-03-10-141726.png](https://i.postimg.cc/2SLyK7rQ/Captura-de-pantalla-2023-03-10-141726.png)](https://postimg.cc/TKGTymy1)

Y listo, ahora si vamos con el punto final:

## Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

Para este punto obtuve el siguiente código:

```
a: float
b: float
c: float
a= float(input("Longitud positiva del lado 1:"))
b= float(input("longitud positiva del lado 2:"))
c= float(input("longitud positiva del lado 3:"))
if a<0 or b<0 or c<0 :
    print ("Las longitudes no pueden ser negativas")
elif a+b>c and a+c>b and b+c>a :
    print (("Con las longitudes ") + str(a) + (", ") + str(b) + (", ") + str(c) + (" si podemos formar un triángulo."))
else:
    print (("Con las longitudes ") + str(a) + (", ") + str(b) + (", ") + str(c) + (" no podemos formar un triángulo."))
   
   ```
   Y finalmente en Visual Studio Code se tiene que ver de la siguiente forma:
   
  [![Captura-de-pantalla-2023-03-10-142124.png](https://i.postimg.cc/PJZhM2mJ/Captura-de-pantalla-2023-03-10-142124.png)](https://postimg.cc/V0Y3f9ZP)
  
  Y listooo, eso sería todo por hoy, espero que sea lo suficientemente claro y que les pueda servir en algo.
  
  Muchas gracias
