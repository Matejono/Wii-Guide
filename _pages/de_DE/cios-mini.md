---
title: "d2xl cIOS für die Wii mini (experimentell)"
---

{% include toc title="Inhaltsverzeichnis" %}

Dieses Tutorial wird dir zeigen, wie du Leserattes d2xl cIOS (custom IOS) für die Wii mini installieren kannst. Dies ist zwingend erforderlich, wenn du Spiele über einen USB-Loader starten möchtest. Einige Homebrew wird mittels cIOS möglicherweise besser funktionieren.

![d2x cIOS Installer](/images/cIOS.png)

Dieser Abschnitt ist ausschließlich für Wii mini-Nutzer vorgesehen. Falls du eine Wii hast, folge stattdessen [dieser Anleitung](cios).
{: .notice--warning}

Solltest du hinsichtlich dieses Tutorials Hilfe benötigen, trete bitte dem [Wii mini Hacking-Discordserver](https://discord.gg/6ryxnkS) bei (empfohlen)
{: .notice--info}

Dieser d2x cIOS Installer wurde ursprünglich für die vWii der Wii U von DaveBaol entwickelt und die angepassten cIOS wurden von Leseratte für die Wii Mini erstellt. Die ursprüngliche Seite zum Herunterladen befindet sich [hier](https://wii.leseratte10.de/d2xl-cIOS/). Leserattes Github-Seite befindet sich [hier](https://github.com/Leseratte10/d2xl-cios). Bitte denk daran, dass cIOS immer noch experimentell sind, obwohl keine Probleme mit ihrer Funktion gemeldet wurden.
{: .notice--info}

#### Voraussetzungen

* Eine Wii mini, auf welcher der Homebrew-Kanal installiert ist
* Ein USB-Laufwerk
* Leserattes [d2xl cIOS Installer](/assets/files/d2xl_wii_mini_cIOS_installer_v1_beta2.zip)

#### Anleitung

##### Abschnitt 1 - Herunterladen

1. Extract the d2xl cIOS Installer to the `apps` folder on your USB drive.
1. Insert your USB drive into your Wii mini and load the d2xl cIOS Installer from the Homebrew Channel.

##### Abschnitt 2 - Installieren

1. Drücke auf Fortfahren, stelle dann folgende Optionen ein:
    ```
    Select cIOS: d2xl-v1-beta2
    Select cIOS base: 57
    Select cIOS slot: 249
    ```
Take a note of the version number under notes (`IOS57-64-` ending in either `v31776` or `v31775`)
1. Sobald dies eingestellt ist, drücke A zum installieren. Wenn der Vorgang erfolgreich abgeschlossen ist, beende den Installer.
   - If the install fails with a `TMD version mismatch` error, press left or right on the +Control Pad over the `Select cIOS base` option until the version number is different than the one you tried before. The number 57 will not change.


##### LAN aktivieren
Falls du Wiimmfi über LAN auf einer Wii mini verwenden möchtest, musst du die [Ethernet Enabler Homebrew](/assets/files/Wii_Mini_Ethernet_Enable.zip)-Anwendung von Fullmetal5 ausführen. Um sie zu starten, entpacke sie zunächst in den `apps`-Ordner auf deinem USB-Laufwerk, und führe sie anschliessend über den Homebrew-Kanal aus.

Versuchen Sie nicht, ein Wii-IOS oder ein Systemmenü auf der Wii mini zu installieren. Dies würde höchstwahrscheinlich deine Konsole bricken.
{: .notice--warning}

You can now use homebrew such as [USB Loader GX](usbloadergx) and [WiiFlow](wiiflow).
{: .notice--info}

[Fortfahren in der Seitennavigation](site-navigation)<br> Wir haben viele weitere Tutorials, welche dir gefallen könnten.
{: .notice--info}
