Ohmyfood
Projet 3 - Améliorez l'interface d'un site mobile avec des animations CSS

Ohmyfood a pour ambition de conquérir le marché de la restauration. L'objectif principal de ce projet était de concevoir un site web en mobile-first, dont la fonction principale serait de répertorier les menus proposés par des restaurants gastronomiques.
Au-delà de la fonctionnalité classique de réservation de tables, le site permet aux clients de composer leur propre menu, offrant ainsi la possibilité de préparer les plats à l'avance pour leur arrivée. Cette fonctionnalité vise à améliorer l'expérience des utilisateurs en leur offrant plus de flexibilité et de personnalisation dans le choix de leur repas.

Objectif et Enjeux:

Nous avons pour objectif d'étendre nos services à Paris. Pour cela, nous avons défini les étapes suivantes pour concrétiser ce projet.

Phases du Projet:

- Phase 1 : La première étape consistait à créer un site web qui présente les menus de quatre restaurants parisiens renommés.
- Phase 2 : Dans la deuxième phase, nous prévoyons de permettre aux utilisateurs de réserver en ligne et de personnaliser leurs menus selon leurs préférences.

Fonctionnement:

Nous disposons d'un budget de 20 000 € pour la réalisation de ce projet. Nous prévoyons de livrer la première version du site dans un délai d'un mois. Ensuite, la deuxième version du site sera achevée dans un délai de six mois.

Technologies Utilisées:

Pour le développement, je n’ai utilisé que CSS, excluant JavaScript. Aucun framework n’a été employé, cependant j’ai utilisé SASS afin de faciliter la maintenabilité du site via une architecture 5:1.

Contenu des pages attendues:

1. Header (Présent sur toutes les pages):

- Sur la page d'accueil, le header affiche le logo du site.
- Sur les pages de menu, en plus du logo, le header comprend un bouton de retour vers la page d'accueil pour faciliter la navigation.

2. Page d'Accueil (x1):

   - Affiche la localisation des restaurants.
   - Permet de choisir une localisation pour trouver des restaurants proches d'un lieu spécifique.
   - Comprend une section affichant les 4 menus sous forme de cartes, avec la possibilité de rediriger l'utilisateur vers la page du menu en cas de clic.

3. Pages de Menu (x4):

   - Chaque page contient le menu complet d'un restaurant spécifique.


4.Footer (Identique sur toutes les pages):

- Contient des éléments identiques sur toutes les pages du site.
- Comporte un lien "Contact" qui redirige vers une adresse e-mail.


Restrictions sur les Effets Graphiques et Animations :

Les effets graphiques et animations visibles dans la maquette doivent être mis en œuvre en utilisant exclusivement les fonctionnalités d'animations et de transitions disponibles en CSS. L'utilisation de JavaScript ou de bibliothèques tierces n'est pas autorisée.

**Boutons :**

Effets au survol des boutons principaux :

- Lorsqu'un bouton principal est survolé, la couleur de fond doit s'éclaircir légèrement.
- L'ombre portée du bouton doit également devenir plus visible.

Bouton "J'aime" (en forme de cœur) :

- Sur la maquette, un bouton "J'aime" en forme de cœur est présent.
- Au clic sur ce bouton, il devra se remplir progressivement.
- Pour cette première version, l'effet de remplissage peut apparaître au survol sur les ordinateurs de bureau au lieu du clic.

**Page d'Accueil :**

Loading Spinner :

- Quand l'application disposera de plus de menus, un "loading spinner" sera nécessaire.
- Sur cette maquette, nous souhaitons avoir un aperçu de ce spinner.
- Il doit apparaître pendant 1 à 3 secondes dès l'arrivée sur la page d'accueil.
- Il doit couvrir l'intégralité de l'écran.
- Les animations CSS doivent être utilisées pour sa création, sans recourir à des bibliothèques.
- Le design du loader n'est pas encore défini, toutes les propositions sont les bienvenues, à condition qu'elles soient cohérentes avec la charte graphique du site.

**Pages de Menu :**

Apparition progressive des plats :

- À l'arrivée sur la page du menu, les plats doivent apparaître progressivement.
- Cette apparition peut se faire soit un par un, soit par groupe (par exemple, "Entrée", "Plat" et "Dessert").
- Un léger décalage dans le temps est souhaité pour l'effet.
- Un exemple de l'effet attendu est fourni.

Sélection des plats :

- Les visiteurs peuvent ajouter des plats à leur commande en cliquant dessus.
- Cela fait apparaître une petite coche à droite du plat.
- Cette coche doit coulisser de la droite vers la gauche.
- Pour cette première version, l'effet de la coche peut apparaître au survol sur les ordinateurs de bureau au lieu du clic.
- Si l'intitulé du plat est trop long, il doit être rogné avec des points de suspension.
- Un exemple de l'effet attendu est fourni.

Les couleurs:

1.Primaire: #9356DC
2.Secondaire: #FF79DA
3.Tertiaire: #99E2D0