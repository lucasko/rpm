docker run --rm -it -v $PWD:/download/ centos:7 bash

yum install --downloadonly --downloaddir=/download/spawn -y spawn
rpm -ivh */*.rpm
