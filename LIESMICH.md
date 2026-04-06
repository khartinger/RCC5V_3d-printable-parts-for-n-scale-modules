<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 5.4.2026 <a name="up"></a><br>   
<h1>3D-Druck-Teile für N-Spur-Module</h1><h3></h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# 1. Worum geht es?
Im Repository [`khartinger/RCC5V`](https://github.com/khartinger/RCC5V/blob/main/LIESMICH.md) werden Steuerelemente für Weichen, Gleise usw. vorgestellt, die zum Beispiel in N-Spur-Modelleisenbahn-Modulen eingesetzt werden. Für den Bau solcher Module wird oft Pappelsperrholz verwendet, es ist aber auch möglich, Teile mit dem 3D-Drucker herzustellen.   
Ein Beispiel für den Modulrahmenbau aus Holz findet sich unter anderem in [https://github.com/khartinger/RCC5V/blob/main/examples/module12/LIESMICH.md](https://github.com/khartinger/RCC5V/blob/main/examples/module12/LIESMICH.md#20).   
Dieses Repository beschäftigt sich mit dem Entwurf und Druck von Modulrahmenteilen sowie Teilen für den Gleisunterbau. Als Software wird das kostenlose, quelloffene (Open-Source) [ 3D-CAD-Programm Freecad](https://www.freecad.org/), als 3D-Drucker wird ein [Prusa-XL-Drucker](https://www.prusa3d.com/de/produkt/original-prusa-xl-3d-drucker/) verwendet. Der Drucker hat ein maximales Druckvolumen von 360 x 360 x 360 mm³.   

<a name="TableOfContents"></a>   

## Inhaltsverzeichnis
1. [Worum geht es?](#x10)   
2. [Rahmenteile (Baseboard Frame)](#x20)   
3. [Blockpanel](#x30)   
4. [Schotterbett (Track Ballast)](#x40)   
5. [Bahndamm (Embankment)](#x50)   
6. [Werkzeuge (Tools)](#x60)    

<a name="x20"></a>   

# 2. Rahmenteile
Die N-Spur-Modelleisenbahn-Module haben eine Breite von 25 cm und eine Länge von 25 bis 100 cm. Da der 3D-Drucker maximal 36 cm große Teile drucken kann, wird der Längsrahmen in 25 cm große Abschnitte unterteilt.   
Das folgende Bild gibt eine Übersicht über die Rahmenteile.   

![Uebersicht Rahmenteile](/images/300_3D_frameparts_overview.png "Uebersicht Rahmenteile")   
_Bild 1: Übersicht über die Lage der Rahmenteile_   

Die Längsrahmenteile haben kleine Haken (2 mm), damit sie zusammenhalten. Durch Noppen in den Querstreben und M3x25 mm Schrauben werden sie dann fixiert.   

Im Detail gibt es folgende Rahmenteile:   
#### Seitenteile ("West", "Ost")
* Eingleisiger Seitenteil mit Gleis in der Mitte des Rahmenteils   
  Datei: `Rahmen_SeiteEingleisig_260312.FCStd`   
* Zweigleisiger Seitenteil mit zwei Gleisen in der Mitte des Rahmenteils   
  Datei: `Rahmen_SeiteZweigleisig_260312.FCStd`   

#### Frontrahmen (im Süden)
* Frontrahmen West   
* Frontrahmen Süd (Mitte)   
* Frontrahmen Ost   

Frontrahmen enthalten meist noch Aussparungen für die Steuerblöcke und/oder den OLED-Block (Steuerblock). Somit gibt sich für die Benennung folgende Syntax:   

`Rahmen_Front_L_1234_240mm_260401.FCStd`   
` Name _ Typ _L_Fenster_Länge_Datum`   

`L ......` Lage: E = Ost (East), S = Süd, W = West   
`1234 ...` Fenster (1 bis 4 oder OLED)   

__*Beispiel*__   
![Rahmen_Front_W_Oled_4](/images/300_Rahmen_Front_W_Oled_4.png "Rahmen_Front_W_Oled_4")   
 Ein Frontrahmen an der Westseite mit Oled-Aussparung und einem Fenster an der 4. Position hat somit den Dateinamen   
`Rahmen_Front_W_Oled_4_240mm_260401.FCStd`    

#### Rückseitiger Rahmen ("Nord")
Der rückseitige (nördliche) Rahmen wird oft aus Pappelsperrholz gefertigt, da dieser meist einfach zu fertigen und preiswerter ist.   
Es können aber auch 3D-Frontrahmen ohne Aussparungen verwendet werden.   

#### Querstreben
Die Querstreben für den 3D-Rahmen unterscheiden sich von den Holzquerstreben durch die Lage der seitlichen Bohrungen, Noppen bei den Bohrungen und die Lage der seitlichen Durchführung:   

![Bohrungen Querstreben](/images/300_3D_pos_holes_cross_member.png "Bohrungen Querstreben")   
_Bild 2: Maße der seitlichen Bohrungen und Durchführungen bei Holz- und 3D-Querstreben_   

Auf den seitlichen Bohrungen befinden sich Noppen, um die Frontteile zu fixieren. Die Größe der Noppen entspricht in etwa dem Kopf von Senkschrauben M3x25 mm.   

![Noppen Querstreben](/images/300_3D_nubs_cross_member.png "Noppen Querstreben")   
_Bild 3: Noppen auf den seitlichen Bohrungen bei 3D-Querstreben_   

#### Rahmen-Distanzplättchen
Sollte die Zusammenstellung der Front- (oder Nord-) Rahmen zu kurz sein, so kann durch Einfügen von Rahmen-Distanzplättchen die passende Länge erreicht werden. Die Plättchen werden zB zwischen dem Front_E-Rahmen und dem Seitenteil eingefügt und haben Dicken von 0,8 mm, 1 mm, 2,5 mm oder 2 mm.   
![Rahmen-Distanzplättchen](/images/300_3D_frame_spacer_plate1.png "Rahmen-Distanzplättchen")   
_Bild 4: Rahmen-Distanzplättchen_   

---   
Technische Details und Freecad-Dateien zu Rahmenteilen befinden sich im Unterverzeichnis [https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame/LIESMICH.md](https://github.com/khartinger/RCC5V_3d-printable-parts-for-n-scale-modules/blob/main/fab/pp2_baseboard_frame/LIESMICH.md).   

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