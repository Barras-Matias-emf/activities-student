# 1. Image de base légère
FROM node:20-alpine

# 2. Définir le répertoire de travail
WORKDIR ./app

# 5. Copier le reste du code source
COPY ./app/* .

# 4. Installer les dépendances
RUN npm install

# 6. Exposer le port de l'application
EXPOSE 3000

# 7. Commande pour lancer l'application
CMD ["node", "server.js"]
