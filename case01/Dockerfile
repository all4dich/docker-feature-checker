FROM python:3.6.14-slim
ADD .. /work
RUN pip3 install -r /work/requirements.txt
CMD ["python3", "/work/src/rabbitmq/sender.py"]