![Logo IUS](image.png)
# Faculté des sciences et des technologies  
**ANNEE UNIVERSITAIRE 2023-2024**

## LICENCE 3 – Sciences Informatiques  
### Réseaux 2  
**Soumis au chargé de cours :** Ismaël SAINT AMOUR  
**Préparé par :** Jameson DOMINIQUE  
**Date :** 01 Avril 2025  


---

# Introduction à GNS3 et Configuration d’un Réseau de Base  
## TD 2  

### Objectif :  
Découvrir comment installer et intégrer GNS3 avec VMware Workstation Pro pour utiliser une machine virtuelle comme serveur dans un environnement de simulation réseau.
- Installer et configurer GNS3 sur votre machine.  
- Installer VMware Workstation Pro et créer une machine virtuelle qui jouera le rôle de serveur.  
- Importer la VMware Workstation Pro dans GNS3 et l'intégrer dans une topologie réseau simulée.  
- Découvrir l'outil GNS3 pour la simulation de réseaux.  

### Matériel Requis :  
- **GNS3 installé** (téléchargement depuis [gns3.com](https://www.gns3.com)).  
- **Images IOS Cisco** (ex : Cisco 7200, Cisco 3725).  
- **VMware Workstation Pro** (optionnel).  
- Un PC ou VM sous Linux/Windows pour simuler des hôtes.  

---

## 1. Installation de GNS3 et Importation dans VMware Workstation Pro  

### 1.1 Importation de l'appareil dans VMware Workstation Pro :  
1. Ouvrez VMware Workstation Pro.  
2. Cliquez sur **Fichier → Importer un appareil virtuel**.  
3. Sélectionnez le fichier `.ova` ou `.ovf` téléchargé.  
4. Suivez les instructions à l'écran.  

![image1](<Screenshot (1).png>)
 ![alt text](<Screenshot (2).png>) ![alt text](<Screenshot (3).png>) ![alt text](<Screenshot (4).png>) ![alt text](<Screenshot (5).png>) ![alt text](<Screenshot (6).png>) ![alt text](<Screenshot (7).png>) ![alt text](<Screenshot (8).png>) ![alt text](<Screenshot (9).png>) ![alt text](<Screenshot (10).png>) ![alt text](<Screenshot (11).png>) ![alt text](<Screenshot (12).png>) ![alt text](<Screenshot (13).png>) ![alt text](<Screenshot (14).png>) ![alt text](<Screenshot (15).png>) ![alt text](<Screenshot (16).png>) ![alt text](<Screenshot (17).png>) ![alt text](<Screenshot (18).png>) ![alt text](<Screenshot (19).png>) ![alt text](<Screenshot (20).png>) ![alt text](<Screenshot (21).png>) ![alt text](<Screenshot (22).png>) ![alt text](<Screenshot (23).png>) ![alt text](<Screenshot (24).png>) ![alt text](<Screenshot (25).png>) ![alt text](<Screenshot (26).png>) ![alt text](<Screenshot (27).png>) ![alt text](<Screenshot (28).png>) ![alt text](<Screenshot (29).png>) ![alt text](<Screenshot (30).png>) ![alt text](<Screenshot (31).png>) ![alt text](<Screenshot (32).png>) ![alt text](<Screenshot (33).png>) ![alt text](<Screenshot (34).png>) ![alt text](<Screenshot (35).png>) ![alt text](<Screenshot (36).png>) ![alt text](<Screenshot (37).png>)
---

## 2. Ajouter les images IOS Cisco (ex : Cisco 7200, Cisco 3725)  

### Étapes :  
1. Dans GNS3, accédez à **Settings → Appliances**.  
2. Cliquez sur **Install appliance** et sélectionnez l'image Cisco souhaitée.  
3. Configurez les paramètres de l'appliance (mémoire, interfaces).  

  ![alt text](<Screenshot (38).png>) ![alt text](<Screenshot (39).png>) ![alt text](<Screenshot (40).png>) ![alt text](<Screenshot (41).png>) ![alt text](<Screenshot (42).png>) ![alt text](<Screenshot (43).png>) ![alt text](<Screenshot (44).png>) ![alt text](<Screenshot (45).png>) ![alt text](<Screenshot (46).png>) ![alt text](<Screenshot (47).png>) ![alt text](<Screenshot (48).png>) ![alt text](<Screenshot (49).png>) ![alt text](<Screenshot (50).png>) ![alt text](<Screenshot (51).png>) ![alt text](<Screenshot (52).png>) ![alt text](<Screenshot (53).png>) ![alt text](<Screenshot (54).png>) ![alt text](<Screenshot (55).png>) ![alt text](<Screenshot (56).png>) ![alt text](<Screenshot (57).png>) ![alt text](<Screenshot (58).png>) ![alt text](<Screenshot (59).png>)

---

## 3. Configuration de la Topologie Réseau  

### Exemple de topologie :  
- **Routeurs :** Cisco 3725, Cisco 7200.  
- **PC virtuels :** VPCS (Virtual PC Simulator).  
- **Connexions :** Switchs Ethernet, Cloud.  

 ![alt text](<Screenshot (60).png>) ![alt text](<Screenshot (61).png>) ![alt text](<Screenshot (62).png>) ![alt text](<Screenshot (63).png>) ![alt text](<Screenshot (64).png>) ![alt text](<Screenshot (65).png>) ![alt text](<Screenshot (66).png>) ![alt text](<Screenshot (67).png>) ![alt text](<Screenshot (68).png>) ![alt text](<Screenshot (69).png>) ![alt text](<Screenshot (70).png>) ![alt text](<Screenshot (71).png>) ![alt text](<Screenshot (72).png>) ![alt text](<Screenshot (73).png>) ![alt text](<Screenshot (74).png>) ![alt text](<Screenshot (75).png>) ![alt text](<Screenshot (76).png>)

---

## 4. Conclusion  
Ce laboratoire a permis de :  
- Maîtriser l'installation de GNS3 et VMware.  
- Configurer des appliances Cisco (routeurs 7200/3725).  
- Simuler une topologie réseau avec des PC virtuels.  

En conclusion, ce laboratoire pratique sur l'installation et la configuration de GNS3 dans VMware Workstation Pro nous a permis d'acquérir une compréhension approfondie des outils de simulation de réseau et de leur application dans un environnement virtuel. Grâce à l'ajout des images IOS Cisco, nous avons pu simuler des routeurs variés tels que le Cisco 7200 et le Cisco 3725, ainsi que configurer les PC associés pour reproduire une topologie réseau. 

En somme, l'apprentissage pratique est essentiel pour maîtriser les concepts théoriques et les appliquer efficacement dans des situations réelles.

