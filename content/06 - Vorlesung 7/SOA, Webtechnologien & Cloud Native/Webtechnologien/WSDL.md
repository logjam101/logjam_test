Web Service Description Language
- basiert auf Webstandards XMLSchema und SOAP
- Beschreibung eines Web-Services durch Datentypen, Operationen, Protokolle
- dient zur Registrierung von Web-Services (UDDI) und zu deren Auffinden
- ermöglicht die automatische Generierung von Proxy-Objekten auf Client-Seite
### Aufbau der WSDL:
WSDL 1.1 XML Datei besteht aus 5 Komponenten
- Types: Beschreibung der verwendeten Datentypen in XML-Schem
- Messages: Definition der einzelnen SOAP Nachrichten mit ihren Argumenten
- Port Types: Definition einzelner Methoden (Operationen) und den zugehörigen (Request/Response) Nachrichten
	- Ein Port fasst mehrere Methoden zusammen
- Binding: Spezifikation eines Protokolls für jede Operation eines Ports
- Service: Definiert einen Web-Service durch mehrere Port/Bindungs-Paare
![[Pasted image 20240226215923.png]]