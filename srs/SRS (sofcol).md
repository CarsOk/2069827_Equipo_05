                                                                                                                      Pag.1

###### SRS

##### ESPECIFICAION  Y ANALISIS DE REQUISITOS DEL SOFTWARE

PROYECTO SOFCOL:(SOFTWARE COLEGIAL)

Aprendices:

	Héctor castro

	Dana arcón

	Luz de la rosa 

Ficha: 2069827

                                                                                                                       Pag.2


TABLA DE CONTENIDO


PAGINA
Especificación y análisis de requisitos del software ---------1

Índice -------------------------------------------------------2

1. Introducción ----------------------------------------------3


 1.1 Propósito -----------------------------------------------3

 1.2 Alcance (Ámbito del sistema) ----------------------------3

 1.3 Definiciones, Acrónimos y Abreviaturas ------------------3

 1.4 Referencias ---------------------------------------------3

 1.5 Apreciación Global --------------------------------------3


2. Descripción General ---------------------------------------4

 2.1 Perspectiva del Producto --------------------------------4

 2.2 Funciones del Producto ----------------------------------4

 2.3 Características de los Usuarios -------------------------4

 2.4 Restricciones -------------------------------------------4

 2.5 Suposiciones y Dependencias -----------------------------4



3. Requerimientos Específicos --------------------------------5


 3.1 Requerimientos Funcionales ------------------------------5

 3.2 Requerimientos no Funcionales ---------------------------5
 
 3.2.1 Requisitos de rendimiento -----------------------------5
 
 3.2.2 requisitos de seguridad -------------------------------5
 
 3.2.3 requisitos de fiabilidad ------------------------------5
 
 3.2.4 requisitos de mantenibilidad --------------------------5
 
 3.2.5 requisito  la estabilidad -----------------------------5
 



                                                                                                                       pag.3


 1. introducción

    En el presente documento se explicarán y analizarán los requisitos del proyecto “Software Colegial”, desarrollado por aprendices del SENA (Centro industrial y de aviación).
 
1.1 propósito


Nuestro propósito en la institución es mejorar el sistema que utilizan para almacenar toda la información ya que tiene muchas fallas en el orden, rapidez, para obtener la información y que los padres se les pueda facilitar saber toda la información de nuestra institución, también darles nuevas herramientas tecnológicas al sector administrativo para que su trabajo pueda ser más eficiente y los padres a la hora de necesitar información de sus hijos puedan conseguirla de una manera rápida y segura


1.2 Alcance (Ámbito del sistema)


   * Nombre del sistema: SOFCOL

   * El sistema será una aplicación web que gestionará los procesos administrativos y educativos de la institución ( ) haciendo modificaciones de registros de alumnos, personal docente y no docente; manejo de reportes (calificaciones, grupos, materias, horarios); Seguimientos a los alumnos de la institución (Datos personales e historial de calificaciones). No realizará transacciones bancarias.

   * El principal beneficiado con SOFCOL es la institución educativa ( ).

   * Se capacitará solo a 10 personas que la institución sugiera. La información que requiera este software será digitada por las 10 personas capacitadas o las que la institución contrate.

   *Este proyecto no incluye la compra de hosting, dominio.

  
1.3 Definiciones, Acrónimos y Abreviaturas

   *	UML: Lenguaje de Modelado Unificado

   * BD: BASE DE DATOS, Una base de datos es un conjunto de datos       pertenecientes a un mismo contexto y almacenados sistemáticamente para su posterior uso. En este sentido; una biblioteca puede considerarse una base de datos compuesta en su mayoría por documentos y textos impresos en papel e indexados para su consulta.

   * Sofcol: nombre asignado a la aplicación que significa "software de colegial " lo que quiere decir que este será implementado en una institución educativa.

   * Aplicación web: En la ingeniería de software se denomina aplicación web a aquellas herramientas que los usuarios pueden utilizar accediendo a un servidor web a través de internet o de una intranet mediante un navegador.
   
   * Capacitación: La capacitación se define como el conjunto de actividades didácticas, orientadas a ampliar los conocimientos, habilidades y aptitudes del personal que labora en una empresa. La capacitación les permite a los trabajadores poder tener un mejor desempeño en sus actuales y futuros cargos, adaptándose a las exigencias cambiantes del entorno.

   * Sector administrativo: un sector administrativo se integra por un conjunto de entidades de actividades afines bajo la responsabilidad de una secretaría, o cabeza de sector a través de la cual se planean, organizan, dirigen, controlan, ejecutan y evalúan las Acciones necesarias para cumplir con los programas del gobierno.
   

1.4	Referencias



  *https://es.wikipedia.org/wiki/Aplicaci%C3%B3n_web#:~:text=En%20la%20ingenier%C3%ADa%20de%20software,una%20intranet%20mediante%20un%20navegador


  
  * https://conceptodefinicion.de/capacitacion/


  * https://www.eco-finanzas.com/diccionario/S/SECTOR_ADMINISTRATIVO.htm#:~:text=B%C3%A1sicamente%20un%20sector%20administrativo%20se,con%20los%20programas%20del%20gobierno.


  * https://es.wikipedia.org/wiki/Base_de_datos

