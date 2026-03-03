# 🌐 SAE 201 & 204 : Construction d'un Réseau d'Entreprise

![Static Badge](https://img.shields.io/badge/BUT-R%26T-blue)
![Static Badge](https://img.shields.io/badge/Projet-Acad%C3%A9mique-green)
![Static Badge](https://img.shields.io/badge/Cisco-L2%20%2F%20L3-orange)

## 📋 Présentation du Projet
Ce projet, réalisé dans le cadre du BUT Réseaux & Télécoms à l'**IUT de Saint-Malo**, consiste à concevoir et déployer l'infrastructure réseau complète d'une petite entreprise multisite.

L'objectif est de répondre aux besoins de **commutation**, de **routage**, de **services réseaux** et de **sécurité** pour assurer le bon fonctionnement d'une structure professionnelle sur une période de deux semaines.

## 🚀 Objectifs Techniques

### 🏗️ Architecture & Réseau
* **Segmentation (VLANs) :** Mise en place de VLANs (Admin, Data, Interconnexion) pour isoler les flux.
* **Commutation :** Configuration de liens Trunks (802.1Q) et gestion du **Spanning Tree (STP)** pour la redondance.
* **Routage :** Activation du routage inter-VLAN sur switch de niveau 3 et configuration d'un accès Internet via **NAT/PAT**.

### 🛠️ Services Déployés
* **DHCP :** Distribution automatique des configurations IP.
* **DNS :** Mise en place d'un serveur DNS relais.
* **Web :** Serveur Apache (HTTP/HTTPS) avec pages personnalisées.
* **Gestion Windows :** Partages de fichiers, gestion des utilisateurs/groupes et impression réseau.
* **Maintenance :** Sauvegarde et restauration des configurations via serveur TFTP.

### 🛡️ Sécurité & Analyse
* Utilisation d'une VM **Kali Linux** pour tester la robustesse de l'infrastructure.
* Simulation d'attaques (spanning-tree, saturation de table MAC) et mise en place de contre-mesures.
* Sécurisation des accès selon les recommandations de l'ANSSI.

## 💻 Environnement Technologique
| Matériel | Systèmes d'Exploitation | Protocoles & Outils |
| :--- | :--- | :--- |
| **Switchs Cisco** (3560 L3, 2960 L2) | **Debian** (Serveurs) | IPv4, STP, NAT, PAT |
| **Routeurs Cisco** | **Windows 10** (Clients) | DNS, DHCP, HTTP/S, SSH |
| **Baies de brassage** | **Kali Linux** (Pentest) | VirtualBox, Wireshark |

## 📁 Structure du Dépôt
* `/Rapports` : Documentation technique et bilans de gestion de projet.
* `/Config` : Extraits des configurations des équipements (Cisco, Linux).

---
*Projet réalisé en équipe de 3 personnes au département R&T de Saint-Malo.*
