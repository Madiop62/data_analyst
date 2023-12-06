# data_analyst
### Fichier 1 :  Madiop_Auto.ipynb
Le script récupère un fichier d’autos csv avec des colonnes :

'dateCrawled', 'name', 'seller', 'offerType', 'price', 'abtest',
       'vehicleType', 'yearOfRegistration', 'gearbox', 'powerPS', 'model',
       'kilometer', 'monthOfRegistration', 'fuelType', 'brand',
       'notRepairedDamage', 'dateCreated', 'postalCode', 'lastSeen',
       'yearOfCreation', 'yearCrawled', 'monthOfCreation', 'monthCrawled',
       'NoOfDaysOnline', 'NoOfHrsOnline', 'yearsOld', 'monthsOld'],
      dtype='object'

L’objectif principal est de faire des requêtes avec le module « pandas » avec des barplot pour mieux visualiser les données. 
La partie la plus intéressante concerne les données relatives à la ville de Francfort où j’ai utilisé un « heatmap » avec Seaborn 

### Fichier 2 : Madiop_Villes_V2.ipynb
Au cours de la dernière décennie, les systèmes de partage de vélos ont gagné en nombre et en popularité dans les villes du monde entier. Ils permettent aux utilisateurs de louer des vélos à très court terme contre un prix. Les technologies d'information facilitent l'accès à ces systèmes pour débloquer ou retourner des vélos.
 
Les données qui sont mises à disposition concernent 3 grandes villes au USA (New York, Chicago et Washington). Les données concernent les 6 premiers mois de l'année 2017 pour New York, puis Juillet, Août et Septembre 2017 pour Chicago et enfin, Octobre, Novembre et Décembre 2017 pour Washington.
L’objectif est de créer une petite application qui, une fois la ville et le mois sélectionnées, donne un tableau de bords avec des statiques.
J’ai utilisé  essentiellement le module « ipywidgets » qui m’a permet d’utiliser des boutons pour la sélection et d’afficher les résultats directement. 
