---
title: Guía rápida para usar a Serbal
---

<div id="toc"></div>

# Registro

## Primer Registro

Como el proceso de validación es algo que usualmente se hace una sola vez por cuenta la guía de validación está en [este enlace](https://acamara7es.github.io/PoGoFuenla/registro)

## Cambios en los datos de la cuenta

Todos los cambios en los datos de tu registro deben hacerse a través del chat **PRIVADO** con el bot [@profSerbalBot](https://t.me/profserbalbot).

- **Cambio de nivel:** El más habitual, para actualizar tu nivel tienes que decirle al bot "_Soy nivel XX_", asegúrate de que le dices tu nivel correcto, si te pones alguno más alto y te piden captura del perfil para comprobarlo te pueden banear el registro del bot.
- **Cambio de nombre:** Si has cambiado tu nombre de entrenador debes volver a validarte, para ello usa el comando "`/newnick`" y sigue las instrucciones.
- **Cambio de color:** Para cambiar el color de tu cuenta si has utilizado el Medallón de equipos usa el comando "`/newteam`" y sigue las instrucciones.

# Nidos

## Registrar nidos

```
/addnest pokemon ubicacion
```

o

```
Registrar nido de pokemon en ubicacion
```

Al terminar de añadir el nido Serbal pedirá que envíes una ubicación para confirmar su posición y que sea más sencillo de encontrar.

## Borrar nidos

Solo pueden borrar nidos los admin y quien que lo haya registrado. La ubicación debe ser exactamente igual a la que se utilizó para registar el nido, así que se recomienda copiarla.

```
/delnest pokemon ubicacion
```

o

```
Borrar nido de pokemon en ubicacion
```

## Pedir nidos

```
/listnests
```

o

```
Lista de nidos completa
```

# Códigos de amigo

Serbal tiene una funcionalidad que permite registrar y obtener los códigos de amigo de los miembros del grupo que lo permitan.

## Registrar código de amigo

Lo primero que debes hacer es registrar tu código de amigo en el bot, para ello hay 2 formas (ambas **por privado** con el bot)

1. Compartir con Serbal directamente el mensaje de "_¡Comencemos una buena amistad..._"
2. Con el comando `/setfc` seguido de los 12 números del código (sin espacios).

## Agregar el código a la lista del grupo

Una vez que Serbal conozca tu código de amigo, si quieres incluirlo en la lista de amigos del grupo debes escribir **en el grupo** `/regfc`.

## Lista de códigos de amigo

Para pedir la lista de códigos de amigo del grupo usa el comando `/listfc`. Recuerda que solo te mostrará aquellos que hayan seguido los pasos anteriores, no el de todos los miembros.

# Llamar a los administradores

Es posible hacer llegar una notificación a todos los administradores del grupo usando un mensaje de la siguiente forma:

```
@admin mensaje
```

Para que funcione y llegue la notificación a los administradores el mensaje **debe empezar con @admin y llevar algo más** (si pones solo _@admin_ no funciona). De todas formas Serbal indicará si la mención ha sido enviada correctamente.

Te pedimos que uses esta función con cuidado y solo cuando sea necesaria, recuerda las palabras que le dijeron a Spiderman:

> Un gran poder conlleva una gran responsabilidad

# Otras funciones

## Buscador de 100IV

Serbal puede ayudarte a buscar entre tus pokemon aquellos con 100% de IV. Para ello el bot genera el texto necesario para buscar en tu lista de pokemon aquellos que pueden tener 100% de IV de una especie concreta usando el comando (se recomienda usarlo **en privado** con el bot):

```
/searchstr pokemon
```

Si el pokemon tiene alguna forma diferente (Ej: Deoxys o los Alola) debes ponerla después del nombre del pokemon (`deoxys ataque` o `marowak alola`)  
**Importante**: Que un pokemon aparezca al hacer la búsqueda en el juego con el texto que devuelve el comando no garantiza que sea 100%, para ello tendrás que recurrir a la valoración del líder del equipo o a apps externas, pero si no aparece es que no puede ser 100%.

## Tablas integradas

El bot dispone de una importante cantidad de "tablas" o infografías sobre el juego, algunas mejores o más útiles que otras. En [este enlace](https://xblau.com/serbal/tables) podéis ver todas las disponibles, os recomendamos usarlas **en privado** con el bot para no saturar el grupo.

## Quién es... y Está aquí...

Los pongo juntos porque están muy relacionados. Con el comando `Quien es` o `/whois` puedes obtener información de un jugador como su nombre de entrenador, su color, nivel y el código de amigo si lo tiene registrado. Se puede usar de 2 formas, junto con el nombre de entrenador `Quien es mejorEntrenador`o respondiendo a un mensaje de la persona sobre la que quieras preguntar.

Con el comando `Esta aqui NombreEntrenador` o `/ishere NombreEntrenador` podrás saber si el entrenador que buscas se encuentra en el grupo en el que estás preguntando y le mencionará para que os podáis poner en contacto por privado (muy útil por ejemplo para acordar subidas de amistad, por ejemplo).

## Buscador de anclado

A veces ocurre que el mensaje anclado "_desaparece_" para algunos usuarios. Si alguna vez te ocurre y necesitas consultarlo solo tienes que poner en el grupo:

```
Serbal, anclado
```

Y te responderá citando el último mensaje anclado que conozca. Utiliza esto solo en el grupo de charla, si has perdido el anclado del grupo de raids pregunta en el grupo de charla cómo recuperarlo.
