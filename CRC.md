
# Tarjetas CRC — Sistema de gestión de una biblioteca

## Clase: Libro

| Responsabilidades | Colaboradores |
|---|---|
| Conocer autor, título e ISBN | — |
| Conocer número de ejemplares disponible | — |
| Prestar un ejemplar (comprobar disponibilidad) | Préstamo |
| Recibir devoluciones | Préstamo |

---

## Clase: Socio

| Responsabilidades | Colaboradores |
|---|---|
| Conocer su nombre, nº de socio y fecha de alta | — |
| Solicitar un libro | Libro, Préstamo |
| Devolver un libro | Préstamo |

---

## Clase: Préstamo

| Responsabilidades | Colaboradores |
|---|---|
| Conocer qué libro y socio están implicados | Libro, Socio |
| Conocer la fecha del préstamo | — |
| Registrar la devolución del libro | Libro |
