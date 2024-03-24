FROM node:14.8
WORKDIR /
COPY ./package.json ./package.json
COPY ./src ./src
RUN yarn install 
EXPOSE 4000
CMD ["yarn", "server"]