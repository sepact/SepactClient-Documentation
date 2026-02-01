# 🌌 SepactClient Documentation
> **Note :** Le client se met à jour automatiquement. 🔄

Bienvenue sur la documentation officielle de **SepactClient**. Vous trouverez ici la liste des modules, leurs fonctionnalités et l'indice de risque vis-à-vis des anti-cheats.
Ainsi que comment utiliser le client.
Le SepactClient (toujours en attente d'un vrai nom) est un Client Injectable pour fabric 1.21.8
Ce Client utilise l'api de fabric donc il est malheuresement necessaire d'etre en fabric et d'avoir fabric api sur son jeu

Au niveau de l'injection sa reste comme les autre Injecteur (vape, prestige etc)
Lancer votre jeu, rejoigner un Monde et lancer l'exe

> **Important :** L'injecteur peut etre détecter par certain anti virus pour des raison "suspect"
> Mais cela n'est pas un virus ! il est simplement detecter car il telecharge et ensuite inject des dll dans le jeu
---

## 🛡️ Légende de Détection
| Icône | Risque de Ban | Description |
| :---: | :--- | :--- |
| 🟢 | **0%** | Indétectable (Safe) |
| 🟡 | **1% - 3%** | Utilisation Safe mais très peu de chance de ban |
| 🔴 | **50% +** | Risque élevé de détection |
| ❓ | **Inconnu** | Non testé sur ce serveur |

---

## 🛠️ Liste des Modules

### 🏃 Mouvement & Visuel
| Module | Description | Détection |
| :--- | :--- | :--- |
| **Sprint** | Sprint automatique. | **All:** 🟢 |
| **Fullbright** | Vision nocturne (Client-side). | **All:** 🟢 |
| **ESP** | Voir les joueurs et leur vie à travers les murs. | **All:** 🟢 |
| **TeleportWarn** | Alerte en cas de téléportation suspecte (Beta). | **All:** 🟢 |

### ⚔️ Combat & Assistance
| Module | Description | Détection |
| :--- | :--- | :--- |
| **AimAssist** | Aide à la visée vers l'adversaire. | **All:** 🟢 |
| **TriggerBot** | Frappe auto quand le curseur est sur l'ennemi (gère les Crit). | **All:** 🟡 |
| **NoMiss** | Annule l'attaque si vous allez frapper dans le vide. | **All:** 🟢 |
| **ShieldDisabler** | Désactive le bouclier adverse (même à travers les murs donc attention). | **PvPClub:** 🟡 / **MMC:** 🔴 |

> ⚠️ **Note sur ShieldDisabler :** Faire un 360° augmente drastiquement la détection (jusqu'à 70%).

### 🎒 Gestion d'Inventaire
| Module | Description | Détection |
| :--- | :--- | :--- |
| **AutoInvTotem** | Place un totem dans la offhand dès l'ouverture de l'inventaire. | **PvPClub:** 🟡 / **MMC:** ❓ |
| **HoverTotem** | Place un totem dans la offhand au survol de la souris. | **All:** 🟡 |
| **AutoDoubleHand** | Switch auto sur le totem en hotbar après un pop. | **All:** 🟡 |
| **AutoHotbarRefill** | Remplit votre hotbar de potions (Inventaire ouvert). | **All:** 🟢 |
| **FastEXP** | Auto-clicker optimisé pour les fioles d'XP. | **All:** 🟢 |
| **AutoHitCristal** | Attaque automatique des cristaux. | **PvPClub:** 🟡 / **MMC:** ❓ |

---

## ⚙️ Configurations Recommandées

### **AimAssist (Optimisé)**
* **Hostile:** `OFF`
* **Murs:** `OFF`
* **Weapon:** `ON`
* **Hoz:** `ON`
* **Ver:** `OFF`
* **Speed:** `10`
* **FOV:** `90`

---

## 🏗️ En cours de développement (Upcoming)
*  **Anchor Macro**
*  **AutoDrain** & 🌪️ **AutoWindPerle** (Correctifs en cours)
*  **Nouveaux modules visuels**
* **Auto Mace**

---

## 💡 À Savoir
> [!IMPORTANT]
> Certains modules comme **AutoThrowPot** ou **AutoWindPerle** nécessitent l'attribution d'une touche. 
> **Attention :** La touche ne sert pas à activer/désactiver le module, mais à déclencher l'action immédiatement. Pour faire marcher **AutoThrowPot**, activez le module, choisissez une touche et c'est prêt.

> [!IMPORTANT]
> Les Modules Suivant ne Marche pas (pas pour l'instant)
> **AutoWindPerle**
---
@ SepactClient 2026 - Copyright
All Rights Reserved
