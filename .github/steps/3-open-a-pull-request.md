<!--
  <<< Author notes: Step 3 >>>
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.
-->

## Paso 3: Abrir un pull request

_¡Buen trabajo haciendo ese commit! :sparkles:_

Ahora que has realizado un cambio en el proyecto y creado un commit, ¡es hora de compartir tu cambio propuesto a través de un pull request!

**¿Qué es un pull request?**: La colaboración ocurre en un _[pull request](https://docs.github.com/es/get-started/quickstart/github-glossary#pull-request)_. El pull request muestra los cambios en tu rama a otras personas y les permite aceptar, rechazar o sugerir cambios adicionales a tu rama. En una comparación lado a lado, este pull request mantendrá los cambios que acabas de hacer en tu rama y propondrá aplicarlos a la rama principal del proyecto `main`. Para más información sobre los pull requests, consulta "[Acerca de los pull requests](https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)".

### :keyboard: Actividad: Crear un pull request

Puede que hayas notado después de tu commit que se mostró un mensaje indicando tu reciente push a tu rama y proporcionando un botón que dice **Compare & pull request**.

![captura de pantalla del mensaje y botón](/images/compare-and-pull-request.png)

Para crear un pull request automáticamente, haz clic en **Compare & pull request**, y luego salta al paso 6 a continuación. Si no haces clic en el botón, las instrucciones a continuación te guían a través del proceso manual para configurar el pull request.

1. Haz clic en la pestaña **Pull requests** en el menú de encabezado de tu repositorio.
2. Haz clic en **New pull request**.
3. En el desplegable **base:**, asegúrate de que esté seleccionado **main**.
4. Selecciona el desplegable **compare:**, y haz clic en `my-first-branch`.

   ![captura de pantalla mostrando ambas selecciones de rama](/images/pull-request-branches.png)

5. Haz clic en **Create pull request**.
6. Ingresa un título para tu pull request. Por defecto, el título será automáticamente el nombre de tu rama. Para este ejercicio, editemos el campo para que diga `Add my first file`.
7. El siguiente campo te ayuda a proporcionar una descripción de los cambios que hiciste. Aquí, puedes agregar una descripción de lo que has logrado hasta ahora. Como recordatorio, hasta el momento has: creado una nueva rama, creado un archivo y hecho un commit.

   ![captura de pantalla mostrando el pull request](/images/Pull-request-description.png)

8. Haz clic en **Create pull request**. Serás automáticamente navegado a tu nuevo pull request.
9. Espera unos 20 segundos y luego actualiza esta página (la que estás siguiendo las instrucciones). [GitHub Actions](https://docs.github.com/es/actions) se actualizará automáticamente al siguiente paso.

   **Nota**: ¡Puede que veas evidencia de que GitHub Actions se está ejecutando en la pestaña con el pull request abierto! La imagen a continuación muestra una línea que podrías ver en tu pull request después de que la Action termine de ejecutarse.

   ![captura de pantalla de un ejemplo de una línea de actions](/images/Actions-to-step-4.png)