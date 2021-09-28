# Recruitment Project

For launch project you need to run command:
```
docker-compose up
```
When application with two containers is running you can upload file via command:
```
curl -F "file=@abc.txt" 0.0.0.0:8080/upload
```
To check that the file is uploaded to both containers please type:
```
curl 0.0.0.0:8090/list
```
```
curl 0.0.0.0:8080/list
```

# fileUploadingWithDocker
