FROM node:12-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
EXPOSE 9898
CMD ["node", "src/index.js"]