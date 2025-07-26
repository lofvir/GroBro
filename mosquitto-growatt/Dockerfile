ARG BUILD_FROM=python:3.11-alpine
FROM $BUILD_FROM

RUN apk add --no-cache mosquitto

WORKDIR /app
COPY . /app
RUN chmod +x ./run.sh

CMD [ "./run.sh" ]
