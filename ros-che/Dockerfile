FROM ros:indigo

# install ros packages
RUN apt-get update && apt-get install -y \
    vim \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /projects

CMD /ros_entrypoint.sh && tail -f /dev/null
