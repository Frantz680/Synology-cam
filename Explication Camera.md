## Mise en Relation Synology et Caméra via HTTP

### 1. Configuration de la Caméra :

- Assurez-vous que la caméra est connectée au même réseau que votre serveur Synology.
- Accédez aux paramètres de la caméra via son interface utilisateur, généralement via un navigateur web.
- Recherchez les options de configuration réseau et notez l'adresse IP de la caméra.

### 2. Configuration du Serveur Synology :

- Connectez-vous à l'interface d'administration de votre Synology via un navigateur web en utilisant son adresse IP.
- Allez dans le "Panneau de configuration" et ouvrez l'application "Caméras".
- Cliquez sur "Ajouter" pour configurer une nouvelle caméra.

### 3. Ajout de la Caméra dans Surveillance Station :

- Sélectionnez le modèle de caméra correspondant dans la liste (si votre caméra est prise en charge) ou choisissez "Caméra générique".
- Entrez le nom de la caméra, son adresse IP, le port HTTP (généralement 80 pour HTTP), le nom d'utilisateur et le mot de passe pour la caméra.
- Cliquez sur "Appliquer" pour sauvegarder les paramètres.

### 4. Vérification de la Connexion :

- Une fois la configuration terminée, revenez à la liste des caméras dans Surveillance Station.
- Vous devriez voir la nouvelle caméra répertoriée. Cliquez dessus pour vérifier si la connexion fonctionne correctement.

### 5. Réglages Additionnels (si nécessaire) :

- Selon la caméra, vous pourriez avoir besoin de configurer d'autres paramètres tels que le flux vidéo, la détection de mouvement, etc.

### 6. Accès à la Caméra via le Synology :

- Vous pouvez maintenant accéder au flux vidéo de votre caméra via l'interface Surveillance Station de votre Synology.

Assurez-vous de consulter les manuels de votre caméra spécifique et de votre serveur Synology pour des instructions détaillées, 
car les étapes peuvent varier en fonction des modèles. De plus, gardez à l'esprit que l'utilisation du protocole HTTP peut poser des problèmes de sécurité, 
il est donc recommandé d'utiliser HTTPS si votre caméra et votre Synology le prennent en charge.



## Astuce et tuo

- https://github.com/EliasKotlyar/Xiaomi-Dafang-Hacks
- https://community.jeedom.com/t/camera-wanscam-hw0021/61432
- https://openipc.org/
