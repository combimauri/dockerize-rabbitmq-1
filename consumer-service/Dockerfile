FROM node:8

# Add everything in the current directory to our image, in the 'app' folder.
ADD . /app/consumer

# Install dependencies
RUN cd /app/consumer; \
    npm install

# Run our app.
CMD ["node", "/app/consumer/receive_logs.js"]