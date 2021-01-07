
<p align="center">
  <a href="https://www.steedos.com/cn">
    <img alt="华炎项目管理系统" src="https://steedos.github.io/assets/logo.png" width="120" />
  </a>
</p>
<h1 align="center">
  车辆管理系统
</h1>

<p align="center">
<a href="https://github.com/steedos/steedos-app-car/blob/master/README.md">English</a>
<a href="https://github.com/steedos/steedos-app-car/issues/"> · 报告错误</a>
<a href="https://github.com/steedos/steedos-app-car/discussions"> · 讨论</a>
</p>

<p align="center" style="border-top: solid 1px #cccccc">
  实现车辆基本信息的统一管理，并统一管控车辆的运营数据，包括车辆行驶里程，以及维修、保养、保险、年检等费用记录等，实现高效、合理的用车管理系统。
</p>

<h3 align="center">
 🤖 🎨 🚀
</h3>


## ✨系统功能

- **车辆信息管理**：管理车辆信息（车辆基本信息、维修记录、保养记录、年检记录、保险记录、出险记录、车辆违章记录等）；管理驾驶员信息（驾驶员基本信息、驾照信息等）；管理车辆使用记录（用车申请记录、车辆调度记录、费用报销记录等）

- **用车审批管理**：根据需求定制用车申请流程、车辆费用报销流程；流程审批完成后，自动生成用车申请记录、费用报销记录。

- **查询与统计**：车辆管理员、管理人员可以拥有不同的权限，对不同范围内的车辆信息进行查询，例如可以查询给定牌照号的车辆在某个特定时间段里的费用情况；按照需求，生成统计报表，包括：费用统计、维修统计、保养统计等。


## 关于华炎魔方

华炎魔方是一套可视化建模、描述式编程的开发工具。设计目标是降低应用构建门槛，让每个人都能参与开发。系统内置了数据建模以及一系列自动化工具，包括验证规则、公式计算、工作流规则、自动化操作、批准过程、报表引擎等等。

- [华炎魔方概述](https://www-steedos-com.oss-accelerate.aliyuncs.com/videos/steedos/steedos-open-source.mp4)
- [华炎魔方文档](https://www.steedos.com/help/)

## 依赖包

- [MongoDB](https://www.mongodb.com/try/download/) version >= 3.4. MongoDB is a general purpose, document-based, distributed database built for modern application developers and for the cloud era.
- [Node.js](https://nodejs.org/en/download/) version >= 10.15.1 or above (which can be checked by running `node -v`). You can use [nvm](https://github.com/nvm-sh/nvm) for managing multiple Node versions on a single machine installed
- [Yarn](https://yarnpkg.com/en/) version >= 1.5 (which can be checked by running `yarn version`). Yarn is a performant package manager for JavaScript and replaces the `npm` client. It is not strictly necessary but highly encouraged.


## 项目目录

```sh
steedos-app-car
├── steedos-app/main/default
│   ├── applications
│   │   └── project.app.yml
│   └── objects
│       └── project__c
│           ├── buttons
│           │   └── print.button.yml
│           │   └── print.button.js
│           ├── fields
│           │   └── name.field.yml
│           │   └── description.field.yml
│           │   └── isDone.field.yml
│           │   └── status__c.field
│           │   └── ...
│           ├── listviews
│           │   └── all.listview.yml
│           │   └── recent.listview.yml
│           │   └── my.listview.yml
│           ├── permissions
│           │   └── user.permission.yml
│           │   └── admin.permission.yml
│           │   └── project_manager.permission.yml
│           └── project.object.yml
│           └──...
├── .env
├── .gitignore
├── package.json
├── README.md
├── server.js
├── steedos-config.yml
└── yarn.lock
```

## 项目运行

项目源码依赖 nodejs 环境，使用 mongodb 数据库，需先部署相应的运行环境。

1、 启动数据库

2、安装依赖软件包

```
yarn
```

3、运行项目

```
yarn start
```

4、使用浏览器访问 http://127.0.0.1:5000/

第一次使用时，数据库为空，需注册一个账户，并选择创建一个企业。

## 保持联系

如果您有任何疑问或想与其他华炎魔方用户交谈，请[点击进入讨论](https://github.com/steedos/steedos-platform/discussions)或扫码添加以下联系方式与我们联系！
##### 开发人员微信群

 ![开发者微信交流群](https://steedos.github.io/assets/github/platform/cn/QR_wechat_developers.jpg)

#### 商务咨询

![商务咨询](https://steedos.github.io/assets/github/platform/cn/business_consulting.jpg)

#### 微信公众号

![微信公众号](https://www.steedos.com/assets/github/platform/cn/public_number.jpg)
 
