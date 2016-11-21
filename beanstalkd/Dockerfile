FROM scratch
MAINTAINER lbbniu <lbbniu@qq.com>
ADD rootfs.tar.gz /
WORKDIR /
EXPOSE 11300
USER beanstalkd
ENTRYPOINT ["beanstalkd"]
CMD ["-p","11300"]
