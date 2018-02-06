### 2018-2-6
#### v1.0.0
* 正式发布v1.0.0版
* 添加rewrite支持

### 2017-9-10
#### v0.4.1
* rules配置中的href改名为url（重大调整）
* rules配置添加method参数支持
* 优化样例文件

### 2017-7-21
#### v0.3.15
* 优化cache map

#### v0.3.14
* 修复因cache map出错导致justreq不能启动的bug

### 2018-2-6
#### v1.0.0
* 正式发布v1.0.0版
* 添加rewrite支持

### 2017-4-25
#### v0.3.12
* 优化CORS，保证即使在服务端CORS配置出错时，也能正常开启CORS

### 2017-4-11
#### v0.3.11
* 修复缓存文件不能跟其它开发小伙伴共享的bug

### 2017-3-31
#### v0.3.10
* 启动失败时，显示友好错误信息，以便快速排查

### 2017-3-25
#### v0.3.8
* 只有状态码为200时才缓存

### 2017-3-22
#### v0.3.7
* echo()方法支持直接输出二进制

### 2017-3-19
#### v0.3.6
* 支持在规则rules里替换host、port
* 添加keepFresh规则，保持cache的同时，每次请求总是尝试拉取最新数据

### 2017-3-15
#### v0.3.5
* 修复禁止缓存时的异常

### 2017-3-2
#### v0.3.4
* 优化文档描述

#### v0.3.3
* 修复由于没有配置inspector导致运行JR Server失败的bug

### 2017-3-1
#### v0.3.2
* 支持介入脚本，可自定义是否缓存请求
* 修复一处当代理失败时读取缓存错误的bug

### 2017-2-28
#### v0.3.1
* 所有非ES6文件重构为ES6格式
* 修复新建slow map失败的bug
* 优化proxy管道处理
* JRScript添加几个常用的全局属性
* 找不到jrs脚本时，JR Server将报404错误
* 修复当字符小时17时，reduce计算错误的bug

### 2017-2-20
#### v0.2.13
* 删除部分文件中的回车符 

### 2017-2-9
#### v0.2.12
* 修复当提交包含checkbox的表单时异常退出的BUG

### 2017-2-4
#### v0.2.11
* 支持往RULE规则的subs里添加search

#### v0.2.10
* 支持正则表达式分组替换功能

### 2017-1-19
#### v0.2.9
* 修复代理超时异常退出的BUG

### 2017-1.17
#### v0.2.8
* 优化清楚缓存逻辑

#### v0.2.7
* CORS处理逻辑优化
* 代码规范化

### 2017-1-15
#### v0.2.6
* 优化替身文件日志信息显示
* 修改README.md

### 2017-1-13
#### v0.2.5
* 添加英文版README.md和examples

#### v0.2.4
* 日志信息显示优化
* 去除已弃用依赖

### 2017-1-12
#### v0.2.3
* 修复替身文件读取时异常退出的bug

#### v0.2.2
* 添加jrs处理文件上传的demo
* 修复因网络延迟造成丢包的bug

### 2017-1-11
#### v0.2.1
* 使用http模块及pipe重构server.js
* 使用https模块实现https代理支持
* 使用pipe重构proxy.js
* 使用formidable重构jrs.js
* 错误处理优化，添加jrs脚本400错误处理
* 添加cors配置选项

### 2017-1-9
#### v0.1.3
* 修复jrs脚本set-cookie不成功的bug

### 2017-1-8
#### v0.1.2
* 添加cors跨域支持
* 完善examples