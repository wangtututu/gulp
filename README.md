如何使用 gulp
===

### 全局安装 gulp：
```Bash
$ npm install --global gulp
```
### 作为项目的开发依赖（devDependencies）安装：
```Bash
$ npm install --save-dev gulp
```
### 在项目根目录下创建一个名为 gulpfile.js 的文件：
```javascript
var gulp = require('gulp');
gulp.task('default', function() {
  // 将你的默认的任务代码放在这
});
```
### 运行 gulp：
```Bash
$ gulp
```
