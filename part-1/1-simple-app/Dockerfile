FROM node:20

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 3000

CMD ["node", "index.js"]



#FROM node:20          -> base-Image
#WORKDIR /usr/src/app  -> working-directory
#COPY . .              -> means, copy everything from this working directory folder to docker file.
#RUN npm install       -> it will install all the external dependencies.


#Interview-Q : should u copy over node modules from your file-system over to docker-image ? -> (ans - No)

