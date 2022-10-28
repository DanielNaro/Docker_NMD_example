FROM r-base:latest
RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get -y install libcurl4-openssl-dev
RUN apt-get -y install libv8-dev libnode-dev
RUN R -e "install.packages('V8')"
RUN apt-get -y install cmake
RUN R -e "install.packages('rstanarm')"
