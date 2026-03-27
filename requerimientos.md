# Requerimientos y Funcionalidades del Sistema de Transporte Aeroportuario

Este documento consolida los requerimientos para la plataforma web de reserva de viajes y transfers desde y hacia el aeropuerto, enfocado en las necesidades específicas de los viajeros.

## Funcionalidades y Requerimientos Clave

1. **Reservas Programadas**:
   - Capacidad del cliente de especificar fecha, hora, lugar de recogida y destino (Drop-off y Pick-up).
   - Validaciones estrictas de datos obligatorios, número de pasajeros.

2. **Adaptación a Vehículo Único (Single Vehicle)**:
   - Capacidad para gestionar de manera centralizada la agenda de un único conductor/vehículo.
   - Algoritmos para evitar reservas superpuestas o incompatibles en tiempo.

3. **Seguimiento de Vuelos y Geolocalización en Tiempo Real**:
   - Campo para el número de vuelo en viajes de Pick-up para facilitar el monitoreo de llegadas.
   - Proveer datos de estado de la reserva y localización del vehículo en tiempo real.

4. **Gestión de Equipaje y Accesorios**:
   - Control de equipaje facturado frente a equipaje de mano.
   - Solicitudes especiales (ej. requerimiento de asiento de bebé).

5. **Pagos e Integración**:
   - Desglose claro para pasarela de pago y manejo de costos variables por distancia/horario.
   
6. **Contacto Rápido y Comunicación**:
   - Integración nativa a través de un botón flotante de WhatsApp que arrastra los datos del formulario directamente hacia la app de mensajería para confirmación.
   - Espacio en la confirmación para instrucciones adicionales del usuario.
