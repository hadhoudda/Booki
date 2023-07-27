[![GitHub](https://badgen.net/badge/icon/github?icon=github&label)](https://github.com) https://github.com/hadhoudda/Booki.git

Lien site : https://hadhoudda.github.io/Booki/

<p align="center">
  <img src="Images/Profil-booki.png">
</p>

### Transformez une maquette en site web avec HTML & CSS
Booki - Trouvez votre hébergement pour des vacances de rêvebr<br>
Maquettes du site Booki : https://www.figma.com/file/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?type=design&node-id=3-0&mode=design

## Scénario
Booki, une petite entreprise proposant un outil de planification de vacances, souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.<br>

Vous êtes chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, vous travaillez en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer. 

## Spécifications fonctionnelles 

# Fonction recherche :

● Les usagers pourront rechercher des hébergements dans la ville de leur choix.

● Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être
édité par l’utilisateur.

● Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas
être fonctionnelle - il s’agit d’une première version pour valider l’interface.

# Liens “Hébergements” et “Activités”

● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils
doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

# Cartes hébergements et activités

● Chaque carte d’hébergement ou d’activité devra être cliquable dans son
intégralité (pas uniquement le titre).

● Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.

# Filtres de recherche:

● Les hébergements peuvent être filtrés par thématique, comme le budget ou l’ambiance.

● Les filtres doivent changer d’apparence au survol.   

● Les filtres ne doivent pas être fonctionnels - il s’agit juste d’une première version pour valider l’interface

# Liens “Hébergements” et “Activités”:

● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et
“Activités à Marseille”.

## Spécifications techniques

# Maquettes:

* Trois maquettes ont été réalisées : desktop, tablette et mobile.

* Nous avons convenu avec le designer UI d’utiliser 1024 px et 768 px :

● >=1024 px pour les écrans d’ordinateurs ;

● >=768 px pour les tablettes ;

● et tout ce qui est en dessous de 768 pour les téléphones portables.

* Largeur max:
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum 
de 1 440 px

* Desktop first:
Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first),
puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra
de réaliser l’intégration pour les différents supports.

* Bibliothèque d’icône:
Les icônes proviennent de la bibliothèque Font Awesome.

* Couleurs: 
    
Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu
(#DEEBFF) et le gris pour le fond (#F2F2F2)

* Police: 

La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer
facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.

* Mise en page:
    
Il est recommandé d'utiliser Flexbox.

* Balises sémantiques:

 Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”, “h1-h2-h3”, “main”, “section”, “article” et “footer”.

* Validité du code:

● Aucun IDE ou éditeur de code particulier n’est imposé pour le développement.

● Le code doit être valide aux validateurs W3C HTML et CSS.

● Le code HTML ne doit pas contenir de propriété CSS.

● Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code
HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la
loupe).

● Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser le nom de l’élément lui-même.

● Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont identiques du point de vue de la mise en forme, alors utiliser une seule et même classe CSS, et non pas 4.

* Compatibilité navigateurs:

 La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.

# Hi, I'm HOUDA! 👋