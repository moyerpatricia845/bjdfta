最新前沿技术资讯

一、入门教程｜Getting Started
原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://zhishi.umesxl.asia/blog/6881713.sHtML

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://zhishi.umesxl.asia/blog/7822547.sHtML

原标题：服务器 Swap 关闭提升响应速度
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://zhishi.umesxl.asia/blog/2049506.sHtML

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://zhishi.umesxl.asia/blog/2168601.sHtML

原标题：站内邮件消息通知功能开发
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://zhishi.umesxl.asia/blog/0176843.sHtML

原标题：golang github actions 多平台构建
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://zhishi.umesxl.asia/blog/3820260.sHtML

原标题：golang 系统设计内存高占用排查思路
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://zhishi.umesxl.asia/blog/5030215.sHtML

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://zhishi.umesxl.asia/blog/4724717.sHtML

原标题：golang kafka 同步异步消费对比
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://zhishi.umesxl.asia/blog/1426617.sHtML

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://zhishi.umesxl.asia/blog/8345240.sHtML

原标题：消息队列重复消费业务处理
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://zhishi.umesxl.asia/blog/9230210.sHtML

原标题：golang github actions 发布 release 包
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://zhishi.umesxl.asia/blog/1279755.sHtML

原标题：前端图片懒加载性能优化
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://zhishi.umesxl.asia/blog/6857494.sHtML

原标题：Practice：实现限流之后友好业务返回处理
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://zhishi.umesxl.asia/blog/7590972.sHtML

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://zhishi.umesxl.asia/blog/4314354.sHtML

原标题：golang 系统设计大文件上传架构
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://zhishi.umesxl.asia/blog/9656194.sHtML

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://zhishi.umesxl.asia/blog/1416279.sHtML

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://zhishi.umesxl.asia/blog/1467041.sHtML

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://zhishi.umesxl.asia/blog/8367250.sHtML

原标题：golang 系统设计消息消费 offset 管理策略
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://zhishi.umesxl.asia/blog/5668467.sHtML

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://zhishi.umesxl.asia/blog/2584269.sHtML

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://zhishi.umesxl.asia/blog/1533751.sHtML

原标题：Practice：数据库分表简单实现方案与代码示例
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://zhishi.umesxl.asia/blog/5512083.sHtML

原标题：golang 系统设计内存高占用排查思路
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://zhishi.umesxl.asia/blog/4258359.sHtML

原标题：一次数据库死锁现场分析与解决方案记录
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://zhishi.umesxl.asia/blog/7611612.sHtML

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://zhishi.umesxl.asia/blog/0979735.sHtML

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://zhishi.umesxl.asia/blog/6655424.sHtML

原标题：CI 流水线构建失败日志排查
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://zhishi.umesxl.asia/blog/4616148.sHtML

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://zhishi.umesxl.asia/blog/4614709.sHtML

原标题：golang ci 流水线环境变量管理方案
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://zhishi.umesxl.asia/blog/1351246.sHtML

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://zhishi.umesxl.asia/blog/8053508.sHtML

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://zhishi.umesxl.asia/blog/8999907.sHtML

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://zhishi.umesxl.asia/blog/5612010.sHtML

原标题：前端打包产物体积压缩优化
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://zhishi.umesxl.asia/blog/5143879.sHtML

原标题：golang mysql 行锁表锁场景区分
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://zhishi.umesxl.asia/blog/4659704.sHtML

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://zhishi.umesxl.asia/blog/9092458.sHtML

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://zhishi.umesxl.asia/blog/8404698.sHtML

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://zhishi.umesxl.asia/blog/0862029.sHtML

原标题：大事务拆分防止连接池耗尽
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://zhishi.umesxl.asia/blog/4953219.sHtML

原标题：golang nginx 反向代理 go 服务配置
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://zhishi.umesxl.asia/blog/8047332.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://zhishi.umesxl.asia/blog/0258039.sHtML

原标题：golang http 请求重试封装工具
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://zhishi.umesxl.asia/blog/3796523.sHtML

原标题：Security：接口鉴权越权漏洞检测与修复
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://zhishi.umesxl.asia/blog/6353105.sHtML

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://zhishi.umesxl.asia/blog/3159467.sHtML

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://zhishi.umesxl.asia/blog/3843185.sHtML

原标题：golang 系统设计文件存储选型对比
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://zhishi.umesxl.asia/blog/7191689.sHtML

原标题：零基础理解会话、Cookie、Session基础
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://zhishi.umesxl.asia/blog/8662258.sHtML

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://zhishi.umesxl.asia/blog/3507901.sHtML

