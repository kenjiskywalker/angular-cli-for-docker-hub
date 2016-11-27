# angular-cli-for-docker-hub

angular-cli for Docker Hub

```
FROM node:XXX

ENV NPM_VERSION XXX
ENV ANGULAR_CLI_VERSION XXX

RUN npm install -g npm@$NPM_VERSION
RUN npm install -g angular-cli@$ANGULAR_CLI_VERSION
```

