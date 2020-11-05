# Vorlage für Thesis, Hausarbeit, Praktikumsbericht, Protokolle an der HS Wismar

## Zweck
Einfaches LaTeX-Dokument mit Beispielen und Kommentaren für das Erstellen von Thesis, Hausarbeit, Praktikumsbericht, Laborprotokollen etc., das auch für LaTeX-Anfänger gut zu verstehen ist.

Zunächst ist dieses Dokument für die Fakultät für Ingenieurwissenschaften gedacht.

## Voraussetzungen
Um einen reibungslosen Ablauf zum Erstellen einer Arbeit mit diesem Dokument empfehle ich zunächst MikTex und danach Texmaker zu installieren.

MikTex garantiert (im Vergleich zu anderen 'Tex-Compilern') ein einfaches Nachladen von fehlenden LaTeX-Paketen.

Texmaker ist als Schreibumgebung meiner Meinung nach am übersichtlichsten und einsteigerfreundlichsten. Dennoch sind dort einige Einstellungen vorzunehmen bevor dieses Dokument erstellt werden kann.

Dazu über `Einstellungen -> Konfiguration` die Texmaker-Einstellungen öffnen. Im Reiter `Kommandos` muss in der Zeile Bib(la)tex `biber` eingerichtet werden (Linux: `biber %`, Windows: `path/to/biber`). Im Reiter `Quick Build` muss die Option `PdfLaTeX + Bib(la)tex + PdfLaTeX (2x) + View Pdf` ausgewählt werden. Nur so kann die Bibliografie erzeugt werden.

## ToDo in diesem Projekt
1. mehr Kommentare
2. englische Version
3. Bereinigung von Warnungen während es Ausführens von `PdfLaTeX`
4. Ausführen von `LaTeX` ermöglichen (bisher: `critical errors`)