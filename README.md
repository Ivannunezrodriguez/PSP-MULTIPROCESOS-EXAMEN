PSP-MULTIPROCESOS-EXAMEN
Este proyecto es una práctica desarrollada en Java que simula un centro de exámenes utilizando múltiples procesos. Forma parte de las actividades del módulo de Programación de Servicios y Procesos (PSP) del ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM).

🧠 Descripción
La aplicación simula un entorno donde varios procesos (representando estudiantes) acceden a un centro de exámenes. Se implementan mecanismos de sincronización para controlar el acceso concurrente y asegurar que se respeten las restricciones del sistema, como el número máximo de estudiantes permitidos simultáneamente.

📁 Estructura del Proyecto
css
Copiar
Editar
PSP-MULTIPROCESOS-EXAMEN/
├── src/
│   └── [Clases Java del proyecto]
├── out/
│   └── production/
│       └── Actividad UF1-2/
├── Actividad UF1-2. Multitarea. Centro de exámenes.INR.docx
├── Actividad UF1-2. Multitarea. Centro de exámenes.INR.pdf
├── Actividad UF1-2.iml
├── .gitattributes
└── .idea/
src/: Contiene el código fuente en Java.

out/: Directorio de salida con los archivos compilados.

Actividad UF1-2. Multitarea. Centro de exámenes.INR.docx/pdf: Documentación de la actividad, que describe los objetivos y requisitos del proyecto.

.idea/ y .iml: Archivos de configuración del entorno de desarrollo (IntelliJ IDEA).

⚙️ Tecnologías Utilizadas
Java: Lenguaje de programación principal del proyecto.

Programación Concurrente: Uso de procesos e hilos para simular el entorno multitarea.

Mecanismos de Sincronización: Implementación de semáforos o monitores para controlar el acceso concurrente.

🚀 Instrucciones de Ejecución
Clonar el Repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-MULTIPROCESOS-EXAMEN.git
Importar el Proyecto:

Abre el proyecto en tu entorno de desarrollo Java preferido (por ejemplo, IntelliJ IDEA).

Compilar el Proyecto:

Asegúrate de que el proyecto se compile correctamente. Si utilizas IntelliJ IDEA, el proyecto debería compilarse automáticamente al abrirlo.

Ejecutar la Aplicación:

Ejecuta la clase principal que inicia la simulación del centro de exámenes. Observa cómo los procesos (estudiantes) acceden y salen del centro respetando las restricciones establecidas.

📝 Notas Adicionales
Asegúrate de que los mecanismos de sincronización estén correctamente implementados para evitar condiciones de carrera.

Puedes modificar los parámetros del sistema (como el número máximo de estudiantes permitidos) para observar diferentes comportamientos en la simulación.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
