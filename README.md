# PDF-Rechnung per PHP erstellen
In der Datei [rechnung.php](rechnung.php) findet ihr ein Beispiel, wie ihr mittels PHP PDF-Dokumente dynamisch erzeugen könnt. Hierzu wird im PHP-Script entsprechender HTML-Code definiert, der den Inhalt des PDFs bereit hält. Dieses wird anschließend mit der Library [tcpdf](https://tcpdf.org) in ein PDF-Dokument übersetzt. Hierdurch müsst ihr keine komplizierte Befehle zur Erzeugung des PDF-Dokuments lernen: Einfacher HTML-Code ist ausreichend.

[rechnung.php](rechnung.php) enthält ein Beispiel zur Erzeugung einer dynamischen PDF-Rechnung. Diese könnt ihr entweder auf dem Server speichern, oder diese direkt im Browser an den Benutzer senden. 

Die erzeugte Rechnung sieht wie folgt aus [Beispiel_Rechnung.pdf](Beispiel_Rechnung.pdf):
![Beispiel_Rechnung.pdf](Beispiel_Rechnung.png "Beispiel_Rechnung.pdf")

