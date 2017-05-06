#编译镜像
git clone https://github.com/chenmins/dockerlib.git
cd dockerlib/mysql/5.5
docker build -t chenmins/mysql:5.5 .