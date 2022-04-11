FROM node:alpine3.15

# local ip
ENV BACKEND_URL ${BACKEND_URL}
ENV FRONTEND_PORT=8000

WORKDIR /moviemaker/ui

COPY . .

EXPOSE 8000

RUN npm install

CMD [ "npm","start" ]