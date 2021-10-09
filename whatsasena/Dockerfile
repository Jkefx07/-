FROM fusuf/whatsasena:latest

RUN git clone https://github.com/jkefx07/𝐉𝐊 𝐁𝐎𝐓 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
