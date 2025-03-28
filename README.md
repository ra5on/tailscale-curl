# Automatisierte Tailscale-Installation für Debian-Systeme

Ein automatisiertes Bash-Script zur schnellen Einrichtung von **Tailscale** auf Debian-basierten Systemen.

## ✅ Funktionen

- Installation von Tailscale über das offizielle Installationsscript
- Automatische Konfiguration mit optimalen Einstellungen:
  - Aktiviertes Subnet-Routing (erkennt automatisch das passende Subnetz)
  - Exit Node aktiviert
  - DNS-Weiterleitung aktiviert
- Aktivierung von IPv4- und IPv6-Forwarding (für Subnet-Routing erforderlich)
- Start von Tailscale mit allen gewählten Optionen
- Authentifizierung per Link oder QR-Code direkt im Terminal
- Übersichtliche Status- und Fortschrittsmeldungen

## ⚙️ Installation

Das Script kann direkt über `curl` ausgeführt werden:

```bash
curl -sL https://raw.githubusercontent.com/ra5on/tailscale-curl/main/tailscale-auto.sh | bash
```
📦 Hinweis: Das Programm curl muss installiert sein. Falls es fehlt, kannst du es mit folgendem Befehl nachinstallieren:
```
sudo apt update && sudo apt install curl -y
```

---

## 📦 Voraussetzungen

- Curl ist installiert
- Debian 11 oder 12 
- Root-Zugriff (z. B. `sudo`)
- Internetverbindung

---


## ⚠️ Hinweis zur Nutzung

Dieses Skript wird ohne jegliche Garantie bereitgestellt und dient ausschließlich zu Lern-, Test- und Demonstrationszwecken.  
Die Ausführung erfolgt auf eigene Gefahr.

Der Autor (alias „ra5on“) übernimmt keine Verantwortung für:
- Schäden am System
- Fehlfunktionen
- Datenverluste
- rechtliche Konsequenzen

---

## 🧩 Drittsoftware & Rechte

Dieses Skript kann Drittsoftware installieren oder konfigurieren  
(z.B. curl, tailscale).

Der Autor:
- übernimmt keine Verantwortung für diese Software,
- macht sich deren Inhalte, Funktionen oder Lizenzen nicht zu eigen,
- beansprucht keine Rechte an fremder Software.

> **Alle Rechte, Marken und Verantwortlichkeiten verbleiben bei den jeweiligen Rechteinhabern.**

---

## 📌 Abschluss

Die Verwendung dieses Skripts sowie aller damit ausgeführten Aktionen erfolgt **vollständig auf eigenes Risiko**.

Es ist **nicht für den produktiven Einsatz** gedacht, ohne **eigene Prüfung und Anpassung** durch den Nutzer.  
Auch bei Änderung, Erweiterung oder Automatisierung bleibt der Haftungsausschluss bestehen.

