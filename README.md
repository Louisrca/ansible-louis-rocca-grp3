pour run le projet :

ansible-playbook -i inventory.yml main.yml -e "user_name=<nom_utilisateur> host_ip=<ip-vm-client>"

pour vérifier que gitlab fonctionne : http://<votre-ip-vm-client>:2443

pour vérifier que postgresql est installé sur la vm : psql -U postgres puis utilisé le mdp
