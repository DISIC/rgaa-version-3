*   Média temporel seulement audio : contenu sonore (Wawe, Mp3...) ;
*   Média temporel seulement vidéo : images ou photos en mouvement ou en séquence ;
*   Média temporel synchronisé : flux audio ou vidéo synchronisé avec un autre format pour présenter de l'information et/ou comportant des composants temporels interactifs. Un média temporel peut être consulté de 2 manières différentes :
    *   fichier à télécharger consultable avec un logiciel externe à la page web ;
    *   contenu embarqué dans la page web et consultable dans la page web via :
        *   un plugin (par exemple une vidéo diffusée par un lecteur Flash) ;
        *   l'élément `video` (par exemple une vidéo) ;
        *   l'élément `audio` (par exemple un podcast) ;
        *   l'élément `svg` (par exemple un dessin animé vectoriel) ;
        *   l'élément `canvas` (par exemple un dessin animé en image bitmap).

Un média temporel peut être diffusé en temps réel ou être proposé en lecture de manière asynchrone (média pré-enregistré).

**Note 1** : l'utilisation du paramètre `wmode` pour un objet Flash avec les valeurs `"transparent"` et `"opaque"` invalide de fait le critère 4.20 (La consultation de chaque média temporel est-elle contrôlable par le clavier et la souris ?). En effet, l'utilisation de ces valeurs a pour conséquence que l'animation Flash vue du côté des utilisateurs de lecteur d'écran est invisible.

**Note 2** : les gif animés, les animations d'images réalisées par JavaScript ou CSS ne sont pas considérés comme étant des médias temporels.
