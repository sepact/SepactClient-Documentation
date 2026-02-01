## 📘 Documentation officielle — SepactClient

Bienvenue sur la documentation officielle de **SepactClient**.  
Vous trouverez ici :
- la liste des modules
- leurs fonctionnalités
- leur indice de risque vis-à-vis des anti-cheats
- ainsi qu’un guide d’utilisation du client

---

### 🔧 Présentation

**SepactClient** *(nom provisoire)* est un **client injectable** pour **Minecraft Fabric 1.21.8**.

Le client utilise l’**API Fabric**, il est donc **obligatoire** :
- d’utiliser **Fabric**
- d’avoir **Fabric API** installé

---

### 💉 Injection

L’injection fonctionne de la même manière que la plupart des injecteurs  
*(Vape, Prestige, etc.)* :

1. Lancez Minecraft  
2. Rejoignez un monde  
3. Lancez l’injecteur (`.exe`)

---

### ⚠️ Important

> **Attention :** l’injecteur peut être détecté par certains antivirus.

Cela est **normal** :
- le programme télécharge des fichiers
- puis injecte des DLL dans le jeu  

❌ Ce n’est **pas un virus**  
✅ C’est simplement lié au fonctionnement de l’injection
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
| **AutoThrowPot**  | Lance automatiquement des potion lorsque vous en avez besoin (force heal etc) | **PvPClub** 🟡 / **MMC** ❓/ **Stray** 🟡 |

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

### Je ne vais pas tous citer mais tout ces modules ont besoin de configuration
* **HoverTotem**
* **AutoDoubleHand**
* **ESP**
*  **AutoThrowPot**
*  

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
> Les Modules Suivant ne Marche pas (pas pour l'instant).
>* **AutoWindPerle**
---
@ SepactClient 2026 - Copyright
All Rights Reserved
