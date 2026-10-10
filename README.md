NOMBRE DEL PROYECTO: Proyecto Horarios Urban Routes

OBJETIVO DEL PROYECTO: Este proyecto se realizo para validar que dentro de la página web Urban Routes se respeten tanto los horarios como los costos que cubren dichos horarios, las pruebas realizadas fueron enfocadas en como se comporta la página al momento de pedir un taxi en cierto rango de horas y validar que los costos por distancia fueran los correctos.

QUE SE BUSCA CON ESTE PROYECTO: Con este proyecto lo que se busco fue confirmar que los costos de los viajes fueran los correctos relacionados con la distancia a recorrer en cada viaje.

DOCUMENTACIÓN: Se trabajo dentro de la página Urban Routes.

TECNOLÓGIAS UTILIZADAS: Google Chrome versión 154.0.8037.98

CASOS DE PRUEBA: Los casos de prueba que se realizaron fueron los siguientes:

 Caso de Prueba-1	El tiempo de conducción y el costo de un viaje en un automóvil compartido en Urban Routes con una hora de inicio de 18:01-22:00	
 "Abrir el servicio de Urban Routes
  Validar el horario para la solicitud
  Agregar direcciones diferentes en los campos ""Desde"" y ""Hasta"""	 	
      1	Introducir un destino en el campo “Desde” 1300 1st St
			2	Introducir un destino en el campo “Hasta” 1917 Bay St     	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar	
  "En el recuadro azul nos mostrará los kilómetros a recorrer y el tiempo,además nos arrojará una ventana emergente con la ubicación del automóvil,el tipo y el costo total del viaje.Para esta información se utilizo la siguiente formula:
Tiempo=Distancia/Velocidad
Costo del viaje=Tiempo x Precio por minuto.
Tiempo= 3.7/25= 0.148 (x60)=8.88 minutos
Costo= 8.88 x0.1=0.888 usd
T = 8.8 MINUTOS
C = 0.888 USD"


Caso de Prueba-2	El tiempo de conducción y el costo de un viaje en un automóvil compartido en Urban Routes con una hora de inicio de 22:01-00:00	
"Abrir el servicio de Urban Routes
Validar el horario para la solicitud
Agregar direcciones diferentes en los campos ""Desde"" y ""Hasta"""
      1	Introducir un destino en el campo “Desde” 1300 1st St
			2	Introducir un destino en el campo “Hasta” 1917 Bay St     	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar	
"En el recuadro azul nos mostrará los kilómetros a recorrer y el tiempo,además nos arrojará una ventana emergente con la ubicación del automóvil,el tipo y el costo total del viaje.Para esta información se utilizo la siguiente formula:
Tiempo=Distancia/Velocidad
Costo del viaje=Tiempo x Precio por minuto.
Tiempo= 3.7/45= 0.082 (x60)=4.92 minutos
Costo= 4.92 x0.1=0.492 usd
T = 4.92 MINUTOS
C = 0.492 USD"
      
Caso de Prueba-3	El tiempo de conducción y el costo de un viaje en un automóvil compartido en Urban Routes con una hora de inicio de 00:01-08:00	
"Abrir el servicio de Urban Routes
Validar el horario para la solicitud
Agregar direcciones diferentes en los campos ""Desde"" y ""Hasta"""	 	
      1	Introducir un destino en el campo “Desde” 1300 1st St
			2	Introducir un destino en el campo “Hasta” 1917 Bay St     	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar	

"En el recuadro azul nos mostrará los kilómetros a recorrer y el tiempo,además nos arrojará una ventana emergente con la ubicación del automóvil,el tipo y el costo total del viaje.Para esta información se utilizo la siguiente formula:
Tiempo=Distancia/Velocidad
Costo del viaje=Tiempo x Precio por minuto.
Tiempo= 3.7/45= 0.082 (x60)=4.92 minutos
Costo= 4.92 x0.1=0.492 usd
T = 4.92 MINUTOS
C = 0.492 USD"

Caso de Prueba-4	El tiempo de conducción y el costo de un viaje en un automóvil compartido en Urban Routes con una hora de inicio de 08:01-12:00	
"Abrir el servicio de Urban Routes
Validar el horario para la solicitud
Agregar direcciones diferentes en los campos ""Desde"" y ""Hasta"""	 
      1	Introducir un destino en el campo “Desde” 1300 1st St
			2	Introducir un destino en el campo “Hasta” 1917 Bay St     	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar

"En el recuadro azul nos mostrará los kilómetros a recorrer y el tiempo,además nos arrojará una ventana emergente con la ubicación del automóvil,el tipo y el costo total del viaje.Para esta información se utilizo la siguiente formula:
Tiempo=Distancia/Velocidad
Costo del viaje=Tiempo x Precio por minuto.
Tiempo= 3.7/30= 0.1233(x60)=7.4minutos
Costo= 7.4 x0.1=0.74 usd
T = 7.4MINUTOS
C = 0.74 USD"
	
Caso de Prueba-5	El tiempo de conducción y el costo de un viaje en un automóvil compartido en Urban Routes con una hora de inicio de 12:01-18:00	
"Abrir el servicio de Urban Routes
Validar el horario para la solicitud
Agregar direcciones diferentes en los campos ""Desde"" y ""Hasta"""	
      1	Introducir un destino en el campo “Desde” 1300 1st St
			2	Introducir un destino en el campo “Hasta” 1917 Bay St     	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar	

"En el recuadro azul nos mostrará los kilómetros a recorrer y el tiempo,además nos arrojará una ventana emergente con la ubicación del automóvil,el tipo y el costo total del viaje.Para esta información se utilizo la siguiente formula:
Tiempo=Distancia/Velocidad
Costo del viaje=Tiempo x Precio por minuto.
Tiempo= 3.7/40= 0.0925 (x60)=5.55 minutos
Costo= 5.55 x0.1=0.555usd
T = 5.5 MINUTOS
C = 0.555 USD"

Caso de Prueba-6	Comprobar que no se puede reservar automóvil compartido en Urban Routes con una hora de inicio de 12:01-18:00 y Distancia = 0	
"Abrir el servicio de Urban Routes
Validar el horario para la solicitud
      1	Introducir un destino en el campo “Desde” 1717 E 7th St
			2	Introducir un destino en el campo “Hasta” 1717 E 7th St	
			3	Seleccionar el modo de la ruta	
			4	Seleccionar la opción compartir automóvil.	
			5	Dar click en el botón reservar	
			6	Completar ventana Emergente de Licencia de Conducir	
			7	Agregar método de pago	
			8	Dar click en el recuadro azul que dice Reservar	

" El recuadro azul que dice Reservar no debe mostrar información,ya que es la misma dirección de inicio y fin del viaje y la aplicación no saca costos en distancias iguales a 0.


APRENDIZAJE: Con este proyecto reforce mis conocimientos en la creación de casos de prueba y pude seguir practicando y mejorando mis técnicas para la creación de las mismas.


