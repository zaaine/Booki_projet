# booki-starter-pack
Maquettes
Trois maquettes ont été réalisées : desktop, tablette et mobile.
Breakpoints
Nous avons convenu avec le designer UI d’utiliser 1024 px et 768 px :
● >1024 px pour les écrans d’ordinateurs ;
● >=768 px pour les tablettes ;
● et tout ce qui est en dessous de 768 pour les téléphones portables.
Largeur min - max
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum de 1440 px. Au-delà, une marge blanche doit apparaître sur les côtés et le contenu doit se limiter à 1440 px de large.
La largeur minimum est fixée à 320 px, en-deçà de cette largeur, le comportement n’est pas garanti.
Desktop first
Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first), puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.
Bibliothèque d’icônes
Les icônes proviennent de la bibliothèque Font Awesome.
 Couleurs
Les couleurs de la charte sont le bleu (#0065FC), le bleu clair (#DEEBFF) et le gris pour le fond (#F2F2F2).
Police
La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.


Mise en page
Il est recommandé d'utiliser Flexbox.
Balises sémantiques
Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”, “h1-h2-h3”, “main”, “section”, “article” et “footer”.
Validité du code
● Aucun IDE ou éditeur de code particulier n’est imposé pour le développement.
● Le code doit être valide aux validateurs W3C HTML et CSS.
● Le code HTML ne doit pas contenir de propriété CSS.
● Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code
HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la
loupe).
● Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser
le nom de l’élément lui-même.
● Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont
identiques du point de vue de la mise en forme, alors utiliser une seule et même classe CSS, et non pas 4.
Compatibilité navigateurs
La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.
Restrictions
Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).