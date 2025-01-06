# spring-boot-mongo-docker-kkfunda

- Environment Variables for the application

- MONGO_DB_USERNAME
- MONGO_DB_PASSWORD
- MONGO_DB_HOSTNAME


- docker run -d --name manam2 --network mynet -p 80:8080 -e MONGO_DB_USERNAME=admin -e MONGO_DB_PASSWORD=java -e MONGO_DB_HOSTNAME=mongodb dockerswaha/userdata:1.0.0
- docker run -d --name mongodb --network mynet -v myvol:/data/db -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=java mongo
