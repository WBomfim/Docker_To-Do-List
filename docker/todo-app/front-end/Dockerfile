FROM node:16-alpine
WORKDIR /todo_frontend
COPY . /todo_frontend
ADD node_modules.tar.gz /todo_frontend
EXPOSE 3000
CMD ["npm", "start"]
