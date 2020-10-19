---
description: Pantalla de conexiones de Experience Platform Debugger
keywords: debugger;experience Platform Debugger extension;chrome;extension;network;information
seo-description: Pantalla de conexiones de Experience Platform Debugger
seo-title: Información de red
title: Información de red
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: ht
source-git-commit: 53f027d5a5ae56c7a8e812b10a2649a38df3b31d
workflow-type: ht
source-wordcount: '227'
ht-degree: 100%

---


# Red {#network}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger se encuentra en la versión beta. La documentación y las funciones están sujetas a cambios.

Para ver la información de red, haga clic en **[!UICONTROL Network]**.

La pantalla Red agrega todas las llamadas de la solución Adobe Experience Cloud realizadas en la página y las muestra en orden de izquierda a derecha. Los parámetros estándar se etiquetan automáticamente con nombres descriptivos y se organizan para agrupar parámetros comunes en la misma función.

![](assets/network.jpg)

Esta pantalla es útil para comparar pares de valor clave entre visitas individuales. Aquí se puede confirmar que los parámetros utilizados para las integraciones, como el ID de visitante de Experience Cloud o el ID de datos suplementarios, son coherentes en todas las integraciones.

>[!NOTE]
>
>En este momento, no todos los parámetros pasados en las llamadas de solución (por ejemplo, variables de contexto de Analytics, parámetros personalizados de Target o ID de cliente del servicio de Experience Cloud ID) están visibles en la pantalla Red.

Para cambiar la información por solución, seleccione la solución que desee ver en la lista de la navegación izquierda. El siguiente ejemplo se filtra para mostrar solo Analytics:

![](assets/network-analytics.jpg)

Para volver a mostrar todas las soluciones, haga clic en **[!UICONTROL Network]**.

Haga clic en un elemento en la vista Red para verlo más grande. Desde la ventana de vista expandida, puede copiar la información mostrada en el portapapeles.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Para borrar la lista, haga clic en **[!UICONTROL Remove Events]**.

Para descargar un archivo de Excel que contenga la información de esta pantalla, haga clic en **[!UICONTROL Download]**.