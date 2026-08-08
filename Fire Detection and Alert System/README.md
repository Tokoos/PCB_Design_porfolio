# 🔥 Système de détection et d'alerte incendie

Un système intelligent et autonome de détection et d'alerte incendie conçu pour **réduire les fausses alertes** et **accélérer l'intervention des sapeurs-pompiers**.

## 📋 Description

Grâce à plusieurs étapes de vérification par les propriétaires, la plateforme transmet automatiquement une alerte fiable accompagnée des **coordonnées GPS exactes** du lieu concerné.

Cette solution vise à :
- ⏱️ Faire gagner un temps précieux aux secours
- 🎯 Améliorer la précision des interventions
- 🏠 Renforcer la sécurité des habitations, entreprises et institutions

Particulièrement pensée pour l'**Afrique**, où chaque minute peut sauver des vies.

## 🛠️ Matériel utilisé

| Composant | Rôle |
|---|---|
| **Seeed Studio ESP32** | Microcontrôleur principal, traitement et connectivité |
| **LoRa (module 02)** | Transmission longue portée, faible consommation |
| **MQ2** | Capteur de gaz / fumée pour la détection incendie |
| **GPS** | Localisation précise du lieu concerné |

## ⚙️ Fonctionnement

1. Le capteur **MQ2** détecte une concentration anormale de fumée ou de gaz
2. Le système déclenche une **phase de vérification** auprès du propriétaire (pour limiter les fausses alertes)
3. Si l'incendie est confirmé, une **alerte** est transmise via **LoRa**
4. Les **coordonnées GPS** exactes sont jointes à l'alerte
5. Les sapeurs-pompiers reçoivent une notification fiable et localisée

## ✨ Points forts

- 🔋 Autonome et basse consommation (LoRa + ESP32)
- ✅ Réduction des fausses alertes grâce à la vérification multi-étapes
- 📍 Localisation GPS précise incluse dans chaque alerte
- 🌍 Solution adaptée aux contextes à infrastructure limitée

## 🖥️ Conception électronique

Toute la conception matérielle (schémas et PCB) a été réalisée sur **Altium Designer**.

### 🧩 Caractéristiques du PCB

| Caractéristique | Détail |
|---|---|
| Nombre de couches | 2 couches |
| Gestion d'impédance | ✅ Contrôle d'impédance sur pistes critiques |
| Module GPS | Intégré directement sur la carte |

**Points techniques :**
- Calcul et respect de l'impédance caractéristique des pistes (adaptée à la fréquence du module GPS)
- Placement optimisé du module GPS pour limiter les interférences
- Plan de masse dédié pour améliorer la qualité du signal
- Routage 2 couches optimisé pour un compromis coût/performance

## 📁 Contenu du dépôt
