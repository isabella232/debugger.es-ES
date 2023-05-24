---
description: Debugger examina las páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud
keywords: debugger;extensión de experience cloud debugger;chrome;extensión
seo-description: Technical documentation for the Adobe Experience Cloud Debugger Chrome Extension - examine your web pages and understand problems with your Experience Cloud solution mplementations
seo-title: Adobe Experience Cloud Debugger Chrome Extension
title: Extensión de Adobe Experience Cloud Debugger
uuid: 42e2c8a2-548a-4a3f-b57d-532535a0e7b9
exl-id: 02d88172-3fb1-4111-a80d-e9d46df9ea1e
source-git-commit: 3b07bfe5764b46a2510b577df8978a35a753ab7b
workflow-type: tm+mt
source-wordcount: '255'
ht-degree: 84%

---

# Extensión de Adobe Experience Cloud Debugger{#adobe-experience-cloud-debugger-extension}

>[!IMPORTANT]
>
>Actualmente hay disponible una nueva versión de Debugger. Para obtener información sobre las funcionalidades más recientes, consulte [Documentación de Adobe Experience Platform Debugger](../debugger2/experience-cloud-debugger.md).

La [extensión de Adobe Experience Cloud Debugger para Chrome](https://chrome.google.com/webstore/detail/adobe-experience-platform/bfnnokhpnncpkdmbokanobigaccjkpob) examina sus páginas web y le ayuda a encontrar problemas con la implementación de las soluciones de Experience Cloud.

Utilice la extensión de Adobe Experience Cloud Debugger con otras soluciones de activación de Adobe para un flujo de trabajo como el siguiente:

1. Uso [etiquetas](https://experienceleague.adobe.com/docs/launch/using/home.html?lang=es) para insertar código que se active [Adobe Experience Cloud](https://experienceleague.adobe.com/docs/home.html) soluciones en sus páginas.
1. Utilizar Adobe Experience Platform Auditor para probar las implementaciones.
1. Utilice la extensión de Adobe Experience Cloud Debugger para depurar los problemas que ha encontrado Auditor o examinar otra información sobre las implementaciones.

Los pasos anteriores no se realizan necesariamente en ese orden, pero es un proceso común.

Aunque puede ejecutar Debugger en cualquier página web, los datos que no sean públicos solo estarán disponibles en la extensión si se ha autenticado en Experience Cloud en una de las pestañas de Chrome abiertas.

## Casos de uso {#section-9fcd0583ed184943a8f0c2d3c00658e0}

Use Debugger para recopilar información que le ayudará a comprender cómo se implementan las soluciones de Experience Cloud. Por ejemplo:

* **Platform Launch:** ver qué propiedad, entorno y compilación se implementan en una página.
* **Target:** consulte para qué actividades cumple o no los requisitos y por qué.
