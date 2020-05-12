# LAMPProject-All-In-One-VM


Tou d'abord,On ouvre la machine (Apache+PHP+Mysql),

Connectez-vous sur les 2 machines. Notre configuration au niveau adresses IP est la suivante: VM(Apache+PHP):

Après,tu dois cloner ce projet sur votre machine serveur (Apache+PHP) en utilisant cette commande:

git clone https://github.com/HamzaDardouri/SecureLoginLamp_2tiers.git

Puis,tu dois déplacer les 2 fichiers .sh (bash script file) sur votre dossier personnelle ~ ou /home/<nom_user>

mv ~/SecureLoginLamp_2tiers/deployer.sh ~/SecureLoginLamp_2tiers/deployer2.sh ~/

On passe vers l'execution: Rendre le fichier deployer.sh exécutable à travers cette commande (votre répertoire personnelle sur la machine (Apache+PHP)): chmod +x deployer.sh

Enfin, Exécutez cette fichier à travers cette commande:

./deployer.sh




