# 🖼️ Set-Wallpaper.ps1 - Script PowerShell pour configurer le fond d'écran via GPO

**Set-Wallpaper.ps1** est un script PowerShell conçu pour configurer automatiquement un fond d'écran sur des postes Windows. Il est compatible avec les stratégies de groupe (GPO) et peut être utilisé dans un environnement d'entreprise pour appliquer une image de fond spécifique à plusieurs utilisateurs ou ordinateurs.

![Logo](https://o2cloud.fr/logo/o2Cloud.png)

## ✨ Fonctionnalités

- 🖌️ **Configuration automatique du fond d'écran** à partir d'un chemin réseau spécifié
- 🔄 **Application automatique des modifications** via la commande `RUNDLL32.EXE`
- 🔧 **Intégration avec GPO** pour une application centralisée
- 🔍 **Vérification préalable du chemin réseau** avant la configuration
- 📦 **Script autonome** - aucune dépendance externe requise

## 📋 Pré-requis

- 💻 Windows PowerShell (version 5.1 ou ultérieure)
- 🌐 Accès réseau au chemin contenant l'image du fond d'écran
- 🔑 Droits d'accès suffisants pour modifier les paramètres de registre utilisateur

## 🚀 Utilisation

1. Téléchargez ou clonez ce dépôt :
   ```bash
   git clone https://github.com/o2Cloud-fr/Set-Wallpaper.git
   ```

2. Placez l'image du fond d'écran dans le répertoire réseau accessible par tous les utilisateurs ou ordinateurs cibles :
   ```bash
   \\SWRep\Screen
   ```

3. Exécutez le script PowerShell pour appliquer le fond d'écran :
   ```powershell
   powershell -ExecutionPolicy Bypass -File Set-Wallpaper.ps1
   ```

## 👨‍💻 Auteurs

- [@MyAlien](https://www.github.com/MyAlien)
- [@o2Cloud](https://www.github.com/o2Cloud-fr)

## 🔖 Badges

[![Apache License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/o2Cloud-fr/Set-Wallpaper/blob/main/LICENSE)
[![Windows](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows)](https://github.com/o2Cloud-fr/Set-Wallpaper)
[![PowerShell](https://img.shields.io/badge/Language-PowerShell-5391FE?logo=powershell)](https://github.com/o2Cloud-fr/Set-Wallpaper)
[![o2Cloud](https://img.shields.io/badge/Powered%20by-o2Cloud-orange.svg)](https://o2cloud.fr/)

## 🤝 Contribution

Les contributions sont toujours les bienvenues !

Consultez le fichier `contributing.md` pour découvrir comment contribuer à ce projet.
Veuillez respecter le `code of conduct` du projet.

## 💬 Feedback

Si vous avez des commentaires ou des suggestions, n'hésitez pas à nous contacter à github@o2cloud.fr

## 🔗 Liens

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://vcard.o2cloud.fr/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/remi-simier-2b30142a1/)

## 🛠️ Compétences

- PowerShell
- Stratégies de groupe Windows (GPO)
- Scripting Windows

## 📝 Licence

[Apache-2.0 license](https://github.com/o2Cloud-fr/Set-Wallpaper/blob/main/LICENSE)

## 🔄 Projets connexes

Voici quelques projets similaires ou complémentaires :
- [GitHub o2Cloud](https://github.com/o2Cloud-fr?tab=repositories)
- [Awesome README](https://github.com/o2Cloud-fr/Set-Wallpaper/blob/main/README.md)

## 🗺️ Feuille de route

- 🎨 Support pour différents modes d'affichage (mosaïque, étirement, centré)
- 📅 Rotation automatique des fonds d'écran selon un calendrier
- 📱 Support pour les configurations multi-écrans
- 👥 Personnalisation par groupe d'utilisateurs ou département
- 📊 Journalisation du déploiement pour l'audit

## 🆘 Support

Pour obtenir de l'aide, envoyez un e-mail à github@o2cloud.fr

## 💼 Utilisé par

Ce projet est utilisé par les entreprises suivantes :
- o2Cloud
- MyAlienTech
