FROM python:3.9.14-slim

RUN pip install example-app-kc-vctormurillo -U

COPY integration-test.py .

ENTRYPOINT ["python", "integration-test.py"]
