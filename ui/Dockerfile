FROM node:alpine3.15

# local ip
ENV BACKEND_URL ${BACKEND_URL}
ENV FRONTEND_PORT ${FRONTEND_PORT}

WORKDIR /moviemaker/ui

COPY . .

EXPOSE 8000

RUN npm install
RUN apk add curl

CMD [ "npm","start" ]
