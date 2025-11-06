🧾 Primer borrador del proyecto: GymTrack 🧾

1. 💡 Idea del proyecto

1.1. Presentación
El proyecto GymTrack consiste en el desarrollo de una aplicación móvil Android, creada en Java usando Android Studio, destinada a gimnasios o entrenadores personales.
El objetivo es gestionar los clientes, registrar sus rutinas de entrenamiento y dietas, y permitir un seguimiento personalizado del progreso de cada usuario, todo almacenado de forma local en una base de datos SQL.
La aplicación permitirá:

👥 Administración diferenciada en función de roles de usuario: público, cliente, entrenador/administrador.
(id, nombre, correo, contraseña, rol)
📋 Crear perfiles de clientes con datos básicos (nombre, edad, peso, altura, objetivos, etc.).
🏋️‍♂️ Registrar rutinas de entrenamiento genéricas o personalizadas según las necesidades de cada cliente.
🥗 Registrar rutinas de entrenamiento personalizadas (ejercicios, series, repeticiones, peso, RIR, etc.).
📊 Consultar el historial de entrenamientos y dietas de cada cliente.
📈 Generar resúmenes de progreso y estadísticas por cliente.

1.2. Justificación
Actualmente, muchos gimnasios —especialmente los más pequeños— carecen de herramientas digitales adecuadas para llevar un control detallado de sus clientes.
La mayoría dependen de hojas de papel o Excel, lo que resulta ineficiente y propenso a errores. En algunos casos, ni siquiera se realiza un seguimiento adecuado de los clientes, afectando la calidad del servicio.
GymTrack ofrece una solución local, práctica y personalizable, que permite a los entrenadores gestionar fácilmente a sus clientes, mientras que estos pueden visualizar su progreso mediante una interfaz sencilla e intuitiva.
Desde un punto de vista académico, este proyecto permite demostrar competencias clave del ciclo de Desarrollo de Aplicaciones Multiplataforma (DAM):
Programación en Java orientada a objetos.
Diseño de interfaces en Android Studio.
Gestión de bases de datos SQL.
Operaciones CRUD avanzadas.
Manejo de datos y lógica de negocio.

1.3. Objetivos del proyecto
Desarrollar una aplicación Android que permita gestionar clientes de un gimnasio, registrando y siguiendo sus entrenamientos y dietas, con almacenamiento seguro y persistente mediante SQL.
Objetivos específicos:
🧩 Diseñar una interfaz clara y fácil de usar para entrenadores y administradores.
🗄️ Crear una base de datos SQL con tablas en función de los datos necesarios.
🔁 Implementar operaciones CRUD sobre esta base de datos.
🏋️ Permitir asignar rutinas y dietas a cada cliente y registrar su progreso.
📊 Generar resúmenes de evolución por cliente.
✅ Validar los datos introducidos para asegurar la integridad de la información.
📝 Documentar el desarrollo de la aplicación y sus funcionalidades.

| Tecnología         | Uso                                    | Justificación                                                |
| ------------------ | -------------------------------------- | ------------------------------------------------------------ |
| **Android Studio** | Entorno de desarrollo de la aplicación | Herramienta completa para crear aplicaciones Android en Java |
| **Java**           | Lenguaje de programación               | Orientado a objetos y ampliamente usado en Android           |
| **SQL**            | Base de datos                          | Permite gestionar de manera eficiente los datos de la app    |
| **XML**            | Diseño de la interfaz                  | Permite crear pantallas claras, adaptables y estructuradas   |

1.5. Separación de roles
Dentro de la aplicación, los usuarios tendrán diferentes roles, cada uno con accesos y funcionalidades específicas:

👤 Público o anónimo
Acceso limitado: puede ver información general, tutoriales o ejemplos de rutinas/dietas.
No puede crear ni editar clientes, rutinas o dietas.
Interfaz simplificada.

🧑‍💻 Usuario registrado
Generalmente, un cliente del gimnasio.
Puede ver sus propias rutinas y dietas asignadas por el entrenador.
Puede registrar sus progresos y consultar su historial de entrenamientos y comidas.
Solo puede modificar su propio perfil y datos.

🧑‍🏫 Administrador / Entrenador
Funcionalidades completas: crear y eliminar clientes, asignar rutinas y dietas, consultar progreso global.
Puede gestionar todos los registros de usuarios y rutinas.

| Rol                    | Menú / Pantallas disponibles                                   |
| ---------------------- | -------------------------------------------------------------- |
| **Público**            | Inicio, Rutinas, Dietas de Ejemplo                             |
| **Usuario registrado** | Inicio, Mi Perfil, Mis rutinas, Mis dietas, Historial          |
| **Administrador**      | Inicio, Clientes, Rutinas, Dietas, Estadísticas, Configuración |
