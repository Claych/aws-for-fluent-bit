FROM public.ecr.aws/amazonlinux/amazonlinux:2

RUN yum upgrade -y && yum install -y python3 pip3

RUN pip3 install boto3

WORKDIR /usr/local/bin

COPY validator.py .

CMD ["python3", "validator.py"]
