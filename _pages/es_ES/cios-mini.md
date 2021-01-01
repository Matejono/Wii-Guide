---
title: "Instalar d2xl cIOS para Wii Mini"
---

{% include toc title="Tabla de contenido" %}

En esta guía te explicaremos cómo instalar el d2xl cIOS de Leseratte para Wii Mini. Esto es necesario si deseas cargar juegos por medio de un USB Loader. Algunas aplicaciones homebrew pueden funcionar mejor usando cIOS.

![Logotipo de d2x cIOS Installer](/images/cIOS.png)

Esta guía es solo para Usuarios de Wii Mini. Si tienes una Wii, usa [este guía](cios) en lugar.
{: .notice--warning}

En caso de que necesites ayuda con alguna cosa relacionada con esta guía, puedes unirte al [servidor de Discord de Wii Mini Hacking](https://discord.gg/6ryxnkS) (recomendado).
{: .notice--info}

Esta versión de d2x cIOS installer fue originalmente desarrollada para el vWii por DaveBaol y el cIOS ha sido creado por Leseratte específicicamente para el Wii Mini. La página de descarga original puede ser encontrada [aquí](https://wii.leseratte10.de/d2xl-cIOS/). El repositorio en GitHub puede ser visitado [aquí](https://github.com/Leseratte10/d2xl-cios). No se han reportado problemas en el funcionamiento de este cIOS, sin embargo, ten en cuenta que aún se encuentra en fase experimental.
{: .notice--info}

#### Requisitos

* Un Wii Mini con el Canal Homebrew instalado
* Una unidad USB
* [d2xl cIOS Installer](/assets/files/d2xl_wii_mini_cIOS_installer_v1_beta2.zip) de Leseratte

#### Instrucciones

##### Sección I - Descarga

1. Extract the d2xl cIOS Installer to the `apps` folder on your USB drive.
1. Insert your USB drive into your Wii mini and load the d2xl cIOS Installer from the Homebrew Channel.

##### Sección II - Instalación

1. Presiona continuar y después ajusta las opciones de la siguiente manera:
    ```
    Select cIOS: d2xl-v1-beta2
    Select cIOS base: 57
    Select cIOS slot: 249
    ```
Take a note of the version number under notes (`IOS57-64-` ending in either `v31776` or `v31775`)
1. Una vez que todas las opciones hayan sido ajustadas correctamente, oprime A dos veces para comenzar a instalar. .Cuando el proceso haya terminado de forma exitosa, sal del instalador
   - If the install fails with a `TMD version mismatch` error, press left or right on the +Control Pad over the `Select cIOS base` option until the version number is different than the one you tried before. The number 57 will not change.


##### Activar Ethernet
Si deseas jugar en Wiimmfi con tu Wii Mini, tendrás que hacerlo a través de Ethernet, y para eso necesitarás ejecutar la aplicación homebrew [Wii Mini Ethernet Enabler](/assets/files/Wii_Mini_Ethernet_Enable.zip) creada por Fullmetal5. Extrae Wii Mini Ethernet Enabler a la carpeta `apps` en tu unidad USB y después inicia la aplicación desde el Canal Homebrew.

No intente instalar un IOS de Wii o Menu del Sistema en el Wii Mini. Hacer esto podría brickear tu consola..
{: .notice--warning}

You can now use homebrew such as [USB Loader GX](usbloadergx) and [WiiFlow](wiiflow).
{: .notice--info}

[Echa un vistazo a nuestras demás guías](site-navigation)<br> Tenemos muchos otros tutoriales que podrían interesarte.
{: .notice--info}
