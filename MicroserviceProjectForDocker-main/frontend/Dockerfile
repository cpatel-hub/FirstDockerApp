FROM node
RUN mkdir -p /home/frontend

COPY ./package.json /home/frontend
WORKDIR /home/frontend
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 3000
CMD ["npm", "start"]