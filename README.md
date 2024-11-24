# Alice 大善人 DNS 多媒体一键分流脚本

**支持操作系统**: Debian & Ubuntu

## 项目简介

该脚本旨在帮助用户通过 **Alice DNS** 实现快速的 DNS 分流与全局 DNS 替换。只需简单的几个步骤，即可轻松配置与解锁 Alice DNS。适用于 VPS 用户，支持一键配置，无需复杂设置。

## 使用指南

### 步骤 1: 注册 Alice 账号
1. 访问 [Alice DNS 官网](https://app.alice.ws) 进行注册。
2. 在注册后，将您的 VPS IP 地址添加至 Alice 白名单。
   > **注意**：此过程可能需要 3-5 分钟生效。

### 步骤 2: 运行一键分流脚本
1. 下载并运行以下脚本：
   ```bash
   wget https://raw.githubusercontent.com/Jimmyzxk/DNS-Alice-Unlock/refs/heads/main/dns-unlock.sh && bash dns-unlock.sh


---

### 解锁方式 1-1：DNS 分流模式
1. 在脚本菜单中选择 `1`。
2. 脚本将自动安装并配置 `dnsmasq`，实现多媒体流量的智能分流。
   - **适用场景**：优化流媒体（如 Netflix、Disney等）访问体验，确保内容加载更快，解锁区域内容。
  
### 选择分流区域（SG / HK）
1. 在脚本菜单中选择 `3`，进入分流区域选择界面。
2. 脚本支持自助选择 **SG（新加坡）** 或 **HK（香港）** 区域进行分流优化。
   - **SG（新加坡）**：适用于连接东南亚地区的用户，提供更优的路由和速度。
   - **HK（香港）**：适用于连接香港及周边地区的用户，提供稳定且快速的网络连接。
   - 选择完毕后，脚本将根据选择的区域配置合适的分流策略。

---

### 解锁方式 1-2：DNS 分流模式
1. 在脚本菜单中选择 `12`。
2. 脚本将自动安装并配置 `samrtdns`，实现多媒体流量的智能分流。
   - **适用场景**：优化流媒体（如 Netflix、Disney等）访问体验，确保内容加载更快，解锁区域内容。


### 解锁方式 2：全局 DNS 替换模式
1. 在脚本菜单中选择 `10`。
2. 系统 DNS 将被替换为 Alice DNS，全局启用。
   - **适用场景**：需要整体优化网络解析速度，提升所有已解锁自媒体请求。

---


