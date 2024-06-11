FROM python:3.9
WORKDIR /app
ADD . /app
EXPOSE 8081
RUN pip install redis
CMD python main.py