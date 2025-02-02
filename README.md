# AugmentForecast

🔍 Présentation du Projet
AugmentForecast est un projet visant à améliorer la précision des modèles de prévision de séries temporelles grâce à des techniques avancées de data augmentation.
L'objectif est de tester différentes approches pour enrichir les données et renforcer la robustesse des modèles, notamment dans un contexte de prévision des prix de l'énergie.

🚀 Méthodes Explorées
Nous avons étudié plusieurs méthodes de data augmentation, allant des techniques classiques aux modèles basés sur l'intelligence artificielle :

📌 Techniques Basiques
✔️ Jittering (ajout de bruit gaussien)
✔️ Time Warping (déformation temporelle)
✔️ Window Slicing (découpage de sous-séries)

📌 Techniques Avancées
✔️ TimeGAN  (Un modèle génératif basé sur un GAN pour produire des séries temporelles synthétiques tout en conservant la dynamique du signal)


📂 Dossier advanced_techniques
Ce dossier contient les expérimentations et implémentations de TimeGAN pour générer des séries temporelles synthétiques.

⚙️ Environnement Virtuel TimeGAN
TimeGAN requiert des versions spécifiques de Python et TensorFlow qui peuvent être en conflit avec d'autres packages utilisés dans le projet.
Pour éviter ces conflits, un environnement virtuel distinct est utilisé, justifiant l'arborescence du projet.

📌 Configuration de l'environnement Conda pour TimeGAN
Créer un environnement virtuel dédié :

Installer les dépendances spécifiques (creer un environnement virtuel pour éviter les conflits de versions de frameworks):

!!! Besoin de python 3.7

```bash
cd advancedTechnics
pip install -r requirement.txt
```


Vous trouverez les résultats de nos expérimentations dans le rapport : Rapport_Augment_Forecast.docx

