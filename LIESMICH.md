<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 6.4.2026 <a name="up"></a><br>   
<h1>3D-Druck-Teile für N-Spur-Module</h1><h3></h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# 1. Worum geht es?
Dieses Repository enthält **3D‑Druck‑Vorlagen und CAD‑Dateien** für den Bau von **Modulrahmen, Gleisunterbau und Zubehörteilen** im **N‑Spur‑Maßstab** (1:160). Die Teile wurden mit dem kostenlosen [3D-CAD-Programm **Freecad**](https://www.freecad.org/) erstellt und eignen sich zum Drucken auf einem 3D‑Drucker – z. B. einem [**Prusa-XL**](https://www.prusa3d.com/de/produkt/original-prusa-xl-3d-drucker/) mit einem Bauraum von bis zu 360 × 360 × 360 mm³.   

Die im Repository [`khartinger/RCC5V`](https://github.com/khartinger/RCC5V/blob/main/LIESMICH.md) hergestellten Steuerelemente für Weichen, Gleise usw. können in die Rahmenteile eingebaut werden.   

<a name="TableOfContents"></a>   

## Inhaltsverzeichnis
1. [Worum geht es?](#x10)   
2. [Rahmenteile (Baseboard Frame)](#x20)   
3. [Blockpanel](#x30)   
4. [Schotterbett (Track Ballast)](#x40)   
5. [Bahndamm (Embankment)](#x50)   
6. [Werkzeuge (Tools)](#x60)    
7. [Wie du die Dateien verwendest (kurz erklärt)](#x70)   

<a name="x20"></a>   

# 2. Rahmenteile
Die Basis jedes Moduls ist der **Rahmen**. Üblich ist hier eine **25 cm Breite** bei variabler Länge (25 – 100 cm). Da der Drucker nur bis ~36 cm drucken kann, wird der Rahmen in mehrere **25 cm‑Abschnitte unterteilt**.   

Im Repository findest du dafür:   
- 📐 Seitenteile für ein- oder zweigleisige Module   
- 🌲 Front‑ und Rückrahmen   
- 🔩 Querstreben mit Bohrungen und Rastnasen   
- 📏 Abstandshalter für präzise Länge   

> Hinweis: Die Teile sind so gestaltet, dass sie sich **mit Schrauben und Rastnasen** einfach zusammensetzen lassen.   

---   
Mehr Informationen und Dateien zu den Rahmenteilen findest du hier: [https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame/LIESMICH.md).   

[Zum Seitenanfang](#up)
<a name="x30"></a>   

# 3. Blockpanel
Blockpanel sind die Frontplatten der Steuerblöcke. Auf sie wird mit M 2,6 x 10 Schrauben die [Halterung für Schaltblöcke (`RW_LEER_LED`)](https://github.com/khartinger/RCC5V/blob/main/fab/rcc5_add_ons/LIESMICH.md#x20) aufgeschraubt. In weiterer Folge wird dann ein Schaltblock - bestehend aus Steuerungs- und Anzeige-Platine - in die Halterung eingesteckt.   
Das folgende Bild zeigt ein Blockpanel, die Halterung und den Schaltblock für eine linke Zweiwegweiche.   

![Blockpanel_Halterung_Schaltblock](/images/300_3D_blockpanel_block1.png "Blockpanel_Halterung_Schaltblock")   
_Bild 5: Blockpanel, Halterung und Schaltblock für eine linke Zweiwegweiche_   

Im Rahmen sind für Blockpanel 42 x 42 mm² große Ausnehmungen vorgesehen (siehe zB _Bild 1_).   

Folgende Blockpanel sind unter anderem verfügbar:   
* Linke Zweiwegweiche Richtung Osten (`Blockpanel_T2LE_260318.FCStd`)   
* Linke Zweiwegweiche Richtung Westen (`Blockpanel_T2LW_260318.FCStd`)   
* Rechte Zweiwegweiche Richtung Osten (`Blockpanel_T2RE_260318.FCStd`)   
* Rechte Zweiwegweiche Richtung Westen (`Blockpanel_T2RW_260318.FCStd`)   
* Dreiwegweiche Richtung Osten (`Blockpanel_T3E_260318.FCStd`)   
* Dreiwegweiche Richtung Westen (`Blockpanel_T3W_260318.FCStd`)   
* Entkuppler (`Blockpanel_Uncoupler_Text_260322.FCStd`)   
* Abschaltbares Gleis (`Blockpanel_DisconTrack_Text_260322.FCStd`)   
* Leeres Blockpanel (`Blockpanel_empty_260403.FCStd`)   
* Leeres Blockpanel-Shield ohne PadBlock (`Blockpanel_empty_shield_260405.FCStd`)   

Das folgende Bild zeigt die entsprechenden Grafiken:   
![Blockpanel_1](/images/300_3D_blockpanel_1of3.png "Blockpanel_1") ![Blockpanel_2](/images/300_3D_blockpanel_2of3.png "Blockpanel_2") ![Blockpanel_3](/images/300_3D_blockpanel_3of3.png "Blockpanel_3")   
_Bild 6: Arten von Blockpanel_   

Das Blockpanel-Shield dient dazu, die Schrauben zwischen den Frontrahmenteilen abzudecken.   

---   
Technische Details und Freecad-Dateien zu Rahmenteilen befinden sich im Unterverzeichnis [https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp3_block_panel/LIESMICH.md](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp3_block_panel/LIESMICH.md).   

[Zum Seitenanfang](#up)
<a name="x40"></a>   

# 4. Schotterbett (Track Ballast)

[Zum Seitenanfang](#up)
<a name="x50"></a>   

# 5. Bahndamm (Embankment)


[Zum Seitenanfang](#up)
<a name="x60"></a>   

# 6. Werkzeuge (Tools)

[Zum Seitenanfang](#up)
<a name="x70"></a>   

# 7. Wie du die Dateien verwendest (kurz erklärt)



[Zum Seitenanfang](#up)