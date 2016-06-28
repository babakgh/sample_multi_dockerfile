# Node.js v5.9.x
FROM smebberson/alpine-nodejs:3.1.0

# Setup environment variables
ENV NODE_ENV production

# Build the npm modules
ADD root/app/package.json .npmrc /app/
RUN cd /app && \
    npm install --production

# Add image source
ADD root /

# Expose the port and start the application
EXPOSE 4000

