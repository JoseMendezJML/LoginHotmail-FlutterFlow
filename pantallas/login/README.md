# Pantalla Login — LoginHotmail

## Descripción

Se desarrolló la interfaz de inicio de sesión de LoginHotmail mediante FlutterFlow, utilizando un diseño centrado y una identidad visual azul.

## Componentes implementados

- Ícono de correo electrónico.
- Título LoginHotmail.
- Mensaje: Inicia sesión con tu cuenta Microsoft.
- Botón Iniciar sesión con Microsoft.
- Botón temporal Probar navegación.

## Funcionamiento

### Botón Microsoft
Se configuró la acción `On Tap → Show Snack Bar`, que muestra el mensaje:

"Inicio de sesión con Microsoft en desarrollo".

Actualmente este botón no realiza autenticación real.

### Botón Probar navegación
Se configuró la acción `On Tap → Navigate To → BienvenidaPage`, que permite comprobar las demás pantallas de la aplicación.

Este acceso es temporal y deberá eliminarse cuando se implemente la autenticación con Microsoft.

## Pruebas realizadas

| Prueba | Resultado |
|---|---|
| Splash navega automáticamente a Login | Correcto |
| Se muestra la interfaz de Login | Correcto |
| Botón Microsoft muestra el mensaje informativo | Correcto |
| Botón temporal abre BienvenidaPage | Correcto |
| Navegación hacia AcercaDePage | Correcto |
| Navegación y regreso desde los perfiles | Correcto |

## Estado

Interfaz y navegación de prueba funcionales.

**Pendiente:** implementar la autenticación real mediante Microsoft OAuth 2.0/OpenID Connect y restringir el acceso a usuarios autenticados.