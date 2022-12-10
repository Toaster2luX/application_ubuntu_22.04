# Installation en one-shot d'application sous (X)ubuntu 22.04
-----------------
Pour installer rapidement l'ensemble des applications


## Exécution
-----------------
$ ansible-playbook -i inventories playbooks/playbook.yml

Avec un tag
$ ansible-playbook -i inventories playbooks/playbook.yml --tags "deb"
