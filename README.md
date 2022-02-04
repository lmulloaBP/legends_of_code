Misiones de Konoha.
El Hokage de Konoha tiene muchas misiones que documentar, así que le pide a varios
jounin que le ayuden con esta tarea.
Originalmente se distribuyen las misiones para que cada jounin tenga una sola sección de
10 misiones, pero debido a los ataques se pierde esa distribución, por lo que cada uno
documenta cualquier cantidad de misiones.
Por este motivo el Hokage ahora tiene algunas misiones documentadas más de una vez y
otras sin documentar, por lo que necesita saber exactamente qué misiones están listas y
cuáles no.
Entrada.
La entrada está formada de la siguiente manera:
Una cadena de números, donde el primer dígito (N) hace referencia al número de
jounin que colaboran en la traducción.
A continuación aparecen N parejas de números (xi, yi), i=1,...,N, que indican la
primera y la última página del registro de misiones documentadas por cada jounin.
Siempre se cumple que 1 ≤ xi ≤ yi ≤ 50.000.000.
Ejemplos.
2 1 5 6 10
El primer número específica 2 jounin, por lo que se necesitan 2 pares de números
1 5 Especifica que el primer jounin documentó las misiones 1, 2, 3, 4, 5
6 10 Especifica que el segundo jounin documentó las misiones 6, 7, 8, 9, 10
La salida esperada es 10, que representa la cantidad de misiones únicas documentadas 1,
2, 3, 4, 5, 6, 7, 8, 9, 10
3 1 5 3 5 5 7
El primer número específica 3 jounin, por lo que se necesitan 3 pares de números
1 5 Especifica que el primer jounin documentó las misiones 1, 2, 3, 4, 5
3 5 Especifica que el segundo jounin documentó las misiones 3, 4, 5
5 7 Especifica que el tercer jounin documentó las misiones 5, 6, 7
La salida esperada es 7 dado que solo se documentaron las misiones 1, 2, 3, 4, 5, 6 y 7
