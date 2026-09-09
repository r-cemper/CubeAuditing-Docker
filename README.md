## CubeAuditing-Docker
The related Pull request was ignored for so long. It's here now     
### Prerequisites
Make sure you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Docker desktop](https://www.docker.com/products/docker-desktop) installed.
### Installation
Clone/git pull the repo into any local directory
```
$ git clone https://github.com/r-cemper/CubeAuditing_Docker.git
```
To build and start the container run:
```
$ docker compose up -d && docker compose logs -f
```
To open IRIS console do:
```
$ docker-compose exec iris iris session iris
USER>
```
or using *iterm**
```
http://localhost:42773/iterm/
```
To access IRIS System Management Portal
```
http://localhost:42773/csp/sys/UtilHome.csp
```
### How to use it
This presents OEX package [CubeAuditing](https://openexchange.intersystems.com/package/MDX-Query-Auditing-Samples) using the actual IPM module    
All user documentation is found there in the [Article on DC](https://community.intersystems.com/post/monitoring-bi-cube-usage-and-cleaning-unused-cubes)  
