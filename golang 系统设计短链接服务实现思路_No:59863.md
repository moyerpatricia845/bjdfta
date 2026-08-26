最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计短链接服务实现思路
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.5jji69.asia/arts/520117.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.5jji69.asia/arts/034669.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.5jji69.asia/arts/903832.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.5jji69.asia/arts/075746.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.5jji69.asia/arts/643034.Doc

原标题：正则表达式优化 CPU 占满问题
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.5jji69.asia/arts/052178.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.5jji69.asia/arts/266856.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.5jji69.asia/arts/044603.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.5jji69.asia/arts/442166.Doc

原标题：golang 开发环境快速搭建指南
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.5jji69.asia/arts/553289.Doc

原标题：golang 批量任务协程控制防雪崩
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/328113.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.5jji69.asia/arts/146970.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/223442.Doc

原标题：从零搭建简单的健康检查接口示例
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.5jji69.asia/arts/155154.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.5jji69.asia/arts/482417.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.5jji69.asia/arts/177925.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.5jji69.asia/arts/466478.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.5jji69.asia/arts/193875.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.5jji69.asia/arts/430870.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.5jji69.asia/arts/290815.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.5jji69.asia/arts/682777.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.5jji69.asia/arts/715029.Doc

原标题：前端打包分包加载提速方案
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.5jji69.asia/arts/216717.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.5jji69.asia/arts/018099.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.5jji69.asia/arts/108369.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.5jji69.asia/arts/436667.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.5jji69.asia/arts/929528.Doc

原标题：线程池拒绝策略任务丢失防护
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.5jji69.asia/arts/376746.Doc

原标题：前端大文件分片上传完整方案
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.5jji69.asia/arts/031677.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.5jji69.asia/arts/089485.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.5jji69.asia/arts/053329.Doc

原标题：golang mysql 慢查询日志开启分析
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.5jji69.asia/arts/877722.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.5jji69.asia/arts/090684.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.5jji69.asia/arts/977903.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.5jji69.asia/arts/044639.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.5jji69.asia/arts/931628.Doc

原标题：gitignore 文件编写过滤规则
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.5jji69.asia/arts/692357.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.5jji69.asia/arts/501748.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.5jji69.asia/arts/942788.Doc

原标题：分布式任务调度集群原型开发
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.5jji69.asia/arts/661015.Doc


二、踩坑排错｜Troubleshooting
原标题：AI实践：大模型生成代码后审查与重构实践
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/676146.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.5jji69.asia/arts/492703.Doc

原标题：内存泄漏定位分析完整流程
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.5jji69.asia/arts/890243.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.5jji69.asia/arts/356169.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.5jji69.asia/arts/500513.Doc

原标题：golang github actions 缓存依赖提速
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.5jji69.asia/arts/365715.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.5jji69.asia/arts/065944.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.5jji69.asia/arts/151758.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.5jji69.asia/arts/808149.Doc

原标题：项目目录结构规范化最佳实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.5jji69.asia/arts/755482.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.5jji69.asia/arts/273665.Doc

原标题：业务错误码完整落地实践
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.5jji69.asia/arts/892468.Doc

原标题：golang base64 编码解码实操
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.5jji69.asia/arts/753176.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.5jji69.asia/arts/466585.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.5jji69.asia/arts/018158.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.5jji69.asia/arts/777588.Doc

原标题：OAuth2 第三方登录服务搭建
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.5jji69.asia/arts/906841.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.5jji69.asia/arts/262110.Doc

原标题：golang 分布式锁防死锁处理
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.5jji69.asia/arts/071654.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.5jji69.asia/arts/599611.Doc

原标题：项目实践：分布式会话Redis存储落地实践
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.5jji69.asia/arts/420516.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.5jji69.asia/arts/762383.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.5jji69.asia/arts/955390.Doc

原标题：golang docker 部署 kafka 本地调试
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.5jji69.asia/arts/830802.Doc

原标题：序列化版本不一致解析失败
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.5jji69.asia/arts/976643.Doc

原标题：golang redis 缓存更新策略讲解
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.5jji69.asia/arts/822742.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.5jji69.asia/arts/141582.Doc

