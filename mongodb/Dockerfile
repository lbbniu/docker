FROM scratch
MAINTAINER lbbniu <lbbniu@qq.com>
ADD rootfs.tar.gz /
WORKDIR /data
RUN chown -R mongodb configdb db
WORKDIR /
RUN chown -R mongodb tmp
VOLUME /data/db /data/configdb
COPY lbbniu.sh /lbbniu.sh
EXPOSE 27017
USER mongodb
ENTRYPOINT ["/lbbniu.sh"]
CMD ["mongod"]
