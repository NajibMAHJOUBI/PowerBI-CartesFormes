# Power BI - Carte de Formes
Créer une carte de formes personnalisée dans Power BI Desktop (en préversion)

Les éléments de ce repo servent à accompagner un [article Linkedin](https://www.linkedin.com/pulse/cr%C3%A9er-une-carte-de-forme-personnalis%C3%A9e-dans-power-bi-desktop-nejib-49r0e) sur la mise en place de Carte de formes dans Power BI Desktop.

Dans le répertoire *[data](data/)*, vous trouverez les données utilisées pour l'article : 

- [Naissances Tunisie.csv](data/Naissances%20Tunisie.csv) : Nombre de naissances en 2022 par gouvernorat en Tunisie
- [Decoupage Tunisie.json](data/Decoupage%20Tunisie.geojson) : Découpage administratif en gouvernorat du territoire tunisien au format GeoJSON
- [Mapshaper](data/Mapshaper%20Tunisie.json) : Découpage administratif en gouvernorat du territoire tunisien au format TopoJSON


Dans le répertoire *[power_bi](power_bi)*, vous trouverez le fichier .pbix permettant de reproduire l'exemple présenté dans l'article LinkedIn.

## Utilisation du fichier .pbix

Pour pouvoir utliser le fichier .pbix fourni, il est nécessaire de modifier le chemin vers le [fichier de données](data/Naissances%20Tunisie.csv).
Pour cela; il faudra réaliser les étapes suivantes :

- Commencer par ouvrir le [rapport](power_bi/naissance_tunisie.pbix)  depuis Power BI Desktop

- Sélectionner **Transformer les données** depuis le menu **Requêtes** : 

![alt text](<images/GitHub 00.png>)

-  Modifier le paramètre **FilePath**

    1. Sélectioner le paramètre **FilePath** depuis le volet **Requêtes**

    2. Cliquer sur le bouton **Gérer le paramètre**

    3. Modifier le champ **Valeur actuelle** pour qu'il indique le chemin du fichier [Naissances Tunisie.csv](data/Naissances%20Tunisie.csv) sur votre machine locale

    4. Cliquer sur le bouton **OK**


![alt text](<images/GitHub 01.png>)