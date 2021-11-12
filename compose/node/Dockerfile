FROM node:latest

# Make Directory - Workspace
RUN mkdir -p /app

# Work in the specific space
WORKDIR /app

COPY ./client/package.json ./

COPY ./client ./

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]