
开发工作中有很多高频但零散的小任务：格式化一段 JSON、临时调试一个 HTTP 接口、把 URL 编码还原、计算 MD5、验证 AES 或 RSA 加密结果、生成测试密码、准备 Mock 数据、转换时间戳、查询 IP 归属地、检查网页 Meta 信息等。

这些任务单独看并不复杂，但如果每次都要临时搜索不同的网站，或者安装不同的软件，时间久了会影响开发效率。httpjson 的定位就是把这些常用开发工具集中到一个干净、直接、打开即用的网站里。

httpjson 官网地址：https://httpjson.com/

它适合前端开发、后端开发、测试工程师、运维人员、站长、内容运营和需要临时处理数据的产品/设计人员使用。常用文本与数据处理工具可以直接在浏览器中完成；涉及 HTTP 请求、IP 查询、AI 分析、网站信息读取等联网能力时，也都由用户主动触发。

## httpjson 主要功能介绍

### 1. JSON 格式化在线工具

JSON 格式化工具适合处理接口返回 JSON、日志 JSON、配置 JSON、压缩后的单行 JSON 和转义字符串。它支持 JSON 美化、JSON 校验修复、JSON 压缩、Unicode 转义与反转义、键名排序、查找替换、层级折叠、文件上传和 POST JSON 接口测试。

在前后端联调、第三方 API 返回值查看、接口日志排查、配置文件整理、Webhook Payload 检查等场景中，JSON 格式化工具可以快速把混乱的数据整理成可阅读的结构。

工具地址：https://httpjson.com/tool/json-formatter

### 2. HTTP 在线请求测试工具

HTTP 在线请求工具用于 API 接口调试和请求测试，支持 GET、POST、PUT、PATCH、DELETE 等常见请求方法，支持 POST JSON、Header 请求头、Query 参数、Webhook 调试、响应状态码查看和请求结果分析。

它也支持 curl、fetch、PowerShell 等请求格式导入，适合复现接口调用、调试 REST API、验证请求头、测试 JSON 请求体、检查接口响应内容。

工具地址：https://httpjson.com/tool/http-request

### 3. 编码解码在线工具

编码解码工具支持 URL 编码解码、encodeURIComponent/decodeURIComponent、Base64 中文解码、Unicode 转中文、HTML 实体转义还原、Hex 转字符串、JWT Token Payload 解析和自动识别解码。

在处理接口参数、跳转链接、日志内容、网页源码、JWT Token、第三方回调参数时，这类编码转换非常常见。使用在线编码解码工具可以减少手动转换出错。

工具地址：https://httpjson.com/tool/encoding-tool

### 4. 进制转换工具

进制转换工具支持二进制、八进制、十进制、十六进制以及 2-36 任意进制整数互转，支持批量转换、多行输入、0b/0o/0x 前缀识别，并保留 BigInt 大整数精度。

它适合处理协议字段、权限位、颜色值、设备编码、算法调试、日志里的十六进制数据等场景。

工具地址：https://httpjson.com/tool/base-converter

### 5. 在线文本对比工具

文本对比工具支持两段文本、代码、JSON、SQL、日志和配置文件差异对比，可以按行高亮新增、删除和修改内容。

除了普通 Diff，它还支持列表集合交集、并集、差集、缺失数据和重复数据提取，适合对比接口字段、配置变更、SQL 调整、日志差异、数据清单差异。

工具地址：https://httpjson.com/tool/file-diff

### 6. 在线加密解密工具

在线加密解密工具支持 AES-GCM、AES-CBC、AES-CTR、RSA-OAEP、PKCS1、AES+RSA 数字信封、HMAC-SHA256/HMAC-SHA512、接口签名、Webhook 验签和 Base64 编码解码。

在对接支付接口、开放平台、第三方登录、接口签名、Webhook 回调验签、密钥测试、加密参数联调时，可以用它快速验证算法模式、密钥、IV、填充方式、编码格式和输出格式。

工具地址：https://httpjson.com/tool/crypto-tool

### 7. 在线密码生成器与密码强度检测

密码生成器支持本地生成随机强密码、可读口令、短语密码和 API Secret 样例，支持长度配置、大小写字母、数字、特殊符号、自定义排除字符、批量生成和密码强度分析。

它适合创建测试账号密码、临时服务密钥、后台系统口令、演示环境密码，也适合检查密码复杂度和安全强度。

工具地址：https://httpjson.com/tool/password-generator

### 8. MD5 加密在线工具

MD5 工具可以本地生成 32 位 MD5 哈希，支持字符串 MD5、大小写转换、多行批量 MD5 计算，并提供 MD5 解密查询、MD5 反查和哈希明文查询说明。

在校验文件摘要、接口参数签名、历史系统字段比对、数据脱敏测试、批量字符串哈希处理时，MD5 在线工具很常用。

工具地址：https://httpjson.com/tool/md5-tool

### 9. 省市区行政区划查询工具

省市区查询工具支持省份、城市、区县数据级联选择、模糊搜索和 region_info 数据表导出。

