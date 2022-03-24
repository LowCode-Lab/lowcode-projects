# 低代码项目集

> 记录市面上已有的 lowcode 项目

```js
[
  {
    name: 'lowcode-engine',
    author: 'alibaba',
    website: 'https://lowcode-engine.cn/',
    isOpenSource: true,
    repository: 'https://github.com/alibaba/lowcode-engine',
    license: 'MIT License'
  },
  {
    name: '钉钉宜搭',
    author: 'alibaba',
    website: 'https://www.aliwork.com/',
    isOpenSource: false
  }
]
```

## 一些说明

### 为什么使用 JSON 形式记录而非更加书面的形式

+ JSON 易于(人类)阅读
+ JSON 易于(机器)处理

### 为什么使用 js 风格的 JSON

+ 因为是由人类完成书写，JSON 过于严格的格式要求（key 要用双引号引起来，String 要用双引号而不能是单引号）不利于人类快速录入，同时也降低了可读性。
+ js 风格的 JSON 可以很轻松的和 json 风格的 JSON 完成互转
+ js 风格的 JSON 其实不是 JSON，是 Javascript 的 Object/Array，但是因为在此处和 JSON 用途等效，所以称其为 JSON
