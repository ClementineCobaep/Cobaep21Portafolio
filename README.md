<html>
<head>
</head>
<body>
<a name="10"><font size="+3" color="black">Colegio de Bachilleres del Estado de Puebla </font><br>
<font size="+3" color="black">Plantel 21   U.H. Loma Bella</font><br>
	<font size="+3" color="black">PORTAFOLIO</font><br>

            <font size="+3" color="black">INFORMATICA</font><br>
	<font size="+2" color="black">Alumno:</font><br>
	<font size="+2" color="black"> Grupo D  	No. Lista:  T/Vespertino</font><br>
<font size="+2" color="black">    Generacion 2017-2020</font><br>
	
<font size="+2" color="black">Profesor : Oscar Ojeda Diaz</font><br>
<font size="+2" color="black">Menu</font><br>
-----<font size="+2" color="black">3er Semestre</font>
<ol>
<li><a href="#1"><font size="+2" color="black">Gestion de Archivos</font><a /></li>
<li><a href="#2"><font size="+2" color="black">Hoja de Calculo</font><a /></li>
</ol>
-----<font size="+2" color="black">4to Semestre</font>
<ol>
<li><a href="#3"><font size="+2" color="black">Mantenimiento</font><a /></li>
<li><a href="#4"><font size="+2" color="black">Comunidades Virtuales</font><a /></li>
</ol>
-----<font size="+2" color="black">5to Semestre</font>
<ol>
<li><a href="#5"><font size="+2" color="black">Programacion</font><a /></li>
<li><a href="#6"><font size="+2" color="black">Sistemas de Informacion</font><a /></li>
</ol>
-----<font size="+2" color="black">6to Semestre</font>
<ol>
<li><a href="#7"><font size="+2" color="black">Paginas Web</font><a /></li>
<li><a href="#8"><font size="+2" color="black">Diseño Digital</font><a /></li>
</ol>
<br>
<br>
<br>
<font size="+5" color="black">3ER SEMESTRE</font><br>
<a name="1"><font size="+3" color="black">Gestion de Archivos</font></a><br>
<div>
<p>Una de las principales tareas del sistema operativo es proporcionar comodidad al usuario cuando trabaja con datos almacenados 
<p>en discos. Para hacer esto, el sistema operativo reemplaza la estructura física de los datos almacenados con un modelo lógico
<p> fácil de usar, que se implementa en forma de un árbol de directorios que se muestra en utilidades como Norton Commander, 
<p>Far Manager o Windows Explorer. El elemento básico de este modelo es un archivo que, al igual que el sistema de archivos en 
<p>su conjunto, se puede caracterizar tanto por su estructura lógica como física.
<p>Los archivos se almacenan en la memoria independientemente de la fuente de alimentación. 
<p>Una excepción es un disco electrónico cuando se crea una estructura en el sistema operativo que simula un sistema de archivos.

<p>Un sistema de archivos (FS) es un componente del sistema operativo que proporciona la organización de la creación,
<p> el almacenamiento y el acceso a conjuntos de datos con nombre: archivos.<p><br>

<p>El sistema de archivos incluye:</p><br>

<p>La colección de todos los archivos en el disco.</p>
<p>Conjuntos de estructuras de datos utilizadas para administrar archivos (directorios de archivos, descriptores de archivos, </p>
<p>tablas de asignación de espacio libre y ocupado en disco).</p>
<p>Un complejo de software de sistema que implementa varias operaciones en archivos: creación, destrucción, lectura, escritura,</p>
<p> nomenclatura, búsqueda.</p>
<p>Las tareas resueltas por el FS dependen del método de organización del proceso informático en su conjunto. El tipo más simple es FS en</p>
<p> sistemas operativos de usuario único y de programa único. Las funciones principales en un FS de este tipo están destinadas a resolver los siguientes problemas:</p><br>

