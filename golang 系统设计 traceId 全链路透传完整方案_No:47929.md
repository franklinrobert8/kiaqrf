最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 traceId 全链路透传完整方案
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.ezol3m.asia/arts/378059.Doc

原标题：分布式任务调度集群原型开发
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.ezol3m.asia/arts/274700.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.ezol3m.asia/arts/304906.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.ezol3m.asia/arts/427974.Doc

原标题：日志输出规范防止磁盘爆满
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.ezol3m.asia/arts/160776.Doc

原标题：golang lru 缓存淘汰算法编写
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.ezol3m.asia/arts/830963.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.ezol3m.asia/arts/658569.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.ezol3m.asia/arts/372405.Doc

原标题：golang 配置文件多环境加载
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.ezol3m.asia/arts/550986.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.ezol3m.asia/arts/456336.Doc

原标题：前端打包产物体积压缩优化
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/504298.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.ezol3m.asia/arts/376326.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ezol3m.asia/arts/122932.Doc

原标题：golang 系统设计分布式任务调度
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.ezol3m.asia/arts/911402.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.ezol3m.asia/arts/319328.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.ezol3m.asia/arts/644499.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.ezol3m.asia/arts/429279.Doc

原标题：Git LFS 大文件推送失败解决
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.ezol3m.asia/arts/038970.Doc

原标题：大文件导出内存溢出防护
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ezol3m.asia/arts/967669.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.ezol3m.asia/arts/960066.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.ezol3m.asia/arts/552995.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.ezol3m.asia/arts/439103.Doc

原标题：golang redis 过期 key 监听业务
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ezol3m.asia/arts/810910.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.ezol3m.asia/arts/900987.Doc

原标题：业务错误码完整落地实践
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.ezol3m.asia/arts/152184.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.ezol3m.asia/arts/041078.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.ezol3m.asia/arts/597314.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.ezol3m.asia/arts/468642.Doc

原标题：golang redis 连接池参数最佳值
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.ezol3m.asia/arts/900255.Doc

原标题：快速入门简单签名校验实现思路
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.ezol3m.asia/arts/079438.Doc

原标题：超大数据集分页性能优化方案
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/023584.Doc

原标题：前端错误监控上报系统搭建
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.ezol3m.asia/arts/621121.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.ezol3m.asia/arts/991280.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.ezol3m.asia/arts/042902.Doc

原标题：golang redis pipeline 批量操作
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.ezol3m.asia/arts/009403.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ezol3m.asia/arts/426011.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.ezol3m.asia/arts/353703.Doc

原标题：OOMKilled 容器被杀完整排查
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/635359.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/245497.Doc

原标题：ORM 框架数据库增删改查实操
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.ezol3m.asia/arts/727401.Doc


二、踩坑排错｜Troubleshooting
原标题：安全复盘：业务登录暴力破解防护完整方案
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.ezol3m.asia/arts/244818.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.ezol3m.asia/arts/753875.Doc

原标题：golang 分布式 ID 雪花算法实现
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.ezol3m.asia/arts/485581.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.ezol3m.asia/arts/170219.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.ezol3m.asia/arts/102414.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.ezol3m.asia/arts/261212.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.ezol3m.asia/arts/753994.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.ezol3m.asia/arts/318410.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.ezol3m.asia/arts/637223.Doc

原标题：css 变量主题切换方案实现
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/836124.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/164818.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/594669.Doc

原标题：并发数据覆盖加锁安全处理
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.ezol3m.asia/arts/537987.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.ezol3m.asia/arts/531076.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.ezol3m.asia/arts/567118.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.ezol3m.asia/arts/292887.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.ezol3m.asia/arts/820637.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.ezol3m.asia/arts/358498.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.ezol3m.asia/arts/125979.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.ezol3m.asia/arts/192653.Doc

原标题：从零编写简易 CLI 命令行工具
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.ezol3m.asia/arts/933588.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.ezol3m.asia/arts/353866.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.ezol3m.asia/arts/837729.Doc

原标题：前后端交互跨域问题完整处理
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.ezol3m.asia/arts/241446.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.ezol3m.asia/arts/744198.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.ezol3m.asia/arts/566501.Doc

