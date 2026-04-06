<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 6.4.2026 <a name="up"></a><br>   
<h1>Rahmenteile</h1><h3>3D-Druck-Teile für N-Spur-Module</h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# Worum geht es?
Dieses Verzeichnis enthält Details zu den Rahmenteilen sowie die Freecad-Zeichnungen.   
Das folgende Bild gibt eine Übersicht über die Rahmenteile.   

![Uebersicht Rahmenteile](/images/300_3D_frameparts_overview.png "Uebersicht Rahmenteile")   
_Bild 1: Übersicht über die Lage der Rahmenteile_   

Es gibt   
1. [Seitenteile ("West", "Ost")](#x10)   
2. [Frontrahmen (im Süden - "West", "Süd", "Ost")](#x20)   
3. [Rückseitiger Rahmen ("Nord")](#x30)   
4. [Querstreben](#x40)   
5. [Distanzplättchen](#x50)   

<a name="x10"></a>   

# 1. Seitenteile
Seitliche Rahmenteile ("Seitenteile") bestehen aus dem Basisteil und dem Aufsatz für das Gleis (im Bild blau markiert):   
![Seitlicher Rahmenteil](/images/300_frame_side_1-rail.png "Seitlicher Rahmenteil")   
_Bild 2: Seitlicher Rahmenteil mit einem Gleis in der Mitte_   

Die Maße zeigt das folgende Bild:   
![Maße seitlicher Rahmenteil](/images/300_frame_side_dim_1-rail.png "Maße seitlicher Rahmenteil")   
_Bild 3: Maße des seitlichen Rahmenteils mit einem Gleis in der Mitte_   

_**Dateinamen**_:   
* `Rahmen_SeiteEingleisig_260312.FCStd` ... Eingleisiger Seitenteil mit Gleis in der Mitte des Rahmenteils   
* `Rahmen_SeiteZweigleisig_260312.FCStd` ... Zweigleisiger Seitenteil mit zwei Gleisen in der Mitte des Rahmenteils   

<a name="x20"></a>   

# 2. Frontrahmen
Die Längsrahmenteile haben kleine Haken (2 mm), damit sie zusammenhalten. Deshalb unterscheidet man   
* Frontrahmen West   
* Frontrahmen Süd (Mitte)   
* Frontrahmen Ost   

_**Zusammenbau**_   
Die Nasen der Frontrahmen werden zusammengehängt und durch die Noppen in den Querstreben sowie durch M3x25 mm Schrauben fixiert.   

_**Dateinamen**_:   
Frontrahmen können Aussparungen für Steuerblöcke und/oder den OLED-Block (Steuerblock) enthalten. Dies steht dann in den Dateinamen:   

`Rahmen_Front_L_1234_240mm_260401.FCStd`   
` Name _ Typ _L_Fenster_Länge_Datum`   
mit   
`L ......` Lage: E = Ost (East), S = Süd, W = West   
`1234 ...` Fenster (1 bis 4 oder OLED)   

__*Beispiel*__   
![Rahmen_Front_W_Oled_4](/images/300_Rahmen_Front_W_Oled_4.png "Rahmen_Front_W_Oled_4")   
 Ein Frontrahmen an der Westseite mit Oled-Aussparung und einem Fenster an der 4. Position hat somit den Dateinamen   
`Rahmen_Front_W_Oled_4_240mm_260401.FCStd`    

<a name="x30"></a>   

# 3. Rückseitiger Rahmen ("Nord")
Der rückseitige (nördliche) Rahmen wird oft aus Pappelsperrholz gefertigt, da dieser meist einfach zu fertigen und preiswerter ist.   
Es können aber auch 3D-Frontrahmen ohne Aussparungen verwendet werden.   

<a name="x40"></a>   

# 4. Querstreben
Die Querstreben für den 3D-Rahmen unterscheiden sich von den Holzquerstreben durch die Lage der seitlichen Bohrungen, Noppen bei den Bohrungen und die Lage der seitlichen Durchführung:   

![Bohrungen Querstreben](/images/300_3D_pos_holes_cross_member.png "Bohrungen Querstreben")   
_Bild 4: Maße der seitlichen Bohrungen und Durchführungen bei Holz- und 3D-Querstreben_   

Auf den seitlichen Bohrungen befinden sich Noppen, um die Frontteile zu fixieren. Die Größe der Noppen entspricht in etwa dem Kopf von Senkschrauben M3x25 mm.   

![Noppen Querstreben](/images/300_3D_nubs_cross_member.png "Noppen Querstreben")   
_Bild 5: Noppen auf den seitlichen Bohrungen bei 3D-Querstreben_   

_**Dateiname**_:   
`Rahmen_Quer_230mm_260313.FCStd`   

<a name="x50"></a>   

# 5. Rahmen-Distanzplättchen
Sollte die Zusammenstellung der Front- (oder Nord-) Rahmen zu kurz sein, so kann durch Einfügen von Rahmen-Distanzplättchen die passende Länge erreicht werden. Die Plättchen werden zB zwischen dem Front_E-Rahmen und dem Seitenteil eingefügt und haben Dicken von 0,8 mm, 1 mm, 2,5 mm oder 2 mm.   
![Rahmen-Distanzplättchen](/images/300_3D_frame_spacer_plate1.png "Rahmen-Distanzplättchen")   
_Bild 6: Rahmen-Distanzplättchen_   

_**Dateinamen**_:   
`Rahmen_Distanzplatte_0.8mm_260404.FCStd`   
`Rahmen_Distanzplatte_1.0mm_260404.FCStd`   
usw.   
[Zum Seitenanfang](#up)