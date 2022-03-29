Reto de Urbvan para BI

Para este reto se solicito lo siguiente:

I. Base de datos
Usando los archivos .csv que le proporcionamos:
  ❖ Hacer una base de datos PostgreSQL.
  ❖ Normalice la BD (tanto como considere necesario).

II. Inteligencia de negocios
Para cada año nos gustaría saber:
  1. Las estaciones más populares.
  2. Las áreas más populares (barrios en NY) [BONIFICACIÓN: si nos proporciona un
     geovisualización de los datos].
  3. Localizar los lugares de mayor interés y que potencialmente podrían influir en la movilidad
  4. La tendencia para cada día de la semana.
  5. Cuánto dura cada viaje para un día y área determinados.
  6. Obtenga información sobre el comportamiento de sus clientes.
  7. BONIFICACIÓN: cualquier otra exploración de datos que considere para brindarnos información relevante.


Además, ¿cuál es el impacto que ha tenido la pandemia en los negocios? Siéntase libre de responder a esta pregunta
como creas que es mejor. Aquí, queremos evaluar las siguientes habilidades:
  ● Comprensión empresarial
  ● Pensamiento analítico
  ● Narración de datos


Siendo el resumen de los hallazgos obtenidos la sigueinte información.

Los principales allazgos sobre los usuarios son:

    * La mayor parte de los usuarios hacen uso en la ciudad de jersey, lo que hace pensar que el concentrado de las bicis se encuentra ahi.
    * El día que más viajes se hacen son los días miercoles.
    * El día que mas tiempo usan en promedio la bicicleta es el día sabado.
     
Contrastando los dos ultimos puntos pasa algo interesante, podriamos decir que el miercoles es el día que mas viajes se hacen por que es cuando menos tiempo la usan, dando posibilidad a que las bicis esten disponibles para un numero mayor de usuarios, lo cual podriamos comprobar, si existe la información del numero de biciletas totales y el dato de bike_id para rastreaer el uso de  las biciletas por hora y determinar si a cierta hora del día ya no existen bicis disponibles haciendo que se reduzca el numero de viajes diarios.

Durante la exploración de la información observe que existian datos que antes de la pandemia se recolectaban como el tipo de usuario,el año de nacieminto del usuario, sexo pero despues de la pandemia esa información era nula, haciendo que una perfilación de clientes sea mas complicada, ya que al menos esas dos ultimos datos son muy utiles, para saber que publico esta haciendo mayor uso del producto y tal vez lanzar una campaña especifica o abrir nuevas rutas a sitios de interes para ese sector de la población ya sea por edad o sexo, obviamente complementando con otras variables como sus rutas principales o distancias recorridas.


Y para culminar de acuerdo con la información presentada en este documento, podemos argumentar que de acuerdo al numero de viajes y el tipo de usuarios de los años 2020 y 2022, exluyendo al 2021 donde la mayoria de las personas estabamos resguardados, la pandemia le hizo bien al negocio ya que existio un incremento en estos dos indicadores.

Lo que faltaria por analizar es el concepto del negocio, si es mas coveniente tener usuarios casuales o suscritos, ya que se incrementaron el numero de viajes por usuarios casuales haciendo que el incremento no sea proporcional para la distribución del 2020 y se tendria que checar la razon de esa desproporción en el crécimiento de los usuarios con suscripción.

En resumen para tener algo mas robusto seria bueno complementar con mas información del usuario, no solo de los viajes, por ejemplo un identificador de usuario para saber de todos esos viajes cuantos usuarios unicos los realizaron y complementar con otras variables para hacer un mejor estudio tanto de la población como de la situación general post-pandemia.
