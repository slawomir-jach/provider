FROM registry-testing.kazan.atosworldline.com/sandbox/stf-multiarch:latest

USER root
RUN mkdir /data && chown stf:stf /data
USER stf
VOLUME ["/data"]
