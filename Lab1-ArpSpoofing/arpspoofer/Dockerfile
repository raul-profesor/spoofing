FROM fedora:latest
RUN echo -e "sslverify=0" >> /etc/dnf/dnf.conf
RUN dnf -y upgrade
RUN dnf -y install dsniff

