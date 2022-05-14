FROM python:3.6
RUN pip install -r reqirements.txt
COPY   . /app/Devops
WORKDIR /app
EXPOSE 8080/tcp
CMD ["python", "app.py"]
