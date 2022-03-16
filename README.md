# skills

## 说明

目录的组织根据: 需求分类->落地方案(核心方案包括框架性的demo)

## 技能目录

```mermaid
flowchart LR

  classDef demo fill:#00f82f;
  subgraph 样式说明 
    ex-demo[demos]:::demo
    link[link*]
  end
  

 
  root["/"]
  skills[职业技能]
  style skills fill:#f9f
  dev[开发技能]
  coo[协作]
  tools[工具基础]
  solution[解决方案]
  techstack[技术栈]
  devops[运维开发]
  docs[项目文档协同]
  computerbasic[计算机基础]
  personal_effiency[个人效率]

  root --> coo
  root --> skills
  root --> personal_effiency

  skills --> dev
  skills --> devops
  skills --> docs
  skills --> computerbasic

  personal_effiency --> 知识检索
  personal_effiency --> 知识管理
  personal_effiency --> 研发环境
  personal_effiency --> 编码技能

  dev --> tools
  dev --> solution
  dev --> techstack

  solution --> fullstack

  techstack --> graphql
  techstack --> angular
  techstack --> react
  techstack --> vue
  techstack --> nestjs
  techstack --> fastapi
  techstack --> springboot
  techstack --> vertx/quarkus

  graphql -.-> demo-angular-nestjs
  angular -.-> demo-angular-nestjs
  nestjs -.-> demo-angular-nestjs

  coo --> techmana[技术管理]
  coo --> srcmana[代码管理*]:::demo

  techmana --> 培训TODO

  srcmana --> 权限管理
  srcmana --> 分支管理,基于版本和功能
  srcmana --> 代码提交规范
  srcmana --> 代码review/merge
  srcmana --> release/fix

  %% 工具基础
  tools --> git
  tools --> vscode

  %%
  computerbasic --> leetcode[leetcode*]
  click leetcode "https://leetcode.com/lovepocky/"
  computerbasic --> leetcode-cn[leetcode-cn*]
  click leetcode-cn "https://leetcode-cn.com/u/lovepocky/"
  computerbasic --> functional-programming

  %% 
  fullstack --> demo-angular-nestjs[demo-angular-nestjs*]
  demo-angular-nestjs:::demo
  click demo-angular-nestjs href "https://github.com/lovepocky-home/solution-fullstack-starter"

  %% devops
  devops --> kubernetes
  devops --> ansible
  devops --> jenkins
  devops --> gitops

```

链接地址

- demo-angular-nestjs: <https://github.com/lovepocky-home/solution-fullstack-starter>
- leetcode-cn: <https://leetcode-cn.com/u/lovepocky/>
- leetcode: <https://leetcode.com/lovepocky/>

## 协作开发流程

## 补充说明

### 个人效率

#### 编码技能

- vim + vscode
- tmux

## 其他知识点

- scala/spark
- js/ts
  - koa2
- docker/docker-compose
- elasticsearch
- redis
- mongodb
- mysql
