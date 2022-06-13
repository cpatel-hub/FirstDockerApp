FROM node
RUN mkdir -p /home/queryservice

COPY ./package.json /home/queryservice
WORKDIR /home/queryservice
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 4003
CMD ["npm", "start"]