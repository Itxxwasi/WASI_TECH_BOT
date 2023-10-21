FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/DENZO-UCHIWA/BLAST-MD /root/DENZO-UCHIWA
WORKDIR /root/DENZO-UCHIWA/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
