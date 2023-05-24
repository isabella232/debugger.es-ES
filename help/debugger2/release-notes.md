---
title: Notas de la versión
description: Las notas de la versión más recientes de Adobe Experience Platform Debugger.
keywords: debugger;extensión de experience Platform Debugger;chrome;extensión;notas de la versión
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 4%

---

# Notas de la versión

## Versión 1.3.0: 28 de enero de 2022

* Se ha añadido el vínculo Acerca de para mostrar la versión y las notas actuales de la versión.
* Se ha agregado la opción para ver las visitas posteriores al procesamiento de las solicitudes de Analytics. La opción está disponible en la sección Analytics.
* Se ha corregido un problema de sesión de depuración remota cuando la sesión se cerraba fuera del depurador.
* Se ha corregido una notificación de error visible en la pestaña Transacciones perimetrales del SDK web.
* Se ha corregido la advertencia Etiquetas de Adobe en la obsolescencia de la página cuando el depurador accedió al objeto _satellite.
* Se han corregido algunos casos en los que no se encontraba una instancia de AppMeasurement en la página.
* Se ha corregido un problema de conexión de página que se producía al abrir por primera vez la ventana del depurador.

## Versión 1.2.0: 26 de octubre de 2021

* Mostrar eventos de todas las fichas del explorador en la vista de red. Para ver solo los eventos de la pestaña actual, seleccione el icono de candado en la esquina inferior derecha de Debugger.
* Marca actualizada.

## Versión 1.1.0: 5 de octubre de 2021

* Visualización de depuración remota: organice los eventos de depuración remota en un gráfico de flujo visual en la sección SDK web de Adobe Experience Platform > Transacciones de Edge.
* Requiera que la organización de IMS del SDK web de Adobe Experience Platform que se utiliza en la página coincida con la organización que ha iniciado sesión al iniciar una nueva sesión de depuración remota.
* Mostrar solo las transacciones perimetrales de la pestaña conectada. Los registros de seguimiento de Target siguen estando disponibles en la sección Registros > Edge.
* Permita anular la configuración del ID de flujo de datos independiente para cada instancia del SDK web de Adobe Experience Platform en la página. Agregar opción de depuración habilitada.
* Se corrigió un problema en el cual el token de seguimiento de Adobe Target no siempre se enviaba con sesiones de depuración remota para el SDK web de Adobe Experience Platform.

## Versión 1.0.0, 5 de mayo de 2021

* Primera versión principal de Experience Platform Debugger. Destinado a reemplazar al Experience Cloud Debugger.
