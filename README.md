⚡ Nexlat

Global Cloud Routing Intelligence
Finde die Cloud-Region mit der besten Verbindung für deinen Standort.
Nexlat misst TCP-Latenzen zu verifizierten Cloud-Endpunkten weltweit und macht die Ergebnisse auf einer interaktiven Karte vergleichbar
 
🚀 **nexlat.itzenton.de**

✨ Was ist Nexlat?
Nexlat ist ein leichtgewichtiges Flask-Dashboard für Cloud-Region-Entscheidungen. Statt nur Standorte aufzulisten, misst Nexlat die reale TCP-Verbindung vom laufenden Server zu regionalen Cloud-Endpunkten auf Port 443.
So kannst du schnell sehen, welche Region für deinen aktuellen Netzwerkpfad besonders interessant ist.
Highlights
- 🌍 Interaktive Weltkarte mit Cloud-Regionen rund um den Globus
- ⚡ Live-Latenztests zu verifizierten regionalen TCP-Endpunkten
- 🏆 Ranking nach gemessener Latenz
- 🔎 Suche & Provider-Filter für Regionen, Anbieter und Standorte
- 📊 Detailansicht mit Latenz, Durchschnitt, Status und Messwerten
- 🗃️ Persistente Test-History mit SQLite
- 🔌 REST API v1 inklusive OpenAPI-Schema
- 📡 Server-Sent Events für Live-Testresultate
- 🇩🇪 / 🇬🇧 Deutsch & Englisch direkt in der Oberfläche
- 🔐 Whitelisted Testziele statt beliebiger externer Hosts
Nexlat enthält aktuell 194 verifizierte regionale Endpunkte von 11 Anbietern.

🌐 Live ausprobieren
Die produktive Version findest du hier:
👉 https://nexlat.itzenton.de
Die API-Dokumentation ist direkt unter folgendem Link erreichbar:
📚 https://nexlat.itzenton.de/api
🧠 Wie funktioniert die Messung?
Nexlat führt einen TCP-Handshake auf Port 443 zu fest definierten, regional zugeordneten Cloud-Endpunkten aus.
Dadurch misst Nexlat den Netzwerkpfad von dem Rechner beziehungsweise Server, auf dem die Flask-App läuft.
Wichtig: Das ist kein klassischer ICMP-Ping und auch keine Garantie für die spätere Latenz innerhalb eines authentifizierten Cloud-Workloads. DNS, Routing und der Standort des Nexlat-Servers beeinflussen das Ergebnis.
