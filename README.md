# Steps to run
1. Run 
```
mvn liberty:run
```
2. Stop the server after seeing the 
```
The defaultServer server is ready to run a smarter planet.
```
3. Run
```
mvn package
```
4. Run
```
docker build -t app-name .
```
5. Run
```
docker run --name app-name --rm -p 9080:9080 app-name
```
