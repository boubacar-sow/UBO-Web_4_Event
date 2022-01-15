# UBO-Web_4_Event
Développement d'un site web pour la gestion d'un évènement. Les technologies utilisées sont HTML5, CSS3, Bootstrap, PHP, CodeIgniter.

Nom : Sow
Prenom : Boubacar
 Intitulé et sujet de l’application : Eventify, Compétition entre plusieurs personne.
Chaque personne
présente un numéro qui met en évidence son talent.
 Nom du bootstrap : Eventify
 URL de l’application :
https://obiwan2.univ-brest.fr/licence/lic101/v2/CodeIgniter/index.php/
 Comptes créés pour tester l’application :
compte simcowell:simoncowell (organisateur)
compte organisateur :(organisateur)
compte biryan:bianca(invite)
compte alex:alex (invite)
compte alexcop (invite)
compte lilou:lilou (invite)
compte laural (invite)
 Descriptif de la dernière version de l’application appelée « Eventify V2.2 » :
La saisie de l’Url de l’application nous dirige sur sa page d’accueil. Sur celle-la figure une
table qui contient toutes les actualités concernant les évenements.
Sur la page d’accueil, tout en bas figure également un bouton permettant d’ajouter un
post.
A partir de la partie publique du site, on peut voir la programmation des animations, les
invités associés à l’évenement et les lieux et services liés à l’évenements.
On peut grâce à un bouton de connexion accéder à la partie privée du site. Si l’on est
administrateur on pourra visualiser les animations programmées et aussi on pourra
supprimer une animation. On pourra également modifier ses informations personnelles. Si
l’on est invité, on pourra visualiser les passeports et posts qui nous concernent et
également modifier ses informations personnelles.
L’application est conçue de façon à pouvoir assurer un minimum de sécurité (e.g Un invité
connecté ne pourra pas accéder à l’espace administrateur et vice versa).
 Nom de la base de données : « znl3-zsowbo000 »
 Descriptif des fonctions, procédures et triggers utilisés :
trigger1 : « trig_invité »
Ce trigger insère une actualité dans la table de gestion des actualités et permet d’indiquer
qu’un
invité a été ajouté.
Trigger2 : « trig_post »
Ce trigger permet d’insérer une actualité dans la table de gestion des actualités et permet
d’indiquer qu’un invité a été ajouté.
Fonction « liste_invite » : permet de récupérer les invités associés à une animation
particulière.
L’id de l’animation étant passée en paramètre.
Procédure « get_actu » : permet de récupérer l’actualité la plus récente. Cette procédure
est appelée dans le db_model.php.
Procédure à suivre pour installer l’application Web sur un serveur :
1. Installer une plateforme de developpement (e.g Wampserveur)
2.Démarer le serveur localhost de wampserveur.
3. Se connecter à sa base donner sur phpmyadmin.
4.Importer la base de données znl3-zsowbo000
5-Ouvrir un éditeur de texte
6- Ouvir le dossier Web4Event/v2
7-Ouvrir le fichier CodeIgniter/config/config.php en vue de l’éditer
8-Modifier le paramètre $config[‘’base_url’’] en ’’localhost/’’
9-Ouvrir un navigateur web
10- Ecrire sur la barre de recherche : localhost/index.php/
Plan de tests de validation : Effectué par Carl Gauss Rugero
