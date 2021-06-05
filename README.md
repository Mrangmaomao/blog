# blog
个人记录博客
# install
  ### step1 安装依赖
    ```npm install ```
  ### step2 本地环境配置，--port端口号
    ```hexo serve```
# deploy
  ### 清除文件
  ```hexo clean```
  ### 打包
  ```hexo -g```
  ### 提交到git仓库
  ```hexo -d```
# git 配置仓库 
  修改文件 _config.yml
  ```deploy:
  type: git
  repo: https://github.com/Mrangmaomao/coiner.github.io
  branch: master
  message: 'test'```
  
