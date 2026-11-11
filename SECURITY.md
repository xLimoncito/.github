# Política de seguridad

## Cómo reportar una vulnerabilidad

Si encontrás un problema de seguridad en Limoncito (autenticación, pagos, acceso a contenido pago, exposición de datos u otro fallo parecido), no abras un issue público.

Escribinos a **soporte@xlimoncito.com**.

Incluí:

- Una descripción clara del problema
- Pasos para reproducirlo, o una prueba de concepto si es seguro compartirla
- A quién podría afectar
- Un contacto para el seguimiento

Buscamos confirmar la recepción dentro de **48 horas hábiles**.

## Alcance

Entra, por ejemplo:

- Acceso no autorizado a cuentas o a contenido pago
- Abuso de pagos o webhooks que permita robar fondos o habilitar acceso gratis
- XSS, CSRF, SSRF o inyección contra xlimoncito.com
- Exposición de secretos o de datos personales

Queda afuera, por ejemplo:

- Ingeniería social contra usuarios
- Denegación de servicio o ataques volumétricos
- Fallos que solo aparecen en navegadores viejos, o CVEs ya públicos en dependencias sin un exploit que funcione sobre nuestro stack

## Puerto seguro

No vamos a iniciar acciones legales contra quien investigue de buena fe y:

- Evite violar la privacidad, destruir datos o interrumpir el servicio
- Nos dé un tiempo razonable para corregir antes de publicar el hallazgo

Gracias por ayudar a cuidar Limoncito.
