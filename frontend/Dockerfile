FROM node:alpine

CMD [ "mkdir", "/app/frontend/" ]

WORKDIR /app/frontend

COPY ./apps/frontend/ .

RUN pnpm install

RUN pnpm run build

EXPOSE 3000

CMD [ "pnpm", "start" ]