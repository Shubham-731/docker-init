# set the base image to create the image for react app
FROM node:20-alpine
# USER app
WORKDIR /app
COPY package*.json ./
# USER root
# RUN chown -R app:app .
# USER app
RUN npm install
COPY . .
EXPOSE 8000
CMD npm start
