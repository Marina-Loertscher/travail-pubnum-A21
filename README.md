# Travail Publication Numérique (Automne 2021)

## Résumé du projet: 
À l’origine, je voulais mettre en page des poèmes avec un effet parallaxe. J’ai fait une ébauche de parallaxe en utilisant du html et css, mais le résultat ne m’a pas convaincue. Alors, j’ai décidé de changer de direction et mettre en page des poèmes dans un environnement 3D. Ce projet met en page des haikus, poèmes japonais, dans un environnement 3D avec l’aide de [A-FRAME](https://aframe.io/)

Les six poèmes choisis sont des haikus. Le thème qui les relie est la nature. Les haikus ont été choisis pour leur apparente clarté et simplicité. L’environnement dans lequel ils se trouvent est une forêt, constituée de différents arbres. Les arbres sont tous construits à l’aide de deux formes géométriques simples: un cylindre pour le tronc et soit une sphère soit un cône pour la partie supérieure de l’arbre. Il y’a un soleil, qui est une des sources de lumière de la scène. 

## Problèmes/Améliorations possibles: 
Ombres: Dans la scène, il manque les ombres. La source du problème vient du fait que A-FRAME intègre par défaut deux sources de lumière dans les scènes. Celles-ci devraient automatiquement se retirer dès lors qu’une autre source de lumière est ajoutée. Cependant, ce n’est pas le cas ici. Ainsi, lorsque j’ai ajouté les ombres aux différents arbres et au sol; les ombres « n’allaient pas dans le bon sens » selon la source de lumière placée aux alentours du soleil. J’ai donc préféré retirer les ombres, plutôt que de les avoir placées « au mauvais endroit ». 

Création de la forêt: Dans ce projet la forêt a dû être créée manuellement. Une des améliorations possibles serait de générer la forêt de manière automatique. J’ai essayé de le faire, mais sans réussir. Si j’avais eu plus de temps à consacrer à ce « problème » ou de meilleures bases en javascript et html, je pense que j’aurai pu trouver la solution à ce problème. 

Autre: De manière générale, plusieurs améliorations pourraient être faites/plusieurs éléments pourraient être ajoutés pour rendre la scène plus intéressante. Cependant, les deux points mis en avant ci-dessus sont selon moi les plus importants. 

Comment ouvrir le projet: 
Pour ouvrir le projet il suffit d’ouvrir la page « index1.html ». 
