# RateLimiter
分布式限流工具

1.基于redis限流, 集群集群流量汇总
2.可配置方法前统计 方法执行后(可过滤统计)

quick start
1.在springBoot程序中加入 @EnableRateLimiter
2.在目标限流方法上加入@RateLimiter注解


admin:
读取admin接口服务查看和配置流量信息, 可暴露成dobbo或http服务
