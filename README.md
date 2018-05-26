# kalix-vue-frame
qiao-frame
## 建立开发环境
### install yarn
```
$ D:\java-develop\project\>npm i -g yarn
C:\Users\Administrator\AppData\Roaming\npm\yarnpkg -> C:\Users\Administrator\AppData\Roaming\npm\node_modules\yarn\bin\yarn.js
C:\Users\Administrator\AppData\Roaming\npm\yarn -> C:\Users\Administrator\AppData\Roaming\npm\node_modules\yarn\bin\yarn.js
+ yarn@1.6.0
added 1 package in 3.362s

$ yarn config set registry https://registry.npm.taobao.org
```
### git clone qiao-frame
```
$ git clone https://github.com/xingshidongman/qiao-frame
$ D:\java-develop\project\qiao-frame>yarn
```
### create link
```
$ D:\java-develop\project\qiao-frame>yarn link
yarn link v1.6.0
success Registered "qiao-frame".
info You can now run `yarn link "qiao-frame"` in the projects where you want to use this package and it will be used instead.
Done in 0.15s.
```
### git clone kalix-vue-frame
```
$ git clone https://github.com/xingshidongman/kalix-vue-frame
$ cd kalix-vue-frame
$ git checkout qiao
 Switched to a new branch 'qiao'
 Branch 'qiao' set up to track remote branch 'qiao' from 'origin'.
$ D:\java-develop\project\kalix-vue-frame>yarn
```
### use link
```
$ D:\java-develop\project\kalix-vue-frame>yarn link qiao-frame
yarn link v1.6.0
success Using linked package for "qiao-frame".
Done in 0.15s.
```
### run
```
$ D:\java-develop\project\kalix-vue-frame>yarn dev
```

## 运行文档环境
> command:
```
npm i docsify-cli -g

docsify serve ./docs

Serving D:\java-develop\project\kalix-vue-frame\docs now.
Listening at http://localhost:3000
```
