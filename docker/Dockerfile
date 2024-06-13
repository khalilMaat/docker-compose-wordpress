FROM mongo

WORKDIR /db

RUN apt update -y

RUN echo "Mongo db image"

COPY . .

EXPOSE 27017

CMD ["mongod"]


