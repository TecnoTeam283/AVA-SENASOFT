# AVA-SENASOFT

## Índice

## Especificaciones de requerimientos
- [Requerimientos de usuario](#requerimientos-de-usuario)
- [Requerimientos Funcionales](#requerimientos-funcionales)
- [Requerimientos No Funcionales](#requerimientos-no-funcionales)


### Requerimientos de usuario
El sistema contara con 3 tipos de usuario:
- Estudiantes
- Profesores
- Administradores


  -Estudiantes:
    - Registro: Los estudiantes deben poder crear su cuenta en la plataforma.
    - Autenticación: Acceso seguro a sus cuentas a través de credenciales únicas.
    - Perfil Personalizado: Los estudiantes tendran una interfaz de perfil distinta a la de los demas usuarios.
    - Acceso a Cursos: Los estudiantes deben poder acceder a la lista de cursos disponibles.
    - Materiales de Estudio: Acceso a materiales de estudio, como lecturas, videos y recursos.
    - Seguimiento del Progreso: Visualización del progreso en los cursos y módulos.
    - Interacción con Compañeros: Participación en foros de discusión y chats en vivo.
    - Realización de Actividades: Realización de cuestionarios, exámenes y tareas en línea.
    - Calendario: Visualización de fechas importantes y plazos de entrega.
    - Notificaciones: Recibir notificaciones por correo o mensajes internos sobre actualizaciones y recordatorios.
 
  -Profesores:
    - Registro: Los profesores deben poder registrarse y ser aprobados por los administradores.
    - Gestión de Cursos: Creación, edición y eliminación de cursos, módulos y lecciones.
    - Materiales Educativos: Carga de recursos como videos, documentos y pruebas.
    - Perfil Personalizado: Los profesores tendran una interfaz de perfil distinta a la de los demas usuarios.
    - Seguimiento de Estudiantes: Acceso a informes de progreso y calificaciones.
    - Comunicación: Interacción con estudiantes a través de foros, chats y notificaciones.
    - Calendario: Programación de clases, exámenes y fechas importantes.
    - Espacios Colaborativos: Facilitar espacios para proyectos grupales y colaborativos.
    - Integración Externa: Posibilidad de enlazar recursos externos y herramientas.
    - Análisis de Datos: Acceso a informes analíticos sobre el rendimiento de los estudiantes.
 
  -Administradores:
    - Gestión de Usuarios: Creación, edición y eliminación de cuentas de estudiantes y profesores.
    - Roles y Permisos: Asignación de roles y permisos a los usuarios.
    - Supervisión: Visualización de actividades y uso de la plataforma.
    - Mantenimiento: Gestión técnica y actualizaciones de la plataforma.

 

Aquí se describen los requisitos desde la perspectiva del usuario.

### Requerimientos Funcionales

Los requerimientos funcionales son aquellas soluciones tecnicas que se necesitan para el cumplimiento de las necesidades de las partes interesadas:

- RF01 - Mostrar pagina de inicio
- RF02 - Crear cuenta 
- RF03 - Iniciar sesión
- RF04 - Cuenta administrador
  - RF04.1 - Home
    - RF04.1.1 - Gestión de Usuarios
      - RF04.1.1.1 - Registro de estudiantes y profesores
      - RF04.1.1.2 - Edición de estudiantes y profesores
      - RF04.1.1.3 - Eliminación de estudiantes y profesores 
    - RF04.1.2 - Perfil
      - RF04.1.2.1 - Ver información
      - RF04.1.2.2 - Actualizar información
                  
- RF05 – Cuenta Profesor
  - RF05.1 - Home
    - RF05.1.1 - Gestionar cursos 
      - RF05.1.1.1 - Crear cursos, módulos y lecciones.
      - RF05.1.1.2 - Editar cursos, módulos y lecciones.
      - RF05.1.1.3 - Eliminar cursos, módulos y lecciones.
    - RF05.1.2 - Cargar material educativo.
    - RF05.1.3 - Perfil
      - RF05.1.3.1 - Ver información
      - RF05.1.3.2 - Actualizar información
      - RF05.1.4 - Seguimiento de estudiantes
        - RF05.1.4.1 - Visualizar informes y calificaciones de estudiantes
      - RF05.1.5 - Comunicación
        - RF05.1.5.1 - Interactuar con estudiantes a través de foros y chats
      - RF05.1.6 - Programar calendario
        - RF05.1.6.1 - Programar clases
        - RF05.1.6.1 - Programar examenes
              
- RF06 – Cuenta Estudiante
  - RF06.1 - Acceder a cursos
    - RF06.1.1 - Visualizar cursos disponibles
  - RF06.2 - Visualización de materiales de estudio
  - RF06.3 - Progreso
    - RF06.3.1 - Visualizar el progreso de los cursos
    - RF06.3.2 - Visualizar el progreso de los modulos
  - RF06.4 - Foro de comunicacón entre profesores y estudiantes
  - RF06.5 - Actividades en linea
    - RF06.5.1 - Responder Cuestionarios, examanes y tareas en linea
  - RF06.6 - Calendario
    - RF06.6.1 Visualizar fechas importantes y plazos de trabajos
  - RF06.7 - Notificaciones.
    


En esta sección, se listan los requerimientos funcionales del proyecto.

### Requerimientos No Funcionales

- Categoría	Usabilidad
  - RNF01 - Aprendizaje del sistema	El tiempo de aprendizaje del     sistema por un usuario deberá ser menor a 4 horas.
  - RNF02 – Tiempo de registro	Los usuarios deben poder completar la tarea de registro en no más de 5 minutos.
  - RNF03 – Acceso de información	Los usuarios deben poder acceder a la información que necesitan en no más de 4 clics.


Categoría	Confiabilidad
  - RNF04 – Seguridad de datos	Los datos almacenados en el sistema deben estar protegidos con medidas de seguridad adecuadas para evitar la pérdida o alteración no autorizada de información.
  - RNF05 - Disponibilidad	El sistema debe ser capaz de manejar una carga de usuarios concurrentes de al menos 2000 usuarios sin afectar el rendimiento.

- Categoría	Seguridad
  - RNF06 – Acceso al sistema	El acceso al sistema debe ser controlado por un sistema de autenticación (JWT) de usuarios basado en numero de identificación y contraseñas.

Categoría	Portabilidad
  - RNF07 – Portabilidad de dispositivos	El sistema debe ser capaz de ejecutarse en diferentes tipos de dispositivos, incluyendo computadoras de escritorio, portátiles y dispositivos móviles.
  - RNF08 – Compatibilidad entre navegadores	El sistema debe ser compatible con la mayoría de navegadores.


Esta sección aborda los aspectos no funcionales, como rendimiento, seguridad, etc.



