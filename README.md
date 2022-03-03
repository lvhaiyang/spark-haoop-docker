1、目录说明

./conf 

    spark和hadooop的配置文件备份

./data

    挂载到镜像的 /data 目录下了  

spark-hadoop.yaml

    docker-compose 配置文件

<br/>  
2、启动 spark Hadoop 集群

目前为master slave1 有需要的可以自己加 slave

docker-compose -f spark-hadoop.yaml up -d

<br/> 

web访问地址

可以通过 http://ip:8888 访问 jupyterLab
 
可以通过 http://ip:8080 访问 spark
 
可以通过 http://ip:9870 浏览 NameNode 的web页面

可以通过 http://ip:8088 浏览 yarn 的web页面
















