FROM       node:16
EXPOSE     8080
WORKDIR    /opt/server
COPY       package.json /opt/server
RUN        npm install -y
COPY       package.json /opt/server
ENTRYPOINT [ "node" , "server.js"]




# FROM node:14

# ENV INSTANA_AUTO_PROFILE true

# EXPOSE 8080

# WORKDIR /opt/server

# COPY package.json /opt/server/

# RUN npm install

# COPY server.js /opt/server/

# CMD ["node", "server.js"]

