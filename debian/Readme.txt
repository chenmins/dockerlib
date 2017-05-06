#编译镜像
git clone https://github.com/chenmins/dockerlib.git
cd dockerlib/debian/jessie
docker build -t chenmins/debian:jessie_163 .