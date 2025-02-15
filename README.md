<i> Se recomienda el uso y visualización del archivo adjunto, el cual será comentado a lo largo de todo el tutorial y, mostrará una visualización más detallada y orientativa para este tutorial mencionado.</i>

<h1> 3.	Odoo </h1>
A continuación, se dará a conocer el uso de Odoo, realizando la instalación en un servidor, y la instalación de varios módulos, configurándolos y cumplimentando algunos datos en ello. 
Para la instalación de Odoo se recomendará una VirtualBox previamente descargada e instalada, donde se realizará la instalación. A continuación, se expondrá una serie de capturas donde se irá explicando por cada apartado, los pasos a seguir para una instalación, configuración y uso correctos para Odoo.
  ------------
  3.1.	Instalación de Odoo.
  
  3.1.1.	Tras haber iniciado nuestra VirtualBox (Oracle VirtualBox) en adelante mencionada en este documento como V.B., nos descargaremos el archivo “.ova” encontrado en: https://bitnami.com/stack/odoo/virtual-machine o descargado previamente. En la siguiente captura, una vez descargado se muestra donde se encuentra dicho archivo dentro de la localización marcada como "descargar" de nuestro dispositivo en uso. 
  
  3.1.2.	Tras la localización de nuestro archivo, procedemos con nuestra V.B. a la instalación. En el documento se mostrará la captura donde se visualiza que se le daría clic en “Archivo” --> “Importar un servicio virtualizado…”. 
   
  3.1.2.1.	Una vez descargado, se elegiría “bitnami-odoo-18.0.20241005-r0-debian-12-amd64.ova” y la opción de “Abrir”. 
  
  3.1.3.	Tras ello se nos habilitará una ventana, donde procederemos a marcar la configuración previa a la instalación de Odoo. Podemos dejar la configuración ya establecida, y darle a Terminar. 
   
  3.1.4.	Aceptaríamos todos los términos y condiciones necesarios para la instalación, como se muestra en la captura del documento adjunto. 
  
  3.1.5.	Una vez realizado el paso anterior, se nos mostrará una ventana en el lateral derecho de nuestro V.B. Administrador, donde se mostrará la importación del servicio virtualizado. Una vez finalizada dicha importación, se nos permitirá darle clic a la fecha verde “Iniciar”.
  
  3.1.6.	Tras ello se nos mostrará en pantalla una ventana de comandos, donde se está configurando e iniciando el Odoo instalado. 
  
  3.1.7.	Tras esto, en la “consola” de comandos de Bitnami para Odoo, aparece distinguida por colores las partes correspondientes. En la parte amarilla se indica los pasos necesarios para acceder a la aplicación de Odoo, siendo así que se muestra la dirección IP que poner en el navegador, los datos de acceso necesarios y otros datos de interés.
  
  3.1.8.	Se coloca la dirección IP que sale en la consola de Bitnami para Odoo que había iniciado en la VirtualBox, indicado en amarillo en la primera fila, “You can Access the application at http://192.168.1.137 ***”, en una pestaña del navegador, llegando a poder acceder como se indicaba en la aplicación de Odoo. Las credenciales que piden, son las que aparece justamente descritas a continuación de la primera línea donde aparecía la IP. Siendo en este caso el “username: user@example.com” y la contraseña *****Z1T+. Se da clic a “log in”. 
  
  3.1.9.	Una vez dentro, nos aparecerá la ventana principal de Odoo, donde se muestra las aplicaciones y un menú principal con todas las categorías y opciones. De primeras, en la esquina superior al lado de Apps, se mostrarán las aplicaciones instaladas y las opciones, mostradas hasta el momento en el idioma preestablecido como “Settings”. 
  
  3.1.10.	Seguidamente haciendo scroll con nuestra rueda de ratón y se selecciona “Languages” para añadir el español, pudiendo buscarlo directamente como “español o spanish” y optando por esto como elección de preferencia, siendo en este caso “Spanish/Español”.
   
  3.1.11.	Asimismo,se clickea a Add, y se configuraría para poder visualizar todo el proceso en Odoo, en el idioma indicado, siendo en este caso, español. 
  
  3.1.12.	Como se muestraría en el archvio adjunto de paso a paso, en la esquina superior al darle clic a guardar, ya estaría guardada la configuración elegida. 
   
  3.2.	Configuración de Odoo.
 
  3.2.1.	Para llegar a configurar los datos principales con la información que se aporta en la tarea en este caso, sobre la “Academia de formación “Poniente””. Se da clic sobre “Usuarios y compañías” y se seleccionará “Compañías”, mostrándose en pantalla lo visualizado en la captura adjuntada dentro del archivo. Como se puede ver en el documento, de base aparece “My Company” y lo que se quiere es poder añadir una nueva, siendo así que se le da a “Nuevo”. 
   
  3.2.2.	Tras esto, aparecerá los datos mostrados en la captura adjuntada en el documento. Dichos datos deberán ser rellenados, tanto con datos ficticios creados en un archivo XML anterior de una tarea realizada, como con datos no “requeridos” en la parte B delaa tarea 01, pero sí necesarios para abordar esta actividad. 
  
  Se incluye en este ejemplo un logo, siendo añadido este tras darle clic en “Your logo” y elegir la imagen que se quiera adjuntar como tal, en el formato que se permita identificado como imagen, siendo en este caso un archivo PNG. 
  
  3.2.3.	Tras rellenar y adjuntar el logo, la compañía quedaría definida y configurada como se muestra en la captura (archivo adjunto). 
   
  3.2.4.	Como se muestra en la captura (archivo adjunto), al poder llegar a darle de nuevo a “Compañías” saldría el listado de las compañías existente dentro del Odoo y, aparecería en este caso, la compañía creada por nuestra parte “Academia de formación “Poniente””. 
   
  3.2.5.	Para la opción de añadir lema de la compañía, como se pide en un subapartado de la tarea sería de la siguiente manera: 
  
  3.2.5.1.	Se iría nuevamente a la parte de “Ajustes” y se buscaría en las opciones generales, la opción de “Compañías” donde aparece “Configurar diseño de documento”. Se pincharía en esa opción.
  
  3.2.5.2.	 Como se muestra en la captura (archivo adjunto), se tendría una ventana donde se vería el diseño del documento que aparecerá, pudiendo incluir un logotipo y, en este caso, el lema, que se ha asignado siendo este “una empresa nueva”. Para guardar, se daría a “Continuar” indicado en el extremo izquierdo del cuadro de configurar el diseño. 
   
  3.3.	Creación de usuarios: 
 
  3.3.1.	Seguidamente, para la creación de dos usuarios, se volverá a dar clic en “Usuarios y Compañía” y dándole en esta ocasión, a la opción “Usuarios”. Como se muestra en la siguiente captura (archivo adjunto), nos saldrá el listado de usuarios que están disponibles o que existen dentro de Odoo y, para la creación de nuevos se le dará en la esquina superior a “Nuevo”.
   
  3.3.2.	Nos aparecerá una ventana donde indicar todos los datos oportunos, como nombre y dirección de correo electrónico; además de aparecer varias pestañas como “Permisos de acceso”, “Preferencias” y “Seguridad de la cuenta”. En esta ventana también da la opción de poder poner un logo o icono, que, en este caso al ser la creación del primer usuario, según la petición de la tarea, tenía que ser el profesor, y de ahí que se haya optado por un logo de profesor que represente a tal. 
   
  3.3.3.	Para la creación del siguiente usuario, se llegará a realizar los mismos pasos anterior y, en la captura anterior se muestra, además, el cómo se puede elegir y establecer las compañías permitidas, dentro de los permisos de acceso, llegando a dar un clic a la opción que se quiera. 
   
  3.3.4.	Al igual, que también según se observa en la siguiente captura (archivo adjunto), se puede elegir las preferencias oportunas, como idioma, zona horaria y cómo sería la firma de correo electrónico. Todo esto se ha realizado de la misma manera, con el primer usuario creado, pero se muestra solamente una vez el ejemplo (archivo adjunto), para no duplicar, puesto que son los mismos pasos. 
   
  3.3.5.	Como se puede visualizar en la captura de pantalla del archivo adjuntado, ya se tendría creado el segundo usuario, además, se muestra la forma de poder ir guardando manualmente si se quisiera, pudiendo señalar en el icono de la nube mostrada al lado del engranaje de opciones, del nombre de usuario.
  
  3.3.6.	Tras los pasos anteriores, se puede volver a darle a “Usuarios” y se podrá ver finalmente, el listado de usuarios internos que se tiene creado.
   
  3.4.	Informe de productos: 
  Para la propuesta de la tarea de este apartado correspondiente, se solicita la instalación del módulo inventario, crear tres productos diferentes (de mobiliario, por ejemplo: mesa, sillas, pizarras, …), generar un informe de productos creados y exportar dicho informe a una hoja de cálculo. Para todo esto, se mostrará los pasos a continuación: 
 
  3.4.1.	Se volvería a darle en la esquina superior al lado de “Ajustes” en el cuadrado, donde se da las opciones de “Aplicaciones” o propiamente “Ajustes”. Seleccionamos en este caso la opción que nos llevará a las aplicaciones. 
   
  3.4.2.	Como se muestra en la captura (archivo adjunto), en pantalla aparece todas las aplicaciones posibles de las cuales se tendrá la opción de actualizar o de activar. Si se le da a “Activar” se estaría, por lo tanto, instando la aplicación a elegir. Hay varias opciones de búsqueda, pero finalmente para una búsqueda más rápida, se puede optar por escribir donde la lupa, y poner la aplicación que estábamos buscando, siendo en este caso, “inventario”.
   
  3.4.3.	Una vez ya localizado, le daríamos a “Activar” para la instalación del módulo “Inventario”. 
  
  3.4.4.	Tras ello, aparecerá directamente en pantalla el módulo como tal, siendo en este caso, la pantalla principal de “Inventario”. 
  
  3.4.5.	Para la creación de productos, se puede ver como en la parte superior al lado de “Inventario” aparece otras opciones, como “Información general”, “Operaciones”, “Productos”, “Informes” y “Configuración”. Para la parte de creación de productos, se pincharía sobre “Productos” y accederíamos a este. 
   
  3.4.6.	En esta ventana saldrá todos los productos creados y se podrá ver cada producto su propia ficha. Para la creación de uno, será señalando a “Nuevo” ubicado en la parte superior al lado de “Productos”. 
   
  
  3.4.7.	Aparecerá una nueva ventana que se rellenará y, se le dará a “Actualizar la cantidad” para finalmente obtener esa cantidad de producto creado, como se muestra en ambas capturas a continuación (archivo adjunto). Se guarda todo automáticamente de tal manera, que cuando se vuelva al listado de productos, ya tendremos los nuestros. 
  
  3.4.8.	(irrelevante para el tutorial solo para la actividad práctica)
   
  3.4.9.	Para el siguiente punto requerido de la obtención del informe sobre los productos creado, el paso a seguir sería pinchar en la parte de “Informes” expuesta en la parte superior y en “Stock”. De tal manera que se nos mostraría la siguiente pantalla con todos los productos que se tienen.
  
  3.4.10.	Para poder generar el informe en una hoja de cálculo, se le daría en el engranaje mostrado al lado de “Stock” y “Exportar todo”. 
  
  3.4.11.	De esa manera, se nos descargaría un archivo en formato “.xlsx” siendo esta nuestra hoja de cálculo oportuna y requerida para el ejercicio, como se muestra en la captura (archivo adjunto), al abrir el archivo. 
  
  3.5.	Peticiones de mantenimiento. 
  Para este apartado, se pide instalar el módulo “Mantenimiento”, crear dos peticiones, una que esté en estado “En progreso” y otra, “Reparado. Además, de visualizar las peticiones en modo Kanban. Por ello, a continuación, se especificará los pasos a seguir con sus capturas correspondientes. 
 
  3.5.1.	Instalar el módulo “Mantenimiento”.
  
  3.5.1.1.	Para poder instalar el módulo de “Mantenimiento” se clickea en el cubo como anteriormente y se seleccionará “Aplicaciones”
  
  3.5.1.2.	Seguidamente, se buscaría “mantenimiento” y, una vez se haya encontrado el módulo, se le da clic a “Activar”. 
   
  3.5.1.3.	Al igual que en el anterior paso, se cargará la página una vez que se haya activado el módulo, y se podrá acceder a éste pinchando directamente en el cubo y seleccionando la opción que se quiera. 
   
  3.5.2.	 Crear dos peticiones, una que esté en estado “En progreso” y otra en estado “Reparado. 
  
  3.5.2.1.	Para la creación de las peticiones, se le da a la opción que sale en la ventana principal de “Mantenimiento” de “0 Pendiente” al no tener ninguno activo actualmente. 
  
  3.5.2.2.	Seguidamente para la creación de una petición se le daría a “Nuevo” presentado en la parte superior. 
   
  3.5.2.3.	Una vez se clickea a nuevo, se nos presenta esta pantalla principal donde se genera la petición que se estime. En este caso se va a crear la primera petición que se pide de “En progreso”. 
   
  
  3.5.2.4.	Para ello, se indicaría la solicitud de la petición en “Solicitud” indicando qué es lo que ocurre, se podría añadir como se muestra en la misma pantalla (archivo adjunto), notas, tipo de mantenimiento, duración, prioridad y otras opciones. Para colocarlo en proceso, solo haría falta señalarlo este en la parte superior, y en vez de señalar como “Nueva solicitud”, darle clic a la opción en este caso de “En proceso”.
  
  
  3.5.2.5.	De tal manera que al darle de nuevo a “Mantenimiento” se nos avisará que hay una petición pendiente (mostrada en la primera captura del archivo adjunto) y al pinchar en esta, se llevaría de nuevo a la ventana principal, donde se puede ver que se encuentra especificado la petición dentro de “En proceso” (segunda captura dentro del archivo adjunto).
   
  
  3.5.2.6.	Para realizar la segunda petición, se realizará el mismo proceso, pero esta vez, se pinchará en “Reparado” para crear esta petición. 
  
  
  3.5.2.7.	Otra posibilidad de creación sería, tanto crear una solicitud y arrastrarla en el panel principal hasta “Reparado” o hasta donde se quiera de las diferentes partes como etapas. Y, otra opción que se muestra a continuación que sería, directamente al darle al “+” y escribir directamente la petición. Dando como resultado finalmente, la petición creada. 
  
  
  3.5.2.8.	Como se muestra en este último pantallazo (archivo adjunto), ya estaría creada la segunda petición solicitada por la tarea, en este caso en “Reparado”. 
  
  3.5.3.	Visualiza las peticiones en modo Kanban.
  A la hora de hablar de la visualización de las peticiones en modo Kanban, estas han sido visualizada anteriormente, puesto que el tablero Kanban es justamente la captura anterior mostrada, y como se ha podido ver en anteriores capturas del módulo “Mantenimiento” donde se podía ver, crear y modificar cada petición. 
    
