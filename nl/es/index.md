---

copyright:
  years: 2017, 2018
lastupdated: "2018-05-21"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:screen: .screen}

# Guía de aprendizaje de iniciación
{: #create}

En {{site.data.keyword.Bluemix}}, puede crear aplicaciones web y móviles a nivel de empresa y aprovechar las extensiones de nube alojadas por {{site.data.keyword.Bluemix_notm}}. Puede utilizar la consola de {{site.data.keyword.Bluemix}} y las herramientas de línea de mandatos para crear, ejecutar y desplegar las apps. Puede empezar de dos formas: creando una con un kit de iniciación que gestiona el proceso en su nombre, o si conoce exactamente lo que necesita, compilando su app con los recursos que necesite.
{:shortdesc}

Utilice un kit de iniciación para empezar rápidamente su app y prepárela para el futuro desarrollo. Seleccione un kit de iniciación y un lenguaje de programación, cree una app y configure una cadena de herramientas de DevOps para desplegar su app automáticamente. También puede descargar el código para una inspección inmediata.

Los kits de iniciación están disponibles para muchas categoría, entre otras:

* [Watson](https://console.bluemix.net/developer/watson){:new_window}
* [Apple](https://console.bluemix.net/developer/appledevelopment){:new_window}
* [Móvil](https://console.bluemix.net/developer/mobile){:new_window}
* [App web](https://console.bluemix.net/developer/appservice){:new_window}
* [Seguridad](https://console.bluemix.net/developer/security){:new_window}
<!--* [Watson Data Platform developer console](https://console.bluemix.net/developer/dataplatform)-->
* [Finanzas](https://console.bluemix.net/developer/finance){:new_window}

## Antes de empezar

[Regístrese](https://console.bluemix.net){: new_window} para una cuenta de {{site.data.keyword.cloud_notm}}. Especifique su correo electrónico, nombre, empresa, región, y número de teléfono.

No es necesaria una tarjeta de crédito para registrarse y obtener una cuenta gratuita, sin embargo, si especifica una tarjeta de crédito tendrá acceso a más recursos y facilitará la compresión completa de todo lo que {{site.data.keyword.cloud_notm}} ofrece.

## Paso 1: Crear una app
{: #project}

1. Pulse el icono **Menú** ![Icono Menú](../icons/icon_hamburger.svg) > **Apps web**.

2. Pulse **Iniciación** en la sección **Empezar desde web**.

3. Seleccione el kit de iniciación que desee, lea los detalles y pulse **Crear**.

  Para ver lo que se incluye en el kit de iniciación, expanda el mosaico en el panel de control de Kits de iniciación de App Service.
  {: tip}

4. Proporcione un nombre para la app, seleccione el idioma y pulse **Crear**.

Acaba de crear una app.

Para inspeccionar el código, pulse **Descargar código** en la página de detalles de la app. Compruebe el archivo `README.md` en el archivo comprimido descargado para averiguar si es necesario realizar algo más para ejecutar su app de inicio.
{: tip}

## Paso 2: Añadir recursos
{: #addResources}

La mayoría de los kits de iniciación indican a {{site.data.keyword.cloud_notm}} iniciar de forma automática el suministro de recursos en su nombre. También es posible asociar más recursos a su app pulsando **Añadir recurso** en la página de detalles de la app.

Para desarrollar y ejecutar la app de forma local, utilice [{{site.data.keyword.dev_cli_notm}}](../cli/idt/index.html)
{: tip}

## Paso 3: Desplegar en {{site.data.keyword.cloud_notm}}
{: #deploy}

Pulse **Desplegar en la nube** en la página de detalles de la app, seleccione un método de despliegue (por ejemplo, clúster de Kubernetes o app de Cloud Foundry) y, a continuación, pulse **Crear**. {{site.data.keyword.cloud_notm}} crea de forma automática una cadena de herramientas abierta que se completa con un repositorio de Git y un conducto de entrega continua. Visualice el componente del conducto de la nueva cadena de herramientas para iniciar el proceso de compilación y despliegue inicial de forma que pueda visualizar en unos minutos en ejecución su nueva app.

Estará ahora preparado para el desarrollo iterativo y la entrega continua.
