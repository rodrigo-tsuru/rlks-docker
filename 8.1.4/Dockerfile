FROM rodrigotsuru/ibmim-docker
MAINTAINER Rodrigo Tsuru "caixapostal@gmail.com"
RUN yum install -y curl \
unzip
RUN cd /tmp && \
curl -O -L https://delivery04.dhe.ibm.com/sar/CMA/RAA/03ywh/1/IBM_Rational_License_Key_Server_Linux_x86_ZIP.zip && \
unzip IBM_Rational_License_Key_Server_Linux_x86_ZIP.zip
