############################################################
# Dockerfile to build Zookeeper container images
# Based on Ubuntu
############################################################

# Set the base image to Ubuntu
FROM sukeshss/zookeeper

# File Author / Maintainer
MAINTAINER Sukesh SS

# Expose the default port
EXPOSE 2181

# Default port to execute the entrypoint (Zookeeper)
CMD ["--port 2181"]

# Set default container command
ENTRYPOINT /opt/zookeeper-3.4.5/bin/zkServer.sh start
