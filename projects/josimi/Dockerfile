FROM node:22-bookworm

WORKDIR /src

COPY . /src

RUN npm ci --ignore-scripts
RUN npm test
