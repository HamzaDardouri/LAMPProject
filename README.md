# LAMPProject-All-In-One-VM


Tou d'abord,On ouvre la machine (Apache+PHP+Mysql),

Connectez-vous sur la machine. Notre configuration au niveau adresses IP est la suivante: 


VM(Apache+PHP+Mysql): 192.168.56.20

Après,tu dois cloner ce projet sur votre machine serveur (Apache+PHP+Mysql) en utilisant cette commande:

git clone https://github.com/HamzaDardouri/SecureLogin.git

Puis,tu dois déplacer le fichier .sh (bash script file) sur votre dossier personnelle ~ ou /home/<nom_user>

mv ~/SecureLogin/deployer.sh   ~/

On passe vers l'execution: Rendre le fichier deployer.sh exécutable à travers cette commande (votre répertoire personnelle):

chmod +x deployer.sh

Enfin, Exécutez cette fichier à travers cette commande:

./deployer.sh


Pour tester :ouvrez ton navigateur et saisissez cette lien: http://192.168.56.20/SecureLogin 

Tapez comme username soit test ou hamza et comme mot de passe soit 123456 ou hamza(par défaut).

Pour que tu puisse ajouter plusieurs utilisateurs, connectez vous sur votre VM(Mysql) et entrez comme devops:

mysql -u devops -p

Mot de passe:devops 

use login; 

Pour inserer, voilà un exemple du requete d'insertion pour un nouveau utilisateur.


insert into accounts (id,username,password,email) values (3,'aaaaaa','aaaaaaaa','aaaa@aaaa.com');

Tu peut créer une infinité des utulisateurs.

#Profitez-en.

Merci pour votre lecture à la fin du page. Aurevoir.




