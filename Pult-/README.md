# 🎛️ Carte de contrôle pour engins industriels

Carte électronique conçue dans le cadre de mon expérience professionnelle, destinée au **contrôle d'engins industriels lourds**.

## 📋 Description

Cette carte permet de piloter et superviser des engins industriels via une interface embarquée, avec affichage local et communication sans fil longue portée pour le suivi et la transmission de données.

## 🛠️ Matériel utilisé

| Composant | Rôle |
|---|---|
| **ESP32** | Microcontrôleur principal — traitement et connectivité |
| **LoRa** | Transmission de données longue portée, faible consommation |
| **Écran TFT** | Interface d'affichage et de contrôle local |

## 🔗 Communications utilisées

| Protocole | Usage |
|---|---|
| **UART** | Communication série avec périphériques / modules |
| **I2C** | Interfaçage avec capteurs et écran TFT |
| **USB** | Programmation, débogage et alimentation |

## ⚙️ Fonctionnement

1. Acquisition et traitement des données de l'engin industriel via **ESP32**
2. Communication avec les périphériques via **UART** et **I2C**
3. Affichage des informations en temps réel sur l'**écran TFT**
4. Transmission des données à distance via **LoRa**
5. Programmation et débogage de la carte via **USB**
6. Contrôle et supervision du fonctionnement de l'engin

## ✨ Points forts

- 🖥️ Interface locale via écran TFT pour un contrôle direct
- 📡 Communication longue portée grâce au module LoRa
- 🔗 Communications filaires robustes (UART, I2C, USB)
- 🏗️ Conçue pour des environnements industriels exigeants
- ⚙️ Architecture robuste basée sur ESP32

## 🖥️ Conception électronique

Toute la conception matérielle (schémas, routage et contrôle d'impédance) a été réalisée sur **Altium Designer**.

### 🧩 Caractéristiques du PCB

| Caractéristique | Détail |
|---|---|
| Nombre de couches | 2 et 4 couches (selon version) |
| Gestion d'impédance | ✅ Contrôle d'impédance sur pistes critiques |
| Documentation de production | BOM, dessin technique, fichiers Gerber |

## 🚀 Applications possibles

- Contrôle d'engins industriels lourds
- Supervision d'équipements de chantier
- Systèmes de télémétrie industrielle
- Solutions IoT pour environnements robustes

## 📌 Statut du projet

🔧 Projet réalisé dans un cadre professionnel

## 📫 Contact

Pour toute question ou suggestion : houndjetodej@mail.ru
