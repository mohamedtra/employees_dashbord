FROM node:alpine
# Creation du repertoire de travail de l'application
WORKDIR '/app'
#copie de toutes les fichiers json vers le repertoire de travail
COPY . .
#nettoyage du cache
RUN npm cache clean
#Installation des dépendences
RUN npm install
# Execute le code pour le lancement de l'application
CMD ["npm","start"]
