---
description: Notas de la versión de Experience Cloud Debugger
keywords: debugger;experience cloud debugger extension;chrome;extension;release notes
seo-description: Notas de la versión de Experience Cloud Debugger
seo-title: Notas de la versión
title: Notas de la versión
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
translation-type: tm+mt
source-git-commit: 1d81f427e2c1a68a182fae8262d0e2ad32a87223
workflow-type: tm+mt
source-wordcount: '699'
ht-degree: 100%

---


# Notas de la versión {#release-notes}

## Notas de la versión {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Versión 0.0.817, 17 de mayo de 2019 {#topic-5dc9026cac864330b04361b1da8309a8}

## Nuevas funciones {#section-71352536e6894ad08f307535529394cd}

<table id="table_7EFCAF456B14404FAF3715FC56519AAF"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Datos de visitas posteriores al procesamiento </p> </td> 
   <td colname="col2"> <p> Se ha agregado la capacidad de <a href="solutions.md#section-f71dfcc22bb44c86bec328491606a482" format="dita" scope="local"> ver valores en las visitas de Analytics después de ejecutar las reglas de procesamiento</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Versión 0.0.810, 6 de marzo de 2019 {#topic-83bb7ddd68594177be9fd7826b650b80}

## Nuevas funciones {#section-0a2f6fcb0045464fa11f0586c69f7ffd}

<table id="table_96AEBFF29F3D40CAA859133B22756B0C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Pruebas de Auditor </p> </td> 
   <td colname="col2"> <p> Se agregaron <a href="run-debugger.md#section-82bc57440406461ebf27a16855b71655" format="dita" scope="local"> pruebas de Auditor</a> a Debugger. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Adobe Audience Manager </p> </td> 
   <td colname="col2"> <p>Debugger ahora muestra respuestas AAM. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correcciones de errores {#section-f5e9d54e9d2546afb97972cdb6d8a093}

* Se ha corregido un problema en el cual el pie de página ocultaba contenido en la parte inferior de la página.

* Se ha actualizado el pie de página de Debugger.
* Se ha corregido un problema que hacía que se usara una terminología obsoleta en Target.

## Versión 0.0.809, 28 de febrero de 2019 {#topic-6241de45fa9e4a23a95ad4d3a73f7348}

## Nuevas funciones {#section-14036b9f2c0144fdac5e292ea42ce564}

<table id="table_66E255E9BA8845CAA92779F580D14EB4"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Funciones de código incrustado </p> </td> 
   <td colname="col2"> <p> Dividir, reemplazar e insertar funciones de código incrustado. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Mejoras {#section-e9e8a6ddedde4c029b1d3d69c009cbad}

* Se ha corregido una potencial vulnerabilidad causada por una entrada no saneada del usuario.

## Correcciones de errores {#section-556417ff055848c1bf037354dd43cbd0}

* Se ha corregido un problema que hacía que los eventos DIL de AAM no se guardaran en la pestaña AAM.

* Se ha corregido un problema en Insertar Launch de forma dinámica en el que la interfaz de usuario parecía asignarse a un código incrustado diferente cuando no era el caso.
* Se ha corregido un problema en Insertar Launch de forma dinámica en el cual se mostraba una dirección URL incorrecta.
* Se ha corregido un problema en el cual Debugger reemplazaba los códigos incrustados incluso cuando se cerraba la ventana de Debugger.

## Versión 0.0.806, 10 de septiembre de 2018 {#topic-a41c9d1969ff4d06ac3bb4e7d6b6d18a}

## Nuevas funciones {#section-4eb2a6ed26a44abc96623384a7e94b0f}

<table id="table_9AC6DE90AF4345DFA707BFBA1E58C328"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Vínculo de Analytics en la pestaña Herramientas </p> </td> 
   <td colname="col2"> <p>Mostrar nombres prácticos para evars/props mediante la API de Analytics en el inicio de sesión de IMS. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Insertar Launch de forma dinámica </p> </td> 
   <td colname="col2"> <p>Desde la pestaña Herramientas, puede Insertar Launch de forma dinámica en cualquier página para probar algo en una página que no tenga Launch instalado. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Mejoras de Target </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_5FCD61733462495D8FB421DE7C813001"> 
      <li id="li_2E8E9AAE5D0D41DC8C42592AFDFA3377">Se han agregado tiempos de rendimiento para solicitudes de Target. </li> 
      <li id="li_98A56E71D72542D694A76DF84CE26AFA">Guardar adobe.target.trackEvent. </li> 
     </ul> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Mejoras {#section-56003a12c32f4998bf1cf2a25a518592}

* Se ha mejorado la visualización de la pestaña Red para que la altura de la tabla no sea demasiado grande y obligue al usuario a desplazarse verticalmente antes de poder desplazarse horizontalmente. En el pasado, las barras de desplazamiento aparecían en la parte inferior de la tabla. Debido a que la tabla podía ser bastante grande, los usuarios tenían que desplazarse verticalmente para poder verla.
* Se ha actualizado el vínculo a ObservePoint desde la pestaña Herramientas.

## Correcciones de errores {#section-d9231f5c77254d0888347e5f569a8b1d}

* Se ha solucionado un problema en el que la pestaña Experience Cloud no se actualizaba.

* Se ha corregido un problema en el cual “Media Optimizer” se mostraba en la fila Solución de la pestaña Red, en lugar del nombre actual “Advertising Cloud”.
* Se ha corregido un problema que provocaba que Debugger inyectara _satellite en todas las páginas.

## Versión 0.0.803, 10 de agosto de 2018 {#topic-d2901fb70ce04a5586f6c7a994fce875}

La versión 0.0.803 no incluye ningún cambio de cara al cliente.

## Versión 0.0.802, 1 de agosto de 2018 {#topic-b93cd396af5e49dc97cd86264871aeb4}

## Nuevas funciones {#section-e6699fb9c9b24035ace56d6a84c9d09b}

<table id="table_E847A9D6711F4CF59E98806FA7AF8379"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Vínculo del auditor en la pestaña Herramientas </p> </td> 
   <td colname="col2"> <p>Se ha agregado un vínculo al Auditor desde Debugger. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Pestañas contraídas </p> </td> 
   <td colname="col2"> <p>Las pestañas contraídas persisten en las pestañas Resumen y Herramienta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Haga clic para ver </p> </td> 
   <td colname="col2"> <p> Se ha agregado la funcionalidad de hacer clic para ver a todas las pestañas. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Mejoras {#section-0e7090e3e6a645f085d4553b983ecff8}

* Se ha cambiado el nombre de Media Optimizer a Advertising Cloud.
* Se han eliminado las soluciones de la pestaña Red si no se encuentran.

## Correcciones de errores {#section-7c0e4cc4b00a428489bed4a0a27c9501}

* Se ha corregido un problema en el cual la función “Haga clic para ver” no se actualizaba.
* Se ha corregido un problema que hacía que las visitas de AAM no se mostraran en la pestaña de AAM.

## Versión 0.0.798, 14 de junio de 2018 {#topic-3b2d44277f2f4c0295d82724c34bf467}

## Nuevas funciones {#section-0d73ae8b7ced417e9039f986fafaa102}

<table id="table_8FDED5A7B7F7430A88AE441336F9C714"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Opción de exportación de Excel </p> </td> 
   <td colname="col2"> <p>Se ha agregado la opción de exportación de Excel a la pestaña Red. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aspecto mejorado </p> </td> 
   <td colname="col2"> <p>Se ha actualizado la fuente de extensión de Chrome a Adobe Clean. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Funcionalidad de barrido del trackpad </p> </td> 
   <td colname="col2"> <p>Funcionalidad de barrido de trackpad hacia adelante y hacia atrás deshabilitada. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Indicador de llamada al servidor sin procesar </p> </td> 
   <td colname="col2"> <p>Se ha agregado un indicador de que se ha copiado la cadena de llamada al servidor sin procesar. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Vaciar la pestaña Registros </p> </td> 
   <td colname="col2"> <p> 
     <ul id="ul_D1EB0BE3A01C494983DAAF625562AC62"> 
      <li id="li_2696D26320F54A089D3CC99962EC9670">Ocultar soluciones en el Filtro de soluciones si no se encuentran elementos de línea para esa solución en los registros. </li> 
      <li id="li_D4586A6AB2AD42BB9F0FA3E7A01382C6">Ocultar el Filtro de nivel si no se encuentran llamadas de la DTM, ya que solo se aplica a la DTM. </li> 
      <li id="li_E2AF179037DC4C63B960013AB1F9AD6A">Cambiar los iconos que se muestran en la columna Nivel para que no parezca que se pueda hacer clic en ellos cuando no es el caso. </li> 
      <li id="li_3DB6682D6C9040D99F04C688E208CE1F">Estandarizar el formato de “Mostrar código” en los elementos de línea de la DTM. </li> 
     </ul> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Actualizar vínculo de ayuda en pie de página </p> </td> 
   <td colname="col2"> <p>Actualizar el vínculo de ayuda en pie de página a <a href="https://docs.adobe.com/content/help/es-ES/debugger/using/experience-cloud-debugger.html" format="https" scope="external">https://docs.adobe.com/content/help/es-ES/debugger/using/experience-cloud-debugger.html</a> </p> </td> 
  </tr> 
 </tbody> 
</table>

## Correcciones de errores {#section-c292cf7dcb17463bb1928de73bd55121}

* Se ha corregido un problema por el cual el número de distintivo no se borraba.
* Se ha corregido un problema por el cual un cliente informaba de detalles de resumen en blanco.

## Versión 0.0.797, 25 de mayo de 2018 {#topic-51490f4f42aa40eb879663fad9d62916}

## Nuevas funciones {#section-bbf8ff7e000e4b5592d348e0870471f6}

<table id="table_8CF872DC245A46C38FE21490C842D47A"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Funcionalidad </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Toggles de  Mbox </p> </td> 
   <td colname="col2"> <p>Se han agregado toggles de mbox a la pestaña Target. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>La configuración de filtro ahora se fija </p> </td> 
   <td colname="col2"> <p>La configuración del filtro ahora se fija a la parte superior de la pantalla en las pestañas Red y Registro. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Ver y copiar valores de red </p> </td> 
   <td colname="col2"> <p>Puede ver los detalles y copiar el valor de cualquier celda en la pestaña de red. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Vínculos de pie de página de aviso legal y copyright </p> </td> 
   <td colname="col2"> <p>Se han agregado vínculos de pie de página de aviso legal e información de copyright a la interfaz de usuario. </p> </td> 
  </tr> 
 </tbody> 
</table>

