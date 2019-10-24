---
description: Uso de las fichas Solución en Adobe Debugger
keywords: depurador;extensión del depurador de Experience Cloud;chrome;extensión;resumen;borrar;solicitudes;soluciones;solución;información;análisis;destino;administrador de público;optimizador de medios;amo;servicio de ID
seo-description: Uso de las fichas Solución en Adobe Debugger
seo-title: Fichas de solución en Adobe Debugger
title: Fichas de solución
uuid: 5e999ef2-6399-4ab5-a841-3a839d081728
translation-type: tm+mt
source-git-commit: 3fd50cde86f0dfc5f66d8faf63112adf24beeac0

---


# Fichas de solución{#solution-tabs}

Haga clic en las fichas de la solución para ver los resultados de soluciones específicas de Adobe Experience Cloud.

## Analytics {#section-f71dfcc22bb44c86bec328491606a482}

La ficha Análisis proporciona información sobre la implementación [de Analytics](https://experiencecloud.adobe.com/resources/help/en_US/reference/) .

**Visitas**

De forma predeterminada, todas las llamadas al servidor realizadas al mismo grupo de informes se contraen.

![](assets/analytics-hits.jpg)

**** Descargar: Descargue información sobre todos los grupos de informes mostrados como una hoja de cálculo de Excel.

**** Borrar todas las solicitudes: Elimine todas las solicitudes mostradas de la vista Análisis. Después de borrar las solicitudes, se mostrarán nuevas solicitudes cuando se produzcan.

Haga clic en la ID del grupo de informes para expandir la vista:

![](assets/analytics-hits-expand.jpg)

Esta pantalla muestra todas las solicitudes desde que se abrió el depurador o se borraron las solicitudes. Los parámetros predeterminados se asignan automáticamente a nombres descriptivos. [Las variables prop y eVar](https://experiencecloud.adobe.com/resources/help/en_US/sc/implement/props_eVars.html) se pueden asignar a sus nombres descriptivos personalizados (por ejemplo, "prop1" podría mostrarse como "Tipo de usuario") si se autentica con la función "Análisis de vínculos" (ver más abajo). Las solicitudes se muestran en secuencia de izquierda a derecha.

**** Descargar: Guarde todas las solicitudes realizadas en el grupo de informes como una hoja de cálculo de Excel.

**** Borrar solicitudes: Elimine todas las solicitudes realizadas a este grupo de informes. Las nuevas solicitudes aparecen a medida que se producen.

**Cuentas vinculadas (heredadas)**

Haga clic en **[!UICONTROL Link Account]** y, a continuación, introduzca la información solicitada para vincular una cuenta de Analytics al depurador.

>[!NOTE]
>
>Actualmente, esta función solo es compatible con las credenciales de inicio de sesión de usuario heredadas de Analytics.

![](assets/analytics-link-account.jpg)

**Recuperar visitas posprocesadas**

Active la opción Recuperar visitas posteriores al procesamiento si desea ver los valores de las visitas de Analytics después de ejecutar las reglas de procesamiento. Debe iniciar sesión en Adobe Experience Cloud para que esta función funcione.

Cuando esta opción está habilitada, se agrega un parámetro de depuración a las solicitudes de Analytics. Las visitas se siguen procesando como cualquier otra visita. Debugger sondea la API de depuración de Analytics para recuperar los valores de las reglas de postprocesamiento de cualquier visita que tenga un ID de visita individual original. Las visitas posteriores al procesamiento tienen un fondo morado y se muestran junto a la visita original.

Para la mayoría de las implementaciones de Analytics, la información de reglas de posprocesamiento estará disponible en unos minutos. La implementación de Analytics para Target (A4T) tarda mucho más.

## Target {#section-988873ba5ede4317953193bd7ac5474c}

Utilice la ficha Target para ver las solicitudes de [Target](https://docs.adobe.com/content/help/en/target/using/target-home.html) o los detalles de respuesta de [seguimiento](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) de mbox.

Haga clic en **[!UICONTROL Requests]** y expanda el entorno para ver información sobre Target.

![](assets/target-requests.jpg)

Haga clic en **[!UICONTROL Clear All Requests]** para eliminar las solicitudes que se muestran actualmente. Se mostrarán más solicitudes a medida que se realicen.

También puede utilizar el filtro de Target para [habilitar el seguimiento de MBox para fines](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html)de depuración de Target.

Debe tener una ficha Chrome abierta que esté autenticada en Experience Cloud para habilitar el seguimiento de mbox. Una vez activado, muestra el nombre de usuario de su ID de Adobe. Amplíe su nombre de usuario para mostrar los códigos de cliente de Target asociados con las organizaciones de Experience Cloud a las que tiene acceso. Haga clic en el código de cliente para el que desea habilitar el seguimiento de mbox y confirme que aparece la marca de verificación verde. Ahora aparecerán todas las solicitudes de Target con información de seguimiento de mbox, agrupadas por código de cliente. Para explorar la información de seguimiento de mbox, expanda la solicitud para ver las fichas:

* [Actividades](https://docs.adobe.com/content/help/en/target/using/activities/activities.html) La ficha Actividades muestra todas las actividades asociadas al nombre de la solicitud de Target, independientemente de si cumple los requisitos para la actividad. "Actividades coincidentes" son las actividades para las que cualificó y cuyas ofertas se entregaron en la respuesta. Puede ampliar el nombre de la actividad para confirmar la experiencia en la que se encuentra y las audiencias y condiciones de segmentación que le cualifican para la actividad. "Actividades evaluadas" son todas las actividades evaluadas, independientemente de si reúne los requisitos. Para solucionar el problema por el que no cumple los requisitos para una actividad que fue "Evaluada" pero no "Coincidida", expanda el nombre de la actividad y revise la sección "Audiencias no coincidentes".

* Solicitud

   La ficha de solicitud de Seguimiento de [mbox](https://docs.adobe.com/content/help/en/target/using/activities/troubleshoot-activities/content-trouble.html) es similar a la ficha de solicitud principal. Puede ver todos los parámetros pasados por la solicitud de Target, además de los encabezados de solicitud.
* Perfil

   Expanda la sección Instantánea de perfil para ver la información [de](https://docs.adobe.com/content/help/en/target/using/audiences/visitor-profiles/variables-profiles-parameters-methods.html) perfil almacenada sobre usted como visitante en la base de datos de perfiles de Target. Aquí se exponen todos los perfiles en mbox y de secuencia de comandos, así como algunos perfiles del sistema. La columna Estado muestra qué perfiles han cambiado en el ámbito de esta solicitud, así como sus valores antes y después de que la solicitud ingresara al sistema de perfiles.
* Audience Manager

   Las secciones "segmentIds" y "cachedSegmentIds" de la ficha Audience Manager exponen los ID de [audiencias](https://docs.adobe.com/content/help/en/target/using/audiences/target.html) compartidas de Experience Cloud a Target y para las que ha calificado. Pueden ser audiencias creadas en Audience Manager, Analytics o el generador de audiencias en el servicio principal Personas. Estos ID se pueden buscar en la interfaz de usuario de Audience Manager para encontrar el nombre de la audiencia.

El siguiente vídeo muestra la funcionalidad general de Target:

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=spa)

El siguiente vídeo muestra el seguimiento de mbox:

>[!VIDEO](https://video.tv.adobe.com/v/23113t2/?captions=spa)

## Audience Manager {#section-1d4484f8b46f457f859ba88039a9a585}

Utilice la ficha [Audience Manager](https://experiencecloud.adobe.com/resources/help/en_US/aam/) para ver los detalles de [los eventos](https://experiencecloud.adobe.com/resources/help/en_US/aam/dcs-event-calls.html). Haga clic en la organización para expandirla y mostrar la información.

![](assets/audience-manager.jpg)

Haga clic en **[!UICONTROL Clear All Events]** para restablecer la información mostrada. Aparecerán nuevos eventos a medida que ocurran.

**Sincronización de ID**

La sincronización de ID es el primer paso en el proceso de transferencia de datos entrante y asincrónico. En este paso, Audience Manager y el proveedor comparan y coinciden los ID de sus respectivos visitantes del sitio.

![](assets/aam-idsync.jpg)

Consulte Sincronización [de ID para transferencias](https://experiencecloud.adobe.com/resources/help/en_US/aam/c_id_sync_in.html) de datos de entrada en la documentación del producto de Audience Manager para obtener más información.

## Advertising Cloud {#section-ee80a9c509f2462c89c1e5bd8d05d7c8}

Utilice la ficha Advertising Cloud para ver las solicitudes de Advertising Cloud.

Haga clic en **[!UICONTROL Requests]** y expanda el entorno para ver información sobre Advertising Cloud.

Haga clic en **[!UICONTROL Clear All Requests]** para eliminar las solicitudes que se muestran actualmente. Se mostrarán más solicitudes a medida que se realicen.

## Servicio Experience Cloud ID {#section-a96c32f8e63a4991abb296f6e8ea01cf}

Utilice la ficha Servicio de ID de Experience Cloud para ver las solicitudes del servicio [de ID de](https://experiencecloud.adobe.com/resources/help/en_US/mcvid/) Experience Cloud.

Haga clic en **[!UICONTROL Requests]** y expanda el entorno para ver información sobre el servicio Experience Cloud ID.

Haga clic en **[!UICONTROL Clear All Requests]** para eliminar las solicitudes que se muestran actualmente. Se mostrarán más solicitudes a medida que se realicen.
