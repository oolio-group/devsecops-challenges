FROM thecodingmachine/nodejs:14

COPY . .

RUN apt-get update
RUN apt-get install curl wget git
RUN npm install -g nodemon

EXPOSE 3000

CMD [ "npm start" ]