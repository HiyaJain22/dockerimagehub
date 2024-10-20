FROM python:3.8-alpine
# all the files which are present copy it in the app folder of docker container
# that . means local repo
COPY . /app1
WORKDIR /app1
RUN pip install -r requirements.txt
CMD python app1.py
