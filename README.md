# [Ansible] Installation en one-shot d'application sous (X)ubuntu 22.04


Pour installer rapidement l'ensemble des applications

## Exécution

```bash
$ ansible-playbook -i inventories playbooks/playbook.yml
```

## Exécution avec un tag

```bash
$ ansible-playbook -i inventories playbooks/playbook.yml --tags "deb"
```

## Structure

```bash
.
├── files
│   └── custom_config_terminator
├── inventories
│   └── hosts
├── playbooks
│   └── playbook.yml
└── README.md
```


## Source

[Installation en one-shot d'application sous (X)ubuntu 22.04](https://it.izero.fr/ansible-installation-en-one-shot-dapplication-sous-xubuntu-22-04/)

## License

[MIT](https://choosealicense.com/licenses/mit/)
