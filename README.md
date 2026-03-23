# VLANS_Router-on-a-stick_static-routing_ssh_VLSM_Lab

## 🇬🇧 English Version

### Description

This project simulates a **school network infrastructure** using core networking concepts from CCNA:

* VLAN segmentation
* Router-on-a-Stick
* VLSM subnetting
* Static routing
* SSH secure access

---

### Network Features

* Inter-VLAN routing using Router-on-a-Stick
* VLAN segmentation (Staff, CCTV, Laboratory, Management)
* VLSM-based IP addressing
* Static routing to Internet network
* Secure remote access via SSH
* Basic network security configurations

---

### Devices Used

* 1 Router (R1)
* 1 Internet Router
* 3 Switches (S1, S2, S3)
* End devices (PCs, CCTV cameras, IoT server)

---

### IP Addressing Overview

* Local Network: `192.168.1.0/24` (VLSM)
* Internet Network: `5.0.0.0/24`

---

### VLAN Structure

| VLAN | Name       | Network          |
| ---- | ---------- | ---------------- |
| 10   | Staff      | 192.168.1.160/27 |
| 20   | CCTV       | 192.168.1.128/27 |
| 30   | Laboratory | 192.168.1.0/25   |
| 99   | Management | 192.168.1.192/29 |

---

### Configuration Highlights

* Static default route configured on R1
* SSH enabled on all network devices
* Password encryption and security policies applied
* Management VLAN for switches

---

### Testing

* Ping the Internet server from any PC
* Access the IoT server via web browser
* SSH into routers and switches
* Analyze network behavior through topology

---

### Topologies

Physical Topology: *(Add your image here)*
Logical Topology: *(Add your image here)*

---

## 🇫🇷 Version Française

### Description

Ce projet simule une **infrastructure réseau scolaire** en utilisant des concepts fondamentaux du CCNA :

* Segmentation VLAN
* Router-on-a-Stick
* Subnetting VLSM
* Routage statique
* Accès sécurisé via SSH

---

### Fonctionnalités du réseau

* Routage inter-VLAN avec Router-on-a-Stick
* Segmentation réseau (Staff, CCTV, Laboratoire, Management)
* Plan d’adressage IP basé sur VLSM
* Routage statique vers Internet
* Accès distant sécurisé avec SSH
* Configuration de sécurité de base

---

### Équipements utilisés

* 1 Routeur (R1)
* 1 Routeur Internet
* 3 Switches (S1, S2, S3)
* Équipements terminaux (PC, caméras CCTV, serveur IoT)

---

### Plan d’adressage IP

* Réseau local : `192.168.1.0/24` (VLSM)
* Réseau Internet : `5.0.0.0/24`

---

### Structure des VLANs

| VLAN | Nom         | Réseau           |
| ---- | ----------- | ---------------- |
| 10   | Staff       | 192.168.1.160/27 |
| 20   | CCTV        | 192.168.1.128/27 |
| 30   | Laboratoire | 192.168.1.0/25   |
| 99   | Management  | 192.168.1.192/29 |

---

### Points clés de configuration

* Route par défaut configurée sur R1
* SSH activé sur tous les équipements
* Chiffrement des mots de passe
* VLAN de management pour les switches

---

### Tests

* Ping du serveur Internet depuis un PC
* Accès au serveur IoT via navigateur web
* Connexion SSH aux équipements réseau
* Analyse du comportement via les topologies

---

### 🗺️ Topologies

Topologie Physique : *(Ajoute ton image ici)*
Topologie Logique : *(Ajoute ton image ici)*

---

### Author

Yannick Dunia
