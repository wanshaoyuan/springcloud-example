### 基于官方PiggyMetrics，主要增加kubernetes部署的yaml文件
https://github.com/sqshq/PiggyMetrics

### 部署到kubernetes集群中  
```
git clone https://github.com/wanshaoyuan/springcloud-example.git
```
```
kubectl apply -f yaml/deployment/.
```
```
kubectl apply -f yaml/svc/.
```

### 访问地址
对外的端口
docker-compose 部署方式  
- http://localhost:80 - Gateway  
- http://localhost:8761 - Eureka Dashboard   
- http://localhost:9000/hystrix - Hystrix Dashboard (paste Turbine stream link on the form)  
- http://localhost:8989 - Turbine stream (source for the Hystrix Dashboard)   
- http://localhost:15672 - RabbitMq management (default login/password: guest/guest)  


kubernetes 部署方式 
- http://localhost:30010 - Gateway  
- http://localhost:30011 - Eureka Dashboard  
- http://localhost:30012/hystrix - Hystrix Dashboard (paste Turbine stream link on the form)  
- http://localhost:30013 - Turbine stream (source for the Hystrix Dashboard)  
- http://localhost:30014 - RabbitMq management (default login/password: guest/guest)  

