---
description: Ejecución de Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;summary;clear;requests;summary screen;solution;information;analytics;target;dtm;audience manager;launch;id service
seo-description: Ejecución de Experience Cloud Debugger
seo-title: Pantalla de resumen
title: Pantalla de resumen
uuid: 46b17eaa-b611-43cf-8c6a-67b2e9b9d940
translation-type: ht
source-git-commit: e5f85bb78ad818d3507ca48eee27bb1e44f4e1a7
workflow-type: ht
source-wordcount: '1047'
ht-degree: 100%

---


# Pantalla de resumen {#summary-screen}

Para ejecutar Adobe Experience Cloud Debugger, haga clic en el icono de extensión de la barra de extensiones y, a continuación, abra la página que desee examinar en Chrome.

![](assets/start-icon.jpg)

Aparece la pantalla Resumen de Experience Cloud Debugger.

![](assets/summary.jpg)

Esta pantalla muestra una miniatura de la página, así como la dirección URL y el título de la página. También muestra información sobre cada solución de Adobe Experience Cloud. La información mostrada varía según la solución, pero generalmente incluye información como la biblioteca y la versión de la solución (por ejemplo, “AppMeasurement v2.9”) e identificadores de cuenta (como el ID del grupo de informes de Analytics, el código de cliente de Target, el ID del socio de Audience Manager, etc.)

Los números en azul junto a las pestañas en la parte superior de la ventana muestran el número de llamadas al servidor que se han realizado. Puede restablecer estos valores a cero si hace clic en **[!UICONTROL Clear All Requests]** en la pestaña correspondiente.

Por ejemplo, la siguiente imagen muestra información sobre Adobe Target. Tenga en cuenta que, para exponer los detalles de la actividad que se muestran a continuación sin autenticación, debe implementar el detector de eventos de depuración en el administrador de códigos o etiquetas y activar los [tokens de respuesta](https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html) necesarios en la interfaz de usuario de Target.

![](assets/summary-target2.jpg)

## Ejecute una auditoría en Adobe Experience Platform Auditor {#section-82bc57440406461ebf27a16855b71655}

Puede utilizar Adobe Auditor para ejecutar una serie de auditorías en su página. Para ejecutar Platform Auditor, haga clic en **[!UICONTROL Auditor]** en el menú superior y, a continuación, haga clic en **[!UICONTROL Audit Page Now]**. Para abrir Platform Auditor, haga clic en **[!UICONTROL Run Multi-Page Audit Now]**.

## Información que aparece en Experience Cloud Debugger {#section-88a95ba53dca43d9b96a585e75e5f5cf}

Experience Cloud Debugger muestra la siguiente información para cada solución:

**Información de página**

<table id="table_FF3B9083524244D29AF350978A0AC236"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Captura de pantalla de la página </p> </td> 
   <td colname="col2"> <p>Miniatura de la página </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>URL </p> </td> 
   <td colname="col2"> <p>Dirección URL de la página </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Título </p> </td> 
   <td colname="col2"> <p>El nombre especificado en la etiqueta <span class="codeph"> &lt;TITLE&gt;</span> </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Analytics**

<table id="table_BEB9CC58E59D4D86BC895A8A51D84A2C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Grupo(s) de informes </p> </td> 
   <td colname="col2"> <p>Los <a href="https://docs.adobe.com/content/help/es-ES/analytics/admin/manage-report-suites/report-suites-admin.html" format="html" scope="external">grupos de informes</a> definen los informes completos e independientes de un sitio web concreto, de un conjunto de sitios web o de un subconjunto de páginas web. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p>Versión de <a href="https://docs.adobe.com/content/help/es-ES/analytics/implementation/js/overview.html" format="html" scope="external"> AppMeasurement</a> definida para la página. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión del visitante </p> </td> 
   <td colname="col2"> <p>Versión de la biblioteca de <a href="https://docs.adobe.com/content/help/es-ES/analytics/components/metrics/unique-visitors.html" format="html" scope="external">ID de visitante</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nombre de la página </p> </td> 
   <td colname="col2"> <p>Variable <a href="https://docs.adobe.com/content/help/es-ES/analytics/implementation/vars/page-vars/page-variables.html" format="html" scope="external">pageName</a> enviada a Analytics que contiene un nombre descriptivo del sitio. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Módulos </p> </td> 
   <td colname="col2"> <p>Los módulos cargados por Adobe Analytics. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Audience Manager**

<table id="table_784AEABADBDA4D14BB9A7A9CB9EF07C3"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Socio </p> </td> 
   <td colname="col2"> <p>El <a href="https://docs.adobe.com/content/help/es-ES/audience-manager/user-guide/dil-api/dil-instance-methods.html#getpartner" format="html" scope="external">nombre del socio</a> para la instancia DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/es-ES/audience-manager/user-guide/api-and-sdk-code/rest-apis/aam-api-dil-methods.html#return-version-dil" format="html" scope="external">Número de versión</a> de la instancia DIL. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Identificador único universal (UUID) </p> </td> 
   <td colname="col2"> <p><a href="https://docs.adobe.com/content/help/es-ES/audience-manager/user-guide/reference/ids-in-aam.html" format="html" scope="external">ID de usuario único</a> asociado a la instancia DIL. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Experience Platform Launch**

