---
title: "RiiTag su Wii"
---

{% include toc title="Table of Contents" %}

Se hai bisogno di aiuto per questo tutorial, unisciti a [il server Discord RiiConnect24 ](https://discord.gg/b4Y7jfD) (raccomandato) o [mandaci una e-mail a support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

RiiTag è una gamertag dinamica e personalizzabile. Condividendo la tua gamertag (una immagine dinamica), puoi mostrare a cosa stai giocando ai tuoi amici! Connettilo a una porta USB, e il tag si aggiorna in tempo reale. Hai bisogno di un account Discord per iniziare ad usare RiiTag.

Want to install RiiTag on your Wii U? See [this guide](riitag-wiiu) on how to connect it to your Wii U Menu.
{: .notice--info}

#### Di cosa hai bisogno

* Un Computer
* Un editor di testo
* Una porta USB

#### Istruzioni

##### Parte 1 - Per cominciare

1. [Vai al sito di RiiTag.](https://tag.rc24.xyz/)
2. Clicca su `Log In` ed accedi col tuo account Discord.
3. Una finestra apparirà chiedendoti se vuoi autorizzare `RiiConnect24 Login` con Discord. Clicca `Autorizza`.
4. Clicca su `Modifica il tuo Tag` e personalizzalo come vuoi. Puoi aggiungere uno sfondo, decorazione, bandiera, nickname, numero Wii, e entrare manualmente nei giochi per mostrare il tuo tag (non necessario se si usa una porta USB).
5. Clicca su `Mostra Chiave` e prendi nota della chiave mostrata. Questo non serve se usi un USB Loader GX, perchè la chiave sarà in un file scaricabile.
6. Clicca su `Salva` per salvare i cambiamenti.

Non condividere la tua Chiave RiiTag con nessuno! Se lo farai, le persone possono abusare la tua tag.
{: .notice--warning}

##### Parte II - Connettere il tuo USB Loader

The steps to connect RiiTag to your USB Loader depend on what USB Loader you use.

###### USB Loader GX

1. Carica USB Loader GX sulla tua Wii.
2. Vai a `Impostazioni` > `Funzionalità` and cambia `Wiinnertag` su acceso. Press `Yes` or `OK` to any dialogues that show up.
3. Assicurati che `Initialize Network` sia acceso.
4. Esci da USB Loader GX.
5. Inserisci la Scheda SD o dispositivo USB dove si trovano i dati di USB Loader GX sul tuo computer.
6. [Vai a questa pagina.](https://tag.rc24.xyz/Wiinnertag.xml)
7. Dal tuo browser, click destro, e clicca `salva come`.
8. Salva il XML sulla cartella `/apps/usbloader_gx`  della tua scheda SD o dispositivo USB, sostituendo l'esistente `Wiinnertag.xml`.
9. Adesso hai impostato RiiTag. Puoi provare a caricare qualunque gioco per vedere se funziona.

###### WiiFlow

1. Porta la Scheda SD o dispositivo USB dove si trovano i dati per WiiFlow sul tuo computer.
2. Apri `/apps/wiiflow/wiiflow.ini` con un text editor. (Se stai usando WiiFlow Lite, potresti avere `wiiflow_lite` invece di `wiiflow`.)
3. Cerca per `gamecards` e sostituisci la linea con `gamercards=wiinnertag`.
4. Cerca `wiinnertag_url` e sostituiscilo con `wiinnertag_url=http://tag.rc24.xyz/wii?game={ID6}&;key={KEY}`.
5. Cerca `wiinnertag_key` e sostituisci la linea con `wiinnertag_key=<key>`, sostituendo `<key>` con la chiave che hai scritto nella Sezione 1.
6. Cerca `gamercards_enable` e sostituisci la linea con `gamercards_enable=yes`.
7. Salva il file modificato di `wiiflow.ini`.
8. Adesso hai impostato RiiTag. Puoi provare a caricare qualunque gioco per vedere se funziona.

###### Dolphin

You need a Discord account for this to work.
{: .notice--info}

1. [Join the RiiConnect24 Discord server](https://discord.gg/b4Y7jfD) if you aren't already in there.
2. Make sure `Show Current Game on Discord` is turned on in preferences.
3. Make sure your Discord client is open.
4. Play a game and RiiTag will automatically update your tag when you play a game.

###### Configurable USB Loader

We do not offer support for Configurable USB Loader, as we are focused on USB Loader GX and WiiFlow.
{: .notice--info}

You can use the `CfgLoaderConfigurator.exe` program (Windows only) instead of editing the `config.txt` file mentioned below if you want to.
{: .notice--info}

1. Take the SD Card or USB device where your Configurable USB Loader data is into your computer.
2. Open `/usb-loader/config.txt` with a text editor.
3. Replace (or add the line) starting with `gamercard_url` with `gamercard_url = http://tag.rc24.xyz/wii?game={ID6}&key={KEY}`.
4. Replace (or add the line) starting with `gamercard_key` with `gamercard_key = <key>`, replacing `<key>` with the key you wrote down in Section 1.
5. Save the modified `config.txt` file.
6. Adesso hai impostato RiiTag. Puoi provare a caricare qualunque gioco per vedere se funziona.

[Check out RiiTag-RPC](https://github.com/RiiConnect24/RiiTag-RPC/releases/latest)<br> Now that you set up RiiTag, you can set up RiiTag-RPC to show your friends what you're playing on the Wii using Discord's rich presence.
{: .notice--info}

[Continua a navigare nel sito](site-navigation)<br> Abbiamo molti altri tutorial che potrebbero interessarti.
{: .notice--info}
