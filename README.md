# 测试本地Git上传代码到Github

## 测试1.0

​测试Git Bash能否上传代码
<br><font color=red>测试通过</font>

### 测试1.1

​ 初始化docsify目录，通过Git Bash上传
<br><font color=red>测试通过</font>

### 测试1.2

​ 同时修改两份README.md文件，期望能够同时修改

​    <br><font color=red>测试通过</font>，与预期相符

## 测试 2.0

​ 测试 git GUI能否使用
<br>测试失败，无法使用pull，显示版本落后

## 测试3.0

​ 使用WebStorm提交，期望能够上传Github
<br>修改 index.html 文件下的 name，repo 参数
<br><font color=red>测试通过</font>

### 测试3.1

​ 修改README.md文件，调整版本号

### 测试3.2

​ 不使用 git add 从工作区添加到缓存区，直接commit