# Installation et configuration d'Ansible

## 1. Mise à jour des dépôts
``` bash
sudo apt update
```
## 2. Installation d'Ansible
``` bash
sudo apt install ansible
```
## 3. Création user ansible avec une clé ssh
``` bash
sudo useradd -s /usr/bin/bash ansible -m
sudo usermod -g root ansible
ssh-keygen -t rsassh-keygen -t rsa
```

