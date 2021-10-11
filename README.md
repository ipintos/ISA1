# ISA1
Bentancor - Pintos - Reyes - Umpierrez

## ESCENARIOS

#### PRIMERA DOSIS:
Posibilidad de agendar para la primera dosis. Aporta comodidad , en tanto simplemente por medio de un click podrán estar agendados sin necesidad de requerir a un centro intermedio.

### SEGUNDA DOSIS:
Posibilidad de agendar para la segunda dosis. Aporta comodidad , en tanto simplemente por medio de un click podrán estar agendados sin necesidad de requerir a un centro intermedio.

### INTENTOS DUPLICADOS
No debería ser posible agendarse una vez la dosis ha sido agendada.En este caso debería ser posible informarle al usuario sobre esta situación y no permitir que esto suceda. El valor del negocio del presente radica en mantener al usuario informado acerca de su agendamiento previo, así como el incorrecto agendamiento duplicado . El intento duplicado exitoso derivaría en un sentimiento desconfianza generalizado y poco control de distribución de las dosis de vacunación en tanto dos usuarios tendrían más de una fecha activa de la misma dosis. Por tanto, evitar y controlar esto apunta a la confianza que se busca generar en los usuarios finales.

### DISPONIBILIDAD
Debe contemplarse en todo momento la disponibilidad de las vacunas del sistema en todo momento, no siendo posible agendarse sin verificar este punto.El valor de este escenario radica en que no malgasta recursos en malentendidos generados por una incorrecto agendamiento de vacunas. Imaginemos el escenario en que se agendan a más usuarios que vacunas disponibles, llegará el momento en que un potencial usuario acuda a un centro de vacunatorio sin vacuna disponible. Esto sería perjudicial y generaría desconfianza en el funcionamiento de la aplicación que aquí referimos. En su contrario, si se evita esta situación el valor radicaría en la omisión de esta desconfianza y por oposición aumentaría la confianza de quienes utilicen este software.


### ZONAS
Varianza de zonas. Los usuarios pertenecen a todo el territorio uruguayo. Por lo tanto , cada uno de ellos proviene de una zona distinta. En este sentido, el valor del negocio obtenido en posibilitar esto radica directamente en la comodidad del usuario final, así como evitar transportarse por horas o posible desorientación causada por el asignamiento de una zona no conocida para este. Por tanto, en términos generales esto proporciona confort y ahorro de tiempo .


### CANCELACIÓN
El usuario podría no poder asistir a la dosis, se prevee la posibilidad de cancelar el turno. En este punto , el valor del negocio radica en la posibilidad de cancelar y volver a agendar en un horario que el usuario pueda, aumenta la flexibilidad de la aplicación en cuestión y disminuye la rigidez. En definitiva, se identifica fundamentalmente un aumento de la flexibilidad , siendo este un valor del negocio fundamental.


### PRIORIDAD
Si un adulto mayor se agenda al mismo momento que un jóven , la prioridad debe ser mayor en el caso del adulto mayor. En este escenario, el valor del negocio remite a la contemplación de los grupos de riesgos . De esta forma, se vela por la salud de la población.


### DISPONIBILIDAD DE LOS DATOS
Sería conveniente disponer de las vacunas obtenidas por el usuario. Esto genera valor, en tanto genera disponibilidad de la información y en la práctica el usuario necesitará esto a modo de certificado requerido por algunos eventos. Continuando con esta línea, aporta un mayor control .


### CONTACTO CON COVID POSITIVO
Si me encuentro en contacto con alguien cuyo test de COVID fue positivo debería llegarme una notificación. Este punto aporta información en el sentido que si el usuario recibe una notificación que alerta el contacto con un usuario COVID positivo es de esperar que el primero solicite un test de COVID , en tanto podría haber sido contagiado por el segundo. En definitiva, aporta información, control de los casos en tanto si el segundo resulta asintomático no se hubiese realizado el test de no ser por la notificación.


### DISPONIBILIDAD DE DATOS DE LA POBLACIÓN
Debería poder visualizarse el estado actual del COVID . Probablemente en forma de mapa del territorio uruguayo y con colores en forma de determinar el riesgo de cada departamento. Este punto aporte transparencia, en tanto los usuarios podrán acceder a datos que deberían ser públicos. Asimismo, satisface el requerimiento público de acceso a la información que es pública. Por último, podría aportar calma en la población en caso de que los casos estén controlados.


