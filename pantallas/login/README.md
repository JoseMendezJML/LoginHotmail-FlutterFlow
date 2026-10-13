# Pantalla Login

## Descripción
Se creó LoginPage en FlutterFlow como pantalla destinada a la autenticación de usuarios mediante cuentas Microsoft, incluyendo Hotmail y Outlook.

Actualmente se utiliza un botón provisional para comprobar la navegación hacia el menú principal.

## Diseño
- Fondo de pantalla: `#F5F7FA`.
- Sin AppBar.
- Botón temporal: Probar navegación.
- Diseño base pendiente de personalizar.

## Funcionamiento actual
El botón Probar navegación utiliza el evento `On Tap` con la acción `Navigate To`, estableciendo BienvenidaPage como destino.

Este botón permite verificar el funcionamiento de las demás pantallas sin implementar todavía la autenticación.

## Funcionalidad pendiente
- Registrar y configurar la aplicación en Microsoft.
- Implementar la autenticación mediante OAuth 2.0 y OpenID Connect.
- Validar el inicio de sesión.
- Permitir el acceso al menú principal solamente a usuarios autenticados.
- Eliminar el botón temporal de prueba.

## Estado
Navegación temporal configurada. La autenticación real con Hotmail continúa pendiente.

## Evidencia
Captura: `loginprueba.png`.