# SDU 教学评估

自动对所有老师进行教学评估。

## Require

- You should install `Node.JS` and you can download it here: [Node.JS](https://nodejs.org/zh-cn/).

- Install tutorial: [菜鸟教程-Node.JS 安装教程](https://www.runoob.com/nodejs/nodejs-install-setup.html)

## Use

prepare: 
```bash
> git clone git@github.com:Grapedge/SDU-Evaluation.git evaluation
> cd ./evaluation
> npm install
```

open `index.js` and modify `config`:

```js
const config = {
  username: '学号', // 你的学号
  password: '密码', // 你的密码
};
```

then, run script:

```bash
> node ./index.js
```