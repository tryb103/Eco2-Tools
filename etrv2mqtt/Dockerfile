FROM python:3.8
WORKDIR /app

RUN pip3 install 'git+https://github.com/tryb103/etrv2mqtt'

CMD [ "etrv2mqtt", "/data/options.json" ]
