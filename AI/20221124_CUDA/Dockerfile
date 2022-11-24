# Base Image
FROM nvidia/cuda:11.0.3-base-ubuntu20.04

# Update images
RUN apt update -y
RUN apt install -y python3
RUN apt install -y python3-pip

# Update Python packages
RUN pip3 install Jupyter
RUN pip3 install jupyterlab
RUN pip3 install pandas
RUN pip3 install numpy
RUN pip3 install torch

# Make work directory
RUN mkdir -p /opt/notebook/work/
