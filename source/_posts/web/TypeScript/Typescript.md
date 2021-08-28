---
title: Typescript 基础教程
date: '2021-01-02 12:23:00'
tages: 'typescript'
categories: 'typescript'
comments: true
top_img: 'https://images.unsplash.com/photo-1598387993211-5c4c0fda4248?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dHlwZXNjcmlwdHxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60'
cover: 'https://images.unsplash.com/photo-1598387993211-5c4c0fda4248?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dHlwZXNjcmlwdHxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=600&q=60'
description: 'typescript 基础语法的使用'

---

# 安装 Typescript

​	**Typescript 官网地址**: https://www.typescriptlang.org/zh/

​	使用 nvm 来管理 node 版本: https://github.com/nvm-sh/nvm

## 安装Typescript	

```npm
npm install -g typescript
```

## 使用 tsc 全局命令

1. 查看 tsc 版本

```shell
tsc -v
```

2. 编译 ts 文件

```shell
tsc fileName.ts
```

# 原始数据类型

​	**原始数据类型 - primitive values:**

- Boolean
- Null
- Undefined
- Biglnt
- Sting
- Symbol

```typescript
// 布尔类型
let isDone: boolean = false

// number注意: es6 支持2进制和8进制
let age: number = 10
let binaryNumber: number = 0b1111

// 之后是字符串，注意es6新增的模版字符串也是没有问题的
let firstName: string = 'lishun'
let message: string = `Hello, ${firstName}, age is ${age}`

// undefined 和 null
let u: undefined = undefined
let n: null = null

// 注意 undefined 和 null 是所有类型的子类型。也就是说 undefined 类型的变量，可以赋值给 number 类型的变量：
let num: number = undefined
```

