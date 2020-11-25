Anleitung zur Verwendung der LaTeX-Vorlage
(Windows)

1.	MiKTeX (https://miktex.org/download) oder alternative Distribution installieren
2.	TeXnicCenter (http://www.texniccenter.org/download/) oder alternativen Editor installieren
3.	TeXnicCenter öffnen
4.	main.tex aus der Vorlage öffnen
5.	Menü: Projekt -> Erzeugen mit aktueller Datei als Hauptdatei
  a.	Haken bei “Verwendet BibTeX” und “Verwendet MakeIndex”
  b.	mit “Ok” bestätigen
6.	Menü: Ausgabe-> Ausgabeprofile definieren
  a.	„Latex -> PDF“ wählen und kopieren
  b.	das kopierte Profil in „Latex -> PDF (Biber)“ umbenennen
  c.	im Tab „(La)TeX“ und „Pfad des BibTeX-Compilers“ die angegebene exe-Datei auf „biber.exe“ ändern
  d.	mit „OK“ bestätigen
 
7.	In der Menüleiste “Latex  PDF (Biber)” in der Dropdownliste wählen
8.	In der Menüleiste “Ausgabe erstellen”   wählen
9.	Falls ein Dialog erscheint, müssen Pakete nachinstalliert werden (ggf. den Haken bei “Always show this dialog[…] entfernen)
10.	Beim Erstellen des PDFs darauf achten, dass die Datei “main.pdf” nicht geöffnet ist. Sollte das Ergebnis noch nicht wie gewünscht aussehen, muss das PDF ggf. noch ein zweites Mal gebaut werden, damit interne Verlinkungen etc. erstellt werden können.
11.	In der Menüleiste gibt es verschiedene Möglichkeiten das Dokument sofort oder nach dem Build-Vorgang zu betrachten.   Sollte das Dokument nicht im PDF-Viewer angezeigt werden, kann für den Adobe Acrobat Reader DC wie folgt vorgegangen werden.
  a.	Menü: Ausgabe-> Ausgabeprofile definieren
  b.	im Tab „Viewer“ zunächst sicherstellen, dass bei „Pfad der Anwendung“ ein Pfad zum PDF-Viewer angegeben ist
  c.	die drei Einträge der „Server“-Eingabefelder ändern in „acroviewR15“ oder „acroviewR17“ (je nach installierter Version)
  d.	sollte es jetzt noch nicht funktionieren muss zusätzlich im Adobe Acrobat Reader DC unter Bearbeiten -> Voreinstellungen… im Abschnitt „Sicherheit (erweitert) der Haken bei „Geschützten Modus beim Start aktivieren“ entfernt werden
 
