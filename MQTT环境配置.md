# 配置云服务器mqtt环境-ubuntu

步骤：
1.安装Mosquitto  -----------------.参考网址：[网站](https://randomnerdtutorials.com/how-to-install-mosquitto-broker-on-raspberry-pi/)

2.安装 Node-RED 软件 ---------参考网址：[网站](https://randomnerdtutorials.com/access-node-red-dashboard-anywhere-digital-ocean/)

3.配置Node-red可视化界面 ----参考网址：[网站](https://randomnerdtutorials.com/getting-started-node-red-dashboard/)

## 安装MQTT软件-Mosquitto


```c
1. sudo apt update && sudo apt upgrade   //按Y同意
2. sudo apt install -y mosquitto mosquitto-clients
3. sudo systemctl enable mosquitto.service //自启动
4. mosquitto -v    //测试安装
5.