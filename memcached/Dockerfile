FROM scratch
MAINTAINER lbbniu <lbbniu@qq.com>
ADD rootfs.tar.gz /
WORKDIR /
EXPOSE 11211
USER memcache
ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["memcached"]
