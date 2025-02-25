ARG IGNITION_VERSION
FROM inductiveautomation/ignition:${IGNITION_VERSION}

USER root

RUN apt-get -y update
RUN apt-get -y install git

COPY *.modl /usr/local/bin/ignition/user-lib/modules/