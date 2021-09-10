FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Tornymark/Whatsdevil1 /root/Whatsdevil1
WORKDIR /root/Whatsdevil1/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
