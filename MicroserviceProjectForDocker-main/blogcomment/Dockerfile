FROM node
RUN mkdir -p /home/blogcomment

COPY ./package.json /home/blogcomment
WORKDIR /home/blogcomment
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 4002
CMD ["npm", "start"]