# tên image : [version của image đó]
FROM node:10  


# app directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
# copy tất cả những thứ mình có lên working directiory 
COPY . .
# EXPOSE 8080 tức là mình sử dụng port 8080 trên docker chứ không phải trên máy của mình
EXPOSE 8080

CMD ["node","index.js"]