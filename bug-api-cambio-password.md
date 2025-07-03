## Bug: Error 500 al cambiar contraseña vía API

**Pasos para reproducir:**
1. Enviar solicitud PUT a /api/user/change-password
2. Con token válido y cuerpo correcto

**Resultado esperado:**
- Estado 200 OK y contraseña cambiada

**Resultado actual:**
- Error 500 del servidor

** notas del QA **
Este error ocurre solo cuando se usa el token generado en el entorno de staging
