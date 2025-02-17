FROM node:lastest
USER node
WORKDIR /home/node
COPY --chown=node:node . .
RUN npm install && npx tsc
EXPOSE 3000
CMD ["node", "./build/index.js"]
