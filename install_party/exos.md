Atelier Git - Exercice
===

## Mise en route - Installation

Commencez par installer git sur votre ordinateur :

* **Windows**

 1. Télécharger git sur le lien [ici](https://git-for-windows.github.io/).
 2. Installer le programme téléchargé
 3. Lancer le programme `git bash`
 4. Taper `git --version`

* **Mac**

 1. Télécharger git sur le lien [ici](https://git-scm.com/download/mac)
 2. Installer le programme téléchargé
 3. Rechercher `Terminal` dans Spotlight (la loupe en haut à droite)
 4. Taper `git --version`

 Problème possible :

 Si vous avez l'erreur (ou similaire):
 > Agreeing to the Xcode/iOS license requires admin privileges

 Pour résoudre, faites `sudo git --version`, tapez votre mot de passe, puis appuyer sur `shift+G` pour arriver en bas de la licence pour l'accepter. La prochaine fois que vous tapez `git --version` il n'y aura plus de problème.

* **Linux**

 Git est pré-installé
 1. Lancer juste la ligne de commande, `Ctrl+Alt+T` sous Ubuntu.
 2. Taper `git --version`


## Premier pas - La console

```lang:bash
cd ~
mkdir version-control
cd version-control
mkdir animals
cd animals
```
