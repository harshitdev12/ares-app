FROM node:16-alpine

ENV BACKEND_URL=http://0.0.0.0:6000

ADD . /app

WORKDIR /app

RUN npm install


ENTRYPOINT ["npm"]

CMD ["start"]