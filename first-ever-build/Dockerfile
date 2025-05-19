FROM python:3

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY my-app.py .

CMD ["python","./my-app.py"]


# docker build -t my-docker-image -f Dockerfile
# docker build -t my-docker-image .  - will look for Dockerfile in current directory (.)