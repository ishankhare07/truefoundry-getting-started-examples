FROM python:3.9
COPY ./requirements.txt /tmp/
RUN pip install -U pip && pip install -r /tmp/requirements.txt
RUN sleep 100
COPY . ./app
WORKDIR app
ENTRYPOINT python app.py