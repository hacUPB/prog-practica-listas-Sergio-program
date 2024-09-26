### Cifrado césar:
- Empieza por recibir un mensaje original.
- Recibe un número que indica el desplazamiento.
- Se expresa el mensaje original como una cadena de numeros según la tabla ASCII.
- Se suma el número ingresado a cada número que representa el mensaje original.
- Se analiza cada nuevo número en la tabla ASCII y se pasa a caracter.
- Devuelve un mensaje igual al original, pero desplazado la cantidad de veces que indica el número (Mensaje cifrado).


### Pseudocódigo:
```
Inicio 
cifrado = ""
mensaje = imprimir ("Ingrese el mensaje a cifrar") #cadena de caracteres #upper
num = imprimir ("Ingrese el número") #entero

for letra in mensaje:
    codig = ord(letra)
    if 65 <= codig <= 90 
        codig += num 
            if codig > 90:
                dif = codig - 90
                codgi = 64 + dif
    car_cif = chr(codig)
    cifrado += car_cif

imprimir ("El código cifrado es: 'cifrado'")
