# XSD-IV-
Ejercicio 1 - Alumnos 1
Se define un esquema para un alumno con los siguientes requisitos:

El número de dirección debe ser un entero entre 0 y 500.

El teléfono puede aparecer de 0 a 5 veces.

El atributo dni debe tener 8 dígitos y una letra mayúscula.

Ejercicio 2 - Alumnos 2
Se amplía la estructura a varios alumnos.

Se permite que cada alumno tenga 1 o 2 direcciones.

Se restringe el contenido del elemento provincia a solo “Badajoz” o “Cáceres”.

Se valida igualmente el formato del dni, número de dirección y teléfonos.

Ejercicio 3 - Heladería 1
Se define una estructura de helado con los siguientes requisitos:

El primer sabor debe ser chocolate o fresa (uno de los dos, no ambos).

El segundo sabor debe ser vainilla, turrón o nata (uno solo).

Se usa un atributo fabricación de tipo fecha (xs:date).

Cada sabor almacena una cantidad entre 0 y 1000 gramos.

Ejercicio 4 - Heladería 2
Se define una estructura en la que:

Cada helado solo puede ser de fresa y chocolate o de vainilla y chocolate.

Los sabores se definen como elementos vacíos (<fresa />).

Ejercicio 5 - FAQ
Se diseña el esquema de una sección de preguntas frecuentes (FAQ):

El elemento faq contiene un único info y uno o más part.

El info incluye título, autor, y opcionalmente email, versión (validada con patrón tipo 1.0) y fecha.

Cada part tiene una o más preguntas q, formadas por qtext y su respuesta a.

Ejercicio 6 - Librería
Se crea un esquema para una librería con:

Código (número entre 1000 y 9999), dirección, teléfono, propietario y libros.

El propietario puede tener varios teléfonos.

Los teléfonos se validan con un patrón de 9 dígitos y se reutiliza el tipo definido.

Cada libro tiene título, autor, y opcionalmente formato (validado con enumeración), año, precio y cantidad.
