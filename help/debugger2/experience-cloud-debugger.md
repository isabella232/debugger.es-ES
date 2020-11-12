---
description: Experience Platform Debugger examina las páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud
keywords: debugger;experience Platform Debugger extension;chrome;extension
seo-description: 'Documentación técnica para la extensión de Chrome y Firefox de Adobe Experience Platform Debugger : Examine sus páginas web y comprenda los problemas con las implementaciones de la solución de Experience Cloud'
seo-title: Extensión de Adobe Experience Platform Debugger para Chrome y Firefox
title: Extensión de Adobe Experience Platform Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 62%

---


# (Beta) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger se encuentra en la versión beta. La documentación y las funciones están sujetas a cambios.

[Adobe Experience Platform Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) y [Firefox](https://addons.mozilla.org/es/firefox/addon/adobe-experience-platform-dbg/) examina sus páginas web y le ayuda a encontrar problemas con la implementación de sus soluciones Experience Cloud.

Utilice Platform Debugger con otras soluciones de activación de Adobe para un flujo de trabajo como el siguiente:

1. Utilizar [Launch](https://docs.adobe.com/content/help/es-ES/launch/using/overview.html) o [DTM](https://docs.adobe.com/content/help/es-ES/dtm/using/dtm-home.html) para insertar código que active las soluciones de [Adobe Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/experience-cloud.html) en sus páginas.

1. Use [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/es-ES/auditor/using/overview.html) to test your implementations.
1. Utilice la extensión de Adobe Experience Platform Debugger para depurar los problemas que ha encontrado Auditor o examinar otra información sobre las implementaciones.

Los pasos anteriores no se realizan necesariamente en ese orden, pero es un proceso común.

Aunque puede ejecutar el depurador de plataforma en cualquier página web, los datos que no sean públicos solo estarán disponibles en la extensión si está autenticado en el Experience Cloud en una de las fichas de Chrome abiertas.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Utilice el depurador de plataformas para recopilar información que le ayudará a comprender cómo se implementan las soluciones Experience Cloud. Por ejemplo:

* **Adobe Experience Platform Launch:** Ver qué propiedad, entorno y compilación se implementan en una página.
* **Target:** Consulte para qué actividades cumple o no los requisitos y por qué.

## Tutorial de vídeo

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)