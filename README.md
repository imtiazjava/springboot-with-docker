# springboot-with-docker

- After creating the springbootwithdocker project do the following things to build the image:
```
- docker build -t springboot-docker-demo:1.0 .
```
- In order to create the container for created above image use the following below command:
```
- docker run -p 8080:1122 springboot-docker-demo:1.0
```
- And finally open the browser and use  the below url:
```
http://localhost:8080/api/msg
```
