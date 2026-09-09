# Actividad M2A2: Registro para un Torneo de Videojuegos

Formulario HTML de inscripción organizado en una tabla, con validaciones en los campos y botones **Enviar** y **Restablecer**.

## Cómo verlo

Abre `index.html` en el navegador.

## Campos y validaciones

| Campo | Tipo | Validaciones |
| --- | --- | --- |
| Nombre del jugador | `text` | Obligatorio, mínimo 3 y máximo 15 caracteres |
| Correo electrónico | `email` | Obligatorio, formato de correo válido |
| Edad | `number` | Obligatorio, entre 12 y 40 años |
| Nickname en el juego | `text` | Solo letras y números (`pattern`) |
| Categoría | `radio` | Selección obligatoria: Principiante, Intermedio o Experto |
| Juegos favoritos | `checkbox` | Selección múltiple: FIFA, LoL, Minecraft |
| Fecha de inscripción | `date` | Solo fechas del año 2025 |

## Botones

- **Enviar**: envía el formulario si las validaciones se cumplen.
- **Restablecer**: limpia todos los campos.
