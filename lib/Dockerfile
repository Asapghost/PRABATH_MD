FROM quay.io/asapghost/secktor
RUN git clone https://github.com/Asapghost/PRABATH_MD /root/prabathLK
WORKDIR /root/prabathLK/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