### SINTOMAS COVID
El usuario puede buscar revisar rápidamente si tiene sintomas de COVID. Debería poder visualizarse esto. Este escenario prevee que el usuario de forma rápida pueda tener acceso a un resumen breve a modo de checklist de modo de aportar rapidez en la búsqueda y evitar malgastar tiempo en sitios web con información parcialmente confiable. En este sentido, se aporta comodidad, acceso rápido a información y posibilidad de sospecha en caso de padecer alguno/s de estos síntomas derivando en un mayor control de los casos , en tanto estos usuarios podrán optar por realizarse un test de COVID.


### NOTIFICACIONES
El usuario debería poder recibir notificaciones con el fin de estar informado de los casos activos, y debería poder cancelar las mismas si así lo quisiera En este punto, el usuario podrá decidir mantenerse constantemente informado apenas la información este publicada. En este punto aporta información en tiempo real y alta disponibilidad de la misma. Asimismo, controlar estas notificaciones deriva en un mayor controlamiento de la aplicación y por tanto desencadena en un aporte de mayor flexibilidad.

## INTERESADOS

En primer lugar, a grandes rasgos los interesados pueden o bien clasificarse por rango etario o por dispositivo en el que utilizan la aplicación en cuestión.

Se identifica como principales interesados relativo al rango etario adolescentes, jóvenes , adultos y adultos mayores cuya edad abarca desde 16 hasta 70.

Sin embargo, es conveniente desglosar este rango en dos.

1. Adolescentes y jóvenes (16-29 años) : en este se enmarca este rango etario , en tanto se percibe que este rango dispone de un buen manejo relativo de la tecnología. Notar que en este grupo se considera que la curva de aprendizaje de la aplicación podría ser menor que en un rango mayor.

2. Adultos (31-55 años): se clasifica en este rango a todos aquellos adultos que si bien el manejo de tecnología se espera que sea alto, la prioridad en la agenda de vacunación debería ser mayor al primer rango. Además, se pueden percibir diferencias en los niveles de aprendizaje con respecto al grupo anterior.

3. Adultos mayores (mayores a 55 años): este grupo se caracteriza por un manejo no fluido de tecnología y por tanto se aprecia que este grupo podría tener una curva de aprendizaje relativa al uso de la aplicación mayor. 

Por otra parte, se identifica dos grandes grupos relativos a dispositivo a utilizar

1. Usuarios con dispositivos Android 

2.Usuarios con dispositivo Ios 

Por este motivo, la aplicación debería funcionar de igual manera en ambos casos.


## Ingenieria Inversa

Instalamos y observamos el funcionamiento de la aplicación Coronavirus Uy.

### Descripción Google Play

“Información, atención médica, y alertas de exposición a COVID-19 para residentes en Uruguay.

Utilizando Coronavirus UY podrás conseguir toda la información actualizada acerca de la enfermedad en Uruguay, y de cómo proteger tu salud y la de tu familia.

En caso de tener alguno de los síntomas podrás realizar consultas directamente a través de la aplicación y, si fuese necesario, tu prestador de salud podrá coordinar para que se te realice un test.

Activando las Alertas de Exposición, tu teléfono podrá avisarte si detecta una posible exposición al virus, para que recibas asesoramiento, seguimiento y atención lo más rápidamente posible.
El sistema es operado y gestionado por la Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento (Agesic) y el Ministerio de Salud Pública del Uruguay (MSP), en el marco del Plan Nacional Coronavirus.

En el caso de contraer la enfermedad, la aplicación te permitirá informar diariamente a tu médico acerca de tu estado de salud (por ejemplo fiebre u otros síntomas). De esa forma podrá mantenerse al tanto de tu salud, indicarte la mejor forma de cuidarte, e incluso contactarte a través de vídeo llamadas.

Permite gestionar el seguimiento de tu grupo familiar, registrando en tu propio dispositivo a tus hijos u otras personas a cargo.

