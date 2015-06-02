L'arborescence du document (<span lang="en">outline</span>) est générée par l'utilisation des balises sectionnantes `<nav>`, `<article>`, `<section>`, `<aside>` et les sections implicites générées par l'utilisation d'une balise `<hx>` (lorsque la balise `<hx>` n'est pas le premier enfant d'une section).

Une balise sectionnante permet de structurer ou de regrouper un contenu, les parties d'un contenu, ou un ensemble de contenus qui peuvent être considérés de manière indépendante du reste du document.

Une zone de navigation dans le site ou dans une rubrique, un sommaire ou la zone de navigation d'une collection de pages (`<nav>`), un contenu "complémentaire" au contenu principal (`<aside>`), le contenu principal ou le regroupement de plusieurs contenus comme des articles (`<article>` ou `<section>`) un ou des contenus secondaires comme un commentaire, un widget Twitter, un fil RSS (`<article>` ou `<section>`) sont autant d'exemples de contenus sectionnés.

Lorsqu'il s'agit de contenus, par opposition à des zones de navigation (`<nav>`) ou des zones de contenus complémentaires (`<aside>`) une section devrait posséder si c'est approprié une zone d'en-tête (`<header>`) et un pied de page (`<footer>`).

Le premier titre `<hx>` dans une section donne le "nom" de la section tel qu'il sera reporté dans l'arborescence du document. Les titres suivants (`<hx>`) créent des sections implicites qui seront présentées comme l'arborescence du contenu de la section.

Une section pouvant être considérée de manière indépendante du reste de la page, l'arborescence générée par les sections implicites (`<hx>`) est calculée à partir d'un niveau 1 affecté au premier titre de la section.

Lorsqu'elle est utilisée, l'arborescence du document peut donc être différente de l'arborescence du contenu représentée par l'ensemble des titres `<hx>` de la page même si les deux structures restent similaires.

Cette arborescence doit donc être représentative de la structure du document et être cohérente avec la structuration du contenu générée par l'utilisation des balises `<hx>`. La structuration du contenu générée par les balises `<hx>`) pouvant être, théoriquement, déduite de l'arborescence du document, la spécification HTML5 recommande d'utiliser uniquement des titres `<h1>`, cet usage est proscrit et le critère 9.1 impose d'utiliser une hiérarchie de titres (`<hx>`) cohérente.

Si l'arborescence du document (à la condition qu'elle soit cohérente) peut permettre de proposer à l'utilisateur des fonctionnalités d'exploration et de navigation, sur certaines technologies d'assistance, elle influe sur la hiérarchie de titres générée par l'utilisation des balises `<hx>` en modifiant le niveau des titres restitués.

Pour accompagner la prise en charge progressive de l'arborescence du document et compte tenu du fait que le référentiel exige de disposer, en tout état de cause, d'une structure de contenu (balises `<hx>`) robuste et cohérente, **il est acceptable de considérer le test 9.2.2 comme non applicable** lorsqu'il n'est pas possible de s'assurer que l'arborescence du document est parfaitement cohérente.

Dans ce cas, la non-conformité au test devrait être relevée sous la forme d'une simple alerte.
