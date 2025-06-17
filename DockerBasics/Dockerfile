FROM python:3.9-slim
# all the files which are present copy it in the app folder of docker container
# that . means local repo
COPY . /app1
WORKDIR /app1
EXPOSE 5000
RUN pip install -r requirements.txt
CMD ["python", "app1.py"]