Permite realizar la declaración jurada obligatoria del estado sanitario de la persona para ingreso a Uruguay.

En la aplicación tendrá disponible la certificación de las vacunas recibidas de acuerdo con el registro del MSP.
Tendrá ademas la posibilidad de descargar el certificado de vacunación.

Nota: las Alertas de Exposición solo están disponibles para teléfonos con Android versión 6 o superior. Requieren tener actualizados los Servicios de Google Play y que estén activadas las Notificaciones de exposición ( Ver Ajustes > Google > Notificaciones sobre exposición al COVID-19 ).”


### Intereses destacados

Lo que más nos interesó de esta aplicación son las funcionalidades de “Mi Estado”, “Notificaciones”, “Exposición a COVID-19” y “Agenda de Vacunación”.

**Mi estado:** en dicha sección se puede visualizar el estado actual de la persona logueada en la aplicación como dosis administradas y test realizados. Nos resulta una sección super importante dado que podemos visualizar nuestro certificado de vacunación, dosis administradas, test realizados, etc.

**Notificaciones:** Esta sección está enfocada a realizar distintas notificaciones al usuario, como pueden ser, resultado de test, test pendientes, dosis pendientes, entre otras.
Es una de las funcionalidades más útiles dado que el usuario no debe estar pendiente de resultados de test realizados, por ejemplo.

**Exposición a COVID-19:** 
¿Cómo funciona?

“Juan va al supermercado. Allí se cruza con María. Mientras espera en la fiambrería, su teléfono empieza a intercambiar códigos aleatorios y encriptados con los otros usuarios, incluida María, con la que está a pocos metros y aguarda ser atendido por más de 15 minutos. Eso sí, solo los intercambia porque ambos tienen Bluetooth encendido. Las últimas versiones de los sistemas operativos de Apple y Android hacen que el usuario intercambie esos códigos de manera automática. Eso fue autorizado cuando el usuario lo aceptó. Luego, cuando la app Coronavirus UY es descargada y las alertas son activadas esos códigos cobran utilidad.

Si Juan tiene el celular en la mano, emitirá ondas por Bluetooth más fuertes que si lo tiene en el bolsillo, por lo que la precisión en esos metros puede variar. Según informaron miembros de la app, a esta tecnología le cuesta mucho definir con exactitud la cantidad de metros en los que está la otra persona. Lo que sí es preciso es el tiempo. Por lo tanto, el código se puede intercambiar si está a dos, tres o cinco metros. También puede darse la posibilidad, aunque no es tan probable, de que se intercambien esos códigos cruzando una pared.
 
Si se da el caso, el usuario intercambia los códigos. Unos días más tarde, María tiene síntomas. Le ordenan hisoparse y da positivo. Ella, como siempre ha tenido la app descargada y las alertas de exposición activadas, autoriza a notificar a las personas con las que estuvo a menos de dos metros y durante 15 minutos en los últimos 14 días.

Poco después, Juan toma el celular y recibe un mensaje. "Alerta de exposición al virus del covid-19. En los últimos 14 días tuviste contacto con un caso confirmado de covid-19". El dato está acompañado por la fecha y la hora en que recibió la notificación. No indica el día en que estuvo en contacto con esa persona.”


**Agenda de vacunación:**

Una de las funcionalidades más valoradas por los usuarios, en la mismas podemos validar si estamos habilitados para la vacunación y en caso de estarlo poder agendarse.

## Mejoras que podemos brindar

Creemos que nuestro rival cuenta con pantallas poco amigables para estratos con poca relación con la tecnología.

**Ejemplos:**

- Funcionalidad “Agendar” (una de las más utilizadas por los usuarios), se encuentra en el final de la página de inicio teniendo que realizar scroll para poder acceder a dicha funcionalidad.

![Pantalla inicio](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/PantallaInicio.png)
![Funcionalidad agendar](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/PantallaInicioAgendar.png)

- Tabs difíciles de visualizar y acceder

![Tabs](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/TabsDificilAcceso.png)

- Botones que no revelan intención.

![Botones](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Botones.png)

- Información muy técnica difícil de entender por la mayoría de los estratos sociales.

