# ISA1
Bentancor - Pintos - Reyes - Umpierrez

1a. entrega de Miniproyecto: iteración 1 => 08-oct

2a. entrega de Miniproyecto: iteración 2 => 22-oct

3a. entrega de Miniproyecto: iteración 3 => 05-nov

Entrega final 19 de noviembre => 19-nov

# Historias de usuario:

### 1:
#### Como usuario

Quiero registrarme para recibir las dosis restantes en algún vacunatorio viendo los horarios disponibles.

Para poder recibir mis vacunas.


El sistema debe mantener actualizado el estado de los vacunatorios para que no haya errores en la asignación de horas.

EL usuario ingresa al sistema, y si está habilitado se le permite registrarse para ser vacunado en un lugar y hora que él puede elegir de los disponibles, cuando se registra recibe una confirmación.

#### Criterios de aceptación:

El tiempo desde que selecciono un horario y recibo la confirmación no debe exceder los 5 segundos.

Una muestra de 5 personas seleccionadas al azar debe ser capaz de agendarse sin recibir ayuda externa en menos de 1 minuto.

Ningún otro usuario además de quien hace la reserva debe ver sus datos personales.

La funcionalidad cuenta con una interfaz Androidy iOS

### 2:

#### Como Usuario

Quiero poder ver las métricas de avance de la enfermedad

Para poder conocer el estado de situación actual.


El usuario debe disponer de una sección en la aplicación donde se muestran las gráficas de interés, estas incluyen: Casos por dia, total de vacunados, fallecidos por día, tests por día.

#### Criterios de aceptación:

Los datos que se muestran son a nivel de toda la población y no se muestra dato personal alguno.

Las gráficas deben cargar en menos de 10 segundos.

Una muestra de 5 personas seleccionadas al azar debe ser capaz de llegar a las gráficas sin recibir ayuda externa en menos de 1 minuto.

La funcionalidad cuenta con una interfaz Androidy iOS

### 3:

#### Como Usuario

Quiero saber si los síntomas que tengo se corresponden a los del covid

Para saber si tengo que tomar alguna acción y para saber si puedo ser contagioso.


El usuario tiene que poder resolver sus dudas en cuanto a la enfermedad con el menor esfuerzo y en el menor tiempo posible. Esta funcionalidad puede implementarse como página de FAQ o como un chat bot.


#### Criterios de aceptación:

Una muestra de 5 personas seleccionadas al azar debe ser capaz de llegar a una respuesta sin recibir ayuda externa en menos de 2 minutos.

Siempre se recomienda una acción para cada caso.

La funcionalidad cuenta con una interfaz Androidy iOS

### 4:

#### Como usuario

Quiero saber si estuve expuesto al virus del covid

Para estar al tanto de la necesidad de tomar alguna medida.


La aplicación debe tener la capacidad de detectar si el dispositivo del usuario estuvo a menos de 2 metros del dispositivo de alguna persona infectada mientras esta cursaba la enfermedad. 

En caso de que se de la situación, tiene que enviar una notificación al usuario y proveerle pasos a seguir.

#### Criterios de aceptación:

La funcionalidad tiene que funcionar en dispositivos android y iOS equipados con bluetooth v4.0 o superior.

Una muestra de 5 personas seleccionadas al azar debe ser capaz de decir que entendió los pasos que se le sugieren.

### 5:

#### Como usuario

Quiero poder iniciar sesión en la aplicación de manera segura.

Para poder acceder a las funcionalidades de la aplicación.


El usuario tiene que poder consguir las credenciales para ingresar al sistema. Estas credenciales estarán asociadas a su identidad digital.


#### Criterios de aceptación:

Debe especificarse una manera de obtener el usuario y contraseña.

Debe haber contingencias para aquellas personas que no tengan celular y/o no entiendan el uso del mismo.


### 6:
 
#### Como ciudadano con cédula uruguaya
 
Quiero registrarme en el sistema
 
Para poder hacer una reserva para vacunación.
  
#### Criterios de aceptación:
 
Debe funcionar para iOS y Android. El usuario debe quedar registrado en la base de datos.
 

### 7:
 
#### Como turista con pasaporte
 
Quiero registrarme en el sistema
 
Para poder hacer una reserva para vacunación.
 
Los turistas deben poder registrarse para crear una solicitud para agenda de vacunación.

#### Criterios de aceptación:
 
Los usuarios con pasaporte deben quedar registrados en la base de datos.
 

### 8:
 
#### Como usuario registrado
 
Quiero ver los horarios y dosis disponibles de mis vacunatorios cercanos
 
Para poder hacer una reserva para vacunación.
 
Los usuarios deben poder ver los vacunatorios cercanos en un mapa y para cada uno de ellos ver las dosis disponibles por horario.
 
#### Criterios de aceptación:
 
La actualización de dosis y horarios debe ser en tiempo real
 
El mapa debe geolocalizar al usuario en android e iOS
 
 
### 9:
 
#### Como usuario registrado
 
Quiero agendar las próximas dosis en un vacunatorio cercano
 
Para concurrir a vacunarme.
 
Los usuarios deben poder agendarse en el vacunatorio seleccionado. En caso de no existir disponibilidad se le debe mostrar más horarios disponibles en el entorno horario previamente seleccionado.
 
#### Criterios de aceptación:
 
La solicitud debe quedar agendada en el MSP
 
 
### 10:
 
#### Como usuario registrado
 
Quiero consultar mis reservas y recibir alertas de agenda próxima
 
Para no olvidar la fecha en la que debo concurrir.
 
