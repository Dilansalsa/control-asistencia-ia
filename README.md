# control-asistencia-ia
Control de Asistencia con Reconocimiento Facial 

Este proyecto utiliza Inteligencia Artificial para automatizar el control de asistencia de personas mediante reconocimiento facial en tiempo real.

¿Cómo funciona?

1. Registro de rostros: 
   Usando el archivo registrar_rostros.ipynb, se capturan y almacenan las imágenes de los participantes en la carpeta dataset/

2. Reconocimiento y asistencia:
   Usando reconocimiento.ipynb, se detectan los rostros en tiempo real y se registra la asistencia en la carpeta registro_de_asistencias/ en un archivo CSV con la fecha del     día.

Tecnologías usadas:
- Python
- Jupyter Notebook
- OpenCV
- face_recognition (IA preentrenada)
- NumPy

Estructura de carpetas:
Control_Asistencia_IA/
├── registrar_rostros.ipynb
├── reconocimiento.ipynb
├── dataset/
│ └── .gitkeep
└── registro_de_asistencias/
└── .gitkeep

Proyecto de Inteligencia Artificial  
  Estudiante: Salas Dilan
