FROM node:6

RUN rm -rf /var/lib/apt/lists/*

WORKDIR /usr/bin/app

RUN git clone https://github.com/jscad/OpenJSCAD.org

WORKDIR /usr/bin/app/OpenJSCAD.org/packages/web

RUN npm install

RUN cp ../examples ./examples

CMD ["npm","run","start-dev"]
