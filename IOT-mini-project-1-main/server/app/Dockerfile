FROM python:3.8-slim

WORKDIR /app

COPY . .

RUN pip3 install --upgrade cython && \
    pip3 install -r requirements.txt

EXPOSE 5683

CMD ["python", "server.py"]