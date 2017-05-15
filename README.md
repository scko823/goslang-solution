### goslang
This repo is solely for making a [docker compose](https://docs.docker.com/compose/) solution for [goslang](http://github.com/scko823/goslang)


### set up
clone this repo to your ```workdir``` of your choice

Clone down [goslang](http://github.com/scko823/goslang) and [goslang-ui](http://github.com/scko823/goslang-ui), either choose a different directory or just under this ```workdir```

To symlink the backend and ui,
```bash
ln -s $(working dir of goslang) backend
ln -s $(working dir of goslang-ui) .
```

To run the service with the docker-compose service,

```bash
docker-compose up
```
