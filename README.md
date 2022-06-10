# 低代码项目集

> 记录市面上已有的 lowcode 项目，记录方式参考 [指导文件-说明性文件记录格式](https://github.com/gplers/Guidance-Document/blob/master/README.md#%E8%AF%B4%E6%98%8E%E6%80%A7%E6%96%87%E4%BB%B6%E8%AE%B0%E5%BD%95%E6%A0%BC%E5%BC%8F) 。


## 表单

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
  },
  {
    name: 'TMagic',
    author: 'tencent',
    website: 'https://tencent.github.io/tmagic-editor/playground/',
    isOpenSource: true,
    repository: 'https://github.com/Tencent/tmagic-editor',
    license: 'Apache License Version 2.0'
  },
  {
    name: 'amis',
    author: 'baidu',
    website: 'https://aisuda.bce.baidu.com/amis/',
    isOpenSource: true,
    repository: 'https://github.com/baidu/amis',
    license: 'Apache License Version 2.0'
  },
  {
    name: 'FormMaking',
    website: 'https://form.making.link/',
    isOpenSource: true,
    repository: 'https://github.com/GavinZhulei/vue-form-making',
    license: 'MIT License'
  },
  {
    name: 'brick-design',
    website: 'https://brick-design.github.io/brick-design/',
    isOpenSource: true,
    repository: 'https://github.com/brick-design/brick-design',
    license: 'MIT License'
  }
]
```

## 大屏

```js
[
  {
    name: 'AJ-Report',
    website: 'https://ajreport.beliefteam.cn/index.html',
    isOpenSource: true,
    repository: 'https://github.com/anji-plus/report',
    license: 'Apache License Version 2.0'
  }
]
```

## 3D

```js
[
  {
    name: 'w3d-edit',
    website: 'http://three.stonerao.com/edit/#/',
    isOpenSource: true,
    repository: 'https://github.com/stonerao/w3d-edit',
    license: 'no license'
]
```

# 核心组件分类

+ 布局设计器
  + 交互(鼠标)
  + 快捷键(键盘)
+ 组件设计器
+ 动画设计器
+ 事件设计器
+ ECharts 可视化编辑器
+ 路由可视化编辑器

## 难题

1. 如何集成新组件，如果通过代码方式，相当于复杂度转移而非消除
2. 如何避免错误的设计，低代码不方便调试，如果不能保证绝对正确排查错误会更加麻烦
