FROM node:8

# Add everything in the current directory to our image, in the 'app' folder.
ADD . /app/producer

# Install dependencies
RUN cd /app/producer; \
    npm install

# Run our app.
CMD ["node", "/app/producer/emit_log.js"]