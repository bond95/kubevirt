FROM centos:7

COPY virt-controller /virt-controller

ENTRYPOINT [ "/virt-controller" ]

RUN useradd -u 111 nonroot
USER nonroot
