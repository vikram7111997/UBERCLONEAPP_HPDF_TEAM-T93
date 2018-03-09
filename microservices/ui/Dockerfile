FROM mhart/alpine-node:7.6.0

WORKDIR /app

# Add package.json
ADD app/package.json

#install node modules and all the dependencies
RUN sudo npm install

#Add the source code
ADD /app

CMD ["npm", "start"]
