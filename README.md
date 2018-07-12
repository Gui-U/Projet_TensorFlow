# Projet_TensorFlow

Projet de fin de 2ième année cycle ingénieur, le but de ce projet était de découvrir les bases et le fonctionnement de TensorFlow pour en retranscrire nos connaissance acquise par le biais de tutoriel et d'une application utilisant un réseau de neurones.

Les tutoriels sont disponibles [ici](https://github.com/JulienPolop/TensorFlow) et [ici](https://github.com/wakafii/TensorFlow).
Nous avons aussi réaliser des tutoriels des bases de Theano un concurent de TensorFlow [ici](https://github.com/wakafii/Theano).

Durant ce projet nous avons réalisé plusieurs réseau de neurones afin d'essayer d'augmenter la précision de nos prédictions, nous avons aussi dû traiter le signal d'entré afin de le découper et faciliter l'apprentissage du réseau de neurones. Vous trouverez ici le code des différents réseau construit pour réaliser la détection du mouvements des jambes ( DataProj(recu), DataProj(Conv) et DataProj(Dense) sont les codes utilisés pour tester les performances des différentes structures de réseau). Ce réseau a été créé afin d'apporter une première solution à la détection de pas pour une personne. Vous trouverez aussi le code expliqué du réseau choisi (Réseau Convolutionnel Projet).

Nous avons ensuite voulu adapter notre solution au quadripède, pour cela nous avons du créer une base de données contenant des pas de quadripède afin d'entrainer notre réseau, vous trouverez le code réalisant cette base de données ainsi que l'entrainement du réseu réalisant les prédictions dans le fichier Réseau quadripède.

Alexandre Boyenval
mail : alexandre.boyenval@edu.esiee.fr
