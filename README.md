# AgentM

> 通过微信 iLink，随时随地用手机掌控电脑上的 Agent 与命令行。

## 项目介绍

AgentM 是一个「手机远程控制电脑」的项目，由两个产物组成：

| 产物 | 说明 |
| --- | --- |
| **PC 端程序** | 部署在电脑上，负责承载和管理各类 Agent、接收并执行来自手机的指令、回传执行结果 |
| **移动端 APP** | 安装在手机上，提供控制界面，可远程查看与操控电脑上的各个 Agent，或直接下发命令行指令 |

两端之间通过**微信 iLink** 进行通信，无需自建服务器/公网穿透，即可实现手机对电脑 Agent 与命令行的远程控制能力。

### 核心能力

- 📱 手机远程查看电脑上各个 Agent 的状态
- 🕹️ 手机远程启动 / 停止 / 控制 Agent
- ⌨️ 手机下发命令行指令到电脑执行，并回传输出结果
- 🔗 基于微信 iLink 的通信链路

## 功能特性

- [ ] 特性一
- [ ] 特性二
- [ ] 特性三

## 快速开始

### 环境要求

- 需要的运行环境及版本要求

### 安装

```bash
# 克隆项目
git clone https://github.com/your-username/AgentM.git
cd AgentM

# 安装依赖
```

### 使用

```bash
# 运行示例
```

## 项目结构

```
AgentM/
├── README.md
├── .gitignore
└── ...
```

## 参与贡献

1. Fork 本仓库
2. 新建 `feat/xxx` 分支
3. 提交代码 (`git commit -m "feat: add xxx"`)
4. 推送到分支 (`git push origin feat/xxx`)
5. 提交 Pull Request

## 许可证

本项目基于 [MIT](LICENSE) 许可证开源。
