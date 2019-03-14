# npx

## 是什么

npx是npm5.2+增加的一个自带模块。

## 作用

依赖相关：查找项目中的可执行文件，找不到去$PATH中查找，还找不到安装临时依赖包

## 怎么用

````
npm i -D webpack
npx webpack -v
````
