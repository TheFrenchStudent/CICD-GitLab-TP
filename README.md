# CI-CD GitLab TP 1

Pour exécuter la pipeline, il faut commit le fichier ```gitlab-ci.yml```. Ou alors le run directement via l'interface graphique de GitLab.

## Fichier ```.env```

Contient le chemin où la config & les données de notre infrastructure sont stockées.

## Fichier ```gitlab-ci.yml```

Fichier de configuration des jobs que les runners vont exécuter.


## Fichier ```docker-compose.yml```

Contient la configuration pour construire et déployer les conteneurs qui vont hoster les runners (gitlab-runner).
