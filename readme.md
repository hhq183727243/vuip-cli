# VUIP-CLI
用于创建vuip项目基础配置的脚手架

## 使用说明
安装vuip-cli
``` bash
npm install -g vuip-cli
```
安装完成后即可以使用vuip命令

## 检测安装是否成功
``` bash
vuip -V
```
输入版本号说明安装成功

## 通过vuip迁出工程模板
``` bash
vuip init
```
选择工程模板，目前只有一个base模板，输入
``` bash
base
```
输入你的工程名
``` bash
<project-name>
```
等待迁出

## 依赖包下载
推荐使用yarn来管理依赖包
``` bash
yarn
```
## 项目启动
``` bash
yarn start
```

## 项目打包
``` bash
yarn build
```