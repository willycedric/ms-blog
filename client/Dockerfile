FROM node:alpine
ENV CI=true
ENV NODE_OPTIONS=--openssl-legacy-provider
WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]