原标题：golang prometheus histogram 指标
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.ezol3m.asia/arts/953213.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.ezol3m.asia/arts/655197.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.ezol3m.asia/arts/594221.Doc

原标题：容器资源限制防止宿主机过载
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/348032.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.ezol3m.asia/arts/195685.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.ezol3m.asia/arts/894248.Doc

原标题：游标分页大数据查询性能提升
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.ezol3m.asia/arts/084576.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.ezol3m.asia/arts/464952.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.ezol3m.asia/arts/409170.Doc

原标题：Cookie Session 会话状态管理
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.ezol3m.asia/arts/450561.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/148460.Doc

原标题：无用对象回收抑制内存上涨
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.ezol3m.asia/arts/237663.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.ezol3m.asia/arts/996377.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.ezol3m.asia/arts/488033.Doc

三、实战开发｜Practice
原标题：Nginx 缓冲区调优大文件上传
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.ezol3m.asia/arts/530071.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.ezol3m.asia/arts/633838.Doc

原标题：golang redis pipeline 批量操作
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.ezol3m.asia/arts/946598.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.ezol3m.asia/arts/266595.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.ezol3m.asia/arts/834777.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.ezol3m.asia/arts/703745.Doc

原标题：golang 速率限制令牌桶实现
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ezol3m.asia/arts/687443.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.ezol3m.asia/arts/384988.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.ezol3m.asia/arts/166020.Doc

原标题：golang k8s 资源请求限制配置
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.ezol3m.asia/arts/856822.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.ezol3m.asia/arts/494169.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.ezol3m.asia/arts/011615.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.ezol3m.asia/arts/645211.Doc

原标题：Docker 网络模式容器互通设置
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.ezol3m.asia/arts/934674.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.ezol3m.asia/arts/572178.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/261822.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.ezol3m.asia/arts/506684.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.ezol3m.asia/arts/325174.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.ezol3m.asia/arts/207478.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.ezol3m.asia/arts/075980.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.ezol3m.asia/arts/884818.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.ezol3m.asia/arts/675281.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.ezol3m.asia/arts/419929.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.ezol3m.asia/arts/325292.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.ezol3m.asia/arts/347122.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.ezol3m.asia/arts/085700.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.ezol3m.asia/arts/228418.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.ezol3m.asia/arts/931009.Doc

原标题：golang context 上下文传参讲解
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.ezol3m.asia/arts/158414.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.ezol3m.asia/arts/338195.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.ezol3m.asia/arts/460658.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://wiki.ezol3m.asia/arts/459217.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.ezol3m.asia/arts/205154.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.ezol3m.asia/arts/746536.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.ezol3m.asia/arts/175126.Doc

原标题：golang html 模板渲染简单示例
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.ezol3m.asia/arts/234198.Doc

原标题：DevOps：日志标准输出容器日志收集方案
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.ezol3m.asia/arts/672814.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.ezol3m.asia/arts/309969.Doc

原标题：浏览器内存泄漏排查前端页面
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.ezol3m.asia/arts/533321.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/792843.Doc

四、架构设计｜Architecture
原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.ezol3m.asia/arts/559985.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://wiki.ezol3m.asia/arts/408464.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.ezol3m.asia/arts/072068.Doc

原标题：golang context 上下文传参讲解
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.ezol3m.asia/arts/526274.Doc

原标题：golang cron 定时任务防并发执行
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.ezol3m.asia/arts/247629.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.ezol3m.asia/arts/774806.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.ezol3m.asia/arts/830436.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.ezol3m.asia/arts/689177.Doc

原标题：Security：服务器最小权限账号运维实践
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.ezol3m.asia/arts/759141.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.ezol3m.asia/arts/456377.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.ezol3m.asia/arts/201178.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.ezol3m.asia/arts/426232.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.ezol3m.asia/arts/967574.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.ezol3m.asia/arts/638021.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.ezol3m.asia/arts/650626.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.ezol3m.asia/arts/706285.Doc

原标题：golang redis 批量 pipeline 实践
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.ezol3m.asia/arts/724980.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.ezol3m.asia/arts/826996.Doc

?
