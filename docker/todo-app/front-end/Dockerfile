FROM node:16-alpine
WORKDIR /app_frontend
COPY . /app_frontend
ADD node_modules.tar.gz /app_frontend
EXPOSE 3000
CMD ["npm", "start"]
