FROM maven:3.8.6-eclipse-temurin-17

# Install Docker CLI inside the image (for building Docker images in pipeline)
RUN apt-get update && \
    apt-get install -y docker.io && \
    apt-get clean

CMD ["cat"]
