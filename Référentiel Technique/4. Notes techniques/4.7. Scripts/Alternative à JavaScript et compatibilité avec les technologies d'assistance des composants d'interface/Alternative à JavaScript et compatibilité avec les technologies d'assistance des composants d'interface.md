Le critère 7.1 implémente la notion de "compatible avec les technologies d'assistance" tel qu'il est défini par les WCAG 2, ainsi que le recours à l'API WAI-ARIA pour rendre un composant ou une fonctionnalité accessible. Le bon usage de l'API WAI-ARIA est vérifié via les tests 7.1.3, 7.1.4, 7.1.5 et 7.1.6.

**Note importante :** dans un environnement HTML5, beaucoup de composants peuvent nécessiter JavaScript pour fonctionner, en conséquence la fourniture d'une alternative à un composant JavaScript qui ne pourrait pas être rendu accessible devra bénéficier d'une méthode spécifique au composant en cause permettant de le remplacer par une alternative accessible (et de le réactiver).

Cela signifie que la désactivation de JavaScript pour l'ensemble de la page ne sera pas acceptée comme une méthode valable, à moins qu'elle ne remette pas en cause l'utilisation des autres composants.
