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
| 🟡 | **1% - 3%** | Utilisation safe, très faible risque |
| 🔴 | **50% +** | Risque élevé de détection |
| ❓ | **Inconnu** | Non testé sur ce serveur |

---

## 🛠️ Liste des Modules

### 🏃 Mouvement & Visuel

| Module | Description | Détection |
| :--- | :--- | :--- |
| **Sprint** | Sprint automatique. | **All:** 🟢 |
| **Fullbright** | Vision nocturne (client-side). | **All:** 🟢 |
| **ESP** | Affiche les joueurs et leur vie à travers les murs. | **All:** 🟢 |
| **TeleportWarn** | Alerte en cas de téléportation suspecte (Beta). | **All:** 🟢 |

---

### ⚔️ Combat & Assistance

| Module | Description | Détection |
| :--- | :--- | :--- |
| **AimAssist** | Assistance de visée vers l’adversaire. | **All:** 🟢 |
| **TriggerBot** | Attaque automatique lorsque le curseur est sur l’ennemi (gestion des crits). | **PVPClub:** 🟡 / **MMC**: 🔴|
| **NoMiss** | Annule l’attaque si le coup va être raté. | **All:** 🟢 |
| **ShieldDisabler** | Désactive le bouclier adverse (fonctionne aussi à travers les murs). | **PvPClub:** 🟡 / **MMC:** 🔴 |
| **AutoThrowPot** | Lance automatiquement des potions selon la situation (heal, etc.). | **PvPClub:** 🟡 / **MMC:** ❓ / **Stray:** 🟡 |

> ⚠️ **Note – ShieldDisabler :** effectuer une rotation à 360° augmente fortement la détection (jusqu’à ~70%).

---

### 🎒 Gestion d’Inventaire

| Module | Description | Détection |
| :--- | :--- | :--- |
| **AutoInvTotem** | Place un totem en offhand à l’ouverture de l’inventaire. | **PvPClub:** 🟡 / **MMC:** ❓ |
| **HoverTotem** | Place un totem en offhand au survol de la souris. | **All:** 🟡 |
| **AutoDoubleHand** | Switch automatiquement sur un totem en hotbar après un pop. | **All:** 🟡 |
| **AutoHotbarRefill** | Remplit la hotbar en potions (inventaire ouvert). | **All:** 🟢 |
| **FastEXP** | Auto-clicker optimisé pour les fioles d’XP. | **All:** 🟢 |
| **AutoHitCrystal** | Attaque automatique des cristaux. | **PvPClub:** 🟡 / **MMC:** ❓ |

---

## ⚙️ Configurations Recommandées

### AimAssist — Configuration Optimisée

- **Hostile:** `OFF`
- **Murs:** `OFF`
- **Weapon:** `ON`
- **Horizontal (Hoz):** `ON`
- **Vertical (Ver):** `OFF`
- **Speed:** `10`
- **FOV:** `90`

> La majorité des modules nécessitent une configuration adaptée à votre serveur et à votre style de jeu, notamment :
- **HoverTotem**
- **AutoDoubleHand**
- **ESP**
- **AutoThrowPot**

---

## 🏗️ En cours de développement

- **Anchor Macro**
- **AutoDrain** & **AutoWindPearl** *(correctifs en cours)*
- **Nouveaux modules visuels**
- **Auto Mace**

---

## 💡 À Savoir

> **Important :**  
> Certains modules comme **AutoThrowPot** ou **AutoWindPearl** nécessitent l’attribution d’une touche.  
> Cette touche ne sert **pas** à activer/désactiver le module, mais à **déclencher l’action instantanément**.

> **Important :**  
> Les modules suivants ne sont **pas encore fonctionnels** :
> - **AutoWindPearl**

---

© SepactClient 2026 — All Rights Reserved
