<h1 align="center">
  Steedos Car Management System
</h1>

<p align="center">
<a href="https://github.com/steedos/steedos-app-car/blob/master/README_cn.md">中文</a>
<a href="https://github.com/steedos/steedos-app-car/issues/"> · Report a bug</a>
<a href="https://github.com/steedos/steedos-app-car/discussions"> · Discussions</a>
</p>

<p align="center" style="border-top: solid 1px #cccccc">
  Realize the unified management of vehicle basic information, and unified control of vehicle operation data, including vehicle mileage, and maintenance, insurance, annual inspection and other cost records, to achieve efficient and reasonable vehicle management system.

</p>

<h3 align="center">
 🤖 🎨 🚀
</h3>

## Features

- **Vehicle information management**: manage vehicle information (vehicle basic information, maintenance records, maintenance records, annual inspection records, insurance records, accident records, vehicle violation records, etc.); manage driver information (driver basic information, driver license information, etc.); manage vehicle use records (vehicle application records, vehicle scheduling records, expense reimbursement records, etc.)
- **Vehicle Approval Management**: customize the vehicle application process and vehicle expense reimbursement process according to the demand; after the process approval is completed, the vehicle application records and expense reimbursement records are automatically generated.
- **Milestone**: Milestone is usually set in the planning phase of a project and are updated as the project progresses. They are visual reference points, which can decompose the project into manageable and controllable phases to create orderly nodes to help project managers and teams anchor projects.
- **Query and Statistics**: Vehicle Administrators and managers can have different permissions to query vehicle information in different ranges, for example, they can query the expenses of vehicles with a given license number in a specific period of time; according to the demand, they can generate statistical reports, including expense statistics, repair statistics, maintenance statistics, etc.

## Requirements

- [MongoDB](https://www.mongodb.com/try/download/) version >= 4.2. MongoDB is a general purpose, document-based, distributed database built for modern application developers.
- [Node.js](https://nodejs.org/en/download/) version >= 10.15.1 or above (which can be checked by running `node -v`). You can use [nvm](https://github.com/nvm-sh/nvm) for managing multiple Node versions on a single machine installed.
- [Yarn](https://yarnpkg.com/en/) version >= 1.5 (which can be checked by running `yarn version`). Yarn is a performant package manager for JavaScript and replaces the `npm` client. It is not strictly necessary but highly encouraged.


## Project Structure

```sh
steedos-app-car
├── steedos-app/main/default
│   ├── applications
│   │   └── project.app.yml
│   └── objects
│       └──project__c
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

##  Quick Start

The source code of the project depends on nodejs environment. To use mongodb database, the corresponding running environment should be deployed first.

  1. Start the database  
  2. Install dependent packages
  3. Running project
  4. Using browser access `http://127.0.0.1:5000/`    For the first time, the database is empty. You need to register an account and choose to create an enterprise.

## About  Steedos Platform

Steedos Platform is a visual modeling and descriptive programming development tool. The design goal is to lower the threshold of application construction so that everyone can participate in the development. The system has built-in data modeling and a series of automatic tools, including validation rules, public computing, workflow rules, automatic operation, approval process, report engine and so on.

- [Steedos Platform](https://www.steedos.org/)

## Keep in Contact

If you have any questions or want to talk to other users of Steedos Platform , please jump to GitHub for discussion [Click to Discuss](https://github.com/steedos/steedos-platform/discussions) or [Join me on Slack-it's a faster,simpler way to work](https://join.slack.com/t/steedos/shared_invite/zt-jq7eupr9-cgKrUOyWb1zymniRzhH4jg).
