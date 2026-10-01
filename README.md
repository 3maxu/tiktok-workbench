# TikTok 运营工作台

实时数据同步与多端协作的运营驾驶舱。

## 用途

支持 TikTok 账号运营、财务流水、WS 客户跟进、收入记录、每日运营日报、考勤记录的数据管理与实时同步。

## 技术栈

- 前端：纯静态 HTML + CSS + ECharts + localStorage
- 认证：Clerk（JWT 登录墙）
- 后端：Google Apps Script（REST API + Google Sheets）
- 部署：GitHub Pages
- 数据同步：15 秒可见轮询 + 本地重试队列

## 使用入口

https://3maxu.github.io/tiktok-workbench/

## 更新方式

直接 push 到本仓库 main 分支，GitHub Pages 自动重新发布。
