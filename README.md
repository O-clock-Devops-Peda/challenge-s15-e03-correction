# challenge-s15e03

## Bienvenue sur le challenge Episode3

Votre mission si vous l'acceptez est de corriger l'application contenue dans les fichiers yaml de ce repository.

## Préambule

Supprimez vos deployment, configmaps, service, horizontal pod autoscalers de vos namespace avant de démarrer le TP.

## Critère de réussite

A la fin de ce TP vous devez pouvoir présenter un ensemble de fichiers yaml applicables sur un namespace de correction.
Vous devrez présenter 2 deployments fonctionnels, chacun présentant un service consultables depuis les loadbalancers AWS.

Le deuxième service devra afficher un contenu différent en page d'accueil que la page nginx (par vos méthodes).
Il peut y avoir: des erreurs, des lignes manquantes, des erreurs d'indentations, tout est possible!

Le premier service chargera une configmap en tant que variable, le contenu de cette variable sera consultable dans les logs du pod à l'aide de la commande kubectl logs.

## Points bonus artistiques:

Des points bonus artistiques seront accordés en cas d'utilisation:
- d'au moins un initContainer
- d'un volume persistant contenant une donnée évoluant à chaque redémarrage de pod

