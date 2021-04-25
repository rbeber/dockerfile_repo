FROM rbeber/geopandas:1.0

LABEL maintainer="raniero.beber@gmail.com"
LABEL version="1.06"
LABEL description="ps_converter"

#install vim

RUN apt-get update && apt-get install -y vim git

#Set working directory
RUN mkdir home/work && mkdir home/work/data

WORKDIR home/work/

RUN git clone https://github.com/rbeber/PSutils.git