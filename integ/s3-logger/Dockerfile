FROM public.ecr.aws/amazonlinux/amazonlinux:2

RUN yum upgrade -y
RUN yum install -y openssl

COPY logscript.sh /

CMD ["bash", "/logscript.sh"]
