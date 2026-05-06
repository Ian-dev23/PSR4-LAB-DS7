#  PHP Manual Autoloading & PSR-4 Lab

Este proyecto es una implementación práctica de la carga automática de clases siguiendo el estándar **PSR-4**, pero gestionada de manera manual para comprender la estructura interna de las dependencias en PHP.

##  Características
- **Estructura PSR-4:** Mapeo de namespaces a directorios físicos.
- **Vendor Manual:** Gestión de carpetas y archivos de carga sin automatización externa inicial.
- **Separación de Responsabilidades:** División clara entre Modelos, Servicios y Lógica de Negocio.

##  Estructura del Proyecto

```text
psr4-lab/
├── src/                # Código fuente de la aplicación
│   ├── Models/         # Clases de datos (Ej: Student.php)
│   └── Services/       # Lógica de negocio (Ej: EnrollmentService.php)
├── vendor/             # Gestión manual de dependencias y autoload
│   └── autoload.php    # Archivo principal de carga
├── index.php           # Punto de entrada de la aplicación
└── .gitignore          # Archivos excluidos del repositorio
