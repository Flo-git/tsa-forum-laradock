# TSA-forum-laradock
La 1ere fois se placer à la racine du projet
- Copier le dossier nginx depuis customize-laradock dans le module laradock à la place du dossier du même nom.
- Copier .env depuis customize-laradock en place de l'existant dans le dossier Laradock
- Faire de même avec docker-compose.yml

Se placer dans le dossier laradock :
- lancer docker-compose up -d nginx mysql phpmyadmin workspace 
Le build des containers la 1ere fois cela peut prendre une heure !
Ensuite  ce sera rapide.

Une fois les containers actifs lancer phpmyadmin dans le navigateur et creer la bdd bloglaravel, puis y copier le sql présent dans customize.

Les fois suivantes travailler dans tsa-forum qui est une appli Laravel
les commits sont à faire à partir du dossier de l'appli vers https://github.com/Flo-git/tsa-forum.git
# Projet-TSA-FORUM-Laradock
