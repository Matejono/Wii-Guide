---
title: "d2xl cIOS para Wii mini (experimental)"
---

{% include toc title="Sumário" %}

Este tutorial irá lhe ensinar a como instalar d2xl cIOS por Leseratte para Wii Mini (IOS customizada). Isso é necessário caso queira jogar em USB Loaders. Alguns aplicativos homebrew podem funcionar melhor com o uso de cIOS.

![Instalador d2x cIOS](/images/cIOS.png)

This guide is only intended for Wii mini users. If you have a Wii, follow [this guide](cios) instead.
{: .notice--warning}

Caso precise de ajuda com algo relacionado a este tutorial, entre no servidor do Discord dedicado para hacks do Wii mini:[](https://discord.gg/6ryxnkS)(recomendado)
{: .notice--info}

O instalador d2x cIOS foi originalmente desenvolvido para o Wii U (vWii) por DaveBaol, e cIOS customizadas no Wii mini foram criadas por Leseratte. A página de download original pode ser encontrada [aqui](https://wii.leseratte10.de/d2xl-cIOS/). A página Github do criador Leseratte pode ser encontrada [aqui](https://github.com/Leseratte10/d2xl-cios). Note que ainda se encontra em estado experimental, embora não foram reportados problemas.
{: .notice--info}

#### Você precisará de

* Um Wii Mini com Homebrew Channel instalado
* Unidade USB / Pendrive
* [d2xl cIOS Installer](/assets/files/d2xl_wii_mini_cIOS_installer_v1_beta2.zip) por Leseratte

#### Instruções

##### Parte I - Baixar

1. Extract the d2xl cIOS Installer to the `apps` folder on your USB drive.
1. Insert your USB drive into your Wii mini and load the d2xl cIOS Installer from the Homebrew Channel.

##### Parte II - Instalar

1. Pressione continuar e defina as opções dessa forma:
    ```
    Select cIOS: d2xl-v1-beta2
    Select cIOS base: 57
    Select cIOS slot: 249
    ```
Take a note of the version number under notes (`IOS57-64-` ending in either `v31776` or `v31775`)
1. Quando feito, pressione A para instalar. Assim que terminar, saia do instalador.
   - If the install fails with a `TMD version mismatch` error, press left or right on the +Control Pad over the `Select cIOS base` option until the version number is different than the one you tried before. The number 57 will not change.


##### Ativando Ethernet
Se você deseja usar o Wiimmfi com cabo Ethernet em um Wii mini, execute o aplicativo [Ethernet Enabler Homebrew](/assets/files/Wii_Mini_Ethernet_Enable.zip) por Fullmetal5. Para executar, basta extrair o arquivo na pasta `apps` da sua unidade USB e inicie pelo Homebrew Channel.

Do not attempt to install a Wii IOS or System Menu on the Wii mini. Se fizer, seu console pode sofrer brick.
{: .notice--warning}

You can now use homebrew such as [USB Loader GX](usbloadergx) and [WiiFlow](wiiflow).
{: .notice--info}

[Continue para a navegação do site](site-navigation)<br> Temos vários outros tutoriais que você pode gostar.
{: .notice--info}
