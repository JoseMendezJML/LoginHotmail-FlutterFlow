# Pantalla de Bienvenida

## Descripción
Se desarrolló la pantalla BienvenidaPage utilizando FlutterFlow como parte de la aplicación LoginHotmail.

Esta interfaz representa el menú principal que se mostrará después de que el usuario inicie sesión correctamente.

## Diseño
- Fondo de pantalla: `#F5F7FA`.
- Título principal: ¡Bienvenido!
- Nombre de la aplicación: LoginHotmail.
- Botón Acerca de nosotros.
- Botón Cerrar sesión.
- Elementos centrados y distribuidos verticalmente.

## Funcionamiento
Se configuró el botón **Acerca de nosotros** mediante el evento `On Tap` y la acción `Navigate To`, estableciendo `AcercaDePage` como destino.

El botón Cerrar sesión está diseñado, pero su funcionamiento se implementará cuando se integre la autenticación con Microsoft.

## Estado
Diseño base terminado y navegación hacia AcercaDePage configurada. La autenticación todavía se encuentra pendiente.

## Evidencia
Captura: `bienvenida.png`.