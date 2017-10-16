FROM continuumio/anaconda3:latest
MAINTAINER Ulrich Eck (firstname.lastname@tum.de)



RUN /opt/conda/bin/conda install jupyter -y --quiet
RUN mkdir /opt/notebooks

# install custom packages


ENTRYPOINT ["/opt/conda/bin/jupyter","notebook","--notebook-dir=/opt/notebooks","--ip='*'","--port=8888","--no-browser"]
EXPOSE 8888