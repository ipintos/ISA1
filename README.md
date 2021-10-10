# ISA1
Bentancor - Pintos - Reyes - Umpierrez

1a. entrega de Miniproyecto: iteración 1 => 08-oct

2a. entrega de Miniproyecto: iteración 2 => 22-oct

3a. entrega de Miniproyecto: iteración 3 => 05-nov

Entrega final 19 de noviembre => 19-nov

# Historias de usuario:

### 1:
Como usuario
Quiero registrarme para recibir las dosis restantes en algún vacunatorio viendo los horarios disponibles.
Para poder recibir mis vacunas.

El sistema debe mantener actualizado el estado de los vacunatorios para que no haya errores en la asignación de horas.
EL usuario ingresa al sistema, y si está habilitado se le permite registrarse para ser vacunado en un lugar y hora que él puede elegir de los disponibles, cuando se registra recibe una confirmación.

Criterios de aceptación:
El tiempo desde que selecciono un horario y recibo la confirmación no debe exceder los 5 segundos.
Una muestra de 5 personas seleccionadas al azar debe ser capaz de agendarse sin recibir ayuda externa en menos de 1 minuto.
Ningún otro usuario además de quien hace la reserva debe ver sus datos personales.
La funcionalidad cuenta con una interfaz andriod y iOS

### 2:

Como Usuario
Quiero poder ver las métricas de avance de la enfermedad
Para poder conocer el estado de situación actual.

El usuario debe disponer de una sección en la aplicación donde se muestran las gráficas de interés, estas incluyen: Casos por dia, total de vacunados, fallecidos por día, tests por día.

Criterios de aceptación:
Los datos que se muestran son a nivel de toda la población y no se muestra dato personal alguno.
Las gráficas deben cargar en menos de 10 segundos.
Una muestra de 5 personas seleccionadas al azar debe ser capaz de llegar a las gráficas sin recibir ayuda externa en menos de 1 minuto.
La funcionalidad cuenta con una interfaz andriod y iOS

### 3:

Como Usuario
Quiero saber si los síntomas que tengo se corresponden a los del covid
Para saber si tengo que tomar alguna acción y para saber si puedo ser contagioso.

El usuario tiene que poder resolver sus dudas en cuanto a la enfermedad con el menor esfuerzo y en el menor tiempo posible. Esta funcionalidad puede implementarse como página de FAQ o como un chat bot.
sadasd

Criterios de aceptación:
Una muestra de 5 personas seleccionadas al azar debe ser capaz de llegar a una respuesta sin recibir ayuda externa en menos de 2 minutos.
Siempre se recomienda una acción para cada caso.
La funcionalidad cuenta con una interfaz andriod y iOS

### 4:

Como usuario
Quiero saber si estuve expuesto al virus del covid
Para estar al tanto de la necesidad de tomar alguna medida.

La aplicación debe tener la capacidad de detectar si el dispositivo del usuario estuvo a menos de 2 metros del dispositivo de alguna persona infectada mientras esta cursaba la enfermedad. 
En caso de que se de la situación, tiene que enviar una notificación al usuario y proveerle pasos a seguir.

Criterios de aceptación:
La funcionalidad tiene que funcionar en dispositivos android y iOS equipados con bluetooth v4.0 o superior.
Una muestra de 5 personas seleccionadas al azar debe ser capaz de decir que entendió los pasos que se le sugieren.

### 5:

Como usuario
Quiero poder iniciar sesión en la aplicación de manera segura.
Para poder acceder a las funcionalidades de la aplicación.

El usuario tiene que poder consguir las credenciales para ingresar al sistema. Estas credenciales estarán asociadas a su identidad digital.

Criterios de aceptación:
Debe especificarse una manera de obtener el usuario y contraseña.
Debe haber contingencias para aquellas personas que no tengan celular y/o no entiendan el uso del mismo.
