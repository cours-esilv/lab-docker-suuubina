FROM python:3.9
WORKDIR /app/back
COPY ./requirements.txt /app/back/requirements.txt
RUN pip install --no-cache-dir -r requirements.txt
COPY . /app/back
EXPOSE 5000
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
