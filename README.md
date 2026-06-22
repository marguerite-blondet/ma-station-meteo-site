Meteo Xplorer - Tableau de bord  
  
Version -- Juin 2026  
Autheur -- Marguerite BLONDET  
Projet  -- D2iP02 : Habib TALL, Jawaher TALL, Rémi TESSE, Clémentine TRANNOY, William SOUCHARD, Marguerite BLONDET  
  
  
Bienvenue sur l'interface web de la station météo connectée et mobile (Meteo Xplorer).   
  
  
-- Technologies utilisées  
* Front-end : HTML5, CSS3, JavaScript
* Back-end : API externe, serveur hébergé sur Render : https://station-meteo1.onrender.com
* Matériel : ESP32, capteurs Arduino, module 4G/5G
  
  
-- Structure du code Front-end  
Le fichier principal, qui correspond à la page d'accueil du site, est index.html.  
Vous trouverez un fichier.html par capteur.  
  
* Température       : temp.html          (Données en temps réels + Graphique)
* Humidité          : humidite.html      (Données en temps réels + Graphique)  
* Luminosité        : luminosite.html    (Données en temps réels + Graphique)
* Pression          : pression.html      (Données en temps réels + Graphique)
* Vitesse du vent   : vitessevent.html   (Données en temps réels + Graphique)
* Direction du vent : dirvent.html       (Données en temps réels)
* Angle du vent     : anglevent.html     (Données en temps réels)
* Présence de pluie : pluie.html         (Données en temps réels)
* GPS               : gps.html           (Données en temps réels)
    
Chaque fichier est composé de 3 parties : CSS, HTML, JavaScript.  

Sur chaque page de capteurs vous pouvez retrouver les 5 dernières données en temps réels (les pages se remettent à jour toutes les minutes). Et un graphique des données dans l'heure lorsque c'est pertinent.  


-- URLs des données en temps réels
* Temperature         : https://station-meteo1.onrender.com/api/meteo/historique/temperature
* Humidite            : https://station-meteo1.onrender.com/api/meteo/historique/humidite
* Luminiosité         : https://station-meteo1.onrender.com/api/meteo/historique/luminosite 
* Pression            : https://station-meteo1.onrender.com/api/meteo/historique/pression
* Vitesse du vent     : https://station-meteo1.onrender.com/api/meteo/historique/vitesse_m_s 
* Direction du vent   : https://station-meteo1.onrender.com/api/meteo/historique/dirVent 
* Angle du vent       : https://station-meteo1.onrender.com/api/meteo/historique/angleVent 
* Présence de pluie   : https://station-meteo1.onrender.com/api/meteo/historique/pluie_mm 
* Longitude           : https://station-meteo1.onrender.com/api/meteo/historique/lng 
* Latitude            : https://station-meteo1.onrender.com/api/meteo/historique/latitude 
* Altitude            : https://station-meteo1.onrender.com/api/meteo/historique/altitude


-- URLs des graphiques
* Temperature        : https://station-meteo1.onrender.com/ui/#!/3?view=fullscreen 
* Humidite           : https://station-meteo1.onrender.com/ui/#!/0?view=fullscreen 
* Luminosite         : https://station-meteo1.onrender.com/ui/#!/2?view=fullscreen 
* Pression           : https://station-meteo1.onrender.com/ui/#!/1?view=fullscreen 
* Vitesse du vent    : https://station-meteo1.onrender.com/ui/#!/4?view=fullscreen 

  
-- Où retrouver le site ?  
Github est en lien avec render qui fournit une URL gratuit. Le site est donc accessible sur https://meteo-xplorer.onrender.com/  
  
Pour modifier/améliorer le site, il vous suffit de cloner ce répertoire.  