Los usuarios deben poder consultar las fechas de sus reservas, y configurar si quieren recibir alertas sobre las próximas citas, mediante notificaciones push.
 
#### Criterios de aceptación:
 
Debe funcionar en android e iOS
 
 
### 11:
 
#### Como usuario registrado
 
Quiero emitir un comprobante de las dosis recibidas.
 
Para presentarlo en mi mutualista.
 
Los usuarios deben poder generar un comprobante digital de código QR que pueda ser escaneado desde la aplicación y también deben tener la posibilidad de imprimirlo. Para realizar esta acción la pauta de vacunación debe estar completa y cumplido el plazo establecido de 15 días desde la última dosis.
 
#### Criterios de aceptación:
 
El código QR debe poder ser leído y mostrar que la pauta de vacunación está completa sin revelar datos personales. 
 
 
### 12:
 
#### Como usuario registrado
 
Quiero cancelar una reserva.
 
Porque no puedo concurrir el día pactado.
 
Los usuarios deben poder cancelar reservas en un plazo mayor a 24h. antes de la fecha agendada.
 
#### Criterios de aceptación:
 
La cita cancelada debe quedar disponible para ser reservada por otro usuario en el momento de confirmación de la cancelación.
 
 
### 13:
 
#### Como usuario registrado
 
Quiero modificar la fecha de mi reserva.
 
Porque no puedo concurrir el día pactado.
 
Los usuarios deben poder modificar la fecha de su reserva en un plazo mayor a 24h. antes de la fecha agendada. Luego de seleccionado el nuevo horario, se le deben agendar automáticamente las dosis restantes con el plazo estipulado de 15 días entre ellas.
 
#### Criterios de aceptación:
 
La o las citas canceladas, debe quedar disponible para ser reservadas por otro usuario en el momento de confirmación de la cancelación.
 
 
### 14:
 
#### Como usuario
 
Quiero consultar los casos activos en el país actualizados al día de hoy y filtrar por departamento.
 
Para mantenerme informado.
 
Los usuarios registrados y no registrados deben poder acceder a la información de casos activos filtrando por departamento, la información se debe mostrar en un mapa interactivo de uruguay. Marcando por colores la densidad de casos activos.
 
#### Criterios de aceptación:
 
La información debe haber sido actualizada en un período no mayor a 24h.
 
 
### 15:
 
#### Como usuario registrado
 
Quiero poder alertar que  tengo covid de forma anónima a otros usuarios que estuvieron en contacto conmigo en los últimos 15 días
 
Para que estén atentos a los síntomas y puedan consultar a su médico.
 
Los usuarios registrados deben poder alertar que están cursando la enfermedad y el sistema debe identificar y enviar notificaciones a los usuarios que hayan tenido contacto con quien disparó la alerta. La identificación de contactos debe hacerse mediante bluetooth y preservar el anonimato.
 
#### Criterios de aceptación:
 
La aplicación debe enviar notificaciones push a los usuarios que fueron contacto.
 
 
### 16:
 
#### Como usuario
 
Quiero consultar los síntomas conocidos.
 
Para saber si debo consultar a mi médico.
 
Los usuarios registrados y los no registrados deben poder acceder a información actualizada sobre los síntomas de covid, reportados por el ministerio de salud pública.
 
#### Criterios de aceptación:
 
La información debe ser legible desde el dispositivo móvil.
 
 
### 17:
 
#### Como usuario registrado
 
Quiero poder recibir alertas de exposición a casos activos.
 
Para estar atento a mis síntomas y consultar a  mi médico.
 
Los usuarios registrados deben poder configurar si desean obtener notificaciones de contactos afectados por la enfermedad.
 
#### Criterios de aceptación:
 
La aplicación debe enviar notificaciones push a los usuarios a quienes así lo configuraron y no en caso contrario.
 
 
### 18:
 
#### Como usuario registrado
 
Quiero poder solicitar ayuda y ver preguntas frecuentes.
 
Para recuperarme de algún problema en la aplicación.
 
Los usuarios registrados deben poder acceder a las preguntas frecuentes y solicitar ayuda en línea desde la aplicación. Se deberá mostrar un chat y la aplicación proveerá un chatbot para estos casos.
 
#### Criterios de aceptación:
 
La aplicación muestra las FAQ y permite chatear para enviar consultas.
 
 
### 19:
 
#### Como usuario registrado
 
Quiero poder usar la aplicación sin necesidad de leer un manual de usuario.
 
Para recuperarme de algún problema en la aplicación.
 
Los usuarios registrados deben poder navegar la aplicación y todas sus características sin conocimiento previo de la aplicación, para ello se debe proveer mensajes autoexplicativos.
 
#### Criterios de aceptación:
 
La aplicación debe ser usada por un usuario sin conocimientos previos del sistema y el mismo debe poder completar las historias de usuario.
  
 
### 20:
 
#### Como usuario registrado que pertenece a un grupo prioritario
 
Quiero quiero que la aplicación me identifiqué como tal.
 
Para poder agendarme para la vacuna en forma prioritaria.
 
Los usuarios registrados que pertenezcan a un grupo prioritario deben poder ser identificados por la aplicación mediante servicios del BPS, en caso de que no estén como tal, deben poder reclamar esta situación desde la aplicación.
 
#### Criterios de aceptación:
 
Los usuarios deben ser tratados como prioritarios en caso que así estén registrados en el BPS.


# Épicas:

Como administrador quiero que todos los usuarios tengan acceso a la aplicación.

Como administrador quiero asegurarme de que los usuarios pueden sacarse las dudas que tengan respecto del coronavirus

Como administrador quiero que todos los usuarios puedan agendarse para ser vacunados.
