# 微服务笔记 

#### --help 
#想在物理机浏览器上查看资源： f
kubectl proxy  --address=0.0.0.0 --accept-hosts='^*$'

#必要字段带有request
kubectl explain pod.spec.containers
##### 手动创建pod：
kubectl create -f pod-test.yaml
##### 监听创建的pod：
kubectl get pods -w
