- Leichtgewichtige Containertechnologie
- Umgebungstypen: Entwicklungs-, Pack- und Laufzeitumgebung für portable, verteilte Anwendungen
- Basiert auf der Linux-Containertechnologie LXC
- Läuft auf den meisten Betriebssystemen
### Docker-Container
- Isolierte Umgebung, die ein eigenes Filesystem und Umgebungsvariablen besitzt
- Enthält kein Betriebssystem nur ein Filesystem
- Kapselt Ressourcen, die ein Programm benötigt, um in einem Container zu laufen
[[Virtualisierungskonzepte]]
### Docker-Images
- Docker-Image: portable Abbildung eines Docker-Containers
- Docker-Hub: Online-Dienst, beinhaltet eine Registry für Docker-Images &Repositories
- Docker-Engine: Laufzeitumgebung mit API und Kommandozeilen-Schnittstelle (CLI
### Docker-Architektur
- links Command line interface, docker build = neues image anlegen,
- docker pull = Download eines Images aus einer registry
- docker run = starten eines Containers, nachdem das Image ausgepackt ist
![[Pasted image 20240227120332.png]]
- Container werden auf beliebigen Rechenknoten bereitgestellt, als ob es sich um einen einzigen, riesigen Computer handeln würde.