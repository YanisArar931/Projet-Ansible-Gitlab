# Projet-Ansible-Gitlab
Déploiement GitLab avec Ansible - ARAR Yanis
# Objectifs
1.Déploiement d'un serveur GitLab via un rôle Ansible.
2.Déploiement de bases de données PostgreSQL (optionnel).
# Déploiement Ansible
Changer l'adresse ip dans le fichier "inventory.yml" avec l'adresse de votre machine client.
Lancer les rôles :
'ansible-playbook -i inventory.yaml playbook.yml'
# Acceder à Gitlab
Nom d'utilisateur : root
Le mot de passe est généré avec la commande :
'cat /etc/gitlab/initial_root_password'
