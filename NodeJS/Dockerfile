FROM node:alpine
# Creation du repertoire de travail de l'application
WORKDIR '/app'
#copie de toutes les fichiers json vers le repertoire de travail
#copie de toutes les fichiers json vers le repertoire de travail
COPY . .
#Installation des dépendences
RUN npm install
#le port vue de l'exterieur
Expose 3005
# Execute le code pour le lancement de l'application
CMD ["node","index.js"]
