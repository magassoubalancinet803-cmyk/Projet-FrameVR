# 🦁 Zoo de Lille : Expérience Immersive FrameVR

![FrameVR Badge](https://img.shields.io/badge/Platform-FrameVR-blueviolet?style=for-the-badge)
![Status Badge](https://img.shields.io/badge/Status-En%20Développement-green?style=for-the-badge)
![License Badge](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

Une plateforme de métavers éducative et immersive recréant les écosystèmes du **Zoo de Lille**. Ce projet utilise la réalité virtuelle (VR) pour sensibiliser à la biodiversité à travers une exploration interactive des classes animales.

---

## 📖 À propos du projet

Ce projet transforme l'espace virtuel **FrameVR** en un centre pédagogique dynamique. Chaque zone est conçue pour offrir une immersion sensorielle (visuelle et informative) basée sur les véritables espèces et infrastructures du Zoo de Lille.

### ✨ Fonctionnalités clés
- **Skyboxes Dynamiques** : Panoramas 360° sur mesure (Savane, Arctique, Jungle).
- **Signalétique Interactive** : Affiches promotionnelles et cartes d'identité des espèces intégrées.
- **Classification Pédagogique** : Zones divisées par classes biologiques (Mammifères, Reptiles, Oiseaux, Vie Aquatique).
- **Optimisation Multi-support** : Expérience fluide sur Casques VR (Oculus), Mobiles et Navigateurs PC.

---

## 🗺️ Organisation du Zoo Virtuel

| Secteur | Thématique | Espèces Emblématiques | Caractéristiques |
| :--- | :--- | :--- | :--- |
| **Savane Africaine** | Mammifères | Lions, Girafes, Éléphants | Poils, allaitement, sang chaud |
| **Vivarium** | Reptiles | Crocodiles, Serpents, Iguanes | Écailles, sang froid, ponte d'œufs |
| **Grande Volière** | Oiseaux | Aras, Toucans, Perroquets | Plumes, bec, ailes et vol |
| **Espace Aquatique** | Faune Marine | Manchots, Otaries, Requins | Nageoires, respiration aquatique |

---

## 🚀 Installation & Déploiement

Pour déployer cette expérience dans votre propre espace FrameVR :

### 1. Préparation de l'espace
- Créez une nouvelle scène sur [FrameVR.io](https://framevr.io).
- Choisissez l'environnement de base (ex: "Outdoor Plaza").

### 2. Configuration de l'environnement (Skybox)
1. Allez dans le menu **Environment** > **Background**.
2. Téléchargez l'un des fichiers de l'archive `/assets/skyboxes/` (Ratio 2:1).
3. Réglez la luminosité pour correspondre à l'ambiance de la zone.

### 3. Importation des Assets 2D
- Utilisez le bouton **Add Asset** pour importer les **Cartes de Classe** et les **Affiches**.
- **Placement** : Positionnez les cartes à l'entrée de chaque enclos virtuel pour servir de guide pédagogique.

---

## 🛠️ Spécifications Techniques

- **Format des images** : JPEG (compressé) / PNG-24.
- **Résolution Skybox** : 4096 x 2048 px (Equirectangulaire).
- **Format Cartes/Affiches** : 1080 x 1920 px (Portrait) ou 1920 x 108
