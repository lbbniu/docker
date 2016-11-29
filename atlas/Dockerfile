FROM centos:6
MAINTAINER lbbniu <lbbniu@qq.com>
ADD Atlas-sharding_1.0.1-el6.x86_64.rpm /
WORKDIR /
RUN rpm -i Atlas-sharding_1.0.1-el6.x86_64.rpm \
	&& rm -f Atlas-sharding_1.0.1-el6.x86_64.rpm
EXPOSE 3306 2345
CMD ['/bin/bash']
