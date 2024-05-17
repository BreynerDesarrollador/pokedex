# Cómo publicar sitios web desde Visual Studio 2022 con Azure App Service

## Requisitos previos

- Tener una suscripción activa de Azure (puedes utilizar tu cuenta de Azure for Students).
- Tener Visual Studio 2022 instalado en tu equipo.
- Tener un proyecto de sitio web listo para publicar.

## Pasos para publicar

1. **Abrir el proyecto en Visual Studio 2022**
  - Abre Visual Studio 2022 en tu equipo (Versión que tenemos como prueba).
  - Selecciona "Abrir un proyecto o solución" y navega hasta la ubicación de tu proyecto de sitio web.
  - Haz clic en "Abrir" para cargar el proyecto de pokedex en la ubicación que se guardó el proyecto clonado del repositorio de github (https://github.com/rcuello/ac4dem1a/tree/master/sistemas-distribuidos/poke-dex-lab).

2. **Crear un Servicio de Aplicaciones de Azure**
  - En la barra de herramientas de Visual Studio, haz clic en "Vista" > "Explorador de servidores".
  - Expande el nodo de "Azure" y haz clic derecho en "App Service".
  - Selecciona "Crear App Service".
  - Sigue las instrucciones del asistente para crear un nuevo Servicio de Aplicaciones de Azure.
  - Proporciona un nombre de aplicación único y selecciona tu suscripción de Azure.
  - Configura otros detalles como el grupo de recursos, el plan de App Service y la región según tus preferencias.
  - Haz clic en "Crear" para finalizar la creación del Servicio de Aplicaciones.

3. **Publicar el sitio web**
  - En el "Explorador de soluciones", haz clic derecho en tu proyecto de sitio web.
  - Selecciona "Publicar".
  - En el cuadro de diálogo "Publicar", selecciona "Azure" como destino de publicación.
  - Selecciona "Azure App Service (Windows)" o "Azure App Service (Linux)" dependiendo de tus necesidades.
  - Haz clic en "Siguiente".
  - Selecciona la suscripción de Azure que quieres utilizar y luego selecciona el Servicio de Aplicaciones que creaste anteriormente.
  - Haz clic en "Siguiente" y sigue las instrucciones para configurar los ajustes de publicación según tus preferencias.
  - Haz clic en "Finalizar" para iniciar el proceso de publicación.

4. **Monitorear el proceso de publicación**
  - Visual Studio comenzará a publicar tu sitio web en el Servicio de Aplicaciones de Azure.
  - Puedes monitorear el progreso en la ventana "Salida" de Visual Studio.
  - Una vez que el proceso se complete, se te notificará el éxito de la publicación.

5. **Acceder al sitio web publicado**
  - En el "Explorador de servidores", haz clic derecho en el Servicio de Aplicaciones que acabas de publicar.
  - Selecciona "Abrir en el navegador".
  - Esto abrirá una pestaña de tu navegador web predeterminado, mostrando tu sitio web publicado en Azure App Service (https://pokedex.azurewebsites.net).

En este punto ya se debe poder visualizar el proyecto en internet.
