FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Itxxwasi/WASI_TECH_BOT /root/WASI_TECH_BOT
WORKDIR /root/WASI_TECH_BOT/ 
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
