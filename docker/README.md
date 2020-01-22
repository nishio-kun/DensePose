first, run
```
$ mkdir input
$ mkdir output
```
put images in ./input/
then, run
```
$ docker build -t densepose .
$ nvidia-docker run -itd densepose bash
$ nvidia-docker exec -it <container ID> bash
```
finally, in the docker container, run
```
$ bash main.sh
```
