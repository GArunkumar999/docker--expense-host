FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js . 
RUN npm install 
#you can use 127.0.0.1 in place of localhost
ENV DB_HOST="localhost"
CMD ["node", "index.js"]


# must give space for docker var