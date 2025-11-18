# Java开发工程师完整学习清单

## 📚 目录
1. [Java基础](#1-java基础)
2. [面向对象编程](#2-面向对象编程)
3. [Java核心API](#3-java核心api)
4. [集合框架](#4-集合框架)
5. [异常处理](#5-异常处理)
6. [多线程与并发编程](#6-多线程与并发编程)
7. [IO/NIO/AIO](#7-ionioaio)
8. [网络编程](#8-网络编程)
9. [JVM虚拟机](#9-jvm虚拟机)
10. [设计模式](#10-设计模式)
11. [算法与数据结构](#11-算法与数据结构)
12. [数据库技术](#12-数据库技术)
13. [Java Web开发](#13-java-web开发)
14. [Spring生态系统](#14-spring生态系统)
15. [微服务架构](#15-微服务架构)
16. [消息队列](#16-消息队列)
17. [缓存技术](#17-缓存技术)
18. [搜索引擎](#18-搜索引擎)
19. [分布式系统](#19-分布式系统)
20. [性能优化](#20-性能优化)
21. [测试技术](#21-测试技术)
22. [开发工具](#22-开发工具)
23. [版本控制](#23-版本控制)
24. [CI/CD](#24-cicd)
25. [容器化与云原生](#25-容器化与云原生)
26. [安全](#26-安全)
27. [系统设计](#27-系统设计)

---

## 1. Java基础

### 1.1 语言特性
- Java语言历史与发展
- JDK、JRE、JVM关系
- Java平台版本（Java 8/11/17/21等）
- 编译与运行机制
- 跨平台原理

### 1.2 基础语法
- 数据类型（基本类型、引用类型）
- 变量与常量
- 运算符（算术、关系、逻辑、位运算）
- 控制流程（if/else、switch、for、while、do-while）
- 数组（一维、多维）
- 字符串（String、StringBuilder、StringBuffer）

### 1.3 方法
- 方法定义与调用
- 方法重载
- 方法参数传递机制
- 可变参数
- 递归

### 1.4 包与导入
- package关键字
- import语句
- 访问控制符（public、protected、default、private）
- 静态导入

---

## 2. 面向对象编程

### 2.1 类与对象
- 类的定义
- 对象的创建与使用
- 构造方法
- this关键字
- static关键字
- final关键字
- 代码块（静态代码块、构造代码块）

### 2.2 封装
- 访问修饰符
- getter/setter方法
- 封装的意义

### 2.3 继承
- extends关键字
- super关键字
- 方法重写（Override）
- 继承的层次结构
- Object类

### 2.4 多态
- 多态的概念
- 向上转型与向下转型
- instanceof关键字
- 多态的实现机制

### 2.5 抽象类与接口
- abstract关键字
- 抽象类与抽象方法
- interface关键字
- 接口的实现
- 接口的默认方法与静态方法（Java 8+）
- 函数式接口
- Lambda表达式
- 方法引用

### 2.6 内部类
- 成员内部类
- 局部内部类
- 匿名内部类
- 静态内部类

### 2.7 枚举
- enum关键字
- 枚举的使用场景
- 枚举的方法

---

## 3. Java核心API

### 3.1 常用类
- Object类及其方法
- String类详解
- 包装类（Integer、Double等）
- Math类
- Random类
- Date与Calendar（Java 8之前）
- LocalDate、LocalTime、LocalDateTime（Java 8+）
- DateTimeFormatter
- BigDecimal与BigInteger

### 3.2 正则表达式
- Pattern与Matcher
- 正则表达式语法
- 常用正则表达式

### 3.3 反射机制
- Class类
- 获取Class对象的方式
- 获取构造方法
- 获取成员变量
- 获取成员方法
- 动态创建对象
- 反射的应用场景

### 3.4 注解
- 注解的定义
- 元注解（@Target、@Retention等）
- 内置注解
- 自定义注解
- 注解处理器

---

## 4. 集合框架

### 4.1 Collection接口
- Collection接口方法
- Iterator迭代器
- List接口
  - ArrayList
  - LinkedList
  - Vector
  - Stack
- Set接口
  - HashSet
  - LinkedHashSet
  - TreeSet
- Queue接口
  - PriorityQueue
  - Deque
  - ArrayDeque

### 4.2 Map接口
- HashMap（JDK 1.7与1.8实现差异）
- LinkedHashMap
- TreeMap
- Hashtable
- ConcurrentHashMap

### 4.3 集合工具类
- Collections工具类
- Arrays工具类
- 集合的排序
- 集合的查找

### 4.4 集合性能分析
- 各集合的时间复杂度
- 集合的选择原则
- 集合的线程安全性

---

## 5. 异常处理

### 5.1 异常体系
- Throwable类
- Error与Exception
- 检查异常与非检查异常
- 常见异常类型

### 5.2 异常处理机制
- try-catch-finally
- throws关键字
- throw关键字
- 自定义异常
- 异常链

### 5.3 异常最佳实践
- 异常处理原则
- 异常日志记录
- 资源管理（try-with-resources）

---

## 6. 多线程与并发编程

### 6.1 线程基础
- 进程与线程
- 线程的创建方式
  - 继承Thread类
  - 实现Runnable接口
  - 实现Callable接口
  - 线程池创建
- 线程的生命周期
- 线程的优先级
- 守护线程

### 6.2 线程同步
- synchronized关键字
- volatile关键字
- wait()、notify()、notifyAll()
- Lock接口
- ReentrantLock
- ReadWriteLock
- Condition

### 6.3 并发工具类
- CountDownLatch
- CyclicBarrier
- Semaphore
- Exchanger
- Phaser

### 6.4 线程池
- Executor框架
- ThreadPoolExecutor
- Executors工具类
- 线程池参数配置
- 线程池监控
- Fork/Join框架

### 6.5 并发集合
- ConcurrentHashMap
- CopyOnWriteArrayList
- BlockingQueue
- ConcurrentLinkedQueue

### 6.6 原子类
- AtomicInteger
- AtomicLong
- AtomicReference
- AtomicStampedReference
- LongAdder

### 6.7 并发编程模式
- 生产者-消费者模式
- 读写锁模式
- 线程本地存储（ThreadLocal）

---

## 7. IO/NIO/AIO

### 7.1 传统IO
- File类
- 字节流（InputStream、OutputStream）
- 字符流（Reader、Writer）
- 缓冲流
- 转换流
- 对象序列化

### 7.2 NIO
- NIO核心概念
- Buffer缓冲区
- Channel通道
- Selector选择器
- NIO与IO的区别
- NIO应用场景

### 7.3 AIO
- AsynchronousFileChannel
- AsynchronousSocketChannel
- CompletionHandler

---

## 8. 网络编程

### 8.1 Socket编程
- TCP Socket编程
- UDP Socket编程
- ServerSocket
- Socket通信模型

### 8.2 HTTP编程
- URL与URLConnection
- HttpURLConnection
- HttpClient（Apache、OkHttp）

### 8.3 网络框架
- Netty框架基础
- Netty核心组件
- Netty编解码器
- Netty应用场景

---

## 9. JVM虚拟机

### 9.1 JVM内存模型
- 程序计数器
- 虚拟机栈
- 本地方法栈
- 堆内存
- 方法区（元空间）
- 直接内存

### 9.2 垃圾回收
- 垃圾回收算法
  - 标记-清除
  - 标记-复制
  - 标记-整理
  - 分代回收
- 垃圾回收器
  - Serial GC
  - Parallel GC
  - CMS GC
  - G1 GC
  - ZGC
  - Shenandoah GC
- GC调优
- 内存泄漏排查

### 9.3 类加载机制
- 类加载过程
- 类加载器
- 双亲委派模型
- 自定义类加载器

### 9.4 JVM调优
- JVM参数
- 内存调优
- GC调优
- 性能监控工具
  - jps
  - jstat
  - jmap
  - jstack
  - jconsole
  - VisualVM
  - MAT
  - JProfiler

---

## 10. 设计模式

### 10.1 创建型模式
- 单例模式
- 工厂模式
- 抽象工厂模式
- 建造者模式
- 原型模式

### 10.2 结构型模式
- 适配器模式
- 装饰器模式
- 代理模式
- 外观模式
- 桥接模式
- 组合模式
- 享元模式

### 10.3 行为型模式
- 策略模式
- 观察者模式
- 模板方法模式
- 命令模式
- 责任链模式
- 状态模式
- 访问者模式
- 中介者模式
- 迭代器模式
- 备忘录模式
- 解释器模式

---

## 11. 算法与数据结构

### 11.1 数据结构
- 数组
- 链表（单向、双向、循环）
- 栈
- 队列（普通队列、双端队列、优先队列）
- 树（二叉树、二叉搜索树、AVL树、红黑树、B树、B+树）
- 图（邻接表、邻接矩阵）
- 哈希表
- 堆

### 11.2 算法
- 排序算法
  - 冒泡排序
  - 选择排序
  - 插入排序
  - 快速排序
  - 归并排序
  - 堆排序
  - 计数排序
  - 桶排序
  - 基数排序
- 查找算法
  - 线性查找
  - 二分查找
  - 哈希查找
- 递归与回溯
- 动态规划
- 贪心算法
- 分治算法
- 图算法（DFS、BFS、最短路径、最小生成树）

### 11.3 算法复杂度
- 时间复杂度
- 空间复杂度
- 大O表示法

---

## 12. 数据库技术

### 12.1 SQL基础
- DDL（CREATE、ALTER、DROP）
- DML（INSERT、UPDATE、DELETE）
- DQL（SELECT、WHERE、JOIN、GROUP BY、HAVING、ORDER BY）
- 索引
- 视图
- 存储过程
- 触发器
- 事务

### 12.2 MySQL
- MySQL安装与配置
- 数据类型
- 存储引擎（InnoDB、MyISAM）
- 索引优化
- 查询优化
- 主从复制
- 分库分表

### 12.3 JDBC
- JDBC API
- DriverManager
- Connection
- Statement与PreparedStatement
- ResultSet
- 事务管理
- 连接池（DBCP、C3P0、HikariCP）

### 12.4 ORM框架
- MyBatis
  - MyBatis配置
  - Mapper XML
  - 动态SQL
  - 结果映射
  - 缓存机制
- Hibernate
  - Hibernate配置
  - 实体映射
  - HQL
  - 关联映射
  - 缓存机制
- JPA
  - Entity注解
  - Repository
  - 查询方法

### 12.5 NoSQL数据库
- Redis
  - 数据类型（String、Hash、List、Set、ZSet）
  - 持久化（RDB、AOF）
  - 主从复制
  - 哨兵模式
  - 集群模式
  - 缓存策略
- MongoDB
  - 文档模型
  - CRUD操作
  - 索引
  - 聚合查询

---

## 13. Java Web开发

### 13.1 Servlet
- Servlet生命周期
- Servlet配置
- Request与Response
- Session与Cookie
- Filter过滤器
- Listener监听器

### 13.2 JSP
- JSP语法
- JSP内置对象
- EL表达式
- JSTL标签库

### 13.3 Web服务器
- Tomcat
- Jetty
- Undertow

### 13.4 MVC模式
- MVC架构
- 前端控制器模式

---

## 14. Spring生态系统

### 14.1 Spring Framework
- Spring IoC容器
- Bean管理
- 依赖注入（DI）
- AOP面向切面编程
- Spring事务管理
- Spring MVC
- Spring JDBC
- Spring Test

### 14.2 Spring Boot
- Spring Boot核心特性
- 自动配置原理
- Starter依赖
- 配置文件（application.yml、application.properties）
- 多环境配置
- Actuator监控
- 自定义Starter

### 14.3 Spring Cloud
- 微服务架构
- Eureka服务注册与发现
- Ribbon负载均衡
- Feign声明式HTTP客户端
- Hystrix熔断器
- Gateway网关
- Config配置中心
- Bus消息总线
- Sleuth链路追踪
- OpenFeign
- Sentinel限流降级

### 14.4 Spring Data
- Spring Data JPA
- Spring Data Redis
- Spring Data MongoDB

### 14.5 Spring Security
- 认证与授权
- JWT
- OAuth2
- 安全配置

---

## 15. 微服务架构

### 15.1 微服务基础
- 微服务概念
- 微服务优缺点
- 微服务拆分原则
- 服务治理

### 15.2 服务通信
- RESTful API
- RPC（gRPC、Dubbo）
- 消息队列通信

### 15.3 服务注册与发现
- Eureka
- Consul
- Nacos
- Zookeeper

### 15.4 配置管理
- Spring Cloud Config
- Nacos Config
- Apollo

### 15.5 服务网关
- Spring Cloud Gateway
- Zuul
- Kong

### 15.6 分布式追踪
- Zipkin
- SkyWalking
- Pinpoint

---

## 16. 消息队列

### 16.1 消息队列基础
- 消息队列概念
- 消息队列应用场景
- 消息模型（点对点、发布订阅）

### 16.2 RabbitMQ
- RabbitMQ基础
- Exchange类型
- 队列与绑定
- 消息确认机制
- 持久化
- 集群

### 16.3 Kafka
- Kafka架构
- Topic与Partition
- Producer
- Consumer
- Consumer Group
- 消息顺序性
- 事务
- 集群

### 16.4 RocketMQ
- RocketMQ架构
- Topic与Queue
- 消息类型
- 事务消息
- 顺序消息

### 16.5 消息队列选型
- 各消息队列对比
- 适用场景

---

## 17. 缓存技术

### 17.1 缓存基础
- 缓存概念
- 缓存策略（Cache-Aside、Read-Through、Write-Through、Write-Behind）
- 缓存更新策略
- 缓存穿透、击穿、雪崩

### 17.2 Redis
- Redis数据类型
- Redis命令
- Redis持久化
- Redis主从复制
- Redis哨兵
- Redis集群
- Redis性能优化
- Redis应用场景

### 17.3 本地缓存
- Caffeine
- Guava Cache
- EhCache

### 17.4 缓存一致性
- 缓存与数据库一致性
- 分布式缓存一致性

---

## 18. 搜索引擎

### 18.1 Elasticsearch
- Elasticsearch基础
- 索引与文档
- 查询DSL
- 聚合查询
- 分词器
- 集群与分片
- 性能优化

### 18.2 Solr
- Solr基础
- Solr配置
- Solr查询

---

## 19. 分布式系统

### 19.1 分布式基础
- CAP定理
- BASE理论
- 分布式事务
- 分布式锁
- 分布式ID生成

### 19.2 分布式事务
- 2PC
- 3PC
- TCC
- Saga
- Seata

### 19.3 分布式锁
- 基于Redis的分布式锁
- 基于Zookeeper的分布式锁
- Redisson

### 19.4 分布式ID
- UUID
- 数据库自增ID
- 雪花算法（Snowflake）
- 美团Leaf

### 19.5 一致性哈希
- 一致性哈希原理
- 虚拟节点

---

## 20. 性能优化

### 20.1 代码优化
- 代码性能分析
- 算法优化
- 数据结构选择
- 避免不必要的对象创建
- 字符串优化

### 20.2 JVM优化
- 堆内存调优
- GC调优
- 类加载优化

### 20.3 数据库优化
- SQL优化
- 索引优化
- 查询优化
- 连接池优化

### 20.4 缓存优化
- 缓存策略优化
- 缓存命中率提升

### 20.5 系统优化
- 负载均衡
- CDN
- 异步处理
- 批量处理

---

## 21. 测试技术

### 21.1 单元测试
- JUnit
- TestNG
- Mockito
- PowerMock
- AssertJ

### 21.2 集成测试
- Spring Test
- TestContainers

### 21.3 性能测试
- JMeter
- Gatling
- 压力测试

### 21.4 测试覆盖率
- JaCoCo
- Cobertura

---

## 22. 开发工具

### 22.1 IDE
- IntelliJ IDEA
- Eclipse
- VS Code

### 22.2 构建工具
- Maven
  - POM文件
  - 依赖管理
  - 生命周期
  - 插件
- Gradle
  - Gradle构建脚本
  - 依赖管理
  - 任务

### 22.3 代码质量
- SonarQube
- Checkstyle
- PMD
- FindBugs

### 22.4 日志框架
- Log4j
- Logback
- Log4j2
- SLF4J

---

## 23. 版本控制

### 23.1 Git
- Git基础命令
- 分支管理
- 合并策略
- 冲突解决
- Git Flow
- GitHub/GitLab使用

### 23.2 SVN
- SVN基础
- SVN命令

---

## 24. CI/CD

### 24.1 CI/CD基础
- 持续集成概念
- 持续部署概念
- CI/CD流程

### 24.2 CI/CD工具
- Jenkins
- GitLab CI
- GitHub Actions
- TeamCity

### 24.3 自动化部署
- 自动化构建
- 自动化测试
- 自动化部署

---

## 25. 容器化与云原生

### 25.1 Docker
- Docker基础
- Dockerfile
- Docker镜像
- Docker容器
- Docker Compose
- Docker网络
- Docker存储

### 25.2 Kubernetes
- Kubernetes基础
- Pod
- Service
- Deployment
- ConfigMap与Secret
- Ingress
- 持久化存储

### 25.3 云原生
- 云原生概念
- 微服务与云原生
- Serverless

---

## 26. 安全

### 26.1 Web安全
- SQL注入
- XSS跨站脚本攻击
- CSRF跨站请求伪造
- 文件上传安全
- 密码加密（MD5、SHA、BCrypt）

### 26.2 认证与授权
- Session认证
- Token认证
- JWT
- OAuth2
- SSO单点登录

### 26.3 安全框架
- Spring Security
- Shiro
- Apache Shiro

---

## 27. 系统设计

### 27.1 系统设计基础
- 系统设计原则
- 可扩展性设计
- 高可用设计
- 高性能设计

### 27.2 常见系统设计
- 短链接系统
- 秒杀系统
- 分布式文件系统
- 搜索引擎
- 推荐系统
- 聊天系统
- 支付系统

### 27.3 架构模式
- 分层架构
- 微服务架构
- 事件驱动架构
- CQRS
- 领域驱动设计（DDD）

---

## 📖 学习路径建议

### 初级阶段（1-3个月）
1. Java基础语法
2. 面向对象编程
3. 集合框架
4. 异常处理
5. IO基础
6. 多线程基础
7. JDBC
8. MySQL基础

### 中级阶段（3-6个月）
1. JVM基础
2. 设计模式
3. 算法与数据结构
4. Spring Framework
5. Spring Boot
6. MyBatis
7. Redis
8. Maven/Gradle

### 高级阶段（6-12个月）
1. JVM调优
2. 并发编程深入
3. Spring Cloud
4. 微服务架构
5. 消息队列
6. 分布式系统
7. 性能优化
8. 系统设计

### 专家阶段（12个月+）
1. 架构设计
2. 技术选型
3. 团队管理
4. 技术领导力
5. 开源贡献

---

## 📚 推荐学习资源

### 书籍
- 《Java核心技术》
- 《Java编程思想》
- 《Effective Java》
- 《深入理解Java虚拟机》
- 《Java并发编程实战》
- 《Spring实战》
- 《设计模式：可复用面向对象软件的基础》
- 《算法导论》
- 《高性能MySQL》
- 《Redis设计与实现》

### 在线课程
- 慕课网
- 极客时间
- 拉勾教育
- 尚硅谷
- 黑马程序员

### 官方文档
- Oracle Java官方文档
- Spring官方文档
- MyBatis官方文档
- Redis官方文档

### 技术社区
- GitHub
- Stack Overflow
- 掘金
- 博客园
- CSDN
- 思否

---

## ✅ 学习检查清单

使用此清单跟踪你的学习进度：

- 完成Java基础学习
- 完成面向对象编程学习
- 完成集合框架学习
- 完成多线程学习
- 完成JVM学习
- 完成Spring学习
- 完成数据库学习
- 完成微服务学习
- 完成分布式系统学习
- 完成至少3个项目实战

---

## 🎯 项目实战建议

### 初级项目
1. 学生管理系统
2. 图书管理系统
3. 在线购物车

### 中级项目
1. 博客系统
2. 在线商城
3. 任务管理系统

### 高级项目
1. 分布式电商系统
2. 微服务架构系统
3. 高并发秒杀系统

---

**最后更新：2024年**

**祝你学习顺利！💪**

