# Jupyter

[jupyter/docker-stacks](https://github.com/jupyter/docker-stacks)

```
docker run --name jupyter -p 10000:8888 \
  -e JUPYTER_ENABLE_LAB=yes \
  -v /home/daniel/jupyter:/home/jovyan/work jupyter/datascience-notebook:33add21fab64
```

