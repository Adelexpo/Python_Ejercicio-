# Python_Ejercicio-3
Escribe un programa en la consola de python que pida al usuario su peso (en kg) 
y estatura (en metros), calcule el índice de masa corporal y lo almacene en una variable,
 e imprima por pantalla la frase Tu índice de masa corporal es donde es 
_=el índice de masa corporal calculado redondeado con dos decimales. 
Tienes que subir capturas de pantalla en una carpeta comprimida zip.

Solucion:

>>> peso = 80
>>> altura = 1.80
>>> masaCorporal= 80/1.80 ** 2
>>> masaRound = round(masaCorporal, 2)
>>> texto = "Su índice de masa corporal es de"
>>> print(texto, masaRound)
Su índice de masa corporal es de 24.69
