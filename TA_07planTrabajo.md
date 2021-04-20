-Informe 03: 13 horas del viernes 16 de abril: INTRODUCCION DE PARAMETROS DE CULTIVO: para este informe se quiere hacer la programación que va a ser la presentación 
de la aplicación, la aplicación va a ser para el manejo de condiciones climáticas de un cultivo por lo tanto los primeros datos que deben ingresar a la aplicación deben ser
las variables que se van a controlar y sus respectivos rangos de valores óptimos, la presentación de la aplicación debería pedir las variables: 1)nombre del cultivo
2)rango de temperatura deseado, 3) rango de nivel de humedad optimo, 4) concentración de CO2 que resiste el cultivo 5) observaciones generales sobre el cultivo ;
estos serian los datos básicos para iniciar el control de variables climáticas en un cultivo, la idea es que puedan almacenarse datos de distintos cultivos creando así
una base de datos sobre los cultivos.

-informe 04: 13 horas del viernes 23 de abril: MEDICION DE TEMPERATURA: Después de tener la base de datos sobre los cultivos se inicia la fase de ejercer control sobre 
las variables climáticas, en esta semana la aplicación pretende experimentar con lo que es conectar un hardware como es Arduino y adicionalmente añadirle un sensor que
pueda medir la temperatura, la programación en esta parte nos debería indicar en tiempo real (o con intervalos de tiempo establecidos) la temperatura actual del cultivo
(o lugar de prueba), con este dato la aplicación debe relacionar la base de datos para verificar que la temperatura esta en el rango deseado para el cultivo, en caso de
no ser así esta deberá enviar algún mensaje de aviso de que la temperatura no esta en un rango optimo y por lo tanto deberá hacer una acción, la aplicación de momento no 
ejercerá una acción de respuesta inmediata, sin embargo deberá enviar un mensaje con una sugerencia de que hacer en caso de que la temperatura este por debajo del promedio 
arriba de este; par ala prueba de esta parte de la aplicación de pretende dejar el hardware conectado durante unas horas y que este tome mediciones libremente y en su registro
debe quedar que emitió señales de aviso cuando las condiciones no son las establecidas en la base de datos.

-informe 05: 13 horas del viernes 30 de abril: MEDICION DE HUMEDAD: Acá nuevamente se va a experimentar con el hardware de Arduino pero esta vez con un sensor de humedad, 
con la conexión de este nuevo sensor debería empezar a tomar forma la aplicación ya que la humedad y la temperatura esta directamente relacionadas y una acción que se tome 
para cambiar una de estas variables puede afectar directamente la otra, para hacer la prueba de esta parte de la aplicación se espera poder recrear un espacio cerrado donde
la temperatura y los niveles de humedad puedan aumentar, hacer la prueba de que la aplicación reporta niveles de temperatura y humedad por fuera de los deseados, que mande
la señal de que no esta bien y que de la sugerencia de que puede hacerse para nivelar estas variables, de poder llevarse con éxito el experimento se podrá controlar estos 
niveles mediante ventilación artificial y agregando cantidades de agua en forma de aspersión, haciendo esto la aplicación debería volver a indicar que los niveles son óptimos.

-informe 06: 13 horas del viernes 7 de mayo: CONTROL SOBRE LA LLUVIA: como se pretende que esta aplicación pueda servir para el uso de un invernadero o de un jardín con 
algún grado de inversión en tecnología, no se podía dejar fuera esta variable tan importante, es que la lluvia en un cultivo controlado puede ser muy perjudicial, puede
ser inundando el cultivo, dañándolo de manera directa con el constante caer de gotas etc., es por esto que nuevamente usando un sensor de Arduino se va a hacer la 
programación para que el cultivo pueda cerrar las posibles entradas de agua o para la apertura de cubiertas que protejan el cultivo, quizás para hacer la demostración
de que la aplicación sirve puede ser compleja debido a que no se cuenta aun con la infraestructura como para desplegar una acción dirigida desde la aplicación, pero si
se intentara recrear o mejor posible la condición para demostrar su funcionamiento en este tipo de sucesos.

-informe 07: 13 horas del viernes 14 de mayo: MEDICION DE GASES: nuevamente recurrimos a un sensor de Arduino, esta vez para poder hacer control sobre los gases que se
acumulan en el ambiente, esta parte de la aplicación pretende medir que los niveles de CO2 presentes en el cultivo no sobrepasen los valores críticos, a parte de ejercer 
la función de control sobre esta variable, también se espera que aporte algo de seguridad al cultivo, es decir que el sensor no solo deberá medir el CO del cultivo, 
también debe ser capaz de detectar con otra concentración de gas que pueda haber en el entorno y mandar una señal a la aplicación de que un gas inusual se esta concentrando, 
estos gases pueden ser metano o humo por poner ejemplos, la presencia de gases inusuales en un lugar cerrado es para considerar de cuidado y se espera que esta parte de
la aplicación pueda controlar esto.

informe 08: 13 horas del viernes 21 de mayo: COMPILCION DE DATOS: hasta el momento se ha estado llevando a cabo la parte de programación para medir todas las variables,
sin embargo el objetivo de la aplicación es el de ofrecer los datos climáticos del cultivo en tiempo real, por lo tanto la aplicación debe tener activa todos los sensores 
simultáneamente, se pedirá una entrada donde se pueda especificar que variable queremos saber en el momento o si queremos una combinación de estas variables o si queremos 
todas las variables al mismo tiempo; la aplicación como respuesta deberá arrojar los datos que se están midiendo en tiempo real y esta deberá dar estos datos en cualquier 
combinación que se le sea especificada arrojar, de esta manera la persona que use la aplicación podrá ver en cualquier momento del día como se encuentran las condiciones,
para demostrar que esta parte funciona correctamente se conectaran todos los sensores y se tomaran distintas pruebas durante varios momentos del día.

-informe 09: 13 horas del viernes 28 de mayo: BORRADOR: para esta fecha se espera poder recolectar toda la información de los informes anteriores y hacer un compilado con 
todo las pruebas significativas, hacer un análisis de todo el material y elegir el material que mejor demuestre el trabajo realizado.

-informe 10: 13 horas del viernes 3 de junio: DEFINITIVA: ya el informe con el material seleccionado para estar en el informe final, este esta presentado con las
especificaciones que se requieran.
