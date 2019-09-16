FROM python:3.7.4-alpine

ADD ./requirements.txt /

RUN set -ex \
	&& pip install -r requirements.txt \
	&& rm -f /requirements.txt

CMD ["python3"]
