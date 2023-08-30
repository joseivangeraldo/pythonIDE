from centos:latest
RUN yum install python -y
RUN yum install firefox -y
RUN pip3 install notebook

CMD /usr/bin/firefox
CMD jupyter-notebook --allow-root