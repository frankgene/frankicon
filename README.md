# frankicon
A SVG Icon font management platform.
```bash
# 下载镜像
wget http://img.frankgene.top/frankicon.tar
# 导入镜像
docker load -i frankicon.tar
# 创建容器，建立一个到容器内3000端口的映射，如果由防火墙记得开
docker run -p 13030:3000 --name=myicon --restart=always frankgene/frankicon /bin/bash -c 'bash /app/service.sh'
```

![](https://cdn.nlark.com/yuque/0/2024/png/22773386/1728036459842-cfefb646-8bee-49c2-901c-5fccdc3de920.png)

出现上面的结果后即可关闭终端，打开浏览器访问（http://<服务器IP地址>:<容器外端口>/home）

![](https://cdn.nlark.com/yuque/0/2024/png/22773386/1728035775367-b360002a-c53a-4523-a0a3-7945b1f60a78.png)

![](https://cdn.nlark.com/yuque/0/2024/gif/22773386/1728042501916-a12e7403-a0db-4c50-848e-dde8e6b279f4.gif)
