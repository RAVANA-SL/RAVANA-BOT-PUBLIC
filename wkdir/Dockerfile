FROM fusuf/whatsasena:latest

RUN git clone https://github.com/RAVANA-SL/RAVANA-BOT-PUBLIC /root/4.5
WORKDIR /root/4.5/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
