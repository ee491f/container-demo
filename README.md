# Container Demo
A demonstration of the Django material for [EE491F](https://ee491f.github.io/course-material/#containers "EE491F Course Webpage").  
Accompanying Notes: [https://jamboard.google.com/d/11tQUEHEEhOFPUx1_mCC7pb5IsTzUO4kdFg83OYP6QTE/edit?usp=sharing](https://jamboard.google.com/d/11tQUEHEEhOFPUx1_mCC7pb5IsTzUO4kdFg83OYP6QTE/edit?usp=sharing "Jamboard")
Accompanying Videos:
* Overview: [TBD](TBD "Overview")
* Docker: [TBD](TBD "Docker")
* Docker Compose: [TBD](TBD "Docker Compose")

Docker Commands
---------------
1. `docker -v`
1. `docker pull nginx`
1. `docker images`
  - `docker image rm nginx`
1. `docker run nginx`
  - `docker run --name container-demo nginx`
  - `docker run --detach nginx`
  - `docker run --publish "8080:80" nginx`
  - `docker run --name container-demo --publish "8080:80" --detach nginx`
1. `docker ps`
  - `docker ps --all`
1. `docker stop container-demo`
1. `docker image rm nginx`

Docker Compose Commands
-----------------------
1. `docker compose version`
1. `docker compose pull`
1. `docker compose images web`
1. `docker compose up`
  - `docker compose up --detach`
1. `docker compose run web bash`
1. `docker compose ps`
1. `docker stop`
1. `docker start`
1. `docker restart web`
1. `docker down`
