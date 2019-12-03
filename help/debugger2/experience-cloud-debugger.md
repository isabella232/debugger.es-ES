---
description: Debugger examina las páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: 'Documentación técnica para Adobe Experience Cloud Debugger 2.0 Chrome y Firefox Extension: examine sus páginas web y comprenda los problemas con las implementaciones de su solución de Experience Cloud'
seo-title: Adobe Experience Cloud Debugger 2.0 Chrome y Firefox Extension
title: Adobe Experience Cloud Debugger 2.0 Extension
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Adobe Experience Cloud Debugger 2.0 Extension{#adobe-experience-cloud-debugger-extension}

The [Adobe Experience Cloud Debugger 2.0 extension for Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/adobe-experience-platform-dbg/) examines your web pages and helps you find problems with how your Experience Cloud solutions are implemented.

Utilice la extensión Adobe Experience Cloud Debugger 2.0 con otras soluciones de activación de Adobe para un flujo de trabajo como el siguiente:

1. Utilizar [Launch](https://docs.adobe.com/content/help/en/launch/using/overview.html) o [DTM](https://docs.adobe.com/content/help/en/dtm/using/dtm-home.html) para insertar código que active las soluciones de [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) en sus páginas.

1. Utilizar [Adobe Cloud Platform Auditor](https://experiencecloud.adobe.com/resources/help/en_US/auditor/) para probar las implementaciones.
1. Utilice la extensión de Adobe Experience Cloud Debugger para depurar los problemas que ha encontrado Auditor o examinar otra información sobre las implementaciones.

Los pasos anteriores no se realizan necesariamente en ese orden, pero es un proceso común.

Aunque puede ejecutar Debugger en cualquier página web, los datos que no sean públicos solo estarán disponibles en la extensión si se ha autenticado en Experience Cloud en una de las pestañas de Chrome abiertas.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use Debugger para recopilar información que le ayudará a comprender cómo se implementan las soluciones de Experience Cloud. Por ejemplo:

* **Experience Platform Launch:** Consulte qué propiedad, entorno y generación se implementan en una página.
* **Target:** Consulte para qué actividades cumple o no los requisitos y por qué.
