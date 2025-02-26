FROM node:20-alpine

WORKDIR /usr/src/app

# Copy the rest of the source files into the image.
COPY . .

RUN npm install
# Expose the port that the application listens on.
EXPOSE 3000

ENTRYPOINT [ "node", "app.js" ]