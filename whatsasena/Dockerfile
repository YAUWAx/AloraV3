FROM fusuf/whatsasena:latest

RUN git clone https://github.com/YAUWAx/AloraV3 /root/AloraV3
WORKDIR /root/AloraV3/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
