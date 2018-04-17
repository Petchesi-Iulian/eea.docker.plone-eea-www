FROM ipetchesi/eea.docker.plone-eea-www:latest-demo

COPY docker-setup.sh /
COPY warmup.ini /plone/instance/
RUN /docker-setup.sh
