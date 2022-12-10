# Installation en one-shot d'application sous (X)ubuntu 22.04
-----------------
Pour installer rapidement l'ensemble des applications


## Exécution
-----------------
$ ansible-playbook -i inventories playbooks/playbook.yml


## Exécution avec un tag
-----------------
$ ansible-playbook -i inventories playbooks/playbook.yml --tags "deb"


### Source
https://it.izero.fr/ansible-installation-en-one-shot-dapplication-sous-xubuntu-22-04/
