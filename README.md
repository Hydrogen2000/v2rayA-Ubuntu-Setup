# v2rayN-Ubuntu-Setup
Ubuntu系统使用v2rayN代理配置

## 一、软件安装

### 1. 添加公钥

```bash
sudo mkdir -p /etc/apt/keyrings/
wget -qO - https://apt.v2raya.org/key/public-key.asc | sudo tee /etc/apt/keyrings/v2raya.asc
```
