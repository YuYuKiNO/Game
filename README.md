# Game

按原仓库名称整理的 JavaScript 静态网页项目。每个项目的 HTML、JavaScript、图片和 README 均按来源提交原样复制。

| 项目 | 页面入口 | 来源仓库 | 来源提交 |
| --- | --- | --- | --- |
| HJUN | [HJUN/index.html](./HJUN/index.html) | [HJUN](https://github.com/YuYuKiNO/HJUN) | [19513c0](https://github.com/YuYuKiNO/HJUN/commit/19513c0dfe59bcc9fa5aaa9f633d4f4f7e5acd12) |
| huafu | [huafu/index.html](./huafu/index.html) | [huafu](https://github.com/YuYuKiNO/huafu) | [c47353d](https://github.com/YuYuKiNO/huafu/commit/c47353dbe78e85655898736f09ced188961d9fa2) |
| IJUN | [IJUN/index.html](./IJUN/index.html) | [IJUN](https://github.com/YuYuKiNO/IJUN) | [29c0dee](https://github.com/YuYuKiNO/IJUN/commit/29c0deecf2e0f3a4931ca80e115f5a68d485d936) |
| LCC | [LCC/index.html](./LCC/index.html) | [LCC](https://github.com/YuYuKiNO/LCC) | [fc1ab28](https://github.com/YuYuKiNO/LCC/commit/fc1ab28d232978361c404611b53c94c54a2965de) |
| MAO | [MAO/index.html](./MAO/index.html) | [MAO](https://github.com/YuYuKiNO/MAO) | [bb25bc6](https://github.com/YuYuKiNO/MAO/commit/bb25bc6517c44bf1c4134715dba466ee39977fc1) |
| maoGroup | [maoGroup/index.html](./maoGroup/index.html) | [maoGroup](https://github.com/YuYuKiNO/maoGroup) | [29c0dee](https://github.com/YuYuKiNO/maoGroup/commit/29c0deecf2e0f3a4931ca80e115f5a68d485d936) |

## 本地运行

在本目录运行 `python -m http.server 8000`，再打开 `http://localhost:8000/项目名/`；也可以直接在浏览器中打开各项目的 `index.html`。

## 整理范围

- 本次纳入 HJUN、huafu、IJUN、LCC、MAO、maoGroup 六个公开仓库。
- yuyin 是需要 Python 运行环境的项目，因此未纳入。
- maoWXgroup 是空仓库，没有可整理的网页文件。
- 原仓库保持不变；这里收录的是注明来源提交的文件副本，不包含原仓库的 Git 历史。

## 原项目已有问题

- LCC/index.html 初次加载时引用 `image/main.jpg`，但来源仓库没有该文件。各队伍图片仍按原目录收录。本次整理保留原代码，未修改此行为。
