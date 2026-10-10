---
noteId: "f5ace070c46311f1a19af77fdb06813c"
tags: []

---

# Pantalla Splash

## Descripción
Se desarrolló la pantalla Splash de la aplicación LoginHotmail utilizando FlutterFlow.

Esta pantalla aparece al iniciar la aplicación y muestra el nombre del proyecto, un ícono de correo electrónico y un mensaje de bienvenida.

## Diseño
- Fondo azul `#2459A6`.
- Ícono de correo en color blanco.
- Nombre de la aplicación: LoginHotmail.
- Mensaje: Bienvenido a nuestra aplicación.
- Elementos centrados en la pantalla.

## Funcionamiento
Se configuró el evento `On Page Load` con dos acciones:

1. `Wait (Delay)`: espera de 3000 milisegundos.
2. `Navigate To`: navegación automática hacia LoginPage.

Se estableció SplashPage como pantalla inicial de la aplicación.

## Resultado
Se ejecutó una prueba en FlutterFlow y se comprobó que la pantalla Splash aparece durante tres segundos y después abre correctamente LoginPage.