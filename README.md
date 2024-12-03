# Projet Ansible
*Louis ROCCA - Groupe 3 Master 1 Développeur FullStack*

**Objectifs** 

- Déployer un serveur GitLab en utilisant Ansible pour automatiser l’ensemble du processus. Le but final est bien de n’avoir qu’un “push button” pour deployer le serveur Gitlab.
- Déployement d'une base de données avec PostgreSQL. 
- Créer une image pour conteneuriser le gitlab.
- Créer une image pour conteneuriser postgreSQL.

### Pour run le projet

```shell
ansible-playbook -i inventory.yml main.yml -e "user_name=<nom_utilisateur> host_ip=<ip-vm-client>"
```

### Pour vérifier que gitlab fonctionne : 

```shell
# Dans votre navigateur, allez à cette URL
http://<votre-ip-vm-client>:2443
```

### Pour vérifier que postgresql est installé sur la vm : 

```shell
psql -U postgres # puis utilisé le mdp
```
