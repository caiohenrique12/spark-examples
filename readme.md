Build dockerfile

docker build --no-cache .

run jupyter in dokcer

docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook

access in browser

localhost:8888

more info: https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html