<p>Nombramiento de archivos.</p>
<p>La interfaz del programa para aplicaciones.</p>
<p>Mapeo del modelo lógico del FS a la organización física del almacén de datos.</p>
<p>Estabilidad FS ante fallas de energía, errores de hardware y software.</p>
<p>Las tareas de FS son complicadas en los sistemas operativos multitarea que están diseñados para funcionar como un solo usuario, pero </p>
<p>proporcionan la capacidad de ejecutar múltiples procesos simultáneamente. Se agrega una nueva encomienda a las tareas enumeradas </p>
<p>anteriormente: compartir un archivo de varios procesos. El archivo en este caso es un recurso compartido, lo que significa que el FS debe</p>
<p> resolver todo el complejo de problemas asociados con dichos recursos. En particular: se deben proporcionar medios para bloquear el archivo</p>
<p> y sus partes, hacer coincidir copias, evitar carreras, eliminar puntos muertos. En los sistemas multiusuario, surge otra tarea: proteger los </p>
<p>archivos del acceso no autorizado de otro usuario.</p><br>

<p>Las funciones FS, que trabajan como parte de un sistema operativo de red, se vuelven aún más complejas; necesita organizar la </p>
<p>protección de los archivos de un usuario contra el acceso no autorizado de otro.</p><br>

<p>El objetivo principal del sistema de archivos y su correspondiente sistema de administración de archivos es organizar</p>
<p> una conveniente gestión organizada de estos: en lugar de un acceso de bajo nivel a los datos que indican direcciones </p>
<p>físicas específicas del registro que necesitamos, el acceso lógico se utiliza con el nombre y el registro del archivo.</p><br>

<p>Deben distinguirse los términos "sistema de archivos" y "sistema de gestión de archivos": el primero tiene que ver con los </p>
<p>principios de acceso a los datos organizados como archivos. Y el segundo está relacionado con la implementación específica </p>
<p>del sistema de archivos, es decir este es un conjunto de módulos de software que proporcionan trabajo con archivos en un sistema</p>
<p> operativo específico.</p><br>

<p>TIPOS DE ARCHIVO<br>
<p>Archivos regulares: contienen información arbitraria que el usuario ingresa en ellos o que se forma como resultado del trabajo</p>
<p> del sistema y los programas del usuario. El contenido de un archivo normal está determinado por la aplicación que trabaja con él.</p>
<p>Los archivos normales pueden ser de dos tipos:<br>

<p>Software (ejecutable): son programas escritos en el lenguaje de comandos del sistema operativo y realizan algunas funciones </p>
<p>del sistema (tienen extensiones .exe, .com, .bat).</p>
<p>Archivos de datos: todos los demás tipos de archivos: textos y documentos gráficos, hojas de cálculo, bases de datos, etc.</p>
<p>Los directorios son, por un lado, un grupo de archivos combinados por el usuario por algunas razones (por ejemplo, archivos </p>
<p>que contienen programas de juegos o archivos que componen un paquete de software) y, por otro lado, este es un tipo especial </p>
<p>de archivo que contiene información de ayuda del sistema sobre un conjunto de archivos agrupados por usuarios de acuerdo con </p>
<p>algún atributo informal (tipo de archivo, su ubicación en el disco, derechos de acceso, fecha de creación y modificación).</p><br>

<p>Los archivos especiales son archivos ficticios asociados con dispositivos de entrada / salida que se utilizan para unificar el mecanismo</p>
<p> de acceso a archivos y dispositivos externos. Los archivos especiales permiten al usuario realizar E / S a través de los comandos habituales </p>
<p>de escritura o lectura desde archivos. Estos comandos son procesados ??primero por los programas FS y luego, en alguna etapa de la </p>
<p>ejecución de la consulta, el sistema operativo se convierte en comandos para controlar el dispositivo correspondiente </p>
<p>(PRN, LPT1 para el puerto de impresora - los nombres simbólicos para el sistema operativo son archivos, - USB para el teclado).</p><br>

