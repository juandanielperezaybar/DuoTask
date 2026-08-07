# DuoTask - Documento de Mockups

**Proyecto:** DuoTask - Aplicación móvil para gestión colaborativa de tareas
**Estudiante:** Juan Daniel Perez Aybar
**Matrícula:** SD-2023-04879
**Asignatura:** INF-4334 - Gestión de Configuración de Software
**Actividad:** Actividad Práctica 3 - Mockups
**Fecha:** Agosto 2026

---

## Descripción del Sistema

DuoTask es una aplicación móvil diseñada para la gestión y organización de tareas de manera individual o colaborativa. Permite a los usuarios registrarse, iniciar sesión, crear, editar y administrar tareas, asignarles prioridad y fecha límite, compartirlas con otros usuarios, visualizarlas en un calendario y gestionar su perfil personal.

---

## Lista de Pantallas Diseñadas

1. Inicio de Sesión (Login)
2. Registro de Usuario
3. Inicio / Lista de Tareas (Home)
4. Crear / Editar Tarea
5. Calendario
6. Perfil de Usuario

---

## 1. Pantalla: Inicio de Sesión

┌─────────────────────────┐
│ DuoTask │
│ │
│ Iniciar Sesión │
│ │
│ [ Correo electrónico ] │
│ [ Contraseña ] │
│ │
│ Olvidé mi contraseña│
│ │
│ [ INGRESAR ] │
│ │
│ ------ o ------ │
│ [ Crear una cuenta ] │
└─────────────────────────┘

**Explicación:** Pantalla inicial de acceso. Contiene campos para correo y contraseña, un enlace para recuperar contraseña (HU-03) y un botón para dirigirse al registro (HU-02).

---

## 2. Pantalla: Registro de Usuario

┌─────────────────────────┐
│ Crear Cuenta │
│ │
│ [ Nombre completo ] │
│ [ Correo electrónico ] │
│ [ Contraseña ] │
│ [ Confirmar contraseña ] │
│ │
│ [ REGISTRARME ] │
│ │
│ Ya tengo cuenta - Login │
└─────────────────────────┘


**Explicación:** Permite a un nuevo usuario crear su cuenta (HU-01), validando que la contraseña coincida con su confirmación.

---

## 3. Pantalla: Inicio / Lista de Tareas


┌─────────────────────────┐
│ Mis Tareas │
│ [ Buscar tareas... ]│
│ [Todas][Pendientes][OK] │
│┌────────────────────────┐
││ Entregar informe SCM │
││ Hoy - Alta ( )│
│└────────────────────────┘
│┌────────────────────────┐
││ Revisar PR mockups │
││ Mañana - Media ( )│
│└────────────────────────┘
│ (+)│
│ [Inicio][Calendario][Perfil]
└─────────────────────────┘

**Explicación:** Pantalla principal luego de iniciar sesión. Muestra el listado de tareas (HU-04) con opción de búsqueda (HU-12), filtros (HU-13) y un botón flotante (+) para crear una nueva tarea (HU-04). Cada tarjeta permite marcar la tarea como completada (HU-07).

---

## 4. Pantalla: Crear / Editar Tarea

┌─────────────────────────┐
│ Nueva Tarea │
│ [ Título de la tarea ]│
│ [ Descripción... ]│
│ Fecha límite │
│ [ dd/mm/aaaa ]│
│ Prioridad │
│ [Alta][Media][Baja] │
│ Compartir con │
│ [ Añadir colaborador ] │
│ [ GUARDAR TAREA ] │
└─────────────────────────┘


**Explicación:** Formulario para crear (HU-04) o editar (HU-05) una tarea. Incluye título, descripción, fecha límite (HU-18), prioridad (HU-17) y opción de compartir con otro usuario (HU-08), con confirmación doble antes de eliminarla (HU-09).

---

## 5. Pantalla: Calendario

┌─────────────────────────┐
│ Junio 2026 │
│ L M M J V S D │
│ 1 2 3 4 │
│ 5 6 7 8 9 10 11 │
│ 12 13 [14]15 16 17 18 │
│ ... │
│ Tareas del día 14: │
│┌────────────────────────┐
││ Entregar informe - 5pm │
│└────────────────────────┘
└─────────────────────────┘

**Explicación:** Vista de calendario mensual (HU-10) donde se resaltan los días con tareas asignadas y se listan las tareas del día seleccionado, incluyendo sincronización en tiempo real (HU-20).

---

## 6. Pantalla: Perfil de Usuario

┌─────────────────────────┐
│ (JD) │
│ Juan Daniel Pérez │
│ juan.perez@duotask.com │
│ │
│ [ Editar perfil ]│
│ [ Notificaciones ]│
│ [ Historial de tareas ]│
│ [ Estadísticas ]│
│ [ Cerrar sesión ]│
└─────────────────────────┘

**Explicación:** Permite editar los datos del perfil (HU-15), acceder a notificaciones (HU-11), historial (HU-14), estadísticas (HU-19) y cerrar sesión (HU-16).

