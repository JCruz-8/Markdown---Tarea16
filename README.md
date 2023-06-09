# Ejercicio Markdown (Apartado A)

Vamos a insertar el primer enlace a una página a la que puedes acceder siempre y buscar información de cualquier cosa.

[Google](https://www.google.com/)

¡Muy bien! Como ves, es una buena página ;).

## Mejor cosa del mundo

Aquí te voy a enseñar el mejor personaje de Dragon Ball Z. Te guste o no.
Te muestro una foto, pero te añadiré un enlace para que veas más.

Aquí la foto:

<img src= "/img/Gohan SS2.jpg" width= "300">

Y aquí el enlace:

[Más foto del mejor personaje del mundo](https://www.google.com/search?q=gohan+ssj2&client=firefox-b-d&sxsrf=AJOqlzVlUhlNTA0OdsvAn_aS18qmlHAwSA:1678867987876&source=lnms&tbm=isch&sa=X&ved=2ahUKEwjE66rQvt39AhWDSUEAHTZYB2kQ_AUoAXoECAEQAw&biw=1235&bih=953)

## Segunda cosa mejor del mundo

Como comprenderás, Gohan no es el único mejor del mundo.
Y esto no es que sea la segunda cosa mejor. Es también la mejor cosa del mundo, pero hablamos de un juego... <strong>EL</strong> juego.

Éste, en concreto:

<img src= "/img/Final Fantasy IX.jpeg" width= "600">

Por cierto, te dejo otro enlace para que aprendas sobre <strong>EL</strong> juego.

[Información del mejor juego del mundo](https://finalfantasy.fandom.com/es/wiki/Final_Fantasy_IX)

A todo esto... te he dejado algo interesante en [INFORMACIÓN sobre Final Fantasy IX](información.md)<br>
<br>
Y algo mucho más chulo en [INSTALACIÓN](instalacion.md). Pero para esto necesitar ir antes a [Información](informacion.md) :D <br>
Siéntete libre de bichear.

--------------------------------------------------------------------------------------

## Cosas Random

Como soy bondadoso y generoso, te voy a pasar un último enlace con datos curiosos random.

[Pincha aquí, curioso :)](https://www.cosmopolitan.com/es/consejos-planes/planes-ocio/a41078807/datos-curiosos-impresionar/)

--------------------------------------------------------------------------------------

Que no falte una tablita de 4x5 celdas. Eso nunca.

Aquí te la dejo:

| Personajes de Final Fantasy IX | Tipo Personaje | Tipo Arma | Habilidad Principal |
|-----------|-----------|-----------|-----------|
| Yitán | Ladrón | Daga | Ataque Sorpresa |
| Garnet | Invocadora | Cetro | Invocación |
| Vivi | Mago Negro | Bastón | Magia Negra |
| Steiner | Caballero | Espada | Ataque Físico |
| Freija | Dragón Caballero | Lanza | Salto |

Y los dos bloques de código fuente, que son muy importantes.

El primero, con un código que hemos aprendido de ejemplo en Python:

``````py
print ("\nBuenos días.")
var_edad = int(input ("\n¿Edad? "))

print (type(var_edad))

if var_edad >= 18:
    print ("¡Qué mayor!")
else:
    print ("¡Sigue creciendo!")

print()
``````

Y ahora el código que nosotros hemos creado, también en Python:

``````py
print ("¡Buenos días!\n")

var_nombre = input ("¿Cuál es tu nombre?\n")
var_edad = input ("¿Y tu edad?\n")

print(f"{var_nombre}, tu edad es:  {var_edad}")
``````
