# 🔄 Décodeur USB pour signaux quadrature d'encodeurs

Carte imprimée compacte servant de **décodeur USB pour signaux quadrature d'encodeurs**, conçue pour lire la **position**, la **vitesse** et le **sens de rotation**, puis transmettre ces données à un PC en temps réel.

## 📋 Description

Fonctionnellement, la carte réceptionne les signaux bruts des encodeurs (**canaux A et B**), les conditionne via des **filtres anti-rebond** et une **isolation galvanique optionnelle** pour les immuniser contre les parasites ou surtensions industrielles.

## 🛠️ Matériel utilisé

| Composant | Rôle |
|---|---|
| **STM32F103T8U6** | Microcontrôleur principal — traitement des signaux de quadrature |
| **FT232RQ** | Convertisseur USB vers UART pour la communication avec le PC |
| **USBLC6-2SC6** | Protection ESD sur la ligne USB |
| **USB4085-GF-A REVA** | Connecteur/protection USB |

## ⚙️ Fonctionnement

1. Réception des signaux de quadrature bruts (canaux **A** et **B**) issus de l'encodeur
2. Conditionnement du signal via **filtres anti-rebond**
3. **Isolation galvanique optionnelle** contre les parasites et surtensions industrielles
4. Décodage de la position, de la vitesse et du sens de rotation par le **STM32F103T8U6**
5. Transmission des données au PC en temps réel via **USB** (grâce au FT232RQ)

## ✨ Points forts

- 🎯 Lecture précise de la position, vitesse et sens de rotation
- 🛡️ Protection contre les parasites et surtensions (isolation galvanique, USBLC6-2SC6)
- 🔌 Communication USB temps réel avec le PC
- 🏭 Conçu pour environnements industriels

## 🖥️ Conception électronique

Toute la conception matérielle (schémas, routage et contrôle d'impédance) a été réalisée sur **Altium Designer**.

### 🧩 Caractéristiques du PCB

| Caractéristique | Détail |
|---|---|
| Gestion d'impédance | ✅ Contrôle d'impédance à **100 Ω** sur les lignes critiques |
| Interface | USB (via FT232RQ) |
| Protection | ESD (USBLC6-2SC6) + isolation galvanique optionnelle |

## 📁 Contenu du dépôt
