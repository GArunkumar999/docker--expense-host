FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js . 
RUN npm install 
ENV DB_HOST="127.0.0.1"
CMD ["node", "index.js"]


# must give space for docker var