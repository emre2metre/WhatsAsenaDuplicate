FROM fusuf/whatsasena:latest

RUN git clone https://github.com/emre2metre/WhatsAsenaDuplicate /root/WhatsAsenaDuplicate
WORKDIR /root/WhatsAsenaDuplicate/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
