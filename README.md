# VetCare — Sistema web de gestión de citas y pacientes

Proyecto del primer bimestre de Desarrollo de Aplicaciones Web (GR2SW, Grupo 5). VetCare es un sitio estático en HTML5 y CSS para la clínica veterinaria Huellitas.

## Integrantes y reparto del trabajo

| Módulo | Responsable | Casos de uso |
| --- | --- | --- |
| 1. Inicio de sesión y propietarios | Christian Alejandro Yanchatipan Jumbo | CU-01 Iniciar sesión; CU-02 Gestionar propietarios |
| 2. Mascotas, atención médica e historial clínico | Mauricio Sebastian Lopez Guerron | CU-03 Gestionar mascotas; CU-07 Registrar atención médica; CU-08 Consultar historial clínico |
| 3. Citas y agenda | Jorge Gabriel Vinueza Tigse | CU-04 Agendar cita; CU-05 Gestionar citas; CU-06 Consultar agenda del día |
| 4. Veterinarios y servicios | Jean Pierre Espinosa Vizcaino | CU-09 Gestionar veterinarios; CU-10 Gestionar servicios |

## Pantallas asignadas

### Christian Alejandro Yanchatipan Jumbo

- `index.html`: inicio de sesión.
- `pages/recepcion-inicio.html`, `pages/veterinario-inicio.html` y `pages/admin-inicio.html`: menús de los tres roles.
- `pages/propietarios-listado.html`: listado y búsqueda de propietarios.
- `pages/propietarios-nuevo.html` y `pages/propietarios-detalle.html`: registro y consulta de propietarios.
- `pages/propietarios-editar.html` y `pages/propietarios-eliminar.html`: edición y confirmación de eliminación.

### Mauricio Sebastian Lopez Guerron

- `pages/mascotas-listado.html` y `pages/mascotas-nueva.html`: listado y registro de mascotas.
- `pages/mascotas-detalle.html` y `pages/mascotas-editar.html`: consulta y edición de mascotas.
- `pages/mascotas-eliminar.html`: confirmación de eliminación de mascota.
- `pages/atencion-nueva.html` y `pages/atencion-detalle.html`: registro y detalle de atención médica.
- `pages/historial-clinico.html`: consulta del historial clínico.

### Jorge Gabriel Vinueza Tigse

- `pages/citas-nueva.html`: formulario de agendamiento con selección de propietario, mascota, servicio y veterinario; fecha y hora con validaciones HTML5.
- `pages/citas-listado.html`: tabla de citas con controles para buscar por mascota o cédula y seleccionar fecha o estado, además de enlaces para ver, reprogramar y cancelar.
- `pages/citas-detalle.html`: vista de los datos de la cita, incluidos propietario, servicio, veterinario, motivo y estado, con enlaces a las acciones disponibles.
- `pages/citas-reprogramar.html` y `pages/citas-cancelar.html`: formularios para cambiar fecha, hora o veterinario y para confirmar la cancelación con un motivo obligatorio.
- `pages/agenda-dia.html`: agenda del veterinario con selección de fecha, tabla de citas programadas y enlaces para iniciar la atención o consultar el historial clínico.

### Jean Pierre Espinosa Vizcaino

- `pages/veterinarios-listado.html` y `pages/veterinarios-nuevo.html`: listado y registro de veterinarios.
- `pages/veterinarios-detalle.html` y `pages/veterinarios-editar.html`: consulta y edición de veterinarios.
- `pages/veterinarios-eliminar.html`: confirmación de eliminación de veterinario.
- `pages/servicios-listado.html` y `pages/servicios-nuevo.html`: listado y registro de servicios.
- `pages/servicios-detalle.html`, `pages/servicios-editar.html` y `pages/servicios-eliminar.html`: consulta, edición y eliminación de servicios.

## GitHub Pages

https://jgabrielvinuezat14.github.io/Proyecto-I-Bim-Vetcare-GR2SW-Grupo5/
