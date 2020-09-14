FROM tiangolo/uwsgi-nginx-flask:python3.8
ENV UWSGI_CHEAPER 1
ENV UWSGI_PROCESSES 2
COPY ./app /app

# For dev purposes comment lines above and uncomment below.
# FROM python:3.8.5
# RUN pip install flask

# WORKDIR /app
# # RUN pip install -r requirements.txt
# ENTRYPOINT ["python"]
# CMD ["app.py"]