# FROM python:3.9
FROM  python:3.12.3-alpine

RUN pip install mkdocs
# LABEL key="value"
WORKDIR /app
COPY . .
RUN mkdocs build

WORKDIR /app/site
EXPOSE 8000

# CMD mkdocs serve --dev-addr=0.0.0.0:8000
CMD python -m http.server 8000
