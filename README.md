PROYECTO TEMA 2
Plantea el proyecto que vas a realizar como una descripción de lo que querría el cliente que hagas o como una conversación informal con el cliente.
Planteamiento del Proyecto (Cliente)
Opción 1: Descripción para el cliente

"Necesito una aplicación web sencilla para gestionar las reservas de citas de mi pequeño negocio. Debe permitir a los clientes ver la disponibilidad en tiempo real, reservar un hueco y recibir una confirmación por email. Yo, como administrador, necesito poder añadir/eliminar servicios, ver todas las reservas del día/semana y bloquear horarios si es necesario."

Opción 2: Conversación informal

Yo: Hola! Entonces, quieres un sistema para que tus clientes puedan reservar online sin que tú tengas que estar pendiente todo el rato, ¿no?

Cliente: Exacto. Que sea fácil de usar y que me avise cuando haya algo nuevo.

Yo: Perfecto. Haremos una web donde se vea el calendario, puedan elegir hora y tú tengas un panel de control para manejarlo todo.

Elige una metodología entre las que hemos visto en el tema, defiende por que has elegido esa teniendo en cuenta también al tamaño del grupo en caso de que no hagas el proyecto en solitario.
Metodología y Justificación
Elijo la metodología Scrum (Agile).

Justificación:

Tamaño del grupo: Si somos un grupo pequeño (3-5 personas), Scrum funciona genial porque fomenta la comunicación constante y la adaptación rápida.

Flexibilidad: Permite entregar valor pronto y ajustar los requisitos si el cliente cambia de opinión (algo común en proyectos escolares/reales).

Ciclos cortos: Los Sprints nos obligan a tener entregables funcionales cada pocas semanas, lo cual es bueno para la evaluación. 4. Describe todas las etapas que conforman el ciclo de vida del proyecto utilizando la metodología anterior, así como los roles que se siguen en dicha metodología y como se distribuyen entre los miembros del grupo. Explica también las reuniones y productos que deberías realizar siguiendo esa metodología. 4. Ciclo de Vida, Roles y Reuniones (Scrum) El ciclo de vida en Scrum se basa en iteraciones llamadas Sprints. Etapas del Ciclo de Vida (Sprint Iterativo)

1.Planificación del Sprint (Sprint Planning): Se decide qué se hará en el Sprint.

2.Ejecución del Sprint: El equipo desarrolla las tareas.

3.Reunión Diaria (Daily Scrum/Stand-up): Reunión corta diaria.

4.Revisión del Sprint (Sprint Review): Se muestra lo hecho al cliente/interesados.

5.Retrospectiva del Sprint (Sprint Retrospective): El equipo reflexiona sobre cómo mejorar el proceso.

Roles Product Owner (PO): Define la visión del producto y gestiona el Product Backlog. (Ej: El que mejor entiende lo que quiere el cliente). Scrum Master (SM): Facilita el proceso, elimina impedimentos y asegura que se siguen las reglas de Scrum. (Ej: El líder/coordinador del grupo). Development Team: Realizan el trabajo (diseño, desarrollo, pruebas). (Ej: El resto del grupo). Para la distribución de roles y productos en Scrum, en la Planificación del Sprint, el Product Owner prioriza el Product Backlog y el Equipo de Desarrollo selecciona y estima las tareas para crear el Sprint Backlog. Durante la Ejecución del Sprint, el Equipo de Desarrollo trabaja activamente, reportando el progreso en el Daily Scrum (reunión diaria corta) donde se mencionan los avances, impedimentos y planes para el día. Al finalizar el ciclo, el producto resultante es el Incremento del Producto (funcionalidad terminada) que se presenta en la Revisión del Sprint al cliente. Finalmente, en la Retrospectiva del Sprint, el equipo genera un Plan de Mejora para el proceso del siguiente ciclo.

Desglosa la descripción de lo que querría el cliente en una lista de requisitos funcionales y no funcionales del proyecto. Requisitos Funcionales (RF) RF1: El sistema debe permitir a los usuarios registrarse y loguearse.
RF2: El sistema debe mostrar un calendario con la disponibilidad de citas.

RF3: El usuario debe poder seleccionar un servicio y un hueco disponible para reservar.

RF4: El sistema debe enviar un email de confirmación tras una reserva exitosa.

RF5: El administrador debe poder crear, modificar y eliminar servicios.

RF6: El administrador debe poder ver todas las reservas por fecha.

Requisitos No Funcionales (RNF)

RNF1 (Usabilidad): La interfaz debe ser intuitiva y tardar menos de 3 clics para reservar una cita.

RNF2 (Rendimiento): El tiempo de carga de la página principal no debe superar los 3 segundos.

RNF3 (Seguridad): Las contraseñas deben almacenarse hasheadas.

RNF4 (Fiabilidad): El sistema debe tener una disponibilidad del 99% (uptime).

Describe las herramientas que necesitarías para realizar el proyecto, como se usarían y en que fases. Incluye IDE, lenguaje de programación, herramientas de documentación, herramienta de pruebas, control de versiones… Para la ejecución del proyecto, se requerirá VS Code como IDE principal para escribir el código, utilizando un lenguaje como Python o JavaScript. El Control de Versiones se gestionará con Git y se alojará en GitHub para colaborar y mantener el historial de cambios. La Documentación se creará usando archivos Markdown dentro del repositorio, cubriendo requisitos y diseño. Para asegurar la calidad, se implementarán Herramientas de Pruebas específicas del lenguaje (como PyTest o Jest) durante la fase de desarrollo para verificar las funcionalidades. Finalmente, para la gestión del flujo de trabajo Scrum, se usará una herramienta como Trello o Jira para administrar el Backlog y los tableros del Sprint.

Describe de forma resumida como se llevaría a cabo el proyecto teniendo en cuenta todo lo anterior. Usaremos Scrum. 1.Inicio: El PO define la visión y creamos el Product Backlog (lista de requisitos). 2.Planificación: Seleccionamos las tareas prioritarias para el primer Sprint (ej: Login y mostrar calendario) y creamos el Sprint Backlog. Usaremos Trello para gestionar las tareas y Git para el código. 3.Desarrollo: El equipo desarrolla usando VS Code y el lenguaje elegido. Hacemos Daily Scrums para sincronizarnos. 4.Pruebas: Se usan PyTest/Jest para asegurar que los requisitos funcionales se cumplen. 5.Entrega: Al final del Sprint, mostramos la funcionalidad al cliente (Review) y vemos cómo mejorar (Retrospectiva). 6.Iteración: Repetimos los pasos 2-5 hasta que todas las funcionalidades del Product Backlog estén completadas. La documentación se mantiene actualizada en Markdown.
