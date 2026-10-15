# CanchaYA
Plataforma para reservar canchas sintéticas por horas con anticipo del 30% y calendario por sede.


# canchaya

CanchaYa es una plataforma web para reservar canchas sintéticas por horas, con anticipo del 30 % y calendario por sede.

## Descripción

Usuarios del sistema: **jugador**, **gestor de sede** y **administrador**.

- El jugador busca canchas por sede, tipo (fútbol 5, 7 u 8), precio y fecha, reserva una hora libre, paga el anticipo y puede cancelar hasta 2 horas antes.
- El gestor crea canchas, define franjas con precios y consulta la agenda del día de su sede.
- El administrador consulta reservas e ingresos por sede.

## Alcance (contrato mínimo)

- 7 tablas con llaves foráneas (usuarios, sedes, canchas, franjas_precio, reservas, pagos, resenas)
- 1 vista (`v_agenda_dia`)
- 1 procedimiento almacenado (`sp_reservar_cancha`)
- 2 transacciones (reservar con anticipo y cancelar reserva)
- 3 roles de base de datos (`rol_jugador`, `rol_gestor`, `rol_admin`)
- 6 pantallas responsive
- 2 formularios con validación en JavaScript (registro y reservar) y 1 listado con filtro (buscar canchas)

## Equipo

| Integrante | Usuario de GitHub | Rol en el equipo |
|------------|-------------------|------------------|
| (Daniel Alexander  Orozco Martinez) | Daniel-1414 | (Scrum Master) |
| (Jhan Lucas Cueva Llanos) | jhanluk10 | (Product owner) |
| (Breyner José Moreno Arévalo) | morenoalberga-spec | (Desarrollador) |
| (Iared Said Peña Castro) | iaredsaid1806 | (Desarrollador) |

## Cómo trabajamos

- `main` está protegida: todo cambio entra por **pull request** con **1 aprobación**.
- Cada integrante trabaja en su propia rama y abre un pull request hacia `main`.
- No se suben contraseñas, llaves ni datos personales reales (el repositorio es público).

## Documentación

- Informe de diseño: historias de usuario, modelo de datos y bocetos de pantallas.
