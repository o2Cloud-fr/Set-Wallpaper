# Set-Wallpaper.ps1 - Script PowerShell pour configurer le fond d'écran via GPO

**Set-Wallpaper.ps1** est un script PowerShell conçu pour configurer automatiquement un fond d'écran sur des postes Windows. Il est compatible avec les stratégies de groupe (GPO) et peut être utilisé dans un environnement d'entreprise pour appliquer une image de fond spécifique à plusieurs utilisateurs ou ordinateurs.

## Fonctionnalités

- Définit le fond d'écran à partir d'un chemin réseau spécifié.
- Applique automatiquement les modifications via la commande `RUNDLL32.EXE`.
- Facilement intégrable aux GPO pour une application centralisée.
- Vérifie si le chemin réseau existe avant de procéder à la configuration.
- Script entièrement autonome : aucune dépendance externe requise.

## Pré-requis

- Windows PowerShell (version 5.1 ou ultérieure).
- Accès réseau au chemin contenant l'image du fond d'écran.
- Droits d'accès suffisants pour modifier les paramètres de registre utilisateur.

## Utilisation

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

## Authors

- [@MyAlien](https://www.github.com/MyAlien)
- [@o2Cloud](https://www.github.com/o2Cloud-fr )

## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-o2Cloud-yellow.svg)]()


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Feedback

If you have any feedback, please reach out to us at github@o2cloud.fr


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://vcard.o2cloud.fr/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/remi-simier-2b30142a1/)


## 🛠 Skills
C#


## License

[Apache-2.0 license](https://github.com/o2Cloud-fr/System-Information-Report-Generator/blob/main/LICENSE)


![Logo](https://o2cloud.fr/logo/o2Cloud.png)


## Related

Here are some related projects

[Awesome README](https://github.com/o2Cloud-fr/System-Information-Report-Generator/blob/main/README.md)


## Roadmap

- Additional browser support

- Add more integrations


## Support

For support, email github@o2cloud.fr or join our Slack channel.


## Tech Stack

## Used By

This project is used by the following companies:

- o2Cloud
- MyAlienTech

