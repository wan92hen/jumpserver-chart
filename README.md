# jumpserver-chart

## 项目说明

参考项目：https://github.com/wojiushixiaobai/docker-compose 

使用了上述项目制作的镜像，并通过 [kompose](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/) 命令将其 docker-compose 文件转换为了 kubernetes 资源的 yaml 文件，在此基础上进行了修改。

## 快速开始

```
$ git clone https://github.com/wangzhen-fit2cloud/jumpserver-chart.git
$ cd jumpserver-chart
$ helm install . --name jumpserver --namespace jumpserver
```
