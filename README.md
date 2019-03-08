# viscum-sel2el

[![TypeScript](https://img.shields.io/badge/lang-typescript-blue.svg)](https://www.tslang.cn/) [![Build Status](https://travis-ci.org/yusangeng/viscum-sel2el.svg?branch=master)](https://travis-ci.org/yusangeng/viscum-sel2el) [![Coverage Status](https://coveralls.io/repos/github/yusangeng/viscum-sel2el/badge.svg?branch=master)](https://coveralls.io/github/yusangeng/viscum-sel2el?branch=master) [![Npm Package Info](https://badge.fury.io/js/viscum-sel2el.svg)](https://www.npmjs.com/package/viscum-sel2el) [![Downloads](https://img.shields.io/npm/dw/viscum-sel2el.svg?style=flat)](https://www.npmjs.com/package/viscum-sel2el)

## 综述 | Abstract

CSS选择函数.

## 安装 | Install

``` bash
npm install @viscum/sel2el --save
```

## 使用 | Usage

``` ts
import sel2el from '@viscum/sel2el'

// return document.querySelector(input)
const el = sel2el('#foobar')

// return input element
const el2 = sel2el(el)
```
