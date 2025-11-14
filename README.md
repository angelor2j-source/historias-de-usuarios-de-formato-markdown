# 7. Ejercicio en clase

Crea tres historias de usuario para una aplicación bancaria móvil.

### Requisitos:
- Usa el formato estándar.  
- Incluye al menos 2 criterios de aceptación por historia.  
- Deben ser claras, valiosas y medibles.

---

## Historia de usuario 1 — Consulta de saldo

**Como** cliente del banco,  
**quiero** visualizar mi saldo actualizado en la pantalla principal,  
**para** conocer rápidamente el estado de mis cuentas.

### Criterios de aceptación:
1. El sistema muestra el saldo de cada cuenta (ahorros y corriente).  
2. La información se actualiza automáticamente al iniciar sesión.  
3. Si ocurre un error al obtener los datos, se debe mostrar un mensaje claro con opción de reintentar.

---

## Historia de usuario 2 — Transferencias

**Como** cliente del banco,  
**quiero** realizar transferencias entre mis cuentas o a terceros,  
**para** mover mi dinero sin necesidad de ir a una sucursal.

### Criterios de aceptación:
1. El formulario solicita cuenta origen, destino, monto y descripción.  
2. El sistema valida que el saldo sea suficiente antes de confirmar la operación.  
3. Después de la transferencia, se genera un comprobante descargable.

---

## Historia de usuario 3 — Bloqueo de tarjeta

**Como** cliente del banco,  
**quiero** bloquear temporalmente mi tarjeta desde la aplicación,  
**para** evitar usos no autorizados en caso de pérdida o sospecha de fraude.

### Criterios de aceptación:
1. El usuario puede activar o desactivar el bloqueo desde un botón.  
2. La tarjeta queda inmediatamente inhabilitada para compras y retiros.  
3. La acción se registra en el historial y se envía una notificación al correo del cliente.



# 9. Actividad final

Desafío:  
Elige una aplicación que uses todos los días (por ejemplo: WhatsApp, Spotify, Moodle, Gmail).  
Redacta 3 historias de usuario con criterios de aceptación para nuevas funciones que te gustaría tener.

---

## Aplicación elegida: WhatsApp

---

## Historia de usuario 1 — Programar mensajes

**Como** usuario de WhatsApp,  
**quiero** programar mensajes para enviarlos automáticamente a una hora específica,  
**para** asegurarme de enviar recordatorios sin tener que hacerlo manualmente.

### Criterios de aceptación:
1. El usuario puede elegir fecha y hora antes de enviar el mensaje.  
2. El mensaje programado se envía automáticamente incluso si la aplicación está en segundo plano.  
3. El usuario puede editar o cancelar un mensaje programado antes del envío.

---

## Historia de usuario 2 — Buscar dentro de audios

**Como** usuario de WhatsApp,  
**quiero** buscar texto dentro de la transcripción de notas de voz,  
**para** encontrar información sin escuchar todo el audio.

### Criterios de aceptación:
1. La búsqueda muestra coincidencias dentro de las transcripciones.  
2. Al seleccionar un resultado, el reproductor salta al segundo exacto donde aparece la palabra.  
3. El usuario puede activar o desactivar la transcripción por chat para proteger su privacidad.

---

## Historia de usuario 3 — Respuestas automáticas por horario

**Como** usuario de WhatsApp,  
**quiero** configurar respuestas automáticas según horarios específicos,  
**para** responder de manera automática cuando no estoy disponible.

### Criterios de aceptación:
1. El usuario define el mensaje automático y los horarios en que estará activo.  
2. La respuesta automática se envía solo una vez por contacto cada periodo configurable.  
3. El usuario puede ver un historial básico de respuestas enviadas.
