# Using official python runtime base image
FROM ubuntu:18.04

RUN apt-get update && apt-get -y install \
    curl apt-transport-https systemd ca-certificates software-properties-common

COPY . /usr/src/app/

RUN chmod 755 /usr/src/app/entrypoint.sh
# RUN chmod +x script.sh
RUN /usr/src/app/entrypoint.sh
# ENTRYPOINT ["/usr/src/app/entrypoint.sh"]

# ENTRYPOINT ["./entrypoint.sh"]

# Make port 80 available for links and/or publish
EXPOSE 80
