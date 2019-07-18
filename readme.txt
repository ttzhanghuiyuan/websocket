#测试步骤
1、在cmd界面运行 php websocket_test.php 启动websocket监听
2、firefox index.html 建立服务连接，启动websocket接收
3、在浏览器直接向9501端口发送数据　　http://127.0.0.1:9501/admin_notify/send_message?message=10000
4、index.html页面弹出message值

#总结
本测试只测试了，服务器向客户端通讯，websocket可以完成全双工双向通讯！有意思～
