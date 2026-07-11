# 云端耀斑挡泥板

本项目修改自 https://gitee.com/ling-xukun/cloudflare-mudguard

## 介绍

云端耀斑挡泥板是一个基于 Web 的 Cloudflare 资源管理控制台，支持管理 Cloudflare Workers、DNS 记录等云服务资源。

## 功能特性

- **用户认证** - 安全的登录功能
- **Workers 管理** - 查看和管理 Cloudflare Workers
- **DNS 解析管理** - 管理域名 DNS 记录（支持 A、CNAME、MX、TXT 等记录类型）
- **仪表盘** - 查看资源概览信息

## 技术栈

- 前端：HTML5 + JavaScript
- 样式：Tailwind CSS
- API：Cloudflare API

## 使用说明

### 前提条件

- Cloudflare 账户
- 已配置 Cloudflare API Token 或 API Key

### 部署

1. 将项目部署到 Web 服务器
2. 配置 Cloudflare API 凭证
3. 访问控制台登录页面

### 配置

在控制台中添加您的 Cloudflare 邮箱和 API Key 即可连接 Cloudflare 账户。

## 参与贡献

1. Fork 本仓库
2. 新建特性分支 (`git checkout -b feat/xxx`)
3. 提交更改
4. 创建 Pull Request

## 许可证

GNU General Public License v3.0

---

了解更多 Cloudflare 服务，请访问：[cloudflare.com](https://www.cloudflare.com)
