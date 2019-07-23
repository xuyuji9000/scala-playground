- Generate new project: `sbt new scala/hello-world.g8`

- Run first time

``` bash
sbt 
~run
```

- Build Docker image: `sbt docker:publishLocal`

- Run Dokcer image:

``` bash
docker run hello-world:1.0
```
