<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 15.4.2026 <a name="up"></a><br>   
<h1>3D-Druck-Teile für N-Spur-Module</h1><h3>Startseite</h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# 1. Worum geht es?
Dieses Repository enthält **3D‑Druck‑Vorlagen und CAD‑Dateien** für den Bau von **Modulrahmen, Gleisunterbau und Zubehörteilen** im **N‑Spur‑Maßstab** (1:160). Die Teile wurden mit dem kostenlosen [3D-CAD-Programm **Freecad**](https://www.freecad.org/) erstellt und eignen sich zum Drucken auf einem 3D‑Drucker – z. B. einem [**Prusa-XL**](https://www.prusa3d.com/de/produkt/original-prusa-xl-3d-drucker/) mit einem Bauraum von bis zu 360 × 360 × 360 mm³.   

## 🧭 Übersicht

**Ziel des Projekts**   
Dieses Repository soll helfen, modulare Teile für den Modellbahnbau selbst zu entwerfen und zu drucken – von Rahmen‑Elementen über Schotterbett‑Teile bis hin zu nützlichen Werkzeugen für den Aufbau.   

**Hinweis für Anfänger**   
Falls du noch nie mit FreeCAD oder GitHub gearbeitet hast, keine Sorge – es gibt viele Tutorials zu FreeCAD und Grundwissen zu GitHub, die dir helfen, Dateien herunterzuladen und zu verwenden.   

<a name="TableOfContents"></a>   

## Inhaltsverzeichnis
1. [Worum geht es?](#x10)   
2. [Rahmenteile (Baseboard Frame)](#x20)   
3. [Blockpanel](#x30)   
4. [Schotterbett (Track Ballast)](#x40)   
5. [Bahndamm (Embankment)](#x50)   
6. [Weichenabdeckungen (Point Motor Cover)](#x60)    
7. [Werkzeuge (Tools)](#x70)    
8. [Wie du die Dateien verwendest (kurz erklärt)](#x80)   

<a name="x20"></a>   

# 2. Rahmenteile
Die Basis jedes Moduls ist der **Rahmen**. Üblich ist hier eine **25 cm Breite** bei variabler Länge (25 – 100 cm). Da der Drucker nur bis ~36 cm drucken kann, wird der Rahmen in mehrere **25 cm‑Abschnitte unterteilt**.   

Im Repository findest du dafür:   
- 📐 Seitenteile für ein- oder zweigleisige Module   
- 🌲 Front‑ und Rückrahmen   
- 🔩 Querstreben mit Bohrungen und Rastnasen   
- 📏 Abstandshalter für präzise Länge   

> Hinweis 1: Die Teile sind so gestaltet, dass sie sich **mit Schrauben und Rastnasen** einfach zusammensetzen lassen.   
> Hinweis 2: In den **Frontrahmen** gibt es Ausnehmungen, in die Steuerblöcke aus dem Repository [`khartinger/RCC5V`](https://github.com/khartinger/RCC5V/blob/main/LIESMICH.md) eingesetzt werden.   

---   
Mehr Informationen und Dateien zu Rahmenteilen findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame/LIESMICH.md).   

[Zum Seitenanfang](#up)
<a name="x30"></a>   

# 3. Blockpanel
Blockpanels sind die **Frontplatten für Steuerblöcke** aus dem Repository [`khartinger/RCC5V`](https://github.com/khartinger/RCC5V/blob/main/LIESMICH.md).   

- Sie haben **Löcher für Taster und LEDs**.   
- Sie zeigen symbolisch die **Funktion des Steuerblocks** (im Bild hellblau).   
- Es gibt ein **Feld zum Beschriften**.   
- Sie passen in **Ausnehmungen** im **Frontrahmen**.   

Das Bild zeigt das Blockpanel für eine linke Zweiwegweiche:   
![Blockpanel_Zweiwegweiche](/images/150_3D_blockpanel_W2LE.png "Blockpanel_Zweiwegweiche")   

### 🛠️ Halterung für Steuerblöcke
Die [Halterung für Steuerblöcke (`RW_LEER_LED`)](https://github.com/khartinger/RCC5V/blob/main/fab/rcc5_add_ons/LIESMICH.md#x20) wird **hinten auf das Blockpanel geschraubt**. In diese Halterung wird **der Schaltblock gesteckt**, sodass er sicher montiert ist und die Taster/LEDs korrekt sitzen.   

### 🛠️ Montage im Rahmen
Im Rahmen sind für Blockpanel 42 x 42 mm² große Ausnehmungen vorgesehen.   

---   
Mehr Informationen und Dateien zu Blockpanel findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp3_block_panel](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp3_block_panel/LIESMICH.md).   

[Zum Seitenanfang](#up)
<a name="x40"></a>   

# 4. Schotterbett (Track Ballast)

---   
Mehr Informationen und Dateien zum Schotterbett findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp4_track_ballast](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp4_track_ballast)   

[Zum Seitenanfang](#up)
<a name="x50"></a>   

# 5. Bahndamm (Embankment)

---   
Mehr Informationen und Dateien zum Bahndamm findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp5_embankment](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp5_embankment)   

[Zum Seitenanfang](#up)
<a name="x60"></a>   

# 6. Weichenabdeckungen (Point Motor Cover)
---   
Mehr Informationen und Dateien zu Weichenabdeckungen findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp6_point_motor_cover/](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp6_point_motor_cover/)   

[Zum Seitenanfang](#up)
<a name="x70"></a>   

# 7. Werkzeuge (Tools)
---   
Mehr Informationen und Dateien zu Werkzeugen findest du hier:   
[https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp7_tools](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/tree/main/fab/pp7_tools)   

[Zum Seitenanfang](#up)
<a name="x80"></a>   

# 8. Wie du die Dateien verwendest (kurz erklärt)



[Zum Seitenanfang](#up)