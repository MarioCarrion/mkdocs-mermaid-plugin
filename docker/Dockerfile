FROM python:3.6.9-alpine3.10

COPY docker/readthedocs/ /mkdocs/readthedocs/

RUN apk --update upgrade && \
    apk add bash git && \
    pip install mkdocs==1.0.4 && \
    pip install git+https://github.com/MarioCarrion/mkdocs-mermaid-plugin.git
