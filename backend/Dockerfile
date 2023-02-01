FROM node:12-alpine
ARG NODE_ENV=staging
WORKDIR /app
COPY . .
RUN npm install --silent
RUN npm run build
EXPOSE 3001
CMD ["node", "dist/main"]
