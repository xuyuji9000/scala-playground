- Run application local: `sbt run`

- Build Docker image: `sbt docker:publishLocal`

``` bash
docker build --build-arg JAR_FILE=target/scala-2.12/akkahttp-quickstart-assembly-0.1.jar \
-t akka-http-playground .
```

- Run container local: `docker run --rm -p 8080:8080 akka-http-playground`
