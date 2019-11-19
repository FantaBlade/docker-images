FROM node:10-alpine

RUN npm install verbose gitbook-cli -g # install gitbook  \
    && gitbook fetch 3.2.3 # fetch final stable version \
    && gitbook install # add any requested plugins in book.json \