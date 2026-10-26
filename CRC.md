
# 1. Tarjetas CRC — Sistema de gestión de una biblioteca

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



## 2. Comportamiento de la clase `Libro` al prestar un ejemplar

Cuando se intenta prestar un ejemplar, la clase `Libro` debe comprobar primero si hay ejemplares disponibles.

- **Si hay ejemplares disponibles:** el préstamo tiene éxito y el número de ejemplares disponibles disminuye en uno.
- **Si no hay ejemplares disponibles:** el préstamo no se realiza y el número de ejemplares disponibles permanece igual.


