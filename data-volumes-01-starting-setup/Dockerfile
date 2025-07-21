FROM node 

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app 

ARG DEFAULT_PORT=80

ENV PORT=DEFAULT_PORT

EXPOSE $DEFAULT_PORT

#anonymous volume
#VOLUME [ "/app/feefback" ]

CMD ["npm", "start"]