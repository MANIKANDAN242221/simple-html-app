# simple-html-app

cd  sample-html-docker-application

mvn clean install

docker build -t html-application  .

docker run -d -p 80:80 html-application

docker ps 
