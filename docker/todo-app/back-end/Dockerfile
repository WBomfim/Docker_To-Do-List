FROM node:16-alpine
WORKDIR /todo_backend
COPY . /todo_backend
ADD node_modules.tar.gz /todo_backend
EXPOSE 3001
CMD ["npm", "start"]
