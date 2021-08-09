---
description: Experience Platform Debugger examina las páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud
keywords: debugger;extensión de experience Platform Debugger;chrome;extensión
seo-description: 'Documentación técnica para la extensión de Chrome y Firefox de Adobe Experience Platform Debugger: Examine sus páginas web y comprenda los problemas con las implementaciones de la solución de Experience Cloud'
seo-title: Extensión de Adobe Experience Platform Debugger para Chrome y Firefox
title: Extensión de Adobe Experience Platform Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: e02bc318-fbff-4a19-980a-d5c0a21ca300
source-git-commit: e3f0fa30fa5caeccc9a01b5d1949722836645da9
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# (Beta) Adobe Experience Platform Debugger {#adobe-experience-platform-debugger}

>[!IMPORTANT]
>
>Adobe Experience Platform Debugger se encuentra en la versión beta. La documentación y las funciones están sujetas a cambios.

[Adobe Experience Platform Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) y [Firefox](https://addons.mozilla.org/es/firefox/addon/adobe-experience-platform-dbg/) examinan sus páginas web y le permiten encontrar problemas con la implementación de las soluciones de Experience Cloud.

Utilice Platform Debugger con otras soluciones de activación de Adobe para un flujo de trabajo como el siguiente:

1. Utilizar [Launch](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=es) o [DTM](https://docs.adobe.com/content/help/es-ES/dtm/using/dtm-home.html) para insertar código que active las soluciones de [Adobe Experience Cloud](https://docs.adobe.com/content/help/es-ES/core-services/interface/experience-cloud.html) en sus páginas.

1. Utilizar [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/es-ES/auditor/using/overview.html) para probar las implementaciones.
1. Utilice la extensión de Adobe Experience Platform Debugger para depurar los problemas que ha encontrado Auditor o examinar otra información sobre las implementaciones.

Los pasos anteriores no se realizan necesariamente en ese orden, pero es un proceso común.

Aunque puede ejecutar Platform Debugger en cualquier página web, los datos que no sean públicos solo estarán disponibles en la extensión si se ha autenticado en Experience Cloud en una de las pestañas de Chrome abiertas.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use Platform Debugger para recopilar información que le ayudará a comprender cómo se implementan las soluciones de Experience Cloud. Por ejemplo:

* **Adobe Experience Platform Launch:** ver qué propiedad, entorno y compilación se implementan en una página.
* **Target:** consulte para qué actividades cumple o no los requisitos y por qué.

## Tutorial de vídeo

>[!VIDEO](https://video.tv.adobe.com/v/32156?quality=12&learn=on)
