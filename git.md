## 在git上发布静态网站
- 必须当前项目下简历一个gh-pages的分支
- 将我们需要发布的内容推到gh-pages这个分支上
- 推送到远程仓库上即可
- github会给你一个网址

- git checkout -b gh-pages
- touch index.html 
- giit add .
- git commit -m 'add index.html'
- git push origin gh-pages
- 在settings中可查找到网址 + 文件名即可（默认会展示index.html）