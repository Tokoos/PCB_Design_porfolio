# 📡 Carte de détection d'objets par radar

Carte électronique conçue dans le cadre de mon expérience professionnelle, destinée à la **détection d'objets** via un module radar.

## 📋 Description

Cette carte permet de détecter la présence, la distance et/ou le mouvement d'objets à l'aide d'un capteur radar, avec traitement embarqué des données via un microcontrôleur ESP32.

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
| Documentation de production | BOM, plan d'assemblage, fichiers Gerber |

## 🚀 Applications possibles

- Détection d'objets ou d'obstacles
- Systèmes de sécurité industrielle
- Comptage ou suivi de présence
- Automatisation et supervision d'équipements

## 📌 Statut du projet

🔧 Projet réalisé dans un cadre professionnel

## 📫 Contact

Pour toute question ou suggestion : houndjetodej2@mail.com
