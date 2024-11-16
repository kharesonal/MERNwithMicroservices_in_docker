#This sets the base image for your container.
FROM node:20
#sets the working directory inside the container to /app.
WORKDIR /app
#This copies all files and folders from your current directory (on your host machine) to the /app directory in the container.
COPY . .
#This runs npm install inside the container to install all the dependencies listed in your package.json file.
RUN npm install
#This tells Docker that the application inside the container listens on port 3001.
EXPOSE 3001
#This sets the default command to run when the container starts
CMD [ "node", "index.js" ]
