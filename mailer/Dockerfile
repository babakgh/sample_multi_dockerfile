FROM smebberson/alpine-nodejs:3.0.1

# Setup environment variables.
ENV NODE_ENV=development

# Build the npm modules.
ADD root/app/package.json /app/package.json
ADD root/app/.npmrc /app/.npmrc
RUN cd /app && npm install --production

# Add image source
ADD root /

