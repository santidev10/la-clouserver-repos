https://www.youtube.com/watch?v=KLOdisHW8rQ&ab_channel=kubucation

Usando el Dockerfile.pesado:

cloud_user@180fde7f1f1c:~/Documents/docker-examples/dockerfile-tutorial/multistage$ docker images
REPOSITORY   TAG       IMAGE ID       CREATED         SIZE
webserver    latest    0990c3da3fa7   8 minutes ago   719MB
golang       1.8       0d283eb41a92   4 years ago     713MB


Despues de hacer el Docker multistage:

cloud_user@180fde7f1f1c:~/Documents/docker-examples/dockerfile-tutorial/multistage$ docker images
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
webserver    latest    c51a1a8ff2cf   11 seconds ago   11.7MB
<none>       <none>    6f51119fc2e1   12 seconds ago   322MB
<none>       <none>    0990c3da3fa7   15 minutes ago   719MB
golang       alpine    011dbc9d894d   8 days ago       315MB
alpine       latest    c059bfaa849c   3 months ago     5.59MB
golang       1.8       0d283eb41a92   4 years ago      713MB
