FROM node:22 as dev
WORKDIR /app/general
COPY ./GeneralRedirectService .
COPY ./GeneralRedirectService/.prod.env .env
RUN npm install
EXPOSE 6001
CMD [ "npm", "start" ]