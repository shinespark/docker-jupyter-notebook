# docker-jupyter-notebook

* from [jupyter/datascience-notebook - Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook/)
* enable JupyterLab
* mount volume

## Run

```
$ docker-compose build
$ docker-compose up
```

Access http://localhost:8888/?token=xxxxxxxx

## Edit Config

```
$ docker-compose exec jupyter sh
$ jupyter notebook --generate-config
$ exit

$ vi ./data/notebook/.jupyter/jupyter_notebook.config.py
```