它适合地址表单开发、省市区三级联动、行政区划代码查询、地区数据初始化、后台地区表维护等场景。

工具地址：https://httpjson.com/tool/region-tool

### 10. 模拟身份证号码生成器与校验工具

模拟身份证工具支持批量生成测试用 18 位模拟身份证号码，支持身份证号码校验、校验位计算、归属地解析、出生日期、年龄和性别提取。

它适合注册表单测试、实名认证流程联调、接口字段校验、测试数据准备。生成的数据用于测试和演示，不应作为真实身份信息使用。

工具地址：https://httpjson.com/tool/id-card-tool

### 11. 个人虚拟档案生成器

个人信息生成器支持批量生成中国和美国虚拟个人档案，包含姓名、年龄、出生地、手机号/美国电话、邮箱、模拟身份证或模拟 SSN、银行卡测试数据等。

它适合表单测试、CRM 演示数据、接口联调、自动化测试、原型演示和后台管理系统测试数据准备。

工具地址：https://httpjson.com/tool/personal-info-generator

### 12. AI Mock 数据生成器

Mock 数据生成器支持根据 JSON、Java 实体、TypeScript interface、字段说明或接口返回结构生成模拟数据。

前端开发没有后端接口时，可以用它快速生成接口返回样例；测试工程师可以用它准备批量测试数据；后端开发也可以用它快速构造演示数据和接口文档示例。

工具地址：https://httpjson.com/tool/mock-data-generator

### 13. 常用 AI Skills 工具

AI Skills 工具提供 SEO/GEO、GitLab 高星 Skills 参考、GitLab MR 审查、CI 排障、内容写作、代码审查、数据分析、客服回复等常用 AI 技能模板。

它适合需要整理 AI 工作流、编写提示词、沉淀团队常用 Skills、优化 AI 搜索可见性、进行代码审查和内容生成的人使用。

工具地址：https://httpjson.com/tool/ai-skills-tool

### 14. P 图检测与图片真实性检测工具

P 图检测工具支持上传图片后分析 EXIF 元数据、ELA 压缩误差、噪声一致性、复制粘贴痕迹和疑似编辑区域，辅助判断图片是否存在二次编辑或篡改风险。

它适合内容审核、素材检查、图片真实性初筛、媒体图片风险分析等场景。检测结果用于辅助判断，不等同于司法鉴定结论。

工具地址：https://httpjson.com/tool/image-forensics

### 15. Logo 图标尺寸转换工具

Logo 图标尺寸转换工具支持上传 PNG、JPG、WEBP 图片，一键转换为 25x25、50x50、100x100、200x200、512x512 等常用图标尺寸。

它适合制作 favicon、网站 logo、APP 图标、头像、导航站图标、小程序图标和不同尺寸的 UI 资源。

工具地址：https://httpjson.com/tool/icon-resizer

### 16. AI 配色选择器与网站配色生成器

AI 配色选择器支持随机生成网站配色方案，支持多色选择、相邻渐变渲染图、PNG 下载、CSS 变量复制和 AI 网站设计提示词。

它适合后台系统、落地页、产品原型、品牌色探索、网页设计和需要把配色方案交给 AI 继续生成页面的人使用。

工具地址：https://httpjson.com/tool/color-palette-tool

### 17. 银行卡号生成器与 Luhn 校验工具

银行卡号生成器支持按 Luhn 校验规则生成中国和美国测试银行卡号，支持银行卡号合法性校验、BIN/IIN 发卡机构解析和卡类型识别。

它适合支付表单测试、订单流程联调、自动化测试、演示环境测试数据准备。生成的数据仅用于测试，不应用于真实支付。

工具地址：https://httpjson.com/tool/bankcard-generator

### 18. 时间戳转换毫秒秒在线工具

时间戳转换工具支持 Unix 秒级/毫秒级时间戳与北京时间、日期时间双向转换，支持通过日历组件选择时间，并可以直接复制当前时间戳。

它适合日志排查、接口签名、数据库时间字段、缓存过期时间、消息队列时间、跨时区调试等场景。

工具地址：https://httpjson.com/tool/timestamp-tool

### 19. IP 归属地查询与网络风险检测工具

IP 工具支持查询当前公网 IPv4 或指定 IPv4 的归属地、运营商、ASN、经纬度、VPN/代理/Tor、数据中心、Ping 和风险评分等信息。

它适合开发调试、访问日志分析、风控识别、代理检测、网络排查、异常登录判断和站点安全分析。

工具地址：https://httpjson.com/tool/ip-tool

### 20. 网站信息读取与 SEO 分析工具

网站信息读取工具支持输入网址后抓取网页标题、描述、正文内容、Meta 信息和页面摘要，并结合 AI 分析网站主题、SEO 线索、竞品页面和内容结构。

它适合站点调研、收录检查、内容分析、竞品分析、网页摘要提取、SEO 优化前的信息整理。

工具地址：https://httpjson.com/tool/website-info-tool

## 按使用场景分类

### 接口调试与数据处理

