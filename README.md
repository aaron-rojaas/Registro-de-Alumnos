# Registro de Alumnos

Proyecto hecho en PHP para la gestion de alumnos de una universidad

---

## Tecnologias utilizadas

- PHP
- MySQl
- **Git / GitHub**
- SQL Lite

---

## Arquitectura del proyecto

Aplicacion web con:

- Registrar Alumno
- Registrar Grupo
- Alumnos Registrados

---

## Estructura del proyecto (actual)

```
├── .gitignore
├── README.md
├── public
│   └── index.php
└── src
    ├── bootstrap.php
    ├── Db.php
    ├── Controllers
    │   ├── GroupsController.php
    │   ├── HomeController.php
    │   └── StudentsController.php
    ├── Http
    │   └── Response.php
    ├── Routing
    │   └── Router.php
    ├── Support
    │   ├── Flash.php
    │   └── View.php
    └── Views
        ├── home.php
        ├── layout.php
        ├── student_edit.php
        └── student_view.php
```

Notas:
Mini-sistema en PHP (sin dependencias) para:
- Registrar grupos (carrera, turno, grado) con código autogenerado.
- Registrar alumnos y asignarlos a un grupo.
- Listar alumnos registrados con acciones: ver, editar y eliminar.

---

## Trabajo en equipo y ramas

Ramas:

- `main` -> version estable
- `irving/*` -> dev
- `aaron/*` -> dev

---

## Requisitos
- PHP 8.1+ (recomendado 8.2+)

## Ejecutar
Desde la raíz del proyecto:

powershell
php -S localhost:8000 -t public


Luego abre http://localhost:8000.

## Base de datos
Usa SQLite en storage/app.sqlite. Se crea automáticamente al primer inicio.

---

## Funcionalidades

- Crear grupo
- Crear Alumno
- Crear Turno
- Crear Grado
- Actualizar
- Registrar Alumno
- Registrar Grupo
- Editar
- Eliminar

---

## Autores

**IRVING ISAY PINEDA PINEDA**
- https://github.com/IRVINGPINEDA

**Aaron Rojas Monroy**
- https://github.com/goku58432
