FROM node:18-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]

ENV MYSQL_HOST=mysql
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=4697
ENV MYSQL_DB=todos

EXPOSE 3000

