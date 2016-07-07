**Formá Cultura**
===========

Descripción General
-------------------

El sistema como un conjunto de elementos relacionados entre sí busca facilitar el acceso a la información de los artistas quetzaltecos y al mismo tiempo
brindar datos que generen nueva información y de forma continua a la toma de decisiones para la dirección de la Casa de la
Cultura.

El benefactor en este sistema a desarrollar será el artista que podrá influir
en la creación de eventos, nuestro artista al momento de crear un evento asignar a este evento un usuario o varios.
Así también encontramos al usuario como persona que estará registrada en el
sistema, notese bien, que el visitante solo es la persona que hace uso de la
aplicación sin necesidad de registro. El usuario hará uso de la aplicación para
poder contactar de forma eficaz y eficiente a un artista, el usuario está
dotado para poder modificar su perfil, recibir en determinado tiempo una
cápsula de información cultural, ver la información de un artista cómo también
la información de un evento, al mismo tiempo como visitante registrado el usuario podrá escribir reseñas de los eventos a los cuales ha asistido.

El administrador del software que según el organigrama cedido por nuestro intermediario será el encargado de la rama de comunicación
podrá a manera de gestión; poder revisar información de un evento cómo de un artista, al momento de revisar dicha información el administrador podrá autorizar un evento o la información ingresada de un artista.

El poder enviar cápsulas informativas el administrador se encargará de esta parte, de tal manera que pueda crear, modificar una cápsula y poder agregar fecha de publicación de la misma. Las estadísticas serán evaluadas para su posterior uso de decisiones que conlleven a poder enforcarse más en cierta rama de arte.


-------
Modulos
-------

 - Gestión Artista
 ^^^^^^^^^^^^^^^^^
Este módulo va estar encargado del registro del artista en el sistema, este módulo otorga al artista modificar incluir en su perfil información acorde al arte en desarrollo, poder crear eventos, toda información debe ser validada por el administrador.
 
    Diagrama de caso de uso: :ref:`Artista <referencia-b>`.

 - Gestión Usuario
 ^^^^^^^^^^^^^^^^
El control sobre los usuarios permite, que los visitantes se registren en el sistema, que puedan consultar eventos y confirmar la asistencia a dichos eventos, poder contactar a un artista y recibir cápsulas informativas; la información está validada también por el administrador.

    Diagrama de caso de uso: :ref:`Usuario <referencia-c>`.

 - Gestión Evento
 ^^^^^^^^^^^^^^^^
Este módulo esta encargado de la creación de eventos, los cuales pueden ser creados por el artista o el administrador; al crear un evento debemos asignar un lugar, una fecha y hora, una descripción; y si es un administrador podrá agregar una prioridad al evento y verificar la información creada. Los eventos estarán agregados al calendario.

-Estadística
^^^^^^^^^^^^
El control sobre los datos que nos genera el sistema está a cargo de un administrador, el cual tiene acceso total a los datos y las estadísticas de los eventos, estos datos son recolectados en la base de datos del sistema, datos como total de participantes en un evento, fechas de eventos con mayor ingreso, etc.

- Administrador
 ^^^^^^^^^^^^^^
El administrador es el principal actor del sistema, ya que este tiene acceso total a los datos del sistema, además de poder verificar datos de artistas, usuarios y eventos. Las cápsulas que se envían a los usuarios en programada fecha están a cargo de él así como toda gestión de información controlada.

  Diagrama de caso de uso: :ref:`referencia-d`.
  
  
Caso de Uso General:  :ref:`Administrador <referencia-a>`.
