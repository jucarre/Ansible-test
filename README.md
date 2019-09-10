# Ansible test
#### Cours ansible symfonycasts

Déploiement de Symfony-Demo avec Ansible et Vagrant

Démarrer le serveur avec Vagrant
```
vagrant up
```

Pour se connecter en SSH au serveur
```
ssh vagrant@192.168.33.10 -i ./.vagrant/machines/default/virtualbox/private_key
```

La lancer a la racine du projet pour configurer le serveur
```
ansible-playbook ansible/playbook.yml -i ansible/hosts.ini
```