1.5 Apreciación Global


  En esta documentación se logra percibir los propósitos que tenemos con la creación de sofcol, cuales serán sus alcances y que avances puede hacer en nuestro país.

  Se sabe que las tecnologías son la aplicación de la ciencia a la resolución de problemas concretos y esto es lo que buscamos con la creación de sofcol que ayudara al desarrollo integral, educativo de las instituciones, además que deseamos que sea globalmente reconocido como una herramienta para el sector de la educación .

  Al crear sofcol no solo ayudamos a las instituciones sino que también se encargara de brindar seguridad y flexibilidad a las estudiantes ayudara a la automatización de los datos, su servicio será de grata importancia por que no solo cuidara de la información de las institucional sino que también ayudara al sector salud en algún momento de emergencia que se presente en cualquier institución siendo más practico con la generación de datos de gran importancia que pueden salvar la vida.
  



                                                                                                                         pag.4





  2. Descripción General
  En el siguiente archivo se denotan las descripciones de sofcol
 
2.1 Perspectiva del Producto
Sofcol se proyecta como un sistema que tendrá la capacidad del manejo de información descriptiva de los alumnos, en este caso datos personales (Situación Socioeconómica), sus materias y el llenado de algunos formatos propios de la institución, también se ofrece la administración de la información académica de dichos alumnos.

2.2	Funciones del Producto


 * Generación de reportes de calificaciones.
 * Vinculación de grupos y materias.
 * Captura y modificación de calificaciones.
 * Alta y baja de alumnos de la institución.
 * Alta y baja del personal docente en la nómina.


2.3 Características de los Usuarios

  El sistema cuenta con tres tipos de usuarios final:

  * El primero se conforma de capturistas o secretario: personas con nivel escolar promedio de preparatoria, deben tener conocimientos básicos de computación (Ofimática). “Nivel     Administrativo”.

  * El siguiente nivel lo constituyen sobre todo el personal docente, el cual incluye también a los directores; son personas con niveles de educación superior con capacidad de      manejo intermedio de equipo de cómputo. “Nivel Académico”.

  * En este nivel se encuentran los padres de familia, tal usuario está pensado que no sepa mucho de tecnología ni la sepa usar. “Padres de Familia”

2.4 Restricciones

  Respecto a la seguridad, se debe considerar el uso de sesiones para limitar el acceso a usuarios no autorizados.
  El cliente no ha especificado ninguna limitante y algunas características son del criterio de los desarrolladores.


2.5 Suposiciones y dependencias

  Para el funcionamiento completo del sistema, se requiere tener los navegadores más comunes (Chrome, Firefox y Explorer), lo más importante:
 
*conexión a internet 



                                                                                                                      Pag.5

  3. Requerimientos Específicos

3.1 Requerimientos Funcionales

  Requisitos funcionales del sistema por tipos de usuario.

  Académicos

  *	Manejo de la autenticación de usuario (Sesión)
  *	Dar de alta calificaciones 
  *	Modificar calificaciones
  *	Consultar listas de grupos y alumnos
  *	Generar reportes de todo lo mencionado anteriormente 

  Administrativo

  * Manejo de la autenticación del usuario (Sesión)
  * Dar de alta a alumnos
  * Dar de baja a alumnos
  * Dar de alta a personal docente
  * Dar de baja a personal docente 
  * Modificar calificaciones en caso que sea necesario
  * Consultar lista de grupos y de alumnos
  * Consultar lista de personal docente
  * Vinculación de grupos-horarios Familiares 
  * Consulta de calificaciones del alumno



3.2 Requerimientos no funcionales

  3.2.1 Requisitos de rendimiento 

  El sistema de tiene un rendimiento para una respuesta de un tiempo mínimo de 1 minuto y medio.

3.2.2 requisitos de seguridad

  Cada usuario contara con una determinada contraseña y usuario único e irrevocable.

  El acceso a los cambios de notas solo estará autorizado para personal docente y administrativo.

3.2.3 requisitos de fiabilidad

  Es uno de los factores que dará confianza al cliente, para lo cual el sistema está encargado del regalamiento de datos, que estos no se vean afectos por otros factores, que solo será manejado por el personal autorizado. 

3.2.4 requisitos de mantenibilidad 
  El sistema cuenta con características parametrizables lo que permitirá futuros mantenimientos, es decir que se pueden hacer cambios en este cuando se deseen ya sea cada un año o cada un mes, del que se encargara el sector administrativo después de hacer recibido su  respectiva capacitación.

3.2.5 requisito  la estabilidad

  Este sistema contara con una gran estabilidad y no necesitara cambios en su interfaz.
