Meteo Xplorer - Tableau de bord  
  
Version -- Juin 2026  
Autheur -- Marguerite BLONDET  
Projet  -- D2iP02 : Habib TALL, Jawaher TALL, Rémi TESSE, Clémentine TRANNOY, William SOUCHARD, Marguerite BLONDET  
  
  
Bienvenue sur l'interface web da la station météo connectée et mobile (Meteo Xplorer).   
  
  
-- Technologies utilisées  
* Front-end : HTML5, CSS3, JavaScript
* Back-end : API externe, serveur hébergé sur Render : https://station-meteo1.onrender.com
* Matériel : ESP32, capteurs Arduino, module 4G/5G
  
  
-- Structure du code Front-end  
Le fichier principal, qui correspond à la page d'accueil du site, est index.html.  
Vous trouverez un fichier.html par capteur.  
  
* Température       : temp.html
* Humidité          : humidite.html
* Luminosité        : luminosite.html
* Pression          : pression.html
* Vitesse du vent   : vitessevent.html
* Direction du vent : dirvent.html
* Angle du vent     : anglevent.html
* Présence de pluie : pluie.html
* GPS               : gps.html
    
Chaque fichier est composé de 3 parties : CSS, HTML, JavaScript.  
  
  
-- Où retrouver le site ?  
Github est en lien avec render qui fournit une URL gratuit. Le site est donc accessible sur https://meteo-xplorer.onrender.com/  
  
Pour modifier/améliorer le site, il vous suffit de cloner ce répertoire.  
