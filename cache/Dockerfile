# Pull the base image.
FROM redis

# Setup the timezone
RUN echo "Australia/Melbourne" | tee /etc/timezone && dpkg-reconfigure --frontend noninteractive tzdata

