## refer:
https://github.com/xPixv/willesPlay.js-Video-Dem

#教程
https://blog.csdn.net/carry_hjr/article/details/102784989
需求是远方的女友和我能够同时播放、暂停、拖动进度条视频
必备环境: 一个国内的具有公网ip的云服务器

下载代码
在服务器上

git clone https://github.com/CarryHJR/coplayer.git

安装依赖
npm install --save express@4.15.2  --registry=https://registry.npm.taobao.org
npm install --save socket.io --registry=https://registry.npm.taobao.org

启动
node index.js

让女票访问ip:3000 然后自己也访问ip:3000，就可以一起看视频啦
