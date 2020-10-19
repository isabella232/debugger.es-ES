---
description: Pantalla de eventos de Experience Platform Debugger
keywords: debugger;experience platform debugger extension;chrome;extension;events;dtm;target
seo-description: Pantalla de eventos de Experience Platform Debugger
seo-title: Eventos
title: Eventos
translation-type: ht
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: ht
source-wordcount: '169'
ht-degree: 100%

---


# Eventos {#events}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger se encuentra en la versión beta. La documentación y las funciones están sujetas a cambios.

La pantalla Eventos proporciona una vista gráfica de los eventos que se producen y que se muestran en una cronología.

![](assets/events.jpg)

Para cada evento, aparece un icono para la solución de aplicable en la cronología. Los iconos también muestran cambios en la capa de datos (si está activada). Pase el ratón sobre un icono para ver un resumen del evento. Haga clic en el evento para obtener más información. Puede pulsar Mayús + clic o Ctrl + clic para ver varios eventos.

![](assets/events-details.jpg)

Haga clic en un detalle para obtener más información.

![](assets/events-details-more.jpg)

## Rastrear cambios en la capa de datos

Para habilitar el seguimiento de los cambios en la capa de datos en la cronología:

1. Haga clic en el icono de engranaje en la parte superior derecha.
1. Introduzca el nombre de la capa de datos.

   ![](assets/event-datalayer.jpg)

1. Haga clic en **[!UICONTROL Save]**.

Los detalles del cambio de la capa de datos muestran cualquier componente que se haya eliminado o agregado. Puede hacer clic en **{}** para ver más información en la capa de datos.

## Descargar información del evento

Haga clic en **[!UICONTROL Download]** para descargar un archivo de Excel que muestre información sobre las llamadas de página.