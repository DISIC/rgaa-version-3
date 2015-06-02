Le contexte du lien représente les informations supplémentaires (on parle d'informations de contexte) qui peuvent être mises en relation par un programme informatique avec l'intitulé du lien. Les informations de contexte qui permettent de rendre un lien explicite sont les suivantes :

*   le contenu de la phrase dans laquelle le lien texte est présent ;
*   le contenu du paragraphe (balise `p`) dans lequel le lien texte est présent ;
*   le contenu de l'item de liste (balise `li`) ou le contenu d'un item de liste parent (balise `li`) dans lequel le lien texte est présent ;
*   le contenu du titre (balise `h`) précédent le lien texte ;
*   le contenu de la ou les cellule(s) d'en-tête de tableau (balise(s) `th`) associée(s) à la cellule de donnée (balise `td`) dans laquelle le lien texte est présent ;
*   le contenu de la cellule de donnée (balise `td`) dans laquelle le lien texte est présent ;
*   le contenu du titre de lien (attribut `title`) ;
*   le contenu de la propriété `aria-label` ;
*   le contenu du passage de texte lié par la propriété `aria-labelledby` ;

**Note 1 :** : l'un des 9 contextes de lien doit permettre à lui seul d'expliciter le lien.

**Note 2 :** RGAA 3.0 considère que des liens particuliers comme des liens de type mailto (qui génère un lien sous la forme d'une adresse email cliquable) sont suffisamment explicites et ne requiert pas de signaler, via un title, que l'action consiste à envoyer un email. L'attention des auteurs est appelée sur le fait que cette règle générale peut être adaptée au contexte, par exemple si la page contient plusieurs adresses email cliquables affectées de comportements différents (envoyer un email via le client de messagerie pour l'une, accéder à un formulaire pour l'autre) il peut être nécessaire de donner des informations complémentaire sur l'action du lien afin de différencier leurs comportements.
