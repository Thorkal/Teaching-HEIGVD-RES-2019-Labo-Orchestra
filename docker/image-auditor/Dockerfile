# FROM node:latest
FROM node:4.3.1

MAINTAINER Tommy Gerardi <tommy.gerardi@heig-vd.ch>

# ../../app/Musician/src
COPY src /opt/app/

# Permet de builder l'app
WORKDIR /opt/app/
RUN npm install

ENTRYPOINT ["node", "/opt/app/auditor.js"]