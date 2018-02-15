# jdk-sbt

a docker file for a useful/portable sbt/scala environment

[Pull `jdk-sbt` from Docker Hub](https://hub.docker.com/r/rudenoise/jdk-sbt/)

```bash
docker pull rudenoise/jdk-sbt
```

```bash
# get a shell
docker run -ti rudenoise/jdk-sbt /bin/bash

# build local
docker build -t jdk-sbt:local .

# run
docker run -ti jdk-sbt:local /bin/bash

# tidy up
docker system prune
```
