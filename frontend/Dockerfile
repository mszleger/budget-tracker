FROM node:22-alpine

WORKDIR /app

ENV CI=true

COPY . .

RUN corepack enable && \
    pnpm install

EXPOSE 3000

CMD ["pnpm", "dev"]
