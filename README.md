Cómo hacer un FeminIndex
Un índice de la perspectiva de género de nuestrxs candidatas y candidatos
¿Qué es el FeminIndex?
Desde Economía Femini(s)ta creamos el FeminIndex como una herramienta para mapear el compromiso de lxs políticxs en torno a los principales tópicos de la agenda de género. en el caso de Argentina, consideramos que estos temas se podían englobar en cinco categorías: derechos reproductivos, participación política y económica, violencia machista y derechos LGBT. 
Con este índice pretendimos mostrar puntualmente la posición de lxs principales candidatxs que se presentaron a las elecciones legislativas de octubre de 2017.
¿Cómo lo hicimos?
Elaboramos una serie de enunciados que expresen una postura sobre un tema de género. Este tipo de formato solo acepta las respuestas “a favor”, “se abstiene” o “en contra”, dado que apuntábamos a mostrar cuál sería la acción de un/a candidatx ante un debate así en el Congreso.
Luego preparamos un formulario de Google para enviar a lxs candidatxs, para que ellos pudieran respondernos. En los casos en los que no lo hicieron, hicimos un trabajo de investigación para rastrear las declaraciones más recientes sobre los distintos temas.
Para elaborar el formulario, utilizamos estos enunciados:
DERECHOS REPRODUCTIVOS
Lxs adolescentes pueden recibir anticonceptivos sin el permiso de sus padres.
La educación sexual debe ser parte integral de la enseñanza en todos los niveles.
El Estado debe garantizar el acceso al aborto legal, seguro y gratuito. 
PARIDAD
Es necesario aumentar el cupo femenino del 30% al 50% en las listas electivas. 
El Estado debe utilizar lenguaje inclusivo en la comunicación pública.
(En este caso, también pedimos información de cómo estaba compuesta la lista y preguntamos si estaba encabezada por una mujer).
ECONOMÍA FEMINISTA
La licencia de paternidad debe ser de al menos 1 mes.
Estoy a favor de una jubilación para las amas de casa. 
Redistribuir el trabajo doméstico no remunerado es clave para la igualdad de género.
LGBT
Es necesario implementar el cupo trans en todos los organismos del Estado.
Se pide información sobre si hay personas LGBT en la lista de candidatxs
NI UNA MENOS
El piropo callejero es una forma de acoso. 
Estoy a favor de las licencias laborales por violencia de género.
Es necesario aumentar el presupuesto para combatir la violencia de género.
Finalmente consultamos si el/la candidatx adhería a la campaña #MenstruAcción, impulsada por Economía Femini(s)ta y si la plataforma electoral contenía alguna propuesta para cerrar las brechas de género. 

¿Cómo armamos la visualización?
Una vez obtenidas las respuestas (en nuestro caso, en un google spreadsheets que emite el google forms), se pasa a ponderar las mismas. Tomando como puntaje general por área de 10 puntos, cada subpregunta tendrá que tener una ponderación para que todas sumen 10.
De esta manera, cuando el usuario va cambiando de área, verá reflejada en la visualización general, el puntaje obtenido por cada candidato dentro de esa área, sumando las respuestas (ponderadas) de cada una de las subpreguntas. El número resultante lo ubicara en el espectro entre 0 y 10. Elegimos no poner numeros sino “bajo-medio-alto” porque no es algo necesariamente cuantitativo sino más cualitativo.
Por último, debajo de la visualización principal, se ubican las subpreguntas del área seleccionada, que el usuario puede a su vez seleccionar para ver las respuestas punutales a ESA pregunta de todos los candidatos. Dado que finalmente logramos mas de 50 respuestas, agregamos un filtrado por distrito para mejorar la usabilidad.  




¿Cómo adaptarlo?
Sugerimos evaluar cuáles son los principales temas en la agenda de género que actualmente están en debate. Esto puede cambiar según los distintos países: en Argentina, por ejemplo, el matrimonio entre personas del mismo sexo es legal, pero en otros países eso no sucede y es parte de un reclamo.
En ese marco, creemos que las cinco categorías del FeminIndex son globales y que, dentro de ellas, cada país puede proponer sus propias preguntas y enunciados en base a los temas que tengan en debate en ese momento.
¿Cómo replicarlo (lado tecnológico)?
El Feminindex de Economía Feminista, fue realizado íntegramente en Javascript (D3.js) por lo que al ser client-side y one-page, fue fácilmente integrado en nuestro wordpress mediante un Iframe.
El código fuente se encuentra aquí:
https://github.com/rusosnith/Feminindex
