FROM python:3.6
RUN mkdir -p /home/ubuntu/hello_django/
WORKDIR /home/ubuntu/hello_django/
ADD ./* /home/ubuntu/hello_django/
RUN pip3 install -r /home/ubuntu/hello_django/requirements.txt
VOLUME /home/ubuntu/hello_django/run/
EXPOSE 8000
ENTRYPOINT ["/home/ubuntu/hello_django/bin/gunicorn_start"]
