**⚡ Nexlat**


Global Cloud Routing Intelligence
Find the cloud region with the best connection for your location.
Nexlat measures TCP latency to verified cloud endpoints worldwide and makes the results easy to compare on an interactive map.

🌐 Live
🚀 Website: nexlat.itzenton.de
📚 API Documentation: nexlat.itzenton.de/api

✨ What is Nexlat?
Nexlat is a lightweight Flask dashboard for cloud region decisions.
Instead of only listing locations, Nexlat measures the real TCP connection from the running server to regional cloud endpoints on port 443. This helps you quickly compare which region is most suitable for your current network path.

Highlights
- 🌍 Interactive world map with cloud regions around the globe
- ⚡ Live latency tests to verified regional TCP endpoints
- 🏆 Ranking by measured latency
- 🔎 Search & provider filters for regions, providers, and locations
- 📊 Detailed view with latency, average, status, and measurements
- 🗃️ Persistent test history with SQLite
- 🔌 REST API v1 including an OpenAPI schema
- 📡 Server-Sent Events for live test results
- 🇩🇪 🇬🇧 German & English directly in the interface
- 🔐 Whitelisted test targets instead of arbitrary external hosts
194 verified regional endpoints from 11 providers.

🧠 How does the measurement work?
Nexlat performs a TCP handshake, region-specific cloud endpoints.
This measures the network path from the computer or server running the Flask application.
Important: This is not a traditional ICMP ping. DNS, routing, and the location of the Nexlat server can affect the result. The measurement therefore does not guarantee the final latency inside an authenticated cloud workload.
