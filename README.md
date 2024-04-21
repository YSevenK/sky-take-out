### 苍穹外卖项目

### 项目结构

| # |      名称      | 说明                                  |
|:-:|:------------:|-------------------------------------|
| 1 | sky-take-out | maven父工程                            |
| 2 |  sky-common  | 存放公共类：工具类、常量类、异常类                   |
| 3 |   sky-pojo   | 存放实体类、vo、DTO                        |
| 4 |  sky-server  | 后端服务、配置文件、controller、service、mapper |

#### sky-pojo 子模块

| # |   名称   |              说明              |
|:-:|:------:|:----------------------------:|
| 1 | Entity |         实体，与数据库中表对应          |
| 2 |  DTO   |      数据传输对象，程序各层之间传输数据       |
| 3 |   VO   |      视图对象，为前端展示数据提供的对象       |
| 4 |  POJO  | 普通Java对象，属性和对应的getter和setter |

#### sky-server 子模块

存放 配置文件、配置类、拦截器、controller、service、mapper、启动类
