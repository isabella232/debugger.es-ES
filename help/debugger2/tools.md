---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;tools;dtm;target
seo-description: 'null'
seo-title: Herramientas
title: Herramientas
uuid: ea3fe1ea-e936-4c5a-8a43-b830d1b75038
translation-type: ht
source-git-commit: dc723f0848c56794e9a1a6eda405de2f4ea6b8fa

---


# Herramientas {#tools}

> [!IMPORTANT]
>
> Adobe Experience Cloud Debugger 2.0 se encuentra en la versión beta. La documentación y las funciones están sujetas a cambios.

En la pantalla Herramientas, puede habilitar o deshabilitar varias herramientas para la solución instalada. Por ejemplo, puede activar las sentencias de depuración de la consola de Target o utilizar la biblioteca de ensayo de la DTM. Estas herramientas solo están disponibles si Target y DTM están instalados en la página.

![](assets/tools.jpg)

Puede Insertar Launch o DTM de forma dinámica en cualquier página para probar algo en una página que no tenga instalado Launch o DTM. Haga clic en el icono **[!UICONTROL Embed Code]**, luego escriba el [código incrustado](https://experiencecloud.adobe.com/resources/help/es_ES/dtm/deployment.html) y haga clic en **[!UICONTROL Save]**.

![](assets/tools-embedcode.jpg)

## Información de DTM {#section-c3d43040440449e5a050170843a600b7}

<table id="table_04625C3319134E169A35DB74C1D1FB31"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Herramienta </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p> Registro de la consola de DTM </p> </td> 
   <td colname="col2"> <p>Esta herramienta muestra las sentencias de depuración específicas de DTM a la consola del explorador. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Usar biblioteca de ensayo </p> </td> 
   <td colname="col2"> <p>Esta herramienta utiliza la biblioteca de ensayo para obtener información de depuración de DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Deshabilitar DTM </p> </td> 
   <td colname="col2"> <p>Esta herramienta bloquea la comprobación de la información de DTM. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Insertar DTM de forma dinámica </p> </td> 
   <td colname="col2"> <p> Esta herramienta inserta código de DTM en la página. Utilice el editor de Código incrustado para editar el código insertado. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Información de Target {#section-31090d95f50e455692b672c26e6a2051}

<table id="table_A71D269B49F4417599EBACA44D5CCF4F"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Herramienta </th> 
   <th colname="col2" class="entry"> Descripción </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Registro de la consola de Target </p> </td> 
   <td colname="col2"> <p>Esta herramienta muestra las sentencias de depuración específicas de Target a la consola del navegador, todo ello comenzando con el prefijo <span class="codeph"> AT:</span>, agregando una cookie denominada <span class="codeph"> mboxDebug=true</span> a su explorador. En este momento, las sentencias de consola no aparecen en la pantalla Registros de Debugger, sino que están visibles en la consola de depuración nativa del explorador. </p> <p> Esta herramienta requiere at.js 0.9.6 o versiones posteriores. Si utiliza una versión anterior de at.js, puede agregar el parámetro de cadena de consulta <span class="codeph"> ?mboxDebug=true</span> a la dirección URL para activar el registro en la consola. Si utiliza mbox.js, puede agregar el parámetro <span class="codeph"> ?_AT_Debug=console</span> para activar el registro de la consola limitado a las actividades del Compositor de experiencias visuales. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Activar seguimientos de mbox </p> </td> 
   <td colname="col2"> <p>Esta herramienta agrega información detallada a las respuestas de Target, que se puede explorar en la pantalla <span class="uicontrol"> Target&gt;Seguimiento de mbox</span> de Debugger. </p> <p> Debe haber iniciado sesión en Experience Cloud en una de las pestañas de Chrome para habilitar esta herramienta. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Deshabilitar Target </p> </td> 
   <td colname="col2"> <p>Esta herramienta deshabilita todas las solicitudes de Target al agregar una cookie denominada <span class="codeph">mboxDisable=true</span> a su explorador. </p> <p> Esta herramienta requiere at.js 0.9.6 o versiones posteriores. Si utiliza una versión anterior, puede agregar el parámetro de cadena de consulta <span class="codeph"> ?mboxDisable=true </span>a la dirección URL para deshabilitar los mboxes. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p> Resaltado de mbox </p> </td> 
   <td colname="col2"> <p> Esta herramienta dibuja un cuadro rojo alrededor de mboxes heredados de estilo envolvente. </p> </td> 
  </tr> 
 </tbody> 
</table>

En el siguiente vídeo se explica cómo utilizar la extensión de Debugger con Adobe Target.

>[!VIDEO](https://video.tv.adobe.com/v/23115t2/?captions=spa)
