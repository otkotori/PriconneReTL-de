<h2 align="center">
<img src=".github/assets/logo.png" style="vertical-align: bottom">

<i>A German patch for Princess Connect! ReDive on DMM</i>
</h2>

---

⚠️ **Warnung:** _Bitte benutzen Sie es auf eigene Gefahr!  ImaterialC (Cornelia) oder otkotori sind nicht verantwortlich für irgendwelche Aktionen, die in Bezug auf Ihr Konto unternommen werden, wenn Sie dieses Übersetzungstool verwenden._

The DE variant of 'Priconne Re:TL' is an unofficial patch / mod for [Cygames' Princess Connect Re: Dive](https://dmg.priconne-redive.jp/). It's main focus is to translate the game's user interface from Japanese to German so that german people can play it easier.

---

## ![Tantei](https://static.wikia.nocookie.net/princess-connect/images/f/fb/Kasumi_Box_Icon.png/revision/latest/scale-to-width-down/40?cb=20190925082622) Inhaltsverzeichnis
- [ Bei der Installation](#-bei-der-installation)
- [ Beim Aktualisieren](#-beim-aktualisieren)
- [ Beim Löschen](#-beim-löschen)
- [ Einstellungen und Funktionen ](#-einstellungen-und-funktionen)


## ![Nozomi](https://static.wikia.nocookie.net/princess-connect/images/4/46/Nozomi_Box_Icon.png/revision/latest/scale-to-width-down/40?cb=20190925084658) BEI DER INSTALLATION

1. Vergewissern Sie sich, dass Sie [priconner](https://dmg.priconne-redive.jp/) von DMM GAMES installiert haben, nicht von einen Android-Emulator.
2. Laden Sie die neueste Version von [Veröffentlicht Versionen](https://github.com/otkotori/PriconneRe-TL-DE-/releases) herunter. Ältere Versionen funktionieren nicht, wenn das Spiel aktualisiert wird.
3. Entpacken Sie alle Dateien aus der Zip-Datei in Ihren `priconner`-Ordner
- (Standardspeicherort: "C:\Benutzer(Users)\%username%\priconner)
4. Stellen Sie sicher, dass Ihr `priconner`-Ordner wie folgt aussieht

![Patched](https://github.com/ImaterialC/PriconneRe-TL/assets/105358849/f9ef7290-1ed4-41d4-b55e-616cb3d84636)

_Nach der Installation kommt es beim ersten Durchlauf zu einer Startverzögerung, beim zweiten Durchlauf und danach läuft alles wie gewohnt._

## ![Shiori](https://static.wikia.nocookie.net/princess-connect/images/7/77/Shiori_Box_Icon.png/revision/latest/scale-to-width-down/40?cb=20190925113434) BEIM AKTUALISIEREN

Laden Sie bei der Aktualisierung die neueste Version herunter und überschreiben Sie sie mit den Dateien, die sich bereits im Ordner `priconner` befinden.

Löschen Sie `BepInEx` im Stammordner `priconne` und entpacken Sie `BepInEx` in der Zip-Datei erneut.

## ![Maho](https://static.wikia.nocookie.net/princess-connect/images/a/a7/Maho_Box_Icon.png/revision/latest/scale-to-width-down/40?cb=20190925080932) BEIM LÖSCHEN

Löschen Sie einfach die Patch-Dateien, die in den Stammordner `priconner` entpackt wurden

Keine Priconne-Dateien, die während der Installation dieses Patches verändert oder beschädigt wurden, so dass Sie sie einfach manuell löschen können. 
Ihr Spiel wird in seinen normalen Zustand zurückkehren.

Wenn das Spiel nach dem Löschen des Patches nicht startet, deinstallieren Sie das Spiel und installieren Sie es erneut über DMM GAMES.

Folgende Dateien müssen für die Deinstallation gelöscht werden:
```
BepInEx
dotnet
doorstop_config.ini
winhttp.dll
.doorstop_version
```

Der Vanilla-Status des Ordners „priconner“ sieht wie folgt aus:
![Originalinstallation](https://github.com/ImaterialC/PriconneRe-TL/assets/105358849/3d5823e6-5f67-42be-aaa7-dd2c452535a5)

## ![Kyouka](https://static.wikia.nocookie.net/princess-connect/images/3/39/Kyouka_Box_Icon.png/revision/latest/scale-to-width-down/40?cb=20190925113712) EINSTELLUNGEN UND FUNKTIONEN

- Die Verwendung von [BepInEx Bleeding Edge](https://github.com/krulci/BepInEx) als Rahmen für die Injektion von [XUnity AutoTranslator](https://github.com/Kevga/XUnity.AutoTranslator).
- Die Konfiguration finden Sie hier:
  - [BepInEx Config](https://docs.bepinex.dev/articles/user_guide/configuration.html)
  - [AutoTranslator Config](https://github.com/bbepis/XUnity.AutoTranslator#configuration)
- [BepInEx FullScreenizer](https://github.com/krulci/FullScreenizer). Die Standardtaste für den Vollbildmodus ist F11.
- 16:9-Seitenverhältnis und kann Client-Größen größer als 1280 x 720 maximieren oder anpassen, um ein besseres Erlebnis auf modernen Bildschirmanzeigen zu ermöglichen.
- 2 Strategien für Texturen basierend auf Größe für Atlanten und Name für andere, es wird automatisch zurückgesetzt, wenn Texturen geändert werden und unbrauchbar sind. **Leider müssen AMD-GPU-Benutzer Atlas-Texturen aufgrund der unterschiedlichen
  Komprimierungsgrößen manuell ersetzen.**
