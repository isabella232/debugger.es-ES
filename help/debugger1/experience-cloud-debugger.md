---
description: Debugger examina las páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud
keywords: debugger;experience cloud debugger extension;chrome;extension
seo-description: 'Documentación técnica para la extensión de Chrome de Adobe Experience Cloud Debugger: Examine sus páginas web y comprenda los problemas con las implementaciones de la solución de Experience Cloud'
seo-title: Extensión de Chrome de Adobe Experience Cloud Debugger
title: Extensión de Adobe Experience Cloud Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
translation-type: tm+mt
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 85%

---


# Extensión de Adobe Experience Cloud Debugger {#adobe-experience-cloud-debugger-extension}

La [extensión de Adobe Experience Cloud Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-cloud-de/ocdmogmohccmeicdhlhhgepeaijenapj) examina sus páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud.

Utilice la extensión de Adobe Experience Cloud Debugger con otras soluciones de activación de Adobe para un flujo de trabajo como el siguiente:

1. Use [Adobe Experience Platform Launch](https://docs.adobe.com/content/help/es-ES/launch/using/overview.html) or [DTM](https://docs.adobe.com/content/help/es-ES/dtm/using/dtm-home.html) to insert code that activates [Adobe Experience Cloud](https://docs.adobe.com/content/help/es-ES/experience-cloud/user-guides/home.html) solutions on your pages.

1. Use [Adobe Experience Platform Auditor](https://docs.adobe.com/content/help/es-ES/auditor/using/overview.html) to test your implementations.
1. Utilice la extensión de Adobe Experience Cloud Debugger para depurar los problemas que ha encontrado Auditor o examinar otra información sobre las implementaciones.

Los pasos anteriores no se realizan necesariamente en ese orden, pero es un proceso común.

Aunque puede ejecutar Debugger en cualquier página web, los datos que no sean públicos solo estarán disponibles en la extensión si se ha autenticado en Experience Cloud en una de las pestañas de Chrome abiertas.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use Debugger para recopilar información que le ayudará a comprender cómo se implementan las soluciones de Experience Cloud. Por ejemplo:

* **Inicio de plataforma:** Ver qué propiedad, entorno y compilación se implementan en una página.
* **Target:** Consulte para qué actividades cumple o no los requisitos y por qué.
