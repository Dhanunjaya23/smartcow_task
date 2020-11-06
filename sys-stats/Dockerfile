FROM node:10

RUN mkdir -p /opt/app

# Add source files & deps
WORKDIR /opt/app
COPY . /opt/app
RUN rm -rf node_modules/* 
RUN npm install
EXPOSE 3000
#CMD ["/usr/local/bin/node", "/opt/app/src/App.js"]
ENTRYPOINT npm start

