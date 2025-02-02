# AugmentForecast

### **Présentation du Projet**<br>
AugmentForecast est un projet visant à améliorer la précision des modèles de prévision de séries temporelles grâce à des techniques avancées de data augmentation.
L'objectif est de tester différentes approches pour enrichir les données et renforcer la robustesse des modèles, notamment dans un contexte de prévision des prix de l'énergie.

### **Méthodes Explorées**<br>
Nous avons étudié plusieurs méthodes de data augmentation, allant des techniques classiques aux modèles basés sur l'intelligence artificielle :

### **Techniques Basiques** <br>
✔️ Jittering (ajout de bruit gaussien)<br>
✔️ Time Warping (déformation temporelle)<br>
✔️ Window Slicing (découpage de sous-séries)<br>

### **Techniques Avancées**<br>
✔️ TimeGAN  (Un modèle génératif basé sur un GAN pour produire des séries temporelles synthétiques tout en conservant la dynamique du signal)<br>


### 📂**Dossier advanced_techniques**<br>
Ce dossier contient les expérimentations et implémentations de TimeGAN pour générer des séries temporelles synthétiques.

### **Environnement Virtuel TimeGAN**<br>
TimeGAN requiert des versions spécifiques de Python et TensorFlow qui peuvent être en conflit avec d'autres packages utilisés dans le projet.
Pour éviter ces conflits, un environnement virtuel distinct est utilisé, justifiant l'arborescence du projet.

 ### **Configuration de l'environnement Conda pour TimeGAN** <br>
Créer un environnement virtuel dédié :<br>

Installer les dépendances spécifiques (creer un environnement virtuel pour éviter les conflits de versions de frameworks):<br>

!!! Besoin de python 3.7!!!<br>

```bash
cd advancedTechnics
pip install -r requirement.txt
```
<br>

Vous trouverez les résultats de nos expérimentations dans le rapport : **Rapport_AugmentForecast.pdf**