<p>La gestión de archivos se da en la organización, almacenamiento y el acceso al conjuntos de estos, de modo que al cumplir </p>
<p>con sus funciones garanticen el cuidado y protección de la información que manejen. Por ello es importante conocer y aplicar este tipo de operaciones.</p><br>
</div><br>
<img src="G1.jpg" height="100" width="200">
<img src="G2.jpg" height="100" width="200">
<img src="G3.jpg" height="100" width="200">
<img src="G4.jpg" height="100" width="200">
<img src="G5.jpg" height="100" width="200">
<img src="G6.jpg" height="100" width="200">

<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<a name="2"><font size="+3" color="black">Hoja de Calculo</font></a><br>
<div>
Una hoja de cálculo es un programa informático que permite manipular y realizar cálculos complejos con datos numéricos almacenados en tablas. También permite automatizar tareas mediante el uso de fórmulas y macros, y crear gráficos como histogramas, curvas, cuadros de sectores, etc.

Por lo tanto, una hoja de cálculo es una herramienta multiuso que sirve tanto para actividades de oficina, que implican la organización de grandes cantidades de datos, como para niveles estratégicos y de toma de decisiones al crear representaciones gráficas de la información sintetizada.
Las principales hojas de cálculo
Las más importantes compañías de software han desarrollado hojas de cálculo, que suelen incluirlas en los paquetes ofimáticos que ofrecen. Entre las principales hojas de cálculo se encuentran Microsoft Excel (Microsoft Office), Sun StarOffice Calc (StarOffice), OpenCalc (OpenOffice), IBM/Lotus 1-2-3 (SmartSuite), Corel Quattro Pro (WordPerfect), KSpread (Koffice).
</div><br>
<img src="H1.jpg" height="100" width="200">
<img src="H2.jpg" height="100" width="200">
<img src="H3.jpg" height="100" width="200">
<img src="H4.jpg" height="100" width="200">
<img src="H5.jpg" height="100" width="200">
<img src="H6.jpg" height="100" width="200">


<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<font size="+5" color="black">4TO SEMESTRE</font><br>
<a name="3"><font size="+3" color="black">Mantenimiento</font></a><br>
<div>
<p>Mantenimiento y redes de computo:</p>
<p>1. Siempre utiliza tu computadora con un SAI (sistema de alimentación ininterrumpida) ya que te ayudará a protegerla de picos de tensión. </p>
<p>Las líneas telefónicas para los módems y los cables de red CAT 5 y CAT 6 también necesitan protección contra los picos de tensión, ya que</p>
<p> pueden y dañarán tu tarjeta de red o módem durante una tormenta eléctrica.</p><br>

<p>2. Limpia tu computadora. El polvo puede acumularse en tu computadora en menos de un año, dependiendo de dónde la coloques. </p>
<p>Limpia el polvo en la base utilizando una aspiradora (o paño), luego utiliza aire comprimido en lata.</p>

<p>3Los pasos para el mantenimiento fisico preventivo al cpu son:</p>

<p>*Retire los tornillos y colóquelos.</p>
<p>*Retire la tapa de la carcasa.</p>
<p>*Haga un diagrama de la posición del cable y de los componentes, para que conozcamos la ubicación de cada uno de ellos.</p>
<p>*Desconectar los buses de datos.</p>
<p>*Desconecte los cables de alimentación.</p>
<p>*Desconectar el ventilador y el microprocesador.</p>
<p>*Utilice un ventilador o aire comprimido para limpiar el ventilador y el microprocesador.</p>
<p>*Retire la tarjeta de expansión.</p>
<p>*Quitar tarjetas de red, sonido, vídeo, etc.</p>
<p>*Retire la placa madre.</p>
<p>*Retire la memoria RAM.</p>
<p>*Limpie las tarjetas con el soplador o con aire comprimido.</p>
<p>*Contactos limpios de tarjetas de expansión y memorias RAM con el borrador blanco.</p>
<p>*Retire las unidades de almacenamiento: unidad de disquete, unidad de disco duro y unidad de CD-ROM.</p>
<p>*Limpie externamente los componentes mencionados anteriormente con alcohol isopropílico y una toalla limpia y sin pelusas.</p>
<p>*Limpie el exterior con un limpiador de espuma y retírelo con una toalla limpia y sin pelusas.</p>
<p>*Vuelva a montar la CPU y todos sus componentes.</p>
</div><br>

