course: https://www.udemy.com/course/docker-kubernetes-the-practical-guide

#Volumes
Are read write by default

## names volumes 
there are saved even after container removal in contrast to annonymous containers if --rm argument is used or container is removed after shutdown.
Can be shared acress contianers

## bind mounts 
managed data by user

#Env and ARGs

Arguments seems to bahave like some kind of variable inside dokcerfile.

Envarionment works for whole container base on image.
