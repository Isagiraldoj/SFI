# SFI
# Concierto Interactivo

### Diseño de experiencia
Hola!! Soy Isabela ingeniera en formación en diseño de entretenimiento digital. A continuación verás un poco lo que fue el proceso de diseño de un concierto interactivo. Cabe aclarar que esto es un ejercicio académico por lo que lo que veras aun no se ha prototipado a mayor escala.

### Fase 1: Conceptualización 

Contextualizándonos, haremos el siguiente concierto de Rufus du Sol, pero lo plantearemos desde una perspectiva de experiencia interactiva. Para conocer que es lo que queremos diseñar primero haremos una pequeña investigación de quienes son, logros musicales y público objetivo.

#### Rufus du sol
Es una banda australiana de música electrónica formada por Tyrone Lindqvist, Jon George y James Hunt. Su música abarca géneros como el house, el techno y el indie dance, creando una mezcla distintiva de sonidos electrónicos melódicos y atmósferas envolventes.

​

El álbum "Bloom" de RÜFÜS DU SOL es una obra que fusiona elementos de la música electrónica, el indie dance y el pop alternativo en una experiencia sonora inmersiva y evocadora. Lanzado en 2016, "Bloom" explora temas de crecimiento personal, introspección y conexión emocional. "Innerbloom" es una de las canciones más emblemáticas del grupo y ha recibido una gran aclamación de la crítica y el público.

#### Público objetivo
Su estilo musical atrae a una amplia variedad de personas, pero generalmente su audiencia está compuesta por aficionados a la música electrónica, amantes de la música alternativa y aquellos que disfrutan de experiencias sensoriales inmersivas. Su música es conocida por su atmósfera emotiva y su capacidad para llevar al oyente en un viaje sonoro, lo que la hace popular entre los aficionados a la música electrónica de vanguardia y los seguidores de la escena underground.

## Narración

Este concierto tendrá como temática "búsqueda de la identidad" que va muy a la mano con su álbum bloom. El concierto se llamara innerblom que traduce renacer, también enfatizando que la canción más importante de ellos es esta. Este concierto esta muy inpirado en el afterlife donde las visuales cuentan historias de personajes. 


En este caso tendremos un personaje que se llama Alon, que es un chico que esta cansado de la rutina, de siempre hacer lo mismo, de que aunque tiene una vida estable, eso no es lo que lo hace feliz. En esta fase del concierto es donde inicia y se da ingreso a los cantantes con canciones como "On my knees", "Until the sun needs to rise", "underwater", donde llevan al público a entrar en mood de concierto y se refleja en el personaje que esta reflexivo, cansado, a punto de caer en quiebre.

​

La segunda escena será cuando Alon ingresa a un portal(esto se replicará en el concierto con un show de láseres que serán manejados por el público) dentro de este, se encuentra con muchos sentimientos, tristeza, angustia, desagrado, perdida, y es un tipo de sueño en el que reflexiona y se da cuenta de que no quiere vivir más con esos sentimientos que ha estado reprimiendo durante tanto tiempo donde se irán tocando canciones como "Alive", "Next to me", "You were Right", "No place". 

​

La tercera escena y última también dará inicio con el portal(show de láseres) donde Alon sale de ese sueño y empieza actuar por su vida, ser libre, renacer. 

Para esta parte utilizaremos el prototipo de manejo de partículas donde las personas tendrán desde su dispositivo que manejar unos faders, para que cuando Alon se quebrante en pedacitos ellos le puedan ayudar a reconstruirlo y así renacer. A este punto ya sonaran las mejores canciones de ellos como "Idont wanna leave", "Treat you better", y cerraremos con "innerblom".

​

La experiencia empezara desde que las personas compran el boleto, ya que al correo le llegara la información de confirmación de la compra con los boletas y también los pasos para que descargue la app del concierto. 

​

Al la persona ingresar en esta app, se encontrara que su funcionalidad será fundamental para la hora del concierto ya que con esta podrá manejar las diferentes experiencias antes y durante. También con la finalidad de hacer mucho más fácil su ingreso, compras, desplazamiento, etc;

​
### Protitipo 1
Este es el prototipo del show de láseres. Este funciona por tracking de movimiento. Asi que cuando la persona mueve su celular este tiene sensores que cambian las variables como aceleración, giro, rotación y esto de vera reflejado en un láser, la idea es que como las personas siempre tienen sus celulares a la mano se les asigen aleatoriamente un laser y con el movimiento de su celular el laser se mueva. A continuacion un poco de como es este prototipo.

​https://www.youtube.com/watch?v=DwDU4yhmHqg

Si quieren probar el prototipo pueden ingresar al siguiente enlace donde esta el repositorio con los archivos(son ejecutables en touchdesigner).

​Para probar este prototipo debes tener instalado, touchdesigner y ZIG SIM pro. Recuerda tener los dispositivos en la misma red local.

​1. Ajusta el puerto de entrada OSC en el nodo OSC In para que coincida con el puerto que usarás en ZIG SIM Pro.

2. Configurar ZIG SIM Pro:
  - En ZIG SIM Pro, necesitarás configurar los parámetros de salida OSC para enviar mensajes a la dirección IP y puerto correctos de tu dispositivo TouchDesigner.
  - Asegúrate de que los mensajes OSC que envíes desde ZIG SIM Pro estén formateados de acuerdo con lo que esperas recibir en TouchDesigner.

