FROM node:latest
WORKDIR /resume
ADD . .
EXPOSE 4200
RUN npm install # Installing dependencies
RUN npx ng build # Building the Stuff
CMD npm start