# Afin de lancer l'application, suivre les étapes suivantes :

# Via le Dockerfile uniquement
1.  Lancer un terminal et se placer dans le répertoire `AppCars`
2.  Éxécuter la commande : `docker build -t nodeapp` qui se basera sur le Dockerfile
3.  Éxécuter la commande : `docker run --name mynodeapp -d -p 9000:3000 nodeapp` pour créer le container qui prendra le nom "mynodeapp"

---

# Via docker-compose
1. Lancer un terminal à la racine du projet (où se trouve le fichier `docker-compose.yml`)
2. Éxécuter la commande `docker compose up -d`

---

# Si le container existe déjà :
1. Dans un terminal éxécuter la commande : `docker start mynodeapp` pour démarrer le container si stoppé
2. pour l'arrêter : `docker stop mynodeapp`

---

# L'application sera disponible sur [http://localhost:9000](http://localhost:9000)