3. Establecer la Conexión:
  - Una vez que hayas configurado tanto el servidor OSC en TouchDesigner como la salida OSC en ZIG SIM Pro, asegúrate de que ambas aplicaciones estén en la misma red.
  - Inicia la simulación en ZIG SIM Pro y asegúrate de que esté enviando los mensajes OSC correctamente.

4. Recepción y Procesamiento en TouchDesigner:
   - En TouchDesigner, verifica que el nodo OSC In esté recibiendo datos de ZIG SIM Pro.
   - Procesa y utiliza los datos recibidos según tus necesidades utilizando los nodos apropiados en TouchDesigner.

### Prototipo 2
Este prototipo es de manejo de partículas por un controlador. Aquí la persona tiene sus faders, y lo que debe hacer es empezar a moverlo para que el montón de partículas se agrupen y formen una figura. En el siguiente enlace verán un video ilustrativo de lo que hace el prototipo. 

https://youtu.be/iz00fmcUH4E?si=f1Ffi2ept22G1mgz

Para probar este prototipo deben hacer lo mismo que las instrucciones anteriores solo que aca ya no será con la aplicación ZIG SIm pro, sino Touch OSC.

## Proceso de diseño

#### Arquetipo
Pasamos hacer un arquetipo para tener más claro el público objetivo. Este fue el resultado.

Descripción: Luna es una persona creativa y en constante búsqueda de inspiración y autoexpresión. Tiene un espíritu aventurero y está abierta a nuevas experiencias que la desafíen y la inspiren en su arte. Le gusta la música electrónica, el techno, house, etc. Vive en la ciudad de Medellín y siempre esta pendiente por redes que festivales se realizaran o eventos de electronica ya que su ciudad se ha convertido en un icono para este tipo de eventos. Ha ido a rituales, afterlife, conciertos de djs reconocidos. Es alterna, le gusta la moda en estilo alterno, aesthetic, le gusta mucho compartir su vida en redes sociales.

Luna consume muchas marcas hechas en Colombia, es descomplicada, es millenial por lo que maneja muy bien la tecnología, es muy activa. Vive en ciudad del rio y trabaja por la aguacatala en mattelsa. Tiene carro como medio de transporte pero los días que tiene pico y placa se va en bus. De actividad fisica le gusta trotar por su casa. Esta soltera, pero tiene varios pretendientes.

#### Journey Map

Conciencia
Luna esta navegando en redes sociales como instagram y tiktok donde le sale una publicidad del concierto. Luna esta caminando por la calle y en un paradero de bus encuentra una activacion del concierto (algo asi como creacion de visuales por medio de tracking de personas)

Adquisición
Luna entra a tu boletaa comprar las entradas, ingresa los datos para comprarlo como el correo, informacion personal, etc. Luna le llega un correo con las instrucciones que debe seguir para descargar la app y vivir la magia de la experiencia.

Pre concierto
Luna llega al lugar donde se realizara el concierto, va a ingresar por un torniquete que reconoce la cara con los datos de las personas ya que por la aplicacion Luna ingreso todos los datos en la app y como ya interactuo con esta, en un apartado la app le pidio hacer un tracking de cara con la finalidad de que en el concierto fuera más fácil el ingreso, y despues el envio de datos.

Despues, ya adentro, en el momento antes del concierto Luna compartirá con activaciones de marca con el objetivo de aprender a usar mejor la app y su interaccion en el concierto.

Servicio: Concierto
Empieza el concierto y luna tiene su celular preparado para interactuar con el concierto. Primero le llega una notificacion de que en unos segundos debe mover su cuerpo para generar visuales. Luna es enfocada con un reflector y baila haciendo que en las pantallas se generen visuales. Despues le llega una notificacion diciendole que tome el control de un laser rotando y dandole movimiento a su celular.

Fidelidad: Feedback
Luna se va del concierto y dias despues le llega un feedback de la experiencia vivida, la visual que generaste, un dibujo de la proyeccion de laser que hizo(tipo de varita magica disney channel). Mini historia de la persona en el concierto, etc. Here is a preview of the journey map looks now.

### Servicios

Al hacer el journey map tuvimos varios insights.

1. Para manejar todas las experiencias, hacer un buen pre del concierto, interactuar con marcas alidas que se quieran unir al proyecto, etc. Es necesario crear una app.
2. Las personas deben tener antes del concierto un tipo de feedback sobre como podran usar su telefono en el concierto.
3. Con lo anterior, hay muchas oportunidades de crear mini experiencias con activaciones de marca para que las personas antes de entrar en si al show ya hayan experimentado con la app y sepan usarla.


### App

Creamos un prototipo de app que esta en el sigueinte link, donde se simula como será, que tendrá. En este caso tiene tres apartados. EL primero de usuarios, donde se guarda tu informacion general y tu boleto. El segundo apartado que viene seindo el de las experiencias, donde las personas ingresaran directamente a los prototipos que creamos como el de manejar el laser y los faders de la distorsión de partículas. Y el tercero donde hay un apartado para las marcas patrocinadoras que les darán beneficios a los usuarios.

https://conciertolive-gixk.glide.page

###
