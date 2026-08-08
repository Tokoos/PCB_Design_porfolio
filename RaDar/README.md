# 📡 RADAR — Carte de détection d'objets

Carte électronique conçue pour **FS Technologies**, destinée à la **détection d'objets** via un module radar.

## 📋 Description

La carte **RADAR** permet de détecter la présence, la distance et/ou le mouvement d'objets à l'aide d'un capteur radar, avec traitement embarqué des données via un microcontrôleur ESP32.

## 🛠️ Matériel utilisé

| Composant | Rôle |
|---|---|
| **ESP32** | Microcontrôleur principal — traitement et connectivité |
| **Module Radar** | Détection de présence, distance et/ou mouvement d'objets |

## 🔗 Communications utilisées

| Protocole | Usage |
|---|---|
| **UART** | Communication série entre le module radar et l'ESP32 |

## ⚙️ Fonctionnement

1. Le module radar émet un signal et détecte les objets à proximité
2. Les données brutes sont transmises à l'**ESP32** via **UART**
3. Traitement des données par l'ESP32 (distance, présence, mouvement)
4. Exploitation des résultats pour l'application cible (alerte, comptage, sécurité, etc.)

## ✨ Points forts

- 🎯 Détection fiable d'objets à distance
- 🔗 Communication simple et robuste via UART
- ⚙️ Architecture compacte basée sur ESP32
- 🏭 Adaptée aux applications industrielles

## 🖥️ Conception électronique

Toute la conception matérielle (schémas et routage) a été réalisée sur **Altium Designer**.

### 🧩 Caractéristiques du PCB

| Caractéristique | Détail |
|---|---|
| Nombre de couches | 2 couches |

## 📦 Dossier de production

- 📋 **BOM** (Bill of Materials)
- 📐 **Plan d'assemblage**
- 🏭 **Fichiers Gerber**

## 📁 Contenu du dépôt
