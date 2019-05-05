FROM node:latest

MAINTAINER Isaia Spinelli <isaia.spinelli@heig-vd.ch>

COPY ../../app/Auditor/src /opt/app/

# Permet de builder l'app
WORKDIR /opt/app/
RUN npm install

ENTRYPOINT ["node", "/opt/app/auditor.js"]