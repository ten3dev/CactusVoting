# 🌵 CactusVoting

**The ultimate voting solution for your Minecraft server.**  
**Die ultimative Voting-Lösung für deinen Minecraft Server.**

---

## 🇺🇸 English Documentation

**CactusVoting** is a standalone, lightweight, and powerful voting plugin designed for modern and legacy Minecraft servers (1.6 - 1.21+). It supports standard Votifier voting, offline voting queuing, VoteParties, and even legacy API polling for `minecraft-serverliste.net`.

### Features
*   **Universal Votifier Support:** Works with NuVotifier and all standard server lists.
*   **Offline Voting Support:** Players can vote while offline and receive rewards when they join.
*   **VoteParty System:** Global rewards after a configurable number of votes.
*   **Legacy API:** Optional direct polling from `minecraft-serverliste.net`.
*   **Multi-Language:** Fully localized in English and German.
*   **Version Independent:** Runs on Bukkit/Spigot versions from 1.6 to 1.21+.

### Installation
1.  Download `CactusVoting.jar` from the releases page.
2.  Install [Votifier](https://www.spigotmc.org/resources/nuvotifier.13449/) (NuVotifier recommended) on your server.
3.  Place `CactusVoting.jar` into your `plugins` folder.
4.  Restart your server.
5.  Configure `config.yml` to your liking.

### Commands & Permissions
| Command | Permission | Description |
| :--- | :--- | :--- |
| `/vote` | None | Shows the vote link. |
| `/vote party` | None | Checks current VoteParty status. |
| `/vote reload` | `cactusvoting.admin` | Reloads the configuration. |
| `/fakevote <player> <service>` | `cactusvoting.admin` | Simulates a vote (for testing). |

### Configuration
The `config.yml` allows you to customize messages, rewards, and feature toggles.
To change the language to German, set `language: "de"` in the config.

---

## 🇩� Deutsche Dokumentation

**CactusVoting** ist ein eigenständiges, leichtgewichtiges und mächtiges Voting-Plugin für moderne und ältere Minecraft Server (1.6 - 1.21+). Es unterstützt normales Votifier-Voting, Offline-Voting (Warteschlange), VoteParties und sogar die Legacy-API von `minecraft-serverliste.net`.

### Funktionen
*   **Universeller Votifier Support:** Funktioniert mit NuVotifier und allen Serverlisten.
*   **Offline Voting Support:** Spieler können offline voten und erhalten ihre Belohnung beim Betreten des Servers.
*   **VoteParty System:** Globale Belohnungen nach einer bestimmten Anzahl an Votes.
*   **Legacy API:** Optionale direkte Abfrage von `minecraft-serverliste.net`.
*   **Mehrsprachig:** Komplett auf Deutsch und Englisch verfügbar.
*   **Versionsunabhängig:** Läuft auf Bukkit/Spigot Versionen von 1.6 bis 1.21+.

### Installation
1.  Lade `CactusVoting.jar` von der Releases-Seite herunter.
2.  Installiere [Votifier](https://www.spigotmc.org/resources/nuvotifier.13449/) (NuVotifier empfohlen) auf deinem Server.
3.  Lege die `CactusVoting.jar` in deinen `plugins` Ordner.
4.  Starte deinen Server neu.
5.  Passe die `config.yml` nach deinen Wünschen an.

### Befehle & Rechte
| Befehl | Recht (Permission) | Beschreibung |
| :--- | :--- | :--- |
| `/vote` | Keine | Zeigt den Vote-Link an. |
| `/vote party` | Keine | Zeigt den aktuellen VoteParty Status. |
| `/vote reload` | `cactusvoting.admin` | Lädt die Konfiguration neu. |
| `/fakevote <player> <service>` | `cactusvoting.admin` | Simuliert einen Vote (zum Testen). |

### Konfiguration
In der `config.yml` kannst du Nachrichten, Belohnungen und Funktionen anpassen.
Um die Sprache aud Deutsch zu stellen, setze `language: "de"`.

---

© 2026 **Oskar Balthasar & Nicolas P. Acker** - ten3 digital services.  
Released under the **MIT License**.
