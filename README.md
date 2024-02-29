# Github & Hexo Tutorial

## 一、搭建环境
1. Win10电脑
2. 安装Git
3. 安装nodejs
4. 安装hexo

## 二、本地建站

### 建站
```
cd <www> #必须是空目录
hexo init
npm install
```
### 生成
```
hexo generate
```

## 三、远程部署
Github创建SSH，在本机保存好。

设置 _config.yaml
```
    deploy:
      type: git
      repo: git@github.com:<username>/<username>.github.io.git
      branch: master
```

一键部署
```
hexo deploy
```

## 四、衍生阅读
- [hexo+Github部署教程（防踩坑）](https://blog.csdn.net/2202_75780138/article/details/132112279)
