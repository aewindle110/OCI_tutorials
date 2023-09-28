# OCI_tutorials
Tutorials on how to access and process PACE OCI data

Once you have pulled the repo down locally via git and have Docker installed all code here can be run fully in Docker based on a prebuilt environment by running:

docker run -it -v <location of code>:/home/jovyan --rm -p 8888:8888 pangeo/pangeo-notebook:2021.05.15 jupyter lab --ip 0.0.0.0

This will launch a Jupyter Lab instance that can run everything for you. This can also be easily done in the cloud if you have a cloud environment that can be launched with a Docker image.
