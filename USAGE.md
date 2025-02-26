# Afin de lancer l'application, suivre les étapes suivantes :

# Directement via le Dockerfile
1.  Lancer un terminal et se placer dans le répertoire `AppCars`, où se situe le Dockerfile
2.  Exécuter la commande : `docker build -t nodeapp` qui se basera sur le Dockerfile
3.  Exécuter la commande : `docker run --name mynodeapp -d -p 9000:3000 nodeapp` pour créer le container qui prendra le nom "mynodeapp" à partir de l'image nodeapp créée précédement

---

# Via docker-compose
1. Lancer un terminal à la racine du projet (où se trouve le fichier `docker-compose.yml`)
2. Exécuter la commande `docker compose up -d`

---

# Si le container existe déjà :
1. Dans un terminal exécuter la commande : `docker start mynodeapp` pour démarrer le container si stoppé
2. Pour l'arrêter : `docker stop mynodeapp`

---

L'application sera disponible sur [http://localhost:9000](http://localhost:9000)