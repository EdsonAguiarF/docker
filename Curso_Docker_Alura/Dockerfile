FROM node:14
#variável para utilizar nos comandos COPY, RUN e ENTRYPOINT como "."
WORKDIR /app-node 
ARG PORT=3000
ENV PORT=$PORT
EXPOSE $PORT
COPY ./node .
RUN npm install .
ENTRYPOINT npm start .
