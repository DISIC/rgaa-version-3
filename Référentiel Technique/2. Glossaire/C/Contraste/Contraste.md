Opposition marquée entre la luminosité d'une couleur de premier plan et d'une couleur d'arrière-plan. Le rapport de contraste est basé sur la différence de luminosité relative entre l'arrière-plan et le premier plan selon la règle : (L1 + 0,05) / (L2 + 0,05) où L1 est la luminosité relative la plus claire et L2 la luminosité relative la plus sombre. La luminosité est calculée selon la formule suivante : L = 0,2126 * R + 0,7152 * G + 0,0722 * B. Où R, G et B sont définis par :

*   si RsRGB >= 0,03928 alors R = RsRGB/12,92 sinon R = ((RsRGB+0,055)/1,055) ^ 2,4 ;
*   si GsRGB >= 0,03928 alors G = GsRGB/12,92 sinon G = ((GsRGB+0,055)/1,055) ^ 2,4 ;
*   si BsRGB >= 0,03928 alors B = BsRGB/12.92 sinon B = ((BsRGB+0,055)/1,055) ^ 2,4 ;

et RsRGB, GsRGB et BsRGB sont définis par :

*   RsRGB = R8bit/255 ;
*   GsRGB = G8bit/255 ;
*   BsRGB = B8bit/255.

Le caractère "^" est l'opérateur exponentiel.

**Note** : la mesure de contraste concerne le texte, le texte en image, le texte et le texte en image dans les animations, le texte de sous-titrage et le texte incrusté dans les vidéos. Pour le texte et le texte en image dans les animations, le texte de sous-titrage et le texte incrusté dans les vidéos, la taille de la police doit être mesurée par rapport à la taille d'affichage par défaut (telle qu'affichée). Les textes présents dans les éléments d'une image ou d'une vidéo (par exemple un écriteau, une affiche etc.) ne sont pas concernés.
