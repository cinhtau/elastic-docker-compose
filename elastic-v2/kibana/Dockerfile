ARG VERSION
FROM kibana:$VERSION
MAINTAINER Vinh Nguyên

RUN apt-get update && apt-get install curl -y && apt-get clean && /opt/kibana/bin/kibana plugin --install elastic/sense