原标题：复盘总结：数据库迁移升级风险评估清单
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://zhishi.umesxl.asia/blog/2490138.sHtML

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://zhishi.umesxl.asia/blog/8557618.sHtML

原标题：golang mysql 字符集排序规则设置
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://zhishi.umesxl.asia/blog/7856865.sHtML

原标题：golang 配置热更新不重启服务
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://zhishi.umesxl.asia/blog/0895219.sHtML

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://zhishi.umesxl.asia/blog/4847808.sHtML

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://zhishi.umesxl.asia/blog/6457491.sHtML

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://zhishi.umesxl.asia/blog/3491862.sHtML

原标题：golang docker compose 本地开发最佳实践
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://zhishi.umesxl.asia/blog/4453917.sHtML

原标题：Nginx 透传真实客户端 IP 配置
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://zhishi.umesxl.asia/blog/9763326.sHtML

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://zhishi.umesxl.asia/blog/9316656.sHtML

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://zhishi.umesxl.asia/blog/1942614.sHtML

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://zhishi.umesxl.asia/blog/1740035.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://zhishi.umesxl.asia/blog/8205544.sHtML

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://zhishi.umesxl.asia/blog/2038054.sHtML

原标题：golang 系统设计无锁编程思路简单示例
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://zhishi.umesxl.asia/blog/0983196.sHtML

原标题：短信服务封装失败自动重试
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://zhishi.umesxl.asia/blog/4536843.sHtML

原标题：Git 误删提交代码恢复找回
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://zhishi.umesxl.asia/blog/4938162.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.umesxl.asia/blog/2986517.sHtML

原标题：golang jwt 鉴权中间件完整示例
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://zhishi.umesxl.asia/blog/4053139.sHtML

原标题：排错：打包后资源路径，开发生产行为不一致
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://zhishi.umesxl.asia/blog/5540056.sHtML

原标题：golang 内存 pprof 定位内存泄漏
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://zhishi.umesxl.asia/blog/8578682.sHtML

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://zhishi.umesxl.asia/blog/2542114.sHtML

原标题：golang aes 对称加密解密示例
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://zhishi.umesxl.asia/blog/9619776.sHtML

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://zhishi.umesxl.asia/blog/9225452.sHtML

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://zhishi.umesxl.asia/blog/8337989.sHtML

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://zhishi.umesxl.asia/blog/9298756.sHtML

原标题：golang es 分页深分页性能优化
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://zhishi.umesxl.asia/blog/9388258.sHtML

原标题：前端组件库按需加载性能优化
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://zhishi.umesxl.asia/blog/8178595.sHtML

原标题：灰度发布策略服务平滑升级
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://zhishi.umesxl.asia/blog/4292080.sHtML

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://zhishi.umesxl.asia/blog/3012572.sHtML

原标题：磁盘占满服务不可用清理方案
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://zhishi.umesxl.asia/blog/8614286.sHtML

原标题：golang net/http 超时全套配置
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://zhishi.umesxl.asia/blog/8260152.sHtML

三、实战开发｜Practice
原标题：Git 误提交撤销回退实操教程
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://zhishi.umesxl.asia/blog/1352899.sHtML

原标题：Performance：避免内存拷贝，大对象处理优化
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://zhishi.umesxl.asia/blog/5646909.sHtML

原标题：golang 分布式锁 redis 实现
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://zhishi.umesxl.asia/blog/6734469.sHtML

原标题：pnpm 包管理工具实战避坑指南
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://zhishi.umesxl.asia/blog/1601278.sHtML

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://zhishi.umesxl.asia/blog/2353833.sHtML

原标题：golang validator 自定义校验规则
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://zhishi.umesxl.asia/blog/9720781.sHtML

原标题：nodejs 集群模式多核利用实现
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://zhishi.umesxl.asia/blog/5253051.sHtML

原标题：golang 系统设计配置灰度下发简单实现思路
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://zhishi.umesxl.asia/blog/4658188.sHtML

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://zhishi.umesxl.asia/blog/2691827.sHtML

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://zhishi.umesxl.asia/blog/6102383.sHtML

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://zhishi.umesxl.asia/blog/8679141.sHtML

原标题：单元测试用例编写入门实操
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://zhishi.umesxl.asia/blog/9389958.sHtML

原标题：前端静态缓存更新生效处理
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://zhishi.umesxl.asia/blog/2691342.sHtML

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://zhishi.umesxl.asia/blog/7465246.sHtML

