# gitbook 构建方法

**安装 Node.js 和 npm**

[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

**安装 GitBook 命令行工具**

```bash
npm install gitbook-cli -g
```

**下载项目**

```bash
git clone xxx_project
```

**构建 GitBook**

***初始化项目(可选)***

```bash
gitbook init xxx_project
```

进入项目：

```bash
cd xxx_project
```

初始化GitBook属性定义

```bash
vim book.json
```

进入项目，执行构建：

```bash
rm -rf docs && gitbook build . docs
```