FROM python:2.7

MAINTAINER Alan <ssisoo@live.cn>

ADD ./config/shadowsocks.json /etc/shadowsocks.json

RUN pip install shadowsocks

CMD ["ssserver","-c","/etc/shadowsocks.json"]

EXPOSE 8988
