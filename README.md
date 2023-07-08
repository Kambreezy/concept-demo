
Install it and run:

```sh
npm install
npm start
```

Create the docker image

```sh
docker build -t dashboard:v1 .
```
Map desired port to 3000, run and start the container
```sh
docker run -p 80:3000 dashboard:v1 
docker ps
docker start <CONTAINER ID>
```