<br>
<div>
<p>Mantenimiento del software: </p>

<p>La revisión de instalación por SETUP:</p>

<p>Consiste en una revisión que se realiza ingresando directamente al menú que se encuentra en la setup detectando las unidades conectadas ala </p>
 <p>computadora. Mediante este se puede detectar alguna falla en conectores.</p>

<p>La desfragmentacion de disco duro</p>:

<p>la desfragmentacion es el proceso en el cual se acomodan los archivos de un disco, este se realiza cuando el disco se fragmenta, esto sucede </p>
<p>cuando el sistema ha escrito diferentes versiones de los archivos, esto es, cuando un archivo después de ser modificado no ocupa direcciones</p>
<p> de memoria contiguas en el disco duro.</p>

<p>La eliminación de archivos TMP (temporales):</p>

<p>Este proceso consiste en la eliminación de los archivos generados por las aplicaciones instaladas en la computadora y que ya no se utilizan.</p>

<p>Liberación de espacio en el disco duro:</p>

<p>El liberador de espacio busca en la unidad y enumera los archivos temporales, archivos de cache de Internet y archivos de programa innecesarios</p>
 <p>que puede eliminar de forma segura.

<p>Ejecución de Antivirus:</p>

<p>Este se utiliza para realizar una analisis del sistema en busca de algun virus.</p>
<p> Aunque hoy en dia, la eliminación de un virus se convierte en una tarea titanica ya que estos han ido evolucionando hasta ser casi indetectables.</p>

 

<p>Papelera de reciclaje:</p>

<p>La papelera de reciclaje no es más que una carpeta más, creada por Windows para almacenar los archivos que el usuario desea eliminar del computador,</p>
<p> solo que el usuario en ciertas veces cambia de parecer con respecto a borrar dicha información, entonces ahí esta otra función de la papelera de reciclaje.</p>
<p> Es recomendable mantenerla limpia para evitar una acumulacion de archivos que no se esten utilizando.</p>
</div><br>
<img src="M1.jpg" height="100" width="200">
<img src="M2.jpg" height="100" width="200">
<img src="M3.jpg" height="100" width="200">
<img src="M4.jpg" height="100" width="200">
<img src="M5.jpg" height="100" width="200">
<img src="M6.jpg" height="100" width="200">
<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<a name="4"><font size="+3" color="black">Comunidades Virtuales</font></a><br>
<div>
<p>Comunidades Virtuales:</p>
<p>Las comunidades son un grupo de personas con objetivos común que se caracterizan por la comunicación entre ellos. </p>
<p>Son aquellas cuyos integrantes libre voluntariamente comparten uno o varios objetivos.</p><br>

<p>Características</p><br>

<p>Las bases comunes a las comunidades virtuales son:</p><br>

<p>Moderación. Todas las comunidades tienen normas y roles de usuarios. Las normas tienen recompensas como pasar de contribuyente a moderador o castigos</p> <p>como puede ser la expulsión del grupo</p>

<p>Protocolo común. Todos los miembros se comunican de forma homogénea para poder entenderse y evitar divisiones.</p>

<p>Interacción. Sin interacción la comunidad pierde todo el sentido, aunque también se pueden definir diferentes tipos de interacción, </p>
<p>como puede ser libre, sin moderación, o censura con moderación.</p>

<p>Filiación. La afiliación puede tener carácter voluntario sin características específicas o que requieran el cumplimiento de algún requisito, </p>
<p>por ejemplo el de ser abogado o médico.</p><br>