原标题：零基础理解幂等性基础概念与场景
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.5jji69.asia/arts/903919.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.5jji69.asia/arts/759812.Doc

原标题：golang k8s secret 加密敏感信息
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.5jji69.asia/arts/700062.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.5jji69.asia/arts/252227.Doc

原标题：消息队列消费堆积扩容处理
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.5jji69.asia/arts/270001.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.5jji69.asia/arts/307948.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.5jji69.asia/arts/825876.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.5jji69.asia/arts/744315.Doc

原标题：golang viper 配置热更新实操
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.5jji69.asia/arts/678031.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.5jji69.asia/arts/873563.Doc

原标题：golang 系统设计多级缓存架构落地
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.5jji69.asia/arts/003362.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.5jji69.asia/arts/144368.Doc

原标题：golang mysql limit 大分页优化
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.5jji69.asia/arts/211464.Doc

三、实战开发｜Practice
原标题：线上故障：消息队列重复消费业务处理异常
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.5jji69.asia/arts/877511.Doc

原标题：golang k8s liveness readiness 探针
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.5jji69.asia/arts/532033.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.5jji69.asia/arts/105908.Doc

原标题：实践：灰度流量切分简易实现方案
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.5jji69.asia/arts/370503.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.5jji69.asia/arts/239448.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.5jji69.asia/arts/903069.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.5jji69.asia/arts/901001.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.5jji69.asia/arts/011216.Doc

原标题：golang mysql json 字段查询使用
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.5jji69.asia/arts/485291.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.5jji69.asia/arts/203171.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.5jji69.asia/arts/835955.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.5jji69.asia/arts/319722.Doc

原标题：golang git 提交信息规范校验
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.5jji69.asia/arts/239860.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.5jji69.asia/arts/140840.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.5jji69.asia/arts/425262.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.5jji69.asia/arts/634072.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.5jji69.asia/arts/207044.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.5jji69.asia/arts/993307.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.5jji69.asia/arts/531083.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.5jji69.asia/arts/717810.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.5jji69.asia/arts/411981.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.5jji69.asia/arts/303525.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.5jji69.asia/arts/439117.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.5jji69.asia/arts/536825.Doc

原标题：golang prometheus counter gauge 使用
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.5jji69.asia/arts/925144.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.5jji69.asia/arts/752640.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.5jji69.asia/arts/030432.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.5jji69.asia/arts/083058.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.5jji69.asia/arts/110795.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.5jji69.asia/arts/366439.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.5jji69.asia/arts/596333.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.5jji69.asia/arts/710495.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.5jji69.asia/arts/173553.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://wiki.5jji69.asia/arts/299655.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/906155.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.5jji69.asia/arts/678351.Doc

原标题：golang grpc protobuf 开发实操
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.5jji69.asia/arts/197909.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.5jji69.asia/arts/628284.Doc

原标题：golang docker 镜像构建最佳实践
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.5jji69.asia/arts/892907.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.5jji69.asia/arts/034798.Doc

四、架构设计｜Architecture
原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.5jji69.asia/arts/102077.Doc

原标题：golang pprof 线上采集性能数据
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.5jji69.asia/arts/948575.Doc

原标题：golang 优雅处理数据库事务
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.5jji69.asia/arts/872935.Doc

原标题：Practice：实现接口防重提交组件实践
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.5jji69.asia/arts/122073.Doc

原标题：接口签名验签完整安全方案
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.5jji69.asia/arts/093014.Doc

原标题：零基础理解幂等性基础概念与场景
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.5jji69.asia/arts/365671.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.5jji69.asia/arts/710756.Doc

原标题：golang docker 私有仓库搭建使用
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.5jji69.asia/arts/333756.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.5jji69.asia/arts/051231.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.5jji69.asia/arts/348772.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.5jji69.asia/arts/740093.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.5jji69.asia/arts/529150.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.5jji69.asia/arts/636186.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.5jji69.asia/arts/015736.Doc

原标题：静态资源 404 路径打包修复
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.5jji69.asia/arts/670383.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.5jji69.asia/arts/845223.Doc

原标题：golang proto 默认值坑点梳理
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.5jji69.asia/arts/965142.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.5jji69.asia/arts/253253.Doc

?
