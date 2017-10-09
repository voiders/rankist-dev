# rankist-dev
the best place to found and create ranking lists

## Getting started

```sh
git clone https://github.com/voiders/rankist-dev.git rankist-dev && cd rankist-dev
git submodule init && git submodule update
git submodule foreach git checkout develop
git submodule foreach npm install
docker-compose build
export MYSQL_ROOT_PASSWORD=root
export MYSQL_DATABASE=rankist
docker-compose up -d
open http://localhost:8000
```
And open [http://localhost:8000](http://localhost:8000)

## Add a new submodule

```sh
git submodule add https://github.com/voiders/<submodule_name>.git
cd <submodule_name> && npm install
```