
### liaohch3.github.io
本项目是 liaohch3 的个人博客，基于 Hugo 搭建

### 如何部署本项目
1. 执行 `hugo new posts/xxx.md` 新建博客文章，编写博客内容


2. 编写完成博客后，`hugo -d`在本地预览博客，确认是否符合预期
   1. 修改 `draft: false` 使博客状态被设置为正式博客
   

3. `hugo -d docs` 生成静态文件


3. git add . && git commit -m "xxx" && git push 推送到 GitHub


4. 稍等片刻，完成部署后，点击 https://liaohch3.github.io 确认部署情况
