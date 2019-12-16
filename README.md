## @cloudbase/adapter-wx_game

[![NPM Version](https://img.shields.io/npm/v/@cloudbase/adapter-wx_game.svg?style=flat)](https://www.npmjs.com/package/@cloudbase/adapter-wx_game)
[![](https://img.shields.io/npm/dt/@cloudbase/adapter-wx_game.svg)](https://www.npmjs.com/package/@cloudbase/adapter-wx_game)

tcb-js-sdk微信小游戏适配器

## 安装
```bash
npm i @cloudbase/adapter-wx_game -S
```

## 使用
### ES Module
```javascript
import tcb from 'tsb-js-sdk';
import adapter from '@cloudbase/adapter-wx_game';

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```

### CommonJS
```javascript
const tcb = require('tsb-js-sdk');
const {adapter} = require('@cloudbase/adapter-wx_game');

// 以下两种方式二选一
// 1.单参数传入
tcb.useAdapters(adapter);
// 2.数组形式传参
tcb.useAdapters([adapter]);
// adapter必须在init之前传入
tcb.init();
```