# Proyecto para aprobación de la materia Programación Web

## Introducción
La universidad es el momento durante el cual el estudiante aprenderá las bases de programación y administración de proyectos que le preparará para una carrera profesional en la industria del desarrollo web.
Siendo así, en la universidad formamos ingenieros y es por ellos que los alumnos de la materia de programación web generarán las herramientas necesarias para construir un sitio web usando las nuevas tecnologías pero sin hacer uso de frameworks y librerías existentes en el mercado actual.
Es importante que a través de un proyecto real, el alumno comprenda el proceso completo de la web y su desarrollo, siendo así, hacer uso de frameworks y librerías en el futuro será mucho más sencillo.

## Objetivos
1. Aprender y familiarizarse con el desarrollo colaborativo al trabajar en un equipo de cinco integrantes.
1. Entender y familiarizarse con el flujo de desarrollo de software a través de la alternancia de roles.
1. Desarrollar habilidades en el uso de control de versiones a través de commits, branching y gitflow durante el desarrollo completo del proyecto.
1. Uso de tecnologías y conocimientos técnicos en el desarrollo de aplicaciones web aplicados al proyecto.

## Descripción General
El equipo desarrollará un API Restful que proveerá todos los servicios necesarios para una aplicación externa, la cual será una aplicación web desarrollada cumpliendo con los requerimientos de la web responsiva, con soporte para los navegadores web más comunes en el mercado actual.
Ambas aplicaciones deberán ser publicadas como software libre en algún servicio de repositorios GIT en línea y deberá estar publicada en un hosting durante el semestre completo hasta la culminación del curso.


## Descripción Técnica
1. Tanto la aplicación web así como el API debe estar montados en un servidor con SSL y con dominio público.
1. El API deberá ser un subdominio del dominio de la aplicación.
1. Todo el código escrito javascript tanto en frontend así como en NodeJS deberá usar ES6, 2015.
1. API Restful en NodeJS con ruteo CRUD para cada una de las entidades principales del proyecto.
1. Las rutas manejan pretty urls, es decir, son textos claros los cuales redireccionan al identificador de la entidad en cuestión.
1. Respuestas del API con páginado, uso de filtros múltiples opcionales y ordenado definido.
1. El API permite la solicitud de listados ordenados aleatoriamente y con un máximo de elementos a responder.
1. El proyecto cuenta con al menos 4 entidades principales y extras un sin fin de tablas secundarias y relacionales.
1. El almacenado de información se maneja en una base de datos relacional.
1. Desarrollo de clase abstracta para la manipulación de la base de datos.
1. Manejo de sesiones de usuario con tokens y cookies de manera nativa.
1. Administración de cuentas de usuario, es decir, registro, edición y recuperación de contraseñas con urls con caducidad definida a través de tokens.
1. Las cuentas de usuarios deben permitir múltiples correos, sin embargo, el ingreso a la plataforma se debe permitir solo con el correo prinicipal o el usuario.
1. El sistema mantiene al menos dos niveles de roles, es decir, usuario y administrador, y ambos tienen permisos diferentes en la plataforma así como acceso o denegación a ciertas secciones.
1. Envío de correos transaccionales, es decir, ante acciones específicas tal como registro, recuperación de contraseña, tarea completada, etc.
1. Validación de entradas del usuario (formularios) en aplicación web y del mismo modo en API.
1. Manipulación de imágenes en el backend para optimización de imágenes proporcionadas por el usuario.
1. La aplicación web deberá tener soporte para IE11, Edge 17, Safari 11, Firefox 61, Chrome 49.
1. La aplicación web debe contener además de “landing page” y manejo de usuarios al menos 5 niveles de navegación.
1. El usuario podrá registrarse a la plataforma con al menos uno de las siguientes redes: Facebook, Twitter, Google, Github, sin embargo, el registro estandar de correo y contraseña se debe mantener y el correo se debe mantener relacionado en caso de coincidir con el de la red social.
1. Para el UI de la aplicación web, se debe crear un library con todos los componentes y sus estilos.
1. En la aplicación web, existe un slider de imágenes las cuales se configuran por el administrador, el cual puede agregar múltiples imágenes así como ordenarlas a su decisión.
1. La validación de formularios en la aplicación web es en tiempo real, con mensajes claros y sin necesidad de refrescar el navegador.
1. En la aplicación web existe al menos un carrousel de elementos que se mueven de manera automática cada N tiempo, y que en vistas móviles muestran un elemento completo y los otros a “medias” para dejar mas claro al usuario que debe arrastrar con el dedo.
1. Todas las notificaciones al usuario en el aplicación web se deben realizar en modales o notificaciones pop en la misma página sin necesidad de actualizar y realizadas de manera nativa.
1. Los filtros de entidades en la plataforma deben incluir animaciones con estilos y realizar la actualización de contenido de manera dinámica.
1. En las vistas para el administrador, todas las tablas deberán contener acciones masivas al elegir dos o más elementos de la tabla o lista.
1. El usuario debe poder subir una nueva foto a su perfil arrastrando la foto desde su dispositivo hacia el sitio web.
1. En el diseño de la aplicación web deben existir elementos tamaño fixed and full width responsivos al dispositivo.
1. El proyecto debe tener un README completo, claro y con todos los detalles tanto para contribuidores como para usuarios de la aplicación.
1. El código de javascript deberá basarse en la guía de estilos de [AirBnB](https://github.com/airbnb/javascript)
1. El CSS y/o SASS deberá cumplir con la guía de estilos definida por el grupo
1. El HTML deberá basarse en la guía de estilos de [Google](https://google.github.io/styleguide/htmlcssguide.html) y aprobar la validación de [W3C](https://validator.w3.org/)



## Deseables
Esta es una lista de temáticas que aunque no son requeridas para el proyecto, se incita a los alumnos para intentar implementarlas.
1. Manejo de pagos con conekta, open pay, paypal, etc
1. Unit Test para el API
1. API Docs con live testing
1. Progressive Web App
1. Integración continua
1. JSON Schema



