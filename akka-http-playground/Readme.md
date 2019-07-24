- Run application local: `sbt run`

- Create fat jar: `sbt clean compile assembly`

- Run container local: `docker run --rm -p 8080:8080 akka-http-playground`

- Build and push Docker image: `skaffold build`

- Deploy: `skaffold deploy`


- Access service: `curl https://scala.yogiman.cn/hello`