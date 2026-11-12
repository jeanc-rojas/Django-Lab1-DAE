# Django - Laboratorio 01 (`todoproject`)

Proyecto web desarrollado en **Django** como parte del Laboratorio 01 del curso **Desarrollo de Aplicaciones Empresariales (DAE)**. Integra múltiples aplicaciones internas para gestionar un listado de tareas y ejecutar operaciones básicas mediante vistas y plantillas.

## Aplicaciones y Estructura

```text
Django-Lab1-DAE/
├── todoproject/
│   ├── manage.py               # Utilidad administrativa de Django
│   ├── todoproject/            # Configuración central, settings y enrutamiento principal
│   ├── tasks/                  # App de gestión de tareas (modelos, vistas y task_list.html)
│   └── operaciones/            # App de lógica y vistas para operaciones matemáticas/básicas
├── requirements.txt            # Dependencias del proyecto (Django 6.1.2)
└── DAE_Laboratorio 1.docx      # Informe técnico y evidencias del laboratorio
```

## Requisitos Previos

* **Python** 3.10 o superior.
* **Django** 6.1.2 (incluido en `requirements.txt`).

## Instalación y Ejecución

1. Clona el repositorio e ingresa a la carpeta:
   ```bash
   git clone https://github.com
   cd Django-Lab1-DAE
   ```
2. Crea y activa un entorno virtual:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Aplica las migraciones de la base de datos e inicia el servidor:
   ```bash
   cd todoproject
   python manage.py migrate
   python manage.py runserver
   ```
