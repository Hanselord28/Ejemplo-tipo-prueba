Ejemplo-tipo-prueba
---
Caso de uso
-
1-la opcion de "ver historial de otras personas", aparte de opcional puede ser reemplazado
por "ver historial de reservas"para que tenga mayor coherenciacon los requisitos del cliente

2-la opcion de "generar reporte de uso" no concuerda con los requisitos tomados por el cliente

3-el actor "API Reserva externa" y la opcion "consultar disponibilidad externa" no tienen coherencia alguna con el caso

4-las relaciones no estan marcadas ni con lineas punteadas ni especificadas como include o extend

5-la relacion del actor "administrador" no deberia estar presente ya que el actor "sistema de notificaciones" deberia ser el encargado de "notificar cambios por correo"

6- la opcion "notificar cambio por correo" deberia estar relacionado con "rechazar reserva"

diagrama de clases
-
1-la clase "reserva" no está relacionada de ninguna forma 

2-el usuario deberia tener 4 metodos siendo reservar, cancelar, ver historial y justificar cancelacion segun el diagrama de caso de uso, sin embargo tiene solo 2 

3-ninguna clase de notificacion obtiene datos como para poder notificar, por ejemplo, el correo 


diagrama de implementacion
-
1-la base de datos central deberia estar diagramada en la parte superior, ya que a partir de ahi comienza el flujo de datos 

