FROM python:3.6
RUN mkdir -p /home/ubuntu/hello_django/
WORKDIR /home/ubuntu/hello_django/
COPY ./* /home/ubuntu/hello_django/
RUN ls
RUN pip3 install -r /home/ubuntu/hello_django/requirements.txt
EXPOSE 8000
ENTRYPOINT ["/home/ubuntu/hello_django/bin/gunicorn_start"]
