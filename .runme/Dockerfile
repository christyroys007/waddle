FROM python:latest
WORKDIR /app
COPY . .
ENTRYPOINT pip install -r requirements.txt && python3 -m tgfilestream
