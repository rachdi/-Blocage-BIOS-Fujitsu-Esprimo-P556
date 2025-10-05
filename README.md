# 🚨 Blocage BIOS Fujitsu Esprimo P556 : la solution signée RBFIBRE Toulouse

![PC-Fujitsu-ESPRIMO-P556](https://github.com/user-attachments/assets/33e57afa-989b-414d-88f1-abfa4d8cdaf3)


## 🔧 Introduction

Chez *RBFIBRE Toulouse, nous avons récemment été appelés pour dépanner un ordinateur **Fujitsu Esprimo P556* totalement bloqué au démarrage.  
L’écran restait figé sur le logo Fujitsu, impossible d’accéder au BIOS, ni de lancer Windows.

Un problème fréquent depuis la mise à jour Windows KB5060533 — et bonne nouvelle, nous avons *trouvé la solution*.

---

## ⚙ Symptômes observés

- Le PC reste bloqué sur le logo Fujitsu dès l’allumage  
- Aucune réaction aux touches F2 ou F12  
- Windows ne se charge plus  
- Parfois, le clavier ou la souris ne sont même plus reconnus  


![blocage-bios-fujitsu-768x488](https://github.com/user-attachments/assets/0d7b78d1-2ab4-4351-a543-9fb675d699b4)

---

## 🧩 La cause : une corruption du BIOS

Le souci provient d’une mise à jour Windows (KB5060533) qui modifie la *base de révocation du Secure Boot (DBX)*.  
Sur certains modèles Fujitsu, cette modification corrompt la mémoire du BIOS (UEFI), rendant la carte mère inutilisable sans restauration manuelle.

Les modèles concernés :
- Fujitsu Esprimo P556  
- Fujitsu E85+  
- Et d’autres équipés de la carte mère *D3400-A11 GS4*

Plusieurs cas similaires ont été recensés en Europe, notamment après la même mise à jour de sécurité.

---

## 🧠 Solution : restauration complète du BIOS

Chez *RBFIBRE, nous avons restauré le BIOS d’un P556 directement depuis notre atelier à **Toulouse*, sans remplacer la carte mère.  
Voici la méthode que nous avons appliquée avec succès :

### Matériel nécessaire :
- Une *clé USB* formatée en *FAT32*  
- Un *autre PC* pour télécharger le BIOS officiel Fujitsu  
- Le fichier BIOS correspondant à la carte mère (ex. D3400-A11 GS4)

### Étapes à suivre :
1. Éteignez complètement l’ordinateur et débranchez l’alimentation.  
2. Ouvrez le boîtier et localisez le *jumper BIOS recovery*.  
3. Déplacez le cavalier vers la position de récupération.  
4. Branchez la clé USB avec le BIOS.  
5. Allumez le PC : la restauration démarre automatiquement.  
6. Après 1 à 2 minutes, replacez le cavalier à sa position d’origine et redémarrez.


![Vue-carte-mere-Fujitsu-Esprimo-P556-768x580](https://github.com/user-attachments/assets/6b61df89-73d9-4133-a69a-054ec031af5d)

---

## ✅ Résultat obtenu

Après la restauration, le Fujitsu Esprimo a redémarré normalement :  
- Accès BIOS rétabli  
- Windows fonctionnel  
- Aucun remplacement matériel nécessaire  

Ce type de réparation est désormais intégré à nos *prestations RBFIBRE* pour les ordinateurs professionnels et particuliers.

---

## 📍 Intervention locale à Toulouse et 50 km autour

*RBFIBRE* intervient dans toute la région toulousaine pour :  
- Restauration de BIOS et UEFI corrompus  
- Diagnostic et réparation d’ordinateurs Fujitsu, HP, Dell…  
- Maintenance, domotique, caméras de surveillance et électricité générale  

---

## 📞 Contact RACHDI BASSEM Toulouse

🧑‍🔧 *Rachdi Bassem – Dépannage informatique et électronique*  
📍 Toulouse et alentours  
📞 07 69 37 63 92  
✉ [rbfibre31@gmail.com](mailto:rbfibre31@gmail.com)  

---

© 2025 RBFIBRE Toulouse – Reproduction interdite.  
Article rédigé par l’équipe RBFIBRE pour informer et assister les utilisateurs victimes du blocage BIOS Fujitsu.
