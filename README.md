# ssh-key-management
Gestion centralisée des clés SSH avec Ansible

## Fonctionnalités

- Génération sécurisée de paires de clés SSH sur un serveur central.
- Stockage sécurisé des clés privées à l'aide d'Ansible Vault.
- Distribution automatique des clés publiques sur les serveurs distants.
- Gestion centralisée des clés SSH pour une infrastructure sécurisée.

## Structure du projet

- `playbooks/`: Contient les playbooks Ansible pour la génération et la distribution des clés.
- `vault/`: Contient les fichiers Vault pour le stockage sécurisé des clés privées.
- `inventory`: Fichier d'inventaire pour définir les serveurs distants.
- `README.md`: Fichier README du projet avec des instructions et des informations supplémentaires.

## Configuration requise

- Ansible installé sur le serveur central.
- Serveurs distants accessibles via SSH pour la distribution des clés.
