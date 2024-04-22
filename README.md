# DockerLab5

//Build :  
docker build -t moja-aplikacja:latest --build-arg SERVER_NAME=my-server --build-arg VERSION=1.0.0 .

//Run :  
docker run -d -p 8080:80 --name moj-kontener moja-aplikacja:latest

//Wynik (Curl) :  
curl http://localhost:8080

#Revutski Dzmitry
