-基础培训Day3
- BOSS系统
     - BSS:业务支撑系统（普通用户可见）CRM/Billing/BI
     -  OSS:用户不可见
- CRM系统功能架构
    - hr：交换机

- 陕西BOSS系统核心模型-三户模型
    - 用户 客户 账户
        - 账户：代付，和付关系，可以一对多

- CRM双中心系统体系架构
    - 与用户直接接触，受理
    - 双中心：异地 一方出问题，另一方仍能使用
    - 双活
    - 软代理：软件代理
    - 负载均衡
    - 会话：即使硬件等全挂，软件生命周期仍存活
    - x86:700G，低成本
    - 数据库 主机 基本语言（基于Java）

- 技术架构
    
- 本地读写缓存
    - 速度快，支持高并发，降低后端数据库读写，提高前端并发
    - 高频 数据变化不大   
    - 三级：本地 主机（成本高） 自研内存数据库  
    - 提高效率 

- BOSS云化项目系统架构

- CRM数据拆分
    - 业务 资料分区（地域） 建立数据模型 拆分的数据按生命周期管
    - 三步：分区 分表 分库
                

- 移动一体化BOSS-CRM系统（开户业务）
    - 以客户为中心的一个服务管理系统
    - 渠道管理：管理营业厅
    - 渠道酬金管理：管理佣金
    - 产品管理

- 三户模型
    - 客户
        - 在中国移动服务的消费者或潜在消费者
        -拥有若干账户        
    - 账户
        - 付费实体
    - 用户
        - 中国移动服务的定购者，有契约关系
    - 三者关系
        - 客户可有多个用户
        - 用户产生过个账目，要销账产生账户

                                   
    