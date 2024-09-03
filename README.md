## 启动方式
- node环境v16
- 全局安装http-server
``npm install -g http-server``
- 当前目录执行
``http-server --cors -p 8002``
- 打开localhost:8002 即可;
注意不能打开本机ip+端口访问,必须要用localhost打开访问。因为用到了
  showOpenFilePicker API。