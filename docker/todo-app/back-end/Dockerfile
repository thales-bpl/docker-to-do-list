FROM node:14-alpine AS build
WORKDIR /todo-app
COPY . /back-end
EXPOSE 3001
# ENTRYPOINT [ "bin/bash" ]
# node_modules.tar.gz
CMD ["npm", "start"]