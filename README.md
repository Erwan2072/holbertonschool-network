Networking Basics
Ce projet vous aidera à comprendre les concepts fondamentaux des réseaux, y compris le modèle OSI, les types de réseaux, les adresses IP, les protocoles TCP/UDP, et l'utilisation de certaines commandes réseau. Vous allez également apprendre à écrire des scripts Bash pour automatiser certaines tâches réseau.

Objectifs d'Apprentissage
À la fin de ce projet, vous devriez être capable d'expliquer les concepts suivants à n'importe qui, sans l'aide de Google :

Modèle OSI
Comprendre ce qu'est le modèle OSI (Open Systems Interconnection).
Connaître les 7 couches du modèle OSI.
Savoir comment ces couches sont organisées et interagissent entre elles.
Types de Réseaux
LAN (Local Area Network)
Usage typique : réseaux locaux (ex. maison, bureau).
Taille géographique : limitée.
WAN (Wide Area Network)
Usage typique : réseaux étendus (ex. Internet).
Taille géographique : grandes distances.
Internet
Comprendre ce qu'est l'Internet et comment il relie différents réseaux.
Adresses et Protocoles Réseau
Adresse IP
Comprendre ce qu'est une adresse IP et son rôle.
Différencier les deux types d'adresses IP : privée et publique.
Localhost
Comprendre ce que représente "localhost" (adresse IP 127.0.0.1).
IPv4 et IPv6
Savoir pourquoi IPv6 a été créé.
Subnet
Comprendre ce qu'est un sous-réseau (subnet).
Protocoles de Transfert TCP/UDP
Identifier les deux principaux protocoles de transfert de données pour IP : TCP et UDP.
Différence principale entre TCP (fiable) et UDP (non fiable).
Numéros de port pour les services courants : SSH (22), HTTP (80), HTTPS (443).
Outils Réseau et Commandes
Utiliser ping (ICMP) pour vérifier la connectivité réseau.
Utiliser netstat pour surveiller les connexions réseau.
Écrire des scripts Bash conformes aux directives du projet.
Tâches
<details> <summary><strong>0. OSI model</strong> (cliquez pour dérouler)</summary>
OSI (Open Systems Interconnection) est un modèle abstrait qui décrit la communication en couches et la conception des réseaux informatiques. L'idée est de séparer les différentes parties qui rendent la communication possible.

Niveau le plus bas : couche 1, pour la transmission sur les couches physiques avec impulsion électrique, lumière ou signal radio.
Niveau le plus haut : couche 7, pour la communication spécifique aux applications, comme SNMP pour les emails, HTTP pour les navigateurs web, etc.
Dans ce projet, nous nous concentrerons principalement sur :

La couche Transport, en particulier TCP/UDP
La couche Réseau, avec IP et ICMP
Questions :

Qu'est-ce que le modèle OSI ?
Comment le modèle OSI est-il organisé ?
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 0-OSI_model
</details> <details> <summary><strong>1. Types of network</strong> (cliquez pour dérouler)</summary>
Les réseaux LAN connectent les dispositifs locaux entre eux, les réseaux WAN connectent les réseaux LAN entre eux, et les réseaux WAN fonctionnent sur Internet.

Questions :

À quel type de réseau un ordinateur local est-il connecté ?
Quel type de réseau pourrait connecter un bureau dans un bâtiment à un autre bureau situé à quelques rues de là ?
Quel réseau utilisez-vous lorsque vous naviguez sur www.google.com depuis votre smartphone (non connecté au WiFi) ?
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 1-types_of_network
</details> <details> <summary><strong>2. MAC and IP address</strong> (cliquez pour dérouler)</summary>
Questions :

Qu'est-ce qu'une adresse MAC ?
Qu'est-ce qu'une adresse IP ?
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 2-MAC_and_IP_address
</details> <details> <summary><strong>3. UDP and TCP</strong> (cliquez pour dérouler)</summary>
Complétons les parties manquantes dans le schéma ci-dessus.

Questions :

Quelle déclaration est correcte pour la boîte TCP ?
Quelle déclaration est correcte pour la boîte UDP ?
Quelle déclaration est correcte pour le travailleur TCP ?
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 3-UDP_and_TCP
</details> <details> <summary><strong>4. TCP and UDP ports</strong> (cliquez pour dérouler)</summary>
Écrivez un script Bash qui affiche les ports d'écoute.

Exigences :

Afficher uniquement les sockets d'écoute.
Afficher le PID et le nom du programme auquel appartient chaque socket.
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 4-TCP_and_UDP_ports
</details> <details> <summary><strong>5. Is the host on the network</strong> (cliquez pour dérouler)</summary>
Écrivez un script Bash qui effectue un ping sur une adresse IP passée en argument.

Exigences :

Accepte une chaîne de caractères en argument.
Affiche Usage: 5-is_the_host_on_the_network {IP_ADDRESS} si aucun argument n'est passé.
Effectue un ping de l'IP 5 fois.
Répertoire :

GitHub repository: holbertonschool-network
Dossier : basics_0
Fichier : 5-is_the_host_on_the_network
</details>
Instructions Générales
Éditeurs autorisés : vi, vim, emacs
Tous vos fichiers de scripts Bash doivent être exécutables.
Votre script Bash doit passer shellcheck sans erreur.
La première ligne de tous vos scripts Bash doit être #!/usr/bin/env bash.
La deuxième ligne de tous vos scripts Bash doit être un commentaire expliquant ce que fait le script.
