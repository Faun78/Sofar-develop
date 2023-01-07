FROM python:3.10

ADD inverter /inverter
ADD run.sh /


RUN pip install paho-mqtt anyconfig && chmod 755 /run.sh

CMD [ "/run.sh" ]