# websocket-chatRoom
基于websocket的聊天室

## 运行步骤
使用node ./app.js即可运行本地服务器
后在浏览器输入localhost:3000即可访问首页网站

## 特别注意：
js/index.js的地址写你对应的服务器地址;<br>
var socket = io('http://服务器地址:3000');<br>
index.html下边script里socket.io也得填上你对应的服务器地址!<br>
<script标签 src="http://服务器地址:3000/socket.io/socket.io.js"></script标签><br>
注意这里的地址localhost写对应你服务器的地址，因为访问的是你服务器的nodejs服务器!!!!!<br>
如果是本地服务器只需要填写localhost即可.
