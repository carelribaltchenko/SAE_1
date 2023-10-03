# SAE_1

## installer ubuntu.
pour installer ubuntu, il faut une clé usb d'au moins 16 Go.  
Il faut :
- se rendre sur le site d'ubuntu et de telecharger la derniere version.
- telecharger l'application rufus et l'executer.
    - dans rufus, selectionner le dossier contenant les fichiers d'Ubuntu et de selectionner la clé USB a rendre bootable.
- quand cela est fait, il faut se rendre dans les options de redemarage avancé puis de selectionner comme moyen de démarage la clé usb. 
- une fois le démarage terminé, finaliser l'installation en parametrant la langue, la date et l'heure, la disposition du clavier.
- enfin, définir le partage de disque avec windows. iol faut au moins définir 50 Go sinon, on peux aussi l'installer a la place du systeme windows existant.

## installer python.
- python est déja préinstallé sur ubuntu, donc pour l'utilliser, il faut aller dans un terminal et utilliser la commande `python3`, ce qui ouvrira un executeur python. pour le fermer, il faut ecrire `exit()`
- il nous faut également un IDE (integrated developpement environnement), comme IDLE ou Visual Studio CODE. au lancement du systeme, une fenetre m'a proposer de telecharger Visual studio code, mais on peut également utiliser la commande `sudo dpkg -i code_*.deb`.

## installer et configurer git.
- pour installer GIT, il faut, dans un terminal, utilliser la commande `sudo apt install git-all`
- pour le configurer, il faut écrire dans notre home `git config --global user.name "nom d'utilisateur"` puis `git config --global user.email email`

- pour faire cela, il faut un compte github ou gitlab ou n'importe quel autre application utilisant git.

## installer un émulateur JAVA
- dans un terminal, taper la commande `sudo apt install default-jre default-jdk`
### realiser le test de la fonction java
- utliser la commande `touch Executable.java` pour créer le fichier correspondant 
- utiliser la commande `nano Executable.java`pour y rentrer le code voulu. 
- ensuite utiliser `javac Executable.java` et enfin `java Executable`


