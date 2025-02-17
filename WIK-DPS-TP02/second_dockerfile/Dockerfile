FROM node:latest
USER node
WORKDIR /home/node/app
COPY --chown=node:node . .
RUN npm install && npx tsc

FROM node:lastet
USER node
WORKDIR /home/node/app
COPY --from=0 --chown=node:node /home/node/app/build .
EXPOSE 3000
CMD ["node", "./index.js"]