
cd Newskillbackend_Production/
ls -lrt
cd Backend/
ls -lrt
docker -v
sudo chmod 777 mongo-db.sh
./mongo-db.sh
update the IP in the .env file
docker build -t backend-docker .
docker run --name backend-docker -d -p 5000:10000 backend-docker
docker ps -a

 