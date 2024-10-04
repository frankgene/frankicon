# frankicon
A SVG Icon font management platform.
## Docker Image Download URL
http://img.frankgene.top/frankicon.tar
## Load Docker Image
docker load -i frankicon.tar
## Create Container
# 创建容器，建立一个到容器内3000端口的映射，如果由防火墙记得开
docker run -p 13030:3000 --name=myicon --restart=always frankgene/frankicon /bin/bash -c 'bash /app/service.sh'
# 完成后即可关闭终端（他默认会一直运行），打开浏览器访问（http://<服务器IP地址>:<容器外端口>/home）
