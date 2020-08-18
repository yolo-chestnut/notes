docker registry

[参考链接](https://blog.csdn.net/yaomingyang/article/details/103978347)

[私有仓库删除插件](https://github.com/burnettk/delete-docker-registry-image)

[docker关于删除的文档](https://docs.docker.com/registry/configuration/#delete)

**常用API：**

[参考链接](https://blog.csdn.net/kan2016/article/details/86105354)

查看所有版本镜像

http://ip:5000/v2/_catalog

查看某镜像所有版本

http://ip:5000/v2/镜像名/tags/list

GET - 查看某版本镜像信息

DELETE - 删除某版本镜像

http://ip:5000/v2/镜像名/manifests/版本号(或者digest)
