# SIT737-2023-t1-prac5d

## 1. Step
Create a sample node application
```
touch server.js
npm init --yes
npm install -s express
```
## 2. Create Dockerfile
```
touch Dockerfile
```

## 3. Build Image
```
docker build -t <imageName> .
```

## 4. Create docker-compose.yml
Enter the required informations

## 5. Create docker network
```
docker network create <myNetwork>
```
## 6. Connect container with that network
```
docker network connect myNetwork <imagename>
```
## 7. Connect to sh of one container
```
docker exec -it <containerID> sh
```
## 8. Ping the other container
```
ping <otherContainerName>
```