原标题：开发记录：批量接口请求并发控制实践
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://zhishi.umesxl.asia/blog/9593294.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://zhishi.umesxl.asia/blog/9057572.sHtML

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://zhishi.umesxl.asia/blog/6826163.sHtML

原标题：CLI 工具进度条交互效果开发
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://zhishi.umesxl.asia/blog/7549408.sHtML

原标题：数据库排序规则统一结果一致
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://zhishi.umesxl.asia/blog/4281299.sHtML

原标题：golang md5 sha 加密工具实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://zhishi.umesxl.asia/blog/2251342.sHtML

原标题：快速入门消息队列基础概念模型
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://zhishi.umesxl.asia/blog/9367648.sHtML

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://zhishi.umesxl.asia/blog/0433328.sHtML

原标题：数值 key 浮点匹配异常规避
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://zhishi.umesxl.asia/blog/0481569.sHtML

原标题：golang http 代理客户端配置
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://zhishi.umesxl.asia/blog/8599553.sHtML

原标题：golang 优雅关闭 grpc 服务示例
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://zhishi.umesxl.asia/blog/0868312.sHtML

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://zhishi.umesxl.asia/blog/4527839.sHtML

原标题：后端登录鉴权模块完整开发
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://zhishi.umesxl.asia/blog/1398073.sHtML

原标题：golang jwt 鉴权中间件完整示例
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://zhishi.umesxl.asia/blog/5490967.sHtML

原标题：服务器 Swap 关闭提升响应速度
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://zhishi.umesxl.asia/blog/1363980.sHtML

原标题：golang 系统设计接口参数防篡改校验
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://zhishi.umesxl.asia/blog/9607750.sHtML

原标题：OpenSource：开源项目贡献者协作流程规范
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://zhishi.umesxl.asia/blog/7708979.sHtML

原标题：golang docker compose 完整语法
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://zhishi.umesxl.asia/blog/1151054.sHtML

原标题：多操作系统开发兼容处理
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://zhishi.umesxl.asia/blog/6992724.sHtML

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://zhishi.umesxl.asia/blog/7084459.sHtML

原标题：golang 系统设计多租户数据隔离方案
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.umesxl.asia/blog/7765182.sHtML

原标题：golang mysql 连接泄漏检测方法
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://zhishi.umesxl.asia/blog/3192400.sHtML

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://zhishi.umesxl.asia/blog/8305251.sHtML

原标题：接口幂等性防重复请求实现
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://zhishi.umesxl.asia/blog/0468498.sHtML

原标题：golang k8s service 服务暴露几种类型
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://zhishi.umesxl.asia/blog/3624499.sHtML

原标题：golang 系统设计 webhook 回调处理架构
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://zhishi.umesxl.asia/blog/7186093.sHtML

四、架构设计｜Architecture
原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://zhishi.umesxl.asia/blog/5238545.sHtML

原标题：快速入门GraphQL基础查询语法示例
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://zhishi.umesxl.asia/blog/8973504.sHtML

原标题：CI 构建缓存加速编译速度
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://zhishi.umesxl.asia/blog/3213399.sHtML

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://zhishi.umesxl.asia/blog/7523527.sHtML

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://zhishi.umesxl.asia/blog/2092503.sHtML

原标题：golang redis 事务 multi exec 使用
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://zhishi.umesxl.asia/blog/2399130.sHtML

原标题：golang 系统设计线上故障排查完整流程
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://zhishi.umesxl.asia/blog/9076020.sHtML

原标题：预编译 SQL 防注入实现
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://zhishi.umesxl.asia/blog/7886900.sHtML

原标题：git cherry‑pick 规范操作防 bug
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://zhishi.umesxl.asia/blog/2855306.sHtML

原标题：前端 pdf 预览渲染方案对比
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://zhishi.umesxl.asia/blog/6644688.sHtML

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://zhishi.umesxl.asia/blog/5981413.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://zhishi.umesxl.asia/blog/3536126.sHtML

原标题：Git LFS 大文件推送失败解决
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://zhishi.umesxl.asia/blog/7591316.sHtML

原标题：开源实践：开源项目如何写好PullRequest
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://zhishi.umesxl.asia/blog/2699794.sHtML

原标题：golang docker 部署 es 本地开发
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://zhishi.umesxl.asia/blog/7209794.sHtML

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://zhishi.umesxl.asia/blog/0469096.sHtML

原标题：消息队列生产消费模型入门
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://zhishi.umesxl.asia/blog/1113330.sHtML

原标题：服务器时钟同步任务错乱修复
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://zhishi.umesxl.asia/blog/2398128.sHtML

?
