FROM python:3.10.12-bullseye
# include all modules in requirements.txt
COPY requirements.txt /tmp/
RUN pip install --retries 5 --default-timeout 100 -r /tmp/requirements.txt


