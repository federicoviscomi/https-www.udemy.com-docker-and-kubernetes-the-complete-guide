# Use an existing docker image as a base
FROM alpine

# Download and install a dependency
RUN apk add --update redis

# On container startup
CMD ["redis-server"]

