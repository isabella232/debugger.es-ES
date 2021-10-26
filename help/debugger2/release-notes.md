---
description: Notas de la versión de Experience Platform Debugger
keywords: debugger;extensión de experience Platform Debugger;chrome;extensión;notas de la versión
seo-description: Experience Platform Debugger release notes
seo-title: Release Notes
title: Notas de la versión
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: 026ce852ded530e89f36bb01274d7481e07731c0
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 11%

---

# Notas de la versión{#release-notes}

## Notas de la versión {#topic-a92c3eb799b74e7fa404af8af5efb215}

## Versión 1.2.0: 26 de octubre de 2021

## Nuevas características

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Función </th>
   <th colname="col2" class="entry"> Descripción </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Eventos de todas las pestañas del explorador visibles en la vista de red </p> </td>
   <td colname="col2"> <p> Mostrar eventos de todas las pestañas del explorador en la vista de red. Para ver solo los eventos de la pestaña actual, haga clic en el icono de bloqueo en la esquina inferior derecha del depurador.</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Cambios en la marca </p> </td>
   <td colname="col2"> <p> El SDK web de AEP se convierte en SDK web de Adobe Experience Platform y Launch se convierte en Adobe Experience Platform Tags.</p> </td>
  </tr>
 </tbody>
</table>

## Versión 1.1.0, 5 de octubre de 2021

## Nuevas características

<table id="table">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Función </th>
   <th colname="col2" class="entry"> Descripción </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Visualización de depuración remota </p> </td>
   <td colname="col2"> <p> Organice los eventos de depuración remota en un gráfico de flujo visual en la sección Adobe Experience Platform Web SDK &gt; Transacciones perimetrales . Además, se requiere que la organización IMS del SDK web de Adobe Experience Platform que se utiliza en la página coincida con la organización iniciada al iniciar una nueva sesión de depuración remota. Filtre las transacciones perimetrales por la pestaña conectada.</p> <p> <b>Nota:</b> Los registros de seguimiento de Target siguen estando disponibles en la sección Registros &gt; Edge .</p> </td>
  </tr>
  <tr>
   <td colname="col1"> <p> Mejoras en la sección de configuración del SDK web de Adobe Experience Platform </p> </td>
   <td colname="col2"> <p> Permite la anulación de la configuración del ID de flujo de datos independiente para cada instancia de la página. Agregar la opción de depuración habilitada .</p> </td>
  </tr>
 </tbody>
</table>

## Correcciones de errores

* Se ha corregido un problema en el cual el token de seguimiento de Adobe Target no siempre se enviaba con sesiones de depuración remota para el SDK web de Adobe Experience Platform.

## Versión 1.0.0, 5 de mayo de 2021

## Nuevas características

<table id="table_7EFCAF456B14404FAF3715FC56519AAF">
 <thead>
  <tr>
   <th colname="col1" class="entry"> Función </th>
   <th colname="col2" class="entry"> Descripción </th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colname="col1"> <p> Versión inicial </p> </td>
   <td colname="col2"> <p> Primera versión principal de Experience Platform Debugger. Se pretende reemplazar al Experience Cloud Debugger. </p> </td>
  </tr>
 </tbody>
</table>
