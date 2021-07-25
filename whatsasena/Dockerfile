FROM fusuf/whatsasena:latest

RUN https://github.com/imashnidusha/WhatsAsena.git /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV REPO="https://imashnidusha/WhatsAsena"
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["run.sh"]
