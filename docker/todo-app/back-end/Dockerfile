FROM node:16-alpine
WORKDIR /app_backend
COPY . /app_backend
ADD node_modules.tar.gz /app_backend
EXPOSE 3001
CMD ["npm", "start"]
