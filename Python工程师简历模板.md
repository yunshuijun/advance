## 骆昊 - Python开发工程师

### 基本信息
| 姓名：骆昊                  | 手机：13812345678              |
| --------------------------- | ------------------------------ |
| 性别：男                    | 年龄：39                      |
| **邮箱：jackfrued@126.com** | **博客：<https://jackfrued.xyz>** |
| 毕业院校：四川大学          | 学历：工学博士                 |
| **英语水平：六级**          | 工作经验：15年                 |


### 专业课程

| 计算机科学与技术专业                                         |
| ------------------------------------------------------------ |
| C语言程序设计、Java面向对象编程、数据结构和算法、数据库概论、操作系统、计算机网络、软件工程、密码学原理、人工智能、编译原理等 |

### 获奖情况

| 年份   | 奖项                                                   |
| ------ | ------------------------------------------------------ |
| 2000年 | 四川大学优秀奖学金三等奖、四川大学优秀学生干部奖       |
| 2001年 | 四川大学优秀奖学金二等奖、全国大学生数学建模竞赛三等奖 |
| 2002年 | 华西都市报优秀大学生奖学金、四川大学优秀奖学金一等奖   |
| 2003年 | 四川省优秀大学毕业生                                   |

### 工作经历
| 时间                 | 公司                    | 职位                 |
| -------------------- | ----------------------- | -------------------- |
| 2015年11月~2018年9月 | 深圳ABC网络科技有限公司 | Python后端开发工程师 |
| 2013年7月~2015年10月 | 北京XYZ科技股份有限公司 | Python爬虫工程师     |


### 专业技能

1. 熟练的使用Python语言进行应用程序开发，有良好的编程习惯，对面向对象的设计原则以及常用设计模式有较为深入的理解，熟悉Python开发中常用的标准库和第三方库。
2. 熟练的使用Django和Flask框架进行Web应用后端开发，熟悉MVC（MTV）架构模式，有在项目中使用django-redis、django-celery、django-rest-framework等第三方库的经验，了解过Web.py、Tornado、Twisted等框架。
3. 熟悉关系型数据库产品MySQL和Oracle，熟练的使用SQL，对MySQL的优化有一定程度的了解，熟悉非关系型数据库产品MongoDB和Redis，有在项目中使用Redis实现高速缓存的经验。
4. 熟练的使用urllib、requests、aiohttp、re、beautifulsoup、pyquery、pymysql、pymongo、redis、hashlib、json、pickle、zlib标准库或三方库进行网络数据采集，有使用Scrapy/PySpider开发爬虫的经验，了解Scrapy-Redis。
5. 能够使用NumPy和SciPy完成科学运算，熟悉数据分析和可视化工具Pandas和Matplotlib。
6. 熟悉常用的机器学习算法和模型，包括：KNN、DecisionTree、LR、Naive Bayes、SVM、PCA、AdaBoost、K-Means等。
7. 熟练的使用Linux操作系统，熟悉Linux常用服务的安装和配置，熟悉Shell编程，熟练的使用vim、awk、xargs等工具，了解Linux系统运维常用命令。
8. 熟悉Web前端开发的语言和框架，对HTML、CSS和JavaScript有较好的理解和掌握，熟悉Ajax和WebSocket相关技术，有在项目中使用jQuery、Axios、Fetch、Vue.js、Bootstrap、sockjs、stomp.js、ECharts等技术的经验。
9. 熟练的使用Git和Mercury实施项目的版本控制，对缺陷管理和持续集成有一定程度的了解，使用过AB、mysqlslap、sysbench等压力测试工具。
10. 熟悉Nginx、uWSGI、Gunicorn、MySQL、Redis等服务器的配置和使用，熟Docker、Docker-Compose、Docker-Swarm等工具在项目部署中的应用。

### 项目经验

> 说明：一定要使用**S.T.A.R**法则书写简历。

| 项目名称     | 企业家（移动端+PC端[管理端]）                                |
| ------------ | ------------------------------------------------------------ |
| **项目简介** | 该项目是为小微企业提供人事、财务、供应链、客户等信息管理的平台而研发的系统，旨在帮助小微企业快速实现企业信息化，节省管理成本，定制管理内容，提高办公效率。 |
| **项目职责** | 1. 实现了人事管理模块中员工档案管理、工资发放管理、入职转正离职管理以及员工分析等功能。<br>2. 实现了客户管理模块中客户信息管理、客户跟进、订单管理、客户分析和销售分析等功能。 |
| **主要技术** | 1. 使用djangorestframework的`APIView`和`ViewSet`为移动端提供REST风格的数据接口，提供了员工档案、客户信息、订单信息、销售记录等数据接口，项目初期使用RAP2为移动端提供测试数据和接口文档。<br>2. 通过为视图类指定`authentication_classes`属性并指定自定义认证类对使用数据接口的用户进行身份认证，检查请求中的用户ID和令牌（登录后自动生成）是否匹配。<br>3. 通过为视图类指定`permission_classes`属性实现对数据接口访问权限的控制，在认证的基础上对用户进行授权处理，使用RBAC（基于角色的访问控制）方式来控制对数据接口的访问访问权限。<br>4. 使用自定义对象保存用户偏好设置信息，通过pickle对用户偏好设置对象进行序列化操作，通过base64模块的base64encode对序列化后的数据进行BASE64编码，通过Signer对编码后的数据进行签名，防止对Cookie数据的恶意篡改。<br>5. 通过django-redis对接Redis服务器实现了页面缓存和查询缓存功能，对数据接口的查询结果以及用户权限资源等数据进行了缓存；通过自定义的应用加载钩子函数实现权限模型数据的缓存预热功能。<br>6. 通过在项目中集成django-crontab实现了工资定期自动结算服务，通过requests模块实现了对云考勤（群英云考勤、得力云考勤等）数据接口的调用。<br>7. 通过接入SendCloud平台实现了重要通知的短信和邮件提醒服务，使用Celery+RabbitMQ对短信和邮件服务进行了任务异步化处理。<br>8. 通过自定义序列化器和`SerializerMethodField`实现了对员工统计分析数据的序列化，为前端ECharts统计图表提供高度定制的数据。 |
| **难点分析** |                                                              |

