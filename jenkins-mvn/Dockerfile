FROM jenkins

# USER root 

RUN cd /tmp \
	&& wget http://www-us.apache.org/dist/maven/maven-3/3.5.3/binaries/apache-maven-3.5.3-bin.tar.gz \
	&& tar xzvf apache-maven-3.5.3-bin.tar.gz 
	# && mv apache-maven-3.5.3 /opt \
	# && PATH=/opt/apache-maven-3.5.3/bin:$PATH
	# && PATH=/tmp/apache-maven-3.5.3/bin:$PATH \
	# && echo $PATH

ENV PATH="/tmp/apache-maven-3.5.3/bin:${PATH}"

# USER usersetup
