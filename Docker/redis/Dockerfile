# Use an existing docker image as a base. Alpine provides unix env
FROM alpine

# Create a Work Directory
WORKDIR /usr/app

# Download and install a dependency
RUN apk add --update redis

# Tell the image what to do when it starts
# as a container
CMD ["redis-server"]