FROM node
WORKDIR /bezkoder_app
COPY package.json .
RUN npm install -g npm@9.1.2
RUN npm install --maxsockets=1
COPY . .
CMD npm run build && npm run start
