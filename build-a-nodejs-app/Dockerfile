FROM node:12-stretch

#USER node

COPY --chown=node:node index.js index.js

WORKDIR /home/node/src

ADD --chown=node:node index.js index.js

CMD ["node", "index.js"]