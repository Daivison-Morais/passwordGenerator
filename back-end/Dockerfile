FROM node

WORKDIR /src/usr/

COPY . .

EXPOSE 5000

RUN npm i
RUN npm run build
RUN npm run prisma:gerenate

CMD ["npm", "start"]