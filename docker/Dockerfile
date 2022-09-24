#dockerfile
#使用 nginx最新版本作为基础镜像
FROM registry.cn-shenzhen.aliyuncs.com/sibionics_dev/nginx:1.20.1


#将当前文件夹的dist文件复制到容器的/etc/nginx/html/目录
COPY dist /etc/nginx/html/dist

# 设置时区
RUN /bin/cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo 'Asia/Shanghai' >/etc/timezone
