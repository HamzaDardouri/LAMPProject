# LAMPProject
Un projet simple d'application (login,mot de passe,profile) pour administrer des serveures d'application
Pour Faire un clonage il sufit de taper:
git clone https://github.com/HamzaDardouri/SecureLogin.git
N.B: En supposant que tu fait le clonage dans votre répertoire personnelle.
Pour faire le déploiement:
sudo cp -r SecureLogin /var/www/html/
Tu peut créer la base en tapant en mysql:
create database login;
Puis, on crée une table en tapant:
CREATE TABLE IF NOT EXISTS `accounts` (
    -> `id` int(11) NOT NULL AUTO_INCREMENT,
    ->   `username` varchar(50) NOT NULL,
    ->   `password` varchar(255) NOT NULL,
    ->   `email` varchar(100) NOT NULL,
    ->     PRIMARY KEY (`id`)
    -> ) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;
Tu peut aussi insérer queleques lignes en tapant:
insert into accounts (id,username,password,email) values (1,'test','123456','test@test.com');
insert into accounts (id,username,password,email) values (2,'hamza','hamza','hamza@admsrv.com');



