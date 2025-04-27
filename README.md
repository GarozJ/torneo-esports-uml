# torneo-esports-uml

El diagrama de casos de uso desarrollado tiene como propósito representar de manera clara y estructurada las principales funcionalidades que el sistema ofrece al Administrador.
El Administrador tiene la capacidad de registrar nuevos equipos, añadir jugadores a dichos equipos y consultar la lista de equipos y jugadores registrados.

Estas acciones son necesarias para garantizar la integridad de la información. Por ello, se empleó la relación «include» en los casos de uso de Registrar equipo y Añadir jugador, incluyendo las acciones de Validar datos y Buscar equipo.

![Diagrama de Casos de Uso](https://github.com/user-attachments/assets/d21e7b5a-6859-4912-aa13-029b86ce7c1c)

El diagrama de clases elaborado describe la estructura del sistema, identificando las principales clases y las relaciones que existen entre ellas.
Se crearon tres clases:
Equipo: representa los equipos que se registran en el sistema, incluyendo atributos como el identificador, nombre y una lista de jugadores asociados.
Jugador: modela a cada jugador individual, detallando atributos relevantes como el nombre, la edad y la posición que ocupa en el equipo.
GestorEquipos: actúa como clase de control encargada de gestionar la lógica de negocio relacionada con la creación de equipos y la adición de jugadores.

Se establece una relación de composición entre las clases Equipo y Jugador, ya que un equipo puede tener varios jugadores, pero un jugador pertenece exclusivamente a un equipo..

![Diagrama de Clases](https://github.com/user-attachments/assets/919cc7ed-f50c-48a3-81d6-0bfe094e9ea0)
