READ ME

Ce projet m'a été soumis lors d'un de mes cours sur l'intelligence artificielle et les sciences des données.

Galaxy Zoo est un jeu de données qui provient d'un projet collaboratif. En répondant à une suite de question sur des images
de galaxies sur leur plateforme on ajoute des données au dataset. Le but est de déterminer si une galaxie est de type 
"smooth" ou de type "spiral". Nous avons donc un jeu de données conséquent avec à peu près 32 000 photos.

Le but de ce projet était de monter un arbre de décision qui permet d'évaluer de nouvelles photo de galaxy et de décider si
elle est smooth ou spiral. Nous avons avec mon équipe décider d'extraire quelques features des images pour trouver des 
éléments discriminatoires pour les galaxies. Ainsi nous avons utilisé la fraction de pixel blanc sur une image binarisé 
pour trois seuils différents, nous avons extrait les composantes RGB du pixel central et nous avons appliqué un algorithme
de détection de contour pour estimer le perimètre de la galaxie et extraire cette donnée.

Notre meilleur résultat est de 84% après un test de validation croisée.