# mac升级node到指定版本

## 1.清楚npm缓存
```
npm cache clean -f
```

## 2.n模块是专门用来管理node.js的版本，安装n模块
```
npm install -g n
```

## 3.更新升级node版本
```
a) n stable // 把当前系统的node更新到最新的稳定版本
b) n lts // 安装到最新长期支持的版本
c) n latest // 更新到最新版本
d) 16.15.0 // 指定安装版本
```

4.查看升级后的node版本
```
node -v
```
