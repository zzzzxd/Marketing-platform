# 实时智能营销推送系统

## 系统概述

​	整个系统主要做一件事情，解决规则以及运算逻辑的硬编码问题，实现系统动态化。具体表现为 当发布配置规则时，可动态的生成运算逻辑 并进行计算，筛选出符合条件的用户进行实时推送，进行个性化引导与挽留。

​	比如 用户在关键转换点附近表现出退出或放弃的迹象，可以立即触达短信或发送相关消息，提供个性化的挽留措施。这样的即时干预可以重新吸引用户的注意力，对于符合某些业务规则的高价值用户可以提供额外的激励或优惠，以促使用户继续转换或完成购买。

​	再比如 对某类画像人群，如果用户发生过A行为n次，并完成了 (X Y Z)行为序列m次，即可判定高潜力用户，实时的进行触达，促成转化。

本项目为实时营销系统的前端演示模块，方便进行功能展示。

前端模块主要开发技术：

- react框架
- ant-design UI组件
- ant-design-pro 脚手架

## 前端模块环境准备

### 添加额外依赖库
```bash
yarn add axios
yarn add nanoid
```

### 安装 `node_modules`:

```bash
npm install
```

## 前端模块编译启动脚本

命令的配置写在文件`package.json`中. 可以根据需求在该文件中添加自定义命令脚本:

### 启动项目

```bash
npm start
```


### 编译项目

```bash
npm run build
```

### 代码风格check

```bash
npm run lint
```

如下命令可自动fix代码缺陷:

```bash
npm run lint:fix
```

### 运行测试代码

```bash
npm test
```

### 功能演示

<img src="https://www.z4a.net/images/2024/01/11/1.jpg" alt="image-20240110225553742" style="zoom:80%;" />

<img src="https://www.z4a.net/images/2024/01/11/2d3d6bba1f573f870.jpg" alt="image-20240110225637006" style="zoom:80%;" />

<img src="https://www.z4a.net/images/2024/01/11/3493f5c0af4d747f1.png" alt="image-20240110225624480" style="zoom:80%;" />
