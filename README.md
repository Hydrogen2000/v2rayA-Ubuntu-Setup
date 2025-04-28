# v2rayA-Ubuntu-Setup
Ubuntu系统使用v2rayA代理配置

## 一、软件安装

### 1. 添加公钥

```bash
sudo mkdir -p /etc/apt/keyrings
wget -qO - https://apt.v2raya.org/key/public-key.asc | sudo tee /etc/apt/keyrings/v2raya.asc
```

### 2. 添加软件源并下载软件

```bash
echo "deb [signed-by=/etc/apt/keyrings/v2raya.asc] https://apt.v2raya.org/ v2raya main" | sudo tee /etc/apt/sources.list.d/v2raya.list
sudo apt update
sudo apt install v2raya xray
```

## 二、软件使用

### 1. 启动v2rayA

```bash
sudo systemctl start v2raya.service
```

### 2. 打开v2rayA Web Panel软件