<table id="table_E9574975444A407887E26514D1BB1601"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nombre </p> </td> 
   <td colname="col2"> <p>Nombre de la <a href="https://docs.adobe.com/content/help/es-ES/launch/using/reference/admin/companies-and-properties.html" format="https" scope="external">propiedad</a> de Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p>La versión de <a href="https://developer.adobelaunch.com/extensions/reference/turbine-free-variable/" format="https" scope="external"> Turbine</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Fecha de compilación </p> </td> 
   <td colname="col2"> <p>Fecha de compilación de la <a href="https://docs.adobe.com/content/help/es-ES/launch/using/reference/publish/libraries.html" format="https" scope="external">biblioteca</a> de Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Entorno </p> </td> 
   <td colname="col2"> <p>El <a href="https://docs.adobe.com/content/help/es-ES/launch/using/reference/publish/environments.html" format="https" scope="external">entorno</a> utilizado por la biblioteca de Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Directorio de scripts </p> </td> 
   <td colname="col2"> <p>El directorio en el que se almacena el script de Platform Launch. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe DTM**

<table id="table_DC76D63FA6EF4891906B9E1D3E4A8A6C"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Nombre de la biblioteca </p> </td> 
   <td colname="col2"> <p>Nombre de la <a href="https://docs.adobe.com/content/help/es-ES/dtm/using/library-management.html" format="html" scope="external">biblioteca</a> de Adobe DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p>La versión de Turbine. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Fecha de compilación </p> </td> 
   <td colname="col2"> <p>Fecha de compilación de la <a href="https://docs.adobe.com/content/help/es-ES/dtm/using/library-management.html" format="html" scope="external">biblioteca</a> de Platform Launch. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Entorno </p> </td> 
   <td colname="col2"> <p>El entorno utilizado por la biblioteca de la DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Directorio de scripts </p> </td> 
   <td colname="col2"> <p>El directorio en el que se almacena el script de la DTM. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Servicio de Adobe Experience Cloud ID**

<table id="table_274CFCEFA8F34D16BB546B4669EC0209"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>ID de organización de Experience Cloud </p> </td> 
   <td colname="col2"> <p>Su <a href="https://docs.adobe.com/content/help/es-ES/id-service/using/home.html" format="https" scope="external"> ID de organización</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p>Versión de la biblioteca de <a href="https://docs.adobe.com/content/help/es-ES/analytics/components/metrics/unique-visitors.html" format="html" scope="external">ID de visitante</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

**Adobe Target**

<table id="table_D30E0CD20FB04E41862B22655136E043"> 
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Código de cliente </p> </td> 
   <td colname="col2"> <p>Su <a href="https://docs.adobe.com/content/help/es-ES/target/using/implement-target/client-side/deploy-at-js/implementing-target-without-a-tag-manager.html" format="html" scope="external"> código de cliente </a> de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Versión </p> </td> 
   <td colname="col2"> <p>Su versión actual de <a href="https://docs.adobe.com/content/help/es-ES/target/using/implement-target/client-side/target-atjs-versions.html" format="html" scope="external"> at.js</a> o mbox.js. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nombre de mbox global </p> </td> 
   <td colname="col2"> <p>El <a href="https://docs.adobe.com/help/es-ES/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">mbox global</a> hace referencia a la llamada al servidor única que se realiza sobre cada página web de la implementación de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nombre de mbox </p> </td> 
   <td colname="col2"> <p>Nombre de un mbox alrededor de una <a href="https://docs.adobe.com/content/help/es-ES/target/using/implement-target/client-side/mbox-implement/global-mbox/understanding-global-mbox.html" format="html" scope="external">ubicación</a> en la página. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external">tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nombre de la actividad </p> </td> 
   <td colname="col2"> <p>El nombre de la <a href="https://docs.adobe.com/content/help/es-ES/target/using/activities/activities.html" format="html" scope="external"> campaña o actividad</a> de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external"> tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID de actividad </p> </td> 
   <td colname="col2"> <p>El ID de la actividad de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external">tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Nombre de fórmula </p> </td> 
   <td colname="col2"> <p>Nombre de la <a href="https://docs.adobe.com/content/help/es-ES/target/using/experiences/experiences.html" format="html" scope="external"> experiencia</a> de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external">tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID de fórmula </p> </td> 
   <td colname="col2"> <p>El ID de la fórmula de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external">tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Oferta </p> </td> 
   <td colname="col2"> <p>Nombre de la <a href="https://docs.adobe.com/content/help/es-ES/target/using/experiences/offers/manage-content.html" format="html" scope="external"> oferta</a> de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external"> tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>ID de oferta </p> </td> 
   <td colname="col2"> <p>El ID de la oferta de Target. Disponible sin autenticación solo si implementa el detector de eventos de depuración en el administrador de códigos o etiquetas y activa los <a href="https://docs.adobe.com/content/help/es-ES/target/using/administer/response-tokens.html" format="html" scope="external"> tokens de respuesta</a> necesarios en la interfaz de usuario de Target. </p> </td> 
  </tr> 
 </tbody> 
</table>

