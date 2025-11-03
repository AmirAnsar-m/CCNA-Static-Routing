Static Routing – Three Routers in Line



 Deutsch:
In diesem Projekt habe ich ein Netzwerk mit drei Cisco-Routern erstellt, die über zwei serielle Verbindungen miteinander verbunden sind.
Jeder Router ist zusätzlich mit einem eigenen LAN (192.168.x.0/24) verbunden.
Die Kommunikation zwischen den Netzen erfolgt über statische Routen.

--- Übersicht

Router1: LAN → 192.168.1.0/24
Verbindung zu Router2 → 10.0.0.0/30

Router2: LAN → 192.168.2.0/24
Verbindungen zu Router1 (10.0.0.0/30) und Router3 (10.0.0.4/30)

Router3: LAN → 192.168.3.0/24
Verbindung zu Router2 → 10.0.0.4/30

Ziel: Verständnis von Static Routing und IP-Adressplanung zwischen mehreren Routern.





 English:
In this lab, I built a network using three Cisco routers connected in series through two point-to-point links.
Each router also connects to its own local LAN (192.168.x.0/24).
All communication between networks is achieved using static routes.

--- Overview

Router1: LAN → 192.168.1.0/24
Link to Router2 → 10.0.0.0/30

Router2: LAN → 192.168.2.0/24
Links to Router1 (10.0.0.0/30) and Router3 (10.0.0.4/30)

Router3: LAN → 192.168.3.0/24
Link to Router2 → 10.0.0.4/30

Goal: To practice static routing and IP address planning between multiple routers.