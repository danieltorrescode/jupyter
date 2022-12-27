# Jupyter

[jupyter/docker-stacks](https://github.com/jupyter/docker-stacks)

```
docker run --name jupyter -p 10000:8888 \
  -e JUPYTER_ENABLE_LAB=yes \
  -v ~/Downloads/Projects/jupyter:/home/jovyan/work jupyter/datascience-notebook:latest
```

