# gitlab-config-kubernetes

#### 介绍
gitlab用kubernetes进行部署

#### 软件架构
gitlab deployment 和 service， gitlab-runner deployment


#### 安装教程

1.  修改各配置文件中的ip和其他配置，符合自己的服务器环境
2.  kubectl apply -f gitlab-deployment.yml
3.  kubectl apply -f gitlab-service.yml
4.  kubectl apply -f gitlab-runner-deployment.yml


