# test
预约系统服务器
创建一个简易的预约系统服务器---以下功能：
1.检索当前主机的所有网卡IP。
2.绑定选择的IP地址后，有新的客户端连接就会出现在第一个表格中。
3.选择第一个表格的选项，可以对这个客户端进行操作，比如断开连接（支持多选）。
4.断开服务器。
5.服务器接收到登录请求就会检索accountinfo 、userinfo、applyinfo数据库（sqlite3）下的所有用户，给客户端返回一个登录信息。
6.客户端发送刷新请求，重新查询第五步操作。
7.客户端发送预约申请请求，服务器会将接收的申请信息插入到applyinfo数据库中。
