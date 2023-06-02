#### springcloud插件化开发（dubbo方式已实现）

插件化开发指功能以插件方式引入或移除，各个微服务可以独立部署，也可以统一部署在一个集中服务中。 本项目采用spring cloud技术栈实践，同时支持微服务部署方式和单体部署方式

感兴趣的话，也可以采用dubbo技术栈实现。

主要服务

       订单中心、 支付中心 、eureka服务端、单体服务

场景

       1. 下单 ---调用---> 支付
       2. 支付 ---回调---> 下单

为方便调试，提供接口文档

[接口文档](https://www.apifox.cn/apidoc/shared-d229af41-e577-400f-97db-7673eff29f13/api-61494925)

整体设计

![功能插件化整体设计](https://foruda.gitee.com/images/1676258763853913977/5c5d0ab9_1610336.png)

捐赠

![捐赠](https://foruda.gitee.com/images/1676258615334879771/dec4e8c6_1610336.png)
