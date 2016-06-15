# nprima-stack

## Make sure docker is running and has a working ip

```
docker-machine kill default
docker-machine start default
eval $(docker-machine env default)
```

##Install

```
 git clone --recursive https://github.com/derek-adair/nprima-stack.git
 cd nprima-stack
 docker-compose build
 docker-compose up
```
## Update
 
```
  git remote update && git pull origin master
  git submodule foreach git pull origin master
```
