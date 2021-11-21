FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Chamodya-official/ALEXA-01 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/Chamodya-official/uploads
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit



CMD ["node", "bot.js"]
