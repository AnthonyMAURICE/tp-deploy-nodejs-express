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

# L'application sera disponible sur `http://localhost:9000/`