<p>Ejemplos:</p>
<p>*Redes sociales</p>
<p>*Foros</p>
<p>*Páginas wiki</p>
</div><br>
<img src="C1.jpg" height="100" width="200">
<img src="C2.jpg" height="100" width="200">
<img src="C3.jpg" height="100" width="200">
<img src="C4.jpg" height="100" width="200">
<img src="C5.jpg" height="100" width="200">
<img src="C6.jpg" height="100" width="200">

<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<font size="+5" color="black">5TO SEMESTRE</font><br>
<a name="5"><font size="+3" color="black">Programacion</font></a><br>
<div>
<p>Un ejemplo de nuestro trabajo esta en los proyectos de arduino que fueron expuestos en nuestro plantel y hechos por nosotros, </p>
<p>estos proyectos constaban de iniciar/crear un codigo para hacer funcionar algo en especifico como un radar o un sistema de riego. </p><br>
<br>
<p>La programación hace referencia al efecto de programar, es decir, de organizar una secuencia de pasos ordenados</p><br>
<p> a seguir para hacer cierta cosa.</p><br>

<p>En el ámbito de la informática, la programación refiere a la acción de crear programas o aplicaciones, a través del desarrollo</p>
<p> de un código fuente, el cual se basa en el conjunto de instrucciones que sigue el ordenador para ejecutar un programa.</p>
<p>Estas instrucciones se encuentran escritas en lenguaje de programación que luego son traducidas a un lenguaje de máquina, </p>
<p>que puede ser interpretado y ejecutado por el hardware del equipo (parte física del equipo). Dicho código fuente es creado, diseñado, codificado</p>, </p>
<p>mantenido y depurado a través de la programación, donde el principal objetivo a lograr es el desarrollo de sistemas que sean </p>
<p>eficaces, accesibles y agradables o amigables para el usuario.</p>
<p>Lo que aprendimos la estructura de la programación  para realizar nuestras propias páginas por medio de HTML desde un código fácil y sencillo.</p>

</div><br>
<img src="P1.jpg" height="100" width="200">
<img src="P2.jpg" height="100" width="200">
<img src="P3.jpg" height="100" width="200">
<img src="P4.jpg" height="100" width="200">
<img src="P5.jpg" height="100" width="200">
<img src="P6.jpg" height="100" width="200">

<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<a name="6"><font size="+3" color="black">Sistemas de Informacion</font></a><br>
<div>
<p>Gestión de archivos: Esta materia nos ayudo a controlar y ordenar mejor nuestros archivos, en especial comenzamos </p>
<p>a dominar unpoco mas el Excel, realizamos diversas actividades, entre ellas la base de datos, una herramientta útil para el campo laboral.</p>
<p>Programación: Una de las materias mas importantes de nuestro ciclo escolar que nos explica el arduo trabajo detrás de algunos </p>
<p>elementos como las páginas web y otros sistemas, prácticas como arduino nos ayudaron bastante.</p>
<p>G.D.A Base de datos de la biblioteca escolar; basandonos en los datos que tenía la bibliotecario y con el conteo </p>
<p>de algunos más logramos registrar ordenadamente uno y cada uno de los libros, y asi entrar en PHP para crear nuestra</p>
<p> propia base de datos y consultarla</p>
</div><br>
<img src="S1.jpg" height="100" width="200">
<img src="S2.jpg" height="100" width="200">
<img src="S3.jpg" height="100" width="200">
<img src="S4.jpg" height="100" width="200">
<img src="S5.jpg" height="100" width="200">
<img src="S6.jpg" height="100" width="200">

<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<font size="+5" color="black">6TO SEMESTRE</font><br>
<a name="7"><font size="+3" color="black">Paginas Web</font></a><br>
<div>
<p>Una Página Web es conocida como un documento de tipo electrónico, el cual contiene información digital, la cual puede venir dada por </p>
<p>datos visuales y/o sonoros, o una mezcla de ambos, a través de textos, imágenes, gráficos, audio o vídeos y otros tantos materiales dinámicos </p>
<p>o estáticos. Toda esta información se ha configurado para adaptarse a la red informática mundial, también conocida como World Wide Web.</p><br>

