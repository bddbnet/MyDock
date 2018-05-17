FROM ghost:latest

MAINTAINER Xiyou <xiyou9981@gmail.com>
WORKDIR /usr/src/ghost
ADD config.js  /usr/src/ghost/config.js
ADD ghost.sh   /usr/src/ghost/ghost.sh
RUN npm install -g cnpm --registry=https://registry.npm.taobao.org && cnpm install -g forever

CMD /bin/bash && sh /usr/src/ghost/ghost.sh
#CMD /bin/bash

EXPOSE 2368
