# Pruebas de navegación — LoginHotmail

## Objetivo
Comprobar la navegación entre las pantallas desarrolladas en FlutterFlow antes de implementar la autenticación real con Microsoft.

## Entorno
- Plataforma: FlutterFlow.
- Modalidad: versión web.
- Método de prueba: Test Mode.
- Proyecto: LoginHotmail.

## Casos de prueba

| ID | Prueba | Resultado |
|---|---|---|
| CP-01 | Abrir la aplicación y mostrar SplashPage | Correcto |
| CP-02 | Esperar 3000 ms y navegar hacia LoginPage | Correcto |
| CP-03 | Utilizar el botón temporal de Login para abrir BienvenidaPage | Pendiente de confirmar |
| CP-04 | Abrir AcercaDePage desde BienvenidaPage | Pendiente de confirmar |
| CP-05 | Abrir los cuatro perfiles individuales | Pendiente de confirmar |
| CP-06 | Regresar desde cada perfil mediante Navigate Back | Pendiente de confirmar |

## Configuración realizada

### SplashPage
Se configuró el evento `On Page Load` con las acciones `Wait (Delay)` de 3000 ms y `Navigate To LoginPage`.

### LoginPage
Se agregó un botón temporal de prueba para navegar hacia BienvenidaPage sin autenticación.

### BienvenidaPage
Se configuró el botón Acerca de nosotros para abrir AcercaDePage.

### AcercaDePage
Se configuraron los botones correspondientes a los cuatro integrantes para navegar a sus perfiles.

### Perfiles
Se configuró la acción Navigate Back en los botones Regresar.

## Observaciones
La autenticación con Hotmail todavía no está implementada. El botón provisional de Login debe eliminarse antes de la entrega final.

Los casos pendientes deberán actualizarse con los resultados observados durante la ejecución completa de la aplicación.