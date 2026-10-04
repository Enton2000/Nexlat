⚡ Nexlat
Global Cloud Routing Intelligence
Finde die Cloud-Region mit der besten Verbindung für deinen Standort.
Nexlat misst TCP-Latenzen zu verifizierten Cloud-Endpunkten weltweit und macht die Ergebnisse auf einer interaktiven Karte vergleichbar.

🌐 Live
🚀 Website: nexlat.itzenton.de
📚 API-Dokumentation: nexlat.itzenton.de/api

✨ Was ist Nexlat?
Nexlat ist ein leichtgewichtiges Flask-Dashboard für Cloud-Region-Entscheidungen.
Statt nur Standorte aufzulisten, misst Nexlat die reale TCP-Verbindung vom laufenden Server zu regionalen Cloud-Endpunkten auf Port 443. Dadurch kannst du schnell vergleichen, welche Region für deinen aktuellen Netzwerkpfad besonders interessant ist.


Highlights
- 🌍 Interaktive Weltkarte mit Cloud-Regionen rund um den Globus
- ⚡ Live-Latenztests zu verifizierten regionalen TCP-Endpunkten
- 🏆 Ranking nach gemessener Latenz
- 🔎 Suche & Provider-Filter für Regionen, Anbieter und Standorte
- 📊 Detailansicht mit Latenz, Durchschnitt, Status und Messwerten
- 🗃️ Persistente Test-History mit SQLite
- 🔌 REST API v1 inklusive OpenAPI-Schema
- 📡 Server-Sent Events für Live-Testresultate
- 🇩🇪 🇬🇧 Deutsch & Englisch direkt in der Oberfläche
- 🔐 Whitelisted Testziele statt beliebiger externer Hosts
194 verifizierte regionale Endpunkte von 11 Anbietern.


🧠 Wie funktioniert die Messung?
Nexlat führt einen TCP-Handshake zu fest definierten, regional zugeordneten Cloud-Endpunkten aus.
Gemessen wird damit der Netzwerkpfad von dem Rechner beziehungsweise Server, auf dem die Flask-App läuft.
Wichtig: Das ist kein klassischer ICMP-Ping. DNS, Routing und der Standort des Nexlat-Servers beeinflussen das Ergebnis. Die Messung garantiert deshalb nicht die spätere Latenz innerhalb eines authentifizierten Cloud-Workloads.
