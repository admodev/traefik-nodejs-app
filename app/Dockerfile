FROM node:18.19.1


RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY dist/final.js .

EXPOSE 5000
CMD ["node","final.js"]

