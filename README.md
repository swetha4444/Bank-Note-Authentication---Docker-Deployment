# Bank Note Authentication - Docker Deployment
<img src="https://user-images.githubusercontent.com/68152189/127616327-4350809b-0b93-4a60-bbb3-65b5287c2ce7.png" width=500></img>

## Dockerize the Application
* Write requirments.txt
* Write Docker File
  * FROM
  * COPY
  * EXPOSE
  * RUN 
  * CMD
* Build Docker Image
```
docker build -t api_name .
```
  ![image](https://user-images.githubusercontent.com/68152189/127616127-d5362acd-6ec4-4b72-8b7b-41e8a58b9375.png)
* Run the Flask App
```
docker run -p 8000:8000 api_name
```

  ![image](https://user-images.githubusercontent.com/68152189/127619190-96550e40-f4c9-4f45-9a6b-5ffd929f2c15.png)

## Application deployed in Docker
#### Run in: 
```
http://192.168.99.100:8000/apidocs/
```
![image](https://user-images.githubusercontent.com/68152189/127618921-1244fe48-b024-490b-bf7f-0b5f6a8b0307.png)