![Grafica 1](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/GraficaI.png)
![Grafica 2](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/GraficaII.png)
![Grafica 3](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/GraficaIII.png)

### Criticas de usuarios

- Fallas de conectividad

![Reseña conexión 1](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aConexionI.png)
![Reseña conexión 2](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aConexionII.png)

- Fallas en obtención de código de validación.

![Código validación 1](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aCodigoValidacionI.png)
![Código validación 2](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aCodigoValidacionII.png)

- Fallas en cambio de datos personales

![Cambio de datos 1](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aCambiarDatosI.png)
![Cambio de datos 2](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aCambiarDatosII.png)

- Extranjeros con residencias en Uruguay

![Extranjero](https://github.com/ipintos/ISA1/blob/feature/inverseEngineering/imagenes/Rese%C3%B1aExtranjero.png)

### Conclusión

Luego de utilizar la app Coronavirus Uy y recabado distintas reseñas de los usuarios que alguna vez utilizaron la aplicación
pudimos ver que la misma carece con algunos criterios de usabilidad mencionados anteriormente para algunos estrator de la población.
Como los que pueden ser botones que no relevan intención, tabs dificiles de visualizar/acceder, funcionalidades principales dificiles
de encontrar, etc.
La conclusión se realiza tomando encuenta todos los estratos, como por ejemplo adultos mayores que deben contar con una aplicación más
facil de usar, datos con graficas muy tecnicas que muchas veces son entendiso por expertos del tema, entre otras.

Por otro lado recabamos información de lo que opinan los usuarios sobre la aplicación. Notamos que la gran mayoria cuentan con quejas
de conectibidad, que la aplicación no permite los cambios de datos personales, fallas en obtención de codigos de validacion, no se toman
en cuenta extranjeros con residencias en uruguay, entre otras.

Este estudio nos revela información o aspectos de la aplicación que debemos atacar/mejorar contra nuestro rival para poder ser aceptada y utilizada por la población.

## Historias de usuario:

### 1:
#### Como usuario

Quiero registrarme para recibir las dosis restantes en algún vacunatorio viendo los horarios disponibles.

Para poder recibir mis vacunas.


El sistema debe mantener actualizado el estado de los vacunatorios para que no haya errores en la asignación de horas.

El usuario ingresa al sistema, y si está habilitado se le permite registrarse para ser vacunado en un lugar y hora que él puede elegir de los disponibles, cuando se registra recibe una confirmación.

#### Criterios de aceptación:

El tiempo desde que selecciono un horario y recibo la confirmación no debe exceder los 5 segundos.

Una muestra de 5 personas seleccionadas al azar debe ser capaz de agendarse sin recibir ayuda externa en menos de 1 minuto.

Ningún otro usuario además de quien hace la reserva debe ver sus datos personales.

La funcionalidad cuenta con una interfaz Androidy iOS

#### story points: 5


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

#### story points: 5


### 3:

#### Como Usuario

Quiero saber si los síntomas que tengo se corresponden a los del covid

Para saber si tengo que tomar alguna acción y para saber si puedo ser contagioso.


El usuario tiene que poder resolver sus dudas en cuanto a la enfermedad con el menor esfuerzo y en el menor tiempo posible. Esta funcionalidad puede implementarse como página de FAQ o como un chat bot.


#### Criterios de aceptación:

Una muestra de 5 personas seleccionadas al azar debe ser capaz de llegar a una respuesta sin recibir ayuda externa en menos de 2 minutos.

Siempre se recomienda una acción para cada caso.

La funcionalidad cuenta con una interfaz Androidy iOS

#### story points: 1


### 4:

#### Como usuario

Quiero saber si estuve expuesto al virus del covid

Para estar al tanto de la necesidad de tomar alguna medida.


La aplicación debe tener la capacidad de detectar si el dispositivo del usuario estuvo a menos de 2 metros del dispositivo de alguna persona infectada mientras esta cursaba la enfermedad. 

En caso de que se de la situación, tiene que enviar una notificación al usuario y proveerle pasos a seguir.

#### Criterios de aceptación:

La funcionalidad tiene que funcionar en dispositivos android y iOS equipados con bluetooth v4.0 o superior.

Una muestra de 5 personas seleccionadas al azar debe ser capaz de decir que entendió los pasos que se le sugieren.

#### story points: 9


### 5:

#### Como usuario

Quiero poder iniciar sesión en la aplicación de manera segura.

Para poder acceder a las funcionalidades de la aplicación.


El usuario tiene que poder consguir las credenciales para ingresar al sistema. Estas credenciales estarán asociadas a su identidad digital.


#### Criterios de aceptación:

Debe especificarse una manera de obtener el usuario y contraseña.

Debe haber contingencias para aquellas personas que no tengan celular y/o no entiendan el uso del mismo.

#### story points: 3


### 6:
 
#### Como ciudadano con cédula uruguaya
 
Quiero registrarme en el sistema
 
Para poder hacer una reserva para vacunación.
  
#### Criterios de aceptación:
 
Debe funcionar para iOS y Android. El usuario debe quedar registrado en la base de datos.

#### story points: 2
 

### 7:
 
#### Como turista con pasaporte
 
Quiero registrarme en el sistema
 
Para poder hacer una reserva para vacunación.
 
Los turistas deben poder registrarse para crear una solicitud para agenda de vacunación.

#### Criterios de aceptación:
 
Los usuarios con pasaporte deben quedar registrados en la base de datos.

#### story points: 2


### 8:
 
#### Como usuario registrado
 
Quiero ver los horarios y dosis disponibles de mis vacunatorios cercanos
 
Para poder hacer una reserva para vacunación.
 
Los usuarios deben poder ver los vacunatorios cercanos en un mapa y para cada uno de ellos ver las dosis disponibles por horario.
 
#### Criterios de aceptación:
 
La actualización de dosis y horarios debe ser en tiempo real
 
El mapa debe geolocalizar al usuario en android e iOS

#### story points: 6

 
### 9:
 
#### Como usuario registrado
 
Quiero agendar las próximas dosis en un vacunatorio cercano
 
Para concurrir a vacunarme.
 
Los usuarios deben poder agendarse en el vacunatorio seleccionado. En caso de no existir disponibilidad se le debe mostrar más horarios disponibles en el entorno horario previamente seleccionado.
 
#### Criterios de aceptación:
 
La solicitud debe quedar agendada en el MSP

#### story points: 7

 
### 10:
 
#### Como usuario registrado
 
Quiero consultar mis reservas y recibir alertas de agenda próxima
 
Para no olvidar la fecha en la que debo concurrir.
 
Los usuarios deben poder consultar las fechas de sus reservas, y configurar si quieren recibir alertas sobre las próximas citas, mediante notificaciones push.
 
#### Criterios de aceptación:
 
Debe funcionar en android e iOS

#### story points: 5 

 
### 11:
 
#### Como usuario registrado
 
Quiero emitir un comprobante de las dosis recibidas.
 
Para presentarlo en mi mutualista.
 
Los usuarios deben poder generar un comprobante digital de código QR que pueda ser escaneado desde la aplicación y también deben tener la posibilidad de imprimirlo. Para realizar esta acción la pauta de vacunación debe estar completa y cumplido el plazo establecido de 15 días desde la última dosis.
 
#### Criterios de aceptación:
 
El código QR debe poder ser leído y mostrar que la pauta de vacunación está completa sin revelar datos personales. 
 
#### story points: 2


### 12:
 
#### Como usuario registrado
 
Quiero cancelar una reserva.
 
Porque no puedo concurrir el día pactado.
 
Los usuarios deben poder cancelar reservas en un plazo mayor a 24h. antes de la fecha agendada.
 
#### Criterios de aceptación:
 
La cita cancelada debe quedar disponible para ser reservada por otro usuario en el momento de confirmación de la cancelación.

#### story points: 5 

 
### 13:
 
#### Como usuario registrado
 
Quiero modificar la fecha de mi reserva.
 
Porque no puedo concurrir el día pactado.
 
Los usuarios deben poder modificar la fecha de su reserva en un plazo mayor a 24h. antes de la fecha agendada. Luego de seleccionado el nuevo horario, se le deben agendar automáticamente las dosis restantes con el plazo estipulado de 15 días entre ellas.
 
#### Criterios de aceptación:
 
La o las citas canceladas, debe quedar disponible para ser reservadas por otro usuario en el momento de confirmación de la cancelación.

#### story points: 6 

 
### 14:
 
#### Como usuario
 
Quiero consultar los casos activos en el país actualizados al día de hoy y filtrar por departamento.
 
Para mantenerme informado.
 
Los usuarios registrados y no registrados deben poder acceder a la información de casos activos filtrando por departamento, la información se debe mostrar en un mapa interactivo de uruguay. Marcando por colores la densidad de casos activos.
 
#### Criterios de aceptación:
 
La información debe haber sido actualizada en un período no mayor a 24h.

#### story points: 7 
 

### 15:
 
#### Como usuario registrado
 
Quiero poder alertar que tengo covid de forma anónima a otros usuarios que estuvieron en contacto conmigo en los últimos 15 días
 
Para que estén atentos a los síntomas y puedan consultar a su médico.
 
Los usuarios registrados deben poder alertar que están cursando la enfermedad y el sistema debe identificar y enviar notificaciones a los usuarios que hayan tenido contacto con quien disparó la alerta. La identificación de contactos debe hacerse mediante bluetooth y preservar el anonimato.
 
#### Criterios de aceptación:
 
La aplicación debe enviar notificaciones push a los usuarios que fueron contacto.

#### story points: 8 

 
### 16:
 
#### Como usuario
 
Quiero consultar los síntomas conocidos.
 
Para saber si debo consultar a mi médico.
 
Los usuarios registrados y los no registrados deben poder acceder a información actualizada sobre los síntomas de covid, reportados por el ministerio de salud pública.
 
#### Criterios de aceptación:
 
La información debe ser legible desde el dispositivo móvil.
 
#### story points: 1

 
### 17:
 
#### Como usuario registrado
 
Quiero poder recibir alertas de exposición a casos activos.
 
Para estar atento a mis síntomas y consultar a  mi médico.
 
Los usuarios registrados deben poder configurar si desean obtener notificaciones de contactos afectados por la enfermedad.
 
#### Criterios de aceptación:
 
La aplicación debe enviar notificaciones push a los usuarios a quienes así lo configuraron y no en caso contrario.

#### story points: 6 

 
### 18:
 
#### Como usuario registrado
 
Quiero poder solicitar ayuda y ver preguntas frecuentes.
 
Para recuperarme de algún problema en la aplicación.
 
Los usuarios registrados deben poder acceder a las preguntas frecuentes y solicitar ayuda en línea desde la aplicación. Se deberá mostrar un chat y la aplicación proveerá un chatbot para estos casos.
 
#### Criterios de aceptación:
 
La aplicación muestra las FAQ y permite chatear para enviar consultas.

#### story points: 9

 
### 19:
 
#### Como usuario registrado
 
Quiero poder usar la aplicación sin necesidad de leer un manual de usuario.
 
Para recuperarme de algún problema en la aplicación.
 
Los usuarios registrados deben poder navegar la aplicación y todas sus características sin conocimiento previo de la aplicación, para ello se debe proveer mensajes autoexplicativos.
 
#### Criterios de aceptación:
 
La aplicación debe ser usada por un usuario sin conocimientos previos del sistema y el mismo debe poder completar las historias de usuario.

#### story points: 3

 
### 20:
 
#### Como usuario registrado que pertenece a un grupo prioritario
 
Quiero quiero que la aplicación me identifiqué como tal.
 
Para poder agendarme para la vacuna en forma prioritaria.
 
Los usuarios registrados que pertenezcan a un grupo prioritario deben poder ser identificados por la aplicación mediante servicios del BPS, en caso de que no estén como tal, deben poder reclamar esta situación desde la aplicación.
 
#### Criterios de aceptación:
 
Los usuarios deben ser tratados como prioritarios en caso que así estén registrados en el BPS.

#### story points: 8


## Épicas:

Como administrador quiero que todos los usuarios tengan acceso a la aplicación.

Como administrador quiero asegurarme de que los usuarios pueden sacarse las dudas que tengan respecto del coronavirus

Como administrador quiero que todos los usuarios puedan agendarse para ser vacunados.
