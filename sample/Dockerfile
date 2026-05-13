FROM python:3.8-alpine
RUN mkdir /app && \
    pip install --no-cache-dir --upgrade wheel==0.46.2
COPY . /app
WORKDIR /app
CMD ["python3", "app.py"]
