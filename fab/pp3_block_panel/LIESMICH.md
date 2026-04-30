<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 6.4.2026 <a name="up"></a><br>   
<h1> Blockpanel</h1><h3>3D-Druck-Teile für N-Spur-Module</h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# 1. Worum geht es?
Blockpanels sind die **Frontplatten für Steuerblöcke** aus dem Repository [`khartinger/RCC5V`](https://github.com/khartinger/RCC5V/blob/main/LIESMICH.md).   
Für jeden Steuerblock gibt es das passende Frontpanel.   

_Beispiel_: Blockpanel für eine linke Zweiwegweiche:   
![Blockpanel_Zweiwegweiche](/images/150_3D_blockpanel_W2LE.png "Blockpanel_Zweiwegweiche")   

<a name="TableOfContents"></a>   

## Inhaltsverzeichnis
1. [Worum geht es?](#x10)   
2. [Gemeinsame Eigenschaften von Blockpanels](#x20)   
3. [Panel für Zweiwegweichen](#x30)   
4. [Panel für Dreiwegweichen](#x40)   
5. [Panel für Entkuppler](#x50)   
6. [Panel für ein abschaltbares Gleis](#x60)   
7. [Weitere Blockpanels](#x70)   

<a name="x20"></a>   

# 2. Gemeinsame Eigenschaften von Blockpanels
Alle Blockpanels:  
- haben **Löcher für Taster und LEDs**   
- zeigen die **Funktion des Steuerblocks** symbolisch   
- haben ein **Beschriftungsfeld**   
- haben **die gleichen Abmessungen**   

**Beschriftungsfeld:** 40 × 7 mm²  
**Außenmaße:** 46 × 54 mm²  
**Maße des 10 mm dicken Blocks:** 42 × 42 mm²

<a name="x30"></a>   

# 3. Panel für Zweiwegweichen
Zweiwegweichen gibt es als **links oder rechts abzweigende Weichen**.   
Sie können in Modulen nach **links (West)** oder **rechts (Ost)** geöffnet sein.   
Damit gibt es **vier Varianten**:   

![Blockpanel_Zweiwegweiche](/images/300_3D_blockpanel_1of3.png "Blockpanel_Zweiwegweiche")   

**Dateien:**  
* `Blockpanel_T2LE_260318.FCStd` – linke Zweiwegweiche Richtung Osten   
* `Blockpanel_T2LW_260318.FCStd` – linke Zweiwegweiche Richtung Westen   
* `Blockpanel_T2RE_260318.FCStd` – rechte Zweiwegweiche Richtung Osten   
* `Blockpanel_T2RW_260318.FCStd` – rechte Zweiwegweiche Richtung Westen   

<a name="x40"></a>   

# 4. Panel für Dreiwegweichen
Dreiwegweichen können nach **links (West)** oder **rechts (Ost)** geöffnet sein.   
Es gibt **zwei Varianten**:   

![Blockpanel_Dreiwegweiche](/images/300_3D_blockpanel_2Aof3.png "Blockpanel_Dreiwegweiche")   

**Dateien:**   
* `Blockpanel_T3E_260318.FCStd` – Dreiwegweiche Richtung Osten   
* `Blockpanel_T3W_260318.FCStd` – Dreiwegweiche Richtung Westen   

<a name="x50"></a>   

# 5. Panel für Entkuppler
Das Panel für Entkuppler gibt es mit und ohne 3D-gedrucktem Text:   
![Blockpanel_Entkuppler](/images/300_3D_blockpanel_3Aof3.png "Blockpanel_Entkuppler")   

**Dateien:**   
* `Blockpanel_Uncoupler_Text_260322.FCStd` ... Entkuppler   
* `Blockpanel_Uncoupler_noText_260318.FCStd` ... Entkuppler (ohne Text)   

<a name="x60"></a>   

# 6. Panel für ein abschaltbares Gleis
Das Panel für ein abschaltbares Gleis gibt es mit und ohne 3D-gedrucktem Text:   
![Blockpanel_Gleis](/images/300_3D_blockpanel_3Bof3.png "Blockpanel_Gleis")   

**Dateien:**   
* `Blockpanel_DisconTrack_Text_260322.FCStd` ... Abschaltbares Gleis   
* `Blockpanel_DisconTrack_noText_260318.FCStd` ... Abschaltbares Gleis (ohne Text)   

<a name="x70"></a>   

# 7. Weitere Blockpanels
Wenn ein Rahmen eine Ausnehmung hat, die man nicht mehr benötigt, dann kann man ein leeres Blockpanel hineinstecken.   
Mit dem leeren Blockpanel-Shield kann man die Schrauben zwischen den Frontrahmenteilen abzudecken.   

**Dateien:**   
* `Blockpanel_empty_260403.FCStd` ... Leeres Blockpanel   
* `Blockpanel_empty_shield_260405.FCStd` ... Leeres Blockpanel-Shield ohne PadBlock   
* `Blockpanel_all_east_260318.FCStd` ... Blockpanel mit allen Bohrungen und einem Dreiwegweichensymbol (für Testzwecken)   

[Zum Seitenanfang](#up)