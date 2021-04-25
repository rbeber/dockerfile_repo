FROM rbeber/ubuntu18_miniconda:1.0

LABEL maintainer="raniero.beber@gmail.com"
LABEL version="1.0"
LABEL description="Geopandas utils"

#install geopandas from conda-forge
RUN conda install -c conda-forge geopandas
#install dbf from anaconda
RUN conda install -c anaconda dbf