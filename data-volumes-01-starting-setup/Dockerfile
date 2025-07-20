FROM node 

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app 

ENV PORT=80

EXPOSE $PORT

#anonymous volume
#VOLUME [ "/app/feefback" ]

CMD ["npm", "start"]