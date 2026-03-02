# Generacion-de-mundos-de-terraria-DSI

https://www.overleaf.com/7729411376hhjrrdnhftjp#721f86

## 1.
### Organización
Venderle el producto a Re-Logic pa que lo meta en Terraria.


### Misión
Empresa de desarrollo de videojuegos. Su misión es mantener el Terraria, pues es el juego más grande que tienen. También si quieren pueden hacer otros juegos (por ver). Objetivos son mantener el terraria, ganar dinero, mantener jugadores, etc. El valor principal de Re-Logic es mantener la calidad de sus productos, en especial Terraria.

### Problema y Solucion
Mejorar la experiencia de los jugadores a la hora del jugar al Terraria.
La generación de terreno base del juego Terraria, aunque en la mayoría de veces funciona, es común que existan casos donde el terreno generado, al que llamamos mundo, no es óptimo para la jugabilidad (terrenos mal generados o sin sentido, terrenos aburridos, terrenos extremadamente difíciles...)

El problema que soluciona este generador de mundos es que, acorde a las especificaciones del jugador, se pueda generar un terreno personalizado, adaptado a los gustos del usuario y que evite los problemas anteriormente mencionados. 

// Podemos dividir este problema en dos: problemas de generación de mundo y problemas de jugabilidad.

### Oportunidades
Este generador puede generar contenido nuevo y personalizado al mundo de terraria, que no existe en el juego base. 

### Factores externos
- Actualización del juego base que afecten a la generación del mundo
- Conflicto con otros mods
- Conflictos con EULA o derivados? -> no se puede vender, debe ser gratuito
- Problemas de portabilidad con otras consolas donde esté presente Terraria

### Escala de valores
Aumentar la cantidad de jugadores, mejorar la jugabilidad, aumentar el tiempo de juego promedio, aumentar ventas


## 2.

Hay que hablar de Re-Logic lamentablemente. 

### estructura 
Es una empresa pequeña, solamente son 11 trabajadores, entre ellos el CEO de la empresa Andrew. Son 3 programadores, con lo cual no tienen mucha fuerza de desarrollo. 

### procesos y recursos 
Como se hace la generacion, que recursos usa (material, codigos, patentes...) y cuales se podrían añadir manteniendo el esquema general del juego (texturar, contexto, etc)

### personal
Hablar de los desarrolladores y equipo directivo + nosotros 

### conocimiento
Buscar al pavo con el que hay que hablar que tiene toda la info de generacion (lead developer?)

### cultura y potencial
Como trabajaremos, como nos comunicaremos con ellos, etc. flujo de trabajo

## 3.
Descomponer en tareas las movidas que vamos a hacer.
Proporcionar endpoints al usuario para que pueda modificar la generacion de terreno a una experiencia más personalizada.
Nombrar los procesos que vamos a hacer. (hacerlo en el 2?) 

## 4. 
Asignar recursos a tareas. 

## 5. 
Tiene que ir de seguida 
La inclusión de un sistema de generación de mundo mas detallado y con mayor personalización no mostrara un beneficio económico directo,en las primeras partidas de la gran mayoría de jugadores este sistema probablemente no sería usado(sin haber experimentado el juego dificilmente van a ver la necesidad de cambiar la experiencia),su beneficio principal se encuentra en los jugadores que lleven más tiempo y busquen experiencias nuevas,más ajustadas a sus gustos y necesidades,pudiendo generar beneficios adicionales a futuro gracias a criticas mas positivos y mayor confianza de los jugadores hacia la empresa para sus futuros juegos.
Se estima un total de 23 semanas para realizar analisis del contexto,modelo conceptual,diseño,implementacion y pruebas (3,6,4,8,2 semanas respectivamente),con 5 dias a la semana 8 horas al dia repartiendo por trabajo da: 520 horas para el ingeniero de conocimiento a 25€ la hora, 400 horas para el programador junior a 15€ la hora y 560 horas para le programador senior a 35€ la hora,pare un total de 38000€ en salarios,siendo un proyecto que no requiere herramientas especializadas (usuarios particulares han podido crear modificaciones al juego sin grandes cantidades de recursos además de su tiempo) ni contratar personas externo para pruebas (es posible dar acceso anticipado para que los usuarios realizen las pruebas finales) se puede estimar unos gastos adicionales de 12000€ donde entran comidas,aperitivos,licencias para algunos programas y otros gastos imprevistos para un total de 50000€.
Es posible utilizar soluciones alternativas,aprovechando más el personal de la empresa para acelerar el proceso pero esto ocasionaría retrasos en otros proyectos especialmente en un equipo tan pequeño como es el de Re-Logic,al usar una solución donde el desarrollo es realizado por una empresa externa(nosotros) no se requiere cambios en la empresa o su estructura.

La tarea ha desarrollar por el SBC muestra una complejidad elevada,múltiples reglas que interactuan una con la otra para definir como se debe generar el mundo mientras se tienen en cuenta las peticiones del usuario supone una carga para el mismo aunque no requiere ninguna técnica nueva,además no puede tardar demasiado ni consumir grandes cantidades de recursos sería necesario que cualquier dispositivo con suficiente potencia para jugar al juego puede usar esta función.
La funcionalidad ha de integrarse correctamente con los sistemas ya existentes para el juego y no desentonar con su interfaz con respecto al resto de menus,no necesita ser extremadamente sencilla,esta es una funcionalidad adicional que principalmente sirve para gente que sabe que quiere,aunque tampoco debería ser tan complicada de usar que requiera leer documentación para entender como funciona,adicionalmente ya existen algunas opciones de creación de mundo que permiten escojer algunas opciones básicas como puede ser el tamaño del mundo,así que en esta creación de mundos se incorporaría este sistema.
Las opiniones de los usuarios sobre el nuevo sistema además del porcentaje de uso mostrara como de exitoso ha sido el proyecto.

El personal de Re-Logic muestra un compromiso alto puesto que una mejora en la generación de mundos puede suponer un aumento en la satisfacción de sus jugadores además de permitirles probar nuevas opciones de generación de mundo con mayor facilidad,el recurso principal a utilizar es el conocimiento de generación de mundo,ya sea de un empleado o la documentación,las expectativas del proyecto son adecuadas,ideas similares en otros juegos han demostrado gran utilidad y mayor satisfacción entre los jugadores.

	Se propone trabajar sobre el área de generación de mundos,al ser esta una área que es la mejora y configuración de contenido procedural y no la creación de contenido nuevo. La solución entonces es la creación de un sistema que permita al jugador configurar parámetros de creación para el terreno y sus estructuras,se puede automatizar las tareas 3 y 4,siendo estas las tareas relacionadas con transformar los parámetros introducidos a reglas para el algoritmo y la creación de dicho algoritmo.








