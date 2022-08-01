FROM thecodingmachine/nodejs:14

COPY . .

RUN apt-get update
RUN apt-get install curl wget git

EXPOSE 3000

CMD [ "node index.js" ]