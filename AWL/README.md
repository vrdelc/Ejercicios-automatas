<h1>Ejercicios de autómatas (AWL)</h1>
<h2>Ejercicio 1. Operaciones lógicas básicas.</h2>
Dadas las variables G (A 124.0), A (E 124.0), B (E 124.1), C (E 124.2), D (E 124.3), E (E 124.4) y F
(E 124.5) y considerando que +, · y ? son, respectivamente, las operaciones OR, AND y XOR,
calcular: G = [(A+B)*NOT(C)] ? (D*E+F)
<h2>Ejercicio 2. Operaciones lógicas básicas. Taladradora.</h2>
Se pretender controlar una taladradora, que en estado de reposo se encuentra en contacto
con el final de carrera superior E 124.6. Si un operario activa el pulsador de marcha E 124.7, la
taladradora bajará accionada por el motor de bajada A 124.1 hasta activar el final de carrera
inferior E 125.0 y, posteriormente, subirá de nuevo accionada por el motor de subida A 124.2.
Si en algún momento se pulsa el interruptor de parada E 125.1, la taladradora también deberá
subir.
Programar la bajada y subida de la taladradora utilizando AWL en el OB1. Simular su
funcionamiento haciendo uso del panel disponible en el autómata.
<h2>Ejercicio 3. Operaciones aritméticas y saltos.</h2><em></em>
El panel entrenador de los autómatas cuenta con un potenciómetro de entrada (ruleta) y otro
de salida (dial) conectados a la periferia del autómata mediante, respectivamente, PEW 758 y
PAW 752.
Programar que cuando el valor de E 125.2 sea 0, el dial muestre el valor de la ruleta dividido
por dos y que cuando el valor de E125.2 sea 1, el dial muestre el doble del valor de la ruleta.
<h2>Ejercicio 4. Operaciones de temporización. Control de un semáforo.</h2>
Se dispone de un semáforo que en condiciones normales se encuentra en verde para los
vehículos (A 124.3) y rojo para los peatones (A 124.7).
Si un peatón acciona el pulsador (E 125.3), el indicador de vehículos pasa inmediatamente a
color ámbar (A 124.4) y se mantiene en ese estado durante 3 segundos. Finalizado este estado,
pasará a rojo para vehículos (A 124.5) y verde para peatones (A 124.6), donde se mantendrá
durante 6 segundos.
Finalizado el proceso, el semáforo regresará al estado normal. Si otro peatón utiliza el pulsador
durante el tiempo de duración del ciclo, éste no se rearma.