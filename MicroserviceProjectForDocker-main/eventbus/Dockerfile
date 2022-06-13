FROM node
RUN mkdir -p /home/eventbus

COPY ./package.json /home/eventbus
WORKDIR /home/eventbus
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 4005
CMD ["npm", "start"]