<p>Página Web</p><br>

<p>Las páginas web o como también son conocidas las web page por su nombre en inglés se encuentran contenidas dentro de los sitios </p>
<p>web o websites, que son mejor conocidos por los desarrolladores con el nombre de dominios, que almacenan o alojan el contenido que se</p>
<p> desarrollan para ser visualizados o usados por el usuario.</p><br>

<p>Todo lo mencionado anteriormente se trata de datos virtuales, pero el sitio físico donde se almacenan todos esos documentos se le </p>
<p>denomina servidores o hosting, que se puede definir como un ordenador conectado constante a Internet para poder acceder a las</p>
<p> páginas web a cualquier hora y desde cualquier lugar. A las páginas web se puede ingresar a través de navegadores o buscadores,</p>
<p>entre los más famosos están Chrome, Mozilla e Internet Explorer.</p><br>

<p>El lenguaje bajo el cual funcionan las ciber páginas se llama HTML, un formato de programación que permite tener acceso a diferentes</p>
<p> páginas web a través de enlaces de hipertexto, los cuales también son conocidos como links, es decir, dentro de un documento</p>
<p> electrónico puede estar contenido otro, que de acceso bien sea a otra parte de la misma página web o simplemente a otra página, </p>
<p>su objetivo básico es facilitar la investigación por medio de la navegación de distintos contenidos. El formato HTML está compuesto </p>
<p>por códigos, pero para el usuario común no se manifiesta de este modo, debido a que los navegadores leen los documentos en HTML</p>
<p> posteriormente lo traducen en las imágenes, textos y sonidos que mencionamos anteriormente y los muestra al usuario en esas </p>
<p>presentaciones para que pueda ser mejor interpretado.</p><br>

<p>Las páginas web presentan variados y atractivos diseños para los distintos usuarios que pueda tener, para que de este modo sea un medio</p>
<p> entretenido, funcional, educativo, ilustrativo, productivo y divertido.</p><br>
</div><br>
<img src="W1.jpg" height="100" width="200">
<img src="W2.jpg" height="100" width="200">
<img src="W3.jpg" height="100" width="200">
<img src="W4.jpg" height="100" width="200">
<img src="W5.jpg" height="100" width="200">
<img src="W6.jpg" height="100" width="200">
<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................
<a name="8"><font size="+3" color="black">Diseño Digital</font></a><br>
<div>
<p>cuya actividad consiste en proyectar comunicaciones visuales destinadas a transmitir mensajes específicos a grupos sociales</p>, 
<p>con objetivos determinados. Esta actividad ayuda a optimizar las comunicaciones gráficas. También se conoce con el nombre</p>
<p> de diseño en comunicación visual, diseño de comunicación visual o diseño digital.</p>
<p>Lo que aprendimos fue a vectorizar imágenes, a crear nuestros propios diseños en base a otros, también a imprimir nuestros </p>
<p>diseños en playeras, maus pad y tazas.</p>
<p>con objetivos determinados. Esta actividad ayuda a optimizar las comunicaciones gráficas. También se conoce con el nombre de </p>
<p>diseño en comunicación visual, diseño de comunicación visual o diseño digital.</p>
<p>Lo que aprendimos fue a vectorizar imágenes, a crear nuestros propios diseños en base a otros, también a imprimir nuestros </p>
<p>diseños en playeras, maus pad y tazas.</p>
</div><br>
<img src="D1.jpg" height="100" width="200">
<img src="D2.jpg" height="100" width="200">
<img src="D3.jpg" height="100" width="200">
<img src="D4.jpg" height="100" width="200">
<img src="D5.jpg" height="100" width="200">
<img src="D6.jpg" height="100" width="200">

<a href="#10"><font size="2" color="black">REGRESAR</font><a />........................................

<font />
</body>	
</html>
