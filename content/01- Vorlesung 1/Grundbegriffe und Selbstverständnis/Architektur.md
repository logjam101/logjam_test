benötigt zur Beschreibung & Gestaltung komplexer Systeme
- **Informationssystem-Architektur**: „Generalbebauungsplan, Rahmenplan, der die Bestandteile und ihre Beziehungen beschreibt“
- **Anwendungsarchitektur**: „Unter einer Anwendungsarchitektur ist die methodisch fundierte Struktur eines für die Benutzer relevanten Softwaresystems als Teil eines Informations- und Kommunikationssystems zu verstehen"
### Funktionen von Architekturen = Sinn und Zweck von Architekturen
- **Abstraktion**: Durch abstrakte & komprimierte Darstellung der wesentlichen Aspekte eines Systems.
	- Um etwas verständlicher und nachvollziehbar zu erklären
	- Gleichgewicht aus einer oberflächlichen und detaillierten Beschreibung finden
- **Strukturierung**: Beschreibung von Strukturen
	- Architektur sollte übersichtlich sein
- **Verständigung**: Durch Gemeinsame Sprache zwischen allen Beteiligten (Anwendern, Entwicklern, ...)
- **Standardisierung**: Branchenspezifische Wiederverwendung von Komponenten
- **Entwicklungsmittel**: Generalbebauungsplan für die Erstellung eines AwS = soll als Blaupause für ein konkretes System dienen → WICHTIG: nicht mehrere Systeme!
### Beispiel einer Anwendungsarchitektur: Open Office
- Abstraktion = gesamte Abbildung
- Strukturierung = z.B.: Top Middle und Bottom
- Verständigung = die Farben, die verwendet werden: einzelne Komponenten werden beschrieben
- Standardisierung = einzelne Komponenten werden an anderen Stellen wiederverwendet
- Entwicklungsmittel = Blaupause/Generalbauungsplan = Spezifisch für OpenOffice, für ein Grundgerüst, um Office zu realisieren
![[Pasted image 20240224132738.png]]
### Beispiel Architektur: Open Shift Enterprise 3
- Architektur, weil es sich um ein bestimmtes System handelt, mit bestimmten Komponenten, die teilweise sehr spezifisch sind
- Technologie ist der Fokus (Aufteilung in Master und Nodes)
- Unabhängig von der Konfiguration & der verwendeten Technologie ➔ Architektur
- Aber: Wenn man alles in Rot rausnehmen würde, dann hätte man ein Referenzmodell für „Containern“