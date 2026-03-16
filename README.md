# ⚔️ SwordMaster Idle

> *Schmiede dein Schicksal — ein Zeitalter nach dem anderen.*

---

## 📖 Über das Spiel

**SwordMaster** ist ein browser-basiertes Idle-RPG, entwickelt von **Bassprojekt**.  
Kämpfe durch endlose Wellen von Monstern, schmiede mächtige Ausrüstung, erforsche neue Zeitalter und baue dir ein legendäres Imperium auf — alles automatisch im Hintergrund, auch wenn du nicht spielst.

---

## 🎮 Features

### ⚔️ Arena
- Automatische Kämpfe gegen Wellen von Monstern
- Mehrere Monster gleichzeitig auf dem Bildschirm (bis zu 4)
- Echte SVG-Monster-Grafiken mit Animationen
- Kritische Treffer, Schaden-Anzeigen in Echtzeit
- Stufensystem mit 8 Zonen

### 🔨 Schmiede
- Schmied Items per Klick oder automatisch
- 6 Seltenheitsstufen: Gewöhnlich → Ungewöhnlich → Selten → Episch → Legendär → **Mystisch**
- Alle Items landen im Inventar und können ausgerüstet werden
- Verkaufs-Manager: Items nach Seltenheit sortiert verkaufen
- Auto-Ausrüsten: Das beste Item je Slot wird automatisch angelegt

### 🧙 Held
- Animierte SVG-Figur die sich je nach Ausrüstung einfärbt (Grau → Grün → Blau → Lila → **Gold** → **Rot**)
- 6 Ausrüstungsslots: Waffe, Helm, Brust, Handschuhe, Stiefel, Ring
- Stats: ATK, DEF, Speed, Crit-Chance

### 🏚️ Dungeon
- 50 Etagen in 5 Schwierigkeitsstufen
- Dungeon-Schlüssel als Ressource (regenerieren alle 30 Min)
- Boss-Kämpfe alle 10 Etagen
- Garantierte Item-Drops im Dungeon

### 🥊 PVP
- Kämpfe gegen andere Spieler
- Punkte-System mit Rängen: Bronze → Silber → Gold → Platin → Diamant → **Legende**
- Saison-Rangliste

### 🐾 Haustiere (12 verschiedene)
- Echte Kampfeffekte: Angriff, Vergiftung, Heilung, Geschwindigkeit
- Giftschlange, Feuerdrache, Leeregeist, Schattendämon und mehr
- Bis zu 3 gleichzeitig aktiv

### 🏰 Gilde
- Eigene Gilde gründen oder beitreten
- Echtzeit-Chat (Supabase-powered)
- Mitglieder befördern / rauswerfen (Anführer-Rechte)
- Gold spenden für Gildenpunkte

### 🏆 Rang
- 13 Ränge basierend auf Level, Kills und Gold
- Weltrangliste aller Spieler

### 🛒 Shop
- Verbrauchsgüter: HP-Tränke, XP-Boosts, Gold-Boosts
- Permanente Upgrades: Meister-Amboss, Inventar-Erweiterung
- Tages-Angebote mit 35% Rabatt

### 🔬 Forschung
- 12 Forschungen in 4 Kategorien: Schmiede, Kampf, Pets, Gold
- Zeitbasierte Forschungen (laufen im Hintergrund)
- Amboss-Upgrades für permanente Stat-Boosts

### 📜 Quests
- Tägliche Quests (reset täglich um Mitternacht)
- Haupt-Quests mit Story-Progression
- Erfolge / Achievements

### 🌅 8 Zeitalter
Steinzeit → Bronzezeit → Mittelalter → Renaissance → Industriezeit → Neuzeit → Raumfahrt → **Quantenzeitalter**

---

## 💾 Spielstand

Spielstände werden automatisch in der **Supabase Cloud** gespeichert:
- Automatisches Speichern alle 30 Sekunden
- Spielstand beim Öffnen automatisch laden
- Offline-Belohnungen: bis zu 8 Stunden werden nachberechnet
- Spielstand auf allen Geräten verfügbar (gleiche Browser-ID)

---

## 🛠️ Technik

| Komponente | Technologie |
|---|---|
| Frontend | Vanilla HTML / CSS / JavaScript |
| Datenbank | Supabase (PostgreSQL) |
| Hosting | Netlify |
| Grafiken | Handgezeichnete SVG |
| Fonts | Cinzel, Crimson Pro (Google Fonts) |

---

## 📁 Dateien

```
swordmaster/
├── index.html                    # Das komplette Spiel
├── swordmaster_db.sql            # Haupt-Datenbank Setup
├── swordmaster_new_tables.sql    # Gilden-Tabellen
└── README.md                     # Diese Datei
```

---

## 📸 Screenshots

| Arena | Schmiede | Held |
|---|---|---|
| Monster-Kämpfe in Echtzeit | Items schmieden & ausrüsten | Animierter Charakter |

---

## 📋 Changelog

### Version 3 (aktuell)
- 11 Tabs: Arena, Held, Schmiede, Dungeon, PVP, Pets, Gilde, Rang, Shop, Forschung, Quests
- Gilde mit Echtzeit-Chat
- 12 Pets mit echten Kampfeffekten (Vergiftung, Heilung, Crit, etc.)
- Dungeon-System mit 50 Etagen
- Supabase Cloud-Speicherung
- Animierter SVG-Held mit farbiger Rüstung

### Version 2
- Zeitalter-System
- Auto-Schmied und Verkaufs-Manager
- Haustiere und Amboss-Upgrades

### Version 1
- Grundlegendes Idle-Kampfsystem
- Schmiede und Inventar

---

## ⚖️ Rechtliche Hinweise

```
Copyright © 2026 Bassprojekt. Alle Rechte vorbehalten.

LIZENZ — PROPRIETÄR / ALLE RECHTE VORBEHALTEN

Dieses Spiel (SwordMaster Idle), einschließlich aller Quelltexte,
Grafiken, Spielmechaniken, Daten, Designs und zugehörigen Materialien,
ist urheberrechtlich geschütztes Eigentum von Bassprojekt.

ES IST AUSDRÜCKLICH VERBOTEN:

  ✗  Das Spiel oder Teile davon zu verkaufen, zu vermieten oder
     anderweitig kommerziell zu verwerten
  ✗  Das Spiel unter anderem Namen oder als eigenes Werk zu veröffentlichen
  ✗  Den Code ohne ausdrückliche schriftliche Genehmigung zu kopieren,
     zu modifizieren oder weiterzuverbreiten
  ✗  Abgeleitete Werke auf Basis dieses Spiels zu erstellen

ERLAUBT (nur mit ausdrücklicher Genehmigung von Bassprojekt):

  ✓  Privates, nicht-kommerzielles Spielen
  ✓  Teilen des offiziellen Spiellinks

Verstöße gegen diese Lizenz werden rechtlich verfolgt.

Anfragen: Kontakt über GitHub Issues oder direkt an Bassprojekt.
```

---

<div align="center">

**⚔️ SwordMaster Idle**  
*Entwickelt mit ❤️ von Bassprojekt*  
© 2026 Bassprojekt — Alle Rechte vorbehalten

</div>
