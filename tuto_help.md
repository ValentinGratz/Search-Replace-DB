## Tutoriel d'utilisation


Si on a repris une sauvegarde contenant le nom du site et l'impossibilité d'accéder à l'admin WordPress d'une sauvegarde en localhost, faire ceci.

1) Télécharger et mettre le script à la base du site (du dossier WP s'il est en sous-domaine)
2) Tapez l'adresse ``` http://nom-de-mon-site.fr/migrer/ ```
3) Une fois le script lancé, une page apparaît (voir la capture qui suit). Ci-dessous, je détaille les différentes sections visible dans la page.

![This is an image](https://www.gregoirenoyelle.com/wp-content/uploads/2013/12/interconnectit-3-accueil.jpg)

#### search/replace: URL à Changer
Dans cette partie, il s’agit de remplacer l’ancienne adresse de vote ancien site par la nouvelle. Dans les deux cas, cela peut être du local vers en ligne ou en ligne à deux endroits différents.

Attention sans mettre de / à la fin de l’URL. Dans mon exemple, je déplace un site test à la racine du serveur.

#### datadase: Vérifier les réglages de la base de données
Les différents champs de cette partie vous permettent de vérifier que les identifiants de la base de données sont les bons. C’est dans celle-ci que les changements vont s’effectuer.

#### tables: Tables sélectionnées
Les tables de votre base s’affichent. Ils seront tous sélectionnez normalement, sinon, utilisez la touche majuscule.

![This is an image](https://www.gregoirenoyelle.com/wp-content/uploads/2013/12/interconnectit-3-selection-table.jpg)

#### action: Lancer le script
Dans la partie suivante, nous verrons qu’il y a deux modes principaux.

Lancement du DryRun : https://www.gregoirenoyelle.com/wordpress-migrer-site-script-interconnect-search-replace/
