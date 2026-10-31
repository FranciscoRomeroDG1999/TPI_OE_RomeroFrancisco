# TPI_OE_RomeroFrancisco

# Documento informativo sobre el Trabajo Práctico Integrador de la materia Organización Empresarial.

# Integrantes del Grupo: Romero, Francisco.

#Descripción del sistema:

Sistema de automatización de alertas, desarrollado con Python. El sistema recibe como entrada un archivo CSV con información, la procesa y en base a la lógica del programa realiza una acción.

Si se acerca la fecha de finalización, de un plazo establecido con anterioridad para el alumno dentro del campus, se envía una notificación vía correo electrónico al alumno y al área de administración. Las alertas se envían 7 días antes del vencimiento del plazo y 1 día antes del mismo.

#Posible arquitectura del proyecto:

TPI_OE_RomeroFrancisco/
├── main.py                 # Menú principal y punto de entrada
├── config.py               # Parámetros: días de aviso, correo de administración, rutas
├── modulos/
│   ├── datos.py            # Lectura, escritura y validación de CSV
│   ├── fechas.py           # Cálculo de días restantes y vencimientos
│   ├── reporte.py          # HU1: genera el reporte de cursos vencidos
│   ├── notificaciones.py   # HU2 y HU3: envío de correos
│   └── estadisticas.py     # Backlog: consultas para el equipo docente
├── data/
│   ├── estudiantes.csv
│   ├── cursos.csv
│   └── inscripciones.csv
├── reportes/               # Reportes generados (vencidos_AAAA-MM-DD.csv)
└── README.md
 
 
#Declaración de IA:

La revisión y estructuración del proyecto se realizó con la ayuda de claude, en primera instancia se utilizó para la revisión de la arquitectura del script, optimizando los módulos planteados por el usuario y su contenido. A su vez, luego de finalizado el TPI se utilizó para auditar el mismo, buscando inconsistencias y errores dentro del mismo.

#Errores observados por claude:

·Error 1 []
·Error 2 []
·Error 3 []

#Observaciones del equipo humano sobre los informes del asistente:


