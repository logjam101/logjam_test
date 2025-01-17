- Optimaler Grad an Redundanz (Facetten)
	- Datenredundanz: Redundante Datenobjekte oder Attribute
	- Funktionsredundanz: überlappende Lösungsverfahren oder Aktionen
- Auswirkung von Redundanz
	- geringe Redundanz:
		- wenige Inkonsistenzen
		- wirtschaftlicher Umgang mit Ressource (z.B. Speicher)
	- hohe Redundanz:
		- Toleranz gegenüber Komponentenausfall → legen nicht das gesamte System lahm, wenn eine Komponente ausfällt
		- Leistungssteigerung bei paralleler Nutzung → Parallele Rechenknoten in der Cloud führt zu schnelleren Ergebnissen
		- Anwendungsszenario, wo hohe Redundanz sinnvoll ist: Banken haben mehrere Server im Einsatz, die Kontobewegungen & Transaktionen erledigen
- Kontrolle der Kommunikationskanäle zwischen Teil-AwS durch eigenständiges Kommunikationssystem (Vorteile):
	- Zusicherung der Konsistenz durch Erhalt der
		- semantischen Integrität (der Daten im Gesamtsystem) z.B.: Adressen sind einheitlich
		- operationalen Integrität (Integrität bei parallelen Transaktionen) → keine mehrfache Überschreibung von Kontoständen, wenn mehrmals Überweisungen getätigt werden
	- Zentrale Lenkung aller Vorgänge des integrierten AwS (Zielorientiertheit).
		- z.B. durch ein Workflowmanagement System
	- Aufgabenträgerunabhängigkeit:
		- Unabhängigkeit vom Technologiestand und eines spezifischen Rechensystems
- 