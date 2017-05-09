# resume

## 个人业余时间完成的项目

 1. https://github.com/Duuuuuke/vue-template  vue项目生成模板
 2. https://github.com/chunmu 网易云播放器(electron + react + redux)
 
## 工作经历

有一些不方便叙述的项目未填写

###  入职第一个项目 - 接待系统web app 

- 采用icloud框架库搭建web app 主要适配移动端
- 阅读icloud api文档进行开发 具有开箱即用的特点 相类似的还有phonegap ionic等
- 在交互上 icloud有提供一些移动端的事件系统 但是和不太完善
- 在性能上和原生应用差距比较大 不过在后续版本上有提到改善比较大(不知道是不是真的)
- 使用建议  如果是不追求卓越性能的场景 已经可以胜任一般app的工作

### 采购系统样式调整项目

- 项目技术采用的是java+easyui 由于需求方需要修改ui界面
- easyui比较厚重 对于数据表现形式还是比较丰富的  但是界面'不好看'
- 只能在新建全局样式文件覆盖easyui 但是容易产生两种风格不搭的情况

### 及时聊天桌面应用项目

- 技术架构

  -初期：angular1.x + sqlize + node-webkit
  -后期：react + redux + react-router + sqlize + node-webkit 开始启用es6代码 采用babel转换

- angularjs是我接触的第一个单页面应用框架 双向绑定特性吸引力一大批人 不过数据脏检查机制在应用规模大了之后出现比较明显的性能下降问题
- react+redux是当时比较新鲜的一套技术组合 redux参考flux的数据状态机类库  给人一种新世界的感官 规范整理数据流
- 有出现过nw占用过多内存bug 原因是nw脏内存 申请不释放  需要手动调用释放内存 1.8后的版本后修复
- 和nw类似的 electron也不错 但是它新建窗口耗时 通用的解决方案是提前新建窗口 需要时显示 耗电脑性能(可以控制到合理数量)
- 在体验上和原生存在差距(不大)  在接受范围内 

### 办公流程项目

- 采用vue框架 简单易学  生态环境完善 配套类库有vuex vue-router superagent q co lodash等
- UI库使用elementUI 简洁美观 样式库使用bootstrap 最近有grid面世 bootstrap的栅栏系统可能被淘汰 虽然以前就有flexbox 但是好像应用并不是很广
- 采用的是vue-cli初始化项目 我做了一个自定义模板 可以在初始化项目的时候搭建项目挂架  https://github.com/Duuuuuke/vue-template 
  已经具有的包括 路由 http(superagent)库 fiter vuex eslint elementUI
  
### 招聘官网项目

-  h5页面  视觉还原 采用vue框架结合nuxt 通过项目结构生成路由 比较新奇

### 网关项目

- vue项目
- 内部应用api接入和注册管理 统计应用的api数据 比如请求数据  统一接口管理
- 负责前端单页应用开发和nodejs后台数据登记 包括api注册 测试 权限管理
- 后台是java技术(不喜欢java) 完成请求转发统计和监控以及一些限流 安全管理等功能

### 其他记录

- 研究webpack打包速度提升途径
- 项目流程探索  changelog  precommit等工具实践
- 采用sass开发
- pm2部署node后台应用
- 学习go语言  看好go
