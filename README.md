<!--
 * @version: v0.0.1
 * @Author: hailong.chen
 * @Date: 2020-06-04 21:53:40
 * @LastEditors: hailong.chen
 * @LastEditTime: 2020-06-05 00:05:50
 * @Descripttion: 
--> 
# git-flow
this is a git-flow
- 在github建立项目仓库，拉取项目
- 项目根目录 npm init -y
- npm i -D husky
- cnpm i -D @commitlint/cli @commitlint/config-conventional
- 配置commitlint.config.js
- 参考 https://blog.csdn.net/wei371522/article/details/84070803
- brew install git
- npx standard-version --first-release
```
✔ created CHANGELOG.md
✔ outputting changes to CHANGELOG.md
✔ committing CHANGELOG.md
✔ tagging release v0.0.1
ℹ Run `git push --follow-tags origin master` to publish
```
- changelog.md 生成html别用户预览
- .git /hooks/ 文件在cnpm i -D husky 时未补全， 需要运行 cnpm rebuild；参考：https://developer.aliyun.com/mirror/npm/package/husky
- 还是有点问题
- husky 最新版本提示 ```Cannot find module 'babel-polyfill'```