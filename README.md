# tid.io

For keeping your apartment tidio


## Installation of dev environment

### Ubuntu

```
apt-get -y update
apt-get -y install build-essential zlib1g-dev libssl-dev libreadline6-dev libyaml-dev
cd /tmp
wget http://ftp.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p0.tar.gz
tar -xvzf ruby-2.0.0-p0.tar.gz
cd ruby-2.0.0-p0/
./configure --prefix=/usr/local
make
make install
```
