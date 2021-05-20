FROM fusuf/whatsasena:latest

RUN git clone https://github.com/asangaudara/Sample /root/Sample
WORKDIR /root/Sample/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
