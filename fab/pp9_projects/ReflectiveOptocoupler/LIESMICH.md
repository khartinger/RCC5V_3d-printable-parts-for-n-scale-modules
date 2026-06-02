<table><tr><td><img src="/images/96_RCC5V_Logo.png"></img></td><td>
Letzte &Auml;nderung: 27.5.2026 <a name="up"></a><br>   
<h1>RCC5V: Reflexkoppler zur Zugerkennung</h1><h3>3D-Druck-Teile für N-Spur-Module</h3>
<a href="#TableOfContents">==> Inhaltsverzeichnis</a>&nbsp; &nbsp; &nbsp;  &nbsp; 
<a href="README.md">==> English version</a>
</td></tr></table>   

<a name="x10"></a>   

# 1. Worum geht es?
Dieses Verzeichnis enthält die Bauanleitung für ein 55,5 mm langes Fleischmann-Schottergleis mit eingebautem Sensorboard HW-870. Das Sensorboard enthält die Reflexlichtschranke TCRT5000.   
![Sensorboard HW-870](/images/300_pp9_HW-870.png "Sensorboard HW-870")   

<a name="TableOfContents"></a>   

## Inhaltsverzeichnis
1. [Worum geht es?](#x10)   
2. [Verwendete Bauteile](#x20)   
3. [Grenzen des Reflexkoppler-Einsatzes](#x30)   
4. [Bau der Reflex-Lichtschranke](#x40)    

<a name="x20"></a>   

# 2. Verwendete Bauteile   
* Fleischmann-Schottergleis, gerade, 55,5 mm lang   
* Sensorboard HW-870   
* FreeCAD Datei `Gerade_Schotter_9103_Opto_260526.FCStd`   
* FreeCAD Datei `Gerade_Damm_9103_Opto_260526.FCStd`   
* FreeCAD Datei `Opto_Beilage_2.2mm_260531.FCStd`   
* Schraube M 2,6 x 10 mm Kreuzschlitz, Halbrundkopf, selbstbohrend   

Weiters sinnvoll:
* Dünnes Doppelklebeband   
* Glasfaserkabel 2,5 mm zum Abdecken der Bohrungen im Gleisschotter   

Bauteile:   
![Bauteile Reflexkoppler](/images/300_pp9_comp_reflective_oc1.png "Bauteile Reflexkoppler")   

Beilage:   
![Beilage](/images/300_pp9_beilage_2.2mm.png "Beilage")   
<a name="x30"></a>   

# 3. Grenzen des Reflexkoppler-Einsatzes
Bei der "Serienfertigung" ergaben sich einige Probleme.   

## 1. Ausrichtung der LEDs am Sensor-Board
Die Reflexlichtschranke TCRT5000 ist nicht direkt auf das Board montiert sondern ca. 10,16 mm über dem Print (Abstand Oberkanten). Damit ergeben sich Lage-Ungenauigkeiten und der Abstand für die Bohrungen im Gleis schwankt zwischen ca. 3,8 mm und 3,1 mm.   

## 2. Umgebungshelligkeit
Befinden sich direkt über dem Koppler starke Lampen oder Sonnenlicht, so schaltet der Empfänger auch ohne Opjekt durch. In diesem Fall kann man die Empfindlichkeit mit dem Poti auf dem Sensorboard reduzieren. Dreht man die Empfindlichkeit zurück so kann es sein, dass dann auch kein Waggon mehr erkannt wird.   

<a name="x40"></a>   

# 4. Bau der Reflex-Lichtschranke
__Montage Sensorboard__   
1. Drucken der 3D-Teile `Gerade_Schotter_9103` und `Damm_Schotter_9103`   
2. Zusammenfügen der Teile mit einem dünnen Doppelklebeband   
3. Drucken des Abstandshalters `Opto_Beilage_2.2mm_260531`   
4. Anlegen des Abstandshalters an das Sensorboard und Einstecken des Boards in die Öffnung des Gleisbettes   
5. Anschrauben des Sensorboards an das Gleisbett   

__Fleischmann-Gleis__
1. `Optobohrlehre_9103_3.4mm_260531` fluchtend auf das Gleis legen.   
2. Auf die beiden Bohrungen von oben draufschauen und kontrollieren, ob die Bohrungen wirklich genau zwischen zwei Schwellen liegen. Dann Optobohrlehre mit Klebeband fixieren.   
3. 2x 2,6 mm Bohrungen in das Gleisbett bohren.   
4. Optobohrlehre entfernen, Glasfaserkabel 2,5 mm durch die Bohrungen im Gleisbett stecken und ablängen.   

Optobohrlehre:   
![Beilage](/images/300_pp9_optobohrlehre_9103_3.4mm.png "Beilage")   

[Zum Seitenanfang](#up)
