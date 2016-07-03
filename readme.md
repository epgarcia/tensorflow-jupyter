##dockerfile-tensorflow-jupyter
Dockerized Jupyter with tensorflow, tflearn & tensorboard

##Get Started
With port forwarding:
```
docker run -d -p 8888:8888 -p 6006:6006 tetmin/tensorflow-jupyter
```
For persistent storage:
```
docker run -d -p 8888:8888 -p 6006:6006 -v /notebook:/notebook tetmin/tensorflow-jupyter
```
Just browse localhost:8888 and write code for tensorflow!
