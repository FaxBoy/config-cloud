# config-cloud
springcloud configuration

      
    feign-service.yml : zuul网关
    product-service.yml : 商品服务
    feign-service.yml : 订单服务



    /product-service.yml
    /{application}/{profile}[/{label}]
    /{application}-{profile}.yml
    /{label}/{application}-{profile}.yml
    /{application}-{profile}.properties
    /{label}/{application}-{profile}.properties

    application:表示应用名称,在client中通过spring.config.name配置
    profile:表示获取指定环境下配置，例如开发环境、测试环境、生产环境 默认值default，实际开发中可以是 dev、test、demo、production等
    label: git标签，默认值master