# Compte-rendu du TP 6

## Notes globales du TP

Ce TP a été réalisé le 1 et le 2 avril, donc bien après les dates recommandées.

En revanche, le fait d'avoir fait le TP "Helm" et d'avoir pu maturer sur les cours et TP faits auparavant a été très bénéfique pour réaliser ce TP 6.

En effet, les différentes étapes du TP se sont passées sans difficulté majeure. Ce TP se situe très bien dans la continuité des TP précédents et, les difficultés ayant pour la plupart déjà été rencontrées en TP, permet de se rendre compte qu'il est assez simple et rapide (dans les limites de ce qui est demandé en TP) d'intégrer des nouveaux éléments à notre architecture.

En revanche, le compte-rendu rédigé ici a été écrit en partie pendant la réalisation du TP, mais a été fini le dimanche 5 avril.

Je m'excuse par avance pour le retard.

## Notes détaillées du TP

### Étape 1 : Création des secrets

Cette première étape s'est globalement bien passé, mais a pris plus de temps que les autres.
Principalement, le temps passé sur cette partie consistait à trouver comment impleménter les objets secrets

Finalement, en pratique, l'implémentation de secrets n'a pas posé de problème et s'est relativement bien passé.

### Étape 2 : Mise en place d'un init-container

Cette deuxième étape s'est bien passé, sauf pour une erreur de syntaxe (j'avais placé les parties "containers" et "volumes" au mauvais endroit ...).
Hormis cet incident, tout est allé relativement vite.

### Étape 3 : Mise en place de probes

Ce TP ayant été réalisé après le TP 5, cette étape est allé très vite et n'a pas posé de problème.

### Étape 4 : Mise en place de la QoS

Cette étape est également allé assez vite. 
En effet, le principe de la "QoS : Guaranteed" n'impliquait que très peu de changement dans les manifests et s'est bien passé lors de l'implémentation.

### Étape 5 : Mise en place d'un headless service

Ce TP ayant été réalisé après la mise en place du StatefulSet, le headless service avait déjà été mis en place avant d'arriver à cette étape.

### Étape 6 : Clustering

Au vu de mon retard, je n'ai pas pu réaliser cette partie. Mais son implémentation m'intéresse, je vais probablement essayer de réaliser cette partie hors TP.