| 项目名称     | 奢侈品租赁商城（PC端[用户端+管理端]）                        |
| ------------ | ------------------------------------------------------------ |
| **项目简介** | 该项目是为XYZ公司定制的专门用于奢侈品租赁的网络平台，XYZ公司是一家专业从事奢侈品租赁、奢侈品实体休闲会所、奢侈品鉴定、奢侈品养护服务的公司，而奢侈品租赁商城则为奢侈品租赁提供了更为便捷的平台，可以吸引更大的消费群体。 |
| **技术栈**   |                                                              |
| **主要技术** |                                                              |
| **难点分析** |                                                              |

| 项目名称     | 美人鱼（移动端+PC端[后台管理]） |
| ------------ | :----------------------------------------------------------- |
| **项目简介** | 美人鱼是一款真人视频认证社交App，通过该App可以随时找人聊天，关注鱼主后可以查看其发布的视频，倡导拒绝照片让社交更真实的交友理念。 |
| **技术栈**   |               |
| **主要技术** |               |
| **难点分析** |               |

| 项目名称     | XYZ公司战略决策支持系统（数据采集子系统） |
| ------------ | ------------------------------------------------------------ |
| **项目简介** | 爬取了瓜子、优信二手车、人人车、58同城、99好车等多个网站的二手车数据，为XYZ公司的竞品分析和战略决策提供数据支持。 |
| **技术栈**   |                                           |
| **主要技术** |                                           |
| **难点分析** |                                           |

### 个人评价

1. 热爱编程，除Python之外还对Java、C/C++、Go等语言有浓厚的兴趣，对大数据、微服务架构、虚拟化等技术保持持续的关注。
2. 喜欢旅游和阅读，有良好的学习能力和英语听说读写能力，喜欢钻研技术文档，经常对技术进行总结和思考，有自己的技术博客和代码仓库。
3. 能够迅速的适应环境并融入团队，能够在高强度的工作中保持劳逸结合，做事讲究规范和效率。

> **有几个注意事项需要提醒大家**。
>
> 书写简历时请一定要使用**S.T.A.R**法则（请参照上面企业家项目中的描述）。
>
> 1. **S**ituation（场景）：场景是指使用某个技术的业务背景是什么，脱离业务讲技术都是耍流氓的行为。例如在介绍项目技术要点时不能够单写“项目中使用xlwt实现了导出Excel报表的功能”，必须得先交代清楚哪些业务需要用到报表功能。
> 2. **T**ask（任务）：任务是指在上面提到的业务场景下，你要解决的问题是什么。例如要实现根据用户的筛选条件或勾选的记录来导出Excel报表。
> 3. **A**ction（行为）：行为是指你如何完成上面的任务，用到了什么技术方案，包括在技术选型的时候你是如何考虑的，为什么选择了A技术，没有选择B技术或C技术。
> 4. **R**esult（结果）：结果是指在你选择了上述的行为后，最终是否完成了任务，你所选择的方案是否满足了既定的设计目标。
>
> 简历中千万不要写自己无法把控的内容，要学会分析每个技术点可能产生的问题，例如上面提到了熟悉Linux系统，那么就有可能产生如下一系列问题，如：
>
> 1. Linux系统下如何查找某种类型的文件并删除？
>
> 2. Linux系统常用运维命令有哪些？（ps、top、mpstat、free、netstat、df、iostat、sar、chkconfig、uptime、ulimit、curl、scp、ifconfig、nc、nslookup、tcpdump等）
>
> 3. 如何通过一条命令结束杀掉MySQL相关进程？
>
> 4. 如何检查有多少个用户登录到系统？
>
>
> 再比如：
>
> 1. 你所说的良好的编程习惯是指什么？
> 2. 什么是OCP？如何实现OCP？说一下你开发中用到的设计模式？
> 3. 什么是MVC架构？为什么要使用MVC架构模式？
> 4. 说一下项目中MySQL、Redis和MongoDB的具体应用场景是怎样的？
> 5. 说一下你知道的关系型数据库优化方式。（1. SQL本身的优化；2. 使用索引；3. 存储过程；4. explain；5. 慢查询日志；6. 适当降低事务隔离级别；7. 适当降低范式级别；8. 放弃必要的外键约束；9. 其他的主键生成策略；……）
> 6. 实现Session共享的方式有哪些，每种方式的优劣对比？
