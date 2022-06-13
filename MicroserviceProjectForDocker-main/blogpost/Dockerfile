FROM node
RUN mkdir -p /home/blogpost

COPY ./package.json /home/blogpost
WORKDIR /home/blogpost
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 4001
CMD ["npm", "start"]