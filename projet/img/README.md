# Travail Intégration

- Repository : `RedLine`
- Dead Line : Dimanche 2 Mars 2025 - 21h00
- Travail seul(e)

## Objectifs d'apprentissage

- respecter un design fourni
- consolider les acquis en git, HTML, CSS, Bootstrap
- utiliser javascript dans un projet réaliste
- avoir un nouveau projet à ajouter à son portfolio

## Le Travail d'intégration Front-End

Ce TI conclut les concepts de front-end que nous avons eus ensemble.

- Un site en ONE PAGE avec un design fourni ([yes !](layout-one-page.jpg)).
- Un site de fans (Design non fourni) [[Accès rapide]](#b-site-de-fans).

Pour cela, vous devez utiliser toutes les technos vues depuis le début, c’est à dire :

- HTML
- CSS
- JavaScript
- Bootstrap
- Responsive design

## A . Site avec LAYOUT

Vous allez réaliser, en groupe, un site internet de location et vente des films. ATTENTION, il s'agit d'un site en **one-page** !

- [Cliquez ici pour voir le layout](layout-one-v2.jpg)
- On met également à votre disposition quelques affiches de films, histoire de vous faire gagner un peu de temps (les titres, années et genre sont dans les noms des images. De rien.)

### Entrée

Lorsqu’on entre dans le site, il faut **contraindre l’utilisateur à indiquer son âge**.
S’il a 18 ans et plus, l’autoriser à entrer sur le site, sinon le rediriger vers IMDB. (Pour cela utiliser JS pour un pop-up).

Une fois sur le site, faire apparaître n’importe où sur le site une box pour la **mise en garde de cookies**. (on en voit ces derniers temps partout sur le net)

Lorsqu’on clique sur les boutons [login ou register], faire apparaître en JS ou avec Bootstrap dans une box/modal un formulaire de connexion/register.

Ce formulaire de connexion contiendra :

- identifiant,
- password,
- un bouton [OK],
- un bouton [Créer un compte],
- un bouton [rester connecté],
- un lien [Si vous avez oublié votre mot de passe],
- et un boutton [cancel].

Pour le formulaire register

- nom
- E-mail
- Password
- Confirm password
- Conditions générales d'utilisation [bouton select]
- Bouton Register

(Difficulté : faire disparaître le formulaire lorsqu'on clique sur CANCEL, sur le formulaire ou sur le bouton register, et vice versa ).

### Menu

Un **menu** en bootstrap avec des sous-menus. (**Menu hamburger pour le responsive**).

Comme c’est une onepage, les liens du menu doivent pointer vers les sections dédiées.

### En-tête

Le **jumbotron** de l'entête doit faire 100% de la largeur de l'écran dans lequel il y a un slide (Cf layout). Faire fonctionner le **slide** en CSS ou en JS ou jQuery)

### Les boutons réseaux sociaux

Les **boutons de réseaux sociaux** sont en position fixe. Si on clique sur un bouton, il doit s’allonger avec une animation (ici utilisez juste du CSS).

### Section Films

Chaque film doit comporter :

- une affiche,
- un titre,
- l’année de sortie,
- et le genre.

Si on clique sur l’image ou titre du film, faire apparaître dans un modal (Bootstrap) le trailer youtube du film, la description, le réalisateur, l’année de sortie du film, le genre, les acteurs…

### Section Featured Movies

Créer des boutons pour filtrer les films par genre (JS).
Si on clique sur le bouton ACTION par exemple, afficher uniquement les films d’actions, etc...

Lorsqu’on clique sur le bouton “plus des films”, afficher les autres films cachés. Faire disparaître le bouton “plus des films” et le remplacer par le bouton “Moins des films” si on clique sur “moins des films”, cacher les films et faire réapparaître le bouton “plus des films“.

### Section Shop Movie

Utiliser les deux petits boutons à droite pour faire défiler les films de gauche à droite et vise-versa (bootstrap ou JS au choix)

### Section Contact Us

Créer un formulaire (dans la page HTML, pas dans un pop-up). Faites en sorte que les entrées du formulaire s'affichent dans un pop-up lorsqu’on clique sur “Send Message”.

Bonus : mettre une map dans la section Contact us.

### Section Footer

Faites en sorte que lorsqu’on clique sur le petit bouton rouge avec la flèche blanche, on monte jusqu’à l'entête du site, le petit bouton disparaît une fois que l'entête apparaît.

CONTRAINTE : créer ce bouton en pur JS avec createElement(), createTextNode() et compagnie(), l’afficher sur le DOM, le positionner puis le styler en CSS dans la feuille de style.

FAITES QUE LE SITE SOIT RESPONSIVE (Bootstrap)

**Conseils**

1. Réalisez d'abord le HTML, placez-y le contenu, ensuite écrivez les scripts nécessaires.
2. N'oubliez pas de bien :

- coder correctement votre HTML (les titres avec des h1, h2 ; les paragraphes dans des balises p ; ...). Un code bien organisé et toujours plus facile à traiter.
- nommer correctement vos ID. Utilisez des noms qui aient du sens, facile à vous situer sur votre page mais aussi pour vos fonctions javascript.
