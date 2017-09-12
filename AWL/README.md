<h1>Ejercicios de aut�matas (AWL)</h1>
<h2>Ejercicio 1. Operaciones l�gicas b�sicas.</h2>
Dadas las variables G (A 124.0), A (E 124.0), B (E 124.1), C (E 124.2), D (E 124.3), E (E 124.4) y F
(E 124.5) y considerando que +, � y ? son, respectivamente, las operaciones OR, AND y XOR,
calcular: G = [(A+B)*NOT(C)] ? (D*E+F)
<h2>Ejercicio 2. Operaciones l�gicas b�sicas. Taladradora.</h2>
Se pretender controlar una taladradora, que en estado de reposo se encuentra en contacto
con el final de carrera superior E 124.6. Si un operario activa el pulsador de marcha E 124.7, la
taladradora bajar� accionada por el motor de bajada A 124.1 hasta activar el final de carrera
inferior E 125.0 y, posteriormente, subir� de nuevo accionada por el motor de subida A 124.2.
Si en alg�n momento se pulsa el interruptor de parada E 125.1, la taladradora tambi�n deber�
subir.
Programar la bajada y subida de la taladradora utilizando AWL en el OB1. Simular su
funcionamiento haciendo uso del panel disponible en el aut�mata.
<h2>Ejercicio 3. Operaciones aritm�ticas y saltos.</h2><em></em>
El panel entrenador de los aut�matas cuenta con un potenci�metro de entrada (ruleta) y otro
de salida (dial) conectados a la periferia del aut�mata mediante, respectivamente, PEW 758 y
PAW 752.
Programar que cuando el valor de E 125.2 sea 0, el dial muestre el valor de la ruleta dividido
por dos y que cuando el valor de E125.2 sea 1, el dial muestre el doble del valor de la ruleta.
<h2>Ejercicio 4. Operaciones de temporizaci�n. Control de un sem�foro.</h2>
Se dispone de un sem�foro que en condiciones normales se encuentra en verde para los
veh�culos (A 124.3) y rojo para los peatones (A 124.7).
Si un peat�n acciona el pulsador (E 125.3), el indicador de veh�culos pasa inmediatamente a
color �mbar (A 124.4) y se mantiene en ese estado durante 3 segundos. Finalizado este estado,
pasar� a rojo para veh�culos (A 124.5) y verde para peatones (A 124.6), donde se mantendr�
durante 6 segundos.
Finalizado el proceso, el sem�foro regresar� al estado normal. Si otro peat�n utiliza el pulsador
durante el tiempo de duraci�n del ciclo, �ste no se rearma.