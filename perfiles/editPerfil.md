# Guía para personalizar el perfil individual en FlutterFlow

**Proyecto:** LoginHotmail
**Materia:** Desarrollo Móvil Integral
**Tecnología:** FlutterFlow
**Repositorio:** [https://github.com/JoseMendezJML/LoginHotmail-FlutterFlow]

## 1. Objetivo

Personalizar la pantalla de perfil individual dentro de la aplicación LoginHotmail, agregando una fotografía, nombre completo, carrera, grado, grupo y materia.

Cada integrante podrá utilizar sus propios colores, distribución y estilo visual, conservando la navegación de la aplicación.

## 2. Ubicar la pantalla del perfil

1. Abrir el proyecto LoginHotmail en FlutterFlow, cuando se tenga acceso autorizado al editor.
2. En el menú izquierdo, seleccionar **Page Selector**.
3. Buscar la pantalla correspondiente:
   - PerfilEfren
   - PerfilValeria
   - PerfilYulissa
4. Abrir únicamente la pantalla asignada.

**Importante:** no eliminar otras pantallas ni modificar SplashPage, LoginPage, BienvenidaPage o AcercaDePage.

## 3. Configurar la pantalla

Seleccionar el widget **Column** principal y establecer:

| Propiedad            | Valor                           |
| -------------------- | ------------------------------- |
| Main Axis Size       | Max                             |
| Main Axis Alignment  | Center                          |
| Cross Axis Alignment | Center                          |
| Alignment            | Center                          |
| Items Spacing        | 12                              |
| Scrollable           | Activar si el contenido no cabe |

El fondo recomendado es `#F5F7FA`, aunque puede modificarse según el diseño personal.

## 4. Agregar una fotografía

1. En el panel izquierdo, buscar el widget **Image**.
2. Arrastrarlo dentro de la Column, encima del botón Regresar.
3. Seleccionar la imagen.
4. En **Image Type**, elegir **Asset**.
5. En **Asset Image**, seleccionar o subir una fotografía personal desde la computadora.
6. Configurar estas propiedades:

| Propiedad     | Valor  |
| ------------- | ------ |
| Width         | 120 px |
| Height        | 120 px |
| Border Radius | 60     |
| Box Fit       | Cover  |

La fotografía debe aparecer con forma circular.

## 5. Agregar el nombre completo

1. Buscar el widget **Text**.
2. Colocarlo debajo de la fotografía.
3. Escribir el nombre completo.
4. Configurar:

| Propiedad   | Valor      |
| ----------- | ---------- |
| Font Size   | 22         |
| Font Weight | 700 - Bold |
| Text Color  | #2459A6    |
| Text Align  | Center     |
| Padding Top | 16         |

## 6. Agregar la información académica

Debajo del nombre, agregar tres widgets **Text** independientes con los siguientes datos:

**Carrera:** Ingeniería en Desarrollo y Gestión de Software

**Grado y grupo:** 10.º B (verificar que corresponda)

**Materia:** Desarrollo Móvil Integral

Configuración recomendada:

- Font Size: 16.
- Font Weight: 400 - Normal.
- Text Color: `#64748B`.
- Text Align: Center.
- Padding Top: 12.

Cada integrante podrá modificar la tipografía, los colores y el estilo de presentación.

## 7. Conservar el botón Regresar

La pantalla ya tiene un botón llamado **Regresar**.

No eliminarlo. Comprobar que tenga la siguiente configuración:

**Actions → On Tap → Navigation → Navigate Back**

Esta acción permite regresar a la pantalla AcercaDePage.

## 8. Personalizar el diseño

Cada integrante podrá realizar mejoras visuales, por ejemplo:

- Cambiar los colores de fondo.
- Agregar contenedores o tarjetas.
- Utilizar íconos.
- Modificar bordes y esquinas.
- Cambiar tamaños de texto.
- Organizar los datos académicos.

El diseño debe ser legible, ordenado y conservar la información solicitada.

## 9. Probar el perfil

Verificar que:

1. La fotografía se visualice correctamente.
2. El nombre y los datos académicos estén completos.
3. No existan elementos fuera de la pantalla.
4. El botón Regresar funcione.
5. No se haya afectado la navegación de las otras pantallas.

Tomar una captura del resultado final.

## 10. Registrar la contribución en GitHub

Debido a que el plan gratuito de FlutterFlow no permite la integración directa con GitHub, se documentarán los diseños, recursos y evidencias realizados.

1. Clonar el repositorio del equipo desde GitHub Desktop.
2. Crear una rama personal desde `main`, por ejemplo `feature/perfil-efren`.
3. Abrir el proyecto local en Visual Studio Code.
4. Entrar a la carpeta asignada dentro de `perfiles/`.
5. Agregar la captura del perfil y los recursos utilizados.
6. Crear un archivo `README.md` que explique el diseño, las modificaciones y las pruebas.
7. Guardar los archivos.
8. En GitHub Desktop, realizar un commit con el mensaje `docs: agregar diseño y evidencias del perfil`.
9. Seleccionar **Push origin**.
10. Crear un Pull Request hacia `main`.

**Cada integrante debe trabajar utilizando su propia cuenta de GitHub**, para que sus contribuciones puedan identificarse en el historial.

## 11. Resultado esperado

Al finalizar, cada integrante deberá entregar:

- Propuesta o personalización de su perfil.
- Fotografía y datos académicos completos.
- Captura del resultado.
- Documentación de su trabajo.
- Contribución registrada mediante GitHub.

**Nota:** si el integrante no dispone de acceso de edición al proyecto compartido en FlutterFlow, deberá elaborar su propuesta, recursos y documentación por separado para que el responsable del proyecto los integre. Subir capturas a GitHub no equivale a subir el código fuente de FlutterFlow.
