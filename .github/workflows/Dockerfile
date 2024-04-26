FROM mohamed046/ry2dr:tag

# Mise à jour des paquets
RUN apt-get update -y 

# Copiez les fichiers de votre application dans le répertoire racine d'Apache
COPY . ./

# Exposez le port 8080 pour accéder à l'application
EXPOSE 8080
