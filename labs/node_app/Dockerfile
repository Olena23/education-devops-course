FROM node:alpine3.10

ENV PORT="3000"
ENV HOST="0.0.0.0"

WORKDIR /app

COPY . .

RUN npm install

ENTRYPOINT ["npm"]

CMD ["start"]