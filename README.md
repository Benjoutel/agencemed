Avant chaque modification du site :
  - git pull origin master (pull notamment les changements apportés dans le readme)

Pour modifier le code, il faut utiliser la branche master.
Pour déployer:
  - pusher les changements de master to origin master
  - puis "bundle exec middleman deploy" ==> actualise le dossier build dans master et la branche "gh-pages"
  - dans settings du repo, ajouter l'url de redirection : www.med-studio.com
  - vérifier que le formulaire de contact est toujours actif en envoyant un message via la page web nouvellement déployée : formulaire activé le 11/4/19 avec l'adresse www.med-studio.com
