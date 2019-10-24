# Tarea para DI02.
Enunciado.
La empresa BK continua con el desarrollo de las interfaces para la aplicación de gestión hotelera.
---------------------------------------------------------------------------------------------------
* Entre otras cosas los usuarios también pueden hacer reservas de los salones de los que dispone el Hotel para eventos, congresos, etc.
* La práctica que debes realizar consiste en crear una interfaz que permita gestionar la reserva de uno de estos salones, llamado "Salón Havana".
 
Los requisitos que debe cumplir esta interfaz son:
------------------------------------------------------
* Se debe escribir el nombre y teléfono de contacto de la persona que hace la reserva.
* Hay que cumplimentar:
* 1 Fecha del evento.
* 2 Tipo, se puede escoger entre Banquete, Jornada o Congreso.
* 3 Número de personas que asistirán.
* 4 Tipo de cocina que se precisará, a elegir entre Bufet, Carta, Pedir cita con el chef o No precisa.
* preguntar si se requerirán habitaciones para los asistentes al evento.
* Si se activa el tipo de evento Congreso el usuario deberá poder cumplimentar el número de jornadas del congreso.
La interfaz generada irá conectada a la interfaz principal de la aplicación que se ha desarrollado durante el estudio de la unidad mediante el menú principal y un botón que abrirá la interfaz.

Criterios de puntuación. APTO/NO APTO
--------------------------------------------------------------
* Creación de la interfaz empleando nombres y ToolTipText para los elementos de formulario adecuado.
* Asociar buddies y establecer el orden de tabulación.
* Asociar un layout apropiado.
* Crear las conexiones signal/slot.
* Crear el fichero .java y añadirlo al proyecto.
* Añadir la funcionalidad programada.
* 1 Mostrar o no los widgets para el número de días del congreso.
* 2 Código para abrir el dialogo nuevo desde el menú y desde el botón de la interfaz principal.
* 3 Se valorará positivamente que seas original y hagas aportaciones propias, por ejemplo, incluyendo una imagen en la interfaz.

# Recursos necesarios para realizar la Tarea.
Para realizar esta tarea debes partir de los archivos con el ejemplo desarrollado a lo largo de la unidad y que puedes encontrar en el siguiente enlace:
* Fuentes para realizar la práctica.(900 KB)
# Consejos y recomendaciones.
* Se pretende poner en práctica los conceptos aprendidos, de la forma más clara posible, por lo que te recomiendo que hagas un diseño previo de la interfaz y estudies dónde se van a posicionar los elementos de formulario para evitar tener repetir varias veces el proceso ya que cada vez que tenemos que generar la interfaz de nuevo con juic el archivo anterior se borra y los cambios realizados se pierden.

* Esta aplicación puede tener gran cantidad de funcionalidades, la seleccionada es una más entre todas ellas, trata de explorar otras posibilidades, como el alta de personal o la gestión de nóminas para seguir practicando con esta técnica.

Indicaciones de entrega.
UTILIZA LA OPCIÓN DE NETBEANS 11 PARA EXPORTAR EL PROYECTO A ZIP.

Una vez realizada la tarea tendrás que comprimir los archivos del proyecto incluido el archivo con la interfaz XML. La estructura de archivos a entregar dentro del archivo comprimido es como sigue:

Dentro de un directorio de nombre interfaces:
-----------------------------------------------
* La interfaz principal, con el nombre de archivo frmPrincipal.jui.
* La interfaz para dar de alta una reserva con el nombre de archivo frmAlta.jui.
* La interfaz para realizar la reserva del salón Havana tal y como de ha especificado más arriba en un archivo llamado frmHavana.jui.
* Un directorio llamado recursos con la imagen que aparece en la interfaz principal.
Dentro de un directorio llamado programa:
-------------------------------------------------
* El correspondiente archivo .java con la clase de los tres archivos .jui, recuerda que debes renombrarlos.
* El archivo Main.java con la clase Main.
* Un archivo llamado recursos.jar con la imagen.
* El envío se realizará a través de la plataforma de la forma establecida para ello, y el archivo se nombrará siguiendo las siguientes pautas:
