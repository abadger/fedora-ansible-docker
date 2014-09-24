# Next version of fedora
FROM fedora:21
MAINTAINER Toshio Kuratomi <tkuratomi@ansible.com>
RUN yum -y update
RUN yum -y install PyYAML python-jinja2 python-httplib2 python-keyczar python-paramiko python-setuptools git python-pip
RUN pip install ansible