FROM python:3.8-slim

WORKDIR /app

COPY . .

RUN pip install hovercraft

EXPOSE 8000
EXPOSE 8002

CMD ["sh", "-c", "hovercraft html.rst & python3 -m http.server 8002"]
