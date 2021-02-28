FROM python:3.9-buster
#RUN /usr/local/bin/pip install -U joblib --extra-index-url https://www.piwheels.org/simple
#RUN /usr/local/bin/pip install -U numpy --index-url https://www.piwheels.org/simple
#RUN /usr/local/bin/pip install https://piwheels.org/simple/numpy/numpy-1.9.3-cp35-cp35m-linux_armv7l.whl#sha256=b542e1f6c4dd53e18c42eb102214078279cb4bca1d183eeccd957da1edcfd024
RUN apt-get update
RUN apt-get -y install software-properties-common
RUN add-apt-repository main 
RUN apt-get update
RUN apt-get -y install libblas-dev liblapack-dev
RUN apt-get -y install gfortran
RUN /usr/local/bin/pip install -U scipy --extra-index-url https://www.piwheels.org/simple