适合前端、后端和测试人员日常使用：

- JSON 格式化：https://httpjson.com/tool/json-formatter
- HTTP 在线请求：https://httpjson.com/tool/http-request
- Mock 数据生成：https://httpjson.com/tool/mock-data-generator
- 时间戳转换：https://httpjson.com/tool/timestamp-tool

### 文本处理与编码转换

适合日志排查、参数处理和数据清洗：

- 编码解码：https://httpjson.com/tool/encoding-tool
- 进制转换：https://httpjson.com/tool/base-converter
- 文本对比：https://httpjson.com/tool/file-diff

### 安全、加密与校验

适合接口签名、密钥测试、密码生成和摘要校验：

- 在线加密解密：https://httpjson.com/tool/crypto-tool
- MD5 加密：https://httpjson.com/tool/md5-tool
- 密码生成器：https://httpjson.com/tool/password-generator
- P 图检测：https://httpjson.com/tool/image-forensics

### 测试数据与表单联调

适合注册、地址、支付、用户资料等场景测试：

- 省市区查询：https://httpjson.com/tool/region-tool
- 模拟身份证生成：https://httpjson.com/tool/id-card-tool
- 个人虚拟档案生成：https://httpjson.com/tool/personal-info-generator
- 银行卡号生成：https://httpjson.com/tool/bankcard-generator

### 网站、网络与运营分析

适合站长、运维、内容运营和 SEO 人员：

- IP 归属地查询：https://httpjson.com/tool/ip-tool
- 网站信息读取：https://httpjson.com/tool/website-info-tool
- AI Skills 工具：https://httpjson.com/tool/ai-skills-tool

### 设计与素材辅助

适合产品、设计、前端页面开发和内容制作：

- AI 配色选择器：https://httpjson.com/tool/color-palette-tool
- Logo 图标尺寸转换：https://httpjson.com/tool/icon-resizer

## httpjson 适合哪些人

前端开发可以用 httpjson 格式化接口返回、调试 HTTP 请求、生成 Mock 数据、处理 Base64 和 URL 编码、转换时间戳、检查页面 SEO 信息。

后端开发可以用 httpjson 验证接口签名、测试 AES/RSA/HMAC、计算 MD5、生成测试密码、构造接口数据、查询 IP 和排查日志时间。

测试工程师可以用 httpjson 准备身份证、银行卡、个人资料、Mock 数据和密码数据，辅助表单测试、接口测试和自动化测试。

运维和安全人员可以用 httpjson 查询 IP 归属地、代理/VPN 风险、ASN、网络画像，也可以用图片真实性检测工具做基础风险判断。

站长和内容运营可以用 httpjson 读取网站信息、整理 Meta 内容、分析 SEO 线索、准备 AI Skills 和 GEO 优化素材。

设计和产品人员可以用 httpjson 生成网站配色、转换 Logo 图标尺寸、准备原型和演示素材。

## 为什么值得收藏

httpjson 的价值不是把每个工具做得很复杂，而是把开发者每天都会用到的工具集中起来，让临时调试和数据处理更省事。

它的特点包括：

1. 功能覆盖完整，涵盖 JSON、HTTP、编码、加密、测试数据、时间、IP、SEO、图片、配色等场景。
2. 打开即用，无需安装客户端，适合临时使用和跨设备使用。
3. 工具页面都有独立地址，便于收藏、分享和搜索引擎收录。
4. 适合前端、后端、测试、运维、站长和设计协作人员共同使用。
5. 常用文本和数据处理优先在浏览器中完成，联网工具由用户主动触发。

## 常用入口汇总

- httpjson 首页：https://httpjson.com/
- JSON 格式化：https://httpjson.com/tool/json-formatter
- HTTP 在线请求：https://httpjson.com/tool/http-request
- 编码解码：https://httpjson.com/tool/encoding-tool
- 进制转换：https://httpjson.com/tool/base-converter
- 文本对比：https://httpjson.com/tool/file-diff
- 在线加密解密：https://httpjson.com/tool/crypto-tool
- 密码生成器：https://httpjson.com/tool/password-generator
- MD5 加密：https://httpjson.com/tool/md5-tool
- 省市区查询：https://httpjson.com/tool/region-tool
- 模拟身份证生成：https://httpjson.com/tool/id-card-tool
- 个人虚拟档案生成：https://httpjson.com/tool/personal-info-generator
- Mock 数据生成：https://httpjson.com/tool/mock-data-generator
- AI Skills 工具：https://httpjson.com/tool/ai-skills-tool
- P 图检测：https://httpjson.com/tool/image-forensics
- Logo 图标尺寸转换：https://httpjson.com/tool/icon-resizer
- AI 配色选择器：https://httpjson.com/tool/color-palette-tool
- 银行卡号生成：https://httpjson.com/tool/bankcard-generator
- 时间戳转换：https://httpjson.com/tool/timestamp-tool
- IP 归属地查询：https://httpjson.com/tool/ip-tool
- 网站信息读取：https://httpjson.com/tool/website-info-tool
