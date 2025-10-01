<br>
<div align="center">
    <img src="docs/爱特logo.svg" width=100/>
</div>
<div align="center">
    <h1>OUC Reminder</h1>
</div>
<br>
<div align="center">
    <img src="docs/Organization-ITstudio-shield.svg"/>
    <img src="https://img.shields.io/badge/Language-C++17-blue">
    <img src="https://img.shields.io/badge/Package-CMake-red">
</div>
<br>

**OUC Reminder** 是一个校园生活助手项目，旨在通过模拟登录校园卡与校园信息系统，集中追踪和管理学生的各类校园数据。

项目支持在账户余额不足、电费/网费即将用尽时自动发出提醒，并计划逐步扩展为一个统一的信息入口，帮助学生更高效地管理日常学习与生活。

## ✨ 功能特点

- **校园卡监控**
    - 自动登录校园卡系统
    - 实时追踪账户余额、电费、网费
    - 阈值提醒（不足时发送通知）
- **计划扩展功能**
    - 查看课程表
    - 获取校内通知与公告
    - 班车时刻表查询
    - 预约与查看空闲教室
    - 更多校园相关功能模块

## 🚀 快速开始

### 环境要求

- C++ 17 或更高版本
- CMake $\geq$ 3.15
- （可选）Docker 用于统一开发环境

### 📂 仓库结构

```bash
ouc_server
├── include/ # 公共头文件
├── src/ # 源代码
├── examples/ # 示例程序
├── tests/ # 单元测试 
├── docs/ # 文档 
├── CMakeLists.txt 
└── README.md
```

## 🗓️ 开发路线图

- [ ] 搭建后端服务器
- [ ] 对接数据库
- [ ] 与校园卡系统对接
- [ ] 绘制小程序 UI 页面

## 📌 注意事项

- 本项目仅用于学习与校园社团内部交流，不涉及对外商用。
- 模拟登录涉及账号隐私，请在使用前确保安全性。

## 📜 许可证

本项目采用 [MIT License](/LICENSE) 开源。