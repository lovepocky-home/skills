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
  dev[开发技能]
  coo[协作]
  tools[工具基础]
  solution[解决方案]
  techstack[技术栈]
  devops[运维开发]
  docs[文档协同]
  computerbasic[计算机基础]

  root --> coo
  root --> skills

  skills --> dev
  skills --> devops
  skills --> docs
  skills --> computerbasic

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

  coo --> techmana[技术管理]
  coo --> srcmana[代码管理] 

  techmana --> 培训TODO

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

```

链接地址

- demo-angular-nestjs: <https://github.com/lovepocky-home/solution-fullstack-starter>
- leetcode-cn: <https://leetcode-cn.com/u/lovepocky/>
- leetcode: <https://leetcode.com/lovepocky/>

## 协作开发流程

## 其他知识点

- scala/spark
- js/ts
  - koa2
- docker/docker-compose
- elasticsearch
- redis
- mongodb
- mysql
