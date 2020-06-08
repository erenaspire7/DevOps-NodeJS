FROM python:3.7.3-alpine

ENV APP_HOME /app
WORKDIR $APP_HOME

COPY ["requirements.txt", "app.py", "./"]


RUN pip install -r requirements.txt

ENTRYPOINT ["python"]
CMD ["app.py"]