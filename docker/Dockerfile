FROM python:3.11.0a2-alpine

LABEL maintainer="Bruce Bentley <brucebentley@me.com>"

VOLUME "/backup"
WORKDIR /backup

RUN pip --no-cache-dir install SlackCleaner

CMD ["python", "-"]
