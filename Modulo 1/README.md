######Introducción a la automatización
####Jesús Manuel Razo

La automatización surge ante la necesidad de reducir tiempos y esfuerzo de pruebas que conllevarían escenarios complicados para la ejecución manual,
que pueden ser repetitivos como las regresiones o bien donde las tareas son monótonas.

La automatización ofrece varias ventajas más además de reducir las limitantes humanas, como poder ejecutar pruebas en ventanas muy cortas sin sacrificar la complejidad y contar con feedback veloz gracias a los reportes automáticos, 
además de que el proceso se puede ir puliendo o mejorando sumando consistencia.

Por otro lado, no se puede solucionar todo con la automatización, pues el costo inicial es elevado, tanto en recursos como en conocimientos. Además el sistema está sujeto al expertise de quien elabora o lanza, 
adicionalmente se requiere mantenimiento continuo para evolucionar junto con el sistema a probar. También está
sujeta a que podría pasar por alto detalles que una persona puede detectar o idear al pensar fuera de la caja, 
sumando que no cubre todos los tipos de prueba debido a los puntos anteriores.

Se piensa en automatizar cuando nos enfrentamos a flujos con pocos o nulos cambios, que son validaciones constantes, monótonas
sumando la variable de costo en tiempo y recursos. Cuando estos criterios se reúnen se opta por automatizar. 
Hablando de tipos de prueba, usualmente las regresiones y los smoke test son excelentes candidatos para automzwtizar debido a su naturaleza.
Sin embargo es importante recordar que toda prueba que paermanezca sin cambios está sujeta a sufrir de la paradoja del pesticida,
por lo que la supervisión humana no deja de ser un componente importante.

La automatización se lleva a cabo gracias a un conjunto de herramientas que son capaces de interpretar el front-end
y localizar las soluciones.
Primero se necesita un lenguaje de programación determinado con el que las herramientas van a correr, hablamos de los frameworks 
de automatización que van leyendo el código de la página para ir localizando las secciones de interés con las cuales 
se suele interactuar a base de scripts, usualmente en javascript.

Mediante estos scripts se pueden dar órdenes para que el framework ponga foco, lleve a cabo acciones y tome evidencia e incluso gestione
parte de la documentación.

Es posible conectar con agentes de gestión como JIRA.






